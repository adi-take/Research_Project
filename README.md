# Adaptive_Dynamic_Traffic_Signal_Control_For_Indian_Vehicles Project
🚦 Intelligent Indian Vehicle Detection & Signal Time Estimation System

This project code seperate in 3 parts:-
  1. Custom_Indian_Vehicle Dataset
  2. Indian_Vehicle_CNN_Classifier
  3. Blend_Model_Pipeline
There are many rooms for improvement in this project but don't worry i'll work on it and update it time to time.

This project leverages deep learning and spatial logic to detect Indian vehicles from live traffic feeds and estimate optimal traffic signal timings based on vehicle type and lane occupation. The system is designed to support smart traffic management solutions tailored to Indian roads.

🔍 Project Highlights
* Vehicle Detection using a custom-trained CNN/YOLO model on an Indian vehicle dataset.
* Time Estimation Logic based on:
 * Vehicle length
 * Safe gaps between vehicles
 * Speed of each category
 * Lane-based spatial arrangement
* Dynamic Signal Control: Calculates green signal time based on vehicle queue length per lane.

🧠 Technologies Used
* Python
* OpenCV
* TensorFlow/Keras (or PyTorch)
* YOLOv8 / CNN
* JSON for data exchange
* Matplotlib/Seaborn for visualization

dataset/
├── Auto Rickshaw/
├── Indian_truck/
├── Indian_bus/
├── Indian_mini_truck/
├── Tractor/

📈 Outputs
* Vehicle category-wise count
* Estimated signal clearance time
* Lane-aware adjustment logic
* Visual plots for training/validation and time estimations

Thank you to my professor and my university for guiding me to make this wonderful little project and my friends you can also share my project's code and report. Just don't get caught..
