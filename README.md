# use-of-Artificial-Intelligence-and-Machine-Learning-in-Structural-Health-Monitoring-System-overview
[1] proposed a novel and intelligent approach for reliably evaluating the system of cable-supported
bridges under stochastic traffic load by utilizing deep belief networks (DBNs). They introduced the
theoretical basis for utilizing DBNs to approximate the structural load, and presented a computational
framework to illustrate the procedures followed to evaluate the bridge system reliability via DBNs. Hou
et al. [2] proposed a novel method for identifying time-varying cable tension based on the variational
mode decomposition (VMD) method. This recent method decomposes signals and adaptively
estimates instantaneous frequencies combined with the Hilbert–Huang transform method, where the
time-varying modal frequencies were identified from stay cable acceleration data, and then the
time-varying cable tension was identified by the relationship between cable tension and identified
fundamental frequency.
The next two research articles [3,4] of the Special Issue proposed a non-probabilistic surrogate
model based on wavelet weighted least squares support vector machine (WWLS SVM) to address
the problem of uncertainty in vibration-based damage detection. The input data for WWLSSVM consist of
selected wavelet packet decomposition (WPD) features of the structural response signals, and the
output is the Young’s modulus of structural elements.
For damage segmentation purposes, Shi et al. [5] proposed ways to improve the damage
segmentation framework using two methods to train VGG-Unet models. They collected and manually
labeled 200 corrosion images of steel and 500 crack images of rubber bearing to build the training
dataset. The first method involves squashing segmentation to input squashed images from high
resolution directly into the VGG-Unet model, while the second method, cropping segmentation, uses
cropped images with a size of 224 × 224 as the input images. Meanwhile, in the study by Hoskere et al.
[6], the structure damage segmentation was used alongside an open-source software platform “InstaDa”
for the fast pixel-wise annotation of damage by utilizing binary masks to aid user input. They described
details of InstaDam’s software architecture and presented some of its key features. They also proposed
several benefits of InstaDam by comparing it to the Image Labeler app in Matlab, and various
comparisons were made between the InstaDam results. Moreover, experiments were conducted where
two employed student annotators were given the task of annotating damage levels in a small dataset of
images using Matlab.
Yazdchi et al. [7] is investigated the effect of nano-MgO on the durability of normal concrete under
freeze–thaw conditions. They also created a total of 98 cubic
10×10×10
10×10×10 concrete samples for the compressive strength test, while 78 cylindrical concrete
10×20
10×20 samples were considered for the tensile strength and permeability tests to build the training
dataset for gene expression programming (GEP) algorithm. They then applied GEP and three
formulations were derived to predict the mechanical properties of concrete containing nano-MgO by
randomly using 80% of the dataset for the training process and 20% for formulation testing.
Machine learning (ML)-aided structural health monitoring (SHM) can rapidly evaluate the safety and
integrity of the infrastructure. The next two research articles [8,9] in this Special Issue introduced the
framework of applying the ML algorithm for damage identification purposes. Muin et al. [8] used low
dimensionality, namely cumulative absolute velocity (CAV)-based features, to enable the use of ML for
rapid damage assessment. This experiment was performed to identify the appropriate features and the
ML algorithm using data from a simulated single-degree-of-freedom system. Gao et al. [9] combined time
series (TS) modeling and ML classification to automatically extract damage features and overcome the
limitation of non-stationarity. They also proposed a two-stage framework, namely auto-regressive
integrated moving-average machine learning (ARIMA-ML) with modules for pre-processing, model
parameter determination, feature extraction, and classification.
The research article of Altabey et al. [10] proposed a novel deep learning framework for the crack
identification for steel pipelines by extracting features from 3D shadow modeling. They also developed
a novel deep neural network to process the 3D images from 3D shadow maps. The proposed automatic
crack identification method successfully and efficiently processed 3D images and accurately diagnosed
corrosion cracks.
Moreover, Finotti et al. [11] used a deep learning algorithm, called the sparse auto-encoder (SAE),
to evaluate the algorithm when applied to characterize structural anomalies. They also explored the
SAE’s performance in a supervised damage detection approach to consolidate its application in the
structural health monitoring (SHM) field, especially when dealing with real-case structures.
For the long-term management and monitoring of bridges, the next two works [12,13] featured in the
Special Issue proposed new techniques for monitoring vehicle–bridge interactions and for the long-term
management of bridge networks. The proposed decision support system used advanced prediction
models, decision trees, and incremental machine learning algorithms to generate an optimal decision
strategy.
Damage identification methods based on structural modal parameters were influenced by the
structure form, the number of measuring sensors, and noise, resulting in insufficient modal data and low
damage identification accuracy. Su et al. [14] and Zhang et al. [15] introduced a new framework for
structure damage identification using new methods such as the bat algorithm (BA) [14] and the virtual
bass method based on damage sparsity [15].
The last article by Tang et al. [16] provided a framework for understanding natural disaster scenes
from mobile images using deep learning. The authors investigated the problem of understanding disaster
scenes through a deep learning approach. Two attributes of images were considered, including hazard
types and damage levels. Three deep-learning models were trained, and their performance was
assessed.
