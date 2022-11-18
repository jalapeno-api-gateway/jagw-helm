# jagw - Jalapeño API Gateway Deployment
This repository contains the helm chart to deploy the JAGW on a Kubernetes cluster.
The official documentation can be found [here](https://jalapeno-api-gateway.github.io/jagw-docs/).

## Requirements
In order to use the Helm chart as is, a Kubernetes load balancer is needed.

## Installation
Please follow the [installation guide](https://jalapeno-api-gateway.github.io/jagw-docs/docs/installation/) in the official Documentation.

Once deployed, the services can be accessed through the Envoy proxy on these ports:

Service | Port
--- | ---
Request-Service | 9903
Subscription-Service | 9902
