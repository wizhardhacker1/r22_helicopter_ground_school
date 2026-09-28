

# 🚁 R22 Flight School

### Interactive R22 Ground School • Cockpit Training • FAA Knowledge Prep • Flight Planning
<img width="1887" height="910" alt="image" src="https://github.com/user-attachments/assets/cc40da2d-1e51-4ef4-8102-2221cebba35b" />

R22 Flight School is a self-hosted training platform designed to bring R22 ground-school study, cockpit procedure training, FAA knowledge preparation, flight planning, aircraft performance, ATC practice, and instructor/student progress tracking into one application.

The project focuses on **interactive learning instead of passive reading**.

Students don't just read a checklist—they work through simulated cockpit controls, switches, gauges, annunciators, RPM changes, engine/rotor states, and procedure flows.

---

## 🚁 R22 Cockpit Training

The application includes two cockpit trainers with intentionally different purposes.
<img width="1893" height="903" alt="image" src="https://github.com/user-attachments/assets/0e1d1098-f579-4850-8463-6064d0d5d40e" />

### Interactive R22 Startup Cockpit

A hands-on R22 startup and run-up simulator.

Students interact with simulated aircraft controls and systems while progressing through the startup procedure.

Features include:

- Master and electrical controls
- Mixture
- Throttle
- Priming
- Starter operation
- Clutch engagement
- Alternator
- Avionics
- Governor
- Cyclic / collective / pedal checks
- Friction controls
- Warning-light tests
- Engine and rotor RPM
- Animated dual E/R tachometer
- Sprag-clutch needle split
- Annunciator behavior
- LOW RPM indication and horn
- Engine-running state
- Animated rotor/blade rotation
- Engine and rotor audio
- Rotor spool-up and coast-down
- State-driven gauges
- READY TO FLY status

The simulator only displays **READY TO FLY** when the required startup/run-up checks and simulated aircraft configuration have been completed.
<img width="1630" height="897" alt="image" src="https://github.com/user-attachments/assets/b6d868a6-1701-4efc-be6b-0b4c5ab46885" />

---

## 🔄 R22 Checklist & Cockpit Flow Study

The Cockpit Flow Trainer has a different purpose from the startup simulator.

It teaches the student to perform the **complete R22 cockpit procedure sequence and cockpit flow from memory**.

### Training phases

- Preflight
- Before Start
- Start & Run-Up
- Takeoff
- Shutdown / Securing

The simulated aircraft changes state as the checklist progresses.

Switches, controls, gauges, RPM indications, warning lights, engine state, rotor state, and system indications respond to the current procedure.

Correctly configured controls receive visual confirmation while actual aircraft warning annunciators retain their appropriate warning/caution behavior.

### Learn / Practice / Test

**Learn**

Guided training with visual assistance and immediate feedback.

**Practice**

Reduced assistance. Students locate and operate the correct controls themselves.

**Test**

Students perform procedures from memory with minimal guidance.

---

## 🛑 Interactive Shutdown Training

Shutdown is not simply a checklist-completion button.

The student performs the shutdown sequence interactively, including:

- Collective positioning
- Cyclic and pedal positioning
- Frictions
- Governor
- RPM reduction
- Engine cool-down
- Throttle closure
- Clutch disengagement
- Procedural timing/waits
- Mixture / idle cutoff
- Mixture guard
- Rotor brake
- Circuit-breaker / clutch verification
- Avionics
- Alternator
- Ignition
- Battery last

The simulation distinguishes between **engine RPM and rotor RPM**.

After engine shutdown, the rotor continues to coast and the E/R tachometer visually separates as rotor RPM decays.

The sequence finishes with:

> **SHUTDOWN COMPLETE — AIRCRAFT SECURED**

only after the required shutdown actions have been completed.

---

## 🎛️ Interactive Cockpit Systems

The cockpit simulation includes state-driven controls and indications rather than static graphics.

Examples include:

- STARTER
- CLUTCH
- LOW RPM
- GOV OFF
- LOW FUEL
- OIL
- ALT
- MR TEMP
- MR CHIP
- TR CHIP

Warning-light testing is performed directly from the cockpit panel.

---

## 📊 Functional Instrument Panel

The training panel includes interactive/state-driven instruments such as:

- Dual Engine / Rotor Tachometer
- Manifold Pressure
- Oil indications
- Airspeed
- Altimeter
- Vertical Speed
- Heading
- Attitude indication

The dual tachometer models separate:

**E — Engine RPM**

**R — Rotor RPM**

This allows the trainer to visually demonstrate events such as clutch engagement, governed operation, sprag-clutch checking, engine shutdown, and rotor coast-down.

---

## 🔊 Engine & Rotor Audio

The cockpit includes offline synthesized aircraft-state audio.

Audio changes according to simulated conditions:

```text
Starter / Cranking
        ↓
Engine Start
        ↓
Engine Idle
        ↓
Clutch Engagement
        ↓
Rotor Begins Turning
        ↓
Rotor Acceleration
        ↓
Governed RPM
        ↓
RPM Changes
        ↓
Engine Shutdown
        ↓
Rotor Coast-Down
        ↓
Rotor Stopped
