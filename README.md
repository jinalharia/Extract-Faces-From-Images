# Create-Face-Data-from-Images
Using OpenCV Face Detection Neural Network to separate faces from list of images.

### Description
This project uses OpenCV's Face Detecttion Neural Network to detect faces in images and perform two tasks:
1. Create images with rectange around faces using **data_generator.py** and store them in the folder **updated_images**
2. Extract faces from a set of images using **face_extractor.py** and store them in the folder **faces**
This would make labelling/extarcting faces very easy and could be used for further analysis.

## Setup

### Python Virtual Environment
1. Clone the repository to your local machine
2. Create a virtual environment using `python -m venv facedata`
3. Activate environment using `source facedata/bin/activate`
4. Install all dependencies using `pip install -r requirements.txt`

## Usage

### Rectanges around faces
1. Create a folder with the name **images**
2. Put all the images inside the folder **images**
3. In the terminal, use the command `python data_generator.py` to generate the images
4. The generated images will be in the folder **updated_images**

### Extract faces
1. Create a folder with the name **images**
2. Put all the images inside the folder **images**
3. In the terminal, use the command `python face_extractor.py` to grab and export faces
4. The faces will be in the folder **faces**
