# Glaucoma Detection Using Deep Learning

This repository contains the code and pre-trained models for accurately detecting glaucoma from fundus images using deep learning techniques. The project aims to develop an automated system that can reliably screen for glaucoma and identify the presence of various glaucomatous features, thereby improving early detection and reducing the risk of preventable blindness.

## Project Overview

Glaucoma is a leading cause of irreversible blindness worldwide, and its asymptomatic nature in the early stages poses significant challenges for detection. The conventional diagnostic method, which involves analyzing fundus photographs, is labor-intensive and requires highly specialized expertise, often leading to variability in diagnosis.

To address this issue, we have developed a deep learning model that can accurately classify fundus images into 'referable glaucoma' and 'no referable glaucoma' cases. Additionally, our model can identify the presence of up to ten glaucomatous features in the fundus images, enabling a more comprehensive understanding of the disease progression.

## Features

- Binary classification of fundus images into 'referable glaucoma' and 'no referable glaucoma' cases.
- Multi-label classification to identify the presence of the following glaucomatous features:
 1. Appearance of neuroretinal rim superiorly (ANRS)
 2. Appearance of neuroretinal rim inferiorly (ANRI)
 3. Retinal nerve fiber layer defect superiorly (RNFLDS)
 4. Retinal nerve fiber layer defect inferiorly (RNFLDI)
 5. Baring of circumlinear vessel superiorly (BCLVS)
 6. Baring of circumlinear vessel inferiorly (BCLVI)
 7. Nasalisation of vessel trunk (NVT)
 8. Presence of disc hemorrhages (DH)
 9. Presence of laminar dots (LD)
 10. Large cup to disc ratio (LC)
- High accuracy and generalization performance achieved through ensemble techniques and transfer learning.

## Results

Our model achieved state-of-the-art performance on the Justified Referral in AI Glaucoma Screening (JustRAIGS) challenge dataset, with a sensitivity and specificity of over 80 percent for glaucoma detection and other features. These results demonstrate the potential of our approach to significantly improve the efficiency and reliability of glaucoma screening protocols worldwide.
