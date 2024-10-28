+++ 
date = 2024-10-10T11:00:55+02:00
title = "Using a Kinect"
description = "Using a Kinect"
authors = ["Sara Naranjo"]
tags = [
  "Kinect",
  "Virtual Environment"
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

It is important to use multiple virtual environments if we are doing multiple projects, we can install on each what we need for our project, and not have heavy programs on our own machine. 

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

Here’s a page detailing our work with the Kinect and the virtual environment setup.

---

## Setting Up the Virtual Environment

To get started with the Kinect, we first set up a virtual environment. This allows us to keep the project’s dependencies separate, avoiding unnecessary installations on our machine.

### Step 1: Activate the Virtual Environment
- Open a terminal and navigate to the project folder:
  ```bash
  D:\Users\Student\Desktop\kinect>.\kinect\student\Scripts\activate
  ```
- If `(student)` appears in the terminal, the virtual environment is active.

### Step 2: Create a New Virtual Environment
- Navigate to your desired folder, then run:
  ```bash
  python -m venv .myenv
  ```
- To activate it, enter:
  ```bash
  .\myenv\Scripts\activate
  ```

> **Note:** The dot (`.`) before the environment name makes it a hidden folder.

---

## Running Kinect Tests

### Step 1: Run a Test
- In the terminal, navigate to the Kinect directory:
  ```bash
  cd kinect
  python data.py
  ```
- Choose the test name and number of sensors (e.g., 1 for a single Kinect).

### Step 2: View Test Data
After the test, two folders are created:
- **Images**: stores captured images.
- **Depth Information**: stores `.npy` files with depth data.

### Step 3: Real-Time Data
To activate the Kinect in real time, run:
```bash
python real_time.py
```
Now, the Kinect camera turns on, displaying data in real time. We also modified this file to add blocks around detected people.

### Kinect SDK and Toolkit
We used the Kinect SDK and Developer Toolkit for various projects and enhancements.

---

Here are some example images of our real-time Kinect project!

## Examples 
{{< figure src="/blogVAR/images/deepness.png" alt="Deepness" caption="Deepness Representation" >}}
{{< figure src="/blogVAR/images/facerecognition.png" alt="Face Recognition" caption="Face Recognition" >}}
{{< figure src="/blogVAR/images/square.png" alt="Square" caption="Face Recognition" >}}


{{< figure src="/blogVAR/images/blender.png" alt="3D reconstruction in Blender" caption="3D reconstruction in Blender" >}}