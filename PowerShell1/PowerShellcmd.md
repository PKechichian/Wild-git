* cp = Copy-Item
* rm = Remove-Item
* cd = Set-Location
* mkdir = New-Item
* man = Get-Help
* history = Get-PSReadlineOption
* alias = Set-Alias
* cat = Get-Content

# PS C:\> Get-Help cp

NAME
    Copy-Item
    
SYNTAX
    Copy-Item [-Path] <string[]> [[-Destination] <string>] [-Container] 
    [-Force] [-Filter <string>] [-Include <string[]>] [-Exclude <string[]>] 
    [-Recurse] [-PassThru] [-Credential <pscredential>] [-WhatIf] [-Confirm] 
    [-UseTransaction] [-FromSession <PSSession>] [-ToSession <PSSession>]  
    [<CommonParameters>]
    
    Copy-Item [[-Destination] <string>] -LiteralPath <string[]> [-Container] 
    [-Force] [-Filter <string>] [-Include <string[]>] [-Exclude <string[]>] 
    [-Recurse] [-PassThru] [-Credential <pscredential>] [-WhatIf] [-Confirm] 
    [-UseTransaction] [-FromSession <PSSession>] [-ToSession <PSSession>]  
    [<CommonParameters>]
    

ALIASES
    cpi
    cp
    copy
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Copy-Item -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113292.




# PS C:\> Get-Help rm

NAME
    Remove-Item
    
SYNTAX
    Remove-Item [-Path] <string[]> [-Filter <string>] [-Include <string[]>] 
    [-Exclude <string[]>] [-Recurse] [-Force] [-Credential <pscredential>] 
    [-WhatIf] [-Confirm] [-UseTransaction] [-Stream <string[]>]  
    [<CommonParameters>]
    
    Remove-Item -LiteralPath <string[]> [-Filter <string>] [-Include 
    <string[]>] [-Exclude <string[]>] [-Recurse] [-Force] [-Credential 
    <pscredential>] [-WhatIf] [-Confirm] [-UseTransaction] [-Stream 
    <string[]>]  [<CommonParameters>]
    

ALIASES
    ri
    rm
    rmdir
    del
    erase
    rd
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Remove-Item -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113373.




# PS C:\> Get-Help cd

NAME
    Set-Location
    
SYNTAX
    Set-Location [[-Path] <string>] [-PassThru] [-UseTransaction]  
    [<CommonParameters>]
    
    Set-Location -LiteralPath <string> [-PassThru] [-UseTransaction]  
    [<CommonParameters>]
    
    Set-Location [-PassThru] [-StackName <string>] [-UseTransaction]  
    [<CommonParameters>]
    

ALIASES
    sl
    cd
    chdir
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Set-Location -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113397.




# PS C:\> Get-Help mkdir

NAME
    New-Item
    
SYNTAX
    New-Item [-Path] <string[]> [-ItemType <string>] [-Value <Object>] 
    [-Force] [-Credential <pscredential>] [-WhatIf] [-Confirm] 
    [-UseTransaction]  [<CommonParameters>]
    
    New-Item [[-Path] <string[]>] -Name <string> [-ItemType <string>] [-Value 
    <Object>] [-Force] [-Credential <pscredential>] [-WhatIf] [-Confirm] 
    [-UseTransaction]  [<CommonParameters>]
    

ALIASES
    ni
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    New-Item -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113353.




# PS C:\> Get-Help man

NAME
    Get-Help
    
