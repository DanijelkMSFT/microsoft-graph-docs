---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.PersonalContacts

$params = @{
	GivenName = "Pavel"
	Surname = "Bansky"
	EmailAddresses = @(
		@{
			Address = "pavelb@fabrikam.onmicrosoft.com"
			Name = "Pavel Bansky"
		}
	)
	BusinessPhones = @(
		"+1 732 555 0102"
	)
}

New-MgUserContact -UserId $userId -BodyParameter $params

```