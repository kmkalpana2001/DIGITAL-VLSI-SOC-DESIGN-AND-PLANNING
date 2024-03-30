# *DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING*
# Contents 
 <div class="toc">
  <ul>
    <li><a href="#header-1">Day 1 - Inception of open-source EDA, OpenLANE and sky130 PDK</a></li>
	<ul>
        <li><a href="#header-1_1"> How to talk to computers</a></li>
		<ul>
			<li><a href="#header-1_1_1">Introduction to QFN-48 Package, chip, pads, core, die and IPs</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_1_2">Introduction to RISC-V</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_1_3">From Software Applications to Hardware</a></li>
		</ul>
      </ul>
      <ul>
        <li><a href="#header-1_2">Soc design and OpenLANE</a></li>
	      <ul>
			<li><a href="#header-1_2_1">Introduction to all components of open-source digital asic design</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_2_2"> Simplified RTL2GDS flow</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_2_3">Introduction to OpenLANE and Strive chipsets</a></li>
		</ul>
	      <ul>
			<li><a href="#header-1_2_4">Introduction to OpenLANE detailed ASIC design flow</a></li>
		</ul>
      </ul>
	<ul>
        <li><a href="#header-1_3">Get familiar to open-source EDA tools</a></li>
		<ul>
			<li><a href="#header-1_3_1">OpenLANE Directory structure in detail</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_3_2">Design Preparation Step</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_3_3">Review files after design prep and run synthesis</a></li>
		</ul>
	      <ul>
			<li><a href="#header-1_3_4">OpenLANE Project Git Link Description</a></li>
		</ul>
		<ul>
			<li><a href="#header-1_3_5">Steps to characterize synthesis results</a></li>
		</ul>
      </ul>
   </div>
  
<div class="toc">
  <ul>
    <li><a href="#header-2">Day 2 - Good floor planning considerations</a></li>
	<ul>
        <li><a href="#header-2_1"> Chip Floor planning consideration</a></li>
		<ul>
			<li><a href="#header-2_1_1">Utilization factor and aspect ratio</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_1_2">Concept of pre-placed cells</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_1_3">De-coupling capacitors</a></li>
		</ul>
	      <ul>
			<li><a href="#header-2_1_4">Power planning</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_1_5">Pin placement and logical cell placement blockage</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_1_6">Steps to run floorplan using OpenLANE</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_1_7">Review floorplan files and steps to view floorplan/a></li>
		</ul>
	      <ul>
			<li><a href="#header-2_1_8">Review floorplan layout in Magic</a></li>
		</ul>
      </ul>
      <ul>
        <li><a href="#header-2_2">Library building and Placement</a></li>
	      <ul>
			<li><a href="#header-2_2_1">Netlist binding and initial place design</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_2_2">Optimize placement using estimated wire-length and capacitance</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_2_3">Final placement optimization</a></li>
		</ul>
	      <ul>
			<li><a href="#header-2_2_4">Need for libraries and characterization</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_2_5">Congestion aware placement using RePlAce</a></li>
		</ul>
      </ul>
	<ul>
        <li><a href="#header-2_3">Cell design and characterization flows</a></li>
		 <ul>
			<li><a href="#header-2_3_1">Inputs for cell design flow</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_3_2">Circuit design steps</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_3_3">Layout design step</a></li>
		</ul>
	      <ul>
			<li><a href="#header-2_3_4">Typical characterization flow</a></li>
		</ul>
      </ul>
	  <ul>
        <li><a href="#header-2_4">General timing characterization parameters</a></li>
		   <ul>
			<li><a href="#header-2_4_1"> Timing threshold definitions</a></li>
		</ul>
		<ul>
			<li><a href="#header-2_4_2">Propagation delay and transition time</a></li>
		</ul>
      </ul>
