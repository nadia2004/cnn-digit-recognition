# MNIST CNN: Digit Recognition, Feature Visualization & Neurobiological Insights

This project implements a **convolutional neural network (CNN)** for handwritten digit classification on the MNIST dataset and integrates it with simulated API data for digit input. Beyond standard classification, it explores **intermediate activations, feature map visualization, and adversarial robustness**, linking model behavior to principles of human visual perception.  

The project was developed as part of a course exploring the **neurobiological principles behind AI**, where we studied how artificial neural networks relate to the human brain’s visual processing. This inspired the design of the model and the focus on visualizing hidden layers and analyzing adversarial examples through a neuroscience lens.

## Key Features

- **Digit Classification:** Train or load a CNN model to recognize handwritten digits with high accuracy.  
- **Simulated API Integration:** Fetch random MNIST images to simulate an external input pipeline.  
- **Feature Map Visualization:** Extract and visualize hidden layer activations to understand what each convolutional filter detects, such as edges, corners, and other low-level features.  
- **Neurobiological Insights:** Discuss parallels between CNN feature detection and human visual processing (e.g., receptive fields in V1 simple cells).  
- **Adversarial Robustness Analysis:** Generate adversarial examples using the Fast Gradient Sign Method (FGSM) to study model vulnerabilities and relate these to biological perceptual phenomena such as optical illusions or misperceptions.  
- **Data Preprocessing & Augmentation:** Includes normalization, reshaping, and optional augmentation to improve model generalization.  
- **Visualization & Analysis:** Compare predictions on original vs adversarial images, and plot feature activations to interpret the model’s internal representations.

## Tech Stack & Skills

Python, TensorFlow, Keras, NumPy, Matplotlib, CNN design, deep learning visualization, adversarial machine learning, neuro-inspired analysis, data preprocessing.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