SYNTAX
    Get-Help [[-Name] <string>] [-Path <string>] [-Category {Alias | Cmdlet | 
    Provider | General | FAQ | Glossary | HelpFile | ScriptCommand | Function 
    | Filter | ExternalScript | All | DefaultHelp | Workflow | DscResource | 
    Class | Configuration}] [-Component <string[]>] [-Functionality 
    <string[]>] [-Role <string[]>] [-Full]  [<CommonParameters>]
    
    Get-Help [[-Name] <string>] -Detailed [-Path <string>] [-Category {Alias | 
    Cmdlet | Provider | General | FAQ | Glossary | HelpFile | ScriptCommand | 
    Function | Filter | ExternalScript | All | DefaultHelp | Workflow | 
    DscResource | Class | Configuration}] [-Component <string[]>] 
    [-Functionality <string[]>] [-Role <string[]>]  [<CommonParameters>]
    
    Get-Help [[-Name] <string>] -Examples [-Path <string>] [-Category {Alias | 
    Cmdlet | Provider | General | FAQ | Glossary | HelpFile | ScriptCommand | 
    Function | Filter | ExternalScript | All | DefaultHelp | Workflow | 
    DscResource | Class | Configuration}] [-Component <string[]>] 
    [-Functionality <string[]>] [-Role <string[]>]  [<CommonParameters>]
    
    Get-Help [[-Name] <string>] -Parameter <string> [-Path <string>] 
    [-Category {Alias | Cmdlet | Provider | General | FAQ | Glossary | 
    HelpFile | ScriptCommand | Function | Filter | ExternalScript | All | 
    DefaultHelp | Workflow | DscResource | Class | Configuration}] [-Component 
    <string[]>] [-Functionality <string[]>] [-Role <string[]>]  
    [<CommonParameters>]
    
    Get-Help [[-Name] <string>] -Online [-Path <string>] [-Category {Alias | 
    Cmdlet | Provider | General | FAQ | Glossary | HelpFile | ScriptCommand | 
    Function | Filter | ExternalScript | All | DefaultHelp | Workflow | 
    DscResource | Class | Configuration}] [-Component <string[]>] 
    [-Functionality <string[]>] [-Role <string[]>]  [<CommonParameters>]
    
    Get-Help [[-Name] <string>] -ShowWindow [-Path <string>] [-Category {Alias 
    | Cmdlet | Provider | General | FAQ | Glossary | HelpFile | ScriptCommand 
    | Function | Filter | ExternalScript | All | DefaultHelp | Workflow | 
    DscResource | Class | Configuration}] [-Component <string[]>] 
    [-Functionality <string[]>] [-Role <string[]>]  [<CommonParameters>]
    

ALIASES
    None
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Get-Help -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113316.




# PS C:\> Get-Help history

NAME
    Get-History
    
SYNTAX
    Get-History [[-Id] <long[]>] [[-Count] <int>]  [<CommonParameters>]
    

ALIASES
    ghy
    h
    history
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Get-History -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113317.




# PS C:\> Get-Help alias

Name                              Category  Module                    Synopsis 
----                              --------  ------                    -------- 
Export-Alias                      Cmdlet    Microsoft.PowerShell.U... ...      
Get-Alias                         Cmdlet    Microsoft.PowerShell.U... ...      
Import-Alias                      Cmdlet    Microsoft.PowerShell.U... ...      
New-Alias                         Cmdlet    Microsoft.PowerShell.U... ...      
Set-Alias                         Cmdlet    Microsoft.PowerShell.U... ...      



#PS C:\> get-help cat

NAME
    Get-Content
    
SYNTAX
    Get-Content [-Path] <string[]> [-ReadCount <long>] [-TotalCount <long>] 
    [-Tail <int>] [-Filter <string>] [-Include <string[]>] [-Exclude 
    <string[]>] [-Force] [-Credential <pscredential>] [-UseTransaction] 
    [-Delimiter <string>] [-Wait] [-Raw] [-Encoding {Unknown | String | 
    Unicode | Byte | BigEndianUnicode | UTF8 | UTF7 | UTF32 | Ascii | Default 
    | Oem | BigEndianUTF32}] [-Stream <string>]  [<CommonParameters>]
    
    Get-Content -LiteralPath <string[]> [-ReadCount <long>] [-TotalCount 
    <long>] [-Tail <int>] [-Filter <string>] [-Include <string[]>] [-Exclude 
    <string[]>] [-Force] [-Credential <pscredential>] [-UseTransaction] 
    [-Delimiter <string>] [-Wait] [-Raw] [-Encoding {Unknown | String | 
    Unicode | Byte | BigEndianUnicode | UTF8 | UTF7 | UTF32 | Ascii | Default 
    | Oem | BigEndianUTF32}] [-Stream <string>]  [<CommonParameters>]
    

ALIASES
    gc
    cat
    type
    

REMARKS
    Get-Help cannot find the Help files for this cmdlet on this computer. It 
    is displaying only partial help.
        -- To download and install Help files for the module that includes 
    this cmdlet, use Update-Help.
        -- To view the Help topic for this cmdlet online, type: "Get-Help 
    Get-Content -Online" or 
           go to https://go.microsoft.com/fwlink/?LinkID=113310.
