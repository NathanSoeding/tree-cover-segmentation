# tree-cover-segmentation

The notebook includes all relevant code including:
1. Data import of 39 Goettingen images and TCD dataset (which is not used in the current version).
2. Vision transformer import of architecture and weights with the possibility to remove the NiR channel for processing RGB images (TCD dataset).
3. Training code including dice and BCE loss, IOU score, result plotting function and learning rate decay for training.
4. Baseline ResNext-50 model training and validation.
5. U-Net-Style Decoder for the Vision Transformer encoder architecture, training and validation.

To use the notebook install all dependencies and replace file paths (data and ViT weights). I trained on kaggle where all dependencies except "segmentation-models-pytorch" were already installed.
