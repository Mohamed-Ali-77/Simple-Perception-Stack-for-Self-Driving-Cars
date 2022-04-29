# Simple-Perception-Stack-for-Self-Driving-Cars
In this project we're going to create a simple perception stack for SDCs. We're only focusing on video streams from cameras for simplicity. We’re mainly going to be analyzing the road ahead, detecting the lane lines, detecting other cars/agents on the road, and estimating some useful information that may help other SDCs stacks. The project is split into two phases.

Phase 1 - Lane line detection:
* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

## List of Contributors
| Names    |      Code     |    Github  |
|----------|:-------------:|:-------------|
| Mohamed Ali Ahmed Bakr |  1801534 | [Mohamed-Ali-77](https://github.com/Mohamed-Ali-77)     |
| Mo'men waleed mamdouh abdelaziz|   1802418  | [Moamenhimself](https://github.com/Moamenhimself)   |

# Check the preformance of the code 

## Output video
https://youtu.be/J0U0mxnsTcM
## Stacked video
https://youtu.be/bV-iakyRaTY
