# Extension board for ECP5_BGA381_RISCV
This is an extension board for the [ECP5_BGA381_RISCV](https://github.com/gildobjanschi/ECP5_BGA381_RISCV) board. To me it was very useful in monitoring what the processor is doing in terms of reading/writting ROM, RAM, IO, what instruction is generating a trap and so on.

## How To setup KiCAD
Checkout the KiCAD project and open it. In the Configure Paths dialog add: Name: ECP5_BGA381_RISCV_EXT and Path: "The full path to the GitHub directory"/GitHub/ECP5_BGA381_RISCV_EXT

In the Manage Footprint Libraries click the Project Specific Libraries tab and add: Name: ECP5_BGA381_RISCV_EXT and Library Path: ${ECP5_BGA381_RISCV_EXT}/footprints/Footprints.kicad_sym

## Project Status
The board has been manufactured and it is fully verified.

![Board 3D view](https://github.com/gildobjanschi/ECP5_BGA381_RISCV_EXT/blob/main/ECP5_ext.jpg)
