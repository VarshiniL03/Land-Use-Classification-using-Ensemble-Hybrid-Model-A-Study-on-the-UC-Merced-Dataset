# Land-Use-Classification-using-Ensemble-Hybrid-Model-A-Study-on-the-UC-Merced-Dataset
This repository presents a deep learning-based remote sensing project that performs land use classification using aerial imagery from the UCMerced Land Use Dataset. The system combines pretrained CNN models (MobileNet and DenseNet121) for feature extraction and utilizes a linear SVM for final classification.
Achieving 96.57% accuracy, this hybrid ensemble approach is optimized for both accuracy and computational efficiency, making it suitable for real-time geospatial analysis and environmental applications.

🧠 Highlights
📷 Uses UCMerced dataset with 21 land use categories
🧩 Combines MobileNet and DenseNet121 features
⚙️ Employs linear SVM classifier with SMOTE balancing
✅ Accuracy: 96.57% | Macro-F1: 96.57%
📊 Evaluated using 5-fold stratified cross-validation

📦 Requirements
* tensorflow
* scikit-learn
* imbalanced-learn
* numpy
* matplotlib
* seaborn

⚙️ How to Run the Project
* Clone the Repository
* Open the Jupyter Notebook
* Run the notebook main_notebook.ipynb in Jupyter or Google Colab.
* Run the Pipeline
* Load UCMerced Dataset
* Perform preprocessing and augmentation
* Extract deep features from MobileNet and DenseNet121
* Apply SMOTE for class balancing
* Train and evaluate SVM using 5-fold cross-validation

Sample images from UC Merced Dataset

![image](https://github.com/user-attachments/assets/c5579257-690c-491f-862f-042832031f83)


System Architecture

![image](https://github.com/user-attachments/assets/48378b30-a42b-4f9f-afa3-a6437cfd081d)

📈 Output & Results
 ✅ Accuracy: 96.57%
 🎯 Macro Precision: 96.82%
 🔁 Macro Recall: 96.57%
 🧠 Macro F1-Score: 96.57%

Confusion Matrix

![image](https://github.com/user-attachments/assets/c9c122cc-d3bd-47a8-b094-69f56b9ff668)

Visualizations include:
* Confusion matrices for all folds
* Accuracy/loss curves
* Class-wise performance metrics
