---
title: Path Tracking For Car By Using Adaptive Model Predictive Control 
author: Junyu Zhou
date: 2020-10-30 17:28:00 +0200
categories: [ADAS Function, Matlab]
tags: [Simulation, MATLAB, Autonomous Driving, MPC]
math: true
---


## Path Tracking For Car By Using Adaptive Model Predictive Control

---
Two different state space equations are applied for path tracking.

Compared to steering angle, the steering angle rate as controlled signal can make system more stable. It can be found in following figures.

---

## Steering angle as controlled signal
![2](/Animation/PathTracking/MPC_Car.jpg)

## Steering angle rate als controlled signal
![2](/Animation/PathTracking/MPC_Car_DeltaS.jpg)


## Code
- [Adaptive Model Predictive Control - Path Tracking](https://github.com/jingtian123qwe/ADAS_Functions_MATLAB/tree/master/PathTracking/MPC)


## Ref:
- [Obstacle Avoidance Using Adaptive Model Predictive Control](https://www.mathworks.com/help/mpc/ug/obstacle-avoidance-using-adaptive-model-predictive-control.html)

## License

MIT

## Author

- [Junyu Zhou](https://github.com/jingtian123qwe/)
	
