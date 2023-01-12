# Outline of Project
### For internal planning purposes

The inital version of the project will be as follows:
- A user creates yaml files for each set component describing a system
- User then creates a master yaml file that descibres relations between components
    - this fille will also include the optimization goals
- the user will then pass the created files to a command in the CMD
- an output text and file will be generated describing the ideal solution

The methods used to solve the problems will for the most part follow the procedures decrived by MOTTS and Shigleys from my UBC Mech 325 course

One of the challenges is sorucing data and graphs of the information required

## Chain Designer
using paramter defined by yaml files out put the optimal chain drive using the given constraints

- input file consists of:
    - input rpm
    - output rpm or gear ratio
    - torque or hp
    - material
    - targets goal weights
        - size
        - weight (approx)
        - factor of saftey
            - min factor of saftey

- output file consists of:
    - center distance
    - chain length
    - sprocket diameters
        - teeth count
    - factor of saftey at important point
        - max and min factor of saftey

## Shaft Designer
using paramter defined by yaml files out put the optimal shaft using the given constraints
    
- input file consists of:
    - shaft elements (gears, sprokets, sheaves, bearings)
        - element forces/torques
        - input rpm
        - locating method
            - key
            - shoulder
            - snap ring
        - location
    - material
    - targets goal weights
        - size
        - weight (approx)
        - factor of saftey
            - min factor of saftey

- output file consists of:
    - shaft diameters along shaft
        - and inside diamters
    - filet radius
    - factor of saftey at important point
        - max and min factor of saftey


