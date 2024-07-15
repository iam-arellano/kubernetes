What is Autoscalling? 
  - autoscaling is a feature that allows a cluster to automatically increase or decrease the number of nodes, or adjust pod resources, in response to demand


Horizontal Pod Autoscaler (HPA)
 - increase the number of replicas whenever there is a spike in CPU, MEMORY or some other metric that
   way the load is distributed among the pods

Vertical Pod Autoscaler (VPA)
- adjusts or increase the resource of existing pods  instead of creating new pods
- automatically adjusts the CPU and memory reservations for your Pods to help "right size" your applications. 

 Cluster Autoscaler (CA)    
-  automatically adds or removes nodes in a cluster based on resource requests from pods.
   The Cluster Autoscaler doesn't directly measure CPU and memory usage values to make a scaling decision.

  ![autoscaler](https://github.com/iam-arellano/kubernetes/assets/157453032/b95f4618-997c-4657-a008-565113133500)
