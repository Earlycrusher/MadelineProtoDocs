---
title: "bots.accessSettings"
description: "bots.accessSettings attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/constructors/bots_accessSettings.html
---
# Constructor: bots.accessSettings  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|restricted|[Bool](/API_docs/types/Bool.html) | Optional|
|add\_users|Array of [User](/API_docs/types/User.html) | Optional|



### Type: [bots.AccessSettings](/API_docs/types/bots.AccessSettings.html)


### Example:

```
$bots_accessSettings = ['_' => 'bots.accessSettings', 'restricted' => Bool, 'add_users' => [User, User]];
```  
