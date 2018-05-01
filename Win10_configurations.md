## Chocolatey Package Manager
##ps: 
<Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))>
#####ps: Packages through chocolatey: Slack, Spotify, Chrome, Battle.net, windirstat
<choco install slack spotify googlechrome battle.net windirstat>

## WSL - https://docs.microsoft.com/en-us/windows/wsl/install-win10
####Turn on Developer Mode:
  Settings -> Update and Security -> For developers <Developer mode>
####ps:
  <Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux>
####Debian Stretch(microsoft store):
  https://www.microsoft.com/store/productId/9MSVKQC78PK6
####ps:
  <bash>
####bash:
<sudo bash debian_packages.sh>


## Manual Install Apps
####Global Protect
  https://www.paloaltonetworks.com/documentation/31/globalprotect/gp-agent-user-guide/globalprotect-agent-for-windows/download-and-install-the-globalprotect-agent-for-windows

####VMware
  https://vmware.et.byu.edu/