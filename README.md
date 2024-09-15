Opencv DNN Support on windows
=============================
- This repository contains the steps to build OpenCV with DNN support on Windows.
- The steps are tested on Windows 10 with Visual Studio 2019.

# Steps
1. Install CMake
    - Download and install CMake from [here](https://cmake.org/download/).
    - Add CMake to the system path.
2. Install Visual Studio 2019
    - Download and install Visual Studio 2019 from [here](https://visualstudio.microsoft.com/downloads/).
3. Install CUDA Toolkit
    - Download and install CUDA Toolkit from [here](https://developer.nvidia.com/cuda-toolkit-archive).
    - Add CUDA Toolkit to the system path.
4. Install cuDNN
    - Download and install cuDNN from [here](https://developer.nvidia.com/cudnn).
    - Add cuDNN to the system path.
5. Innstall anaconda
    Although this is not an important step, it’s recommended for smooth installation.
    You need to uninstall previous installations of Python and Anaconda.
    Reinstall Anaconda from here.
    - Download and install anaconda from [here](https://www.anaconda.com/download).
    Install NumPy from the terminal using pip install numpy.
6. clone opencv and opencv_contrib
    - clone opencv from [here](https://github.com/opencv/opencv.git)
    - clone opencv_contrib from [here](https://github.com/opencv/opencv_contrib.git)
    ```bash
    git clone https://github.com/opencv/opencv_contrib.git
    git clone https://github.com/opencv/opencv.git
    ```
7. Create a build directory

# Reference:
- Linux: 
    - https://learnopencv.com/opencv-dnn-with-gpu-support/
- Windows: 
    - https://learnopencv.com/how-to-use-opencv-dnn-module-with-nvidia-gpu-on-windows/
    - https://machinelearningprojects.net/build-opencv-with-cuda-and-cudnn/