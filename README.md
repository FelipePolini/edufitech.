 Trabalho TCC
 https://felipepolini.github.io/edufitech./frontend/front.html

  Trabalho TCC
 https://felipepolini.github.io/edufitech./frontend/front.html

Página Principal:

 1. Estrutura Básica
Cabeçalho (<head>)

Define o charset como UTF-8 e configura a viewport para responsividade.
Inclui o arquivo de estilo Front.css e um ícone de atalho.
Inclui o script front.js para funcionalidades JavaScript.
Corpo (<body>)

Contém a estrutura principal do site: imagem inicial, cabeçalho, conteúdo principal e rodapé.
2. Imagem Inicial
Div com classe intro-image
Mostra uma imagem de introdução com um título e uma legenda.
Inclui um link com a classe intro-scroll que, ao ser clicado, rola suavemente para a seção "Sobre Nós".
3. Cabeçalho (<header>)
Barra de navegação
Exibe o nome do site "EduFiTech" e um menu de navegação com links para diferentes seções da página:
Sobre Nós
Educação
Contato
Link para a página de login
Cada item do menu usa um botão estilizado e um link âncora para navegar até a seção correspondente.
4. Seção Principal (<main>)
Seção "Sobre Nós"

Inclui um vídeo com controles e uma descrição sobre a empresa.
Apresenta a missão e visão da EduFiTech.
Seção "Educação"

Exibe uma série de cartões (cards) com imagens e links para páginas relacionadas a diferentes tópicos de educação.
Cada cartão contém uma imagem, um título e um botão "Saber mais" que leva a uma página específica.
5. Rodapé (<footer>)
Informações de Contato
Exibe um endereço de e-mail clicável.
Inclui um botão com um ícone do GitHub que leva ao repositório do projeto.
6. Funcionalidades JavaScript
Scroll da Página

Adiciona uma classe ao botão de voltar ao topo quando o usuário rola para baixo.
Esconde a imagem inicial quando o usuário rola para baixo.
Define a função voltarTopo para rolar suavemente para o topo da página quando o botão de voltar ao topo é clicado.
Define a função que rola suavemente para a seção "Sobre Nós" quando o link de rolar para baixo é clicado.
Inclusão de Bibliotecas

Adiciona scripts para Popper.js e Bootstrap para suporte a funcionalidades adicionais, como pop-ups e componentes dinâmicos.

Resumo das Funcionalidades:

Imagem Inicial e Navegação:
Uma introdução visual com navegação suave.

Cabeçalho:
Navegação entre seções e acesso à página de login.

Conteúdo Principal:
Seções de informações e links para tópicos educativos.

Rodapé:
Informações de contato e link para o GitHub.

JavaScript:
Funções de rolagem e exibição dinâmica dos elementos.

Cursos de Aprendizagem:

Claro, aqui está um passo a passo das funcionalidades do código HTML fornecido para a página "Impostos":

1. Estrutura Básica
- Cabeçalho (`<head>`)**
  - Define o charset como UTF-8 e configura a viewport para responsividade.
  - Inclui o arquivo de estilo `pagina_imposto.css`.
  - Define o ícone de atalho e preconecta com as fontes do Google.
  - Adiciona o link para o Google Fonts para usar a fonte Roboto.
  - Define o título da página como "EduFiTech | Impostos".

- Corpo (`<body>`)**
  - Contém a estrutura principal da página, incluindo cabeçalho, conteúdo principal e rodapé.

2. Cabeçalho (`<header>`)
- Barra de navegação
  - Exibe o nome do site "EduFiTech" e um menu com botões:
    - Voltar: Leva o usuário de volta para a página principal (`front.html`).
    - **Entrar: Leva o usuário para a página de login (`login/index.html`).

3. Conteúdo Principal (`<main>`)
- Seção "Imposto"
  - Descrição Geral
    - Título da seção como "Imposto".
    - O que é imposto?**
      - Inclui um vídeo explicativo sobre impostos.
      - Texto explicativo sobre impostos no Brasil, dividido em categorias (Federais, Estaduais e Municipais) com detalhes sobre cada um.
    - Como pago meus impostos?**
      - Inclui outro vídeo explicativo sobre como declarar imposto de renda.
  - Quiz
    - Seção de quiz para testar o conhecimento do usuário sobre o conteúdo apresentado. (Detalhes do quiz são gerados dinamicamente pelo script `quiz.js`.)

4. Rodapé (`<footer>`)
- Informações de Contato
  - Exibe um endereço de e-mail clicável.
  - Inclui um botão com um ícone do GitHub que leva ao repositório do projeto.

5. Funcionalidades JavaScript
- Scroll da Página
  - Adiciona uma classe ao botão de voltar ao topo quando o usuário rola para baixo.
  - Define a função `voltarTopo` para rolar suavemente para o topo da página quando o botão de voltar ao topo é clicado.

- Inclusão de Bibliotecas
  - Adiciona scripts para Popper.js e Bootstrap para suporte a funcionalidades adicionais.
  - Inclui um script `quiz.js` para gerenciar o funcionamento do quiz na página.

Resumo das Funcionalidades:
1. Cabeçalho:
   - Navegação entre a página principal e a página de login.
2. Conteúdo Principal:
   - Informações sobre impostos, incluindo vídeos explicativos e uma seção de quiz.
3. Rodapé:
   - Informações de contato e link para o GitHub.
4. JavaScript:
   - Funções de rolagem e exibição dinâmica dos elementos.
   - Script adicional para o quiz.
