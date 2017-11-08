# 3DMM models:

## Morphable Face Models - An Open Framework (2017) [downloaded data, model and paper]
http://faces.cs.unibas.ch/bfm/ 
#### papers:
https://arxiv.org/pdf/1709.08398.pdf
#### models:
http://faces.cs.unibas.ch/bfm/bfm2017/restricted/model2017-1_bfm_nomouth.h5 (original Basel Face Model mask)
http://faces.cs.unibas.ch/bfm/bfm2017/restricted/model2017-1_face12_nomouth.h5 (Model cropped to the face region)
username: bagonzalo@gmail.com
password: QkdM5BGD
#### additional data:
http://faces.cs.unibas.ch/bfm/bfm2017.html
#### others/code:
The Basel Face Model 2017 is available in the Statismo (https://github.com/statismo/statismo) file format used by the Scalable Image Analysis and Shape Modelling Software Scalismo (https://github.com/unibas-gravis/scalismo).
A tool to view the model can be downloaded under https://github.com/unibas-gravis/basel-face-model-viewer
For model based face image analysis you can use our model adaptation framework Scalismo-faces (https://github.com/unibas-gravis/scalismo-faces).
To get started with our software we prepared tutorials (http://gravis.dmi.unibas.ch/PMM/).
#### other learning resources:
http://shapemodelling.cs.unibas.ch/StatisticalShapeModelling_2017.html

## Volumetric Regression Network
This is an unguided version of the Volumetric Regression Network (VRN) for 3D face reconstruction from a single image. This method approaches the problem of reconstruction as a segmentation problem, producing a 3D volume, spatially aligned with the input image. A mesh can then be obtained by taking the isosurface of this volume.

#### model/code:
https://github.com/AaronJackson/vrn


## Regressing Robust and Discriminative 3D Morphable Models with a very Deep Neural Network
From this page you can download the ConvNet used in our paper [1] to regress discriminative 3D Morphable Model parameters for face shape and texture, directly from image intensities. The ConvNet is a ResNet 101 model based on [2].
#### project page:
http://www.openu.ac.il/home/hassner/projects/CNN3DMM/
#### model/code:
https://gist.github.com/iacopomasi/0646722f97fb087926a16b7e044ed6ed


http://www.openu.ac.il/home/hassner/projects/CNN3DMM/
https://github.com/anhttran/3dmm_cnn/


# Tools
## menpo3d - Tools for manipulating meshes
https://github.com/menpo/menpo3d
