# Credit_Card_Classification
O objetivo é treinar e avaliar o desempenho do modelo em um conjunto de dados obtido no Kaggle, especificamente na competição CDS Hackday 3.
# K-Nearest Neighbors (KNN) - Classification

## 📌 Descrição
Este é um pequeno projeto que implementa o algoritmo de K-Nearest Neighbors (KNN) para classificação de dados. O projeto está estruturado em um notebook Jupyter (`knn.ipynb`), onde é realizada a carga dos dados, a análise exploratória e a aplicação do modelo de classificação.

## 🛠 Requisitos
Para rodar este projeto, é necessário ter instalado:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (opcional, para visualizações)

Para instalar as dependências, utilize o seguinte comando:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## 📂 Estrutura do Projeto
- `knn.ipynb`: Notebook Jupyter contendo a implementação do modelo KNN.
- `train.csv`: Arquivo com os dados de treino utilizados para treinar o modelo.


## 🚀 Como Executar
1. Clone este repositório ou baixe os arquivos.
2. Abra um terminal e navegue até o diretório do projeto.
3. Execute o seguinte comando para iniciar o Jupyter Notebook:

```bash
jupyter notebook
```

4. Abra o arquivo `knn.ipynb` no Jupyter Notebook.
5. Execute as células sequencialmente para carregar os dados e rodar o modelo KNN.

## 🔍 Explicação do Algoritmo KNN
O algoritmo K-Nearest Neighbors (KNN) é um método de classificação que funciona encontrando os `k` vizinhos mais próximos de um ponto de dados e atribuindo a ele a classe mais comum entre esses vizinhos. Ele funciona em três etapas principais:
1. **Cálculo da distância** entre os pontos de dados.
2. **Seleção dos `k` vizinhos mais próximos**.
3. **Classificação** baseada na maioria das classes dos vizinhos escolhidos.

## 📊 Resultados e Avaliação
O notebook inclui:
- Carregamento e limpeza dos dados.
- Treinamento do modelo KNN.
- Avaliação do desempenho usando métricas como acurácia.
- Visualizações opcionais para melhor entendimento dos dados.


[Conjunto de Dados - Kaggle HackDays 3](https://www.kaggle.com/competitions/cdshackdays3)




