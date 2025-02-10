# CS203_Assign_5
CS203: Software tools and techniques for AI

# Team Members:
Sarvesh Pravin Chaudhari (23110076) <br>
Afraz Azeem (23110019)

# Description
LAB 05 Submission

# Model Architectural Diagram

Input Image (3 channels, 224x224)
       |
       v
ResNet-50 (Pre-trained)
       |
       v
Pooler Output (2048-dimensional vector)
       |
       v
Reshape (Flatten to 1D)
       |
       v
ClassificationHead (Linear Layer: 2048 -> 1)
       |
       v
Output (Single value for prediction)
