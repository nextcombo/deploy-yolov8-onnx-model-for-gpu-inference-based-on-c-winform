# Deploy YOLOv8 ONNX model for GPU inference based on C# Winform

# YOLOv8 ONNX GPU Deployment Project## Project Overview This project uses C# to implement the YOLOv8 ONNX model on GP.

```
# YOLOv8 ONNX GPU Deployment Project
## Project Overview
This project implements the deployment of YOLOv8 ONNX model on GPU using C#, based on .NET 8.0 framework and Windows Forms development. The project uses the YoloSharp.Gpu library for model inference and OpenCvSharp for image processing.
## Environmental Requirements
- Visual Studio 2022
- .NET 8.0
- NVIDIA graphics card driver (supports CUDA 12.4)
- CUDA 12.x (tested 12.4)
- cuDNN 9.x (tested 9.1.0)
## Project Structure

```

1. Product Technical Requirements

```
## Functionality Characteristics
- Supports image detection
- Supports video file detection
- Supports real-time detection of cameras
- Display the results and FPS
- Automatically retrieve class names from ONNX models
## Usage Method
1. Clone or download this project.
2. Open FIRC.sln using Visual Studio 2022
3. Ensure that the required dependencies (CUDA, cuDNN) are installed.
4. Place the YOLOv8 ONNX model file in the `bin\x64\Debug\net8.0-windows\weights\` directory
5. Compile and run the project
## Interface Description
- Select image: Load an image file for detection.
- Start Detection: Target detection on the loaded image
- Select Video: Load video files for real-time detection
- Camera detection: Real-time detection using a camera.
## Notes
1. Ensure that the graphics card driver supports CUDA 12.4.
2. If the precompiled version is used, CUDA and cuDNN may not need to be installed separately.
3. The project uses the `yolov8n.onnx` model by default, which can be replaced with other YOLOv8 models.

```

The README.md file already contains the basic information of the project, environmental requirements, and functionality descriptions. You can further modify and improve it according to actual needs.

Project demo video: https://www.bilibili.com/video/BV11eRRY6ENu/


## Payment

Here is a pay link on Stripe ( https://buy.stripe.com/3cs8yP7sY87d0vu9AB ). Please contact me lonlonago@foxmail.com after funding $89, and I will send you a complete data files , thank you!

![111.png](111.png)
