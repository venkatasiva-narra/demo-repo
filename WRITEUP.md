# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*I would choose an App Service

# Azure Pricing
- Azure Pricing for App Service is generally less than the Pricing for VM's.
- App Services cost less than VMs do

# Scalability
- Scale limit is generally less for the App Services compared to VM's.
- VM's can support more number of users compared to App services.
- Since scalability is less of a concern we can go with App services

# Availability
- Apps running in a customer subscription will be available 99.95% of the time.
- you will have Virtual Machine Connectivity to at least one instance at least 99.99% of the time.

# Other 
- Since it is light weight, the size limit for App Services will not be a problem.
- Security is best in VM's compared to App services but can be acheived in App service too.



### Assess app changes that would change your decision.

- If there is a vast increase in the number of users
- If there is a need for dedicated servers for handling sensitive information.
- It may be necessary in the future if many more features are added then scaling is required.
