# U-Net-_SIIM
U-Net++ model for SIIM-ACR-Pneumothorax-Seg-XR dataset. For original repo, see [UNet++](https://github.com/4uiiurz1/pytorch-nested-unet)

#### Dataset

SIIM-ACR-Pneumothorax-Seg-XR dataset.

#### Environment

python = 3.7, PyTorch = 1.7.1, cuda = 10.1

#### Installation

```
pip install -r requirements.txt
```

#### File Directory
```
.
|-- U-Net-_SIIM
    |-- inputs
        |-- SIIM-ACR-Pneumothorax-Seg-XR
            |-- images
                |-- <your image>
            |-- masks
                |-- 0
                    |-- <your label>(the same name with image)
        |-- SIIM-ACR-Pneumothorax-Seg-XR_test (this is for segmentation)
            |-- images
                |-- <your image>

```
