## General Explanation:
General descriptions of notebooks are provided here. For more details, read notebook codes.


## Q1
Q1 notebook aims to Fine-tune AlexNet on Cifar10 dataset. Novelity is using Triplet loss. In first section, we just use cross-entropy; In the next section we replace it with triplet loss. In the last section we use a combination of both to train the network and get 98.6% accuracy.

## Q2
Q2 notebook compares deformable convolutions and normal covolutions and try to prove deformable convolutions advantages. The used dataset is COCO. For more details about them, read https://arxiv.org/abs/1703.06211


Paper Abstract:

Convolutional neural networks (CNNs) are inherently limited to model geometric transformations due to the fixed geometric structures in its building modules. In this work, we introduce two new modules to enhance the transformation modeling capacity of CNNs, namely, deformable convolution and deformable RoI pooling. Both are based on the idea of augmenting the spatial sampling locations in the modules with additional offsets and learning the offsets from target tasks, without additional supervision. The new modules can readily replace their plain counterparts in existing CNNs and can be easily trained end-to-end by standard back-propagation, giving rise to deformable convolutional networks. Extensive experiments validate the effectiveness of our approach on sophisticated vision tasks of object detection and semantic segmentation. The code would be released.

