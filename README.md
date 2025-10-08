## Problema de Negócio

A área de logística de uma empresa automotiva enfrentava desafios na otimização da
eficiência operacional e na melhoria da satisfação dos clientes. O processo de acompanhamento de entregas e custos era fragmentado, dificultando a análise de
desempenho e a tomada de decisões estratégicas. Havia necessidade de uma solução
visual e analítica para integrar informações de transporte, custos e performance das
transportadoras contratadas.

## Contexto

A empresa realiza reuniões mensais com as transportadoras e necessitava de uma visão
consolidada e interativa que permitisse a análise de rotas, desempenho de transporte,
custos e uso da frota. O objetivo principal foi desenvolver um dashboard em Power BI que possibilitasse o monitoramento de KPIs logísticos em tempo real.

## Premissas da análise

Os dados utilizados representam informações simuladas de transporte. - As métricas
seguem o padrão de acompanhamento logístico, considerando peso, cubagem, tipo de
veículo e OTD (On Time Delivery).

As transportadoras foram avaliadas de forma consolidada, considerando o período de janeiro de 2022 a agosto de 2023.

## Estratégia da solução

Foi desenvolvido um dashboard interativo em Power BI, com foco na análise descritiva e exploratória dos dados de transporte. A modelagem de dados foi estruturada com base em uma tabela fato de viagens e tabelas dimensão de veículos, regiões e
transportadoras. Os principais indicadores foram representados em gráficos e cartões que permitem o acompanhamento rápido da performance logística.

## Passo 1: Como a empresa pode melhorar sua eficiência operacional e reduzir custos de transporte por meio da análise dos dados logísticos?

<img width="1165" height="648" alt="Image" src="https://github.com/user-attachments/assets/735fb500-c204-4bc2-b53e-5d22a94e9b8b" />

Dashboard Logística, que consolida os principais indicadores de desempenho da operação de transporte, como On Time Delivery (OTD), custo total de transporte, número de viagens, cubagem, peso movimentado, além de análises por região, tipo de veículo e valor do frete ao longo do tempo.

## Passo 2: Qual é o percentual de entregas dentro do prazo (OTD) e como ele varia por região, tipo de transporte e período?

<img width="246" height="240" alt="Image" src="https://github.com/user-attachments/assets/688007d0-4f44-465f-aca1-483a1305d018" />

O OTD é o principal indicador de desempenho operacional na logística, pois mede a pontualidade das entregas. O resultado atual de 70,92% demonstra que, embora a maioria das entregas ocorra no prazo, há espaço significativo para melhoria nos processos de planejamento e execução de transporte.

Este KPI é essencial para avaliar a satisfação do cliente e a confiabilidade das transportadoras. Um OTD abaixo da meta impacta diretamente a reputação e pode gerar custos adicionais, como retrabalho e multas contratuais.

## Passo 3: Fato principal: Viagens realizadas, Valor do frete, peso, cubagem, OTD, custo total de transporte.

<img width="282" height="289" alt="Image" src="https://github.com/user-attachments/assets/ebfd87df-f5f7-48a0-99ac-abfa524ec4f0" />

Custo Total de Transporte 

KPI: R$ 40,1 milhões
 
Representa o valor total gasto com fretes no período analisado. Esse dado é crucial para mensurar a eficiência financeira e avaliar o custo-benefício de diferentes transportadoras, tipos de veículos e rotas.
Permite identificar oportunidades de redução de custos, otimizando contratos e negociações. Acompanhá-lo junto ao OTD possibilita avaliar se o investimento em transporte está alinhado à performance operacional. 

Total de Viagens 

KPI: 8.362 viagens realizadas 

Esse indicador reflete o volume de operações logísticas no período. O acompanhamento é importante para entender a demanda de transporte, sazonalidade e capacidade da frota.
O número de viagens, em conjunto com peso e cubagem, permite avaliar a eficiência na utilização da frota e a produtividade das transportadoras contratadas. 

Cubagem (m³) 

KPI: 251,60 mil m³ transportados 

A cubagem expressa o volume total ocupado pelas cargas, sendo determinante para a otimização do espaço disponível nos veículos. Esse KPI auxilia na análise de planejamento logístico e dimensionamento da frota, garantindo o uso adequado dos recursos e redução de custos com viagens ociosas. 

