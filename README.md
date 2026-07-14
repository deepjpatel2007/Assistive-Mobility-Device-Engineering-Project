# Assistive Mobility Device Engineering Project

<div align="center">

## Arduino-Powered Teddy Bear Wheelchair — **Ambearlance**

**Second Place Overall among all first-year engineering teams**  
**Fastest Device Award — 5.81-second precision speed run**

An Arduino-controlled assistive mobility prototype designed, manufactured, programmed, and tested as part of the University of Guelph's first-year engineering design program.

</div>

---

## Prototype Display Images

<p align="center">
  <img width="377" alt="Front view of the completed Ambearlance assistive mobility device" src="https://github.com/user-attachments/assets/29e82002-8b8a-46a0-9e67-ca546448d749" />
  &nbsp;&nbsp;
  <img width="437" alt="Side view of the completed Ambearlance assistive mobility device" src="https://github.com/user-attachments/assets/cfced7f6-c6ea-4767-ba45-b26d41a3644a" />
</p>

---

## Project Overview

The **Assistive Mobility Device Engineering Project**, originally completed as the **Teddy Bear Wheelchair Project**, challenged our team to design and build a small-scale wheelchair-style vehicle capable of safely transporting a teddy bear through multiple performance events.

Our final prototype, nicknamed **Ambearlance**, combined a custom three-wheel chassis, an Arduino Uno, DC motor control, a battery-powered drivetrain, and a servo-triggered launcher within an ambulance-inspired exterior. The project required us to move from an open-ended problem statement to a functional physical system through concept generation, weighted decision analysis, prototyping, subsystem integration, testing, and technical documentation.

The completed device earned **Second Place Overall across all first-year engineering teams** and received the **Fastest Device Award** after completing the precision speed course in **5.81 seconds**.

---

## Competition Achievements

| Achievement | Result |
|---|---:|
| Overall Competition Placement | **2nd Place Overall** |
| Speed Recognition | **Fastest Device Award** |
| Precision Speed Run | **5.81 seconds** |
| Speed Run Score | **30/30** |
| Eco-Trash Launch Score | **26/30** |
| Aesthetics Score | **18.30/20** |
| Safety and Stability Testing | **Passed** |

---

## Engineering Challenge

The device had to satisfy mechanical, electrical, safety, cost, and performance constraints while completing two major competition tasks:

1. **Precision Speed Run** — travel forward through a marked course, stop, reverse, and return as quickly and accurately as possible.
2. **Eco-Trash Launch** — approach a target area and use an onboard mechanism to launch a piece of trash successfully.

The design also had to remain stable, protect the model passenger, support the required subsystems, and stay within the project's dimensional and material constraints.

---

## System Design

### Mechanical System

- Custom three-wheel chassis selected through weighted decision analysis
- Structural frame designed to support the teddy bear, drivetrain, electronics, and launcher
- Wheel-and-axle arrangement optimized for speed, stability, and straight-line tracking
- Final measured prototype mass of **1,148 g**
- Centre of mass positioned near the vehicle's centre to improve balance and handling

### Electrical System

- Arduino Uno microcontroller
- DC motor and motor controller
- Battery-powered drivetrain
- Servo motor for launcher activation
- Integrated wiring and power distribution

### Embedded Control

The device used deterministic, timing-based control because the competition courses were fixed and repeatable. Separate Arduino programs were tuned for the speed and launch events.

**Speed-run sequence:**

1. Wait for the competition start delay
2. Drive forward
3. Stop
4. Reverse
5. Stop at the finish position

**Launch sequence:**

1. Drive toward the launch position at reduced power
2. Stop the drivetrain
3. Rotate the servo to release the launcher
4. Move the servo clear of the mechanism

Key Arduino connections included motor enable on pin 9, forward and reverse motor control on pins 3 and 6, and servo control on pin 8.

### Launcher System

