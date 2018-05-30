# Volatility

Must provide a way to compute implied volatility surfaces from market quotes.
Must provide a way to compute an implied volatility surface from a listed price surface.
Must provide a way to compute a local volatility surface from an implied volatility surface.
A volatility surface must satisfy non arbitrage conditions:
No calendar spread arbitrage (total variance is increasing[v2T /'])
No butterfly arbitrage for all smiles.
