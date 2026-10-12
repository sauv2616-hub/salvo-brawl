# Salvo

A live 2–8 player tank brawler. The computer (or a TV plugged into it) shows the battle, and each player uses their phone as a controller by scanning a QR code. Keyboards and game controllers work too.

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

1. Open your site address on the computer and click the full-screen icon (top right).
2. Pick an arena and its map type from the two drop-down menus, and set up the match (see *The lobby* and *Match settings*).
3. Each player scans the QR code with their phone camera. If scanning doesn't work, open the link shown under the code and type the four-letter room code. Phones connect most reliably on the same Wi-Fi as the computer. The code stays the same each time you open the game on that computer, so phones can rejoin with it.
4. On a phone, swipe the tank to pick one, pick two weapons and tap **READY UP**. When everyone is ready, the brawl starts on its own. The computer can also start it with **Start match** or the Enter key, and so can the host phone (see *Host phone*).
5. Turn phones sideways and go full screen (see below).

Up to 8 players, in any mix of phones, keyboard players, game controllers and CPU players. You need at least 2 to start.

### The lobby

- **Left:** the match setup. The **arena** drop-down lists the seven arena types with a little map of each; the size buttons under it pick **Small**, **Big** or **Mega**. The **map type** drop-down picks **Regular**, **Classic**, **Bounce**, **Active** or **Rising** (see *Map type*), and the match rules sit underneath. The arena you pick is shown live behind the lobby, a little darker so the tanks stand out.
- **Middle:** every player's tank, big, turning slowly on a plain dark turntable under a spotlight. Under each tank is the player's name plate: their tank, their two weapons and how they're playing (keys, controller or phone). Keyboard and controller players can click their tank's name or weapons to change them. Click the team badge to move a player to another team, and **×** to remove them.
- **Right:** the room code and QR code for phones, the CPU players, and **Start match**.
- **Top right:** the gear opens the settings: music and effects volume, mouse aiming, and **Customize keys**, which shows and changes every control. The icon next to it goes full screen.

### CPU players

Click **+ Add CPU** in the CPUs panel on the right to add a computer-controlled tank, up to 5 of them. Each CPU gets a small row instead of a big turntable. Use **− / +** to set its level from 1 (slow, wild shots, falls off a lot) to 10 (quick, accurate, recovers well, switches weapons by range, grabs power-ups and dodges). Click its tank name to change its tank, its weapons to change its two weapons, and **×** to remove it. CPUs are always ready, so the brawl starts as soon as every human is ready; it never starts with CPUs alone. The host phone can also add or remove CPUs and set their difficulty.

### Match settings

- **Mode · Lives / Timed / Diamond:** a set number of lives each, last one standing wins; or a timed match. The **− / +** buttons set the lives (1 to 9) or the minutes (1 to 10). In a timed match you respawn every time, score **+1 for every tank you knock out and −1 each time you go down** (including falling off), and the highest score when time runs out wins. If it's tied, the tied players go into **sudden death**: low health, and the next knockout wins.
- **Mode · Diamond:** hold the diamond for as long as you can. A glowing diamond drops in at the top of the arena; drive into it to grab it, and your clock (on your card) runs for as long as you carry it. Getting knocked out drops it: it pops out and rolls around until someone else picks it up. If it falls off the map (or into lava or a rising hazard), it comes back at the top. Every attack does **2.5× damage** in this mode but knocks tanks back about 30% less, so tanks go down (and the diamond changes hands) a lot more often than they fly off. If it touches a bounce net it also comes back at the top. You respawn every time. There's no match clock: the **− / +** buttons set how long you need to hold it (15 seconds to 5 minutes, 1:00 to start with), and the first player (or team, adding up its players' times) to hold it that long wins. The clock at the top shows the leader's time and the goal. CPUs go after the diamond and its carrier too.
- **Teams · Free-for-all / Teams:** with Teams on, each player is on the red, blue, green or gold team, and everyone on a team drives that colour. Teams can be any size (1 against 3 is fine). New players join the smaller of red and blue; click the team badge on a player's card to move them, or players can tap **TEAM · SWITCH** on their phone. **Auto** splits everyone evenly between red and blue. Teammates can't hurt each other, and in every mode each team starts together on its own side of the map (red on the left, blue on the right, then green and gold in between when there are more teams). In timed and diamond games your team also respawns on its own side of the centre. When two or more real players (not CPUs) are on the same team, each one gets a coloured dot and their tag in their own player colour (on their card, above their tank and on the phone), so teammates can tell each other apart while their tanks stay the team colour.
- **Power-ups:** click it to open a small panel: how often power-ups fall (Off, Low, Normal, High or Chaos) and which kinds can drop (at least one stays on). See *Power-ups*.
- **Sound:** the gear icon at the top right has the music and effects volume. They're also on the pause screen, and M mutes everything.

