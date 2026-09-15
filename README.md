# 📊 Dashboard de Produção — Power BI

Dashboard desenvolvido durante o **curso de Power BI do SENAI**, com o objetivo de consolidar e visualizar indicadores de produção industrial a partir de uma base de apontamentos.

##  Sobre os dados

A base utilizada possui mais de **31 mil registros** de apontamentos de produção, contendo informações como:

- **31 operadores**
- **447 produtos diferentes**
- Período de **janeiro de 2021 a janeiro de 2022**
- Ocorrências relacionadas a falhas de equipamento, peças danificadas, manutenção, erros de projeto, entre outras situações.

##  O que o dashboard apresenta

### Indicadores

- **Quantidade Produzida**
- **Quantidade Rejeitada**
- **Horas Produtivas**
- **Horas Paradas**

### Gráficos e análises

- **Produção mensal:** evolução da quantidade produzida ao longo do período, com os meses apresentados em ordem cronológica.
- **% Produtividade:** indicador calculado utilizando medida DAX para representar o percentual de produtividade no período.
- **% Qualidade:** indicador calculado pela fórmula:

  `(% Qualidade) = (Quantidade Produzida − Quantidade Rejeitada) ÷ Quantidade Produzida`

### Filtros

O dashboard possui filtros dinâmicos para análise por:

- **Operador**
- **Mês**

##  Principais aprendizados

Durante o desenvolvimento do projeto, foram praticados conceitos como:

- Criação e utilização de **medidas DAX**
- Utilização de **Medidas Rápidas (Quick Measures)**
- Ajuste manual de fórmulas DAX geradas pelo Power BI
- Configuração de **gráficos e indicadores (Gauge)**
- Definição de valores mínimos e máximos em indicadores percentuais
- **Ordenação personalizada de campos de texto**, utilizando uma coluna auxiliar numérica e o recurso **Classificar por Coluna**
- Criação de filtros e interação entre os elementos do dashboard
- Organização e apresentação visual de indicadores de produção

##  Ferramentas utilizadas

- **Power BI Desktop**
- **DAX**

##  Autor

**Henrique Jesus Amorim da Cruz**

Projeto desenvolvido como parte do **curso de Power BI do SENAI**.
