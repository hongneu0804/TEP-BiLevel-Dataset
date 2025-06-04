## File Description
Shengbo Hong, State Key Laboratory of Synthetical Automation for Process Industries, Northeastern University, China

This repository contains data and resources related to the Tennessee Eastman Process (TEP) public simulation platform and bi-level decision-making research. The contents are organized as follows:

- `temexd_mod/`: MATLAB simulation files from the official TEP public platform, used for generating process data.
- `ISOPE_upper_layer.csv`: Upper-layer dataset representing high-level decision variables (e.g., setpoints) constructed from the TEP simulation.
- `ISOPE_lower_layer.csv`: Lower-layer dataset representing low-level operational variables (e.g., manipulated variables) corresponding to the upper-layer decisions.
- `paper1.pdf`: The primary reference paper that proposes a bi-level decision-making algorithm based on the TEP simulation platform. The two CSV datasets above were constructed based on the methodology described in this paper.
- `paper2.pdf`, `paper3.pdf`, `paper4.pdf`: Supplementary materials related to the TEP public dataset, providing additional insights and support for further study and reproduction.

