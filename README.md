RetinaWise AI: An AI-Powered AMD Analysis and Clinical Decision Support System

An ongoing AI/ML research project focused on developing an intelligent clinical decision-support system to assist ophthalmologists in analyzing Age-Related Macular Degeneration (AMD) using retinal Fundus and Optical Coherence Tomography (OCT) images, as well as patient reports.
Key Features
- Multimodal Data Processing: Extracts and processes relevant retinal images and information from uploaded patient reports, supporting both Fundus photography and OCT imaging.
- AMD Activity Classification: Predicts AMD status and classifies wet AMD as active or inactive to support clinical assessment.
- Biomarker-Based Segmentation: For active wet AMD, identifies and segments five key OCT biomarkers using deep learning architectures such as U-Net++ and Attention U-Net.
- Anti-VEGF Injection Prediction: Estimates the potential number of anti-VEGF injections based on relevant imaging findings and available patient data.
- Explainable AI (XAI): Highlights image regions associated with detected biomarkers to help doctors understand the model's predictions.
- Automated Report Generation: Generates structured reports summarizing image analysis, classification results, biomarker segmentation, and prediction outputs.
- Human-in-the-Loop Validation: Incorporates ophthalmologist feedback to review AI-generated predictions, validate segmentation results, and support iterative system improvement.
Technology Stack
Python, Deep Learning, Computer Vision, U-Net++, Attention U-Net, Explainable AI, OpenCV, NumPy, Scikit-learn, TensorFlow/PyTorch, and Google Colab.
Current Status
In Progress — Developing and evaluating the image-analysis pipeline, segmentation models, prediction modules, explainability features, and doctor-in-the-loop validation workflow.
Objective
To build a reliable, interpretable, and doctor-supervised AI system that streamlines retinal image analysis and supports clinical decision-making in AMD management. The system is intended to assist medical professionals, not replace their clinical judgment.
