🚗 Number Plate Detection of Vehicles
A smart and automated system that detects and recognizes vehicle number plates using Computer Vision and OCR (Optical Character Recognition). This project is built using Python, OpenCV, and EasyOCR, and is suitable for applications like traffic surveillance, parking automation, toll systems, and smart city infrastructure.

📌 Features
Detects number plates from static images or video frames
Recognizes text using OCR (EasyOCR)
Supports grayscale preprocessing and contour detection
Easily extensible to real-time applications
Flexible deployment: Local, Web, or Cloud
🧾 Project Structure

number-plate-detection/
│
├── Number\_Plate\_Detection.ipynb     # Main Jupyter Notebook
├── images/                          # Folder to store input images
├── outputs/                         # Folder for results (detected plates)
├── README.md                        # Documentation
└── requirements.txt                 # List of dependencies

🛠️ Libraries Used
Library	Purpose
OpenCV	Image processing and plate region detection
EasyOCR	Recognizing characters from plate regions
NumPy	Numerical operations
Matplotlib	Displaying processed images
▶️ How to Run
Clone this repository:
git clone https://github.com/your-username/number-plate-detection.git
cd number-plate-detection

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Number_Plate_Detection.ipynb
   ```

---

## 🧱 Architecture Overview

1. **Input**: Image or video frame
2. **Preprocessing**: Grayscale, thresholding, edge detection
3. **Plate Detection**: Find contours likely to be plates
4. **Text Recognition**: OCR using EasyOCR
5. **Output**: Annotated image with detected number plate and text

---

## 🚫 Limitations

* Lower accuracy in poor lighting or motion blur
* Fails on dirty/damaged plates
* Difficulty reading regional languages or fancy fonts

---

## 🔮 Future Enhancements

* Integrate YOLOv8 for robust plate detection
* Real-time video processing support
* Database logging and vehicle tracking
* Multilingual OCR using fine-tuned models

---

## 🚀 Deployment Options

* **Local**: Run the notebook or script on a PC or Raspberry Pi
* **Web App**: Integrate with Flask/Django
* **Cloud**: Deploy as an API using AWS, GCP, or Azure

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Jushna Breethi**
Computer Science Engineering Student
Project Title: *Number Plate Detection of Vehicles*

---
