# Modules

The following modules are to deployed in the following order:

### application-iapp-admin-portal
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-iapp-admin-portal.yaml
> + cloudformation/application-iapp-admin-portal.md

Template: [application-iapp-admin-portal](./application-iapp-admin-portal.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [iapp-admin-portal-template](./iapp-admin-portal-template.md)