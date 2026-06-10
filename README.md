# Desafio Técnico – Analista de Dados (RAIS 2020–2022)

## Objetivo

Construir uma solução analítica utilizando dados da Relação Anual de Informações Sociais (RAIS) dos anos de 2020, 2021 e 2022 para apoiar análises do mercado de trabalho formal no estado de Santa Catarina.

O projeto contempla todas as etapas do processo analítico, desde a preparação e consolidação dos dados até a construção de dashboards interativos no Power BI.

---

## Tecnologias Utilizadas

- Python
- Pandas
- Jupyter Notebook
- Power BI
- Git
- GitHub

---

## Etapas do Projeto

### 1. Inventário e Compreensão dos Dados

Nesta etapa foi realizado o levantamento dos arquivos disponibilizados, análise do dicionário de dados e identificação das variáveis relevantes para o desenvolvimento dos indicadores.

### 2. Tratamento e Padronização

Principais atividades executadas:

- Padronização de nomes de colunas
- Conversão de tipos de dados
- Tratamento de valores ausentes
- Remoção de inconsistências
- Validação de integridade dos dados

### 3. Consolidação das Bases

Os dados dos anos:

- 2020
- 2021
- 2022

foram consolidados em uma única base analítica, permitindo análises históricas e comparações temporais.

### 4. Modelagem Dimensional

Foi desenvolvido um modelo estrela para otimizar o desempenho e a análise dos dados.

#### Tabela Fato

- fato_vinculos

#### Tabelas Dimensão

- dim_municipio
- dim_cnae
- dim_escolaridade
- dim_faixa_etaria
- dim_raca
- dim_sexo

---

## Indicadores Desenvolvidos

- Total de Vínculos
- Vínculos Ativos
- Percentual de Vínculos Ativos
- Tempo Médio de Emprego
- Remuneração Média
- Remuneração Máxima
- Remuneração Mínima
- Total de Desligamentos
- Quantidade de Municípios
- Quantidade de CNAEs

---

## Dashboards Desenvolvidos

### Página 1 – Visão Geral

Indicadores principais:

- Total de vínculos
- Vínculos ativos
- Tempo médio de emprego
- Remuneração média

Análises do perfil dos trabalhadores:

- Faixa etária
- Escolaridade
- Sexo
- Raça/Cor

Distribuição dos vínculos por setor econômico.

![Página 1 - Visão Geral](assets/pagina_1.png)

---

### Página 2 – Análise Geográfica

Análise da distribuição dos vínculos ativos por:

- Municípios
- Regiões Imediatas
- Regiões Intermediárias

Objetivo:

Identificar os principais polos de emprego e concentração de vínculos formais no estado.

![Página 2 - Análise Geográfica](assets/pagina_2.png)

---

### Página 3 – Análise Econômica e Temporal

Indicadores analisados:

- Top 10 setores econômicos por remuneração média
- Evolução dos vínculos entre 2020 e 2022
- Evolução da remuneração média entre 2020 e 2022

Objetivo:

Avaliar tendências do mercado de trabalho e evolução salarial ao longo do período.

![Página 3 - Análise Econômica e Temporal](assets/pagina_3.png)

---

### Página 4 – Comparações Regionais e Disparidades Salariais

Análises realizadas:

- Comparação da remuneração média dos municípios em relação à média estadual
- Disparidade salarial por sexo
- Disparidade salarial por raça/cor

Objetivo:

Identificar diferenças salariais entre grupos e regiões.

![Página 4 - Comparações Regionais](assets/pagina_4.png)

---

## Principais Insights

### Mercado de Trabalho

- Houve crescimento dos vínculos formais entre 2020 e 2022.
- Florianópolis, Joinville e Blumenau concentram grande parte dos vínculos ativos do estado.

### Perfil dos Trabalhadores

- Predominância da faixa etária entre 30 e 39 anos.
- Ensino Médio Completo representa o maior grupo de escolaridade.

### Remuneração

- Existem diferenças significativas de remuneração entre municípios.
- Alguns municípios apresentam remuneração média superior à média estadual.

---

## Estrutura do Projeto

```text
desafio_td_business/
│
├── notebook/
│   └── 002_exploracao.ipynb
│
├── assets/
│   ├── pagina_1.png
│   ├── pagina_2.png
│   ├── pagina_3.png
│   └── pagina_4.png
│
├── Bases/
│
├── desafio_td_business.pbix
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

---

## Como Executar

### Ambiente Python

```bash
pip install -r requirements.txt
```

### Dashboard Power BI

Abra o arquivo:

```text
desafio_td_business.pbix
```

utilizando o Power BI Desktop.

---

## Resultados

O projeto entrega uma visão consolidada do mercado de trabalho formal em Santa Catarina entre 2020 e 2022, permitindo análises demográficas, econômicas, temporais e regionais por meio de dashboards interativos.

---

## Autor

**Roberto Sulkovski**