# NavsoftAI-Project

PROJECT SUMMARY
Project Name: Vehicle License Plate Detection and Extraction
Objective: Build an AI model to automatically detect license plates in video footage

🎯 What Was Done:

Data Collection

Extracted 200 frames from video at 1 FPS
Diverse vehicle positions and lighting conditions


Annotation

Manually annotated all 200 frames using Roboflow
Drew bounding boxes around license plates
Split into: Train (70%), Validation (20%), Test (10%)


Model Training

Used YOLOv8 Nano (pretrained on COCO)
Fine-tuned on license plate detection
Trained for 81 epochs (early stopping at epoch 61)
Device: GPU (Tesla T4)


Results

mAP50: 0.994 (99.4% - Excellent!)
Precision: 0.989 (98.9%)
Recall: 0.994 (99.4%)
Training completed in 5 minutes


Testing

Tested on 5 sample images
Generated confusion matrix
Verified model works correctly

📊 Key Metrics:
MetricValueDataset Size200 imagesTraining Time5 minutesModel Accuracy (mAP50)0.994Precision0.989Recall0.994FrameworkYOLOv8 NanoGPU UsedTesla T4

📦 Deliverables:
✅ Annotated dataset (YOLO format)
✅ Trained model weights (best.pt)
✅ Complete Colab notebook
✅ Training visualizations
✅ Detection results
✅ Full documentation

🎓 This Demonstrates:
✅ End-to-end machine learning pipeline
✅ Computer vision expertise
✅ Data annotation skills
✅ Model training & optimization
✅ Performance evaluation
✅ Professional code documentation
Perfect for internship evaluation! 🚀
