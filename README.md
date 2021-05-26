## Step By Step Mask RCNN Installation

**Attention❗️** 
* Compatible Python Version: python==3.6.12
* IDE: Anaconda Cloud & Conda Prompt
    
    -Anaconda Cloud: https://www.anaconda.com

🔺 **Step 1:** Compatible with Python 3.6 version, a virtual environment named maskrcnn is created in conda prompt.
>conda create -n maskrcnn python=3.6.12

🔺 **Step 2:** The maskrcnn virtual environment is activated.
>conda activate maskrcnn
 
🔺 **Step 3:** The Mask RCNN published by Matterport is cloned from the GitHub repository.
>git clone https://github.com/matterport/Mask_RCNN.git

🔺 **Step 4:** Mask RCNN must be installed in the requirements.txt file located in the GitHub store. The requirements.txt file will load the libraries needed for your project in batch.
>pip install -r requirements.txt

**Dependencies**
>numpy, scipy, cython, h5py, Pillow, scikit-image, 
tensorflow==1.3 keras==2.0.8, jupyter

For GPU: tensorflow-gpu:1.15.0, keras:2.2.5
For CPU: tensorflow:1.14.0, keras:2.0.8, h5py:2.10.0

🔺 **Step 5:** Download the pre-trained weights from https://github.com/matterport/Mask_RCNN/releases.
    
 Download the file mask_rcnn_balloon.h5 from Mask_RCNN_2.1 file and mask_rcnn_coco.h5 model from Mask_RCNN_2.0 file. These 2 models should be placed in the samples folder.

**Attention❗️** 
 
 If the TensorFlow and Keras versions have landed in high versions, you can make a specific installation with the following commands.

🔺 **Step 6:** Running the setup.py file.
 >python setup.py install

🔺 **Step 7:** Loading the pycocotols module.
>pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI

🔺 **Step 8:** Let's run it on the Jupyter notebook.
>jupyter notebook

A view from the project: ![Mask RCNN Sample](Sample.png "Mask RCNN Sample")
