# Pact Broker Demo

## About
This is a demo project to demonstrate the usage of Pact Broker. Whole demo contains two clients and a server. The clients are used to publish contracts to the Pact Broker. The server is used to verify the contracts.

## Getting Started

### Prerequisites
- Make sure you've Docker available & running in your system.
- Make sure you've .envs folder in the root of the project with the following files:

```
  * .postgres
  * .pact
```

### Running the broker
Run the broker with the following command:
```
docker-compose up -d
```



