---
title: StressNet-Deep learning to predict stress with fracture propagation in
  brittle materials
publication_types:
  - "2"
authors:
  - Yinan Wang
  - Diane Oyen
  - Weihong Grace Guo
  - Anishi Mehta
  - Cory Braker Scott
  - Nishant Panda
  - M Giselle Fernández-Godino
  - Gowri Srinivasan
  - Xiaowei Yue
doi: doi.org/10.1038/s41529-021-00151-y
publication: npj Materials Degradation
abstract: Catastrophic failure in brittle materials is often due to the rapid
  growth and coalescence of cracks aided by high internal stresses. Hence,
  accurate prediction of maximum internal stress is critical to predicting time
  to failure and improving the fracture resistance and reliability of materials.
  Existing high-fidelity methods, such as the Finite-Discrete Element Model
  (FDEM), are limited by their high computational cost. Therefore, to reduce
  computational cost while preserving accuracy, a deep learning model,
  StressNet, is proposed to predict the entire sequence of maximum internal
  stress based on fracture propagation and the initial stress data. More
  specifically, the Temporal Independent Convolutional Neural Network (TI-CNN)
  is designed to capture the spatial features of fractures like fracture path
  and spall regions, and the Bidirectional Long Short-term Memory (Bi-LSTM)
  Network is adapted to capture the temporal features. By fusing these features,
  the evolution in time of the maximum internal stress can be accurately
  predicted. Moreover, an adaptive loss function is designed by dynamically
  integrating the Mean Squared Error (MSE) and the Mean Absolute Percentage
  Error (MAPE), to reflect the fluctuations in maximum internal stress. After
  training, the proposed model is able to compute accurate multi-step
  predictions of maximum internal stress in approximately 20 seconds, as
  compared to the FDEM run time of 4 h, with an average MAPE of 2% relative to
  test data.
date: 2022-03-26T21:58:28.146Z
---
