# Jalapeño API Gateway - Deployment
Helm Chart for the Jalapeño API Gateway

```bash
$ helm install <release-name> jagw --namespace <namespace>
```

Once deployed, the services can be accessed through these ports:

Service | Port
--- | ---
Request-Service | 30061
Subscription-Service | 30060
