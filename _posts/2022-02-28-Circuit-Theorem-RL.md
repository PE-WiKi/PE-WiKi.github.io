---
title: RL Circuit
tags: Basic
---  

# Introduction  
RL Circuit consists of resistors and Inductors. Depending on the configuration, RL circuit can be applied in various fields. For example, RL circuit can be used as a relay circuit.  

# Magnitude of Inductance  
<img class="image image--lg" src="/assets/images/contents/RL_Circuit/Inductor.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 60%;"/>  

$$
L = {N^{2}μA \over ℓ}
$$

# Voltage    
## Faraday’s Law  
> The amount of voltage induced in a coil is directly proportional to the rate of change of the magnetic field with respect to the coil.  
> The electromotive force around a closed path is equal to the negative of the time rate of change of the magnetic flux enclosed by the path.  

With Faraday's Law, we can find the equation for the amount of induced voltage.  

$$
{\vert}V_{ind}{\vert} = N{d\phi \over dt}
$$

## Lenz’s Law  
When the current through a coil changes, an induced voltage is created as a result of the changing electromagnetic field and the polarity of the induced voltage is such that it always opposes the change in current.  

With Lenz’s Law, we can find the direction of the induced voltage.  

$$
V_{ind} = -N{d\phi \over dt}
$$

# Step Response  
<img class="image image--lg" src="/assets/images/contents/RL_Circuit/step_response.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 60%;"/>  

# Practical Issues  
## Winding Resistance (DC Resistance)  
When a coil is made of a certain material, for example, insulated copper wire, that wire has a certain resistance per unit of length. In many applications, the winding resistance may be small enough to be ignored and the coil can be considered an ideal inductor. In other cases, the resistance must be considered.
<img class="image image--xl" src="/assets/images/contents/RL_Circuit/Inductor_Winding_Resistance.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

### Q Factor  
This resistance dissipates some of the reactive energy. The quality factor (or Q) of an inductor is the ratio of its inductive reactance to its resistance at a given frequency, and is a measure of its efficiency. The higher the Q factor of the inductor, the closer it approaches the behavior of an ideal inductor.  
$$
Q = {wL \over R}
$$

## Winding Capacitance  
When two conductors are placed side by side, there is always some capacitance between them. In many applications, this winding capacitance is very small and has no significant effect. In other cases, particularly at high frequencies, it may become quite important.  
<img class="image image--xl" src="/assets/images/contents/RL_Circuit/Inductor_Winding_Capacitance.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

## Saturation  
# Types of Inductors  
## Air-core Inductor  
The term air core coil describes an inductor that does not use a magnetic core made of a ferromagnetic material. The term refers to coils wound on plastic, ceramic, or other nonmagnetic forms, as well as those that have only air inside the windings. Air core coils have lower inductance than ferromagnetic core coils, but are often used at high frequencies because they are free from energy losses called core losses that occur in ferromagnetic cores, which increase with frequency. A side effect that can occur in air core coils in which the winding is not rigidly supported on a form is 'microphony': mechanical vibration of the windings can cause variations in the inductance.  
<img class="image image--xl" src="/assets/images/contents/RL_Circuit/air_core_inductor.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

## Ferromagnetic-core inductor  
Ferromagnetic-core or iron-core inductors use a magnetic core made of a ferromagnetic or ferrimagnetic material such as iron or ferrite to increase the inductance. A magnetic core can increase the inductance of a coil by a factor of several thousand, by increasing the magnetic field due to its higher magnetic permeability. However the magnetic properties of the core material cause several side effects which alter the behavior of the inductor.  

<img class="image image--xl" src="/assets/images/contents/RL_Circuit/iron_core_inductor.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

### Side Effects - Core losses  
A time-varying current in a ferromagnetic inductor, which causes a time-varying magnetic field in its core, causes energy losses in the core material that are dissipated as heat, due to Eddy currents, Hysteresis.  

**Eddy currents**  


**Hysteresis**  




**Iron-core Inductor**  



**Toroidal Inductor**  

<img class="image image--xl" src="/assets/images/contents/RL_Circuit/air_core_inductor.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

**Laminated Core Inductor**  

<img class="image image--xl" src="/assets/images/contents/RL_Circuit/air_core_inductor.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

**Powdered Iron-core Inductor**  

<img class="image image--xl" src="/assets/images/contents/RL_Circuit/air_core_inductor.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

# Calculation of inductance  
## Series  
Leq = L1 + L2 + ... + Ln  

## Parallel  
1/Leq = 1/L1 + 1/L2 + ... + 1/Ln  

# Applications  
<p style="font-size: 20px;font-weight: bold;">Relay Circuit</p> 
<img class="image image--lg" src="/assets/images/contents/RL_Circuit/Relay_Circuit.jpg" />

----  

<div class="item">
  <div class="item__image">
    <img class="image" src="/assets/images/contents/refs.jpg"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <p style='font-size=6px;font-weight: bold;'>References</p>
      <p style='font-size=5px;'>- Charles Alexander, Matthew Sadiku - Fundamentals of Electric Circuits-McGraw-Hill Science_Engineering_Math (2012)</p>
      <p style='font-size=5px;'>- Thomas L. Floyd, David M. Buchla - Principles of Electric Circuits 10th ed</p>
      <a href="https://en.wikipedia.org/wiki/Inductor" style='font-size=5px;'>- Wikipedia - Inductor</p>
    </div>
  </div>
</div>