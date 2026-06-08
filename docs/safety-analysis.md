# Safety Analysis

## Overview
Safety was considered throughout the design of the Teddy Bear Wheelchair Project. The final design protected the teddy bear passenger, separated moving components from wiring, and maintained stability during testing.

## Safety Requirements

The final vehicle successfully met the following safety requirements:

- Static tipping test in four directions: Pass
- Upside-down test: Pass
- Continuous line-of-sight test at 240 degrees: Pass
- Teddy bear head positioned higher than torso: Pass
- Teddy bear remained secure during operation
- Vehicle did not tip during speed or launch events

## Passenger Safety

The teddy bear was positioned in an elevated recessed seat on the ambulance body. The seating area was reinforced with additional cardboard layers and staples to improve support.

Key safety features:

- Recessed seating area
- Reinforced passenger support
- Open top carriage design
- Clear positioning away from launcher movement
- Stable seating height

## Electrical Safety

The electronics were kept accessible through the hinged roof design. This allowed the team to troubleshoot and switch Arduino programs without removing the entire body shell.

Electrical safety considerations:

- Accessible electronics compartment
- Organized wiring
- Separation between wiring and moving launcher parts
- Secure mounting of Arduino, battery pack, and breadboard

## Mechanical Safety

The launcher was positioned so that it extended through the side of the ambulance body and stayed clear of the teddy bear. The chassis was kept rigid and compact to reduce loose components and improve predictable motion.

Mechanical safety considerations:

- Launcher positioned away from passenger area
- Front bumper for small impacts
- Stable wheelbase configuration
- Reduced vibration through secure mounting
- No major loose components during final operation

## Risk Areas Identified

| Risk | Cause | Mitigation |
|---|---|---|
| Tipping | Three-wheel chassis geometry | Centre of mass kept near vehicle center |
| Electrical disconnection | Movement and vibration | Components securely mounted |
| Launcher interference | Servo and hook alignment | Servo repositioned lower to reduce misfires |
| Passenger instability | Acceleration and speed bump | Recessed and reinforced teddy bear seat |
| Projectile instability | Projectile mount movement | Projectile remained secured during operation |

## Future Safety Improvements

- Add protective covers around moving launcher components
- Improve cable routing with clips or channels
- Add a dedicated battery enclosure
- Use a more rigid projectile holder
- Add formal pre-run safety checklist

## Summary
The final design successfully passed all required safety tests while maintaining strong speed performance. The main safety improvements for future iterations would focus on launcher guarding, wire management, and stronger component enclosures.
