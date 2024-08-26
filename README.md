<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Backtesting: Relative Strength Index (RSI)

## Description

This project aims to develop a Python algorithm for backtesting financial assets using the Relative Strength Index (RSI). Backtesting is a crucial technique for evaluating the effectiveness of investment strategies, allowing investors to test their approaches with historical data before applying them in real-time.

## Project Features

- **Data Collection**: Import historical price data of financial assets (stocks, currencies, etc.) from sources such as financial APIs or CSV files.
  
- **RSI Calculation**: Implement the calculation of the Relative Strength Index (RSI) to assess the strength of a price trend and identify overbought or oversold conditions. RSI is calculated based on price changes over a specified period, commonly 14 days.

- **Strategy Simulation**: Test various trading strategies based on RSI, such as buying in oversold conditions and selling in overbought conditions, or crossing critical levels (e.g., 30 and 70).

- **Performance Evaluation**: Measure the performance of strategies using metrics such as total return, drawdown, and other relevant financial metrics.

- **Visualization**: Generate charts to visualize asset prices, RSI values, and buy/sell signals. Visualizations help understand the relationship between price movements and RSI signals.

## Technologies Used

- **Language**: Python

- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical calculations
  - `matplotlib` and `seaborn` for visualization
  - `requests` or `yfinance` for financial data collection

- **Development Environment**: Jupyter Notebook or your preferred IDE

## Project Structure

1. **Data Collection**: Scripts for importing and cleaning financial data.
   
2. **RSI Calculation**: Implementation of the Relative Strength Index calculation, including the determination of average gains and losses.

3. **Backtesting Engine**: Logic for simulating trading strategies and evaluating performance based on RSI.

4. **Visualization**: Tools for creating charts and detailed reports on RSI performance and applied strategies.

## Disclaimer

This code is provided for demonstration purposes only. The content here is intended to provide supplementary information to assist the investor in making their own investment decisions. None of the topics covered should be construed as any form of endorsement/offer/solicitation for the purchase/sale of any product.

## Documentation for the Library to be Used

[https://vectorbt.dev/](https://vectorbt.dev/)

## What is the Relative Strength Index (RSI)

The Relative Strength Index (RSI) is a widely used technical indicator in financial market analysis to evaluate the speed and change of price movements. Developed by J. Welles Wilder in the 1970s, RSI oscillates between 0 and 100 and is typically calculated over a 14-day period.

- **Overbought and Oversold Conditions**: RSI is used to identify overbought and oversold conditions. Generally, values above 70 indicate overbought conditions, while values below 30 indicate oversold conditions. These conditions can suggest potential reversal points in the market.

- **RSI Formula**: RSI is calculated using the formula:
  
  \[
  RSI = 100 - \frac{100}{1 + RS}
  \]

  Where \( RS \) is the average of gains over the past 14 periods divided by the average of losses over the same periods.

- **Interpretation**: RSI is used to identify potential reversal points in prices and to confirm the strength of a trend. It helps traders recognize moments of potential exhaustion of the current trend.


-------------------------------------------------------------------------------------------------------------------

# Backtesting: Índice de Força Relativa (RSI)

## Descrição

Este projeto visa desenvolver um algoritmo em Python para realizar backtesting de ativos financeiros utilizando o Índice de Força Relativa (RSI). O backtesting é uma técnica crucial para avaliar a eficácia de estratégias de investimento, permitindo que investidores testem suas abordagens com dados históricos antes de aplicá-las em tempo real.

## Funcionalidades do Projeto

- **Coleta de Dados**: Importar dados históricos de preços de ativos financeiros (ações, moedas, etc.) a partir de fontes como APIs financeiras ou arquivos CSV.
  
- **Cálculo do RSI**: Implementar o cálculo do Índice de Força Relativa (RSI) para avaliar a força de uma tendência de preço e identificar condições de sobrecompra ou sobrevenda. O RSI é calculado com base nas variações de preço em um determinado período, comumente 14 dias.

- **Simulação de Estratégias**: Testar diferentes estratégias de negociação baseadas no RSI, como as estratégias de compra em sobrevenda e venda em sobrecompra, ou cruzamentos de níveis críticos (por exemplo, 30 e 70).

- **Avaliação de Desempenho**: Medir o desempenho das estratégias usando métricas como retorno total, drawdown e outras métricas financeiras relevantes.

- **Visualização**: Gerar gráficos para visualizar os preços dos ativos, os valores do RSI e os sinais de compra/venda. As visualizações ajudam a compreender a relação entre os movimentos de preço e os sinais do RSI.

## Tecnologias Utilizadas

- **Linguagem**: Python

- **Bibliotecas**:
  - `pandas` para manipulação de dados
  - `numpy` para cálculos numéricos
  - `matplotlib` e `seaborn` para visualização
  - `requests` ou `yfinance` para coleta de dados financeiros

- **Ambiente de Desenvolvimento**: Jupyter Notebook ou IDE de sua escolha

## Estrutura do Projeto

1. **Data Collection**: Scripts para importar e limpar dados financeiros.
   
2. **RSI Calculation**: Implementação do cálculo do Índice de Força Relativa, incluindo a determinação dos períodos de ganho e perda média.

3. **Backtesting Engine**: Lógica para simulação de estratégias de negociação e avaliação de desempenho com base no RSI.

4. **Visualization**: Ferramentas para criar gráficos e relatórios detalhados sobre o desempenho do RSI e as estratégias aplicadas.

## Disclaimer

Este código foi elaborado para fins exclusivamente demonstrativos. O conteúdo aqui apresentado visa fornecer informações complementares para auxiliar o investidor na tomada de suas próprias decisões de investimento. Reforçando, nenhum tópico aqui abordado constitui qualquer tipo de indicação/oferta/solicitação de compra/venda de qualquer produto.

## Documentação da Biblioteca que será Usada

[https://vectorbt.dev/](https://vectorbt.dev/)

## O que é o Índice de Força Relativa (RSI)

O Índice de Força Relativa (RSI) é um indicador técnico amplamente utilizado na análise de mercados financeiros para avaliar a velocidade e a mudança dos movimentos de preço. Desenvolvido por J. Welles Wilder na década de 1970, o RSI oscila entre 0 e 100 e é tipicamente calculado para um período de 14 dias.

- **Sobrecompra e Sobrevenda**: O RSI é usado para identificar condições de sobrecompra e sobrevenda. Normalmente, valores acima de 70 indicam sobrecompra, enquanto valores abaixo de 30 indicam sobrevenda. Essas condições podem sugerir pontos de reversão no mercado.

- **Fórmula do RSI**: O RSI é calculado usando a fórmula:
  
  \[
  RSI = 100 - \frac{100}{1 + RS}
  \]

  Onde \( RS \) é a média dos ganhos nas últimas 14 barras dividida pela média das perdas nas mesmas barras.

- **Interpretação**: O RSI é utilizado para identificar possíveis pontos de reversão de preços e para confirmar a força de uma tendência. Ele ajuda os traders a reconhecer momentos de possível exaustão da tendência atual.

