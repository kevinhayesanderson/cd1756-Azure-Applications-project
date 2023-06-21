# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app

I have chosen App Service for this app deployment for the following reasons,
1.VMs can be more expensive as they require more infrastructure and maintenance costs.
App Service is more cost-effective as it provides a managed platform with no additional infrastructure or maintenance costs.
2.VMs can be scaled vertically or horizontally, but require manual setup and configuration.
App Service provides automatic horizontal scaling and easy configuration for vertical scaling.
3.App Service provides high availability with automatic fail-over and build-in redundancy.
4.App Service provides a streamlined deployment process with easy integration with source control and continuous deployment tools.

### Assess app changes that would change your decision

If we require to open this to multiple groups of users at a wider scale , also add more functionalities that would require maybe role level permissions , then a VM would be more applicable as it would give us the flexibility to customize and the cost would be justified.
If the application requires very large scaling and customization i would choose VM.
If there is a requirement for high uptime, backup  and recovery process, VM is s better choice.
