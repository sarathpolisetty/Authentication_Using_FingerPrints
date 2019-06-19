# Authentication_Using_FingerPrints
Reading Finger prints and storing them in the database 
are the major tasks that have to be concentrated when working on any projects related to fingerprints.


# Reading FingerPrints
Reading fingerprints can be done using different types of fingerprint sensors like morphos, r30x sensors etc which are widely available in the market.
Let us see how to read fingerprints using r30x fingerprint sensor.

![Picture2](https://user-images.githubusercontent.com/29407642/59752575-22561400-92a0-11e9-8194-da80d499a726.jpg)

# Reading fingerprints using r307 fingerprint sensor
Requirements:- Arduino board, R30x fingerprint module(x be an integer from 5-9).

![Picture3](https://user-images.githubusercontent.com/29407642/59752834-8e387c80-92a0-11e9-87fb-6aca39586050.jpg)

Sensors or any other application oriented electronic devices can be operated only through connecting them to a physical programmable circuit board, which has a software support used to write and upload computer code to the physical board (for example:- ARDUINO, Rasberry_pi etc).
Reading fingerprints can be achieved through below 2 steps:-
1. Connecting R307 fingerprint sensor to ARDUIONO board,
   
![Picture2](https://user-images.githubusercontent.com/29407642/59752399-ce4b2f80-929f-11e9-9f5d-92791d551938.jpg)

Connect the both devices as shown in the picture.                                                                                         
   ie. (i) TD (pin 3 of P1) connects with RXD (receiving pin of Arduino)                                                                   
       (ii) RD (pin 4 of P1) connects with TXD (transferring pin of Arduino).
       
2. Uploading corresponding Arduino programme in to arduino board.                                                                           
   Upload the code at below link into the arduino board from arduino IDE.(We can download Arduino from https://www.arduino.cc/en/Main/Donate)                                                                
   https://github.com/adafruit/Adafruit-Fingerprint-Sensor-Library/blob/master/examples/enroll/enroll.ino
   
Now we can happily enroll our fingerprints in the fingerprint sensor.

# Moving fingerprints to database
Fingerprint sensors will have a limited memory space to store the fingerprints ie, nearly 1000 images. So, it is better to store the fingerprints in external data bases which can also spread the applications of fingerprints.
This can be achieved through 3 steps.
1. Connecting Arduino board to pc/laptop.                                                                                                                                                                                                                                          This can be done using a USB cable.
   ![arduino_pc](https://user-images.githubusercontent.com/29407642/59757328-26d2fa80-92a9-11e9-89dd-c925ce26f344.jpg)
2. Creating a python interface to establish communication between computer and Arduino.
3. Uploading corresponding Arduino programme in to arduino board.





 
