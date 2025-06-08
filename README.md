# Robustness-Testing-of-Facial-Recognition-Algorithms
THe project undertaken during Defence Reseach and Development Organisation, Ministry of Defence, Govt. of India, summer internship develops attack methods, testing black box and white box adversarial attacks on facial recognition deep learning models, using the celeb_a, lfw and VGG Face datasets.

Adversarial Attacks on Facial Recognition Systems

A comprehensive research project investigating the vulnerability of facial recognition deep learning models to adversarial attacks. This project implements and evaluates both black-box and white-box attack methodologies on state-of-the-art facial recognition systems.

🎯 Project Overview

This research project, conducted as part of the DRDO (Defence Research and Development Organisation) summer internship program, focuses on developing and testing adversarial attack methods against facial recognition systems. The study evaluates the robustness of deep learning models when subjected to carefully crafted adversarial perturbations.

🔬 Research Objectives

1) Security Assessment: Evaluate vulnerabilities in facial recognition systems

2) Attack Development: Implement sophisticated adversarial attack algorithms

3) Robustness Testing: Assess model performance under adversarial conditions

4) Defense Analysis: Investigate potential countermeasures and defensive strategies

5)Comparative Study: Analyze effectiveness across different model architectures

🛠️ Technical Stack

Python 3.8+: Primary programming language

PyTorch/TensorFlow: Deep learning frameworks

OpenCV: Computer vision operations

NumPy: Numerical computations

Matplotlib/Seaborn: Visualization and analysis

Jupyter Notebook: Research and development environment

📊 Datasets Used
CelebA Dataset
- Size: 200,000+ celebrity images
- Attributes: 40 binary facial attributes
- Usage: Training and testing facial recognition models

LFW (Labeled Faces in the Wild)

Size: 13,000+ face images
Subjects: 5,749 different individuals
Usage: Benchmark for face verification tasks

VGG Face Dataset

Size: 2.6M+ face images
Subjects: 2,622 identities
Usage: Large-scale face recognition training

🎯 Attack Methodologies
White-box Attacks

FGSM (Fast Gradient Sign Method): Single-step gradient-based attack
PGD (Projected Gradient Descent): Iterative gradient-based attack
C&W Attack: Carlini & Wagner optimization-based attack
DeepFool: Minimal perturbation attack method

Black-box Attacks

Transfer-based Attacks: Leveraging model transferability
Query-based Attacks: Decision boundary estimation
Evolutionary Attacks: Genetic algorithm-based perturbations
Substitute Model Attacks: Training surrogate models
