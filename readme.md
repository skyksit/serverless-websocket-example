# What's this for?
this is for all the developers who building microservice (usually http) based on
AWS Gateway / AWS Lambda, Plus sweet typescript / serverless framework

# How to start?
There are few things you need to customize to starts.

1) serverless.yml
  - name service

    ```service: lambda-microservice-template # NOTE: update this with your service name```


# How to invoke function on lambda

serverless invoke -f #{functionName}

# How to invoke function locally

npm run invoke -- --function="hello"