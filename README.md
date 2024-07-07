**Procedure**
1.	First, you have to create a gesture database. For that, run CreateGest.py. Enter the gesture name and you will get 2 frames displayed. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
2.	Repeat this for all the features you want.
3.	Run CreateCSV.py for converting the images to a CSV file
4.	If you want to train the model, run 'TrainEmojinator.py'
5.	Finally, run Emojinator.py for testing your model via webcam

Technologies Used -
-	Intel Optimised Python.
-	Intel Optimised TensorFlow.
-	Keras
-	OpenCV
![image](https://github.com/anuvce/OWN-EMOJI-CREATOR-WITH-ML-EMOJIFY/assets/73528611/873a9318-e98f-4d68-955b-cb259f07ff00)

