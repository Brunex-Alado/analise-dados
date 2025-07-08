# 📊 Análise de Dados - Challenge Data Science

## 🚀 Tecnologias Utilizadas
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white">
</div>

## ▶️ Como Executar o Notebook

1. Clone este repositório (se estiver usando Git):
git clone https://github.com/Brunex-Alado/analise-dados

2.  Abra o Jupyter Notebook:
Você pode usar VS Code, Jupyter Lab, Jupyter Notebook ou Google Colab.

3. Instale as bibliotecas Pandas e Matplotlib:
pip install pandas
pip install matplotlib

4. Execute todas as células em ordem:
O notebook lê automaticamente os dados de 4 lojas via internet e gera todos os gráficos.

✅ Importante: Requer conexão com a internet para ler os dados CSV.


## 📁 Estrutura do Projeto

```text
📂 challenge1-data-science-main
├── 📂 base-de-dados-challenge-1
├──     ├── loja_1.csv
├──     ├── loja_2.csv
├──     ├── loja_3.csv
├──     ├── loja_4.csv
├── 📂 img
├──     ├── Grafico1_Faturamento
├──     ├── Grafico2_Categoria
├──     ├── Grafico3_Avaliacao
├──     ├── Grafico4_Produtos
├──     ├── Grafico5_Frete
├── Bruno_AluraStoreBr.ipynb        # Notebook principal com a análise
├── codigo-grafico.py               # Código completo em Python
└── README.md
```

## 🎯 Propósito da Análise

Este projeto realiza uma **análise exploratória de dados (EDA)** com o objetivo de auxiliar o Sr. João a decidir **qual das suas quatro lojas deve ser vendida**, utilizando Python, Pandas e Matplotlib.

| Indicadores Utilizados           | Objetivo                                  |
| -------------------------------- | ----------------------------------------- |
| ✅ Faturamento total por loja     | Identificar qual loja gera mais receita   |
| ✅ Vendas por categoria           | Compreender o foco de vendas de cada loja |
| ✅ Produtos mais e menos vendidos | Avaliar desempenho por produto            |
| ✅ Média das avaliações           | Analisar a satisfação dos clientes        |
| ✅ Valor médio de frete           | Estimar impacto logístico por loja        |


---

## 💰 Faturamento Total por Loja

Nessa análise avaliamos o total arrecadado por cada loja, considerando o volume de vendas e os valores envolvidos. O objetivo é entender qual loja gera mais receita de forma geral.

![Faturamento das Lojas](https://raw.githubusercontent.com/Brunex-Alado/analise-dados/refs/heads/main/challenge1-data-science-main/img/Grafico1_Faturamento.png)

**Análise:**

- **Loja 1** Apresenta o maior faturamento, indicando um desempenho superior em vendas.  
- **Loja 4** Possui o menor faturamento, sugerindo uma performance abaixo das demais.

---

## 📦 Vendas de Produtos por Categoria

A análise por categoria permite identificar quais tipos de produtos são mais vendidos em cada loja, ajudando a compreender o foco e a especialização de cada uma.

![Vendas por Categoria](https://raw.githubusercontent.com/Brunex-Alado/analise-dados/refs/heads/main/challenge1-data-science-main/img/Grafico2_Categoria.png)

**Análise:**

- **Loja 1** Tem um foco mais restrito, concentrado em Moda.
- **Loja 2** Apresenta maior variedade de categorias, com forte presença em Eletrônicos.
- **Loja 3** Possui distribuição mais equilibrada entre as categorias, sugerindo uma abordagem mais diversificada.

---

## 🛍️ Média das avaliações

As avaliações dos clientes foram analisadas para verificar o nível de satisfação em cada loja, o que é um indicador importante para avaliar a qualidade do atendimento e dos produtos.

![Média das Avaliações](https://raw.githubusercontent.com/Brunex-Alado/analise-dados/refs/heads/main/challenge1-data-science-main/img/Grafico3_Avaliacao.png)

**Análise:**

- **Loja 4** Possui a maior média de avaliações, sugerindo um alto nível de satisfação dos clientes.  
- **Loja 1** Apresenta a menor média, indicando possíveis áreas de melhoria no atendimento ou na qualidade dos produtos.

---

## 🛒 Venda de produtos

Análise dos 5 produtos com maior e menor número de vendas e faturamento em cada loja, exibida em uma matriz de gráficos (4x4) para facilitar a comparação.
Aqui investigamos as quantidades totais de produtos vendidos por loja. Essa métrica ajuda a entender o volume de vendas independentemente do valor.

![Produtos Mais Vendidos e Mais Faturados](https://raw.githubusercontent.com/Brunex-Alado/analise-dados/refs/heads/main/challenge1-data-science-main/img/Grafico4_Produtos.png)

**Análise:**

- **Loja 1** Possui os produtos mais vendidos e com maior faturamento, reforçando seu destaque no mercado.  
- **Loja 4** Apresenta produtos com menor volume de vendas e faturamento, indicando uma possível necessidade de revisão de estratégias.


---

## 🚚 Valor de Frete por Loja

Essa análise mostra o custo médio de frete por loja, permitindo verificar se o custo logístico pode impactar a margem de lucro ou a experiência do cliente.

![Valor Médio de Frete](https://raw.githubusercontent.com/Brunex-Alado/analise-dados/refs/heads/main/challenge1-data-science-main/img/Grafico5_Frete.png)

**Análise:**

- **Loja 1** Possui o melhor custo logístico, potencialmente contribuindo para sua liderança em faturamento.
- **Loja 4** Apresenta o maior custo médio de entrega.

---

## ✅ Conclusão

Baseado nos indicadores analisados: Faturamentos, Venda por Categorias, Avaliações, Venda de Produtos e frete — o Sr. João poderá tomar uma decisão mais embasada sobre qual loja vender. A combinação entre performance financeira e satisfação do cliente permite uma visão estratégica completa. A venda da loja 4 é mais indicada pela baixa performance em relação às outras lojas.

---
