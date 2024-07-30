# FlightWatch

In this application, users can view a list of flights and subscribe to receive notifications about them. Admins have the ability to update the status of flights and add new ones. This ensures that all subscribers are informed of any changes in real-time.

## Installation

```bash
For Frontend

cd client
npm install
npm start
```

```bash
For Server

cd server
npm install
npm start
```

```RabbitMQ Consumer
For RabbitMQ worker

node .\Consumer\consumer.js
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

Create .env in Both Client and Server.

Client :

`REACT_APP_BACKEND`

Server :

`PORT`

`DATABASE`

`DB_USERNAME`

`DB_PASSWORD`

`HOST`

`DIALECT`

`JWT_SECRET`

`JWT_EXPIRES_IN`

`QUEUE`

`RABBITMQ_URI`

`EMAIL_SENDER`

`EMAIL_SENDER_PASSWORD`

`EMAIL_SERVICE`

`TWILIO_ACCOUNT_SID`

`TWILIO_AUTH_TOKEN`

`TWILIO_PHONE_NUMBER`

## Screenshots

![alt text](<Screenshot 2024-07-30 114837.png>)

![alt text](<Screenshot 2024-07-30 115027.png>)
