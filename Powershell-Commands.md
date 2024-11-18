# Active Directory

_Rename the machine._

> Rename-computer -NewName PDC -Restart

_Install Active Directory Services_

> Install-WindowsFeature AD-Domain-Services -IncludeManagementTools

_Promote Domain Controller._

> Install-ADDSDomainController -DomainName "rabat.local" -InstallDns:$true -Credential (Get-Credential "RABAT\administrator")

_Install DHCP Role._

> Install-WindowsFeature DHCP -IncludeManagementTools

_Authorize or Unauthorize The DHCP Server on the domain._

> Add-DhcpServerInDC / Remove-DhcpServerInDC

_Adds an IPv4 scope on the DHCP server service._

> Add-DhcpServerv4Scope -Name "LAN" -StartRange 192.168.150.2 -EndRange 192.168.150.254 -SubnetMask 255.255.255.0

_Adds a range of excluded IP addresses for an IPv4 scope._

> Add-Dhcpserverv4ExclusionRange -ScopeId 192.168.150.0 -StartRange 192.168.150.2 -EndRange 192.168.150.29

