# TriggoAI - Data Engineering & DataOps Challenge

Este repositório contém a solução para o desafio técnico do programa de trainees/bootcamp da **TriggoAI** na trilha de Engenharia de Dados e DataOps.

---

## ⚙️ Setup do Ambiente

Siga os passos abaixo para configurar o ambiente localmente. Pelo terminal:

### 1. Clone o repositório

```bash
git clone https://github.com/diunkz/TriggoAI-DataEngineering-DataOps-Challenge.git
```

### 2. Crie seu ambiente virtual

```bash
python3 -m venv .challengevenv
```

### 3. Ative o ambiente virtual

#### Linux/Mac:
```bash
source .challengevenv/bin/activate
```

#### Windows:
```bash
.challengevenv\Scripts\activate
```

### 4. Instale os pacotes necessários (dentro do arquivo `requirements.txt`)

```bash
pip install -r requirements.txt
```

### 5. Inicialize o Jupyter Notebook para executar o arquivo `triggoai_challenge.ipynb`

```bash
jupyter notebook
```

## 📊 Principais Resultados Encontrados

###  🧹 Preparação dos Dados

Todos os arquivos CSV foram importados e tratados com foco em integridade relacional.

Realizada limpeza de dados: remoção de duplicatas, tratamento de nulos e conversão de colunas de data.

Criado modelo relacional entre as tabelas principais (pedidos, clientes, produtos, pagamentos, avaliações, etc.).

As tabelas foram integradas de forma que permitisse análises temporais, espaciais e comportamentais.

## 📈 Análise Exploratória de Dados

Volume de pedidos por mês

Tempo de entrega

Frete vs. Distância

Categorias mais vendidas (faturamento)

Estados com maior valor médio de pedido

## 🧠 Solução de Problemas de Negócio

🔁 Análise de Retenção

⏰ Predição de Atraso

🎯 Segmentação de Clientes

⭐ Análise de Satisfação

## 📊 Visualizações e Dashboards

Criado um dashboard geral interativo com filtros por estado e categoria.

Desenvolvido um mapa de calor com a concentração de vendas por estado.

Gráficos de dispersão e boxplots mostram a relação entre avaliação e tempo de entrega.

Painel dos vendedores mostra:

- Volume de vendas por seller

- Satisfação dos clientes

- Tempo médio de entrega por vendedor

