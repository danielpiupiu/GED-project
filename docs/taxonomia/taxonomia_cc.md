# NÚMERO DA ETAPA

## AABBB.**CC**-DDD-EE-FF.GGG-HHHH-III

A numeração das etapas se dará pela combinação de dois caracteres alfanuméricos pertencente ao seguinte conjunto:
$$
[0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ]
$$
Sua implementação seguirá ordem **lexicográfica** (como a ordem alfabética em dicionários), um algoritmo de fácil implementação por sistemas computacionais.

Segue abaixo um exemplo de ordenação crescente de números aleatório:
$$
00 < 01 < 09 < 0A < 0B < 0Z < 10 < 19 < 1A < 23 < AA < B3 < CG < ZZ
$$
Nesse sistema a quantidade total de etapas pelas combinações possíveis é:
$$
(10 + 26)^2 = 1296
$$
A adoção deste sistema se justifica pela quantidade de obras, principalmente de pequeno porte, à que estão sujeitas as instalações no modelo setorial e para facilitar a adoção de valores reservados; pois, por apresentar combinação de números e letras, este sistema permite combinações de fácil leitura e interpretação para aplicação em documentos específicos que têm escopo mais amplo e atendem diversas etapas de uma vez, como é o caso dos desenhos consolidados e dos padrões de engenharia. Assim:

- **00** é reservado para os desenhos consolidados do "conforme construído";
- **CH** é reservado para documentos padrões de engenharia Chesf;
- **EN** é reservado para documentos padrões de engenharia Eletronorte;
- **ES** é reservado para documentos padrões de engenharia Eletrosul;
- **FU** é reservado para documentos padrões de engenharia Furnas;
- **PE** é reservado para padrões de engenharia geral.

A tabela abaixo apresenta o campo **CC** com descrição, bem como os números reservados que não devem ser usados para as etapas.

### **Tabela 3**: CC – Número da etapa do empreendimento

| Campo CC | Descrição                                 |
| :------: | :---------------------------------------- |
| 01 a ZZ  | Etapas 01 a ZZ (ordem lexicográfica)      |
|    00    | Projeto consolidado (conforme construído) |
|    CH    | Padrão de engenharia Chesf                |
|    EN    | Padrão de engenharia Eletronorte          |
|    ES    | Padrão de engenharia Eletrosul            |
|    FU    | Padrão de engenharia Furnas               |
|    PE    | Padrão de engenharia Geral                |