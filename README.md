# dados-de-empregados
O conjunto de dados é o <a href="https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset"> employee dataset</a>, extraído do Kaggle.

Respondendo 5 perguntas de negócios 

1. Qual é a distribuição das qualificações educacionais entre os funcionários?
2. Como o tempo de serviço (Ano de Adesão) varia entre as diferentes cidades?
3. Existe uma correlação entre Nível de Pagamento e Experiência no Domínio Atual?
4. Qual é a distribuição de gênero dentro da força de trabalho?
5. Há algum padrão no comportamento de afastamento entre os funcionários?

Para responder a essas perguntas vou usar estatística descritiva e visualizações gráficas com o auxílio de:
* maptplotlib, seaborn, plotly - para gráficos
* matriz de correlação

Também vou criar modelos de machine learning para prever o comportamento de afastamento (se o funcionário ficará ou sairá da empresa) com base em várias características, como educação, idade, experiência etc
Os algoritos de machine learning que vão ser usados para classificação:
-> Regressão Logística
-> Random Forest
-> Gradient Boosting
-> XGBoosting

Vou usar a validação cruzada (cross-validation) para avaliar o desempenho dos modelos de machine learning de maneira mais robusta. A validação cruzada é uma técnica importante
para estimar a capacidade de generalização de um modelo e reduzir o risco de overfitting ou subajuste.

Por fim, vou exibir um quadro comparativo dos modelos e ver qual teve melhor desempenho.
