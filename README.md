# Documentação do Código HTML com Bootstrap

## 🎶 Introdução

Este documento descreve a estrutura e funcionalidade do código HTML que utiliza o framework Bootstrap para criar um site responsivo e estilizado para uma escola de jazz chamada **"Tom's Jazzschool"**. O Bootstrap é usado para facilitar o design responsivo, a estilização e a organização dos componentes visuais.

---

## 🏗️ Estrutura Geral

O código é dividido em três partes principais:

1. **Cabeçalho (Header):** Contém a navegação principal com links centralizados, a logo à esquerda e um botão de inscrição à direita.
2. **Conteúdo Principal (Main):** Inclui seções de introdução, cursos e informações sobre a escola.
3. **Rodapé (Footer):** Exibe informações adicionais, links rápidos e um formulário de inscrição para novidades.

---

## 🔝 Cabeçalho (Header)

O cabeçalho utiliza o componente **Navbar** do Bootstrap:

1. **Container:** Envolve a navbar para centralizar e limitar a largura.
2. **Navbar-brand:** Exibe a logo da escola na extrema esquerda.
3. **Navbar-nav:** Lista de links centralizada usando a classe `mx-auto`.
4. **Botão de Inscrição:** Um botão à direita com classes `btn btn-primary` e `ms-lg-3` para espaçamento.
5. **Responsividade:** Inclui um botão hambúrguer (`navbar-toggler`) para dispositivos menores.

---

## 📄 Conteúdo Principal (Main)

### 1️⃣ Seção de Introdução

- **Estrutura:** Usada a classe `container` para organizar o conteúdo em duas colunas (imagem e texto) usando `d-flex` e classes responsivas (`flex-lg-row`, `flex-column-reverse`).
- **Texto:** Inclui um título e um parágrafo com classes do Bootstrap como `mt-3` e `text-lg-start` para espaçamento e alinhamento.
- **Imagem:** Usa a classe `img-fluid` para tornar a imagem responsiva.

### 2️⃣ Seção de Cursos

- **Cards:** Criados com o componente **Card** do Bootstrap, organizados em uma grade responsiva usando `row` e `col-md-3`.
- **Conteúdo:** Cada card possui uma imagem, título, descrição e botão com classes como `card-img-top`, `card-title`, e `btn-outline-primary`.

---

## 🔽 Rodapé (Footer)

1. **Colunas:** Organizado em três colunas usando `row` e `col`.
   - **Primeira Coluna:** Exibe a logo e uma descrição.
   - **Segunda Coluna:** Contém links rápidos.
   - **Terceira Coluna:** Inclui um formulário com `input-group` para inscrição via e-mail.
2. **Cores:** Usa classes como `bg-dark` e `text-white` para estilização.

---

## 🎨 Personalizações com CSS

- **Contorno em Imagens:** Usada a classe `.img-bordered` para adicionar bordas e espaçamento a imagens SVG.
- **Botões Personalizados:** A classe `.subscribe-btn` aplica bordas arredondadas e estilo adicional ao botão "Se-inscreva".

---

## 🎯 Conclusão

Este código demonstra como usar os componentes do Bootstrap para criar um site bem estruturado e responsivo. A combinação de classes prontas do framework com personalizações CSS permite um design elegante e funcional para promover a escola de jazz.
