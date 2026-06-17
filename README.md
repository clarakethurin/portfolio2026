# 🧑‍💻 Portfolio — Landing Page Pessoal

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Responsivo-Mobile%20First-58a6ff?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-3fb950?style=for-the-badge)

> Página de apresentação profissional desenvolvida com **HTML5 e CSS3 puro**, sem frameworks. Projeto prático.

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Demonstração](#-demonstração)
- [Funcionalidades](#-funcionalidades)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias](#-tecnologias)
- [Como Executar](#-como-executar)
- [Estrutura HTML](#-estrutura-html)
- [Autor](#-autor)

---

## 📌 Sobre o Projeto

Este projeto é uma **landing page pessoal** criada como portfólio de apresentação profissional. O objetivo é demonstrar habilidades em HTML semântico e CSS moderno, apresentando informações sobre o desenvolvedor, suas habilidades técnicas e projetos realizados.

Desenvolvido como atividade prática com foco em:

- Uso correto de tags semânticas do HTML5
- Estilização avançada com CSS puro (sem Bootstrap ou Tailwind)
- Layout responsivo com CSS Grid e Media Queries
- Organização e legibilidade de código

---

## 🖥️ Demonstração

```
📁 portfolio-web/
└── index.html   ← abra este arquivo no navegador
```

**Preview das seções:**

| Seção | Descrição |
|---|---|
| Header | Nome, avatar, frase e nav |
| Sobre mim | Apresentação pessoal |
| Habilidades | Grid de tecnologias com indicadores coloridos |
| Projetos | Cards com descrição e tags |
| Aside | Links, hobbies e curiosidades |
| Footer | Contato e copyright |

---

## ✅ Funcionalidades

- [x] Layout responsivo (desktop e mobile)
- [x] Navegação interna com âncoras (`#seção`)
- [x] Nav fixo no topo com `position: sticky`
- [x] Aside fixo durante o scroll no desktop
- [x] Tema dark com paleta consistente via CSS custom properties (`--variáveis`)
- [x] Hover interativo nos cards de projeto
- [x] Tags de tecnologia com código de cores por categoria
- [x] HTML semântico (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`)

---

## 📁 Estrutura do Projeto

```
portfolio-web/
│
├── index.html        # Página principal (HTML + CSS interno)
└── README.md         # Documentação do projeto
```

> O CSS está embutido via `<style>` dentro do próprio `index.html`, conforme requisito da atividade. Para projetos maiores, recomenda-se separar em um arquivo `.css` externo.

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura semântica da página |
| CSS3 | Estilização, layout e responsividade |
| CSS Grid | Layout de duas colunas (main + aside) |
| CSS Custom Properties | Sistema de tokens de design (cores, bordas) |
| Media Queries | Adaptação para telas menores que 680px |
| Position Sticky | Nav e aside fixos durante o scroll |

**Nenhum framework externo foi utilizado.**

---

## 🏗️ Estrutura HTML

```html
<body>
  <header>         <!-- Nome, avatar, frase de impacto -->
    <nav>          <!-- Menu com links internos -->
  </header>

  <main>
    <section id="sobre">       <!-- Apresentação pessoal -->
    <section id="habilidades"> <!-- Grid de skills -->
    <section id="projetos">    <!-- Cards com <article> -->
      <article>                <!-- Projeto 1 -->
      <article>                <!-- Projeto 2 -->
  </main>

  <aside>          <!-- Links, hobbies, curiosidades -->

  <footer id="contato">  <!-- E-mail e copyright -->
</body>
```

---

## 👤 Autor

**Clara Kethurin**

<p align="center">
  Desenvolvido por <strong>Clara Kethruin</strong>
</p>