### Host phone

The first phone to join is the host (its name plate says HOST). Once everyone has joined, nobody needs to touch the computer. The host's phone has two tabs so it never gets crowded:

- **1 · Your tank:** the same tank garage as every other phone (see *Your phone in the lobby*). **Next · Match setup** at the bottom takes you to the second tab.
- **2 · Match setup:** a split screen. On the right, the arena card shows the arena theme with its colours, a little map and what's special about it; **swipe it** (or tap the arrows) to slide in the next arena type (Skyforge, Frostpeak, Magma and so on), and the big screen follows. On the left, drop-down menus set the arena size, the map type (Regular, Classic, Bounce, Active or Rising), how often power-ups drop (with **Pick power-ups** to choose which kinds), the mode (lives, timed or diamond), the lives, minutes or diamond goal, teams, how many bots and how hard they are.
- **Start match** starts right away, even if not everyone has tapped ready.
- **During a match**, the host has a **MENU** button in the top-right corner. It pauses the game and offers **RESUME** or **END MATCH · MAIN MENU**.
- **After a match**, the host gets **REMATCH** and **MAIN MENU** buttons.

If the host leaves or drops out, the next phone in line becomes the host. The volume can only be changed on the computer.

### Full screen on phones

Full screen hides the browser bars and stops the page from zooming when thumbs bump the screen.

- **Android:** tap **FULL SCREEN** on the join screen or in the lobby, or the **⤢** button in the corner of the controller. The phone goes full screen and locks sideways.
- **iPhone:** Safari doesn't let web pages go full screen, so add the controller to the home screen once: tap the **Share** button, choose **Add to Home Screen**, then **Add**. From then on, open **Salvo Pad** from the home screen and type the room code. It runs with no browser bars and can't zoom. The FULL SCREEN button shows these steps too.

Even without full screen, the controller blocks pinch and double-tap zoom while you're playing.

### Your phone in the lobby

- **Tank garage:** one side of the screen shows your tank turning on a stage, the other its stats (speed, armour, blast, reload, jet) and what makes it different. **Swipe the tank** left or right (or tap the arrows) and the next one slides in, spinning. Your two weapons are underneath.
- **Ready up:** tap **READY UP** and the screen shows **WAITING FOR GAME START**. **← Change tank** takes you back to the garage.
- **Control settings:** once you're ready, the gear at the top right (**CONTROLS**) opens your control settings, saved on that phone:
  - **Quick weapon swap:** double-tap the driving side of the screen to swap weapons, instead of using the weapon button above BOMB.
  - **Sides:** drive on the left and aim on the right (the normal way), or swap them: aim on the left, drive on the right. The BOMB and weapon buttons move to the aiming side.

### Phone controls

- **Left half:** put your thumb down anywhere and slide. Left and right drive. **Push up to fire the jetpack.** Pull down to drop through a floating ledge.
- **Right half:** drag in the direction you want to shoot. The farther you drag, the more power. **Let go to fire.** A quick tap fires your last shot again.
- **BOMB button** (bottom right, unlimited bombs): put your thumb on it and drag, just like aiming a missile. The farther you drag, the harder you throw, and the big screen shows where the bomb will land. **Let go to throw.** A quick tap without dragging drops a mine under your tank.
- **Weapon button** (above BOMB): tap to swap between your two weapons (see *Weapons*). It shows the one you have. With **quick weapon swap** on, double-tap the driving side instead.
- The left and right halves swap over if you picked **aim left · drive right** in the control settings.
- **AIR STRIKE button** (next to BOMB): appears when you grab an air strike. Tap it, then steer the big red target on the TV with the left stick and tap **LAUNCH**.
- **SOUND** (lobby): your phone plays its own sounds when your tank gets hit, knocks someone out, grabs a power-up or goes down. iPhones stay silent when the ring/silent switch is set to silent.

### Keyboard controls

