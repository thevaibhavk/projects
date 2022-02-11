# Adele Virtual Assistance
## _Chatbot built on Rasa_

![N|Solid](https://upload.wikimedia.org/wikipedia/commons/e/e4/Rasa_nlu_horizontal_purple.svg) 

Adele (Chatbot) is an enterprise to customer end-to-end based chatbot, made for the ease of access to many fuctions on any e-commerce platform


- AI-Powered chatbot, trained using Rasa-X NLU
- Customers can change Order ID, Details, Address
- Admin can login in and see the Authentication of Address' by a adress checking API, can get visual data about the various relevant pictorial data of the Pending Orders

## Features

- Customer can enter Order ID, to check thier order Status
- Order Status can be failed due to wrong information about the Address, Phone No and Email ID
- The Customer can change thier details, and the chatbot in real-time checks these details again by various API's in the Backend
- The Customer's data is stored in a NoSQL database, and is fetched by the chatbot using API
- Admin can also login, and has all customer priveleges in addition to being able to download a real-time Data Analysis report, pie-charts based on the real-time order Activity


## Advantages

- Because RASA is an opensource platform, the the Chatbot can deployed on local servers. Rather than DialogeFlow/Alexa for sensitive infromation
- We have made Seperate Containers for the Project on Docker for easy deployment
- The Chatbot can be deployed on any platform like Telegram, Slack and Discord in under 5 Mins
