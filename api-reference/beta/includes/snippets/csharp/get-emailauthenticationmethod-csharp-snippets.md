---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var emailAuthenticationMethod = await graphClient.Me.Authentication.EmailMethods["3ddfcfc8-9383-446f-83cc-3ab9be4be18f"]
	.Request()
	.GetAsync();

```