# 200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor

![Input currents](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/bd5a1a7e-e15a-474f-9406-a57ee76f9f5d)

![EM meshing](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/e163a9c0-f781-4fe4-bc74-01ac92ab4c44)

![Flux Density](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/8abe905f-7a84-488c-8ae9-e885e5f3da6f)


optimal design of the cooling system using pipes:
In recent years, with the expansion of the use of electric motors in various industries, the need for motors with limited dimensions and high torque and power density at the same time has increased. To design and construct such a motor, in addition to electromagnetic analysis, we also need thermal analysis. Because practically, there are thermal limits that determine the rated power of the electric machine. On the other hand, the performance of various parts of the electric motor, such as magnets, insulations, and bearings, is highly dependent on the operating temperature. Therefore, thermal analysis is very important for electric motors. This analysis should cover fluid issues in addition to solids issues; In other words, besides the motor, we must also consider the internal and external fluids of the motor. This fluid has a significant effect on the cooling of the motor, and this fluid causes the main convective currents of the electric motor.

![ANN](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/29aa99ff-19a0-4c1d-aec1-9e3ab9080f23)

![Assem3](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/7e754492-48af-4863-84a0-bfb6e4b0e4f5)

![Stator Temp](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/1380921c-3130-4d42-9066-2a1ce68286bb)

The use of a cooling system directly affects the temperature of the motor. In addition to reducing heat, this optimization must also be fluid and economically efficient. For this reason, we must optimize this system from all three aspects of temperature, fluidity, and economy. Finally, the results obtained from the comparisons between the initial and optimal design in terms of thermal and electromagnetic will show the effect of optimization. Classical and intelligent algorithms are used for this optimization. Intelligent algorithms have a higher priority due to the stagnation of local optimal points and the ability to integrate into any derivative and non-derivative system.
The problem of heat transfer and electromagnetism determines the initial condition of the motor for practical use. While for complete information about the motor's condition in practical and applied testing, it is necessary to perform mechanical and acoustic (harmonic) analyses on the motor. Therefore, after the mechanical test, we can comment on the length of the air gap. The acoustic analysis will also result in motor noise, so we can have a complete view of the motor performance by completing these two analyses.

![Stator](https://github.com/toohidsharifi/200kW-water-cooled-surface-mounted-permanent-magnet-synchronous-motor/assets/126771405/bfeebb27-0c48-4c21-a7d2-731f00d03176)


Why this project can help you?

As you know, the design process of electrical machines contains branches, including electromagnetic design, thermal design,
    mechanical design, vibration design, and drive system design.

According to Juha Pyrhonen [1], the stuff of thermal design in electrical machines is much more complicated than the clas-
    sic electromagnetic design.

Empirical constants are very popular in the field of electrical machines as machine designers usually don't have the spec-
    ific ability to design the thermal circuits for the machine.

The empirical constants are only valuable in the realm of standard electric motors which are used and experiments multiple
    times to ensure the fruitfulness of the constants.

On the other hand, when you want to design a totally new machine, you won't be able to use constants because their preass-
    umptions may not be present or applicable in the surroundings of your motor.

For such situations, the only remained way is to design the cooling system from 0 to 100.

In this project, the cooling system design and thermal analysis of a large-scale, 200kW, 6-phase, and surface-mounted per-
    manent magnet synchronous motors were investigated and explained.

For implementing the cooling system, firstly the cooling performance of the motor was modeled using multi-layer perceptron
    artificial neural network (MLPANN) modeling.

After modeling and system identification, it is time to optimize the cooling system. Like every optimization problem, we 
    should determine the decision variables, the objective function (s), and the optimization methods.

As the cooling performance of the motor is determined from fluidic, thermal, and economical perspectives, we have speci-
    fied three objective functions. Therefore, we face a multi-objective optimization problem. A trade-off between the
    objective functions finally determines the result of the cooling system design.

For fluidic performance, we have selected the pressure drop of cooling pipes. To consider the thermal viewpoint we moni-
    tored the temperature of hotspots (in this case the hotspots appear in the end-windings.) Additionally, to include the
    economic perspective, the price of cooling pipes is considered the third objective function.

After implementing the sensitivity analysis, we concluded that three decision variables are more effective in the flu-
    idic, thermal, and economic performances. Firstly, the number of heat pipes directly affects the fluidic, thermal,
    and economic performances. Increasing the number of heat pipes causes the temperature of hotspots to lessen, while
    the total pressure drop and cost of cooling pipes would be increased directly.

As mentioned earlier, this is what we call a trade-off in the context of multi-objective optimization.

The second decision variable is the diameter of the cooling pipes. The wider the cooling pipe, the less pressure drop 
    will result. Moreover, because of the increased touching surface between the pipe and the motor, the temperature 
    of the motor would be alleviated. At the same time, the peripheral area of the pipe increases as the pipe becomes
    wider. So, the cost of the cooling system escalates. The trade-off is obvious.

Thirdly, the speed of the inlet fluid of the pipe is considered as it has a substantial effect on fluidic performance. 
    After optimization, post-processing including various comparisons between the initial and optimal cooling systems 
    proves the effectiveness of optimization and the resultant cooling system.

[1]	J. Pyrhonen, T. Jokinen, and V. Hrabovcova, Design of Rotating Electrical Machines: Wiley, 2009.
