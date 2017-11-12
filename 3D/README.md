http://www.face-rec.org/databases/

## 3D
http://areeweb.polito.it/ricerca/cgvg/3DDB.html

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

#### EURECOM Kinect Face Dataset (EURECOM KFD)
(applied)
The Dataset consists of multimodal facial images of 52 people (14 females, 38 males) acquired with a Kinect sensor. The data is captured in two sessions at different intervals (of about two weeks). In each session, 9 facial images are collected from each person according to different facial expressions, lighting and occlusion conditions: neutral, smile, open mouth, left profile, right profile, occluded eyes, occluded mouth, side occlusion with a sheet of paper and light on. An RGB color image, a depth map (provided both as a bitmap depth image and a text file containing the original depth levels sensed by Kinect) as well as the associated 3D data are provided for all samples. In addition, the dataset includes 6 manually labeled landmark positions for every face: left eye, right eye, tip of the nose, left side of mouth, right side of mouth and the chin. Other information, such as gender, year of birth, ethnicity, glasses (whether a person wears glasses or not) and the time of each session are also available.
http://rgb-d.eurecom.fr/

#### PhotoFace: Face recognition using photometric stereo
(applying)
This unique 3D face database is amongst the largest currently available, containing 3187 sessions of 453 subjects, captured in two recording periods of approximately six months each. The Photoface device was located in an unsupervised corridor allowing real-world and unconstrained capture. Each session comprises four differently lit colour photographs of the subject, from which surface normal and albedo estimations can be calculated (photometric stereo Matlab code implementation included). This allows for many testing scenarios and data fusion modalities. Eleven facial landmarks have been manually located on each session for alignment purposes. Additionally, the Photoface Query Tool is supplied (implemented in Matlab), which allows for subsets of the database to be extracted according to selected metadata e.g. gender, facial hair, pose, expression.
http://www1.uwe.ac.uk/et/mvl/projects/facerecognition.aspx
http://ieeexplore.ieee.org/document/5981840/?reload=true

#### UMB database of 3D occluded faces
(applied)
The University of Milano Bicocca 3D face database is a collection of multimodal (3D + 2D colour images) facial acquisitions. The database is available to universities and research centers interested in face detection, face recognition, face synthesis, etc. The UMB-DB has been acquired with a particular focus on facial occlusions, i.e. scarves, hats, hands, eyeglasses and other types of occlusion wich can occur in real-world scenarios.

143 subjects, (98 male, 45 female; a pair of male twins and a baby included);
1473 total acquisitions (3D + colour 2D);
4 facial expressions: neutral, smiling, bored, hungry;
- 3 neutral acquisition per subject;
- 1 acquisition per subject for the smiling, bored and hungry expressions.
883 non-occluded acquisitions;
590 occluded acquisitions, using various objects:
http://www.ivl.disco.unimib.it/minisites/umbdb//description.html

#### Texas 3D Face Recognition Database (Texas 3DFRD)
(applied)
Texas 3D Face Recognition database (Texas 3DFRD) contains 1149 pairs of facial color and range images of 105 adult human subjects. The images were acquired at the company Advanced Digital Imaging Research (ADIR), LLC (Friendswood, TX), formerly a subsidiary of Iris International, Inc. (Chatsworth, CA), with assistance from research students and faculty from the Laboratory for Image and Video Engineering (LIVE) at The University of Texas at Austin. This project was sponsored by the Advanced Technology Program of the National Institute of Standards and Technology (NIST). The database is being made available by Dr. Alan C Bovik at UT Austin. The images were acquired using a stereo imaging system at a high spatial resolution of 0.32 mm. The color and range images were captured simultaneously and thus are perfectly registered to each other. All faces have been normalized to the frontal position and the tip of the nose is positioned at the center of the image. The images are of adult humans from all the major ethnic groups and both genders. For each face, is also available information about the subjects' gender, ethnicity, facial expression, and the locations 25 anthropometric facial fiducial points. These fiducial points were located manually on the facial color images using a computer based graphical user interface. Specific data partitions (training, gallery, and probe) that were employed at LIVE to develop the Anthropometric 3D Face Recognition algorithm are also available.
http://live.ece.utexas.edu/research/texas3dfr/

#### The Basel Face Model (BFM)
(2009/2017)
(downloded)
The Basel Face Model (BFM) is a 3D Morphable Face Model constructed from 100 male and 100 female example faces. The BFM consists of a generative 3D shape model covering the face surface from ear to ear and a high quality texture model. The model can be used either directly for 2D and 3D face recognition or to generate training and test images for any imaging condition. Hence, in addition to being a valuable model for face analysis it can also be viewed as a meta-database which allows the creation of accurately labeled synthetic training and testing images. To allow for a fair comparison with other algorithms, we provide both the training data set (the BFM) and the model fitting results for several standard image data sets (CMU-PIE, FERET) obtained with our fitting algorithm. The BFM web page additionally provides a set of registered scans of ten individuals, together with a set of 270 renderings of these individuals with systematic pose and light variations. These scans are not included in the training set of the BFM and form a standardized test set with a ground truth for pose and illumination.
http://faces.cs.unibas.ch/bfm/
http://gravis.dmi.unibas.ch/PMM/
#### !!!! check github models

