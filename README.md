# faceRecognition

This repository contains code for facial recognition using openCV and python with a tkinter gui interface.

Technology used :
-openCV 
-Python
-tkinter 
-LBPH algorithm


How it works :
To test the code you can run the train.py file. A window will pop up asking you to enter the name and the id to register the student. On clicking the button "take images". The software will connect to the default camera of your system and it will take 60 images of your face.
After taking image sample we have to click Train Image button.Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.
Now all initial setups are done. By clicking Track Image button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image otherwise it will print "unkown". Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time.


