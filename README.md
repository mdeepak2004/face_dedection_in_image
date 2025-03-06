# face_dedection_in_image


Face Detection in Images using OpenCV & Matplotlib
📌 Overview
This Python script detects faces in an image using OpenCV's Haar Cascade Classifier. The detected faces are highlighted with a bounding box, and the image is displayed using Matplotlib.

🛠 Requirements
Ensure you have the following dependencies installed:

sh
Copy
Edit
pip install opencv-python matplotlib
🚀 Usage
Place the image file in the same directory as the script.
Modify the detect_faces() function to point to your image file.
Run the script using:
sh
Copy
Edit
python deepak_face_detection.py
🖼 How It Works
The script loads an image and converts it to grayscale.
It detects faces using OpenCV’s Haar Cascade model.
A rectangle is drawn around each detected face.
The processed image is displayed using Matplotlib.
🔍 Example Output
(Replace with an actual output image)

📝 Future Improvements
Add real-time face detection using a webcam.
Use deep learning models for improved accuracy.
