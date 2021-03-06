---
title: include file
description: include file
services: cognitive-services
author: chliang
manager: bix

ms.service: cognitive-services
ms.component: anomaly-finder
ms.topic: include
ms.date: 04/13/2018
ms.author: chliang
ms.custom: include file
---
The data returned with the expected value and default upper and lower margins. In practice, you can define a [sensitivity] parameter, and then use (ExpectedValue + sensitivity * UpperMargin) as the upper bound and (ExpectedValue - sensitivity * LowerMargin) as the lower bound to tune the anomaly point by yourselves. The value of the [sensitivity] should be greater than 1. Below are some diagrams for tuning.

> [!NOTE]
> The diagrams are not generated by the sample application. They are created by a seperate tool with the sample application.

![Tunning: sensitivity = 1.0](../media/sensitivity_1.png)
![Tunning: sensitivity = 1.5](../media/sensitivity_1.5.png)
![Tunning: sensitivity = 2](../media/sensitivity_2.png)
![Tunning: sensitivity = 3.5](../media/sensitivity_3.5.png)