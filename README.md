# brain-tumor-detection-yolov10
Real-time brain tumor detection on MRI scans using YOLOv10-MobileNetV3

Dataset 1 (Roboflow): https://app.roboflow.com/computer-vision-by-mehedi/brain-tumour-detection-mri/models/brain-tumour-detection-mri/1
Dataset 2 (Figshare):https://app.roboflow.com/computer-vision-by-mehedi/brain-tumor-detection-mri-6677c/4

# 🧠 NeuroYOLO: A Robust Tailored Model for Real-Time Brain Tumor Detection in MRI Data

**Author:** Md. Mehedi Hasan  
**Affiliation:** Lecturer in the department of Computer science and engineering at Global Institute of Information Technology.  
**Contact:** mehedi.hasan.ict@mbstu.ac.bd  
**Status:** Submitted for publication to Elsevier journal (under review).

---

## 📝 Abstract

Timely and precise brain tumor detection is crucial for improving patient survival rates and treatment efficacy. This study introduces **Neurological You Only Look Once (NeuroYOLO)**, a novel real-time detection framework that enhances the YOLOv10 architecture with **MobileNetV3** for high-accuracy brain tumor identification in **Magnetic Resonance Imaging (MRI)** scans.

Unlike conventional deep learning models, **NeuroYOLO** is tailored for real-time clinical applications, balancing **computational efficiency** and **detection precision**. The model is trained on two publicly available datasets:

- **Dataset One:** 1,008 MRI images (Brain Tumor vs Eye)
- **Dataset Two:** 3,064 MRI images (Glioma, Meningioma, Pituitary Tumor), converted from `.mat` to `.jpg` and annotated using **Roboflow**

Benchmarking against YOLOv7, YOLOv8, and baseline YOLOv10 demonstrates that **NeuroYOLO outperforms existing models**, achieving:
- **mAP50**: 97.20% (Dataset One), 96% (Dataset Two)
- **mAP50-95**: 86.40% (Dataset Two)
- **Real-time inference**: 3.1 ms (Dataset One), 7.9 ms (Dataset Two)
- **Precision / Recall**: 91.20% / 100% (multi-class tumor detection)

⚠️ Eye class accuracy slightly lower (81%–91%) due to limited training samples.

---

