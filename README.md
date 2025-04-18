# FLA: Force-Language-Action Model for Robot Safe Contact-Rich Manipulation
this project is in progress.
## Overview
Motivation: Fine-tuning by safe RL with force and torque perception to advance the safe performance of VLA for manipulation, especially contact-rich tasks.

**Contact**: heng.zhang@iit.it

## Table of Contents
- [TODO](#todo)
- [Results](#results)
- [Open Questions](#open-questions)
- [Citation](#citation)

## TODO
- [ ] Deploy common VLA models locally
    - [x] [OpenVLA](#openvla)
    - [ ] RDT
    - [ ] Others...
- [ ] Evaluate performance of each VLA model as baselines
    - [x] OpenVLA
    - [ ] RDT
- [ ] Add F/T sensor integration for each setup
- [ ] Create 5-10 contact-rich task environments
- [ ] Design and implement FLA environment
    - [ ] Integration with force/torque perception
    - [ ] Safe RL framework setup
    - [ ] Reward function design
    - [ ] Safety constraints implementation
- [ ] Train and evaluate FLA model
    - [ ] Initial training phase
    - [ ] Performance benchmarking
    - [ ] Comparison with baselines
- [ ] exps in real world
## Results
### Baselines
- ### OpenVLA:
- ### OpenVLA-Goal
    | Task | Success | Failure | Success Rate |
    |------|---------|---------|--------------|
    | Pick & Place (Between Plate) | ![](videos/drawer_success.gif) | ![](videos/drawer_fail.gif) | 50.2% |
    | Pick & Place (Cabinet) | ![](videos/door_success.gif) | ![](videos/door_fail.gif) | 80% |
    | Pick & Place (Stove) | ![](videos/screw_success.gif) | ![](videos/screw_fail.gif) | 60% |
    | Pick & Place (Drawer) | ![](videos/insertion_success.gif) | ![](videos/insertion_fail.gif) | 70% |
    | PickAPlace (cookie_box) | ![](videos/wiping_success.gif) | ![](videos/wiping_fail.gif) | 85% |
- ### OpenVLA-spatial
    | Task | Success | Failure | Success Rate |
    |------|---------|---------|--------------|
    | Pick & Place (Between Plate) | ![](videos/drawer_success.gif) | ![](videos/drawer_fail.gif) | 50.2% |
    | Pick & Place (Cabinet) | ![](videos/door_success.gif) | ![](videos/door_fail.gif) | 80% |
    | Pick & Place (Stove) | ![](videos/screw_success.gif) | ![](videos/screw_fail.gif) | 60% |
    | Pick & Place (Drawer) | ![](videos/insertion_success.gif) | ![](videos/insertion_fail.gif) | 70% |
    | PickAPlace (cookie_box) | ![](videos/wiping_success.gif) | ![](videos/wiping_fail.gif) | 85% |
- ### RDT:
    - *Results pending*

### Our Approach
*Work in progress*

## Open Questions
- How to create a scale of contact-rich tasks environments?
- *Add more questions as they arise*

## Citation
```bibtex
@ARTICLE{10517611,
  author={Zhang, Heng and Solak, Gokhan and Lahr, Gustavo J. G. and Ajoudani, Arash},
  journal={IEEE Robotics and Automation Letters}, 
  title={SRL-VIC: A Variable Stiffness-Based Safe Reinforcement Learning for Contact-Rich Robotic Tasks}, 
  year={2024},
  volume={9},
  number={6},
  pages={5631-5638},
  doi={10.1109/LRA.2024.3396368}}
```