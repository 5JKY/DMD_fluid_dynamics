# DataDrivenFluid
Illustration of Proper Orthogonal Decomposition (POD) and (DMD)

Data    : flow past a cylinder at Reynolds number, Re = 200. There are two data files.
          Only one data uploaded.

          cyldata6h.csv contains 600 snapshots of the vorticity at a time step of dt = 0.125
            
          The grid consists of 768 x 192 points in the streamwise and spanwise directions. 
          The field is stored as an 1D vector of size 768*192 = 147456
          
          A smaller data, cyl_data_clean.csv, contains the vorticity at a time step of dt = 0.02
          This field is stored as 151 of 1D vectors of size 199*499.

          There are an example code (python script) showing how to read and visualize the data. 
          
# DMD_fluid_dynamics
