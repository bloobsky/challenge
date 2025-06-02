# Exante challenge

Mini challenge for Aidan

## Overview

VPC -- both public & pprivate with two avail. zones

ECS Fargate -- service that run container with nginx

ALB -- HTTPS Listener active with ACM certificate

IAM Role -- minimun for ECS Task execution


## How to deploy ?

Make sure you have Terraform installed and aws cli configured, also needs to be predefined cert in eu-west-1 regions

```bash
terraform init
terraform apply 
```
and pass certificate as string

