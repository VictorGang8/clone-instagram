# 📸 Clone Instagram — Instadev

Projeto front-end que reproduz a interface visual de uma página inicial do Instagram, desenvolvido para praticar estruturação de páginas, estilização responsiva e organização de código com HTML, CSS e JavaScript.

O projeto apresenta uma interface inspirada no feed do Instagram, com área de stories, publicações, navegação e sugestões de perfis.

## 🎯 Objetivo do projeto

O objetivo é desenvolver uma página web que simule a experiência visual de navegação pelo Instagram e consolidar conhecimentos de desenvolvimento front-end, especialmente:

- Estruturação semântica de páginas com HTML5;
- Estilização e organização visual com CSS3;
- Criação de layouts responsivos com media queries;
- Manipulação do DOM e eventos com JavaScript;
- Organização de arquivos em pastas para facilitar a manutenção.

## ✨ Funcionalidades e elementos da interface

- **Cabeçalho:** exibe a identidade visual e ícones de navegação em telas menores.
- **Menu lateral:** apresenta opções de navegação, como Página inicial, Pesquisa, Explorar e Reels.
- **Stories:** exibe avatares e nomes de perfis em uma faixa horizontal.
- **Navegação dos stories:** botões laterais avançam ou retornam a faixa de stories com rolagem suave.
- **Feed de publicações:** apresenta exemplos de posts com avatar, imagem, ícones de interação, curtidas, comentários e data.
- **Barra lateral:** mostra informações do perfil e sugestões de contas.
- **Navegação inferior:** disponibiliza ícones de acesso rápido em telas menores.
- **Layout responsivo:** adapta a disposição dos elementos conforme a largura da tela.
- **Tema claro e escuro:** acompanha a preferência de aparência configurada no sistema operacional/navegador.

> **Observação:** esta é uma reprodução visual para fins de estudo. Os ícones de curtir, comentar, compartilhar, salvar, seguir e os links de navegação são elementos de interface; não representam, nesta versão, funcionalidades conectadas a um servidor ou a uma conta real do Instagram. A interação JavaScript implementada nesta versão é a rolagem horizontal dos stories.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo da página;
- **CSS3** — layout, componentes visuais, responsividade e tema;
- **JavaScript** — manipulação do DOM e rolagem dos stories;
- **SVG** — ícones vetoriais da interface.

## 📁 Estrutura do projeto

```text
clone-instagram/
├── index.html
└── assets/
    ├── css/
    │   ├── base.css
    │   ├── header.css
    │   ├── main.css
    │   ├── aside.css
    │   ├── footer.css
    │   ├── feed.css
    │   └── stories.css
    ├── js/
    │   └── script.js
    └── images/
        ├── avatars/
        └── feed/
```

## ▶️ Como executar o projeto

Não é necessário instalar dependências ou configurar um servidor.

1. Faça o clone do repositório:

   ```bash
   git clone https://github.com/VictorGang8/clone-instagram.git
   ```

2. Acesse a pasta:

   ```bash
   cd clone-instagram
   ```

3. Abra o arquivo `index.html` no navegador.

Você também pode abrir a pasta no Visual Studio Code e executar o projeto com a extensão **Live Server**, caso prefira visualizar as alterações automaticamente durante o desenvolvimento.

## 📚 Aprendizados

Este projeto permite praticar:

- Separação de responsabilidades entre HTML, CSS e JavaScript;
- Organização de estilos por componentes da interface;
- Uso de Flexbox e media queries;
- Uso de variáveis CSS e preferências de tema;
- Seleção de elementos e tratamento de eventos no JavaScript;
- Criação de uma interface adaptável para diferentes tamanhos de tela.

## ⚠️ Aviso

Este projeto é independente, desenvolvido para fins educacionais e de portfólio. Não possui vínculo com a Meta ou com o Instagram e não utiliza serviços, APIs, autenticação ou dados reais dessas plataformas. Marcas e referências visuais pertencem aos seus respectivos proprietários.

## 👨‍💻 Autor

**Victor Gabriel**

- GitHub: [@VictorGang8](https://github.com/VictorGang8)

---

Desenvolvido para fins de estudo e prática de desenvolvimento front-end.
