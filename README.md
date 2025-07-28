# 1.-Design-and-Simulation-of-uncontrolled-half-wave-rectifier
## AIM
To design and simulate Half wave rectifier (Uncontrolled) in MATLAB Simulink.
## APPARATUS REQUIRED
•	MATLAB
## PROCEDURE
1.	Open MATLAB and click on the icon for SIMULINK as shown below
   <img width="685" height="536" alt="image" src="https://github.com/user-attachments/assets/e7351866-9cbf-4432-83e1-20a44624721c" />
Another way is to open is through START icon of MATLAB Start ⇒ Simulink ⇒ Library  browser. 
2.	Click on NEW MODEL or go to FILE ⇒ NEW ⇒ MODEL and a new blank model is created as shown below
<img width="796" height="542" alt="image" src="https://github.com/user-attachments/assets/3a48e8fc-77b9-4e06-88d9-e2236d732696" />
3.	After creating a blank model you need to open the SIMULINK component storeroom/library by going to View ⇒ Library Browser. Select SIMPOWER SYSTEMS then select Power Electronics library and by right clicking on diode and click on add to the model will add the diode in the blank model. Alternatively you can drag the component directly in the model page as shown below
<img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/a659713a-8a01-4390-8428-49cc2ae445a7" />
4.	Similarly go to ELECTRICAL SOURCES ⇒ AC Voltage Source and add it to the model. Select Elements and select “SERIES RLC BRANCH” and add it to the model. Simulink do not perform simulation unless and until a measurement block is present in a system. Since we need to measure the input and output voltages and the load current. To add them select Measurement in SIMPOWER SYSTEMS and then add current measurement and voltage measurement blocks to the model. Oscilloscope is not included in SIMPOWER SYSTEMS and is present in the top most block of the left column that is SIMULINK ⇒ Sinks ⇒ Scope. We can join various blocks by clicking
on their edges and then drag the wire till the other connection terminal.
5.	Construct the circuit by joining them together in the form as given below
<img width="940" height="318" alt="image" src="https://github.com/user-attachments/assets/9be26c47-e7b4-481f-95c0-55eaa3462fe5" />
6.	Now double click the voltage block to set the values of voltage and frequency.
<img width="484" height="450" alt="image" src="https://github.com/user-attachments/assets/d5f854e0-f7c8-4c8d-b52e-07e6341a1630" />
7.	Double click on diode and you can set various parameters for DIODE according to the specific data sheet.
8.	Double click on series RLC branch, Select the Branch type as R and set the values for R.
9.	In the Scope menu “>” is shown which can only be connected to the inverse icon “<” in the measurement blocks.
10.	Double click on SCOPE and then click on parameter icon as shown
<img width="974" height="438" alt="image" src="https://github.com/user-attachments/assets/c4ef2bb4-d9d0-4c91-8247-bc4cef16fe55" />
11.	Make the number of axes as required.
12.	Before running the simulation, we have to configure the parameters. Go to Simulation ⇒ Configuration parameters as shown
<img width="566" height="417" alt="image" src="https://github.com/user-attachments/assets/e5ece0f9-d6f5-49d1-8b65-25132390f517" />
13.	Select the ode23tb (Stiff/TR-BDF2) or ode15s (Stiff/NDS) or any suitable solver as
shown below 
<img width="566" height="401" alt="image" src="https://github.com/user-attachments/assets/3a80e2fb-55b3-47d0-94d6-4d6e05fde6a0" />
14.	Start the simulation by either clicking on Start Simulation icon as shown in below or
by going to Simulation ⇒ Start
<img width="770" height="308" alt="image" src="https://github.com/user-attachments/assets/20842380-f81a-4c17-b9bf-9dbd037778bb" />
15.	Double click on scope and observe the graphs.
16.	Right click on each graph and select the axes properties and label each graph.
17.	Save the file. 
18.	Analyze and record your inference.

## Task
Design, Simulate and analyse the below given circuit using the following values.
Resistance=0.5 ohm
Vin = 220 Vrms at 50Hz (312 Vp)
<img width="940" height="349" alt="image" src="https://github.com/user-attachments/assets/b2bb32b7-4bbf-4398-a2eb-a14853f5205a" />
## Simulation

## Output

## Result






