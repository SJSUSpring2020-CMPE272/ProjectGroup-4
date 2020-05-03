# Group Number : 4

## Project Title : Sleep Stoppers
  -   "Time is money". We often hear this in relevance with the fast paced 21st century life. This has meant
      that we use more cab/taxi services than ever before. The cab drivers end up doing longer work/drive hours to earn
      that much extra money. This ofen puts them through a lot of stress and results in a bad sleep schedule. Accidents
      happen due to lapse of concentration which are a result of drowsiness or sleep depravity. We aim to install a sensor
      which detects the "drowsiness" level of the driver and raise an alarm if it crosses threshold.

## Abstract
  - Target Users: This will mainly be useful for companies like Lyft, Uber, etc for providing extra security to their
      employees(drivers) as well as their customers(passengers). At the same time, a normal person may also use this for 
      increased safety while he/she drives.
      
## Architecture Diagram
![alt text](https://github.com/SJSUSpring2020-CMPE272/Sleep-Stoppers/blob/master/architecture_diag_ss.png "arch diag")

![alt text](https://github.com/akshay-sjsu-173/cmpe272-project/blob/master/Report%20Stuff/How-facial-recog-works.JPG "prof flow")
## Technology Stack
   - Video Camera : This must be capable of capturing the driver's face.
   - Image Map : Python deep learning library to create an image map from the video/image stream
   - Open CV : This is required to stream video camera data to code.
   - Dlib : Dectection of Facial Features
   - Machine Learning : Keras , Tensorflow
   - Mini speaker : We will require this to trigger an alarm if "drowsiness" threshold is breached.
