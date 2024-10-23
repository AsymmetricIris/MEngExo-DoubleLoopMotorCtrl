# MEngExo-DoubleLoopMotorCtrl
Modification to the Parkinson's wrist tremor simulator which uses a motor controller with 2 control loops (position w low gain + voltage w high gain) to simulate power wrist oscillations while approximating the angle the "patient's" wrist is trying to maintain.

Control system designed will control a DC motor using 1 part closed-loop position control with 1 part open loop direction control. The proportion of each control input's influence will be tunable, enabling a flexible balance in case new applications arise.
![](https://github.com/AsymmetricIris/MEngExo-DoubleLoopMotorCtrl/blob/master/img/design/block-2loop_ctrl.drawio.png?raw=true)
 \
 \
 \

Currently, double loop control behaves as expected electrically. Further testing required to simulate real world mechanics and ascertain any potential surprises. Then, we will fabricate a prototype and test with real life components.
![Currently, double loop control behaves as expected electrically](https://github.com/AsymmetricIris/MEngExo-DoubleLoopMotorCtrl/blob/master/img/2loop_ctrl.png?raw=true)
 \
 \
 \
H-bridge sub-circuit used within the above position control loop
![H-bridge sub-circuit used within the above position control loop](https://github.com/AsymmetricIris/MEngExo-DoubleLoopMotorCtrl/blob/master/img/h-bridge.png?raw=true)
 \
 \
 \
Gantt Chart Showing of Current Progress
![Gantt Chart Showing of Current Progress](https://github.com/AsymmetricIris/MEngExo-DoubleLoopMotorCtrl/blob/master/img/plan.png?raw=true)