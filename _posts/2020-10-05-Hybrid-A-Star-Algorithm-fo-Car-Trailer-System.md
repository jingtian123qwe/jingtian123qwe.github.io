---
title: Hybrid A Star Algorithm for Car Trailer System
author: Junyu Zhou
date: 2020-10-05 16:07:00 +0200
categories: [ADAS Function, Matlab]
tags: [Simulation, MATLAB, Autonomous Driving, Trailer]
math: true
#image: /Animation/img/sample/devices-mockup.png
---


## Hybrid A Star Algorithm for Car Trailer System

---

Path optimization is not included and will be added further.

Similar path planning algorithms for a car pulling trailer are discussed by [Habrador](https://blog.habrador.com/2015/11/explaining-hybrid-star-pathfinding.html) and [Atsushi Sakai](https://github.com/AtsushiSakai/HybridAStarTrailer)

The difference is that hitch point can be set not only at the midpoint of rear axle but also at the rear point of car body, more general for a car pulling a trailer.

---

## Perpendicular Parking

![Perpendicular parking](/Animation/PathPlanning/PerpendicularParkingTrailer.jpg)

![Perpendicular parking](/Animation/PathPlanning/PerpendicularParkingTrailer.gif)

## Parallel Parking

![Parallel parking](/Animation/PathPlanning/ParallelParkingTrailer.jpg)

![Parallel parking](/Animation/PathPlanning/ParallelParkingTrailer.gif)

## Code
- [Trailer Assist System](https://github.com/jingtian123qwe/ADAS_Functions_MATLAB/tree/master/PathPlanning)
## Ref

- [Practical Search Techniques in Path Planning for Autonomous Driving](http://ai.stanford.edu/~ddolgov/papers/dolgov_gpp_stair08.pdf)
- [Application of Hybrid A* to an Autonomous Mobile Robot for
  Path Planning in Unstructured Outdoor Environments](https://pdfs.semanticscholar.org/6e00/16024b257040db590d2de352556f64f46787.pdf)

## License

MIT

## Author

- [Junyu Zhou](https://github.com/jingtian123qwe/)
	