</div>
  
  <div class="toc">
  <ul>
    <li><a href="#header-3">Day 3 - Design library cell using Magic Layout and ngspice characterization</a></li>
	<ul>
        <li><a href="#header-3_1"> Labs for CMOS inverter ngspice simulations</a></li>
		<ul>
			<li><a href="#header-3_1_0">IO placer revision</a></li>
		</ul>
		 <ul>
			<li><a href="#header-3_1_1">SPICE deck creation for CMOS inverter</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_1_2">SPICE simulation lab for CMOS inverter</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_1_3"> Switching Threshold Vm</a></li>
		</ul>
	      <ul>
			<li><a href="#header-3_1_4">Static and dynamic simulation of CMOS inverter</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_1_5">Lab steps to git clone vsdstdcelldesign</a></li>
		</ul>
      </ul>
      <ul>
        <li><a href="#header-3_2">Inception of layout ̂A CMOS faabrication process </a></li>
		 <ul>
			<li><a href="#header-3_2_1">Create Active regions</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_2_2">Formation of N-well and P-well</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_2_3"> Formation of gate terminal</a></li>
		</ul>
	      <ul>
			<li><a href="#header-3_2_4">Lightly doped drain (LDD) formation</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_2_5">Source ÃÂ drain formation</a></li>
		</ul>
  		<ul>
			<li><a href="#header-3_2_6">Local interconnect formation</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_2_7"> Higher level metal formation</a></li>
		</ul>
	      <ul>
			<li><a href="#header-3_2_8"> Lab introduction to Sky130 basic layers layout and LEF using inverter</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_2_9">Lab steps to create std cell layout and extract spice netlist</a></li>
		</ul>
      </ul>
	<ul>
        <li><a href="#header-3_3">Sky130 Tech File Labs</a></li>
		<ul>
			<li><a href="#header-3_3_1">Lab steps to create final SPICE deck using Sky130 tech</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_3_2">Lab steps to characterize inverter using sky130 model files</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_3_3"> Lab introduction to Magic tool options and DRC rules</a></li>
		</ul>
	      <ul>
			<li><a href="#header-3_3_4">Lab introduction to Sky130 pdk's and steps to download labs</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_3_5">Lab introduction to Magic and steps to load Sky130 tech-rules</a></li>
		</ul>
  		<ul>
			<li><a href="#header-3_3_6">Lab exercise to fix poly.9 error in Sky130 tech-file</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_3_7"> Lab exercise to implement poly resistor spacing to diff and tap</a></li>
		</ul>
	      <ul>
			<li><a href="#header-3_3_8"> Lab challenge exercise to describe DRC error as geometrical construct</a></li>
		</ul>
		<ul>
			<li><a href="#header-3_3_9">Lab challenge to find missing or incorrect rules and fix them</a></li>
		</ul>
      </ul>
   </div>
	  
<div class="toc">
  <ul>
    <li><a href="#header-4">Day 4 - Pre-layout timing analysis and importance of good clock tree</a></li>
	<ul>
        <li><a href="#header-4_1">Timing modeling using delay tables</a></li>
		 <ul>
			<li><a href="#header-4_1_1">Lab steps to convert grid info to track info</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_1_2">Lab steps to convert magic layout to std cell LEF</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_1_3">Introduction to timing libs and steps to include new cell in synthesis</a></li>
		</ul>
	      <ul>
			<li><a href="#header-4_1_4">Introduction to delay tables</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_1_5">Delay table usage Part 1</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_1_6">Delay table usage Part 2</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_1_7">Lab steps to configure synthesis settings to fix slack and include vsdinv</a></li>
		</ul>
      </ul>
      <ul>
        <li><a href="#header-4_2">Timing analysis with ideal clocks using openSTA</a></li>
	       <ul>
			<li><a href="#header-4_2_1">Setup timing analysis and introduction to flip-flop setup time</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_2_2">Introduction to clock jitter and uncertainty</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_2_3">Lab steps to configure OpenSTA for post-synth timing analysis</a></li>
		</ul>
	      <ul>
			<li><a href="#header-4_2_4">Lab steps to optimize synthesis to reduce setup violations</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_2_5">Lab steps to do basic timing ECO</a></li>
		</ul>
      </ul>
	<ul>
        <li><a href="#header-4_3">Clock tree synthesis TritonCTS and signal integrity</a></li>
		  <ul>
			<li><a href="#header-4_3_1">Clock tree routing and buffering using H-Tree algorithm</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_3_2">Crosstalk and clock net shielding</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_3_3">Lab steps to run CTS using TritonCTS</a></li>
		</ul>
	      <ul>
			<li><a href="#header-4_3_4">Lab steps to verify CTS runs</a></li>
		</ul>
      </ul>
	  <ul>
        <li><a href="#header-4_4">Timing analysis with real clock using openSTA</a></li>
		  <ul>
			<li><a href="#header-4_4_1">Setup timing analysis using real clocks</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_4_2"> Hold timing analysis using real clocks</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_4_3">Lab steps to analyze timing with real clocks using OpenSTA</a></li>
		</ul>
	      <ul>
			<li><a href="#header-4_4_4">Lab steps to execute OpenSTA with right timing libraries and CTS assignment</a></li>
		</ul>
		<ul>
			<li><a href="#header-4_4_5">Lab steps to observe impact of bigger CTS buffers on setup and hold timing</a></li>
		</ul>
      </ul>
</div>
	
