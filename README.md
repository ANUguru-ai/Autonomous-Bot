# Autonomous Bot using CNN
CNN stands for Convolutional Nueral Network which we developed using Machine learning techniques. YOLO is the frame work used to develop the CNN . Using this model we can identify each room number in the floor using object_detection techniques. This model can be testined in real-time or using pre-recorded video. Here we use supervised machine learning approach where we prepare the dataset manually and train the model using Yolov3. We got excellent test accuraqcy ranging from 80 to 90 % in a 1000 training steps.

Using this model we simulate a video frame showing rooms in a hotel frame which can be seein in the output folder inside YOLO_object_detection_model. We tested our video using yolo_video.py and images using yolo.py . The dataset for training the model is available as Dataset.zip . You can test our model by running the python file for that you require  yolov3.weights file which is available in the link: https://drive.google.com/open?id=1-1hOc9NTJWcVFpxZeviUGOgpPtcRFft- download the weight file using the link and copy to the yolo-coco folder.

We aslo develop a GPS tracking app which can track multiple loaction by activating the GPS. The app is available in the GPS traking floder.Using this app we can enable traking of different rooms in each floor.
