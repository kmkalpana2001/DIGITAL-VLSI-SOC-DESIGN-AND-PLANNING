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
**Arduino Board**:- This is an arduino microcontroller board. The encircled area shows the chip(microprocessor) which is interfaced with other components of the board. The designing of this chip from abstract level all the way down to the fabrication is done by RTL to GDSll flow.Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a piece of software, or IDE (Integrated Development Environment) that runs on the computer, used to write and upload computer code to the physical board.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ff3696b5-cf69-41dd-86e5-160875e8eaba)


#### chip components 
(1) **Pads:** Through which we can send the signal inside the chip.

(2) **Core:** Place where all the logic gates are fixed.

(3) **Die:** Present at the corner. it is the size of the entire chip.

**EX. RISC-V SoC**:- It consist of SRAM,SOC,ADC,DAC,SPI these all are called foundary IP's.All devices depends upon foundary where all chips are fabricated using deposition and lithography techniques and so on.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0900c16a-29b9-47fd-84bd-28b7249a2938)


### <h1 id="header-1_1_2">Introduction to RISC-V</h1>
RISC-V, where five refers to the number of generations of RISC architecture that were developed at the University of California, Berkeley. RISC is an open standard instruction set architecture (ISA) based on established RISC principles. Unlike most other ISA designs, RISC-V is provided under open source licenses that do not require fees to use. A number of companies are offering or have announced RISC-V hardware, open source operating systems with RISC-V support are available, and the instruction set is supported in several popular software toolchains.

The instruction set is designed for a wide range of uses. The base instruction set has a fixed length of 32-bit naturally aligned instructions, and the ISA supports variable length extensions where each instruction can be any number of 16-bit parcels in length. The instruction set specification defines 32-bit and 64-bit address space variants. The specification includes a description of a 128-bit flat address space variant, as an extrapolation of 32 and 64 bit variants, but the 128-bit ISA remains "not frozen" intentionally, because there is yet so little practical experience with such large memory systems.
Chip is connected to the package with the help of bond wires.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d3bfdac2-c95c-49dd-bdab-223a42692197)


### <h1 id="header-1_1_2">From Software Applications to Hardware</h1>
Here we will se how apps runs on the system?

Application Software - System Software - Hardware chip

Apps enters into a block of system software and system sodtware converts the entire program into binary language. There are some layers inside the system software whish are as follows

**Operating System, Compiler, Assembler**

 Operating system handles input/output operations and allocate memory also it manage the low level system functions.

 Compiler takes the output from the operating system as C,C++,Java and convert them into intsructions. These instructions depends upon hardware.

 Assembler take the instructions from compiler and convert them into respective binary numbers. This binary language now send to hardware and hardware performs ouput based on the function it recieve and gives the output.
Instruction acts as abstract interface between C-language and the hardware.

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/681544f8-bc0b-4967-85f3-96cb2e764adb)
 

 ## <h1 id="header-1_2">Soc design and OpenLANE</h1>
### <h1 id="header-1_2_1">Introduction to all components of open-source digital asic design</h1>
To design Digital ASIC, few tools or things which are required from the day one. These are

**RTL Design
EDA tools
PDK data**
**what is RTL design?**
In digital circuit design, register-transfer level (RTL) is a design abstraction which models a synchronous digital circuit in terms of the flow of digital signals (data) between hardware registers, and the logical operations performed on those signals.for this designs many open sorces are available. like, librecores.org, opencores.org, github.com, etc...

**What is EDA tools?**
The term Electronic Design Automation (EDA) refers to the tools that are used to design and verify integrated circuits (ICs), printed circuit boards (PCBs), and electronic systems, in general. many open sorces tools are available like Qflow, OpenROAD, OpenLANE, etc...

**What is PDK Data?**
PDK is process design kit. It is interface between FAB and design. This data is collections of files like,

process design rules: DRC, LVS, REX
Digital standerd cell libreries
i/o librerirs
etc.....
which are used to model a fabrication process for the EDA tools used to design an ICs. for example, in 2020, google release the open source PDK for FOSS 130nm production with the skywater technology. But right now it is at cutting age of the 5 nm also. But in many applications, the advance node is not required, and the cost of advanced node is also high as compared to 130nm processors. This 130nm processors are also fast processor. for example,
intel: P4EE @3.46 GHz(Q4'o4)
sky130_OSU (single cycle RV32i CPU) pipeline version can achieve more than 1 GHz clock.

### <h1 id="header-1_2_2"> Simplified RTL2GDS flow</h1>

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/bfa1cad8-6338-4306-8ce2-446f7bec8c92)

**Step 1. Synthesis**:-  In the synthesis, the design RTL is translated to a circuit out from the SCL. The resultant circuit is describes in HDL and usualy refered to the gate level netlist. the gate level netlist is functionaly equivelent to the RTL. "standard Cells" have regular layouts like Electrical. HDL,SPICE

**Step 2. Floor/Power Planning**:-The main objective here is that to plan silicon area and distribute the power to the whole circuit. In the chip floor planning, the partition chip die between different system building blocks and place the i/o pads. In micro floor planning, we define the dimensions, pin locations, rows.
In power planning, the power network is connstructed. tipically, the chip is power by multiple VDD and GND. so, total components are connected to power supply horizontaly and vertically by metal streps. here parallel structures are used to reduce the resistance. To address the electromagnetization problem, power distribution network uses upper metal leyers, which are thicker than lower metal layers. Hence have less resistance.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4037aad0-4da5-477f-a46f-0cf62d8ea68c)

**Step 3. Placement**:- In this process, we place the gate level netlist on the floor planning rows, alligned with the sites. cells should be placed very closed to eachother to reduce the interconnnect delay. Usually placement is done in 2 steps:

**Global placement**:- It is very first stage of the placement where cells are placed inside the core area for the first time looking at the timing and congestion. Global Placement aims at generating a rough placement solution that may violate some placement constraints while maintaining a global view of the whole Netlist.

**Detailed placement**:- In detailed placements, we determined the exact route and layers for each netlist. the objective of detailed placement is valid routing, minimize area and meet timing constrains. Additional objective is minimum via and less power.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4834af5e-a20a-48b6-987a-4b2d7102d787)

**Step 4. Clock Tree Synthesis**:- Before routing the signals, we have to route the clock. In the process of clock synthesis, we have distribute the clock to the every sequential elements. for example flipflops, registers, ADC, DAC ete. basically clock netwroks looks likes a tree. where the clock source is roots and the clock elements are end leaves. Synthesization should be done in a manner that with minimum skew and in a good shape.To minimize the clock skew by using the low-skew global routing resources for clock signals.Microsemi devices provide various types of global routing resources that significantly reduce skew.Usually a tree is a H tree, X tree etc.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/32d071b0-b762-4670-af57-708abb963744)

**Step 5. Routing**:- After routing the clock, the signal routing comes. Making physical connections between signal pins using metal layers are called Routing. Routing is the stage after CTS and optimization where exact paths for the interconnection of standard cells and macros and I/O pins are determined. There are two types of nets in VLSI systems that need special attention in routing:

Clock nets
Power/Ground nets
The sky130 PDK defines the 6 routing leyers. the lowest leyer is called local interconnect layer (titanium nitride layer). Other five layers are alluminium layersIn the proccess of routing, metal trackes forms a routing grids and these grids are huge. so, devide and conquer approach is use for routing. The two types of routing is used:

**Global routing:** Generates the routing guides
**Detailed Routing:** Uses the routing guides to implement the actual wiring.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ec0b01e0-046f-47e2-b2f3-e91582e4f9e4)

**Step 6. Sign Off**:- Once the routing is done, we can construct the final layout. This final layout will goes under the verification. Two types of verifications are there:

Physical verification: Here design rule checking will done and it will check the final layout and owners layout
Timing Verification: Here Static Timing Analysis will done.


### <h1 id="header-1_2_3">Introduction to OpenLANE and Strive chipsets</h1>

OPENLANE is an automated RTL to GDSII flow that is composed of several tools such as OpenROAD, Yosys, Magic, Netgen, Fault, CVC SPEF-Extractor, CU-GR, Klayout and a number of scripts used for design exploration and optimization. It is started as an Open-source flow for a true Open Source tape-out Experiment. striVe is a family of open everything SoCs:
Open PDK, Open EDA, Open RTL

