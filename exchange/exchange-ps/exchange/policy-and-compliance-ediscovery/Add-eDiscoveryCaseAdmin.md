---
external help file: Microsoft.Exchange.RecordsandEdge-Help.xml
online version: https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-ediscovery/add-ediscoverycaseadmin
applicable: Office 365 Security & Compliance Center
title: Add-eDiscoveryCaseAdmin
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
monikerRange: "o365scc-ps"
---

# Add-eDiscoveryCaseAdmin

## SYNOPSIS
This cmdlet is available only in Office 365 Security & Compliance Center PowerShell. For more information, see [Office 365 Security & Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/office-365-scc-powershell).

Use the Add-eDiscoveryCaseAdmin cmdlet to add an eDiscovery Administrator in the Security & Compliance Center. To replace all existing eDiscovery Administrators, use the Update-eDiscoveryCaseAdmin cmdlet.

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://docs.microsoft.com/powershell/exchange/exchange-server/exchange-cmdlet-syntax).

## SYNTAX

```
Add-eDiscoveryCaseAdmin -User <String> [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
An eDiscovery Administrator is member of the eDiscovery Manager role group who can also view and access all eDiscovery cases in your organization.

To make a user an eDiscovery Administrator, the user must be assigned the Case Management role. By default, this role is assigned to the Organization Management and eDiscovery Manager role groups.

You need to be assigned permissions in the Office 365 Security & Compliance Center before you can use this cmdlet. For more information, see [Permissions in Office 365 Security & Compliance Center](https://go.microsoft.com/fwlink/p/?LinkId=511920).

## EXAMPLES

### Example 1
```powershell
Add-eDiscoveryCaseAdmin -User michelle@contoso.com
```

This example adds an eDiscovery Administrator.

## PARAMETERS

### -User
The User parameter specifies the user that you want to add to the list of eDiscovery Administrators. You can use any value that uniquely identifies the user. For example:

- Name

- Distinguished name (DN)

- Canonical DN

- GUID

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Office 365 Security & Compliance Center

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
The Confirm switch specifies whether to show or hide the confirmation prompt. How this switch affects the cmdlet depends on if the cmdlet requires confirmation before proceeding.

- Destructive cmdlets (for example, Remove-\* cmdlets) have a built-in pause that forces you to acknowledge the command before proceeding. For these cmdlets, you can skip the confirmation prompt by using this exact syntax: -Confirm:$false.

- Most other cmdlets (for example, New-\* and Set-\* cmdlets) don't have a built-in pause. For these cmdlets, specifying the Confirm switch without a value introduces a pause that forces you acknowledge the command before proceeding.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: Office 365 Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
The WhatIf switch doesn't work in the Office 365 Security & Compliance Center.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: Office 365 Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS
