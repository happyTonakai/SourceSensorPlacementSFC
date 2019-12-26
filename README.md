# SourceSensorPlacementSFC

## Description
MATLAB scripts for "Optimizing Source and Sensor Placement for Sound Field Control: An Overview," in press for publication on  *IEEE/ACM Transactions on Audio, Speech, and Language Processing*.

The article will be open access on IEEE Xplore (https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655).

> In order to control an acoustic field inside a target region, it is important to choose suitable positions of secondary sources (loudspeakers) and sensors (control points/microphones). This paper provides an overview of state-of-the-art source and sensor placement methods in sound field control. Although the placement of both sources and sensors greatly affects control accuracy and filter stability, their joint optimization has not been thoroughly investigated in the acoustics literature. In this context, we reformulate five general source and/or sensor placement methods that can be applied for sound field control. We compare the performance of these methods through extensive numerical simulations in both narrowband and broadband scenarios.

## Usage
1. Download acoustic transfer function (ATF) data generated by FreeFEM++ (https://freefem.org/) from the following link:
   - https://www.sh01.org/data/SourceSensorPlacementSFC/atf.zip (4.83GB)
   
   To reproduce all the results, the full ATF data is required:
   - https://www.sh01.org/data/SourceSensorPlacementSFC/atf_full.zip (25.27GB)
   
2. Extract the zip file (atf.zip/atf_full.zip) in the folder "data".

3. Run "main.m".
