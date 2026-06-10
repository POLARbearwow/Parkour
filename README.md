# Isaaclab_Parkour

Isaac Lab based parkour locomotion.

Base model: [Extreme-Parkour](https://extreme-parkour.github.io/)

## Repository layout

- `parkour_isaaclab/`: core parkour environment, terrain, manager, and MDP logic
- `parkour_tasks/`: task registration and robot-specific environment configuration
- `scripts/rsl_rl/`: training, evaluation, demo, and export entry points
- `parkour_test/`: local test and validation scripts
- `s2s/`: sim-to-sim deployment and reference experiments

## Notes

- The repository contains configuration for both the base Go2 setup and a custom DogV2 robot.
- Large generated artifacts, editor history, and local task notes are intentionally not tracked in Git.
- Parts of `s2s/` are experimental deployment references and may require local path or dependency adjustments before use.

## Citation

If you use this code for your research, you **must** cite the following paper:

```
@article{cheng2023parkour,
title={Extreme Parkour with Legged Robots},
author={Cheng, Xuxin and Shi, Kexin and Agarwal, Ananye and Pathak, Deepak},
journal={arXiv preprint arXiv:2309.14341},
year={2023}
}
```

```
@article{mittal2023orbit,
   author={Mittal, Mayank and Yu, Calvin and Yu, Qinxi and Liu, Jingzhou and Rudin, Nikita and Hoeller, David and Yuan, Jia Lin and Singh, Ritvik and Guo, Yunrong and Mazhar, Hammad and Mandlekar, Ajay and Babich, Buck and State, Gavriel and Hutter, Marco and Garg, Animesh},
   journal={IEEE Robotics and Automation Letters},
   title={Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments},
   year={2023},
   volume={8},
   number={6},
   pages={3740-3747},
   doi={10.1109/LRA.2023.3270034}
}
```

```
Copyright (c) 2025, Sangbaek Park

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software …

The use of this software in academic or scientific publications requires
explicit citation of the following repository:

https://github.com/CAI23sbP/Isaaclab_Parkour
```