<div class="toc">
  <ul>
    <li><a href="#header-5">Day 5 -Final step for RTL2GDS using tritinRoute and openSTA</a></li>
	<ul>
        <li><a href="#header-5_1">Routing and design rule check (DRC)</a></li>
		<ul>
			<li><a href="#header-5_1_1">Introduction to Maze Routing ÃÂ LeeÃÂs algorithm</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_1_2">LeeÃÂs Algorithm conclusion</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_1_3">Design Rule Check</a></li>
		</ul>
      </ul>
      <ul>
        <li><a href="#header-5_2">Power Distribution Network and routing</a></li>
	      <ul>
			<li><a href="#header-5_2_1">Lab steps to build power distribution network</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_2_2">Lab steps from power straps to std cell power</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_2_3">Basics of global and detail routing and configure TritonRoute</a></li>
		</ul>
      </ul>
	<ul>
        <li><a href="#header-5_3">TritonRoute Features</a></li>
		<ul>
			<li><a href="#header-5_3_1">TritonRoute feature 1 - Honors pre-processed route guides</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_3_2">TritonRoute Feature2 & 3 - Inter-guide connectivity and intra- & inter-layer routing</a></li>
		</ul>
		<ul>
			<li><a href="#header-5_3_3">TritonRoute method to handle connectivity</a></li>
		</ul>
	      <ul>
			<li><a href="#header-5_3_4">Routing topology algorithm and final files list post-route</a></li>
		</ul>
      </ul>
</div>

<div class="toc">
  <ul>
    <li><a href="#header-6">All commands to run the openlane flow</a></li>
  </ul>
</div>

	
<div class="toc">
  <ul>
    <li><a href="#header-7">References</a></li>
  </ul>
</div>

<div class="toc">
  <ul>
    <li><a href="#header-8">Acknowledgement</a></li>
  </ul>
</div>

# <h1 id="header-1">Day 1 -Inception of open-source EDA, OpenLANE and sky130 PDK</h1>	 
## <h1 id="header-1_1">How to talk to computers?</h1>
### <h1 id="header-1_1_1">Introduction to QFN-48 Package, chip, pads, core, die and IPs</h1>
#### chip components 
(1) **Pads:** Through which we can send the signal inside the chip.

(2) **Core:** Place where all the logic gates are fixed.

(3) **Die:** Present at the corner. it is the size of the entire chip.

**EX. RISC-V SoC**

### <h1 id="header-1_1_2">Introduction to RISC-V</h1>





## <h1 id="header-1_3">Get familiar to open-source EDA tools</h1>
### <h1 id="header-1_3_1">OpenLANE Directory structure in detail</h1>


### <h1 id="header-1_3_2">Design Preparation Step</h1>
when we enter in the OpenLANE, we have to use flow.tcl because as a name says, it will goes with the flow using the script. And by using interactive switch, we will do step by step process. without interactive switch, it will run complete flow from RTL to GDSII. Now OpenLANE is open and we can see that prompt will change now.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1a2531f3-892b-4d94-8a8c-2f8edb4daabf)

Now we have to input all the packages which required to run the flow.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3e69f11d-fc79-4b4c-8515-3ef79537f99c)

Now, here we are ready to execute the command.

Now, if we are going into the design folder in openlane, there are nearly 30-40 designs are already builted. Out of them we can open any of the design. for example, here we are opening the picorv32a.v design. In this design we can see many files are available. i.e., scr, config.tcl, etc. This config.tlc file contains every details about the design. for example, details about enrollment, clock period, clock period port etc.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a5f643dd-75de-491b-a832-5e1090c7ce51)

Here we can see that the time period is set to the 5.00 nsec. but is we see in the openlane sky130_fd_sc_hd folder, the period is set about 24 nsec. so it is not override to the main file. If it override then give first priority to the main folder.

Now, in openlane, we are going to run the synthesis, but before synthesis, we have to prepare design setup stage. for that command is " prep -design picorv32a".

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7d6d587c-da4f-4c47-8f69-07f4e5abfcc8)

so, here it is shown that preparation is completed.


### <h1 id="header-1_3_3">Review files after design prep and run synthesis</h1>

After completing the preparation, in the picorv32a file, the run terictory is created. Inside the folder, Today's date is created. so in this terictory some folders are available which is required for openlane.

In the temp file, merged.lef file is available which was created in preparation time. if we open this merged.lef file, we get all the wire or layer level and cell level information.


![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6d7e82c8-843d-48d4-96a6-2198d1fca660)

While, in the result folder is empty because till we have not run anything and in the report folder all the folders are there about synthesis, placement, floorplanning,cts,routing,magic,lvs.

now here also one config.tcl file is available similar like design folder. But this config.tcl file contains all default parameter taken by the run.

when we make some change in the origional configuration and then we run, for example if we make a change in core utilization in the floorplanning and then we run the floorplanning, at this time in the congig.tcl file, the core utility will change and by cross checking it we can check that the modification is reflected in the exicution or not.

