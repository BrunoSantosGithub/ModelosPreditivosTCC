# Modelos Preditivos - TCC

🔍 **Descrição do Projeto<br/>**
<br/>
Trabalho de conclusão de curso do Bacharelado em Sistemas de Informação, cujo objetivo foi desenvolver e comparar modelos de aprendizado de máquina para prever o desfecho clínico (alta ou óbito) de pacientes internados em uma UTI do estado do Rio de Janeiro. Utilizando dados clínicos coletados no momento da internação e 24 horas após, foram aplicados algoritmos como Regressão Logística, Naive Bayes, SVM, KNN, Árvore de Decisão, Random Forest e XGBoost, com otimização por Grid Search e validação cruzada k-fold. Os dados passaram por etapas de pré-processamento (limpeza, imputação, codificação com OneHotEncoder e normalização com StandardScaler), e foram divididos estratificadamente em treino e teste. A avaliação foi conduzida por métricas como AUC-ROC, F1-score, sensibilidade, precisão e acurácia. <br/>
<br/>

📊 **Etapas do Projeto<br/>**
* Extração de Dados: Coleta dos dados por meio de uma API em Python com requisições HTTP POST ao banco de dados do projeto, resultando em um dataset estruturado.<br/>
* Análise Exploratória e Pré-processamento: Utilização da plataforma Anaconda para limpeza dos dados, imputação de valores ausentes, codificação (OneHotEncoder) e normalização (StandardScaler), além de análises iniciais.<br/>
* Divisão dos Dados: Separação estratificada dos dados em conjuntos de treino e teste, garantindo a representatividade dos desfechos.<br/>
* Desenvolvimento dos Modelos: Preditivos Aplicação e comparação de algoritmos como Regressão Logística, Naive Bayes, SVM, KNN, Árvore de Decisão, Random Forest e XGBoost.<br/>
* Otimização de Hiperparâmetros: Ajuste dos modelos usando Grid Search aliado à validação cruzada k-fold.<br/>
* Avaliação de Desempenho: Métricas de classificação binária utilizadas: AUC-ROC, F1-score, sensibilidade, precisão e acurácia.<br/>
<br/>

🚀 **Tecnologias utilizadas<br/>**
* Linguagem: Python
* Principais Bibliotecas: Pandas, NumPy, Seaborn, Matplotlib e Scikit-Learn.
* Modelos de Machine Learning: Regressão Logística, Random Forest, Naive Bayes, KNN, SVM, XGBoost.
<br/>

📁 **Organização dos Notebooks<br/>**

O repositório está estruturado com os notebooks principais localizados na pasta notebooks/, organizados por etapas do projeto:
* Análise Exploratória.ipynb: Responsável pela investigação inicial dos dados, geração de estatísticas descritivas, visualizações das variáveis clínicas e aplicação dos tratamentos necessários. Este notebook também gera o dataset final já tratado e pronto para uso nos modelos preditivos.
* 1° Modelo Preditivo.ipynb: Implementa o primeiro modelo de aprendizado de máquina com base nos dados coletados no momento da internação. Inclui testes de algoritmos, ajustes iniciais e validação cruzada.
* 2° Modelo Preditivo.ipynb: Desenvolve o segundo modelo de aprendizado de máquina, utilizando os dados atualizados 24 horas após a internação. Também contempla testes de algoritmos, ajustes de parâmetros e validação cruzada.
Além dos notebooks, o repositório inclui gráficos salvos em formato de imagem (.png) gerados durante a análise exploratória e o tratamento dos dados, com o objetivo de documentar visualmente os principais achados do pré-processamento.
