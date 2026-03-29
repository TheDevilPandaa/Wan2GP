# Wan2GP
This document will clone DeepBeepMeep's amazing Wan2gp repo and will provide you with easy to copy and paste links / commands.

WAN2GP has some of the best Ai tools - from video, Text to speech, voice cloning, image generation and more. Which will be available to you in one place using this repo.

Follow the instructions in the video to install:

<br>

## Clone the repo:

```bash
git clone https://github.com/deepbeepmeep/Wan2GP.git
```

<br>

## Go into Wan2GP folder

```bash
cd Wan2GP
```

<br><br>
## Create a Virtual Environment

<br>

## For Python 10 (For older PCs recommended) -- Install Python 11 or newer for future support
```bash
conda create -n wan2gp python=3.10.9
```

### Activate the Virtual Environment ( This will need to be executed everytime to run the modals)
```bash
conda activate wan2gp
```

### Torch and Cuda Installation
```bash
pip install torch==2.7.1 torchvision torchaudio --index-url https://download.pytorch.org/whl/test/cu128
```

### Install Requirements
```bash
pip install -r requirements.txt
```
<br>
      
## For Python 11 or newer (For RTX 2xxx and higher GPUs --- Use above version if there is any issue)
```bash
conda create -n wan2gp python=3.11.14
```

### Activate the Virtual Environment
```bash
conda activate wan2gp
```

### Torch and Cuda Installation
```bash
pip install torch==2.10.0 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu130
```

### Install Requirements
```bash
pip install -r requirements.txt
```

<br><br>
FOR HIGHER END GPUs if you are having issues, follow specific instructions in the below file to install Sage Attention, Triton, Flash Attention.

[Installation Guide - GPU Specific](https://github.com/deepbeepmeep/Wan2GP/blob/main/docs/INSTALLATION.md)


<br><br>


Optional Setup.

<br>

## Install Flash Attention (Optional) 
```bash
pip install https://github.com/deepbeepmeep/kernels/releases/download/Flash2/flash_attn-2.8.3-cp311-cp311-win_amd64.whl
```

<br>

## Run the App
```bash
python wgp.py
```
<br>


## To Delete the virtual Environment
```bash
conda uninstall -n wan2gp --all
```
<br><br>

# Gallery

![3](https://i.postimg.cc/0yW1XQL4/Qwen-TSS.png)
![1](https://i.postimg.cc/htyRZjH6/2.png)
![2](https://i.postimg.cc/pLGMcTgc/3.png)


<br><br>

**AI Modal**<br>
[Wan 2.1](https://github.com/Wan-Video/Wan2.1)

<br>


**Sepcial Thanks:** <br>
[DeepBeepMeep](https://github.com/deepbeepmeep/)

