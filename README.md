# EPIC_KITCHEN_IRM
    Invariant Risk Minimization [1] on EPIC KITCHEN [2] ResNet 50 Features 

## Dataset
    EPIC dataset consist of action annotated videos. 
    Two labels Verb and Nound are provided along with the video annotated segments.
    
    Features are extracted of this video chunks and stored in npy files consisting of 2050 dimensional data point for each instances in EPIC dataset 
    (2048 for ResNet50 features pretrained over EPIC with additional verb and class fc as in [3], 
    one for verb class label, 
    and finally one for noun class label). 
    To be considered, only output of feature layer (and not logits of fcs) are considered here.
    
    Features and annotation files can be downloaded from [4] 

[1] Arjovsky, M., Bottou, L., Gulrajani, I. and Lopez-Paz, D., 2019. Invariant risk minimization. arXiv preprint arXiv:1907.02893.

[2] https://epic-kitchens.github.io/2020

[3] https://github.com/shaanrockz/EPIC_KITCHENS

[4] https://drive.google.com/drive/folders/1ffEi7I-ipR_Enhhf96v0Sy8Y0Bw-xWdf?usp=sharing
