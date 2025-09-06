# AIMS-Octomap (LiDAR to OctoMap Publisher)

This project provides a pipeline to read LiDAR data over serial(for Mac, use COM4 otherwise) and publish it into [OctoMap](https://octomap.github.io/) for 3D occupancy mapping.  
It’s designed to work with LiDAR hardware and integrates into a ROS2-based environment. It can combine multiple lidar scans from multiple drones into a single map that can be continually updated.

---

## 🚀 Features
- Reads data from a LiDAR device.
- Converts raw data into usable range scans.
- Publishes scans to an OctoMap subscriber node.
- Saves maps for future access and updates.

---

## 📂 Installation

### Prerequisites
- **ROS2** (tested on ROS2 Kilted)  
- **OctoMap**  
- Python 3.8+ (or C++ if you have a compiled publisher)  
- Serial library (`pyserial`)  

### Clone the repo
```bash
git clone https://github.com/JasonLin8888/lidar-octomap-publisher.git
cd lidar-octomap-publisher

---

