# Extension board for ECP5_BGA381_FT2232HQ_FIFO
This is an extension board for the [ECP5_BGA381_FT2232HQ_FIFO](https://github.com/gildobjanschi/ECP5_BGA381_FT2232HQ_FIFO) board. To me it was very useful in monitoring what the processor was doing in terms of accessing ROM, RAM, IO or when a trap occurred.

## How To setup KiCAD
Checkout the KiCAD project and open it. In the Configure Paths dialog add: Name: ECP5_BGA381_FT2232HQ_FIFO_EXT and Path: <The full path to the GitHub directory>/GitHub/ECP5_BGA381_FT2232HQ_FIFO_EXT

In the Manage Footprint Libraries click the Project Specific Libraries tab and add: Name: ECP5_BGA381_FT2232HQ_FIFO_EXT and Library Path: ${ECP5_BGA381_FT2232HQ_FIFO_EXT}/footprints/Footprints.kicad_sym

## Project Status
The board has been manufactured and it is fully verified.

![Board 3D view](https://github.com/gildobjanschi/ECP5_BGA381_RISCV_EXT/blob/main/ECP5_ext.jpg)
