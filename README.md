# traffic-light-color-detector

**AI Traffic Light Color Classifier**

Welcome to the AI Traffic Light Color Detector! This project is designed to classify the color of traffic lights from static images using advanced deep learning techniques supported by the NVIDIA Jetson Nano. This tool provides accurate color classification, making it useful for analyzing traffic light images in various applications such as traffic monitoring and autonomous vehicle systems.


**Supported by the jetson-inference repository, this project features:**

-Image-Based Classification
-High Accuracy
-Googlenet and Resnet supported learning model


**Algorithm**
This project uses a Recurrent Neural Network (RNN), which is specialized for classifying images and other grid-like data types. A RNN is designed to process sequences of data, and it can be specialized to work with sequences of images. By remembering information from one image to the next, it can recognize patterns or changes over time. The re-trained model was trained on images of red, yellow, or green lights. The computer recognizes similarities between similar lights and then classifies accordingly.


**To compile this project:**
1. Clone the github repository to your device
2. Make sure that all necessary applications are downloaded
3. Navigate to the jetson-inference/python/training/classification directory
4. Type 
```
python3 traffic_light_driver.py
```
5. Complete the inputs 
 a. The first input should be one of these [red,green,yellow]
 b. The second should be a .jpg file (check the test files and choose one) 
 c. The third should also be a .jpg file (with the name of your choosing)
6. Open the .jpg image you created. It will be in the classification folder!

