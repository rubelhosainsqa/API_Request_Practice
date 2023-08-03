### API_Request_Practice

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run API_Request_Practice.postman_collection.json -e API_Request_Practice.postman_environment.json
```
- Run Command for Report: 
```console 
newman run API_Request_Practice.postman_collection.json -e API_Request_Practice.postman_environment.json -r cli,htmlextra
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
npm install -g newman
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/25355745/2s9XxwxEoZ

## API Request Method List:
1. ### Create Booking - POST

2. ### Get Booking - GET
	
3. ### Create Token - POST
	
4. ### Update Booking - PUT
	

5. ### Get Booking After Update - GET
	

6. ### Delete Booking - DELETE
	
7. ### Get Booking After Delate - GET
	

	
## Newman Report Summary:
![Newman Report Summary](https://github.com/rubelhosainsqa/API_Request_Practice/assets/119733194/b1edf811-b3db-4868-a90f-a4cb98ac306d)


![Newman Report Summary](https://github.com/rubelhosainsqa/API_Request_Practice/assets/119733194/9c35053a-17a8-4bc5-a2bf-6109be99d738)

