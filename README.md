# FutureTargets Lite — Free MT5 Indicator

  Hosoda Price & Time Projections for MetaTrader 5. Drag three anchors (A, B, C) on any swing → indicator draws projected price targets and time cycles based on Goichi Hosoda's
  full Ichimoku methodology.

  ## Lite features (free)

  **Price projections** from A-B-C anchors:
  - **V** = B + (B − C)
  - **N** = C + (B − A)
  - **E** = B + (B − A)
  - **NT** = C + (C − A)

  Drag any anchor → all targets recompute live.

  ## Pro features (Patreon Neural · per-account licensed)

  - **Extended price targets** — 2E / 2V / 3E / 3V / S / P
  - **Magnetic snap** — anchors auto-lock to bar high/low on release
  - **Kihon Suchi time cycles** — `{9, 17, 26, 33, 42, 51, 65, 76}` bars from C
  - **Taito Suchi** — AB / AC / BC wave-equality time projections
  - **Time-toggle button** — on-chart `TIME` overlay
  
  **Get Pro:** https://www.patreon.com/AlphaTRADER_Neural/join
  
  ## Install

  1. MT5 → File → Open Data Folder → `MQL5/Indicators/`
  2. Drop `FutureTargets.ex5` into that folder
  3. Restart MT5 (or right-click Navigator → Refresh)
  4. Drag `FutureTargets` from Navigator onto chart
  5. Anchors A, B, C appear — drag to your swing high/low/retrace points
  
  ## Licensing

  Lite version: works on any account (demo or live), no whitelist.  
  Pro version: per-account licensed via MT5 login number whitelist.
