
# terraformGCPi

Allow the SDK to communicate with GCP:
```sh
$ gcloud auth login
```
Create the service account key:


```sh
$  gcloud iam service-accounts keys create /downloads/terraform.json --iam-account <SERVICE_ACCOUNT_EMAIL>
 
```

Replace the <PROJECT_NAME> with your project name within the main.tf file.




Initialize the configuration file:  

```sh
terraform init
```

Validate the configuration file

```sh
terraform validate
```

Create the execution plan

```sh
terraform plan
```

Apply the changes

```sh
terraform apply
```


