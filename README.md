Skin Cancer (Melanoma) Classification Proposal
===================================

## Introduction

In this project, we are going to develop a custom application that identifies skin cancer (Melanoma) lesions from dermoscopic images. The application will utilize the state-of-art deep learning technologies and libraries to accomplish this task with high accuracy. To this end, we are going to use special kind of neural networks (NNs) which are highly effective in discovering and classifying patterns in images. this special kind of NNs is called Convoluted Neural Networks (CNNs).


## Research Questions

- Can we (in early stage of the disease) be able to classify and/or predict the existence of melanoma and distinguish it from the rest of other non-cancerous skin lesions from dermoscopic images of patients?



## Data Source

- We downloaded public data set of skin cancer dermoscopic images from Kaggle Website.
- The data set was contributed to kaggle by The international Skin Imaging Collaboration Consortium (ISIC). The ISIC is an international consortium which aims to improve melanoma diagnosis, sponsored by the international society of Digital Imaging of The Skin (ISDIS). The ISIC Archive contains the largest publicly available collection of quality controlled dermoscopic images of skin lesions.

## Data Description

- Mainly, The data contains approximately 10,000 dermoscopic images of melanoma that has a size of ~ 3GB on disk.
- The data has metadata file associated with it, below is just the top 10 records.

|lesion_id  |image_id    |dx |dx_type|age |sex   |localization|
|-----------|------------|---|-------|----|------|------------|
|HAM_0000118|ISIC_0027419|bkl|histo  |80.0|male  |scalp       |
|HAM_0000118|ISIC_0025030|bkl|histo  |80.0|male  |scalp       |
|HAM_0002730|ISIC_0026769|bkl|histo  |80.0|male  |scalp       |
|HAM_0002730|ISIC_0025661|bkl|histo  |80.0|male  |scalp       |
|HAM_0001466|ISIC_0031633|bkl|histo  |75.0|male  |ear         |
|HAM_0001466|ISIC_0027850|bkl|histo  |75.0|male  |ear         |
|HAM_0002761|ISIC_0029176|bkl|histo  |60.0|male  |face        |
|HAM_0002761|ISIC_0029068|bkl|histo  |60.0|male  |face        |
|HAM_0005132|ISIC_0025837|bkl|histo  |70.0|female|back        |
|HAM_0005132|ISIC_0025209|bkl|histo  |70.0|female|back        |


image_id: is the name of the image file on disk

sex: the patient gender

localization: the location of the skin lesion in the patient's body





## Tools

- Software Platform: Jupyter Notebook
- Programming Language: Python
- Libraries:
	- Sci-Kit Learn
	- TensorFlow
	- Keras
	- Numpy
	- Seaborn
	- Matplotlib
