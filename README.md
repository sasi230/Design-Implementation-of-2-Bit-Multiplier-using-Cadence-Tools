# EXP NO:6  Design-Implementation-of-2-Bit-Multiplier-using-Cadence-Tools


## Aim:
To design and implement a 2-bit multiplier circuit using Cadence EDA tools, simulate its functionality, and to understand its application in digital arithmetic operations.

## Tools Required:
+	Personal Computer
+	Cadence Virtuoso Software

## Circuit Diagram:
![WhatsApp Image 2024-11-15 at 3 07 27 PM](https://github.com/user-attachments/assets/32e8d876-bd4b-4207-9237-8c824fea7b05)

## S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 


## Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre



### i)	Procedure for Creating New Library.
•	File –New – Library
•	Name: Give name for ur library Ex: VLSILAB_EXP_1
•	Enable Attach to an existing technology library, Click OK
•	Attach the library to the technology library gpdk045.Click OK

### ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)
•	File-New-Cell view
•	Setup the new file form
+	Library: Select the one you created.
+ Cell: Give the experiment name Ex: Inverter ViewSchematic
+	Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
+	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
+	Click on browse. This opens the library browser
+	Now select the appropriate library for components like 
+	Gpdk45 ------------------------nmos1v, pmos1v
+	Create Input and Output pins
+	Make the connections by using fixed narrow wire key
+	Click Check and Save button
![Screenshot 2024-11-09 213423](https://github.com/user-attachments/assets/c8778735-2420-4bef-a254-f3b6f9ac7549)



 
### iii)	Creating the Symbol for schematic Cell view

+	In the schematic window, execute 
+	Create – Cell view – From Cell view
+	The cell view from cell view window appears
+	Check Lib Name, Cell Name, From View name must be schematic Press ok
+	Now Symbol generation form appears. Click Ok If No changes required
+	A new window with with default symbol is created.
+	Edit the symbol if you want to give actual symbol shape else continue.
+	Execute Create-Cell view-from cell view
+	Library Name and Cell Name must be same which you have used for schematic. Press OK
+	Check for the position of pin side.Prss OK
+	Edit for the shape by Create-Shape-Choose required options to edit.

 ![Screenshot 2024-11-12 220931](https://github.com/user-attachments/assets/ee617a6d-4475-4ff2-8f1c-a9f34812ba04)



### iv)	Creating the new test cell view

+	Go to CIW window, Execute File-New-Cell view
+	Setup the new file form
+	Library: Select the one you created.
+	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
+	View: Schematic
+	Type: Schematic press OK
•	Follow the step 3(ii) d to make the required connections
![Screenshot 2024-11-09 213025](https://github.com/user-attachments/assets/86a3a6aa-b50f-4694-97f8-4fab5c7f226e)




 

### Analog simulation by SPECTRE.
+	In test cell view window
+	Launch – ADE L(Analog Design Environment)
+	Execute Setup—Simulation/directory/Host A new window opens
+	Set the simulation window to spectre and click ok
+	Execute Analysis – Choose. A window opens.
+	Select the type and set the specifications and press OK
+	Execute Output s—to be plotted – Select on Schematic
+	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
+	Execute Simulation -- Net list and Run
![Screenshot 2024-11-09 213433](https://github.com/user-attachments/assets/5ee25166-2d89-404c-81ec-dd192d2c2cd9)


## For Transient Analysis Settings and Output
![Screenshot 2024-11-09 213356](https://github.com/user-attachments/assets/c4e64e25-e966-48a1-bd96-928ac9776b21)






### Results:

The design and implementation of the 2-bit multiplier using Cadence EDA tools were successfully carried out. The simulation results confirmed the correct operation of the multiplier for all input combinations. 
