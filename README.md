# Introduction

Project overview for **Society-5**. [Intro.pdf](./Intro.pdf) is the first draft (10 Aug 2018) of the abstract of the project paper:

> **Robosapien – model of AI traveler**
> *Towards Future Society 5.0: Modeling, Exploration & Understanding*
> Alex Tsvetanov & Ivaylo Ivanov, under the direction of Assoc. Prof. Zlatogor Minchev
> Summer Research School (SRS) of the High School Students Institute of Mathematics and Informatics, Pamporovo, Bulgaria, August 2018

The full paper (LaTeX sources and compiled PDF) is in the [Paper](https://github.com/Society-5/Paper) repository.

Society-5 is a robotics project built around the **WowWee Robosapien X**. The goal is a "robo-researcher" that can explore an environment and get past obstacles without a user steering it, for example as a stand-in for a Mars exploration task. A mixed-reality interface also lets a person see through the robot's eyes and control it remotely.

## In the media

**[Военните репортери, 4.11.2018](https://youtu.be/1aO4j-VQSGU)** is an episode of "Military Reports" on the Bulgarian Military TV Channel. It includes a documentary, about 19 minutes long, on the live experiment and training on the future digital society (Society 5.0) run at SRS'2018 in Pamporovo. The robot appears in the footage.

The event was organized by Assoc. Prof. Zlatogor Minchev (JTSAC) as part of the *Securing Digital Future 21* initiative, during the Summer Research School of the High School Students Institute of Mathematics and Informatics. Participants in the video: Alex Tsvetanov, Antoan Georgiev, Ivaylo Ivanov, Konstantin Delchev and Dimitar Chakarov.

## Repositories

| Repository | Role |
|---|---|
| [Vision-Control](https://github.com/Society-5/Vision-Control) | QR code detection from the phone camera stream (C++, OpenCV, ZBar) |
| [Mapping](https://github.com/Society-5/Mapping) | Steers the robot from the positions of QR codes in the frame |
| [collision-detection](https://github.com/Society-5/collision-detection) | Keras classifier for collision vs. clear path |
| [Object-Recognition](https://github.com/Society-5/Object-Recognition) | Webcam object detection with SSD MobileNet (TensorFlow) |
| [robot-controller](https://github.com/Society-5/robot-controller) | UDP server that sends infrared commands to the Robosapien |
| [command-sender](https://github.com/Society-5/command-sender) | Sends user actions from VR to the robot controller |
| [VR-interface](https://github.com/Society-5/VR-interface) | Mixed-reality front end (robot's-eye view) |
| [SearchAlgorithmVisualization](https://github.com/Society-5/SearchAlgorithmVisualization) | WPF maze generator and path-search visualizer |
| [Voice-Control](https://github.com/Society-5/Voice-Control) | Voice commands for the robot (planned) |
| [Paper](https://github.com/Society-5/Paper) | LaTeX write-up of the project (SRS 2018) |
