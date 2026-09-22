# Multimodal-Object-Identification-Wearable-Glove
A multimodal wearable system for non-visual material recognition using tactile, conductivity, and olfactory sensing with deep learning and multimodal sensor fusion.

# Overview

Conventional object recognition systems rely heavily on visual information and can become unreliable in low-visibility environments such as darkness, smoke, fog, and clutter.
This project develops a wearable multimodal sensing system that combines complementary information from: Tactile sensing, Conductivity sensing, Olfactory sensing
The collected sensor signals are processed and combined using deep learning to support real-time material identification.

# Problem Statement:

Develop a multimodal sensing and deep learning framework capable of identifying materials in real time using tactile, conductivity, and olfactory sensor signals while addressing environmental variability, sensor drift, and modality-specific limitations.

# Objectives:
1. Design and develop a wearable multimodal sensing system using tactile, conductivity, and olfactory sensors.
2. Collect and analyze multimodal sensor data under different interaction and environmental conditions.
3. Preprocess sensor signals and extract meaningful statistical and physics-based features.
4. Implement CNN–BiLSTM models to learn spatial and temporal characteristics from sensor data.
5. Develop multimodal fusion techniques and evaluate unimodal, bimodal, and trimodal approaches.
6. Deploy the recognition framework on the ESP32-S3 platform.

# System Architecture

The overall workflow is:

Tactile Sensors ───────┐
                       
                       
Conductivity Sensors ──┼──>   Sensor Data Acquisition
                       
                                     
Olfactory Sensor ──────┘             
                                   
                                      
                                      ↓

                              Data Synchronization
                              
                                      ↓
                                      
                                Preprocessing
                                
                                      ↓
                                      
                             Feature Extraction
                             
                                      ↓
                                      
                              CNN–BiLSTM Learning
                              
                                      ↓
                                      
                              Multimodal Fusion
                              
                                      ↓
                                      
                             Material Classification
                             
                                      ↓
                                      
                              Real-Time Prediction

# Hardware

ESP32-S3, Tactile sensors, Conductivity sensors, Olfactory sensing using BME688

# Software

The project uses a deep-learning-based multimodal recognition framework involving:
CNN, BiLSTM, Multimodal sensor fusion,Feature extraction, Time-series sensor signal processing, The CNN–BiLSTM framework is used to learn spatial and temporal characteristics from multimodal sensor signals.

# Sensor Modalities

Tactile Sensing: Captures pressure-related interaction patterns and physical characteristics of materials.

Conductivity Sensing: Captures electrical characteristics of material surfaces.

Olfactory Sensing: Captures gas-related information associated with different materials.

# Processing Pipeline

Sensor data acquisition
Data synchronization
Modality-specific preprocessing
Temporal segmentation
Feature extraction
Unimodal learning
Bimodal and trimodal fusion
Performance evaluation
Real-time material prediction
Evaluation

The system is evaluated using standard classification metrics:
Accuracy
Precision
Recall
F1-score
Confusion Matrix

# Applications

Potential applications include: Assistive technology, Low-visibility environments, Intelligent wearables, Industrial material sorting, Robotics, Human–machine interaction, Search and rescue environments

Project Documentation: The repository contains project documentation, system architecture, selected results, and demonstration images.
The source code and dataset are not included in this repository.



# Institution
Amrita Vishwa Vidyapeetham, Bengaluru
B.Tech Final Year Project — 2025–2026
