# Waste Classification Web App



### Deployment



We deployed it online using Streamlit and FastAPI





### FEATURES OF APP



1- Upload or capture an image



2- YOLOv8 (custom trained) detects objects



3- CNN classifies them



4- Audio feedback announces whether the object is biodegradable or not



5- Generates a downloadable PDF report with details on proper waste disposal



6- Works in three languages: English, Tamil or Malay





### Terms / Neural Networks used



YOLO (You Only Look Once) is a real-time object detection algorithm that

predicts object classes and their bounding boxes in a single neural network pass.



A Convolutional Neural Network (CNN) is a deep learning model designed that learn 

spatial features from data, especially images, using convolutional layers.





### Tricky part



Streamlit doesn’t allow installing the Ultralytics (YOLOv8) library directly.



It took a lot of time to debug



SOLUTION:  we deployed the YOLOv8 model separately using FastAPI on Render.



Our Streamlit frontend, hosted via GitHub, sends image data to the FastAPI backend

to receive detection results 





























































