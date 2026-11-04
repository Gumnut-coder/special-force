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

- **Main weapons (24):** submachine guns, assault rifles, shotguns, sniper and marksman rifles, machine guns (including the Buzzsaw Minigun), energy weapons (Arc Plasma, Photon Laser, Volt Shock Rifle that freezes robots, Railgun X) and launchers (Boomer Grenade Launcher, Thumper Rocket Launcher). New ones unlock as you rank up.
- **Sidearms (8):** your second weapon can be any of 8 sidearms: P9 Pistol, Raptor .45, Whisper SD9 (suppressed), Hornet Machine Pistol, Bulldog .44 revolver, Shorty Sawn-off, Hand Cannon .50 and Ion Blaster. Buy them in the Armory and press **Equip as sidearm**. Switch weapons with Q, 1 or 2.
- **Smoke bombs:** press V (or 💨) to throw one. The cloud lasts 14 seconds and robots can't see or shoot through it. Buy more in the Armory (carry up to 4).
- **Walls stop bullets:** no weapon, robot or squad mate can shoot through walls. Glass is the exception, and it shatters.
- **Crew:** there are 17 specialists to hire, including Mule (Supply), Frost (Cryo), Patch (Field Medic), Falcon (Marksman), Jinx (Decoy hologram) and Warden (Commander). Hire as many as you like. After pressing **Deploy**, you choose who comes on that mission, up to 4 (you get 1 slot at the start, 2 at Rank 4, 3 at Rank 8 and 4 at Rank 11).

## Missions

There are 24 missions. Missions 13–24 take place in and around the buildings: Mall Rescue, Warehouse Raid, Corner Office, Car Park Siege, Game Over (sports hall), Power Cut, Level Up, Underground, Stadium Rescue, Night Shift, Shopping Spree and Final Showdown. Robots guard the upper floors too, so clear each level as you go.

## Multiplayer

1. One player opens **Multiplayer** and picks **🔒 Host private game** or **🌐 Host public game**, and gets a 5-letter room code.
2. Everyone else opens the same GitHub Pages link on their own PC or iPad and goes to **Multiplayer**:
   - **Private room:** type the code and press **Join**. Only people with the code can get in.
   - **Public room:** it appears under **🌐 Public games**. Press **Join** next to it (press **↻ Refresh** to update the list).
3. The host picks the mode (Team Deathmatch, Capture the Flag, Bomb Defuse or King of the Hill), the map and the bots, then presses **START**. The host can switch the room between Private and Public in the lobby at any time.

Many rooms can run at the same time, each with up to 8 players. Up to 20 public rooms show in the list at once; private rooms have no limit.

Online play needs an internet connection. Players connect to each other directly, using the free PeerJS service to find each other. Some school or work networks block this, but home Wi-Fi is usually fine.

**Practice vs Bots** works offline.

## Saving

Progress (rank, cash, gear, squad) is saved in each browser. The PC and the iPad keep separate progress.
