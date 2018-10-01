# DrivingLicence

This repository aims to extract basic information from image of a given driving licence using ocr.
drive.py is the python code for information extraction as text.
Software packages used are:-
1. opencv-To read image
2. pytesseract-To extract string from image 
3. matplotlib- To show image

noise_cancellation.py is imported in drive.py to reduce noise and get precise results.

driving license.ipynb is the stepwise implementation in jupyter.

Input

![Input](https://github.com/gggggggolu/DrivingLicense/blob/master/drive.jpg)

Output

 'Licence No . : DL-0420110149646 (P) N',

 'Name : ANURAG BREJA',
 
 'Address:HNO-178 A2/B MIG FLATS PASCHIMVIHAR,DELHI 110063',
 
 'DOB: 09/02/1976 BG: 0',
 
 'SIWID : BODH RAJ BREJA'
