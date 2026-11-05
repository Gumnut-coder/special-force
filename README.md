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
- Left Ctrl: crouch → lie down → stand (C and Z work too). Tap Ctrl rather than holding it while you walk, because Ctrl+W closes the browser tab.
- Space: jump.
- Ladders: walk into a ladder on a building to climb onto the roof. The office, warehouse, sports hall and shopping centre all have a ladder up to their roofs too.
- Tunnels: take the ⬇ TUNNEL stairs to go underground. They're short (about 30–40 m). Bridges have stairs at both ends, and you can walk underneath them.
- Buildings: walk into the office, warehouse, shopping centre (5 levels), car park and sports hall. Use the stairs, escalators and car-park ramps to go up. The HUD shows which level you're on.
- Glass: shoot it, or blow it up with a grenade, to smash windows, shop fronts and atrium railings. Robots can see you through glass, and any shot that hits a pane smashes it, so glass is not real cover.
- Mounted guns: hold E at a minigun or rocket turret to hop on, and press E again to get off. They overheat if you fire too long.
- G: grenade. V: smoke bomb. H: medkit.
- E (hold): free hostages, plant or defuse bombs, revive squad.
- Squad orders: 3 follow, 4 hold, 5 go where I aim, 6 hunt, T choose who gets the order. You can also click a squad member's name.
- Tab: scoreboard (multiplayer).
- Esc: pause.

**iPad / touch**
- Left side: drag to move. Right side: drag to look.
- Buttons for FIRE, AIM, reload, swap weapon, grenade (💣), smoke bomb (💨), medkit and USE.
- ⤒ jumps. 🧎 crouches, press again to lie down, and again to stand.
- Push forward into a ladder to climb onto a roof.
- Hold USE at a mounted gun to hop on, and tap USE to get off.
- 👥 opens squad orders. Tapping a squad member's name changes their order.

## Weapons and crew

- **Customise:** tap 🎨 (or a weapon's picture) to open Inspect, then pick a **sight** (Iron, Red Dot, Holo, 3x ACOG, 6x Scope; each zooms differently when you aim and shows its own reticle), a **skin** (13 camos up to Gold and Diamond) and a **sticker** (emoji, or your own text up to 8 letters). Buy each once, then use it on any gun.
- **Armory:** every weapon card shows its rarity (Common, Rare, Epic, Legendary), damage, rounds per minute, magazine, range and special tags. Tap a weapon's picture to **Inspect** it in a rotating 3D view.
- **Main weapons (24):** submachine guns, assault rifles, shotguns, sniper and marksman rifles, machine guns (including the Buzzsaw Minigun), energy weapons (Arc Plasma, Photon Laser, Volt Shock Rifle that freezes robots, Railgun X) and launchers (Boomer Grenade Launcher, Thumper Rocket Launcher). New ones unlock as you rank up.
- **Sidearms (8):** your second weapon can be any of 8 sidearms: P9 Pistol, Raptor .45, Whisper SD9 (suppressed), Hornet Machine Pistol, Bulldog .44 revolver, Shorty Sawn-off, Hand Cannon .50 and Ion Blaster. Buy them in the Armory and press **Equip as sidearm**. Switch weapons with Q, 1 or 2.
- **Smoke bombs:** press V (or 💨) to throw one. The cloud lasts 14 seconds and robots can't see or shoot through it. Buy more in the Armory (carry up to 4).
- **Walls stop bullets:** no weapon, robot or squad mate can shoot through walls. Glass is the exception, and it shatters.
- **Crew:** there are 17 specialists to hire, including Mule (Supply), Frost (Cryo), Patch (Field Medic), Falcon (Marksman), Jinx (Decoy hologram) and Warden (Commander). Hire as many as you like. After pressing **Deploy**, you choose who comes on that mission, up to 4 (you get 1 slot at the start, 2 at Rank 4, 3 at Rank 8 and 4 at Rank 11).

## Missions

There are 44 missions.

- **1–12:** open city maps.
- **13–24:** in and around the buildings (office, warehouse, 5-level shopping centre, car park, sports hall).
- **37–44: new maps.**
  - **Snow:** Frozen Outpost, Avalanche Rescue. Falling snow, snowy pines and cabins.
  - **Forest:** Into the Woods, Forest Ambush. Thick trees, fallen logs for cover.
  - **Mountain:** Mountain Pass, Eagle's Nest. Boulders you can jump onto for high ground.
  - **Space:** Moon Base Alpha, Robot Mothership. Low gravity, so you jump much higher and grenades fly further.
- **25–36: inside one building.** These include:
  - **Floor by floor** missions (Office Lockdown, Car Park Climb, Mall Sweep, Tower Siege, Mega Mall Finale): clear every level, bottom to top, then reach the green extraction zone on the top level. The objective tells you which level still has robots.
  - **Indoor sweeps** (Warehouse Sweep): every robot is hiding inside.
  - **Upper-floor bombs:** Food Court Bomb (defuse on level 3 of the mall) and Server Room (plant on the office's top floor).
  - **Other indoor missions:** Penthouse (commanders on every floor), Court Defense (waves in the sports hall), Late Night Shopping (rescue in the mall) and Hall of Doom (a Titan boss on the court).

## Multiplayer

1. One player opens **Multiplayer** and picks **🔒 Host private game** or **🌐 Host public game**, and gets a 5-letter room code.
2. Everyone else opens the same GitHub Pages link on their own PC or iPad and goes to **Multiplayer**:
   - **Private room:** type the code and press **Join**.
   - **Public room:** it appears under **🌐 Public games** within about 10 seconds. The list refreshes itself; **↻ Refresh** checks right away.
3. The host picks the team size (**4 v 4** up to **20 v 20**), mode, map (Daytime, Industrial, Desert, Night, Snow, Forest, Mountain or Space) and bots, then presses **START**. Bots fill every empty spot.

**Bots** spread out across the map. Each takes its own lane (left, centre or right) and its own style (rusher, flanker, holder or roamer), and they keep their distance from each other. In Capture the Flag, attackers push for the flag and escort whoever is carrying it.

**Big rooms:** everyone connects through the host's device. 20 v 20 with bots runs well anywhere. For lots of *real* players, the host should be a PC on good home internet; an iPad host may lag.

**If a public game doesn't show up:**
- Everyone needs the same game version. It's shown next to the SPECIAL FORCE title (for example v13). After you update GitHub, reload the page on every device (on iPad, pull down to refresh). Rooms from a different version show an "Update" button instead of "Join".
- The host should keep the game on screen. If an iPad goes to sleep or switches apps, the room drops off the list until the game is opened again.
- Online play only works from the GitHub Pages copy, not the claude.ai preview.

Online play needs an internet connection. Players connect to each other directly, using the free PeerJS service to find each other. Some school or work networks block this, but home Wi-Fi is usually fine.

**Practice vs Bots** works offline.

## Saving

Progress (rank, cash, gear, squad) is saved in each browser. The PC and the iPad keep separate progress.
