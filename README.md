# Lane Detection Using LaneNet and PyTorch

## Overview

This repository contains an implementation of lane detection using the LaneNet model with PyTorch. LaneNet is a deep learning model designed for lane detection in autonomous driving applications.

For detailed architecture and methodology, refer to the [original paper](https://arxiv.org/abs/1802.05591).

## Architecture

LaneNet consists of two main components:
1. **Lane Segmentation Branch**: This part of the model outputs a binary segmentation map indicating which pixels belong to lanes.
2. **Lane Embedding Branch**: This component further processes the segmented lane pixels to distinguish between different lane instances.

The model is trained to detect and segment lanes in images, which can be used for various applications in autonomous driving systems.

## Requirements

To run the code, make sure you have the necessary dependencies installed. You can install them using the provided `requirements.txt` file.

### Installation

```bash
pip install -r requirements.txt
```

Download the pretrained model from [here](https://drive.google.com/drive/folders/1c30um1r-PXcC_-9_aY0jLZqYVKw0Ni91?usp=sharinghttps://drive.google.com/drive/folders/1c30um1r-PXcC_-9_aY0jLZqYVKw0Ni91?usp=sharing)

### Test model using image
```bash
python test.py --img ./data/tusimple_test_image/0.jpg
```
### Test model using video
```bash
py test4.py
```

Remember, this model is only trained on 25 epochs. for more goods results and accuracy you can train model on large dataset with many epochs.

for more updates connect with me on [linkedln](https://www.linkedin.com/in/hamas-ali-raja-2a5822277)



