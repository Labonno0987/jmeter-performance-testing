# JMeter API Testing & Performance Evaluation
## Description
 This repository includes JMeter test plans for two API scenarios. The Booking API (booking.jmx) is designed for performance testing, including load and stress tests, to evaluate system stability. The Dmoney API (dmoney.jmx) focuses on functional testing of financial transactions, ensuring seamless deposits, money transfers, and payments.

## Technology I used
- JMeter
- Postman

## Prerequisites
Before running the tests, ensure you have:
- Apache JMeter installed
- Java (JDK 17) installed

## How to run this project
- ### Clone the Repository
     - ```git clone https://github.com/Labonno0987/jmeter-performance-testing.git ```
     - ```cd jmeter-performance-testing ```
       
- ### Running the Booking API Test (Performance Test)
   - #### Steps
      - Open booking.jmx in JMeter.
      - Run the test for 5 minutes, then 10 minutes, then 20 minutes.
      - Check the HTML report for results.
      - If the load test passes, gradually increase the users to find the bottleneck (stress test).
      - Generate an HTML report and save results in booking-api-test-report.xlsx.
        
- ### Running the Dmoney API Test (Functional Test)
   - #### Steps
      - Open dmoney.jmx in JMeter.
      - Ensure the deposit.csv, sendMoney.csv, and payment.csv files are present.
      - Run the test to validate financial transactions.
## CSV File For those test
https://docs.google.com/spreadsheets/d/1Le9AZrgVxg_jc8Q0ueeENUO_W8y6h42C/edit?usp=sharing&ouid=106851050293382559720&rtpof=true&sd=true
## Results & HTML Reports
   - ### Booking API 
     ## For Load Testing:
     - ![Load Test Report](https://github.com/user-attachments/assets/97055ba7-9883-4430-9f2a-9d0d9d175198) 
     ## For Stress Testing: 
     - ![Stress Test Report](https://github.com/user-attachments/assets/f13e64e7-714f-4209-90a5-16f5aa734116) 
   - ### Dmoney API
     - ## For Functional Testing: 
     - ![Dmoney Report](https://github.com/user-attachments/assets/b11de3ce-c6f6-440e-bf00-f07f7282eda1)

    




