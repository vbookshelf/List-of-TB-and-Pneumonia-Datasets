# List of TB and Pneumonia X-ray Datasets
A list of publicly available Tuberculosis (TB) and Pneumonia chest x-ray image sources.

Last Updated: 13 Feb 2023

[ Repo Under Construction ]

<br>
<img src="https://github.com/vbookshelf/List-of-TB-and-Pneumonia-Datasets/blob/main/images/h0186.png" width="300"></img>
<i>An image from the TBX11K dataset</i><br>

<br>

A few years ago when I first worked on a TB project there were only 394 publicly available TB chest x-ray images. These were part of the well know Montgomery and Shenzhen datasets. Since then the number of available images has grown, but they are not easy to find. Therefore, I've tried to list all the data sources here to make things easier for those working on ML projects. I've also included Pneumonia because my rough research has shown that TB and Pneumonia look similar on chest x-rays i.e. they appear as opacity. 

The datassets are listed below. In some cases the entire dataset is dedicated to one disease. In other cases the TB or Pneumonia images are located inside other much larger datasets. Some datasets include bounding boxes that can be used to train detection models. The image quantities are appoximate.

<br>

# Tuberculosis (TB) Datasets

### Shenzhen and Montgomery datasets
- 394 TB images
- Download: https://www.kaggle.com/datasets/kmader/pulmonary-chest-xray-abnormalities<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4256233/


### TBX11K Simplified
- 799 TB images
- Includes bounding boxes
- Download: https://www.kaggle.com/datasets/vbookshelf/tbx11k-simplified<br>
- Paper: https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Rethinking_Computer-Aided_Tuberculosis_Diagnosis_CVPR_2020_paper.pdf


### Belarus dataset
- 305 TB images
- Download: https://github.com/frapa/tbcnn<br>
- Paper: https://www.nature.com/articles/s41598-019-42557-4

### DA and DB datasets
- 102 TB images
- DA and DB images are located in the folder named "extra" inside the original TBX11K dataset
- Download: https://www.kaggle.com/datasets/usmanshams/tbx-11<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4229306/

### VinDr-PCXR dataset
- 15 TB images
- Includes bounding boxes
- All images are pediatric images (children under 10 years old)
- Download: https://physionet.org/content/vindr-pcxr/1.0.0/<br>
- Paper: https://www.medrxiv.org/content/10.1101/2022.03.04.22271937v1.full-text

### VinDr-CXR dataset
- 479 TB images in the original dataset
- Original dataset has TB global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition. 
- No TB labels are in the competition dataset: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/data
- Need to be a crentialed user and undergo training before accessing the original dataset
- Download: https://physionet.org/content/vindr-cxr/1.0.0/<br>
- Paper: https://www.nature.com/articles/s41597-022-01498-w

### Tuberculosis (TB) Chest X-ray Database
- The dataset on Kaggle contains 700 TB images. These images have been sourced from other public datasets.
- The experiments in the paper also used images sourced from the NIAID TB dataset
- Download: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset<br>
- Paper: https://ieeexplore.ieee.org/document/9224622

### NIAID TB dataset
- I did not access this data.
- There are reportedly 3500 TB images in this dataset. 
- This dataset is mentioned under the "Contribution" section here: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset
- A data request form needs to be submitted in order to access the data.
- Location: https://tbportals.niaid.nih.gov/download-data


<br>

# Pneumonia Datasets

### Chest X-Ray Images (Pneumonia)
- Includes x-rays of children
- Has labels for viral and bacterial pneumonia
- Download: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia<br>
- Paper: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### RSNA Pneumonia Detection Challenge
- Includes bounding boxes
- Download from Kaggle: https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data<br>
- Download from the RSNA website: https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/rsna-pneumonia-detection-challenge-2018<br>
- Paper: https://pubs.rsna.org/doi/10.1148/ryai.2019180041

### Pediatric Pneumonia Chest X-ray
- X-rays of children
- Download: https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray<br>
- Paper: https://pubmed.ncbi.nlm.nih.gov/29474911/

### VinDr-CXR dataset
- 469 Pneumonia images in the original dataset
- Original dataset has Pneumonia global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition. 
- No Pneumonia labels are in the competition dataset: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/data
- Need to be a crentialed user and undergo training in order to access the original dataset
- Download: https://physionet.org/content/vindr-cxr/1.0.0/<br>
- Paper: https://www.nature.com/articles/s41597-022-01498-w

### CheXpert Dataset
- 4,576 pneumonia images (see Table 1 in the paper)
- Website with dataset info: https://stanfordmlgroup.github.io/competitions/chexpert/<br>
- Download: https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2<br>
- Test set labels: https://github.com/rajpurkarlab/cheXpert-test-set-labels
- Paper: https://arxiv.org/abs/1901.07031

### MIMIC-CXR Database
- 15,769 pneumonia images (see Table 2 in the paper)
- Need to be a crentialed user and undergo training in order to access dataset
- Download: https://physionet.org/content/mimic-cxr/2.0.0/<br>
- Paper: https://arxiv.org/pdf/1901.07042.pdf

### NIH Chest X-rays
- 1,062 pneumonia images (see Table 1 in the paper)
- Download: https://www.kaggle.com/datasets/nih-chest-xrays/data<br>
- Paper: https://arxiv.org/abs/1705.02315

### Open-i Chest X-ray images
- 40 pneumonia images (see Table 1 in this paper: https://arxiv.org/abs/1705.02315)
- Download: https://openi.nlm.nih.gov/faq#collection<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5009925/

