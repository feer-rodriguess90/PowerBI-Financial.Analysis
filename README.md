
# 📊 Power BI Sales Dashboard 📈 
## Bootcamp DIO e NTT DATA - Engenharia de Dados com Python  

Este repositório contém um projeto desenvolvido durante o Bootcamp de Engenharia de Dados com Python promovido pela DIO e NTT Data. O objetivo do projeto é criar um dashboard em Power BI para análise de dados de vendas usando dados de exemplo do Power BI.

## ✍🏼 Descrição do Projeto
O projeto consiste na criação de três relatórios de vendas distintos com o objetivo de fornecer insights detalhados sobre produtos, segmentos, países e lucro. Cada relatório apresenta diferentes visualizações e métricas para facilitar a análise de dados e a tomada de decisões.

### Relatório 1: Vendas por Produto e Segmento
- **Gráfico de Pizza:** Exibe a soma de vendas por produto.
- **Gráfico de Área:** Mostra a média de lucro por produto.
- **Gráfico de Barras:** Representa a soma de vendas por ano, mês e segmento.
- **Filtros:** Possibilidade de segmentar os dados por ano e mês para análise personalizada.

![Relatorio_1](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/Relatorio_1.png)

### Relatório 2: Vendas e Lucro por País
- **Cartão 1:** Soma de vendas totais.
- **Cartão 2:** Total de unidades vendidas.
- **Gráfico de Pizza:** Lucro total por país.
- **Gráfico de Barras 1:** Soma de lucro por ano e mês.
- **Gráfico de Barras 2:** Soma de vendas por país.

![Relatorio_2](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/Relatorio_2.png)

### Relatório 3: Visualizações Geográficas
- **Mapa 1:** Soma de vendas e unidades vendidas por país.
- **Mapa 2:** Soma de lucro por país.
- **Gráfico de Pizza:** Lucro por segmento.

![Relatorio_3](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/Relatorio_3.png)

## 🛠 Tecnologias Utilizadas
- **Power BI:** Ferramenta principal para a construção dos relatórios e dashboards.
- **Dados de Exemplo do Power BI:** Base de dados utilizada para a análise de vendas.
- **Python (opcional):** Possibilidade de integração futura para manipulação e limpeza de dados antes da visualização no Power BI.

## ⚙ Como Usar
1. Faça o download ou clone este repositório.
2. Abra o arquivo `.pbix` no Power BI Desktop.
3. Explore os relatórios de vendas utilizando os filtros e visualizações disponíveis.

## 🎯 Resultados Esperados
Este dashboard permite que os usuários obtenham insights valiosos sobre o desempenho de vendas em diferentes segmentos e regiões, além de facilitar a identificação de tendências de vendas e lucros.

# 👩🏽‍💻 *DESAFIO Parte II - Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX*

## Processo de Criação das Tabelas
Essa parte do desafio abrange a criação de tabelas usando Power BI a partir de um tabela de origem. Além da criação da tabela calendário usando `DAX`. As tabelas criadas incluem:

- D_Produtos: Contém dados como ID do produto, nome, média de unidades vendidas, média e mediana do valor de vendas, e valores máximo e mínimo de venda.
- D_Produtos_Detalhes: Contém o ID do produto, faixa de desconto, preço de venda, unidades vendidas e preço de fabricação.
- D_Descontos: Inclui o ID do produto, valor do desconto e faixa de desconto.
- D_Detalhes: Tabela com ID do produto, lucro, custo das mercadorias vendidas (COGS), vendas, e vendas brutas.
- D_Calendário: Criada usando DAX com a função `calendar()`, fornece uma tabela de calendário para relacionar as datas do relatório.
- F_Vendas: Tabela principal de fatos com dados como SK_ID, ID do produto, produto, unidades vendidas, preço de venda, faixa de desconto, segmento, país, vendedor, lucro, e data.

![Star Schema](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/Desafio_FormulasDAX.png)

# 👩🏽‍💻 *Desafio Final - Foco na Experiência do Usuário*
No desafio final, for realizado alterações no layout do dashboard com o objetivo de aprimorar a experiência do usuário. As mudanças foram realizadas considerando princípios de:

- **Posicionamento e Contraste:** Ajustes no posicionamento de elementos e uso de cores para destacar informações principais, facilitando a legibilidade e interpretação dos dados.
- **Proporção Áurea:** Aplicação de proporções harmônicas para organizar os componentes visuais de forma equilibrada e agradável ao olhar.
- **Segmentação de Dados:** Inclusão de filtros claros e acessíveis, permitindo a personalização e segmentação da análise de acordo com variáveis como ano e país.
- **Botões e Menu de Navegação:** Adição de botões de ação e menus de navegação intuitivos, facilitando a movimentação entre os relatórios e a exploração das diferentes visões de dados.

## 1ª Página
![](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/RelatorioFinal_1.png)
## 2ª Página
![](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/RelatorioFinal_2.png)
## 3ª Página
![](https://github.com/feer-rodriguess90/PowerBI-Financial.Analysis/blob/main/assets/RelatorioFinal_3.png)

Essas melhorias visam tornar a análise mais fluida e intuitiva, maximizando a eficiência e a satisfação dos usuários ao interagir com o dashboard.
Para uma melhor análise, o repositório contém os arquivos do respectivo relatório nos formatos de arquivos `.pbix` e `.pdf`. 

## 🤝🏽 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Happy coding! 👩🏽‍💻

[![linkedin](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/datavizwithfer/) 
[![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@DataVizWithFer)
