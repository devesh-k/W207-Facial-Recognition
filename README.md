# W207-Facial-Recognition  
Final project for w207  
Group Members:  
Devesh Khandelwal, Sanjay Saravanan, Sony Wicaksono, Erik Zinn  
  
The objective of this task is to predict keypoint positions on face images. This can be used as a building block in several applications, such as:  
* tracking faces in images and video  
* analysing facial expressions  
* detecting dysmorphic facial signs for medical diagnosis  
* biometrics / face recognition  
Detecing facial keypoints is a very challenging problem.  Facial features vary greatly from one individual to another, and even for a single individual, there is a large amount of variation due to 3D pose, size, position, viewing angle, and illumination conditions. Computer vision research has come a long way in addressing these difficulties, but there remain many opportunities for improvement.  

Each predicted keypoint is specified by an (x,y) real-valued pair in the space of pixel indices. There are 15 keypoints, which represent the following elements of the face:  
left_eye_center, right_eye_center, left_eye_inner_corner, left_eye_outer_corner, right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end, left_eyebrow_outer_end, right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip, mouth_left_corner, mouth_right_corner, mouth_center_top_lip, mouth_center_bottom_lip
Left and right here refers to the point of view of the subject.  
In some examples, some of the target keypoint positions are misssing (encoded as missing entries in the csv, i.e., with nothing between two commas).  
The input image is given in the last field of the data files, and consists of a list of pixels (ordered by row), as integers in (0,255). The images are 96x96 pixels.  
https://www.kaggle.com/c/facial-keypoints-detection/data


