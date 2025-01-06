# Ferramenta de Análise de Rentabilidade de Carteira de Investimentos

## Descrição

Este projeto é uma ferramenta, desenvolvida em Python, para analisar a rentabilidade de uma carteira de investimentos. Ele utiliza dados do Yahoo Finance para calcular a rentabilidade dos ativos de uma carteira em um período de tempo específico e compara o desempenho da carteira com o índice Bovespa (^BVSP). O código é ideal para quem deseja ter uma visão consolidada da performance de seus investimentos de forma prática e objetiva.

## O que o projeto faz?

1. **Leitura e estruturação da carteira de investimentos:**
   - Importa os ativos e valores investidos a partir de um arquivo `carteira.txt`.
   - Constrói um dicionário com os ativos (chaves) e os valores iniciais investidos (valores).

2. **Coleta de dados históricos:**
   - Obtém cotações ajustadas dos ativos e do índice Bovespa através do Yahoo Finance.
   - Calcula a rentabilidade de cada ativo com base nos preços inicial e final do período selecionado.

3. **Cálculo da rentabilidade:**
   - Calcula a rentabilidade total da carteira utilizando o peso de cada ativo e suas respectivas rentabilidades.
   - Compara a rentabilidade total da carteira com a do índice Bovespa no mesmo período.

4. **Exibição dos resultados:**
   - Mostra o valor inicial e final da carteira.
   - Exibe a rentabilidade da carteira e do índice Bovespa em porcentagem.
   - Avalia se a carteira teve um desempenho superior, igual ou inferior ao índice Bovespa.

## Para que serve?

O projeto serve para:
- **Investidores individuais** que querem avaliar o desempenho de suas carteiras em relação a um índice de referência.
- **Estudantes ou iniciantes em finanças** que desejam aprender como realizar análises de rentabilidade de ativos.
- **Projetos acadêmicos** ou demonstrações práticas de uso de bibliotecas como `pandas`, `yfinance` e `datetime`.
