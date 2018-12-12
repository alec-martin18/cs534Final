# cs534Final

## How to run our implementation with Homework 4


## Optional 0 step- run sift program 
  1. Install the VLFEATROOT step, and place the four chosen photos (with one bad exposure picture) into the input_images folder. Run main. This will create a poor panorama that we will be updating with our implementation to match the exposure.

## 1st step: Run ComputeHist Function (Our Implementation)
  1. Have four photos uploaded into the directory CS-534Final/MATLAB/ (DO NOT PUT THESE PHOTOS INTO THE INPUT IMAGES YET)
  (This part of the directory will include things such as an empty folder "input_images", blending.m, main.m, etc. just so you know your in the right spot in the directory), and place the 4 photos with the poor-exposure picture in the current directory, labeled 1-4.JPG.
  2. Run computeHist -> this will find the outlying photo with the most different exposure and match the histogram to a reference photo of better lighting. Both of these photos will be printed, and the new image will be saved in the current directory as "new_image.JPG".
  
## 2nd step: Hard-coding to create new panorama
  1. Whichever photo was updated (1-4.JPG) deleted/remove from the program. Rename "new_image.JPG" to #.JPG ( the number of what was updated). Place these 1-4.JPG files into the input images folder. Run main and the panorama printed will be the updated panorama with matching exposure.
