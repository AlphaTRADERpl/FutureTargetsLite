# FutureTargets Lite — Free MT5 Indicator

  Hosoda Price Projections for MetaTrader 5. Drag three anchor points (A, B, C) on any A-B-C swing — indicator draws four projected price targets based on Goichi Hosoda's Ichimoku
  methodology.

  ## Features
  
  Price targets from A-B-C anchors:
  - **V** = B + (B − C)
  - **N** = C + (B − A)
  - **E** = B + (B − A)
  - **NT** = C + (C − A)

  Drag any anchor → targets recompute live.
  
  Works on any MT5 account (demo or live, no whitelist).

  ## Pro version

  Pro tier (per-account licensed) adds:
  - Extended targets: 2E / 2V / 3E / 3V / S / P
  - Magnetic snap to bar high/low when releasing anchors
  - Kihon Suchi time cycles {9, 17, 26, 33, 42, 51, 65, 76} from anchor C
  - Taito Suchi wave-equality time projections from AB / AC / BC durations
  - On-chart TIME toggle button

  License Pro: https://www.alphatrader.pl/tools/future-targets
  
  ## Install

  1. MT5 → File → Open Data Folder → `MQL5/Indicators/`
  2. Drop `FutureTargets.ex5` into that folder
  3. Restart MT5 (or right-click Navigator → Refresh)
  4. Drag `FutureTargets` from Navigator onto a chart
  5. A, B, C anchors appear — drag to your swing points
  
  ---
  Proprietary © SPIDER'S LAB OÜ
