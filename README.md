# 🏠 Projeto de Insights: Recomendação de Imóveis sem o uso de Machine Learning

---

📄 **Artigo completo no Medium:**  
[Projeto de Insights: Recomendação de imóveis sem o uso de Machine Learning](https://medium.com/@brenorupf/projeto-de-insights-recomenda%C3%A7%C3%A3o-de-im%C3%B3veis-sem-o-uso-de-machine-learning-94a96626cab8)


---

## 📘 Descrição Geral

Este projeto foi desenvolvido como parte de um desafio proposto pelo blog **“Seja um Data Scientist”**, com o objetivo de gerar **insights de negócio sem o uso de Machine Learning**.

A análise simula o papel de um **Data Scientist da empresa fictícia “House Rocket”**, que busca identificar **as melhores oportunidades de compra e venda de imóveis** a partir de uma **análise exploratória de dados (EDA)**.  
O foco é mostrar como uma EDA bem conduzida pode gerar recomendações estratégicas — mesmo sem modelos preditivos complexos.

---

## 🎯 Objetivo do Projeto

A missão é **maximizar a receita da empresa**, respondendo a três perguntas-chave:

1. 🏘️ Quais casas o CEO da House Rocket deveria comprar e por qual preço?  
2. 💰 Qual o melhor momento para vendê-las e por quanto?  
3. 🧱 A House Rocket deveria reformar as casas? Quais mudanças fariam sentido e qual seria o impacto no preço?

---

## 🧩 Fonte dos Dados

Os dados foram obtidos do **Kaggle**, e se referem a imóveis vendidos no **Condado de King (EUA)** — região de Seattle — entre **maio de 2014 e maio de 2015**.

📦 **Dataset original:**  
[House Sales in King County, USA – Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

---

## 🧠 Metodologia e Etapas

1. **Entendimento do problema** e definição das métricas de sucesso.  
2. **Limpeza e tratamento dos dados**:
   - Correção de erros (ex: imóveis com 33 quartos, imóveis com 0 banheiros/quartos).  
   - Criação de variáveis de data (ano, mês, dia, estação).  
3. **Análise exploratória (EDA):**
   - Identificação de variáveis com maior correlação com `price`.  
   - Avaliação do impacto de variáveis como `sqft_living`, `bathrooms`, `bedrooms`, `grade`, `view`, `condition` e `zipcode`.  
4. **Geração de insights acionáveis**:
   - Faixas ideais de metragem, número de quartos e banheiros.  
   - Cidades e regiões mais valorizadas.  
   - Impacto das reformas e época ideal de venda.  
5. **Seleção final de imóveis**:
   - Filtros baseados em correlação e características de valorização.  
   - Sugestão de preços de compra e venda, considerando margem de negociação.

---

## 📊 Principais Descobertas

- Imóveis com maior metragem interior (`sqft_living`) possuem forte correlação com o preço.  
- Casas reformadas são, em média, **19% mais caras** do que as não reformadas.  
- Imóveis com **4 a 6 quartos** são os mais valorizados.  
- O **melhor momento para vender** é na **primavera (março a maio)**.  
- O **Zip Code 98039 (Medina)** concentra as propriedades mais caras do condado.  
- Reformas com adição de **um quarto e um banheiro** geram incrementos expressivos no valor médio.

---

## 🧾 Ferramentas Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn  
- **Ambiente:** Google Colab  
- **Fonte de Dados:** Kaggle  
- **Documentação:** Markdown  
- **Versionamento:** Git e GitHub  

---

## 💡 Conclusões e Recomendações

A análise demonstrou que:
- É possível gerar recomendações robustas **apenas com EDA**, sem Machine Learning.  
- O uso inteligente de variáveis de correlação e geográficas pode sustentar decisões de compra.  
- Reformas e o momento de venda são fatores críticos para maximizar lucro.  

---
