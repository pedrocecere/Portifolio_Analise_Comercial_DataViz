# Análise Comercial - Pinsky Modas

<img src="imagens/sinais-de-desconto-da-sexta-feira-negra-em-uma-loja-de-roupas-grandes-poupancas-esperam-nao-perca-o-incrivel_996993-103818.jpg" alt="Capa do README" width="1000" />


## 1. Descrição do projeto

Este projeto busca transformar a forma como a Pinsky Modas, uma loja de departamento de vestuário, entende e gerencia seu desempenho comercial. O foco é trazer clareza para os desafios diários, oferecendo uma visão completa das vendas, metas e performance de produtos. Usando o Power BI para criar dashboards interativos e intuitivos, pretendemos fornecer as ferramentas certas para facilitar decisões rápidas e bem informadas, além de ajudar a equipe a definir estratégias mais eficazes.

A ideia é ir além dos números, capturando os detalhes que realmente fazem a diferença: entender como as vendas evoluem mês a mês, identificar padrões ou oscilações e perceber quais produtos têm um desempenho que se destaca ou precisa de atenção. E, claro, olhar para as equipes – do gerente ao vendedor – e acompanhar se as metas estão sendo atingidas, onde estão as oportunidades de crescimento e como motivar o time a alcançar resultados ainda melhores.

## 2. Problema de negócio e objetivos

### 2.1 Qual o problema de negócio deste projeto?

A Pinsky Modas enfrenta um desafio crítico no acompanhamento de seus principais indicadores comerciais. Apesar de bater meta nos últimos oito meses do ano, temos uma tendência estacionária nas vendas ao longo do tempo, a loja carece de um sistema eficiente para mapear e monitorar os KPIs essenciais que direcionam o negócio. A falta de uma visão consolidada dificulta a identificação de padrões e a análise das causas de variações no desempenho.

Em resposta a essa necessidade, foi solicitado um dashboard que permita um monitoramento contínuo e detalhado desses indicadores. A ideia é fornecer uma ferramenta que centralize as informações de receita, desempenho das equipes e vendas por produto, facilitando a gestão e permitindo decisões mais rápidas e informadas para alavancar os resultados.

### 2.2 Quais são os conceitos importantes a conhecer no contexto de comercial analisado?

Para entender os indicadores analisados no projeto, é essencial conhecer alguns conceitos fundamentais:

**Conceitos Importantes:**
- **Faturamento:** Refere-se ao total gerado com as vendas, após deduzir descontos, devoluções e taxas aplicáveis. É um indicador chave para medir o desempenho financeiro da loja.
- **Ticket Médio:** Representa o valor médio gasto pelos clientes em cada transação. É calculado dividindo o faturamento total pelo número de vendas realizadas no período analisado, ajudando a identificar tendências de consumo e oportunidades para aumentar o valor médio das compras.
- **Margem Bruta:** Percentual que indica quanto a loja ganha sobre o preço de custo dos produtos vendidos. Calcula-se subtraindo o custo das mercadorias vendidas do faturamento e dividindo o resultado pelo faturamento, expressando a lucratividade antes das despesas operacionais.
- **Faturamento YoY:** Compara o faturamento de um período com o mesmo período do ano anterior. É utilizado para avaliar o crescimento ou declínio das vendas em relação ao ano passado, oferecendo uma visão clara das tendências e sazonalidades.
  
## 3. Pipeline de solução

