##**LANE DETECTION FOR AUTOMATED CARS USING COMPUTER VISION**

In this project we used a image and named it road.jpg

image shown below


![main](https://user-images.githubusercontent.com/67842238/103204102-8f7a4900-491c-11eb-9dca-2ec57922320e.PNG)



we read the image using OpenCV and converted the RGB (width,heigth,3) to GRAY
using OPENCV function

cv2.cvtColor()

on which we ussed ***Canny Edge detection method***
and the output is shown below


![edge](https://user-images.githubusercontent.com/67842238/103203526-1b8b7100-491b-11eb-99d7-a460412ba8d7.PNG)


we also used Gaussian blur to check if it gives us better results.


After this we found our ***REGION OF INTEREST***

and found our lane as region of interest


![roi](https://user-images.githubusercontent.com/67842238/103204011-6063d780-491c-11eb-9451-edd671064ebb.PNG)


and we applied HOUGH LINES DETECTION to find desired output .


![lane](https://user-images.githubusercontent.com/67842238/103204073-82f5f080-491c-11eb-8c14-4c0b75831123.PNG)

Hence we used OPENCV to detect lanes in road for autonomous car.

