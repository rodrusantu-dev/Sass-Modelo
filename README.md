# Arquitetura Sass - 7-1 - RODRUSANTU.DEV
## Visualizar em códigdo no VSCODE

scss/
|
|- base/
|   |- _base.scss         # Elementos Base do Projeto
|   |- _fonts.scss        # Tipos de Letra
|   |- _typography.scss   # Regras de Tipografia
|
|- components/
|   |- _buttons.scss      # Botões
|
|- global/
|   |- _reset.scss        # Reset do Projeto
|
|- layout/
|   |- _navigation.scss   # Navegação
|   |- _grid.scss         # Grelha
|   |- _header.scss       # Cabeçalho
|   |- _footer.scss       # Rodapé
|   |- _sidebar.scss      # Barra Lateral
|   |- _forms.scss        # Formulários
|
|- pages/
|   |- _home.scss         # Estilos específicos à página Inicial
|   |- _contact.scss      # Estilos específicos à página de Contacto
|
|- utils/
|   |- _functions.scss    # Funções
|   |- _helpers.scss      # Auxiliares de classes e placeholders
|   |- _mixins.scss       # Mixins
|   |- _variables.scss    # Variáveis
|
|- vendors/
|   |– _bootstrap.scss    # Bootstrap
|   |– _jquery-ui.scss    # jQuery UI
|   …                     # Etc.
|
`– main.scss              # Principal ficheiro de Sass

## Execução do arquivo - via Terminal VSCode com o Sass já instalado no projeto.
Transformando o arquivo **.scss** em **.css** para uso no HTML

```
sass main.scss style.css
```