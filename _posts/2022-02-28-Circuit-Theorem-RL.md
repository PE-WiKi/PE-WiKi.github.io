---
title: RL Circuit
tags: Basic
---  

# Introduction  
RL Circuit consists of resistors and Inductors. Depending on the configuration, RL circuit can be applied in various fields. For example, RL circuit can be used as a relay circuit.  

# Magnitude of Inductance  
$$
L = {N^(2)μA \over ℓ}
$$
<img class="image image--lg" src="/assets/images/contents/RL_Circuit/Inductor.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 60%;"/>  

# Voltage    
## Faraday’s Law  
> The amount of voltage induced in a coil is directly proportional to the rate of change of the magnetic field with respect to the coil.

# Limits  
## Winding Resistance
When a coil is made of a certain material, for example, insulated copper wire, that wire has a certain resistance per unit of length. In many applications, the winding resistance may be small enough to be ignored and the coil can be considered an ideal inductor. In other cases, the resistance must be considered.
<img class="image image--xl" src="/assets/images/contents/RL_Circuit/Inductor_Winding_Resistance.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

## Winding Capacitance  
When two conductors are placed side by side, there is always some capacitance between them. In many applications, this winding capacitance is very small and has no significant effect. In other cases, particularly at high frequencies, it may become quite important.  
<img class="image image--xl" src="/assets/images/contents/RL_Circuit/Inductor_Winding_Capacitance.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

# Types of Inductors  
[Mica Capacitor](https://eepower.com/capacitor-guide/types/mica-capacitor/#)  


# Calculation of inductance  
## Series  
Leq = L1 + L2 + ... + Ln  

## Parallel  
1/Leq = 1/L1 + 1/L2 + ... + 1/Ln  

# Applications  
<img class="image image--xl" src="/assets/images/contents/RC_Circuit/Relay_Circuit.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>
<p style="font-size: 20px;font-weight: bold;">Relay Circuit</p> 

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
    </div>
  </div>
</div>