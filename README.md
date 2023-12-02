# brain-tumour-classification-algorithm
Brain tumour classification using modified DenseNet

# Abstract
In the area of image processing, the study of brain tumors involves intricate analysis and interpretation of 
medical images such as MRIs and CT scans. Leveraging advanced algorithms and techniques, image processing plays a 
pivotal role in detecting, classifying, and understanding the characteristics of brain tumors. Deep convolutional 
neural networks, well-known for their adeptness in feature extraction, have proven their efficacy in various detection 
and classification tasks. Nevertheless, they necessitate substantial training datasets and meticulous parameter tuning. 
The Modified Dense Convolutional Network (MDCN) proposed in this study presents a valuable classification framework for 
categorizing brain tumors. Leveraging the capabilities of pre-trained networks, the MDCN adapts them to the specific 
context of brain tumor classification through the incorporation of transfer learning techniques. The data loader 
constructs mini-batches for model training, significantly reducing the training time. Additionally, optimization 
approaches are employed to enhance the overall model efficiency and reduce computational costs. The MDCN is applied 
to the BrainTumorBD Dataset, comprising a total of 4,205 images. Experimental results demonstrate that the proposed 
system outperforms existing techniques, achieving superior performance and overall throughput.

# Prerequisites
Ensure that you have the following dependencies installed:
1.	Python V3.10
2.	MONAI library (pip install monai == 1.3.0)
3.	Matplotlib (pip install matplotlib == 3.8.2)
4.	Pillow (pip install Pillow == 10.1.0)
5.	Torch (pip install torch == 2.1.1)
6.	NumPy (pip install numpy == 1.26.2)
7.	Scikit-learn (pip install scikit-learn == 1.3.2)
8.	OpenCV (pip install opencv-python == 4.8.1.78)
9.	TensorFlow (pip install tensorflow == 2.15.0)
10.	Pandas (pip install pandas == 2.1.3)
11.	Seaborn (pip install seaborn == 0.13.0)

# Dataset
Image dataset containing samples of meningioma(1), glioma(2), pituitary tumor(3) brain tumor types. The link to the dataset is as follows
https://www.kaggle.com/datasets/denizkavi1/brain-tumor 
