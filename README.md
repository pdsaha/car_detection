
# Real-Time Car Number Plate Extraction using Deep Learning 

This project presents a real-time system for automatic car number plate detection and recognition using advanced deep learning and computer vision techniques. Developed as part of an academic initiative at BUET, the system is designed to process live video feeds to identify vehicles, detect license plates, and recognize the alphanumeric characters using OCR — all in real-time.

## 🔧 Features

* Real-time vehicle detection from video streams
* License plate localization using:

  * **YOLOv5**
  * **Inception ResNet v2**
  * **VGG-16**
* Optical character recognition (OCR) using **Tesseract**
* Accurate character segmentation and recognition
* Outputs stored in structured CSV format
* Tested on datasets like **Kaggle ANPR** and **UFPR-ALPR**

## 🧠 Technologies Used

* Python, OpenCV
* Deep Learning (PyTorch/TensorFlow)
* Inception ResNet v2, YOLOv5, VGG-16
* Tesseract OCR
* Real-time video processing

## 📊 Results

| Model               | Train Accuracy | Validation Accuracy | Test Accuracy |
| ------------------- | -------------- | ------------------- | ------------- |
| Inception ResNet v2 | \~68%          | \~66%               | 61.75%        |
| YOLOv5              | \~67%          | \~55%               | 48.93%        |
| VGG-16              | \~72.5%        | \~58%               | 51.21%        |

## 📁 Outputs

Each detection event is logged in a CSV file including:

* License plate number
* Timestamp
* Additional info (e.g., vehicle type if available)

## 🔬 Future Work

* Real-world testing under diverse weather/lighting conditions
* Development of a dedicated Bangladeshi license plate dataset
* Improved OCR performance for multilingual plates (e.g., Bangla)

## 📚 Acknowledgments

Developed under the supervision of **Dr. Shaikh Anowarul Fattah** and **Shahed Ahmed** at BUET for the course EEE 402 (Artificial Intelligence and Machine Learning Sessional).

## 📎 References

* [Automatic Number Plate Detection using Deep Learning – Girinath N](https://ieeexplore.ieee.org/document/10009582)
* [UFPR-ALPR Dataset](https://paperswithcode.com/dataset1/ufpr-alpr)
* [Kaggle ANPR Dataset](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection)
