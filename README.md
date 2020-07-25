
# UDACITY OPENVINO Intel® EDGE-AI CERTIFIACTION

 This scholorship was provided by Udacity.It was five-lesson plan which provided insight how to make Edge application which make deeep learning model run locally on the device. OpenVINVO tool allows us to convert a deep learning model and configure it to run on a specialized hardware.

### Why Edge AI Application?
Defined as edge computing as “a part of a distributed computing topology in which information processing is located close to the edge – where things and people produce or consume that information".

###  1. Consequences from Video
This folder cantains a project which analyze the [video](https://github.com/web-codegrammer/Intel-Edge-AI-using-OpenVINO-toolkit/blob/master/consequences%20from%20video/pets.mp4) and return the time two particular set of pets are in camera scene and returns the time stamp when a particular event occurs.

Files contained are:-
1. prototype.xml:- xml reprenstaion of Deep Learning Model used as a consequence to model
1. prototype.bin:- bin reprenstaion of Deep Learning Model
1. Interpretation 2020-02-23 201346.png:- Screenshot of image
1. App.py :- Main file of python
 

###  2. Integrating-on-web
In this project, Data was transfered from Edge Application to the web Server using **MQTT** and **FFmpeg servers**.[Input video](https://github.com/web-codegrammer/Intel-Edge-AI-using-OpenVINO-toolkit/blob/master/consequences-on%20-web/test_video.mp4)  was converted to [output video](https://github.com/web-codegrammer/Intel-Edge-AI-using-OpenVINO-toolkit/blob/master/consequences-on%20-web/out_video.mp4) and was dispalyed along with data like **speed** and **classes counted** from JSON server.


Files contained are:-
1. app.py :- Main file of python
1. consequence.py:- supporting file for app.py
1. Captured.PNG:- Screenshot of server with video server
1. test_video.mp4:- Input video given to program
1. out_video.mp4 :- output video seen on server


### Library Used are:-
1. OpenVino toolkit 
1. openCV for image processing
1. paho.mqqt
1. Tensorflow
1. Numpy

## License 
[MIT](https://github.com/web-codegrammer/Intel-Edge-AI-using-OpenVINO-toolkit/blob/master/LICENSE)
Issued to ```Devanshu Vashishtha``` | All Rights Reserved | 2020

https://github.com/web-codegrammer/Intel-Edge-AI-using-OpenVINO-toolkit/blob/master/LICENSE
