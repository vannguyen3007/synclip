1. Folder Structure

LipSync-Video-Generation/
├── data/                     # Contains the dataset files (extracted)
├── models/                   # Contains pre-trained model checkpoints
├── notebooks/                # Colab or Jupyter notebooks for running the code
│   ├── notebook1_generate_audio.ipynb
│   └── notebook2_generate_lipsync_video.ipynb
├── requirements.txt          # Python package dependencies
├── README.md                 # This file
└── LICENSE                   # License file


2. Requirements

opencv-python
matplotlib
imageio
gdown
tensorflow

3. How to Run the Code

* Install the dependencies with bash script: 

!pip install -r requirements.txt

* Download the required models and data using gdown 
!pip install gdown 

* Run the Jupyter/Colab Notebooks

* Test and evaluate the model using your own video/image as input.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
