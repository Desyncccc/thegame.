<div align="center">

# ⚡ NEON SWARM ⚡

### Two players. One arena. Endless machines.

**A first-person co-op wave shooter that runs in your browser. No install, no account, no server.**

`three.js` · `WebRTC peer-to-peer` · `one HTML file`

</div>

---

## 🔥 What is this

You and a friend get dropped into a neon arena. Waves of hostile drones pour in from the walls. You shoot, dash, rocket-jump and drag each other back up off the floor until the swarm finally wins.

Every wave you clear, you each pick an upgrade. By wave 10 you are a different animal.

## 🎮 Play with a friend

1. Both of you open the game (see **Run it** below).
2. One player clicks **HOST GAME** and reads out the 4-letter room code in the top-left.
3. The other types the code and clicks **JOIN**.
4. Host presses **ENTER**. Good luck.

Supports up to 4 players. **SOLO** works too.

## 🕹️ Controls

| Key | Action |
| --- | --- |
| `W A S D` | Move |
| `MOUSE` | Aim / fire |
| `SPACE` | Jump, press again mid-air to double jump |
| `SHIFT` | Dash |
| `1` `2` `3` / `Q` / wheel | Switch weapon (and pick upgrades between waves) |
| `R` | Reload |
| `E` (hold) | Revive a downed teammate |
| `ENTER` | Host: start / restart |

## 🔫 Arsenal

| Weapon | Feel |
| --- | --- |
| **RIFLE** | Full-auto laser. Reliable. Aim for the eye. |
| **SHOTGUN** | Nine pellets of "get away from me". |
| **LAUNCHER** | Area damage. Also launches *you*. Rocket-jumping is encouraged. |

**Every enemy has a glowing eye. Hit it for double damage.**

## 👾 The swarm

| Enemy | Problem |
| --- | --- |
| 🔴 **Grunt** | Runs at you and hits you. Lots of them. |
| 🟠 **Bomber** | Fast. Explodes. Shoot it before it arrives. |
| 🟢 **Spitter** | Keeps its distance and shoots back. |
| 🟣 **Tank** | Huge health pool, heavy hits. |
| 💀 **Boss** | Every 5th wave. Bullet rings and reinforcements. |

## ⬆️ Upgrades

Clear a wave, pick 1 of 3. They stack.

`OVERCHARGE` more damage · `HAIR TRIGGER` faster fire · `PLATING` more HP · `THRUSTERS` more speed · `VAMPIRE` heal on kill · `DRUM MAG` bigger mags · `VOLATILE` your kills explode · `DEADEYE` stronger eye-shots · `BLINK` faster dash · `SLEIGHT` faster reload

## 🤝 Co-op rules

- Go down and your teammate can revive you by holding `E` next to you.
- Everyone downed = game over.
- Clearing a wave revives and heals the whole team.
- Green crystals dropped by enemies restore health.

## 🚀 Run it

**Easiest: GitHub Pages.** In this repo go to *Settings → Pages*, set the source to the branch containing `index.html`, and send your friend the link it gives you.

**Or locally:**

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`. Your friend can open their own copy of the page too. The room code connects you over the internet either way.

## 🧠 Good to know

- The host's browser runs the enemies, so the **host should keep the game tab focused**. If the host tabs out, the swarm freezes for everyone.
- Connections are peer-to-peer through the free public PeerJS broker. Very strict networks (some school or office Wi-Fi) can block it.
- Desktop with mouse and keyboard only.

---

<div align="center">

**Hold the arena.**

</div>
