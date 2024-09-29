# OpenIC

A collection of open-source tools for IC design and nanoelectronics engineering.

[OpenIC 28-09-2024](https://drive.google.com/drive/folders/1OC2PqxyITxwAAfkFKiqqkY4tVvCiXbRn?usp=sharing)

---

## VM Info

```plain
Title: 				OpenIC
Author: 			Ahmed S. Lilah
Contact: 			sabrylilah2325667@gmail.com
Download Link:			https://drive.google.com/drive/folders/1OC2PqxyITxwAAfkFKiqqkY4tVvCiXbRn?usp=sharing
VM Version:			28-09-2024
VM Password:			0000
Compressed Size:		32GB
Extracted Size: 		160GB
Recommended Disk Space: 	200GB+

Installed: 
				# NAME					# DISCRIPTION
				------------------------		-------------------------------------------------------------------------------------------------------------
				cace					# Circuit Automatic Characterization Engine.
				cicsim					# Custom IC Creator Simulation Tools.
				clang-LLVM                              # Clang+LLVM version 18.1.8 a C/C++ compiler.
				code					# Visual Studio Code.
				miniconda				# Minimalist conda installation.
				freecad					# Parametric 3D modeling software.
				    |--	Electronic WrokBench		# FastCap2, FasterCap (capacitance extraction tool), FastHenry2 (inductance extraction tool), VoxHenry (inductance extraction for voxelized structures), FastImp (full-wave impedance extraction).
				gaw	 				# waveform viewer (installed in a fork named xschem-gaw optimized for xschem requests).
				gcc 					# A C/C++ compiler.
				gh 					# GitHub CLI.
				i3					# i3wm tiling window manager.
				irsim					# switch-level digital circuit simulator.
				kicad					# A Cross Platform and Open Source Electronics Design Automation Suite Mainly for PCB Design.
				klayout					# Your Mask Layout Friend.
				lunar vim				# A NeoVim Distro.
				magic					# VLSI layout editor, extraction, and DRC tool.
				maxima					# An open-source, free system for symbolic and numerical expression manipulation. It is the right companion for SciLab.
				neovim					# Vim-based text editor.
				netgen					# Circuit netlist comparison (LVS) and netlist conversion tool.
				ngspice 				# Circuit simulator.
				octave					# GNU Octave, version 6.4.0.
				pcb					# Printed circuit board layout editor.
				python3					# Python 3.10.12
				qflow 					# Complete digital synthesis design flow using open-source software and open-source standard cell libraries.
				qrouter					# Over-the-cell (sea-of-gates) detail router.
				scilab					# scilab is free and open-source software for numerical computation providing a powerful computing environment for engineering and scientific applications. It is a very valid replacement for Matlab.
				systemc					# Core SystemC Language and Examples.
				tcl-tk					# TCL-TK (Tool Command Language)
				texlive					# TeX Live is a cross-platform, free software distribution for the TeX typesetting system.
				texstuido				# TeXstudio is an integrated writing environment for creating LaTeX documents.
				verilator				# Verilator is a verilog to C++ or SystemC compiler.
				xcircuit				# Circuit drawing and schematic capture tool.
				xschem					# Completer design environment (schematic entry, layout entry, testbench setup).

PDKs
				# NAME					# DISCRIPTION
				------------------------		-------------------------------------------------------------------------------------------------------------
				openpdk					# PDK installer for open-source EDA tools.
				    |--	IHP-SG12G2			# IHP Open Source PDK.
					    |--	ihp-sg12g2		# 130nm BiCMOS Open Source PDK, dedicated for Analog/Digital, Mixed Signal and RF Design.
				    |--	SKY130				# Google/SkyWater 130nm PDK.
					    |--	sky130-pdk		# Skywater 130nm PDK Core Library All Variants.
					    |--	sram-sky130		# re-compiled and verified memory blocks created with OpenRAM with commonly used configurations like 32-bit wide data in blocks of 1kB, 2kB, and 4kB.
					    |--	sram-space-sky130	# single- and dual-port SRAM cores.
					    |--	osu-t12-sky130		# OSU 12-track height digital standard cell library.
					    |--	osu-t15-sky130		# OSU 15-track height digital standard cell library.
					    |--	osu-t18-sky130		# OSU 18-track height digital standard cell library.
				    |--	GF180MCU			# Google/Global Foundries 180nm PDK.
					    |--	GF180nm			# GF 180nm PDK Core Library All Variants.
					    |--	osu-sc-gf180mcu		# OSU digital standard cell library.

WARNING:
	If you are not familiar with the machine setup refrain from deleting any files on the machine.

Special Instruction:
	Using OpenPDKs Variants:
                - run `naneng list` to know the available PDKs.
                - run `naneng init <pdk_name>` initializes the xschemrc files for the PDK
	How to run CACE:
		- run `cd ~/.naneng/tools/cace`
		- run `nix-shell` -> the current shell will be the Nix Shell.
		- now you can run `cace` to run the program or `cace -h` to get the cace help page.
		- after you're finished you can run exit to close the nix-shell and return back to the normal ubuntu shell.
```

---

## Bugs & Features

If you find a situation where you are stuck with something related to the machine.
Then take the initiative to open a GitHub issue regarding the problem. 
Choosing the correct label will help us get to you better so choose the appropriate label.
- bug
- documentation
- enhancement
- question
