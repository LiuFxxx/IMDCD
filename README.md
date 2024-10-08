# IMDCD: Iterative Mamba Diffusion Change Detection Model for Remote Sensing
### Feixiang Liu Yihan Wen, Jiayi Sun, Peipei Zhu, Liang Mao, Guanchong Niu, and Jie Li*

#### Shenzhen Polytechnic University，China
#### Xidian University，China
## Our code will be presented soon

## Network Architecture
![输入图片说明](photos/network.png)
### The Variable State Space CD (VSS-CD) we proposed
![输入图片说明](photos/vsscd.png)
### The Global Hybrid Attention Transformer (GHAT) we proposed
![输入图片说明](photos/ghat.png)
## Quantitative & Qualitative Results on CDD, WHU, LEVIR and OSCD
![输入图片说明](photos/cdd.png)
![输入图片说明](photos/whu.png)
![输入图片说明](photos/levir.png)
![输入图片说明](photos/oscd.png)
##  Usage
### Requirements
```
Python 3.8.0
pytorch 1.10.1
torchvision 0.11.2
einops  0.3.2
```
Please see ```requirements.txt``` for all the other requirements.
### Installation
Clone this repo:
```
git clone https://github.com/LiuFxxx/IMDCD.git
```
### Setting up conda environment:
Create a virtual ```conda``` environment named ```IMDCD``` with the following command:
```
conda create --name IMDCD --file requirements.txt
conda activate IMDCD
```
