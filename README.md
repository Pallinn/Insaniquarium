# Reeflight Aquarium

An original aquarium game that runs in your browser. Feed fish, collect the coins they drop, and defend your tank from timed alien raids.

## Run locally on Windows

Clone the repo and open PowerShell in it. With Python 3 installed, run:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser. Keep PowerShell open while you play. Press Ctrl+C in PowerShell to stop the server. The game has no package dependencies and works offline after cloning.

## Controls and saves

- Choose **Full screen** in the top bar. Press Esc or use **Exit full screen** to return.
- Click the water to drop food. Every successful drop costs cash. Collect silver and gold coins before they disappear, then spend cash on fish or stronger food. Food changes shape and color with each upgrade.
- The first alien arrives after 48 seconds of active play. Click it or use **Fire blaster**. Later raids become more frequent and aliens can withstand more shots.
- With the tank focused, use Space to feed, Enter to collect a coin, and G to shoot. If all fish are lost, choose **Start a new tank**.
- The game saves every five seconds and after actions that change cash, equipment, or a raid. **Save** saves immediately. Return to the same browser profile and address to continue.
- Earlier browser saves retain their fish, cash and feed upgrade. Uncollected pearls are converted to coins. The new raid timer starts when the save is migrated. The game pauses while its tab is hidden or closed.
