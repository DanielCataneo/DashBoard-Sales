# DashBoard-Sales

### Objetivos do Projeto: 
Dashboard criado  do zero buscando analisar e extrair insghts de uma tabela de vendas durante 2023 e 2024

### Ferramentas Usadas:
Excel e PowerBI

### Fórmulas DAX utilizadas na criação das medidas
 - 01 -Custo Total = CALCULATE(SUM(DadosTratados[ Custo_Producao ]))
 - 02 - Receita Total = CALCULATE(sum(DadosTratados[ Receita ]))
 - 03 - Lucro = [02 - Receita Total] - [01 - Custo Total] 
 - 04 - Quantidade Total = CALCULATE(SUM(DadosTratados[Quantidade_Produzida]))
 - 05 - Margem de Lucro = DIVIDE([03 - Lucro],[02 - Receita Total],0)

 ### Dashboard
![BIPython_page-0001](https://github.com/user-attachments/assets/3de23635-a9cf-4dff-9918-f43932dcf21b)
