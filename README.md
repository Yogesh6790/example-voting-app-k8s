# example-voting-app-k8s
This is an example voting application which has two screens.
1. To Cast the vote
2. To view the Poll
This application uses 5 PODS where each communicate with each other through k8s services.

Deployment is like superset of Replicaset which is like a superset of PODs.
If we have a deployment-defenition YAML files, no of PODS are created based on the replicas set in the YAML