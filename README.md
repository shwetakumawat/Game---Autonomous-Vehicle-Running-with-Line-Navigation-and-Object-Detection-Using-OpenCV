# Game---Autonomous-Vehicle-Running-with-Line-Navigation-and-Object-Detection-Using-OpenCV

<h2 align="center"> Autonomous Vehicle Running with Line Navigation and Object Detection Using OpenCV and AI Techniques - Live Streaming.</h2>

 <p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/74568334/128628482-a327be8f-5cdb-41ce-9af2-a93bc327814c.gif">
</p> 

<h4 align="center"> <span style="color:green">Line detection/OpenCV/ SSD_mobilenet, Keras/TensorFlow/ Deep Learning and Computer Vision </span></h4>

<h3 align="left">Introduction </h3>
 
<p style= 'text-align: justify;'> Mobility on a wide scale is moving towards complete automation. Though the technology for automating the vehicles already exists, these technologies must be optimised to fit the current environment.  This project would be a scaled-down model of the Autonomous Car and focus on the live streaming lane detection using OpenCV.</p>

  
 <p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/74568334/128623886-e2144326-a462-47c9-aac2-612a97886c73.jpg">
</p> 
 
  
<h3 align="left"> Project Limitations </h3>

 
<p style= 'text-align: justify;'> * Three wheels were used instead of four wheels. To build a three-wheel Car, three-wheeled was to have a mounting where the third wheel could be assembled. This mount is designed based on the space available on the model car. To provide the steering, a servo motor must be fitted so that the mounting used for the steering wheel could be extended for mounting the servo motor.</p>
  
  
 <p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/74568334/128624299-5317b1e7-3a50-4782-b7a8-712d9fddc145.gif">
 
</p> * camera mounting is required to place the camera in an optimal height to get the future images which would be adjacent to the vehicle.</p>
 
<h3 align="left"> Camera Holder</h4>
  
 <p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/74568334/128624444-04313456-55c2-49fe-a04c-a23d535d910e.png">
  <img width="450" src="https://user-images.githubusercontent.com/74568334/128624392-3fa6aaec-ce00-4208-9fb8-587b618c407a.jpg">
</p> 
  
 ### 🔑 Prerequisites
 
* [Freenove 4WD Smart Car Kit](https://www.amazon.de/-/en/Freenove-Raspberry-Avoidance-Colourful-Ultrasonic/dp/B07YD2LT9D/ref=sr_1_5?crid=3VP3TDHEI052K&dchild=1&keywords=pi%20car%20kit&qid=1628421094&sprefix=pi%20car,aps,194&sr=8-5)

 ### 🚀 Initialization For Running the car Autonomously
 
 1. Clone the repo with local computer

```
git clone https://github.com/KrishArul26/Live--streaming-Autonomous-Vehicle-running-With-line-detection-using-OpenCV.git

```
 2. Connect the raspberry Module with local computer via Power shell(with wireless network)

```
ssh pi@car_name
``` 
 3.Navigate the Raspberry Module code directory 

```
cd ...
```  
```
cd share/Code
```  
4. For running the car: Run the main.py

```
sudo python main.py
```  
4. For visualization on the browser to see line detection: Run the app.py
 
```
sudo python app.py


  
