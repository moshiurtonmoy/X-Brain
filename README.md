# X-Brain
Explainable Automated Recognition of Brain Tumors using Robust Deep Attention CNN

## Abstract
Automated brain tumor recognition is crucial for swift diagnosis and treatment in healthcare, enhancing patient survival rates but manual recognition of tumor types is time-consuming and resource intensive. Over the past few years, researchers have proposed various Deep Learning (DL) methods to automate the recognition process over the past years. However, these approaches often lack convincing accuracy and rely on datasets consisting of limited samples, raising concerns regarding real-world efficacy and reliability. Furthermore, the decisions made by black-box AI models in healthcare, where lives are at stake, require proper decision explainability. To address these issues, we propose a robust and explainable deep CNN-based method for effective recognition of brain tumor types, attaining state-of-the-art accuracies of 99.81%, 99.55%, and 99.30% on the training, validation, and test sets, respectively, surpassing both the previous works and baseline models. Moreover, we employed three Explainable AI techniques: Grad-CAM, Grad-CAM++, and Score-CAM for explainability analysis, contributing towards the development of trustworthy and reliable automation of healthcare diagnosis.

## Result Summary

| Dataset        | Accuracy       | Loss               |
|----------------|----------------|--------------------|
| **Train set**  | 0.9981         | 0.0589             |
| **Validation set** | 0.9955     | 0.0739             |
| **Test set**   | 0.9930         | 0.0763             |

### Class-wise Performance over the Test set                   
| Class        | Precision | Recall    | F1-Score  | Support |
|--------------|-----------|-----------|-----------|---------|
| **glioma**       | 0.994141  | 0.984526  | 0.989310  | 517     |
| **meningioma**   | 1.000000  | 0.989031  | 0.994485  | 547     |
| **no_tumor**     | 0.992352  | 1.000000  | 0.996161  | 519     |
| **pituitary**    | 0.985689  | 0.998188  | 0.991899  | 552     |
| **accuracy**     |           |           | 0.992974  | 2135    |
| **macro avg**    | 0.993045  | 0.992936  | 0.992964  | 2135    |
| **weighted avg** | 0.993022  | 0.992974  | 0.992971  | 2135    |

## XAI Visualization
<p align="center">
  <img src="XAI Viz/Glioma.jpg" alt="Glioma.jpg" width="400"/>
  <br>
  <b>Glioma</b>
</p>

<p align="center">
  <img src="XAI Viz/Meningioma.jpg" alt="Meningioma" width="400"/>
  <br>
  <b>Meningioma</b>
</p>

<p align="center">
  <img src="XAI Viz/No Tumor.jpg" alt="No Tumor" width="400"/>
  <br>
  <b>No Tumor</b>
</p>

<p align="center">
  <img src="XAI Viz/Pituitary.jpg" alt="Pituitary" width="400"/>
  <br>
  <b>Pituitary</b>
</p>

