### ReadMe


Install: powershell.exe -ex bypass -file Add-AOVPNConnections.ps1 -UserTunnelXmlFilePath ProfileXML_User_EAP.xml -DeviceTunnelXmlFilePath ProfileXML_Device.xml -UserTunnelConnectionName "User VPN" -DeviceTunnelConnectionName "Device Tunnel VPN" -Version 1 -VersionKey TunnelVersion -UserTunnelInterfaceMetric 3 -DeviceTunnelInterfaceMetric 6 -replace
Remove: powershell.exe -ex bypass -file Remove-AovpnConnections.ps1 -UserTunnelConnectionName "User VPN" -DeviceTunnelConnectionName "Device Tunnel VPN"