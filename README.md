# Digital-VLSI-SoC-Design-and-Planning
Notes Summarized for the Workshop held between 18th June and 1st July 2025
## Day 1 - Inception of open-source EDA, OpenLANE and sky130 PDK
### How to talk to computers
Introduction to QFN-48 Package, chip, pads, core, die and IPs
2. Introduction to RISC-V
3. From Software Applications to Hardware
### Soc design and OpenLANE
1.Introduction to all components of open-source digital asic design
2.Simplified RTL2GDS flow
3.Introduction to OpenLANE and Strive chipsets
4.Introduction to OpenLANE detailed ASIC design flow
### Get familiar to open-source EDA tools
1.OpenLANE Directory structure in detail
2.Design Preparation Step
3.Review files after design prep and run synthesis
4.OpenLANE Project Git Link Description
5.Steps to characterize synthesis results
## Day 2 - Good floor planning considerations
### Chip Floor planning consideration
1.Utilization factor and aspect ratio
2.Concept of pre-placed cells
3.De-coupling capacitors
4.Power planning
5.Pin placement and logical cell placement blockage
6.Steps to run floorplan using OpenLANE
7.Review floorplan files and steps to view floorplan/a>
8.Review floorplan layout in Magic
### Library building and Placement
Netlist binding and initial place design
Optimize placement using estimated wire-length and capacitance
Final placement optimization
Need for libraries and characterization
Congestion aware placement using RePlAce
### Cell design and characterization flows
1.Inputs for cell design flow
2.Circuit design steps
3.Layout design step
4.Typical characterization flow
### General timing characterization parameters
1.Timing threshold definitions
2.Propagation delay and transition time
## Day 3 - Design library cell using Magic Layout and ngspice characterization
Labs for CMOS inverter ngspice simulations
IO placer revision
SPICE deck creation for CMOS inverter
SPICE simulation lab for CMOS inverter
Switching Threshold Vm
Static and dynamic simulation of CMOS inverter
Lab steps to git clone vsdstdcelldesign
Inception of layout ̂A CMOS faabrication process
Create Active regions
Formation of N-well and P-well
Formation of gate terminal
Lightly doped drain (LDD) formation
Source Ã�Â� drain formation
Local interconnect formation
Higher level metal formation
Lab introduction to Sky130 basic layers layout and LEF using inverter
Lab steps to create std cell layout and extract spice netlist
Sky130 Tech File Labs
Lab steps to create final SPICE deck using Sky130 tech
Lab steps to characterize inverter using sky130 model files
Lab introduction to Magic tool options and DRC rules
Lab introduction to Sky130 pdk's and steps to download labs
Lab introduction to Magic and steps to load Sky130 tech-rules
Lab exercise to fix poly.9 error in Sky130 tech-file
Lab exercise to implement poly resistor spacing to diff and tap
Lab challenge exercise to describe DRC error as geometrical construct
Lab challenge to find missing or incorrect rules and fix them
## Day 4 - Pre-layout timing analysis and importance of good clock tree
Timing modeling using delay tables
Lab steps to convert grid info to track info
Lab steps to convert magic layout to std cell LEF
Introduction to timing libs and steps to include new cell in synthesis
Introduction to delay tables
Delay table usage Part 1
Delay table usage Part 2
Lab steps to configure synthesis settings to fix slack and include vsdinv
Timing analysis with ideal clocks using openSTA
Setup timing analysis and introduction to flip-flop setup time
Introduction to clock jitter and uncertainty
Lab steps to configure OpenSTA for post-synth timing analysis
Lab steps to optimize synthesis to reduce setup violations
Lab steps to do basic timing ECO
Clock tree synthesis TritonCTS and signal integrity
Clock tree routing and buffering using H-Tree algorithm
Crosstalk and clock net shielding
Lab steps to run CTS using TritonCTS
Lab steps to verify CTS runs
Timing analysis with real clock using openSTA
Setup timing analysis using real clocks
Hold timing analysis using real clocks
Lab steps to analyze timing with real clocks using OpenSTA
Lab steps to execute OpenSTA with right timing libraries and CTS assignment
Lab steps to observe impact of bigger CTS buffers on setup and hold timing
## Day 5 -Final step for RTL2GDS using tritinRoute and openSTA
Routing and design rule check (DRC)
Introduction to Maze Routing Ã�Â� LeeÃ�Â�s algorithm
LeeÃ�Â�s Algorithm conclusion
Design Rule Check
Power Distribution Network and routing
Lab steps to build power distribution network
Lab steps from power straps to std cell power
Basics of global and detail routing and configure TritonRoute
TritonRoute Features
TritonRoute feature 1 - Honors pre-processed route guides
TritonRoute Feature2 & 3 - Inter-guide connectivity and intra- & inter-layer routing
TritonRoute method to handle connectivity
Routing topology algorithm and final files list post-route
References
Acknowledgement
