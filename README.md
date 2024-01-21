# Simple Email Queue

This project is a simple email queue service written in TypeScript using NestJS, SQLite, and RabbitMQ.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- NestJS
- SQLite
- Type ORM
- Node Mailer
- RabbitMQ

### Installing

1. Clone the repository
```bash
git clone https://github.com/faiaz000/simple-email-queue.git
```
2. Navigate into the cloned repository
```bash
cd simple-email-queue
```
3. Install the dependencies
```bash
npm install
```
4. Start the RabbitMQ server (you may need to adjust this command based on your RabbitMQ installation)
```bash
rabbitmq-server
```
5. Run the service
```bash
npm start
```

## Usage

The service connects to a RabbitMQ server running on localhost using the AMQP protocol. It listens for messages on a specified queue and sends emails based on the received messages.

Sure, here's the updated README with the notes section:

```markdown
# Simple Email Queue

This project is a simple email queue service written in TypeScript using NestJS, SQLite, and RabbitMQ.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- NestJS
- SQLite
- RabbitMQ

### Installing

1. Clone the repository
```bash
git clone https://github.com/faiaz000/simple-email-queue.git
```
2. Navigate into the cloned repository
```bash
cd simple-email-queue
```
3. Install the dependencies
```bash
npm install
```
4. Start the RabbitMQ server (you may need to adjust this command based on your RabbitMQ installation)
```bash
rabbitmq-server
```
5. Run the service
```bash
npm start
```

## Usage

The service connects to a RabbitMQ server running on localhost using the AMQP protocol. It listens for messages on a specified queue and sends emails based on the received messages.

## Notes

- RabbitMQ needs to be installed and running on your machine. You can download it from [here](https://www.rabbitmq.com/download.html).
- You need to create a `.env` file in the root directory of the project with the following variables:

```properties
SMTP_HOST = XXXX
SMTP_PORT = XXXX
SMTP_USER = XXXX
SMTP_PASSWORD = XXXX
FROM_EMAIL = XXXX
```

Replace `XXXX` with your actual SMTP server details and email.

