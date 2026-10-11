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
2. Pick an arena. Turn on **Star drops** if you want power-up stars.
3. Each player scans the QR code with their phone camera. If scanning doesn't work, open the link shown under the code and type the four-letter room code. Phones connect most reliably on the same Wi-Fi as the computer. The code stays the same each time you open the game on that computer, so phones can rejoin with it.
4. On the phone, pick a tank and tap **READY UP**. When everyone is ready, the brawl starts on its own. The computer can also start it with **START BRAWL** or the Enter key.
5. Turn phones sideways and go full screen (see below).

Up to 4 players, in any mix of phones, keyboard players and game controllers. You need at least 2 to start.

### Full screen on phones

Full screen hides the browser bars and stops the page from zooming when thumbs bump the screen.

- **Android:** tap **FULL SCREEN** on the join screen or in the lobby, or the **⤢** button in the corner of the controller. The phone goes full screen and locks sideways.
- **iPhone:** Safari doesn't let web pages go full screen, so add the controller to the home screen once: tap the **Share** button, choose **Add to Home Screen**, then **Add**. From then on, open **Salvo Pad** from the home screen and type the room code. It runs with no browser bars and can't zoom. The FULL SCREEN button shows these steps too.

Even without full screen, the controller blocks pinch and double-tap zoom while you're playing.

### Phone controls

- **Left half:** put your thumb down anywhere and slide. Left and right drive. **Push up to fire the jetpack.** Pull down to drop through a floating ledge.
- **Right half:** drag in the direction you want to shoot. The farther you drag, the more power. **Let go to fire.** A quick tap fires your last shot again.
- **BOMB button** (bottom right): tap it while you're driving to throw a bomb that way. Tap it while standing still to drop a mine under your tank. Tap it while jetpacking to drop a bomb on whoever is below.

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
| Bomb | T | I |

Hold a drive key while pressing the bomb key to throw it; press it on its own to drop a mine. Esc pauses, M mutes.

Game controllers join with A. Left stick drives (A or LB for jetpack), right stick aims and sets power, RT or RB fires, B or Y drops or throws a bomb.

### Rules

- Everyone has **3 lives**.
- Missiles and bombs drain health. A **direct hit** does the most damage; near misses do less the farther away they land.
- Every hit **knocks you back**, and the less health you have, the farther you fly. Each player's card shows a **knockback multiplier**: ×1.0 at full health, about ×2.2 at half and nearly ×4 when you're almost out. It turns red at ×2 or more.
- Your **jetpack** has about 3.5 seconds of fuel and refills while you're on the ground. Use it to reach higher levels and to fly back after a big knockback.
- Falling off the map is **instant death**: you lose a life no matter how much health you had.
- Running out of health also costs a life. You respawn at the top after a couple of seconds, briefly invincible.
- The last tank with lives left wins.

### Bombs

- Everyone carries **2 bombs**. Each one recharges 4 seconds after you use it.
- A bomb does more damage than a missile (up to 30) and has a bigger blast, but it's harder to land.
- **Thrown bombs** arc a short distance in the direction you're driving, bounce, and explode on their own after about 2.5 seconds, or right away if they hit a tank.
- **Mines** sit where they land, arm after a moment (the light starts blinking), and go off when an enemy drives over them. They last 14 seconds.
- Your own bombs never hurt you, but their blast still pushes you, so a mine under your own tank works as a rocket jump.
- Shooting a bomb or mine sets it off, and explosions set off any bombs nearby.

### Star drops (optional)

Turn on **Star drops** in the lobby. A star then falls somewhere on the map every 15–20 seconds. Drive into it to **fire twice as fast for 8 seconds**; your tank glows gold while it lasts. Stars that nobody grabs disappear after a while.

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

### Tanks

Every tank uses the same missiles, bombs and jetpack. They differ in these stats:

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
