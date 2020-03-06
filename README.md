# lambda_invoking_lambda Asynchronously

# Reverse_Proxy 

There is a scenario which invokes the another lambda from current lambda function by attaching with API Gateway

key terms :

Boto3 --> python SDK 
lambda --> Serverless compute service that runs your code in response to events automatically manage the underlying resources also which runs on containers


# User ---> API Gateway ---> Lambda1 ---> Lambda2

AWS Lambda functions execute in a container (sandbox) that isolates them from other functions and provides the resources, such as memory, specified in the function's configuration