| | Keys 1 | Keys 2 |
|---|---|---|
| Join in the lobby / ready up (the fire key) | G | K |
| Change tank in the lobby | F / H | J / L |
| Drive | A / D | ← / → |
| Jetpack (hold) | W | ↑ |
| Drop through ledge | S | ↓ |
| Aim barrel | F / H | J / L |
| Fire | Hold G to charge, release | Hold K to charge, release |
| Bomb | Hold T to charge, release to throw | Hold I to charge, release to throw |
| Swap between your two weapons (in the lobby: change which two) | R | U |
| Air strike (when you have one) | E to aim, W A S D move the target, G or E to launch | O to aim, arrows move the target, K or O to launch |

Bombs fly the way your barrel points, so aim with the barrel keys while you hold the bomb key. A quick tap of the bomb key drops a mine. With the machine gun, hold the fire key to keep firing. Esc pauses, M mutes.

### Change any key

Every keyboard key can be changed. Open settings (the gear at the top right of the lobby, or **KEYS** on the pause screen) and click **Customize keys**. Click the key you want to change, then press the new one. If another action already uses that key, the two swap, so nothing ends up on two jobs. Esc cancels, and **Reset to default** puts everything back. Your keys are saved on this computer, and the lobby hints and the controls list (the keyboard icon) always show the keys you picked. Esc (pause), M (mute) and Enter (start) can't be used.

### Mouse or trackpad aiming

One keyboard player can aim with the mouse or trackpad. It's Keys 1 to start with; change it (Keys 1, Keys 2 or Off) under **Mouse aims** in settings or in the Customize keys window.

- **Point** to aim: the barrel follows the pointer. The farther the pointer is from your tank, the more power.
- **Click** to fire. Hold the click to see where the shot will go, then let go to fire. With the machine gun, hold the click to keep firing.
- **Right-click** (a two-finger click on most trackpads) drops a mine. Hold the right button to throw a bomb toward the pointer instead. The bomb key still throws along the barrel too.
- **Air strike:** the big target follows the pointer; click to launch.

The keyboard keys keep working alongside the mouse, and the pointer is a bigger red target, so it's easy to see.

### Game controllers

Game controllers join with A. Left stick drives (A or LB for jetpack), right stick aims and sets power, RT or RB fires (hold it with the machine gun). B throws bombs: hold the right stick in the direction you want and hold B, then let go of B to throw, or tap B with the stick centred for a mine. Y swaps between your two weapons (in the lobby it changes which two). X calls an air strike: move the target with the left stick, then press X or RT to launch.

### Rules

- Everyone has the same number of lives, **3** unless you change it (or unlimited respawns in a timed match).
- Missiles and bombs drain health. A **direct hit** does the most damage; near misses do less the farther away they land.
- Every hit **knocks you back**, and the less health you have, the farther you fly. Each player's card shows a **knockback multiplier**: ×1.0 at full health, about ×2.2 at half and nearly ×4 when you're almost out. It turns red at ×2 or more.
- Your **jetpack** has about 3.5 seconds of fuel and **refills the moment you land**. Use it to reach higher levels and to fly back after a big knockback.
- Falling off the map is **instant death**: you lose a life no matter how much health you had.
- Running out of health also costs a life. You respawn at the top after a couple of seconds, invincible for about 3 seconds.
- **Combos:** hit the same tank again before it lands and settles and the hit does more damage: ×1.25 for the second hit, ×1.5 for the third, up to ×2. The hit shows **2 HIT COMBO**, **3 HIT COMBO** and so on. Only hits from the same player (or CPU) count, so hits from different players never add up to one combo. For example, bomb a tank into the air, then snipe it before it lands, and the snipe does extra damage.
- Who goes down and who grabs a power-up shows near the top of the big screen, small enough to stay out of the way.
- The camera only zooms in and slows down for the **final knockout** of a match. The screen shakes when tanks get hit, and shakes less the more tanks there are, so an 8-player brawl stays easy to watch.

### Music

The lobby plays a calm groove. Matches switch to a pumping battle track built in four-bar phrases: the drums and a rolling bass start it off, then a sweeping arpeggio comes in, then the lead riff, then everything at once with a snare-roll build, and each new phrase lands with a crash and a deep drop. In a timed match it speeds up through the last minute, a clock ticks through the last ten seconds, and sudden death plays every layer flat out. In a lives match it picks up for the final showdown, once every tank still in the fight is on its last life.

### Weapons

Before each match, every player picks **two of the four weapons** and can only use those two during the match. You can swap between them at any time (a short pause after swapping stops quick-swap combos), and the tank stats still apply on top.

