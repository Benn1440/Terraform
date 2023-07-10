# Terraform with AWS

Terraform is an open-source infrastructure-as-code software tool created by HashiCorp.
With Terraform we can automate Infrastructure to provision and manage resources in any cloud or data center. ## https://www.terraform.io/

For this project, an IAM User was created with Administrator access

![IAM](https://github.com/Benn1440/Terraform/assets/67696393/c2d28374-3bef-4b22-8d89-58b7e9e69920)

On Visual Studio code there was the need to install the AWS Toolkits and Terraform extension, and thereafter login with the already generated Access key ID & Secret access key on the Credentials profile command palette.

Which generated various AWS resource Templates in our selected Region.

![Terraform](https://github.com/Benn1440/Terraform/assets/67696393/3f10b409-19b8-4275-9ed5-50b83991f789)

# AWS Providers

A provider is basically used by Terraform to interface with the Application Programming Interface (API) of whatsoever infrastructure you are trying to build which is available to the cloud service provider. ## https://registry.terraform.io/providers/hashicorp/aws/latest/docs

# Terraform init

Running the terraform init within the working directory, terraform checks the provider's file installs required hashicorp files and then creates Two(2) extra files
.terraform.lock.hcl ensures that the selected version is frozen, Which helps to avoid issues in cases of upgrade and a .exe file. 


![Terraform init](https://github.com/Benn1440/Terraform/assets/67696393/5fe3e1db-9830-464d-8485-f7ad5acdb176)

# Terraform plan

After creating a main.tf file, with the specified resources, in this instance a VPC, running terraform plan creates a state file.

![terraform plan](https://github.com/Benn1440/Terraform/assets/67696393/26220752-f64b-458f-9652-e5b889d85548)

# Terraform apply

This creates the specified resource.

![terraform apply](https://github.com/Benn1440/Terraform/assets/67696393/069e8db4-ea44-4a7c-b5a9-bb77492f0491)

VPC Resource created on AWS GUI

![VPCfrmTerraform](https://github.com/Benn1440/Terraform/assets/67696393/59f24c75-4ac8-47c8-b53a-630e5c7038aa)


