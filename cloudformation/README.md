# Modules

The following modules are to deployed in the following order:

### application-iapp-admportal
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-iapp-admportal.yaml
> + cloudformation/application-iapp-admportal.md

Template: [application-iapp-admportal](./application-iapp-admportal.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [iapp-admportal-template](./iapp-admportal-template.md)