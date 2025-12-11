# 📘 ETL com API DummyJSON – Análise de Produtos

Este projeto realiza um fluxo completo de **ETL (Extract, Transform, Load)** utilizando a API pública DummyJSON, com foco em produtos. O objetivo é demonstrar conhecimento em consumo de APIs, tratamento de dados com Pandas, geração de insights e exportação dos resultados.

---

## 🔍 Etapas do Projeto

### **1. Extração (Extract)**
- Conexão com a API `https://dummyjson.com/products`
- Conversão da resposta JSON em estruturas Python
- Criação de um DataFrame base para análise

### **2. Transformação (Transform)**
- Renomeação de colunas para nomes mais claros em português  
- Cálculo do preço com desconto aplicado  
- Seleção das colunas mais relevantes  
- Geração do DataFrame tratado (`df_clean`)

### **3. Geração de Insights**
Foram calculadas métricas simples e úteis, como:
- Total de produtos  
- Preço médio sem desconto
- Preço médio com desconto  
- Categoria mais frequente  
- Produto com maior desconto  
- Produto com melhor avaliação  

### **4. Carga (Load)**
Os resultados finais são exportados em formato CSV:
- `produtos_tratados.csv`  
- `insights_produtos.csv`

---

## 🛠️ Tecnologias Utilizadas
- Python  
- Requests  
- Pandas  
- Jupyter Notebook  

---

## 📂 Arquivos Gerados
- **`notebook.ipynb`** – código completo do pipeline  
- **`produtos_tratados.csv`** – dados limpos e padronizados  
- **`insights_produtos.csv`** – métricas e análises consolidadas  

---

## ✅ Conclusão
Este projeto implementa um pipeline de ETL simples e funcional, utilizando boas práticas como modularização, docstrings, comentários relevantes e organização clara das etapas. É uma base eficiente para análises de dados provenientes de APIs públicas.

