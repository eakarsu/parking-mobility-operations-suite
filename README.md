# Parking Mobility Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIParkingMobilityOperationsAssistant`
- `AIParkingMobilityOperationsOperations`
- `AIParkingMobilityOperationsAnalytics`
- `AIParkingMobilityOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/parking-mobility-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:4990`

Seeded users:
- `admin@parking-mobility-operations.local / admin123`
- `manager@parking-mobility-operations.local / manager123`
- `analyst@parking-mobility-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/parking-mobility-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:4990 npm run smoke
```
