# Análise Exploratória de Dados: Renda e Perfil dos Indivíduos

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em um conjunto de dados contendo informações socioeconômicas e demográficas de indivíduos. A análise foca em identificar padrões, correlações e distribuições na variável renda, bem como sua relação com outras variáveis como tempo de emprego, quantidade de filhos, idade, entre outras.

Ferramentas e Bibliotecas
Python 
Pandas
NumPy
Seaborn
Matplotlib

Etapas Realizadas
1. Limpeza dos Dados
Remoção de valores ausentes (NaN) com dropna.

2. Seleção de Variáveis Quantitativas
Seleção das colunas numéricas relevantes para a análise:
posse_de_veiculo, posse_de_imovel, qtd_filhos, idade, tempo_emprego, qt_pessoas_residencia, renda.

3. Visualização com Pairplot
Gráfico de dispersão múltipla (pairplot) para observar relações entre todas as variáveis quantitativas.

4. Matriz de Correlação + Heatmap
Cálculo da correlação entre variáveis com corr().

Visualização com heatmap.

5. Gráficos de Dispersão com Linha de Tendência
Relações entre:

Quantidade de filhos × Renda

Tempo de emprego × Renda

Regressão linear com numpy.polyfit para indicar tendência.

6. Análise da Distribuição da Renda
Criação de faixas de renda com pd.cut.

Gráficos de barras com frequências e boxplots para entender a variação da renda em cada grupo.

7. Transformação Logarítmica da Renda
Aplicação da transformação logarítmica para normalizar a variável renda.

Comparação das distribuições antes e depois da transformação com histogramas e boxplots.

