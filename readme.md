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

# Docker

## Installations
Ajout des dépots
```bash
. /etc/os-release
curl -4fsSL https://download.docker.com/linux/${ID}/gpg | sudo tee /etc/apt/trusted.gpg.d/docker.asc
echo "deb [arch=amd64] https://download.docker.com/linux/${ID} ${VERSION_CODENAME} stable" | sudo tee /etc/apt/sources.list.d/docker.list
sudo apt update
```
Installation
```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose docker-compose-plugin
```
