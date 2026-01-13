# Gemini-Based Vision–Language Experiments

This directory contains experiments leveraging **Google Gemini** for zero-shot vision–language understanding tasks in disaster scenarios.

The goal of this module is to explore the capabilities and limitations of **large multimodal models (LMMs)** when applied to disaster-related perception tasks without task-specific fine-tuning.

## 📁 Contents

This folder currently includes the following notebooks:

- `zero_shot_object_detection.ipynb`  
  Zero-shot object detection using Gemini, guided by natural language prompts to identify disaster-relevant objects and scene elements.

- `zero_shot_image_segmentation.ipynb`  
  Zero-shot image segmentation experiments using Gemini for text-guided region identification and semantic interpretation in disaster scenes.

These notebooks focus on **prompt-based reasoning**, rather than traditional supervised learning or model fine-tuning.

## 🎯 Experimental Purpose

The Gemini-based experiments are designed to:

- Evaluate the feasibility of zero-shot disaster perception using large vision–language models,
- Compare prompt-driven reasoning with traditional vision-based baselines,
- Analyze the strengths and failure modes of LMMs in complex, real-world disaster imagery.

These experiments serve as an **exploratory and analytical component** of the DisasterVLP framework.

## 🧠 Methodological Notes

- All experiments rely on **natural language prompts** to guide visual understanding.
- No additional training or fine-tuning is performed.
- Model outputs may vary depending on prompt design, image content, and API version.

## ⚠️ Usage Notes

- The notebooks may require valid API access to Gemini.
- Results are intended for **research and comparative analysis only**.
- Outputs should not be interpreted as operational disaster assessments.

## 📌 Relevance to DisasterVLP

Insights from this module inform:
- Prompt design strategies,
- Failure analysis of vision–language reasoning,
- The overall design of the DisasterVLP framework.

## 📬 Contact

For questions regarding Gemini-based experiments or prompt design, please contact:

**Yifan Yang**  
Email: yyf990925@gmail.com

