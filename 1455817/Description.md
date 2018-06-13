# Homework Representation and Description

* Don't deal with the elements that consist of noise of the image. The program recognizes the light particles as flocs
* You use a area restriction (if area > 150 and area < 20000:) to avoid the capture of noise as particle. This can be incorrect if the image contains flocs of small sizes
* Use cv2.RETR_EXTERNAL instead of cv2.RETR_TREE for cv2.findContours function. With this argument, the function don't take in account the internal hole in the particles
* If the particles are given in micrometers (micrometers/pixel), you must to specify the measurement units in the result
* Don't show the results of the descriptors in a table

### Grade: 3.0