# 2D-3D-face-datasets

## 2D

#### WIDER FACE
http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/index.html

#### NIST-provided (IJB-B + FRVT (testing only))
The IARPA Janus Benchmark-B face challenge (IJB-B) defines eight challenges addressing verification, identification, detection, clustering and processing of crowded images.  This is supported by a the IJB-B set of 67000 face images, 7000 face videos, and 10000 non-face images.

https://www.nist.gov/programs-projects/face-challenges

#### AFW
http://www.ics.uci.edu/~xzhu/face/

#### 300-W (LFPW + AFW + HELEN + IBUG)
https://ibug.doc.ic.ac.uk/resources/300-W/

#### MALF
http://www.cbsr.ia.ac.cn/faceevaluation/

#### FDDB (2009/10)
A data set of face regions designed for studying the problem of unconstrained face detection. This data set contains the annotations for 5171 faces in a set of 2845 images taken from the Faces in the Wild data set. More details can be found in the technical report below.

http://vis-www.cs.umass.edu/fddb/index.html

#### VGGFace
http://www.robots.ox.ac.uk/~vgg/data/vgg_face/

#### VGGFace2
http://www.robots.ox.ac.uk/~vgg/data/vgg_face2/
(paper - https://arxiv.org/abs/1710.08092)


## 3D

### Landmarks
#### MEMPO
All the training images of the dataset are obtained from the FDDB, AFLW,  as well as from YouTube (under creative commons license) database. In order to develop a comprehensive benchmark for evaluating 3D facial landmark localisation 
algorithms in the wild in arbitrary poses, we have fitted with state-of-the-art 3D facial morphable models [4] all the images provided by the 300 W and Menpo challenges. The parameters of the model have been carefully selected and all fittings have been visually inspected. The final landmarks have been manually corrected (if needed). We found that for better 3D face landmark localisation more landmarks are required in the boundary, hence we provide 16 more landmarks. The above data can be used for training models. In summary, for static images we provide (a) the x,y coordinates in the image space that correspond to the projections of a 3D model of the face and (b) x,y,z coordinates of the landmarks in the model space. In total, we provide 84 landmarks. The data are available here: 3D Menpo static. Please see Fig. 1 for the markup and 2 to 8 for some examples.
https://ibug.doc.ic.ac.uk/resources
https://github.com/menpo/lsfm

#### LS3D-W
LS3D-W is a large-scale 3D face alignment dataset constructed by annotating the images from AFLW[2], 300VW[3], 300W[4] and FDDB[5] in a consistent manner with 68 points using the automatic method.

https://www.adrianbulat.com/face-alignment

### Others
#### LSFM
LSFM is the largest-scale 3D Morphable Model (3DMM) of facial shapes ever constructed, based on a dataset of around 10,000 distinct facial identities from a huge range of gender, age and ethnicity combinations.

https://ibug.doc.ic.ac.uk/resources/lsfm/ (not available for a 'non-research' dataset)
https://github.com/menpo/lsfm
https://link.springer.com/content/pdf/10.1007%2Fs11263-017-1009-7.pdf
