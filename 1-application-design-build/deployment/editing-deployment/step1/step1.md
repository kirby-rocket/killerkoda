
- Run the following command to create the Deployment:

`kubectl create deployment ckad --image=nginx --replicas=3 --port=80`

- Edit the deployment and add the label on `spec.template.metadata.labels:`

`kubectl edit deploy ckad`


`team=dev`


