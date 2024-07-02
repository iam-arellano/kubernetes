What is nodeport?

NodePort service in Kubernetes is a service that is used to expose the application to the internet from where the end-users can access it. If you create a NodePort Service Kubernetes will assign the port within the range of (30000-32767).
 The application can be accessed by end-users using the node's IP address