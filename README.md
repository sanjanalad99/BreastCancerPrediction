BREAST
CANCER
CLASSIFICATION

Table of Contents
1.	About The Project
-	Built With
2.	Getting Started
-	Installation
3.	Usage
4.	Roadmap
5.	Contact
6.	Acknowledgments


















1.About this project:


Neural networks, specifically deep learning models such as convolutional neural networks (CNNs), can play a vital role in the early detection of breast cancer. Breast cancer is the leading cause of cancer-related death in women. Early detection and accurate diagnosis are critical to improving patient outcomes. Convolutional neural networks (CNNs) have emerged as powerful tools for early detection of cancer due to their ability to learn and extract important features from clinical images. Using its algorithm and convolutional filters, CNNs can detect complex patterns and subtle abnormalities in mammograms, histopathology images, and other medical imaging modalities. CNNs, through extensive training on big data, can distinguish between soft tissue and soft tissue of the breast, enabling accurate classification and detection of tumors in the early days. CNN's layers enable the model to learn complex representations, helping to identify subtle features that are not easily visible to a human observer. By providing accurate and reliable analysis of cancer diagnosis, CNNs have the potential to support radiologists and physicians in diagnostic decisions, enable early detection, improved treatment planning and ultimately patient outcomes. In this project, we investigate the use of convolutional neural networks (CNNs) to classify breast cancer using histopathology images from the Kaggle dataset. We implemented a CNN model using Python and trained it on Google Colab using CUDA.


-Built with:

Python
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/d127997a-1b8a-482e-8f03-b174e48945be)

Google Colab
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/f2147e96-d334-4f13-bd56-9724d6bcb8b8)

Google Drive
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/95ce874a-ab57-4784-aeb7-c59196b08428)

Pytorch
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/bacc6c35-146b-4b22-ae94-c8fe7fcbb435)

Cuda
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/e590de39-bb69-4183-b4ea-1bdd79f6e5bc)


GPU


Kaggle dataset







2.Getting Started :
1. Open the NEWBCP.ipynb file from the repository 
2. Run each and every code module one by one from step 1 to step 5
3. Wait until step 5 completely executes, we’ll get the output image 10 times. Will take up to 2-3 minutes to run the step 5 (Training the model).
4. After the training is finished –




5. Setting up Kaggle API access: Collect Kaggle API access token. Navigate to Kaggle profile “Account” page. Find “create your API token”. Download token as a JSON file containing username and key.
6. Save API token in Drive: Create a folder for Kaggle in Google Drive. Save a copy of the API token as a private file in this folder to access it easily
7. Mount Google Drive to Colab: This will make sure we don’t have to download the data every time we restart runtime. 
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/ab4d900a-7f1e-47b3-b66c-818880a7b546)
















3. Usage:
1. Download the dataset in our local system and uploading few folders from the downloaded dataset to the google drive.
Note that in this step, we are just using few folders (images) from the entire dataset as it takes a very long time to process such a huge dataset. Here’s a screenshot of the folders we used –

![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/eef6bc18-bed1-4a90-a178-130fceee8461)

2. Once the dataset is downloaded and connected, we start building the network and converting images to tensor 
3. We then find the number of samples in each class

 ![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/74423825-c8f0-489c-a844-1b368630e466)


4. Roadmap:
1. Splitting the dataset

![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/e5c01316-85f7-4161-8adc-3227105fd7b5)


2. Output after splitting
![image](https://github.com/sanjanalad99/FinalBCC/assets/133920285/6c6597ea-d50e-4039-8f1f-fa0e4270ebab)


3. Getting 84% accuracy for 20 epochs 

 


5.Contact:

Sanjana Lad (sanjana.lad@csu.fullerton.edu)

Pavan Kumar Kandregula (kandregula123@csu.fullerton.edu)

6.Acknowledgement:



Guidance under Professor Lan Nygyen for the course Principles of Neural Systems

Master of Science in Computer Engineering 

California State University, Fullerton 