striVe SoC Family

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1e6d2791-89d0-419d-b392-c35ddadc356d)

The main goal of OPENLANE is to produce a clean GDSII with no human intervation (no-human-in-the-loop). here the meaning of clean is that:
No LVS violations
No DRC Violations
No timing Violations
OPENLANE is tuned for skyWter130nm open PDK. it can be used to harden Macros and chips.there is two mode of operation
Autonomus : it is the push botton flow. with the push botton , it is a some time base design and due to this push botton, we get final GDSII
interactive : here we can run comamds and steps one by one.
It has large number of design examples(43 designs with their best configurations).


### <h1 id="header-1_2_4">Introduction to OpenLANE detailed ASIC design flow</h1>

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f46800c7-53cc-4541-b8eb-fd3fe9422cc6)

The design exploration utility is also used for regression testing(CI). we run OpenLANE on ~ 70 designs and compare the results to the best known ones.

**DFT(Design for Test)**
it perform scan inserption, automatic test pattern generation, Test patterns compaction, Fault coverage, Fault simulation.After that physical implementation is done by OpenROAD app. physical implementation involves the several steps:

Floor/Power Planning

End Decoupling Capacitors and Tap cells insertion

Placements: Global and Detailed

Post Placement Optimization

Clock Tree synthesis (CTS)

Routing: Global and Detailed

Every time the netlist is modified.(CTS modifies the netlist and Post Placements optimization also modifies the netlist).so for that verification must be performed. The LCE(yosys) is used to formally confirm that the function did not change after modifying the netlist. ### Dealing with antenna rules Violation: when a metal wire segment is fabricated, it can act as antenna.as an antenna, it collect charges which can demaged the transister gates during the fabrication.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/be8630b5-1b3d-4061-a636-8ecbbed1669e)


To address this issue, we have to limit the lenght of the wire. usually this is the job of the router. If router fails to do this, then there are two solutions:
Bridging attaches a higher layer intermediary.Add antenna diode cell to leak away charges.(Antenna diodes are provided by the SCL)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c1ff8bd1-2951-44ae-8a4e-aa31d63e0322)


With OpenLANE, we took a preventive approach. here we add fake antenna diode next to every cell input after placement. Then run the Antenna checker on the routed layout. If the checker reports a violation on cell input pin, replace the fake diode cell by a real one.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9448d09a-5647-4b60-986c-d1e8f8f16309)


**Static Timing analysis(STA)**
It involves the interconnect RC Extraction(DEF2SPEF) from the routed layout, followed by STA on OpenSTA(OpenROAD) tool. resulting report will shows the timing violations if any violations is there.

**Physical Verification (DRC and LVS)**
Magic is used for design Rules checking and SPICE Extraction from Layout. Magic and Netgen are used for LVS.



## <h1 id="header-1_3">Get familiar to open-source EDA tools</h1>
### <h1 id="header-1_3_1">OpenLANE Directory structure in detail</h1>
**Basic Linux Commands**

**cd** : opens the particular folder

**ls** : lists the content of the folder

**pwd** : shows the present working directory

**mkdir** : to make a new directory

**command --help** : shows the complete use that command

**clear** : clears the terminal screen

Here we are working in Sky130_fd_sc_hd PDK varient. where, "sky130" is process name or node name."fd" is a foundary name (skyWater foundary)."sc" means standerd cell librery files and the last one "hd" stands for high density(basically one type of varient).

Sky130_fd_sc_hd varient contains many technology files like verilog, spice, techlef, meglef,mag,gds,cdl,lib,lef,etc. (techlef file contains the layer information).


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

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/36985c6b-3e9f-473d-ab32-29b224cff6f1)

To watch how floorplane looks, we have to go in the results. in the result, one def( design exchange formate) file is available. if we open this file, we can see all information about die area (0 0) (660685 671405), unit distance in micron (1000). it means 1 micron means 1000 databased units. so 660685 and 671405 are databased units. and if we devide this by 1000 then we can get the dimensions of chips in micrometer.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cb35a72a-6fa7-402b-a0ed-8010ffdcccd3)

so, the width of chip is 660.685 micrometer and height of the chip is 671.405 micrometer.
To see the actual layout after the flow, we have to open the magic file by adding the command magic -T /home/kunalg123/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def

And then after pressing the enter, Magic file will open. here we can see the layout.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/bc916128-b14b-4d46-af0c-296f39dafb5f)


### <h2 id="header-2_1_8">Review floorplan layout in Magic</h2>
In the layout we can see that, input output pins are at equal distance.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f02464f8-3bbc-4475-90a6-1d523ba36857)


after selecting (To select object, first click on the object and then press 's' from keyboard. the object will hight lited. to zoom in the object, click on the object and then press 'z' and for zoom out press 'sft+z') one input pin, if we want to check the location or to know at on which layer it is available, we have to open tkcon window and type "what". it will shows all the details about that perticular pin.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5dc0a65b-4216-4879-b786-e4de4319dfc4)


so, it show that the pin is in the metal 3.similarly doing for the vertical pins, we find that this pin is at metal 2.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b934b69a-5357-4b4d-a51a-e66cd352fb6c)


Along with the side rows,the Decap cells are arranged at the border of the side rows.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e5f09e25-ff25-411b-aacc-74ae3df0ae61)



here we can see that first standerd cells is for buffer 1. similarly other cells are for buffer 2, AND gate etc.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e0624489-5298-45cd-a08d-db2b3ec572b7)


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

Right now we are not constrain about timing, but constrain about the congestion. so, we are making the congrstion is less.

The placement is donne in two stages. Global and detailed. In global placement, legalization is not happened but after detailed placement legalization will be done.

When we run the placement, first Global placement is happens. main objective of glibal placement is to reducing the length of wires.

Now opening the Magic file to see actual view of standerd cells placement.And the actual view in the magic file is given below.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d7e29ff0-f009-4c72-9129-d7662b46f8b8)

If we zooom into this, we find the buffers, gates, flip flops in this.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/768d1fbd-c7b4-4b15-bbd5-cebd57a1c79a)



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


### <h2 id="header-2_4_2">Propagation delay and transition time</h2>

Based on these above values we are going to calculate the further values like propogation delay, current,slews etc.
If we want to calculate the delay of anything we need to subtract the out_rise_thr from in_rise_thr. Here let's take typical value 50%, let's see on the particular waveform how does it works
Time delay = Time(out_thr)-time(in_thr).

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d157a7da-02ba-44d7-9acf-90899273eb7f)

In the above example in_rise_thr and out_fall)thr was kept at 50%. But if the threshold ponit moves to the top the the output comes before the input and we see negative delay and negative delays are not accepted. So the reason behind having this negative delay is poor choice od threshold point so thr choice of the threshold point is really important.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6540a5e2-cf40-4202-994e-e7ff05d6d60f)

Let's take another example where we have choosed threshold point correctly but still can get a negative delay. Because uotput comes before the input that's why we are getting negative delay here, which is not accepted

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/03a0e311-2552-4a40-8345-9075f655fdee)

**Transition time**=  time(slew_high_rise_thr)- time(slew_low_rise_thr)

or

transition time = time(slew_high_fall_thr)- time(slew_low_fall_thr)
Let's say we have the waveform to understand the slew calculation.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2f7d8314-e195-48fc-98f3-b20441352242)

# <h3 id="header-3">Day 3 - Design library cell using Magic Layout and ngspice characterization</h3>	 
## <h3 id="header-3_1">Labs for CMOS inverter ngspice simulations</h3>
### <h3 id="header-3_1_0">IO placer revision</h3>
Till now, we have done floor planning and run placement also. But if we want to change the floorplanning, for example, in our floor planning, pins are at equal distance and if we want to change it then we can also make it by "Set" command.

For that first we have to check the swithes in the configuration and from that we have to take the syntax "env(FP_IO_MODE) 1". and make it to the "env(FP_IO_MODE) 2". then again run the floorplanning.

