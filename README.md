## About ##

This code is about .pcd to .bin converting tool.  
PointCloud(.pcd) file includes `x, y, z, intensity, (ring, time)` data.  
You can convert all the .pcd files (sorted in ascending order by file name) in the directory.  

## How to use ##
### 0. Environment ###
Python 2.7

### 1. Install python libraries ###
`$ pip install numpy`  
`$ pip install argparse`  
`$ pip install pypcd`  
`$ pip install tqdm`  

### 2. Launch python file ###
`$ python pcd2bin.py --pcd_path={path of input pcd file directory} --bin_path={path of output bin file directory}  --file_name={name of bin file}`

#### Parameters ####
|Name|Description|Default value|
|:---|:---|:---|
|pcd_path|.pcd file path|"/home/user/lidar_pcd"|
|bin_path|.bin file path|"/home/user/lidar_bin"|
|file_name|.bin file name|"file_name"|
