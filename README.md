# Trabalho-Processamento-de-Sinais-I-2
CEFET/RJ  
Disciplina: Processamento de Sinais I  

Autores: Caio Bernardo, Fabio Daniel dos Santos Lacerda, Leonardo Sant’Ana Bittencourt.  

Este repositório contém a implementação e análise desenvolvidas na Aula Prática 2 da disciplina de Processamento de Sinais.

O projeto aborda conceitos fundamentais como:
- Transformada de Fourier (FFT)
- Análise espectral de sinais
- Espectro de frequência (single-sided e completo)
- Amostragem e frequência de Nyquist
- Subamostragem (downsampling)
- Reconstrução de sinais
- Processamento de sinais de áudio reais

Objetivos:
- Compreender a representação de sinais no domínio da frequência
- Relacionar sinais no tempo com seus espectros
- Analisar sinais sintéticos e sinais reais de áudio
- Investigar os efeitos da amostragem e subamostragem
- Entender o fenômeno de aliasing
- Aplicar ferramentas computacionais para análise espectral

Atividades Desenvolvidas:
- Implementação da função `calculate_spectrum()`
- Geração e análise de sinais senoidais e compostos
- Análise espectral de sinais com diferentes frequências
- Estudo do comportamento do espectro ao variar a frequência de amostragem
- Subamostragem de sinais de áudio (fatores M = 2, 4 e 8)
- Comparação entre métodos de reamostragem
- Análise espectral de sinais reais (ex: som de taça e resposta ao impulso)

Tecnologias Utilizadas:
- Google Colab
- Python
- NumPy
- SciPy
- Matplotlib
- IPython Display

Resultados:
Os experimentos demonstraram:
- A correspondência entre frequência de um sinal e picos no espectro
- A importância da frequência de Nyquist para evitar aliasing
- A distorção introduzida pela subamostragem
- Diferenças entre sinais harmônicos e sinais ruidosos
- O impacto da discretização na análise de sinais

Referências:
- Material da disciplina
- Documentação SciPy / NumPy
- Conteúdo teórico de Processamento de Sinais
