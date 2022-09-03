# Colorectal-Cancer-Histology-Transfer-Learning-and-Fine-Tuning

* Fine-tuning an image classification model on a Colorectal-Cancer-Histology dataset.
* This is a biological 8-class classification problem.
* The dataset consists of 5000 images.
* Each example is a 150 x 150 x 3 RGB image of one of 8 classes.
* The class labels are: ("tumor", "stroma", "complex", "lympho", "debris", "mucosa", "adipose", "empty")
* The state-of-the-art CNN, ResNet50V2, is used as base model.
* The last 10 layers of the base model are unfreezed for fine-tuning.
* Data augmentation is implemented for regularization.
* Accuracy of 93% is achieved on validation and test datasets.

* Source: https://www.tensorflow.org/datasets/catalog/colorectal_histology
* Dataset homepage: https://zenodo.org/record/53169#.XGZemKwzbmG
