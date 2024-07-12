Blue-green deployment - is a technique where two identical production environments, known as blue and green, are maintained. When a new version of the application is ready, traffic is switched from the blue environment to the green environment without downtime, allowing for seamless updates.

Once the new feature has been thoroughly tested and is ready for full release, the company performs a blue-green deployment. The new feature is deployed to the green environment while the blue environment continues to serve the existing version. Once the green environment is confirmed to be working properly, traffic is switched from blue to green, completing the deployment without any downtime.

Advantage

- Reduced downtime: Blue-green deployments allow for seamless updates with minimal disruption to users
- Easy rollback: If any issues arise during the deployment, rolling back to the previous version can be done quickly and easily.
- Disaster recovery: In the event of a failure, the inactive environment can be quickly activated to restore service without downtime

Disadvantage
- infrastracture cose very high because you use 2 website with different region


![bluegreen](https://github.com/user-attachments/assets/bedd2d8f-3847-4263-bd14-feaaf4f2379f)




Canary deployment-  is a method in software development where a new version of an application is gradually rolled out to a small subset of users before being released to the entire user base. This allows developers to detect and fix any issues before impacting a larger audience.

A company is releasing a new feature on their website. They decide to use canary deployment by gradually rolling out the feature to 10% of users. After monitoring for any issues or bugs, they gradually increase the rollout to 25%, 50%, and finally 100% of users.

Advantage

- Allows for early detection of issues: By rolling out updates to a small subset of users, any potential issues or bugs can be identified and resolved before a full deployment.
- Minimizes risk: Canary deployments help reduce the risk of deploying updates by limiting the impact to a small subset of users.
- Improved user experience: Canary deployments ensure that users are not negatively impacted by any potential issues or bugs in the new release

Disadvantage

- Limited feedback: Since only a small subset of users receive the update initially, the feedback may not be representative of the entire user base.
- Managing multiple versions of the software can be more complex and may require additional resources.
- Potential for version discrepancies: With multiple versions running simultaneously, there may be inconsistencies in data or functionality between different users.

![canary](https://github.com/user-attachments/assets/44953900-77cb-4d77-aa9c-17816abd7a31)
