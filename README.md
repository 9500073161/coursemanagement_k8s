# coursemanagement_k8s

kubectl apply -f below yaml

1.run mysql-pv-pvc.yaml for PV creation .
2.run init-sql-configmap.yaml

3. run db-deployment.yaml
4. run app-deployment.yaml
5. app-clusterip-service.yaml
6. db-clusterip.yaml

kubectl get pods

kubectl get svc

kubectl get pv 
kubectl get pvc


# application accessing through any node port IP with port number

http://35.209.80.164:30080/course
                          /teacher
                          /student
                          /entrollment

 #test your code with postman.                         
