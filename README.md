# SiDB-Bench

This is a collection of randomly generated SiDB layouts that can be used for benchmarking. 

#### General information:

- Make sure that [Git LFS](https://git-lfs.com/) is installed on your machine. 

#### Folder structure of the ``random_layouts``:
- number_sidbs_#; # of SiDBs.
- Each of these folders consists of a ``loc`` and a ``sqd`` folder.

sqd folder:
- Layouts are stored as ``sqd`` files. Layouts can be simulated in [SiQAD](https://github.com/siqad) or [fiction](https://github.com/marcelwa).

loc folder:
- File names always have the same structure: The first number is the layout number, the last number is the µ-value used for the simulation.
- Data stored in the file: 
  -   The first two columns are the x,y coordinates of the SiDBs in nm.
  -   The last column is the charge state of the corresponding SiDB for the ground state (if the ground state is degenerate, several columns are provided).
  
  
  #### Data overview:
- Randomly generated layouts on a 40 X 40 grid.
- There are layouts with `1` placed SiDB up to and including `35` placed SiDBs.
- From 1 to 32 SiDBs: 500 Layouts for each.
- From 33 to 35 SiDBs: 50 Layouts for each.
