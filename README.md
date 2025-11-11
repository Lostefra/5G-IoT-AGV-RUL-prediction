# 5G Architectures Enabling Remaining Useful Life Estimation for Industrial IoT: a Holistic Study

## Abstract

In the ever-evolving landscape of industrial connectivity, significant strides have been made in the integration of 5th generation (5G) cellular technology with Industrial Internet of Things (IIoT) systems. At the same time, data-driven analytics has become an effective tool for leveraging information from interconnected industrial devices, enabling organizations to gain valuable insights and make informed decisions. However, among these advancements, the holistic perspective of end-to-end analysis related to their integration remains a critical aspect that has yet to be comprehensively addressed. To this end, we investigate 5G IIoT network architectures that support automated guided vehicles (AGVs) on a factory floor as an illustrative example. In particular, we leverage real sensor data collected by AGVs to estimate their remaining useful life (RUL) using a deep learning (DL)-based pipeline. We conduct an in-depth analysis to assess the compatibility of 5G New Radio infrastructures with the aforementioned case study, focusing on round trip time (RTT) requirements and emphasizing the inter-dependencies between communication network and data-driven application.

### This repository contains code and data used in the paper "5G Architectures Enabling Remaining Useful Life Estimation for Industrial IoT: a Holistic Study", avilable at https://ieeexplore.ieee.org/document/10843389.

Detailed discussion about models and their hyper-parameters is available here: [deep_learning_models_analysis.pdf](https://github.com/Lostefra/5G-IoT-AGV-RUL-prediction/blob/main/deep_learning_models_analysis.pdf).

The results provided in the paper are also available [here](https://github.com/Lostefra/5G-IoT-AGV-RUL-prediction/blob/main/testing_summary_5.csv) and [here](https://github.com/Lostefra/5G_IoT_AGV_RUL_prediction/blob/main/testing_summary_10.csv).

### Dataset available on Kaggle: https://www.kaggle.com/datasets/lorenzoamorosa/5g-industrial-iot-for-remaining-useful-life

## If you find this work useful in your research, please consider citing:
```
@ARTICLE{LonghiAmorosa2025,
  author={Longhi, Nicolò and Amorosa, Lorenzo Mario and Cavallero, Sara and Buracchini, Enrico and Verdone, Roberto},
  journal={IEEE Open Journal of the Communications Society}, 
  title={5G Architectures Enabling Remaining Useful Life Estimation for Industrial IoT: A Holistic Study}, 
  year={2025},
  volume={6},
  number={},
  pages={1016-1029},
  keywords={5G mobile communication;Industrial Internet of Things;Pipelines;Estimation;Liquids;Training;Network architecture;Servers;Remotely guided vehicles;Predictive models;5G;5G new radio;automated guided vehicles;deep learning;industrial Internet of Things;remaining useful life;round trip time},
  doi={10.1109/OJCOMS.2025.3530094}}
```
