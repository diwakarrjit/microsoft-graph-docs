---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Users

Get-MgUser -Filter "startswith(displayName,'Eric')" -Property "displayName,signInActivity"  -OutFile $outFileId

```