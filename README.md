# 💇‍♀️ Blog Prohair - Template Moderno

Um template de blog moderno e responsivo, desenvolvido em HTML, CSS e JavaScript puro, inspirado em uma estética elegante e minimalista com toques de **Glassmorphism**.

Este projeto simula a página inicial de um blog de beleza e cuidados capilares, com foco na usabilidade e na experiência fluida do usuário.

## ✨ Destaques do Projeto

* **Design Glassmorphism:** Utiliza `backdrop-filter: blur()` na barra de navegação (`nav`) e no rodapé (`footer-glass`) para um visual contemporâneo de "vidro líquido".
* **Carrossel de Posts Responsivo:** Exibe os posts em um layout de grid adaptável, com um efeito de *hover* atraente (`transform: scale(1.10)`).
* **Navegação Inteligente:** Menu de navegação fixo com efeito *glass*, adaptando-se perfeitamente para dispositivos móveis com um menu *hamburger* e transição suave.
* **Rodapé Completo (Footer Glass):** Apresenta informações detalhadas, tags, posts recentes e ícones de mídias sociais, todos dispostos em um layout de grid.

## 🚀 Tecnologias Utilizadas

| Categoria | Tecnologia | Detalhes |
| :--- | :--- | :--- |
| **Estrutura** | HTML5 | Semântica e organização do conteúdo. |
| **Estilização** | CSS3 | Estilos modernos, `flexbox`, `grid`, `media queries` (Responsividade). |
| **Interatividade** | JavaScript Vanilla | Função `toggleMenu()` para o menu mobile. |
| **Design UI** | Glassmorphism | Utilizado em `nav` e `footer`. |

## 📐 Estrutura do Código

O projeto é dividido em seções claras:

1.  **`<head>` e `<style>`:** Contém metadados, o link para a fonte 'Poppins' e todo o CSS incorporado, incluindo a estilização de **Mobile-First** com a regra `@media (max-width: 768px)`.
2.  **`<nav>`:** Barra de navegação fixa, dividida em logo, menu desktop e menu mobile (hambúrguer).
3.  **`<section class="hero">`:** Título principal e descrição do blog.
4.  **`<section class="carousel">`:** Contêiner dos posts do blog, utilizando **CSS Grid** para layout.
5.  **`<section class="social">`:** Chamada para a loja oficial.
6.  **`<footer class="footer-glass">`:** Rodapé multi-coluna (também usando **CSS Grid**), com informações, links e redes sociais.
7.  **`<script>`:** Script simples para controlar a abertura/fechamento do menu mobile.

## 📱 Responsividade (Mobile-First)

O layout foi otimizado para uma visualização perfeita em qualquer dispositivo, priorizando a experiência móvel:

* **Menu Hamburger:** O menu principal (`.desktop-menu`) é ocultado em telas menores que `768px`, sendo substituído pelo menu mobile (`.mobile-menu`) com a função JavaScript `toggleMenu()`.
* **Layout Adaptável:** As seções de posts (`.carousel`) e o rodapé (`.footer-container`) utilizam `grid-template-columns: repeat(auto-fit, minmax(Xpx, 1fr))` para garantir que as colunas se ajustem dinamicamente ao tamanho da tela.

## 🛠️ Como Executar

1.  Salve o código HTML em um arquivo chamado `index.html`.
2.  Abra o arquivo `index.html` em qualquer navegador da web.

> **Nota:** As imagens e logos são carregadas a partir de URLs externas (`https://...`), garantindo que o projeto funcione imediatamente sem a necessidade de baixar arquivos de imagem adicionais.

---

## 🔗 Estrutura de Links

Os links de navegação e rodapé direcionam para as seguintes categorias principais:

* **Categorias:** Coloração, Cortes de Cabelo, Tendências, Tratamentos.
* **Contato:** Link direto para o WhatsApp da Prohair.
* **Loja:** Link para o site oficial `https://prohair.com.vc/`.

## 📜 Licença

Este template é de uso livre para estudos e adaptações. NÃO COPIE!
