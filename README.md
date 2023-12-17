### PET-CT Cancer Detection using Deep Learning detection approaches GE Research
### Columbia University Capstone Project

### Group members Name UNI 
- Rohan Sheelvant (rns2167) 
- Vibhu Krovvidi (vk2500)
- Vritansh Kamal (vk2501)
- Wei Xiong Toh (wt2354)
- Yu Song Ng (yn2436)

Emails  &lt;UNI&gt; @ columbia.edu

### Supervisors
- Inna Stainvas (GE Research)
- Adam Kelleher (Columbia University)

<br>
This project aims to address a significant challenge in the field of medical imaging, specifically in the context of Positron Emission Tomography with Computed Tomography (PET-CT) for lung cancer diagnosis. The problem at hand is the efficient and accurate detection of tumor lesions within whole-body FDG-PET/CT scans.


This project will leverage publicly available data from the 3D segmentation grand challenge project, which includes annotated ground truth for segmentation. Our task involved converting this segmentation ground truth into detection annotations, enabling the training and evaluation of object detection models on the PET/CT data.

Preprocessing : Contains all the EDA and Preprocessing required to prepare data for modelling
Training : Contains the DETR and YOLO model training files

**Directory tree**
```
│   .gitignore
│   README.md
│
├───.ipynb_checkpoints
├───assets
│       PETCT_0117d7f11f_axial_190.jpg
│       snip_architecture.PNG
│       
│
├───preprocessing
│   | CT_2D_Nifti_Slices_Preprocessing.ipynb
│   | Create_yolo_labels.ipynb
│   | Generate_SUV_CT_k_means.ipynb
│   | PET_&_CT_Stacked_2D_Nifti_Slices_Preprocessing.ipynb
│   | SUV_&_CT_2D_Nifti_Slices_Preprocessing.ipynb
│   | TrainValTest_split.ipynb
│   | data_folder_structure_script.ipynb
│   | data_folder_structure_script_k_means.ipynb
│   | detr_create_annotations.ipynb
│   | show_bounding_box.ipynb
│   └───eda
│      | eda_preprocess.ipynb
│      |  README.md
│
├───training
│   └───DETR    
│        | Training_Conditional_DETR.ipynb
│        | readme.md
|        | requirements.txt
│   └───YOLO
│       │ CT_YOLOv8.ipynb
│       │ PETCT_stacked_kmeans_YOLOv8.ipynb
│       │ SUV_YOLOv8.ipynb
│       │ SUV_kmeans_YOLO_v8.ipynb
│       │ petct_stacked_kmeans_yolov8.yaml
│       │ petct_stacked_yolov8.yaml
│       │ suv_kmeans_yolov8.yaml
│       │ suv_yolov8.yaml
|        └───models
|            | ct_yolov8_best.pt
|            | petct_stacked_kmeans_yolov8_best.pt
|            | petct_stacked_yolov8_best.pt
|            | suv_kmeans_yolov8_best.pt
|            | suv_yolov8_best.pt
```     


### Architecture 
![alt text](https://raw.githubusercontent.com/VibhuKrovvidi/PET_CT_CV/main/assets/snip_architecture.PNG)
