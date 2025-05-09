# YZTA Datathon Submission

**Project:** Predicting Monthly Product Prices  
**Authors:** Osman Sener, [Co-Author 1], [Co-Author 2]  
**Repository:** https://github.com/osnn96/YZTA-Datathon

---

## 📋 Table of Contents
1. [Project Overview](#project-overview)  
2. [Data Description](#data-description)  
3. [Environment Setup](#environment-setup)  
4. [Usage](#usage)  
5. [Modeling Pipeline](#modeling-pipeline)  
6. [Results](#results)  
7. [Folder Structure](#folder-structure)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## 📝 Project Overview
We build time-series models (SARIMAX, Prophet, XGBoost, LightGBM, hybrid approaches) to forecast product prices (e.g., kıyma) from January 2019 through December 2023 and predict 2024 prices. Our goal is to deliver a robust pipeline for monthly price prediction that can scale to thousands of product–market combinations.

---

## 📊 Data Description
- **train.csv**: Contains historical monthly prices (2019–2023) with columns:  
  `tarih` (date), `ürün`, `ürün besin değeri`, `ürün kategorisi`, `ürün fiyatı`, `ürün üretim yeri`, `market`, `şehir`.  
- **testFeatures.csv**: Contains product–market–city combos for 2024 with the same feature columns (no price).