- **Phone:** in the lobby, tap two weapon cards. The one marked **START** is the one you begin the match with; tap your other one to make it the starting weapon instead. In the match, the weapon button swaps between your two.
- **Keyboard:** in the lobby, **R** (Keys 1) or **U** (Keys 2) steps through the possible pairs, or click the weapons on your name plate. In the match, the same key swaps.
- **Game controller:** **Y** steps through the pairs in the lobby and swaps in the match.
- **CPUs** get a random pair; click a CPU's weapons to change them.

| Weapon | How it fires | Damage | Reload |
|---|---|---|---|
| ◆ Missile | Arcs; drag farther (or charge longer) for more power | 22 direct, splash around the blast | About 1 second |
| ≡ Machine gun | A stream of fast rounds while you hold the aim; just point it | 3 per round, no splash; each round pushes a little | About 8 rounds a second |
| ⊕ Sniper | A very fast, almost straight shot | 40 direct, small blast | About 2.6 seconds |
| ⬤ Bazooka | A slow, heavy rocket with a high arc | 30 direct and a huge blast radius with big knockback | About 3.2 seconds |

Your card on the big screen shows the weapon you have and the other one you can swap to.

### Bombs

- Bombs **never run out**. After each one there's a short cooldown (about 1 second) before you can use the next. The bomb button on the phone dims while it cools down.
- A bomb does more damage than a missile (up to 30) and has a bigger blast.
- **Thrown bombs** are aimed like missiles (see the controls). They arc, bounce, and explode after about 2.5 seconds, or right away if they hit a tank. You can throw as many as you like.
- **Mines** sit where they land, arm after a moment (the light starts blinking), and go off when an enemy drives over them. They last 20 seconds.
- **Two mines at most:** you can have two mines planted at once. Dropping a third sets off both of the planted ones, wherever they are, and plants the new one. That makes a handy remote trigger: plant two, wait for someone to walk past, then drop another. Throwing bombs never sets your mines off.
- The dots on your phone's bomb button and on your card show how many mines you have planted.
- Your own bombs never hurt you, but their blast still pushes you, so a mine under your own tank works as a rocket jump.
- Shooting a bomb or mine sets it off, and explosions set off any bombs nearby.

### Power-ups (optional)

Pick how often they fall with the **POWER-UPS** button in the lobby: **LOW** (every 24–34 seconds), **NORMAL** (13–20), **HIGH** (6–10) or **CHAOS** (2–4). Only one is on the map at a time; drive into it to grab it. Ones nobody grabs disappear after a while. The buttons next to POWER-UPS turn each kind on or off.

| Power-up | What it does |
|---|---|
| ★ Star | Fire twice as fast for 16 seconds. Your tank glows gold. |
| ⬢ Shield | A bubble blocks all damage and knockback for 16 seconds. It doesn't stop you falling off the map. |
| ⇈ Wings | Wings sprout from your tank and your jetpack never runs out for 16 seconds, so you can fly the whole time without landing. |
| ▾ Tiny | Your tank shrinks to half size for 16 seconds, so missiles and bombs often fly right over it. Knockback stays exactly the same as normal size. |
| ✚ Med kit | +15 health straight away (up to your maximum). |
| ✹ Spam bombs | No bomb cooldown for 16 seconds: throw as fast as you can tap. |
| ☄ Mega missile | Your next shot is a huge missile: 4× damage, a massive blast and extra knockback. Use it within 30 seconds. |
| ➶ Heat seeker | Your next shot is a slow missile that chases the nearest enemy for 8 seconds, then explodes in the air if it hasn't hit anything. Shooting it down works too. Use it within 30 seconds. |
| ◎ Air strike | Kept until you use it (or go down). Calling it shows a giant red target on the big screen; steer it, then launch, and three missiles fly in from the screen and blast the area. While you aim, your tank can't move and can still be hit. It launches by itself after 12 seconds. |

### Arenas

There are seven arena types, and each one comes in three sizes: **Small**, **Big** (about double) and **Mega** (huge, for up to 8 players). Every type changes the game in its own way.

