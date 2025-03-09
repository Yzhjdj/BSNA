# BSNA(The code will be made public once the paper is accepted.)

# 3D Nuclear Waste Packing Problem Solver

This repository contains code for solving the **Three-Dimensional Nuclear Waste Packing Problem* using a beam search-based algorithm. The solution is packaged as a runnable JAR file that can be executed with Java.

## Usage

### Running the JAR File

You can directly run the JAR file using the following commands:

### Process a Single Problem

To solve a single problem instance, use the following command format:

`java -jar 'path_to_jar_file' 'problem_n.txt_folder_path' 'output_folder_path' 'n' 'parameter_a_value' 'runtime'`

#### Example:
`java -jar C:\out\artifacts\BSNA_jar\BSNA.jar C:\dataset\C C:\outcome 81 0.7 30`

This will solve the problem defined in `problem81.txt` located in the `C:\dataset\C` directory. The results will be saved in the `C:\outcome` folder. The algorithm will run for 30 seconds, with `b=0.1`

## Requirements

Java 8 

