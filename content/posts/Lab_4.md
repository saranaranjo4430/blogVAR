+++ 
date = 2024-10-10T11:00:55+02:00
title = "Lab 4"
description = "Using Kinect"
authors = ["Sara Naranjo"]
tags = [
    ]
categories = []
externalLink = ""
series = []
+++

## Virtual environment 

to go to the virtual environment (Student)

{{< notice tip >}}
D:\Users\Student\Desktop\kinect>.\kinect\student\Scripts\activate

(student) D:\Users\Student\Desktop\kinect>
{{< /notice >}}

The (student) shows that we are in a virtual environment. 

It is important to usee multiple virtual environments if we are doing multiple projects, we can install on each what we need for our project, and not have heavy programs on our own machine. 

To isolate the project. Whatever you install in your virtual environment does not interfere with the other, or your other projects. 

{{< notice tip >}}
first go to the folder where you want to create your virtual environment 
...\test> python -m venv .nameofvirtualenvironment

to activate it : 

...\test> .\nameofvirtualenvoronment\Scripts\activate

and this happens : 

(.nameofvirtualenvironment) ...\test>
{{< /notice >}}
{{< notice note >}}
The dot makes it a hiden folder 
{{< /notice >}}


### To start the test with the kinect : 
{{< notice tip >}}
cd kinect
python data.py
{{< /notice >}}

We choose the name of our test and the number of sensors (in this case we are using one kinect so it's 1)
Session name : name of the test 
Number of sensors : 1

Then the test starts, and at the end we have two folders with the information : 
images : 
depth information : .npy files 


## Direct live information 

{{< notice tip >}}
python real_time.py
{{< /notice >}}

And the camera turns on and you can do thing in real time. 

We can modify the real_time-py file to add blocks where people is. 

SDK Brouser Kinect : there are some projects in there. 

We install the developper toolkit for kinect. 


Reconstruct

## Examples 
{{< figure src="/blogVAR/images/deepness.png" alt="Deepness" caption="Deepness Representation" >}}
{{< figure src="/blogVAR/images/facerecongnition.png" alt="Face Recognition" caption="Face Recognition" >}}
{{< figure src="/blogVAR/images/square.png" alt="Square" caption="Face Recognition" >}}
{{< figure src="/blogVAR/images/3D_reconstruction.mp4" alt="3D reconstruction" caption="3D Reconstruction" >}}
{{< figure src="/blogVAR/images/skeleton.mp4" alt="Skeleton" caption="Skeleton" >}}
{{< figure src="/blogVAR/images/blender.png" alt="3D reconstruction in Blender" caption="3D reconstruction in Blender" >}}