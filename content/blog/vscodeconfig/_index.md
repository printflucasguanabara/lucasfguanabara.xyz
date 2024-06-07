---
title: "Minhas configurações do vscode"
summary: "Um VSCode mais minimalista, deixando apenas oque é importante!"
date: 2024-04-07
draft: false
tags: ["vscode","configs","settings.json","personalização"]
showDate : true
authors:
  - lucasfguanabara

howLikes: true

---

 [{{< icon "github" >}}  settings.json disponível em repositório](https://github.com/printflucasguanabara/vscode-settings)


> Um VSCode Minimalista, deixando apenas oque é importante!


Configurei umas das minhas ferramenta principais de trabalho de modo que removesse toda distração possível. Então te mostrarei algumas configurações que fiz, fique à vontade para copiar e adicionar ao seu [Visual Studio Code](https://code.visualstudio.com/).

O VSCode usa o arquivo settings.json para que os usuários personalizem vários aspectos do editor, adaptando-o ao seu fluxo de trabalho e preferências específicas. Voce pode acessar este arquivo  pressionando Control (Command no MacOS) + Shift + P para abrir o painel de comando, digite "settings" e selecione a opção Open User Settings (JSON).

Agora copie o codigo abaixo e cole nas suas settings, fique a vontade para mudar da forma que achar melhor.





## settings.json

```json

{
    // editor config
    "editor.formatOnSave": true,
    "editor.fontSize": 14,
    "editor.minimap.autohide": true,
    "editor.minimap.renderCharacters": true,
    "editor.cursorBlinking": "blink",
    "editor.cursorStyle": "line",
    "editor.codeLens": true,
    "editor.fontLigatures": true,
    "editor.lineHeight": 1.5,
    "editor.guides.indentation": true,
    "editor.guides.highlightActiveIndentation": true,
    "editor.fontFamily": "'Jetbrains Mono', monospace",
    "editor.folding": false,
    "editor.rulers": [
        100
    ],
    "editor.quickSuggestions": {
        "strings": true
    },
    // window config
    "workbench.activityBar.location": "top",
    "window.titleBarStyle": "custom",
    "window.openFilesInNewWindow": "on",
    "breadcrumbs.enabled": true,
    "workbench.sideBar.location": "left",
    // code preferences
    "editor.bracketPairColorization.enabled": true,
    "editor.matchBrackets": "always",
    "editor.parameterHints.enabled": true,
    "editor.autoClosingBrackets": "alw  ays",
    "editor.formatOnPaste": true,
    "editor.selectionHighlight": true,
    "prettier.useTabs": true,
    "prettier.tabWidth": 4,
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 1000,
    "files.trimTrailingWhitespace": true,
    "files.eol": "\n",
    "editor.showUnused": true,
    // extension config: code spell checker
    "cSpell.language": "en,pt,pt_BR",
    "cSpell.allowCompoundWords": true,
    "cSpell.enabledLanguageIds": [
        "go"
    ],
    // theme config
    "workbench.colorTheme": "One Monokai",
    "workbench.productIconTheme": "fluent-icons",
    "symbols.hidesExplorerArrows": true,
    "workbench.iconTheme": "vscode-jetbrains-icon-theme-2023-dark",
    // privacy
    "telemetry.telemetryLevel": "off",
    // search config
    "search.exclude": {
        "**/node_modules": true,
    },
    // terminal config
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.lineHeight": 1.5,
    "terminal.integrated.fontWeight": "300",
    "terminal.integrated.fontFamily": "'Jetbrains Mono', monospace",
    "tabnine.experimentalAutoImports": true,
    "cSpell.userWords": [
        "allocs",
        "bemobidev",
        "cmdline",
        "dimiro",
        "msisdn"
    ],
    // git
    "gitlens.currentLine.enabled": true,
    "gitlens.currentLine.uncommittedChangesFormat": "🚧 ${author} (${date}) - ${message}",
    "gitlens.blame.highlight.enabled": true,
    "gitlens.defaultDateFormat": "YYYY-MM-DD",
    "gitlens.defaultDateShortFormat": "MMM D, YYYY",
    "gitlens.defaultDateStyle": "relative",
    "gitlens.blame.avatars": true,
    "window.customTitleBarVisibility": "auto",
}

```

Para verificar se as configurações foram aplicadas corretamente, você pode fechar e reabrir o Visual Studio Code ou simplesmente recarregar a janela.


