#  Minidrone Line Follower
***
![line_follower](/screenshots/line_follower.jpg)
# Video
***
https://youtube.com/shorts/nlAD_U2LvhE?feature=share

# Description
***

The main objective of this project is to leverage the camera onboard the drone for the purpose of detecting a colored line and subsequently enabling the drone to follow the identified line autonomously. The project involves the following key steps:

1. **Image Processing for Line Detection**: Utilize the drone's camera to capture images of the environment. Implement image processing techniques to identify and isolate the colored line within the captured images. This step is crucial for providing the drone with the necessary information to recognize the path it should follow.

2. **Bresenham's Line Algorithm**: Develop a line-following algorithm based on Bresenham's line algorithm. This algorithm is well-suited for accurately plotting a path between two points and is commonly used in robotics for trajectory planning. Implementing this algorithm will enable the drone to calculate the optimal path along the detected colored line. [Link](https://digitalbunker.dev/bresenhams-line-algorithm/) 

3. **Edge Detection**: Incorporate edge detection techniques to enhance the accuracy of line detection. Edge detection algorithms can highlight the boundaries of the colored line, providing additional information for the drone's navigation system.

4. **Line Following Control**: Integrate the line-following algorithm with the drone's control system. This involves adjusting the drone's orientation and movement based on the calculated path, allowing it to autonomously follow the colored line.

By combining image processing, Bresenham's line algorithm, edge detection, and control mechanisms, the project aims to create a system where the drone can actively detect and follow a colored line in its environment. This capability has applications in various fields, including automated inspection, logistics, and entertainment.

### Hardware and Software
***
1. Parrot Mambo
2. Matlab and Simulink (Package: https://www.mathworks.com/matlabcentral/fileexchange/63318-simulink-support-package-for-parrot-minidrones)
