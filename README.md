# Welcome to my Vanilla Minecraft Server

This CDK project contains the necessary resources to host a Minecraft server. Albiet, the EC2 configured here is for a small server, but you can change the instance type to fit your needs.

---

## Getting Started

### Pre-requisites

1. You need the latest version of the `aws` and `cdk` CLI. A simple search will guide you on how to install these libraries.
2. You need an AWS account to deploy to.
3. You need an AWS profile configured via CLI. (ex `aws configure --profile personal`)
4. Create a key-pair to access your EC2 instance via the AWS console.

### Steps

1. Run `npm install`
2. Run `npm build` (to ensure everything is at least compiling correctly)
3. Run `cdk bootstrap --profile personal`
4. Run `cdk deploy --profile personal` (this will create the resources in your account)

---

#### Disclaimer

In extension to the standard MIT license agreement, the creator and/or maintainers of this code package are not responsible for any charges accured by AWS. The user of this code package assumes all responsibility for any charges accrued by AWS.
