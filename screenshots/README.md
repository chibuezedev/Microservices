
## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook 
* Travis CI showing a successful build and deploy job

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify proper horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that i have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