| Type | Small | Big | Mega | What's special |
|---|---|---|---|---|
| Skyforge (grass) | Skyforge Isles | Skyforge Archipelago | Skyforge Expanse | **Earthquakes:** every so often the ground rumbles, then the islands shake for a few seconds and bounce the tanks around. Careful near the edges. |
| Frostpeak (ice) | Frostpeak Basin | Glacier Fortress | Frostfall Citadel | Very slippery ice: tanks slide a long way and take a while to stop or turn round. |
| Magma (fire) | Magma Foundry | Magma Refinery | Magma Inferno | **Volcano bounce pads** (glowing pads with arrows rising out of them) throw any tank that drives or lands on them sky-high, with a full jetpack. Every few seconds a pad also rumbles and erupts in a column of fire that burns and launches whoever is on top. |
| Titan (space) | Titan Outpost | Titan Orbital | Titan Megastation | Low gravity (half normal): tanks float up and drift down, and shells fly in long, floaty arcs. |
| Warp (portals) | Warp Junction | Warp Nexus | Warp Labyrinth | Linked portals (shown by colour) teleport tanks, missiles and bombs. The camera holds still so teleports don't make it jump. |
| Abyss (underwater) | Coral Reef | Sunken Ruins | Abyssal Trench | Tanks are buoyant and sink slowly, missiles and bombs drag through the water and slow down, and a strong current drifts back and forth, pushing tanks and shots with it. |
| Neon City (city) | Neon Rooftops | Neon Boulevard | Neon Megacity | **Fog** rolls in every so often, thick enough to hide the whole background and the platforms for a few seconds. They're still there, so remember where they were. Tanks, bombs and power-ups stay visible. |

**Map type** (pick one; only one can be on at a time):

- **Regular:** the arena as it is, with its own twist (see the table above).
- **Classic:** no twists at all: no bounce pads, fog, earthquakes, portals, slippery ice, low gravity or water. Just the platforms.
- **Bounce:** a glowing energy net stretches under the arena. Fall into it and it throws you back up with a full jetpack, but every bounce costs 30 health (and can knock you out if you're low). Fly off the sides past the net and you still fall. Bombs and missiles explode on the net.
- **Active:** the map changes while you play. Every 11 to 17 seconds something happens. There's no warning banner: each event has its own signature sound (a howling wind, a rumbling avalanche, bubbling lava, horns of hover traffic and so on) that starts a second or two before it hits, so you can hear it coming. Half the time a group of platforms (the left side, the right side, the top platforms or the bottom decks) blinks red, crumbles away, and comes back about 6 seconds later, so get off them when they blink. The other half is the arena's own event:

| Type | Active-map event |
|---|---|
| Skyforge | **Wind gust:** a strong wind blows everything one way for a few seconds. |
| Frostpeak | **Avalanche incoming:** a wall of snow sweeps across the high or low half of the map, hitting and shoving every tank in its way. |
| Magma | **Lava is rising:** the lava climbs up over the bottom decks, holds there, then drains. Touching it burns and throws you upward. |
| Titan | **Meteor shower:** meteors rain down and explode where they land. |
| Warp | **Portals haywire:** every portal leads somewhere random for a few seconds. |
| Abyss | **Tidal surge:** a powerful current pushes everything one way. |
| Neon City | **Hover traffic:** a stream of flying cars sweeps across the high or low half of the map, hitting and shoving every tank in its way. |

- **Rising:** the whole map keeps climbing. A few seconds into the match a deep rumble plays and a hazard that matches the arena starts rising from the bottom, and the view (and the edge you fall off) climbs with it. New platforms keep appearing at the top; the lowest ones flash, then the hazard swallows them, so keep climbing. The camera always keeps the hazard in view, and it rises a little faster the longer the match goes on.

| Type | What rises |
|---|---|
| Skyforge | **Earthquake:** the islands shake apart from the bottom up. The lowest ones shake hard, then crumble away. There's nothing underneath, so falling below them knocks you out. |
| Frostpeak | **Snow:** a snowdrift buries the lowest ledges. Touching it hurts and throws you back up. |
| Magma | **Lava:** lava swallows the lowest decks. Touching it burns and throws you back up. Some of the new platforms have volcano bounce pads. |
| Titan | **Meteor belt:** a band of tumbling rocks climbs through the station. Touching it hurts and knocks you up and sideways. |
| Warp | **Warp storm:** touching it costs health and throws you back to the top of the map. Portals it swallows switch off. |
| Abyss | **Riptide:** the tide floods the lowest shelves. Touching it hurts and pushes you back up. |
| Neon City | **Toxic fog:** the fog swallows the lowest rooftops, and you can't see platforms inside it. Touching it hurts and throws you back up. |

CPU players know what's coming too: they get off dropping platforms, away from rising lava, and on a rising map they keep climbing.

Mega maps are wide, so with everyone spread out the camera pulls back a long way and tanks look small. They play best on a big TV.

### Tanks

In the lobby, each player's tank turns slowly on a turntable. Each tank has its own look, but every tank is the same size and uses the same missiles, bombs and jetpack. They differ in these stats (the phone shows them when you pick a tank):

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
