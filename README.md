# DeepTCNet
## Overview
This repository contains trained models reported in the paper "##" by Jing-Yi Zhuo and Zhe-Min Tan. The paper is under the review of *Journal of Advances in Modeling Earth Systems*.

## Running the code
### Setup
First follow the instructions for [installing keras].


[installing keras]:    https://keras.io/#installation/ 

Then clone this repository using 

$ git clone https://github.com/jyzhuo/DeepTCNet

### Sample code
This loads the pre-trained DeepTCNet model, and then passes an example infrared imagry of Typhoon Lekima(2019) from Augest 5th to Augest 10th. through the model.

This script outputs the intensity, includes maximum surface wind (MSW; unit: kt) and minimum seasurface pressure(MSLP; unit: hPa), as well as the size, includes radius of maximum wind (RMW; Unit: nmi) and critical wind radii of 34-, 50- and 64-kt wind (R34, R50 and R64, respectively; Unit: nmi)  of Lekima.

Using the default flags, the output should resemble the following.


### Running the test
This script loads the DeepTCNet to estiamte the intensity and size of North Atlantic hurricanes (NATC) in 2017. 

The DeepTCNet is our best performing model collection, including one for intensity estiamtion and the other for size estimation. The DeepTCNet are trained with NATC samples in 1988-2014, and called early stop using NATCs in 2015-16. On the test set: NATCs in 2017, we obtained the following erros (the metrics are counted in comparision to the best track):
...

## Further details
The directory best_models/ contains our best performing model, which was trained on ##.

The directory sen_models/ contains the models built up in the sensitivity experiments.