Now coming to the openlane, we are going to run the synthesis. for that command is "run_synthesis". It will take some 3-4 mnts to run the synthesis and finally synthesis will complited.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/885b133d-49a3-4a32-86a3-4829a096e4e8)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cf5dbd02-4c62-4c7d-b88c-53718b983ac2)

### <h1 id="header-1_3_5">Steps to characterize synthesis results</h1>

From the data of synthesis, total number of counter D_flip-flops is 1613. and the number of cells is 14876.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/de4ac20d-f54a-4ac5-ae59-f5205165011b)

So, the flop ratio = (number of flip flops)/(number of total cell).

So, the flop ratio is 10.84%.

Before run, we saw that the result folder is empty. but now, after running the synthesis, we can see that all the mapping have been done by ABC.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/efb4e674-c3c9-49fc-ade6-c33521d5b455)

And in the report, we can see when the actual synthesis has done. and the actual statistics synthesis report is showing below, which is same as what we have seen before.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a1099ec5-2a9f-434f-af4f-28e34f0eabf5)


# <h2 id="header-2">Day 2 - Good floor planning considerations</h2>	 
## <h2 id="header-2_1">Chip Floor planning consideration</h2>
### <h2 id="header-2_1_1">Utilization factor and aspect ratio</h2>

In this section we will try to cover up the width and height of Core and Die. It is the first step in physical design flow to find out the width and height. Let's begin with a netlist, netlist  is two flipflops and have a simple combination logic in between. A netlist describes the connectivity of an electronic design. Here, we dependent on the dimensions of the logic gates(AND & OR) and particular flipflop. Now, let's convert the symbols into physical dimensions. We are interested in the dimensions of the Core and Die not in the dimensions of the wires. 
Let's standard cell have dimensions of 1unit*1unit
So, area= 1 Sq. units
Asuume same area for the flipflop as well = 1 Sq. units
with help of these dimensions and netlist let's calculate the area occupied by the netlist on a silicon wafer.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/abf79875-e1e3-4faf-87a6-43a12d44db8d)

Befor that will remove all the wires and bring all the flip flops and logic gates in a single plate. So after combining them together width and length will be 2 Sq. units each and if we calculate the total area the it will be 4 Sq. units. So now we have the rough calculation of minimum area occupied by the netlist.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/beb2d87b-db4f-47ac-95db-7a5586018c98)

What is 'Core' and 'Die' section of a chip?
Let's have a silicon wafer on which all the logics are implemented. In thes one section is refered as 'Die' and inside the Die we have the Core. 
A **Die** which consists of core, is small semicondcutor material  specimen on which the fundamental circuit is fabricated.
A '**Core** is the section of the chip where the fundamental logic of the design is placed.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c95ab725-89cb-46eb-929b-c00be187848e)

Now, Let's try to place that particular logic inside the core. The netlist will occupy the whole area inside the core it means it utilizes the core 100%. From this we can calculate the utilisation factor which is given by,
            Utilization Factor = Area occupied by netlist / Total area of the core
	    lets put the dimensions we have, we get
     Utilization factor = 4*1sq.unit / 2unit *2unit
                        = 4sq unit /  4sq unit
So, utilization factor = 1 (It means core has utilized all the area and no spane left)
Aspect Ratio = Height /  width =  2 unit /  2unit =  1
Whenever Aspect Ratio is 1 it signifies that chip is square shaped. When it is not 1 it means the chip is in rectangular shape.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/51360246-9ab3-4209-ba7d-d1d99bcd65ef)

For example, Lets take another dimensions of the width= 4unit and height = 2unit. So from the above formula of utilization factor we it equal to 0.5 which means the chip has not covered the whole area of the core and aspect ratio is also 0.5  which means the chip is rectangular in shape.
The leftover area can be used to placed some additional cells like buffers or something else.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/10a1d860-d6c2-4efc-95a7-d5f123cbdca3)


### <h2 id="header-2_1_2">Utilization factor and aspect ratio</h2>

Lets take another example for a square chip wth dimensions 4*4 sq units. We will get utilization factor= 0.25 it means out of the whole chip area only 25% area is utilized by the netlistand 75% is available for additional cells which can be use for routing in which we will have layering. Aspect ratio we get = 1 it means chip is square in shape.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a64a81cd-760a-44b8-a81c-93318bf49746)

**Define locations of Preplaced Cells**:-  Lets take a combinational logic which does some amount of function and assume its a huge circuit having some N Logic gates so let's devide it into some small numbers of gates. We will cut the whole circuit into two parts, and separate both of them into two blocks and both block will be implemented seperately.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/477f5715-38c7-4cb8-ab4f-6b6108839e69)

