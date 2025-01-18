+++  
date = 2025-01-12T11:00:55+02:00  
title = "My First VR Interaction in Unity"  
description = "My First VR Interaction in Unity"  
authors = ["Sara Naranjo"]  
tags = [  
    "Unity",  
    "VR",  
    "XR Interaction Toolkit",  
    "Oculus",  
    "OpenXR"  
    ]  
categories = []  
externalLink = ""  
series = []  
+++  

Here’s how I adapted my Unity game for Virtual Reality using the **XR Interaction Toolkit**.

---

### Step 1: Install Plugins 🎮
- Open the **Package Manager** and add:
  - **OpenXR Plugin**  
  - **XR Interaction Toolkit**  
- Import the **Controller Profiles** from the OpenXR Plugin and the **Starter Assets** from the XR Interaction Toolkit.
{{< figure src="/blogVAR/images/OpenXR.png" alt="OpenXR" caption="OpenXR" >}}
{{< figure src="/blogVAR/images/InteractionToolkit.png" alt="InteractionToolkit" caption="InteractionToolkit" >}}

---

### Step 2: Configure Settings ⚙️
- Navigate to **Edit > Project Settings > XR Plug-in Management** and enable **Oculus**.  
{{< figure src="/blogVAR/images/Oculus.png" alt="Oculus" caption="Oculus" >}}
- Import the **Starter Assets** from **Assets > Samples > XR Interaction Toolkit > 2.2.0**, and assign presets to **ActionBasedContinuousMoveProvider default**.
{{< figure src="/blogVAR/images/Starter Assets.png" alt="Starter Assets" caption="Starter Assets" >}}
{{< figure src="/blogVAR/images/Starter Assets 2.png" alt="Starter Assets 2" caption="Starter Assets 2" >}}

---

### Step 3: Create the XR Setup 🌐
- Add an **XR Origin (VR)** from **XR > XR Origin (VR)** in the Hierarchy.  
- Add the following components to the XR Origin:  
  - **Character Controller**  
  - **Character Controller Driver**  
- Ensure the XR Origin’s base GameObject is set to **XR Origin**, not **Floor**.  
- Remove the default **Main Camera** from the Hierarchy.
{{< figure src="/blogVAR/images/XR Origin Inspector.png" alt="XR Origin Inspector" caption="XR Origin Inspector" >}}

---

### Step 4: Set Up Locomotion 🌟
- Add **Locomotion System (Action Based)** from the XR menu.  
- Link the **Locomotion System** to the **Locomotion Provider** in the **Character Controller Driver**.  
- Configure the following:
  - Untick **Teleportation** and **Snap Turn Provider (Action Based)**.  
  - Add **Continuous Turn Provider (Action Based)** for smoother motion.  
- Ensure the **Input Action Manager** is set with **XRI Default Input Actions**.
{{< figure src="/blogVAR/images/Locomotion System Inspector.png" alt="Locomotion System Inspector" caption="Locomotion System Inspector" >}}

---

### Step 5: Configure Controllers 🕹️
- Set up **RightHand Controller** and **LeftHand Controller**:
  - Remove unnecessary components like **XR Ray Interactor** and **Line Renderer**.  
  - Add a **ModelParent GameObject** under each controller and attach the custom hand model prefabs.
{{< figure src="/blogVAR/images/LeftHand Inspector.png" alt="LeftHand Inspector" caption="LeftHand Inspector" >}}
{{< figure src="/blogVAR/images/LeftHand Inspector 2.png" alt="LeftHand Inspector 2" caption="LeftHand Inspector 2" >}}

---

### Step 6: Create Hand Models 🖐️
- Create a **HandController Prefab**:
  - Add a **Cube** as a child (named **Handle**) and a **Cylinder** (named **Pad**).  
  - Customize their sizes and colors for aesthetics.  
  - Remove colliders and disable **Cast Shadows** for both objects.  
{{< figure src="/blogVAR/images/HandController.png" alt="HandController" caption="HandController" >}}
{{< figure src="/blogVAR/images/Handle.png" alt="Handle" caption="Handle" >}}
{{< figure src="/blogVAR/images/Pad.png" alt="Pad" caption="Pad" >}}

---

### Step 7: Add Interaction Features ✨
- Add **Sphere Colliders** to both controllers with the **Is Trigger** option enabled and set their radius to `0.5`.  
- Attach **XR Direct Interactor** to both the RightHand and LeftHand Controllers.  

---

### Step 8: Make the PlayBoard Interactable 🎲
- Add **XR Grab Interactable** to the PlayBoard.  
{{< figure src="/blogVAR/images/Playboard Inspector.png" alt="Playboard Inspector" caption="Playboard Inspector" >}}

---

### Step 9: Create Attach Points 📍
- Create **AttachPointL** and **AttachPointR** as empty GameObjects under the PlayBoard.  
- Assign these points in the PlayBoard’s **XR Grab Interactable** component for custom hand positions.

---

### Step 10: Test and Iterate 🛠️  
- Run the scene and test all interactions.  
- Adjust movement, grabbing, and interaction parameters until the experience feels smooth and intuitive.

---

### Final Result 🎥
Check out the final VR experience here:  
{{< youtube nyMbirZ7d7M >}}  

---

This was an incredible learning experience, and I’m so excited to explore more VR projects! 🎉  
