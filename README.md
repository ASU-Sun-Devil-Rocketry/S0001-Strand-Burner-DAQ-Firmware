# S0001-Strand-Burner-DAQ-Firmware

<p>PCB: Strand Burner DAQ S0001</p>
<p>MCU: Arduino Nano </p>
<p>MPU Architecture: N/A</p>

<p>Description: The Strand Burner Data Aquisition board collects data during solid propellant burn 
tests that is used for propellant performance characterization. This is achieved through the use of continuity 
wires that are run through the propellant grain, which are used to time the burn rate. The timer is set and triggered
by external interrupts set on the continuity pins of the processor. Additionally, the firmware polls the pressure 
transducer ADC to measure combustion pressure. </p>

<p><b>Source Directories:</b></p>
<p>
main: firmware to be run during propellant characterization

test: testcode for verification of PCB functionality
</p>

<p><b>Working Directory Structure</b></p>

<p>
doc: documentation

src: source code files and build files

lib: libraries for device drivers and external functions
</p>
