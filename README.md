# 1.-Design-and-Simulation-of-uncontrolled-half-wave-rectifier
## AIM
To design and simulate Half wave rectifier (Uncontrolled) in MATLAB Simulink.
## APPARATUS REQUIRED
•	MATLAB
## PROCEDURE
1.	Open MATLAB and click on the icon for SIMULINK as shown below
 
Another way is to open is through START icon of MATLAB Start ⇒ Simulink ⇒ Library  browser. 

2.	Click on NEW MODEL or go to FILE ⇒ NEW ⇒ MODEL and a new blank model is created as shown below
 
3.	After creating a blank model you need to open the SIMULINK component storeroom/library by going to View ⇒ Library Browser. Select SIMPOWER SYSTEMS then select Power Electronics library and by right clicking on diode and click on add to the model will add the diode in the blank model. Alternatively you can drag the component directly in the model page as shown below
 
4.	Similarly go to ELECTRICAL SOURCES ⇒ AC Voltage Source and add it to the model. Select Elements and select “SERIES RLC BRANCH” and add it to the model. Simulink do not perform simulation unless and until a measurement block is present in a system. Since we need to measure the input and output voltages and the load current. To add them select Measurement in SIMPOWER SYSTEMS and then add current measurement and voltage measurement blocks to the model. Oscilloscope is not included in SIMPOWER SYSTEMS and is present in the top most block of the left column that is SIMULINK ⇒ Sinks ⇒ Scope. We can join various blocks by clicking
on their edges and then drag the wire till the other connection terminal.
5.	Construct the circuit by joining them together in the form as given below
 


6.	Now double click the voltage block to set the values of voltage and frequency.
 
7.	Double click on diode and you can set various parameters for DIODE according to the specific data sheet.
8.	Double click on series RLC branch, Select the Branch type as R and set the values for R.
9.	In the Scope menu “>” is shown which can only be connected to the inverse icon “<” in the measurement blocks.
10.	Double click on SCOPE and then click on parameter icon as shown
 
11.	Make the number of axes as required.
12.	Before running the simulation, we have to configure the parameters. Go to Simulation ⇒ Configuration parameters as shown
 
13.	Select the ode23tb (Stiff/TR-BDF2) or ode15s (Stiff/NDS) or any suitable solver as
shown below 
 
14.	Start the simulation by either clicking on Start Simulation icon as shown in below or
by going to Simulation ⇒ Start
 
15.	Double click on scope and observe the graphs.
16.	Right click on each graph and select the axes properties and label each graph.
17.	Save the file. 
18.	Analyze and record your inference.

## RESULT.
Thus, Half wave rectifier circuit was designed and simulated in MATLAB Simulink.
