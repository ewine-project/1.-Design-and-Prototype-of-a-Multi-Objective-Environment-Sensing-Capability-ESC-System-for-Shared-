# Design and Prototype of a Multi-Objective Environment Sensing Capability ESC System for Shared With Rotating Radars
## Summary 
Recent recommendations by regulatory bodies to use a distributed network of spectrum sensing/measurement devices, called environmental sensing capability (ESC) devices, which facilitates shared access (SA) between wireless communications and rotating radar systems has generated considerable research interest. We demonstrate a prototype of a multi-objective ESC system that facilitates a spectrum access system (SAS) to enable SA with ground-based fixed rotating radars. The implemented ESC device 1) detects radar signals; 2) measures interference from secondary users (Sus) for radar protection; and 3) also measures SUs’ airtime utilization (ATU) in a channel. The proposed ESC assisted SAS architecture can help in reducing the size of currently proposed large exclusion zones around the rotating radar systems. The prototype of the proposed ESC is implemented on Wireless Open Access Research Platform (WARP) nodes with Xilinx Field-programmable gate array (FPGAs).
## Brief description
While the use of a spectrum access system (SAS) to facilitate spectrum sharing has been the focus of research during the last few years, the design of a distributed network of ESC devices is a relatively new topic and its development is clearly in early stages [1]. In general, much of the effort on ESC design has focused on the study of a network of distributed sensors that can detect/geolocate shipborne rotating radars in 3.5 GHz band. In such a design, once an incumbent radar is detected then any SU active on the same channel within the radars’ protected contour is moved to another channel. However, in this proposal, we focus on an ESC-SAS-based sharing approach in the frequency channels of ground-based fixed rotating radar systems. Some examples of rotating radar systems and their frequency usage include: 1) weather radar systems in the 5 GHz band; 2) airport surveillance radar systems in the 1030 MHz uplink channel and their 1090 MHz downlink channel, and 3) surveillance radar systems in 2200-2245 MHz band. In this work, we design and prototype a sensor/measuring device. A distributed network of such devices can enable an ESC to assist the SAS to allow an efficient use of the frequency channels of ground-based fixed rotating radar systems on a SA-basis. The proposed ESC can help reduce the size of currently proposed large exclusion zones around the rotating radar systems. This in turn can allow a higher number of SU transmissions with the same level of interference protection to a radar system. In particular, we present a novel ESC algorithm which is used to: 1) detect the presence of a radars’ transmissions; 2) measure interference from SUs for incumbent protection; and 3) measure SU airtime utilization (ATU) in a channel which can be used by a SAS to help improve SU spectrum utilization. A prototype of the proposed ESC devices is also implemented on a Wireless Open Access Research Platform (WARP) devices with Xilinx field-programmable gate array (FPGA). The effectiveness of the proposed design and its FPGA-based implementation will be demonstrated under various scenarios.
![Alt text](https://user-images.githubusercontent.com/24733570/32942167-813b61d6-cb88-11e7-85d3-1ca753aff580.png)
## Algorithm description
### ESC Device Algorithm for SA with Rotating Radars
![Alt text](https://user-images.githubusercontent.com/24733570/32941929-bb5818d8-cb87-11e7-9295-7bff1511ca4d.png)
### Adaptive Noise Floor Estimation Algorithm 
![Alt text](https://user-images.githubusercontent.com/24733570/32942342-0e55022a-cb89-11e7-9aca-c442a2344f5a.png)
### Interference Design Module
![Alt text](https://user-images.githubusercontent.com/24733570/32942343-0e69a7de-cb89-11e7-8f1c-85b508e18137.png)
### Secondary Users Airtime Utilization Module
![Alt text](https://user-images.githubusercontent.com/24733570/32942344-0e7cf99c-cb89-11e7-9c19-a06d5bccd81b.png)
### Radar Signal Detection Module
![Alt text](https://user-images.githubusercontent.com/24733570/32942345-0e9096d2-cb89-11e7-9675-ef251c288a18.png)
# Reference 
If you want more information, then your can refer to our publised paper. In addition, if you find any information in the content that is help for your research, then please cite the paper in your work.

*Khan Z, Lehtomäki JJ, Aguilar-Gonzalez R, Vuohtoniemi R, Hossain E, DaSilva LA, Marshall A. Database-Assisted Distributed and Cloud-Based Access Methods for Unlicensed and Radar Bands. IEEE Transactions on Cognitive Communications and Networking. 2017 Sep;3(3):404-19.

# Contact
zaheer.khan@oulu.fi

