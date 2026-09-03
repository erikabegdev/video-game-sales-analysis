# 🎮 Análise de Dados do Mercado de Videogames

## 📌 Sobre o projeto

Este projeto teve como objetivo identificar padrões associados ao sucesso comercial de jogos eletrônicos, utilizando dados históricos de vendas, avaliações de críticos e usuários, plataformas, gêneros e classificação etária.
A análise foi desenvolvida com foco em apoiar decisões estratégicas de marketing para o mercado de videogames em 2017, considerando dados disponíveis até dezembro de 2016.

---

## 🎯 Objetivos

- Identificar padrões relacionados ao desempenho comercial dos jogos;
- Analisar a evolução das vendas ao longo dos anos;
- Avaliar o desempenho das principais plataformas;
- Investigar a relação entre avaliações e vendas;
- Identificar os gêneros com maior desempenho comercial;
- Comparar preferências entre diferentes regiões;
- Avaliar o impacto da classificação etária (ESRB);
- Aplicar testes estatísticos para validar hipóteses.

---

## 🛠️ Tecnologias e ferramentas

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- Jupyter Notebook

---

## 🔎 Etapas da análise

### 1. Carregamento e inspeção dos dados

Foi realizada uma análise inicial da estrutura do dataset, incluindo:

- Tipos de dados;
- Estatísticas descritivas;
- Identificação de valores ausentes;
- Avaliação da qualidade dos dados.

### 2. Preparação dos dados

Foram realizadas etapas de tratamento e padronização, incluindo:

- Padronização dos nomes das colunas;
- Conversão de tipos de dados;
- Tratamento de valores ausentes;
- Criação da variável `total_sales`, representando as vendas globais.

### 3. Análise exploratória

A análise investigou diferentes aspectos do mercado, como:

- Número de jogos lançados por ano;
- Plataformas com maior volume de vendas;
- Distribuição das vendas por plataforma;
- Relação entre avaliações críticas e vendas;
- Desempenho dos diferentes gêneros;
- Identificação de outliers e padrões de comportamento.

### 4. Análise regional

Foram analisados os mercados de:

🌎 América do Norte  
🇪🇺 Europa  
🇯🇵 Japão

A análise considerou diferenças entre:

- Plataformas;
- Gêneros;
- Classificações etárias (ESRB);
- Preferências de consumo.

### 5. Testes estatísticos

Foram realizados testes de hipótese utilizando nível de significância de **5% (α = 0.05)**.

#### Xbox One × PC

**H₀:** As médias das avaliações dos usuários são iguais.

**H₁:** As médias das avaliações são diferentes.

Resultado: **p-valor = 0.98**

Não foram encontradas evidências estatísticas suficientes para rejeitar a hipótese nula.

#### Action × Sports

**H₀:** As médias das avaliações dos usuários são iguais.

**H₁:** As médias das avaliações são diferentes.

Resultado: **p-valor = 1.45e-15**

A hipótese nula foi rejeitada, indicando diferença estatisticamente significativa entre as médias das avaliações dos dois gêneros.

---

## 📊 Principais insights

A análise mostrou que:

- O mercado de videogames é fortemente influenciado pelo **ciclo de vida das plataformas**;
- Poucos títulos apresentam vendas extremamente altas, enquanto a maioria possui vendas moderadas;
- Determinados gêneros concentram maior volume de vendas;
- Existem diferenças relevantes nas preferências de consumo entre as regiões analisadas;
- Avaliações positivas podem estar relacionadas a um melhor desempenho comercial, mas não são, isoladamente, determinantes para o sucesso;
- A análise estatística ajuda a diferenciar padrões observados de diferenças realmente significativas.

---

## 💡 Recomendação estratégica

Com base nos resultados, recomenda-se:

- Priorizar plataformas com maior desempenho no período recente;
- Direcionar campanhas para gêneros com maior potencial comercial;
- Adaptar estratégias de marketing às características de cada região;
- Utilizar avaliações de usuários e críticos como indicadores complementares;
- Considerar a combinação entre **plataforma, gênero e público-alvo** na definição das estratégias.

---

## 📁 Estrutura do projeto

```text
📦 projeto-analise-videogames
 ┣ 📓 projeto_integrado_1.ipynb
 ┗ 📄 README.md
