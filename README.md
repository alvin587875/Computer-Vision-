# LEGO Piece Detection Using Faster R-CNN

## Overview
This project aims to detect various LEGO pieces using the Faster R-CNN algorithm. The dataset for this project was obtained from Kaggle, and the model is trained to identify and classify different types of LEGO pieces accurately.

### Project Details
- **Author:** Alvin Mathew  
- **Algorithm Used:** Faster R-CNN  
- **Dataset Source:** [Kaggle LEGO Dataset](https://www.kaggle.com/)  
- **Purpose:** This project serves as a practical implementation of object detection using a custom dataset to recognize LEGO pieces. 

## Features
- Detection of multiple LEGO piece types.
- High precision due to the use of the Faster R-CNN model.
- Custom-trained model on a well-curated dataset.

## Getting Started
Follow the steps below to set up the project and run the detection model.

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- pip
- CUDA (optional, for GPU acceleration)

### Installation
1. Clone the repository:
   ```bash
   git clone <[repository-link](https://github.com/alvin587875/Computer-Vision-/edit/main)>
   cd <Computer-Vision>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/) and place it in the `data` folder.

### Usage
1. Open the notebook `RCNN_lego.ipynb` in Jupyter Notebook or JupyterLab.
2. Ensure the dataset is loaded correctly by running the data preparation cells.
3. Train the Faster R-CNN model by following the steps outlined in the notebook.
4. Test the model on sample images to visualize the detection results.

## Results
The trained Faster R-CNN model demonstrates high accuracy in detecting LEGO pieces, as illustrated in the `RCNN_lego.ipynb` notebook. Example results are shown in the output cells of the notebook.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with detailed documentation on your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or support, feel free to contact Alvin Mathew at [alvinmathew112@gmail.com].
