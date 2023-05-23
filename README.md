# **Kitti Vehicle Dataset**

## **Approach**
### 1. General
### 2. Adapter
### 3. VPT (To be completed.)
<br/>

---
<br/>

## **Install the Required Packages**

```bash
$ conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=11.3 -c pytorch
$ pip install ftfy regex tqdm
$ pip install git+https://github.com/openai/CLIP.git
```
<br/>

---
<br/>

## **Prepare KITTI Dataset**
To be completed.
<br/>

---
<br/>

## **Preprocessing Label**
```bash
python text_generation.py
```
<br/>

---
<br/>

## **Fine Tune**
```bash
# General fine tune on whole model
python train.py

# Using adapter to fine tune
python train.py --adapter --lr 0.01 --weight_decay 0.00001
```
<br/>

---
<br/>

## **Acknowledgement**
This repo benefits from [CLIP](https://github.com/openai/CLIP) and [AIM](https://github.com/taoyang1122/adapt-image-models). Thanks for their wonderful works.
