# KML_Maker
use Sample.xlsm fle as sample.

input your point lat. and long. data with pint name in EP_All sheet

in Input sheet it is possible to clarify points that you need to have KML line between

finally hit the generate KML button, specify output path for KML file

Enjoy it!

Note that distance for point also calculated by following formula
this is (C2,D2) Long.,Lat. for point one and (E2,F2)Long.,Lat for point two
=ACOS(COS(RADIANS(90-D2)) *COS(RADIANS(90-F2)) +SIN(RADIANS(90-D2)) *SIN(RADIANS(90-F2)) *COS(RADIANS(C2-E2))) *6371
