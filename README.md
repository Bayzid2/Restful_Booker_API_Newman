# Restful Booker API using Postman & Newman
## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:
   ```bash
  newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
- Run Command for Report:
  
 ```bash
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
 ```
## Technology used:
- Postman
- Newman
## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library
## Newman and Report Installation Process:
- Newman Install Command:
 ```
npm install -g newman-reporter-htmlextra
 ```
- Newman Html Report Install Command:
 ```
npm install -g newman-reporter-htmlextra
 ```
## API Documentation:
- https://documenter.getpostman.com/view/40715992/2sAYJ9BJq1
## Test case list:
 ### 1.Create Booking
   > i.Create Data Sets with dynamic values
   > ii.Verify response time
### 2.Booking Status
In the test case you need to validate the following field values:

   > i.First Name

   > ii.Last Name

   > iii.Total Price

   > iv.Deposit Paid

   > v.Checkin Date

   > vi.Checkout Date

   > vii.Additional Needs

### Token
   > i.Generate Token for authentication

### Update Booking
In the test case you need to validate the following field values:

   > i.Successfull message
   > ii.Verify response time
### Booking Status after Update
In the test case you need to validate the following field values:
   > i.First Name

   > ii.Last Name

   > iii.Total Price

   > iv.Deposit Paid

   > v.Checkin Date

   > vi.Checkout Date

   > vii.Additional Needs

### Delete Booking
   > i.Verify Status code
   > ii.Verify response time


## Newman Report Summary:

![App Screenshot](https://github.com/user-attachments/assets/521b2ed7-9613-485f-b985-ec88c7ceda73)
![2](https://github.com/user-attachments/assets/f0b69ce4-94dc-4c06-a67c-2fa5ca887112)
![3](https://github.com/user-attachments/assets/7fc48818-522d-471f-a4a4-fcaae617e99f)





