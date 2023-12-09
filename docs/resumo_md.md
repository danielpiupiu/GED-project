# Título 1
## Título 2
### Título 3
#### E assim por diante...

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
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
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