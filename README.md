
# Custom Image Classification Model

**CSE445: Machine Learning — Course Project**

This repository contains the implementation and resources for a custom image classification model developed as part of the CSE445 (Machine Learning) course project. The objective is to design, train, and evaluate a robust classifier capable of distinguishing between five animal classes: **Dog, Cow, Cat, Lamb, and Zebra**.

## Project Overview

The project demonstrates the end-to-end process of building an image classification system using machine learning techniques. It covers dataset preparation, preprocessing, model selection, training, evaluation, and result analysis. The primary goal is to achieve at least **90% accuracy** in classifying the five animal categories.

https://github.com/MRSHAKILS/Custom-image-classification-model/blob/main/others/445%20Project%20Presentation%20Video.mp4

## Key Features

- **Custom Dataset**: 100+ images per class, organized for supervised learning.
- **Comprehensive Workflow**: Includes data cleaning, preprocessing, augmentation, model training, and evaluation.
- **Multiple Models**: Experiments with various machine learning and deep learning algorithms (e.g., XGBoost, KNN, Decision Tree, SVM-RBF Kernel, Logistic Regression).
- **Jupyter Notebooks**: All code and experiments are documented in interactive notebooks for reproducibility and clarity.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/MRSHAKILS/Custom-image-classification-model.git
   cd Custom-image-classification-model
   ```

2. **Dataset Preparation**
   - Collect at least 100 images for each animal class (Dog, Cow, Cat, Lamb, Zebra).
   - Place images in respective folders under `data/` (e.g., `data/dog/`, `data/cow/`, etc.).

3. **Install Dependencies**
   - Ensure Python 3.8+ and Jupyter Notebook are installed.
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```

4. **Run the Notebooks**
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open the relevant notebook (e.g., `hybrid-model.ipynb`, `xgboost-with-vgg16-and-rbf.ipynb`) and follow the instructions.

## Methodology

1. **Data Loading**: Images are loaded and split into training, validation, and test sets.
2. **Preprocessing**: Images are resized, normalized, and augmented to improve model generalization.
3. **Model Training**: Multiple algorithms are trained and compared, including deep learning and traditional ML models.
4. **Evaluation**: Models are evaluated using accuracy and other relevant metrics, with a target of ≥90% accuracy.

## Learning Outcomes

- Gain practical experience in computer vision and machine learning.
- Understand the workflow of building and evaluating image classifiers.
- Develop skills in data collection, preprocessing, and model selection.

## Contributing

Contributions, suggestions, and improvements are welcome. Please open an issue or submit a pull request for any changes or enhancements.


---

**Course:** CSE445 (Machine Learning)

**Institution:** North South University

**Instructor:** [Dr. Mohammad Shifat-E-Rabbi (MSRB)](https://ece.northsouth.edu/people/dr-mohammad-shifat-e-rabbi/)

**Authors:**

| Name                         | ID         |
|------------------------------|------------|
| Raisul Islam Kabbo           | 2222542042 |
| Md. Rafawat Islam            | 2122343642 |
| Shakil Ahmed                 | 2221453042 |
| Entishar Rashid Chowdhury    | 2222145042 |
| Sudipto Roy                  | 2222756042 |

---

Happy coding! 
