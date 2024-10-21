`EXP 2: CUSTOM DESIGN OF 2X1 MUX`

`AIM:` 

To design and implement a 2:1 multiplexer (MUX) circuit using Cadence EDA tools, analyse its functionality and performance, and understand the principles of digital logic design, including schematic creation, layout design, and simulation. 

`TOOLS REQUIRED:`<br>
• Personal Computer <br>
• Cadence Virtuoso Software<br>

`S C H E M A T I C S I M U L A T I O N` <br>
PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION Commands to get into Cadence

-Right Click and open the terminal window <br>
-Type the following commands as follows and press enter. <br>
• csh <br>
• source /cadence/install/cshrc <br>
• virtuoso Procedure for Schematic simulation using Cadence <br>

-Now two windows must open <br>
i)virtuoso/command interpreter window <br>
ii)”Whats New…” <br>

-Close the 2nd window<br>
Use 1st window i.e virtuoso window(CIW) for further processing.<br>
i. Create a New Library <br>
ii. Create Schematic Cell view.<br>
iii. Create the Symbol for schematic Cell view.<br>
iv. Create the test Cell view. <br>
v. Analog simulation by spectre<br>

i) Procedure for Creating New Library. <br>
• File –New – Library <br>
• Name : Give name for ur library Ex: VLSILAB_EXP_1<br>
• Enable Attach to an existing technology library, Click OK <br>
• Attach the library to the technology library gpdk045.Click OK <br>

ii) Create Schematic Cell view. <br>
• Go to 1st window i.e virtuoso(CIW) <br>
• File-New-Cell view <br>
• Setup the new file form Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View_Schematic Type: Schematic press OK <br>
• Add the required components from the libraries and make the connections. <br>
 Go to instance fixed menu or use shortcut key “I” from keypad to go instances <br>
 Click on browse. This opens the library browser <br>
 Now select the appropriate library for components like <br>
 Gpdk45 ------------------------nmos1v, pmos1v <br>
 Create Input and Output pins  Make the connections by using fixed narrow wire key  Click Check and Save button image<br>

iii) Creating the Symbol for schematic Cell view <br>

• In the schematic window, execute  Create – Cell view – From Cell view  The cell view from cell view window appears  Check Lib Name, Cell Name, From View name must be schematic Press ok <br>
• Now Symbol generation form appears. Click Ok If No changes required <br>
• A new window with with default symbol is created.<br>
• Edit the symbol if you want to give actual symbol shape else continue. <br>
• Execute Create-Cell view-from cell view <br>
• Library Name and Cell Name must be same which you have used for schematic. Press OK <br>
• Check for the position of pin side.Prss OK<br> 
• Edit for the shape by Create-Shape-Choose required options to edit.<br>

![WhatsApp Image 2024-09-10 at 22 04 13_17107dbe](https://github.com/user-attachments/assets/6b0d1f24-0856-4045-a2a9-948747dfa4bc)<br>

iv) Creating the new test cell view<br>
• Go to CIW window, Execute File-New-Cell view <br>
 Setup the new file form <br>
 Library: Select the one you created. <br>
 Cell: Cell name must be different from the name used in schematic cell view. <br>
Ex: Inverter_test  View: Schematic <br>
 Type: Schematic press OK <br>
• Follow the step 3(ii) d to make the required connections image<br>

![WhatsApp Image 2024-09-10 at 22 05 41_c12e0e48](https://github.com/user-attachments/assets/e2a0c769-f17a-458f-be26-d96f0e1bac8d)<br>


Analog simulation by SPECTRE. <br>
• In test cell view window <br>
• Launch – ADE L(Analog Design Environment) <br>
 Execute Setup—Simulation/directory/Host A new window opens<br> 
 Set the simulation window to spectre and click ok <br>
 Execute Analysis – Choose. A window opens.<br> 
 Select the type and set the specifications and press OK <br>
 Execute Output s—to be plotted – Select on Schematic <br>
 Then Select the INPUT WIRE(Vin) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
• Execute Simulation -- Net list and Run image<br>

![WhatsApp Image 2024-09-10 at 22 05 41_383ac9e5](https://github.com/user-attachments/assets/9bd0ce08-96a5-49df-83f1-f2debec1f6fc)<br>


`For Transient Analysis Settings and Output image`<br>


![WhatsApp Image 2024-09-10 at 22 03 18_cb7bfd8c](https://github.com/user-attachments/assets/30bf1863-8742-444c-9578-a75a4b2acf03)<br>


`Results:`<br>

-The experiment successfully demonstrated the design and implementation of a 2:1 MUX using Cadence EDA tools.<br>
-The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.<br>
