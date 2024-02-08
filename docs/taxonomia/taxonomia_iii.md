# REVISÃO

## AABBB.CC-DDD-EE-FF.GGG-HHHH-**III**

Texto descritivo

### **Tabela 8**: III - Identificação da revisão

|                        Campo III                        | Descrição                                      |
| :-----------------------------------------------------: | :--------------------------------------------- |
|                        000 a 099                        | Revisão numérica - Documentos aprovados        |
| 00A, 00B, 00C, ...<br> 01A, 01B, ... <br> 02A, 03A, ... | Revisão alfanumérica - Documentos em aprovação |

As revisões se darão de forma regressiva quando o documento ganha o status de aprovado. Esta forma de numeração visa manter o número de algarismos do campo revisão completo desde a primeira revisão, evitando de outra forma uma lógica extra apenas para eliminar caracteres. Assim, numa numeração regressiva, a ordenação dos documentos seguirá como no exemplo abaixo:

- 00A (elaboração inicial)
- 00B (primeira revisão)
- 00C (segunda revisão)
- 000 (documento aprovado)
- 01A (nova revisão)
- 001 (documento aprovado)
- 02A (nova revisão)
- 02B (revisão)
- 002 (documento aprovado)
- ...