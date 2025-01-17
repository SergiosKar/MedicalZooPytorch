# Medical Zoo Pytorch
We strongly believe in open and reproducible deep learning research. In order to reproduce our results, the code (alpha release) and materials of this thesis are available in this repository. The goal is to implementent an open-source medical segmentation library of state of the art 3D deep neural networks in PyTorch along with data loaders of the most common medical MRI datasets. The first stable release of our repository is expected to be publised in the end of September. 

## Alpha release - work in progress
![Alt text](./figs/intro.png?raw=true "title")

This MSc Thesis is focused on multi-modal brain segmentation.   For our experiments, we used two common benchmark datasets(ISEG 2017 & MRBRAINS2018) from MICCAI MRI image challenges. Brain MR segmentation challenges aim to evaluate state-of-the-art methods for the segmentation of brain by providing a 3D MRI dataset with ground truth tumor segmentation labels annotated by physicians. We perform a comparative analysis of the modern 3D architectures through extensive evaluations. The implemented networks were based on the specifications of the original papers. Finally, we discuss the reported results and provide future directions.

## Early results

## Comparison with Ground truth data
![Alt text](./comparison.png?raw=true "Dice coeff.")


### Train-Val curves
![Alt text](./figs/unet_3d_dice_coeff.jpg?raw=true "Dice coeff.")


![Alt text](./figs/unet_3d_loss.jpg?raw=true "Dice loss")

### Out volume features visualization
![Alt text](./figs/a1.png?raw=true "Slice viz")

![Alt text](./figs/a2.png?raw=true "Slice viz")

![Alt text](./figs/a3.png?raw=true "Slice viz")

## Virtual env
This command should get you working. Better Documentation after summer holidays :)
```
pip install torch numpy nibabel
```

## Where to brain-MRI segmentation datasets

### iSeg-2017
```
http://iseg2017.web.unc.edu/
```
### MR-BRAINS 2018 DATASET
```
https://mrbrains18.isi.uu.nl/
```


## Top References
```
TODO
```
