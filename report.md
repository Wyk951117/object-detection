###Reoprt for YOLOv3

##Date: 10/16/2018

#observation: 
1. using the data from VOC2007, the network would converge at around epoch 10.


##Date: 10/18/2018

#done:
1. understand the file structure;
2. add average score to validation step.

#try:
1. deal with the anchor boxes since the locations seem to affect the outcome;
2. download dac dataset, can grab a small portion for training and validation each time;
3. derive the detailed structure of feature extraction step as well as three scales.


##Date: 10/19/2018

#try:
1. reading materials about anchor boxes (and scales), might come up with something espeically for human
since current anchor boxes are intended for various objects.

#observation:
1. It seems that scales are used for literally three scales of objects in am image (large, medium, small)
while anchor boxes are for predicting the offset of objects.

#try:
1. consider increasing the number of scales;
2. might use K-clustering later for the choices of anchor boxes.
3. look to check the various conditions of DAC dataset since there are different categories of people represented.
