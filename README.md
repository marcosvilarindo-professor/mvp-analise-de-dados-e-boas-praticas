# Desigualdades no Desempenho em Matemática no Brasil

## Descrição do Projeto

Projeto MVP de Análise de Dados e Boas Práticas, com foco em exploração, modelagem e interpretação de dados utilizando técnicas de Machine Learning.

Este projeto tem como objetivo analisar as desigualdades no desempenho em matemática no Brasil, utilizando dados do Sistema de Avaliação da Educação Básica (SAEB).

A análise considera três dimensões principais:

- Rede de ensino (pública vs privada)
- Localização das escolas (urbana vs rural)
- Diferenças regionais

O estudo foi desenvolvido como um MVP (Minimum Viable Project), com foco em análise exploratória de dados, visualização da informação e pré-processamento.

---

## Objetivo

Investigar como fatores estruturais, como tipo de escola, localização e região, influenciam o desempenho dos estudantes em matemática ao longo da educação básica.

---

## Hipóteses

- Estudantes de escolas privadas apresentam maior desempenho que os de escolas públicas;
- Estudantes de áreas urbanas apresentam melhores resultados que os de áreas rurais;
- Existem desigualdades regionais significativas no desempenho;
- Fatores estruturais impactam diretamente a aprendizagem em matemática.

---

## Base de Dados

Os dados utilizados são provenientes do SAEB (INEP), considerando os anos:

- 2017
- 2019
- 2021

Foram utilizadas bases agregadas por Unidade Federativa (UF), contendo médias de proficiência em matemática.

---

## Variáveis Utilizadas

- `NO_UF`: Unidade Federativa
- `DEPENDENCIA_ADM`: Rede de ensino (pública ou privada)
- `LOCALIZACAO`: Urbana, rural ou total
- `MEDIA_5_MT`: Proficiência no 5º ano
- `MEDIA_9_MT`: Proficiência no 9º ano
- `MEDIA_12_MT`: Proficiência no Ensino Médio
- `REGIAO`: Região do Brasil (variável criada)
- `ANO`: Ano da avaliação

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Etapas do Projeto

### 1. Definição do Problema
- Contextualização das desigualdades educacionais no Brasil
- Formulação de hipóteses

### 2. Análise Exploratória de Dados (EDA)
- Estatísticas descritivas
- Análise de distribuição
- Comparações entre grupos

### 3. Visualização de Dados
- Gráficos de barras
- Boxplots
- Histogramas
- Matriz de correlação

### 4. Pré-processamento de Dados
- Tratamento de valores ausentes
- Criação de variáveis derivadas
- Normalização e padronização

---

## Principais Resultados

- Diferença significativa entre escolas públicas e privadas;
- Melhor desempenho em áreas urbanas em relação às rurais;
- Desigualdade regional no desempenho em matemática;
- Evidência de fatores estruturais impactando a aprendizagem.

---

## Limitações

- Dados agregados (não permitem análise individual dos estudantes);
- Ausência de variáveis diretas sobre formação docente;
- Não é possível inferir causalidade, apenas associações.

---


