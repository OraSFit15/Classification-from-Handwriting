# Classification-from-Handwriting
The authors' contact information
Ora Fitoussi
345010946
Shami Shamoon Beer Sheva

Description
Automatic classification of the writer's gender.
The purpose of the program is to  classify images by gender (man's handwriting or woman's handwriting)
for this we  need to extract features thanks to LBP and  to train an SVM model, perform experiments with different parameters and kernels,
and report which combination of parameters achieves the highest accuracy. (Thanks to GridSearchCV).

Environment
- pip install opencv
- pip install numpy
- pip install sys
- pip install sklearn

How to Run Your Program
in your terminal run : python3 Classifier.py HHD_gender/train HHD_gender/val HHD_gender/test
