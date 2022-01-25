# Duplicate Elimination using The Two-Pass Multiway Merge Sort

Using `jdk-11.0.11.9-hotspot`

## Folder Structure
- `src`: The folder to maintain sources.
- `output`: The sorted relation with distinct records is stored in this folder.
- `input`: Program looks for the specified relation in this folder.

Meanwhile, the compiled output files will be generated in the `bin` folder by default. Input and Output locations can be changed in Constants.java file. 

## Execution Parameters

The execution parameters such as the available memeory size and command line arguments can be modified from Run Configuration in Eclipse IDE. 

## Command Line Arguments

1. `filename`: The program expects the first command line argument to be the name of file containing the relation. This file must be located in the `input` directory. 

2. `v`: Verbose. Optional argument to display all the duplicated records as they are found.
