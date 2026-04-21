# ✂️ Estilo Livre — Barbearia

Site institucional responsivo da barbearia fictícia **Estilo Livre**, desenvolvido como projeto prático do módulo de front-end com foco em Bootstrap 5 e boas práticas de desenvolvimento web.

---

## 🖥️ Preview

> Site disponível via Live Server em ambiente local.

---

## 🚀 Tecnologias utilizadas

| Tecnologia | Versão | Finalidade |
|---|---|---|
| HTML5 | — | Estrutura semântica |
| CSS3 | — | Estilização e animações |
| Bootstrap | 5.3.8 | Grid, componentes e responsividade |
| Google Fonts | — | Tipografia (Oswald + Open Sans) |

---

## 📁 Estrutura do projeto

```
estilo-livre/
│
├── index.html          # Página principal
├── README.md           # Documentação do projeto
│
├── css/
│   └── style.css       # Estilos customizados
│
└── img/
    ├── home__img.jpg    # Imagem do hero
    ├── estilo-livre.jpg # Imagem da seção Sobre Nós
    ├── rafael.jpg       # Avatar depoimento 1
    ├── lucas.jpg        # Avatar depoimento 2
    └── bruno.jpg        # Avatar depoimento 3
```

---

## 📄 Seções do site

- **Navbar** — Menu responsivo com hamburguer em mobile, fixo no topo com `sticky-top`
- **Hero** — Banner com imagem de fundo, overlay escuro e chamada de ação
- **Sobre Nós** — Layout em duas colunas com imagem e números de impacto
- **Serviços** — Grid de cards responsivo com efeito hover
- **Depoimentos** — Carrossel automático com controles manuais
- **Contato** — Formulário com validação HTML5 nativa
- **Footer** — Três colunas com informações da barbearia

---

## 🎨 Identidade visual

| Elemento | Valor |
|---|---|
| Cor primária | `#1a1a1a` (preto grafite) |
| Cor de destaque | `#c8a96e` (dourado) |
| Fonte de título | Oswald (400, 600, 700) |
| Fonte de corpo | Open Sans (400, 500) |

---

## 📱 Responsividade

O projeto foi desenvolvido com a abordagem **mobile-first**, utilizando o sistema de grid do Bootstrap 5.

| Breakpoint | Layout |
|---|---|
| `< 576px` | 1 coluna — mobile |
| `≥ 576px` | 2 colunas — tablet pequeno |
| `≥ 768px` | 2 colunas — tablet |
| `≥ 992px` | 3 colunas — desktop |

---

## ✨ Destaques técnicos

- **Overlay via `::before`** — pseudo-elemento CSS para overlay do hero sem markup extra
- **Efeito parallax** — `background-attachment: fixed` no hero em desktop
- **Animação fill radial** — hover do botão principal com expansão circular via `::before`
- **Scroll suave** — `scroll-behavior: smooth` e `scroll-margin-top` para navegação por âncoras
- **Lazy loading** — `loading="lazy"` nas imagens fora da dobra inicial
- **Variáveis CSS** — paleta e tipografia centralizadas em `:root`
- **Nomenclatura BEM** — classes organizadas com padrão `bloco__elemento`

---

## ⚙️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/lucassloliveira/estilo-livre.git
```

2. Abra o projeto no VSCode e instale a extensão **Live Server**

3. Clique em **"Go Live"** na barra inferior do VSCode

4. O site abrirá automaticamente em `http://127.0.0.1:5500`

> Não é necessário instalar dependências — Bootstrap e Google Fonts são carregados via CDN.

---

## 📚 Aprendizados aplicados

- Estrutura semântica com HTML5 (`main`, `section`, `header`, `footer`, `blockquote`, `figcaption`)
- Sistema de Grid do Bootstrap com breakpoints mobile-first
- Componentes Bootstrap: Navbar, Cards, Carousel, Forms
- Pseudo-elementos CSS (`::before`) para efeitos visuais
- Hierarquia visual com tipografia e espaçamento
- Debugging metódico de HTML e CSS
- Boas práticas de acessibilidade (`aria-label`, `alt`, `lang`, `role`)
- SEO básico com `meta description` e `title` descritivo

---

## 👨‍💻 Autor

Desenvolvido como projeto prático do curso de front-end.

---

## 📝 Licença

Este projeto é fictício e desenvolvido para fins educacionais.
