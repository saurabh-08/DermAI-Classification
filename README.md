## DermoscopySimCLR

DermoscopySimCLR is a deep learning project focused on the classification of skin lesions using dermoscopy images. This repository utilizes the SimCLR (Simple Framework for Contrastive Learning of Visual Representations) model for feature extraction and classification of benign and malignant skin lesions. The project aims to leverage advanced techniques in data augmentation, contrastive learning, and transfer learning to improve the accuracy and robustness of skin lesion classification.

**Dataset**

This project uses the ISIC (International Skin Imaging Collaboration) dataset, which contains a diverse set of dermoscopy images for the classification of skin lesions. The dataset can be downloaded here: https://api.isic-archive.com/collections/70/

## Getting Started

### Prerequisites
- Python 3.10
- CUDA (Optional)

### Environment Setup
**Create the environment from the `env.yaml` file:**

   ```bash
   conda env create -f env.yaml
```

### Install Required Packages
```bash
pip install -r requirements.txt
```

### Prepare the dataset

Download the ISIC dataset and place the images in the ISIC-images directory.
Ensure the metadata CSV file is named metadata.csv and placed in the root directory.

### Run the model
   ```bash
DermoscopySimCLR_FullPipeline.ipynb
```

### Research Paper
For more details on the methodology and findings, please refer to our research paper: Self-Supervised Learning to Detect and Classify Skin Anomalies using Unlabelled Dermoscopy Images
