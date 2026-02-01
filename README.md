# 🔢 Task 10: KNN Handwritten Digit Classification

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange?logo=scikit-learn)

## 📖 Overview
**Task 10** explores computer vision basics. We used **K-Nearest Neighbors (KNN)** to recognize handwritten digits from the Scikit-Learn `digits` dataset.

## ⚙️ Workflow
1.  **Data Loading:** Loaded 8x8 pixel grayscale images of digits 0-9.
2.  **Scaling:** Applied `StandardScaler` to normalize pixel intensities (crucial for distance calculations).
3.  **Tuning:** Tested K values [1, 3, 5, 7, 9] to find the optimal number of neighbors.
4.  **Evaluation:** Visualized misclassifications using a Confusion Matrix.

## 📊 Key Results
* **Best K:** Found that K=__ (fill in from your run) gave the highest accuracy.
* **Accuracy:** Achieved ~98% accuracy on the test set.

## 🖼️ Visualizations
| Visualizations |
| :---: |
| **K-Value Tuning** |
| <img width="708" height="470" alt="K-Value Plot" src="https://github.com/user-attachments/assets/7e0231aa-4951-4bf5-a2e4-e94fcefbc282" /> |
| **Sample Predictions** |
| <img width="1189" height="567" alt="Sample Predictions" src="https://github.com/user-attachments/assets/3133ad1f-71f8-4c19-affc-1406ad30f4c7" /> |

---
## 📂 Deliverables
* [📓 Jupyter Notebook](./Task_10.ipynb)
