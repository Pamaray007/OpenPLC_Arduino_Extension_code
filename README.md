#OpenPLC New Feature- Arduino Sketch on PLC Programs
****************************************************************
OpenPLC Arduino Extension code used for the video tutorial

https://youtu.be/JjRy6S8KPwo

The Arduino Extension is a newly added feature to the OpenPLC editor. With this extension, now you can add Arduino Sketches that will run alongside your PLC program on the same board.

#What you can do with this Extension
You can create your own functions and also #include external libraries as long as they are also installed on your Arduino IDE.

#What you need not to do 
Using this extension, you need to know that codes that will block the loop() function such as long while loop or delays are not allowed,because it will block your PLC code as well resulting in unpredictably behavior.

