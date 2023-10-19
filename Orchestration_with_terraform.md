### Orchestration with Terraform

- Orchestration with Terraform refers to the process of automating and managing the deployment, configuration, of complex infrastructure and applications using Terraform, an open-source infrastructure as code (IaC) tool. 

### What is Orchestration with Terraform?

- Terraform allows you to define and automate the provisioning of infrastructure components e.g. VMs
- Terraform handles dependencies between infrastructure components, ensuring that resources are provisioned in the correct order to avoid conflicts and errors.
- Terraform maintains a state file that keeps track of the current state of the deployed infrastructure. 

### Where can it be used?
- Cloud Environments
- On-premises data centres
- Multi-cloud deployments
- Development and Testing environments

### Why isit used?
- **Infrastructure as Code**: Terraform enables the principles of IaC, allowing infrastructure to be version-controlled, tested, and treated like software code. This improves collaboration and repeatability.
- **Scalability**: It allows for easy scaling of infrastructure
- **Collaboration**: Terraform configurations can be shared and collaborated on within teams

### When isit used?
- New infrastructure deployment 
- Infrastructure updates
- Disaster recover
- Compliance and Security 

### How isit used?
1. Write Terraform configuration describing the desired infrastructure. 
2. Initialise Terraform `terraform init`
3. `terraform plan` to create an execution plan
4. Apply changes `terraform apply`
