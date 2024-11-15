# Configuration配置
该模型基于MATLAB 2020b，与对应版本Simulink，Simscape与Simscape Electrical。参数配置与仿真控制采用实时脚本实现。

1 This model is based on ***MATLAB 2020b***, as well as corressponding ***Simulink***，***Simscape*** adn ***Simscape Electrical***.

2 The configurations of parameters and the control of simulations are integrated in ***.mlx***.


# Overview总览
该模型用于仿真用NPC型三电平逆变器控制十二相永磁同步电机。永磁同步电机采用无相移架构，可分为4套对称的三相绕组，采用多dq轴解耦策略建模。负载模型参考螺旋桨空气阻力模型，为电机转速的三次方。该模型可进行系统在一整个工况周期的仿真，工况分为5个常见工况。电流环采用带前馈解耦的PI控制器。 

1 This model is used to simulate twelve-phase permanent magnet synchronous motor with NPC three-level inverter control. 

2 PMSM adopts zero phase-shift architecture, which can be divided into 4 sets of symmetrical three-phase windings, and adopts multi-DQ axis decoupling strategy to model. 

3 The load model refers to the propeller model， which is in proportion to the cube of the motor rotate speed. 

4 The model can simulate the system in a whole working cycle, which is divided into 5 common working conditions. 

5 The current loop uses PI controller with feedforward decoupling.
