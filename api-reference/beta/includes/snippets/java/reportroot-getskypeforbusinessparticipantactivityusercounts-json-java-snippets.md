---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ISkypeForBusinessParticipantActivityUserCountsCollectionPage getSkypeForBusinessParticipantActivityUserCounts = graphClient.reports()
	.getSkypeForBusinessParticipantActivityUserCounts("D7")
	.buildRequest()
	.get();

```