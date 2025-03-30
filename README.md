# Face Recognition Project  

## 📌 Description  
This project utilizes OpenCV's Haar Cascade classifier to detect human faces in an image. The program processes an input image by converting it to grayscale, detecting faces, and marking them with bounding boxes. This is a fundamental implementation of face recognition using computer vision techniques.  

## 🚀 Features  
- Uses OpenCV’s `haarcascade_frontalface_default.xml` for face detection.  
- Reads and processes input images of various formats.  
- Converts images to grayscale for better feature extraction.  
- Detects multiple faces in an image.  
- Draws rectangles around detected faces.  

## 📂 Installation  
1. Install OpenCV if not already installed:  
   ```bash
   pip install opencv-python
   ```
2. Download the `haarcascade_frontalface_default.xml` file from OpenCV’s official repository.  
3. Place the cascade file in the same directory as the script.  

## 🛠️ Usage  
Run the script by providing an image file:  
```bash
python face_recognition.py
```
Make sure the image file is present in the same directory. The program will display the image with detected faces highlighted.  

## 🖼️ Example  
Input Image → Face Detected Image (with rectangles around faces).  

## 📜 Dependencies  
- Python 3  
- OpenCV (`cv2`)  

## 🔥 Future Improvements  
- Implement real-time face detection using a webcam.  
- Integrate deep learning-based face recognition for better accuracy.  
- Add GUI for user-friendly interaction.  

---

Let me know if you need any modifications or additional details! 🚀
