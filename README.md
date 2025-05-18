# 🚗 Automatic Number Plate Recognition (ANPR) using YOLOv8 & EasyOCR

An end-to-end solution for detecting and reading vehicle number plates in video files using **YOLOv8** for object detection and **EasyOCR** for text extraction. The project displays annotated frames in a Jupyter Notebook and saves the output as a video file.

## 📌 Features

 🔍 Vehicle license plate detection using YOLOv8
 🧠 OCR on detected plates using EasyOCR
 🎥 Video frame processing and real-time display in Jupyter Notebook
 💾 Save annotated video output (`.avi`)

🧠 Model Information

Model used: license_plate.pt (YOLOv8 format)

● You can train this using a dataset like OpenALPR or your own plate dataset

● Alternatively, test with a default YOLOv8 model: yolov8n.pt (not optimized for platees)

📈 Future Enhancements 

 Add CSV export of detected plate numbers

 Real-time detection from webcam

 Build a simple Streamlit/Flask dashboard

 Add region-specific number plate formatting filters




