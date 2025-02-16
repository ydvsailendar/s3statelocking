# README

```bash
# create s3 bucket
aws s3api create-bucket --bucket s3statelocking01 --profile sandbox --region eu-west-2 --create-bucket-configuration LocationConstraint=eu-west-2
```

```bash
# enable versioning in the created bucket
aws s3api put-bucket-versioning --bucket s3statelocking01 --versioning-configuration Status=Enabled --profile sandbox --region eu-west-2
```
