What is helm?
 - helm is a package manager like brew, yum and apt in linux
 - helm is a package manager for kubernetes that makes it easy to take application and services thar are highly repeatable or
   get used in a lot of different scenarios, and it makes it easier to deploy 


3 Primary Concepts of helm

1. Helm chats - which is a bundle of yaml files necessary to create a kubernetes applications (deployment, service, pvc, secret and etc.)

2. Config Values - this is dynamic configuration you can provide that will customize the deployment of the helm chart config

3. Helm releases - this is the running instance of a chart combined  with a specific configuration releases are  how helm  manages deployed
applications and it allows you to install, upgrade or rollback deployments