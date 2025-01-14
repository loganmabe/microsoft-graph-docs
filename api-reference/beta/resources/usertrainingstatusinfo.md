---
title: "userTrainingStatusInfo resource type"
description: "Represents assigned training and its status for a user in attack simulation and training."
author: "Gopal-MSFT"
ms.localizationpriority: medium
ms.prod: "reports"
doc_type: resourcePageType
---

# userTrainingStatusInfo resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents an assigned training and its status for a user in attack simulation and training.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|assignedDateTime|DateTimeOffset|Date and time of assignment of the training to the user.|
|completionDateTime|DateTimeOffset|Date and time of completion of the training by the user.|
|displayName|String|Display name of the assigned training.|
|trainingStatus|trainingStatus|Status of the training assigned to the user. Possible values are: `unknown`, `assigned`, `inProgress`, `completed`, `overdue`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.userTrainingStatusInfo"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userTrainingStatusInfo",
  "assignedDateTime": "String (timestamp)",
  "completionDateTime": "String (timestamp)",
  "trainingStatus": "String",
  "displayName": "String"
}
```

