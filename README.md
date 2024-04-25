<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>

<h1>Temas e Cores no Visual Studio Code</h1>

<p>O Visual Studio Code oferece uma variedade de opções para personalizar temas e cores de acordo com suas preferências.</p>

<p>Esta documentação fornece instruções sobre como realizar essas personalizações.</p>

<h2>Personalização de Temas</h2>

<p>Pressione Ctrl + , (ou Cmd + , no macOS) para abrir as configurações do usuário.<br>
No canto superior direito, clique no ícone de engrenagem e selecione "Settings".<br>
Na barra de pesquisa, digite "workbench.colorCustomizations" para encontrar as configurações de personalização de cores.<br>
Clique em "Edit in settings.json" para abrir o arquivo settings.json.<br>
Adicione ou modifique as configurações de personalização de cores conforme desejado. Veja:</p>
<pre>
"workbench.colorTheme": "GitHub Dark",

    "workbench.colorCustomizations": {
        // Personalização das cores do ambiente de trabalho do VS Code
        "activityBar.background": "#3a3f4b",
        // Cor de fundo da barra de atividades
        "activityBar.foreground": "#c7c7c7",
        // Cor do texto e ícones da barra de atividades
        "activityBar.inactiveForeground": "#9ca1b2",
        // Cor do texto e ícones inativos da barra de atividades
        "sideBar.background": "#2f3440",
        // Cor de fundo da barra lateral
        "sideBarSectionHeader.background": "#2a2f3e",
        // Cor de fundo do cabeçalho da seção da barra lateral
        "sideBar.foreground": "#c7c7c7",
        // Cor do texto da barra lateral
        "terminal.background": "#2f3440",
        // Cor de fundo do terminal
        "terminalSectionHeader.background": "#2a2f3e",
        // Cor de fundo do cabeçalho da seção do terminal
        "titleBar.activeBackground": "#2a2f3e",
        // Cor de fundo da barra de título ativa
        "dropdown.background": "#2a2f3e",
        // Cor de fundo do menu suspenso
        "dropdown.listBackground": "#2a2f3e",
        // Cor de fundo da lista do menu suspenso
        "dropdown.border": "#2a2f3e",
        // Cor da borda do menu suspenso
        "dropdown.foreground": "#c7c7c7",
        // Cor do texto do menu suspenso
        "titleBar.activeForeground": "#c7c7c7",
        // Cor do texto da barra de título ativa
        "input.background": "#2a2f3e",
        // Cor de fundo do campo de entrada
        "panel.background": "#2a2f3e",
        // Cor de fundo do painel
        "panel.border": "#5c677e",
        // Cor da borda do painel
        "panelTitle.activeBorder": "#5c677e",
        // Cor da borda do título do painel ativo
        "panelTitle.inactiveForeground": "#9ca1b2",
        // Cor do texto do título do painel inativo
        "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
        // Fonte do editor de código
        "editor.fontSize": 14,
        // Tamanho da fonte do editor de código
        "editor.fontWeight": "400",
        // Peso da fonte do editor de código
        "editor.lineHeight": 24,
        // Altura da linha do editor de código
        "editor.letterSpacing": 0.5,
        // Espaçamento entre letras do editor de código
        "editor.tabSize": 2,
        // Tamanho da tabulação do editor de código
        "editor.wordWrap": "on",
        // Quebra de linha automática no editor de código
        "editor.cursorStyle": "line",
        // Estilo do cursor do editor de código
        "editor.cursorWidth": 2,
        // Largura do cursor do editor de código
        "editor.cursorBlinking": "solid",
        // Piscar do cursor do editor de código
        "editor.renderWhitespace": "none",
        // Renderizar espaços em branco no editor de código
        "editor.minimap.enabled": false,
        // Habilitar minimapa no editor de código
        "editor.scrollbar.vertical": "auto",
        // Aparência da barra de rolagem vertical do editor de código
        "editor.scrollbar.horizontal": "auto",
        // Aparência da barra de rolagem horizontal do editor de código
        "editor.scrollbar.verticalScrollbarSize": 10,
        // Tamanho da barra de rolagem vertical do editor de código
        "editor.scrollbar.horizontalScrollbarSize": 10,
        // Tamanho da barra de rolagem horizontal do editor de código
        "editor.renderIndentGuides": false,
        // Renderizar guias de recuo no editor de código
        "editor.renderControlCharacters": false,
        // Renderizar caracteres de controle no editor de código
        "editor.snippetSuggestions": "top",
        // Sugestões de fragmentos de código no topo do editor de código
        "editor.formatOnSave": true,
        // Formatar automaticamente no salvamento do editor de código
        "editor.formatOnType": true,
        // Formatar automaticamente durante a digitação no editor de código
        "editor.rulers": [80, 120],
        // Exibir régua no editor de código
        "editor.showFoldingControls": "mouseover",
        // Exibir controles de dobragem ao passar o mouse no editor de código
        "editor.matchBrackets": "always",
        // Realçar parênteses correspondentes no editor de código
        "editor.lineNumbers": "on",
        // Exibir números de linha no editor de código
        "editor.codeLens": true,
        // Exibir lentes de código no editor de código
        "editor.background": "#282c34",
        // Cor de fundo do editor de código
        "editor.foreground": "#abb2bf",
        // Cor do texto do editor de código
        "editor.selectionBackground": "#3e4451",
        // Cor de fundo da seleção de texto no editor de código
        "editor.lineHighlightBackground": "#2c313a",
        // Cor de fundo do destaque de linha no editor de código
        "editor.lineHighlightBorder": "#282c34",
        // Cor da borda do destaque de linha no editor de código
        "editorIndentGuide.background1": "#abb2bf",
        // Cor de fundo da guia de recuo no editor de código
        "editorIndentGuide.activeBackground1": "#FFFFFF00"
        // Cor de fundo da guia de recuo ativa no editor de código
    },

  "editor.semanticTokenColorCustomizations": {},
  
  "editor.tokenColorCustomizations": {  // Personalização das cores dos tokens no editor
  "textMateRules": [  // Regras TextMate para definir a aparência de diferentes tipos de tokens
      {
          "scope": [  // Escopo da regra
              "keyword"  // Palavras-chave
          ],
          "settings": {
             "foreground": "#fca3f9",  // Cor do texto para palavras-chave
             "fontStyle": ""  // Deixar o texto em negrito
        }
      },
      {
        "scope": ["variable", "entity.name.variable"],
        "settings": {
            "foreground": "#8adbf3", // Cor do texto para variáveis
            "fontStyle": "italic",   // Estilo da fonte
            //"fontWeight": "normal",  // Peso da fonte
            //"fontSize": "14px",      // Tamanho da fonte
            //"fontFamily": "Arial, sans-serif" // Família da fonte
        }
      },
      {
          "scope": [  // Escopo da regra
              "constant"  // Constantes
          ],
          "settings": {  // Configurações para este escopo
              "foreground": "#f0a56c",  // Cor do texto para constantes
              "fontStyle": "italic"  // Deixar o texto em negrito
          }
      },
      {
          "scope": [  // Escopo da regra
              "string"  // Strings
          ],
          "settings": {  // Configurações para este escopo
              "foreground": "#84bb73"  // Cor do texto para strings
          }
      },
      {
          "scope": [  // Escopo da regra
              "numeric"  // Números
          ],
          "settings": {  // Configurações para este escopo
              "foreground": "#653a44"  // Cor do texto para números
          }
      },
      {
          "scope": [  // Escopo da regra
              "comment",  // Comentários
              "punctuation.definition.comment"  // Pontuação que define comentários
          ],
          "settings": {  // Configurações para este escopo
              "foreground": "#5a5c5f"  // Cor do texto para comentários
          }
      },
      {
        "scope": [
            "storage.type", // Tipo de armazenamento (por exemplo, int, float, bool)
        ],
        "settings": {
            "foreground": "#cc2378",// Cor do texto para tipos de armazenamento
            "fontStyle": ""
        }
    },
    {
        "scope": [
            "support.type", // Tipos de suporte (por exemplo, std::string, std::vector)
        ],
        "settings": {
            "foreground": "#097409" // Cor do texto para tipos de suporte
        }
    },
    {
        "scope": [
            "entity.name", // Nomes de funções
        ],
        "settings": {
            "foreground": "#f8d28d", // Cor do texto para nomes de funções
            "fontStyle": ""
        }
    },
    {
        "scope": [
            "function", // Nomes de funções
        ],
        "settings": {
            "foreground": "#f50000", // Cor do texto para nomes de funções
            "fontStyle": ""
        }
    },
  ]
},
</pre>

<p>Salve o arquivo settings.json.</p>

<h2>Reinicie o VSCode</h2>

<p>Após realizar as personalizações, pode precisar reiniciar o VSCode para que as alterações tenham efeito.</p>

</body>
</html>

