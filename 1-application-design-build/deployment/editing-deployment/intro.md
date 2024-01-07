## Deployment

- Create a Deployment named ckad in default ns running nginx image on 3 replicas exposing containerport 80.
- Label the pod with tead=dev
- Expose the deployment using a NodePort Service named world serving on port 80 and connecting to the containers on port 8080.

