---
author: "Maria Izabel"
project:
  type: website
  output-dir: docs
format: html
editor: visual
Copyright: "Maria Izabel de Almeida Leite"
  toc: true 
warning: false 
message: false
editor_options: moderno
  markdown: 
    wrap: 72
website: 
 navbar:
    background: "#DDA0DD"
    foreground: "#000000"
  navbar:
    left:
    icon: bar-chart
      - text: "Sobre"
        file: index.qmd
        icon: info-circle
      - text: "Introdução ao R"
        file: INTRODUÇÃO.qmd
      - text: "Manipulação de Dados"
        file: "Aula 1.qmd"
      - text: "Instalação de pacotes"
        file: "Aula 2.qmd"
        icon: book
  navbar:
    left: 
      - text: "Visualização de Dados usando ggplot2"
        file: ggplot.qmd
      - text: "Gráficos de dispersão, histograma e gráfico de densidade"
        file: "GRAFICOS DISP.qmd"
      - text: "BoxPlot"
        file: "GGPLOT2.qmd"
      - text: "Box-Cox"
        file: "BoxCox.qmd"
      - text: "Teste de Hipótese"
        file: "Teste de hipótese.qmd"
      - text: "Transformação de Dados"
        file: "Transformação de dados (log e sqrt).qmd"
       
  navbar:
    left: 
    icon: bar-chart
      - test: "Teste T"
        file: "Aula test T.qmd"
      - text: "ANOVA"
        file: "Aula Anova.qmd"
      - text: "Correlação"
        file: "Análise de Correlação.qmd"
      - text: "Regressão"
        file: "regressão.qmd"
heme: [minty, custom.scss]
    css: styles.css
    toc: true
    toc-depth: 2
    smooth-scroll: true
---

# FIP-606-Analise-e-visualiza-o-de-dados-em-Fitopatologia

# 
