# Brain-aligned visual encoding via feature pruning
This project investigates how visual representations are extracted from pretrained computer vision models aligning with human visual cortex responses measured with fMRI. Building on recent work such as VISGate and BOLDREAMS, we study whether compact and interpretable brain-aligned encoders can be obtained by selecting feature subsets that are specific to cortical regions of interest (ROIs) and to the semantic content of images. The project compares modern visual backbones such as DINOv2 and CLIP, predicts ROI-level fMRI responses on images, and evaluates whether ROI-aware and semantics-aware pruning improves the trade-off between compactness, interpretability and predictive accuracy. The core pipeline focuses on ROI-wise encoding and feature pruning.  
  
Executing the project is as simple as setting up the dataset below and running the notebook.  
  
## Dataset:
Downloadable at: https://drive.google.com/drive/folders/17_5bKFH7e_54q0Eu3x8mnSk8kumhGrs0?usp=sharing
You can also add a shortcut to your drive instead of downloading the dataset and reuploading it on drive.

### Dataset structure:
We used only a subset of the dataset for this project.  
Subj01 for train and test.  
Subj02-03-04-05 only for cross-subject testing.

## References:
• Mahdiani, Morteza, and Ian Charest. "VISGate: ROI-Conditioned Dual-Head Encoders that Align
Visual Features and Brain Responses." UniReps: 3rd Edition of the Workshop on Unifying
Representations in Neural Models.  
https://neurips.cc/virtual/2025/loc/san-diego/127148

• Uzair Hussain and Kamil Uludag. “Boldreams: Dreaming with pruned in-silico fmri encoding models
of the visual cortex.” arXiv preprint arXiv:2501.14854, 2025C  
https://arxiv.org/abs/2501.14854