# BMS
BMS project specifically designed for use on Electric Skateboards

**Introduction**

    With the introduction of [Benjamin Vedder's open source ESC](https://github.com/vedderb/bldc-hardware), the popularity of electric skateboards as a hobbie and also as an alternative transportation took off. The problem is that while the VESC is a powerful and highly adjustable controller, an equivalent battery management system was non-existent. While only a couple of BMS companies sell compatible products for the electric skateboard market, they are unadjustable and have an undesirable form factor, making them hard to fit inside the limited space of skateboard enclosures. They also use cheap components, thus making them unreliable due to heavy current spikes and also mechanically due to the nature of skateboarding. The goal of this project is to create a Battery Management System that is reliable and can handle enough current to power 4 motors, while fitting neatly inside the space of a skateboard enclosure.

**Features**
    1. Variable compatibility for 9-12s Li-ion/Lipo or 9-14s LiFePo4    
    1. 120 A max continuous current
    1. Adjustable over/under voltage detection
    1. Adjustable over current and short circuit detection
    1. Adjustable over temperature detection via 3 thermistors
    1. Coulomb counter
    1. Lifetime data-logging
    1. Compensated End-of-Discharge Voltage Gauging Algorithm
    1. Passive battery cell balancing up to 100 mA per cell
    1. 5-segment LED gauge or LCD
    1. Supports up to 320 Ahr
    1. Built in E-switch (requires a NO momentary switch)

