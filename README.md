# List of TB and Pneumonia Chest X-ray Datasets
A list of publicly available Tuberculosis (TB) and Pneumonia chest x-ray datasets.

Last Updated: 3 March 2023



<br>
<img src="https://github.com/vbookshelf/List-of-TB-and-Pneumonia-Datasets/blob/main/images/h0186.png" width="300"></img>
<i>An image from the TBX11K dataset</i><br>

<br>

TB and Pneumonia indicators look similar on chest x-rays. That's why I decided to include datasets for both diseases in this list.

In some cases the entire dataset is dedicated to one disease. In other cases the TB or Pneumonia images are located inside other much larger datasets. Some datasets include bounding boxes that can be used to train detection models. The image quantities are appoximate.

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
- Download from Kaggle: https://www.kaggle.com/datasets/vbookshelf/tbx11k-simplified<br>
- Paper: https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Rethinking_Computer-Aided_Tuberculosis_Diagnosis_CVPR_2020_paper.pdf


### Belarus dataset
- 305 TB images
- 305 total images
- Download: https://github.com/frapa/tbcnn<br>
- Paper: https://www.nature.com/articles/s41598-019-42557-4

### DA and DB datasets
- 125 TB images
- 278 total images
- Filenames starting with "n" are TB negative and filenames starting with "p" are TB positive
- Download from Kaggle: https://www.kaggle.com/datasets/vbookshelf/da-and-db-tb-chest-x-ray-datasets<br>
- Download: https://sourceforge.net/projects/tbxpredict/files/data/<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4229306/

### VinDr-PCXR dataset
- All x-ray images are of children (under 10 years old)
- 15 TB pediatric images
- 9,125 total images
- Includes bounding boxes
- Download: https://physionet.org/content/vindr-pcxr/1.0.0/<br>
- Paper: https://www.medrxiv.org/content/10.1101/2022.03.04.22271937v1.full-text

### VinDr-CXR dataset
- 479 TB images in the original dataset
- 18,000 total images
- Original dataset has TB global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/overview
- No TB labels are in the competition dataset: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/data
- Need to be a crentialed user and undergo training before accessing the original dataset
- Download: https://physionet.org/content/vindr-cxr/1.0.0/<br>
- Paper: https://www.nature.com/articles/s41597-022-01498-w

### Tuberculosis (TB) Chest X-ray Database
- The dataset on Kaggle contains 700 TB images. 
- 4,200 total images
- All images have been sourced from other public datasets.
- The experiments in the paper also used images sourced from the NIAID TB dataset
- Download from Kaggle: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset<br>
- Paper: https://ieeexplore.ieee.org/document/9224622

### NIAID TB dataset
- This dataset is mentioned under the "Contribution" section here: https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset
- There are reportedly 3500 TB images in this dataset. 
- A data request form needs to be submitted in order to access the data.
- Location: https://tbportals.niaid.nih.gov/download-data


### PadChest dataset
- 176 TB study counts
- 160,000 total images
- Contains radiographic reports in Spanish
- Download: https://bimcv.cipf.es/bimcv-projects/padchest/<br>
- Paper: https://arxiv.org/abs/1901.07441


<br>

# Pneumonia Datasets

### Child Chest X-Ray Images (Version 2)
- All x-ray images are of children (1-5 years old)
- 4,273 pneumonia images
- 5,856 total images
- Has labels for viral and bacterial pneumonia included in the file names
- paultimothymooney dataset version 2 on Kaggle: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia<br>
- andrewmvd dataset version 2 on Kaggle: https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray<br>
- Paper: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### Child Chest X-Ray Images (Version 3)
- All x-ray images are of children
- 4,273 total pneumonia images
- 5,856 total images
- Has labels for bacterial and viral pneumonia included in the file names
- Download: https://data.mendeley.com/datasets/rscbjbr9sj<br>
- Paper: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### RSNA Pneumonia Detection Challenge
- 6,012 pneumonia train images (labeled as opacity)
- 26,684 total train images
- Includes bounding boxes
- The raw images were sourced from the NIH ChestX-ray8 dataset.
- Download from Kaggle: https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data<br>
- Download from the RSNA website: https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/rsna-pneumonia-detection-challenge-2018<br>
- Paper: https://pubs.rsna.org/doi/10.1148/ryai.2019180041


