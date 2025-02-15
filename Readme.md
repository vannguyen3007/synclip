# LipSync-Video-Generation

This project provides an end-to-end pipeline for generating lip-synced videos where a person (2D/3D model or real) reads a given text with the most natural mouth movement possible.

## Folder Structure
LipSync-Video-Generation/ ├── data/ # Contains the dataset files (extracted) ├── models/ # Contains pre-trained model checkpoints ├── notebooks/ # Colab or Jupyter notebooks for running the code │ ├── notebook1_generate_audio.ipynb │ └── notebook2_generate_lipsync_video.ipynb ├── requirements.txt # Python package dependencies ├── README.md # This file └── LICENSE # License file

- **`data/`**: This folder contains the dataset files which are extracted and ready for processing.
- **`models/`**: This folder stores pre-trained model checkpoints used for lip-sync generation.
- **`notebooks/`**: Contains the Jupyter or Colab notebooks that run the code for audio and video generation.
    - **`generate_audio.ipynb`**: Generates audio for the given text.
    - **`generate_lipsync_video.ipynb`**: Generates a video with lip-sync based on the audio.
- **`requirements.txt`**: Lists the Python package dependencies required to run the project.
- **`README.md`**: This file containing instructions for the project.
- **`LICENSE`**: License information for the project.

## Requirements

Make sure to install the following Python dependencies:

- `opencv-python`: For video processing
- `matplotlib`: For data visualization
- `imageio`: To handle video and image data
- `gdown`: For downloading data and models from Google Drive
- `tensorflow`: For building and training the deep learning model

To install these dependencies, you can use the `requirements.txt` file:
## How to Run the Code
```bash
pip install -r requirements.txt

Use gdown to download the pre-trained models and dataset.

First, make sure gdown is installed:
pip install gdown
gdown <link_to_the_data_or_model>


3. Run the Notebooks
We provide two Jupyter/Colab notebooks:

notebook1_generate_audio.ipynb: This notebook generates audio from a given text paragraph in Vietnamese using a reference voice.

notebook2_generate_lipsync_video.ipynb: This notebook takes a video/image and replaces the audio with the audio generated from the first notebook, ensuring the mouth movements are synchronized with the new audio.

You can run these notebooks in either a local Jupyter environment or in Google Colab. If you're using Google Colab, simply upload the notebook and required files.

4. Test and Evaluate the Model
Once the notebooks are executed, you can test and evaluate the model by providing your own video/image as input. The model will then generate a lip-synced video with the provided audio.

License
This project is licensed under the MIT License. See the LICENSE file for more details.





