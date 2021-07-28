# Face-Recognition
Face Recognition - Using OpenCV in python
# Requirements :-
-> pip 
-> numpy module
-> opencv-python module
-> opencv-contrib-python module

Note: Use the latest verison of pip and modules.

# Instructions for :-
**1. 'Facial_Recognition_model.py' script**

**step_1 :** Use location/path_name of 'haarcascade_frontalface_default.xml' file according to your system. 
For example: face_classifier = cv2.CascadeClassifier('C:/Users/Kush/AppData/Local/Programs/Python/Python38-32/Lib/site-packages/cv2/data/haarcascade_frontalface_default.xml')  

**step_2 :** Use location/path_name of 'Face_Samples_Dataset' folder according to your system i.e where you save this folder (In 'Face_Samples_Dataset' folder save the images of different persons in separate folders and give integral names to these sub-folders).
For example: data_path = 'C:/Users/Kush/PycharmProjects/Facial_Recogniton/Face_Samples_Dataset/'
   	    
Note: I have created a folder named 'Face_Samples_Dataset' and further created some sub-folders in it for saving 
the images of different persons, say one folder named '0' containing images of 'Narender Modi' and one more folder 
named '1' containing images of 'Virat Kohli'.
            
**step_3 :** Run the 'Facial_Recognition_model.py' script, a 'Training_data.yml' file will be generated.

**2. 'Face_Detector.py' script**

**step_1 :** Load the 'Training_data.yml' file, use location/path_name according to your system.
     For example: face_recognizer.read('C:/Users/Kush/PycharmProjects/Facial_Recogniton/Training_data.yml')

**step_2 :** Run the 'Face_Detector.py' script.  	
