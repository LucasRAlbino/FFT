# FFT com o Método da Borboleta

Este projeto implementa a Transformada Rápida de Fourier (FFT) usando o método da borboleta em Python. A FFT é uma técnica fundamental em processamento de sinais, análise de frequências e muitas outras aplicações em ciência e engenharia.

## Visão Geral

A Transformada Rápida de Fourier (FFT) é um algoritmo eficiente para calcular a Transformada Discreta de Fourier (DFT) e sua inversa. O método da borboleta é uma abordagem de divisão e conquista que divide o problema em subproblemas menores e os combina para obter a transformada completa.

Este projeto inclui:

- **Implementação da FFT** usando o método da borboleta.
- **Geração e visualização** de sinais no domínio do tempo e da frequência.
- **Aplicação de janelas e sinais específicos**, como o sinal `sinc` e o sinal `cos`.

## Como Funciona

1. **Permutação por Reversão de Bits:**
   - Reorganiza os dados para a ordem correta necessária para a FFT.

2. **Método da Borboleta:**
   - Divide o problema em partes menores e combina os resultados usando o fator twiddle.

3. **Geração de Sinais:**
   - Cria sinais de exemplo, aplica a FFT e plota os resultados no domínio do tempo e da frequência.

