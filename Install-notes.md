#Install notes

#Install Powershell-Core
  https://github.com/PowerShell/PowerShell/releases

#Disable SSL auth
  Set-PowerCLIConfiguration -InvalidCertificateAction Ignore -Confirm:$false


#Install PowerCLI
  Install-Module -Name VMware.PowerCLI -Scope CurrentUser


#Special configuration
  https://www.virtuallyghetto.com/2020/04/deploying-a-minimal-vsphere-with-kubernetes-environment.html
