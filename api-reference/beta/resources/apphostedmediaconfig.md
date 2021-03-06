---
title: "appHostedMediaConfig resource type"
description: "Media stack hosted by the application."
---

# appHostedMediaConfig resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

Media stack hosted by the application.

## Properties

| Property                          | Type    | Description                                                     |
| :-------------------------------- | :------ | :---------------------------------------------------------------|
| blob                              | String  | The media configuration blob generated by smart media agent.    |
| removeFromDefaultAudioGroup       | Boolean | Remove audio from the default audio group                       |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.appHostedMediaConfig"
}-->
```json
{
  "blob": "String",
  "removeFromDefaultAudioGroup": true
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "appHostedMediaConfig resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
