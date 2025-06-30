# USB-GPIB Adapter 
## Version 3-MINI 

## Project Introduction

This project is based on the popular Xyphro USB-GPIB adapter https://github.com/xyphro/UsbGpib 
forked by Dazz100  https://github.com/dazz100/UsbGpib .

The enhancements are purely hardware. I did not do any software modifications and both Xypro and Daz100 can run.

Modifications :

1. Used a thru-hole, vertical USB-C connector for mechanical robstness. SMD connectors break too easy.
2. Optimized BOM to use LCSC parts so the JLCPCB service can be used to make and assemble the board.
3. Single sided SMD placement for cost optimisation
4. Changed the GPIB connector to a vertical, thru-hole connector
5. Board shape designed to fit directly behind the GPIB conector without protrusions
6. Changed CPU to QFN version and most components to 0402
7. Changed one LED to BLUE for colorblind people like me

This repository includes the hardware and software files to build this version.
The software is a clone fromt he DAZ100 firmware as it stood on 06/29/2025
You may want to check the Xypro and DAZ100 repositoreis for updates.
and information needed to build the latest USB-GPIB enhanced adapter.

## PCB

The project was recreated in Altium and the production pack (Gerber,NCDrill,pick and place and BOM) for JLCPCB is included in a single ZIP file.

Source files (schdoc,pcbdoc and prjpc Altium Designer V25) are provided. Most other CAD tools can import those.


