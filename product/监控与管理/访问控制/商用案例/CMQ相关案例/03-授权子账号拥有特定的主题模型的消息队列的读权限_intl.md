### Authorize a sub-account with the read permission of the message queue with a specific topic model

The enterprise account CompanyExample (ownerUin is 12345678) has a message queue based on the topic model, and a sub-account Developer who wants to access the message queue.

Step 1: Create the following policy using policy syntax
```
{
    "version": "2.0",
    "statement":   
     {
        "action": "cmqqueue:SendMessage",
        "resource":"qcs::cmqqueue:::queueName/uin/12345678/test-caten",
        "effect": "allow"
     } 
}
```

Step 2: Authorize the policy to the sub-account. For more information on authorization, see [Authorization Management](https://cloud.tencent.com/document/product/378/8961).

