# Hey, I'm Rishi Shanthan 👋

**ML / AI Engineer** · **Computer Vision** · **Published Researcher** · **Original Dataset Author**

I build ML/DL systems **from scratch** — hand-coded backpropagation, diffusion samplers, camera calibration via DLT+SVD, and biometric evaluation pipelines. ~5 years of experience across computer vision, generative modeling, NLP, and production software engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rishishanthan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishishanthan)
[![Kaggle](https://img.shields.io/badge/Kaggle-rishishanthan-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/rishishanthan)
[![Email](https://img.shields.io/badge/Email-rishishanthan@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rishishanthan@gmail.com)
[![HuggingFace](https://img.shields.io/badge/🤗_Live_App-Blackberry_Lime_Classifier-FFD21E?style=for-the-badge)](https://huggingface.co/spaces/brs13/blackberry-lime-classifier)

---

### 🔧 Tech Stack

**Languages:** `Python` `SQL` `MATLAB` `R` `C` `JavaScript`  
**DL / ML:** `PyTorch` `TensorFlow` `scikit-learn` · CNNs · LSTMs · Transformers · Diffusion (DDIM) · GANs · Autoencoders  
**Computer Vision:** `OpenCV` · YOLO · Face Recognition · Biometrics (PAD) · Medical Imaging  
**Data & Infra:** `pandas` `NumPy` `Docker` `Git` `Linux` `Supabase/Postgres` `REST APIs` `CUDA` `HuggingFace` `MLflow`  
**Cloud:** AWS Solutions Architect (Associate) · AWS Cloud Practitioner · AWS AI Practitioner

---

### 🚀 Featured Projects

> These are the highlights — [all 23 repos are listed below](#-all-repositories)

| | Project | What I Built | Key Result |
|:--:|---|---|---|
| 🎨 | [**DDIM Inpainting**](https://github.com/rishishanthan/ddim-mnist-inpainting) | From-scratch UNet + DDIM diffusion with v-prediction, self-conditioning, EMA, CoordConv | PSNR 14.41 on MNIST |
| 🔐 | [**Face PAD (Anti-Spoofing)**](https://github.com/rishishanthan/face-pad-msu-mfsd) | End-to-end video-level face attack detection. Subject-disjoint protocol, EER/ACER thresholds | ACER 0.029, Acc 98.1% |
| 🍇 | [**Blackberry-Lime Classifier**](https://github.com/rishishanthan/blackberry-lime-visual-classifier) | Original 6K-image dataset (published on Kaggle) + dual ResNet-18 classifier → [**Live App**](https://huggingface.co/spaces/brs13/blackberry-lime-classifier) | 100% / 99% accuracy |
| 🧠 | [**Transformer from Scratch**](https://github.com/rishishanthan/transformer-from-scratch-seq) | Encoder + Decoder with sinusoidal positional encoding, multi-head attention on Yelp Polarity | 79% test, ROC-AUC |
| 📈 | [**LSTM Stock + VaR**](https://github.com/rishishanthan/lstm-stock-forecasting-with-var) | Next-day forecasting with Value-at-Risk quantification on Dropbox stock | MAPE 1.51%, R² 0.908 |
| 🧮 | [**From-Scratch MLP**](https://github.com/rishishanthan/handwritten-digits-and-faces-mlp) | Hand-coded forward pass + backpropagation + L2 reg, no autograd. MNIST + CelebA faces | 95% / 85% test |
| 📹 | [**YOLOv3 Traffic Detection**](https://github.com/rishishanthan/traffic-object-detection-yolov3) | Real-time detection on traffic video with NMS, custom IoU, FPS profiling | Real-time on 3 videos |
| 📷 | [**Camera Calibration**](https://github.com/rishishanthan/camera-geometry-calibration) | DLT + SVD camera calibration from scratch — intrinsic & extrinsic decomposition | Pure NumPy math |

---

### 📄 Publication

**"Cardiovascular Disease Prediction using ML"** — *IJSREM, Vol. 07, Issue 08, Aug 2023*  
Co-authored · Cleveland Heart Disease DB · LogReg vs Random Forest · Flask web app  
[📎 View Paper](https://ijsrem.com/download/cardiovascular-disease-prediction-using-ml/)

---

### 📂 All Repositories

<details>
<summary><b>🧠 Deep Learning & Generative Models</b> (click to expand)</summary>

- [ddim-mnist-inpainting](https://github.com/rishishanthan/ddim-mnist-inpainting) — DDIM diffusion, UNet, v-prediction, self-conditioning
- [transformer-from-scratch-seq](https://github.com/rishishanthan/transformer-from-scratch-seq) — Transformer encoder+decoder on Yelp Polarity
- [lstm-sentiment-analysis](https://github.com/rishishanthan/lstm-sentiment-analysis) — LSTM vs GloVe+BiGRU on IMDB 50K (81.8%)
- [anomaly-detection-autoencoders](https://github.com/rishishanthan/anomaly-detection-autoencoders) — Dense AE on NAB CloudWatch data
- [lstm-stock-forecasting-with-var](https://github.com/rishishanthan/lstm-stock-forecasting-with-var) — LSTM + Value-at-Risk on stock data
- [covid-mlp](https://github.com/rishishanthan/covid-mlp) — MLP on CDC COVID data (87.58%)
</details>

<details>
<summary><b>👁️ Computer Vision & Biometrics</b> (click to expand)</summary>

- [face-pad-msu-mfsd](https://github.com/rishishanthan/face-pad-msu-mfsd) — Video-level face anti-spoofing (PAD)
- [faces-can-lie-identity-analysis](https://github.com/rishishanthan/faces-can-lie-identity-analysis) — ArcFace embeddings + clustering
- [traffic-object-detection-yolov3](https://github.com/rishishanthan/traffic-object-detection-yolov3) — Real-time YOLOv3 detection
- [camera-geometry-calibration](https://github.com/rishishanthan/camera-geometry-calibration) — DLT camera calibration from scratch
- [rgb-channel-alignment](https://github.com/rishishanthan/rgb-channel-alignment) — ORB + RANSAC homography alignment
- [blackberry-lime-visual-classifier](https://github.com/rishishanthan/blackberry-lime-visual-classifier) — Original dataset + deployed app
- [octmnist-retinal-disease-cnn](https://github.com/rishishanthan/octmnist-retinal-disease-cnn) — Medical imaging CNN (91.3%)
- [vgg16-vs-resnet18-64x64](https://github.com/rishishanthan/vgg16-vs-resnet18-64x64) — From-scratch VGG vs ResNet
- [cnn-multiclass-28x28](https://github.com/rishishanthan/cnn-multiclass-28x28) — 36-class CNN, 3-optimizer comparison
</details>

<details>
<summary><b>📊 Classical ML (From Scratch — No sklearn)</b> (click to expand)</summary>

- [mnist-logreg-svm](https://github.com/rishishanthan/mnist-logreg-svm) — Hand-coded LogReg + Softmax + SVM sweep (98.32%)
- [lda-qda-ridge-regression](https://github.com/rishishanthan/lda-qda-ridge-regression) — LDA/QDA/Ridge all from scratch
- [handwritten-digits-and-faces-mlp](https://github.com/rishishanthan/handwritten-digits-and-faces-mlp) — MLP with manual backprop
- [kmeans-farthest-first-init](https://github.com/rishishanthan/kmeans-farthest-first-init) — Farthest-first K-Means (3.4× speedup)
- [adult-census-income-prediction](https://github.com/rishishanthan/adult-census-income-prediction) — NB/DT/RF/XGBoost pipeline
</details>

<details>
<summary><b>🔬 Research & Numerical Methods</b> (click to expand)</summary>

- [nanoglass-md-preprocessor](https://github.com/rishishanthan/nanoglass-md-preprocessor) — MATLAB + LAMMPS for Cu-Zr nanoglass MD (B.Tech thesis)
- [predictive-health-assessment](https://github.com/rishishanthan/predictive-health-assessment) — K-Means health risk stratification (R, 100K records)
- [Mini-Projects](https://github.com/rishishanthan/Mini-Projects) — Gauss-Newton, Monte Carlo/LHS, Newton-Raphson, ARIMA, time-series
</details>

---

### 🎓 Education

**Master of Science in Engineering Science (Data Science)** — University at Buffalo (SUNY), 2024–2025  
**Bachelor of Tech** — IIT Bhubaneswar, 2019–2023

---

*Building models that see, think, and act intelligently.*
