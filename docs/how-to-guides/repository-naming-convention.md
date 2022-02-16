# Repository Naming Convention

To contribute a new code resource, such as a Terraform module, it is necessary to host it in its independent repository.

Below you will find the naming convention to use when creating new repositories for the central registry initiative.

### Expected structure

*glo-[main area]-[tool]-[provider]-[target]*

Main Area | Tool | Provider | Target - examples
---|---|---|---
iac: Infrastructure as code| - terraform<br> - pulumi| - aws<br> - gcp<br> - azr<br> - oci<br> - mix: Mixed| - vpc<br> - vnet<br> - lambda<br> - storage
cac: Configuration as code | - ansible<br> - chef<br> - puppet| - onp: On premise<br> - ghb: GitHub<br> - dtd: Datadog| - ecs<br> - docker<br> - Wordpress
scr: Scripting | - lnx: Linux<br> - win: Windows<br> - mac| - bash<br> - python<br> - powershell| - upgrade<br> - check<br> - install<br>

### Examples

```
git@github.globant.com:CloudNativePatrol/glo-iac-terraform-mix-template.git

glo - iac - terraform - mix - template
```

Main Area | Tool | Provider | Target
---|---|---|---
iac| terraform| mix | Template
Infrastructure as code| terraform| Mixed | Template
