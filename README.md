# DisasterVLP: Perceiving Multidimensional Disaster Damages from Street-View Images Using Visual–Language Models

## 🗂 Overview
DisasterVLP is a vision-language framework designed to perceive disaster damages from bi-temporal street-view images. It leverages large language models and contrastive learning to assess disaster severity and generate descriptive captions.

## 📊 Dataset
**Citation**:  
Yang, Yifan (2025). *Perceiving Multidimensional Disaster Damages from Street–View Images Using Visual–Language Models*. figshare. Dataset.  
https://doi.org/10.6084/m9.figshare.28801208.v2

---

## 📄 Paper Citation
If you use this code or dataset in your research, please cite:

Yang, Y., and Zou, L. (2025).  
*Perceiving Multidimensional Disaster Damages from Street-View Images Using Visual-Language Models*.  
**Abstracts of the International Cartographic Association**, 10, 310.  
https://doi.org/10.5194/ica-abs-10-310-2025

---

## 🧠 Overview (Detailed)
**DisasterVLP** is a vision-language framework that leverages pre- and post-disaster street-view images to perceive and classify disaster damage severity. The model integrates large vision-language models like CLIP, BLIP, and GPT to perform visual-language grounding and disaster impact estimation.

---

## 📊 Dataset (Detailed)
Yang, Yifan (2025). *Perceiving Multidimensional Disaster Damages from Street–View Images Using Visual–Language Models*. figshare.  
**DOI**: https://doi.org/10.6084/m9.figshare.28801208.v2

---

## 🧱 Framework Overview

### 🔍 Overall Structure
![Overall Framework](figure/overall%20framework.drawio.png)

### 🔬 Phase 2: Pseudo Post-Disaster Generation
![Phase 2](figure/phase2.drawio.png)

### 📊 Phase 3: Multi-modal Disaster Perception
![Phase 3](figure/phase3.drawio.png)

---

## 🌍 Study Area
![Study Area](figure/llm_studyarea.drawio%20(1).png)

---

## 🧪 Label Results Example
![Label Result](figure/label%20result.drawio.png)

---

## 🚀 Getting Started

### 🔧 Installation
```bash
git clone https://github.com/rayford295/DisasterVLP.git
cd DisasterVLP
pip install -r requirements.txt

