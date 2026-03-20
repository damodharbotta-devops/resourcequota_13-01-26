# resourcequota_13-01-26

## Commands:

kubectl create ns dev
kubectl describe ns dev
kubectl create -f resource-quota.yml
kubectl create -f pod.yml
kubectl describe pod mypod -n dev
