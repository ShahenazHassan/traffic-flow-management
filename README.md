# traffic-flow-management
Traffic Flow Management Using Deep Learning
Project Overview
A smart traffic management system powered by deep learning to detect vehicles, estimate traffic density, and optimize traffic light timings in real time.
The system also prioritizes emergency vehicles (ambulances, fire trucks, police cars) by dynamically adjusting traffic signals to ensure faster and safer responses.

Objectives
Detect and classify vehicles in real-time.

Dynamically adjust traffic light timings based on traffic density.

Prioritize emergency vehicles for faster passage.

Reduce traffic congestion, fuel consumption, and air pollution.

Improve overall traffic efficiency and emergency response times.

Technologies Used
Python

TensorFlow

YOLOv8 and YOLOv12 (Object Detection)

SSD MobileNetV2 (Object Detection)

Roboflow (Dataset management and labeling)

Google Colab (Training and evaluation)

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, PIL, Ultralytics

Models and Experiments

Model	Training Accuracy	Testing Accuracy	Detection Level
YOLOv8n (Nano)	89.13%	90.43%	Good
YOLOv8s (Small)	92.98%	93.62%	Excellent
YOLOv8m (Medium)	90.80%	91.51%	Moderate
YOLOv12n (Nano)	91.67%	92.14%	Good
YOLOv12s (Small)	90.86%	91.20%	Good
YOLOv12m (Medium)	91.70%	93.21%	Very Good
SSD MobileNetV2	86.15%-93.61%	91.98%-93.56%	Moderate
✅ YOLOv8s was selected as the best-performing model for real-time deployment.

Dataset
Labeled real-world traffic images using Roboflow.

Five vehicle classes were detected and classified.

Data augmentation techniques were applied to enhance model performance.

Evaluation Metrics
Accuracy

mAP (Mean Average Precision)

Precision

Recall

F1-Score

Key Features
Real-time vehicle detection.

Dynamic adjustment of traffic signals based on congestion.

Emergency vehicle prioritization.

Model deployed on Google Colab environment with real-world simulation.

Future Improvements
Integrate video streaming for continuous traffic monitoring.

Improve congestion prediction by analyzing vehicle speed and movement patterns, not just count.

Expand dataset diversity with more real-world scenarios.

Deploy models on edge devices for live traffic analysis.

Demo Preview
Simulated real-world traffic scenarios.

Adjusted traffic light durations based on congestion and emergency vehicle detection.

✨ Thank you for visiting!
Feel free to explore the project, and reach out for any questions or collaborations!
