#Gravitational Simulator
###Authors: Siddharth Rau (sidrau2), Vithuran Rathakrishnan (vr27)
This project is a 3D N-Body Simulator that models and visualizes gravitational interactions between celestial bodies. The system uses numerical methods to simulate the motion of objects under the influence of gravity. The simulation is designed to replicate the behavior of bodies in a gravitational field, such as planets, stars, or asteroids, and provide a 3D visualizations of their trajectories.

A key component of our solar system simulation is the Runge-Kutta 4th Order (RK4) numerical integration method. This technique allows us to approximate the continuous motion of celestial bodies by breaking down their movement into discrete time steps. Unlike other methods, RK4 provides a more accurate representation of gravitational dynamics by:

* Calculating multiple intermediate steps within each time interval
* Accounting for the complex, non-linear nature of gravitational interactions
* Minimizing accumulated numerical errors
