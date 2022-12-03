# DIP_Final
This is the final project for Digital Image Processing class.  
Our task is to complete "Seamless Focal-Stack Refocusing".  

./main.py -- Main program in this project. Use command "python main.py" to run it.  
./images/ -- 1.jpg ~ 5.jpg are input images and output1.jpg ~ output5.jpg are output images.  

Strategy : Resize the image and find the min_dist(F, F_r), where F is the origin image and F_r is the image after resizing.   

Issues to slove:
  1. Time Complexity is too higher.  
  2. Refocusing result can be better.  
  
Things to do:
  1. Ternary Search for function adjust(img1, img2).  
  2. Set the unit of function adjust(img1, img2) from 0.01 to 0.001.  
  
Things can try:
  1.  Do some image preprocessing, like high pass filter, edge detection, or debluring, to find the more accurate min picture.   
