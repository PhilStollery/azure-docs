---
title: 'Overview: Perform an access review in Privileged Identity Management for Azure resources | Microsoft Docs'
description: This document describes how to perform an access review in PIM for Azure resources.
services: active-directory
documentationcenter: ''
author: rolyon
manager: mtillman
editor: markwahl-msft
ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.component: protection
ms.date: 03/30/2018
ms.author: rolyon
ms.custom: pim
---

# Use a resource dashboard to perform an access review

You can use a resource dashboard to perform an access review in Privileged Identity Management (PIM) for Azure resources. The Admin View dashboard has three primary components:

- A graphical representation of resource role activations.
- Two charts that display the distribution of role assignments by assignment type.
- A data area pertaining to new role assignments.

![Screenshot of the Admin View dashboard, showing graphs and charts](media/azure-pim-resource-rbac/rbac-overview-top.png)

![Screenshot of teh Admin View dashboard, showing data lists](media/azure-pim-resource-rbac/role-settings.png)

The graphical representation of resource role activations covers the past seven days. This data is scoped to the selected resource, and displays activations for the most common roles (owner, contributor, user access administrator), and for all roles combined.

To the right of the activations graph, two charts display the distribution of role assignments by assignment type, for both users and groups. You can change the value to a percentage (or vice versa), by selecting a slice of the chart.

Below the charts, you see the number of users and groups with new role assignments over the last 30 days, and a list of roles sorted by total assignments (in descending order).


