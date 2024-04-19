# YONNX7

Portable YOLOv7 ONNX runtime for CPU. This is an extremely low-dependency framework that can run YOLOv7 models on a CPU. The only dependencies needed are *xtensor*, which is a header-only library for multi-dimensional arrays, *protobuf* for parsing ONNX models, and a *BLAS* library of your choice for matrix multiplication. Additional optional dependencies are *OpenCV* for drawing the bounding boxes and applying NMS (Non-Maximum Supression) on the resulting images and *GoogleTest* for unit testing some kernels.

## Why this?

I wanted to understand how inference in convolutional neural networks works and how to implement them from scratch with minimal dependencies. This was also the basis of one of my discarded Master's thesis which focused on developing a framework to run computer vision models on RISC-V CPUs.

## Is this faster than X?

Most likely not!