Then check the changes in the pins location through magic -T.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e547b9d4-7ffe-4f78-a73a-a9178ab72142)

So, here we can see that there are no pins in the upper half side. all pins are in the lower half of the core.


### <h3 id="header-3_1_1">SPICE deck creation for CMOS inverter</h3>

**VTC- SPICE simulations**:-Here first part is to create SPICE deck, it's the connectivity information about the netlist so basically it's a netlist.It has input that are provided to the simulation and the deck points which will take the output.

**Component connectivity**:- In this we need to define the connectivity of the substrate pin. Substrate pin tunes the threshold voltage of the PMOS and NMOS.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5ab978a9-96ae-41ee-80b2-737a01eb26e6)

**Component values**:- Values for the PMOS nad NMOS. We have taken the same size of both PMOS and NMOS.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/be67d51c-8d97-4a09-9007-1a61101112ba)

**Identify the nodes**:- Node mean the points between which there is a component.These nodes are required to define the netlist.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1aded7c7-a96f-4dd2-9f63-aea58e2fad16)

**Name the nodes**:- Now we wiil name these nodes as Vin, Vss, Vdd, out.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/315c2ee6-5f34-405c-8791-c44e7e6ebb86)

Now we will start writing the SPICE deck. It's written like shown below

Drain- Gate- Source-  Substrate

For M1 MOSFET drain is connected to out node, gate is connected to in node, PMOS transistor substrate and Source is connected to Vdd node. 

For M2 MOSFET drain is connected to out node, gate is connected to in node, NMOS source and substrate are connected to 0.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3e3fac0c-021e-4b3d-b1ae-11f437bf8f4d)


### <h3 id="header-3_1_2">SPICE simulation lab for CMOS inverter</h3>

Till now we have described the connectivity information about CMOS inverter now we will describe the other components connnectivity information like load capacitor, source. Let's seee the connectivity of output load capacitor.

It is connected between out and the node 0. And it's value is 10ff. Supply voltage(Vdd) which is connected between Vdd and node 0 and value of it is 2.5 , Similarly we have input voltage which is connected between Vin and node 0 and its value is 2.5.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/38bf54d3-95cd-4bb4-8bf3-db767a76550c)

Now we have to give the simulation commands in which we are swiping the Vin from 0 to 2.5 with the stepsize of 0.05. Because we want Vout while changing the Vin.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/352b8f5d-5109-4a2c-9c2e-de63c43b2f7f)

Final step is to model files. It has the complete description about NMOS and PMOS.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/03d4797a-3c88-42e2-9202-30f79922f28c)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d8c67c04-a6c8-4016-8d8a-dc89fefbbd41)

Now we will do the SPICE simulation for the particular values. And will get the graph.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/dd03eb88-a3b3-4cc2-9d0f-26fde325e723)

Now, doing other simulation in which we change the PMOS width to 3 times of NMOS width. and after diong the simulation, we get the graph like this shown below

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4a0d7457-cbda-4121-8f4c-3a8dc46f9c55)

The difference between these two graphs is that in the second graph the transfer charactoristic is lies in the ecxact middle of the graph where in the first graph it is lies left from the middle of the graph.


### <h3 id="header-3_1_3"> Switching Threshold Vm</h3>

These both model of different width has their own application. By comparing this both waveform, we can see that the shape of the both waveform is same irrespective of the voltage level.It tells that CMOS is a very roboust device. when Vin is at low, output is at high and when Vin is at high, the output is at low. so the charactoristic is maintain at all kind of CMOS with different size of NMOS or PMOS. That is why CMOS logic is very widely used in the design of the gates.

Switching thresold, Vm (the point at which the device switches the level) is the one of the parameter that defined the robustness of the Inverter. Switching thresold is a point at which Vin=Vout.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6b53f54e-b3a3-47ab-b632-a3e734d11615)

In this figure, we can see that at Vm~0.9v, Vin=Vout. This point is very critical point for the CMOS because at this point there is chance that both PMOS and NMOS are turned on. If both are turned on then there are high chances of leakage current(Means current flow direcly from power to ground).

By comparing this both the graph we can understang the concept of switching thresold voltage.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4e6885bc-da70-4f86-8715-451f7e90e1dd)

In the graph below we can identify that the PMOS and NMOS are in which region. The direction of current flowing is different for NMOS nad PMOS.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1e8aa0ce-1524-4c57-9c44-b3162dc94a2c)


### <h3 id="header-3_1_4"> Static and dynamic simulation of CMOS inverter</h3>

In Dynamic simulation we will know about the rise and fall delay of CMOS inverter and how does it varying with Vm. In this simulation everything else will remian same except the input which is provided will be a pulse and simulation command will be .tran

The graph Time vs Voltage will be plotted here from where we can calculate the rise and fall delay.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6b3926ab-2fb7-46a2-b1c5-aa65c8105f38)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c26fe6c9-73f1-4e96-9098-708cce913129)



### <h3 id="header-3_1_5"> Lab steps to git clone vsdstdcelldesign</h3>

To get the clone, copy the clone address from reporetery and paste in openlane terminal after the command "git clone". this will create the folder called "vsdstdcelldesign" in openlane directory.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a2af6024-46c9-47fd-9662-34a1563cff3c)

now, if we open the openlane directory, we find the vsdstdcelldesing folder in the openlane directory.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3e50b424-ea04-4e7a-bc2c-801f1077e641)

Now if we goe to the vsdstdcelldesign folder and open it, we get the .mag file,libs file etc.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7e3663c6-5125-45c8-a246-b540e03bbd58)

now, let's open the .mag file and see that which layers are used to build the inverter. But before opening the mag file, we need tech file. so we will copy this file from this given below address,
And do copy by "cp" command to the location which is given below.Now, we can see that this file is copied in the vsdstdcelldesign folder.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/90704094-baa9-437d-ae9b-2587452ca920)

Now, here to see the layout in magic, we don't need to write the whole address because we copy the tech file here.Now, we can see the layout of CMOS inverter in the magic like this.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/43015161-9f70-4793-9c1b-41c743cdb5b3)


## <h3 id="header-3_2">Inception of layout ̂A CMOS faabrication process</h3>
### <h3 id="header-3_2_1">Create Active regions</h3>

**1) selecting a substrate**:- we have a p-type silicon substrate having high resistivity(5-50ohm) well dopped, and orintation(100).

**2) creating active region for transistor**:- Region where you see PMOS and NMOS. On p-type substrate we are going to create some small pockets which will be called as active region and in these pockets we are going to create PMOS and NMOS transistor. Will cretae isolation between each and every pockets. 

We create the isolation layer by depositing the Sio2 layer (~40nm) on the substrate. Now, we are depositing the Si3N4 layer (~80 nm) on the Sio2 layer.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9bca2b5b-622a-4d3a-abed-1b0077d44065)

Before creating the pocket identify the region where we need to crete the pocket. Now will deposite a layer of photoresist(~1um) on which we will create some mask1 using UV light.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2ad424e2-c9ab-4e50-8182-9a5f841fcd74)

Unwanted area has been exposed using UV light. And we get pattern the exposed area is getting washed away.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/124dd0ca-4531-4482-b05f-da1585ba2204)

In the next step mask will be removed and doing etching of Si3N4 layer on the exposed area.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/536dc391-5fb5-46c2-9c3c-a14cb2cad640)

Now, next step is to remove photoresist by chamical reaction, because now to Si3N4 layer itslef behaves like good protecting layer for Sio2 layer. now,We will place it in the oxidation furnace. if we do LOCOS (local oxidation of silicon) process, the exposed sio2 part will grow and bird break also form. This grown sio2 will provide the perfect isolation between two PMOS and NMOS. This is how we protect two transistor communicating with each other.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e4f0bf05-69e2-44f2-b3f6-66802a218e2a)

Next step is to remove the Si3N4 using hot phospheric acid.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d3e25e70-6a27-4fe3-a0b6-bd46dc5c028d)


### <h3 id="header-3_2_2">Formation of N-well and P-well</h3>

**3) N-well and P-well formation**:- we can not form P-well and N-well at a same time. we have to protect a region while forming one of the region by photoresist. And then using mask 2 and UV light, we will do patterning of photoresist to form P-well.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2ecf0ef6-2c39-42c0-b19c-a82ef972699a)

