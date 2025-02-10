# CS203_Assign_5
CS203: Software tools and techniques for AI

# Team Members:
Sarvesh Pravin Chaudhari (23110076) <br>
Afraz Azeem (23110019)

# Description
LAB 05 Submission

# Model Architectural Diagram

Input Image (3 channels, 224x224) <br>
       | <br>
       v <br>
ResNet-50 (Pre-trained) <br>
       | <br>
       v <br>
Pooler Output (2048-dimensional vector) <br>
       | <br>
       v <br>
Reshape (Flatten to 1D) <br>
       | <br>
       v <br>
ClassificationHead (Linear Layer: 2048 -> 1) <br>
       | <br>
       v <br>
Output (Single value for prediction)
