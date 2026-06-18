### What is Measured?

During the experiment, the following quantities are measured:

- Effective head acting on the turbine,
- Discharge through the turbine,
- Rotational speed of the turbine,
- Brake load,
- Brake drum dimensions.

These measurements are used to determine the hydraulic input power, shaft output power, and overall efficiency of the turbine.

### Why are these Measurements Important?

#### Effective Head

The head represents the hydraulic energy available to drive the turbine.

#### Discharge

The discharge determines the quantity of water supplying energy to the turbine.

#### Rotational Speed

The speed indicates the operating condition of the turbine and is required for calculating shaft power.

#### Brake Load

The brake load provides the torque developed by the turbine shaft.

#### Turbine Efficiency

Comparing the hydraulic input power with the shaft output power indicates the effectiveness of the turbine in converting water energy into mechanical energy.

### Sequential Calculations

#### Step 1

Calculate the hydraulic input power.

$$
P_h=\rho gQH
$$

#### Step 2

Calculate the shaft torque.

$$
T=(W-S)R
$$

where

- $W$ = Dead load,
- $S$ = Spring balance reading,
- $R$ = Brake drum radius.

#### Step 3

Calculate the output power.

$$
P_o=\frac{2\pi NT}{60}
$$

#### Step 4

Calculate the overall efficiency.

$$
\eta=\frac{P_o}{P_h}\times100
$$

### Solved Numerical Example

Given,

Head,

$$
H=5\ m
$$

Discharge,

$$
Q=0.02\ m^3/s
$$

Speed,

$$
N=900\ rpm
$$

Brake load difference,

$$
W-S=12\ N
$$

Brake radius,

$$
R=0.15\ m
$$

Hydraulic power,

$$
P_h=1000\times9.81\times0.02\times5
=981\ W
$$

Torque,

$$
T=12\times0.15=1.8\ Nm
$$

Output power,

$$
P_o=\frac{2\pi\times900\times1.8}{60}
=170\ W
$$

Efficiency,

$$
\eta=\frac{170}{981}\times100
=17.3%
$$

### Observation Table

| Trial | Head (m) | Discharge ($m^3/s$) | Speed (rpm) | Output Power (W) | Hydraulic Power (W) | Efficiency (%) |
| ----- | -------: | ------------------: | ----------: | ---------------: | ------------------: | -------------: |
| 1     |        3 |               0.015 |         700 |               90 |                 441 |           20.4 |
| 2     |        4 |               0.018 |         800 |              125 |                 706 |           17.7 |
| 3     |        5 |               0.020 |         900 |              170 |                 981 |           17.3 |
| 4     |        6 |               0.022 |         950 |              215 |                1295 |           16.6 |
| 5     |        7 |               0.025 |        1000 |              280 |                1717 |           16.3 |

### Interpretation

The observations show that increasing the operating head and discharge increases the hydraulic power available to the turbine.

The turbine converts a portion of this hydraulic energy into useful mechanical power at the shaft. The difference between the hydraulic input power and shaft output power is due to hydraulic, mechanical, and frictional losses.

The efficiency of the turbine depends on the operating conditions and generally reaches a maximum within a particular range of discharge and speed.

The experiment demonstrates the practical conversion of water energy into mechanical energy and illustrates the operating characteristics of hydraulic turbines used in hydroelectric power generation.
