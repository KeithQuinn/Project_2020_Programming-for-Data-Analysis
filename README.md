# Project_2020_Programming-for-Data-Analysis

## *The Manufacturing of Medical Device Tubing*
<br>


This repository includes all files and details that make up the 2020 project for the module 'Programming for Data Analytics'.

The real-world phenomenon considered for this project was the manufacturing of medical device tubing. There are two key parts of medical device manufacturing;

- The Extrusion Process
- Process Validation

Before simulating data, it was felt necessary to provide an overview of the extrusion process and process validation.

For the extrusion process an explanation of the extruder itself is provided, this is followed with an explanation of the overall process including the downstream ancillary equipment, images and video links are included to ensure the reader has an appreciation of the process. Finally, in this section an explanation of where extrusion is used and why it's important in the medical device industry.

The next section provides a process validation overview. This section is broken into three main sections;

- Product Design
- Process Development
- Process Validation Analysis

With an understanding of the extrusion process and of process validation the next part of the project looks at the manufacturing of an extruded tube through simulation. This section starts off by identifying the process inputs and outputs and their relationships. The data types and typical distributions are discussed. Data in generated using the NumPy random function and plots of the distributions are provided and discussed.

The product design is discussed, and the part drawing provided. The process is then developed through simulation. In the development section the dimensions, specifications and tolerances are used to test the process i.e. can parts be made that are in specification. 

In the first development runs there are some process issues, these issues result in data that is off-centred, data that has a huge spread (standard deviation) and data that has too many reject parts. 

Following this there are some adjustments made to the process and a second set of process development results are generated to simulate the process improvements that have been made, this data is then analysed using the part drawing specifications. The process changes result in improved data that proves the process is capable of manufacturing parts that are in specification.

With the process looking good from a development standpoint, process validation is initiated. Once again simulated data is generated representative of the process for the validation. 

This data is then analysed in terms of process capability (Cpk). The results of the analysis determine if the process is capable enough to pass the validation. Passing the validation provides the scientific evidence required to manufacture medical device tubing for commercial use.
