# KubernetesMicroservicesProject

# KubernetesMicroservicesProject

#Create the folder for volumes 
mkdir -p /var/lib/votevibe/redis

kubectl apply -f 01-namespaces.yaml

kubectl apply -f 02-redis-storage.yaml

kubectl apply -f 03-redis.yaml

kubectl apply -f 04-blue.yaml

kubectl apply -f 05-red.yaml

kubectl apply -f 06-result.yaml

kubectl apply -f 07-network-policies.yaml

kubectl apply -f 08-rbac.yaml
