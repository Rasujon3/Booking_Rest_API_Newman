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
- https://restful-booker.herokuapp.com/apidoc/index.html

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
![booking-rest-api-newman](https://user-images.githubusercontent.com/61946723/232899693-41562a12-1e93-4742-bc56-748e4363a6e9.png)
