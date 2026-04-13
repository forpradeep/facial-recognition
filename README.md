# Face Recognition Attendance System 🎓

A real-time face recognition based attendance system built with Python, OpenCV, and Streamlit.

## 🔗 Live Dashboard
https://facial-recognition-pradeep.streamlit.app/

## 📸 Features
- Real-time face detection using OpenCV
- Face recognition using KNN algorithm
- Automatic attendance marking
- Text-to-speech notification
- Web dashboard using Streamlit

## 🛠️ Tech Stack
- Python 3.11
- OpenCV
- Scikit-learn (KNN)
- Streamlit
- Pandas
- NumPy
- PyWin32 (Text to Speech)

## ⚙️ Installation

### Step 1 - Clone the repository
git clone https://github.com/forpradeep/facial-recognition
cd facial-recognition

### Step 2 - Create virtual environment
py -3.11 -m venv .venv
.venv\Scripts\activate

### Step 3 - Install dependencies
pip install -r requirements.txt

## 🚀 Usage

### Step 1 - Add your face (only once)
python add_face.py
- Enter your name
- Look at the webcam
- Wait for 100 photos to be captured

### Step 2 - Mark attendance
python test.py
- Look at the webcam
- It will recognize your face
- Attendance is automatically saved

### Step 3 - View attendance
python -m streamlit run "app.py"
- Open browser at http://localhost:8501
- View attendance table

## 📁 Project Structure
facial-recognition/
├── add_face.py        # Add new face
├── test.py            # Mark attendance
├── app.py             # Streamlit dashboard
├── requirements.txt   # Dependencies
├── background.png     # Background image
├── data/              # Face data and models
└── Attendance/        # Attendance CSV files

## ⚠️ Requirements
- Windows OS
- Webcam
- Python 3.11

## 👤 Author
Pradeep
GitHub: https://github.com/forpradeep
