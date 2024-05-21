# Custom Mask R-CNN for Leaf Disease Detection

This repository contains code for training and testing a custom Mask R-CNN model to detect various leaf diseases. The project uses the Mask R-CNN implementation from Matterport.

## Table of Contents
- [Forking the Repository](#forking-the-repository)
- [Cloning the Repository](#cloning-the-repository)
- [Installing Dependencies](#installing-dependencies)
- [Setting Up the Project](#setting-up-the-project)
- [Running the Script](#running-the-script)
- [Acknowledgments](#acknowledgments)

## Forking the Repository

1. Go to the [GitHub repository](https://github.com/your-repo-url) you want to fork.
2. Click on the `Fork` button on the top right corner of the repository page.
3. Select your GitHub account to fork the repository.

## Cloning the Repository

## Cloning the Repository

1. After forking the repository, clone it to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

## Installing Dependencies:

```bash
1. pip install -r requirements.txt
2. conda create -n maskrcnn python=3.6.8
3. conda activate maskrcnn
4. pip install tensorflow==1.15.0
```
## Setting Up the Project:
```bash
1. git clone https://github.com/matterport/Mask_RCNN.git
   cd Mask_RCNN
   python setup.py install
   cd ..
```
2. Copy the mrcnn folder from the Mask R-CNN repository into your project directory.

3. Set the root directory in custom.py to your project directory:
```bash
(python code) ROOT_DIR = "path/to/your/project"
```
Ensure you have the COCO weights file in your project directory. If not, download it from COCO weights.

## Running the script:

1. To train the model, run the custom.py script:
```bash
python custom.py
```
After training, the weights will be saved in the logs directory.

2. To test the model, use the test_model.ipynb Jupyter notebook:
```bash
jupyter notebook test_model.ipynb
```
3. Load the trained weights and run the inference on your test images.

## Acknowledgments
This README file includes all the instructions and necessary code for setting up and running the Mask R-CNN model for leaf disease detection.









