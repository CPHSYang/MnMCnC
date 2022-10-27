# Mini-CNC : M&M-CNC

### Description : Create a miniture CNC machine with ready made parts, limited 3D printed parts, and basic hobby circuitry 

##### General Requirements 

1. CNC should cut metal and wood
2. CNC must have ability to replace spindle for higher spec motor
3. Use only ready made kit parts, precut, or rapid prototyped (laser cut or 3D print) 
4. Use AC power, no battery

##### Technical Requirements 

1. 3-axis degrees of freedom 
2. x-axis: +- 400 mm minimum 
3. y-axis: +- 400mm minimum
4. z-axis: +- 200 mm minimum 
5. Bit sizes between 10mm and 1 mm 
6. Spindle Speed 6000 rpm
7. Feed rate 200 ipm 
8. Max Budget: 300$ 
9. 12V for all components

#### Work Break Down
![image](https://user-images.githubusercontent.com/33789192/198336130-44954e44-8490-4b33-a3fe-6c73970693aa.png)

[Cnc Work Breakdown](https://app.diagrams.net/#G1-pGSj6zrlPf-V_P4YyosqtA9TX-E5aWt)

#### Calculations 

| Item        | Value           |
| ------------- |:-------------:|
| Max RPM stepper motor     | |
| Max RPM gear box motor     | |
| Max length lead screw | 1000mm |

#### Bill of Materials 

[Bill of Materials](https://docs.google.com/spreadsheets/d/18Q-QuPedNc3dOqKtJqhoTGTPmJNXPU0npuWzOIBIFFE/edit#gid=0)

##### Stepper Motor Selection: Stepperonline Stepper Bipolar


<img src="https://user-images.githubusercontent.com/33789192/198341589-e13d15b4-a93b-46d1-b018-3b0971e8bda6.png" alt="stepper" style="width:200px;height:200px;">

| Item        | Technical Specification           | This Motor |
| ------------- |:-------------:|---|
| Power    | 12V | 12V |
| Current Draw | 2 A | 2 A |
| Feed Rate    | 200 ipm | XXXX |
| Max torque| XXXX | 59 Ncm |
| Shaft Diameter | 4mm max | 2.54 mm |
| Step Angle | 1-2 degrees| 1.8 degrees|
| Dimensions | XXXX | 1.65 x 1.65 x 1.89 inches | 

##### Planetary Motor Selection: 
| Item        | Technical Specification           | This Motor |
| ------------- |:-------------:|---|
| Power    | | |
| Current Draw | | |
| RPM     | | |
| Max torque| 1000mm | |
| Shaft Diameter | | |
| Dimensions | | | 

#### Appendixes 

**I : Feed and Spindle Rate Sources**

[Spindle and Feed Link General](https://martinsupply.com/cnc-machining-understanding-feeds-speeds/)

[Spring and Feed Characterization](https://www.cncci.com/post/understand-spindle-speed-limiting-on-turning-centers#:~:text=The%20spindle%20range%20surprise&text=The%20low%20range%20runs%20from,automatically%20limited%20to%202%2C000%20rpm.)

