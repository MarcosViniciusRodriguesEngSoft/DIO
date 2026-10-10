# Desafio 03: Construindo a Página Inicial do YouTube com CSS Grid

Bem-vindo(a) ao terceiro desafio da Trilha de CSS da DIO! Neste desafio, você vai colocar a mão na massa e construir a página inicial do YouTube, colocando em prática todos os conceitos aprendidos, principalmente sobre **CSS Grid Layout**.

![Banner Trilha de CSS](assets/banner.png)

## 📝 Sobre o Desafio

Este projeto foi construído **do zero**, desde a estrutura HTML até a estilização CSS, aplicando os conhecimentos adquiridos ao longo da trilha. O objetivo foi recriar a interface da página inicial do YouTube, focando em:

- **CSS Grid Layout:** Utilizado para criar a estrutura principal da página (Sidebar + Grade de Vídeos) e a grade responsiva de cards de vídeos com `repeat(auto-fill, minmax(280px, 1fr))`.
- **Flexbox:** Utilizado dentro dos componentes (Header, Sidebar e cards) para alinhar ícones, avatares e textos de forma precisa.
- **Posicionamento:** Uso de `position: sticky` no cabeçalho e na Sidebar para que permaneçam fixos durante a rolagem.
- **Responsividade:** Criação de um `@media query` para adaptar o layout em telas menores, escondendo a Sidebar e reorganizando a grade de vídeos.
- **Organização de Arquivos:** Estrutura de pastas com `assets` para imagens, `index.html` e `style.css`.
- **Ícones SVG:** Uso de ícones vetoriais direto no HTML, fiéis ao protótipo do Figma, para a Sidebar e o Header.

[Link do Figma](https://www.figma.com/design/KknwioExyqKD3D2eSVFrcW/Desafio-Grid---DIO?node-id=1-130&t=qCFqcMUko2zvxsBq-0) contendo o protótipo do desafio para que você possa se basear.

*Observações: para aplicar os textos em gradiente, utilize a propriedade CSS `background-clip`, porém, para funcionar em alguns navegadores, é necessário utilizar a propriedade `-webkit-background-clip: text;`*