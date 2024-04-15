**This repository has a model file or trained model (mobilenet_v3_large) along with the ONNX file for Driver distraction detection, and that is used for inference on NVIDI's DeepStream.**

**Features:**

-Trained a mobilenet_v3_large model on a Driver Distractions detection dataset.

-Exports the trained model to ONNX format.

-Converts the ONNX model to a TensorRT engine for optimized inference.

-Uses DeepStream for real-time object detection with the TensorRT engine.




**Requirements:**
 1. To get the engine file and deployment on the deepstream app, make sure you have a Jetson device with the following requirements.
    
  • Hardware Platform (Jetson / GPU): Jetson Orin Nano or above
  
  • DeepStream Version: deepstream-6.4
  
  • JetPack Version : Version: 6.0-b52
  
  • TensorRT Version: Version: 8.6.2

**Results:**
https://www.youtube.com/watch?v=Rshln1-NCqc&ab_channel=anilsarode
