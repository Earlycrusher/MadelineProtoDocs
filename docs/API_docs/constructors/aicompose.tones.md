---
title: "aicompose.tones"
description: "aicompose.tones attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/constructors/aicompose_tones.html
---
# Constructor: aicompose.tones  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|hash|[long](/API_docs/types/long.html) | Yes|
|tones|Array of [AiComposeTone](/API_docs/types/AiComposeTone.html) | Yes|
|users|Array of [User](/API_docs/types/User.html) | Yes|



### Type: [aicompose.Tones](/API_docs/types/aicompose.Tones.html)


### Example:

```
$aicompose_tones = ['_' => 'aicompose.tones', 'hash' => long, 'tones' => [AiComposeTone, AiComposeTone], 'users' => [User, User]];
```  
