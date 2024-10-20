# X-Brain: Explainable Automated Recognition of Brain Tumors using Robust Deep Attention CNN
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <a target="_blank" href="https://colab.research.google.com/github/moshiurtonmoy/X-Brain/blob/master/X_Brain.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 
[![DOI:10.1016/j.bspc.2024.106988](https://zenodo.org/badge/DOI/10.1016/j.bspc.2024.106988.svg)](https://doi.org/10.1016/j.bspc.2024.106988) 
<hr/>

Automated brain tumor recognition is crucial for swift diagnosis and treatment in healthcare, enhancing patient survival rates but manual recognition of tumor types is time-consuming and resource intensive. Over the past few years, researchers have proposed various Deep Learning (DL) methods to automate the recognition process over the past years. However, these approaches often lack convincing accuracy and rely on datasets consisting of limited samples, raising concerns regarding real-world efficacy and reliability. Furthermore, the decisions made by black-box AI models in healthcare, where lives are at stake, require proper decision explainability. To address these issues, we propose a robust and explainable deep CNN-based method for effective recognition of brain tumor types, attaining state-of-the-art accuracies of 99.81%, 99.55%, and 99.30% on the training, validation, and test sets, respectively, surpassing both the previous works and baseline models. Moreover, we employed three Explainable AI techniques: Grad-CAM, Grad-CAM++, and Score-CAM for explainability analysis, contributing towards the development of trustworthy and reliable automation of healthcare diagnosis.

<ul>
  <li>The article has been published in <b><i>Biomedical Signal Processing and Control</i></b> and can be accessed from <a target='_blank' href="https://doi.org/10.1016/j.bspc.2024.106988"> here</a></li>
</ul>


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

<table>
  <tr>
    <td align="center">
      <img src="XAI Viz/Glioma.jpg" alt="Glioma.jpg" width="400"/>
      <br>
      <b>Glioma</b>
    </td>
    <td align="center">
      <img src="XAI Viz/Meningioma.jpg" alt="Meningioma" width="400"/>
      <br>
      <b>Meningioma</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="XAI Viz/No Tumor.jpg" alt="No Tumor" width="400"/>
      <br>
      <b>No Tumor</b>
    </td>
    <td align="center">
      <img src="XAI Viz/Pituitary.jpg" alt="Pituitary" width="400"/>
      <br>
      <b>Pituitary</b>
    </td>
  </tr>
</table>


## Citation
```
@article{TONMOY2025106988,
title = {X-Brain: Explainable recognition of brain tumors using robust deep attention CNN},
journal = {Biomedical Signal Processing and Control},
volume = {100},
pages = {106988},
year = {2025},
issn = {1746-8094},
doi = {https://doi.org/10.1016/j.bspc.2024.106988},
url = {https://www.sciencedirect.com/science/article/pii/S1746809424010462},
author = {Moshiur Rahman Tonmoy and Md. Atik Shams and Md. Akhtaruzzaman Adnan and M.F. Mridha and Mejdl Safran and Sultan Alfarhood and Dunren Che},
keywords = {Brain tumor, Medical imaging, XAI, Attention mechanism, Computer vision}
}
```
<hr/>
