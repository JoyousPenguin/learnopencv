# Depth Estimation using Stereo Camera and OpenCV

Create a custom low-cost stereo camera and capture depth maps with it using OpenCV.

## Usage

### C++ code

To run the code in C++, please go into the `cpp` folder, then compile the `disparity_params_gui.cpp`, `obstacle_avoidance.cpp` and `disparity2depth_calib.cpp` code files, use the following:

```shell
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

Refer to the following to use the compiled files:

```shell
./build/disparity_params_gui
./build/disparity2depth_calib
./build/obstacle_avoidance
```

### Using the python code

To run the code in Python, please go into the `python` folder and refer to the following to use the `disparity_params_gui.py`, `obstacle_avoidance.py` and `disparity2depth_calib.py` files respectively:

```shell
python3 disparity_params_gui.py
python3 disparity2depth_calib.py
python3 obstacle_avoidance.py
```

# AI Courses by OpenCV

Want to become an expert in AI? [AI Courses by OpenCV](https://opencv.org/courses/) is a great place to start.

<a href="https://opencv.org/courses/">
<p align="center">
<img src="https://www.learnopencv.com/wp-content/uploads/2020/04/AI-Courses-By-OpenCV-Github.png">
</p>
</a>