<br>
The datasets that follow are multi label datasets that contain pneumonia images.<br>
I've listed the approx. number of pneumonia images in each.<br>

### VinDr-PCXR dataset
- All x-ray images are of children (under 10 years old)
- 481 pneumonia pediatric images
- 6 pleuro-pneumonia pediatric images
- 9,125 total images
- Includes bounding boxes
- Download: https://physionet.org/content/vindr-pcxr/1.0.0/<br>
- Paper: https://www.medrxiv.org/content/10.1101/2022.03.04.22271937v1.full-text

### VinDr-CXR dataset
- 469 Pneumonia images in the original dataset
- 18,000 total images
- Original dataset has Pneumonia global labels as explained here: https://vindr.ai/datasets/cxr
- Includes bounding boxes
- A modified version of this dataset was used for a Kaggle competition: https://www.kaggle.com/competitions/vinbigdata-chest-xray-abnormalities-detection/overview
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

### NIH ChestX-ray14 dataset
- 1,062 pneumonia images (see Table 1 in the paper)
- 112,1208 total images
- This dataset expands on NIH ChestX-ray8 dataset by providing labels for six additional diseases.
- Download from homepage: https://nihcc.app.box.com/v/ChestXray-NIHCC<br>
- Download: https://www.kaggle.com/datasets/nih-chest-xrays/data<br>
- Paper: https://arxiv.org/abs/1705.02315

### Open-i Chest X-ray images
- 40 pneumonia images (see Table 1 in this paper: https://arxiv.org/abs/1705.02315)
- 2,435 total images
- Download: https://openi.nlm.nih.gov/faq#collection<br>
- Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5009925/

### PadChest dataset
- 5,778 pneumonia study counts
- 160,000 total images
- Contains radiographic reports in Spanish
- Download: https://bimcv.cipf.es/bimcv-projects/padchest/<br>
- Paper: https://arxiv.org/abs/1901.07441

### Large Dataset of OCT and Chest X-Ray Images (Version 3)
- All x-ray images are of children
- 4,273 total pneumonia images (bacterial pneumonia and viral pneumonia)
- 1,583 normal images
- paultimothymooney dataset version 2 on Kaggle: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia<br>
- andrewmvd dataset version 2 on Kaggle: https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray<br>
- Download version 3: https://data.mendeley.com/datasets/rscbjbr9sj<br>
- Paper: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

<br>

# Helpful Resources

### Kaggle COVID-19 Comp solutions
This is a link to short video summaries of the top 10 solutions of the Kaggle COVID-19 AI Detection Challenge (2021).<br>
Includes links to the solution writeups and code.<br>
Many of the winning models were pre-trained on the datasets listed above.<br>
https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/covid-19-al-detection-challenge-2021

<br>

### ChatGPT - A virtual domain specialist
https://openai.com/blog/chatgpt/<br>
Do you sometimes wish that you could consult with a radiologist when training your models? I'm finding that ChatGPT is the next best thing. In fact ChatGPT has passed the three-part medical exam that doctors take in order to practice medicine in the US.<br>

This is the answer I got when I asked, "How do radiologists differentiate between TB and Pneumonia?"


"""

Radiologists can differentiate pneumonia from tuberculosis (TB) on chest x-rays by looking for specific characteristics in the images. Here are some of the ways they might differentiate between the two conditions:

1. Location: Pneumonia typically affects one lobe of the lung, while TB can involve multiple lobes.<br>
2. Shape: The opacities caused by pneumonia are often round or lobular, while the opacities caused by TB are often more irregular in shape.<br>
3. Size: The opacities caused by pneumonia are typically smaller than those caused by TB.<br>
4. Distribution: Pneumonia is more likely to affect the peripheral parts of the lung, while TB is more likely to affect the central portions of the lung.<br>
5. Associated findings: Pneumonia can cause pleural effusion (fluid in the pleural cavity), while TB often causes small nodules or cavities.<br>

Radiologists will also consider the patient's medical history, such as recent exposure to infectious agents, symptoms, and other test results, in making their diagnosis. In some cases, additional tests, such as sputum analysis or blood tests, may be needed to confirm the diagnosis and differentiate between pneumonia and TB.

"""

Please keep in mind that ChatGPT makes mistakes - the facts are not always correct.<br>
It's free to use.<br>

<br>
