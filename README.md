# cfn-stacks

## setup

* AWS creds / profile / etc
* `npm i`

## usage

* `npx cfn-deploy --stackname mysite-s3-and-cf-stack --template stacks/s3-and-cf.cfn.yaml --region ap-southeast-2`
* `aws cloudformation update-stack --stack-name mysite-s3-and-cf-stack --template-body file://stacks/s3-and-cf.cfn.yaml`