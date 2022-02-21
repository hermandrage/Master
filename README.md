# Master

This repository is a part of the the final report in TTK4900 - Engineering Cybernetics, Master’s Thesis, at the Norwegian University of Science and Technology (NTNU) at the department of Engineering Cybernetics. 

The files are modifided versions of those in the darknet version 3. The total darknet code can be found at https://pjreddie.com/darknet/yolo/ 

In order to run this system, clone the darknet code and replace detector.c and image.c with those in this repository. 
Run the code byting the following in the terminal: ./darknet detector test cfg/coco.data cfg/yolov3.cfg yolov3.weights data/"name_of_test_image" -thresh 0.1