In both the blocks lets extend the input output pins and now we will black box the boxes and detached them. After black boxing, the upper portion is invisible from the top or invisible to the one , who is looking into the main netlist. now will seperate them out as two different IP's or modules.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/46f293e3-5e1a-470f-99f6-6e067310806e)

Advantage of doing this is we can reuse them multiple times after implimenting once only. Similary there are other IP's also available for eg. Memory, Clock-gating cell, Comporator, MUX  all of these are part of the top level netlist.They recieve some signals and perform functions and deliver the outputs but the functionality of the cell is implemented only once. 
The arrangement of these IP's in a chip is refferd as **floorplanning**.
These IP's have user-defined locations, and hence are placed in chip before automated placement and routing are called **"pre-placed cells"**. 
These cells are placed in such a way that, the placement and routing tool do not touch the location of the cell.


### <h2 id="header-2_1_3">De-coupling capacitors</h2>
**surround pre-placed cells with Decoupling capacitor**:- Let consider some circuit, which is the part of the blocks which has been described earlier. When some gate (let consider AND gate) switched from 0 to 1 or 1 to 0, considered amount of the switching current required because of available small capacitance . This capacitor should be completely charged to represent logic 1 and completly discharged to represent logic 0. Consider capacitance to be 0. Rdd,Ldd,and Lss are well defoned values. During switvhing operation, the circuit demands switching current i.e. peak current. Now, due to the presence of Rdd and Ldd, there will be a voltage drop across them and the voltage at Node 'A' would be Vdd' instead of Vdd.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b8b1d031-c395-4fde-8c28-25a7f2f7cfcc)

So, due to this if ideal logic 1 = 1 volt then here practically it can be less then 1 volt i.e., 0.97 volts (Vdd'). So, for any signal to be considered as Logic '0' and '1' in the NM low and NM high range. It is danger case.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/36d7fe02-ad66-4b72-be7a-998378684242)

To solve this problem,, we have to put De-coupling capacitor in parallel with the circuit. Every time the circuit switches, it draws current from Cd, whereas, the  RL network is used to replenish the charge into Cd. And the amount of current needed for the circuit is supplied by the De- Coupling Capacitor.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3547d7d2-ff77-43ba-9e69-c1e64393c1c1)

In the chip it will look something like shown below Decoupling capacitors are placed in between the block a, block b and block c. So here in this whole block it has been ensured that supply is being done by the de-coupling capacitor. Once we are done with this we have taken care of the local communication.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3078f01a-e20f-4aee-868a-9a2bb0449f71)


### <h2 id="header-2_1_4">Power planning</h2>

 Now let's consider that local circuitory and keep it as a black box and it can be repeat multiple times and there is some logic present at the boundaries also and the problem of current demand was solved by de-coupling capacitor. There is signal which is send from driver to load and the signal is basically logic 0 to logic 1. Here we need to maintain the particular driver to load line with same signal so that the load recieves the same. Now power supply is applied. Now assume 16 bit bus has to retain the same signal from driver to the load. so it should get the sufficient power from the supply. But at this bus, there is no de-coupling capacitor is available because it is not physible to put capacitor at all over the place. now, power supply is far away from the bus, that is why some voltage drop between them will occur definetly.

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7c9f6257-fb53-43e6-a5d2-bb37e703f943)


When we say one particular line of 16-bit bus is logic 1 it says that the capacitor is being charged to Vdd, and whenever we say logic 0 it says that the capacitor is discharged to ground.Let consider this 16 bit bus connected to inverter. So, all the capacitor are initially charged will get discharged and vice-versa due to inverter.


![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/77998949-b1e9-4321-a935-1f463dffc968)


But the problem is occurs due to all capacitor is connected to the single ground. This will cause a bump in 'ground' tap point during discharging. That bump is called as Ground Bounce. If the size of the bump exceeds the noise margin levelit might enter into an undefined state and due to undefined state it can either go to logic 1 or logic 0. So here thing becomes unpredictable

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/67eb5dd9-6bf5-4581-8f21-af3ad7fb8285)


Also , all capacitors which were'0' volts will have to charge to 'V'volts through single 'vdd'tap point. This will cause lowering of voltage at Vdd tap point. As long as this voltage drop is in noise margin level we are good enough but if it goes into an undefined region then things become unpredictable.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ef424a46-925a-431b-bdb8-9a210e7ca3bf)

The phenomenon we have seen was causing the lowering of the supply voltage,this problem occured because power has applied to one point only. The solution of the problem is use multiple power supply. So, every block will take charge from neartest power supply and similarly dump the charge to the nearer ground. this type of power supply is called **mesh**.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b1d49ca0-8e8a-4953-887a-19628abc3448)


And the power planning is shown below,

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/97e14546-cd7d-4eff-aa10-c93df7ae3562)

