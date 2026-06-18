The Performance Characteristics of a Pelton Turbine Experiment is performed to determine the output power and efficiency of the turbine under different loading conditions.

During the experiment, the discharge, turbine speed, and applied load are measured. These observations are used to calculate the hydraulic input power, shaft torque, output power, and overall efficiency of the turbine.

### Measured Data

The following quantities are measured during the experiment.

|       Parameter        | Symbol |  Unit   |
| :--------------------: | :----: | :-----: |
|     Effective head     |  $H$   |    m    |
|       Discharge        |  $Q$   | m$^3$/s |
|     Turbine speed      |  $N$   |   rpm   |
|      Applied mass      |  $M$   |   kg    |
| Spring balance reading |  $S$   |   kg    |

For the apparatus,

- Brake drum diameter,

$$
D=0.45;m
$$

- Rope diameter,

$$
d=0.020;m
$$

- Density of water and acceleration due to gravity are

$$
\rho=1000;kg/m^3,\qquad g=9.81;m/s^2
$$

### Calculation of Hydraulic Input Power

The hydraulic power supplied to the turbine depends upon the discharge and the available head.

The input power is

$$
P_i=\rho gQH
$$

For

$$
Q=0.005;m^3/s
$$

and

$$
H=28.5;m,
$$

$$
P_i=1000\times9.81\times0.005\times28.5
$$

$$
P_i=1397.9;W
$$

### Calculation of Torque

The applied load produces a braking force on the turbine shaft. This braking force is used to determine the shaft torque.

The effective radius of the brake drum is

$$
r=\frac{D+d}{2}
$$

For

$$
D=0.45;m
$$

and

$$
d=0.020;m,
$$

$$
r=\frac{0.45+0.02}{2}
$$

$$
r=0.235;m
$$

The torque developed by the turbine is

$$
T=(M-S)gr
$$

For

$$
M=12;kg
$$

and

$$
S=2;kg,
$$

$$
T=(12-2)\times9.81\times0.235
$$

$$
T=23.05;N.m
$$

### Calculation of Output Power

The output power developed by the turbine shaft depends upon the torque and rotational speed.

The output power is

$$
P_o=\frac{2\pi NT}{60}
$$

For

$$
N=450;rpm
$$

and

$$
T=23.05;N.m,
$$

$$
P_o=\frac{2\pi\times450\times23.05}{60}
$$

$$
P_o=1086.2;W
$$

### Calculation of Overall Efficiency

The efficiency indicates how effectively the hydraulic energy supplied to the turbine is converted into mechanical power.

The overall efficiency is

$$
\eta=\frac{P_o}{P_i}\times100
$$

Using

$$
P_o=1086.2;W
$$

and

$$
P_i=1397.9;W,
$$

$$
\eta=\frac{1086.2}{1397.9}\times100
$$

$$
\eta=77.7%
$$

A higher efficiency indicates better conversion of hydraulic energy into useful mechanical work.

### Sample Observation Table

| Trial | $Q$ (m$^3$/s) | $N$ (rpm) | $M$ (kg) | $S$ (kg) | Torque (N.m) | Input Power (W) | Output Power (W) | Efficiency (%) |
| :---: | :-----------: | :-------: | :------: | :------: | :----------: | :-------------: | :--------------: | :------------: |
|   1   |    0.0050     |    450    |    12    |    2     |    23.05     |     1397.9      |      1086.2      |      77.7      |
|   2   |    0.0050     |    420    |    14    |    2     |    27.66     |     1397.9      |      1216.8      |      87.0      |
|   3   |    0.0050     |    380    |    16    |    2     |    32.28     |     1397.9      |      1284.5      |      91.9      |
|   4   |    0.0050     |    320    |    18    |    2     |    36.89     |     1397.9      |      1236.2      |      88.4      |
|   5   |    0.0050     |    250    |    20    |    2     |    41.50     |     1397.9      |      1086.7      |      77.7      |

### Interpretation

As the load applied to the Pelton turbine increases, the torque developed by the runner increases while the rotational speed decreases. The output power and efficiency initially increase because of improved energy transfer from the water jet to the buckets. Beyond an optimum operating condition, further loading causes a reduction in speed and output power, leading to a decrease in efficiency.

The experimentally calculated values of output power and efficiency are used to plot the performance characteristics of the Pelton turbine and to identify its most efficient operating range.
