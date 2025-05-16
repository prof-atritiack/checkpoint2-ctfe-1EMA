### Checkpoint 02: Computational Thinking For Engineering

**Objetivo:**
Desenvolver a capacidade de resolver problemas utilizando conceitos de lógica e aritmética em Python, sem o uso de bibliotecas, listas ou dicionários. Os problemas estão organizados em nível intermediário/avançado e visam estimular o raciocínio lógico e a habilidade de manipulação de variáveis, operadores e estruturas condicionais.

---

### Instruções:
- O código base (`.ipynb`) para a entrega já está disponível no repositório. Utilize-o para organizar as respostas de todas as questões.
- O trabalho pode ser realizado individualmente ou em grupos de até 3 integrantes.
- Não utilize bibliotecas externas.
- Não utilize listas ou dicionários.
- Os códigos devem estar devidamente comentados e organizados.
- Utilize strings formatadas para a apresentação das saídas, assegurando clareza e padronização.
- Não utilize IA generativa para a resolução dos problemas.
- Todas as questões devem ser implementadas em um único notebook Python (`.ipynb`).

---

### Questão 1: Controle Avançado de Carga em Elevadores Industriais

**Contexto:**
Uma empresa especializada em elevadores industriais deseja implementar um sistema para calcular a carga total suportada por um conjunto de elevadores em um edifício de múltiplos setores. Cada elevador possui um sistema de verificação de carga que considera um padrão oscilante em cada andar. A carga suportada por cada elevador no andar `i` é calculada por:

\[ S = \sum_{i=1}^{N} \frac{i^2}{i + 1} \]

**Problema:**
Desenvolva um programa em Python que recebe um número inteiro `N` representando a quantidade de setores (elevadores) e calcula a carga total suportada por todos os elevadores, utilizando a fórmula acima.

**Entrada:**
- Um número inteiro `N` (N > 0), representando o número de setores (elevadores).

**Saída:**
- A soma da carga total suportada com duas casas decimais, apresentada de forma formatada: `A carga total suportada é: 5.47`

---

### Questão 2: Análise Estrutural dos Cabos de Aço dos Elevadores

**Contexto:**
Os cabos de aço dos elevadores comerciais estão sujeitos a tensões variáveis durante o funcionamento. A resistência nominal de um cabo é um número composto pela soma dos dígitos de seu código multiplicado pelo valor do andar onde o elevador se encontra. Um cabo é considerado fora do padrão se o resultado desse cálculo não for um número primo.

**Problema:**
Crie um programa em Python que receba um código numérico do cabo e um número inteiro `A` representando o andar. O programa deve calcular a soma dos dígitos do código, multiplicar pelo andar e verificar se o resultado é um número primo.

**Entrada:**
- Um número inteiro `X`, representando o código do cabo.
- Um número inteiro `A`, representando o andar onde o cabo está instalado.

**Saída:**
- A saída deve ser apresentada de forma formatada: `O resultado para o cabo X no andar A é PRIMO/NÃO PRIMO.`

---

### Questão 3: Identificação Avançada de Falhas nos Elevadores

**Contexto:**
Uma empresa que gerencia um prédio de 10 andares deseja implementar um sistema para identificar padrões de falhas nos elevadores. Cada elevador possui um código numérico único que indica sua identificação. A soma dos cubos dos dígitos do código do elevador é utilizada para identificar possíveis falhas. Se a soma dos cubos dos dígitos for um número ímpar, o elevador deve ser considerado em "Alerta". Se for par, deve ser considerado "Normal".

**Problema:**
Implemente um programa em Python que receba um código numérico e calcule a soma dos cubos dos dígitos. O programa deve exibir o estado do elevador com base na paridade do resultado.

**Entrada:**
- Um número inteiro `N`, representando o código do elevador.

**Saída:**
- A saída deve ser apresentada de forma formatada: `O elevador N está em estado: Alerta/Normal.`

---

### Critérios de Avaliação:
- Correção da lógica aplicada na solução dos problemas.
- Uso adequado de estruturas condicionais e operadores aritméticos.
- Formatação e clareza do código.
- Uso adequado de comentários para explicar a lógica dos programas.
- Organização do código, padronização das saídas e utilização de strings formatadas.
