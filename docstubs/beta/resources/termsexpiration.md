---
title: "termsExpiration resource type"
description: ""
localization_priority: Normal
author: "$(metadata.owner)"
ms.prod: ""
doc_type: "resourcePageType"
---

# termsExpiration resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

## Properties

| Property      | Type           | Description |
| :------------ | :------------- | :---------- |
| frequency     | Duration       |             |
| startDateTime | DateTimeOffset |             |

## Relationships

None.

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.termsExpiration",
}
-->

```json
{
  "@odata.type": "#microsoft.graph.termsExpiration",
  "frequency": "Duration",
  "startDateTime": "DateTimeOffset"
}
```