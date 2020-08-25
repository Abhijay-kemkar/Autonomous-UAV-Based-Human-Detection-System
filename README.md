# Autonomous-UAV-Based-Human-Detection-System

Target search in an obstacle-filled environment is a practically significant challenge in the field of robotics that significantly impacts society. The wide range of applications includes searching for victims in a search and rescue operation, patrolling borders for the military and navy, detecting weeds in precision agriculture, etc. The development of navigation, tracking, and object detection using unmanned aerial vehicles (UAV) has evolved more rapidly throughout these years. This technology's utilization is diverged throughout the area, including for search and rescue in small and large spaces. The UAV has a primary camera mounted, for human body detection developed and integrated into a fully autonomous system for search and rescue. It produces an optimal framed horizon plan in the form of a 3D minimum-snap trajectory that minimizes flight time by rendering maximum area coverage, without any collision with the obstacles. The first stage is designing a PID controller to perform the UAVs stable flying to navigate in a cluttered environment. The second step is to integrate the primary camera's computer on the UAV with the OpenCV library installed with the HOG, Haar Cascades and Convolutional Neural Network Algorithms to detect humans. Finally, the project completes with mapping an effective path without any object collision, via successfully detecting all humans in the field of view. The simulation was done using Gazebo and Rviz.
