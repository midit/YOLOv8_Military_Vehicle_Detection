![image](https://github.com/user-attachments/assets/f0f0b6cb-c6da-4136-b26c-624607d19494)
# YOLOv8 Military Vehicle Detection

## Overview
This project focuses on the detection of military vehicles, specifically of russian origin, using the YOLOv8 (You Only Look Once) object detection model. In today's geopolitical landscape, accurate vehicle detection plays a crucial role in national security and strategic planning. By leveraging state-of-the-art deep learning techniques, this project aims to provide a robust system for real-time identification of military vehicles.

## Dataset
The dataset used for training and validation was sourced from the [CapstoneProject’s russian Military Annotated Dataset](https://universe.roboflow.com/capstoneproject/russian-military-annotated), provided by Tuomo Hiippala from the Digital Geography Lab, Department of Geosciences and Geography, University of Helsinki, Finland. 
- **Contact Information**: Tuomo Hiippala, [tuomo.hiippala@iki.fi](mailto:tuomo.hiippala@iki.fi)

The dataset includes a comprehensive collection of annotated images featuring various military vehicle classes, allowing for effective model training and evaluation.

## Technologies Used
- **Framework**: YOLOv8 (Ultralytics)
- **Programming Language**: Python
- **Data Annotation**: Roboflow
- **Development Environment**: Google Colab
- **Libraries**: TensorFlow, OpenCV, Roboflow API, Ultralytics YOLOv8

## Features
- **High-Speed Object Detection**: The YOLOv8 model is optimized for real-time performance, making it suitable for applications like surveillance and autonomous systems.
- **Data Preprocessing**: Includes image normalization, augmentation (rotations, brightness adjustments), and annotation using Roboflow.
- **Model Evaluation**: Performance metrics such as mean Average Precision (mAP) and confusion matrices are used to assess detection accuracy.

## Project Workflow
1. **Data Collection**: The dataset was sourced from Roboflow and consists of high-resolution images of military vehicles.
2. **Data Preprocessing**: Images were normalized and augmented using Roboflow to improve model generalization.
3. **Model Training**: The YOLOv8 model was trained on a high-performance GPU using Google Colab for 100 epochs, with parameters optimized for precision and recall.
4. **Model Evaluation**: The trained model was evaluated on a validation dataset, and performance metrics were visualized using plots and confusion matrices.
5. **Inference and Testing**: The final model was tested on unseen data to verify its performance and robustness.

## Results
- **Accuracy**: The model achieved a satisfactory mean Average Precision (mAP) score, demonstrating its effectiveness in detecting and classifying military vehicles.
- **Inference Speed**: The model's real-time detection speed makes it suitable for applications requiring quick response times.

## Acknowledgments
- **Dataset Provider:** The dataset was provided by Tuomo Hiippala, Digital Geography Lab, Department of Geosciences and Geography, University of Helsinki, Finland. Contact: tuomo.hiippala@iki.fi
- **Roboflow:** For providing tools to facilitate data annotation and augmentation.
- **Ultralytics:** For developing the YOLOv8 framework.
- 
## License
This project is licensed under the MIT License. Feel free to use and modify the code for your own projects.

## Contact
For any questions or collaboration opportunities, feel free to reach out to me at:

- **Email:** patrushevx@gmail.com
- **GitHub:** github.com/midit
- **LinkedIn:** linkedin.com/in/patrushevx
