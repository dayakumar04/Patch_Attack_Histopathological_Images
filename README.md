# Patch_Attack_Histopathological_Images
This repository contains code for generating a multi-patch attack for histopathological images. 
### Description 
This work demonstrates the feasibility of designing adversarial patch attacks for histopathological images. The efficacy of the proposed approach is demonstrated by the observed reduction in the accuracy of the CNN model. Such reductions can have significant implications for safety-critical applications in pathology and healthcare. Furthermore, the utilization of multiple patches over a single patch is shown to be an effective mechanism for designing imperceptible attacks targeted toward histopathological images. To enhance the naturalistic appearance of the patch, constraints on the initial patch color and the incorporation of image morphing techniques are also found to be effective. The choice of kernel size during image morphing emerges as a significant factor in the effectiveness of the proposed approach. Specifically, smaller kernel sizes correspond to imperceptible patches but poor adversarial accuracy, while larger kernel sizes lead to visible distortions in the original image but result in an effective adversarial attack.
### Dataset
The datatset used is open-souce. Link - https://www.kaggle.com/competitions/histopathologic-cancer-detection.

### File Description 
1. The `main.py` file contains the primary code for baseline model training, patch training, and experiments with image morphing. 
2. `mask.jpg` is the mask used for patch training. 
3. `weights.pt` is the saved weights for the baseline CNN model. 


