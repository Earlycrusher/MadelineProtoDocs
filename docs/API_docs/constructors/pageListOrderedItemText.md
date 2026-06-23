---
title: "pageListOrderedItemText"
description: "Ordered list of text items"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: pageListOrderedItemText  
[Back to constructors index](/API_docs/constructors/index.html)



Ordered list of text items

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|checkbox|[Bool](/API_docs/types/Bool.html) | Optional|
|checked|[Bool](/API_docs/types/Bool.html) | Optional|
|num|[string](/API_docs/types/string.html) | Optional|Number of element within ordered list|
|text|[RichText](/API_docs/types/RichText.html) | Yes|Text|
|value|[int](/API_docs/types/int.html) | Optional|
|type|[string](/API_docs/types/string.html) | Optional|



### Type: [PageListOrderedItem](/API_docs/types/PageListOrderedItem.html)


### Example:

```
$pageListOrderedItemText = ['_' => 'pageListOrderedItemText', 'checkbox' => Bool, 'checked' => Bool, 'num' => 'string', 'text' => RichText, 'value' => int, 'type' => 'string'];
```  
