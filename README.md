# Google-Hash-Code-2022
This repository contains our attempt for the <b>[Google Hash Code 2022, Qualification Round](https://codingcompetitions.withgoogle.com/hashcode/)</b>. The code is written in a single Java file. The inputs and outputs are stored in <b>.txt files</b>.

## Directories

+ <u>[JaKichuDiyeDe.java](./JaKichuDiyeDe.java)</u>: Contains the code
+ <u>[input_data](./input_data/)</u>: Contains the input testcases
+ <u>[output_data](./output_data/)</u>: Contains the output of the program

## Code Structure
We used 4 nested Classes. Their definitions are given below:

+ <u>`Contributer:`</u> Stores information related to each contributer
+ <u>`Project:`</u> Stores information related to requirements for each project
+ <u>`Skill:`</u> Stores information related to requirements of the skillset for a project
+ <u>`ProjectExecution:`</u> Simulates the execution of a project

## Algorithm
The algorithm uses a simple heuristic to assign a cost to each unfinished project based on the current day. The projects then get assigned contributers <b>greedily</b> in descending order of their cost function.

## Remarks
We were able to obtain <b>International Rank - 95</b> and <b>National Rank (India) - 4</b>. Honestly, neither of us were expecting such results. The decision to take this competition was made 3 hours prior to the actual competition, simply as a fun exercise. But we are extremely pleased with the outcome.

<i>An additional note, the code was taking too long to execute for the final test case. Hence, the code was made to break before full execution. Whatever obtained in the output directory was submitted.</i>
