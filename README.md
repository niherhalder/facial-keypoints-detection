# 👁️ Facial Keypoints Detection using CNN

This project predicts **30 facial keypoints** (e.g., eyes, nose, mouth corners) from grayscale face images using a custom **Convolutional Neural Network (CNN)** built with TensorFlow and Keras.

---

## 📁 Project Structure

facial-keypoints-detection/
├── notebooks/
├── gallery/
├── model/
├── submission/
├── report/
├── requirements.txt
├── README.md

---

## 🧠 Tools & Technologies

- **TensorFlow / Keras** — Deep learning framework  
- **Python**, **Pandas**, **NumPy** — Data handling  
- **Matplotlib**, **Seaborn** — Visualization  
- **OpenCV** (optional) — Image processing


---

## ✅ Model Performance

- **Root Mean Squared Error (RMSE)**: `0.0230`  
- **Mean Absolute Error (MAE)**: `0.0163`  
- **Training Data**: 2,140 labeled 96x96 grayscale images  
- **Model**: Custom CNN with augmentation and early stopping  
- **Result**: Robust keypoint detection with strong generalization

---


## ✅ Results

- **RMSE**: 0.0230
- **MAE**: 0.0163
- Trained on 2140 labeled images
- Generalizes well on test data

---

## 📸 Visual Outputs (from `gallery/`)

| Visual | Description |
|--------|-------------|
| `predicted_vs_actual_keypoints.png` | Comparison of predicted vs true landmarks |
| `cnn_architecture_diagram.png` | Model layer flow |
| `face_grid_keypoints_comparison.png` | Sample grid of predicted faces |
| `submission_file_preview.png` | Kaggle-style CSV preview |
| `training_validation_rmse_curve.png` | Training vs validation loss graph |

## 📂 Deliverables

- ✅ 6-stage Jupyter notebook pipeline  
- ✅ Trained model file (`cnn_model.h5`)  
- ✅ Final CSV predictions (`submission/final_submission.csv`)  
- ✅ Visual outputs gallery  
- ✅ 📄 [PDF summary report](./report/project_summary.pdf)


---

## 🧠 Conclusion

This project demonstrates a full **deep learning pipeline for facial landmark detection**, showcasing:
- Custom CNN architecture
- Data augmentation and tuning
- Visual analysis of predictions

👉 Applicable in **biometrics, AR/VR, facial analysis, and healthcare** use cases.

---

> _“AI doesn’t just recognize faces — it understands the points that make us human.”_

---
