# cs534Final

## How to run our implementation with Homework 4


## Optional 0 step- run sift program of original panorama
  1. Install the VLFEATROOT step, and place the four chosen photos (with one bad exposure picture) into the input_images folder. Run main. This will create a poor panorama that we will be updating with our implementation to match the exposure.

## 1st step: Run ComputeHist Function (Our Implementation)
  1. Have four photos uploaded into the directory CS-534Final/MATLAB/
  (This part of the directory will include things such as an empty folder "input_images", blending.m, main.m, etc. just so you know your in the right spot in the directory), and place the 4 photos with the poor-exposure picture in the current directory, labeled 1-4.JPG.
  2. Run computeHist -> this will find the outlying photo with the most different exposure and match the histogram to a reference photo of better lighting. Both of these photos will be printed, and the new picture will replace the older picture, and all four photos will be placed in the 'input_images' folder, under the names 1-4.JPG.
  
## 2nd step: Run main with new images
1. Run main and the new panorama will be placed in the current directory under the name "new_panorama.JPG"


## Notes
  1. 4 photos that make a panorama have already been provided in the correct directory- run computeHist and then immidiately run main to see a quick result of the updated panorama.
  2. To see the original panorama (with 1 picture at bad exposure) copy the 4 original photos in the current directory into the input_images folder and run main.


 
