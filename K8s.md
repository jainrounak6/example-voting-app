# Kubernetes (K8s) Commands CheatSheet

### Check Pods of specific Name Space

`kubectl get pods -n <namespace-name>`

### To describe pod
`kubectl describe pod <pod-name> -n <namespace-name>`

### To check logs of pod (Follow-up logs)
`kubectl logs -f <pod-name> -c <container-name>  -n <namespace-name>`

### Configure Monitoring of Node and Pods using TOP command
`kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml`

### Check CPU and Memory status of Node

`kubectl top node`

### Check CPU and Memory status of pods of specific Name Space
`kubectl top pod -n <namespace-name>`

### To Get Node Public IP (External IP)
`kubectl get nodes -o wide`


## Clean Up Process
### To delete namespace
`kubectl delete namespace <namespace-name>`

### To delete deployment of specific Name Space
`kubectl delete deployment <deployment-name> -n vote-app`
### To delete service of specific Name Space
`kubectl delete service <service-name> -n vote-app`



# _Contact & Support_
##### _Developer : [Rounak Jain](mailto:jainrounak1997@outlook.com)_