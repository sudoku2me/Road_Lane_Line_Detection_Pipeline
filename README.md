# Road_Lane_Line_Detection_Pipeline
This project contains code that is from this source: https://github.com/georgesung/road_lane_line_detection.
The code used is transformed into multiple steps to illustrate each step of the road lane line detection pipeline with the outputs.
Each step saves the image without the axis such that it can be included in the report for comparisons between each transformation.
The final transformation resizes the dimensions of the image Transformation6.jpg such that the addWeighted function of cv2 can be called.
This is because the image dimensions of solidYellowCurve.jpg and Transformation6.jpg are not of the same size and the function requires parameters including images of the same size.
The output of each transformation and the initial and final images are also included in this project.