Now, the area where we want to form the P-well is exposed. now we remove the mask and by applying the ion implantaton method (~200kev)to form P-well using Boron. But still it is P implant. After performing the high temparature anneling, it will become P-well.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/be5f46e2-de29-4039-931d-fa0ed5820f45)

We wiil do a similar process to form N-well by using mask 3 and using Phosphorus ions.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5cea8915-867f-4bbc-a77b-b937fe28bc80)

Till now depth of wells are not define. so, by putting into the high temparature furnace (drive-in diffusion), we will define the depth of wells.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/82f3e2c7-bd33-41aa-991e-b59550e50d99)


### <h3 id="header-3_2_3"> Formation of gate terminal</h3>

**4)Gate formation**:- Gate terminal is the most important terminal of the PMOS and NMOS because from the gate terminal only we can control the thresold voltage. doping concentration and oxide capacitance will control the thresold voltage.so, first we are maintain the doping concentration here. for that we use mask 4 and again doing the ion implantation of boron ion at lower energy (~60kev).

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1ccc4ea2-47db-439b-a430-9f1adf241910)

same process we will repeat for N-well also by using mask 5 and Arsenic ion.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/04d59a3e-028c-49c4-81ec-ce06e5e42089)

Next step is that we have to fix the oxide layer. but before that we have to remove the oxide layer because this layer is got dammeged because of the privious processes. so,first we remove the layer using HF solution and again re-grown the high quality oxide layer with same thickness.

The final step is the deposition of polysilicon layer over oxide layer with more impurities for low resistance gate terminal.Then etched out this polysilicon layer by using mask 6 and photoresist.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4b4d2b2c-c42b-431c-b08f-d507229b28ee)

After etching, remove the photoresist and gate terminal looks like,

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/70ac48ac-1626-4cab-b066-ec01b969940b)


### <h3 id="header-3_2_4">Lightly doped drain (LDD) formation</h3>

**5) LDD formation**:- Here, we actully want P+,P-,N doping profile in the PMOS and N+,N-,P doping profile for NMOS. Reason for that is

Hot electron effect

short channel effect

For the formation of LDD, we again do ion implantation in P-well by using mask 7 and here we use phosphoros as a ion for light doping.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/637bc28f-5b4e-45ad-9399-e7715837d3a0)

Same process we will repeat for N-well. there we use mask 8 and BOron Ion.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/715a33d9-f6f1-4cd9-a821-b7142a2c8073)


Now, by creating the spacers, we can protect the actual structre remain constant of P-implantt and N-implant. For that we deposite a thick Sio2 or Si3N4 layer over the gate tereminal.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/529ec3e5-7f57-4c5b-b30a-eddf10e9f183)

Now, we do Plasma anisotropic etching. By that side-wall spacers are formed.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cc82a672-8f0d-490d-b371-6b70a41ee433)


### <h3 id="header-3_2_5">Source ÃÂ drain formation</h3>

**6)source-drain formation**

Next step is deposite the very thin screen oxide layer to avoid the effect of channeling.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/60ebcafa-9b72-4b33-b0c3-8efca8fb0b0f)

Now to form the drain and source, again we do the ion implantation of arsenic at 75kev to create the N+ implant by using mask 9 in the P-well to form PMOS.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4f3edbee-232d-403c-b8b1-d35994ca8bb6)


Same process we will repeat for NMOS by using the mask 10 and boron ion in the N-well at 50kev to creat P- implant.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8c6fa089-b4e9-4872-bbf5-e8f1ac2bffd5)

Now we put this Half made CMOS into the high temparature (1000 degree)anneling. So P+ implant and N+ implant now become the source and drain.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/38520c60-20cc-4c83-affc-16876beacab3)



### <h3 id="header-3_2_6">Local interconnect formation</h3>

**7)steps tp form contacts and local interconnects**:- First step is remove the thin screen oxide layer by etching. Then deposite the titanium (Ti) using sputtering. here Ti is used because Ti has very low resistivity.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2cc79d8a-6cdc-4959-be74-1bcad07909e2)

Next step is to create the reaction between Ti layer and source, gate, drain of CMOS. For that wafer is heated at about 650-700 degree temparature in N2 ambient for about 60 seconds. and after reaction, we can see the titanium siliside over the wafer. One more reaction is heppend there between Ti and N. and it results the TIN which is used for local communication.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3079655b-32a0-4a89-94bd-1d117056d330)

Now by using mask 11 and photoresist, we will etched out the TIN and make perticular contacts. TIN is etched out by using RCA cleaning.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/90d2f632-eda4-477f-8126-73c2f9bb1c46)

Now, local interconnects are formed after etching and removing the photoresist.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8ac4e88d-58b7-4edd-bc40-af6e57f61cf0)


### <h3 id="header-3_2_7"> Higher level metal formation</h3>

**8)Higher level metal formation**:- These steps are very semilar like previous steps. First thing that we are noticing is that the surface is non planner. it is not good to use this type of non planner serface for matel interconnects because of the problems regarding the metal disconinuty. so, we have to plannerize the surface by depositing the thick layer of sio2 with some impurity to make less resistive layer. and then we used CMP (chemical mechanical polishing) technique to plannerise the surface.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ef768dbd-78c1-4ab6-b527-418e6e6b3587)

Now using mask 12 and photorsist we etched the sio2 layer to diposite the metal in it.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/412b9665-d2af-4309-a6ea-4055b3aca9a4)

Now remove the photoresist and seposite the thin later of TIN (~10nm) over the wafer. Because TiN is act as very good adession layer for sio2 and also act as a barrier between bottom layer and top layer of metal interconnects.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b2160026-0d08-45bb-a057-284c68107c50)

Next step is to deposite the blanket tungsten (W) layer over the wafer. and then do the CMP here to plannerize the surface.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c7092e04-a09c-48e9-8580-cfc62a394b4f)

This W is act as a contact holes and this holes needs to connect to the Higher metal layer. so we will deposite the Al (aluminium) layer.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/298cc45d-b5c4-44d9-b999-f2ab20d6cf15)

Then by using the mask 13 and photoresist, we etched the W layer out to form the contact at perticular place by Plasma etching.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c0ef4f54-d5d4-4358-acda-ff956151dda3)

This is our first level of metal interconnets. now we again do the same process as above to deposite the second level of metal interconnect by using mask 14 for etched out the sio2 and using mask 15 for etched out Al leyer.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/00e4b8b6-8f80-4f0f-b472-1490674126f7)

The upper layer of Al is bit thicker as compared to lower layer of Al.Now, again deposite the layer of sio2 or si3N4 to protect the chip.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6df94765-37ea-4a47-8931-9381446afd31)

And finally our CMOS is looks like this after the fabrication.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ffcc1402-44ae-4a4c-8a82-06752bdc0fb1)



### <h3 id="header-3_2_8"> Lab introduction to Sky130 basic layers layout and LEF using inverter</h3>

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f6e17f1a-9dc0-4718-bb29-87cf3490f61c)

In sky130, every color is showing the different layer. here the first layer is for local interconnect shown by blue_purple color, then second layer is metal 1 which is shown by light purple color, and the metal 2 is shown by pink color. N-well is shown by solide das line. green is N-diffusion region. and red is for polysilicon gate. similarly the brown color is for P-diffusion.

In tckon window, we can see that the selected area is NMOS and similarly we can chech PMOS also. and that is how we can check that the CMOS is working or not.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ecaed121-2348-4cd7-b4fc-e89b64c9a0f1)

similarly we will check for the output terminal also.(by double pressing "S" to select the entire thing at output Y).

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/12f5c601-e2a7-4fe6-815d-bf27d7a8a117)

so, we can see that "Y" is attached to locali in cell def sky130_inv.
we can check the source of the PMOS is connected to the ground or not. and similarly we can check it for NMOS also.



### <h3 id="header-3_2_9">Lab steps to create std cell layout and extract spice netlist</h3>

To extract the file from here, we have to write the command in tckon window. and the comand is "extract all".

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/264e9dd3-3ac5-4ede-a898-dd2f1c5ad83e)

