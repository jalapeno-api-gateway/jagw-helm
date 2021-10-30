# Jalapeño API Gateway - Deployment
Helm Chart for the Jalapeño API Gateway

## Usage

**Install the chart with the following command:**

```bash
$ helm install <release-name> jagw --namespace <namespace>
```
**Update the chart with the following command:**
```bash
$ helm upgrade <release-name> jagw --namespace <namespace>
```

Once deployed, the services can be directly accessed through these ports:

Service | Port
--- | ---
Request-Service | 30061
Subscription-Service | 30060

There is also an Envoy proxy deployed. The services can be accessed through the Envoy proxy with the following ports:

Service | Port
--- | ---
Request-Service | 30050
Subscription-Service | 30051