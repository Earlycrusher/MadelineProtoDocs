---
title: "messages.composedMessageWithAI"
description: "messages.composedMessageWithAI attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/constructors/messages_composedMessageWithAI.html
---
# Constructor: messages.composedMessageWithAI  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|result\_text|[TextWithEntities](/API_docs/types/TextWithEntities.html) | Yes|
|diff\_text|[TextWithEntities](/API_docs/types/TextWithEntities.html) | Optional|



### Type: [messages.ComposedMessageWithAI](/API_docs/types/messages.ComposedMessageWithAI.html)


### Example:

```
$messages_composedMessageWithAI = ['_' => 'messages.composedMessageWithAI', 'result_text' => TextWithEntities, 'diff_text' => TextWithEntities];
```  
