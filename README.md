# Introduction

To support M1Pay Payment Integration in PHP language for MobilityOne.
The development is using Docker.

⚠️ Disclaimer: This project provides code for M1Pay Payment Gateway integration functions only. It has been tested on my own server and worked as intended. If you fork or reuse this code, please modify it accordingly to fit your own environment and requirements. Use at your own discretion.

# Requirements
Register to M1Pay first  

# Process to Setup M1Pay Payment Integration
1- Initial setup usualy on M1Pay UAT Environment before live in production server.  
2- After registration and M1 approve, merchant may obtain the credential such as  
   - Client ID  
   - Client Secret  
   - File of private key  
   - File of public key  

3- Merchant's developer need to copy and paste `.env_sample` and rename the file as `.env`  
4- The Client ID and Client Secret value must place in .env accordingly.  
5- The key files must placed in merchant's server and set the path of the files under 'PAYMENT_CERTS' accordingly.  

# Contact M1Pay for
Registration : bd@mobilityone.com.my  
Transaction Inquiries : ccc@mobilityone.com.my  
Technical Issues Related to PHP coding : amalina.works@gmail.com (Attention to Ms Amalina Nusyirwan)
