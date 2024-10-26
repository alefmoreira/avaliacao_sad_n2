# Dashboard de Análise de Desempenho dos Estudantes

Este projeto consiste em um dashboard interativo criado com Streamlit para analisar o desempenho de estudantes com base em dois datasets diferentes. O objetivo é explorar os fatores que influenciam as notas finais dos alunos e visualizar as correlações entre variáveis como horas de estudo, atividades extracurriculares, qualidade do ensino e outros fatores.

## 🎯 Objetivo do Projeto

O principal objetivo deste dashboard é facilitar a visualização dos dados e identificar os principais fatores que impactam o desempenho dos estudantes. A ideia é proporcionar uma análise fácil de entender, permitindo que os usuários explorem os dados de forma interativa.

## 📊 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para análise e processamento de dados.
- **Streamlit**: Biblioteca utilizada para criar o dashboard interativo.
- **Pandas**: Para manipulação e limpeza de dados.
- **Altair**: Para a criação de gráficos interativos.

## 🗂️ Datasets Utilizados

1. [Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors): Contém dados sobre fatores que podem influenciar o desempenho dos estudantes, como motivação, apoio dos pais e qualidade do ensino.
2. [Student Performance Predictions](https://www.kaggle.com/datasets/haseebindata/student-performance-predictions): Inclui informações sobre as notas dos estudantes e variáveis relacionadas ao desempenho acadêmico.

## 🔍 Funcionalidades do Dashboard

### 1. Carregamento de Dados
- O usuário pode carregar os dois datasets diretamente no dashboard.
- Verificação se os arquivos foram carregados corretamente e mensagens de erro caso ocorram problemas.

### 2. Filtros Interativos
- Filtro dinâmico para selecionar o intervalo de notas finais.
- Navegação com a barra lateral para explorar diferentes análises.

### 3. Análise Geral
- **Média das Notas Finais**: Valor exibido com duas casas decimais.
- **Gráficos Interativos**:
  - Gráfico de dispersão entre horas de estudo e notas finais.
  - Gráfico de pizza mostrando a distribuição da qualidade do ensino.
- **Top 5 Alunos com Maiores Notas**: Exibe os cinco alunos com as melhores notas finais.

### 4. Fatores Influenciadores
- Análise do impacto de atividades extracurriculares, qualidade do ensino, motivação e outros fatores sobre as notas finais.
- Gráficos de barras, box plots e outras visualizações interativas.

## 📈 Exemplos de Gráficos Utilizados
- **Gráficos de dispersão (Altair)**: Para visualizar a correlação entre horas de estudo e notas finais.
- **Gráficos de pizza (Altair)**: Para mostrar a distribuição da qualidade do ensino.
- **Box plots (Altair)**: Para analisar a distribuição das notas por gênero.
- **Gráficos de barras (Altair)**: Para visualizar a média das notas finais por diferentes fatores.

## 📑 Estrutura do Código
- O código é dividido em seções para facilitar o entendimento:
  - Carregamento e verificação dos datasets.
  - Mesclagem e filtragem dos dados.
  - Criação de gráficos e tabelas interativas.
  - Configuração da navegação e dos filtros.
