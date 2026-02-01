# Options Trading Book Simulator

## Pitch
Simulation d’un book d’options vanilla avec delta-hedging discret,
décomposition complète du PnL (Δ, Γ, Vega, Θ),
et analyse de l’impact des régimes de volatilité et de la fréquence de hedge.

## Data (100% réelles)
- Sous-jacent : SPY (EOD)
- Options : OPRA EOD aggregates (Polygon)
- Taux sans risque : SOFR (FRED)
- Volatilité de marché : VIX (Cboe / FRED)

## Méthodologie
- Pricing Black–Scholes
- Reconstruction IV & greeks
- Delta hedge discret avec coûts de transaction
- PnL explain vs residual

## Résultats clés
- Performance vs fréquence de hedge
- Impact IV ≠ RV
- Stress regimes (VIX)

## Limitations
- Options equity traitées comme européennes
- Smile ignoré → impact sur residual PnL
