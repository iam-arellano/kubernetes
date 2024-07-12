Blue-green deployment - is a technique where two identical production environments, known as blue and green, are maintained. When a new version of the application is ready, traffic is switched from the blue environment to the green environment without downtime, allowing for seamless updates.

Once the new feature has been thoroughly tested and is ready for full release, the company performs a blue-green deployment. The new feature is deployed to the green environment while the blue environment continues to serve the existing version. Once the green environment is confirmed to be working properly, traffic is switched from blue to green, completing the deployment without any downtime.


Canary deployment-  is a method in software development where a new version of an application is gradually rolled out to a small subset of users before being released to the entire user base. This allows developers to detect and fix any issues before impacting a larger audience.

A company is releasing a new feature on their website. They decide to use canary deployment by gradually rolling out the feature to 10% of users. After monitoring for any issues or bugs, they gradually increase the rollout to 25%, 50%, and finally 100% of users.