---
title: " secureScoreControlStateUpdate resource type"
description: "This resource contains history of control states updated by user (control states include Default, Ignored, ThirdParty, Reviewed)."
---

#  secureScoreControlStateUpdate resource type

This resource contains history of control states updated by user (control states include Default, Ignored, ThirdParty, Reviewed).

|Property |Type |Description |
|:--|:--|:--|
|assignedTo | string | assign the control to the user who will take the action |
|comment | string | Provides optional comment about the control |
|state | string | State of the control can be modified using PATCH command(Ex: ignored, thirdParty etc) |
|updatedBy | string |ID of the user who updated tenant state, etc |
|updatedDateTime | DateTimeOffset? |Time at which control state got updated |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.secureScoreControlStateUpdate"
}-->

```json
{
  "assignedTo": "String",
  "comment": "Double",
  "state": "Double",
  "updatedBy": "Double",
  "updatedDateTime": "Double"
}

```


<!-- {
  "type": "#page.annotation",
  "description": "secureScoreControlStateUpdate resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
