# DeepTCNet
## Overview
This repository contains trained models reported in the paper "##" by Jing-Yi Zhuo and Zhe-Min Tan. The paper was under the review of ##.

## Running the code
### Setup
First follow the instructions for [installing Keras]: [1] ( tensorflow backended).
[1]: https://keras.io/#installation

Then cole this repository using 
$ git clone https:

### Sample code
With default flags, this loads the pre-trained DeepTCNet model, and then passes an example infrared imagry of Typhoon Lekima(2018) at ##UTC on Aug.# through the model.

This script outputs the intensity, includes maximum surface wind (MSW; unit: kt) and minimum seasurface pressure(MSLP; unit: hPa)), as well as the size, includes radius of maximum wind (RMW; Unit: nmi) and critical wind radii of 34-, 50- and 64-kt wind (R34, R50 and R64, respectively; Unit: nmi)  of Lekima.

Using the default flags, the output should resemble the following.


### Running the test
...

## Further details
The directory best_models/ contains our best performing model, which was trained on ##.

The directory sen_models/ contains the models built up in the sensitivity experiments.
