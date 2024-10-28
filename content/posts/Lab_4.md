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