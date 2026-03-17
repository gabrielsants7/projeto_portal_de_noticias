# Portal de Noticias

Pagina inicial de um portal de noticias desenvolvida com HTML e CSS, com foco em estruturacao semantica, organizacao de estilos e reproducao de um layout moderno de conteudo tecnologico.

## Sobre o projeto

Este projeto consiste na construção de uma landing page de portal de noticias com seções de destaque, notícias mais lidas, conteúdos sobre inteligência artificial e uma área lateral com publicidade e recomendações adicionais.

O objetivo foi praticar:

- Estruturação semântica com HTML
- Organização de estilos em multiplos arquivos CSS
- Uso de variáveis CSS
- Criação de grids e composição visual
- Posicionamento de elementos e sobreposição de conteúdo sobre imagens
- Construção de layout inspirado em prototipo no Figma

## Tecnologias utilizadas

- HTML5
- CSS3

## Estrutura do projeto

```bash
projeto_portal_de_noticias/
|-- assets/
|   |-- icons/
|   `-- images/
|-- styles/
|   |-- global.css
|   |-- header.css
|   |-- index.css
|   |-- sections.css
|   `-- utility.css
`-- index.html
```

## Organizacao dos estilos

- `global.css`: reset, variaveis, tipografia, container e estilos globais
- `utility.css`: classes utilitarias de grid, espacamento e tipografia
- `header.css`: estilos do cabecalho e menu de navegacao
- `sections.css`: estilos das secoes principais da pagina
- `index.css`: arquivo central de importacao dos estilos

## Funcionalidades da pagina

- Cabeçalho com navegação principal e secundária
- Seção de notícias em destaque
- Seção "Mais lidas da semana"
- Seção de destaques sobre inteligência artificial
- Area lateral com banner publicitário
- Seção "Viu isso aqui?" com noticias complementares

## Layout

A interface foi desenvolvida com foco em:

- Visual escuro
- Destaque para conteúdo editorial
- Cards com imagens e sobreposição de texto
- Distribuição em grid
- Hierarquia visual com tipografia e tags de categoria

## Como executar o projeto

Como este projeto utiliza apenas HTML e CSS, basta abrir o arquivo `index.html` no navegador.

Se preferir, voce tambem pode utilizar uma extensao como o Live Server no VS Code.

## Aprendizados

Durante o desenvolvimento deste projeto, foram praticados conceitos importantes de front-end, como:

- Separacao de responsabilidades entre arquivos de estilo
- Reutilizacao com classes utilitarias
- Estrutura semantica no HTML
- Construcao de layouts com CSS Grid
- Aplicacao de identidade visual com variaveis CSS

## Autor

Projeto desenvolvido por Ana.
