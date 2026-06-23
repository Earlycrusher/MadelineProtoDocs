---
title: "inputRichMessage"
description: "inputRichMessage attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputRichMessage  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|rtl|[Bool](/API_docs/types/Bool.html) | Optional|
|noautolink|[Bool](/API_docs/types/Bool.html) | Optional|
|blocks|Array of [PageBlock](/API_docs/types/PageBlock.html) | Yes|
|photos|Array of [MessageMedia, Message, Update or InputPhoto](/API_docs/types/InputPhoto.html) | Optional|
|documents|Array of [MessageMedia, Message, Update or InputDocument](/API_docs/types/InputDocument.html) | Optional|
|users|Array of [Username, chat ID, Update, Message or InputUser](/API_docs/types/InputUser.html) | Optional|



### Type: [InputRichMessage](/API_docs/types/InputRichMessage.html)


### Example:

```
$inputRichMessage = ['_' => 'inputRichMessage', 'rtl' => Bool, 'noautolink' => Bool, 'blocks' => [PageBlock, PageBlock], 'photos' => [InputPhoto, InputPhoto], 'documents' => [InputDocument, InputDocument], 'users' => [InputUser, InputUser]];
```  
