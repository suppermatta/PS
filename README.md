Get-PSSnapin -Registered 

get-help *module 

Get-Module 

Get-Module -ListAvailable 

Import-Module -name ActiveDirectory 

Get-Command -Module VPNClient 

Get-Help *adcomputer* 

$PSVersionTable 

Find-Module 

Install-Module psreadline 

Set-PSReadLineOption -EditMode Emacs 

Find-Package 

Get-Service -Name BITS 

Stop-Service -Name BITS 

Get-Service -Name BITS | Stop-Service 

Get-Service | Stop-Service -WhatIf 

Get-Service | Out-File -FilePath C:\CCNA\services.txt 

Get-Content -Path C:\CCNA\service.txt 

notepad C:\CCNA\services.txt 

Get-EventLog -LogName System -EntryType Error -Newest 100 | Out-File -FilePath C:\CCNA\errors.txt 

Get-EventLog -LogName System -EntryType Error -Newest 100 | Export-Csv -Path C:\CCNA\errors.csv -NoTypeInformation 

Get-EventLog -LogName System -EntryType Error -Newest 100 | convertto-Csv -NoTypeInformation 

Import-Csv -Path C:\CCNA\errors.csv 

Get-EventLog -LogName System -EntryType Error -Newest 100 | Export-Clixml -Path C:\CCNA\errors.xml 

 
