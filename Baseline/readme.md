# Baseline Methods

This directory contains baseline models and reference implementations used for comparison in the **DisasterVLP** project.

The baselines are designed to evaluate how existing **vision or vision–language pipelines** perform on disaster-related perception and grounding tasks, in contrast to the proposed DisasterVLP framework.

## 📁 Contents

This folder currently includes the following baseline implementations:

- `InstructPix2Pix.ipynb`  
  A prompt-guided image editing baseline used to explore instruction-following behavior in disaster-related visual transformations.

- `ControlNet_&_Owlvit.ipynb`  
  A combined baseline using **ControlNet** for conditional image generation and **OWL-ViT** for open-vocabulary object detection, serving as a reference for structure-aware and detection-based pipelines.

- `GroundingDINO_with_Segment_Anything.ipynb`  
  A grounding-based baseline that integrates **GroundingDINO** with **Segment Anything (SAM)** for text-guided object localization and segmentation in disaster scenes.

These baselines represent commonly used or representative approaches in:
- Vision-language grounding,
- Conditional image generation,
- Open-vocabulary detection and segmentation.

## 🎯 Purpose of Baselines

The baseline methods are used to:
- Provide fair and transparent performance references,
- Analyze limitations of existing models in complex disaster scenarios,
- Highlight the advantages of large vision–language model–based reasoning in DisasterVLP.

They are **not** intended to be optimized or tuned beyond standard configurations.

## ⚠️ Notes

- All notebooks are provided for **research and comparison purposes only**.
- Results obtained from these baselines may vary depending on prompts, random seeds, and model versions.
- Some notebooks may require external checkpoints or API access; please refer to comments within each notebook.

## 📌 Reproducibility

Where applicable, baseline outputs are reported in tables or figures in the accompanying paper and documentation.  
Users are encouraged to run the notebooks in a controlled environment to reproduce results.

## 📬 Contact

For questions regarding baseline implementation details or experimental setup, please contact:

**Yifan Yang**  
Email: yyf990925@gmail.com
