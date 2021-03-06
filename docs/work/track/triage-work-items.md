---
title: Triage work items using a work item query 
titleSuffix: VSTS & TFS  
ms.global_help.title: Triage work items
description: Review and update work items use the triage mode from the query results view in Visual Studio Team Services & Team Foundation Server
ms.prod: devops
ms.technology: devops-agile
ms.assetid: 486A876F-A04F-4DC7-829C-94E88BB9B7E1 
ms.topic: tutorial
ms.manager: douge
ms.author: kaelliauthor: KathrynEE
monikerRange: '>= tfs-2013'
ms.date: 06/21/2018  
---


# Triage work items  

[!INCLUDE [temp](../_shared/version-vsts-tfs-all-versions.md)]

Using a work item query you can quickly review and update work items. Oftentimes team use the triage mode for a query to perform the following tasks: 
- Set the priority of a bug or work item 
- Assign a work item to a sprint or team member 
- Add details to the description, acceptance criteria, or repo steps 
- Link related work items 
- Update the status of work items 

In this topic you'll learn how to:

>[!div class="checklist"]      
> * Use triage query mode to update a list of work items   
> * Bulk save work items that you've updated  

[!INCLUDE [temp](../_shared/prerequisites.md)]


## Open Queries 

[!INCLUDE [temp](../_shared/new-agile-hubs-feature.md)] 

[!INCLUDE [temp](../_shared/open-queries.md)] 


::: moniker range="vsts"

The buttons to move up or down within the query results list are outside the work item form. Click Bottom to cycle through the choices for where the work item form appears: Bottom, Right, or Off. 

![Web portal, choose Work>Queries](_img/triage-queries/triage-buttons-new-exp.png)

::: moniker-end

::: moniker range=">= tfs-2013 <= tfs-2018"

The buttons to move up or down within the query results list are inside the work item form. Click Bottom to cycle through the choices for where the work item form appears: Bottom, Right, or Off.

![Triage query results ](_img/triage-queries/scrum-active-bug-triage-mode-co.png)

::: moniker-end


 
## Save bulk changes made to work items 

You can update several work items through the triage process, and then do a bulk save when you're finished. Work items shown in bold text indicate that local changes have not yet been saved to the data store.   


::: moniker range="vsts"
Choose **Save items** to save all work items you've modified. 

<img src="_img/triage-queries/save-work-items-new-exp.png" alt="Choose Save work items to save all modified work items" style="border: 1px solid #C3C3C3;" /> 

::: moniker-end

::: moniker range=">= tfs-2013 <= tfs-2018"

Choose the ![double-save-icon](../_img/icons/icon-double-save.png) double-save icon to save all work items you've modified.

![VSTS and TFS 2017, Query results page, save bulk modified items](../backlogs/_img/bulk-modify-save-ts.png)  

::: moniker-end


## Related articles

- [Manage bugs](../backlogs/manage-bugs.md) 
- [Create a query](using-queries.md) 

