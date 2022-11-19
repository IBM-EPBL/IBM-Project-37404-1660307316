# IBM-Project-37404-1660307316
A Gesture-based Tool for Sterile Browsing of Radiology Images
Gesture Based Tool for Sterile Browsing of Radiology Images
Home page:                                         
  ![image](https://user-images.githubusercontent.com/114077595/202844329-5bc16e3d-83f7-4ca7-bd2e-4ff3f16770bb.png)
  
  Introduction page:
  ![image](https://user-images.githubusercontent.com/114077595/202844349-1aaf653d-e228-44c4-a03d-94a5cbe2f669.png)

Model launch page: 
![image](https://user-images.githubusercontent.com/114077595/202844363-5e7e55d5-686c-4e2a-9c29-d4cd0eedd6af.png)

Predicting results using Random Image:
![image](https://user-images.githubusercontent.com/114077595/202844371-0ad94b8e-eb81-4c98-bd07-c4013bcbe496.png)
![image](https://user-images.githubusercontent.com/114077595/202844378-6f421b9e-fb4c-43ce-b290-b6123eaa7fd1.png)

 In this project we have used CNN to first train the model on the images of different hand gestures. Then we made a web portal using Flask where user can input any image on which he/she wants to perform the operations. After uploading the image, our portal uses the integrated webcam to capture the video frame using OpenCV. The gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified. If the prediction is 1 - image is Resized into (200,200), 2 - image is rotated by -45॰, 3 - image is blurred , 4 - image is Resized into (400,400) , 5 - image is converted into grayscale.

Flask Folder
https://github.com/IBM-EPBL/IBM-Project-37404-1660307316/tree/main/Final%20Deliverables

Dataset
https://github.com/IBM-EPBL/IBM-Project-37404-1660307316/tree/main/Project%20Development/Sprint%201/Dataset

API Used for IBM Model Training
https://api.us-south.cf.cloud.ibm.com
