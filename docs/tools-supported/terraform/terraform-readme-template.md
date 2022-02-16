# Terraform Modules Readme Template

Below you will find the reference structure for documenting a Terraform Module.

## Table of Contents

- [Terraform Modules Readme Template](#terraform-modules-readme-template)
  - [Table of Contents](#table-of-contents)
  - [Diagram](#diagram)
  - [How to use](#how-to-use)
  - [Information required](#information-required)
  - [Template](#template)

## Diagram

Image a quick look of your module is
[![Architecture]][Architecture]

  [Architecture]: ../../assets/images/architecture.png

## How to use

Example or examples that how to use your module using snipets of code, like this

```terraform
module "ec2_instance" {
  source  = "terraform-aws-modules/ec2-instance/aws"
  version = "~> 3.0"

  name = "single-instance"

  ami                    = "ami-ebd02392"
  instance_type          = "t2.micro"
  key_name               = "user1"
  monitoring             = true
  vpc_security_group_ids = ["sg-12345678"]
  subnet_id              = "subnet-eddcdzz4"

  tags = {
    Terraform   = "true"
    Environment = "dev"
  }
}
```

## Information required

This documentation is generated for *terradocs tool*, lear more about this tool <https://terraform-docs.io/user-guide/introduction/>

----

> ## Requirements

> ## Provider

> ## Modules

> ## Resources

> ## Inputs

> ## Outputs

---

## Template

In this link you will find the template repository for the construction of Terraform Modules: <https://github.globant.com/CloudNativePatrol/glo-iac-terraform-mix-template>
