# Bootecamp Alura Data Science

## Módulo 1: Analisando dados da saúde com Python e Pandas
Seleção dos dados no DATASUS (https://datasus.saude.gov.br/) utilizando o tabnet (https://datasus.saude.gov.br/informacoes-de-saude-tabnet/) referente aos custos de assistência a saúde para tratamento e visualização dos dados. No desafio do módulo foi constatado que região Sul do Brasil possui a maior média de gastos em saúde por internação no período estudado.

![alt text](https://github.com/MarcosRMG/Bootecamp-Alura-Data-Science/blob/main/img/custo_medio_internacao.png)

## Módulo 2: Visualização de dados com Seaborn e Matplotlib
Seleção dos dados no DATASUS (https://datasus.saude.gov.br/) utilizando o tabnet (https://datasus.saude.gov.br/informacoes-de-saude-tabnet/) referente a cobertura de imunização. No desafio do módulo foi constataddo tendência de queda da imunização no Brasil. 

![alt text](https://github.com/MarcosRMG/Bootecamp-Alura-Data-Science/blob/main/img/queda_vacinal.png)

## Módulo 3: Estatística com Python para análise de dados
Por meio dos dados da Pesquisa Nacional de Saúde do Escolar - PeNSE 2015 foram estudados os conceitos de análise descritiva e testes estatísticos, por meio de ferramentas como tabela de frequência, cruzamento de dados com o Pandas Crosstab, histogramas e boxplots, medidas de centralildade e dispersão e intervalo de confiança e testes estatísticos. No projeto do módulo estudei os resultados da amostra 1 e 2 da pesquisa PeNSE 2015, dentre os resultados foi constatado que para a mostra 1 a gravidez influencia na pretensão do grau de escolaridade da estudante. 

![alt_text](https://github.com/MarcosRMG/Bootecamp-Alura-Data-Science/blob/main/img/engravidaram.png)

![alt_text](https://github.com/MarcosRMG/Bootecamp-Alura-Data-Science/blob/main/img/nao_engravidaram.png)

P-value é menor do que 0.05, logo a hipótese nula (ambas as distribuições são iguais) deve ser rejeitada, deste modo a distribuição da pretensão de escolaridade das estudantes que já engravidaram alguma vez e das que nunca engravidaram são diferentes.

Estatisticamente a gravidez altera a pretensão do grau de escolaridade para a amostra 1 (PeNSE, 2015).

## Módulo 5: Análise de séries temporais

Neste módulo foram estudados conceitos necessários para análise de série temporal, como a tendência da série, sazonalidade e ruído, estacionariedade e modelos de previsão de série temporal. 

![alt_text](https://github.com/MarcosRMG/Bootcamp-Alura-Data-Science/blob/main/img/prophet.png)

Analisando o número de casos e óbitos por COVID-19 no Brasil foi possível perceber que o modelo de previsão Prophet foi o que melhor se ajustou a série e consequentemente melhor previu dados futuros. 
