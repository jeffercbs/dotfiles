# **dotfiles for win**

### **PowerShell**

- `Microsoft.PowerShell_profile.ps1` Configuring for PowerShell

**_install_**

- _oh-my-posh_

```shell
$ Install-Module oh-my-posh -Scope CurrentUser -AllowPrerelease
```

- **Terminal-Icons**

````shell
$ Install-Module -Name Terminal-Icons -Repository PSGallery
```
````

- **choco**

```shell
$  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
