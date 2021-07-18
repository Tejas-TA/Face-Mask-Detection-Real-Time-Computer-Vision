## Face Mask Detection Real Time / Computer Vision / Object Detection

<img src="https://github.com/Tejas-TA/Face-Mask-Detection-Real-Time-Computer-Vision/blob/main/Real%20Time%20Face%20Detection%20Demo.gif" width = "100%" height="100%">

<hr>

Detecting whether a person is wearing a mask or not in real time using Python, Keras, OpenCV, TensorFlow, NumPy, etc. Folder consists of 1900 masked images and unmasked images. <br>

### Project Walkthrough -<br>
### Data Preprocessing<br>
1.	Created 2 lists – data [] and labels []<br>
2.	In data [], arrays of all the images will be appended and in labels [], arrays of “with_mask” and “without_mask” which will be converted using LabelBinarizer from scikit learn library<br>
3.	All the images are listed using load_img function from Keras library, and then attached corresponding labels to it<br>
4.	Target size is set to 224*224(width and height) so that model is perfect.<br>
5.	Using img_to_array from Keras, all the images are converted to arrays.<br>
6.	MobileNet is applied so preprocess_input is used.<br>
7.	 Train Test split is done.<br>

### Building the network<br>
<img alt="image" src="https://user-images.githubusercontent.com/13360641/126059769-5577527f-98f5-44a5-bcdc-dd5f24c27a72.png" width = "100%" height="100%">

<br>
### Train the Model – <br>
Below graph summarizes the training<br>
<img alt="image" src="https://github.com/Tejas-TA/Face-Mask-Detection-Real-Time-Computer-Vision/blob/main/plot.png" width = "100%" height="100%"> <br><br>
Face Detection using Camera (Real-Time)<br>
Using deploy.prototxt and res10_300x300_ssd_iter_140000.caffemodel face is detected and using our deep learning model mask is detected. Please refer “Detect Mask Video.ipynb” for code.


<hr>

LinkedIn - https://www.linkedin.com/in/tejasta/ <br>
Email Id - tejasta@gmail.com <br>
Blogs - https://tejasta.medium.com/ <hr>
  
