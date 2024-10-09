+++
date = 2024-09-16T11:00:55+02:00
title = "Lecture 1"
description = "Congnition and Perception"
authors = ["Sara Naranjo"]
tags = [
    "Cognition",
    "Perception",
    "Affordance",
    "Gestalt Laws",
    "Dark Design Patterns"
    ]
categories = []
externalLink = ""
series = []
+++

# Summary and key concepts of the lecture 
Human-Computer Interaction (HCI) focuses on designing intuitive, efficient, and user-friendly interfaces between humans and computer systems. Here are the key forms and concepts discussed in the lecture:

1. Input Devices:
Devices that allow users to input commands or data into a system, such as keyboards, mice, touchscreens, and motion sensors.
2. Output Devices:
These provide feedback to the user through visual, auditory, or tactile means, including monitors, speakers, and augmented reality displays.
3. User Interface Elements:
Components like buttons, sliders, icons, and text fields that users interact with to communicate with the computer.
4. Graphical User Interface (GUI):
A visual-based interface with elements like windows, icons, and menus, commonly used in operating systems and applications.
5. Command-Line Interface (CLI):
A text-based interface where users type commands to interact with the system, typically used by advanced users or developers.
6. Natural Language Interfaces:
Interfaces that allow interaction through spoken or written natural language, such as virtual assistants like Siri or Alexa.
7. Gesture-Based Interfaces:
Interfaces that interpret physical gestures or motions to interact with the system, often used in virtual and augmented reality.

## What is HCI?
HCI is a discipline that aims to optimize the interaction between people and computers, focusing on usability and user satisfaction. Understanding user needs and behavior is key in designing better interfaces.

### Bad Designs and Their Motivations
Bad designs often occur when systems fail to consider user needs or expectations, leading to frustration. Examples include overly complicated microwave controls or ATM designs that make users forget their cards. These failures motivate improvements in HCI by promoting designs that align with how users think and behave.

### Cognitive Models and Design Implications
Models like the Human Processor Model help predict how users interact with systems by breaking down human cognition into processes akin to a computer's operations. However, these models are limited because they don’t account for emotions, bodily interactions, or context.

### Affordances
Affordances refer to the cues or hints an object provides to suggest how it can be used. For instance, a well-designed faucet with a single lever indicates easy control, while a confusing microwave interface with 31 buttons is a poor affordance. Affordances guide users in understanding how to interact with interfaces intuitively.

### Gestalt Laws in Design
Gestalt principles, such as proximity and similarity, help explain how users group visual elements. Poorly applied Gestalt laws can confuse users, such as improperly spaced buttons on a device or inconsistent grouping on a website, which disrupts the user experience.

### Dark Design Patterns
Dark design patterns manipulate users into taking actions they wouldn’t normally choose, such as making it difficult to cancel subscriptions (forced continuity) or creating false urgency on e-commerce sites. Ethical design counters these patterns by making processes clear, transparent, and user-centered.

In conclusion, as technology advances, it becomes increasingly important to design interfaces that respect users' cognitive limitations, prioritize accessibility, and avoid manipulative practices. Understanding cognition, perception, and behavior is key to creating intuitive and user-friendly systems. 

# Homework 
## Affordances (Good and Bad)

### Good Affordance:
{{< notice example >}}
A laptop trackpad that allows multitouch gestures (like pinch-to-zoom or two-finger scrolling).
Why it's good: The trackpad not only allows users to move the cursor but also affords more complex interactions, such as zooming or scrolling, without needing additional buttons. The smooth, flat surface encourages exploration and gestures, which most users can discover intuitively.
{{< /notice >}}

{{< figure src="/blogVAR/images/trackpad.JPG" alt="Trackpad Example" caption="A good affordance example" >}}


### Bad Affordance:
{{< notice example >}}
A USB port on a device that’s difficult to find or access because it’s hidden behind a cover or in an awkward position.
Why it's bad: Users struggle to identify where the port is or how to plug in the cable properly. The design doesn’t afford easy access or use, leading to frustration when trying to connect a device.
How to fix it: Position the USB port in a more accessible location, and perhaps add a small light or visible marker that indicates where to plug in the cable.
{{< /notice >}} 

{{< figure src="/blogVAR/images/usb.jpeg" alt="Usb Example" caption="A bad affordance example" >}}

## Gestalt Laws (Bad Applications)
### Bad Application 1:
{{< notice example >}}
A poorly designed bookshelf where books of different genres are placed together without clear visual separation.
{{< /notice >}} 
**Gestalt Law:** Law of Similarity – Objects that share visual characteristics are perceived as related.
Problem: If mystery novels and science fiction books are mixed together without any kind of visual cue (like different colored sections or labels), users might have a harder time distinguishing between the genres. This disrupts the browsing experience.
Fix: Use clear genre labels, different color-coded sections, or signage that visually separates the categories to help users find what they are looking for more efficiently.

### Bad Application 2:
{{< notice example >}}
Street signs on a busy road where different signs are placed too close together.
{{< /notice >}} 
Gestalt Law: Law of Proximity – Objects close to each other are perceived as related.
Problem: When signs are placed close together (e.g., speed limits, directions, and warnings), drivers might mistakenly associate them as a single message or miss some of them because they’re too cluttered.
Fix: Space out the signs appropriately so each one is clearly distinct from the others, making it easier for drivers to process the information quickly.

## Dark Design Patterns
### Dark Pattern 1:
{{< notice example >}}
A website that has a countdown timer on a sale that resets when you reload the page.
{{< /notice >}} 
Dark Pattern: "False Urgency" – This creates a fake sense of urgency by making users believe they need to act quickly, even though there’s no real deadline.
Redesign: Be transparent about actual sale times and deadlines. If a sale is time-sensitive, provide a real, non-resetting timer that shows when it will end. Avoid manipulating users into making rushed decisions with deceptive tactics.
### Dark Pattern 2:
{{< notice example >}}
Websites that automatically add items to your shopping cart.
{{< /notice >}} 
Dark Pattern: "Sneak into Basket" – Adding extra items without the user's clear consent.
Redesign: Ensure that only the items the user selects are added to the cart, providing a confirmation step before adding extras.


