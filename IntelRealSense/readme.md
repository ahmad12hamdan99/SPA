# Lab Assignment - Detect Object 3D coordinates and dimensions with respect to World Coordinate System
 Full code and documentation is available on [GitHub](https://github.com/ahmad12hamdan99/SPA/tree/main/IntelRealSense)

## Requirements: 
### Python Version
This code requires Python 3.6 or newer versions

### Packages: 
1. OpenCV
2. LibRealSense
3. Numpy

Get these packages using pip: pip install opencv-python numpy pyrealsense2


## Aim
This code demonstrates the ability to solve a simple task such as dimension calculation of a box using one realsense camera.


## Workflow
1. Place the calibration chessboard object into the field of view the realsense camera. Update the chessboard parameters in the script in case a different size is chosen.                                 
2. Start the program.                                                                                                 
3. Allow calibration to occur and place the desired object on the chessboard when the program asks for it. Make sure that the object to be measured is not bigger than the calibration chessboard in length and width.            
4. The length, width and height of the bounding box of the object is then displayed in millimeters.    


## Example Output
Once the calibration is done and the target object's dimensions are calculated, the application will open a window displaying a color image along with an overlay of the calculated bounding box.
![alt text](https://github.com/ahmad12hamdan99/SPA/blob/main/IntelRealSense/detected.png)

[Video Output](https://github.com/ahmad12hamdan99/SPA/blob/main/IntelRealSense/video.mp4)

## References
[InteleRealsense Library](https://github.com/IntelRealSense/librealsense.git)

