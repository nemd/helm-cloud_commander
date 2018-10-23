# helm-cloud_commander
Helm chart for [cloud commander](http://cloudcmd.io)

## usage

### default
`helm install ./helm-cloud_commander --name cloud-commander`

### ingress
`helm install ./helm-cloud_commander --name cloud-commander --set ingress.enabled=true --set ingress.host=cmd.example.com`

### from repo (codefresh backed chart museum)
- `helm repo nemd update`
- `helm repo update`
- `helm install nemd/cloud_commander --name cloud-commander`
