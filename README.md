# Wan2GP
This repo will clone DeepBeepMeep's amazing Wan2gp repo and will provide you with easy to copy and paste links / commands.

WAN2GP has some of the best Ai tools - from video, Text to speech, voice cloning, image generation and more. Which will be available to you in one place using this repo.

Follow the instructions in the video to install:

## Clone the repo:

```bash
git clone https://github.com/deepbeepmeep/Wan2GP.git
```


## Go into Wan2GP folder

```bash
cd Wan2GP
```



## Create a Virtual Environment

For Python 10 (Not recommended but works perfectly file) -- Install Python 11 or newer for future support
```bash
conda create -n wan2gp python=3.10.9
```

For Python 11 or newer (Update the version if required)
```bash
conda create -n wan2gp python=3.11.14
```

## Activate the Virtual Environment ( This will need to be executed everytime to run the modals)

```bash
conda activate wan2gp
```

## Install Pitourch and Cuda

### Windows Installation for GTX 10XX -16XX Only

```bash
pip install torch==2.6.0+cu126 torchvision==0.21.0+cu126 torchaudio==2.6.0+cu126 --index-url https://download.pytorch.org/whl/cu126
```

### Windows Installation for RTX QUADRO - 20XX Only

Windows Install PyTorch 2.6.0 with CUDA 12.6 for RTX QUADRO - 20XX Only
```bash
pip install torch==2.6.0+cu126 torchvision==0.21.0+cu126 torchaudio==2.6.0+cu126 --index-url https://download.pytorch.org/whl/cu126
```

Windows Install Triton for RTX QUADRO - 20XX Only
```bash
pip install -U "triton-windows<3.3"
```

Windows Install Sage1 Attention for RTX QUADRO - 20XX Only
```bash
pip install sageattention==1.0.6
```

### Windows Installation for RTX 30XX Only

Windows Install PyTorch 2.6.0 with CUDA 12.6 for RTX 30XX Only
```bash
pip install torch==2.6.0+cu126 torchvision==0.21.0+cu126 torchaudio==2.6.0+cu126 --index-url https://download.pytorch.org/whl/cu126
```

Windows Install Triton for RTX 30XX Only
```bash
pip install -U "triton-windows<3.3"'
```

Windows Install Sage2 Attention for RTX 30XX Only
```bash
pip install https://github.com/woct0rdho/SageAttention/releases/download/v2.1.1-windows/sageattention-2.1.1+cu126torch2.6.0-cp310-cp310-win_amd64.whl
```

### Installation for RTX 40XX, 50XX Only

Windows Install PyTorch 2.7.1 with CUDA 12.8 for RTX 40XX - 50XX Only
```bash
pip install torch==2.7.1 torchvision==0.22.1 torchaudio==2.7.1 --index-url https://download.pytorch.org/whl/cu128
```

Windows Install Triton for RTX 40XX, 50XX Only
```bash
pip install -U "triton-windows<3.4"
```

Windows Install Sage2 Attention for RTX 40XX, 50XX Only
```bash
pip install https://github.com/woct0rdho/SageAttention/releases/download/v2.2.0-windows/sageattention-2.2.0+cu128torch2.7.1-cp310-cp310-win_amd64.whl
```

### Installation for 50XX Only Python 3.11, PyTorch 2.10.0 Cuda 13. for NVFP4 optimized kernels

Create Python 3.11 environment using Conda
```bash
conda create -n wan2gp python=3.11.14
```

Windows Install PyTorch 2.10.0 with CUDA 13.0 for RTX 50XX Only
```bash
pip install torch==2.10.0 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu130
```

Windows Install Triton for RTX 50XX Only
```bash
pip install -U triton-windows
```

Windows Install Sage2 Attention for RTX 50XX Only

```bash
pip install https://github.com/woct0rdho/SageAttention/releases/download/v2.2.0-windows.post4/sageattention-2.2.0+cu130torch2.9.0andhigher.post4-cp39-abi3-win_amd64.whl
```


### **For CPU (if not using GPU):**
  ```bash
  pip install torch
  ```
  This installs the CPU-only version of PyTorch.


## Install Requirements
```bash
pip install -r requirements.txt
```

## Install Flash Attention (Optional but recommended) 
```bash
pip install https://github.com/deepbeepmeep/kernels/releases/download/Flash2/flash_attn-2.8.3-cp311-cp311-win_amd64.whl
```

## Run the App
```bash
python wgp.py
```

