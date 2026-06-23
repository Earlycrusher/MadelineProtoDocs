---
title: "updateWebBrowserException"
description: "updateWebBrowserException attributes, type and example"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateWebBrowserException  
[Back to constructors index](/API_docs/constructors/index.html)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|delete|[Bool](/API_docs/types/Bool.html) | Optional|
|open\_external\_browser|[Bool](/API_docs/types/Bool.html) | Optional|
|exception|[WebDomainException](/API_docs/types/WebDomainException.html) | Yes|



### Type: [Update](/API_docs/types/Update.html)


### Example:

```
$updateWebBrowserException = ['_' => 'updateWebBrowserException', 'delete' => Bool, 'open_external_browser' => Bool, 'exception' => WebDomainException];
```  
