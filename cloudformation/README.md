# Modules

The following modules are to deployed in the following order:

### application-utility-portal
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-utility-portal.yaml
> + cloudformation/application-utility-portal.md

Template: [application-utility-portal](./application-utility-portal.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [utility-portal-template](./utility-portal-template.md)