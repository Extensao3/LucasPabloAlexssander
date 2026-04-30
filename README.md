<p align="center">
  <img src="https://img.shields.io/badge/status-protótipo-blue?style=for-the-badge&logo=figma">
  <img src="https://img.shields.io/badge/licença-acadêmica-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/HTML5-Tailwind-38B2AC?style=for-the-badge&logo=tailwindcss">
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript">
</p>

<h1 align="center">💰 FinControl — Landing Page de SaaS Financeiro</h1>

<p align="center">
  <strong>Um ambiente unificado para gestão financeira, projetos e equipe.</strong><br/>
  Protótipo front-end estático com foco em UI/UX, animações e experiência de navegação fluida.
</p>

<p align="center">
  <a href="#demo">📱 Demonstração</a> •
  <a href="#seções">📌 Seções</a> •
  <a href="#tecnologias">🛠️ Tecnologias</a> •
  <a href="#como-executar">🚀 Como executar</a> •
  <a href="#próximos-passos">🔮 Próximos passos</a>
</p>

<br/>

---

## 🖼️ Preview

<p align="center">
  <img src="assets/preview.png" alt="Preview do FinControl" width="800" style="border-radius: 16px; box-shadow: 0 8px 20px rgba(0,0,0,0.1);">
</p>

> 💡 *Se ainda não tem uma screenshot, você pode adicionar depois em `assets/preview.png`*

---

## 🎯 Objetivo do Projeto

Servir como **vitrine visual** e **pitch de produto** para o **FinControl** — uma plataforma SaaS que integra:

- 📊 **Dashboard** com KPIs e gráficos  
- 💰 **Financeiro** com controle de transações  
- 📁 **Projetos** com status e progresso  
- 👥 **Equipe** com produtividade e membros  
- 📈 **Relatórios** inteligentes  

> Tudo em **um só lugar**, com dados **mockados** (fictícios) para demonstração de UI/UX.

---

## 📌 Seções da Landing Page

| Seção | Descrição |
|-------|-----------|
| **Hero** | Proposta de valor + CTA principal |
| **Problemas** | Dores comuns (financeiro isolado, equipe desalinhada, projetos perdidos) |
| **Solução** | Gestão unificada, nuvem, decisões baseadas em dados |
| **Funcionalidades (abas)** | Dashboard / Financeiro / Projetos / Equipe / Relatórios — com conteúdo visual interativo |
| **Depoimentos** | Prova social com cards de clientes fictícios |
| **Planos** | Gratuito / Pro / Premium — com preços e benefícios |
| **Rodapé** | Links institucionais e informações de contato |

---

## 🧪 Demonstração das Abas

As abas simulam a experiência de um sistema real:

- **Dashboard** → KPIs, gráfico de receitas x despesas, atividades recentes  
- **Financeiro** → Tabela de transações com valores, categorias e status  
- **Projetos** → Cards com andamento, prazo e responsável  
- **Equipe** → Lista de membros, cargo, produtividade (barra de progresso)  
- **Relatórios** → Indicadores sintéticos de performance  

> 📌 *Tudo é estático e visual — ideal para apresentações e validação de conceito.*

---

## 🛠️ Tecnologias Utilizadas

<div align="center">

| Tecnologia | Finalidade |
|------------|-------------|
| **HTML5** | Estrutura semântica |
| **Tailwind CSS (CDN)** | Estilização rápida e responsiva |
| **CSS3 personalizado** | Hovers, animações, tabs e detalhes |
| **JavaScript (Vanilla)** | Abas interativas, scroll suave, IntersectionObserver |
| **Font Awesome** | Ícones vetoriais |
| **Google Fonts (Inter)** | Tipografia moderna |

</div>

> ⚠️ *Requer conexão com internet para carregar CDNs (Tailwind, Font Awesome, Google Fonts).*

---

## 🚀 Como Executar

### 🔹 Opção 2 — VS Code (recomendado para desenvolvimento)

```bash
1. Instale a extensão "Live Server"
2. Clique com botão direito no index.html → "Open with Live Server"
```

### 🔹 Opção 3 — Via terminal (Python)

```bash
python -m http.server 8000
# Acesse http://localhost:8000
```

---

## 📁 Estrutura do Projeto

```text
FinControl/
│
├── index.html          # Página principal (landing completa + abas)
├── style.css           # Estilos complementares e animações
├── tst.html            # Rascunho / versão alternativa
├── assets/             # (opcional) Imagens, previews, ícones
│   └── preview.png
└── README.md           # Este arquivo
```

---

## ⚠️ Notas e Limitações (Protótipo)

- ❌ **Sem back-end, banco de dados ou autenticação**  
- ✅ Dados 100% **mockados** (estáticos) → apenas para demonstração  
- 🏷️ Alguns trechos podem mencionar "FinanSys" (variação de nome durante o desenvolvimento)  
- 🎨 O foco é **UI/UX, animações e apresentação comercial** — não funcionalidade de sistema real.

---

## 🔮 Próximos Passos (em um produto real)

- [ ] Transformar as abas em páginas SPA com roteamento  
- [ ] Implementar **autenticação** (login + perfis)  
- [ ] Conectar a **API REST** e banco de dados (PostgreSQL/Firebase)  
- [ ] Tornar gráficos e relatórios **dinâmicos** (Chart.js ou D3.js)  
- [ ] Adicionar **dark mode** e responsividade avançada  
- [ ] Publicar em ambiente de staging (Vercel / Netlify)

---

## 👨‍💻 Contexto Acadêmico

Projeto desenvolvido com fins **acadêmicos** para apresentar o conceito de um **SaaS de gestão integrada (FinControl)**.  
Ideal para:

- Portfólio de front-end  
- Pitch de produto / validação de ideia  
- Estudo de UI/UX com Tailwind e JavaScript vanilla  

---

## 📄 Licença

Distribuído sob licença **acadêmica** — uso livre para estudos e apresentações, desde que mantidos os créditos.

---

<p align="center">
  Feito com ☕ e código por <strong>FinControl Team</strong><br/>
  <sub>✨ *Gerencie seu negócio como nunca antes — tudo em um só lugar.* ✨</sub>
</p>