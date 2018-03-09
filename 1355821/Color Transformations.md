# Homework Color Transformations

## Application: 

* The application does not allow to select the path to load and save image (You should use a QFileDialog). The application loads a default path, if the application is run on another pc,  it will not work
* The application should show all channels of color transformations in separate panels. The user can not see the transformations
* Combo box in the application doesn't do anything
* To save the image, you use a default path. If the folder "ProcessingImages" doesn't exist, the image will not be saved 
* You must to improve the code presentation (Many code blocks commented) 

## Color Transformation Algorithms: 

### RGB to HSV

* For calculating __varR__, __varG__ and __varB__, you use a integer division operation, if you calculate float variable on this way, you can lose decimal precision
*  In this line, you pass the image variable by value. The changes will not be performed in temp variable. 
    ```
    convert->convertRgbToHsv(temp);
    convert->writeImage(temp, "convertHSV.jpg");
    ```   

### RGB to HSL

* For calculating __varR__, __varG__ and __varB__, you use a integer division operation, if you calculate float variable on this way, you can lose decimal precision
*  In this line, you pass the image variable by value. The changes will not be performed in temp variable. 
    ```
    convert->convertRgbToHsl(temp);
    convert->writeImage(temp, "convertHSL.jpg");
    ```   

# Grade: 