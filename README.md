# Random-User-API-Performance-Test-Using-JMeter

## Here in this project, I attempted to find the actual TPS for a site with a given number of users and time frame. Then I tried to find out the bottleneck/stress test point. (At which point the system starts to show 1% error).
   - Site Tested: https://random-data-api.com/api/v2/users
   - Number of User: 120000
   - Timeframe: 12 Hours

## Tools / Technology Used
  - JMeter
  
## Scenario
  - Find the Actual TPS
  - Compare it with Expected TPS
  - Find out the Bottleneck/Stress test point
  
## Prerequisite
  - Java must be installed (Preferred version 8 or 11)
  
## How to run this project
  - Clone this project
  - Open the jmx file using JMeter
  - Test with different time frame and users to find the target value
  
## TPS calculation
  Link to Excel: https://docs.google.com/spreadsheets/d/1QP_rwRzCUuiVU4z7Zdso7LqvRulhhvWZ/edit?usp=sharing&ouid=111664543842830847321&rtpof=true&sd=true
  
## Bottleneck Calculation
  Link to Excel: https://docs.google.com/spreadsheets/d/1Ws2pLtIEFNZDnqykWmo-RibvB97-WGHe/edit?usp=sharing&ouid=111664543842830847321&rtpof=true&sd=true
  
## Necessary Formulas
   - Throughput = Number of users / seconds
  
## TPS Output 
  - First break down the process
  -  ![image](https://user-images.githubusercontent.com/111375124/194072172-2fd9ae08-0885-4451-ba17-d013d530e614.png)
  - Perform tests with different number of users and timeframe
  - ![image](https://user-images.githubusercontent.com/111375124/194072354-04dc470d-48f6-42ea-9008-6e1dcbfa31ba.png)


## Bottleneck Output
  - First break down the process
  -  ![image](https://user-images.githubusercontent.com/111375124/194072172-2fd9ae08-0885-4451-ba17-d013d530e614.png)
  - Perform tests with different number of users with same timeframe
  - ![image](https://user-images.githubusercontent.com/111375124/194072720-e47eae27-92c8-44c2-819c-9ee674420818.png)

