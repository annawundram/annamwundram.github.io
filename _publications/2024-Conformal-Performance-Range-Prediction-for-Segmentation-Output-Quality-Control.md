---
title: "Conformal Performance Range Prediction for Segmentation Output Quality Control"
collection: publications
type: conference
permalink: /publication/2024-Conformal-Performance-Range-Prediction-for-Segmentation-Output-Quality-Control
abstract: 'Recent works have introduced methods to estimate segmentation performance without ground truth, relying solely on neural network softmax outputs. These techniques hold potential for intuitive output quality control. However, such performance estimates rely on calibrated softmax outputs, which is often not the case in modern neural networks. Moreover, the estimates do not take into account inherent uncertainty in segmentation tasks. These limitations may render precise performance predictions unattainable, restricting the practical applicability of performance estimation methods. To address these challenges, we develop a novel approach for predicting performance ranges with statistical guarantees of containing the ground truth with a user specified probability. Our method leverages sampling-based segmentation uncertainty estimation to derive heuristic performance ranges, and applies split conformal prediction to transform these estimates into rigorous prediction ranges that meet the desired guarantees. We demonstrate our approach on the FIVES retinal vessel segmentation dataset and compare five commonly used sampling-based uncertainty estimation techniques. Our results show that it is possible to achieve the desired coverage with small prediction ranges, highlighting the potential of performance range prediction as a valuable tool for output quality control.'
date: 2024-01-01
venue: 'International Workshop on Uncertainty for Safe Utilization of Machine Learning in Medical Imaging (UNSURE) held in conjunction with MICCAI'
paperurl: '/files/paperUNSURE2024.pdf'
bibtexurl: '/files/bibtexUNSURE2024.bib'
figure: '/files/figureUNSURE2024.png'
video: 'https://youtu.be/jAmzPpllDXo?si=RnwqK46uDJFn9GqD'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
