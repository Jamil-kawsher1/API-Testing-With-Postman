
#  API Testing With PostMan (Dmoney)

This is A Simple API Testing Project Where I try to test an API(DMoney) which is mainly an MFS API.
Here User Can Do All There Financial Transactions using It like Bkash.

I have done All the tests manually and also done All the test cases which cover all the features of this API.

After that, I have done all the assertion points to do the API Automation.
Finally, I have generated report using Newman.


## Author

- [@Jamil-kawsher1](https://www.github.com/Jamil-kawsher1)

## Tools Used
- Jmeter

## Request I have Covered

1. Login to user
2. Create a new agent
3. Give balance to the newly created agent from system
4. Create a customer
5. Search the newly created user by phone number
6. Deposit balance to the customer from the agent
7. Withdraw some money from the agent
8. Delete the user

## How to run this project

- Clone This project
- Then run the follwing command 

```bash
 $ jmeter -n -t Jmeter Performance test using API Chaining.jmx -l Dmoney-Load-Test.csv -e -o Reports
```




## Requests ScreenShot:
![image](https://user-images.githubusercontent.com/42008531/215797249-68846705-e712-4ca7-8d61-c008d0567b65.png)


## Genarated HTML Report:
![image](https://user-images.githubusercontent.com/42008531/215797749-308c1b5c-7ceb-4a6e-a4c4-24fcfb55c692.png)
![image](https://user-images.githubusercontent.com/42008531/215797920-9099178b-0278-46e0-9439-aec27aef7174.png)

# Summary Report:
![image](https://user-images.githubusercontent.com/42008531/215798969-059fbaf0-56b2-4514-abab-393e0824bb22.png)







