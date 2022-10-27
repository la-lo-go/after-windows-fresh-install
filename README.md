# After Windows Fresh Install

## IDEs
- [Visual Studio Code](https://code.visualstudio.com/)
- [Eclipse](https://www.eclipse.org/downloads/)
- [Android Studio](https://developer.android.com/studio)
- [IntelliJ](https://www.jetbrains.com/idea/)
- [GoLand](https://www.jetbrains.com/go/)
- [PyCharm](https://www.jetbrains.com/pycharm/)
- [Visual Studio](https://visualstudio.microsoft.com)

## Lenguages
- [Python](https://www.python.org/downloads/)
- [Java](https://www.java.com/download/ie_manual.jsp)
- [Node](https://nodejs.org/en/)
- [Go](https://go.dev/dl/)
- [Rust](https://www.rust-lang.org/learn/get-started)
- TypeScript: `npm install -g typescript`

## Services
- [Docker](https://docs.docker.com/get-docker/)
- [Maven](https://maven.apache.org/download.cgi)
- [XAMPP](https://www.apachefriends.org/index.html)

## Developer tools
- [Notepad++](https://notepad-plus-plus.org/downloads/)
- [TeamViewer](https://www.teamviewer.com/es/descarga/windows/)
- [Notion](https://www.notion.so/desktop)
- [Postman](https://www.postman.com/downloads/)
- [WizTree](https://diskanalyzer.com/download)
- [Unity](https://unity.com/es/download)

## Utilities
- [Firefox](https://www.mozilla.org/firefox/new/)
- [GreenShoot](https://getgreenshot.org/downloads/)
- [EarTrumpet](https://www.microsoft.com/store/productId/9NBLGGH516XP)
- [Discord](https://discord.com/)
- [WhatsApp](https://www.microsoft.com/store/productId/9NKSQGP7F2NH)
- [7-Zip](https://www.7-zip.org/download.html)
- [OBS](https://obsproject.com/download)
- [4K Video Downloader](https://www.4kdownload.com/es/downloads/6#)
- [qBittorrent](https://www.qbittorrent.org/download.php)
- [DuetDisplay](https://es.duetdisplay.com/#download)
- [PotPlayer](https://potplayer.daum.net/)
- [ScpToolkit](https://github.com/nefarius/ScpToolkit/releases/tag/v1.6.238.16010)
- [Avidemux](https://avidemux.sourceforge.net/download.html)

## Games
- [Steam](https://store.steampowered.com/about/)
- [Amazon Games](https://www.amazongames.com/support/prime-gaming/articles/download-and-install-the-amazon-games-app)
- [Epic Games](https://store.epicgames.com/download)
- [EA](https://www.ea.com/ea-app)


## Oh my posh
1. Update terminal from the [WindowsStore](https://www.microsoft.com/store/productId/9N0DX20HK701)
2. Install from [here](ms-windows-store://pdp/?productid=XP8K0HKJFRXGCK)
3. Open a new console and type:
   ``` powershell
   code $PROFILE
   ```
4. Install a theme by copying this inside and save it:
   ``` powershell
    oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\agnoster.omp.json" | Invoke-Expression
   ```

   A list of themes is avalible [here](https://ohmyposh.dev/docs/themes), to change it replace "agnoster" with the name of the theme

5. Try open a new PowerShell window, if you are having a problem like this:
    ``` powershell
    No se puede cargar el archivo C:\Users\USER\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1 porque la ejecución de scripts está deshabilitada en este sistema. Para obtener más información, consulta el tema about_Execution_Policies en https:/go.microsoft.com/fwlink/?LinkID=135170.
        En línea: 1 Carácter: 3
        'C:\Users\USER\Documents\WindowsPowerShell\Microsoft.PowerShell_pr ...
        + ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        + CategoryInfo          : SecurityError: (:) [], PSSecurityException
        + FullyQualifiedErrorId : UnauthorizedAccess'
    ```

    Execute a new console as administrator and write:
    ``` powershell
    Set-ExecutionPolicy -ExecutionPolicy Bypass
    ```
6. Install a nerd font from ([here](https://www.nerdfonts.com/font-downloads) you have a few)
7. Restart the Terminal
8. Change the font to the new font: Configuracion > Valores predeterminados > Aparecia > Tipo de fuente    
