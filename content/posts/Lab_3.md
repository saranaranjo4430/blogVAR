+++ 
date = 2024-09-25T11:00:55+02:00
title = "Mobile Application of a Unity Game"
description = "Mobile Application of a Unity Game"
authors = ["Sara Naranjo"]
tags = [
    "Unity",
    "Mobile Application"
    ]
categories = []
externalLink = ""
series = []
+++

Here’s how I got my Unity game running on my phone using the accelerometer with **Unity Remote 5**!

---

### Step 1: Download Unity Remote 5 📲
- First, I downloaded **Unity Remote 5** on my phone from the App Store. This lets you test Unity games live on your mobile.

### Step 2: Setting Up Accelerometer Controls 🎮
- **Remove Windows Player Input**: In the Inspector panel, remove the original Player Input to avoid conflicts.
- **Create Mobile Input**: Add a new *Player Input* in a folder called `MobileInput`, set it up as `mobileInPutInteraction` in the Inspector, and assign it under *Actions*.

### Step 3: Updating the PlayerController Script 📜
- I updated `PlayerController.cs` to use the iPhone’s accelerometer instead of `rb.AddForce(movement * speed)`. This was done by setting up a boolean (`isMobileBuild`) to switch to accelerometer input, using `rb.AddForce(accelerometer_values)`.

### Step 4: Modifying Camera View 🎥
- I changed the main camera to a top view for easier control, plus added UI text to display acceleration values with **TextMeshPro**.

### Step 5: Project Preferences ⚙️
- Finally, I adjusted project preferences to ensure Unity Remote could communicate with my iPhone’s accelerometer. 

To get your Unity game running on your iPhone using Unity Remote 5:

1. **Connect the iPhone** to your computer.
2. In Unity, go to **Edit > Preferences > External Tools**.
3. Under **Device**, select your iPhone.

This will let Unity Remote 5 use your iPhone’s sensors for testing. Now, as you play the game in Unity, it streams to your phone, and you can use the accelerometer to control the game.

Now, as I tilt my phone, the ball rolls accordingly! 

Check the final result here : 
{{< youtube lF-Qpa39f1A >}}

And that’s it—game on! 🎉