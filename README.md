[README_YODA.md](https://github.com/user-attachments/files/27915123/README_YODA.md)
# Y.O.D.A - Your Optical Detection Assistant

AI-powered face recognition and image analysis system built using Python, OpenCV, Streamlit, and PostgreSQL.

---

## 📌 Overview

Y.O.D.A (Your Optical Detection Assistant) is an intelligent face recognition system designed to detect, analyze, and compare faces from uploaded images using computer vision and AI techniques.

The project combines traditional face detection methods with modern embedding-based similarity comparison to provide an interactive and efficient facial recognition experience.

---

## 🚀 Features

- Face detection using Haar Cascade
- AI-based face embeddings using CLIP
- Duplicate face detection and comparison
- Interactive Streamlit web interface
- PostgreSQL database integration
- Stored image gallery management
- Smart AI image suggestions
- Adjustable detection settings
- Real-time image upload and processing

---

## 🧠 Technologies Used

### Programming & Frameworks
- Python 3
- Streamlit

### Computer Vision & AI
- OpenCV
- CLIP Model
- Sentence Transformers

### Database
- PostgreSQL
- pgvector
- psycopg2

### Additional Libraries
- NumPy
- PIL
- Requests
- streamlit-lottie

---

## 🏗️ System Architecture

1. Upload image through Streamlit interface
2. Detect faces using Haar Cascade
3. Generate embeddings using CLIP
4. Compare embeddings with stored database
5. Store only unique faces
6. Display results and similarity matches

---

## 📸 Main Interfaces

### Upload and Store Faces
Upload images and automatically store unique faces.

### Search for Faces
Search for similar faces using AI embeddings.

### Stored Gallery
Manage stored images inside the database.

### Smart AI Suggestions
Receive AI-based suggestions for improving image quality.

### Settings
Adjust detection parameters such as `minNeighbors`.

---

## ⚙️ Installation

```bash
git clone https://github.com/AAFLY99/yoda-face-recognition.git
cd yoda-face-recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 🗄️ Database Setup

The project uses PostgreSQL with pgvector extension.

Example connection setup:

```python
conn = psycopg2.connect(
    host="localhost",
    database="yoda",
    user="postgres",
    password="your_password"
)
```

---

## 📈 Results

- Successfully detects and compares faces
- Interactive and user-friendly UI
- Embedding-based duplicate prevention
- Achieved approximately 70% detection accuracy under suitable lighting conditions

---

## ⚠️ Challenges

- Low-light image detection
- Side-angle face recognition
- Similarity threshold tuning
- Streamlit and CLIP integration compatibility

---

## 🔮 Future Improvements

- Real-time camera detection
- Improved AI models for higher accuracy
- Better low-light performance
- Advanced image management
- Data encryption and enhanced security
- Automatic face labeling

---

## 👨‍💻 Authors

- Ahmed Al Faleet
- Ali Tawfiq Naji
- Omar Ismail Badi

Supervisor:
- Dr. Marwa Aldakhli

---

## 📄 License

This project is developed for educational and research purposes.
