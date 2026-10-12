# Salvo Brawl

A live 2–4 player tank brawler. The computer (or a TV plugged into it) shows the battle, and each player uses their phone as a controller by scanning a QR code. Keyboards and game controllers work too.

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The game. Open this on the big screen. |
| `controller.html` | The phone controller. Phones open it by scanning the QR code. |
| `manifest.webmanifest` | Lets phones add the controller to their home screen and run it full screen. |
| `icon-192.png`, `icon-512.png` | The controller's home-screen icon. |
| `README.md` | This guide. |

## Put it online with GitHub Pages (about 5 minutes)

Phones can only connect when the game runs from a real website, so it needs to be published once.

1. Sign in at [github.com](https://github.com) and click **New** (the green button) to make a new repository.
2. Name it `salvo-brawl`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in all six files from this folder, then click **Commit changes**.
4. Open the repository's **Settings** tab, then **Pages** in the left sidebar.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Pick the **main** branch and the **/ (root)** folder, then click **Save**.
6. Wait a minute or two, then refresh the Pages settings screen. It shows your site's address, which looks like `https://YOUR-USERNAME.github.io/salvo-brawl/`.

**Updating to a new version:** open the repository, click **Add file → Upload files**, drag in all six files, and click **Commit changes**. GitHub replaces the old files and adds the new ones, and the site updates within a couple of minutes. If a phone still shows the old controller, refresh the page on the phone (or close and reopen the home-screen app).

## Playing

1. Open your site address on the computer and click **Fullscreen**.
2. Pick an arena and set up the match (see *Match settings*).
3. Each player scans the QR code with their phone camera. If scanning doesn't work, open the link shown under the code and type the four-letter room code. Phones connect most reliably on the same Wi-Fi as the computer. The code stays the same each time you open the game on that computer, so phones can rejoin with it.
4. On the phone, pick a tank and tap **READY UP**. When everyone is ready, the brawl starts on its own. The computer can also start it with **START BRAWL** or the Enter key, and so can the host phone (see *Host phone*).
5. Turn phones sideways and go full screen (see below).

Up to 4 players, in any mix of phones, keyboard players and game controllers. You need at least 2 to start.

### Match settings (lobby buttons)

- **MODE · LIVES / MODE · TIMED:** a set number of lives each, last one standing wins; or a timed match. The **− / +** buttons next to it set the lives (1 to 9) or the minutes (1 to 10). In a timed match you respawn every time, score **+1 for every tank you knock out and −1 each time you go down** (including falling off), and the highest score when time runs out wins. If it's tied, the tied players go into **sudden death**: low health, and the next knockout wins.
- **FREE-FOR-ALL / 2V2 TEAMS:** with exactly four players, 2v2 splits everyone into Team A and Team B. Teammates can't hurt each other (missiles and bombs pass through). The button next to it changes who's paired with whom. With fewer than four players the match plays free-for-all.
- **POWER-UPS:** how often power-ups fall: OFF, LOW, NORMAL, HIGH or CHAOS. Click it to step through. The buttons next to it switch each kind on or off (at least one stays on). See *Power-ups*.
- **MUSIC** and **EFFECTS** sliders: volume for the background music and the sound effects. They're also on the pause screen, and M mutes everything.

### Host phone

The first phone to join is the host (its slot card on the big screen says HOST). Once everyone has joined, nobody needs to touch the computer:

- **In the lobby**, the host's phone shows a match setup panel above the tank list: arrows to pick the arena, the mode, lives or minutes, teams and how often power-ups fall. **START MATCH** starts right away, even if not everyone has tapped ready.
- **During a match**, the host has a **MENU** button in the top-right corner. It pauses the game and offers **RESUME** or **END MATCH · MAIN MENU**.
- **After a match**, the host gets **REMATCH** and **MAIN MENU** buttons.

If the host leaves or drops out, the next phone in line becomes the host. The power-up kinds and the volume can only be changed on the computer.

### Full screen on phones

Full screen hides the browser bars and stops the page from zooming when thumbs bump the screen.

- **Android:** tap **FULL SCREEN** on the join screen or in the lobby, or the **⤢** button in the corner of the controller. The phone goes full screen and locks sideways.
- **iPhone:** Safari doesn't let web pages go full screen, so add the controller to the home screen once: tap the **Share** button, choose **Add to Home Screen**, then **Add**. From then on, open **Salvo Pad** from the home screen and type the room code. It runs with no browser bars and can't zoom. The FULL SCREEN button shows these steps too.

Even without full screen, the controller blocks pinch and double-tap zoom while you're playing.

### Phone controls

- **Left half:** put your thumb down anywhere and slide. Left and right drive. **Push up to fire the jetpack.** Pull down to drop through a floating ledge.
- **Right half:** drag in the direction you want to shoot. The farther you drag, the more power. **Let go to fire.** A quick tap fires your last shot again.
- **BOMB button** (bottom right): put your thumb on it and drag, just like aiming a missile. The farther you drag, the harder you throw, and the big screen shows where the bomb will land. **Let go to throw.** A quick tap without dragging drops a mine under your tank.
- **SOUND** (lobby): your phone plays its own sounds when your tank gets hit, knocks someone out, grabs a power-up or goes down. iPhones stay silent when the ring/silent switch is set to silent.

### Keyboard controls

| | Keys 1 | Keys 2 |
|---|---|---|
| Join in the lobby / ready up | G | K |
| Change tank in the lobby | F / H | J / L |
| Drive | A / D | ← / → |
| Jetpack (hold) | W | ↑ |
| Drop through ledge | S | ↓ |
| Aim barrel | F / H | J / L |
| Fire | Hold G to charge, release | Hold K to charge, release |
| Bomb | Hold T to charge, release to throw | Hold I to charge, release to throw |

Bombs fly the way your barrel points, so aim with the barrel keys while you hold the bomb key. A quick tap of the bomb key drops a mine. Esc pauses, M mutes.

Game controllers join with A. Left stick drives (A or LB for jetpack), right stick aims and sets power, RT or RB fires. For bombs, hold the right stick in the direction you want and hold B or Y, then let go of B or Y to throw; press B or Y with the right stick centred to drop a mine.

### Rules

- Everyone has the same number of lives, **3** unless you change it (or unlimited respawns in a timed match).
- Missiles and bombs drain health. A **direct hit** does the most damage; near misses do less the farther away they land.
- Every hit **knocks you back**, and the less health you have, the farther you fly. Each player's card shows a **knockback multiplier**: ×1.0 at full health, about ×2.2 at half and nearly ×4 when you're almost out. It turns red at ×2 or more.
- Your **jetpack** has about 3.5 seconds of fuel and **refills the moment you land**. Use it to reach higher levels and to fly back after a big knockback.
- Falling off the map is **instant death**: you lose a life no matter how much health you had.
- Running out of health also costs a life. You respawn at the top after a couple of seconds, briefly invincible.
- The camera only zooms in and slows down for the **final knockout** of a match.

### Music

The lobby plays a calm groove. Matches switch to a much harder, faster battle track. In a timed match it speeds up through the last minute, a clock ticks through the last ten seconds, and sudden death runs flat out. In a lives match it picks up for the final showdown, once every tank still in the fight is on its last life.

### Bombs

- Everyone carries **2 bombs**. Each one recharges 4 seconds after you use it.
- A bomb does more damage than a missile (up to 30) and has a bigger blast.
- **Thrown bombs** are aimed like missiles (see the controls). They arc, bounce, and explode after about 2.5 seconds, or right away if they hit a tank.
- **Mines** sit where they land, arm after a moment (the light starts blinking), and go off when an enemy drives over them. They last 14 seconds.
- Your own bombs never hurt you, but their blast still pushes you, so a mine under your own tank works as a rocket jump.
- Shooting a bomb or mine sets it off, and explosions set off any bombs nearby.

### Power-ups (optional)

Pick how often they fall with the **POWER-UPS** button in the lobby: **LOW** (every 24–34 seconds), **NORMAL** (13–20), **HIGH** (6–10) or **CHAOS** (2–4). Only one is on the map at a time; drive into it to grab it. Ones nobody grabs disappear after a while. The buttons next to POWER-UPS turn each kind on or off.

| Power-up | What it does |
|---|---|
| ★ Star | Fire twice as fast for 8 seconds. Your tank glows gold. |
| ⬢ Shield | A bubble blocks all damage and knockback for 8 seconds. It doesn't stop you falling off the map. |
| ◌ Invisibility | Your tank fades to a faint shimmer for 8 seconds, with no name tag or aiming line. It flickers into view when you fire or get hit. |
| ☄ Mega missile | Your next shot is a huge missile: 4× damage, a massive blast and extra knockback. Use it within 15 seconds. |

### Arenas

| Arena | Size | Notes |
|---|---|---|
| Skyforge Isles | Standard | One big island with floating ledges above it |
| Magma Foundry | Standard | Two decks with a lava pit in the middle |
| Frostpeak Basin | Standard | High cliffs around a sunken valley |
| Titan Orbital | **Big** (double size) | Space station with five tiers and two wide gaps to cross |
| Skyforge Archipelago | **Big** (double size) | A chain of four sky islands with three gaps; jetpack between them |
| Magma Refinery | **Big** (double size) | Refinery decks, a central pillar and catwalks over a lava sea |
| Glacier Fortress | **Big** (double size) | An ice keep in the middle, sunken valleys either side and high cliffs at the ends. The only big map with no gaps, so most KOs come from knockback |
| Warp Nexus | **Big** (double size) | Four portals spread across the station in two linked pairs: the cyan pair joins the bottom-left corner to the upper-right deck, the pink pair joins the bottom-right corner to the upper-left deck. Drive in one, come out the other. Missiles and thrown bombs go through too, keeping their speed and direction. The camera holds still on this map and shows the whole station, so teleports don't make it zoom in and out |
| Shattered Skies | **Big** (double size) | Platforms with pale, cracked tops crumble if you stay on them too long (their trim turns red and they shake first), then rebuild about 6 seconds later. The two side islands, the two spawn pads and the top platform never crumble |

### Tanks

In the lobby, each player's tank turns on a lit platform in their slot card. Each tank has its own look, but every tank is the same size and uses the same missiles, bombs and jetpack. They differ in these stats:

| Tank | Role | Strengths | Trade-offs |
|---|---|---|---|
| Vanguard | All-rounder | Even in every stat | No standout strengths |
| Striker | Scout | 25% faster, 25% more jet fuel, slightly quicker reload | 15% less health, easier to knock back |
| Bulwark | Heavy | 28% more health, 28% harder to knock back, 5% more damage | 20% slower, reloads 22% slower, 15% less jet fuel |
| Ravager | Demolition | 15% bigger blasts, 10% more damage, 20% more knockback | Reloads 10% slower, a little slower to drive |
| Viper | Rapid fire | Reloads 26% faster, faster missiles | 22% less damage, 10% less health, smaller blasts |

## If something goes wrong

- **The QR box says "NO ROOM":** the computer couldn't reach the room server. Check the internet connection and click **TRY AGAIN**.
- **A phone says "ROOM NOT FOUND":** check the code on the big screen. If the game page was just opened or reloaded, wait a few seconds and tap **TRY AGAIN**.
- **A phone says "CAN'T LINK UP":** the phone found the game, but its network wouldn't let it connect to the computer. Put the phone on the same Wi-Fi as the computer and tap **TRY AGAIN**. If it's already on the same Wi-Fi, switch it to mobile data instead. The big screen also shows a yellow note when this happens. School, campus, work and guest Wi-Fi often block devices from talking to each other; a phone hotspot is a good fallback.
- **A phone says "CAN'T REACH THE SERVER":** the phone's network is blocking the game's connection server. Switch between Wi-Fi and mobile data.
- **A phone says "THIS BROWSER CAN'T CONNECT":** it opened the link in a QR-scanner app's built-in browser. Open the link in Chrome (Android) or Safari (iPhone) instead.
- **An iPhone home-screen shortcut opens an old game:** delete the Salvo Pad shortcut and add it again from the controller page. Shortcuts added from now on open the join screen with the last code that worked.
- **A phone drops out mid-match:** it reconnects by itself, and its tank keeps its spot. If the link goes quiet, the tank stops moving until the phone is back, so it won't drive off a ledge on its own. You can also scan the code again.
- **The phone zooms or the browser bars get in the way:** go full screen (see *Full screen on phones*). On iPhone, play from the home-screen app.

## How it works

The phones and the computer find each other through PeerJS's free public server. Once connected, controls go straight from each phone to the computer. When a network won't allow a direct link (common on mobile data and campus Wi-Fi), the controls go through a free public relay server instead (PeerJS's or Metered's Open Relay), which adds a little delay. Those free servers come with no guarantees, so the same Wi-Fi is still the most reliable setup. Nothing is stored online and no accounts are needed.
