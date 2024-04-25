Customização de Temas e Cores no Visual Studio Code
O Visual Studio Code oferece uma variedade de opções para personalizar temas e cores de acordo com suas preferências. 
Esta documentação fornece instruções sobre como realizar essas personalizações.

Personalização de Temas

Pressione Ctrl + , (ou Cmd + , no macOS) para abrir as configurações do usuário.
No canto superior direito, clique no ícone de engrenagem e selecione "Settings".
Na barra de pesquisa, digite "workbench.colorCustomizations" para encontrar as configurações de personalização de cores.
Clique em "Edit in settings.json" para abrir o arquivo settings.json.
Adicione ou modifique as configurações de personalização de cores conforme desejado. Por exemplo:
Exemplo:
"workbench.colorCustomizations": {
        // Personalização das cores do ambiente de trabalho do VS Code
        "activityBar.background": "#3a3f4b",
        // Cor de fundo da barra de atividades
        "activityBar.foreground": "#c7c7c7",
        // Cor do texto e ícones da barra de atividades
        "activityBar.inactiveForeground": "#9ca1b2",
        // Cor do texto e ícones inativos da barra de atividades
        "sideBar.background": "#2f3440",
}
Salve o arquivo settings.json.
Exemplos de Customização de Cores
"activityBar.background": Cor de fundo da barra de atividades.
"activityBar.foreground": Cor do texto da barra de atividades.
"editor.background": Cor de fundo do editor de texto.
"editor.foreground": Cor do texto no editor de texto.
Reinício do Visual Studio Code
Após realizar as personalizações, você pode precisar reiniciar o Visual Studio Code para que as alterações tenham efeito.
