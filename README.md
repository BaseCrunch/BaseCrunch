<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:081221,45:141b38,100:ff4d8d&text=Project%20Nava&fontSize=50&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Next-gen%20Anime%20Streaming%20Engine&descAlignY=60&descSize=18" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=700&color=FF4D8D&center=true&vCenter=true&width=900&lines=Torrent-powered+anime+streaming;Playback+V2+architecture;Autoplay+without+broken+handoffs;C%23+%2B+WPF+%2B+real+playback+lifecycle+design" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-WPF-68217A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Streaming-Torrent%20Powered-0EA5E9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Playback-V2-FF4D8D?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Autoplay-Engine%20Focused-F59E0B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-22C55E?style=for-the-badge" />
</p>

<h1 align="center">⚔️ Project Nava</h1>
<p align="center"><b>Anime-styled engineering. Built around real playback lifecycle design — not UI tricks.</b></p>

<p align="center">
  <sub>Project Nava is a torrent-powered anime streaming engine focused on startup correctness, clean playback teardown, and multi-episode autoplay stability.</sub>
</p>

---

## 🌸 Identity

<table>
<tr>
<td width="58%" valign="top">

### Who I am
I’m building **Project Nava** — a streaming engine designed around **fresh playback sessions**, **strict validation**, and **autoplay that survives real usage**.

### What I care about
- smooth startup
- strict validation
- no reused broken media state
- autoplay that survives multiple episodes
- product feel, not just “it kinda works”

### Tech focus
`C#` `WPF` `Torrent Streaming` `Playback Systems` `State Management`

</td>
<td width="42%" valign="top">

```text
BOOT SEQUENCE
─────────────
> initialize engine
> attach torrent backend
> validate stream
> create fresh playback session
> arm autoplay
> ready
```

</td>
</tr>
</table>

> **Optional anime upgrade:** upload your Milim render to GitHub and replace the preview block below with the raw image URL if you want character styling without broken image boxes.

---

## 🎬 Project Preview

> Replace the placeholder below with a real screenshot or GIF from Nava for the biggest visual upgrade.

```text
┌──────────────────────────────────────────────────────────────┐
│ PROJECT NAVA                                                │
│ Episode: 03                                                 │
│ Source: Torrent Stream                                      │
│ Buffer: Stable                                              │
│ Playback: Active                                            │
│ Autoplay: Armed → Episode 04                                │
└──────────────────────────────────────────────────────────────┘
```

### Recommended real assets
- one clean **home screen screenshot**
- one **player screenshot**
- one short **autoplay GIF**

---

## 🎛 Control Panel

```text
[ PLAY ]   [ NEXT ]   [ AUTOPLAY ON ]

ENGINE: ACTIVE
SESSION: CLEAN
STATE: VALIDATED
HANDOFF: READY
```

---

## 📡 Live System

<table>
<tr>
<td width="50%" valign="top">

### Runtime Feed
```text
[23:14:02] preload target episode
[23:14:04] front probe validated
[23:14:05] previous session torn down
[23:14:05] fresh playback session created
[23:14:06] playback started
[23:14:06] autoplay armed
```

</td>
<td width="50%" valign="top">

### Current State
```text
ENGINE            ONLINE
TORRENT BACKEND   CONNECTED
PLAYBACK V2       ACTIVE
AUTOPLAY          READY
PHASE             STABILITY / VALIDATION
```

</td>
</tr>
</table>

---

## ⚡ Core Features

- **Instant torrent streaming**
- **Playback V2 architecture**
- **Strict episode session reset**
- **Autoplay handoff designed to survive multiple episodes**
- **Preload → Validate → Play startup model**
- Planned: **subtitle defaults**, **audio defaults**, **cache cleanup**, **privacy controls**

---

## 🎥 Playback Pipeline

```text
[User Action]
      ↓
[Preload Target Episode]
      ↓
[Front Probe Validation]
      ↓
[Teardown Previous Session]
      ↓
[Create Fresh Playback Session]
      ↓
[Start Stream]
      ↓
[Arm Autoplay For Next Episode]
```

### Rules
- no fake-ready playback
- no stale media carryover
- no reusing previous playback state
- every episode starts through the same main playback route

---

## 🧩 Architecture

```text
Torrent Backend
    ↓
Episode Preload Layer
    ↓
Startup Validation
    ↓
Playback Session Factory
    ↓
Embedded Video Player
    ↓
Autoplay Coordinator
```

### Design Philosophy
> **Every episode should behave like a fresh, clean launch — even during autoplay.**

Teardown is not a side detail. It is part of playback correctness.

---

## ⚔️ Nava vs Typical Players

| System Behavior | Typical Players | Project Nava |
|---|---:|---:|
| Torrent startup | ⚠️ loose | ✅ controlled |
| Playback reset | ❌ partial reuse | ✅ full teardown |
| Autoplay reliability | ❌ fragile | ✅ architecture-first |
| Session isolation | ⚠️ inconsistent | ✅ strict |
| Multi-episode continuity | ⚠️ shaky | ✅ target design |

---

## ❌ What I Won’t Do

- I won’t fake playback readiness
- I won’t reuse broken media state
- I won’t ship unstable autoplay just to say it “works”
- I won’t treat teardown like an optional cleanup detail

---

## 🗺 Roadmap

- ✅ **Phase 1** — Core playback
- ✅ **Phase 2** — Autoplay foundation
- 🚧 **Phase 3** — Stability & validation
- ⬜ **Phase 4** — Preload intelligence
- ⬜ **Phase 5** — Playback recovery
- ⬜ **Phase 6** — Decode policy
- ⬜ **Phase 7** — UX polish
- ⬜ **Phase 8+** — Full refinement

---

## 🧪 Dev Log

- rebuilt playback lifecycle around **fresh-session startup**
- removed weak startup admission paths
- tightened autoplay handoff behavior
- focusing on **stability before feature clutter**
- pushing toward **product-grade streaming feel**

---

## 🌙 Philosophy

```text
No hacks.
No fake playback.
No broken autoplay.
No pretending stale state is good enough.
```

**Only clean systems that work.**

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=BaseCrunch&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=BaseCrunch&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=BaseCrunch&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&margin-h=8" />
</p>

---

## 💬 Contact / Focus

- Ask me about **torrent streaming**, **playback systems**, and **autoplay architecture**
- Currently solving **real-time playback stability**
- Building toward a **production-level anime streaming engine**

---

<p align="center">
  <sub>Project Nava — anime energy × playback engineering</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:ff4d8d,50:141b38,100:081221" />
</p>