Now let's go to this location from the terminal. it is exctracted.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/802fa021-ce0c-4797-a464-157ed84737a4)

we will use this .ext file to create the spice file to be use with our ngspice tool. for that we have apply the comand "ext2spice cthresh 0 rthresh 0". this will not create anything new. now again we have to type "ext2spice" comand in tckon window.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5d92bc3e-ccd2-4629-9944-b67bb6af5d24)

so, now we are checking the location and at there spice file has been created.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/00f61462-b458-4856-92f2-0bf8a487344b)

let's see what inside the spice file by "vim sky130_inv.spice".

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/87e9816d-955a-4039-bb27-3176a5a16fb7)


## <h3 id="header-3_3">Sky130 Tech File Labs</h3>
### <h3 id="header-3_3_1">Lab steps to create final SPICE deck using Sky130 tech</h3>

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f7190142-b08e-49c4-808f-81758b72b54e)

here, we can see the all details about the connectivity of the NMOS and PMOS and about the power supply also.

X0 is NMOS and X1 is PMOS and both's connectivity is shown as GATE DRAIN SUBSTATE SOURCE.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/62bac9f9-d70f-420f-905d-5a8e50691b16)

Now we have to include the PMOS and NMOS lib files. it is inside the libs folder in the vsdstdcellsdesign folder.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4369412f-e9bb-4882-93f0-76d2b13b5b43)

so, now we include this file in the terminal by ".include ./libs/pshort.lib" and ".include ./libs/nshort.lib" comand.

And then set the supply voltage "VDD" to 3.3v by "VDD VPWR 0 3.3V" comand. and similarly set the value of VSS also.

Now, we need to specify the input files. by Va A VGND PULSE(0V 3.3V 0 0.1ns 2ns 4ns).

Also add the comand for the analysis like, ".tran 1n 20n", ".control" , "run",".endc",".end".

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f2eb9aa9-9b83-4f86-b6ae-f380c555fc86)


after running this file we get output of ngspice like this,

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/3734948c-65e5-425f-91a5-ab26b908789f)

Now, ploting the graph here by comand, "plot y vs time a".

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b4e73775-22a1-4e71-8fc0-060117a19586)

NOw if we increase the C3 value from 0.024ff to 2ff the graph will look like this, graph become more smoother.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6d5afd2f-2b06-4a7f-bf5c-8b62f5dab03c)


### <h3 id="header-3_3_2">Lab steps to characterize inverter using sky130 model files</h3>

Here, we have to find value of 4 parameters.
	
<ul>
	<li><a> rise time</a></li>
	</ul>
	
it is time taken to the output waveform to 20% value to 80% value.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5485cced-e163-44c4-ac83-54a81cc86783)

so, rise time= (2.2489 - 2.1819)e-09 = 66.92 psec.


<ul>
	<li><a> fall time</a></li>
	</ul>
 
it is the time take by output for transition from 80% to 20%.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/dde449de-7004-459b-b51b-009155b810d6)

so, rise time= (4.09512 - 4.05264)e-09 = 42.51 psec.

<ul>
	<li><a> propagation delay</a></li>
	</ul>

it is the time difference between the 50% of input and 50% of the output.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d89e4c30-d806-4907-9ac7-0e1af3d14627)

so, propogation delay =(2.2106 - 2.15012)e-09 =  60.48 psec.


<ul>
	<li><a> cell fall delay</a></li>
	</ul>
 
it is time for output falling to 50% and input is rising to 50%.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/95652d8b-57cb-4033-8e42-dc4c579a9189)

so, cell fall delay =(4.07735 - 4.04988)e-09 =  27.47 psec.

We have successfully characterized our inverter.
Our next objective is to create a lef file using the layout and we will plugin this lef file in the picorv32a core

### <h3 id="header-3_3_3">Lab introduction to Magic tool options and DRC rules</h3>

To know more about the Magic DRC we can go to the website:- http://opencircuitdesign.com/magic/Technologyfiles/TheMagicTechnologyFileManual/DrcSection 

Link to Google_Skywaters Design Rules: - https://skywater-pdk.readthedocs.io/en/main/rules/periphery.html
For reference , we can use the github repo of Google-Skywater: - https://github.com/google/skywater-pdk


### <h3 id="header-3_3_4">Lab introduction to Sky130 pdk's and steps to download labs</h3>

Follow the steps:

First go to the home directory.

To download the lab files for performing DRC corrections:

wget http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz

To extract the lab files from the downloaded file:

tar xfz drc_tests.tgz

Then go inside the lab folder drc_tests.

Then we can list all the directories by using the ls -al command.

Then we will view the .magicrc file by using the gvim .magicrc command.This file is the startup script for magic. It tells magic where to find the technology file. The technology file is already made available locally in the same directory because we may need to make changes to this file.

Then we will open the magic tool by using magic -d XR & command to start the magic in better graphics.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6285501b-7b2e-4b31-9273-5c81a7b4da59)

Content of .magicrc file by using command vi .magicrc

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d6668093-e775-418b-a73a-8c2208ba13be)


### <h3 id="header-3_3_5">Lab introduction to Magic and steps to load Sky130 tech-rules</h3>

Now use magic -d XR command to open magic tool, 
Just for example we open the met3.mag file in the magic tool from file then open met3.mag file. Here we will see some different layouts having different DRC value and these layouts are called rule number.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8abdf2a4-2bb2-4e65-820a-3860340e4304)

These rule number can be found at  Google-Skywater documentation.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/26e16828-6711-4e54-97f1-c84571e36b7b)

Now we can select the any layout area and then type drc why in tckon.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8d1517ff-fa73-4350-80b2-6f1106ec6782)

Now we will select any blank area then hovering the mouse pointer over the metal3 contact icon and pressing the p button. type pek in tckon and then we will execute the command cif see VIA2 in the tkcon tab, then we will see bunch of black square appears inside the area.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a9585c99-9a41-4df8-8100-73fc3653a09e)


### <h3 id="header-3_3_6">Lab exercise to fix poly.9 error in Sky130 tech-file</h3>

Now, we will open the poly.mag file in the magic tool by typing the command  load poly.mag in the tkcon terminal.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4528478e-58cd-46bb-a99e-63ecb5f31c3a)

Now let's consider the rule poly.9 then check the website for that rule.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/10ad235a-a615-4167-9cb8-68e8d8971b41)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cb3bf544-4e0f-4aa8-968e-49e6cea7a1f6)

Now to find the error look at the file vi sky130A.tech  we will open the file sky130A.tech file which is present in the drc_tests directory with the text editor of linux itself.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/32cd1437-efd3-4cff-b84c-56b133443de0)

We will search for poly.9 in this file by using the Find option. We find it in 2 places . First one in the POLY section and the second one in the uhrpoly(polyresistor) section. The rules are not set properly in both these places. So we will add a change in both of these sections.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/99981782-d58f-40a9-aea7-3d6496098367)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/eaa26fe7-6583-460c-8562-08c1f77b9eea)

Click on Save and close the editor file.

Then we will execute the commands tech load sky130A.tech in the tkcon terminal. Then drc check as shown below

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/93876300-43b9-4748-82cb-24bb98c0df14)


### <h3 id="header-3_3_7">Lab exercise to implement poly resistor spacing to diff and tap</h3>

 To correctly implement poly resistor spacing we need to again make the changes in the sky130A.tech file.

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d1f1d0bd-993b-44a1-937b-0dd68d9c9af7)

 Now execute in Tkon after saving it

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/58c628ba-e309-4ebb-a24c-900e9dc80f47)

We can make the copy of the poly.9 model of poly.mag file in the magic window itself and check for errors:

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/11af550e-0fe6-44d2-ab97-51974382d9a3)

We can select the area having drc error and then run the drc why command in the tkcon terminal to find the description of that error.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1ba9feba-382e-46a5-817f-b9c861116af3)


### <h3 id="header-3_3_8">Lab challenge exercise to describe DRC error as geometrical construct</h3>

The changes we need to make in sky130A.tech file are as follows:

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c8a20821-704e-4b85-b7b8-14c223b6da27)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c8268fbb-cdd7-4b52-bed1-77a104bdd8ff)


