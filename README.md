# Assistive Mobility Device Engineering Project

## Arduino-Powered Teddy Bear Wheelchair / “Ambearlance”

This repository documents the **Teddy Bear Wheelchair Project**, an ENGG*1100 engineering design project focused on building an Arduino-powered miniature assistive mobility vehicle. The final prototype, nicknamed the **Ambearlance**, combined mechanical design, electronics, embedded systems, cost analysis, safety validation, and performance testing into one complete engineering project.

The project was completed by **Section 07, Team 08** as a multidisciplinary first-year engineering design challenge.

---

## Final Design Images

> Add two final product images below after uploading them to the `images/` folder.

<p align="center">
  <img src="images/final-design-image-1.jpg" alt="Final Ambearlance Design Image 1" width="45%">
  <img src="images/final-design-image-2.jpg" alt="Final Ambearlance Design Image 2" width="45%">
</p>

---

## Project Summary

The goal of this project was to design, build, and test a small-scale wheelchair-style mobility device capable of transporting a teddy bear safely while completing competition-based performance tasks. The final design used an Arduino-controlled drive system, a mechanical chassis, an integrated mousetrap launcher, and an ambulance-inspired exterior shell.

The project emphasized:

- Mechanical design and chassis development
- Arduino-based embedded control
- Electrical system integration
- Launcher mechanism design
- Safety and stability validation
- Cost and lifecycle analysis
- Engineering documentation and teamwork

---

## Key Results

| Category | Result |
|---|---:|
| Precision Speed Run Time | 5.81 seconds |
| Precision Speed Run Score | 30/30 |
| Eco-Trash Launch Score | 26/30 |
| Final Measured Mass | 1148 g |
| Calculated Mass | 1113 g |
| Centre of Mass | (12.96, 6.42, 5.13) cm |
| Aesthetics Score | 18.30/20 |
| Static Tipping Test | Pass |
| Upside-Down Test | Pass |
| Line-of-Sight Safety Test | Pass |
| Production Cost | $161.11 CAD |

---

## Technical Overview

The final vehicle was built as an integrated mechatronics system with four major subsystems.

### Mechanical System

The mechanical design used a three-wheel chassis with a widthwise baseplate configuration. This layout was selected through a weighted decision matrix because it offered the best balance of feasibility, reduced rolling resistance, and low mass.

Key mechanical features:

- Three-wheel chassis
- Front-wheel-drive system
- Single DC motor drivetrain
- Pulley-based power transmission
- Meccano structural frame
- Cardboard ambulance-style shell
- Recessed teddy bear seating area

### Electrical System

The electrical system used an Arduino Uno, motor controller, DC motor, breadboard, wiring, passive components, and an AA battery power system.

Key electrical components:

- Arduino Uno
- L298N motor controller
- DC motor
- Breadboard
- AA battery holder
- 22 AWG wiring
- Diodes, resistors, and capacitors

### Software System

The vehicle used deterministic Arduino timing logic instead of sensors. This was chosen because the competition course was fixed and repeatable, allowing the team to tune timing values through testing.

Control functions included:

- Forward motion
- Reverse motion
- Timed stopping
- Launcher triggering
- Servo-based release control

### Launcher System

The Eco-Trash Launch subsystem used a mousetrap launcher with a servo-controlled trigger. The launcher was mounted so that it extended from the side of the ambulance body, keeping it clear of the teddy bear passenger and electronics.

---

## Engineering Decision Process

The team used weighted decision matrices to compare design options. The final chassis design was selected based on weight, speed, reliability, stability, and feasibility.

### Chassis Decision

The selected option was:

> **Three wheels with a widthwise baseplate**

This option scored the highest overall because it reduced weight and rolling resistance while remaining feasible with the available parts.

### Aesthetic Decision

The final ambulance theme was selected because it:

- Matched the assistive mobility concept
- Provided a practical box-like body shape
- Allowed the teddy bear to sit securely
- Avoided copyrighted themes
- Provided easy electronics access through a hinged roof

---

## Testing and Validation

The final design was tested across several performance and safety categories.

### Performance Testing

The vehicle successfully completed the speed run with a final time of **5.81 seconds** and earned a full **30/30** score.

### Launcher Testing

The launcher achieved **26/30** points in the Eco-Trash Launch event. The launcher functioned successfully, although the team identified future improvements related to projectile consistency, launcher arm stiffness, and servo clearance.

### Safety Testing

The vehicle passed all required safety tests, including:

- Static tipping test in four directions
- Upside-down test
- Continuous 240-degree line-of-sight test
- Teddy bear head-position requirement
- Passenger security during operation

