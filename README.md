# ⚾ Moneyball - Landing Page Temática

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Style-CSS3-blue?logo=css3&logoColor=white)
![UI/UX](https://img.shields.io/badge/Design-Responsive-purple)

> Uma Landing Page imersiva dedicada ao filme "Moneyball" (O Homem que Mudou o Jogo), demonstrando habilidades de estruturação de layout e design visual focado em entretenimento.

## 🎯 Motivação e Propósito

No desenvolvimento frontend, a capacidade de traduzir uma identidade visual artística (como a de um filme) para código é crucial. O propósito deste projeto foi criar um **Hotsite Promocional**.

Este repositório resolve o desafio de apresentar informações (sinopse, elenco, trailer) de forma atraente e organizada. O foco técnico foi exercitar o **CSS Layout** (Flexbox/Grid) para garantir que a estética do filme (cores, tipografia, imagens de fundo) fosse preservada em diferentes tamanhos de tela.

## 🖼️ Demonstração Visual



## 🛠️ Tecnologias Utilizadas

A stack é focada nos fundamentos da Web, garantindo leveza e compatibilidade:

* **[HTML5 Semântico](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Uso de tags apropriadas (`<header>`, `<section>`, `<article>`, `<footer>`) para SEO e acessibilidade.
* **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):**
    * **Backgrounds:** Manipulação de imagens de fundo e sobreposições (overlays) para dar o tom cinematográfico.
    * **Flexbox:** Alinhamento de cards de elenco e menus.
    * **Media Queries:** Adaptação do layout para dispositivos móveis (Responsividade).
* **Git:** Controle de versão.

## ✨ Funcionalidades

A página é estruturada como uma "Single Page" informativa contendo:

1.  **Hero Section:** Banner principal com destaque visual, título e Call to Action (CTA) ou Trailer.
2.  **Sinopse:** Seção de texto com tipografia legível e contrastante.
3.  **Galeria de Elenco:** Grid de imagens apresentando os atores principais.
4.  **Embed de Mídia:** Integração de vídeo (Trailer) via iframe (YouTube/Vimeo).
5.  **Design Responsivo:** O layout se ajusta fluidamente, empilhando elementos em telas menores (Mobile First).

## 📦 Instalação e Execução

Este é um projeto de site estático (`static site`), não exigindo compilação ou instalação de pacotes complexos.

### Pré-requisitos
* Um navegador web moderno (Chrome, Firefox, Edge, Safari).

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/_moneyball.git](https://github.com/DouglassenG/_moneyball.git)
    ```

2.  **Acesse o diretório:**
    ```bash
    cd _moneyball
    ```

3.  **Visualização:**
    * Localize o arquivo `index.html`.
    * Dê um duplo clique para abrir diretamente no seu navegador padrão.
    * *Dica:* Para uma experiência de desenvolvimento melhor, use a extensão "Live Server" do VS Code.

## 💻 Estrutura e Padrões

O código segue uma organização limpa, típica de projetos institucionais:

```text
_moneyball/
├── index.html       # Estrutura (Markup)
├── css/             # Folhas de estilo
│   └── style.css    # Estilização global e reset
├── img/             # Ativos visuais (Posters, fotos do elenco)
└── README.md        # Documentação
