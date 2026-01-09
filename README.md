
# Semantic Correspondence Project

This project implements Semantic Correspondence using foundation models (DINOv2, DINOv3, and SAM) on Google Colab. 

You could check our report in the folder.

## Project Overview

- **Main Notebook**: `Semantic_Projrct5NoToken.ipynb`
- **Platform**: Google Colab (Requires GPU), Google drive
- **Datasets**: SPair-71k, PF-Pascal, PF-Willow

## Setup Instructions 

Since this project relies on large datasets and pre-trained model weights, please set up your Google Drive before running the notebook.

### 1. Download Required Files
Please download the datasets and pre-trained models from the following Google Drive link:
[Download Datasets and Models Here](https://drive.google.com/drive/folders/18kP7eIIUHrXAgtU4BBXwxwx5d8fSIM5y?usp=drive_link)

Only the datasets and training models are needed, the results folder isn't used in our project.
### 2. Configure Google Drive
1.  Go to your Google Drive root directory (`My Drive`).
2.  Create a new folder named `Project_Semantic`.
3.  Upload the downloaded files into this folder.
4.  Ensure your directory structure matches the tree below exactly, otherwise the code will fail to load the data.
```text
/content/drive/MyDrive/
└── Project_Semantic/
    ├── SPair-71k.tar.gz
    ├── pf-pascal.zip
    ├── pf-willow.zip
    └── Training models/
        ├── dinov2_base_1L.pth
        ├── dinov2_base_2L.pth
        ├── dinov2_base_3L.pth
        └── dinov3_large_1L.pth
```
5.  Everything is done, just do it ! 


### 3. Hugging face token
Pleas repalce all the [HF_TOKEN = "Your hugging face token here"] with your DINOv3 token to use this model, because I'm not suer whether is safe or not to put my token in Github with public :D

(It's not safe, I update my coding with token and my token was expired by hugging face :( 
