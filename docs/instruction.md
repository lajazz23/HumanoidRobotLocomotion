# Getting Started With IsaacLab

This section serves as instructions that I followed to successfully set up my Isaac Lab environment. Instructions are originally found on the Isaac Lab [website](https://isaac-sim.github.io/IsaacLab/main/index.html). You can find their GitHub [here](https://github.com/isaac-sim/IsaacLab).

## Requirements

To determine if your current set up is optimal to run Isaac Lab and Isaac Sim, you can install the NVIDIA Isaac Sim compatibility checker, found in the Omniverse Launcher. It is important to know that, by October 2025, the Omniverse Launcher will be deprecated. You may reference the Isaac Lab website for minimum dependencies.

Our project was run on the following specifications:

- NVIDIA GeForce RTX 4090
    - Driver Version 551.61
    - 25.76 GB VRAM
- Intel(R) Core (TM) i9-14900KF
    - 32 CPU cores
    - 68.42 GB RAM
    - 7315 GB Storage
- Windows 11 Pro v24H2
- Anaconda 24.11.1

## Installation

Isaac Lab is built on top of Isaac Sim, so we will have to install that first. Our device is Windows-based. To find instructions for the Linux installation, please consult the Isaac Lab website.

### Isaac Sim

To begin, we create a virtual environment called, "isaaclab" with python 3.10 inside Windows Terminal, and activate it. 

```
conda create -n isaaclab python=3.10
conda activate isaaclab
```
Next, we install PyTorch that is compatible with our system's CUDA version. In this case, we had CUDA 12.4:

```
pip install torch==2.5.1 torchvision==0.20.1 --index-url https://download.pytorch.org/whl/cu121
```
The Isaac Lab repository recommends updating pip:
```
python -m pip install --upgrade pip
```
To install the Isaac Sim packages, we ran the following:
```
pip install "isaacsim[all,extscache]==4.5.0" --extra-index-url https://pypi.nvidia.com
```
After this, Isaac Sim is fully installed. To test if this is true, we run ` isaacsim ` inside the terminal. After a few minutes, the Isaac Sim application will open, indicating a successful installation.

### Isaac Lab

Next, we can begin the installation of Isaac Lab. To begin, clone the repository:
```
git clone https://github.com/isaac-sim/IsaacLab.git
```
Navigate into the folder and install Isaac Lab:
```
cd IsaacLab
isaaclab.bat --install
```
After installation, open a demo file:
```
isaaclab.bat -p scripts\tutorials\00_sim\create_empty.py
```
This should open Isaac Sim, with Isaac Lab inside it.