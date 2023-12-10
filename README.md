# Dunkin' Donuts Drive-Thru Queueing Analysis

The project file can be found [here](https://github.com/omotuno/Dunkin-Donuts-Drive-Thru-Queueing-Analysis/blob/main/Queuing%20Project%20.pdf), the code can be founde [here](https://github.com/omotuno/Dunkin-Donuts-Drive-Thru-Queueing-Analysis/blob/main/Queuing%20Code.pdf)
### This project analyzes the queueing process at a Dunkin' Donuts drive-thru location in Bowling Green, OH. Queueing data was collected for 54 cars over a 90 minute morning peak period. The analysis focuses on the following:

-- Calculating inter-arrival times, queueing times, service times, and waiting times

-- Exploring distributions of these metrics

-- Modeling the queueing process as an M/M/1 queue initially but realizing it is better described as a 4-node tandem queue
<img width="796" alt="Screenshot 2023-12-10 at 4 56 49 PM" src="https://github.com/omotuno/Dunkin-Donuts-Drive-Thru-Queueing-Analysis/assets/65866718/e009029d-f788-4b99-a92f-90b701f6be69">
<img width="886" alt="Screenshot 2023-12-10 at 4 56 58 PM" src="https://github.com/omotuno/Dunkin-Donuts-Drive-Thru-Queueing-Analysis/assets/65866718/2a9d596e-aa0c-4df0-a258-9646800cb949">
<img width="779" alt="Screenshot 2023-12-10 at 4 57 09 PM" src="https://github.com/omotuno/Dunkin-Donuts-Drive-Thru-Queueing-Analysis/assets/65866718/f1713a93-ec09-4c2d-9300-f27be6f1dc18">


### Key findings:

-- Inter-arrival times follow an exponential distribution with mean 1.57 mins

-- Service and waiting times do not match common distributions

-- The system is actually a 4-node tandem queue rather than M/M/1

-- Arrival rate is 0.635 cars/min and mean service time is 5.19 mins

-- More data needed on service times at each node to properly model the full system


#### The analysis provides insight into queueing behavior but is limited by the data collected. Further observation to capture node-level service times would allow for more detailed modeling.


##### code= Queuing.pdf
##### writeup= Queuing Project.pdf
