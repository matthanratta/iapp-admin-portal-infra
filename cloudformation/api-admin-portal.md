# api-admin-portal.yaml

## Resource Types
+ [AWS::ApiGateway::Deployment](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigateway-deployment.html)
+ [Custom::String](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-cfn-customresource.html)
+ [AWS::DynamoDB::Table](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-dynamodb-table.html)
+ [AWS::IAM::InstanceProfile](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iam-instanceprofile.html)
+ [AWS::IAM::Policy](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iam-policy.html)
+ [AWS::IAM::Role](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iam-role.html)
+ [AWS::Logs::LogGroup](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-logs-loggroup.html)
+ [AWS::Serverless::Api](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-resource-api.html)
+ [AWS::Serverless::Function](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-resource-function.html)
+ [AWS::WAFv2::WebACLAssociation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-wafv2-webaclassociation.html)

## Template Parameters
| Parameter                 | Type    | Description                                                                                                 |
| ------------------------- | ------- | ----------------------------------------------------------------------------------------------------------- |
| pOrganization             | String  | The name of the portfolio that identifies its products, applications, and components                        | 
| pPortfolio                | String  | The name of the portfolio that identifies its products, applications, and components                        |
| pProduct                  | String  | The name of the product that identifies its applications and components                                     |
| pApplication              | String  | The name of the application (or service module) that identifies its components                              |
| pComponent                | String  | The name of the component that aligns with the application or service module                                |
| pDepartment               | String  | The name of the department that owns the resource                                                           |
| pEnvironment              | String  | The name of the environment in which the resource is running (e.g.: sandbox, development, test, production) |
| pSupportEmail             | String  | The email address of the support team to contact                                                            |
| pReleaseTag               | String  | The name of the release to pull the code from                                                               |
| pArtifactName             | String  | The name of the artifacvt repository (S3 Bucket) where the artifact is stored.                              |
| pArtifactName             | String  | The name of the artifact that is the source code for the functions, (e.g.: iapp-live-conference.zip)        |
| pDomainName               | String  | The domain name to use for the API service. This is optional adn can be left empty.                         |
| pCertificateArn           | String  | The AWS arn for the certificate used by the API                                                             |
| pSourceCodeURL            | String  | The location (url) where to find the source code                                                            |
| pStageName                | String  | The name od the API gateway stage where the deployments posted, (default = latest)                          |
| pUserPoolArn              | String  | The AWS arn of the Cognito User Pool to use for authorization to the API                                    |
| pAllowHeaders             | String  | The value for the Access-Control-Allow-Headers response header                                              |
| pAllowOrigin              | String  | The value for the Access-Control-Allow-Origin response header, (default = https://iapp.org)                 |
| pExternalEndpoint         | String  | Indicates if the API Gateway endpoints is external facing, (true or false)                                  |

## Exports
| Name                                                     | Description                                     |
| -------------------------------------------------------- | ----------------------------------------------- |

## Further Reading
+ https://iappadmin.atlassian.net/wiki/spaces/FIP/pages/1352204585/Auth+Auth+NonHuman+System+Components
+ https://github.com/PrivacyAssociation/system-scaffolding/tree/master/src/auth_api
+ https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification-generated-resources-api.html
+ https://aws.amazon.com/blogs/aws/api-gateway-update-new-features-simplify-api-development/
+ https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-property-function-api.html#sam-function-api-requestparameters
+ https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-property-function-requestparameter.html
+ https://stackoverflow.com/questions/35773025/is-it-possible-to-use-wildcards-or-catch-all-paths-in-aws-api-gateway