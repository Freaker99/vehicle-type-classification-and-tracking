## Vehicle Type Classification And Tracking

This project presents the concept and implementation of a tool for detecting and classifying objects in traffic. The goal was to develop a tool for detecting and classifying objects in traffic, which can be used to assess the level of road noise and its impact on the environment.

The study reviewed the available object detection algorithms, and then decided to implement the YOLO algorithm, while using the BDD100K image database. The main part of the project consisted of training and experiments with different model variants. Prior to training, the input data was modified to match the format accepted by the YOLO model. The model was then trained and tested on both the test set and real-world recordings, where moving objects were recorded from the position of the overpass. It was possible to evaluate the model's effectiveness in detecting objects, classifying them into different categories and tracking their movement.

Here are the pictures below showing the results of the work:

![Alt text](example_clear.png?raw=true "Car tracking")
![Alt text](example.png?raw=true "Car tracking")
