# Motorsport Tools

A collection of  vehicle dynamics and race engineering tools in Excel and Python (Jupyter), covering tyre management, strategy, suspension design and steering loads. These projects were put together for trackside jobs, Formula Student, and a Le Mans Hydrogen car group design project for the MSc of Advanced Motorsport Engineering at Cranfield University, 2025.


## What it does
- Trackside/tyre_datasheet.xlsm	- Tracks tyre mileage for a given circuit length. Colour coding distinguishes tyre sets and sides.
- Trackside/tyre_strategy.ipynb	- Outputs the fastest 1-stop tyre strategy for a given set of compounds, using degradation and initial pace inputs.
- Vehicle Dynamics/load_transfer_&_actuators.xlsx - Calculates load transfer at peak conditions, extracts spring rates at maximum pitch and heave, and derives anti-roll bar rates by subtracting them from the target roll stiffness. Then finds critical damping rates and selects the damping ratio with the lowest contact patch load variation using a 7-post rig model.
- Vehicle Dynamics/steering_torque.ipynb	- Compares the steering torque required over a lap between the LFS23 car and the ChassisSim LFS24 model, to check whether the target distribution is met.
- Vehicle Dynamics/suspension_loads.xlsx	- Uses a free-body diagram of the suspension pick-up points to find the forces through each control arm. Reference: FS Wiki: Suspension Forces.


## Author

José Albuquerque Vale, LinkedIn: josealbuquerquevale, jose.a.vale@outlook.com
