# 🐾 VetCare - Clínica Veterinária

Projeto desenvolvido como parte da atividade prática de **Desenvolvimento Front-End Professional**, simulação de entrega para um cliente fictício.

---

## 📌 Sumário
- [Visão Geral e Objetivo](#-visão-geral-e-objetivo)
- [Tecnologias e Conceitos Aplicados](#-tecnologias-e-conceitos-aplicados)
- [Arquitetura de Arquivos](#-arquitetura-de-arquivos)
- [Instruções de Visualização e Execução](#-instruções-de-visualização-e-execução)
- [Requisitos e Especificações do Projeto](#-requisitos-e-especificações-do-projeto)
- [Principais Desafios Técnicos e Aprendizados](#-principais-desafios-técnicos-e-aprendizados)

---

## 🐶 Visão Geral e Objetivo

O projeto **VetCare** consiste em uma landing page institucional responsiva desenvolvida para um hospital veterinário fictício. A plataforma apresenta informações sobre a clínica, suas especialidades médicas, corpo clínico, estrutura física, horários de atendimento, FAQ interativo e um canal rápido de contato via WhatsApp.

O objetivo da atividade é consolidar práticas avançadas de desenvolvimento front-end com HTML5 semântico, arquitetura CSS modular, nomenclatura BEM, acessibilidade e responsividade sem o uso de frameworks externos.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **HTML5 Semântico:** Estruturação utilizando tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<details>`, `<summary>`, `<footer>`)[cite: 1, 4].
* **CSS3 Modular & Variáveis (`:root`):** Implementação de um Design System com tokens para cores, tipografia, espaçamentos e sombras[cite: 5].
* **Metodologia BEM (Block Element Modifier):** Padronização rigorosa da nomenclatura de classes e seletores CSS[cite: 2].
* **Tipografia e Unidades Relativas:** 
  * Importação da fonte **Poppins** (pesos 400, 500, 600, 700) via Google Fonts[cite: 2, 6].
  * Uso da unidade relativa `rem` para tipografia, espaçamentos e bordas com escala base na raiz (`:root`)[cite: 2].
* **Layout Fluido e Responsivo:**
  * Uso de `Flexbox` para alinhamento e organização dos componentes e cards[cite: 3, 4].
  * Dimensões em porcentagem (`%`), unidades de viewport (`vh`/`vw`) para seções em tela cheia e breakpoints CSS (`@media`)[cite: 2].
* **Microinterações:** Efeitos de estado (`:hover`), `transition`, `transform` e `box-shadow` nos cards e links de navegação[cite: 4, 5].
* **Redirecionamento de API:** Integração do botão flutuante do WhatsApp configurado com a API oficial e número institucional da Escola SENAI Henrique Lupo[cite: 4].

---

## 📁 Arquitetura de Arquivos

Para garantir a **separação de responsabilidades** (RNF04) e organização limpa do código[cite: 1], adotou-se a seguinte estrutura[cite: 1, 3]:

```text
vetcare-website/
├── assets/
│   ├── css/
│   │   ├── variables.css    # Tokens de Design System (:root)
│   │   ├── reset.css        # Reset de estilos e escala base rem
│   │   ├──