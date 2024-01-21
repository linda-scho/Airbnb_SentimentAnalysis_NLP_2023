# Airbnb_SentimentAnalysis_NLP_2024
This repository contains the code files and report for the project " Enhancing Malaria Diagnosis: Comparative Analysis of CNN and SVM Models for P. vivax Cell Detection" developed as a final project in the course Data Mining, Machine Learning, and Deep Learning at the Copenhagen Business School.

## Description
* **Project**: The project focuses on the detection of P. vivax malaria-infected cells. Using the Broad Bioimage Benchmark Collection (BBBC) dataset of over 85.000 blood smear images, different classification models were developed and compared. As hypothesized, the Support Vector Machines (SVM) model was outperformed by the two Convolutional Neural Networks (CNN) models. The highest accuracy was demonstrated by CNN1 with 0.98.

* **Course**: The course aimed to teach students about the fundamental challenges of machine learning, such as model selection and model complexity, and the underlying mathematical relationships within and across machine learning algorithms. Students were also taught to characterize the strengths and weaknesses of various machine learning approaches and algorithms, design, implement, analyze, and apply different data mining, machine learning techniques, and deep learning techniques for big/business datasets in organizational contexts and for real-world applications. The course also covered the application areas, trends, and challenges in data mining and machine learning. The students were required to complete a project and report that reflected on their critical awareness of methodological choices and written skills to accepted academic standards.

## Authors
Konstantin Kleffke, Linda Schombach and Mira Metzger

## Folder Structure

The folders are structured as follows:

```bash
.
├── Code
│   ├── 1_Script_Cropping_images.ipynb
│   ├── 2_Script_Preprocessing.ipynb
│   ├── 3_Script_Preprocessing.ipynb
│   ├── 4_Script_ExploratoryAnalysis.ipynb
│   ├── 5_Script_CNN.ipynb
│   └── 6_Script_SVM.ipynb
├── README.md
└── Report.pdf
```

## Data

* The dataset [BBBC041](https://bbbc.broadinstitute.org/BBBC041) is obtained from the Broad Bioimage Benchmark Collection (BBBC) and holds 1.228 images that were manually created from P. vivax parasite infected humans in Manaus, Brazil, and Thailand with theire labels (infected or uninfected)
