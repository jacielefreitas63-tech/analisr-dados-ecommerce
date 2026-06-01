
# Análise de Dados - E-commerce

Este projeto foi desenvolvido como parte do curso de Análise de Dados da EBAC. O objetivo principal é analisar uma base de dados de e-commerce e gerar visualizações estatísticas para entender o comportamento das vendas, produtos e faturamento.

## 📁 Estrutura do Repositório

* *data/*: Contém o arquivo de dados bruto utilizado na análise (ecommerce_estatistica.csv).
* *notebooks/*: Contém o arquivo de código (analise_ecommerce.ipynb) com todo o desenvolvimento em Python.

## 📊 Gráficos Gerados

Utilizando as bibliotecas *Seaborn* e *Matplotlib* no Python, foram geradas as seguintes visualizações:
1. *Histograma*: Distribuição de preços dos produtos.
2. *Gráfico de Dispersão*: Relação entre preço e quantidade vendida.
3. *Mapa de Calor*: Correlação entre as variáveis numéricas.
4. *Gráfico de Barras*: Faturamento total acumulado por categoria.
5. *Gráfico de Pizza*: Proporção do volume de vendas por categoria.
6. *Gráfico de Densidade*: Distribuição visual das notas dos produtos.
7. *Gráfico de Regressão*: Tendência de faturamento baseada no preço do produto.

## 🛠️ Tecnologias Utilizadas

* *Python 3*
* *Pandas* (Manipulação dos dados)
* *Seaborn* & *Matplotlib* (Visualização de dados)
* *Google Colab* (Ambiente de desenvolvimento)


  ## 📊 Atualização: Dashboard Interativo com Dash & Plotly

O projeto foi expandido com a criação de uma aplicação web interativa em tempo real, estruturada para o acompanhamento dinâmico das métricas do e-commerce.

### 🛠️ Novas Tecnologias Utilizadas
* *Dash (v2.x)*: Construção do layout e da interface web.
* *Plotly Express*: Renderização de 7 gráficos dinâmicos com suporte a filtros e zoom.
* *Statsmodels*: Modelagem estatística para plotagem de linhas de tendência.
* *Threading*: Execução do servidor em segundo plano para viabilizar o funcionamento no Google Colab.

### 📈 Funcionalidades do Dashboard
* Consolidação de *7 gráficos interativos* em uma única página.
* Análise de faturamento, preços e distribuição de notas de forma visual.
* Gráficos dinâmicos que permitem explorar os dados diretamente pelo navegador.

<img width="1742" height="800" alt="distribuicao_precos" src="https://github.com/user-attachments/assets/c4105a4b-8c05-45e6-9026-5f46429bad1a" />


 <img width="1748" height="654" alt="Captura de tela 2026-06-01 140108" src="https://github.com/user-attachments/assets/fe9c8ea5-22f0-4aa3-8a7a-51058df7499e" />

