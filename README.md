# Supercapacitor-Battery-combo-in-Electric-Vehicles
This project provides a way of using supercapacitors in tandem with batteries in electric vehicles to achieve the following benefits:
  1. Reduction of the peak currents in batteries to increase battery life.
  2. Improving an electric vehicle's acceleration & driving range.

The project involves a matlab simulation of an electric vehicle being alternatively driven by a battery and a supercapacitor in different stages of its motion i.e accleration/deceleration/constant motion.

# Matlab Simulation Model

The model uses a controller to identify the vehicle's motion and accordingly selects the battery or the supercapacitor. During periods of acceleration the supercapacitor runs the motor whereas during periods of constant motion or deceleration the battery drives the motor.
This is shown in the following 2 submodels:



The above picture shows that part of the model which sends real time current readings of the motor to workspace. 




The above picture invloves making use of the current readings from the workspace into the matlab processor to identify the nature of motion of the vehicle and accordingly instruct the power sources (batteries & supercapacitotrs).
