# openvla-libero-project-
基于 OpenVLA 在 LIBERO 仿真环境中的机器人策略评估与微调实验
# OpenVLA-LIBERO Evaluation & Finetuning

## Overview
This project implements evaluation and finetuning experiments on OpenVLA in the LIBERO robotic manipulation benchmark.

## Key Features
- OpenVLA rollout evaluation in LIBERO simulation
- Reproduction of official pretrained checkpoint results
- Task-specific finetuning experiments
- Failure mode analysis of robotic manipulation policies
- Training monitoring with Weights & Biases

## Results
- Official checkpoint success rate: ~71% (LIBERO-Spatial, 10 tasks, 100 episodes)

## Failure Analysis
- Action collapse in finetuned policy
- Grasp instability in manipulation tasks
- Long-horizon rollout drift

## Demo
![demo](assets/vedio/2026_05_07-20_48_10--episode=9--success=True--task=pick_up_the_black_bowl_between_the_plate_and_the_r.mp4)

## Setup
```bash
pip install -r requirements.txt
