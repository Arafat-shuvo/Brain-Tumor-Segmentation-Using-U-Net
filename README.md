# Brain Tumor Segmentation using U-Net

A deep learning project for brain tumor segmentation from MRI images using the U-Net architecture. This repository includes data preprocessing, model training, evaluation, and inference scripts.

## 📌 Features

- U-Net implementation in PyTorch
- MRI image preprocessing
- Automatic dataset splitting
- Model training and validation
- Dice Score and IoU evaluation
- Model checkpoint saving
- Inference on new MRI images

## 🛠️ Tech Stack

- Python 3.11
- PyTorch
- NumPy
- OpenCV
- Albumentations
- Matplotlib
- scikit-learn


## 📊 Dataset

This project is designed for brain MRI segmentation datasets such as:

- BraTS 2021
- BraTS 2023

> Download the dataset from the official BraTS website.

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/your-repository.git
cd your-repository
```

Install dependencies

```bash
pip install -r requirements.txt
```

## ⚙️ Data Preprocessing

```bash
python preprocess.py
```

## 🏋️ Train the Model

```bash
python train.py
```

## 📈 Evaluate

```bash
python evaluate.py
```

## 🔍 Inference

```bash
python inference.py
```

## 📐 Evaluation Metrics

- Dice Score
- Intersection over Union (IoU)
- Loss Curve

## 🖼️ Sample Results

| MRI Image | Ground Truth | Prediction |
|-----------|--------------|------------|
| Coming Soon | Coming Soon | Coming Soon |

## 📦 Requirements

- Python 3.11+
- PyTorch
- CUDA (Optional)

Install:

```bash
pip install -r requirements.txt
```

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Md. Arafat Hossain**

GitHub: https://github.com/Arafat-shuvo

---

If you find this project useful, please ⭐ the repository.
