# CTReport-Inf Dataset

## 1. Dataset Overview

This repository provides a curated chest CT image–report paired dataset designed for medical image report generation and multimodal learning tasks. The dataset contains **2,161 CT images**, each paired with corresponding **Chinese and English radiology reports**.

All reports are derived from real clinical radiological findings and have undergone standardized preprocessing procedures, including de-identification, content filtering, and normalization. These processes ensure compliance with medical data usage regulations and enhance the dataset’s suitability for research applications.

---

## 2. Directory Structure

The dataset is organized under the root directory `CT/`, which contains three subdirectories and one Excel file:
```text
CTReport-Inf dataset/
├── images300_(300,300)/
├── report-CN/
├── report-EN/
└── CTReport-Inf.xlsx
```
### 2.1 images300_(300,300)

- Contains **2,161 CT images**
- All images are resized to a uniform resolution of **300 × 300 pixels**
- Each image is a representative slice extracted from the original CT examination, preserving diagnostically relevant features

### 2.2 report-CN

- Contains **2,161 Chinese radiology reports**
- One-to-one correspondence with CT images
- Reports describe imaging findings such as lesion location, morphology, and severity

### 2.3 report-EN

- Contains **2,161 English radiology reports**
- Professionally translated from the original Chinese reports
- Supports international research and cross-lingual tasks

### 2.4 CTReport-Inf.xlsx

- Provides structured data for the dataset
- Includes:
  - ID
  - Image
  - Report_CN
  - Report_EN

---

## 3. Data Alignment

CT Image ↔ Chinese Report ↔ English Report

---

## 4. Data Access

https://drive.google.com/file/d/12MKvcZ21tGAO3hM0AOf84Owv2wn9IZpL/view?usp=sharing

---

## 5. Notes

- All data have been **fully de-identified**
- Reports are **filtered to retain only imaging-relevant content**
- The dataset is intended **for research purposes only**
