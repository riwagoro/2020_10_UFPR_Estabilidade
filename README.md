# 2020_10_UFPR_Estabilidade

Análise preditiva em testes de estabilidade dentro do desenvolvimento de produtos no setor de cosméticos

Autor:
Ricardo Iwagoro, riwagoro@gmail.com
Walmes Zeviani, Professor do Departamento de Estatística - DEST/UFPR, walmes@ufpr.br

A realização de teste de estabilidade é uma etapa essencial no desenvolvimento e comercialização de produtos. É responsabilidade da empresa a seguridade do teste e cabe a Anvisa a fiscalização. Cada componente, variáveis extrínsecas ou intrínsecas podem afetar a estabilidade de umproduto. Os testes seguem um protocolo e recomendações conforme o Guia de Estabilidade de Produtos Cosméticos - Anvisa (1) e devem seguir determinadas condições de armazenamento, parâmetros de avaliação e periodicidade. O objetivo deste trabalho é encontrar umametodologia de aprendizado demáquina que possibilite predizer com um bom nível de acurácia se o estudo sofrerá alteração ou não ao final da avaliação t90. O presente estudo teve início com a criação de um banco de dados relacional, agrupando dados de duas tabelas. Foram aplicados os modelos de Naive Bayes, Regressão logística com regularização(GLM) e Support vector machine. Como métrica de avaliação foi utilizada amatriz de confusão, acurácia e especificidade. Foram gerados 5 dataframes conforme a FAMILIA que o estudo pertence e suas características. O modelo com melhor desempenho foi o GLM, utilizando kfold = 10 com uma acuráciamédia entre as FAMILIAS de 92%.

Palavras-chave: ANVISA, CRISP-DM, classificação supervisionada, caret, GLM, Naive Bayes, SVM, matriz de confusão, acurácia, especificidade, varImp, linguagem R.
