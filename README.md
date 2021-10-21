# Learn Terraform Modules Use and Create

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/.../...)

Learn what Terraform modules are and when to create them.

This repo is a companion repo to the [Use Modules from the Registry learn tutorial](https://learn.hashicorp.com/tutorials/terraform/module-use?in=terraform/modules), containing Terraform configuration files to provision infrastructure using the `vpc` and `ec2-instances` modules. **Do not** clone the example repository. The files are already included here.

Add changes to version control as you go through the steps in the tutorial. This will make it easier to see which configuration settings have changed.

**Warning:** Not sure if all the AWS resources provisioned in this tutorial are covered by the free tier (NAT gateway definitely isn't). There may be some small charges. If you leave resources provisioned and don't `terraform destroy` at the end, there definitely will be charges.
