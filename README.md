# Image Detection Using Teachable Machine

In this project, I utilized Teachable Machine AI to create an image detection system that allows users to upload an image for classification. The system is integrated with a web interface (HTML, CSS, JavaScript) and a database (MySQL using XAMPP) to store detection data. The main objective was to develop an image upload-based detection system while ensuring accurate classification and proper database management.

## How It Works
**1. Web Interface (HTML, CSS, JavaScript)**

-The index.html file provides a user-friendly interface where users can upload an image.

-The uploaded image is displayed in the browser for preview.

-A Predict button triggers AI-based classification.

-The detection results are shown on the webpage, along with a detection counter that tracks the number of detected images.

**2. AI Model Integration (Teachable Machine & JavaScript)**

-The AI model is loaded from model.json and metadata.json.

-When a user uploads an image, the model predicts the most probable class.

-The highest probability class name is displayed along with its confidence level.

**3. Database Integration (MySQL + PHP + XAMPP)**

-The detection results (class name and detection count) are stored in a MySQL database.

-PHP scripts (update_counter.php, reset_counter.php) handle database updates via AJAX requests from JavaScript.

-A table detection_log is used to keep a record of each detection with a timestamp.


## Key Functionalities
**Image Upload & Preview**

Users can upload an image, which is displayed in the browser.

**AI Prediction Using Teachable Machine**

The AI model classifies the uploaded image and displays the result.

**Detection Counter System**

-A counter keeps track of the number of images detected.

-The counter is stored in the database and can be reset using the Reset Counter button.

**Database Logging**

-Each detection is stored in a MySQL database with a timestamp.

-The counter updates dynamically in the database.
