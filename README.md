# Image-Filter-Application
### `An Application to apply different Filters to different BMPs Images`
## Table of Contents

1) [An overview](#project)
2) [Building Image-Filter-Application](#building)
3) [Running Image-Filter-Application](#running)

## Project

This Project is Associated with Department of Integrated MCA Utkal University, Bhubaneshwar, Odisha.<br>
This is a command line Application which can be used in Terminal.<br>
We will be adding GUI to this application in Future.

## Building

To `build Image-Filter-App` Make sure To install `make` in your System and g++ compiler.<br>
`make` installation in windows -> [link](https://www.technewstoday.com/install-and-use-make-in-windows/)<br>
`make` installation in Ubuntu -> [link](https://askubuntu.com/questions/161104/how-do-i-install-make) 

To build `Image-Filter-App`, go to your project directory and open your `Terminal` and type.
```shell
make
```
Boom! You have successfully build `Image-Filter-Application`
## Running

+ Currently `Image-Filter-Application` supports `5 Filters`, these filters can be used using the following flags below.<br>
+ We have several example Images to test these Filters stored in [imgDB](https://github.com/Blaze-Stars/Image-Filter-Application/tree/main/img-db)

| Filters | Flag |
| ------- | ----- |
| GrayScale | -g |
| Blur | -b |
| Reflect | -r |
| Edge | -e |
| Sepia | -s |

To Use any of the Filters :
```shell
./filter -g img-db/<pickAnyImage> <YourOutputFileName>.bmp
```
### NOTE
```
The above example shows output for the grayscale filter, you can change the flags and image to apply any other filter 
```