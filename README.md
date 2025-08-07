# 🔍 AI-Based Firearm Detection
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is an independent mini project that leverages **deep learning** and **computer vision** to detect firearms in real-time through live camera feeds. Built using **YOLOv8**, it demonstrates how AI can enhance security and public safety by triggering alerts the moment a weapon is spotted.

---

## 🚀 Features

- 🎯 **Real-Time Firearm Detection** using YOLOv8  
- 📢 **Instant Alerts** with customizable alarm sounds  
- 🖥️ **GUI Interface** for simple, local monitoring  
- 🌐 **Web Server Dashboard** using Django  
- 🛠️ **Trainable and Extendable** on new custom datasets  

---

## 🧩 Installation

1. **Clone This Repository**
   ```bash
   git clone https://github.com/AdvaitRak/AI-Based-Firearm-Detection.git
   cd AI-Based-Firearm-Detection
   ```

2. **Install Dependencies**  
   Make sure you have Python 3.8+ and then run:
   ```bash
   pip install -r needs.txt
   ```

3. **Download YOLOv8 Model**  
   Place the `yolov8m.pt` file in the project root. You can download it from [Ultralytics YOLOv8 GitHub](https://github.com/ultralytics/ultralytics).

---

## 🧪 Usage

### 1. Run the GUI App
```bash
python guiapp.py
```

### 2. Launch the Web Dashboard (Django)
```bash
cd weapon_detection_server
python manage.py runserver
```

### 3. Train on Custom Dataset
```bash
python train.py
```

### 4. Test the Model
```bash
python test.py
```

### 5. Download Images for Training/Testing
```bash
python download_images.py
```

---

## 📁 Project Structure

```
├── alarm.mp3                  # Alarm sound file  
├── best.pt                    # Trained model checkpoint  
├── guiapp.py                  # Main GUI application  
├── train.py                   # Training script  
├── test.py                    # Testing script  
├── oog.py                     # Miscellaneous script  
├── download_images.py         # For image scraping  
├── needs.txt                  # Python dependencies  
├── yolov8m.pt                 # Pre-trained YOLOv8 model  
└── weapon_detection_server/   # Django web server  
    ├── app1/                  # Django app logic  
    ├── media/                 # Uploaded images  
    ├── static/                # CSS/JS files  
    ├── template/              # HTML templates  
    ├── db.sqlite3             # SQLite database  
    └── manage.py              # Django management script  
```

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to submit issues, feature requests, or pull requests.

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👤 Author

**Advait Rak**  
This is an independent project built for academic and practical exploration in AI-powered security systems.
