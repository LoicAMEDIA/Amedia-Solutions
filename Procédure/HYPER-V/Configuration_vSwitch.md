# Configuration : Mettre en place un vSwitch pour les VM

  ```powershell
  New-VMSwitch -Name "vSwitch-VM" -NetAdapterName "Ethernet1", "Ethernet2" -EnableEmbeddedTeaming $true -AllowManagementOS $false
```
