# Homework Color Transformations

## Application: 4.0

* Please, you must use serious file names

## Color Transformation Algorithms: 4.0

### RGB to HSV

* This block of code have an error:

```
 else if (G == maxValue) {
    H = ((1/3) + deltaR - deltaB);
}
else if (B == maxValue) {
    H = ((2/3) + deltaG - deltaR);
```
 
(1/3) is an integer division and the result is 0.0 therefore there is a loss in decimal precision. The correct way is (1/3.0f) or (1.0f/3)

### RGB to HSL

* Similar to RGB to HSV

# Grade: 4.0