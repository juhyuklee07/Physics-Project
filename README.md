# Physics-Project
Chain Fountain simulation
- Group name : 1234
- Programming language : Python
- Description : This simulation computes the critical angle, the height that the chain is lifted off, and the steady-state chain speed based on the equations of the Pantaleone's paper.
- How to use this :
  1. Select chain types : Choose the chain type ("ball" or "bar")
  2. Enter parameters: Input the physical values following the units requested:
   - D (Diameter in cm)
   - L (Length in cm, for ball chains it is length between two centers, and for bar chains it it length between two outer hemisphere's center)
   - S (Cylindrical section length in cm, only for bar chains)
   - h_below (Height below the container in m)
  3. Results : The simulation will calculate and display the results. results includes these things:
   - d : delta, dimensionless parameter
   - critical angle
   - h_above / h_below
   - h_above : maximum chain fountain height above the container
   - V / V_freefall
   - V : steady-state speed
- Reference : J. Pantaleone. A quantitative analysis of the chain fountain. American Journal of Physics, 85(6):414–421, 06 2017.
