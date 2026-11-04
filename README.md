# Special Force

A first-person shooter you play in the browser. Lead an elite squad against a robot uprising, complete missions, earn cash, rank up, buy new gear and hire specialists. It also has a team multiplayer mode: Red vs Blue, up to 8 players.

Everything is in one file, `index.html`, so there's nothing to install.

## Put it on GitHub Pages

1. Create a new repository on GitHub, for example `special-force`. Make it **Public**.
2. Click **Add file → Upload files** and upload `index.html` (and this `README.md`). Click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, then choose the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two the game is live at `https://<your-username>.github.io/special-force/`.

To update the game later, upload the new `index.html` over the old one.

## Controls

**PC**
- WASD: move. Shift: sprint.
- Mouse: look. Left-click: shoot. Right-click: aim.
- R: reload. Q, 1, 2: switch weapon.
- G: grenade. H: medkit.
- E (hold): free hostages, plant or defuse bombs, revive squad.
- Squad orders: Z follow, X hold, C go where I aim, V hunt, T choose who gets the order. You can also click a squad member's name.
- Tab: scoreboard (multiplayer).
- Esc: pause.

**iPad / touch**
- Left side: drag to move. Right side: drag to look.
- Buttons for FIRE, AIM, reload, swap weapon, grenade, medkit and USE.
- 👥 opens squad orders. Tapping a squad member's name changes their order.

## Multiplayer

1. One player opens **Multiplayer → Host a game** and gets a 5-letter room code.
2. Everyone else opens the same GitHub Pages link on their own PC or iPad, goes to **Multiplayer**, types the code and presses **Join**.
3. The host picks the mode (Team Deathmatch, Capture the Flag, Bomb Defuse or King of the Hill), the map and the bots, then presses **START**.

Online play needs an internet connection. Players connect to each other directly, using the free PeerJS service to find each other. Some school or work networks block this, but home Wi-Fi is usually fine.

**Practice vs Bots** works offline.

## Saving

Progress (rank, cash, gear, squad) is saved in each browser. The PC and the iPad keep separate progress.
