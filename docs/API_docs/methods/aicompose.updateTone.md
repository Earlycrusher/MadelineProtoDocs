---
title: "aicompose.updateTone"
description: "aicompose.updateTone parameters, return type and example"
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/aicompose_updateTone.html
---
# Method: aicompose.updateTone
[Back to methods index](index.html)



### Parameters:

| Name     |    Type       | Required |
|----------|---------------|----------|
|tone|[InputAiComposeTone](/API_docs/types/InputAiComposeTone.html) | Yes|
|display\_author|[Bool](/API_docs/types/Bool.html) | Optional|
|emoji\_id|[long](/API_docs/types/long.html) | Optional|
|title|[string](/API_docs/types/string.html) | Optional|
|prompt|[string](/API_docs/types/string.html) | Optional|


### Return type: [AiComposeTone](/API_docs/types/AiComposeTone.html)

### Can users use this method: **YES**


### Can bots use this method: **YES**


### Can bots use this method over a business connection with the `businessConnectionId` flag: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$AiComposeTone = $MadelineProto->aicompose->updateTone(tone: $InputAiComposeTone, display_author: $Bool, emoji_id: $long, title: 'string', prompt: 'string', );
```

