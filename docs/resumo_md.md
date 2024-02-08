https://www.markdownguide.org/basic-syntax/

# Título 1
## Título 2
### Título 3
#### E assim por diante...

$$
\vec{a} = b + \vec{c}
$$

\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}

**Negrito**<br>
*Itálico*<br>
==Destacado==<br>
~~Tachado~~<br>
>Comentado

``Bloco de texto``

<p align="center">Códigos HTML para estilos avançados:<br>
  <b>Negrito</b><br>
  <u>Sublinhado</u><br>
  <i>Itálico</i><br>
  <em>Ênfase</em><br>
  <font color='red'>Fonte colorida nomeada</font><br>
  <font color=#FF00FF>Fonte colorida #RRGGBB</font><br>
  <font size=5>Tamanho da fonte de 1 a 7</font><br>
  <font face='arial'>Fonte arial</font><br>
  <font face='courier'>Fonte courier</font><br>
  <font face='verdana'>Fonte verdana</font>
</p>

>Emojis

:smile:

:sweat_smile:

:arrow_right:

1. Lista numerada;
2. Segundo elemento da lista;
3. Terceiro elemento;
4. E assim por diante...
      1. Lista numerada;
      2. Segundo elemento da lista;
      3. Terceiro elemento;
      4. E assim por diante...
         1. Lista numerada;
         2. Segundo elemento da lista;
         3. Terceiro elemento;
         4. E assim por diante...
      5. Lista numerada;
      6. Segundo elemento da lista;
      7. Terceiro elemento;
      8. E assim por diante...
5. Lista numerada;
6. Segundo elemento da lista;
7. Terceiro elemento;
8. E assim por diante...

> **`UUU - AAAAAAAA - TT - DDD - SSSS`**

```
UUU - Unidade de Furnas
      AAAAAAAA - Identificação da área
                 TT - Tipo de documento
                      DDD - Disciplina
                            SSSS - Número Sequencial
```

=== "**UUU**"
    UUU - **Unidade de Furnas**
=== "**AAAAAAAA**"
    AAAAAAAA - **Identificação da área**
=== "**TT**"
    TT - **Tipo de documento**
=== "**DDD**"
    DDD - **Disciplina**
=== "**SSSS**"
    SSSS - **Número Sequencial**


``` mermaid
---
title: Fluxo do repositório
---
%%{init: { 'gitGraph': {'showBranches': true, 'showCommitLabel':true,'mainBranchName': 'Consolidado'}} }%%
      gitGraph TB:
        commit type:REVERSE tag:"Revisão 004"
        commit tag:"Revisão 005"
        branch Etapa_acessante
        commit tag:"Revisão 00A"
        commit tag:"Revisão 00B"
        checkout Consolidado
        commit tag:"Revisão 006"
        branch Etapa_03_PB
        commit tag:"Revisão 00A"
        checkout Etapa_acessante
        commit tag:"Revisão 00C"
        checkout Etapa_03_PB
        commit tag:"Revisão 00B"
        commit type:HIGHLIGHT tag:"Revisão 000"
        branch Etapa_03_PE
        commit tag:"Revisão 00A"
        commit type:HIGHLIGHT tag:"Revisão 000"
        commit tag:"Revisão 01A"
        commit tag:"Revisão 01B"
        commit type:HIGHLIGHT tag:"Revisão 001"
        checkout Consolidado
        merge Etapa_03_PE tag:"Revisão 007"
        checkout Etapa_acessante
        commit type:HIGHLIGHT tag:"Revisão 000"
        checkout Consolidado
        merge Etapa_acessante tag:"Revisão 008"
```

``` mermaid
---
title: Fluxo do projeto básico
---
flowchart LR
  INICIO(("Início")):::inicio --> GP0
  subgraph EEEP
    direction TB
    GP0("Solicitar\n contratação\n de consultoria") --> GPE0("Ponto focal")
    subgraph EEEPE
        direction LR
        GPE0 --> 
        GPE1("Consultoria") --> GPE2("Engenharia do proprietário")
        GPE2 --> D1{"Aprovado?"}
        D1 -->|"Sim"| DB{{"teste"}}
        D1 -->|"Não"| GPE1
    end
    subgraph EEEPC
        direction LR
        GPC1("Consultoria") --> GPC2("Engenharia do proprietário")
    end
    EEEPE -->|"notificação"| EEEPC
    EEEPC --> EEEPE
    subgraph EEEPP
        direction LR
        GOS1("Consultoria") --> GPS2("Engenharia do proprietário")
    end
    EEEPE -->|"notificação"| EEEPP
    EEEPP --> EEEPE
  end
  DB --> FIM((("Fim"))):::fim
  INICIO -.->|"Solicita Projeto Básico"| DOCUMENTO[["CI EEPMT"]]
    
  classDef inicio stroke:#0f0
  classDef fim stroke:#f00
  style DOCUMENTO stroke-dasharray: 5 5
```

``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```

``` mermaid
stateDiagram-v2
  state fork_state <<fork>>
    [*] --> fork_state
    fork_state --> State2
    fork_state --> State3

    state join_state <<join>>
    State2 --> join_state
    State3 --> join_state
    join_state --> State4
    State4 --> [*]
```

``` mermaid
classDiagram
  Person <|-- Student
  Person <|-- Professor
  Person : +String name
  Person : +String phoneNumber
  Person : +String emailAddress
  Person: +purchaseParkingPass()
  Address "1" <-- "0..1" Person:lives at
  class Student{
    +int studentNumber
    +int averageMark
    +isEligibleToEnrol()
    +getSeminarsTaken()
  }
  class Professor{
    +int salary
  }
  class Address{
    +String street
    +String city
    +String state
    +int postalCode
    +String country
    -validate()
    +outputAsLabel()  
  }
```

``` mermaid
erDiagram
  CUSTOMER ||--o{ ORDER : places
  ORDER ||--|{ LINE-ITEM : contains
  LINE-ITEM {
    string name
    int pricePerUnit
  }
  CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

=== "Aba 'A'"

    Este assunto diz respeito ao tópico 'A'.

=== "Aba 'B'"

    Este assunto diz respeito ao tópico 'B'.

=== "Aba 'C'"

    Este assunto diz respeito ao tópico 'C' e não se repete mais à frente.

<br>

=== "Aba 'A'"

    Este assunto TAMBÉM diz respeito ao tópico 'A'.

=== "Aba 'B'"

    Este assunto TAMBÉM diz respeito ao tópico 'B'.

<div class="grid" markdown>

=== "Lista desordenada"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Lista ordenada"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

</div>

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

=== "Python"

    ``` py
    import pandas as np

    def main():
      print("Hello world!")
      return 0
    ```

=== "JavaScript"

    ``` js
    let lista = [];

    function main() {
      alert("Hello world!");
      return 0
    }
    ```