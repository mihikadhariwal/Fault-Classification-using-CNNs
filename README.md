# Fault-Classification-using-CNNs

This project aims to address the crucial requirement for an efficient and accurate fault detection and classification system in transmission lines, by using deep learning. The goal of this project is to overcome the challenges of timely fault identification and categorization, enhance the reliability and resilience of power grids, minimize downtime and optimize maintenance efforts.

The approach involves training a neural network (VGG16 like architecture) on heatmaps generated from the raw signal data, i.e., R, Y, B phase voltage signals

**Types of Faults:**
Line-to-ground (RG, YG, BG)
Line-to-line (RY, YB, RB)
Double line to ground (RYG, YBG, RBG)
Triple line (RYB)
Triple line to ground (RYBG) 
