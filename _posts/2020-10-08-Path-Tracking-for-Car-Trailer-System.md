---
title: Path Tracking for Car Trailer System
author: Junyu Zhou
date: 2020-10-08 11:28:00 +0200
categories: [ADAS Function, Matlab]
tags: [Simulation, MATLAB, Autonomous Driving, Trailer]
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


Here the modus operandi of exact input/output linearization technique is used to calculate the steering wheel angle.
It works well with small deviation between current and desired path.

---

## Straight Path Tracking
![2](/Animation/PathTracking/Demo_Straight.jpg)

![2](/Animation/PathTracking/Deviation_Straight.jpg)


## Circle Path Tracking
![2](/Animation/PathTracking/Demo_Circle.jpg)

![2](/Animation/PathTracking/Deviation_Circle.jpg)

![2](/Animation/PathTracking/Circle.gif)


## Code
- [Trailer Assist System - Path Tracking](https://github.com/jingtian123qwe/ADAS_Functions_MATLAB/tree/master/PathTracking)


## Ref

- Reversing the General One-Trailer System: Asymptotic Curvature Stabilization and Path Tracking

## License

MIT

## Author

- [Junyu Zhou](https://github.com/jingtian123qwe/)
	
