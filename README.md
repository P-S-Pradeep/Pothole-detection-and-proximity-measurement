## POTHOLE DETECTION AND PROXIMITY MEASUREMENT
Potholes pose significant risks to drivers worldwide, leading to accidents, vehicle damage, and road hazards. Our project addresses this issue by developing a real-time pothole detection and proximity measurement system. Leveraging computer vision technology and the YOLOv8 model, our system accurately identifies potholes on roads from video streams.
By providing drivers with timely warnings about potholes and their proximity, our project aims to enhance road safety and prevent potential accidents and damages.


## About
Road safety remains a paramount concern for drivers worldwide, with potholes posing significant risks to vehicle integrity and passenger safety. In this project, we present a comprehensive solution titled "PathHole Detection and Proximity Measurement" aimed at leveraging YOLOv8, a cutting-edge object detection model, and digital image processing techniques to detect potholes on roads and measure the proximity between the vehicle and the detected potholes in real-time.
The system initiates by capturing real-time images of the road ahead using on-board cameras integrated into the vehicle. These images are then subjected to YOLOv8, a state-of-the-art deep learning model trained specifically for pothole detection. The utilization of YOLOv8 ensures efficient and accurate detection of potholes, enabling rapid processing of road images and precise identification of pothole locations.
Upon detecting a pothole in the captured image, the system employs digital image processing algorithms to compute the distance between the vehicle and the detected pothole. This process involves intricate geometric analysis and calibration techniques to translate pixel distances into real-world measurements, accounting for factors such as camera perspective and vehicle speed.
Subsequently, the system employs a robust alert mechanism to promptly notify the driver about the presence of a pothole ahead and the estimated distance to it. The alert interface is designed to deliver timely notifications through visual cues on the vehicle's dashboard, auditory signals, or tactile feedback, ensuring that drivers are informed and can react appropriately to avoid potential hazards.
The implementation of "Pothole Detection and Proximity Measurement" offers a proactive approach to enhancing driver safety by providing real-time warnings about potholes, enabling drivers to take pre-emptive measures to mitigate risks. By amalgamating advanced computer vision technologies with precise proximity measurement techniques, the system offers a reliable solution to address the challenges associated with potholes on roads, ultimately fostering safer driving environments for all road users.


## Features
-Model deployment
-Real-time Processing
-Image Acquisition


## Requirements
* Real-time Image Acquisition: The system should capture real-time images of the road ahead 
  using onboard cameras integrated into the vehicle.

* Pothole Detection: Utilize YOLOv8, a deep learning model, for efficient and accurate 
  detection of potholes in the captured images.

* Proximity Measurement: Compute the distance between the vehicle and detected potholes using 
  digital image processing algorithms and geometric analysis techniques.

* Integration with YOLO Model: Seamlessly integrate the YOLOv8 model for pothole detection, 
  allowing for easy training, validation, and testing on relevant datasets.

* Alert Mechanism: Implement a robust alert mechanism to promptly notify the driver about the 
  presence of potholes ahead and the estimated distance to them. The alert interface should 
  deliver notifications through visual cues on the vehicle's dashboard, auditory signals, or 
  tactile feedback.


## System Architecture


![image](https://github.com/P-S-Pradeep/Pothole-detection-and-proximity-measurement/assets/102652887/571720fa-7671-403a-9808-ca0f00c8bc92)


## Output

#### Output1 - Model Training

![Screenshot 2024-03-20 213415](https://github.com/P-S-Pradeep/Pothole-detection-and-proximity-measurement/assets/102652887/c5b0d56e-c6bb-4687-851f-b2be06754c11)

#### Output2 - Predicting Potholes using YOLOv8 

![Screenshot 2024-03-20 213457](https://github.com/P-S-Pradeep/Pothole-detection-and-proximity-measurement/assets/102652887/abe8b485-7a2f-466b-a175-4c70ee1b2a5a)


#### Output3 - Pothole prediction with distance estimation 

![Screenshot 2024-03-20 213528](https://github.com/P-S-Pradeep/Pothole-detection-and-proximity-measurement/assets/102652887/dc47b3df-3463-41e2-a820-0fa1e2d12a12)


## Results and Impact
In conclusion, the proposed "Pothole Detection and Proximity Measurement" system offers a proactive solution to address road safety concerns by leveraging advanced computer vision techniques and deep learning algorithms. By employing the YOLOv8 model trained on real-time video data captured by onboard cameras, the system can accurately detect potholes in road surfaces and provide timely alerts to drivers. The segmentation of video frames into three distinct regions (left, center, right) enhances the system's ability to localize potholes and measure their proximity to the vehicle, enabling drivers to take pre-emptive measures to avoid potential hazards.

Furthermore, the system's modular architecture facilitates efficient data preprocessing, model training, and real-time pothole detection, ensuring robust performance and reliability in diverse road conditions. Through rigorous testing and validation, including metrics such as accuracy and precision, the system demonstrates its effectiveness in detecting potholes and estimating their proximity with high confidence.

Overall, the "Pothole Detection and Proximity Measurement" system represents a significant advancement in road safety technology, offering drivers valuable insights into road conditions and empowering them to make informed decisions while driving. With its potential to mitigate risks associated with potholes and enhance overall driving safety, the system holds promise for widespread adoption and implementation in vehicular environments.

## Articles published / References
1.Egaji, Oche Alexander, Gareth Evans, Mark Graham Griffiths, and Gregory Islas. "Real-time machine learning-based approach for pothole detection." Expert Systems with Applications 184 (2021): 11556

2.Kavitha, R., and S. Nivetha. "Pothole and object detection for an autonomous vehicle using yolo." In 2021 5th international conference on intelligent computing and control systems (ICICCS), pp. 1585-1589. IEEE, 2021.

3.Reddy, E. Sai Tarun Kumar, and V. Rajaram. "Pothole detection using CNN and YOLO v7 algorithm." In 2022 6th International Conference on Electronics, Communication and Aerospace Technology, pp. 1255-1260. IEEE, 2022.

4.Shaghouri, Anas Al, Rami Alkhatib, and Samir Berjaoui. "Real-time pothole detection using deep learning." arXiv preprint arXiv:2107.06356 (2021).

5.Sathvik, Madarapu, G. Saranya, and S. Karpagaselvi. "An intelligent convolutional neural network based potholes detection using YOLO-V7." In 2022 International Conference on Automation, Computing and Renewable Systems (ICACRS), pp. 813-819. IEEE, 2022.

6.Bučko, Boris, Eva Lieskovská, Katarína Zábovská, and Michal Zábovský. "Computer vision based pothole detection under challenging conditions." Sensors 22, no. 22 (2022): 8878.
