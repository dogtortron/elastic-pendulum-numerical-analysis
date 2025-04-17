# Executive Summary
In this project, I studied the trajectory of an elastic pendulum using explicit methods (Forward Euler and Runge-Kutta 4) and implicit methods (Backward Euler, Crank-Nicholson, Adams-Moulton, and Backward-Difference Formula.)

Here are some conclusions:
- Forward Euler is not suitable for this elastic pendulum problem, but RK4 is suitable.
- Backward Euler may perform better than Forward Euler in providing a solution, but it does not beat RK4 in solving this elastic pendulum problem.
- The studied implicit methods did not give stable solutions at time step larger than 0.035.
- Starting the pendulum at a slight angle can result in a big maximum angle of displacement.
- RK4 was surprisingly good at solving this problem. It matched so well with the Crank-Nicholson solution.
