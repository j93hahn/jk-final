# jk-final
Final Project for CMSC 25040: Introduction to Computer Vision focused on DETR.

# Objective:

DETR is an object detection architecture consisting of a joint Convolutional Neural Network (CNN) and Transformer with a feed-forward network as a head.  The Transformer component is responsible for reasoning about object relations using the multi-head attention mechanism, given features extracted by the CNN. Compared with other object detectors, DETR effectively replaces hand-designed components, such as region proposals, non-maximum suppression, or anchor generation, that explicitly encode possible object locations in the image


(1) Implement new dataloaders to process the chosen dataset other than COCO.

(2) Adapt the DETR structure to the classes for your dataset.

(3) Modify training/testing/visualization/analysis codes and fine-tune the system for your detection task



# Resources

- https://arxiv.org/pdf/2005.12872.pdf
- https://www.kaggle.com/c/global-wheat-detection/data
- https://github.com/facebookresearch/detr
