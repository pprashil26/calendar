# Life Calendar v1

Compact local-first continuous calendar.

## Run
Serve this folder from localhost or HTTPS (required for full PWA installation):

    python3 -m http.server 8080

Then open http://localhost:8080. Opening index.html directly will run the calendar, but service-worker installation requires localhost or HTTPS.

## Data
Events, categories, settings, and recovery snapshots are stored in IndexedDB. Use Export backup regularly. Import creates a recovery snapshot before replacing data. Up to five automatic recovery snapshots are retained.
