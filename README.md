# Face-Recognition

Trained a face recognition model, as part of my University Honours Thesis, to identify victims/attackers in a group photo for big data digital forensics. The model detects a face in a group photo and simultaneously collects facial features to identify if a person is a victim or an attacker. 
The model successfully detected faces from side profiles, with facial obstructions (glasses, masks) and in low lighting conditions. 
The model requires further work to extract personality traits on the victim/attacker

![MyModel](https://github.com/Ihlaam/Face-Recognition/assets/47963182/1f113c45-c0ad-49c7-90db-b36be32791a1)

- Model: MTCNN on Tensorflow 2.6
- Training data: MS1M-ArcFace dataset, converted to a TFRecord using L_Resnet50_E_IR architecture.
- Testing data: Labeled Faces in the Wild (LFW), Celebrities in Frontal-Profile in the Wild (CFP) and AgeDB
- Discussion, results and model can be found here: https://drive.google.com/drive/folders/1UFgWYwDEWvsYxOQ-gk-YuP1WCWxCoj_e?usp=sharing
  
