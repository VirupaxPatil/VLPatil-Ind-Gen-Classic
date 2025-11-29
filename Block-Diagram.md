VLPatil-Ind-Gen-Classic – Block Diagram (Version 1 – Classic)

┌──────────────┐        ┌─────────────────────┐       ┌─────────────────┐
│   Wind / Hydro  │        │   Main Induction        │       │   50 Hz Grid       │
│   Prime Mover   │── ──►│   Generator (MIG)        │──►. │   or Village       │
│   (variable     │  Same │   Wound-rotor            │       │   Load             │
│    speed)       │  Shaft│   Stator fixed           │       └─────────────────┘
└──────────────┘        │   Rotor receives        │
                           │   slip-frequency        │
                           │   excitation            │
                           └────────┬────────────┘
                                     ▲
                                      │
                           ┌────────▼───────────┐
                           │ Auxiliary Induction    │
                           │ Machine (AIM)          │
                           │ ≈ 1/3 rd power         │
                           │ Wound-rotor            │
                           └────────┬───────────┘
                                    ▲
                    ┌──────────────┴─────────────┐
                    │  Tiny 400–750 W servo motor     │
                    │  rotates AIM stator slowly      │
                    └────────────────────────────┘

Connections:
- AIM stator → fed from 50 Hz grid via one low-power slip-ring set
- AIM rotor output → directly wired to MIG rotor (no rotor slip rings!)
- Servo direction/speed sets exact slip frequency and torque

Result → clean 50 Hz at MIG stator over ±30–40 % speed range
         with zero power electronics.
