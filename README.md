# Object-detection-and-Image-Captioning
This repository contains a Jupyter notebook demonstrating object detection using PyTorch's Faster R-CNN/Mask R-CNN models and image captioning using the nlpconnect/vit-gpt2-image-captioning model from Hugging Face Transformers.

Tech Stack
Object Detection: torchvision.models.detection.fasterrcnn_resnet50_fpn (pretrained)

Image Captioning: nlpconnect/vit-gpt2-image-captioning

Visualization: Matplotlib with bounding box overlays

Dataset: Open Images V4 (train split)

| Task       | Model                     | Framework    | Confidence            |
| ---------- | ------------------------- | ------------ | --------------------- |
| Detection  | Faster R-CNN ResNet50-FPN | TorchVision  | >0.6                  |
| Captioning | ViT-GPT2                  | Transformers | Beam search (4 beams) |


<img width="917" height="639" alt="image" src="https://github.com/user-attachments/assets/ed389827-9ba1-46a4-8501-dd64842c6880" />
<img width="903" height="986" alt="image" src="https://github.com/user-attachments/assets/9ee983b2-1a68-4d63-8beb-748d2d10bd43" />
<img width="878" height="1117" alt="image" src="https://github.com/user-attachments/assets/53f02008-9ad1-462c-813f-8d5f6ed302dc" />


