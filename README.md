**🧠 Real-Time Face and Eye Detection System**

A real-time face and eye detection project using Python and OpenCV. Implements Haar Cascade Classifiers to identify faces and eyes from live video feed, highlighting them with labeled boxes. Focused on accuracy, speed, and simple visualization for easy interaction.


**📋 Description**
* The Real-Time Face and Eye Detection System is a computer vision mini-project developed using Python and OpenCV.
  It demonstrates real-time object detection through a live webcam feed using Haar Cascade Classifiers a machine learning-based method for visual object recognition.
  
* The system captures video frames, converts them into grayscale, and applies pre-trained cascades to detect human faces and eyes efficiently. 
  Detected objects are highlighted with color coded bounding boxes (green for faces and blue for eyes), and results are displayed live with smooth rendering.
  
* This project emphasizes accuracy, speed, and user-friendliness, achieved through optimized detection parameters and an intuitive visualization interface.
  It runs seamlessly both in Jupyter Notebook (for demonstration) and as a standalone Python script.
  
* The project provided hands-on experience in image processing, object detection, and real-time video analysis, showcasing how traditional algorithms can be used effectively in practical computer vision applications.


**🚀 Features**

Real-time detection of faces and eyes from webcam input.

Uses Haar Cascade Classifiers for efficient detection.

Displays bounding boxes with clear labels.

Adjustable parameters for better accuracy and performance.

Works in both Jupyter Notebook and command-line script modes.

Modular and easy to extend with other detectors or DNN models.


**🧰 Technologies Used**

Python 3.x

OpenCV (cv2)

NumPy

Pillow (PIL)

Jupyter Notebook



**📂 Folder Structure**

**realtime-face-eye-detection/
│

├── src/

│   └── face_eye_detection.py    # Main program file

│

├── notebooks/

│   └── RealTime_Face_Eye_Detection.ipynb

│

├── assets/

│   ├── screenshot1.png

│   └── demo.gif

│

├── requirements.txt

├── README.md

└── LICENSE**


**⚙️ Installation and Setup**

1.Clone the repository
git clone https://github.com/<your-username>/realtime-face-eye-detection.git
cd realtime-face-eye-detection

2.Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows

3.Install required packages
pip install -r requirements.txt

4.Run the program
python src/face_eye_detection.py

Press q to close the live webcam window.



**🧪 Running in Jupyter Notebook**

**Open the file:**
notebooks/RealTime_Face_Eye_Detection.ipynb
Run each cell to see the live detection output right inside your notebook (you’ll need webcam permissions).


**🛠️ How It Works**

1.Captures frames from your system’s webcam.

2.Converts frames to grayscale for efficient processing.

3.Applies Haar Cascade Classifiers to detect faces.

4.Locates eyes within detected face regions.

5.Draws labeled bounding boxes and displays live results.


**🌟 Future Enhancements**

1.Add Deep Learning (DNN)-based face detectors for better accuracy.

2.Integrate mask detection or emotion recognition.

3.Include a GUI for starting/stopping the camera feed.

4.Deploy as a small desktop or web app using Flask or Streamlit.


**🧑‍💻 Author**
Vidyashree S

🎓 Student Project – Computer Vision / Python

📧 vidyaa1103@gmail.com

🌐 

