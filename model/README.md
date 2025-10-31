# Egg Detection YOLOv8

- **Dataset:** `/kaggle/input/eggs-dataset/`  
- **Model:** `yolov8n.pt`  
- **Task:** Detect & classify eggs (Good, Cracked, Salted, Unidentified)  
- **Training:** 100 epochs, batch 32, image size 640, GPU (Tesla T4)  
- **Augmentation:** Mosaic, Mixup, Flip, Color jitter, Erasing  
- **Metrics:** mAP50=0.596, mAP50-95=0.420  
