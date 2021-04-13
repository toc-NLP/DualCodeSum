# DualCodeSum

## Overview
This project is a Torch implementation which code summarization by dual learning.

## Hardware
The models are trained using folloing hardware:
- CentOS Linux 8
- NVIDA GeForce RTX 3090 24GB * 4
- AMD Ryzen Threadripper 3960X 24-Core Processor
- 256GB RAM

## Dependencies
- Python version is 3.6.7
- 
We use the following version of Pytorch.

Etc. (Included in "requirements.txt")
- torch>=1.3.0
- torchtext==0.3.1
- numpy==1.16.1
- tqdm
- matplotlib
- regex

## Prerequisite
- Use virtualenv
```	sh
    sudo apt-get install build-essential libssl-dev libffi-dev python-dev
    sudo apt install python3-pip
    sudo pip3 install virtualenv
    virtualenv -p python3 venv
    . venv/bin/activate
    # code your stuff
    deactivate
```
