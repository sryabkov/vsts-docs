---
title: Kanban quickstart 
titleSuffix: VSTS & TFS
description: Plan and track your work using the Kanban board in Visual Studio Team Services (VSTS) and Team Foundation Server (TFS)  
ms.topic: get-started-article
ms.technology: vs-devops-wit
ms.prod: vs-devops-alm
ms.assetid: 4942A638-9888-461E-969D-0BB9B1FE1736
ms.manager: douge
ms.author: kaelli
ms.date: 12/11/2017
---

# Get started using your Kanban board

<b>VSTS | TFS 2018 | TFS 2017</b> 

Your Kanban board turns your backlog into an interactive signboard, providing a visual flow of work. As work progresses from idea to completion, you update the items on the board. Each column represents a work stage, and each card represents a backlog item, user story, or bug at that stage of work.  

User stories and bugs correspond to types of work items. You use  [work items](../backlogs/add-work-items.md) to share information, assign work to team members, update status, track dependencies, and more.


## Prerequisites 

- You must have a team project. If you don't have an account or team project yet, create one in [VSTS](../../user-guide/sign-up-invite-teammates.md).  
- To contribute to the Kanban board, you must be a member of the Contributors group. If you don't have access to the team project, ask the [account owner or project administrator](../../security/add-users-team-project.md) to add you.
- To configure the Kanban board, you must be [added as a team administrator](../scale/add-team-administrator.md) or be a member of the Project Administrators group. If you're the account owner or creator of the team project, then you'll have these permissions.  


## Open your Kanban board from the web portal

0. To view your Kanban board, click **Work>Backlogs**, and then click **Board**. 

	<img src="_img/kanban-basics-intro.png" alt="Kanban board, Agile template" style="border: 1px solid #C3C3C3;" />   

	The web browser URL follows this pattern:  
	- **VSTS**: ```https://{account name}.visualstudio.com/DefaultCollection/{project name}/_backlogs\board```  
	- **On-premises TFS**: ```http://serverName:8080/tfs/DefaultCollection/projectName/_backlogs\board```  

	You can use this URL to quickly open the team project, substituting the {account name} and {project name} with your specific account and project name (remove braces). 

0. If you don't see the **Work** hub, your screen size may be reduced. Click the three dots (![elipses](../../_shared/_img/ellipses-reduced-screen-size.png)), then click **Work**, **Backlogs**, and then **Board**. 

	![Open Work hub when screen size is reduced](_img/kanban-quickstart-reduced-screensize.png) 

0. If you don't see the team or team project you want, click the ![VSTS icon](../_img/icons/project-icon.png) VSTS icon to [browse all team projects and teams](../../user-guide/account-home-pages.md). 


<!---
### TFS 2015, TFS 2013

<img src="../backlogs/_img/cyb-open-backlog-tfs-2015.png" alt="Open the backlog" style="border: 1px solid #C3C3C3;" />  

The URL follows this pattern:  
```http://serverName:8080/tfs/DefaultCollection/projectName/_backlogs```  

If you don't see the team or team project you want, open the team project/team drop-down menu and select the team project/team that you've recently visited. If you don't see the team or team project you want, choose **Browse all** to browse all team projects and teams. 

<img src="../_shared/_img/switch-team-project-2.png" alt="Choose another team from the team project menu" style="border: 1px solid #C3C3C3;" /> 

To view your Kanban board, click the **Board** link from the **Work>Backlogs** page. 

<img src="_img/kanban-basics-intro.png" alt="Kanban board, Agile template" style="border: 1px solid #C3C3C3;" />  
-->


[!INCLUDE [temp](../_shared/image-differences.md)] 


<a id="add-work-items"> </a>
## Add work items 

0. To add a work item, simply click the plus sign (![plus icon](../_img/icons/add_icon.png)) and enter a title for the item, and then press Enter on your keyboard. 

	<img src="_img/kanban-qs-add-new-item.png" alt="Kanban board, Agile template, add a work item" style="border: 1px solid #C3C3C3;" />  

	The system automatically saves the work item with the title you entered. You can add as many work items you want using this method. 

0. To add details to any work item, click the title. Or, you can directly modify any field that displays. For example, you can reassign a work item by clicking the Assigned To field.   

<a id="update-status">  </a>
## Update the status of work items via drag-and-drop

<meta name="description" content="Kanban tools track progress" />

As work completes in one stage, update the status of an item by dragging and dropping it to a downstream stage. 

<img src="_img/ALM_CC_MoveCard.png" alt="Kanban board, Agile template, update status of work item" style="border: 1px solid #C3C3C3;" />  

## Update fields from the card 

Also, you can quickly update a field or reassign ownership directly from the board. 

![Kanban, assign items](_img/ALM_CC_UpdateFieldOnCard.png)

If the field you want to update isn't showing, then [customize the card to show it](../customize/customize-cards.md). 

## Invite others to work on your Kanban board 

All members of a team project will be able to view and contribute to your Kanban board. To invite users to start contributing, copy the URL of your Kanban board and email it to those you want to invite to your project. 

<img src="_img/kanban-basics-url.png" alt="Browser URL for the Kanban board" style="border: 1px solid #C3C3C3;" /> 

To add users to your team project, see [Add users to a team project](../../security/add-users-team-project.md)   


## Try this next 

To get the full power of the Kanban board working for you, you'll want to configure it to map the flow of work and set WIP limits for your team.   

> [!div class="nextstepaction"]
> [Kanban basics](kanban-basics.md)  

If you're new to VSTS or TFS and want to understand what you can customize, see [Customize your work tracking experience](../customize/customize-work.md). 

> [!NOTE]  
> Your Kanban board is one of two types of boards available to you. For an overview of the features supported on each backlog and board, see [Backlogs, boards, and plans](../backlogs/backlogs-boards-plans.md). To switch to the [product backlog](../backlogs/create-your-backlog.md), click **Backlog**. And, to switch to the [Task board](../scrum/task-board.md), click on the current iteration or other sprint of interest. If no sprints appear, see [Schedule sprints](../scrum/define-sprints.md). 

<!--- 
Here are a few things you can do. See at a glance the estimated size of work for each item which displays at the bottom right of each card. Add items to your backlog in the first column. When priorities change, move items up and down within a column. And, as work completes in one stage, update the status of an item by dragging and dropping it to a downstream stage.

Each team can manage their backlog and customize their Kanban board. [Add teams](../scale/multiple-teams.md) when you assign specific feature areas to different teams for development. Each team can then manage their backlog and focus on how they will develop their deliverables. 

Here are some useful tips when working with the Kanban board:
- To quickly assign items to a team member, add the Assign To field to display on the cards (see [Customize cards](../customize/customize-cards.md))   
- Customize cards to show the fields you most care about  
- Add a swimlane to track high-priority work or track work which falls into different service level agreements (see [Swimlanes](expedite-work.md))   
- Highlight specific work items by color coding cards based on a field value or tag (see [Customize cards](../customize/customize-cards.md)) 
- If you use Scrumban, drag-and-drop cards onto a sprint to quickly assign them to a sprint.  


-->

 


 
 

