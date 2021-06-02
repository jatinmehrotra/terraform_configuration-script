# Terraform-configuration-script

This repository contains bash script for configuring terraform and aws provider when using roles and MFA.This script incorporates error handling for null values of role ARN's and incorrect values.

## Prerequisites
install jq package manually or allow script to do it for you


```shell
  sudo apt install jq
```
## Usage
> change the permissions of script
```shell
  chmod 700 terraform_configuration-script
```

> To run the script 
```shell
  source ./terraform_configuration-script
```


> enter the arn manually when prompted by script
```shell
 
 Enter your account role arn: //enter your complete role arn

```

