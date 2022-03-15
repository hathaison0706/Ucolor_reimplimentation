# Reimplimentation of UColor model for Underwater Image Enhancement

## Description

The main goal of this algorithm is to use deep learning architectures such as ResNet, Squeeze'N'Exciation alongside with the physical properties of underwater images to restore and enhance the visibility and the naturalness of the images. Inspired by the UColor model proposed by Li [1], we reimplimented the model and at the same time changed the input color spaces HSV to YCbCr.

![Comparisons between 2 methods](https://github.com/hathaison0706/Ucolor_reimplimentation/blob/main/figure1.png?raw=true)

The code can be found at: 
```
https://drive.google.com/drive/folders/1Bne3h68H1SZLawvp3pNt8e2aOdEuuzCw?usp=sharing
```

## Usage

### Dependencies

Python 3.0, Tensorflow 2.7.0 , CUDA 11.2

### Testing

1. Use Colab to run the code
2. Put all testing images in the "/testing_input" folder and the depth map in the "/testing_depth" folder, make sure all images are in .png format
3. Run MAIN_TEST.ipynb
4. The results will be found in "/testing_result" folder

Extra testing data can be found in "/DATA" folder


### Training

1. Use Colab to run the code
2. Run MAIN_TRAIN_YCBCR.ipynb
3. The checkpoint will be updated in the "/checkpoint" folder. One training graph will be included at the end of training


## Reference
[1.] C. Li, S. Anwar, J. Hou, R. Cong, C. Guo, and W. Ren, "Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding," IEEE Trans Image Process, vol. 30, pp. 4985-5000, 2021, doi: 10.1109/TIP.2021.3076367


## License

This project is open sourced under MIT license - see the LICENSE.md file for details

## Help

Any questions please contact Thai Son Ha at hathaison0706@gmail.com


