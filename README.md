# Multi-hazard-mapping-using-ML
A Machine Learning module designed to automatically identify and map disaster-affected areas by analyzing satellite imagery
# 🌍 Multi-Hazard Mapping using Machine Learning

### 🏛️ Project Context
[cite_start]This academic project was submitted as part of the requirements for the Artificial Intelligence course at **Umm Al-Qura University**[cite: 1, 2]. The research was conducted under the supervision of **Dr. [cite_start]Afaf Almehmadi**[cite: 6].

[cite_start]**Project Team[cite: 4]:**
* [cite_start]Remas Saleh Ghandorah [cite: 4]
* Shatha Ali Alhumaidi [cite: 4]
* [cite_start]Haden Hassan Alshaar [cite: 4]
* [cite_start]Hadeel Mohammad Turki [cite: 4]
* Linah Ebrahim ALsayed [cite: 4]

---

### 🎯 Primary Goal
* [cite_start]The objective of this research is to design a Machine Learning (ML) module capable of automatically identifying and mapping disaster-affected areas[cite: 29].
* [cite_start]The system analyzes geo-spatial data to generate initial maps of critical affected sites requiring urgent relief[cite: 30].
* The module functions by comparing pre-disaster and post-disaster satellite imagery to produce an accurate, automated damage map[cite: 419, 420].
* [cite_start]This approach improves the speed, precision, and scalability of disaster assessment for emergency response teams[cite: 421].

---

### 🛠️ Technical Approach
[cite_start]The **Random Forest Classifier** was selected as the supervised machine learning technique for this project[cite: 11, 423]. This algorithm was chosen for the following reasons:
* It can handle a large number of features extracted from satellite imagery[cite: 425].
* [cite_start]It effectively captures complex changes between pre- and post-disaster imagery[cite: 425].
* [cite_start]It provides stable and interpretable results [cite: 425][cite_start], which improves transparency and trust through feature importance analysis[cite: 398].
* [cite_start]It maintains high accuracy even when data is noisy or partially incomplete[cite: 426].

---

### ⚙️ Workflow
The data processing follows a structured sequence:
1. [cite_start]**Input Data:** Acquisition of pre-disaster and post-disaster satellite imagery[cite: 431, 434].
2. [cite_start]**Preprocessing:** Resizing the images to a uniform dimension of $256 \times 256$ pixels[cite: 435].
3. [cite_start]**Feature Stacking:** Concatenating image channels channel-wise to create a feature matrix (X)[cite: 436, 438].
4. [cite_start]**Training:** Partitioning the dataset into 70% for training and 30% for testing[cite: 115, 440, 442].
5. [cite_start]**Prediction:** The model performs pixel-level classification to determine if individual pixels represent damaged areas[cite: 447].

---

### 📊 Results
[cite_start]The system produces a predicted damage map to assist emergency planners[cite: 445, 484]:
* **White Color:** Indicates a "Damage Zone"[cite: 448, 484].
* [cite_start]**Black Color:** Indicates "No Damage"[cite: 448, 484].

---

### 💡 Significance (Gap Analysis)
* [cite_start]Our module is designed to be trained on publicly available satellite imagery, ensuring the method can be generalized and applied in low-resource contexts[cite: 400].
* The system is designed as a dynamic mapping module to support real-time decision-making, moving away from static historical maps[cite: 51, 405].
* [cite_start]By utilizing radar satellite imagery (Sentinel-1), the approach is robust against environmental obstructions such as cloud cover[cite: 408].
