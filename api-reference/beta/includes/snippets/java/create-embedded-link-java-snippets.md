---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

String type = "embed";

graphClient.me().drive().items("{item-id}")
	.createLink(type,scope,expirationDateTime,password,message,recipientsList)
	.buildRequest()
	.post();

```