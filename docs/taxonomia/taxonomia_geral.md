ELETROBRAS - GERAÇÃO E TRANSMISSÃO - Taxonomia para documentos de engenharia - Revisão 00A

# TAXONOMIA

## **AABBB.CC-DDD-EE-FF.GGG-HHHH-III**

**AA** – Tipo da instalação<br>
**BBB** – Nome da instalação<br>
**CC** – Número da etapa do empreendimento<br>
**DDD** - Identificação do setor da Instalação por tipo de instalação<br>
**EE** – Finalidade do Projeto<br>
**FF** - Identificação da Disciplina<br>
**GGG** - Tipologia do documento<br>
**HHHH** - Número sequencial<br>
**III** - Identificação da revisão (automatizado pelo GED)


``EX1: SEIGT.01-SE2-PE-ELM-DE-0001-00A``<br>
``EX2: UHCNY.03-CSF-PB-CIV-DE-0007-01A``<br>
``EX3: UHCNY.03-UNG-FA-MEC-LM-0001-002``


```
_
|____Subestação de transmissão (AA – Tipo da instalação)
    |
    |____SE Igaporã III (BBB – Nome da instalação)
        |
        |____Etapa 01 (CC – Número do empreendimento)
        |   |
        |   |____Pátio 230 kV (DDD - Setor da Instalação)
        |       |
        |       |____Projeto Executivo (EE – Finalidade do Projeto)
        |           |
        |           |____Modelo civil (FFF - Identificação da Disciplina)
        |           |   |
        |           |   |____Documento SEIGT.01-SE2-PE-CIV-DE-0001-01B
        |           |   |
        |           |   |____Documento SEIGT.01-SE2-PE-CIV-DE-0002-000
        |           |   |
        |           |   |____Documento SEIGT.01-SE2-PE-CIV-MC-0003-00C
        |           |
        |           |
        |           |____Modelo eletromecânico
        |               |
        |               |____Documento SEIGT.01-SE2-PE-ELM-DE-0001-000
        |               |
        |               |____Documento SEIGT.01-SE2-PE-ELM-LM-0002-00B
        |               |
        |               |____Documento SEIGT.01-SE2-PE-ELM-MC-0003-00A
        |
        |
        |
        |____Etapa 02
            |
            |____Pátio 138 kV
                |
                |____Projeto Básico
                    |
                    |____Modelo civil
                    |   |
                    |   |____Documento SEIGT.02-SE1-PB-CIV-DE-0001-00B
                    |   |
                    |   |____Documento SEIGT.02-SE1-PB-CIV-DE-0002-000
                    |
                    |
                    |____Modelo eletromecânico
                        |
                        |____Documento SEIGT.02-SE1-PB-ELM-DE-0001-000
                        |
                        |____Documento SEIGT.02-SE1-PB-ELM-LM-0002-00A
```

O campo de revisão e extensão não precisam ser apontadas na taxonomia.

Instalações/ Unidade seriam tabeladas por letras com a denominação (usina, subestação, etc.) (uma sugestão seria utilizar os dígitos do ONS)

Existe a necessidade de desenvolver a taxonomia compatível com projetos simultâneos?

Ou as etapas concomitantes poderiam permanecer apenas como metadata e informação no carimbo?

AABBB, onde AA representa o tipo da instalação (UH Usina Hid., ST sub. trans., LT Lin. trans.) e BBB representa a nome da instalação (TUC Tucuruí, FUR Furnas, etc.)