# BSNA(The code will be made public once the paper is accepted.)

# 3D Nuclear Waste Packing Problem Solver

This repository contains code for solving the **Three-Dimensional Nuclear Waste Packing Problem* using a beam search-based algorithm. The solution is packaged as a runnable JAR file that can be executed with Java.

## Usage

### Running the JAR File

You can directly run the JAR file using the following commands:

### Process a Single Problem

To solve a single problem instance, use the following command format:

`java -jar 'path_to_jar_file' 'problem_n.txt_folder_path' 'output_folder_path' 'runtime' 'num_threads' '1(default)' 'parameter_b_value' 'minFillRate' 'n'`

#### Example:
`java -jar C:\out\artifacts\BSGT_jar\BSPA.jar C:\dataset\C C:\outcome 30 16 1 0.1 1 21`

This will solve the problem defined in `problem21.txt` located in the `C:\dataset\C` directory. The results will be saved in the `C:\outcome` folder. The algorithm will run for 30 seconds, using 16 parallel threads, with `b=0.1`, `minFillRate=1`

### Process the Entire Dataset

To process an entire dataset, use the following command format:

`java -jar 'path_to_jar_file' 'dataset_folder_path' 'output_folder_path' 'runtime' 'num_threads' '1(default)' 'parameter_b_value' 'minFillRate'`

#### Example:

`java -jar C:\out\artifacts\BSGT_jar\BSPAForSet.jar C:\dataset\C C:\Coutcome 30 16 1 0.1 1`

This will process all problems in the `C:\dataset\C` directory, saving the results in the `C:\Coutcome` folder. The algorithm will run for 30 seconds, using 16 parallel threads, with `b=0.1` and `minFillRate=1`.

## Requirements

- Java 8 

