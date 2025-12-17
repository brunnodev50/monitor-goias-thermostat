# 🌡️ Monitor Goiás - Termostato Glassmorphism

![GitHub repo size](https://img.shields.io/github/repo-size/brunnodev50/monitor-goias-thermostat?style=flat-square)
![GitHub language count](https://img.shields.io/github/languages/count/brunnodev50/monitor-goias-thermostat?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/brunnodev50/monitor-goias-thermostat?style=flat-square)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> Uma interface de alta fidelidade visual para monitoramento climático em tempo real das 246 cidades do estado de Goiás.

<p align="center">
  <a href="https://brunnodev50.github.io/monitor-goias-thermostat/">
    <img src="https://img.shields.io/badge/DEMO_ONLINE-Ver_Projeto_no_GitHub_Pages-00a2fa?style=for-the-badge&logo=github&logoColor=white" alt="Ver Demo Online">
  </a>
</p>

---

## 🖼️ Preview

*(Adicione um print da tela do seu projeto aqui depois, basta arrastar a imagem para essa área de edição do GitHub)*

## 📄 Sobre o Projeto

O **Monitor Goiás** é uma aplicação web Full Front-end que combina design moderno (**Glassmorphism**) com engenharia de dados em tempo real. O objetivo foi criar uma experiência visual imersiva onde o usuário pode consultar a temperatura exata de qualquer município goiano.

Diferente de widgets comuns, este projeto utiliza **física de fluidos simulada via SVG** para o mercúrio do termostato e consome múltiplas APIs para garantir dados sempre atualizados.

## ✨ Funcionalidades

- **🎨 UI Glassmorphism:** Interface sofisticada com efeitos de vidro fosco (`backdrop-filter`), sombras dinâmicas e iluminação neon.
- **💧 Física de Fluido (SVG):** O líquido do termostato utiliza filtros `feTurbulence` e `feDisplacementMap` para simular um fluido vivo e orgânico.
- **📡 Dados em Tempo Real:** Conexão direta com a API **Open-Meteo** para buscar a temperatura baseada em geolocalização precisa.
- **🗺️ Integração IBGE:** Listagem automática e filtro de busca para todas as **246 cidades** de Goiás via API de localidades do IBGE.
- **🎛️ Calibração Fina:** Variável de controle `CALIBRATION` no código para ajuste manual de discrepâncias térmicas (offset).
- **👆 Interatividade GSAP:** Botão de controle deslizante com física de inércia e feedback visual instantâneo.

## 🛠️ Tecnologias

Este projeto foi construído utilizando as seguintes tecnologias:

- **HTML5** (Semântico)
- **CSS3** (Variáveis, Flexbox, Grid, Animations)
- **JavaScript ES6+** (Async/Await, Fetch API)
- **[GSAP](https://greensock.com/gsap/)** (GreenSock Animation Platform)
- **APIs Externas:**
  - [IBGE Localidades](https://servicodados.ibge.gov.br/api/docs/localidades)
  - [Open-Meteo Weather API](https://open-meteo.com/)

## 🚀 Como Executar Localmente

Como o projeto não possui dependências de build (como Node.js), é muito simples rodá-lo:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/brunnodev50/monitor-goias-thermostat.git](https://github.com/brunnodev50/monitor-goias-thermostat.git)
