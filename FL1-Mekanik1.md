# Mekanik 1

## Kinematik

### I en dimension

T.ex. en kula med massan m rullar i hastigheten v mellan x(t = 0) och x(t = t<sub>1</sub>).

v = v<sub>0</sub> (konstant)

dx = x(t = t<sub>1</sub>) - x(t = 0) = v<sub>0</sub>*t<sub>1</sub>

1. `=> x(t) = x(t = 0) + v`<sub>`0`</sub>`*t`<sub>`1`</sub>` `

a = a<sub>0</sub> (konstant)

dv / dt = a<sub>0</sub>

dx = v<sub>0</sub>*dt + 1/2 * a<sub>0</sub>*t<sub>1</sub><sup>2</sup>

1/a<sub>0</sub>t<sub>1</sub><sup>2</sup> = 1/2 * dv * dt

v(t) = lim (dt->0) dx/dt = dt/dx (derivata)

a(t) = lim (dt->0) dv/dt = dv/dt = d<sup>2</sup>x/d<sup>2</sup>t


### I 3 dimensioner

r<sup>-></sup> = (x,y,z)
(lägesvektor)

hastighet: v<sup>-></sup> = (V<sub>x</sub>, V<sub>y</sub>, V<sub>z</sub>) = (dx/dt, dy/dt, dz/dt) = dr<sup>-></sup>/dt

acceleration: a<sup>-></sup> = (dv<sub>x</sub>/dt, dv<sub>y</sub>/dt, dv<sub>z</sub>/dt) = d<sup>2</sup>r<sup>-></sup>/dt<sup>2</sup>

## Newtons ekvationer

`Newton`
`ma`<sup>`->`</sup>` = F`<sup>`->`</sup>` `


### Exempel

En kula med massan m rullar av ett bord(med höjden h) med hastigheten v<sub>0</sub> i x-riktning (v<sub>x0</sub>). (Räkna ut vad som händer i fallet från y<sub>0</sub> -> y = 0 och x = 0 -> x(t<sub>1</sub>).

Sök t<sub>1</sub> och x(t<sub>1</sub>)

#### Lösning

Dela upp rörelsen i x- och y-led.

x-led: Inga krafter.

y-led: Konstant acceleration nedåt.
a<sub>y</sub> = -g
g = tyngdaccelerationen = 9.81 m/s<sup>2</sup>

x(t) = v<sub>x0</sub>t (x(0) = 0)
= v<sub>0</sub>t
=> x(t<sub>1</sub>) = v<sub>0</sub>t<sub>1</sub>
y(t) = y<sub>0</sub> + v<sub>y0</sub>t + t/2 * a<sub>y</sub> * t<sup>2</sup>
a<sub>y</sub> = -g =>
y(t<sub>1</sub>) = -h = 1/2 (-g)t<sub>1</sub><sup>2</sup>
=> t<sub>1</sub><sup>2</sup> = 2h/g => t<sub>1</sub> = sqrt(2h/g)
x(t<sub>1</sub>) = v<sub>0</sub> * sqrt(2h/g)

