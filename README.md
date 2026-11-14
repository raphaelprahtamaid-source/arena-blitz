# Arena Blitz

A small 3D arena shooter that runs in the browser, on phones and desktops.

**Play:** open the GitHub Pages link for this repo, type a callsign, and tap **Play online**. Everyone who uses the same match code is in the same game. **Practice vs bots** works offline.

Rules: a match is 5 rounds of 1 minute. The first kill in a round wins that round; most rounds won takes the match.

Controls:
- Phone (landscape works best): left thumb moves, right thumb aims, hold FIRE, tap HEAL for +50 health (12 s cooldown).
- Desktop: click to lock the mouse, WASD to move, Space to jump, click to shoot, R to reload, E to heal.

Online play is peer-to-peer (WebRTC via PeerJS's free public broker). The first player in a match relays for everyone; if they leave, another player takes over.
