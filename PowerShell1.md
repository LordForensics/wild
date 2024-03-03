# Découverte du language PowerShell

## Lien entre PowerShell et Unix

Les Commandes **PowerShell** correspondent aux commandes **Linux _shell bash_**

Voici quelques exemples de commandes **PowerShell** et leurs équivalents côté **Unix**

Vous trouverez également les commandes utilisées dans pour trouver les _cmdlets_ **PowerShell**


1. **Copy-Item** correspond à la commande _cp_ qui permet de copier des fichiers ou des répertoires

> PS C:\Users\forensics> Get-Help cp
>
>NOM
>    Copy-Item
>
>SYNTAXE
>    Copy-Item [-Path] <string[]> [[-Destination] <string>]  [<CommonParameters>]
>
>    Copy-Item [[-Destination] <string>]  [<CommonParameters>]
>
>
>ALIAS
>    cpi
>    cp
>    copy

2. **Remove-Item** correspond à la commande _rm_ qui permet supprimer des fichiers dans un répertoire

>PS C:\Users\forensics> Get-Help rm
>
>NOM
>    Remove-Item
>
>SYNTAXE
>    Remove-Item [-Path] <string[]>  [<CommonParameters>]
>
>    Remove-Item  [<CommonParameters>]
>
>
>ALIAS
>    ri
>    rm
>    rmdir
>    del
>    erase
>    rd

3. **Set-Location** correspond à la commande _cd_ qui permet de naviguer dans les fichiers et les répertoires

>PS C:\Users\forensics> Get-Help cd
>
>NOM
>    Set-Location
>
>SYNTAXE
>    Set-Location [[-Path] <string>]  [<CommonParameters>]
>
>    Set-Location  [<CommonParameters>]
>
>    Set-Location  [<CommonParameters>]
>
>
>ALIAS
>    sl
>    cd
>    chdir

4. **New-Item** correspond à la commande _mkdir_ qui permet de créer un ou plusieurs répertoire en une fois

>PS C:\Users\forensics> Get-Help mkdir
>
>NOM
>    New-Item
>
>SYNTAXE
>    New-Item [-Path] <string[]>  [<CommonParameters>]
>
>    New-Item [[-Path] <string[]>]  [<CommonParameters>]
>
>
>ALIAS
>    ni

5. **Get-Help** correspond à la commande _man_ qui permet de fournir un manuel d'utilisation des commandes

>PS C:\Users\forensics> Get-Help man
>
>NOM
>    Get-Help
>
>SYNTAXE
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>    Get-Help [[-Name] <string>]  [<CommonParameters>]
>
>
>ALIAS
>    Aucun(e)

6. **Get-History** correspond à la commande _history_ qui permet d'afficher l'historique des commandes éxécutées

>PS C:\Users\forensics> Get-Help history
>
>NOM
>    Get-History
>
>SYNTAXE
>    Get-History [[-Id] <long[]>] [[-Count] <int>]  [<CommonParameters>]
>
>
>ALIAS
>    ghy
>    h
>    history

7. **New-Alias** correspond à la commande _alias_ qui permet de créer un raccourci ayant les mêmes fonctionnalités qu'une commande, un nom de fichier ou un texte

>PS C:\Users\forensics> Get-Help alias
>
>Name                              Category  Module                    Synopsis
>
>Export-Alias                      Cmdlet    Microsoft.PowerShell.U  
>Get-Alias                         Cmdlet    Microsoft.PowerShell.U  
>Import-Alias                      Cmdlet    Microsoft.PowerShell.U  
>New-Alias                         Cmdlet    Microsoft.PowerShell.U  
>Set-Alias                         Cmdlet    Microsoft.PowerShell.U  
>
>PS C:\Users\forensics> Get-Help New-Alias
>
>NOM
>    New-Alias
>
>SYNTAXE
>    New-Alias [-Name] <string> [-Value] <string>  [<CommonParameters>]
>
>
>ALIAS
>    nal

8. **Get-Content** correspond à la commande _cat_ qui permet de concaténer afin d'afficher le contenu des fichiers

>PS C:\Users\forensics> Get-Help cat
>
>NOM
>    Get-Content
>
>SYNTAXE
>    Get-Content [-Path] <string[]>  [<CommonParameters>]
>
>    Get-Content  [<CommonParameters>]
>
>
>ALIAS
>    gc
>    cat
>    type

## Résumé des commandes sous forme de tableau

|Recherche|Commandes PowerShell|Commandes Unix|
|:-:|:-:|:-:|
|get-help cp|copy-item|cp|
|get-help rm|remove-item|rm|
|get-help cd|set-location|cd|
|get-help mkdir|new-item|mkdir|
|get-help man|get-help|man|
|get-help history|get-history|history|
|get-help alias|new-alias|alias|
|get-help cat|get-content|cat|

