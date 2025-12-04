<p align="center">
  <img src="assets/logo-vassouras.png" alt="Universidade de Vassouras" width="400"/>
</p>

<h3 align="center">
  Universidade de Vassouras  
</h3>

---

### 📚 Curso: **Engenharia de Software**  
### 🖥️ Disciplina: **Probabilidade e Estatística**  
### 👨‍🎓 Autor: **Matheus Beiruth**

---

# 🏖️ Rio Airbnb Market Analytics

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)

> Uma análise exploratória de dados (EDA) sobre o mercado de aluguel de curta temporada no Rio de Janeiro, focada em estratégias de precificação, distribuição geográfica e impacto da reputação (Superhosts).

---

## 💼 Visão Geral do Negócio

Este projeto visa auxiliar investidores e anfitriões a entenderem o cenário competitivo do Airbnb no Rio de Janeiro. Utilizando dados reais do portal [Inside Airbnb](http://insideairbnb.com/), respondemos a perguntas cruciais sobre **onde investir** e **como precificar** imóveis.

### Principais Descobertas:

* **Dominância de Mercado:** O mercado carioca é dominado por aluguéis de espaços inteiros (Apartamentos/Casas), indicando um perfil de turismo voltado para privacidade e grupos.
* **Precificação Geográfica:** A Zona Sul não é apenas turística, é o motor financeiro. Bairros como **Leblon** e **Ipanema** comandam os maiores preços medianos, enquanto oportunidades de entrada existem em regiões adjacentes.
* **Fator Superhost:** Ser um *Superhost* impacta marginalmente no preço, mas drasticamente na taxa de ocupação implícita (via número de reviews) e na nota média, sugerindo que a qualidade do serviço é um fator de conversão, não apenas de preço.

## 📓 Estrutura da Análise

O projeto foi desenvolvido em **Jupyter Notebook** e aborda as seguintes etapas do pipeline de dados:

1.  **Ingestão de Dados:** Coleta automatizada de dados brutos via URL.
2.  **Limpeza e Tratamento:**
    * Tratamento de dados monetários (conversão de strings financeiras).
    * Remoção de *outliers* de preço (filtragem estatística entre os percentis 1% e 99%).
    * Seleção de colunas relevantes para a análise.
3.  **Análise Exploratória (EDA):**
    * Distribuição de tipos de acomodação.
    * Ranking de bairros por valor mediano.
    * Correlação entre avaliações e preço.

## 📊 Visualizações Chave

*(Sugestão: Salve as imagens geradas no notebook e coloque aqui. Exemplo abaixo)*

| Distribuição de Imóveis | Preço por Bairro (Top 15) |
|:---:|:---:|
| *[Insira o gráfico de pizza/barra aqui]* | *[Insira o gráfico de barras horizontais aqui]* |

## 🛠️ Como Reproduzir

### Pré-requisitos
Você precisará de Python 3 e das bibliotecas listadas em `requirements.txt`.

1. **Clone o repositório**
   ```bash
   git clone [https://github.com/BeiruthDEV/rio-airbnb-pricing-analytics.git](https://github.com/BeiruthDEV/rio-airbnb-pricing-analytics.git)
   cd rio-airbnb-pricing-analytics
---

2. **Instale as dependências
   ```bash
   pip install -r requirements.txt
   ```
3. **Execute o Jupyter Notebook
   ```bash
   jupyter notebook notebooks/Rio_Market_Analysis.ipynb
   ```


## 📂 Fonte dos Dados
Os dados utilizados referem-se ao snapshot de 24/06/2025 da cidade do Rio de Janeiro, disponibilizados publicamente pelo Inside Airbnb.

## Autor
Matheus Beiruth

