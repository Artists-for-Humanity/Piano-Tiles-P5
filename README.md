# Pose-Based Interactive Projects

Two small interactive experiments built with **p5.js** and **ml5.js BodyPose**.

## Projects

### 1. Piano Tiles
A rhythm-style game where falling tiles are triggered by stepping into lanes.
- Tracks feet/ankles using pose detection
- 3 lanes mapped across the screen
- Step in the correct lane to hit notes
- Score / miss system + start gesture

### 2. Scrapbook Body
A visual experiment that draws body parts as shapes based on pose data.
- Tracks key joints (shoulders, hips, limbs, etc.)
- Reconstructs the body using simple geometry
- Designed to be replaced with collage-style cutouts

## How to Run

1. Open either folder (`piano-tile` or `scrapbook`)
2. Open the folder in VS Code
3. Use the **Live Server** extension (“Go Live”)

## Tech

- p5.js
- ml5.js (BodyPose / BlazePose)

## Notes

- Uses webcam input
- Pose detection runs in real-time in the browser
- Interactions are based on tracked keypoints (feet, joints, etc.)
