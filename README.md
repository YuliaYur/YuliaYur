# Hi, I'm Yuliana 👋

I'm a Machine Learning Engineer with 5+ years of experience building, deploying, and optimizing production ML systems across computer vision, LLM applications, real-time inference, synthetic data generation, and on-device AI.

My work combines applied ML research with production engineering: model training, evaluation, inference optimization, data pipelines, CI/CD, testing, monitoring, and developer-facing documentation.

Currently, I work as a Machine Learning Engineer at Samsung Electronics, focusing on real-time ML systems, model optimization, synthetic data pipelines, and production deployment.

## Focus areas

- Production machine learning systems
- PyTorch and deep learning model development
- Hugging Face ecosystem: Transformers, Datasets, model inference workflows
- Cloud ML and MLOps with AWS, Docker, CI/CD, and monitoring
- Computer vision: OCR, pose estimation, face recognition, object detection
- Synthetic data generation and model evaluation
- LLM-powered automation and feedback analysis systems

## Selected projects

### OCR Dataset Generator
Synthetic OCR data generation pipeline for creating clean and degraded text images with word-level annotations.

Highlights:
- Generates synthetic text images and realistic degradation effects
- Supports noise, blur, resize, rotation, and filtering transformations
- Produces annotation files for model training and benchmarking
- Includes CLI tools, examples, tests, and visual previews

Repository: https://github.com/YuliaYur/ocr-dataset-generator

### OCR Engine
CRNN + CTC OCR for low-quality (noisy, blurred, skewed) document images, and the reference implementation behind two published papers. A training-free line-cutting algorithm lets a single-line recognizer read full multi-line pages, beating Tesseract and Google Cloud Vision on degraded text.

Highlights:
- ~0.02 relative Levenshtein distance vs 0.74 (Tesseract) and 0.19 (Google Cloud Vision)
- Novel line-cutting preprocessing: align the page, split into single-line crops, recognize each, merge
- Synthetic-to-real transfer learning cuts recognition error by ~32% on the SROIE dataset
- Unified KerasOCR/TesseractOCR interface, CLI train/evaluate, TensorBoard logging, and a GPU Dockerfile

Papers:
- *Development of a prototype of an optical text recognition system for low-quality images* — Visnyk of Lviv University (Applied Mathematics and Informatics), 2021: https://publications.lnu.edu.ua/bulletins/index.php/ami/article/view/11344
- *Enhancing OCR Model Training with Synthetic Data: A Case Study with the SROIE Dataset* — IEEE SIST 2024: https://ieeexplore.ieee.org/document/10629363

Repository: https://github.com/YuliaYur/ocr-engine

### Mask Detection
Computer vision research project for face/mask detection and image preprocessing experiments.

Highlights:
- Face detection and mask-detection experiments
- Docker-based project setup
- Research-oriented repository with model and preprocessing experiments

Repository: https://github.com/YuliaYur/mask-detection

## Professional experience

- Machine Learning Engineer at Samsung Electronics
- Former Machine Learning Engineer at Abto Software
- Led small ML teams delivering production AI systems
- Built LLM-powered customer feedback analysis, OCR systems, face recognition systems, pose estimation models, and synthetic data pipelines

## Tech stack

**Languages:** Python, SQL, C#  
**ML/DL:** PyTorch, TensorFlow, Hugging Face, scikit-learn, OpenCV, LangChain  
**MLOps & Cloud:** AWS, Docker, CI/CD, DVC, Git, Git LFS, monitoring, testing  
**Deployment:** ONNX, TFLite, real-time inference, edge/on-device ML  
**Domains:** Computer Vision, OCR, Pose Estimation, LLM Applications, Synthetic Data, Time-Series ML

## Education & research

- Master's degree in Applied Mathematics
- Bachelor's degree in Computer Science
- Research experience in OCR, synthetic data generation, and computer vision
- National-level programming olympiad winner and ICPC regional medalist

## Links

- LinkedIn: https://www.linkedin.com/in/yuliana-yurchenko
- GitHub: https://github.com/YuliaYur
