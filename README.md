Cloud DevOps Engineer Capstone Project
This project represents the successful completion of the last final Capstone project and the Cloud DevOps Engineer Nanodegree at Udacity.

What did I learn?
In this project, I applied the skills and knowledge I developed throughout the Cloud DevOps Nanodegree program. These include:
-	Using Circle CI to implement Continuous Integration and Continuous Deployment
- Building pipelines
- Building Kubernetes clusters
- Building Docker containers in pipelines
- Working in AWS


==>

kubectl get pods

NAME                                READY   STATUS    RESTARTS   AGE
capstoneproject5-77dcf84ff5-nq6d2   1/1     Running   0          3h53m
capstoneproject5-77dcf84ff5-rzt42   1/1     Running   0          3h53m

kubectl get svc,pods,deployments

NAME                       TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)    AGE
service/capstoneproject5   ClusterIP   10.100.172.89   <none>        8080/TCP   3h53m
service/kubernetes         ClusterIP   10.100.0.1      <none>        443/TCP    6h45m

  
NAME                                    READY   STATUS    RESTARTS   AGE
pod/capstoneproject5-77dcf84ff5-nq6d2   1/1     Running   0          3h53m
pod/capstoneproject5-77dcf84ff5-rzt42   1/1     Running   0          3h53m

  
NAME                               READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/capstoneproject5   2/2     2            2           3h53m

kubectl get pods -o wide
  
NAME                                READY   STATUS    RESTARTS   AGE     IP              NODE                            NOMINATED NODE   READINESS GATES
capstoneproject5-77dcf84ff5-nq6d2   1/1     Running   0          3h54m   172.31.10.206   ip-172-31-15-142.ec2.internal   <none>           <none>
capstoneproject5-77dcf84ff5-rzt42   1/1     Running   0          3h54m   172.31.2.218    ip-172-31-15-142.ec2.internal   <none>           <none>


