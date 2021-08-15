Real Time Face Recognition using opencv

* Install those libraries:

pip install opencv-python

conda install -c conda-forge dlib

pip install face_recognition

* Extracting features from Face
  * Create a new folder with your name inside "Images", and paste some of your face images there.
  * Execute features extracting code with this command : 
      
      python features_extracting.py
  
  to get a new file named “face_enc”, this is our trained model that we can use him to recognise faces in images or live video stream.

* For Face Recognition in Live webcam Feed, jsut execute this command : 
    
    python facerec.py
    
* For Face Recognition in Images, jsut change the line code number 16 (Path-to-img) with your image path like this ("myimage.jpg") and execute this command : 
    
    python facerec_in_img.py