Peso (kg) 

KPI: 53 milhões de kg transportados 

O peso total movimentado complementa a análise de cubagem, ajudando a entender o tipo de carga predominante e o impacto sobre o consumo de combustível e manutenção dos veículos. Permite calcular a eficiência energética e estimar o custo operacional por tonelada transportada


## Passo 4: Dimensões: Transportadora, Tipo de Veículo, Região, Data e Tipo de Transporte.

<img width="248" height="277" alt="Image" src="https://github.com/user-attachments/assets/335eb1b1-fa66-4a38-8ba2-f229e43bd5af" />

O uso predominante de trucks (caminhões médios) mostra um equilíbrio entre capacidade e custo operacional. Analisar essa distribuição ajuda na otimização da frota, permitindo ajustar a alocação dos veículos conforme o perfil de carga e as rotas mais frequentes.

<img width="285" height="257" alt="Image" src="https://github.com/user-attachments/assets/c5c3eb2f-1036-40e3-93f5-e7612e77229d" />

As melhores performances foram observadas em SP (72,54%), RN (72,32%) e MG (71,23%), enquanto SC (67,81%) e CE (68,46%) apresentaram os menores índices. Esse KPI é essencial para identificar variações regionais de desempenho, permitindo ações direcionadas, como revisão de rotas, troca de transportadoras ou melhoria no planejamento logístico local.

<img width="286" height="518" alt="Image" src="https://github.com/user-attachments/assets/e69951b8-76c2-4e4b-aa3a-01733dd83ad1" />

O mapa exibe a distribuição geográfica das entregas, facilitando a identificação das rotas mais utilizadas e das regiões com maior concentração de demandas. Ferramenta fundamental para analisar cobertura logística, planejar expansão e identificar gargalos regionais.

<img width="565" height="245" alt="Image" src="https://github.com/user-attachments/assets/baae84b8-6c31-4adc-8112-9e140eb4fcbd" />

O gráfico temporal permite observar oscilações nos custos de frete, evidenciando períodos de aumento (possivelmente por sazonalidade ou reajuste de combustíveis). Importante para ajustar estratégias de negociação e previsão orçamentária, além de auxiliar na compreensão de tendências de mercado.

## Passo 5: Hipóteses Analíticas

1. O desempenho logístico (OTD) varia conforme a região. 
2. O tipo de veículo impacta ocusto médio do frete. 
3. O volume transportado influencia diretamente o custo total. 
4. Regiões com maior número de entregas apresentam menor OTD. 
5. A evolução do valor do frete acompanha as oscilações sazonais do mercado.

## Critérios de Priorização

Foram priorizadas hipóteses com maior impacto financeiro e operacional, especialmente as relacionadas à eficiência de entrega e custos logísticos.

## Priorização das Hipóteses Analíticas

1. Avaliar o OTD por região. 
2. Analisar o custo médio por tipo de veículo. 
3. Relacionar
volume (peso e cubagem) com custos. 
4. Monitorar a evolução temporal do valor do frete.

## Insights da análise

O índice de entregas dentro do prazo (OTD) atingiu 70,92%, ficando 11,35% abaixo da
meta estabelecida (80%). - O tipo de veículo mais utilizado foi o Truck, responsável por
cerca de 5 mil viagens. - As regiões SP, MG e PR apresentaram melhor desempenho no
cumprimento de prazos. - O custo total de transporte foi de aproximadamente R$ 40,1
milhões, com peso total de 53 mil kg e cubagem de 251,60 m³.

## Resultados

O dashboard permitiu consolidar as informações logísticas de forma visual e dinâmica,
otimizando o processo de análise e suporte à decisão. Com ele, os gestores podem
monitorar indicadores de performance, identificar gargalos e propor melhorias nas rotas e gestão de transportadoras.

## Visualização e Análise Completa

A visualização final apresenta KPIs estratégicos, gráficos de evolução temporal, mapa
logístico interativo e comparativos de performance por região e tipo de veículo. Este
projeto demonstra a aplicação prática do Power BI em contextos empresariais de logística e transporte.
