# License_plate_detection

*TrainRecognizeCharactres.py* is the training process (SVC(svm) classifier is used-linear kernel) 
data folder contains the training data (images of Letters & numbers)

Then we save our model

*SegmentCharacters.py* is considering dimensions & building boxes around the plate

*PlateDetection.py* is plate detection (extracting image frames from video & detecting a plate in extracted image)

*PredictCharacter.py* predicts the character as given in the last image (3.jpeg)



Plate Detection:
![alt text](https://github.com/i-am-manish/License_plate_detection/blob/master/1.jpeg)

Plate Character Recognition:
![alt text](https://github.com/i-am-manish/License_plate_detection/blob/master/2.jpeg)

Predicted Character:
![alt text](https://github.com/i-am-manish/License_plate_detection/blob/master/3.jpeg)
Credits to: Apoorva Dave (https://github.com/apoorva-dave/LicensePlateDetector) 
