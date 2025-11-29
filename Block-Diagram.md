
### Block Diagram – VLPatil-Ind-Gen-Classic (Version 1 – Classic)

**Flow:**
- Prime Mover (Wind/Hydro Shaft, variable speed)  
  ↓ (Rigid coupling – same shaft for both rotors)  

- **Main Induction Generator (MIG)**  
  - Power: 5 kW (example)  
  - Type: Wound-rotor  
  - Stator: Fixed → Directly connected to 50 Hz Grid/Load  
  - Rotor: Receives slip-frequency excitation from AIM  
  - Output: Clean 50 Hz power  

  ↓ (Direct wire connection – no rotor slip rings)  

- **Auxiliary Induction Machine (AIM)**  
  - Power: ≈1/3 of MIG (1.5 kW example)  
  - Type: Wound-rotor  
  - Stator: Fed from 50 Hz grid via low-power slip rings  
  - Stator: Rotated by tiny 400–750 W servo (speed/direction tunes torque)  
  - Rotor: Generates slip-frequency voltage → feeds MIG rotor  

**Key Features:**  
- No high-power slip rings (rotors turn together)  
- Servo controls slip for ±30–40 % speed range  
- Zero power electronics – pure mechanical  
- Result: Fixed 50 Hz output, legendary reliability  

**Notes:**  
- Build with standard Indian motors (e.g., Kirloskar or Crompton).  
- Servo: Any BLDC/stepper for AIM stator rotation.
