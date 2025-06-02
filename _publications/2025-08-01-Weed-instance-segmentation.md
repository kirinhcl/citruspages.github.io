---
title: "Weed instance segmentation from UAV Orthomosaic Images based on Deep Learning"
collection: publications
category: manuscripts
permalink: /publication/2025-08-01-Weed-instance-segmentation
excerpt: 'This study uniquely integrated Real-ESRGAN Super-Resolution (SR) for UAV image enhancement and the Segment Anything Model (SAM) for semi-automatic annotation. '
date: 2025-08-01
venue: 'Smart Agricultural Technology'
paperurl: 'http://citruspages.github.io/files/paper2.pdf'
citation: 'Lu, C., Gehring, K., Kopfinger, S., Bernhardt, H., Beck, M., Walther, S., Ebertseder, T., Minceva, M., Hu, Y. and Yu, K., 2025. Weed Instance Segmentation from UAV Orthomosaic Images based on Deep Learning. Smart Agricultural Technology, p.100966.'
---

Weeds significantly impact agricultural production, and traditional weed control methods often harm soil health and environment. This study aimed to develop deep learning-based segmentation models in identifying weeds in potato fields captured by Unmanned Aerial Vehicle (UAV) orthophotos and to explore the effects of weeds on potato yield. Previous studies predominantly employed U-Net for weed segmentation, but its performance often declines under complex field environments and low-image resolution conditions. Some studies attempted to overcome this limitation by reducing flight altitude or using high-cost cameras, but these approaches are not always practical. To address these challenges, this study uniquely integrated Real-ESRGAN Super-Resolution (SR) for UAV image enhancement and the Segment Anything Model (SAM) for semi-automatic annotation. Subsequently, we trained the YOLOv8 and Mask R-CNN models for segmentation. Results showed that the detection accuracy mAP50 scores were 0.902 and 0.920 for YOLOv8 and Mask R-CNN, respectively. Real-ESRGAN reconstruction slightly improved accuracy. When multiple weed types were present, accuracy generally decreased. The YOLOv8 model characterized plant and weed coverage areas could explained 41.2 % of potato yield variations (R2 = 0.412, p-value = 0.01), underscoring the practical utility of UAV-based segmentation for yield estimation. Both YOLOv8 and Mask R-CNN achieved high accuracy, with YOLOv8 converging faster. While different nitrogen fertilizer treatments had no significant effect on yield, weed control treatments significantly impacted yield, highlighting the importance of precise weed mapping for spot-specific weed management. This study provides insights into weed segmentation using Deep Leaning and contributes to environmentally friendly precision weed control.
