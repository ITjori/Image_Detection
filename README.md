# Teachable Machine and Web Technologies: AI-Based Image Detection

## Overview

The goal of this project is to connect Teachable Machine with a web application that recognizes users and objects through a camera. The system processes the detected results and stores the final output in a MySQL database as well as XAMPP. The main objective was to construct an image capturing system capable of image recognition, predicting objects, and recording detections into a database in real time.

## How to Do It
**Step 1: Design a Website**

-Created an HTML interface with user interface elements such as buttons for starting the camera, taking pictures, and showing results.

-CSS was applied to the webpage to improve the user's interaction.

-A new JavaScript command was added to allow the webcam to be accessed so that images from the video could be captured.

-The webpage was also decorated with Teachable Machine model for predictions within the webpage.

**Step 2: The Loading and Application of the AI Model**

-Imported the Teachable Machine model that was made available on the internet.

-Used image Tensors for loading images and making predictions in Javascript and TensorFlow.js.

-Wrote code to take a picture, pre-process it correctly and pass it to the AI model for inference.

-Prediction results with associated confidence scores were rendered on the webpage.

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
