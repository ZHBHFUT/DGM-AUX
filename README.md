# DGM-AUX

A positive volume preserved dymanic mesh method using Delaunay Graph method with auxiliary point and iterative strategy.

Usage:
  DGM-AUX.exe -i input-grid-file -d deforming-file -o output-tecplot-file [-n number-of-aux-pnt]
  
Where, number-of-aux-pnt is optional and has default value of 80. Please see `*.bat` file in testcase for more detail.

Supported input grid file format:
+ UGRID(*.ugrid)

Deforming file format (ASCII):
```
  N1  DX1  DY1  DZ1
  N2  DX2  DY2  DZ2
  ...
  Nn  DXn  DYn  DZn
```
where, Ni is nodal id(one-based), DXi/DYi/DZi is the displacement value of node i.
