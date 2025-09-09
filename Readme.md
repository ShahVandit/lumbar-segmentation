# Lumbar Vertebrae Segmentation

This repository contains implementations of various deep learning models for lumbar vertebrae segmentation using medical imaging data. The focus is on segmenting lumbar vertebrae from different image formats and modalities with models such as U-Net, UNETR, and Pix2Pix.

## Files Overview

- **lumbar-segmentation.ipynb**  
  Implements a U-Net model for segmentation using PNG image data.

- **unetr.ipynb**  
  Implements the UNETR model using MONAI, trained on .mha files.

- **pix2pix.ipynb**  
  Implements the Pix2Pix model for image-to-image translation tasks in segmentation.

- **pix2pix_mri.ipynb**  
  Provides a complete training pipeline for the Pix2Pix model, trained on PNG MRI data.