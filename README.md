# Cruise-Controller

Implementing the concept of PID controller by designing cruise controller to reach desired velocity

## Motion Model
If the inertia of the wheels is neglected, and it is assumed that air drag(proportional to the car's speed at low speeds) is opposing the motion of the car, then the motion model is reduced to a simple first order system.
Thus the motion of the car can be written as:

## Model Parameters
Mass(m) = 50 kg<br /> 
Drag Coefficient(b) = 25<br /> 
Desired Velocity(v) = 60 m/s<br /> 
![cruise](https://user-images.githubusercontent.com/102024497/229163195-b32ecaf5-13cf-4fd9-9cd7-89fd52b1476b.png)

## Results
Rise time of the system(time taken to reach 90% of the target velocity) = 1.12 seconds <br /> 
Maximum overshoot is 2.82%.

# 1D Trajectory Control

## Hover Control
![hover_controls](https://user-images.githubusercontent.com/102024497/229165449-9595f65b-ab0c-465b-8ef1-8be104c9d8cf.jpeg)

## Step Response
![step_responses](https://user-images.githubusercontent.com/102024497/229165508-7094bb5e-90b3-4e24-a1c0-90eba1f450e4.jpeg)

# 2D Trajectory Control

## Line Trajectory
![lineeee](https://user-images.githubusercontent.com/102024497/229166063-888c8d82-709b-4326-9f1b-db023c3f8eb8.jpeg)

## Sine Trajectory
![sineeee](https://user-images.githubusercontent.com/102024497/229166242-c75ba646-cefd-4fa7-b5a0-e72a936d5f91.jpeg)
