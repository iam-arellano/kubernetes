What is ingress?

- Ingress is a feature in Kubernetes that allows you to route external traffic to your services within the cluster. 	

What is ingress controller?

- An Ingress controller is a specific type of controller that manages the traffic routing for Ingress resources.


In simple terms, Ingress is like a set of traffic rules for directing incoming traffic to the right services, and the Ingress controller is the tool that enforces those rules.


 A sample scenario could be a web application running on a Kubernetes cluster that needs to be accessed by external users. In this case, you would create an Ingress resource to define how traffic
 should be directed to the application, and then use an Ingress controller (like NGINX or Traefik) to actually manage the routing of the traffic. This ensures that users can access the application securely and efficiently.

