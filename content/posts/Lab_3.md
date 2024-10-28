+++ 
date = 2024-09-25T11:00:55+02:00
title = "My first project on Unity"
description = "My first project on Unity"
authors = ["Sara Naranjo"]
tags = [
    "Unity"
    ]
categories = []
externalLink = ""
series = []
+++

Here’s how I created my **first Unity project** – a simple game called *Roll-a-Ball* – and the steps I followed to bring it to life!

---

### Step 1: Setting Up Unity 🎮
- **Download Unity Hub** from [here](https://unity.com/download).
- Install Unity Editor through Unity Hub.
- Create a new 3D project and name it whatever you like. I called mine *Roll-a-Ball*.

### Step 2: Follow the Tutorial
You can follow the official *Roll-a-Ball* tutorial on [Unity Learn](https://learn.unity.com/project/roll-a-ball), but here’s what I did!

---

### Project Breakdown:

#### **Unity’s Prefab System:**
I used **Prefabs** to reuse GameObjects (GOs). Here’s how:
- **Drag the GameObject** from the Hierarchy into the `Assets/Prefabs` folder.
- The GO turns blue, meaning it’s now a Prefab!

#### **Creating Collectibles (PickUps):**
I created **PickUps** (green for points, orange for penalties). Then I added some animation using this simple code for oscillation:
```csharp
float t = (Mathf.Sin(Time.time * speed * Mathf.PI * 2.0f) + 1.0f) / 2.0f;
```
{{< figure src="/blogVAR/images/unity_plateau.png" alt="Plateau" caption="Plateau" >}}

#### **Adding Rotation and Oscillation:**
I used the **Lerp function** to interpolate between two points, giving the PickUps a rotating and oscillating effect, which made the game feel dynamic.

#### **Player Controller and Collisions:**
I modified the `PlayerController.cs` script to detect collisions using Unity's **colliders**. When the player hits a **green** object, they score +1; when they hit **orange**, they lose 1 point.

Make sure to set **"Is Trigger"** in the inspector and use **rigidbody components** on PickUps.

#### **UI for the Score:**
To display the score, I added a **UI text element** with TextMeshPro. You can find it under **Hierarchy > UI > Text-TextMeshPro** and drag it into the PlayerController script to keep track of the player’s score.

---

### Step 3: Testing the Game
Once everything was set, I hit the play button and tested the mechanics to make sure the score, rotation, and collisions worked as expected.

---

Now you have a basic game in Unity! You can follow along with the full tutorial [here](https://learn.unity.com/project/roll-a-ball), but this is a great foundation to start creating your own projects.

{{< [youtube yY96hTb8WgI](https://youtu.be/lF-Qpa39f1A) >}}

<br> 


<video width="640" height="360" controls>
  <source src="/blogVAR/videos/unity_game_mobile.MOV" type="video/MOV">
  Your browser does not support the video tag.
</video>
