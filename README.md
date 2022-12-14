# Automatic Vehicle License Plate Detection Using Deep Learning
Across the globe, automating vehicle identification in real time has gained prominence for a variety of reasons ranging from issuing speeding tickets to theft identification. In this regard, since the turn of the century, plethora of traffic cams have been placed in every nook and corner of most cities that provide us with rich high resolution data necessary for detection of vehicles at scale. While the ethics and  privacy concerns of uniquely identifying vehicles are debatable, a number of use cases for vehicle identification that are non-invasive, anonymised, beneficial and consent driven do still exist. And so our focus in this project is to build a real time automatic vehicle detection system for any of the net positive use cases we will discuss in further sections.

## Pre-requisites
- Need to have a kaggle API token json file (kaggle.json)
- Familiarity and access to Google Colab environment


## How to run the code.
*The script is designed to create all the necessary directories.*
- Load the **ANPR_final.ipynb** into Colab environment
- Select runtime as GPU
- Upload the **kaggle.json** in file in the current directory when prompted
- The cells following the upload will
1. Setup the directories
2. Load the necessary Yolov5 libraries 
3. Set up the directory structure
4. Perform the necessary manipulations to set up the training data in the correct format for Yolo
5. Train the model
6. Produce diagnostics of the trained model
7. Load the trained model
8. Setup the easyOCR
9. Load the necessary functions to make Yolo inferences and pass through OCR

-Finally in the last cell, provide a name of the image to scan from the directory. Feel free to upload any personal image to run through the model.
