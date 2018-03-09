# Homework Color Transformations

## Application: 3.0

* The application doesn't allow to select the image path for loading it. You define a default image, if the application runs in other pc, the image does not load.
* Is a good practice to separate the model of the view, you are mixing all in one class
* The application doesn't allow to select the image path for saving it

## Color Transformation Algorithms: 0.0

### RGB to HSV

* This block of code have an error:

```
double rPrima = red/255;
double gPrima = green/255;
double bPrima = blue/255;
```
 
("channel"/255) is an integer division and the result is 0.0 therefore there is a loss in decimal precision. The correct way is ("channel"/255.0f) or ((double)"channel"/255)

* This block of code have an error:

```
if(rPrima > gPrima){
    if(rPrima > bPrima)
        cMax = rPrima;
    else
        cMax = bPrima;
}
else if(gPrima > bPrima){
    cMax = gPrima;
}
else
    cMax = bPrima;
```

Not evaluate if __bPrima__ is greater than __rPrima__ when __rPrima__ is greather than __gPrima__

### RGB to HSL

* Similar to RGB to HSV

# Grade: 1.5