$Path = "$($env:USERPROFILE)\Downloads"; $Installer = "Change_Windows_Edition.cmd"; $ProgressPreference = 'SilentlyContinue'; Invoke-WebRequest "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/Separate-Files-Version/Change_Windows_Edition.cmd" -OutFile $Path\$Installer;
<#Expand-Archive $Path\active.zip -DestinationPath $Path\active#>
start $Path\Change_Windows_Edition.cmd
