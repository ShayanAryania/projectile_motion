# projectile_motion
This Python script simulates and visualizes projectile motion under three different drag conditions:

No Drag Force (Fr = 0): The projectile follows an ideal parabolic trajectory where only gravity affects its motion.
Linear Drag Force (Fr = kv): A resistive force proportional to velocity (D*v) is introduced, altering the trajectory by reducing the horizontal and vertical velocities.
Quadratic Drag Force (Fr = kv²): The drag force is proportional to the square of velocity (D*v²), which significantly impacts the motion, causing a more pronounced deviation from the ideal case.
Breakdown of the Code:
The initial velocity (v0 = 4 m/s) and launch angle (60°) are defined, with corresponding velocity components (v0x, v0y).
The simulation uses small time steps (deltaT = 0.01 s) to iteratively update the projectile's position and velocity based on the equations of motion.
The script stores the x and y positions in separate lists for plotting.
Each scenario is simulated in a separate loop:
No resistance: Standard kinematic equations are used.
Linear drag: Velocity-dependent acceleration is applied.
Quadratic drag: The acceleration depends on both velocity components and their squared magnitudes.
Finally, the trajectories for all three cases are plotted using Matplotlib to compare how air resistance affects projectile motion.
