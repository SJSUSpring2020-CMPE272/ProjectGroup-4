# ProjectGroup-4

# APPROVED
1.  Intelligent drowsy driver detection:
  - Description:  "Time is money". We often hear this in relevance with the fast paced 21st century life. This has meant
      that we use more cab/taxi services than ever before. The cab drivers end up doing longer work/drive hours to earn
      that much extra money. This ofen puts them through a lot of stress and results in a bad sleep schedule. Accidents
      happen due to lapse of concentration which are a result of drowsiness or sleep depravity. We aim to install a sensor
      which detects the "drowsiness" level of the driver and raise an alarm if it crosses threshold.
  - Target Users: This will mainly be useful for companies like Lyft, Uber, etc for providing extra security to their
      employees(drivers) as well as their customers(passengers). At the same time, a normal person may also use this for 
      increased safety while he/she drives.
  - Implementation/Technology Stack: We need to use the following technology stack to accomplish this project -
      - Video Camera : This must be capable of capturing the driver's face.
      - Image Map : Python deep learning library to create an image map from the video/image stream
      - Open CV : This is required to stream video camera data to code.
      - Machine Learning : Python's Keras library to train the machine.
      - Mini speaker : We will require this to trigger an alarm if "drowsiness" threshold is breached.
