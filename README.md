# Kubernates-Yaml-Templates
Raw yaml configuration files for K8s


######################################
####### KUBECTL STEP BY STEP #########
######################################

1. kubectl apply -f mongoDB-secret.yaml
2. kubectl apply -f mongoDB-depl.yaml
3. kubectl apply -f mongoDB-depl.yaml
------------- two steps --------------
4. kubectl apply -f mongo-configmap.yaml
5. kubectl apply -f mongoExpress-depl.yaml
------------------------------------------
6. kubectl apply -f mongoExpress-depl.yaml
