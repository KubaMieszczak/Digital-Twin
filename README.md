# Digital Twin

## Project description
Project aim to detect a robot in warehouse and determine its localization on map. We will use cascade classifier learned on our own data. Images is collected from the webcam of the laptop.

## How it works:
1. We are learning the warehouse corner point detection model, with our data
![image](https://user-images.githubusercontent.com/106450951/209823741-6e41abc0-7c87-4b2a-b24b-80e95850be8e.png)


2. Model we created, are not perfect. Sometines it detects objects that are not corners of warehouse. I decited to make confidence intervals besause camera will be places at similar angle for the most of the time. Persormers now is much better
![image](https://user-images.githubusercontent.com/106450951/209826259-d32711b9-e540-493d-9407-521ee7de981d.png)

3. Once again, we learn the detection model of our robot, model performers is not bad but sometines it detects more then one robot, to solve that problem we are checking color of detected object to find out if our object is a robot. We determing it by RGB elements.
![image](https://user-images.githubusercontent.com/106450951/209826740-fdb8b1a1-55c0-46d6-b6af-c129c31edea3.png)

Our 'robot' to detect:

![image](https://user-images.githubusercontent.com/106450951/209827787-56163101-9234-419e-af22-19e762dec6e2.png)

# Results of project:
We shows the image that we will use to detects objects.
Secound pictore is a map with robot represinting localizsation of robot in magazine

![image](https://user-images.githubusercontent.com/106450951/209827353-dcb14df7-c6e0-4177-a2eb-58715401eaee.png)
