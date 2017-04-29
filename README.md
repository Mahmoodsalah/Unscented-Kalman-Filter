
# Unscented Kalman Filter Project Starter Code
Implement Unscented Kalman Filter (UKF) to track bicycle arround Self-Driving Car using Lidar and Radar Sensors.
This part from Self-Driving Car Engineer Nanodegree Program 

---
## Results

Required result:  px, py, vx, and vy RMSE should be less than or equal to the values [.09, .10, .40, .30].
My Result: [0.07,0.08,0.35,0.27]

## Data Visualization
Plots below showing how the UKF can track the moving object (bicycle) 

Difference between Positions of UKF Estimation, Ground truth value and Measurment 
![alt text]('UKFmainplot.png')

Note: ground truth not appear because its totally below the UKF estimation (high accurate)


## Dependencies

* cmake >= v3.5
* make >= v4.1
* gcc/g++ >= v5.4

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./UnscentedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./UnscentedKF ../data/obj_pose-laser-radar-synthetic-input.txt`




## Generating Additional Data


If you'd like to generate your own radar and lidar data, see the
[utilities repo](https://github.com/udacity/CarND-Mercedes-SF-Utilities) for
Matlab scripts that can generate additional data.

## Results

Required result:  px, py, vx, and vy RMSE should be less than or equal to the values [.09, .10, .40, .30].
My Result: [0.07,0.08,0.35,0.27]


```python

```
