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



