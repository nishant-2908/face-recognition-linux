# face-recognition-linux
This repository contains the Project for the Face Detection and Face Recognition in Linux or MacOS 
### Python Version: 3.11 or above
### Start using this project
- Download the zip file
- Open the folder where you have downloaded the zip file
- Extract the folder
- Now add some photos to the directory `face-recognition-linux/known_persons` in the folder where the zip is extracted
- Now add some data into the `crime-history-sample.csv` (Caution: Do not edit the headers, only add the names and the other data, but the names of the person in the csv should be the same mentioned in the `known_persons` directory.
- Save the `crime-history-sample.csv` file and open the terminal in the folder where you have extracted the zip file.

Run the following commands  
`sudo apt update & sudo apt upgrade -y & sudo apt-get update & sudo apt-get upgrade -y`  
`sudo pip3 install face_recognition numpy pandas opencv-python`  
`python3 capture_faces.py`  
