# kubernetes
And related stuff

# K3s.io
The best way to get a cluster working through portainer.

# CheatSheet
## Most Used

$ kubectl get pods -o wide
$ kubectl get nodes
$ kubectl get svc
$ kubectl get endpoints
$ kubectl logs <POD_NAME>
$ kubectl get events

# Maintenance


$ kubectl scale deployment pihole --replicas=3

$ kubectl set image deployment/pihole pihole=pihole/pihole:latest

## Redirecionar sem Traefik

$ kubectl port-forward svc/pihole-service 8080:80

Pra desativar, utilize o Portainer.
