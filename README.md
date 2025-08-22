
# Probalistic Machine Learning for 6G Signal Processing

This repository implements techniques for signal classification, channel estimation, and data detection using:
- **Automatic Differentiation Variational Inference (ADVI)** for Bayesian signal classification.
- **Support Vector Machines (SVM)** for robust channel estimation and data detection in one-bit massive MIMO systems.
- **Partitioned Variational Inference (PVI)** for decentralized probabilistic signal detection.

## Overview

1. **Signal Classification with ADVI**  
   ADVI simplifies Bayesian inference by approximating complex posterior distributions. Implemented within the **STAN** probabilistic programming framework, ADVI eliminates the need for manual derivations, making Bayesian signal classification accessible and efficient.

2. **Channel Estimation and Data Detection with SVM**  
   SVM provides a principled way to handle binary classification tasks, aligning well with the binary outputs of one-bit ADCs in massive MIMO systems. The method ensures robustness and computational efficiency in scenarios with severe nonlinearity and limited training data.

3. **Decentralized Signal Detection with PVI**  
   PVI is a framework for probabilistic federated learning, where a central server collaborates with multiple clients, each holding a unique subset of the data. Without sharing data among clients, each client updates the posterior distribution of the desired random variable on the server while incorporating the likelihood of its local data. This decentralized approach preserves data privacy and ensures efficient model training.


## Documentation (Slides)
- Comprehensive slides covering the methodology, results, and insights for all the signal signal pricessing techniques can be accessed [here](https://docs.google.com/presentation/d/1XpKIJMtW62KtcsYW3NGnZvqsax1RX4NIBo5sxioQXfE/edit?usp=sharing).

- Project report can be accessed [here](https://drive.google.com/file/d/1Ml763YsETAUe_bYRuMHIh21TjAG1Lpaj/view?usp=sharing).
- Project poster can be accessed [here](https://docs.google.com/presentation/d/1XpKIJMtW62KtcsYW3NGnZvqsax1RX4NIBo5sxioQXfE/edit?usp=sharing).

