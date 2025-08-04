# Espíndola iPhones – Tecnologia e Perfumaria

Bem-vindo ao protótipo do site **Espíndola iPhones**, uma landing page one-page desenvolvida com **Tailwind CSS** e JavaScript puro para exibir seções de produtos (smartphones e áudio), perfumaria, assistência técnica e informações institucionais.

---

## 📌 Sumário

* [Visão Geral](#visão-geral)
* [Funcionalidades](#funcionalidades)
* [Tecnologias](#tecnologias)
* [Estrutura de Pastas](#estrutura-de-pastas)
* [Como Usar](#como-usar)
* [Personalização](#personalização)
* [Scripts](#scripts)
* [Créditos](#créditos)
* [Licença](#licença)

---

## 🌐 Visão Geral

Este protótipo tem o objetivo de:

* Demonstrar uma experiência de navegação one-page,
* Apresentar seções de **Produtos**, **Perfumes**, **Assistência Técnica** e **Quem Somos**,
* Exibir um **carrossel** interativo na seção inicial,
* Implementar um **menu fixo** no topo com dropdown e versão mobile (hambúrguer),
* Garantir **scroll suave** e posicionamento correto de cada âncora abaixo do header fixo.

> **Nota**: Este código é um protótipo gerado via Readdy.site + ajustes manuais, focado na etapa de apresentação ao cliente.

---

## 🚀 Funcionalidades

* **Carrossel automático** com três slides (produtos, perfumes, assistência).
* **Menu fixo** no topo com dropdown "Serviços" e links para seções.
* **Menu mobile** com botão hambúrguer, painel deslizante e destaque ativo.
* **Scroll suave** para âncoras (`scroll-behavior: smooth;` e `scroll-margin-top`).
* **Dropdown estilizado** com bordas arredondadas e overflow hidden.
* **Seções responsivas** usando utilitários Tailwind.

---

## 🛠️ Tecnologias

* **HTML5**
* **Tailwind CSS 3.4.16 (via CDN)**
* **JavaScript Vanilla**
* **Google Fonts (Pacifico)**
* **Remixicon** para ícones

---

## 📂 Estrutura de Pastas

```text
/ (raiz)
├── index.html        # Arquivo principal com todo o markup, CSS inline e scripts
└── README.md         # Este documento explicativo
```

> Observação: Como protótipo, não há pastas de `css/` ou `js/`; tudo está contido em `index.html`.

---

## 📝 Como Usar

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/espindola-iphones.git
   cd espindola-iphones
   ```
2. Abra o `index.html` no seu navegador favorito.
3. Para modificar textos e imagens, edite diretamente as tags HTML:

   * Slides do carrossel: `<div class="carousel-slide" style="background-image: url('...')">`.
   * Links do menu: `<a href="#secao">Título</a>`.
4. Para ajustes de estilo, altere o bloco `<style>` dentro de `<head>`.

---

## 🎨 Personalização

* **Cores**: modifique o objeto `tailwind.config` no `<script>` do CDN.
* **Fontes**: troque a família `Pacifico` no `<link>` do Google Fonts.
* **Bordas**: ajuste `border-radius` no CSS customizado.
* **Dropdown**: estilização adicional em `.dropdown-menu`.
* **Scroll**: altere `scroll-padding-top` e `scroll-margin-top` conforme o header.

---

## ⚙️ Scripts

* **Carrossel**: atalho `setInterval` para trocar slides a cada 5s e `click` nos pontos.
* **Scroll suave**: intercepta `click` em `a[href^='#']` e posiciona abaixo do header.
* **Mobile menu**: toggles `hidden` na `.mobile-menu` ao clicar no `.mobile-menu-button`.

---

## 🤝 Créditos

* Protótipo gerado com **Readdy.site**
* Código adaptado e refinado por **Devsphz**
* Empresa responsável pelo projeto: **HeinSoft Company**
* Ícones por **Remixicon**
* Fonte **Pacifico** por Google Fonts

---

## 📄 Licença

Este projeto é oferecido **"AS IS"**, sem garantias de qualquer espécie. Uso para prototipação e apresentação apenas.

---

> Desenvolvido com ♥ pela equipe HeinSoft Company | [https://heinsoft.com.br](https://heinsoft.com.br)
