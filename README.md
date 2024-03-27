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
      </ul>
	<ul>
        <li><a href="#header-2_3">Cell design and characterization flows</a></li>
      </ul>
	  <ul>
        <li><a href="#header-2_4">General timing characterization parameters</a></li>
      </ul>
</div>
  
  <div class="toc">
  <ul>
    <li><a href="#header-3">Day 3 - Design library cell using Magic Layout and ngspice characterization</a></li>
	<ul>
        <li><a href="#header-3_1"> Labs for CMOS inverter ngspice simulations</a></li>
      </ul>
      <ul>
        <li><a href="#header-3_2">Inception of layout ̂A CMOS faabrication process </a></li>
      </ul>
	<ul>
        <li><a href="#header-3_3">Sky130 Tech File Labs</a></li>
      </ul>
   </div>
	  
<div class="toc">
  <ul>
    <li><a href="#header-4">Day 4 - Pre-layout timing analysis and importance of good clock tree</a></li>
	<ul>
        <li><a href="#header-4_1">Timing modeling using delay tables</a></li>
      </ul>
      <ul>
        <li><a href="#header-4_2">Timing analysis with ideal clocks using openSTA</a></li>
      </ul>
	<ul>
        <li><a href="#header-4_3">Clock tree synthesis TritonCTS and signal integrity</a></li>
      </ul>
	  <ul>
        <li><a href="#header-4_4">Timing analysis with real clock using openSTA</a></li>
      </ul>
</div>
	
<div class="toc">
  <ul>
    <li><a href="#header-5">Day 5 -Final step for RTL2GDS using tritinRoute and openSTA</a></li>
	<ul>
        <li><a href="#header-5_1">Routing and design rule check (DRC)</a></li>
      </ul>
      <ul>
        <li><a href="#header-5_2">Power Distribution Network and routing</a></li>
      </ul>
	<ul>
        <li><a href="#header-5_3">TritonRoute Features</a></li>
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
