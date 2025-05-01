 PPE Detection Project

This project is used to detect whether a person is wearing Personal Protective Equipment (PPE) such as a helmet, face mask, and safety vest using computer vision and deep learning.

 Features
 
- Detects:
  - Helmet
  - Face Mask
  - Safety Vest
- Works with live webcam or video feed
- Shows real-time detection on a web page using Flask

 Technologies Used
 
- Python
- OpenCV
- TensorFlow or YOLO (any one)
- Flask (for web interface)
- HTML, CSS (for basic frontend)

 🚀 Basic Workflow
Dataset – Use public PPE datasets or create your own.

✅ Model Training – Train a YOLOv5 or similar model to detect:

Helmet

Mask

Vest

Person

🔁Model Inference – Run real-time video stream for detection.

Flask App – Serve detection model with video stream in browser.

Frontend – Display video feed + detection output.

Logging – Save non-compliance events to DB.

🚀 4. CI/CD Pipeline for Deployment

✅ CI (Continuous Integration)
CI automatically tests and builds your application whenever you push to your repository.

Steps:

Push Code to GitHub

Run Tests (if any)

Build Docker Image

Push Docker Image to DockerHub or GitHub Container Registry

🔁 CD (Continuous Deployment)

CD deploys the tested code automatically to your hosting server/cloud.

Steps:

Pull image from DockerHub

Deploy to server (AWS/GCP/Heroku)

Run container

Expose app via Nginx or public port


✅OUTPUT


