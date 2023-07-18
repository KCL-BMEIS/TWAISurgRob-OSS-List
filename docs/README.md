# Overview
![CME logo](/assets/medicalengineering-logo.svg)

The aim of the [Wellcome / EPSRC CME](https://medicalengineering.org.uk) - [Pillar 3 on "Trustworthy Artificial Intelligence for Sensory-rich Surgical Robotics"](https://medicalengineering.org.uk/centre-activities/pillar-3-trustworthy-artificial-intelligence-for-sensory-rich-surgical-robotics/) is to lay the foundations of a sustainable programme leading to surgical robot autonomy in collaborative human-robot teams. The team will advance the field across four directions feeding in this ambition: Trustworthy AI, computational ultrasonography, knowledge extraction from connected medical devices, and sensory-rich human-machine interfaces.

This pages serves as a curatel list of open-source software developped, maintained, or simply useful for members of the pillar.

## Robotics
- [lbr_fri_ros2_stack](https://github.com/KCL-BMEIS/lbr_fri_ros2_stack): ROS 2 packages for the KUKA LBR, including communication to the real robot via the Fast Robot Interface ([FRI](https://github.com/KCL-BMEIS/fri)) and [Gazebo](http://gazebosim.org/) simulation support.
- [optas](https://github.com/cmower/optas): An optimization-based task specification library for task and motion planning (TAMP), trajectory optimization, forward/inverse kinematics, and model predictive control in Python. Also, see [paper](https://ieeexplore.ieee.org/document/10161272).
- [FRI-Client-SDK_Python](https://github.com/cmower/FRI-Client-SDK_Python): Library for the FRI library that controls the KUKA LBR robot arm in Python.
- [FRI-Client-SDK_Cpp](https://github.com/cmower/FRI-Client-SDK_Cpp): C++ FRI library including CMake files for controlling the KUKA LBR robot arm.
- [geomagic_touch_x_ros_driver](https://github.com/RViMLab/geomagic_touch_x_ros_driver): ROS package for control of 3D Systems Geomagic Touch X.
- [eff_wrench](https://github.com/cmower/eff_wrench): ROS 2 node for estimating end-effector wrench. 


## Scientic equipment
-  [spectrumdevice](https://github.com/KCL-BMEIS/spectrumdevice): Python library for communicating with digitisers manufactured by [Spectrum Instrumentation](https://spectrum-instrumentation.com/).
-  [pymagewell](https://github.com/KCL-BMEIS/pymagewell): a Python library for interfacing with Magewell ProCapture frame grabbers.

## Surgical vision
- [torch-content-area](https://github.com/charliebudd/torch-content-area): A PyTorch tool kit for estimating the circular content area in endoscopic footage.
- [semi-synthetic](https://github.com/luiscarlosgph/semi-synthetic): Image compositing for segmentation of surgical tools without manual annotations.
- [list-of-surgical-tool-datasets](https://github.com/luiscarlosgph/list-of-surgical-tool-datasets): List of surgical tool datasets organised by task.

## Data management
- [synapi](https://github.com/luiscarlosgph/synapi): Python package to deal with Synapse datasets in a more convenient way.
