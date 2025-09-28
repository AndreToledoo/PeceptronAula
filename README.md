# Introdução

O presente trabalho teve como finalidade o desenvolvimento de uma função computacional denominada perceptron_aspirador, inspirada nos princípios fundamentais do perceptron — um dos modelos pioneiros de redes neurais artificiais. O objetivo consistiu em criar um mecanismo de decisão automatizado capaz de determinar a potência de sucção e a velocidade de deslocamento ideais de um aspirador inteligente, com base em três variáveis de entrada: tipo de piso, quantidade de sujeira e distância até a sujeira. A atividade visa integrar conceitos teóricos de Inteligência Artificial a uma aplicação prática simplificada.

# Desenvolvimento

Para a construção do modelo, o primeiro passo consistiu na definição de valores numéricos associados aos tipos de piso, de modo a representar suas diferentes características físicas e permitir o processamento matemático. Pisos cerâmicos receberam valores mais elevados por possibilitarem maior velocidade, enquanto carpetes tiveram valores reduzidos, refletindo a necessidade de maior cautela na limpeza.

Na sequência, foi aplicada a normalização das variáveis de entrada, convertendo a quantidade de sujeira e a distância até a sujeira para uma escala entre 0 e 1. Essa etapa foi essencial para evitar discrepâncias entre unidades de medida distintas e garantir proporcionalidade nas decisões do modelo.

A determinação da potência baseou-se majoritariamente no nível de sujeira, com uma escala de saída entre 1 e 3. Já a velocidade foi calculada por meio de uma combinação ponderada entre o tipo de piso (peso de 60%) e a distância (peso de 40%), resultando em valores entre 1 e 5. Foram realizados testes com diferentes combinações de entradas para avaliar o comportamento da função. Os resultados mostraram coerência com a lógica proposta: por exemplo, pisos cerâmicos com sujeira alta e distância média resultaram em maior potência e velocidade, enquanto pisos com sujeira leve e distância curta geraram configurações mais econômicas.

# Conclusão

O desenvolvimento do perceptron_aspirador proporcionou a aplicação prática de conceitos importantes da Inteligência Artificial, como normalização, atribuição de pesos e tomada de decisão automatizada. Apesar de não se tratar de um perceptron treinável, o modelo representa uma abordagem determinística eficaz para problemas de adaptação de comportamento em dispositivos inteligentes. A atividade permitiu compreender de maneira mais concreta como regras matemáticas e lógicas podem ser utilizadas para aproximar o funcionamento de sistemas reais, contribuindo para a formação de uma base sólida em técnicas de IA e programação aplicada.


## Alunos: 
André Luiz Gusmão Carneiro de Toledo - 1232021455
Marcelo Gutemberg Peres Campos - 125111398712
Guilherme Lustosa do Carmo - 12316574
