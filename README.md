# Detecting-Concrete-Lining-in-Tunnel-GPR-Images

This repository contains tutorials and resources for detecting concrete linings in GPR images using Mask R-CNN and YOLOv8 models.

# Contents

- Mask R-CNN_ResNeXt_GPR.ipynb
- YOLOv8_GPR.ipynb

# How to Detect Concrete Lining in GPR Images Using Mask R-CNN

- This model does not provide training and validation sets in accordance with our data sharing policy.
- The training file of this paper, model_final.pth, is provided in hugging face, so you can download it and check the detection results.
- my_dataset_test can be applied by downloading the test.zip stored on GitHub and specifying the path of your choice

# How to Detect Concrete Lining in GPR Images Using YOLOv8

- This model does not provide training and validation sets in accordance with our data sharing policy.
- Go into the yaml file and change the path of the test set to yours
- For YOLOv8, the training files have been uploaded to the GitHub repository, so if you download the test dataset and the yaml file YOLO_best.pt and set a new path, you can see the resulting images.

# Result
<img width="397" alt="스크린샷 2025-05-04 오후 2 06 24" src="https://github.com/user-attachments/assets/c6e7237e-40dd-4fd7-9250-794af4372602" /> 
<img width="405" alt="스크린샷 2025-05-04 오후 2 06 38" src="https://github.com/user-attachments/assets/dc675bbe-9ac2-4cc1-96ac-22638636e666" />

- Detection results of the concrete lining: (a) a
case where both Mask R-CNN and YOLOv8 successfully
identify the target areas, (b) a case where Mask R-CNN
successfully identifies the target areas, while YOLOv8 does
not.
