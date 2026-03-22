# Hearing-Aids
Continious Development Project with a goal to achieve the best possible hearing aids device

## Used materials
> Microphones
>> MAX9814

> Amplifiers
>> PAM8403

> Load
>> Magnet Dynamics(8 Ohm 1 W)/ Headphone driver)

> Power
>> LP85204 3.7 V Li-Po Battery

> SMD Components
>> Resistors(5 - 10k Ohm, 1 - 2k Ohm)
>> 
>> Capacitors(1 - 68 uF)

> Jumpwires/Dupontwires

## Used tech
> Osciloscope DHO804
> 
> Solder Air Station Yihua 948D
> 
> LabView 2026

## Progress
1. Battery - MAX9814 - PAM8403 - Magnet Dynamics
> Circuit - https://raw.githubusercontent.com/TwilightSaw/Hearing-Aids/refs/heads/main/images/circuit_dynamic.jpg
>> Strong feedback loop due to close in and out sound placement, signal is clear but unstable higher the frequency up to unhearable.
2. Battery - MAX9814 - PAM8403 - Headphone Driver
> Circuit - https://raw.githubusercontent.com/TwilightSaw/Hearing-Aids/refs/heads/main/images/circuit_headphone.jpg
>> Feedback loop is almost gone but is still present if out is too close to microphone, signal is clear and amplified but unstable and grainy.

## Tests and measurements 
> Osciloscope was set to 1.00 ms, 50 mV and AC measurements.
>> Here you can see OUT from MAX9814(1-yellow) and PAM8403 IN after resistors(2-aquamarine)
>> [!image](https://raw.githubusercontent.com/TwilightSaw/Hearing-Aids/refs/heads/main/images/Osciloscope_1.png)

> [!image](https://github.com/TwilightSaw/Hearing-Aids/blob/main/images/labview_1.jpg)

> [!image](https://raw.githubusercontent.com/TwilightSaw/Hearing-Aids/refs/heads/main/images/labview_out.jpg)

> [!image](https://raw.githubusercontent.com/TwilightSaw/Hearing-Aids/refs/heads/main/images/labview_gain.jpg)

LabView files connect test.vi and mV.vi test osciloscope connection and circuit measurements accordingly.

## Conclusions
Circuit works but requires further development in terms of stability and clearance. Next steps will require to go into more smaller parts and creating separate PCB. 
