# PyTorch Blueprint

Explore PyTorch projects with ease.

This PyTorch Blueprint offers a comprehensive structure for your PyTorch projects, including samples in key areas such as Image Segmentation, Object Classification, Generative Adversarial Networks, and Reinforcement Learning.

Working with deep learning projects often leaves little room for organizational or modular code considerations. After encountering numerous challenges regarding file organization and code duplication across various projects, we've designed a modular framework to suit any PyTorch endeavor. This template serves as a foundation for the community to extend and customize.

Creators: Sergei

## Contents

- **Overview**
- **Motivation**
- **How-to Guides**
- **Contributing**
- **Architecture Overview**
- **Referenced Examples**
- **Migration Guide**
- **Project Structure**
- **Dependencies**
- **Planned Extensions**
- **License**

## Overview

Our template provides a starting point for PyTorch projects, streamlining your focus towards model implementation. The key features include:

- A scalable project structure with dedicated templates for modular coding.
- A configuration file that manages all hyper-parameters for specific problems.
- Embedded examples for a variety of challenges, each operable with a simple change in the configuration file.
- Step-by-step tutorials to jumpstart your project.

## How-to Guides

To facilitate your project initiation:

- **Basic Setup Guide**: Steps to configure the environment and start your project.
- **Mnist Case Study**: Adapt an existing neural network model to fit within our structured template.

## Contributing

This template is meant to be a hub for various PyTorch models. Contributions that expand or enhance the collection of models are highly encouraged. We welcome all forms of contributions, including new models and discussions on improving the design patterns used.

## Architecture Overview

Refer to the included architecture diagram for a visual representation of the class hierarchy and module organization.

## Referenced Examples

- **Semantic Segmentation with ERFNet**: Trained on Pascal Voc dataset.
- **DCGAN**: Deep Convolutional GANs, applied to the CelebA dataset.
- **CondenseNet for Image Classification**: Utilizing the Cifar10 dataset.
- **DQN Reinforcement Learning**: Implemented on the CartPole-V0 environment.
- **RecAE Time Series Anomaly Detection**: Applied to ECG5000 dataset.

## Migration Guide

We began with the implementation of DCGAN, and progressively integrated additional projects, ensuring the architecture supports various model types and data structures.

## Project Structure

Our repository is organized as follows to ensure clarity and modularity:

```
repository
├── agents
├── configs
├── data
├── datasets
├── experiments
├── graphs
│   ├── models
│   └── losses
├── pretrained_weights
├── tutorials
└── utils
├── main.py
└── run.sh
```

## Dependencies

List of essential libraries required to run the templates smoothly:

- numpy
- torch
- torchvision
- matplotlib
- and others

## Planned Extensions

We aim to further enrich the template with cutting-edge models and architectures, including MobilenetV2 and more.

## License

The project is released under the MIT License. See the LICENSE file for more details.
