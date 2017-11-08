# 3DMM models

## 1. Morphable Face Models - An Open Framework (2017)
[downloaded data, model and paper]
#### project page:
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
http://gravis.dmi.unibas.ch/PMM/
http://shapemodelling.cs.unibas.ch/StatisticalShapeModelling_2017.html


## 2. Volumetric Regression Network
This is an unguided version of the Volumetric Regression Network (VRN) for 3D face reconstruction from a single image. This method approaches the problem of reconstruction as a segmentation problem, producing a 3D volume, spatially aligned with the input image. A mesh can then be obtained by taking the isosurface of this volume.
#### project page:
http://aaronsplace.co.uk/papers/jackson2017recon/
#### papers:
http://aaronsplace.co.uk/papers/jackson2017recon/jackson2017recon.pdf
#### model/code:
https://github.com/AaronJackson/vrn


## 3. Regressing Robust and Discriminative 3D Morphable Models with a very Deep Neural Network (ResNet-101 for 3DMM Regression)
From this page you can download the ConvNet used in our paper [1] to regress discriminative 3D Morphable Model parameters for face shape and texture, directly from image intensities. The ConvNet is a ResNet 101 model based on [2].
#### project page:
http://www.openu.ac.il/home/hassner/projects/CNN3DMM/
#### model/code:
https://gist.github.com/iacopomasi/0646722f97fb087926a16b7e044ed6ed
https://github.com/anhttran/3dmm_cnn/

Note that this project's 3DMM is (1).

## 4. Surrey 3DMM face models
3D morphable face models created at the Centre of Vision, Speech and Signal Processing at the University of Surrey. The models are available in these resolutions: 29587, 16759, 3448 and 1724 vertices. They are also available as either shape only, or shape + texture.  
#### project page:
http://cvssp.org/faceweb/3dmm/facemodels/
#### model/code:
https://github.com/patrikhuber/eos

## n/a. Large Scale Facial Model (LSFM)
The Large Scale Facial Model (LSFM) is a 3D statstical model of facial shape built from nearly 10,000 individuals.
#### project page:
https://ibug.doc.ic.ac.uk/resources/lsfm/
#### papers (check last):
https://spiral.imperial.ac.uk/bitstream/10044/1/45997/7/art%253A10.1007%252Fs11263-017-1009-7.pdf
https://link.springer.com/content/pdf/10.1007%2Fs11263-017-1009-7.pdf
https://ibug.doc.ic.ac.uk/media/uploads/documents/ijcv-16_(1).pdf
http://www.sciencemag.org/news/2017/05/computer-scientists-have-created-most-accurate-digital-model-human-face-here-s-what-it
#### model(n.a.)/code(for training the model):
https://github.com/menpo/lsfm


##### to-review:
https://arxiv.org/pdf/1701.05360.pdf
https://github.com/anilbas/3DMMasSTN
http://openaccess.thecvf.com/content_cvpr_2017/papers/Booth_3D_Face_Morphable_CVPR_2017_paper.pdf
http://openaccess.thecvf.com/content_ICCV_2017/papers/Dai_A_3D_Morphable_ICCV_2017_paper.pdf

http://publications.idiap.ch/downloads/papers/2017/Yu_FG2017_2017.pdf

# Tools
## menpo3d - Tools for manipulating meshes
https://github.com/menpo/menpo3d



