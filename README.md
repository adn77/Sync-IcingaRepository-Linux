# Icinga custom repository synchronisation for Linux
Bash version of Sync-IcingaRepository

Argument list matches powershell command except for the *-Latest* option which downloads only
most recent packages in order to keep the local repo small and reduce download traffic

```
Sync-IcingaRepository
    -Name 'Icinga Stable Local'
    -Path './var/www'
    -RemotePath 'https://monitoring.example.org/repo'
    -Source 'https://packages.icinga.com/IcingaForWindows/stable/ifw.repo.json';
   [-Latest]
```
