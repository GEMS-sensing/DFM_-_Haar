# Type: Atmospheric Temperature/Pressure/RH
# Make: GEMS
# Model(s): Haar v2.0

#### [Haar_Primal_HardMount_2v0](Haar_Primal_HardMount_2v0.mnt) 
Position file for surface mount parts

#### [Haar_Primal_HardMount_2v0_2022-02-11](Haar_Primal_HardMount_2v0_2022-02-11.zip)
Gerber files for Haar PCB

#### [Haar_Primal_HardMount_2v0_BoM](Haar_Primal_HardMount_2v0_BoM.csv)
Bill of Materials for PCB assembly 

#### [Haar_Assembly_BoM](Haar_Assembly_BoM.csv)
Bill of Materials for system assembly

#### [HaarBody_v000](HaarBody_v000.zip)
Zip file of STL for Haar body.

## Body

__Manufacturer:__ Hubs (Formerly known as 3D Hubs)

__Process:__ SLS

__Material:__ HP PA 12 Nylon, __white__

__File:__ [HaarBody_v000](HaarBody_v000.zip) - Unzip before submitting 

## PCB

- FR4
- 1oz copper
- Lead-Free HASL
- __White Soldermask__ 
- __Black Silkscreen__ 
- 0.062" thickness

## Board Assembly

- Follow handling instructions outlines in [Senserion Handling Instructions For SHTxx Humidity and Temperature Sensors](https://sensirion.com/media/documents/6D95AA80/6374D8C1/Sensirion_Handling_Instructions_SHTxx.pdf)
- When applying any glue or conformal coating, ICs `U1` and `U2` must be protected with Kapton tape (See details in above document)
- Small angular alignment error when soldering on connector `J1` is acceptable 
- Ensure tab on `J1` is on the top (component side) of PCB

Note: Pad `JP1` should be left _open_

# System Assembly

- Before Assembly: Conformal coat board using the protections described above
1. Remove jam nut from connector on Haar board assembly (if still in place)
2. Finger tighten Haar board assembly into larger end of 3D printed body
3. Finger tighten GoreTex vent into smaller end of 3D printed body

