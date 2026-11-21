# Smart Autonomous Car - GPS/INS Navigation with EKF Sensor Fusion

GPS/IMU integrated navigation for a smart autonomous car (team project: GPS + INS + nRF24L01 wireless link + Kalman Filter system), with an Extended Kalman Filter for state estimation.

## What it does

- Handles the GPS/IMU data pipeline: synchronization and integration between both sensors so raw data lines up in time for precise positioning.
- Links the processed data to a MATLAB implementation of an Extended Kalman Filter for state estimation and sensor fusion.
- Turns raw sensor data into a stable navigation solution, improving trajectory consistency compared with either sensor alone.

## Role

Responsible for the GPS/IMU data handling pipeline - synchronization and integration between the sensors - and the MATLAB EKF implementation for state estimation and sensor fusion.

## Tools & stack

- MATLAB (Extended Kalman Filter implementation)
- GPS + IMU (INS) sensors, nRF24L01 wireless module
- Arduino / embedded systems

## Links

- Project post: https://www.linkedin.com/posts/aya-mubarak-829862298_smart-autonomous-car-activity-7467919504317083650-rPpo

## Status

README first; MATLAB code and results can be added later.
