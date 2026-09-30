# Learning-based Visual Saliency Prediction

This repo contains my university project for the Neural Network and Deep Learning course. The project explores visual saliency prediction using convolutional neural networks, with a focus on comparing different model architectures and training configurations.

Visual saliency prediction aims to estimate which regions of an image are likely to attract human visual attention. Given an input image, a model produces a saliency map that assigns higher values to regions predicted to receive more attention.

This repo includes experiments with single-stream and multi-level ResNet-18 architectures, together with notebooks for testing the models and visualizing their predictions.

### Workflow

The work starts with the exploration and preparation of the SALICON dataset. Model development and hyperparameter tuning are followed by training and evaluation. Predicted saliency maps are then inspected alongside the reference maps to examine the models’ behavior and identify their limitations.

### Repository contents

SSresnet18_tuning.ipynb and SSresnet18_training.ipynb contain the tuning and training experiments for the single-stream model.

MLresnet18_tuning.ipynb and MLresnet18_training.ipynb contain the corresponding experiments for the multi-level model.

Saliency_prediction.ipynb and Saliency_testing.ipynb contain notebooks related to saliency prediction and model testing.

NNDL_report.pdf provides the accompanying final project report.

### References

W. Wang and J. Shen. “Deep Visual Attention Prediction.” IEEE Transactions on Image Processing, 27(5), 2368–2378, 2018. DOI: 10.1109/TIP.2017.2787612.

M. Jiang et al. “SALICON: Saliency in Context.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2015.
