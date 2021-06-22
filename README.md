To update the image of existing kKubernetes Cluster: kubectl set image deployment/client-deployment client=stephengrider/multi-client:v5
To list pods: kubectl get pods

# Run before applying server configuration
To create a secret: kubectl create secret generic  pgpassword --from-literal PGPASSWORD=12345asdf