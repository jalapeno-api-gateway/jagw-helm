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
**Uninstall the chart with the following command:**

```bash
$ helm uninstall <release-name> --namespace <namespace>
```

Once deployed, the services can be accessed through the Envoy proxy on these ports:

Service | Port
--- | ---
Request-Service | 30050
Subscription-Service | 30051
