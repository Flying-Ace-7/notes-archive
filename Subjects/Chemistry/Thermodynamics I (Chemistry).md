[[Chemistry MOC]]

[[First Law of Thermodynamics]]


Different types of thermodynamical systems:

- Isolated System
	- No exchange of energy and matter
- Closed system
	- Exchange of energy in and out of the system
	- no Exchange of matter
- Open System
	- Both exchange of matter and energy


Heat transfer between systems and surroundings:

- <mark class="hltr-orange">Exothermic process</mark> is any process that gives off heat-transfers thermal energy from the system to the surroundings (System loses energy)
- <mark class="hltr-blue"> Endothermic process</mark> is the reverse, absorbs energy from the surroundings (System gains energy)

> [!note] Sign conventinon
> \+ -> Work done on the system by the surroundings
> \-  -> Work done on the surroundings by the sysetem
> \+ -> Heat gained by the system
> \- -> heat lost by the system

### Work
Work done is not a state function. Work is dependant on path. Hence, work may be different for reactions wit the same start and end points.

#### Free expansion
When a ssytem expands under a vacum .
Work done is zero

#### Work under constant pressure
Work is described as the negative integral of pressure with respect to volume:
where the pressure is the **external** pressure acting on the system
$$
 w = - \int_{v_{i}}^{v_{f}} p \, dv 
$$
since pressure is constant:
$$
 w = - p_{ext}\int_{v_{i}}^{v_{f}}  \, dv 
$$
#### Isothermal reversible expansion
Basically when a gas expands reversibly under constant temperature.
$$
w = - \int_{v_{i}}^{v_{f}} p \, dv

$$
since:

$$
PV = nRT
$$
$$
P = \frac{nRT}{V}
$$
$$
w = - nRT \int_{V_{i}}^{V_{f}} \frac{dv}{v} = -nRT \ln\left( \frac{V_{f}}{V_{i}} \right)
$$



Now, let us learn some state functions, that are helpful to thermodynamics:

### U , internal energy

we define $\Delta U$ to be:
$$
\Delta U = q+w
$$
where, $q$ is the heat supplies to the system, and $w$ is the work donw by the systeem.

Note: $U$ is a function of temperature, and when temperature is constant, $\Delta U$ is 0
### H, enthalpy

$$
\Delta H = \Delta U + \Delta(PV)
$$
Now, we shall observe these functions under different conditions:

### Constant volume

$$
\Delta U_{V}=q_{v}
$$
$$
\Delta H = \Delta U + \Delta P V= q_{V} + \Delta PV
$$
### Constant pressure
$$
\Delta U = q_{P}-P\Delta V


$$
$$
q_{p}= \Delta U + P\Delta V
$$

$$
\Delta H=q_{P}
$$
Hence, we can say that enthalpy, $\Delta H$ is the heat released under constant pressure condition


### An important derivation of the heat capacities 

Let $C_{p}$ be the heat capacity of a system under constant pressure, and $C_{V}$ be the heat capacity under constant volume .
We know that for any System, :
$$
Q = C \Delta T
$$
where Q is the heat supplied to the system.
$$
C = \frac{Q}{\Delta T}= \frac{dQ}{dT}
$$
now,
$$
C_{p}= \left( \frac{dQ_{p}}{dT} \right)_{p}
$$
since $q_{p}=\Delta H,\, dQ_{P}=dH$
$$
C_{P}= \left( \frac{dH}{dt} \right)_{p}
$$
since $\Delta H = \Delta U +\Delta PV$ , $dH = dU + pdV$

$$
C_{P}= \frac{dU+pdV}{dT}

$$
$$
C_{P}= \frac{dU}{dt} + \frac{pdV}{dt}
$$
note that in constant volume: $\Delta U = q_{v}$, and also $pdV=nr dT$

hence:
$$
C_{P}= \frac{dQ_{v}}{dt} +nR
$$
$$
C_{P}=C_{V}+nR
$$
