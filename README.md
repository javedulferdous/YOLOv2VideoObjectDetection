#Step2 - Download the Darkflow repo
1. https://github.com/thtrieu/darkflow
2. extract the files somewhere locally

#Step3 - Build the library
1. open an cmd window and type
2. python setup.py build_ext --inplace  OR  pip install -e .

#Step 4 - Download a weights file
1. Download the YOLOv2 608x608 weights file here (https://pjreddie.com/darknet/yolov2/)
2. NOTE: there are other weights files you can try if you like
3. create a bin folder within the darkflow-master folder
4. put the weights file in the bin folder

#Step 5 - Processing a video file
1. move the video file into the darkflow-master
2. from there, open a cmd window
3. Run "'YOLOdetect.py'"
videofile.mp4 is the name of your video.

NOTE: if you do not have the GPU version of tensorflow, leave off the --gpu 1.0

--saveVideo indicates to save a name video file, which has the boxes around objects
