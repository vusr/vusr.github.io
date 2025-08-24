---
layout: default
title: Uday Vysyaraju
---

<br>
**📚  Master of Science in Data Science** &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; *Aug 2023 – May 2025*  
&emsp; *Texas A&M University, College Station, Texas*  
&emsp; **CGPA 4.0 / 4.0**

**📚  Bachelor & Master of Technology, Electronics**  &emsp; *Jul 2013 – Jul 2018*  
&emsp; *Indian Institute of Technology, Kharagpur*  
&emsp; **CGPA 8.6 / 10.0**  <br><br><br>
  
<h2 style="color: gray;">Projects</h2>
### 🖥️  Vision-Language & Multimodal AI for Strep Throat (StrepApp)  
> - Designed and trained CNN models for strep throat classification, leveraging data augmentation, Optuna hyperparameter optimization, and Grad-CAM visualization for model interpretability.
> - Integrated vision-language models (Llama 4, Gemma 3) to automate image quality assessment and extract visual features from smartphone-captured throat images.
> - Developing <a href="https://www.auscultechdx.com/technology" target="_blank" style="text-decoration: underline;">StrepApp</a> for Android with an AutoCapture feature, combining object detection, tracking, and custom algorithms to capture throat anatomy efficiently.
> - Optimized on-device inference performance, reducing detection latency from 200ms to 40ms by implementing TensorFlow Lite runtime with GPU acceleration.
> - Delivering an end-to-end healthcare AI solution, transitioning from model research to production-ready deployment in a real-world medical application.

### 🖥️  Respiratory Disease Detection in Cattle through Activity Analysis 
> - Developed a computer vision system to detect early signs of Bovine Respiratory Disease (BRD) by analyzing cattle activities (standing, lying, walking, feeding, drinking) from video footage.
> - Built datasets for segmentation, activity recognition, and cattle identification; achieved 89.8 mAP (YOLOv8) for segmentation, 99.7% accuracy (YOLOv11) for identification, and 95.3% accuracy in activity classification.
> - Designed an automated health monitoring pipeline that generates activity profiles for each animal, enabling early disease prediction and reducing reliance on manual observation.
> - Deployed a multi-camera data collection system across four feedlot pens for large-scale testing and future model expansion.
> - Recognized through conference presentations (<a href="https://www.aai.msstate.edu/2025-ai-ag-conference" target="_blank" style="text-decoration: underline;">AI in Agriculture 2025</a>, <a href="https://enreec.unl.edu/2025usplf-lincoln/" target="_blank" style="text-decoration: underline;">U.S. Precision Livestock Farming 2025</a>) and an upcoming journal publication.

### 🖥️  Rapid Damage Probability Estimation Through Social Media (NLP + Geolocation)
> - Built a BERT-based multi-label classification system to analyze geolocated tweets during hurricanes, identifying disaster outcomes such as structural damage and eligibility for assistance.
> - Achieved 92% accuracy and 91% F1-score on test data from three major hurricanes by aligning model predictions with FEMA ground-truth survey benchmarks.
> - Designed an incremental, real-time damage prediction pipeline that aggregates results at the ZIP code level, offering faster and broader disaster impact assessments than traditional methods.
> - Released the curated dataset publicly via <a href="https://data.griidc.org/data/O1.x158.000:0003" target="_blank" style="text-decoration: underline;">GRIIDC</a> and prepared findings for journal publication.

### 🖥️  Remote Sensing in Agriculture: Yield Prediction & Field Boundary Detection
> - Corn Yield Prediction – Designed a deep learning framework combining multispectral satellite imagery, plant age, and nitrogen treatments to estimate corn yield per acre. Achieved top-4 finish in the MLCAS 2024 Challenge and delivered an oral presentation at IPPS 2024.
> - Cotton Field Detection – Built a CNN-based classification model on Sentinel-2 imagery + NOAA weather data, detecting cotton fields with 83% accuracy and 75.9% F1-score. Secured 2nd place at the Texas A&M Datathon 2024.
> - Winter Wheat Field Detection – Developed a lightweight segmentation model using multispectral imagery and proxy labels, achieving 95.7% accuracy and 87.3% F1-score, demonstrating scalable crop boundary detection for regions lacking labeled data.

### 🖥️  X-ray Object Detection
> - Improved medical X-ray object detection accuracy by generating synthetic cross-domain images using GANs and applying multi-scale training (SNIPER).
> - Replaced batch normalization with switch normalization, boosting baseline mAP from 90 → 97.

### 🖥️  Defect Detection in Display Panels (LG Display)
> - Built an image segmentation system to automatically detect defects in display panels.
> - Delivered a scalable solution for manufacturing quality control, reducing manual inspection effort.

### 🖥️  Smart CCTV System
> - Developed a real-time surveillance system for people counting and loitering detection with support for RTSP streaming and multi-channel video processing.
> - Implemented object detection & tracking pipelines and containerized deployment with Docker.
> - Benchmarked multiple detection/tracking models, achieving higher accuracy in detecting small/occluded persons.

### 🖥️  AI-Based Analog and Digital Meter Reading
> - Designed an AI pipeline to automatically extract readings from analog and digital utility meters.
> - Applied data augmentation, custom datasets, and CNNs, raising accuracy to 85% from baseline.

