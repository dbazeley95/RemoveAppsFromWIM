# RemoveAppsFromWIM
Remove Apps from Custom WIM


.DESCRIPTION
    Removing Built-in apps from a Windows 10/11 WIM File
.PARAMETER 
    PathtoWim - Full path to .wim file.
    selectapps - activates the selection function
    index - allows the selection of an index. Default value is 1.
.EXAMPLE
    .\removeapps.ps1 -pathtowim c:\10\install.wim
    .\removeapps.ps1 -pathtowim c:\10\install.wim -selectapps $true
    .\removeapps.ps1 -pathtowim c:\10\install.wim -selectapps $true -index 2
