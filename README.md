# One-shot-Siamese-Signature-Verification
This repository showcases a one-shot Siamese signature verification model.
The model uses a pretrained ResNet18 as the feature extractor which is fed into a Siamese Network. The model uses constrastive loss during its training. The distance function used is Euclidean distance. The model saves the reference image in its embedded form to reduce security risk. The reference image is then used as comparison when determining whether the new signature is a forged or genuine signature.

The source dataset can be downloade through this link https://www.kaggle.com/datasets/shreelakshmigp/cedardataset/data
