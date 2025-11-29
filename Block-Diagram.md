### Block Diagram – VLPatil-Ind-Gen-Classic (Version 1 – Classic)

```text
                            50 Hz Grid / Load
                                   ▲
                                   │
┌───────────────┐       ┌──────────┴──────────┐       ┌───────────────┐
│ Wind / Hydro  │       │ Main Induction      │       │  Fixed Stator │
│ Prime Mover   │──────►│ Generator (MIG)     │──────►│  50 Hz output │
│ (variable spd)│  Same │ Wound-rotor         │       └───────────────┘
└───────────────┘  Shaft└──────────┬──────────┘
                                   ▲
                                   │
                          ┌────────┴────────┐
                          │ Auxiliary       │
                          │ Induction       │
                          │ Machine (AIM)   │
                          │ ≈ 1/3 rd power  │
                          └────────┬────────┘
                                   ▲
                Tiny 400–750 W servo rotates AIM stator
                AIM stator fed via low-power slip rings
                AIM rotor → directly wired to MIG rotor
