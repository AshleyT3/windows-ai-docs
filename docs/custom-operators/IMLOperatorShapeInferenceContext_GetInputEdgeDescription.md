---
author: eliotcowley
title: IMLOperatorShapeInferenceContext.GetInputEdgeDescription method
description: Gets the description of the specified input edge of the operator.
ms.author: elcowle
ms.date: 11/1/2018
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: windows 10, windows machine learning, WinML, custom operators, GetInputEdgeDescription
ms.localizationpriority: medium
topic_type:
- APIRef
api_type:
- NA
api_name:
- IMLOperatorShapeInferenceContext.GetInputEdgeDescription
api_location:
- MLOperatorAuthor.h
---

# IMLOperatorShapeInferenceContext.GetInputEdgeDescription method

Gets the description of the specified input edge of the operator.

```cpp
void GetInputEdgeDescription(
    uint32_t inputIndex,
    _Out_ MLOperatorEdgeDescription* edgeDescription)
```

## Requirements

| | |
|-|-|
| **Minimum supported client** | Windows 10, build 17763 |
| **Header** | MLOperatorAuthor.h |

[!INCLUDE [help](../includes/get-help.md)]