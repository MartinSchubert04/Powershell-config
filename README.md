# Oh My Posh config

Pegar config de txt dentro de $PROFILE (cambiar ruta del theme segun corresponda)

```pwsh
New-Item -Path $PROFILE -Type File -Force
notepad $PROFILE
```

### Instalar PSReadLine

\*\* Predictview solo para Powershell 7

```pwsh
Install-Module PSReadLine -Force -AllowClobber
```

### Anifetch

Source [here](https://github.com/Notenlish/anifetch)

```
winget install chafa ffmpeg fastfetch
```

```
pip install anifetch-cli
```

La animacion no se ejecuta en la terminal integrada de VS Code ni en sesiones de OpenSSH.

### Windows Terminal

Copiar `windows-terminal/settings.json` a:

```
%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
```

### Iconos:

```pwsh
Install-module -name terminal-icons -repository PSGallery
```

### Fonts:

```pwsh
  oh-my-posh font install Hack
```

Recomendadas:

- Hack mono
- Fira code mono
- Meslo
- Jetbrains

[more](https://www.nerdfonts.com/)

### VS-code settings:

```json
{
  "terminal.integrated.fontFamily": "Hack Nerd Font",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.lineHeight": 1.2
}
```
