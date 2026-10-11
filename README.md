# kinematics-lab

> Forward and inverse kinematics experiments in C, from 2D arms to 3D robots.

**Status:** Planned — roadmap only. No implementation has been claimed.

## Goal

Compute how a robot arm moves using your own geometric models.

## Available / suggested hardware

No hardware required to start; optional two-servo arm later.

## MVP (first demonstrable result)

1. Implement 2D two-link forward kinematics in C.
2. Draw arm joints and link segments with a lightweight viewer.
3. Implement inverse kinematics for reachable end-effector targets.

## Next milestones

- [ ] Visualize unreachable targets and alternative IK solutions.
- [ ] Add homogeneous transforms and 3D joints.
- [ ] Explore numerical Jacobian-based inverse kinematics and joint limits.

## Skills to learn

- Trigonometry and vectors
- Rotation matrices and coordinate frames
- Forward / inverse kinematics
- Jacobian, numerical optimization

## Connections to other repositories

- **cbrik:** reuse basic vector/matrix primitives where appropriate.
- **sim-engine:** reuse motion models in simulated robots.
- **robot-hand:** apply joint kinematics to a physical prototype.

## Important scope note

Kinematics determines geometry and motion without modeling forces; dynamics belongs in sim-engine.

## Definition of done for MVP

- [ ] A reproducible demo or data output is committed.
- [ ] README explains how to run it.
- [ ] At least one validation result, plot, photo or screenshot is included.

## License

License to be selected before redistributing code.
