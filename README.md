# stock-price-edge-data

Public read-only published outputs of the [`stock-price-edge`](https://github.com/alexkozzy/stock-price-edge)
scanner. Served via GitHub Pages and consumed by
[`stock-price-edge-dashboard`](https://stock-price-edge-dashboard.vercel.app/).

## Files

- `data/snapshot_latest.json` — most recent scanner snapshot
- `data/snapshot_<UTC-timestamp>.json` — timestamped archive of each run

## Schema

See `lib/types.ts` in the dashboard repo (`StockEdgeSnapshotSchema`).
