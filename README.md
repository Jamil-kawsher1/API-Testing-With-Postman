
#  API Testing With PostMan (Dmoney)

This is A Simple API Testing Project Where I try to test an API(DMoney) which is mainly an MFS API.
Here User Can Do All There Financial Transactions using It like Bkash.

I have done All the tests manually and also done All the test cases which cover all the features of this API.

After that, I have done all the assertion points to do the API Automation.
Finally, I have generated report using Newman.


## Author

- [@Jamil-kawsher1](https://www.github.com/Jamil-kawsher1)


## How to run this project

- Clone This project
- Then run the follwing command 

```bash
  npm i
  npm run report.js
```
## Tools Used
- Postman
- Newman


## Test Case:
https://docs.google.com/spreadsheets/d/1TlqU_8-HCT_h76P69iPLE_aJhjsKX7g9/edit?usp=sharing&ouid=105413695096846736430&rtpof=true&sd=true

## Bug And Improvement Report:
https://docs.google.com/spreadsheets/d/1GpIxce69jw1vQdlDSwo0Bdi1SlfEMjH0/edit?usp=sharing&ouid=105413695096846736430&rtpof=true&sd=true

# Postman documentation:
https://documenter.getpostman.com/view/23351657/2s8ZDbX1VA

# Newman Full Live Report Link
https://newmanlive.netlify.app/

### ScreenShot of Newman Report
![image](https://user-images.githubusercontent.com/42008531/214326339-ffb3d907-c97c-4ba5-bbfc-73131a68322f.png)
![image](https://user-images.githubusercontent.com/42008531/214326554-bfbc94b1-6b9a-4f72-acc8-8fb88dd7ed8d.png)



## Positive and Negative case are Created for Follwing Scenraio

1. Admin creates an agent and random 2 customers
2. Deposit some money from SYSTEM account to the agent
3. Agent deposit to any of 1 customer
4. The customer checks balance
5. Then withdraw any amount from the agent
6. And send money to the other customer
7. Then the customer will check statement
8. For each transaction, assert expected balance

