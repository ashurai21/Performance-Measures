# Performance-Measures
IMPLEMENTING OPERATIONAL MANAGEMENT PROCESS ANALYSIS TOOL AT PRECAST YARD USING SIMULATION

Steps for estimating operational performance values through ExtendSim Simulation:
1. Assuming at each front available, one crew is deployed for carrying out all the activities require for casting of segments. This is done by following command:
![G1](https://user-images.githubusercontent.com/103962807/164161180-97a01c86-8c5d-46cc-87c7-4bed3f1f1583.JPG)
2. In order to determine monthly capacity, equation function under value library is used, where processing time and crew deployed for each work is used as an input. It is important to note that only 26 days are assumed to be working days and rebar yard is in operational in day shift, and jig and casting bed stations are working in both shifts. Even in shifts, workers are not working full day, they are taking rest, doing lunch, snacks. Hence, total available time in a day for rebar yard worker will be 10.5 hours and for other workers it is 20.5 hours. Same has been used in doing capaicty calculations. 
![G2](https://user-images.githubusercontent.com/103962807/164162593-723a845b-c7a2-4a12-ad00-2ed6fd18be81.JPG)
3. Process capacity is the lowest capacity in the process flow. It is estimated by typing following command in ExtendSim:
![G3](https://user-images.githubusercontent.com/103962807/164163034-af6fc2fa-b1b8-4dc5-8a88-27d5a44acf1c.JPG)
4. Demand value is obtained from erection schedule. Demand value varies from project to project and mainly depend upon the project’s scope and duration. Assuming maximum 10 segments are required from two short-line bed in a month. Flow rate is defined as the minimum between process capacity and demand and is estimated as:
![G4](https://user-images.githubusercontent.com/103962807/164163221-939ebaa8-6810-43e7-bfbd-a9df0844ece4.JPG)
5. Utilization at each station is defined as flowrate divided by capacity. Following command has to be type for estimating utilzation values:
![G5](https://user-images.githubusercontent.com/103962807/164163768-cdf83089-0292-4177-9cf8-d123b5c9e2f8.JPG)
6. Cycle time is estimated through simulation variable, set item, and information blocks. Using following command to estimate cycle time of the process.
![G9](https://user-images.githubusercontent.com/103962807/164164131-05635b6a-a359-4bcb-b271-68c4ee596d9e.JPG)
![G6](https://user-images.githubusercontent.com/103962807/164164168-94b397dd-40f5-49ac-af03-6951cdbc87d5.JPG)
7. Idle time is the difference of cycle time and processing time and it estimated by following command:
 ![G7](https://user-images.githubusercontent.com/103962807/164164401-40db770d-3c72-4d65-85b2-8c7071097faf.JPG)
 8. Direct labour content and direct labour utilization is estimated by following command :
 ![G8](https://user-images.githubusercontent.com/103962807/164164766-ce870db1-3d78-47f1-bfce-ed57f6701e78.JPG)
