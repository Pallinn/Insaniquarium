# Reeflight Aquarium

An original aquarium game that runs in your browser. Keep your fish alive, collect the pearls they produce, and spend them to restore five corals.

## Run locally on Windows

Clone the repo and open PowerShell in it. With Python 3 installed, run:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser. Keep PowerShell open while you play. Press Ctrl+C in PowerShell to stop the server. The game has no package dependencies and works offline after cloning.

## Controls and saves

- Click the tank to drop food. Feed fish when their hunger bars fall. Collect glowing pearls before they dissolve.
- Buy fish for more income, upgrade feed for stronger meals, or plant coral to make future pearls more valuable. Two corals unlock the purchase of a skimmer that periodically collects a sunken or fading pearl.
- The tank warns you before a low-oxygen current arrives. Use **Aerate water** as oxygen drops. With the tank focused, use Space to feed, Enter to collect a pearl, or A to aerate.
- Plant all five corals to unlock free swim. If the tank loses all its fish, use **Start a new round**.
- The game saves every five seconds while playing, after purchases and pearl collection, and when you leave the page. **Save now** saves immediately.
- Return to the same address and browser profile to continue. Saves from the first browser version load automatically. The game pauses while its tab is hidden or closed. Clearing the site's data deletes its save.
