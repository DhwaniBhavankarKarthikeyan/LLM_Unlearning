# Neuro-Refine: Sensitive Content Penalization

## Overview

Neuro-Refine is an industrial project aimed at addressing the critical issue of sensitive content in machine learning models. As datasets and models grow, ensuring they do not perpetuate or amplify harmful information is crucial. Neuro-Refine focuses on identifying and unlearning sensitive content, retraining models to exclude such content while maintaining the integrity of non-sensitive data.

---

## Key Objectives

1. **Accurate Detection**:
   - Identify hate speech, explicit material, personal data, and more across diverse platforms.

2. **Real-Time Processing**:
   - Operate in real-time for instant detection and mitigation.

3. **Adaptability**:
   - Adapt to evolving language patterns, cultural nuances, and new forms of sensitive content.

4. **Error Minimization**:
   - Reduce false positives/negatives to avoid unnecessary censorship or missed harmful content.

5. **Retention of Useful Information**:
   - Ensure only sensitive content is removed, preserving the usability of non-sensitive data.

---

## Features

- **Machine Unlearning Approach**:
   - Advanced algorithms and techniques including Reinforcement Learning with Human Feedback (RLHF) and Genetic Algorithms (GA).
   - Strategies for real-time response optimization.
  
- **Modified Traditional Approach**:
   - Combines NLP techniques with ML/DL models for sensitive content identification and removal.

- **Application Support**:
   - Android and iOS applications for streamlined interaction.
   - Secure authentication and data encryption using AWS services.

---

## Technology Stack

### Software Requirements
- Programming: Python, TensorFlow/PyTorch, scikit-learn, spaCy/NLTK
- Frontend: ReactJS, HTML, CSS
- Backend & Database: MongoDB, AWS RDS
- App Development: Android Studio, Flutter

### Hardware Requirements
- **For Training**: 
  - High-performance multi-core CPU (e.g., Intel i7, AMD Ryzen 7).
  - 16GB+ RAM and 512GB+ storage.
- **For Deployment**:
  - Scalable cloud servers with multiple high-end GPUs.

---

## Setup Guide

### Prerequisites
1. Install Python (3.7 or above) and necessary packages (`requirements.txt`).
2. Install Android Studio or Flutter for app development.
3. Deploy backend services using AWS RDS or other cloud platforms.

### Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/DhwaniBhavankarKarthikeyan/NLP_WMAD_DL_Project.git
   ```
2. Navigate to the project directory and set up the Python environment:
   ```bash
   cd NLP_WMAD_DL_Project
   pip install -r requirements.txt
   ```
3. For mobile applications, use the provided links:
   - [Android App Repository](https://github.com/shubh28012004/Neuro_Refine_Android_App)
4. Build and deploy:
   - Backend on AWS RDS.
   - Application as `.apk` via `flutter build apk --release`.
   - Deploy to AWS S3 for production use.

---

## Dataset
1. `ForgetData.csv`
2. `TruthfulQA.csv`

---

## References
- [Key Research Papers](https://arxiv.org/pdf/2406.08607)
- [YouTube Demos](https://www.youtube.com/watch?v=em9F6fyq8yU)

---

## Demo and Deployment
Check the project workflow and app demo sections for step-by-step details about backend deployment and application use.

---

## Contributors
- **Guide**: Dr. Rahee Walembe
- **Co-Guide**: Dr. Ketan Kotecha
- **Project Members**: Dhwani Bhavankar, Het Sevalia, Shubh Agarwal

---


Thank you for your interest in **Neuro-Refine**! We look forward to your feedback and collaboration!

