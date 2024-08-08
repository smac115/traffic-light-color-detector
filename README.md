# traffic-light-color-detector

**AI Traffic Light Color Classifier**

Welcome to the AI Traffic Light Color Classifier! This project is designed to classify the color of traffic lights from static images using advanced deep learning techniques supported by the NVIDIA Jetson Nano. This tool provides accurate color detection, making it useful for analyzing traffic light images in various applications such as traffic monitoring and autonomous vehicle systems.

Supported by the jetson-inference repository, this project features:

 - **Image-Based Classification** 
 - **High Accuracy**
 - **Googlenet and Resnet supported learning model** 

To compile this project:
1. Clone the github repository to your device
2. Make sure that all necessary applications are downloaded
3. Navigate to the jetson-inference/python/training/classification directory
4. Type "python3 traffic_light_driver.py"
5. Complete the inputs
    a. The first input should be one of these [red,green,yellow]
    b. The second should be a .jpg file (check the test files and choose one)
    c. The third should also be a .jpg file (with the name of your choosing)
6. Open the <new-file-name>.jpg image you created. It will be in the classification folder!
