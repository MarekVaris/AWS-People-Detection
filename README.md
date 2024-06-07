**AWS People Detection**

*Using SageMaker Notebook to Train YOLOv3 for People Detection and Store Results in S3*

**Overview:**
AWS People Detection is a project that leverages Amazon SageMaker Notebooks to train a YOLOv3 model for detecting people in images. The trained model processes images and stores the detection results in an S3 bucket, providing a scalable and efficient solution for people detection.

**Features:**
- **Model Training with SageMaker:** The project utilizes Amazon SageMaker Notebooks for training the YOLOv3 model. SageMaker provides a managed environment to build, train, and deploy machine learning models at scale.
- **People Detection with YOLOv3:** The YOLOv3 (You Only Look Once) model is known for its high accuracy and real-time object detection capabilities, making it ideal for detecting people in images.
- **Output Storage in S3:** After processing the images, the detection results, including bounding boxes and confidence scores, are stored in an Amazon S3 bucket. This ensures that the results are easily accessible and can be integrated with other AWS services.

**Workflow:**
1. **Data Preparation:** Collect and prepare a dataset of images containing people. Annotate the images to create labeled data for training the YOLOv3 model.
2. **Model Training:** Use Amazon SageMaker Notebook to set up and configure the training environment. Train the YOLOv3 model using the prepared dataset.
3. **Inference:** Deploy the trained YOLOv3 model to SageMaker Endpoint for inference. The model processes input images and detects people, returning bounding boxes and confidence scores.
4. **Output Storage:** The detection results are saved to an Amazon S3 bucket. Each result includes the processed image with bounding boxes and a metadata file with detailed detection information.

**Technical Details:**
- **Developed in:** Python
- **Machine Learning Framework:** Darknet (YOLOv3)
- **Platform:** Amazon SageMaker
- **Storage:** Amazon S3
