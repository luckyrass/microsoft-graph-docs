---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

boolean securityEnabledOnly = True;

graphClient.me()
	.getMemberObjects(securityEnabledOnly)
	.buildRequest()
	.post();

```