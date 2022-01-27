---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.People

$params = @{
	Categories = @(
		"Branding"
	)
	Client = @{
		DisplayName = "Contoso Ltd."
		Department = "Corporate Marketing"
		WebUrl = "https://www.contoso.com"
	}
	DisplayName = "Contoso Re-branding Project"
	Detail = @{
		Company = @{
			DisplayName = "Adventureworks Inc."
			Department = "Consulting"
			WebUrl = "https://adventureworks.com"
		}
		Description = "Rebranding of Contoso Ltd."
		JobTitle = "Lead PM Rebranding"
		Role = "project management"
		Summary = "A 6 month project to help Contoso rebrand after they were divested from a parent organization."
	}
}

New-MgUserProfileProject -UserId $userId -BodyParameter $params

```