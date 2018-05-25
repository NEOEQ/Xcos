<h2>Tutorial Continuous Stirred Tank with Heating </h2>

1. [Introduction](https://github.com/NEOEQ/Xcos/wiki/Xcos/_edit#1-introduction)
2. [Mathematical model] 
3. [Implementation into XCOS]

<h2> Introduction </h2>

In this example, a stirred tank is used to heat a fluid stream that is continuously fed into the tank. A coil, through which steam flows, provides heat to the tank. In this way, a PID controller is used to control the temperature of the tank. The tank, containing liquid with volume V, is fed with a volumetric flow stream f(t) with inlet temperature $T_{i}$ (t). The system is heated by a steam stream with mass flow rate of w(t), with temperature T_s (t). The product stream leaves the tank with volumetric flow rate f(t) and temperature T(t).
