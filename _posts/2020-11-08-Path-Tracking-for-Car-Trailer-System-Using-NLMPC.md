---
title: Path Tracking For Car Trailer System By Using Nonlinear Model Predictive Control
author: Junyu Zhou
date: 2020-11-08 01:28:00 +0200
categories: [ADAS Function, Matlab]
tags: [Simulation, MATLAB, Autonomous Driving, Trailer, MPC]
math: true
---


## Path Tracking for Car Trailer System - nonlinear system

---
Backing up a trailer is not easy for driver. Driver should always think steering wheel angle.
Usually the car goes one way and the trailer goes in the opposite direction.
In this post, the path tracking methode can be applied for autonomous driving for trailer.
Unlike driving forward, car pulls the trailer, that means trailer will just follow car's movement.
And the standard path tracking algorithms can also work in trailer system.
When backing up a trailer, the full car-trailer-system should be considered.
Controlling the trailer's direction and the system looks like a trailer pulling a car.


Here nonlinear model predictive control is used to calculate the steering wheel angle.
It works well with small deviation between current and desired path.

---

## Straight Path Tracking
![2](/Animation/PathTracking/nmpc_trailer_straight_backup.jpg)


## Code
- [Trailer Assist System - Path Tracking - NLMPC](https://github.com/jingtian123qwe/ADAS_Functions_MATLAB/tree/master/PathTracking/NLMPC)

## Ref

- [Nonlinear model predictive controller](https://www.mathworks.com/help/mpc/ref/nlmpc.html)


## License

MIT

## Author

- [Junyu Zhou](https://github.com/jingtian123qwe/)
	
