# Intro
This repo contains two dashboards for monitoring and investigating security states of a tenant. These are used in PowerBi, and entering in your own data can provide you with the same insights. 

# Vulnerability Management Dashboard
This focuses in on 365 Defender's Threat and Vulnerability Management platform. Using hunting queries via the Graph API and authenticating directly using a Microsoft Account, we can get direct insights on vulnerabilities:

## Pages

### Home/Filter page applying to all other pages
![image](https://github.com/user-attachments/assets/872f882e-493d-4e8f-b2f9-668311117be2)

### Device Inventory
![image](https://github.com/user-attachments/assets/b018603c-2687-4ebe-8e41-62cdfe232594)

### Software Inventory
![image](https://github.com/user-attachments/assets/ba152bc9-b36f-4146-b019-65c2e3c6b32d)

### Last 2 Weeks of Vulnerabilities
![image](https://github.com/user-attachments/assets/10249b74-3334-4282-b94e-013c72d80d9c)

### CVE Inventory
![image](https://github.com/user-attachments/assets/ac59bddd-5411-4806-8ace-dff86f65d297)

### Raw Data Table
![image](https://github.com/user-attachments/assets/1ed0e787-55b7-4206-a956-c36e86d7b64f)

# International Signin Dashboard
Using data from a Logs Analytics Workspace, this provides insight into different types of logins from different countries and of different types. Data can also be filtered to only look for certain types of logins or countries. 

## Pages

### Home/Map
![image](https://github.com/user-attachments/assets/a7915657-2a7b-45c7-9aa7-71954a09c881)

### Raw Data
![image](https://github.com/user-attachments/assets/79cd46fa-cf83-4db9-8aab-51228dbe749a)

### Note: For this to work, you need to enter your Logs Analytics Workspace ID here:
![image](https://github.com/user-attachments/assets/2efdb0c2-38bd-4341-aad1-baeddeac4098)


