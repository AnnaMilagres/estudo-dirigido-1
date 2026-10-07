# Processamento Digital de Sinais - Estudo Dirigido 1

Este repositório contém as simulações computacionais e o Mini Projeto Integrador desenvolvidos para a disciplina de Processamento Digital de Sinais do curso de Engenharia de Computação (IFPB).

## Sobre o Projeto

O objetivo deste estudo é investigar a transição de sinais do domínio contínuo para o discreto, explorando conceitos de amostragem (Teorema de Nyquist), quantização, e as propriedades fundamentais de sistemas LTI (Lineares e Invariantes no Tempo). 

O repositório culmina num **Mini Projeto Integrador**, que simula o pipeline completo de aquisição e processamento de um sinal de áudio. O sinal é corrompido com ruído gaussiano e posteriormente recuperado através da convolução com um filtro digital de média móvel.

## Estrutura do Repositório

O repositório está organizado da seguinte forma para facilitar a navegação e a execução dos códigos:

* **`relatorio/`**: Contém o documento final em formato PDF com toda a fundamentação teórica, cálculos analíticos e discussão de resultados.
* **`simulacoes/`**: Contém o ficheiro `simulacoes.ipynb`, que agrupa os códigos das etapas teóricas introdutórias.
* **`mini-projeto/`**: 
  * **`codigo/`**: Contém o ficheiro principal `mini-projeto.ipynb` com o pipeline de processamento do sinal de áudio.
  * **`resultados/`**: Armazena os gráficos exportados gerados durante o processamento do áudio.