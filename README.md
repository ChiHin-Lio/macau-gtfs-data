# Macau GTFS Data

Experiment: Macau GTFS feed using ML (XGBoost) for realistic bus trip times.

## Structure

- `raw_logs/` — DSAT API scraper output (per-route CSVs with bus positions)
- `dsat-data/` — Official DSAT data (BUS_POLE.csv, ROUTE_NETWORK.csv)
- `bus-stops.json` — All Macau bus stops with WGS84 coords
- `route-metadata.json` — Route definitions (name, origin, destination)
- `operators.json` — Bus operator mappings
- `route-stops.json` — Stop sequences for each route
