---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Calendar

Get-MgUserEvent -UserId $userId -EventId $eventId -Property "subject,start,end,occurrenceId,exceptionOccurrences,cancelledOccurrences`$expand" 

```