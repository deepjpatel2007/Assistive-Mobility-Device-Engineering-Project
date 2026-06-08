# Arduino Control Logic

## Source
The Arduino code was extracted from Engineering Analysis C of the final design report. The report includes two testing-day programs:

- Speedrun test code
- Launch test code

## Control Approach
The TBWC used timing-based control instead of sensors. This was chosen because the course was fixed and repeatable, allowing the team to tune movement timing through testing.

## Pin Assignments

| Signal | Arduino Pin | Purpose |
|---|---:|---|
| enA | 9 | Motor enable |
| Forw | 3 | Motor controller forward input |
| Back | 6 | Motor controller backward input |
| ServoPin | 8 | Servo control for launcher release |

## Speedrun Program Summary

The speedrun program followed this sequence:

1. Wait 10 seconds.
2. Drive forward.
3. Stop.
4. Drive backward.
5. Stop.

Reported timing values:

- Forward motion: 2.25 seconds
- Reverse motion: 3.35 seconds
- Stop delay: 0.5 seconds

## Launch Program Summary

The launcher program followed this sequence:

1. Wait 10 seconds.
2. Drive forward at reduced power.
3. Stop.
4. Move servo to trigger the launcher.
5. Move servo out of the mousetrap path.

Reported timing values:

- Forward motion: 3.51 seconds
- Servo trigger delay: 2 seconds
- Motor power value: 100

## Engineering Notes

The Arduino system demonstrated deterministic embedded control. The speedrun program prioritized fast traversal and return, while the launch program reduced motor power for controlled approach before activating the servo-controlled mousetrap trigger.

## Source Code Files

The original report contains two code listings:

- `speedrun_test.ino`
- `launch_test.ino`

These should be stored under `software/source-code/`.
