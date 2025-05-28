# Projeto Google Glass - Site de Especificações

Este projeto é um site estático que apresenta informações, especificações e uma galeria de fotos sobre o Google Glass, utilizando HTML, CSS e JavaScript para uma navegação interativa.

---

## Estrutura do Projeto

- **HTML**  
  O arquivo principal é o `specs.html`, que contém a estrutura do site com um cabeçalho, menu de navegação, área de conteúdo com mapa de imagem clicável e um iframe para exibição de detalhes.  
  Também há páginas adicionais (como `google-glass.html`) que apresentam informações específicas ao clicar nas áreas do mapa.

- **CSS**  
  Os estilos estão divididos em arquivos separados:
  - `_css/estilo.css` - Estilos gerais do site, incluindo fonte, cabeçalho, menu, layout, tabelas e rodapé.
  - `_css/specs.css` - Estilos específicos para a página de especificações, incluindo o layout do conteúdo principal e iframe.
  - Outros estilos para formulários, galerias de fotos e mídia (áudio e vídeo).

- **JavaScript**  
  O arquivo `_javascript/funcoes.js` controla a troca dinâmica da imagem no cabeçalho conforme o usuário passa o mouse sobre os itens do menu.

---

## Funcionalidades

- **Menu interativo**  
  O menu principal muda a imagem do cabeçalho quando o usuário passa o mouse sobre as opções, melhorando a experiência visual.

- **Mapa de imagem**  
  A imagem do Google Glass contém áreas clicáveis que carregam conteúdos específicos no iframe à direita, permitindo navegação sem sair da página.

- **Galeria de fotos**  
  A galeria apresenta miniaturas que aumentam e exibem legendas ao passar o mouse, usando transições CSS suaves.

- **Formulário personalizado**  
  Os formulários contam com estilos visuais para diferentes fieldsets, com ícones e interações ao focar nos campos.

- **Suporte a mídia**  
  Inclui players de áudio e vídeo posicionados com CSS para complementar o conteúdo da página.

---

## Tecnologias Utilizadas

- HTML5
- CSS3 (incluindo @font-face, transições e posicionamento)
- JavaScript (simples para troca de imagens)
- Fontes externas do Google Fonts
- Recursos visuais e ícones em arquivos locais (`_imagens` e `_fonts`)
