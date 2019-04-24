# Supercapacitor-Battery-combo-in-Electric-Vehicles
This project provides a way of using supercapacitors in tandem with batteries in electric vehicles to achieve the following benefits:
  1. Reduction of the peak currents in batteries to increase battery life.
  2. Improving an electric vehicle's acceleration & driving range.

The project involves a matlab simulation of an electric vehicle being alternatively driven by a battery and a supercapacitor in different stages of its motion i.e accleration/deceleration/constant motion.

# Matlab Simulation Model

The model uses a controller to identify the vehicle's motion and accordingly selects the battery or the supercapacitor. During periods of acceleration the supercapacitor runs the motor whereas during periods of constant motion or deceleration the battery drives the motor.
This is shown in the following 2 submodels:


![MODEL-1](https://user-images.githubusercontent.com/49238787/56644827-1b44c800-669a-11e9-9e2a-8673a9d9a2bd.PNG)

The above picture shows that part of the model which sends real time current readings of the motor to workspace. 


![model-2](https://user-images.githubusercontent.com/49238787/56644837-20097c00-669a-11e9-848c-71656f5db561.PNG)

This picture shows how current readings from the workspace are sent into the matlab processor to identify the nature of motion of the vehicle and accordingly instruct the power sources (batteries & supercapacitotrs).