#### The Bosphorus Database
(registered - applying)
The Bosphorus Database is a new 3D face database that includes a rich set of expressions, systematic variation of poses and different types of occlusions. This database is unique from three aspects: (1) The facial expressions are composed of judiciously selected subset of Action Units as well as the six basic emotions, and many actors/actresses are incorporated to obtain more realistic expression data; (2) A rich set of head pose variations are available; (3) Different types of face occlusions are included. Hence, this new database can be a very valuable resource for development and evaluation of algorithms on face recognition under adverse conditions and facial expression analysis as well as for facial expression synthesis.
The Bosphorus Database is intended for research on 3D and 2D human face processing tasks including expression recognition, facial action unit detection, facial action unit intensity estimation, face recognition under adverse conditions, deformable face modeling, and 3D face reconstruction. There are 105 subjects and 4666 faces in the database. This database is unique in three aspects:

1) Rich repertoire of expressions:
- Up to 35 expressions per subject
- FACS scoring (includes intensity and asymmetry codes for each AU)
- One third of the subjects are professional actors/actresses
2) Systematic head poses (13 yaw and pitch rotations)
3) Varieties of face occlusions (beard & moustache, hair, hand, eyeglasses)
Data Acquisition:
Facial data are acquired using structured-light based 3D system. Acquisitions are single view, and subjects were made to sit at a distance of about 1.5 meters away from the 3D digitizer. The sensor resolution in x, y & z (depth) dimensions are 0.3mm, 0.3mm and 0.4mm respectively, and colour texture images are high resolution (1600x1200 pixels). A 1000W halogen lamp was used in a dark room to obtain homogeneous lighting for good quality texture images.
http://bosphorus.ee.boun.edu.tr/register.aspx?returnurl=http%3a%2f%2fbosphorus.ee.boun.edu.tr%2fhowtoobtain.aspx

#### BJUT-3D Chinese Face Database
(research access)
The BJUT-3D is a three dimension face database including 500 Chinese persons. There are 250 females and 250 males in the database. Everyone has a 3D face data with neutral expression and without accessories. Original high-resolution 3D face data is acquired by the CyberWare 3D scanner in given environment, Every 3D face data has been preprocessed, and cut the redundant parts. Now the face database is available for research purpose only. The Multimedia and Intelligent Software Technology Beijing Municipal Key Laboratory in Beijing University of Technology is serving as the technical agent for distribution of the database and reserves the copyright of all the data in the database.

#### FRAV3D Database
(research access)
This database contains 106 subjects, with approximately one woman every three men. The data were acquired with a Minolta VIVID 700 scanner, which provides texture information (2D image) and a VRML file (3D image). If needed, the corresponding range data (2.5D image) can be computed by means of the VRML file. Therefore, it is a multimodal database (2D, 2.5D y 3D). During all time, a strict acquisition protocol was followed, with controlled lighting conditions. The person sat down on an adjustable stool opposite the scanner and in front of a blue wall. No glasses, hats or scarves were allowed. A total of 16 captures per person were taken in every session, with different poses and lighting conditions, trying to cover all possible variations, including turns in different directions, gestures and lighting changes. In every case only one parameter was modified between two captures. This is one of the main advantages of this database, respect to others. This database is delivered for free exclusively for research purposes.

#### 3D_RMA database
(research access)
The 3D_RMA database is a collection of two sessions (Nov 1997 and Jan 1998) consisting of 120 persons. For each session, three shots were recorded with different (but limited) orientations of the head. Details about the population and typical problems affecting the quality are given in the referred link. 3D was captured thanks to a first prototype of a proprietary system based on structured light (analog camera!). The quality was limited but sufficient to show the ability of 3D face recognition. For privacy reasons, the texture images are not made available. In the period 2003-2008, this database has been downloaded by about 100 researchers. A few papers present recognition results with the database (like, of course, papers from the author).

#### GavabDB: 3D face database, GAVAB research group, Universidad Rey Juan Carlos, Spain
(research access)
GavabDB is a 3D face database. It contains 549 three-dimensional images of facial surfaces. These meshes correspond to 61 different individuals (45 male and 16 female) having 9 images for each person. The total of the individuals are Caucasian and their age is between 18 and 40 years old. Each image is given by a mesh of connected 3D points of the facial surface without texture. The database provides systematic variations with respect to the pose and the facial expression. In particular, the 9 images corresponding to each individual are: 2 frontal views with neutral expression, 2 x-rotated views (ą30o, looking up and looking down respectively) with neutral expression, 2 y-rotated views (ą90o, left and right profiles respectively) with neutral expression and 3 frontal gesture images (laugh, smile and a random gesture chosen by the user, respectively).

#### The Extended M2VTS Database, University of Surrey, UK
(pay dataset)
Contains four recordings of 295 subjects taken over a period of four months. Each recording contains a speaking head shot and a rotating head shot. Sets of data taken from this database are available including high quality colour images, 32 KHz 16-bit sound files, video sequences and a 3D model.
http://www.ee.surrey.ac.uk/CVSSP/xm2vtsdb/

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

• 3D Facial Expression Database:  $400 per year
• 4D Facial Expression Database:  $1,000 per year
• 3D + 4D combination: $1,250 per year
• BP4D (“Binghamton-Pittsburgh”) Spontaneous Database:  $1,250 per year
• BP4D+ only accessible as part of an R&D collaboration with the professors who created it.
