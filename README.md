# Powershell-Config
 
## Installation
1. Install WindowsTerminal
&nbsp;
2. Install the following font
[Hack Regular Nerd Font Complete Mono Windows Compatible.ttf](https://github.com/ryanoasis/nerd-fonts)
Install it by opening the file and press the install button on the top right corner.
&nbsp;

3. WindowsTerminal theme
[copy the code from here]()
&nbsp;

4. Allow executing scripts in Powershell
* Open Powershell as administrator
```
Set-ExecutionPolicy RemoteSigned
```

5. Install Powershell modules
* Open Powershell as administrator
```
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
Install-Module -Name PSWriteColor
```

6. Install my custom oh-my-posh theme
```
cd ~\OneDrive\Dokumente\WindowsPowerShell\Modules\oh-my-posh
cd 3.132.0  #Remind that this folders name changes based on the version you have installed.
cd themes
New-Item -ItemType file mussweg.omp.json
notepad mussweg.omp.json
```
or if your Documents are not saved to Onedrive then use this command
```
cd ~\Dokumente\WindowsPowerShell\Modules\oh-my-posh
cd 3.132.0  #Remind that this folders name changes based on the version you have installed.
cd themes
New-Item -ItemType file mussweg.omp.json
notepad mussweg.omp.json
```
[copy the code from here into the mussweg.omp.json file]()
&nbsp;

7. Create a Powershell $PROFILE
```
notepad $PROFILE
```
[copy this code in your Powershell profile]()


8. Import my custom aliases
```
cd ~\OneDrive\Dokumente\WindowsPowerShell
New-Item -ItemType file powershell_alias.ps1
```

or if your Documents are not saved to Onedrive then use this command

```
cd ~\Dokumente\WindowsPowerShell
New-Item -ItemType file powershell_alias.ps1
```

[copy the code from here into the powershell_alias.ps1 file]()

9. Enjoy