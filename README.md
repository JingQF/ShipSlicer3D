# ShipSlicer3D

Description: A novel tool to make section/slice data (body plan) from a ship STL model.

This is the program and database related to the paper "xxxx-xxx".

If this program offered help to your research, plear refer the paper above.[Paper Link-not released yet]()

## Program Instruction

### Fuction of the program
1. Fast and consice slicing operation in specific direction and number of ship STL model.(not limited to ships)
2. Wetted surfaced calculation (based on different empirical methods and slicing method).
3. 3D slice data display.
4. 2D slice data display.

### Basic operations
1. Slice.
2. Read STL.
3. Set slicing parameters.
4. Display slice data.

Figure...

## Database Instruction
1. The STL model is constructed based on the .igs model of KVLCC2, KCS, and DTMB5415 from [SIMMAN 2014](https://simman2014.dk/).
2. The sample database is obtained from the STL models above using the proposed program.
3. The database consists of three direction (x,y,z) of slice data of the ships.
4. Each direction of folder is consists of detailed data under difference slice number.
5. data name rules: xxx_xxx_xxx

## Cautions
1. The STL model used in the program must be a closed one. It is prfered to repaired the STL model in software such as Netfabb before you using the slicing program.
2. This program is aim to conduct research on ship motion simulation and validation. It is not complete in function, so the stability is not ensured under any kind of commerical usage.

## Sample Video and figures
video of slice a ship STL

figures in matlab
