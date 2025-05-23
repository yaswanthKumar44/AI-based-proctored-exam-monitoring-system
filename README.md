# 🎥 AI-Based Proctored Exam Monitoring System 🎓

An AI-powered exam monitoring system built using **Python**, **OpenCV**, and **Deep Learning**. This system ensures secure online exam sessions by integrating **face recognition-based authentication**, **drowsiness detection**, and **live exam proctoring** via webcam feeds.

---

## 📌 Features

- 🔒 **Face Recognition Authentication**
- 👁️ **Drowsiness Detection** (Eye Aspect Ratio & Head Pose Tracking)
- 🎥 **Real-Time Proctoring & Suspicious Behavior Detection**
- 📈 **98% Face Recognition Accuracy** with fast detection (under 0.5 seconds)
- 🗣️ **Voice-Assisted AI Chatbot (Optional via OpenAI API)**

---

## 📦 Required Python Libraries

Before running the project, install the following dependencies:

```bash
pip install flask face_recognition opencv-python numpy pillow openpyxl openai
pip install cmake
pip install dlib
📥 Pre-trained Model Files
Download and save the following pre-trained models into a folder named models/ in your project directory.

model.txt (contains):

bash
Copy
Edit
1) https://github.com/smahesh29/Gender-and-Age-Detection/blob/master/age_deploy.prototxt
2) https://github.com/eveningglow/age-and-gender-classification/blob/master/model/age_net.caffemodel
3) https://github.com/spmallick/learnopencv/blob/master/AgeGender/gender_deploy.prototxt
4) https://github.com/eveningglow/age-and-gender-classification/blob/master/model/gender_net.caffemodel
5) https://github.com/austinjoyal/haar-cascade-files/blob/master/haarcascade_eye.xml
6) https://github.com/opencv/opencv/blob/4.x/data/haarcascades/haarcascade_frontalface_default.xml
⚙️ API Key Setup
If you're using the optional OpenAI-powered chatbot or text-based assistant module, set your OpenAI API Key before running the application:

powershell
Copy
Edit
$env:OPENAI_API_KEY = "sk-Your_API_Key_Here"
$env:OPENAI_API_KEY
Replace sk-Your_API_Key_Here with your actual OpenAI API key.

🖥️ How to Run the Project
1️⃣ Install the required libraries (if not already):

bash
Copy
Edit
pip install flask face_recognition opencv-python numpy pillow openpyxl openai
pip install cmake
pip install dlib
2️⃣ Download all the model files listed in model.txt and place them in a models/ folder inside your project directory.

3️⃣ Set your OpenAI API Key if you’re using AI voice or text modules.

4️⃣ Run your main Python script:

bash
Copy
Edit
python app.py
(Replace app.py with your actual main file name if different.)

5️⃣ Access your system via the localhost URL provided by Flask (usually http://127.0.0.1:5000/)

📐 Project Modules
Face Recognition: Real-time user authentication via webcam.

Drowsiness Detection: Eye Aspect Ratio (EAR) monitoring and head pose estimation using 68 facial landmarks.

Exam Monitoring: Live face, eye, and behavior tracking; instant alerts for drowsiness, absence, or cheating attempts.

Optional Voice Chatbot: OpenAI-powered AI assistant for exam-related queries.

📸 Demo
Add demo screenshots or video previews here to showcase the system in action.


👨‍💻 Author
P. Yaswanth Kumar 
📧 yashyaswanth714@gmail.com
