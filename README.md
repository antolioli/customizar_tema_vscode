Customização de Temas e Cores no Visual Studio Code<br>
O Visual Studio Code oferece uma variedade de opções para personalizar temas e cores de acordo com suas preferências. <br>
Esta documentação fornece instruções sobre como realizar essas personalizações.<br>

Personalização de Temas<br><br>

Pressione Ctrl + , (ou Cmd + , no macOS) para abrir as configurações do usuário.<br>
No canto superior direito, clique no ícone de engrenagem e selecione "Settings".<br>
Na barra de pesquisa, digite "workbench.colorCustomizations" para encontrar as configurações de personalização de cores.<br>
Clique em "Edit in settings.json" para abrir o arquivo settings.json.<br>
Adicione ou modifique as configurações de personalização de cores conforme desejado. Por exemplo:<br>
<br>
Exemplo:<br>
<br>
"workbench.colorCustomizations": {<br>
        - Item 1:// Personalização das cores do ambiente de trabalho do VS Code<br>
       - Item 1: "activityBar.background": "#3a3f4b",<br>
       - Item 1: // Cor de fundo da barra de atividades<br>
       - Item 1: "activityBar.foreground": "#c7c7c7",<br>
       - Item 1: // Cor do texto e ícones da barra de atividades<br>
       - Item 1: "activityBar.inactiveForeground": "#9ca1b2",<br>
       - Item 1: // Cor do texto e ícones inativos da barra de atividades<br>
       - Item 1: "sideBar.background": "#2f3440",<br>
}
<br>
<br>
Salve o arquivo settings.json.<br>
Reinício do Visual Studio Code<br>
Após realizar as personalizações, você pode precisar reiniciar o Visual Studio Code para que as alterações tenham efeito.
