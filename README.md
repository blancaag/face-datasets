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

#### DMCSv1 (Multimodal Biometric Database of 3D Face and Hand Scans)
 -  research and educational institutions  - (applied)
The database contains 3D face and hand scans. Its core elements comprise two 3D scanning heads performing measurements using the structured light technology.The DMCSv1 database was collected in two sessions. Time interval between the sessions was approximately 2 weeks and varied depending on an individual. 
Number of individuals 	35
Number of sessions 	2
Total number of face scans 	35 x 15 x 2 = 1050
Files format 	.ply (binary)
For each acquisition the following point clouds were collected:
- scan from the first scanning head
- scan from the second scanning head
- merged scans from the scanning heads
- preprocessed and merged scans from the scanning heads
http://biometrics.dmcs.pl/en/databases/dmcsv1

#### 3D Mask Attack Database (3DMAD)
(applied)
The 3D Mask Attack Database (3DMAD) is a biometric (face) spoofing database. It currently contains 76500 frames of 17 persons, recorded using Kinect for both real-access and spoofing attacks. Each frame consists of: (1) a depth image (640x480 pixels – 1x11 bits); (2) the corresponding RGB image (640x480 pixels – 3x8 bits); (3) manually annotated eye positions (with respect to the RGB image). The data is collected in 3 different sessions for all subjects and for each session 5 videos of 300 frames are captured. The recordings are done under controlled conditions, with frontal-view and neutral expression. The first two sessions are dedicated to the real access samples, in which subjects are recorded with a time delay of ~2 weeks between the acquisitions. In the third session, 3D mask attacks are captured by a single operator (attacker). If you use this database please cite this publication: N. Erdogmus and S. Marcel. "Spoofing in 2D Face Recognition with 3D Masks and Anti-spoofing with Kinect", in IEEE Sixth International Conference on Biometrics: Theory, Applications and Systems (BTAS), 2013. Source code to reproduce experiments in the paper: https://pypi.python.org/pypi/maskattack.lbp

The 3D Mask Attack Database (3DMAD) is a biometric (face) spoofing database. It currently contains 76500 frames of 17 persons, recorded using Kinect for both real-access and spoofing attacks. Each frame consists of:
- a depth image (640x480 pixels – 1x11 bits)
- the corresponding RGB image (640x480 pixels – 3x8 bits)
- manually annotated eye positions (with respect to the RGB image).

The data is collected in 3 different sessions for all subjects and for each session 5 videos of 300 frames are captured. The recordings are done under controlled conditions, with frontal-view and neutral expression. The first two sessions are dedicated to the real access samples, in which subjects are recorded with a time delay of ~2 weeks between the acquisitions. In the third session, 3D mask attacks are captured by a single operator (attacker).

In each video, the eye-positions are manually labelled for every 1st, 61st, 121st, 181st, 241st and 300th frames and they are linearly interpolated for the rest.

The real-size masks are obtained using "ThatsMyFace.com". The database additionally contains the face images used to generate these masks (1 frontal and 2 profiles) and paper-cut masks that are also produced by the same service and using the same images.

https://www.idiap.ch/dataset/3dmad

### Others
#### LSFM (not publicly available)
LSFM is the largest-scale 3D Morphable Model (3DMM) of facial shapes ever constructed, based on a dataset of around 10,000 distinct facial identities from a huge range of gender, age and ethnicity combinations.

https://ibug.doc.ic.ac.uk/resources/lsfm/ (not available for 'non-research' purposes)
https://github.com/menpo/lsfm
https://link.springer.com/content/pdf/10.1007%2Fs11263-017-1009-7.pdf

Next three DB - not public: pricing below
http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html

#### BU-3DFE Database (Static Data)
BU-3DFE (Binghamton University 3D Facial Expression) includes 100 subjects with 2,500 facial expression models. The BU-3DFE database is available to the research community (e.g., areas of interest come from as diverse as affective computing, computer vision, human computer interaction, security, biomedicine, law-enforcement, and psychology). The database contains 100 subjects (56% female, 44% male), ranging age from 18 years to 70 years old, with a variety of ethnic/racial ancestries, including White, Black, East-Asian, Middle-east Asian, Indian, and Hispanic Latino.

#### BU-4DFE Database (Dynamic Data)
To analyze the facial behavior from a static 3D space to a dynamic 3D space, BU-3DFE Database is extended and a new database is formed: BU-4DFE (3D + time): A 3D Dynamic Facial Expression Database. A newly created high-resolution 3D dynamic facial expression database are presented, which is made available to the scientific research community. The 3D facial expressions are captured at a video rate (25 frames per second). For each subject, there are six model sequences showing six prototypic facial expressions (anger, disgust, happiness, fear, sadness, and surprise), respectively. Each expression sequence contains about 100 frames. The database contains 606 3D facial expression sequences captured from 101 subjects, with a total of approximately 60,600 frame models. Each 3D model of a 3D video sequence has the resolution of approximately 35,000 vertices. The texture video has a resolution of about 1040×1329 pixels per frame. The resulting database consists of 58 female and 43 male subjects, with a variety of ethnic/racial ancestries, including Asian, Black, Hispanic/Latino, and White.

#### BP4D-Spontanous Database
Because posed and un-posed (aka “spontaneous”) 3D facial expressions differ along several dimensions including complexity and timing, well-annotated 3D video of un-posed facial behavior is needed. Therefore, newly developed 3D video database of spontaneous facial expressions in a diverse group of young adults is introduced - BP4D-Spontanous: Binghamton-Pittsburgh 3D Dynamic Spontaneous Facial Expression Database. Well-validated emotion inductions were used to elicit expressions of emotion and paralinguistic communication. Frame-level ground-truth for facial actions was obtained using the Facial Action Coding System. Facial features were tracked in both 2D and 3D domains using both person-specific and generic approaches. The work promotes the exploration of 3D spatiotemporal features in subtle facial expression, better understanding of the relation between pose and motion dynamics in facial action units, and deeper understanding of naturally occurring facial action. The database includes 41 participants (23 women, 18 men). They were 18-29 years of age; 11 were Asian, 6 were African-American, 4 were Hispanic, and 20 were Euro-American. An emotion elicitation protocol was designed to elicit emotions of participants effectively. Eight tasks were covered with an interview process and a series of activities to elicit eight emotions. The database is structured by participants. Each participant is associated with 8 tasks. For each task, there are both 3D and 2D videos. As well, the metadata include manually annotated action units (FACS AU), automatically tracked head pose and 2D/3D facial landmarks. The database is in the size of about 2.6 TB (without compression).












3DMM models:

https://github.com/AaronJackson/vrn
https://gist.github.com/iacopomasi/0646722f97fb087926a16b7e044ed6ed


http://www.openu.ac.il/home/hassner/projects/CNN3DMM/
https://github.com/anhttran/3dmm_cnn/


