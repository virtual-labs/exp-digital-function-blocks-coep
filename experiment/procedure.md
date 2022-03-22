### **The procedure for using simulator is as follows:**
Click on the link provided under simulator tab to open the simulator. You need to configure the required logic.

### **Part 1: Understanding the operation of AI and AO function block**

1. First **left click** on AI block available under IO tab. Drag this block to required position preferably left side and vertically at center.
2. Now **left click** on AO block. Drag it and put it next to AI block.
3. Take the cursor to the color dot at the output side of AI block. Move it by **left clicking** and take it to the color dot at the Input side of AO block.
4. Now click on Compile tab. If any compilation errors are there, it will be shown. Otherwise Run tab gets activated.
5. When user clicks on Run tab, default value of AI will get displayed on wired connection.
To change the input value and observe the output change, **right click** on the AI block. Select edit and enter an input value in the range 0-100. You will observe the change at the AO block output.
When you click on the block, the properties of the block gets displayed at left hand bottom corner.
To delete the connection, **click** on the wire **question mark** at the output side of the block and press delete key.
Other options like delete, disable and configure are available on **right clicking** the block. For modifying the logic, user need to first press Stop tab and enter into Configure tab.
For clearing the workspace, Clear tab is available.

### **Part 2: Understanding the operation of DI and DO function block**
Follow same procedure as above to get the bolcks in the workspace and connect DI and DO blocks. In RUN mode, change the digital input value to 0 from1 or vice-versa and observe the effect.

### **Part 3: Understanding the operation of Logic function block**
To configure the logic circuit, first reload the page by clicking Clear tab
1. First **left click** on digital input (DI) block to get it in the workspace. Repeat this procedure for getting 2 DI blocks. They will be by default DI1 and DI2. Similarly get 1 DO block in the workspace.
2. **Left click** on any logic function block e.g. AND function from Logic Tab available in the left hand panel.
3. Connect output of DI1 to one of the inputs of AND block.
**Initially only one input connection is available with the logic block. As you make DI connection with this input, another connection appears for this logic block.**
Connect DI2 output to this second AND block input. Connect output of AND block to input of DO.
4. Now click on Compile tab. If any compilation errors are there, it will be shown. Otherwise Run tab gets activated.
5. Now change one of the inputs to AND gate by toggling DI value from 0 to 1. Observe the DO status.
6. Change another input to AND gate in the similar manner and observe DO status.
7. Verify the AND gate truth table by changing DI status.
Similarly verify the truth tables for OR and NOT Logic Gates.