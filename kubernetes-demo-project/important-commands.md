# Some important commands to execute the project 
### PowerShell - bash/sh
convert words into base64 so as to be accepted in mongdb credentials
```
[System.Convert]::ToBase64String([System.Text.Encoding]::UTF8.GetBytes('Word')) 
echo -n 'Word' | base64
```
### kubectl commands
```
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl get secret
kubectl get all
kubectl get pod 
kubectl get pod --watch // get pod status
kubectl decribe pod <"pod name"> // get pod info
```



