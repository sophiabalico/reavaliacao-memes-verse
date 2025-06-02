# MemeVerse - Reavaliação

## Descrição do Projeto

O MemeVerse é uma plataforma web para compartilhar, explorar e interagir com memes de diversas categorias. O projeto foi desenvolvido em React, com componentes modulares e estilização via CSS Modules, proporcionando uma experiência moderna e responsiva.

---

## Instruções de Instalação e Execução

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/sophiabalico/reavaliacao-memes-verse.git
   cd reavaliacao-memes-verse
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Execute o projeto:**
   ```bash
   npm run dev

O projeto estará disponível em `http://localhost:3000`.

---

## Descrição dos Componentes Criados

- **Header:** Barra de navegação principal do site.
- **Footer:** Rodapé com informações e links úteis.
- **HeroSection:** Destaque do meme do dia, com informações do autor e interações.
- **CategoriesSection:** Exibição das categorias de memes disponíveis.
- **Feed:** Lista dos memes populares, com filtros e botão de carregar mais.
- **MemeCard:** Card individual para cada meme, mostrando imagem, autor, categoria e interações.
- **InteractionBar:** Barra de interações (curtir, comentar, compartilhar, salvar) para cada meme.
- **Sidebar:** Área lateral com eventos próximos, plano premium e tags populares.
- **EventCard:** Card individual para eventos exibidos na sidebar.
- **FeaturedMemesSection:** Sessão de memes em destaque.
- **CreatorSection:** Destaque para criadores de memes.
- **NewsLetterSection:** Seção para inscrição na newsletter.

---

## Decisões de Design Tomadas

- **Componentização:** O projeto foi dividido em componentes reutilizáveis para facilitar manutenção e escalabilidade.
- **CSS Modules:** Utilizado para garantir o escopo local dos estilos e evitar conflitos.
- **Props e Tipagem:** Os dados são passados via props, permitindo flexibilidade e reutilização dos componentes.
- **Responsividade:** O layout foi pensado para funcionar bem em diferentes tamanhos de tela.
- **Separação de Dados:** Os dados de memes, eventos e categorias são mantidos em arrays separados, facilitando futuras integrações com APIs.

---

## Desafios Enfrentados e Soluções Aplicadas

- **Tive dificuldade em aplicar props durante o andamento do projeto**