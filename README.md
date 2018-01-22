# Label-free assessment of red blood cell storage lesions by deep learning
Analytic scripts for Doan et al. (2018), "Label-free assessment of red blood cell storage lesions by deep learning"

# Usage:

- Step 0: IDEAS 6.2 - Preliminary gating, remove out-of-focus, collect single cells, and exporting .CIF
- Step 1: Python 3.6 - Parse little images inside .CIF into .NPY
- Step 2: Python 3.6 - Train convolutionaly neural network ResNet50
- Step 3: Python 3.6 - Evaluate trained model, supervised classification of RBC morphology
- Step 3b: Python 3.6 - Data-driven visualization of deep learning feature space
- Step 4: Python 3.6 - Construct confusion matrices and other plots

iPython notebooks for steps 1-4 are provided in this repository

# Dependencies:
Prior to installation of deepometry itself, user needs the following packages pre-installed:

- deepometry 1.0.0
- python 3.6.1
- numpy 1.12.1 
- scipy 0.19.0
- click 6.7
- pandas 0.19.2
- jupyter 1.0.0
- h5py 2.7.0
- matplotlib 2.0.0
- seaborn 0.7.1
- scikit-image 0.13.0
- scikit-learn 0.18.1
- imageio 2.1.2
- tensorflow 1.0.1 (CPU or GPU version)
- keras 2.0.2
- Java development kit
- python-bioformats 1.1.0
- javabridge 1.0.14

Note: Java development kit (32- or 64- bit version to be matched with operating system) should be installed before python-bioformats and javabridge.

Note: Tensorflow python package is sufficient for CPU use. However, in order to utilize a CUDA-compatible GPU, Tensorflow-GPU as well as CUDA and cuDNN packages are required; more details are described on Tensorflow homepage.

Note: Windows user will need Microsoft Visual C++ Build tools and its compilers installed, with respect to Python versions of 2.7 or 3.5+ accordingly. Windows user is also advised to install numpy (numpy+mkl version), scipy and scikit-image as wheel packages: numpy-1.12.1+mkl-cp35-cp35m-win_amd64.whl, scipy-0.19.0-cp35-cp35m-win_amd64.whl, scikit_image-0.13.0-cp35-cp35m-win_amd64.whl

# Installation of deepometry: 

Please visit http://github.com/broadinstitute/deepometry
