# Pendigit_Analysis_and_Visualization.ipynb

## Overview

The **Pendigit Dataset** is a widely recognized dataset in the field of handwriting recognition, consisting of thousands of numeric samples representing handwritten digits. This dataset plays a critical role in understanding and developing systems for digit recognition, which is essential for Optical Character Recognition (OCR) applications. This project explores the dataset through preprocessing, visualization, and machine learning techniques to gain insights and build predictive models.

---

## Project Features

### 1. Exploratory Data Analysis (EDA)
- Analyze the dataset structure and statistical properties.
- Identify patterns and trends in handwriting styles.
- Generate summary statistics for better understanding.

### 2. Data Visualization
- Create meaningful visualizations to represent insights:
  - **Scatter Plots**: Visualize clusters of digits based on feature relationships.
  - **Heatmaps**: Show feature correlations for better understanding of dependencies.
  - **Sample Visualizations**: Display examples of handwritten digit representations.

### 3. Machine Learning Models
The following models and techniques were implemented:
- **Decision Tree**:
  - Explored the impact of tree depth on accuracy and overfitting.
  - Pruning was used to balance model performance.
- **Bagging**:
  - Compared hard voting and soft voting strategies.
  - Highlighted trade-offs between computation time and accuracy.
- **Boosting**:
  - Demonstrated superior accuracy compared to bagging.
  - Discussed risks of overfitting in boosting methods.
- **PCA and Feature Selection**:
  - Reduced dimensionality and highlighted important features to improve performance.
- **Random Forest**:
  - Achieved high classification accuracy but flagged for overfitting concerns.

---

## Dataset Details

- **Source**: Pendigit dataset (UCI Machine Learning Repository or other sources).
- **Content**: Handwritten digit samples represented numerically.
- **Features**: 
  - Numeric attributes representing x and y coordinates of pen strokes.
  - Class labels indicating the digit (0-9).

---

## Visualizations

The project includes the following visualizations:
1. **Scatter Plots**:
   - Show clustering of different digits based on their feature space.
2. **Heatmaps**:
   - Highlight feature correlations and relationships.
3. **Sample Visualizations**:
   - Provide a graphical representation of digits to show patterns in the dataset.

---

## Results

1. **Decision Tree**:
   - Demonstrated how pruning can enhance model reliability by preventing overfitting.
2. **Bagging**:
   - Showed the advantages of soft voting over hard voting for accuracy.
3. **Boosting**:
   - Achieved higher accuracy than bagging, with considerations of potential overfitting.
4. **Random Forest**:
   - Reached 100% accuracy, signaling overfitting concerns despite excellent performance.
5. **PCA and Feature Selection**:
   - Improved model performance by reducing noise and irrelevant features.
