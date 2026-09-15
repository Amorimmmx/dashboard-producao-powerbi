Dashboard de Produção — Power BI

Dashboard desenvolvido durante o curso de Power BI do SENAI, com o objetivo de consolidar indicadores de produção industrial a partir de uma base de apontamentos.

Sobre os dados

A base utilizada contém mais de 31 mil registros de apontamentos de produção, incluindo:

31 operadores
447 produtos diferentes
Período de janeiro/2021 a janeiro/2022
Ocorrências como falha de equipamento, peça danificada, manutenção, erro de projeto, entre outras
O que o dashboard mostra
Cartões de indicadores: Quantidade Produzida, Quantidade Rejeitada, Horas Produtivas e Horas Paradas
Gráfico de produção mensal: evolução da quantidade produzida ao longo do ano, ordenado cronologicamente (janeiro a dezembro)
% Produtividade: medida DAX que indica o percentual de produtividade no período
% Qualidade: medida DAX calculada como (Qtd Produzida − Qtd Rejeitada) ÷ Qtd Produzida
Filtros dinâmicos: por Operador e por Mês
Principais aprendizados técnicos
Ordenação customizada de campos de texto no eixo do gráfico (criação de coluna auxiliar numérica + "Classificar por Coluna"), já que o Power BI ordena texto em ordem alfabética por padrão
Criação de medidas rápidas (quick measures) em DAX e ajuste manual da fórmula gerada
Configuração de visuais do tipo gauge (indicador) com valores mínimo/máximo em porcentagem
Ferramentas utilizadas
Power BI Desktop
DAX
Autor

Desenvolvido por Henrique como parte do curso de Power BI do SENAI.
