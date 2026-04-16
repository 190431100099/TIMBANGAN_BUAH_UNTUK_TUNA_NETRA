# 🎛️ FRUIT SCALE FOR THE VISUALLY IMPAIRED  
Fruit Type Classification Using CNN and Arduino Uno

## 📝 Project Description  
This project aims to assist visually impaired individuals in recognizing fruit types based on weight and visual images using CNN (Convolutional Neural Network) technology integrated with an Arduino Uno.  
This scale not only displays the fruit's weight but is also capable of identifying the fruit type and providing feedback in the form of voice or text accessible to blind users.

## 🍎 Fruits Used  
The CNN model was trained using four types of fruits as test data:  
• 🥑 Avocado  
• 🌰 Durian  
• 🍊 Local Orange  
• 🍊 Imported Orange  

Each type of fruit was photographed under various lighting conditions and viewing angles, then combined with weight data from the load cell sensor readings to improve classification accuracy.

## ⚙️ Technology Used  
• **Arduino Uno** — as the main controller for weight sensor readings.  
• **Load Cell + HX711** — to measure the mass of the fruit.  
• **Python & TensorFlow/Keras** — to train and run the CNN model.  
• **Serial Communication (UART)** — to connect the Arduino with the classification system on the computer.  
• **Text-to-Speech (TTS)** — to provide voice output to the user.

## 🧠 CNN Method  
The CNN model processes fruit images to extract unique visual features such as color, texture, and shape. The classification results are combined with weight data from the sensor to provide more precise fruit identification.

## 📊 Results and Testing  
Testing was conducted using the dataset of the four fruits mentioned above under various lighting conditions. The model demonstrated a good level of accuracy in recognizing fruit types from the provided images and weights.

## 🚀 Objectives  
• To assist visually impaired individuals in recognizing fruit types independently.  
• To combine a weight measurement system and digital image recognition in one integrated tool.  
• To apply AI and IoT technology for accessibility needs.
