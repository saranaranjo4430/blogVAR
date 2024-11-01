+++ 
date = 2024-10-15T11:00:55+02:00
title = "Prototyping and Evaluation of a Smart Fridge Organizer App Concept"
description = "Prototyping and Evaluation"
authors = ["Sara Naranjo"]
tags = [
    "Prototyping",
    "Evaluation",
    "Testing", 
    "App", 
    "Smart Fridge Organizer"
    ]
categories = []
externalLink = ""
series = []
+++
___
# Prototype
### Smart Fridge Organizer App Concept

The **Smart Fridge Organizer** is a mobile app designed to simplify food inventory management, allowing users to keep track of their fridge and counter items, and helping them avoid waste and optimize meal planning.

### Key Features:

1. **QR Code Integration for Easy Input**: 
   The app integrates with supermarkets by using a QR code provided during purchase. Supermarkets have access to information like product expiration dates, lots, and nutritional details, which are embedded in the QR code. When users scan this QR code, the app automatically uploads all the purchased items into the inventory, including their expiration dates. This feature is essential as traditional receipts are often illegible, making manual input cumbersome. By scanning the supermarket's QR code, users don't have to input their items one by one, saving time and effort.

2. **Expiration Date Alerts**: 
   The app notifies users when a product is approaching its expiration date, helping to minimize food waste. These expiration dates are automatically loaded when scanning the QR code from the supermarket.

3. **Recipe Suggestions Based on Ingredients**: 
   With a focus on reducing waste and simplifying cooking, the app offers recipe suggestions based on the ingredients you currently have. Users can filter recipes by dietary preferences or specific nutritional goals, such as low-carb, high-protein, or balanced meals.

4. **Nutritional Information & Custom Recipes**: 
   The app provides detailed nutritional information for each item in the inventory, retrieved from the QR code's data. Users can generate custom recipes based on their nutritional preferences, setting calorie or macronutrient targets for meals.

5. **Tracking Non-Fridge Items**: 
   The app also allows users to track items on the counter, such as bread, fruits, or other pantry products, ensuring that the entire kitchen's food inventory is covered.

### Workflow Example:
- After a shopping trip, scan the QR code provided by the supermarket.
- The app automatically updates your inventory with all the purchased products, their expiration dates, nutritional information, and more.
- Get alerts when items are about to expire and view recipe ideas that make use of your soon-to-expire ingredients.
- Search or receive custom recipe suggestions based on the ingredients you have and your nutritional needs.

This combination of automation, tracking, and health-focused features makes the **Smart Fridge Organizer** a powerful tool for both simplifying kitchen management and promoting healthier, waste-free living.

Here's an example of what the actual app might look like : 
{{< figure src="/blogVAR/images/proto_app.jpeg" alt="Prototype" caption="Prototype" >}}

### Features:
- **Home Screen**: Displays organized food inventory by expiration.
- **Add Items**: You can easily add items via barcode or receipt scanning.
- **Recipe Suggestions**: Provides recipe ideas based on what you already have.
___
# Using the Prototype for Evaluation
I decided to test my **Smart Fridge Organizer app** concept with a friend. I showed him my paper prototype, which included hand-drawn sketches of the app's interface and features like the QR code integration, expiration date alerts, and recipe suggestions based on the items in your fridge and counter.

#### User Feedback:
My friend found the concept very practical, especially the ability to scan the QR code from the supermarket to upload purchases automatically. He appreciated that this feature avoids the hassle of manually inputting every item, which he found tedious in other food tracking apps. Additionally, the expiration date alerts were seen as helpful for reducing food waste, a concern for him as he often forgets when items are close to expiring.

However, he pointed out that some people might not use the app if it requires too many steps initially (such as scanning a QR code or searching for products manually). He suggested integrating the app with supermarket loyalty cards to automatically sync purchases without needing to scan anything.

#### Critical Reflection:
Based on this feedback, I realized that user experience must prioritize minimal effort, especially for busy individuals. The QR code system simplifies input significantly, but further integration with existing supermarket systems could make the app even more seamless. A future improvement could be exploring partnerships with grocery stores for automatic data syncing, ensuring that users don't need to remember to scan a QR code.

Overall, the concept seems to meet user needs for easy food management, but further iteration is necessary to streamline the onboarding process.