---

## Repository Structure

```text
.
├── README.md
├── docs/
│   ├── project-overview.md
│   ├── problem-statement.md
│   ├── design-process.md
│   ├── engineering-decisions.md
│   ├── testing-validation.md
│   ├── performance-analysis.md
│   ├── safety-analysis.md
│   ├── lifecycle-analysis.md
│   ├── lessons-learned.md
│   ├── team-contributions.md
│   └── project-achievements.md
│
├── data/
│   ├── bill_of_materials.csv
│   ├── performance_results.csv
│   ├── decision_matrix_chassis.csv
│   ├── decision_matrix_aesthetics.csv
│   ├── centre_of_mass_data.csv
│   └── lifecycle_metrics.csv
│
├── hardware/
│   ├── system-architecture.md
│   ├── mechanical-design.md
│   ├── electrical-system.md
│   └── launcher-system.md
│
├── software/
│   └── arduino-control-logic.md
│
└── images/
```

---

## Documentation Guide

| File | Purpose |
|---|---|
| [`docs/project-overview.md`](docs/project-overview.md) | High-level project summary |
| [`docs/design-process.md`](docs/design-process.md) | Engineering design process and design evolution |
| [`docs/engineering-decisions.md`](docs/engineering-decisions.md) | Major tradeoffs and design reasoning |
| [`docs/testing-validation.md`](docs/testing-validation.md) | Testing methods and validation results |
| [`docs/performance-analysis.md`](docs/performance-analysis.md) | Speed, launch, mass, and aesthetics results |
| [`docs/safety-analysis.md`](docs/safety-analysis.md) | Safety requirements, risks, and mitigations |
| [`docs/lifecycle-analysis.md`](docs/lifecycle-analysis.md) | Environmental impact and sustainability notes |
| [`docs/team-contributions.md`](docs/team-contributions.md) | Team roles and individual contributions |
| [`hardware/mechanical-design.md`](hardware/mechanical-design.md) | Chassis, drivetrain, and frame design |
| [`hardware/electrical-system.md`](hardware/electrical-system.md) | Arduino, motor controller, battery, and wiring system |
| [`hardware/launcher-system.md`](hardware/launcher-system.md) | Mousetrap launcher and servo release mechanism |
| [`software/arduino-control-logic.md`](software/arduino-control-logic.md) | Arduino timing logic and control sequence |

---

## Data Files

| File | Description |
|---|---|
| [`data/bill_of_materials.csv`](data/bill_of_materials.csv) | Production BOM and cost breakdown |
| [`data/performance_results.csv`](data/performance_results.csv) | Competition and validation metrics |
| [`data/decision_matrix_chassis.csv`](data/decision_matrix_chassis.csv) | Chassis weighted decision matrix |
| [`data/decision_matrix_aesthetics.csv`](data/decision_matrix_aesthetics.csv) | Aesthetic concept decision matrix |
| [`data/centre_of_mass_data.csv`](data/centre_of_mass_data.csv) | Centre of mass and mass comparison data |
| [`data/lifecycle_metrics.csv`](data/lifecycle_metrics.csv) | Environmental lifecycle metrics |

---

## Skills Demonstrated

- Mechanical design
- Mechatronics
- Arduino programming
- Embedded systems
- Circuit integration
- Motor control
- Servo control
- Engineering decision matrices
- Testing and validation
- Safety analysis
- Cost analysis
- Lifecycle analysis
- Technical documentation
- Team-based engineering design

---

## Challenges and Improvements

### Main Challenges

- Managing torque steer caused by offset pulley placement
- Keeping mass below the project limit
- Improving launcher consistency
- Avoiding interference between the servo and release mechanism
- Balancing speed, stability, cost, and feasibility

### Future Improvements

- Improve drivetrain symmetry to reduce drifting
- Add sensors or wheel encoders for closed-loop control
- Use a rechargeable battery system
- Reinforce the launcher arm and trigger mechanism
- Improve projectile holder stability
- Add cleaner cable routing and protective electronics housing
- Create a more durable body shell using lightweight rigid materials

---

## Project Status

This project is complete as an academic engineering prototype and has been reorganized as a professional portfolio repository. Original school deliverables should remain preserved, while the extracted documentation and datasets summarize the project in a cleaner engineering format.

---

## Author

**Deep Patel**  
Computer Engineering Student  
Mechanical Systems Contributor — Teddy Bear Wheelchair Project

---

## Acknowledgements

This project was completed as part of **ENGG*1100** by Section 07, Team 08. The team included contributors across mechanical design, electronics, aesthetics, testing, and documentation.
