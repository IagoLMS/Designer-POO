# Esse reposiório descreve 3 ténicas dentro de POO

# Herança

- A herança e um dos 4 pilares do POO, onde podemos fazer uma classe como a principal sendo conhecida como a classe pai, mas se a sua utilização for de forma geral apresentara maleficios maiores do que beneficios, pois ao utilizarmos em animais, temos 2 problemas que são:
1- Aumenta fragilidade da estrutura, pois a herança sempre ira atribuir suas características herdadas da classe pai o que indica que todos animais teriam as mesmas funções que todos e se fosseamos adicionar funções em cada um seria mais tempo e não poderíamos reutilizar o código pois seria um copia e cola.
2- O segundo fator seria que teriamos que limitar todas as outras classes que estão herdando animais o que não se aplica na vida real, pois o POO sempre pretende aplicar ao mais próximo da vida real.

# Composição / Associação

- A composição ou associação, se trata em criar características e atribuir essas funções ou características a outras classes, permitindo com que outras classes recebem essas modificações, permitindo uma melhor flexibilidade e assim também evitando que todos os animais tenham as mesmas características o que deixa mais fácil organizar o código e permite mudar com uma melhor estabilidade. Mas assim com seus benefícios ele tem os seus malefícios em termos de responsabilidade não podemos atribuir ou dar características a uma coisa que já tem, como exemplo um pássaro seguindo a metodologia de associação nós estamos dando asas e capacidade de voar pra algo que já nasce sabendo o que é contra intuitivo, visto que esaas características atribuidas com New nos construtores.

# Injeção de Dependencia


- E a metodologia mais prática e eficiente de se usar permite enquadrar em conjunto com o SOLID, pois como a injeção de dependência que ao inves de você dar essas características elas já venha em sua estrutura ja iniciem com elas, seguindo ima linha de uma responsabilidade permitindo o pássaro ja nasça voar ou dormir sem que ele precisa ganhar essa atribuição de ninguém.
