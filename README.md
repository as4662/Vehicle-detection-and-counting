# Vehicle-detection-and-counting
We are taking frames from the video and then convert it into gray scale image and apply 
gaussian blur to remove the high frequency noises from the frames.
Cascade classifier detects objects in the video stream, so particularly, we will use the 
functions cv2.CascadeClassifier to load a .xml classifier file. It can be either a Haar or a 
LBP classifier to perform the detection.
Haar cascade uses the cascading window, and it tries to compute features in
every window and classify whether it could be an object.
Haar cascade works as a classifier. It classifies positive data points that are part
of our detected object and negative data points that are don’t contain our object.
The cascade is defined in the association with the help of the keyword cascade
and it specifies all the operations that must be cascaded to the target of the
association and mostly used while collection mapping. By default, there are no
operations cascaded to the association. It is the convenient solution provided
which saves the lines of the code needed to be added for handling sate of the
other side while doing it manually.
Surveillance cameras in roads have been broadly installed worldwide, but traffic
pictures are rarely openly released due to copyright, privacy, and security
concerns. Therefore, we collected those images from various sources, such as
those taken by the car camera and the surveillance camera and those taken by
non-monitoring cameras of multiple lighting conditions and different weather
conditions.
