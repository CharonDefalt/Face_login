# Face_login
login with face using python

Installation

You can choose to install any environment either system, pipenv, anaconda etc
I used Visual Code and Python 3.8 and installed these using pip(Google gives more on this)

pip install opencv-python pip install opencv-contrib-python

pip install pillow

pip install pandas

pip install numpy

#######################################################################

Running the test for Face login

1. git clone this page and unzip the zip files
2. Run Readface.py to take some images of user for login, It asks for Name and Id in console
Note: *if didnt work change profile.csv manual and move all images to the TrainingImages*
3. Run Train.py, this will train all images taken and put in TrainData Folder
4. Run Detectface.py to detect the face and Login, Console shows the login messages

Finally Face login is Successful and Unknow faces tried to login are stored in UnkownFaces folder 


Tested on Lubuntu
