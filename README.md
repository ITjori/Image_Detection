# Teachable Machine and Web Technologies: AI-Based Webcam Prediction

## Overview

This project integrates Teachable Machine with a web-based AI-powered detection system that uses a webcam to recognize objects in real time. The system captures images, processes predictions, and logs detection results into a MySQL database managed through XAMPP. The objective is to create an interactive AI-driven recognition platform capable of identifying objects via a web interface and efficiently storing detection data for analysis.

## How to Do It
**Step 1: Design a Website**

-Created an HTML interface with user interface elements such as buttons for starting the camera, taking pictures, and showing results.

-CSS was applied to the webpage to improve the user's interaction.

-A new JavaScript command was added to allow the webcam to be accessed so that images from the video could be captured.

-The webpage was also decorated with Teachable Machine model for predictions within the webpage.

**Step 2: The Loading and Application of the AI Model**

-Imported the Teachable Machine model that was made available on the internet.

-Used image Tensors for loading images and making predictions in Javascript and TensorFlow.js.

-Wrote code to capture an image from the webcam, convert it into a suitable format, and send it to the AI model for inference.

-Prediction results with associated confidence scores were rendered on the webpage.
Imported the Teachable Machine model hosted online, including model.json and metadata.json files.

**Step 3: Building and Linking the Database**

-Built a mySQL database called 'TMPro' using phpMyAdmin in XAMPP.

-Constructed tables to save detection logs and other counters associated with the number of times detections were made.

-Setup a MySQL driven backend using PHP programming language for managing the database.

**Step 4: Saving Detection Results into the Database**

-Developed PHP scripts (update_counter.php and reset_counter.php) to update the database.

-When the object is detected the detection count and class name is added into the database.

-Add detection reset function to deletion of counts when appropriate.

**Step 5: Debugging and Managing Data in the System Simultaneously**

-Wrote Javascript code to carry out AJAX requests for dynamically updating the detection counter.

-Changed the UI in response to events without refreshing the page.

-Resolved connection problems associated with Javascript and PHP and MySQL interactions.
