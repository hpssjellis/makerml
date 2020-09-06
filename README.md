# makerml
Machine Learning for anyone who is not a Data Scientist, Computer Science Researcher or Mathematician.


# General:

Started Spetember 7th, 2020

This will mainly use Javascript https://www.tensorflow.org/js to make Deep Learning models and to view them, then tfjs_convert and tflite_convert to convert the models to c header files and then TensorflowMicro a subset of tensorflowLite https://www.tensorflow.org/lite to run the models on Arduino style microcontrollers.


Information here will be condenscend and simplified from these sites:

1. https://www.rocksetta.com/tensorflowjs/  but I work mainly from the github website version at https://hpssjellis.github.io/beginner-tensorflowjs-examples-in-javascript/

2. The gitpod version of https://github.com/hpssjellis/Gitpod-auto-tensorflowJS-to-arduino   by using this link https://gitpod.io/#github.com/hpssjellis/Gitpod-auto-tensorflowJS-to-arduino

3. This Machine Learning site using the PortentaH7 which should work for many other Arduino boards (SeeeduinoXIAO, Nano 33BLESense PortentaH7 and hopefully the ESP32 eventually)  https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7/tree/master/m09-Tensoflow

4. Online Arduino IDE at https://create.arduino.cc/ You can use this even without an Arduino. If you have an arduino you will need to install the arduino create plugin for your computer at https://create.arduino.cc/getting-started/plugin/welcome .

5. Draft. looking into https://www.programmingelectronics.com/ as an online arduino testing area. not sure about pricing.



# Lets Get Started:

1. My easiest Deep Learning example is at https://www.rocksetta.com/tensorflowjs/beginner-keras/20keras-xOr.html Try to understand as much as you can about this one page program as all of my other programs will be in some ways similar. It uses 2 inputs that are either on or off and ouputs one decimal number about how close it things the answer is to either 1 or 0. Make sure you change variables and try to improve the example. xOr means if both inputs are the same the answer is close to 0. If inputs are differrent then it outputs close to 1. Note near the bottom of the page that you can save your designed model.

2. Use this gitpod link https://gitpod.io/#github.com/hpssjellis/Gitpod-auto-tensorflowJS-to-arduino to convert your TensorflowJS model to a c header file calle d model.h . Checkout how big the file is by looking at the last line. Note that the "MyExamples" folder shows how things should eventually look. The "myFolder" is where you do your work. You should be able to click on model.h and see what is contains.

3. For this course we will use the Arduino Create online IDE, but many people will have installed the regular Arduino IDE or the Pro Arduino IDE any of the three can be used even if you don't have the corresponding Arduino board. (Just you can't tell what it does without the board.) Hopefully youhave generated the model.h file if not we have one for you embedded in the file at https://github.com/hpssjellis/my-examples-for-the-arduino-portentaH7/blob/master/m09-Tensoflow/b02_makerML_xor.ino >we are going to try to get this working on an Arduino. The esaiest should be the Nano 33 BLE Sense. You will need the board installed and Arduino_tensorFlowLite library installed.





