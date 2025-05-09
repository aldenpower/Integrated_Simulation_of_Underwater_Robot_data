# Integrated_Simulation_of_Underwater_Robot_data
This repository contains the datasets and ROS 2 bag files used under the validation section as part of the study on integrating Gazebo and Unity3D simulators.

## 📁 Directory Structure

### `csv_data/`

Processed data files extracted from the ROS 2 bag:

- `gazebo_pose.csv`: Pose data from Gazebo
- `unity_pose.csv`: Pose data from Unity3D
- `merged_pose.csv`: Time-aligned poses from both simulators
- `abserror.csv`: Computed absolute errors between Gazebo and Unity poses (position & orientation)
- `force.csv`: Forces applied to the robot
- `torque.csv`: Torques applied during the simulation
- `current.csv`: Water current applied dugin the simulation

### `ros2_bag/`

Raw simulation data in ROS 2 bag format:

- `full_bag2_0.db3`: The main SQLite database storing all topics
- `metadata.yaml`: ROS 2 bag metadata for session details and topic mapping

## 📦 Cloning the Repository with Git LFS

This repository contains large files (e.g., ROS 2 bag data) managed with [Git LFS](https://git-lfs.com). Follow the steps below to ensure proper setup:

### 1. Install Git LFS

**Ubuntu/Debian:**
```bash
sudo apt update
sudo apt install git-lfs
```

### 2. Initialize Git LFS
```bash
git lfs install
```

### 3. Clone the Repository

```bash
git clone https://github.com/aldenpower/Integrated_Simulation_of_Underwater_Robot_data.git
```
