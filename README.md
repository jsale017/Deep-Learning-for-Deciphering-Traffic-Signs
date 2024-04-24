# Deep-Learning-for-Deciphering-Traffic-Signs

[Google Drive](https://drive.google.com/drive/folders/1647YjbJVfwIwr9o_zYZ6Wv4q16mLxi_9?usp=drive_link)

 ## Problem Statement & Motivation
   As the world advances towards autonomous vehicles, our team has observed the remarkable efforts of large car manufacturers, who are working with data scientists to develop fully autonomous cars. Our team is excited to contribute to the development of this technology by creating a neural network model that will be able to classify different traffic signs. Our ultimate goal is to assist car makers in overcoming the challenges they may face in implementing neural network models that effectively read traffic signs and further their efforts toward a fully autonomous car or assisted driving. We believe autonomous driving to be an important problem to solve due to the great economic benefits it can generate for car manufacturers and the improvement of general driving safety
   
 ## Data Preparation
  We've selected the German Traffic Sign Recognition Benchmark (GTSRB) as our primary dataset. It's renowned for its complexity, featuring over 50,000 images across more than 40 classes of traffic signs. The GTSRB is publicly accessible through two resources. To efficiently manage the extensive and complex GTSRB dataset, our strategy integrates preprocessing for uniformity, data augmentation for robustness, and batch processing for computational efficiency. We'll employ distributed computing to parallelize operations, enhancing processing speed, and use stratified sampling for quick experimentation without compromising representativeness

## Breakdown of Notebooks:
 We have organized our analysis into separate notebooks for clarity and structure. Here is a brief overview of what each notebook (.ipynb file) contains:
 - EDA Notebook: EDA.ipynb
	- Fixing Test Dataset Notebook: Fix_Test_Data.ipynb 
	- Draft Models Notebook: Draf_Models.ipynb 
	- SVM Notebook: SVM_Baseline_Model.ipynb
	- MLP Notebook: MLP_Models.ipynb
	- CNN Notebook: CNN_Models.ipynb
	- Resnet-18 Notebook: pre-trained_Resnet18_Model.ipynb
