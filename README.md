# 🌱 Agricultural Pest Classification using Deep Learning

This repository hosts the implementation of our research on **automated agricultural pest classification** using computer vision and deep learning techniques.  
The project focuses on building an ensemble learning framework that can accurately classify different insect species from images, supporting **early pest detection** and **sustainable agricultural practices**.  

The notebook (`Agricultural_Pest_Classification.ipynb`) has been made public to ensure **reproducibility** of our results, in line with research best practices.

---

## 📌 Motivation

Agricultural pests are among the leading causes of crop losses worldwide, impacting both food security and the economy. Early and accurate pest identification is crucial for implementing Integrated Pest Management (IPM) strategies.  

Traditional pest identification methods rely on expert entomologists and are time-consuming, making them impractical for large-scale deployment. By leveraging **deep learning models trained on pest image datasets**, we aim to provide a scalable and efficient solution for automatic pest classification.

---

## 📊 Dataset

We used the **[Dangerous Insects Dataset](https://www.kaggle.com/datasets/tarundalal/dangerous-insects-dataset)** from Kaggle.

### Dataset Details:
- Contains multiple classes of **dangerous insect species** relevant for agricultural and ecological research.  
- Includes high-quality labeled images.  
- Suitable for **multi-class classification** tasks.  

### Preprocessing Steps:
- Resized all images to match model input dimensions (224×224).  
- Normalized pixel values to [0,1] or standardized using ImageNet statistics.  
- Applied data augmentation techniques (random flips, rotations, brightness/contrast adjustments) to improve generalization.  

---

## 🚀 How to Run the Notebook

### 1. Clone this repository
```bash
git clone https://github.com/your-username/Agricultural_Pest_Classification.git
cd Agricultural_Pest_Classification
