# fpga_workshop
## Day 1
1.Use the given RTL and simulation sources


![image](https://user-images.githubusercontent.com/19501036/160136251-ba92961e-86b3-419e-8764-544dd6eeaf3a.png)

2.Run the simulation
![image](https://user-images.githubusercontent.com/19501036/160138501-177e6c29-f20d-4948-ace7-ba8591c0f93a.png)

3.Generate the Constarints File
![image](https://user-images.githubusercontent.com/19501036/160141394-597edbf0-5d86-4fe7-a49a-1778fa39b318.png)

4.Since clock is not defined for simulation it cannot have any reference to report the timing
![image](https://user-images.githubusercontent.com/19501036/160142357-a31d7b11-a716-4870-b74d-fd95a391b085.png)

5.Timing Constraints

6.This is power consumed by the FPGA to implement the design
![image](https://user-images.githubusercontent.com/19501036/160146209-de69c9fb-4f87-421e-a793-af9ea4933bb5.png)

## ---------------------------------------------------------------------------------------------------------
## Day 2
Ran the VTR command with Earch file and Berkeley Logic Interchange Format (Blif) file 
https://course.ece.cmu.edu/~ee760/760docs/blif.pdf

This is the command with the display ON.
![image](https://user-images.githubusercontent.com/19501036/160222888-eb327f4d-8ea6-4dc5-b7cf-d2fcbad6d19f.png)

1..net file contains the netlist
2..place gives the placement
3..route the routing that has done
4.packing pin report will the pin utilisation
5.report_timing_setup will give the timing analysis
  - Since the timing constraints is not provided the this will not be a valid analysis

![image](https://user-images.githubusercontent.com/19501036/160223508-6ea3f6f0-490b-49c3-b90c-b72b28e2a2ef.png)

After the passing on the Blif file the 
![image](https://user-images.githubusercontent.com/19501036/160223618-f4af87c8-8146-4b6d-b889-1dbf0c6cd7df.png)


![image](https://user-images.githubusercontent.com/19501036/160224075-3f8b1f0b-e7fd-40a6-bd42-b555fd078d50.png)




