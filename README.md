# Reeflight Aquarium

An original aquarium game that runs in your browser. Feed your fish, collect the pearls they produce, and spend them to grow your aquarium and restore five corals.

## Run locally on Windows

Clone the repo and open PowerShell in it. With Python 3 installed, run:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser. Keep PowerShell open while you play. Press Ctrl+C in PowerShell to stop the server. The game has no package dependencies and works offline after cloning.

## Controls and saves

- Click the tank to drop food. Click glowing pearls to collect them. With the tank focused, use Space to feed and Enter to collect.
- Click **Buy fish** or **Plant coral** when you have enough pearls.
- The game saves every five seconds while playing, after purchases and pearl collection, and when you leave the page. **Save now** saves immediately.
- Return to the same address and browser profile to continue. Clearing the site's data deletes its save. The game pauses while its tab is hidden or closed.
