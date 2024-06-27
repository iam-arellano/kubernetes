RBAC (Role-Based Access Control) in Kubernetes is a way to control who has access to what resources within a Kubernetes cluster based on their roles.
role based access control - its basically used to create specific role with a  k8s cluster  to allow different application and different users with different access rights.

In RBAC, you create roles that define what actions a user or group of users can perform on specific resources in the cluster. Users are then assigned roles and these roles determine the permissions they have.

Scenario example:
Let's say you have a Kubernetes cluster with different namespaces for your development, testing, and production environments. You want to restrict access to certain resources based on the user's role.

1. Create a role called "developer" with permissions to create and delete pods in the development namespace.
2. Assign the "developer" role to users who are responsible for development.
3. Create a role called "tester" with permissions to view pods in the testing namespace.
4. Assign the "tester" role to users who are responsible for testing.
5. Create a role called "admin" with permissions to manage all resources in all namespaces.
6. Assign the "admin" role to users who have overall control over the cluster.

By setting up RBAC in this way, you can control access to resources within your Kubernetes cluster based on the roles assigned to users.


sample image
![sample_image](<rbac sample.png>)
