## Setup
Install nodejs serverless framework
```
  npm install serverless
```
Create IAM account and setup cerdential
```
  sserverless config creendtials \
  --provider aws \
  --key          \
  --secret       \
```
or using aws cli
```
  pip install --upgrade awscli
  aws configure
  ls ~/.aws
```