### <h2 id="header-2_1_5">Pin placement and logical cell placement blockage</h2>

**Pin Placement**
Lets take below designs for example that needs to be implemented. Here first circuit is driven by clk1  and second circuit is driven by clk2 and both has different inputs Din1 and Din2 respectively and outputs as Dout1 and Dout2.Along with that we have some preplaced cells as well as Blocka which recieves inputs from Din1 second input from Din2. We have another preplced cell as Blockb Which recieves input from clk1 and clk2 and provides a clk output. So currently we have 4 input ports Din1,Din2,Clk1,Clk2 and 3 output ports Dout1,ClkOut,Dout2

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0e1bf8ee-1b0e-452e-8a05-6b7dbbce57c7)

let's have one more design that needs to be implemented. this types of circuits are very much helpful to understand the timing analysis of inter clocks.
now complete design becomes like given below which has 6 input ports and 5 output ports. The connectivity information between the gates is coded using VHDL/Verilog language and is called as 'Netlist'.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e52f43cc-dda8-4afe-9dec-d797a5d988e0)

Let's put this netlist in the core which we have designed before and let's try to fill this empty area between core and die with the pin information. The frontend team who decides the netlist connectivity input and output and the backend team who done the pin placements. So according to the pin placements, we have to locate the preplaced blocks nearer to the inputs of the preplaced blocks.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/fcacd10f-8811-427e-be3a-3931819553c6)


Here one thing that we noticed is that clock-in and clock-out pins are bigger in size as compared to input and output pins. reason behind this is that, input clocks are conntinuously provides the signal to the every elements of the chip and output clock should out the signal as fast as possible. So, we need least resistance path for the clocks inputs and clocks outputs. So, bigger the size, lower the resistance.

One more thing is need to take care about is that, this pin placement area is blocked for routing and cell placements. so we nned to do logical cell placement blockage. this blockage is shoown in above image in between pins.
So, floor plan is ready for Placement and Routing step.

### <h2 id="header-2_1_6">Steps to run floorplan using OpenLANE</h2>

Before run the floorplanning, we required some switches for the floorplanning. these we can get from the configuration from openlane.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/67041b25-ee43-4864-9bce-fb0386d53641)

Here we can see that the core utilization ratio is 50% (bydefault) and aspect ratio is 1 (bydefault). similarly other information is also given. But it is not neccessory to take these values. we need to change these value as per the given requirments also.

Here FP_PDN files are set the power distribution network. These switches are set in the floorplane stage bydefault in OpenLANE.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2b1281f9-b85a-4b08-b507-49c39c51c434)

Here, (FP_IO MODE) 1, 0 means pin positioning is random but it is on equal distance.

In the OpenLANE lower priority is given to system default (floorplanning.tcl), the next priority is given to config.tcl and then priority is given to PDK varient.tcl (sky130A_sky130_fd_sc_hd_congig.tcl).

Now we see, with this settings how floorplan run.

### <h2 id="header-2_1_7">Review floorplan files and steps to view floorplan</h2>

In the run folder, we can see the connfig.tcl file. this file contains all the configuration that are taken by the flow. if we open the config.tcl file, then we can see that which are the parameters are accepted in the current flow.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/be2a8bf3-4857-427e-a690-5ff3241bfbd9)








 
## <h2 id="header-2_2">Library building and Placement</h2>
### <h2 id="header-2_2_1">Netlist binding and initial place design</h2>
**Bind netlist with physical cells**:- Lets we have the netlist of gates and shape of these gates represents the functionality of this gates. Foe example we have NOT gate as a tringular shape but in reality it is a box with physical dimensions it has width and height.Similarly for AND gate it also has a box shape in reality, Flipfops are also square boxes.So, we have given the physical dimensions to all the gates and flipflops. For everycomponent of the netlist we will give the particular shape with particular dimensions because ir real world the shapes like AND,OR gates does not exists so we make them as square all the blocks also have the width and height and proper shape.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/687b1d86-e4aa-48d6-9cec-f354f5b2c5eb) 

Now we will remove the wires,all the gates, flipflops and blocks are present in the shelf which is called as **Library**. A library is a place where you can find all kind of books all the gates,f/f are books here. Library also has the timing information of the perticular book like delay of the gates. Library can be devides into two sublibraries, One library consist of shape and size and other library might consist only of the delay information. Library has the various flavours of each and  every cell. Like same cell can have bigger in size in different self, bigger the size of cell lesser the resestnce path so it will work faster and will have lesser delay. We can pick up from these what we want based on the timing condition and available space on the floorplan.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8871a0f8-ddd0-419c-bbf5-fe09fe42fb49)

