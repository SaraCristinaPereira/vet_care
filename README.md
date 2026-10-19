# 🐾 VetCare - Hospital Veterinário e Centro Diagnóstico

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![BEM](https://img.shields.io/badge/BEM-Metodologia-000000?style=for-the-badge&logo=css3)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-Poppins-4285F4?style=for-the-badge&logo=google&logoColor=white)

> Aplicação Web Front-end para o **Hospital Veterinário VetCare**, desenvolvida com foco em arquitetura semântica, acessibilidade, metodologia BEM e responsividade avançada.

---

## 📌 Visão Geral e Objetivo do Projeto

O **VetCare** é uma solução web desenvolvida para um cliente fictício que atua como hospital veterinário e centro diagnóstico com atendimento 24 horas. O objetivo principal deste projeto é simular um ambiente de desenvolvimento front-end profissional, aplicando boas práticas de estruturação de código, estilização limpa, usabilidade e navegação intuitiva para tutores de animais de estimação.

### Key Features / Funcionalidades
- **Menu Lateral Esquerdo Fixo (`fixed`):** Navegação sempre acessível na versão desktop com suporte a rolagem suave (*scroll-behavior*).
- **Layout de Seções em Tela Cheia:**
  - **Hero / Boas-vindas:** Apresentação institucional de alto impacto.
  - **Especialidades Médicas:** Cards informativos organizados com Flexbox.
  - **Corpo Clínico:** Quadro de profissionais veterinários com seus respectivos números de CRMV.
  - **Infraestrutura e Atendimento:** Destaques operacionais e horários de consultas.
  - **FAQ Interativo:** Seção de perguntas frequentes construída de forma semântica com `<details>` e `<summary>`.
- **Microinterações e Feedback Visual:** Efeitos de hover, transições suaves e sombras (*box-shadow*) dinâmicas nos componentes interativos.
- **Botão Flutuante do WhatsApp:** Integração via URL da API oficial do WhatsApp configurada para contato direto com a central (Escola SENAI Henrique Lupo).
- **Rodapé Fixo:** Exibição contínua de informações de localização, direitos autorais e expediente.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Estruturação acessível utilizando tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>` e `<footer>`.
- **CSS3 Moderno:**
  - **Design System com Variáveis CSS (`:root`):** Padronização de tokens de cor, tipografia, espaçamentos, sombras e transições.
  - **Metodologia BEM (Block Element Modifier):** Nomenclatura clara e modular de classes HTML e seletores CSS.
  - **Escala Tipográfica Proporcional (`rem`):** Definição da fonte base na raiz do documento e conversão de medidas tipográficas e de espaçamento.
  - **Layout Fluido:** Uso de porcentagens (`%`), `vw` e `vh` para controle dimensional de telas flexíveis e seções full-screen.
  - **Flexbox Layout:** Alinhamento e distribuição eficiente dos componentes internos (cards, menus e contêineres).
  - **Media Queries:** Breakpoints responsivos para adaptação contínua em smartphones, tablets e desktops.
- **Tipografia Externa:** Família de fontes **Poppins** (pesos 400, 500, 600 e 700) importada do Google Fonts.
- **Recursos Visuais:** Consumo de imagens placeholder temáticas (*Placehold.co*).

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do projeto foi organizada seguindo o princípio da **Separação de Responsabilidades (SoC)**, mantendo a estilização e arquivos de suporte totalmente desacoplados da estrutura HTML:

```text
vetcare-hospital/
│
├── index.html                # Estrutura HTML5 semântica principal da aplicação
├── README.md                 # Documentação detalhada do projeto
│
├── css/
│   ├── variables.css         # Tokens do Design System (Cores, Fontes, Sombras, Transitions)
│   ├── reset.css             # Reset de estilos globais e regras de escala REM
│   ├── layout.css            # Estilos de posicionamento (Sidebar, Header, Footer, Seções)
│   ├── components.css        # Estilização de componentes BEM (Cards, FAQ, Botão WhatsApp)
│   └── responsive.css        # Regras de media queries e breakpoints para responsividade
│
└── img/              # Imagens e recursos visuais locais (se houver)

Bash
git clone [https://github.com/SaraCristinaPereira/vet_care](https://github.com/SaraCristinaPereira/vet_care.git)

