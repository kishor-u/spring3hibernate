### Spring3Hibernate - IaC

This folder contains the nested cloudformation templates for the creation of CI/CD deployment pipeline for the java [application](https://github.com/opstree/spring3hibernate).

#### Steps :

* Clone the repo and paste the contents of /spring3-infra folder to a S3 Bucket.

* Create the stack using AWS Cloudformation using the index file : main.yaml

* Give a sample stack name and a service name for the stack. Remeber every resources made using this stack will have a tag name which we are giving as the ServiceName.

* Provide other asked parameters required for the project.

* Please make sure every resources has been created once every stacks shows the CREATE-COMPLETE status.

* Approve the Manual Approval stage of the Code Pipeline.

* Hit the DNSName output of Loadbalancer stack and verify the application is now live.
