## K8s Learning

- This repository holds the K8s YAMLs to create the required resources.
- Each directory is named on the basis of the k8s resource/workload YAML it holds.

#### Command to create a resource:

`kubectl apply -f [YAML file name]`

- Sample Command to create a deployment,

 `kubectl apply -f deployment-python-web-app/application_deployment.yml`

#### Command to delete a resource:

`kubectl delete -f [YAML file name]`

- Sample Command to delete a deployment,

 `kubectl delete -f deployment-python-web-app/application_deployment.yml`