**Placement**:- Once we have given proper shape and size to each and every gates the next step is to take those particular shapes ans sizes and place it on the floorplan. We have the floorplan with inout and output ports, we have particular netlist, and we have particular size given to each component of this netlist. So we have the physical view of the logic gates. Next step is to place the netlist onto the floorplan. We have to take the connectivity information from the netlist and design the physical view gates on the floorplan.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7936ded3-ad15-404b-9a32-3ea64bc591b2) 

Now, we have the floorplan where we have the preplaced cells from the previous slides, Plcement will make syre that the pre placed cells locations are not affected they are kept as it as and the second thing which will be taken care of that is no cell should be placed over the pre-placed cells. We need to place the physical view of the netlist onto the floorplan in such a fashion that logical connectivity should be maintained and that particular circuit should interact with their input and output ports to maintain the timing and the delay will be minimal.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8c6fb8e4-9124-4983-be3f-757f2845ecea)


Here first we will see the arrangement of the remaining parts from the netlist onto the floorplan.We have placed all the element in such manner that all elements are closed to it's input and output pins.
But, the distance of FF1 of Stage 4 and Din4 is still far them others. By optimizing the placement, we can solve this problem.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ac32f3c9-c3a9-4320-894b-a08ab407f068)


### <h2 id="header-2_2_2">Optimize placement using estimated wire-length and capacitance</h2>
**Optimize Plecement:-** In optimize placement we will resolve the problem of distancing.Lrt's take the example of FF1 to Din2. There must be a wire going from Din2 to FF1 but before going into routing the desing or wiring we will try to estimate the capacitances. If we lokk the capacitance from Din2 to FF1 it is every huge because wire length is huge in that case even the resutance will also be huge because of that length. If we send the signal from Din2 then it will be difficult for FF1 to catch that input because distance is large. So we can place some intermediate steps to maitain the Signal integrity. By this the input is succesfully driven to the FF1 from Din2. These intermediate steps are called here Repeaters , Repeaters are basically buffers that will recondition the original signal and make a bew signal which replicate the original signal and send it forward this process repeates untill we reach to the actual cell where we want to send the input in this way signal integrity is maintained. By using repeaters we resolve the problem of signal integrity but there will be a loose of area because more and more repeaters are used more area will be used of the particular floorplan.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f47771b4-b28a-47db-b0dc-e5f13dd4c1b1)

In the stage 1, there is no need of any repeater to transmit the signal. But in stage 2, due to high distance, the lenth of wire is high and signal is not transmitted in perticular range. so we required repeater.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/52f989ab-d149-403e-8653-69de4b3a7756)

### <h2 id="header-2_2_3">Final placement optimization</h2>

As similar to stage 2, in Stage 3 also we required the buffer between gate2 and FF2.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2fc8bf91-4303-4837-b7e9-f9832d7a3723)

Stage 4 is bit tricky as compared to other stages.Now we have to check that, what we have done is correct or not. For that we need to do Timing analysis by considering the ideal clocks and according to the data of analysis, we will understand that, the placement is correct or not.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/121df907-96ad-4893-ae1d-d9fa96b7a328)

### <h2 id="header-2_2_4">Need for libraries and characterization</h2>

Every ICdesign Flow needs to go through the several steps. First step to go through is Logic Synthesis, let's say if we have a functionality which is coded in a form of an RTL so first we need to convert the functionality into legal hardware is refered to as Logic Synthesis. Ouput of the logic synthesis is arrangement of gates that will represent the original functionality that has been described using an RTL. 
Next step of logic synthesis is Floorplaning, in this we omport the output of logic synthesis and decide the size of the Core and Die. The next step after floorplaning is Placement, in this we take the particular logic cellsand place them on the chip in such a fashion that initial timing is better. Next step is CTS(Clock tree synthesis), in this we take care that clk should reach each and every signal at the same time also take care of each clk signal has equal rise and fall.Next step is Routing, routing has to go through the certain flow dependendent on the characterization of the flip flop.And now comes the last step STA(Static timing analysis), in this we try to see the set up time, hold time, maximum achieved frequency of the circuit.
One common thing across all stages 'GATES or Cells'.

### <h2 id="header-2_2_5">Congestion aware placement using RePlAce</h2>








## <h2 id="header-2_3">Cell design and characterization flows</h2>
### <h2 id="header-2_3_1">Inputs for cell design flow</h2>
In Cell Design Flow, Gates, flipflops, buffers are named as 'Standard Cells'. These standard cells are being placed in the section called as 'Library'.And in the library many other cells are available which have same functionality but the size is different.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/22c0c83e-e32e-453b-ad64-b5cef4c4d6af)

If you lokk into one of the inverter from the library the cell design flowis as follows
The inverter has to represented in form of the shape, drive strength, power charracteristic and so on. Here cell design flow is devided into three parts.

1. Inputs

