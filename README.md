# traffic-light-color-detector

**AI Traffic Light Color Detector**
Welcome to the AI Traffic Light Color Detector! This project is designed to classify the color of traffic lights from static images using advanced deep learning techniques supported by the NVIDIA Jetson Nano. This tool provides accurate color detection, making it useful for analyzing traffic light images in various applications such as traffic monitoring and autonomous vehicle systems.

Supported by the jetson-inference repository, this project features:

 - **Image-Based Detection** 
 - **High Accuracy**
 - **Googlenet and Resnet supported learning model** 

To compile this project:
1. Clone the github repository to your device
2. Make sure that all necessary applications are downloaded
3. Navigate to the jetson-inference/python/training/classification directory
4. Set the NET and DATASET variables like so: 
  a. NET = models/traffic_light
  b. DATASET = data/traffic_light
5. Run the imagenet on the chosen image in the test folder like so:
6. imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/<color-folder>/<file-name> <new-file-name>.jpg
7. Open the <new-file-name>.jpg image you created. It will be in the classification folder!
