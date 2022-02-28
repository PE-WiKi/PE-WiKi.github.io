---
title: RC Circuit
tags: Basic
---  

# Introduction  
RC Circuit consists of resistors and capacitors. Depending on the configuration, RC circuit can be applied in various fields. For example, RC circuit can be used as a Delay circuit.  
<img class="image image--xl" src="/assets/images/contents/RC_Circuit/capacitor_simple.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>

<img class="image image--xl" src="/assets/images/contents/RC_Circuit/illustration_of_capacitor_charging.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 70%;"/>  

# Step Response  
<img class="image image--lg" src="/assets/images/contents/RC_Circuit/capacitor_step_response.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 70%;"/>  

# Limits

## Voltage Rating
Every capacitor has a limit on the amount of voltage that it can withstand across its plates. The voltage rating specifies the maximum dc voltage that can be applied without risk of damage to the device. Below is a datasheet of a MLCC. Appropriate capacitors must be selected to avoid damage to the circuit.  
<img class="image image--xl" src="/assets/images/contents/RC_Circuit/datasheet_mlcc.jpg" style="height: 200px; display: block;margin-left: auto;margin-right: auto;width: 90%;"/>  

## Temperature Coefficient  
The temperature coefficient indicates the amount and direction of a change in capacitance value with temperature. For example, a negative temperature coefficient of 150 ppm/°C for a 1 mF capacitor means that for every degree rise in temperature, the capacitance decreases by 150 pF.  

## Leakage  
No insulating material is perfect. The dielectric of any capacitor will conduct some very small amount of current. Thus, the charge on a capacitor will eventually leak off. Some types of capacitors, such as large electrolytic types, have higher leakages than others.  
<img class="image image--md" src="/assets/images/contents/RC_Circuit/capacitor_leakage_eq_circuit.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>  

# Types of Capacitors  
[Mica Capacitor](https://eepower.com/capacitor-guide/types/mica-capacitor/#)  
Mica capacitors are available with capacitance values ranging from 1 pF to 0.1 mF and voltage ratings from 100 V dc to 2,500 V dc. Mica has a typical dielectric constant of 5.

[Ceramic Capacitor](https://eepower.com/capacitor-guide/types/ceramic-capacitor/)  
Ceramic dielectrics provide very high dielectric constants (1,200 is typical). As a result, comparatively high capacitance values can be achieved in a small physical size. Ceramic capacitors typically are available in capacitance values ranging from 1 pF to 100 mF with voltage ratings up to 6 kV.  

[Plastic-Film Capacitors](https://eepower.com/capacitor-guide/types/film-capacitor/)  
A film capacitor is a capacitor that uses a thin plastic film as the dielectric. They are relatively cheap, stable over time and have low self-inductance and ESR, while some film capacitors can withstand large reactive power values.  

[Electrolytic Capacitors](https://eepower.com/capacitor-guide/types/electrolytic-capacitor/)  
An electrolytic capacitor is a polarized capacitor which uses an electrolyte to achieve a larger capacitance than other capacitor types. Electrolytic capacitors have polarity. So, they must be forward biased.  

# Calculation of capacitance  
## Series  
1/Ceq = 1/C1 + 1/C2 + ... + 1/Cn

## Parallel  
Ceq = C1 + C2 + ... + Cn

# Applications  
<img class="image image--xl" src="/assets/images/contents/RC_Circuit/DelayCircuit.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>
<p style="font-size: 20px;font-weight: bold;">Delay Circuit</p>
<p style="font-size: 15px;font-weight: normal;">The larger R2, the longer it will take for the neon lamp to fully light up.</p>

<img class="image image--xl" src="/assets/images/contents/RC_Circuit/RC_Charging.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>
<p style="font-size: 20px;font-weight: bold;">Charging State</p>
<p style="font-size: 15px;font-weight: normal;">4~5τ can be used as a settling time.</p>

<img class="image image--xl" src="/assets/images/contents/RC_Circuit/RC_Discharging.jpg" style="display: block;margin-left: auto;margin-right: auto;width: 50%;"/>
<p style="font-size: 20px;font-weight: bold;">Discharging State</p>
<p style="font-size: 15px;font-weight: normal;">4~5τ can be used as a settling time.</p>

----  

<div class="item">
  <div class="item__image">
    <img class="image" src="/assets/images/contents/refs.jpg"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <p style='font-size=6px;font-weight: bold;'>References</p>
      <p style='font-size=5px;'>- Charles Alexander, Matthew Sadiku - Fundamentals of Electric Circuits-McGraw-Hill Science_Engineering_Math (2012)</p>
      <p style='font-size=5px;'>- thomas l. floyd - Principles of Electric Circuits 10th ed</p>
    </div>
  </div>
</div>