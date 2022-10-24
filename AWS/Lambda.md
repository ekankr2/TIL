# Lambda
AWS Lambda is a serverless compute service that runs your functions.
The functions are run by triggers you added.

## To make server
> Usually Lambda servers are used with API Gateway triggers.

<img src="https://user-images.githubusercontent.com/83811729/197516546-f6d55d7f-ba63-46b4-b9c2-723ab19fc5ac.png" width="550px">

## Basic Example
we have a default function.
```
import json

def lambda_handler(event, context):
# TODO implement
return {
'statusCode': 200,
'body': json.dumps('Hello!')
}
```

>To run the function, we have to add a new API Gateway trigger.
<img src="https://user-images.githubusercontent.com/83811729/197517985-1ecf8bc4-1e75-40d8-8b71-2963cd87ca0f.png" width="550px">

>The trigger is added to Lambda dashboard.
<img src="https://user-images.githubusercontent.com/83811729/197517765-64dd596a-b2a0-4250-b9d0-d686c1aed336.png" width="550px">

>When you access into the API Gateway url.
<img src="https://user-images.githubusercontent.com/83811729/197518235-38111f49-1d75-4e48-a148-70a3e4c34124.png" width="550px">

    "Hello!"