2. Design steps

3. Outputs

**1)Inputs**:- Inputs required for cell design is PDKs, DRC and LVS rules SPICE models, library and user defined specs. In DRC& LVS rules tech file is provided which contains design rules and actual values. Rules can be converted in to code. SPICE MODEL tells about threshold voltage equation.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2fb42be5-76e2-4017-9ff9-4fb23306b24e)

### <h2 id="header-2_3_2">Circuit design steps</h2>
The seperation between the power rail and the ground rail defines the cell height. Cell width depends upon the timing and drive strength.

**2)design steps**:- Design involves three steps which are circuit design, layout design, characterization.
**In circuit Design** there are two steps.
First step is to implement the function itself and second step is to model the PMOS nad NMOS transistor in such a fashion in order to meet the libraray.
**3)Outputs**
The typical output what we get from the circuit design is CDL(circuit description language) file,GDSII,LEF,extracted spice netlist(.cir).


![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8e9891ea-35e0-48eb-b6f5-53376c86528e)


### <h2 id="header-2_3_3">Layout design step</h2>

In Layout Design First step is to get the function implemented through the MOS transistor through a set of PMOS and NMOS transistor and the second step is to get the PMOS network graph and the  nNMOS network graph out of the design that has been implemented.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/25c9f2db-c630-41d7-be4a-cab6f93a94af)

After getting the network graphs next step is to obtain the Euler's path. Eule's path is basically the path which is traced only once.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/117eb8be-2f24-4b7b-a5fa-052ef4b3bd43)

Next step is to draw stick diagram based on the Euler's path. This stick diagram is derived out of the circuit diagram.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a89a6f84-fa7e-4a36-9af7-74ab04f5b5c3)



Next step is to convert this stick diagram into a typical Layout, into a proper layout and then get the proper rule we have discissed earlier. Once we get the particular layout then we have the cell width, cell length and all the specifications will be there like drain current, pin locations and so on.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7917c567-5aa7-4c66-b8ab-43e0e4808e06)

Next and Final step is to extract the parasatics of that particular layout and charaterise it in terms od timing. So before that the output of the layout design will be GDSll. Once you get the extracted spice netlist then we characterize it. Characterization helps in getting timing, noiseand power information.

### <h2 id="header-2_3_4">Typical characterization flow</h2>

Let's try to build the characterization flow based on the inputs we have,
First step is to read in the model, second step is to read the extracted spice netlist, third step is to define or recognize the behaviour of the buffer, fourth step is to read the subcircuits of the inverter and then in the fifth step need to attach the necessary power supplies, sixth step is to  apply the stimulus then in the seventh step we need to provide the necessary output capacitance then in the final eighth step in which we need to provide necessary simulation command for example if we are doinf transent simulation so we need to give .tran command , if we are doing DC simulation then we give .dc command.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/78e61e38-0569-4ffb-8b67-0d90cefbfe0b)

Next step is to feed in all this inputs from 1 to 8 in a form of a configuration file to the characterization software **"GUNA"** . This software will generate power, noise and timing model.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/19b01aa6-c6ba-4d39-8d10-539a40ab9f39)

## <h2 id="header-2_4">General timing characterization parameters</h2>
### <h2 id="header-2_4_1">Timing threshold definitions</h2>


As seen in the previous section we have inverter connected back to back, we have power sources, we have the stimulus applied to the inverter all these things brings a very important point of understanding differenet threshold points of a waveform itself and it is called as "Timing threshold definitions'.
in the figure below the term 'Slew_low_rise-thr' depicts the value close to 0. and the typically value of this is about 20% it could be 30% as well.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3819e09b-be65-480b-b01b-dab709ef687b)

Slew_high_rise_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d8134157-d13c-49b3-9ec2-ef50e8ff1bf7)


Slew_low_fall_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cca7ece5-603a-46b4-b781-9c82b3d14f9b)


Slew_high_fall_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3e5dd161-ff39-4a74-89da-06a642835f14)


NOw, taking the waveform of input stimulus which is input of the first buffer and with that taking output of the first buffer.Similar as a slew, thresolds are for delay also available. for that same as slew, we have to take some rise and fall points from the waveforms. this tresolds are almost 50%.

in_rise_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/eb232344-b6d9-4de0-b351-9910214a8fbc)

in_fall_thr , its typical value is 50%.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b40bb02f-aac3-4635-9615-d7e95901aa08)

out_rise_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9e16ea11-c75e-40da-91d8-82baa271b7d8)

out_fall_thr

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2cb0db7d-8dcb-41bb-b0d9-b2b10e8eb31b)

Based on these above value we are goin to calculate the further values like propogation delay, current,slews etc.

### <h2 id="header-2_4_2">Propagation delay and transition time</h2>























































































