# Mixed-type-Wafer-Defect-Semiconductor-using-CNN-and-Pytorch
 The "Mixed-type Wafer Defect Datasets" contains about 38,000 wafer maps, including various defect patterns.I used Pytorch and CNN to classify them.

# What is Wafer?
A wafer is a thin slice of semiconductor material, such as silicon, that serves as the foundation for creating integrated circuits (ICs) and other microelectronic devices. Wafers are used in the manufacturing process for components like processors, memory chips, and sensors.

# Defects:-
During the wafer fabrication process, defects can occur due to:

Impurities in the material.
Mechanical stress or mishandling.
Issues in the photolithography or etching process.

These defects can render the wafer unusable for manufacturing, making defect detection a critical task for maintaining quality control.

# Dataset
The Mixed-type Wafer Defect Datasets consists of:

38,000 wafer maps with defect patterns.
Input shape: (52x52) grayscale images.
Target: One-hot encoded vector representing 8 defect classes.
Dataset source:https://www.kaggle.com/datasets/co1d7era/mixedtype-wafer-defect-datasets/code

# Result
65-67 percent on training ,validation and testing



