# Real-Time Driver Drowsiness Detection System

This project is a real-time drowsiness detection system that monitors drivers for signs of fatigue to prevent accidents. It uses computer vision techniques to detect eye closure, yawning, and head position, providing immediate alerts when drowsiness is detected.

---

## 🚀 **Features**

✅ Real-time detection using webcam  
✅ Alerts driver with warning sounds when drowsiness is detected  
✅ Detects eye closure and yawning  
✅ Uses Haar cascades and facial landmark detection  
✅ Lightweight implementation using Python and OpenCV

---

## 🛠 **Technologies Used**

- **Python 3.11**  
- **OpenCV**  
- **Dlib**  
- **imutils**  
- **NumPy**
- **Haarcascade Classifiers**

---

## 📁 **Project Structure**

Driver_Drowsiness_Detection/
┣ Alert.wav
┣ drowsiness_yawn.py
┣ haarcascade_frontalface_default.xml
┣ shape_predictor_68_face_landmarks.dat
┣ requirements.txt
┣ README.md

yaml
Copy
Edit

---

## ⚙️ **How to Run**

1. **Clone the repository**

```bash
git clone https://github.com/YourUsername/Driver_Drowsiness_Detection.git
cd Driver_Drowsiness_Detection

Install dependencies**

bash
Copy
Edit
pip install -r requirements.txt
Run the script

bash
Copy
Edit
python drowsiness_yawn.py
Allow camera access. The system will start detecting drowsiness and trigger alerts when necessary.

