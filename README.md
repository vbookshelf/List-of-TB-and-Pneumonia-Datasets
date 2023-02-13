# List of TB and Pneumonia Chest X-ray Datasets
A list of publicly available Tuberculosis (TB) and Pneumonia chest x-ray datasets.

Last Updated: 13 Feb 2023

[ Repo Under Construction ]

<br>
<img src="https://github.com/vbookshelf/List-of-TB-and-Pneumonia-Datasets/blob/main/images/h0186.png" width="300"></img>
<i>An image from the TBX11K dataset</i><br>

<br>

A few years ago there were only 394 publicly available TB chest x-ray images. These are part of the well know Montgomery and Shenzhen datasets. Since then the number of available TB images has grown. But these images are not easy to find. Therefore, here I've listed the data sources that I've come across. I've included Pneumonia datasets because TB and Pneumonia indicators look similar on chest x-rays i.e. they appear as opacity. 

The datassets are listed below. In some cases the entire dataset is dedicated to one disease. In other cases the TB or Pneumonia images are located inside other much larger datasets. Some datasets include bounding boxes that can be used to train detection models. The image quantities are appoximate.

<br>

# Tuberculosis (TB) Datasets

### Shenzhen and Montgomery datasets
- 394 TB images
- 800 total images
- Download: https://www.kaggle.com/datasets/kmader/pulmonary-chest-xray-abnormalities<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4256233/


### TBX11K Simplified
- 799 labeled TB images
- 8,399 total labeled images
- 400 unlabeled TB test set images
- 3300 total unlabeled test images
- Includes bounding boxes
- Download: https://www.kaggle.com/datasets/vbookshelf/tbx11k-simplified<br>
- Paper: https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Rethinking_Computer-Aided_Tuberculosis_Diagnosis_CVPR_2020_paper.pdf


### Belarus dataset
- 305 TB images
- 305 total images
- Download: https://github.com/frapa/tbcnn<br>
- Paper: https://www.nature.com/articles/s41598-019-42557-4

### DA and DB datasets
- 102 TB images
- 303 total images
- DA and DB images are located in the folder named "extra" inside the original TBX11K dataset
- Download: https://www.kaggle.com/datasets/usmanshams/tbx-11<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4229306/

### VinDr-PCXR dataset
- 15 TB pediatric images (children under 10 years old)
- 7,728 total images
- Includes bounding boxes
- Download: https://physionet.org/content/vindr-pcxr/1.0.0/<br>
- Paper: https://www.medrxiv.org/content/10.1101/2022.03.04.22271937v1.full-text

### VinDr-CXR dataset
- 479 TB images in the original dataset
- 18,000 total images
- Original dataset has TB global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition. 
- No TB labels are in the competition dataset: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/data
- Need to be a crentialed user and undergo training before accessing the original dataset
- Download: https://physionet.org/content/vindr-cxr/1.0.0/<br>
- Paper: https://www.nature.com/articles/s41597-022-01498-w

### Tuberculosis (TB) Chest X-ray Database
- The dataset on Kaggle contains 700 TB images. 
- 4,200 total images
- All images have been sourced from other public datasets.
- The experiments in the paper also used images sourced from the NIAID TB dataset
- Download: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset<br>
- Paper: https://ieeexplore.ieee.org/document/9224622

### NIAID TB dataset
- I did not access this data.
- This dataset is mentioned under the "Contribution" section here: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset
- There are reportedly 3500 TB images in this dataset. 
- A data request form needs to be submitted in order to access the data.
- Location: https://tbportals.niaid.nih.gov/download-data


<br>

# Pneumonia Datasets

### Chest X-Ray Images (Pneumonia)
- 4,273 pneumonia images
- 5,856 total images
- All x-rays are of children (1-5 years old)
- Has labels for viral and bacterial pneumonia
- Download: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia<br>
- Paper: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### RSNA Pneumonia Detection Challenge
- Includes bounding boxes
- The raw images were sourced from the NIH ChestX-ray8 dataset.
- Download from Kaggle: https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data<br>
- Download from the RSNA website: https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/rsna-pneumonia-detection-challenge-2018<br>
- Paper: https://pubs.rsna.org/doi/10.1148/ryai.2019180041


<br>
The datasets that follow are multi label datasets that contain pneumonia images.<br>
I've listed the approx. number of pneumonia images in each.<br>

### VinDr-PCXR dataset
- 392 pneumonia pediatric images (children under 10 years old)
- 7,728 total images
- Includes bounding boxes
- Download: https://physionet.org/content/vindr-pcxr/1.0.0/<br>
- Paper: https://www.medrxiv.org/content/10.1101/2022.03.04.22271937v1.full-text

### VinDr-CXR dataset
- 469 Pneumonia images in the original dataset
- 18,000 total images
- Original dataset has Pneumonia global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition. 
- No Pneumonia labels are in the competition dataset: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/data
- Need to be a crentialed user and undergo training in order to access the original dataset
- Download: https://physionet.org/content/vindr-cxr/1.0.0/<br>
- Paper: https://www.nature.com/articles/s41597-022-01498-w

### CheXpert Dataset
- 4,576 pneumonia images (see Table 1 in the paper)
- 224,316 total images
- Website with dataset info: https://stanfordmlgroup.github.io/competitions/chexpert/<br>
- Download: https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2<br>
- Test set labels: https://github.com/rajpurkarlab/cheXpert-test-set-labels
- Paper: https://arxiv.org/abs/1901.07031


### MIMIC-CXR Database
- 15,769 pneumonia images (see Table 2 in the paper)
- 377,110 total images
- Need to be a crentialed user and undergo training in order to access dataset
- Download: https://physionet.org/content/mimic-cxr/2.0.0/<br>
- Paper: https://arxiv.org/pdf/1901.07042.pdf

### NIH ChestX-ray8 dataset
- 1,062 pneumonia images (see Table 1 in the paper)
- 112,1208 total images
- Download: https://www.kaggle.com/datasets/nih-chest-xrays/data<br>
- Paper: https://arxiv.org/abs/1705.02315

### Open-i Chest X-ray images
- 40 pneumonia images (see Table 1 in this paper: https://arxiv.org/abs/1705.02315)
- 2,435 total images
- Download: https://openi.nlm.nih.gov/faq#collection<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5009925/

