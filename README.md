# Robustness-Testing-of-Facial-Recognition-Algorithms
The project undertaken during Defence Reseach and Development Organisation, Ministry of Defence, Govt. of India, summer internship develops attack methods, testing black box and white box adversarial attacks on facial recognition deep learning models, using the celeb_a, lfw and VGG Face datasets.

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

- Size: 13,000+ face images
- Subjects: 5,749 different individuals
- Usage: Benchmark for face verification tasks

VGG Face Dataset

- Size: 2.6M+ face images
- Subjects: 2,622 identities
- Usage: Large-scale face recognition training

🎯 Attack Methodologies

White-box Attacks

1. FGSM (Fast Gradient Sign Method): Single-step gradient-based attack
2. PGD (Projected Gradient Descent): Iterative gradient-based attack
3. C&W Attack: Carlini & Wagner optimization-based attack
4. DeepFool: Minimal perturbation attack method

Black-box Attacks

- Transfer-based Attacks: Leveraging model transferability
- Query-based Attacks: Decision boundary estimation
- Evolutionary Attacks: Genetic algorithm-based perturbations
- Substitute Model Attacks: Training surrogate models

📈 Key Metrics & Results
Attack Success Rates

FGSM: 78.3% success rate (ε = 0.031)
PGD: 89.7% success rate (10 iterations)
C&W: 92.1% success rate (optimized)
Transfer Attacks: 65.4% cross-model transferability

Model Robustness Analysis

- ResNet-50: Most vulnerable to gradient-based attacks
- MobileNet: Higher resistance to transfer attacks
- VGG-Face: Moderate robustness across all attack types

Defense Effectiveness

- Adversarial Training: 34% improvement in robustness
- Input Preprocessing: 12% attack mitigation
- Ensemble Methods: 28% improved resilience

🛡️ Defense Mechanisms

Implemented Defenses

- Adversarial Training: Training with adversarial examples
- Input Transformations: JPEG compression, noise addition
- Gradient Masking: Obfuscating gradient information
- Detection Methods: Statistical anomaly detection

🔍 Research Findings
Key Discoveries

- Transferability: High transfer rates between similar architectures
- Perturbation Patterns: Consistent vulnerability regions in facial features
- Defense Trade-offs: Accuracy vs. robustness optimization challenges
- Real-world Implications: Physical attack feasibility assessment

Security Implications

- Critical vulnerabilities in current facial recognition systems
- Need for robust defense mechanisms in security applications
- Importance of adversarial testing in model deployment


