# FinControl — Landing Page de SaaS Financeiro (Protótipo)

Projeto front-end (estático) que apresenta o **FinControl**, um conceito de plataforma SaaS para **gestão financeira + projetos + equipe** em um único ambiente.

A página foi construída no formato de **landing page** (apresentação de produto), com seções de valor, prova social, planos e uma área de **demonstração visual** via abas (Dashboard, Financeiro, Projetos, Equipe e Relatórios). Todo o conteúdo é **mock (dados fictícios)**, focado em UI/UX e apresentação.

---

## Objetivo

- Servir como **apresentação do produto** (pitch/marketing) e vitrine visual.
- Demonstrar uma **experiência de navegação fluida** (scroll suave, cards com hover, animações de entrada).
- Simular, de forma visual, como seria um sistema de gestão integrado.

---

## Principais seções da página

- **Navbar** fixa com navegação por âncoras.
- **Hero** com proposta de valor e CTA.
- **Problemas/Dores** comuns de gestão (financeiro, equipe e projetos).
- **Solução** (gestão unificada + SaaS na nuvem + decisões por dados).
- **Funcionalidades** em **abas interativas**:
  - Dashboard (KPIs, gráficos e atividades recentes)
  - Financeiro (tabela de transações)
  - Projetos (cards de status/progresso)
  - Equipe (membros, produtividade e status)
  - Relatórios (KPIs e indicadores)
- **Depoimentos** (prova social simulada).
- **Planos** (gratuito, pro e premium).
- **CTA final** e **rodapé**.

---

## Tecnologias utilizadas

- **HTML5**
- **CSS3** (arquivo próprio + utilitários)
- **Tailwind CSS (CDN)**
- **JavaScript (Vanilla)**
  - Abas interativas (tabs)
  - Scroll suave para âncoras
  - Animações ao entrar no viewport (IntersectionObserver)
- **Font Awesome** (ícones via CDN)
- **Google Fonts — Inter**

> Observação: como Tailwind e ícones são carregados por CDN, é necessário estar com **internet** para visualizar exatamente como no desenvolvimento.

---

## Estrutura do projeto

- `index.html` — Página principal (landing page completa + abas e scripts)
- `style.css` — Estilos complementares (hover, botões, tabs, animações)
- `tst.html` — Versão alternativa/rascunho (layout semelhante, com estilos inline)

---

## Como executar

### Opção 1 — Abrir direto no navegador

1. Abra o arquivo `index.html` no navegador (Chrome/Edge/Firefox).

### Opção 2 — VS Code (recomendado)

1. Instale a extensão **Live Server** no VS Code.
2. Clique com o botão direito em `index.html` → **Open with Live Server**.

---

## Notas e limitações (por ser protótipo)

- Não há back-end, banco de dados ou autenticação.
- Os valores, gráficos e listas são **estáticos** (mock) e servem apenas para demonstração.
- Algumas partes do texto/branding podem aparecer como **FinControl** e **FinanSys** (conteúdo de demonstração).

---

## Próximos passos (se virar produto)

- Transformar as abas em telas reais (SPA) com roteamento.
- Persistência de dados (API + banco).
- Login/controle de acesso (RBAC).
- Painéis e relatórios dinâmicos.

---

## Autor / Contexto acadêmico

Projeto desenvolvido com fins **acadêmicos** para apresentar a ideia de um SaaS de gestão (FinControl).

Se você quiser, eu também posso:
- adicionar screenshots na pasta `assets/` e referenciar aqui,
- padronizar o nome FinControl/FinanSys no HTML,
- ou converter para um projeto com build (Tailwind via npm/Vite).
