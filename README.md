Person Re-Identification with Market-1501 Dataset

This repository contains code for person re-identification using the Market-1501 dataset. The project utilizes various libraries including segmentation-models-pytorch, albumentations, and opencv-contrib-python for image processing and deep learning tasks.

Installation

To install the required packages, run the following commands:

bash

pip install segmentation-models-pytorch

pip install -U git+https://github.com/albumentations-team/albumentations

pip install --upgrade opencv-contrib-python

Dataset

Download the Market-1501 dataset from Kaggle.

Cloning the Repository

To clone this repository, use the following command:

bash

git clone https://github.com/parth1620/Person-Re-Id.git

Usage

Prepare the Dataset:

Place the downloaded Market-1501 dataset in the appropriate directory as required by the script.

Run the Script:

Execute the main script for person re-identification.

bash

python main.py

Dependencies

segmentation-models-pytorch==0.3.3

albumentations==1.4.11

opencv-contrib-python==4.10.0.84

torch>=2.3.0+cu121

numpy>=1.24.4

scikit-learn>=1.5.1

scikit-image>=0.24.0

Project Structure

css

.

├── data

│   └── Market-1501

│       ├── bounding_box_test

│       ├── bounding_box_train

│       ├── gt_bbox

│       ├── gt_query

│       ├── query

│       └── readme.txt

├── src

│   ├── dataset.py

│   ├── model.py

│   ├── train.py

│   └── utils.py

├── main.py

└── README.md

Acknowledgements

The Market-1501 dataset is provided by C. Zheng, L. Zheng, S. Gong, and Y. Yang. Details can be found in their paper.

Special thanks to the contributors of the libraries used in this project.

Contact

For any inquiries or contributions, please contact Naman Jain.
