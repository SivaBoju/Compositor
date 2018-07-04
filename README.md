#  Compositor Test

## Requirements
In the app's main view play source.mp4 composited with with still.png and mask.png such that the movie's motion blends with still.png relative the alpha channel of mask.png. That is, wherever mask.png is totally transparent, show still.png; wherever it's totally opaque, show the frame from source.mp4; wherever it's partially transparent, show a blend proportional to the alpha value.

## Guidelines
- use what ever frameworks you deem necessary to satisfy the requirements 
- don't be afraid to ask questions
- take your time to do it well
- show your work (avoid monolithic commits)
- open a pull request when you are ready to have it reviewed

## Stretch Goals 
1. Loop the video playback
2. Add a button to toggle bounce or repeat loop
3. Add a button that renders the composition to a video and saves the video to the Photo Library 

