# YOLOv5-detection
YOLOv5 Object Detection Experiments and Results

# YOLOv5 Object Detection on Film Photos
This project uses YOLOv5 to perform object detection on both public datasets and personal analog film image.

## 🧠 Overview
- Model: YOLOv5s (pretrained)
- Platform: Google Colab
- Dataset: COCO val2017 + personal image
- Evaluation: mAP@0.5 = 56.6%, mAP@0.5:0.95 = 37.1%

## 📸 Detection Result Example
![result](이미지분석.jpeg)

## 📓 Code Notebook
You can check the full detection notebook [here](./YOLO_model.ipynb)

## 💡 What I Learned
- Applied YOLOv5 to a non-standard image type (analog film)
- Learned how to set up detection pipeline with Google Colab
- Understood basic metrics (Precision, Recall, mAP) for evaluating models
