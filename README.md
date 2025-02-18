# kubernetes
And related stuff

# K3s.io
The best way to get a cluster working through portainer.

## CheatSheet

$ kubectl get nodes

$ kubectl get endpoints

$ kubectl get svc

$ kubectl get events

$ kubectl port-forward svc/pihole-service 8080:80

$ kubectl set image deployment/pihole pihole=pihole/pihole:latest

$ kubectl scale deployment pihole --replicas=3