- **Entendendo o problema de negócio:** Inicialmente, foi realizada uma análise aprofundada para identificar os principais desafios enfrentados pela Pinsky Modas e definir os objetivos que a solução deveria alcançar. Embora as metas mensais tenham sido atingidas na maior parte do ano, observou-se uma tendência estacionária na receita. Nesta etapa, o foco foi entender quais seriam as principais alavancas no setor comercial de vestuário que poderiam impulsionar o crescimento da receita anual, explorando oportunidades para otimizar o desempenho e superar essa estagnação.
- **Preparação e limpeza dos dados:** Os dados foram extraídos da fonte fornecida pela empresa e passaram por um rigoroso processo de tratamento para garantir sua consistência e qualidade. Essa etapa incluiu a remoção de registros duplicados, o tratamento de valores ausentes e a padronização de formatos. Além disso, variáveis adicionais foram criadas quando necessário.
- **Modelagem de Dados:** A modelagem dos dados foi realizada inteiramente no Power Query, onde foram criadas tabelas, realizadas junções e aplicadas regras de negócio específicas. Esse processo garantiu que os dados estivessem estruturados de forma adequada para análises subsequentes.
- **Análise exploratória dos dados:** Os dados disponíveis foram analisados para entender sua distribuição, tendências e possíveis anomalias. Nessa etapa, buscamos identificar padrões nas vendas, variações sazonais e outros fatores que poderiam impactar o desempenho comercial.
- **Criação dos Visuais e Indicadores:** A partir dos dados tratados e modelados, foram criados dashboards com visualizações interativas. Esses visuais abordam os principais KPIs, como faturamento, ticket médio, margens, desempenho por produto e por equipe de vendas permitindo uma análise intuitiva e detalhada.
- **Storrytelling e Apresentação aos StackHolders:** Para assegurar que os insights gerados fossem facilmente compreendidos e aproveitados, os resultados foram apresentados de maneira clara e objetiva. O dashboard foi utilizado como uma ferramenta narrativa para ilustrar o desempenho da loja, enfatizando pontos críticos e destacando oportunidades de melhoria. Atendendo à solicitação do gestor da área, o layout foi concebido em uma única tela, facilitando a visualização e a interpretação rápida das informações.

## 4. Tecnologias e ferramentas

- Power BI
- Estatística
- Power Query
- DAX
- Excel

## 5. Insights e Resultados

A análise comercial da loja de vestuário revelou resultados positivos no crescimento das receitas, mas também destacou áreas que necessitam de ajustes estratégicos para melhorar a rentabilidade. A loja apresentou um crescimento de 3,7% no faturamento entre 2022 e 2023, embora a tendência da receita ao longo do período tenha se mantido estacionária, sugerindo que o aumento foi linear e sem grandes variações ao longo do tempo.

O desempenho da equipe de vendas foi positivo, com um faturamento total de R$ 1.898.013,00 e um ticket médio de R$ 1.765,59. Contudo, um ponto crítico foi a redução de 5,8% na margem bruta, o que indica uma estratégia falha na definição das metas mensais e possíveis erros na precificação dos produtos. Este fator ressalta a necessidade de revisar as políticas de preço para recuperar a margem de lucro, uma vez que o crescimento da receita não foi acompanhado por um crescimento proporcional na lucratividade.

Apesar do resultado geral positivo, a análise mais detalhada da performance individual dos vendedores revelou que cinco membros da equipe não atingiram as metas estabelecidas. Isso indica que o desempenho geral pode ser comprometido por uma parcela da equipe, o que torna fundamental o acompanhamento mais próximo e a adoção de medidas corretivas.

Para sustentar e acelerar o crescimento no futuro, recomenda-se a implementação de uma estratégia de preços dinâmica, que ajuste os valores de acordo com períodos de sazonalidade e condições de mercado, visando aumentar as margens de lucro. Além disso, campanhas de marketing mais agressivas devem ser realizadas em períodos de baixa sazonalidade, com o objetivo de aumentar o ticket médio e a frequência de compras dos clientes.

Em relação ao portfólio de produtos, os itens de alta margem, como o "Blazer Poderoso Chefão", tiveram um bom desempenho. No entanto, outros produtos com grande potencial de lucro, como "Psyco Universe" e "Klamath Weed", apresentaram vendas insatisfatórias. Esses produtos possuem margens atrativas, mas não conseguiram conquistar uma aceitação significativa no mercado. A recomendação é que a equipe de marketing promova campanhas específicas focadas nesses produtos, de modo a aumentar sua visibilidade e demanda. Além disso, personalizar as ofertas com base na segmentação de clientes pode ser uma estratégia eficaz para elevar a rentabilidade, sem depender exclusivamente de um aumento no volume de vendas.

Finalmente, é fundamental investir em treinamentos de vendas consultivas, capacitando a equipe para vender produtos de maior margem com mais eficiência. A revisão da política de descontos também se faz necessária, para garantir que não haja erosão da margem de lucro com promoções mal calibradas. Com o sistema de acompanhamento de metas individuais já implementado via dashboard, o monitoramento constante permitirá a identificação e correção de eventuais desvios na performance da equipe de vendas.

Com essas ações, a loja estará mais preparada para sustentar seu crescimento e melhorar a rentabilidade, ajustando-se às demandas do mercado e maximizando o desempenho de sua equipe e de seus produtos.

<img src="imagens/produtos.png" alt="Produtos" width="700" />

