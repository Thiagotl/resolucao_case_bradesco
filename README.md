## :telephone: Análise Customer Churn 

Este projeto realiza uma análise exploratória e descritiva de cliente com foco em **Churn** e **Satisfação (NPS)** de um empresa de serviço de telecomunicação. A baase final foi construída a partir da integração de três fontes de dados, permitindo identificar fatores associados à perda de clientes e segmentar perfis com maior risco de cancelamento.

## Resultados principais

Após a limpeza, padronização e integração das bases, a análise foi conduzida sobre uma amostra final de **7.034 clientes**.

### :white_check_mark: Os principais achados foram:

- **Churn geral de 26,6%**, indicando que aproximadamente um em cada quatro clientes cancelou o serviço;
- **NPS agregado de 7,58**, com **42,7% de promotores**, **22,2% de neutros** e **35,1% de detratores**;
- O **tempo de permanência** se mostrou um dos fatores mais importantes: clientes com **1 a 6 meses** de contrato apresentaram churn de **54,7%**, enquanto clientes com mais de **60 meses** apresentaram apenas **6,7%**;
- Clientes com **baixo NPS** apresentaram probabilidade muito maior de evasão. Entre os clientes com nota **0**, o churn foi de **88,9%**; entre os clientes com nota **10**, caiu para **2,2%**;
- Entre os fatores categóricos mais associados ao churn, destacaram-se:
  - contrato **month-to-month** (**42,7%**),
  - pagamento via **electronic check** (**45,3%**),
  - ausência de **tech support** (**41,7%**),
  - ausência de **online security** (**41,8%**),
  - clientes da categoria **SeniorCitizen** (**41,7%**);
- A relação entre **quantidade de serviços contratados** e churn indicou que clientes com maior vínculo com a empresa tendem a cancelar menos, com destaque para aqueles com **7 ou 8 serviços contratados**.

## Segmentação de clientes

Como etapa complementar, foi realizada uma análise de segmentação utilizando **PCA + K-Means**. A melhor solução encontrada foi de **3 clusters**.

### :bangbang: O grupo com maior risco apresentou: 

- **churn de 45,7%**;
- **baixo tempo médio de permanência**;
- **NPS médio mais baixo**;
- menor contratação de serviços adicionais.

Esse resultado reforça que o churn está associado a uma combinação de **baixa satisfação, pouco vínculo contratual e menor adesão a serviços de suporte e segurança**.

## Conclusão

Os resultados sugerem que ações de retenção devem priorizar:

- clientes nos primeiros meses de contrato;
- clientes com NPS baixo;
- contratos mensais;
- clientes com menor adesão a serviços complementares;
- perfis identificados no cluster de maior risco.

Esse projeto demonstra habilidades em **limpeza de dados, integração de bases, análise exploratória, geração de indicadores de negócio, segmentação de clientes e tradução de resultados em recomendações estratégicas**.