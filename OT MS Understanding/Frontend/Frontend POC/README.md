# Frontend POC
### This document provides Proof-of-Concept (POC) of frontend in detail.

## Table of Contents

- [Introduction](https://github.com/Kaustubh9804/sprint1/tree/main?tab=readme-ov-file#introduction)
- [Pre-Requisites](https://github.com/Kaustubh9804/sprint1/blob/main/README.md#pre-requisites)
- [Walkthrough_of_Frontend](https://github.com/Kaustubh9804/sprint1/blob/main/README.md#walkthrough-of-frontend)
- [Contact](https://github.com/Kaustubh9804/sprint1/blob/main/README.md#contact)

## Metadata

| Author        | Created On | Version |
|---------------|------------|---------|
| Kaustubh Battul  | 12-11-2024 |  1   |

## Introduction

The frontend application is based on REACTJS which main ui of [OT-Microservices](https://github.com/OT-MICROSERVICES) stack. This application is cross-platform, meaning it can run on different operating systems as long as a JavaScript runtime environment is available. A ReactJS-based web framework that powers the application's entire web page functionalities.

## Pre-Requisites
- **Node.js**: The runtime environment for executing JavaScript on the server side.
- **NPM (Node Package Manager)**: Used to install, manage, and run dependencies and packages in your application.


## Walkthrough of Frontend
To get started with the attendance API POC, follow these steps:

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/OT-MICROSERVICES/frontend.git
    cd frontend
    ```
 ![Screenshot from 2024-11-11 14-06-33](https://github.com/user-attachments/assets/84b736f8-b674-4f57-8ad6-27acbc88a3a2)
   


2. **Create directory name `Public`** into frontend directory and create `index.html` file Where we have add following content.
```
html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>React App</title>
</head>
<body>
  <div id="root"></div>
</body>
</html>
```

3. **Edit the package.json file:**
Here, in `package.json` change the Change ip-address by your public ip-address in the proxy with valid port.


![Screenshot from 2024-11-11 13-08-11](https://github.com/user-attachments/assets/834759fe-906d-4d64-8e05-0435204cb8b0)


4. **Install nodejs:**
```sh 
    sudo apt update
    sudo apt install nodejs -y
```
![Screenshot from 2024-11-11 14-24-57](https://github.com/user-attachments/assets/577730ad-716f-4fc9-9055-a58d62e1f43a)


5. **Building the application:**
For building the application. we can use make command from the Makefile. The command is as follows.
```sh
    make build
```
![Screenshot from 2024-11-11 14-43-29](https://github.com/user-attachments/assets/ca604e9e-610e-4092-9f11-87c1f0a2fb8a)


6. **For Running the application:**
The command for running the application the command is as follows.
```sh
    npm start
```
![Screenshot from 2024-11-11 15-45-38](https://github.com/user-attachments/assets/d59ce301-3dce-454b-b6d6-b2f06b799d9c)



7. **Output:**
Finally the output from running the above Command is given below 

![Screenshot from 2024-11-11 15-40-31](https://github.com/user-attachments/assets/f0ac2082-3d2f-4fd8-b4f3-677c28d375ea)



## Contact

| Name          | Email Address       |
|---------------|---------------------|
| Kaustubh Battul |  kaustubh.battul.snaatak@mygurukulam.co|
