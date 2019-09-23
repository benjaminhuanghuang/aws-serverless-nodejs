Install nodejs serverless framework
```
  npm install serverless -g
```
## create serverless project (yml file and handler.js)
```
  serverless create --template aws-nodejs --name cake-ordering-backend
```  
serverless.yml
```
service: cake-ordering-backend
provider:
  name: aws
  runtime: nodejs10.x
  
functions:
  hello:
    handler: handler.hello
```
## Create node.js project
```
  npm init -y
```

## Deploy
```
  serverless deploy
```
or
```
  sls deploy
```
POST - https://vxg27gag98.execute-api.us-east-1.amazonaws.com/dev/order