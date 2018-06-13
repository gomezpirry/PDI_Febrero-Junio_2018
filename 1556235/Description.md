# Homework Representation and Description

* As recommendation, the process of read file in this line (cv2.imread("img.jpg")) is expensive because is an I/O operation. The program should request the information to hard drive. OpenCV have a copy operation (numpy copy), and this copy is more efficient because the data is in memory
* As recommendation, you can reduce the number of for loop, using only one for can perform all process. Remember, for loop evaluate a stop condition, with unnecessary for, you are increasing the computational complexity of the program
* For each metric, don't show perimeter and diameter
* Don't deal with the elements that consist of noise of the image. The program recognizes the light particles as flocs
* If the image represents a 2micrometer by pixel, you must converter the results
* If the particles are given in micrometers (micrometers/pixel), you must to specify the measurement units in the result. Also, you should indicate to what corresponds each value

### Grade: 3.5