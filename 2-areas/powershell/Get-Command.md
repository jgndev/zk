
## Overview

When you run the `Get-Command` cmdlet in [[Cloud Shell]] you get a list of every command that's installed in PowerShell.

The common naming convention for PowerShell cmdlets is *verb-noun*.
For example `Get-Random`.

## Filtering the command list

```powershell
# Search for cmdlets where the noun is alias something
Get-Command -Noun alias*
```

```powershell
# Search for cmdlets where the verb is Get and the noun is alias something
Get-Command -Verb Get -Noun alias*
```