# Imbalance Problems in Object Detection: A Review (Submitted to IJCV, arXiv: )

Here, we present the list of papers within the scope of imbalance problems in object detection by following our problem-based taxonomy (the numbers in the parenthesis indicates the section that the corresponding problem is discussed in the paper.):

![ProblemTaxonomy](assets/taxonomy.png)

# Class Imbalance

## Foreground-Backgorund Class Imbalance

**1.Hard Sampling Methods**  
    * Random Sampling  
    * Hard Example Mining  
        * Bootstraping  
        *- SSD*  
        *- Online Hard Example Mining*  
        *- IoU-based Sampling*  
    C.Limit Search Space  
        *- Two-stage Object Detectors*  
        *- IoU-lower Bound*  
        *- Objectness Prior*  
        *- Negative Anchor Filtering*  

**2.Soft Sampling Methods**  
        *- Focal Loss*  
        *- Gradient Harmonizing Mechanism*  
        *- Prime Sample Attention*  
        *- AP Loss*  
        *- DR Loss*  

**3.Generative Methods**  
        *-Adversarial Faster-RCNN*  
        *-Task Aware Data Synthesis*  
        *-PSIS*  
        *-Bounding Box Generator*  

## Foreground-Foreground Class Imbalance  
        *-Fine-tuning Long Tail Distribution for Obj.Det.*  
        *-PSIS*  
        *-OFB Sampling*

# Scale Imbalance

## Object/box-level Scale Imbalance

**1.Methods Predicting from the Feature Hierarchy of Backbone Features**
		*-Scale-dependent Pooling*
        *-SSD*
        *-Multi Scale CNN*
        *-Scale Aware Fast R-CNN*

**2.Methods Based on Feature Pyramids**
        *-FPN*
        *-See feature-level imbalance methods*

**3.Methods Based on Image Pyramids**
        *-SNIP*
        *-SNIPER*

**4.Methods Combining Image and Feature Pyramids**
        *-Scale Aware Trident Network*

## Feature-level Imbalance
**1.Methods Using Pyramidal Features as a Basis**
		*-PANet*
        *-Libra FPN*

**2.Methods Using Backbone Features as a Basis**
		*-STDN*
        *-Parallel-FPN*
        *-Deep Feature Pyramid Reconf.*
        *-Zoom Out-and-In*
        *-Multi-level FPN*
        *-NAS-FPN*
        *-Det-NAS*

# Spatial Imbalance

## Imbalance in Regression Loss
**1.$Lp$ norm based**
    	*-Smooth L1*
        *-Balanced L1*
        *-KL Loss*
        *-Gradient Harmonizing Mechanism*

**2.IoU based**
		*-IoU Loss*
        *-Bounded IoU Loss*
        *-GIoU Loss*
       
## IoU Distribution Imbalance
		*-Cascade R-CNN*

## Object Location Imbalance
		*-Guided Anchoring \citep{GuidedAnchoring}*

# Objective Imbalance
       
		*-Task Weighting*
		*-Classification Aware Regression Loss*
		