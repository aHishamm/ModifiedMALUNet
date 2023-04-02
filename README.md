# MALUNet
This implementation is based on the "MALUNet: A Muti-Attention and Light-weight UNet for Skin Lesion Segmentation". [[arxiv]](https://arxiv.org/abs/2211.01784)

**0. Main Environments**
- python 3.8
- pytorch 1.8.0
- torchvision 0.9.0

**1. Prepare the dataset.**

- ISIC17 and ISIC18 dataset can be found [here](https://challenge.isic-archive.com/data/). 

- The data should be stored in the following order inside the ./data folder 

- './data/ph2/'
  - train
    - images
      - .png
    - masks
      - .png
  - val
    - images
      - .png
    - masks
      - .png

**2. Train the MALUNet.**
```
cd MALUNet
```
```
python train.py
```

**3. Obtain the outputs.**
- After trianing, you could obtain the outputs in './results/'
