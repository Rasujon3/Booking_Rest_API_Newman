# Booking_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Restful-booker.postman_collection.json -e BatchIT.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Restful-booker.postman_collection.json -e BatchIT.postman_environment.json -r cli,htmlextra
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
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/13082503/2s93Xwz4Az

## Test case list:
1. ### Create Auth Token
	> Using Form Data with those data
	1. username : admin
	2. password: password123
	
1. ### Create Booking
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Crated Booking Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

3. ### Update Booking
	> In the test case you need to validate the following field values:
 	1. > Only Message
4. ### Verify Verify Updated Booking Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

5. ### Get the Booking's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

6. ### Delete Specific Booking
	> In the test case you need to validate the following field values:
	1. > Only Message

## Newman Report Summary:
![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209683-ddb8e3c5-4f23-4355-8919-61cd6ddca91a.png)

![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209794-f84c539b-e3cf-4e80-ab0e-9d6d59b1a339.png)
