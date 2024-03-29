
# Car Density Visualizer

Welcome to the Car Density Visualizer, a tool designed to visualize and analyze Car traffic patterns with ease. This comprehensive solution transforms raw data into interactive and visually appealing heatmaps, providing valuable insights for businesses, event organizers, and urban planners

# Features
Effortless Integration: Seamlessly integrate our Car Density Visualizer into your existing workflow, allowing you to process and visualize Car traffic data effortlessly.

Customizable Visualizations: Tailor the appearance of your heatmaps to suit your specific needs. Adjust color schemes, intensity gradients, and overlays to create stunning visual representations of Car patterns.

Real-time Analytics: Stay informed with real-time analytics, enabling you to make data-driven decisions promptly. Monitor changes in Car traffic dynamically and adapt strategies accordingly.

Scalability: Whether you're working with a small business space or a large event venue, our Car Density Visualizer is designed to scale according to your needs, providing accurate and detailed visualizations for areas of any size.

## Tech Stack

- [DeepStream] - Streaming Analytics toolkit for video, image, audio processing/understanding.
- [TensorRT] - TensorRT is a machine learning framework that is used to run machine learning inference on Nvidia hardware.
- [YOLOV5] - YOLO is a advanced computer vision algorithm that is used in object detection.
- [Jetson] - It is a SOM device manufactured by Nvidia for running tensor intensive application.

![Jetson](https://i.imgur.com/eCMj2EV.jpg)



## Installation

1.Install Deepstream-6.3 using 

```bash
    sudo apt install \
    libssl1.1 \
    libgstreamer1.0-0 \
    gstreamer1.0-tools \
    gstreamer1.0-plugins-good \
    gstreamer1.0-plugins-bad \
    gstreamer1.0-plugins-ugly \
    gstreamer1.0-libav \
    libgstreamer-plugins-base1.0-dev \
    libgstrtspserver-1.0-0 \
    libjansson4 \
    libyaml-cpp-dev
```

2.Download and install Deepstream 6.3 from [here]( https://catalog.ngc.nvidia.com/orgs/nvidia/resources/deepstream)
```bash
    sudo apt-get install ./deepstream-6.3_6.3.0-1_arm64.deb
```

## Usage

1.Clone repository 

```bash
    git clone git@github.com:ANANTHAN-VM/Car-density-visualizater.git
```

2.Build 
```bash
    make
```

3.Run
```bash
    ./Car file://<path to any video file.mp4>
```

Please find the demo link [here](https://youtu.be/ObMPh8CjfbE)
