##📦 Previsão de Estoque Inteligente com Machine Learning

Neste projeto, desenvolvi um modelo de Machine Learning para Previsão de Estoque Inteligente utilizando o Amazon SageMaker Canvas. O objetivo foi aplicar, na prática, os conceitos apresentados ao longo do conteúdo, explorando uma solução de ML sem necessidade de programação, capaz de apoiar a tomada de decisão relacionada ao controle e planejamento de estoque.

Todo o desenvolvimento seguiu o passo a passo proposto, desde a escolha do dataset até a geração e análise das previsões.

#🧭 Etapas do Desenvolvimento
#1️⃣ Seleção do Dataset

Inicialmente, naveguei até a pasta datasets deste repositório, onde estão disponíveis alguns conjuntos de dados para treinamento e teste do modelo.

Após analisar os arquivos disponíveis, escolhi um dataset adequado para o problema de previsão de estoque, contendo informações históricas como vendas, produtos, datas e quantidade em estoque. Também considerei que esses dados representam um cenário realista de operação comercial.

Em seguida, acessei o Amazon SageMaker Canvas e realizei o upload do dataset selecionado, garantindo que o arquivo fosse carregado corretamente e que todas as colunas estivessem devidamente reconhecidas pela ferramenta.

#2️⃣ Construção e Treinamento do Modelo

Com o dataset carregado no SageMaker Canvas, iniciei a criação de um novo projeto de Machine Learning.

Nessa etapa:

- Importei o dataset para o projeto;

- Configurei as variáveis de entrada, utilizando os dados históricos disponíveis (como datas, produtos e vendas);

- Defini a variável de saída, que representa a quantidade a ser prevista para o estoque/demanda futura.

Após a configuração das variáveis, iniciei o processo de treinamento do modelo. O SageMaker Canvas realizou automaticamente:

- O pré-processamento dos dados

- A seleção do algoritmo mais adequado

- O ajuste de parâmetros necessários para a previsão

O treinamento levou alguns minutos, dependendo do volume de dados utilizado.

#3️⃣ Análise do Modelo

Após a conclusão do treinamento, analisei as métricas de desempenho apresentadas pelo SageMaker Canvas, como erro médio e precisão das previsões.

Além disso, a ferramenta forneceu uma visualização das principais características que influenciaram o modelo, o que me permitiu entender melhor quais variáveis tiveram maior impacto nas previsões de estoque.

Com base nessa análise, avaliei se o desempenho do modelo era satisfatório. Quando necessário, realizei pequenos ajustes nos dados e re-treinei o modelo, buscando melhorar a qualidade das previsões.

#4️⃣ Previsão de Estoque

Com o modelo treinado e validado, utilizei o SageMaker Canvas para gerar previsões de estoque com base em novos dados.

#✅ Concluindo

A realização deste projeto permitiu aplicar, de forma prática, os conceitos de Machine Learning voltados para previsão de estoque, utilizando uma ferramenta intuitiva e acessível como o SageMaker Canvas.

O modelo desenvolvido demonstrou como dados históricos podem ser utilizados para gerar previsões úteis, contribuindo para uma gestão de estoque mais eficiente e baseada em dados.

Este projeto reforçou a importância do uso de ML como apoio à tomada de decisão e mostrou que é possível desenvolver soluções inteligentes mesmo sem conhecimento avançado em programação.
