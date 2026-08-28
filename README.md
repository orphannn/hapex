<div align="center">
<h1>HOOZi APEX V3</h1>
<p><strong>ESP &nbsp;|&nbsp; Smart Items &nbsp;|&nbsp; Throw Assist &nbsp;|&nbsp; Lua Scripts</strong></p>
<p> An all-in-one Apex Legends assistant focused on visual information, configuration flexibility and an extensible Lua scripting system. </p>
</div>

<p align="center">
  <a href="https://discord.gg/PnfR95ADW">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://www.hoozi.cc">
    <img src="https://img.shields.io/badge/www.hoozi.cc-0077B6?style=for-the-badge&logo=internetarchive&logoColor=white" alt="www.hoozi.cc">
  </a>
  <a href="https://docs.hoozi.cc">
    <img src="https://img.shields.io/badge/Docs-222222?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs">
  </a>
</p>

## Exclusives
### Map collision models ("miss-hit")
Map model collision works like this: when part of a character's bones are blocked, the aimbot automatically searches the remaining body parts — commonly called miss-hit.

<video src="collision-demo.mp4" controls="controls" width="500" height="300"></video>

## Features
<img width="4200" height="3200" alt="image" src="https://github.com/user-attachments/assets/890bf702-4ef3-4177-aa5c-e25c1081d134" />

```
Aimbot
├── Aim
│   ├── Master switches / Current weapon / Basic (hotkey · aim on fire · visible check · ignore team/downed/roster)
│   ├── FOV (dead zone · hip/ADS FOV · distance/zoom shrink)
│   ├── Body part (head/neck/upper body/full body · exclude head)
│   ├── Target (closest to crosshair/distance/ADS crosshair+hip distance/weighted priority · sticky lock · lost-target grace · switch lockout · switch delay · max range)
│   ├── Timing (lock during cooldown · hard turn reaction · teleport no-lock)
│   ├── No recoil (X / Y strength)
│   └── Model aim (drone / overdrive drone / gas tank / jump pad / electric fence / trophy)
├── Smooth (hip X/Y · ADS X/Y)
├── Smoothness algorithm (normal ramp / magnet / curve)
├── Movement algorithm (normal proportional / PID: Kp · Ki · Kd deteriorate · damp)
└── Trigger (master · basic · release · timing · smooth · algorithm)
    └── Throw (grenade point · auto throw · damage range · trajectory)

Visuals
├── Player (ESP drawing · glow · 4 per-state scenarios · optimize)
└── Enhance (aim predict point · mini map radar · big map radar · off-screen indicator)

Items
├── Ground items (master · stacking · text · icon · colors · smart items/smart settings/backpack management)
└── Entity models (death box · traps · ultimates)

Scripts       — Lua script management / auto-load
Misc          — watermark · perf monitor · keybinds · spectators · heirloom · ALGS radar · web radar

Configs       — reload · combat · bunnyhop · superglide · mantle boost · auto grapple · tap strafe
Rosters       — add · import/export · cloud settings
USettings     — menu · draw · theme · display · device (input device rate) · license · notice · dev tools
```

## Showcase
<p align="center">
  <iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/qYd1LjixROA"
    title="HApex Demo"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</p>
