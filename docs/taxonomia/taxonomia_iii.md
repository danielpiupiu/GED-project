# REVISÃO

## AABBB.CC-DDD-EE-FF.GGG-HHHH-**III**

Codificação para Revisões.

1. Documentos para aprovação serão emitidos com codificação alfanumérica.
2. A o código seguirá assim até que seja aprovado formalmente pela engenharia do proprietário.
    
    Revisão alfanumérica.<br>
    ``Ex: VISÃO GERAL DOS PARQUES - W-09661-DE-1-D14-0001``<br>
    CÓDIGO CHESF: ECND-E-GE00-CAR-DE-001-RA (Emissão Inicial para aprovação revisão A).<br>
    Após a emissão inicial para aprovação RA prosseguirá RB,RC,RD...<br>
    Após aprovação CHESF será emitida a emissão inicial aprovada R0.<br>
    Depois de aprovada a emissão inicial R0, caso haja novos comentários futuros, inicia-se a R0A, R0B...<br>
    ECND-E-GE00-CAR-DE-001-R0A (em elaboração na revisão R0A, após a R0).

3. Documentos Aprovados:
    
    Após a aprovação da CHESF deverá ser gerada Revisão apenas numérica.<br>
    ``Ex: VISÃO GERAL DOS PARQUES - W-09661-DE-1-D14-0001``<br>
    CÓDIGO CHESF: ECND-E-GE00-CAR-DE-001-R0 (emissão inicial aprovada) ECND-E-GE00-CAR-DE-001-R1 (Após aprovação da versão 0A, 0B... será gerada a revisão R1).<br>
    Desta forma teremos sempre documentos aprovados com revisão apenas numérica, enquanto que para aprovação teremos sempre documentos alfanuméricos.

### **Tabela 8**: III - Identificação da revisão

|                                 Campo III                                  | Descrição                                      |
| :------------------------------------------------------------------------: | :--------------------------------------------- |
|                                  00 a 99                                   | Revisão numérica - Documentos aprovados        |
| 00A, 00B, 00C, ...<br> 01A, 01B, ... <br> 02A, 03A, ... <br> 99A, 99B, ... | Revisão alfanumérica - Documentos em aprovação |

As revisões se darão de forma regressiva quando o documento ganha o status de aprovado. Esta forma de numeração visa manter o número de algarismos do campo revisão completo desde a primeira revisão, evitando de outra forma uma lógica extra apenas para eliminar caracteres. Assim, numa numeração regressiva, a ordenação dos documentos seguirá como no exemplo abaixo:

- 00A (elaboração inicial)
- 00B (primeira revisão)
- 00C (segunda revisão)
- 00 (documento aprovado)
- 01A (nova revisão)
- 01 (documento aprovado)
- 02A (nova revisão)
- 02B (revisão)
- 02 (documento aprovado)
- ...