open the nwell.mag file in the magic tool and look for the nwell.6 model error. Here in thw given figure the deep nwell is shown in the yellow stripes and the nwell is shown in dotted green pattern.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5e705fcf-fdfc-4c4c-a6f6-1ff185f49e4a)

We can check this error on the site as well

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/56ac4c1b-7476-4d59-a548-dcd22b9e7ee2)

### <h3 id="header-3_3_9">Lab challenge to find missing or incorrect rules and fix them</h3>

Now  open the magic tool and then execute the commands drc style drc(full) and drc check.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e98833bd-d19b-4772-a814-bb3487723bb8)


# <h4 id="header-4">Day 4 - Pre-layout timing analysis and importance of good clock tree</h4>	 
## <h4 id="header-4_1">Timing modeling using delay tables</h4>
### <h4 id="header-4_1_1">Lab steps to convert grid info to track info</h4>

Now the concept of 'lef' file will comes into the picture. it contains all the information which we discuss earlier. so our next objective is to extract the '.lef' file out of the '.mag' file. and next step is that extracted file could be placed into the picorv32a flow.

you need to folow certain guideline while making standerd cells.the guidelines are

The input and output port must lie on the intersection of the verticle and horizontal tracks
The width of the satnderd cell should be odd multiple of the track pitch and the height should be odd multiple of track verticle pitch
Now oprning the track file from the pdk/sky130/libs.tech /openlane/sky130_fd_sc_hd/track.info. where we get the info like this,

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/86282d04-0357-4906-b2f6-882a65f43624)

so, the track is basically nothing but it is used during the routing stage.Rout will be go over the tracks. tracks are basically trases of matel layers.i.e., metal 1, matel 2, etc.

PNR is a automated. so we need to specified, where from we want routs to go. this specification is given by tracks. here we can see that each of the tracks are placed at (0.23 0.46)um horizontaly and (0.17 0.34)um vertically for li1, metal 1, metal 2 layer.

In layout, we can see that the ports are on the li1 layer. so we need to insure that the ports are on the intersection of the tracks or not. For that we have to cinvert the grid into the tracks. for that we have to first into the tracks file and the open the tckon window and type the "help grid" command.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cad6a58e-5e45-4f84-93aa-b636c6c001e1)

Then again write comand according to the track file.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/344a1e23-8710-42cf-8e2e-7eeb5e3a5276)


Here we can see that, as per the guideline the ports are placed at the intersection of the tracks. Now, between the boundaries, 3 boxes are coverd. so our second requirment also satisfied here.

### <h4 id="header-4_1_2">Lab steps to convert magic layout to std cell LEF</h4>

Now we will decide the port name and its values as follows. We can set the values for different ports and for power and ground port we need to do the changes in attach tolayer as Metal1.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e65285fd-fbd2-479a-a461-2e1d257253d3)

Once these parameters are set we are ready to extract the lef file from the mag

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2d838026-3faf-4b08-a09b-1be08506dc5e)

Now, we open this file in the magic by using comand "magic -T sky130A.tech sky130_vsdinv.mag &".Now to extract the lef file we have to write the comand in the tckon window "lef write". so it will create a lef file and we can check it in the vsdstdcellsdesign folder.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/288b219e-2720-4f54-b5ce-f08ba9fe3a1f)


### <h4 id="header-4_1_3">Introduction to timing libs and steps to include new cell in synthesis</h4>

Now, lef file is created and now step is plug this lef file in picorv32a. before that we move our files to src folder where all the design files are available at one location.

for that we are copiying this file in the src folder by 'cp' command.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/10c7a3da-fe77-4df2-9ca8-446d89e59951)

this is how the library file looks like. We have different library files named as typical,slow ,fast.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5744e9b7-522d-4d66-98ff-6903ee1d7fe6)

Now we will copy it to the src folder

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4cbadeda-835d-42ca-b190-5c98510f4d21)

We need to modify the config.tcl file of picorv32a directory,
 
So open the config.tcl file of picorv32a directory in any editor and add the commands shown in below image :

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5a729a04-1651-454b-a900-d6fb64e12794)


**OPENLANE :-** Go to the open lane directory and execute the docker command.