### 🖥️  Versatile Object Detection System
> - Implemented a customizable object detection system using EfficientDet, adaptable across domains.
> - Deployed as part of a deep learning vision inspection service, enabling rapid prototyping of detection use cases.

### 🖥️  Smart Retail Store with Automatic Checkout
> - Built a product recognition system for retail checkout automation with few-shot learning techniques.
> - Enhanced accuracy by combining synthetic datasets with image processing methods (background elimination, foreground detection, SIFT, SURF feature matching).

<br><br>
<h2 style="color: gray;">Hackathons & Workshop Presentations</h2>
<h3 style="margin-bottom: 2px;">
    🏅 <a href="https://tamu-datathon.devpost.com/" target="_blank" style="text-decoration: underline;">TAMU Datathon AgriTech Challenge</a>
</h3>
<h3 style="margin-bottom: 2px;">&emsp; (Cotton Field Detector, 2nd place)</h3>
&emsp; &nbsp; *Nov 2024*  
- Designed a CNN-based tool to identify cotton fields within 24 hours, using multi-spectral satellite imagery and weather data.
- Achieved 83% accuracy and 76% F1 score.
- Presented the poster at the <ins>[TAMU Beef Sustainability Summit 2024](https://livestock-sustainability.com/summit/)</ins>.

<h3 style="margin-bottom: 2px;">
    🏅 <a href="https://2024.mlcas.site/" target="_blank" style="text-decoration: underline;">MLCAS</a> 
    <a href="https://eval.ai/web/challenges/challenge-page/2332/overview" target="_blank" style="text-decoration: underline;">Corn Yield Prediction Challenge</a> (4th place)
</h3>
&emsp; &nbsp; *Aug 2024*
- Predicted corn yield using a multi-modal CNN model applied to satellite imagery, incorporating vegetation indices calculated from multiple image bands. (<ins>[github](https://github.com/deregina/Agriculture_competition)</ins>)

<h3 style="margin-bottom: 2px;">🏅  American Airlines Hackathon (2nd place)</h3>
&emsp; &nbsp; *Feb 2024*  
- Applied collaborative filtering techniques to predict customer destination preferences by analyzing search and booking histories of users with similar behavior.  

<br><br>
<h2 style="color: gray;">Scholarships</h2>
- **🎓  Computer Science Department 1000$ Scholarship, Texas A&M University** (*Aug 2023 – May 2024*)  
- **🎓  Maerit Cum Means Scholarship, IIT Kharagpur** (*Jul 2013 - Jul 2017*)  

<br><br>
<h2 style="color: gray;">Employment</h2>
### 💼  Senior R&D Engineer  
> **AusculTech DX, Silver Spring, Maryland (Health Care Company)**  
> *Jul 2025 – Present*  
> - **Vision-Language & Multimodal AI** – Applied models like Llama 4, Gemma 3, and CNNs for medical image quality assessment and strep throat classification, with techniques such as augmentation, hyperparameter tuning (Optuna), and Grad-CAM visualization.
> - **Mobile AI Deployment** – Optimized TensorFlow Lite inference on Android, reducing model latency from 200ms to 40ms using GPU acceleration, and implemented object detection & tracking for real-time automatic image capture.
> - **End-to-End Product Development** – Built and deployed production-ready healthcare AI solutions, integrating research models into the <a href="https://www.auscultechdx.com/technology" target="_blank" style="text-decoration: underline;">StrepApp</a> Android application used in real-world medical settings.

### 💼  AI Researcher  
> **LG CNS, Seoul, South Korea**  
> *Aug 2018 – Sep 2022*
> - **Deep Learning for Computer Vision** – Expertise in object detection, segmentation, tracking, and classification using models like YOLO, EfficientDet, and custom CNNs.
> - **Model Optimization** – Experience improving accuracy through normalization techniques, multi-scale training, synthetic data generation (GANs), and advanced augmentation.
> - **End-to-End AI Systems** – Built and deployed full pipelines including preprocessing, model training, inference, evaluation, and optimization for real-world applications.
> - **Deployment & Scalability** – Hands-on experience with Docker, RTSP streaming, and multi-channel video systems for scalable AI deployment.
> - **Domain Adaptation** – Applied cross-domain datasets, transfer learning, and few-shot learning to handle limited or imbalanced data.
> - **Industry Applications** – Delivered AI solutions for X-ray screening, manufacturing defect detection, smart surveillance, retail checkout automation, and utility meter reading.Authored reports on profit analysis and operational issues for SK Group’s senior management, providing key insights for strategic decision-making. 

<br><br>
<h2 style="color: gray;">Skills</h2>
<h3 style="margin-bottom: 2px;">🌟  Programming Languages & Tools</h3>
&emsp; &nbsp; Python, C, C++, Kotlin, Matlab, Git, Docker  

<h3 style="margin-bottom: 2px;">🌟  Machine Learning & Data Science  </h3>
&emsp; &nbsp; Deep learning (PyTorch, TensorFlow), reinforcement learning, optuna, 
&emsp; &nbsp; large language models, vision language models, computer vision,  
&emsp; &nbsp; data visualization (QGIS, GeoPandas, Matplotlib, Seaborn, Plotly)  

<h3 style="margin-bottom: 2px;">🌟  Databases & Web Development  </h3>
&emsp; &nbsp; RDBMS (MySQL, PostgreSQL, MongoDB), web development (Gradio)  

---

