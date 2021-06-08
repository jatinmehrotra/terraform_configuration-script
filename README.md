# Terraform-configuration-script

This repository contains bash script for configuring terraform with AWS provider when using **Roles** and **MFA**. This script incorporates error handling for **null value of role ARN's and incorrect values.**
- Note  :- **The variables for this script are valid for current bash session. Need to rerun script if terminal is closed or new bash session is started.**

## Prerequisites
install jq package manually or allow script to do it for you

> install jq package for parsing json
```shell
sudo apt install jq
```
## Usage
> change the permissions of script
```shell
chmod 700 terraform_config_script
```

> To run the script 
```shell
source ./terraform_config_script
```


> enter the profile name after running the script
```shell
 
Enter your profile name to find associated ARN: //enter your profile which is prompted by script
```

