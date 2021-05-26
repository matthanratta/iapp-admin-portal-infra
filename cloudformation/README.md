# Modules

The following modules are to deployed in the following order:

### application-iapp-portal
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-iapp-portal.yaml
> + cloudformation/application-iapp-portal.md

Template: [application-iapp-portal](./application-iapp-portal.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [iapp-portal-template](./iapp-portal-template.md)