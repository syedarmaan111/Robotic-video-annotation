# Robotic Video Annotation

This project demonstrates video annotation of robotic manipulation tasks using CVAT.

## Objective

The goal was to identify robotic actions and annotate them using action-specific bounding-box tracks.

## Labels Used

- AGITATION
- REACH
- GRASP
- LIFT
- TRANSPORT
- PLACE
- RELEASE
- RETRACT

## Annotation Method

Bounding boxes were drawn around the active robotic gripper/end-effector.

Each action was annotated using a separate track.

Keyframes and interpolation were used to keep bounding boxes consistent across frames.

## Tools

- CVAT
- Video Annotation
- Bounding Box Tracking
- Keyframe Interpolation
- Annotation Quality Review

## Repository Contents

- `annotations/` — exported CVAT XML annotation files
- `screenshots/` — examples of annotated frames
- `demo/` — short annotated video demonstrations
- `annotation_guidelines.md` — labeling rules used in the project

## Quality Review

Annotations were manually reviewed for:

- correct action labels
- bounding-box consistency
- action transition frames
- interpolation accuracy
- track continuity
