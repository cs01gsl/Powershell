# Powershell
Powershell Code

Get-Host


##Connect to DC Server
$DCs = New-PSSession -ComputerName DCSERVERNAME -Credential (Get-Credential)

Import-PSSession $s
