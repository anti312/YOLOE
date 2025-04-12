# YOLOE

YOLOE is an efficient implementation of the YOLO (You Only Look Once) object detection model. It is designed to provide fast and accurate object detection in images and videos. YOLOE optimizes the original YOLO architecture to ensure better performance, especially in real-time applications. This model is capable of detecting multiple objects in images with a single forward pass, making it highly efficient for real-world applications.

## Tutorial

Follow the steps below to use the YOLOE model for object detection:

### 1. Import the notebook on Google Colab
To get started, import the notebook into your Google Colab environment by opening the notebook file (`.ipynb`) in your Google Drive.

### 2. Configure the classes you want to search for in the images
In the configuration section of the notebook, specify the classes you want to detect.

### 3. Upload the images to the `dataset` folder
Create a folder named `dataset` in the Colab environment and upload all the images you want to analyze into this folder.

#### 3.1 Optional: To calculate the average IoU (Intersection over Union) across the entire dataset
If you wish to calculate the average IoU for your dataset, create a subfolder inside the `dataset` folder named `annotations`. In this subfolder, upload the bounding boxes (bbox) for each image in YOLO format (xywhn).

### 4. Run the code
Execute the code cells in the notebook to begin the object detection process. The model will process the images and detect objects based on the specified classes.

### 5. View the results
After the code completes, you can view the results, which will include the detected objects along with the corresponding bounding boxes on the images.
