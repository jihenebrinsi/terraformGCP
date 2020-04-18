
# terraformGCPi

Allow the SDK to communicate with GCP:

gcloud auth login

Create the service account key:

gcloud iam service-accounts keys create /downloads/terraform.json --iam-account <SERVICE_ACCOUNT_EMAIL>

Replace the <PROJECT_NAME> with your project name within the main.tf file.




Initialize the configuration file:  
terraform init

Validate the configuration file
terraform validate

Create the execution plan

terraform plan

Apply the changes
terraform apply



