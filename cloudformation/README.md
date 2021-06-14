# Modules

The following modules are to deployed in the following order:

### application-iapp-portal2
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-iapp-portal2.yaml
> + cloudformation/application-iapp-portal2.md

Template: [application-iapp-portal2](./application-iapp-portal2.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [iapp-portal2-template](./iapp-portal2-template.md)