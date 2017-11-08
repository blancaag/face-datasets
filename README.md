# 2D-3D-face-datasets

http://www.face-rec.org/databases/

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
The dataset contains 3.31 million images of 9131 subjects (identities), with an average of 362.6 images for each subject. Images are downloaded from Google Image Search and have large variations in pose, age, illumination, ethnicity and profession (e.g. actors, athletes, politicians).The dataset was collected with three goals in mind:
(i) to have both a large number of identities and also a large number of images for each identity;
(ii) to cover a large range of pose, age and ethnicity; and
(iii) to minimize the label noise through automated and manual filtering,
The whole dataset is split to a training set (including 8631 identites) and a test set (including 500 identites). The identities in the training set are disjoint with the ones in benchmark datasets IJB-A and IJB-B. 
http://www.robots.ox.ac.uk/~vgg/data/vgg_face2/
(paper - https://arxiv.org/abs/1710.08092)

## 3D

### Landmarks
#### MEMPO
All the training images of the dataset are obtained from the FDDB, AFLW,  as well as from YouTube (under creative commons license) database. In order to develop a comprehensive benchmark for evaluating 3D facial landmark localisation 
algorithms in the wild in arbitrary poses, we have fitted with state-of-the-art 3D facial morphable models [4] all the images provided by the 300 W and Menpo challenges. The parameters of the model have been carefully selected and all fittings have been visually inspected. The final landmarks have been manually corrected (if needed). We found that for better 3D face landmark localisation more landmarks are required in the boundary, hence we provide 16 more landmarks. The above data can be used for training models. In summary, for static images we provide (a) the x,y coordinates in the image space that correspond to the projections of a 3D model of the face and (b) x,y,z coordinates of the landmarks in the model space. In total, we provide 84 landmarks. The data are available here: 3D Menpo static. Please see Fig. 1 for the markup and 2 to 8 for some examples.
+
Furthermore, we provide 3D facial landmarks for all the videos of 300 VW competition. The landmarks in this case have been produced in a more sophisticated way. In short, a non-rigid structure from motion algorithm was used on the original 2D landmarks of the 300 VW competition to get a first estimate of the 3D coordinates. Afterwards, a modified version of [4] was used that fits all the frames of the video simultaneously. Finally, all landmarks have been visually inspected and manually corrected if needed.
https://ibug.doc.ic.ac.uk/resources
https://arxiv.org/pdf/1701.05360.pdf [4]
https://github.com/menpo/lsfm [4]

#### LS3D-W
LS3D-W is a large-scale 3D face alignment dataset constructed by annotating the images from AFLW[2], 300VW[3], 300W[4] and FDDB[5] in a consistent manner with 68 points using the automatic method.
https://www.adrianbulat.com/face-alignment

#### FLORENCE 3D/2D (acquired)
The dataset consists of:
- High-resolution 3D scans of human faces from many subjects.
- Several video sequences of varying resolution, conditions and zoom level for each subject.
Each subject is recorded in the following situations:
- In a controlled setting in HD video.
- In a less-constrained (but still indoor) setting using a standard, PTZ surveillance camera.
- In an unconstrained, outdoor environment under challenging recording conditions.
Each subject is composed from the following:
- Four High Quality 3D Model (two frontal models once for test and one for training, one left side model, one right side model). In the case the subject wears glasses, we provide a 3D Model also with the glasses.
- One HD Video (1280 x 720) in cooperative environment recorded at 4 levels of zoom. The subject here is asked to generate some out-of-plane head rotations, viewing six points: top-right,top-left, middle-right,middle-left,bottom-right,bottom-left. Frame rate 25 fps.
- One Indoor Video (704×576 – 4CIF) from a PTZ  with 3 levels of zoom. Here the subject is asked to be spontaneous. Frame rate 25 fps.
- One Outdoor Video (736×544) from a PTZ with 3 levels of zoom. Here the subject is asked to be spontaneous, but this time the recorded video is very challenging. Frame rate 5-7 fps.
Generally a subject file is about 400MB and it contains the four models in three different formats: OBJ, PLY and VRML.
Regarding the video they are video encoded in MJPEG.
https://www.micc.unifi.it/resources/datasets/florence-3d-faces/

#### FLORENCE superface
The Florence Superface dataset comprises low-resolution and high-resolution 3D scans aiming to investigate innovative 3D face recognition solutions that use scans at different resolutions. Currently, 20 subjects are included in the dataset, but enrolling is still ongoing. For each subject, the dataset includes:
- A 2D/3D video sequence acquired with the Microsoft Kinect. During capture, subjects sit in front of the camera with the face at an approximate distance of 80cm from the sensor. Subjects are also asked to slightly rotate the head around the yaw axis up to an angle of about 60-70 degrees, so that both the left and right side of the face are visible to the sensor. This results in video sequences lasting approximately 10 to 15 sec. Videos are released as a sequence of depth (16 bits) and rgb (24 bits) frames in PNG format;
- A 3D high-resolution face scan acquired with the 3dMD scanner: 3D mesh with about 40,000 vertices and 80,000 facets; texture stereo image with a resolution of 3341 x 2027 pixels. The geometry of the mesh is highly accurate with an average RMS error of about 0.2mm or better (VRML format).
https://www.micc.unifi.it/resources/datasets/florence-superface/

### Others
#### LSFM (not publicly available)
LSFM is the largest-scale 3D Morphable Model (3DMM) of facial shapes ever constructed, based on a dataset of around 10,000 distinct facial identities from a huge range of gender, age and ethnicity combinations.

https://ibug.doc.ic.ac.uk/resources/lsfm/ (not available for a 'non-research' dataset)
https://github.com/menpo/lsfm
https://link.springer.com/content/pdf/10.1007%2Fs11263-017-1009-7.pdf

3DMM models:

https://github.com/AaronJackson/vrn
https://gist.github.com/iacopomasi/0646722f97fb087926a16b7e044ed6ed


http://www.openu.ac.il/home/hassner/projects/CNN3DMM/
https://github.com/anhttran/3dmm_cnn/


