# List of TB and Pneumonia X-ray Datasets
A list of publicly available Tuberculosis (TB) and Pneumonia chest x-ray image sources.

Last Updated: 13 Feb 2023

[ Repo Under Construction ]

When I first worked on a TB project a few years ago there were only 394 publicly available TB chest x-ray images. These were part of the well know Montgomery and Shenzhen datasets. Since then the number of available images has grown, but they are not easy to find. Therefore, I've tried to list all the data sources here to make things easier for those working on ML projects. I've also included Pneumonia because my rough research has shown that these two conditions look similar on chest x-rays e.g. they appear as opacity. 

In some cases the entire dataset is dedicated to one disease, in other cases the TB or Pneumonia images are located inside other much larger datasets. The image quantities below are appoximate.

<br>

# Tuberculosis (TB)

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

# Pneumonia

