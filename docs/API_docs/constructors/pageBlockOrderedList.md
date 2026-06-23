---
title: "pageBlockOrderedList"
description: "Ordered list of IV blocks"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: pageBlockOrderedList  
[Back to constructors index](/API_docs/constructors/index.html)



Ordered list of IV blocks

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|reversed|[Bool](/API_docs/types/Bool.html) | Optional|
|items|Array of [PageListOrderedItem](/API_docs/types/PageListOrderedItem.html) | Yes|List items|
|start|[int](/API_docs/types/int.html) | Optional|
|type|[string](/API_docs/types/string.html) | Optional|



### Type: [PageBlock](/API_docs/types/PageBlock.html)


### Example:

```
$pageBlockOrderedList = ['_' => 'pageBlockOrderedList', 'reversed' => Bool, 'items' => [PageListOrderedItem, PageListOrderedItem], 'start' => int, 'type' => 'string'];
```  
