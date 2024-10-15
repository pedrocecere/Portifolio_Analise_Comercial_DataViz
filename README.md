# Análise Comercial - Pinsky Modas

<img src="https://sennda.com.br/wp-content/uploads/2018/06/foto-loja-roupa.jpg" alt="Capa do README" width="800" />


# 1. Descrição do projeto

Este projeto busca transformar a forma como a Pinsky Modas, uma loja de departamento de vestuário, entende e gerencia seu desempenho comercial. O foco é trazer clareza para os desafios diários, oferecendo uma visão completa das vendas, metas e performance de produtos. Usando o Power BI para criar dashboards interativos e intuitivos, pretendemos fornecer as ferramentas certas para facilitar decisões rápidas e bem informadas, além de ajudar a equipe a definir estratégias mais eficazes.

A ideia é ir além dos números, capturando os detalhes que realmente fazem a diferença: entender como as vendas evoluem mês a mês, identificar padrões ou oscilações e perceber quais produtos têm um desempenho que se destaca ou precisa de atenção. E, claro, olhar para as equipes – do gerente ao vendedor – e acompanhar se as metas estão sendo atingidas, onde estão as oportunidades de crescimento e como motivar o time a alcançar resultados ainda melhores.

# 2. Problema de negócio e objetivos
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
  
# 3. Pipeline de solução

- **Entendendo o problema de negócio:** Inicialmente, foi realizada uma análise aprofundada para identificar os principais desafios enfrentados pela Pinsky Modas e definir os objetivos que a solução deveria alcançar. Embora as metas mensais tenham sido atingidas na maior parte do ano, observou-se uma tendência estacionária na receita. Nesta etapa, o foco foi entender quais seriam as principais alavancas no setor comercial de vestuário que poderiam impulsionar o crescimento da receita anual, explorando oportunidades para otimizar o desempenho e superar essa estagnação.
- **Preparação e limpeza dos dados:** Os dados foram extraídos da fonte fornecida pela empresa e passaram por um rigoroso processo de tratamento para garantir sua consistência e qualidade. Essa etapa incluiu a remoção de registros duplicados, o tratamento de valores ausentes e a padronização de formatos. Além disso, variáveis adicionais foram criadas quando necessário.
- **Modelagem de Dados:** A modelagem dos dados foi realizada inteiramente no Power Query, onde foram criadas tabelas, realizadas junções e aplicadas regras de negócio específicas. Esse processo garantiu que os dados estivessem estruturados de forma adequada para análises subsequentes.
- **Análise exploratória dos dados:** Os dados disponíveis foram analisados para entender sua distribuição, tendências e possíveis anomalias. Nessa etapa, buscamos identificar padrões nas vendas, variações sazonais e outros fatores que poderiam impactar o desempenho comercial.
- **Criação dos Visuais e Indicadores:** A partir dos dados tratados e modelados, foram criados dashboards com visualizações interativas. Esses visuais abordam os principais KPIs, como faturamento, ticket médio, margens, desempenho por produto e por equipe de vendas permitindo uma análise intuitiva e detalhada.
- **Storrytelling e Apresentação aos StackHolders:** Para assegurar que os insights gerados fossem facilmente compreendidos e aproveitados, os resultados foram apresentados de maneira clara e objetiva. O dashboard foi utilizado como uma ferramenta narrativa para ilustrar o desempenho da loja, enfatizando pontos críticos e destacando oportunidades de melhoria. Atendendo à solicitação do gestor da área, o layout foi concebido em uma única tela, facilitando a visualização e a interpretação rápida das informações.

# 4. Tecnologias e ferramentas

- Power BI
- Estatística
- Power Query
- DAX
- Excel

# 5. Insights e Resultados

- Crescimento no Faturamento:
A loja registrou um crescimento de 3,7% no faturamento e na performance em relação às metas, comparando os anos de 2022 e 2023.

- Estratégia de Precificação:
É recomendável revisar a estratégia de precificação dos produtos. Um ajuste nos preços pode aumentar a competitividade da loja no mercado, atraindo mais clientes.

- Campanhas de Marketing:
Deve-se focar em campanhas de marketing direcionadas a produtos com maior margem bruta que estão apresentando desempenho insatisfatório. A promoção adequada desses itens pode resultar em um aumento significativo nas vendas.

- Segmentação de Clientes:
Identificar e segmentar clientes com base no número de produtos comprados e suas respectivas categorias pode fornecer insights valiosos para estratégias de vendas personalizadas e aumento da fidelização.

- Treinamento de Vendedores:
Recomenda-se a realização de treinamentos ou reciclagens comerciais para cinco vendedores, que representam 41,7% do total do quadro. Esse investimento pode ser crucial para melhorar a performance geral da equipe em 2023.

- Desempenho da Equipe de Vendas:
A equipe de vendas da Pinsky Modas superou as metas em 8 meses de 2023, alcançando um faturamento total de R$ 1.898.013,00. No total, foram realizadas 1.075 vendas, resultando em um ticket médio de R$ 1.765,59. No entanto, observou-se uma perda de margem bruta de -5,8%. De modo geral, pode-se afirmar que a performance de vendas da equipe foi POSITIVA ✅ em comparação ao ano anterior.

- Tendência de Faturamento:
Apesar do crescimento em termos de metas, notou-se uma tendência estacionária no faturamento ao longo do tempo, indicando que medidas adicionais podem ser necessárias para impulsionar as vendas.

- Produto com Maior Margem Bruta:
O produto com maior margem bruta identificado foi o "Blazer Poderoso Chefão". Recomenda-se a implementação de campanhas de marketing exclusivas para impulsionar as vendas desse item, aproveitando seu desempenho financeiro favorável.

<img src="imagens/produtos.png" alt="Produtos" width="700" />

