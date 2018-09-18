# FingerPrint_Authentication-Automation-of-log-books-
Getting Finger prints using Adafruit_R30x_Fingerprint module and storing them dynamically where ever you want(external memory) instead of in the memory of R3ox module.
The major part that have to be concentrated when working on any projects regarding fingerprints is how to get the finger prints to the local storage.
Here is the solution for that:-
Initially we can get the images of fingerprints using some fingerprint scanner like R307 along with aurdino.
For reading the fingerprint images, one can use "Adafruit fingerprint library" which has a lot number of functions to read the image from scanner, to convert that to template etc. (one has to clearly understand the programmes got with the package, to use them efficiently.)
Using the getimage() function present in the programme called Register fingerprint, in Adafruit package one can get the image of fingerprint to the r30x module.
After that using python programming one can communicate to the arduino board, in tern with the fingerprint module.(Arduino + Python).
From that we can get the image of the fingerprint from the R30x module to arduino, then to python programme and finally from python programme to local storage/Cloud/Sql Data base etc..
Here I will explain the process step by step.
CONNECTING ARDUINO AND ADAFRUIT FINGERPRINT MODULE(R30x series only). 
