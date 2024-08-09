# yolov5-broken_packages_recognition

## Overview

This project focuses on detecting damaged packages using a custom-trained YOLOv5 model. The goal is to identify packages with visible signs of damage in real-time, aiding in the automation of package inspection in logistics operations.

## Project Structure

- **dataset**: https://pan.baidu.com/s/1JKo1WqwrIbdH88Zz6ZJmjg?pwd=35v0 code：35v0
- **best.pt**: Includes the YOLOv5 model

## Training Process

1. **Data Collection**: We gathered a dataset of package images, ensuring a balanced representation of both damaged and undamaged packages.

2. **Data Preprocessing**: The images were resized, and labels were annotated using YOLO format. Data augmentation techniques were applied to increase the diversity of the training set.

3. **Model Training**: 
   - The YOLOv5 model was trained on the preprocessed dataset.
   - Hyperparameters were tuned to optimize model performance, including learning rate, batch size, and number of epochs.

4. **Evaluation**: The model was evaluated on a separate validation set. Metrics such as precision, recall, and mAP (mean Average Precision) were calculated to assess the model's performance.

5. **Inference**: The trained model was used to detect damaged packages in new images. The results were visualized and saved for further analysis.

## Results

- ![image](https://github.com/user-attachments/assets/19ec5850-3f48-4d48-9e1a-3bf2b220f477)



## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/damaged-package-detection.git
   cd damaged-package-detection
