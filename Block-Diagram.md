### Block Diagram – VLPatil-Ind-Gen-Classic (Version 1 – Classic)
Prime Mover (Wind/Hydro Shaft) ↓ (Same Shaft) ┌─────────────────────┐ │ Main Ind. Generator │ │ (MIG)               │ │ Wound-Rotor         │ │ Stator: Fixed → 50 Hz Grid/Load │ Rotor: Receives Slip-Freq from AIM └────────┬──────────────┘ │ │ (Direct Wire) ↓ ┌─────────────────────┐ │ Aux. Ind. Machine   │ │ (AIM)               │ │ ≈ 1/3 Power         │ │ Wound-Rotor         │ │ Stator: Grid via    │ │ Slip Rings + Servo  │ │ Rotation (400–750 W)│ └─────────────────────┘
Key:
No rotor slip rings (both rotors on same shaft)
Servo speed/direction tunes torque & frequency
Result: Clean 50 Hz output over ±30–40% speed range
Zero power electronics

**Notes**:  
- Build with standard Indian motors (e.g., 5 kW MIG, 1.5 kW AIM).  
- Servo: Any 400–750 W BLDC/stepper for AIM stator rotation.
