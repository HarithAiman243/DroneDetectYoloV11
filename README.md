# Drone Detection in Adverse Weather Conditions using YOLOv11 Algorithm

Final Year Project for Bachelor's degree (EE), IIUM.

## Overview
This project improves drone detection during rainy weather using the YOLOv11 deep learning algorithm. Since rain causes visual distortions that reduce detection accuracy, the solution involves applying synthetic rain effects to drone images and training YOLOv11 models to recognize drones in such conditions.

## Contributions
- • 𝗦𝘆𝗻𝘁𝗵𝗲𝘁𝗶𝗰 𝗥𝗮𝗶𝗻 𝗗𝗮𝘁𝗮𝘀𝗲𝘁: Created a augmented dataset of 5,000 drone images with synthetic rain effects at five intensity levels using Albumentations.
- • 𝗬𝗢𝗟𝗢𝘃𝟭𝟭 𝗧𝗿𝗮𝗶𝗻𝗶𝗻𝗴: Trained multiple YOLOv11 models (n, s, m, l, x) on the augmented dataset.
- • 𝗠𝗼𝗱𝗲𝗹 𝗢𝗽𝘁𝗶𝗺𝗶𝘇𝗮𝘁𝗶𝗼𝗻: Fine-tuned the best-performing model (YOLOv11m) for better accuracy in heavy rain.
- • 𝗘𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻: Assessed models using precision, recall, F1-score, mAP, and fitness across all rain levels.
 
## Tech Stacks & Frameworks:
YOLOv11, PyTorch, Albumentations, OpenCV, Pandas, Matplotlib & Seaborn

## Results/Output:
- • Achieved s𝘁𝗿𝗼𝗻𝗴𝗲𝗿 𝗱𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻 𝗽𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲 in rain, especially at higher intensities.
- • 𝗬𝗢𝗟𝗢𝘃𝟭𝟭𝗺 𝗴𝗮𝘃𝗲 𝘁𝗵𝗲 𝗯𝗲𝘀𝘁 𝗿𝗲𝘀𝘂𝗹𝘁𝘀 with 𝗽𝗿𝗲𝗰𝗶𝘀𝗶𝗼𝗻 (𝟬.𝟵𝟬𝟰𝟳), 𝗿𝗲𝗰𝗮𝗹𝗹 (𝟬.𝟴𝟲𝟱𝟴), and 𝗺𝗔𝗣 (𝟬.𝟵𝟮𝟮𝟴).
 
## Setup (Linux / macOS / WSL / Windows with py)
1. Clone:
```bash
git clone https://github.com/HarithAiman243/DroneDetectYoloV11.git
cd DroneDetectYoloV11
