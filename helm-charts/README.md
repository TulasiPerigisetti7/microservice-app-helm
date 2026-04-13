# Helm Charts

This directory contains Helm charts for deploying the microservice application components.

## Charts

- **auth-api**: Helm chart for the authentication API service written in Go.
- **frontend**: Helm chart for the frontend Vue.js application.
- **log-message-processor**: Helm chart for the log message processor written in Python.
- **redis-queue**: Helm chart for the Redis queue service.
- **todos-api**: Helm chart for the todos API service written in Node.js.
- **users-api**: Helm chart for the users API service written in Java (Spring Boot).
- **zipkin**: Helm chart for the Zipkin tracing service.

## Usage

To install a chart, use:

```bash
helm install <release-name> <chart-directory>
```

For example:

```bash
helm install auth-api ./auth-api
```

Customize the `values.yaml` files as needed for your environment.