# Game-Based Cognitive Assessment for Early Dementia Detection

This work introduces a gaming approach inspired by deep learning for the early detection of dementia. This research employs a convolutional neural network (CNN) model to analyze health metrics and facial images via a cognitive assessment gaming application. We have collected 1000 samples of health metric data from Apollo Diagnostic Center and hospitals, labeled “demented” or “nondemented,” to train a modified 1-dimensional convolutional neural network (MOD-1D-CNN) for game level 1. Additionally, a dataset of 1800 facial images, also labeled  “demented” or “non-demented,” is collected in our work to train a modified 2-dimensional convolutional neural network (MOD-2D-CNN) for game level 2. The MOD-1D-CNN has achieved a loss of 0.2692 and an accuracy of 70.50% in identifying dementia traits via health metric data; in comparison, the MOD-2D-CNN has achieved a loss of 0.1755 and an accuracy of 95.72% in distinguishing dementia from facial images. A rule-based linear weightage method combines these models and provides a final decision.

# Reference

https://www.sciencedirect.com/science/article/pii/S0952197624020608?casa_token=de9XGrF19tIAAAAA:U8UuI1miBjjgBYuExz-t_1otpwL3t2PeZeF7jdBB2hY8u7Dqh5TGKFwiEBCsV6VadPcBFd0IKdc

# Citation
@article{maji2025deep,
  title={Deep learning inspired game-based cognitive assessment for early dementia detection},
  author={Maji, Paramita Kundu and Acharya, Soubhik and Paul, Priti and Chakraborty, Sanjay and Basu, Saikat},
  journal={Engineering Applications of Artificial Intelligence},
  volume={142},
  pages={109901},
  year={2025},
  publisher={Elsevier}
}
