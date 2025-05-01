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

 How to Run the Project
 
 1. Clone the Project
```bash
git clone https://github.com/yourusername/ppe-detection.git
cd ppe-detection

2.CI/CD Pipeline (GitHub Actions)
This project uses GitHub Actions to:

Run tests and linting

Build Docker image

Push to DockerHub

Deploy to server using SSH

Workflow File: .github/workflows/deploy.yml
Check the CI/CD YAML file for details.

OUTPUT
![Screenshot 2024-11-18 183751](https://github.com/user-attachments/assets/8a5c34a9-4831-490f-826c-285d9ca358eb)
