---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

$params = @{
	Subject = "Party planning"
	ToRecipients = @(
		@{
			EmailAddress = @{
				Name = "Samantha Booth"
				Address = "samanthab@contoso.onmicrosoft.com"
			}
		}
	)
	Mentions = @(
		@{
			Mentioned = @{
				Name = "Dana Swope"
				Address = "danas@contoso.onmicrosoft.com"
			}
		}
	)
}

New-MgUserMessage -UserId $userId -BodyParameter $params

```