# Aptum Dashboard Final Patched 4.5

Fixes:
- Removed duplicate Current in metrics card.
- Removed useless Motor metric from metrics.
- Metrics now show Voltage, Odometer, Current, Power, Battery, Pack.
- Redline no longer appears fully at start; red only appears after high RPM.
- Replaced motor temperature icon with custom electric motor drawing.
- Demo throttle/brake now smooths speed and does not force lean full left/right.
- Brake light turns on when demo brake > 15%.
- Uses uploaded MP3s:
  - startup.mp3
  - scanning.mp3
  - connected.mp3
- Scanning sound plays when scan starts.
- Connected sound plays when BLE connects.
- Developer options include Live Activity status check and force update.
- Live Activity note: iOS does not show a normal permission popup for this; it must be enabled in Settings and requires the widget extension embedded.
- Project target forced to iOS 16.2+ and Swift 6 mode.
- Widget dependency embedded when widget target is present.
- Robust IPA workflow.