A servo-triggered mousetrap mechanism converted stored mechanical energy into a controlled launch. The servo acted as the release mechanism, allowing the Arduino to coordinate vehicle movement and launch timing within one automated sequence.

---

## Engineering Design Process

The team followed a complete iterative design process:

1. Defined the user need, competition objectives, and engineering constraints
2. Generated multiple chassis, mobility, launcher, and aesthetic concepts
3. Evaluated alternatives using weighted decision matrices
4. Built and tested an initial prototype
5. Integrated mechanical, electrical, and software subsystems
6. Tuned motor timing, speed, alignment, and launcher activation
7. Completed safety, stability, and competition testing
8. Analyzed performance, cost, lifecycle impact, and design trade-offs
9. Documented the final design and lessons learned

---

## My Contributions

As a mechanical systems contributor, **Deep Patel** worked primarily on:

- Chassis development and structural design decisions
- Mechanical assembly and subsystem integration
- Prototype refinement and troubleshooting
- Wheel, axle, and structural testing
- Competition testing and validation
- Engineering analysis and documentation support
- Collaborative design reviews and iterative improvements

This project strengthened my ability to translate engineering requirements into a manufactured prototype while working across mechanical, electrical, and embedded-system interfaces.

---

## Key Technical Results

| Metric | Final Result |
|---|---:|
| Precision Speed Run | 5.81 s |
| Forward Program Timing | 2.25 s |
| Reverse Program Timing | 3.35 s |
| Launch Approach Timing | 3.51 s |
| Launch Motor Power Value | 100 |
| Final Measured Mass | 1,148 g |
| Final Calculated Mass | 1,113 g |
| Estimated Production Cost | $161.11 CAD |

---

## Repository Structure

```text
.
├── data/       # Performance results, decision matrices, BOM, mass and lifecycle data
├── docs/       # Design process, testing, achievements, analysis and team documentation
├── hardware/   # Mechanical, electrical, launcher and system architecture documentation
├── images/     # Prototype, development, testing and final-device photographs
├── software/   # Arduino control documentation and source code
└── README.md   # Project overview and portfolio summary
```

### Detailed Documentation

- [`docs/project-overview.md`](docs/project-overview.md) — project background and purpose
- [`docs/project-achievements.md`](docs/project-achievements.md) — competition and technical results
- [`docs/team-contributions.md`](docs/team-contributions.md) — subsystem responsibilities and individual contributions
- [`software/arduino-control-logic.md`](software/arduino-control-logic.md) — control strategy, pin assignments, and event sequences

---

## Skills Demonstrated

- Mechanical design and prototyping
- Arduino programming and embedded control
- Mechatronic system integration
- DC motor and servo control
- Design selection using weighted decision matrices
- Testing, calibration, and validation
- Root-cause troubleshooting
- Centre-of-mass and performance analysis
- Cost and lifecycle analysis
- Technical documentation
- Multidisciplinary teamwork

---

## Lessons Learned

The project demonstrated that strong competition performance depends on the interaction of every subsystem. Small changes in chassis alignment, wheel friction, mass distribution, motor timing, or launcher positioning could significantly affect the final result. Repeated testing and controlled iteration were essential to achieving the fastest speed-run time while maintaining stability and reliability.

Potential future improvements include sensor-based navigation, encoder feedback, closed-loop motor control, a rechargeable power system, a more rigid launcher assembly, improved cable management, and a lighter modular chassis.

---

## Project Information

- **Course:** ENGG*1100 — Engineering and Design I
- **Institution:** University of Guelph
- **Project Team:** Section 07, Team 08
- **Project Type:** First-Year Multidisciplinary Engineering Design Project
- **Status:** Completed

---

## Author

**Deep Patel**  
Computer Engineering Student, University of Guelph  
Mechanical Systems Contributor

---

## Acknowledgements

This project was completed collaboratively by Section 07, Team 08. The final outcome reflects the combined work of the mechanical, electronics, programming, aesthetics, testing, and documentation contributors.
