# FreshGuard

A dependency-free, responsive web prototype for the SIH food freshness and safety concept. All sensor values are simulated and clearly identified as prototype estimates.

## Run locally

Open `index.html` in a modern browser. For the most reliable browser storage behavior, serve this folder over localhost:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Test history and preferences are stored in the browser's local storage. The New Test screen includes deterministic Fresh, Caution, and Unsafe demo scenarios.
