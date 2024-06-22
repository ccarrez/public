# AI

## Installations
### Conda environement
Download from: https://docs.anaconda.com/miniconda/
```bash
./Miniconda3-latest-Linux-x86_64.sh
```
### Python autotrain environement
https://github.com/huggingface/autotrain-advanced
```bash
conda create -n autotrain python=3.10
conda activate autotrain
pip install autotrain-advanced
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
conda install -c "nvidia/label/cuda-12.1.0" cuda-nvcc
```
