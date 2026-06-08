# Engineering Decisions

## Overview
This document summarizes the major engineering decisions made during the Teddy Bear Wheelchair Project and explains the reasoning behind each design choice.

## Chassis Selection
The team compared three main chassis options using a weighted decision matrix:

- Option A: 4 wheels, baseplate lengthwise
- Option B: 4 wheels, baseplate widthwise
- Option C: 3 wheels, baseplate widthwise

The final selected design was Option C: a three-wheel chassis with a widthwise baseplate. It received the highest weighted score because it was the most feasible with the available parts and reduced rolling resistance and mass.

## Drivetrain Selection
The team selected a single-motor front-wheel-drive system.

### Reasons for Selection
- Reduced mass compared with a two-motor drivetrain
- Lower electrical complexity
- Lower cost
- Strong speed performance
- Better fit within the available chassis layout

### Tradeoff
The pulley was slightly offset, which created torque steer and caused some drifting under acceleration. This was handled through careful alignment and testing.

## Launcher Selection
The team selected a mousetrap-based launcher with a servo-controlled trigger.

### Reasons for Selection
- Simple mechanism
- Readily available material
- Lightweight compared with more complex launcher systems
- Easy to integrate with an Arduino-controlled release

### Tradeoff
The launcher underperformed compared with the speed system. Added rubber band tension increased launch force but introduced bending and inconsistency in the launcher arm.

## Sensor Decision
The team chose not to use sensors and instead relied on timed Arduino control.

### Reasons for Selection
- The competition course was static
- Timing could be refined through testing
- Reduced wiring and programming complexity
- Improved reliability by minimizing components

## Body and Aesthetic Selection
The final exterior was an ambulance-themed body called the “Ambearlance.”

### Reasons for Selection
- Matched the assistive mobility theme
- Provided a practical box-like shape
- Allowed the teddy bear to sit securely
- Avoided copyrighted visual themes
- Allowed easy electronics access through a hinged roof

## Material Selection
Cardboard and cardstock were used for the exterior body because they were lightweight, easy to shape, inexpensive, and practical for rapid prototyping.

## Key Engineering Tradeoffs

| Decision | Benefit | Tradeoff |
|---|---|---|
| Single motor drivetrain | Lower mass and cost | Torque steer from offset pulley |
| Three-wheel chassis | Lower weight and rolling resistance | Less stable than four-wheel alternatives |
| Timing-based control | Simpler and reliable for fixed course | Less adaptable than sensor-based control |
| Mousetrap launcher | Simple and lightweight | Less consistent launch performance |
| Cardboard body | Lightweight and easy to modify | Lower durability than rigid materials |

## Summary
The final design prioritized feasibility, speed, simplicity, and stability. The engineering decisions show a clear balance between available resources, performance goals, competition constraints, and project timeline.
