# OilSpill-Net: Semantic Segmentation of Oil Spills

##  Project Overview
Oil spills pose a catastrophic threat to marine ecosystems. This project implements a **Deep Learning-based Computer Vision** pipeline to automate the detection of oil slicks from satellite imagery. By leveraging the **U-Net architecture**, the model provides pixel-level masks to help environmental agencies monitor spill spread and coordinate cleanup efforts.



##  Key Features
* **Architectures:** Support for U-Net, Attention U-Net, and Unet++.
* **Pipeline:** High-performance `tf.data` API implementation with real-time data augmentation.
* **Robust Metrics:** Evaluated using **Mean IoU (Intersection over Union)** and **Dice Coefficient** to handle the high class-imbalance between water and oil.
* **Custom Loss:** Integrated Binary Crossentropy + Dice Loss for better boundary convergence.

##  Performance Results
The current baseline model achieves:
* **Mean IoU:** 0.5461
* **Dice Coefficient:** 0.6788
* **Training Time:** ~30 epochs on NVIDIA T4 GPU.

##  Installation & Usage
1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/OilSpill-Net-Segmentation.git](https://github.com/your-username/OilSpill-Net-Segmentation.git)
