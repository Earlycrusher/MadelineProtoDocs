---
title: "updateJoinChatWebViewDecision"
description: "updateJoinChatWebViewDecision attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateJoinChatWebViewDecision  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|peer|[long](/API_docs/types/long.html) | Yes|
|query\_id|[long](/API_docs/types/long.html) | Yes|
|result|[JoinChatBotResult](/API_docs/types/JoinChatBotResult.html) | Yes|



### Type: [Update](/API_docs/types/Update.html)


### Example:

```
$updateJoinChatWebViewDecision = ['_' => 'updateJoinChatWebViewDecision', 'peer' => long, 'query_id' => long, 'result' => JoinChatBotResult];
```  
