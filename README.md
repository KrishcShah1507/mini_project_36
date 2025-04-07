# YOLO-Based Toor Dal Classification 🫘📸

This project uses a YOLOv8 model to classify different types of Toor Dal grains using image analysis. It aims to bring transparency and trust in the grain trade by automatically identifying the grain type from images.

---

## 📁 Project Structure

mini_project_36/ ├── dataset/ │ ├── type_1.zip │ └── type_2.zip ├── yolo_training.ipynb └── README.md

---

## 🚀 Features

- ✅ Image-based classification of Toor Dal grains
- ✅ YOLOv8 model trained on annotated datasets
- ✅ Bulk classification support (multiple grains per image)
- ✅ Potential to extract color and size-based features for better accuracy
- ✅ Can assist both sellers and buyers in verifying product quality

---

## 📦 Dataset

- Stored in `dataset/` folder
- Two ZIP files:
  - `type_1.zip`: Contains images of Toor Dal - Type 1
  - `type_2.zip`: Contains images of Toor Dal - Type 2
- Annotated using [Roboflow](https://roboflow.com/) for YOLOv8

---

## 🧠 Model Training

The training notebook is in `yolo_training.ipynb`, and includes:
- Preprocessing with OpenCV
- YOLOv8 training and validation
- Prediction and visualization

---

## 🔮 Future Enhancements

- Add more Toor Dal types
- Combine type models into a single multi-class YOLO model
- Integrate with a mobile/web app for real-time grain quality verification
- Feature extraction (color, size, texture) for quality-based pricing

---

## 👨‍💻 Author

**Krish Shah**  
[GitHub: KrishcShah1507](https://github.com/KrishcShah1507)

---

## 📜 License

This project is for academic/research use. Please contact the author for commercial usage or collaboration.
