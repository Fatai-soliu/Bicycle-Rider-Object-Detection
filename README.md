# Bicycle-Rider-Object-Detection

This project showcase my work in building a robust bicycle-rider detection system using state-of-the-art YOLO models. By using YOLOv7 and YOLOv8, I hope to improve cyclist safety and traffic management in urban environments using this model

# The Process

Dataset: I manually collected and annotated 175 high-quality images and videos of cyclists under diverse conditions (day/night, different locations, and various bike types).
Preprocessing: I performed data cleaning, augmentation (flipping, rotation, brightness adjustments, etc.), and splitting (70% train, 15% validation, 15% test) to ensure the dataset was ready for training.
Model Training: I implemented YOLOv7 and YOLOv8 using transfer learning with pre-trained weights, optimizing hyperparameters like epochs and batch sizes for performance.

# Tools and Techniques 
Frameworks: I used TensorFlow, PyTorch, and Roboflow for annotation and preprocessing.
Techniques: I leveraged transfer learning, data augmentation, and Google Colab’s GPU runtime for training efficiency.

# Results 
YOLOv7: Achieved 95% precision, 80% mAP@50–95, and strong detection capabilities in challenging scenarios.
YOLOv8: Delivered superior results with 99% precision, 90% mAP@50–95, and faster training times, making it the preferred model for this task.

This project taught me the importance of high-quality data and effective preprocessing in achieving accurate detections. YOLOv8's advancements in speed and accuracy make it highly suitable for real-time applications, reinforcing its potential for urban traffic management systems.
