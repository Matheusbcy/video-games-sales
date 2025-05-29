# 🎮 Video Game Sales

Projeto de análise de dados baseado em um conjunto de dados de vendas de jogos eletrônicos em diferentes regiões do mundo. Utiliza Python, pandas, matplotlib e seaborn para explorar, visualizar e tratar os dados.

---

## 📁 Sobre o dataset

O arquivo `VideoGamesSales.csv` contém informações sobre vendas globais de jogos, com as seguintes colunas:

- `Name`: Nome do jogo  
- `Platform`: Plataforma (ex: PS4, Xbox, etc.)  
- `Year`: Ano de lançamento  
- `Genre`: Gênero (ex: Action, Sports)  
- `Publisher`: Publicadora  
- `NA_Sales`: Vendas na América do Norte (em milhões)  
- `EU_Sales`: Vendas na Europa (em milhões)  
- `JP_Sales`: Vendas no Japão (em milhões)  
- `Other_Sales`: Outras regiões  
- `Global_Sales`: Vendas globais (soma das anteriores)

---

## 📌 Objetivos do projeto

- Carregar e limpar os dados
- Padronizar valores categóricos
- Tratar valores ausentes e **outliers**
- Analisar tendências de vendas por região
- Criar **gráficos de barras** e outras visualizações
- Explorar relações entre gênero, plataforma e desempenho em vendas

---

## 🛠️ Tecnologias usadas

- Python 3
- pandas
- matplotlib
- seaborn
- Jupyter Notebook (opcional)

---

## 📊 Exemplos de análises realizadas

- Gêneros com maior desempenho em vendas globais
- Análise de outliers usando percentis (ex: `quantile(0.95)`)

---

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/video-game-sales.git
   cd video-game-sales
2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
3. Execute o notebook ou script principal:
    ```bash
    video_game_sales.ipynb (notebook)

## 📂 Estrutura do projeto

```
video-game-sales/
├── VideoGamesSales.csv
├── video_game_sales.ipynb
├── README.md
└── requirements.txt

```
## ✍️ Autor

Matheus – Estudante de Análise e Desenvolvimento de Sistemas com foco em Ciência de Dados
