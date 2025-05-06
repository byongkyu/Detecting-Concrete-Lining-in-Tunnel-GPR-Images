# Detecting-Concrete-Lining-in-Tunnel-GPR-Images

This repository contains tutorials and resources for detecting concrete linings in GPR images using Mask R-CNN and YOLOv8 models. While this repository does not provide training and validation data due to the data sharing policy of the provider, we do provide the code for training the models, model weights, and test data to replicate the result.

# Contents

- `Mask R-CNN`: This directory includes a notebook for training and testing the model.
- `YOLOv8`: This directory includes a notebook for training and testing the model, model weights, and a configuration file. 

# How to Detect Concrete Lining in GPR Images Using Mask R-CNN
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/byongkyu/Detecting-Concrete-Lining-in-Tunnel-GPR-Images/blob/main/Mask%20R-CNN/Mask_R_CNN_ResNeXt.ipynb)
- The trained model, `model_final.pth`, is provided in hugging face, so you can download it and check the detection results.
- `my_dataset_test` can be applied by downloading the test.zip stored on GitHub and specifying the path of your choice

# How to Detect Concrete Lining in GPR Images Using YOLOv8
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/byongkyu/Detecting-Concrete-Lining-in-Tunnel-GPR-Images/blob/main/YOLOv8/YOLOv8.ipynb)
- Go into the `yaml` file and change the path of the test set to yours.
- For YOLOv8, the trained model weights have been uploaded to the GitHub repository, so if you download the test dataset and the yaml file YOLO_best.pt and set a new path, you can see the resulting images.

# Result
<img width="397" alt="스크린샷 2025-05-04 오후 2 06 24" src="https://github.com/user-attachments/assets/c6e7237e-40dd-4fd7-9250-794af4372602" /> 
<img width="405" alt="스크린샷 2025-05-04 오후 2 06 38" src="https://github.com/user-attachments/assets/dc675bbe-9ac2-4cc1-96ac-22638636e666" />

- Detection results of the concrete lining: (a) a
case where both Mask R-CNN and YOLOv8 successfully
identify the target areas, (b) a case where Mask R-CNN
successfully identifies the target areas, while YOLOv8 does
not.

<img width="371" alt="스크린샷 2025-05-04 오후 3 31 33" src="https://github.com/user-attachments/assets/eaff45f2-1b46-4f72-8a0a-9e7acbc8a25a" />

- Violin plot comparing IoU distributions from
Mask R-CNN with ResNeXt backbone, Mask R-CNN with
ResNet backbone, YOLOv8, and U-Net models. Box plots are
inscribed inside the violin plot.


