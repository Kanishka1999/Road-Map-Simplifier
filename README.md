# Road-Map-Simplifier

## Problem Statement: 
The traffic on the roads has been increasing day by day despite the signals and deployment of traffic personnel. It has hence become a necessity to find a technologically smart solution to reduce vehicular traffic. As we all know, currently CCTC cameras have been installed at most of the major junctions which help in surveillance and finding offenders as of now. These cameras can further be put to better use to reduce traffic. Vehicles in each lane can be counted and depending on the count, the green time of each and every lane could be adjusted dynamically. Vehicles could be detected with the help of YOLO or any other object detection mechanism.

## Approach to implement the Project:
The idea is to implement the project in a module wise manner. The first and the major module would be the vehicles detection part itself. As we know that, in India, the view from the camera would contain many disturbances, hence these disturbances need to filtered out by selecting a Region of Interest (ROI) for each lane and it is only in this ROI that the count must be taken. For the sake of development and testing, a sample recorded video grab of an actual road may be used. 
Once this is done, the next major module is to design your own algorithm in python which smartly allocates green time dynamically to each lane on the basis of the captured count at that instant. The subsequent module would be to integrate the object detection code with our algorithm and test the proper working of the same. Then, in the final module, proper system with a user interactive front-end could be created for better usability of the application developed.

## Modular Segmentation of the Project:
Module 1- Vehicles Detection (Completed)
Module 2- Algorithm to allocate green time (Ongoing)
Module 3- Integration of module 1 and module 2
Module 4- System Development 
