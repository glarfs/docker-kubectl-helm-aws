# kubectl-helm-aws

[![Docker Repository on Quay](https://quay.io/repository/helmpack/kubectl-helm-aws/status "Docker Repository on Quay")](https://quay.io/repository/helmpack/kubectl-helm-aws)


AWS CLI Dockerfile with kubectl and Helm

## Variables
* AWS_ACCESS_KEY_ID: AWS access key associated with an IAM user or role. 	AKIAIOSFODNN7EXAMPLE
* AWS_SECRET_ACCESS_KEY: Secret key associated with the access key. (ex.	wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY)
* AWS_DEFAULT_REGION: AWS Region to send the request to.(ex. ap-southeast-2)

## Run
```
docker run -e AWS_ACCESS_KEY_ID=AKIA.. -e AWS_SECRET_ACCESS_KEY=wJal.. -e AWS_DEFAULT_REGION=ap-southeast-2 glarfs/kubectl-helm-aws
```
