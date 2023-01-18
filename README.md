<p align="center">
	<img src="https://github.com/jalapeno-api-gateway/.github/raw/main/img/logo.png">
</p>
<h1 align="center">Jalapeno Gateway Helm Chart</h1>
<p align="center">
	<img src="https://img.shields.io/github/v/tag/jalapeno-api-gateway/jagw.svg?label=release&logo=github&style=flat-square">
</p>

<p align="center">
This repository contains the helm chart to deploy the JAGW on a Kubernetes cluster.
The official documentation can be found <a href="https://jalapeno-api-gateway.github.io/jagw">here</a>.
</p>

---

## Installation
Please follow the [installation guide](https://jalapeno-api-gateway.github.io/jagw/docs/installation/) in the official Documentation.

Once deployed, the services can be accessed through the Envoy proxy on these ports (when using a LoadBalancer):

Service | Port
--- | ---
Request-Service | 9903
Subscription-Service | 9902
