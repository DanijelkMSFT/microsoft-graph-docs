---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.People

$params = @{
	Categories = @(
		"football"
	)
	DisplayName = "Lyn Damer"
	WebUrl = "www.lyndamer.no"
}

New-MgUserProfileWebsite -UserId $userId -BodyParameter $params

```