Execute the following commands :

    ./flow.tcl -interactive
    package require openlane 0.9
    prep -design picorv32a
    set lefs [glob $::env(DESIGN_DIR)/src/*.lef]      
    add_lefs -src $lefs
    run_synthesis

  ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4da8bf77-2951-4076-a97c-4640b4d3e88c)

  ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f61778fe-7c40-4bf2-ac50-86c1921b84a2)

  ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/944ee857-ecd4-4ca4-8442-4c6953bd035d)

  ### <h4 id="header-4_1_4">Introduction to delay tables</h4>

**Power Aware CTS**:- If we make enable pin at logic '1' in the AND gate, then clock will propagate and if we make it 'logic 0' it will block the clock. Similarly in 'OR' gate if we make enable as 'logic 0' it will propagate and on making it 'logic 1' it will block the clock.

So the advantage of this blocking period is that we can save lot of power in clock tree.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7ee8dd3f-1766-4341-93f2-fe32eb98de7e)

Let's say we have a clock tree, The buffer present at the first input is driving the load of second two buffers. We have splited the buffer and in clock gating technique we have just swaped the buffer with and gate so now will all the other characteristic will be same or will get changed will see in coming steps.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/638b696f-516a-473f-b78f-6748220c4b89)

Before swaping the buffer with gate we have made some assumptions which are follows

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5d7dff63-31be-4e77-bd22-d44cf85fdb50)


<ul>
	<li><a> Assume c1=c2=c3=c4=25fF</a></li>
	</ul>
<ul>
	<li><a>Assume Cbuf1=Cbuf2=30fF</a></li>
	</ul>
<ul>
	<li><a>Total Cap at node 'A'=> 60fF</a></li>
	</ul>
<ul>
	<li><a>Total Cap at node 'B'=> 50fF</a></li>
	</ul>
 <ul>
	<li><a>Total Cap at node 'C'=> 50fF</a></li>
	</ul>
 
 We have made some observations from here which are as follows

 <ul>
	<li><a>2 levels of buffering</a></li>
	</ul>
<ul>
	<li><a>At every level,each node driving same load</a></li>
	</ul>
 <ul>
	<li><a>Identical buffer at same level</a></li>
	</ul>

So the output capacitance of the buffer for the entire circuit is not constant, load at the output will be varying and since the load is varying so input transition is also varying. 

So becuase of this variation in output and input we will have varity of delays so how to capture that delay we will see with delay tables

**How delay tables are prepared?**

For this purpose we have carried out the one buffer from the circuit and and seperately varying its input transition within some range of let's say 10ps-100ps than the output load will also vary so we willl characterise the delay and put the data in tabular format.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8adffa38-98d2-4787-9bb1-52062de98557)


### <h4 id="header-4_1_5">Delay table usage Part 1</h4>

Let's take the example for other buffers.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4a39b172-b1d4-47be-986f-e3264ce2fe2a)

For practical example let's say we have the input transition of 40ps of buffer1 the output capacitance of this particular buffer is 60ff. The delay of the cell in this case is lies between x9-x10.

So the values which are not available in the delay table those are extrapolated from the given data so we can take the range in that case.


### <h4 id="header-4_1_6">Delay table usage Part 2</h4>

Now we have to calculate the delay of buffer 2 and after that we can find the latency at the 4 clock end points.

Here input transition is common for both the buffers. now assuming that the transition is around the 60psec and load at both the buffers is 50fF. so it will give the delay of y15.

The total delay from input to the output is= x9' + y15.(here we are ignoring the delay of the wires). that means the skew at the any output point is zero.

If load is not same at the every nodes, the skew will not be the zero.

### <h4 id="header-4_1_7">Lab steps to configure synthesis settings to fix slack and include vsdinv</h4>

We will try to modify the parameters of our cell by referring the README.md file in the configuration folder in openlane directory :
The README.md file contains information about the parameters of the cell. 

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/21ad1228-9f16-4044-adc2-044eac7af2a5)

We will give the following commmands in the terminal in openlane directory

  prep -design picorv32a -tag 01-04_12-54 -overwrite
  set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
  add_lefs -src $lefs

  echo $::env(SYNTH_STRATEGY)
  set ::env(SYNTH_STRATEGY) "DELAY 3"
  echo $::env(SYNTH_BUFFERING)
  echo $::env(SYNTH_SIZING)
  set ::env(SYNTH_SIZING) 1
  echo $::env(SYNTH_DRIVING_CELL)
  run_synthesis
  
 prep -design picorv32a -tag 01-04_12-54 -overwrite is used to overwrite the existing files with previous values of simulations.

After synthesis, we observed that the slack is nagative here. wns(worst negative slack)= -23.89 and tns(total negative slack)= -711.59.

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/864c6c75-b5af-42aa-9a81-179be228c4e0)

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/82bb71ed-436a-4d35-a90e-bb90281c15ca)

Now run_synthesis, here chip area will increas and the value of slack will reduce.
Since synthesis of the picorv32a using our custom designed cell is successful, so we will run the floorplan using command run_floorplan

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9f44d8b7-3abe-443c-ab6d-fb1714ff2ca9)

Since, we are getting the error so first again do the synthesis using above commands and then we will use following commands to do the floorplan:

  init_floorplan
  place_io
  tap_decap_or

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/48adf433-267b-4f73-9a38-6d3adbdfb3d3)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0f743f80-ec2f-48d9-a641-e7f112b383f4)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/856fb2fa-02f1-482f-b39e-9611f45fa1a1)

so now we can run the placement using command run_placement

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/65232f8d-540e-408c-9d3e-0f28c9a42411)

SO placement is succesfull now.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6d637fc9-823e-4516-887e-ee6bbee1c481)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/dab482cb-950a-451d-9747-3d9d21b3b836)


We can run the expand command in the tkcon window 

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a5103878-a12a-4d8b-b93c-2bc44c9f2e14)


## <h4 id="header-4_2">Timing analysis with ideal clocks using openSTA</h4>
### <h4 id="header-4_2_1">Setup timing analysis and introduction to flip-flop setup time</h4>

**Timing analysis (with ideal clock)**:- Let's start the setup analysis with the ideal clock(single clock). specifications of the clock is

clock frequency =1 GHz

clock period =1 ns

Now will do the analysis between '0' and 'T' clock period. We sent at edge to the launch flop at '0' clock period and at T=1ns period the second edge reached to capture flop.

Let's say here we have combinatonal delay of theta and set up timing analysis says that this combinational delay should be less than the T for system to work properly.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1f37c84e-adf8-4c4a-b516-738cef0ed663)

 Now let's open the capture flop and we will see some combinational circuit there it has several MOSFETs , several logics,resistances and capacitances inside it.Also have the time graph for this particular flop

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/02b99aec-f35a-4777-a88c-5a1a4677a731)

When there is logic '0' or logic '1' of clock 1 the delay of MUX1 and MUX2 will restrict or effect the combinational delay requirement.

So there is some finite amount of time which is required to the D input to settle and this amount of time is reffered to as **SET UP TIME**.

Hence finite time 's' required before clk edge for 'D' to reach Qm.

So, we can write that the internal delay of the MUX1 = set up time(S).

So, now θ<T becomes θ<(T-S).

### <h4 id="header-4_2_2">Introduction to clock jitter and uncertainty</h4>

So in Jitter the clock is being created by PLL(phase-locked loops) and the clk source is expected to sent the clk signal at exactly 0,T,2T,....But that clk source might or might ot be able to generate the clk exactly at 0 or any other certain time because of it's inbuilt variations that is called **jitter.** Jitter is refered as temporary variation of the clk pulse.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/46f48919-5c6a-4c63-8c50-b358710b4bc7)

Let's consider this uncertantity time(US) in consideration. So, now equation will become θ<(T-S-US). Now assuming  'S'=0.01ns and 'US'=0.09ns. by taking this, Let's identify the timing path in our circuit stage 1 and stage 3 logic path has single clock.

Now,we have to identify the combinational path delay for the both logics.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/ce3d7d96-f5c2-44a6-ad38-78c1cc4f2fc7)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6560c3db-2bdb-4233-b8ec-58fff0c27d89)

### <h4 id="header-4_2_3">Lab steps to configure OpenSTA for post-synth timing analysis</h4>

We will do STA on the initial picorv32a design which had timing violations.First we need to run the synthesis using the following commands in openlane directory:

    docker
    ./flow.tcl -interactive
    package require openlane 0.9
    prep -design picorv32a
    set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
    add_lefs -src $lefs
    set ::env(SYNTH_SIZING) 1
    run_synthesis

 ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/5498fefc-0656-48a2-a04b-dd40c9424c2d)

Now we need to make a new pre_sta.conf file. We can do this by vim editor.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/d0885737-368b-4ee7-8ba3-2707aa5be258)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/da429e3b-ca3d-47e8-b389-856fad2f5d74)

We need to remember that when we are outside openlane , we cannot use the definitions of environmental variables which were used during synthesis. So, we will create a my_base.sdc file which will contain the definitions of environment variables.

Now, we also need to create my_base.sdc file containing the content shown in below image in openlane/designs/picorv32a/src directory

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/cf294e81-401c-45f7-9d0f-48501f07faee)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b841d16a-bced-44b4-b05c-dad5df2c4ba6)

Now go to the openlane directory in a new terminal and execute the sta pre_sta.conf command.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/309447be-b3ae-4b33-9b36-43d82e738fa0)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e1a1977b-ce38-43aa-8a34-b844f5d6ff4d)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/146e218e-a4a5-4f37-9ca2-088d74eb5d99)


### <h4 id="header-4_2_4">Lab steps to optimize synthesis to reduce setup violations</h4>

 Now we will try to change the FANOUT parameter and again do the synthesis by executing the following commands:

prep -design picorv32a -tag 02-04_05-27 -overwrite
set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
add_lefs -src $lefs
set ::env(SYNTH_SIZING) 1
set ::env(SYNTH_MAX_FANOUT) 4
echo $::env(SYNTH_DRIVING_CELL)
run_synthesis

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/003f8f6d-d126-40a4-ab51-491698e10cdf)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9199ddfe-ed3a-4eab-b489-5afd3b240e38)

Now, run the sta pre_sta.conf command in a new terminal in openlane directory :

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f883522d-8b5a-4cb6-b7e6-72a07b179c0e)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/abc6aad2-ba40-42a2-b59b-ad78d3eb3392)


### <h4 id="header-4_2_5">Lab steps to do basic timing ECO</h4>



## <h4 id="header-4_3">Clock tree synthesis TritonCTS and signal integrity</h4>
### <h4 id="header-4_3_1">Clock tree routing and buffering using H-Tree algorithm</h4>

**Clock tree synthesis:-**  Let's connect clk1 to FF1 & FF2 of stage 1 and FF1 of stage 3 and FF2 of stage 4 with physical wire.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/70e302e7-a5be-4faa-bb5c-9b879a08dbc2)

Now let's see what is the problem with this? Let's consider some physical distance from clk to FF1 and FF2 , so due to this t2>t1. 

Skew= t2-t1,  and skew should be 0ps

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c85bc4c8-78b1-4eb8-937f-7eb9ecacf680)

Previously we have build bad tree now we will try to modify that in a smarter way. Hrre clk will come in somewhere mid points with this clk will reach to every flip flop at almost same time. In the same way we will connect the clk2 with flip flops like midpoint manner.
 
![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/08ee4831-32c9-48d0-9356-18564ba45735)

Now will se clock tree synthesis(Buffering), Let's we have some clock route through which it has to reach to particular locations and clock end points and in the path many capacitance, resitors are there.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/26cccdd6-9698-41c6-9cf7-92d7470b5c1a)

Because of the wire length we did not get the same wave form at ouput as input and bcz of RC networks , so to resolve this problem we use repeaters.
The only difference between the repeaters we use for clock or for data path is that clock repeaters repeaters will have equal rise and fall time.

First step is we will remove the clock route and place 2 repeaters and allow the clock to go through this particular repeater, in this case whatever wave form is generated here will go to the output. So we can as many as repeaters we want to make the continuous flow of th clock till the output.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/65462f38-a26a-4d3e-8054-bb7203685d74)

### <h4 id="header-4_3_2">Crosstalk and clock net shielding</h4>

**Clock Net Shielding:-** Till now we have built the clk tree in such a fashion that the skew between the launch flop and capture flop  is 0. Skew means the latency difference between clk ports of the flop pins.
Clk net shielding is the critical net scene in the design. We take the particular clk net and shield it means we protect the clk from the outside world, it's like house for tha clk. 

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/9fa477bb-3cba-4f3e-bda1-e25fc7e984f4)

If we do not protect the clk then two types of problem we can face **Glitch** and **Delta delay**

Let's consider on of the clk net. So whenever there is switching activity happening at the aggraser because of the coupling capacitance between the wires and this capacitance is so strong that any activity happening at the aggraser will directly impact the net which is close. 

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/6b516ccc-1aed-491e-9050-6cf912619f24)

The shielding is the technique, by which we can protect the net from these problems. In a shielding, we put wire between the either two wire where coupling capacitance is generate. This extra wire is grounded or connected to VDD.

We see the amount of delta delay because of the bump when we are switching from logic '1' to logic '0'. And skew is not anymore 0 here. So the impact of crosstalk delta delay is that it make the skew value non-zero.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/4f2fcb95-f28d-42a0-a58c-836f981f00f9)

By shielding we are breaking the coupling capacitance between the aggraser and victim. Shields don't switch.


### <h4 id="header-4_3_3">Lab steps to run CTS using Triton</h4>

### <h4 id="header-4_3_4">Lab steps to verify CTS runs</h4>


## <h4 id="header-4_4">Timing analysis with real clock using openSTA</h4>
### <h4 id="header-4_4_1">Setup timing analysis using real clocks</h4>

Circuit tree looks little bit different than ideal clock with real clock here we have buffers,wires etc Clock reach to launch flop and capture flop through a set of buffers.So clock signal will not reach to the buffer at t=0 time due to these buffers. So the combinational circuit equation will be  (θ+1+2)<(T+1+3+4). Initially it was θ<T.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/7b0dab5b-f9ee-4f81-9f5b-06308a3cd79b)

Let's called "1+2"=∆1 and "1+3+4"=∆2 and (∆1-∆2)=skew

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/8d64a80a-7b5c-4031-aa87-ad0a54ab8baf)

And here also, we have to consider the propogation skew (s) and uncertainty delay (US). so final equaltion becomes like, (θ+∆1)<(T+∆2-S-US).

we can also say that (θ+∆1)= data arrival time and (T+∆2-S-US)=data required time.
If (Data required time)- (Data arrival time) = +ve then it is fine. If it is -Ve then it is called 'slack'.

**Hold timing analysis:-** It is littel bit different then setup timing analysis. here we are sending the first pulse to the both launch FLop and capture flop.

Hold condition state that, Hold time (H)< combinational delay (θ). So, (θ>H).

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/21a17bf8-5526-4c9b-8a89-09d432e52af5)

Hence, finite time 'H' required for 'Qm' to reach Q i.e., internal delay of mux2= hold time.

Now, if we add the real time clock, the equation will be change. now equation becomes (θ+∆1)>(H+∆2).

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b2978f1d-6743-40af-b522-2a1497df0929)

### <h4 id="header-4_4_2">Hold timing analysis using real clocks</h4>

Combinational delay should be grater then the hold time of the capture flip flop. Once the clk reaches the launch flop it takes ariund 2buffer delay(∆1) and when it reaches to the capture flip flop it takes around 3 buffer delay(∆2). Uncertainity will be same for both the flip flops becaiuse clock applied to both the flops from the same edge only. Now let's add the uncertainity value to it.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/1ef562f2-8943-4657-aa3b-0e4116c9a696)

Slack= Data ariival time - data required time. Slck either should be positive or 0. If slack goes to negative  it is refer to as voilation

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/f4e02f66-f9cb-458e-8ab9-7ddebf33f32a)

Let's identify the timing paths from design, with single clock 

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/2989418f-52ae-4108-83c8-7dbf9efc5114)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0dbf4092-b74c-4c5a-89d8-5b94e5dff59f)  ![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/b2597a4f-b999-4d48-a1fa-d6bb7c9985e9)

### <h4 id="header-4_4_3">Lab steps to analyze timing with real clocks using OpenSTA</h4>


# <h5 id="header-5">Day 5 -Final step for RTL2GDS using tritinRoute and openSTA</h5>	 
## <h5 id="header-5_1">Routing and design rule check (DRC)</h5>
### <h5 id="header-5_1_1">Introduction to Maze Routing ÃÂ LeeÃÂs algorithm</h5>

So the next and final stage in the physical design is Routing and DRC. 

**Routing:-** It is finding the best shortest possible connection between two end points with one point being the source and other point being the target and with less number of twist and turns.

**Maze-Routing(Lee's Algorithm):-** Therse should not be zig-zag lines of connections most of the connections should be in L shape or in Z shape. So according to algorithm first it create some grids and grids are routing at the backend. It's called as routing grid. There are some numbers of grids on this routig having some dimensions. SO here we are having two points one is 'Source' and the other is 'Target'. With the help of this routing grid algorithm has to find out the best possible way between them.

First step is algorithm tries to lable all of the grids surrounded. Only the adjacent horizontal and vertical grids are labeled not the digonal one as shown in the image below.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0628c349-0714-417d-9c31-4d9b64b3c18f)

### <h5 id="header-5_1_2">LeeÃÂs Algorithm conclusion</h5>

Now we will lable the grids to the next integer untill we reach to the target. In the example we reacged the target after integer 9.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/c5620bca-5d4b-4533-8c8a-6823ff932c66)

SO now there are so many ways to reach  to target from source but we have to choose the best shortest possible way to reach the target.And we need to avoid the zig-zag way better to cghoose 'L' shape routing'

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/968051c8-d8c7-4819-8481-dc6501f5261b)

Now take one more example for routing, and will follow the exact same step as follows in the above example.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/75d8cd15-4621-40cc-aaca-feb77b155496)

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/e4844e57-b8da-4a9e-82a0-b27e65aa66e3)

### <h5 id="header-5_1_3">Design Rule Check</h5>

So in order to go to DRC we need to follow some steps which are called drc cleaning.

Let's take the example of the above circuit. Let's we have two parallel wires so the rule says that whenever we choose two wires there should be minimum distance between these two wires.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/0ef82844-21b1-4963-b620-30de435a27bb)

**Rule 1) Wire width:-** Width of the wire should be minimum that derived from the optical wavelenth of lithography technique applied.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/57519723-b095-42a3-9bf3-6d3ec0993094)

**Rule 2) Wire Pitch:-** The minimum pitch between two wire should be this much as shown in the figure below.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/141d1b66-0efd-466c-a7cc-aa5941710e7c)

**Rule 3) Wire Spacing:-** The wire spacing between two wires should be as shown in the image below.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/433af510-0dcb-4eac-9ac3-5c864dee9a42)

Let's take the other part for design rule check from the same example .

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/766c4c20-2500-43c7-9969-acbf27d60047)

Solution of this signal short problem is take one of the wire and put it on the other metal layer. usually upper metal is wider than the lower metal.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a88f8467-912b-4fbf-84ad-fd063c3545d5)

After this solution, we add two new DRC rules should be check.

**Rule 1) Via Width:-** via width should be some minimum value.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/acfb8c4b-adf7-494e-a948-012ee6d40415)

**Rule 2) Via Spacing:-** Via spacing should be minimum value.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/91595b25-a47e-4c9d-944b-273b868940eb)

After routing and DRC the next step is Parasitic extraction. Resistance and capacitance present on every wire should be extracted and use for further process.

![image](https://github.com/kmkalpana2001/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/165163110/a002217b-0866-4ab4-a603-454ad0bb0adf)


## <h5 id="header-5_2">Power Distribution Network and routing</h5>
### <h5 id="header-5_2_1">Lab steps to build power distribution network</h5>

