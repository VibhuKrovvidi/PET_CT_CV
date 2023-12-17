### PET-CT Cancer Detection using Deep Learning detection approaches GE Research
### Columbia University Capstone Project

Group Members:
Rohan Sheelvant (rns2167) 
Vibhu Krovvidi (vk2500)
Vritansh Kamal (vk2501)
Wei Xiong Toh (wt2354)
Yu Song Ng (yn2436)

Supervisors
Inna Stainvas (GE Research)
Adam Kelleher (Columbia University)

<br>
This project aims to address a significant challenge in the field of medical imaging, specifically in the context of Positron Emission Tomography with Computed Tomography (PET-CT) for lung cancer diagnosis. The problem at hand is the efficient and accurate detection of tumor lesions within whole-body FDG-PET/CT scans.


This project will leverage publicly available data from the 3D segmentation grand challenge project, which includes annotated ground truth for segmentation. Our task involved converting this segmentation ground truth into detection annotations, enabling the training and evaluation of object detection models on the PET/CT data.

### File Structure
<ol>
<li> models: this folder contains our models
<li> preprocessing: this folder contains code to pre-process the data from the raw DICOM into jpg formats
<li> assets: misc files used for this readme.
</ol>

### Architecture 
![alt text](https://raw.githubusercontent.com/VibhuKrovvidi/PET_CT_CV/main/assets/snip_architecture.PNG)
