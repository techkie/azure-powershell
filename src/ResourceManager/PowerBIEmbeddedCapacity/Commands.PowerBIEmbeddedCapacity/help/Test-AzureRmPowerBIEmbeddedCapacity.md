---
external help file: Microsoft.Azure.Commands.PowerBIEmbeddedCapacity.dll-Help.xml
online version: 
schema: 1.0.0
---

# Test-AzureRmPowerBIEmbeddedCapacity

## SYNOPSIS
Tests the existence of an instance of PowerBI Embedded Capacity

## SYNTAX

```
Test-AzureRmPowerBIEmbeddedCapacity 
	[-Name] <String> 
	[[-ResourceGroupName] <String>] 
	[<CommonParameters>]
```

## DESCRIPTION
The Test-AzureRmPowerBIEmbeddedCapacity cmdlet tests the existence of an instance of PowerBI Embedded Capacity

## EXAMPLES

### Example 1
```
PS C:\> Test-AzureRmPowerBIEmbeddedCapacity -Name "testcapacity" -ResourceGroupName "testgroup"
```

This command will test if there is a capacity named testcapacity in the resourcegroup testgroup

## PARAMETERS

### -Name
Name of the PowerBI Embedded Capacity

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Name of the Azure resource group to which the capacity belongs

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Boolean

## NOTES
Alias: Test-AzurePBIECapacity

## RELATED LINKS

[Get-AzureRmPowerBIEmbeddedCapacity](./Get-AzureRmPowerBIEmbeddedCapacity.md)

[Remove-AzureRmPowerBIEmbeddedCapacity](./Remove-AzureRmPowerBIEmbeddedCapacity.md)