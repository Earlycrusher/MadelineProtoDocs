---
title: "botInlineMessageRichMessage"
description: "botInlineMessageRichMessage attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: botInlineMessageRichMessage  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|reply\_markup|[ReplyMarkup](/API_docs/types/ReplyMarkup.html) | Optional|
|rich\_message|[RichMessage](/API_docs/types/RichMessage.html) | Yes|



### Type: [BotInlineMessage](/API_docs/types/BotInlineMessage.html)



## Usage of reply_markup

You can provide bot API reply_markup objects here.  


### Example:

```
$botInlineMessageRichMessage = ['_' => 'botInlineMessageRichMessage', 'reply_markup' => ReplyMarkup, 'rich_message' => RichMessage];
```  
