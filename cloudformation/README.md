# Modules

The following modules are to deployed in the following order:

### application-admin-portal
Performs the default steps to setup the application, (registration, secret, etc).
> NOTE: Make sure to rename the CFT based on your applicaiton name.
> + .iapp/manifest.yaml
> + cloudformation/application-admin-portal.yaml
> + cloudformation/application-admin-portal.md

Template: [application-admin-portal](./application-admin-portal.md)

### Example Calling Custom Resources
Provides an example Stack that call custom resources to reference networking resources, (e.g.: VPN, Subnet, Security Group).

Template: [admin-portal-template](./admin-portal-template.md)