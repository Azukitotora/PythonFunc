# MakeMeshFromLatLong.py
Add mesh number in the data
e.g.
from func import MakeMeshFromLatLong as MMFLL
data = MMFLL.MakeMeshGridFromLatLong(data,50,37.52995,139.95510,37.48896,139.92480,"latitude","longitude","50meshNum")

# MakeRepPoint.py
Make representative point from latitude and longitude in the data
return new data
e.g.
from func import MakeRepPoint as MRP
repdata = MRP.MakeRepPoint(data,"50meshNum",50,37.52995,139.95510,37.48896,139.92480,"latitude","longitude")
NOTE: Need mesh_number in the data. You can get this data from MakeMeshFromLatLong.py
