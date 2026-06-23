---
title: "pageListItemBlocks"
description: "List item"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: pageListItemBlocks  
[Back to constructors index](/API_docs/constructors/index.html)



List item

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|checkbox|[Bool](/API_docs/types/Bool.html) | Optional|
|checked|[Bool](/API_docs/types/Bool.html) | Optional|
|blocks|Array of [PageBlock](/API_docs/types/PageBlock.html) | Yes|Blocks|



### Type: [PageListItem](/API_docs/types/PageListItem.html)


### Example:

```
$pageListItemBlocks = ['_' => 'pageListItemBlocks', 'checkbox' => Bool, 'checked' => Bool, 'blocks' => [PageBlock, PageBlock]];
```  
