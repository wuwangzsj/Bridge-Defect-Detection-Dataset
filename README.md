# 🏗️ Bridge Defect Detection Dataset
This repository provides an optimized and re-annotated Bridge Defect Detection Dataset developed by the Institute of Marine Geotechnics, School of Civil Engineering and Architecture, Hainan University.
🔍 Background
However, a large portion of the raw image samples in GYU-DET were redundant, low-quality, or unsuitable for effective bridge defect detection.
To address this, we conducted a rigorous filtering and re-annotation process to improve image quality, consistency, and usability.
Display of invalid images (these may affect the results)：


In addition to the GYU-DET source, we integrated two publicly available datasets (Dataset A and Dataset B) as complementary data sources.
A：
B：
All valid images were re-screened, relabeled, and unified under a consistent annotation standard.
The final annotation results are illustrated as follows:



🧾 Categories
The dataset currently includes four main defect types:
0: Reinforcement exposure  
1: Spalling  
2: Honeycomb voids  
3: Crack

While some researchers include Efflorescence as an additional category, our analysis shows that it contributes little to model performance.
Nevertheless, we plan to add optional Efflorescence samples in future updates to support more diverse experimental needs.

🧠 Annotation and Format
All data have been provided in both JSON and YOLO annotation formats, allowing researchers to conveniently use the dataset across different deep learning frameworks.
Each image has been quality-checked and re-labeled to ensure reliable defect localization and class balance.

🤝 Collaboration and Open Sharing
We encourage more researchers to contribute their bridge inspection data to enrich this open resource.
Our goal is to build a comprehensive and community-driven dataset for advancing intelligent infrastructure inspection.
All valuable contributions will be integrated and shared openly through this repository.

Contact For collaboration or questions,
please contact: Shangjun Zhao PhD Student, Hainan University 
Email: zhaoshangjun@foxmail.com
