---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var plannerPlan = await graphClient.Planner.Plans["'id'"]
	.Request()
	.GetAsync();

```