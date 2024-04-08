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
# TIPO DA INSTALAÇÃO

## **AA**BBB.CC-DDD-EE-FF.GGG-HHHH-III

O tipo da instalação

### **Tabela 1**: AA – Tipo da instalação

| Campo AA | Descrição                            |
| :------: | :----------------------------------- |
|    GR    | Geral                                |
|    UH    | Usina hidroelétrica                  |
|    SE    | Subestação de transmissão            |
|    LT    | Linha de transmissão                 |
|    UT    | Usina termoelétrica                  |
|    EO    | Parque eólico                        |
|    PS    | Planta solar                         |
|    NU    | Usina nuclear                        |
|    HI    | Hidrogênio                           |
|    RP    | Estação repetidora/ telecomunicações |
|   ...    | ...                                  |

# NOME DA INSTALAÇÃO

## AA**BBB**.CC-DDD-EE-FF.GGG-HHHH-III

Texto descritivo

### **Tabela 2**: BBB – Nome da instalação

| Campo BBB | Descrição            |
| :-------: | :------------------- |
|    ELB    | Geral Eletrobras     |
|    CHF    | Geral Chesf          |
|    ELN    | Geral Eletronorte    |
|    ELS    | Geral Eletrosul      |
|    FUR    | Geral Furnas         |
|    ENG    | Padrão de Engenharia |
|    ...    | ...                  |
|    IGT    | Igaporã III          |

Para LTs utilizar o código da instalação fonte (montante).

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

# SETOR DA INSTALAÇÃO

## AABBB.CC-**DDD**-EE-FF.GGG-HHHH-III

Texto descritivo

### **Tabela 4**: DDD - Identificação do setor da Instalação por tipo de instalação

| Tipo da instalação | Campo DDD | Descrição                                                       |
| :----------------: | :-------: | :-------------------------------------------------------------- |
|         UH         |    APT    | Acesso/Plataforma                                               |
|         GR         |    ACI    | Acessos Internos                                                |
|         EO         |    AEG    | Aerogerador                                                     |
|         EO         |    A00    | Aerogerador – Geral                                             |
|         GR         |    ALM    | Almoxarifado                                                    |
|         EO         |    ANM    | Anemômetros                                                     |
|         UH         |    AMT    | Área de Montagem                                                |
|         UH         |    BGP    | Barragem Principal                                              |
|         UH         |    CNA    | Canal de Adução                                                 |
|         UH         |    CNF    | Canal de Fuga                                                   |
|         GR         |    COB    | Canteiro de Obras                                               |
|         SE         |    CSC    | Casa de comando                                                 |
|         UH         |    CSF    | Casa de Força                                                   |
|         UH         |    CMQ    | Casa de Máquinas                                                |
|         SE         |    CSR    | Casa de relés                                                   |
|         UH         |    CSA    | Casa dos Serviços Auxiliares                                    |
|         UH         |    CDA    | Castelo D’Água                                                  |
|         UH         |    CHA    | Chaminé de Equilíbrio                                           |
|         UH         |    CGE    | Circuito de Geração                                             |
|         EO         |    CDA    | Coletor de Dados Anemométricos                                  |
|         UH         |    TFO    | Conduto Forçado, Túnel Forçado                                  |
|         LT         |    CNX    | Conexão ao Sistema Interligado Nacional                         |
|         GR         |    DPG    | Depósito de Gases                                               |
|         GR         |    DPQ    | Depósito de Produtos Químicos                                   |
|         UH         |    DSR    | Desvio do Rio                                                   |
|         UH         |    DIK    | Diques                                                          |
|         UH         |    ECL    | Eclusa                                                          |
|         UH         |    EDC    | Edifício de Comando                                             |
|         UH         |    ETC    | Eletrocentro                                                    |
|         UH         |    ENC    | Ensecadeira                                                     |
|         EO         |    ESM    | Estação de Monitoramento                                        |
|         GR         |    EFE    | Estradas de Ferro                                               |
|         GR         |    ERR    | Estradas de Rodagem                                             |
|         UH         |    FND    | Fundação                                                        |
|         GR         |    GCA    | Galerias de Cabos                                               |
|         UH         |    GER    | Gerador                                                         |
|         GR         |    GRL    | Geral                                                           |
|         GR         |    GUA    | Guarita                                                         |
|         UH         |    HUB    | Hub                                                             |
|         GR         |    LAB    | Laboratório                                                     |
|         UH         |    LTU    | Linha de Transmissão da Usina                                   |
|         EO         |    M00    | Módulo de Agrupamento de Aerogeradores                          |
|         FV         |    MDF    | Módulo Fotovoltaico                                             |
|         FV         |    MSO    | Módulo Solar                                                    |
|         UH         |    CON    | Muros de Contenção                                              |
|         UH         |    MPO    | Muros de Proteção de Obras Hidráulicas                          |
|         UH         |    MTA    | Muros de Transição ou Ala                                       |
|         EO         |    NCL    | Nacele                                                          |
|         GR         |    OCV    | Obras Civis                                                     |
|         GR         |    OAC    | Obras de Apoio e Complementares                                 |
|         UH         |    ODR    | Obras de Desvio do Rio                                          |
|         UH         |    ORS    | Obras do Reservatório                                           |
|         GR         |    OFI    | Oficinas                                                        |
|         EO         |    PQE    | Parque Eólico                                                   |
|         SE         |    SE1    | Pátio de 138 kV                                                 |
|         SE         |    SE2    | Pátio de 230 kV                                                 |
|         SE         |    SE5    | Pátio de 500 kV                                                 |
|         SE         |    SE0    | Pátio de 69 kV                                                  |
|         GR         |    PLV    | Plano Viário                                                    |
|         GR         |    POV    | Pontes e Viadutos                                               |
|         UH         |    PON    | Pontes, Passarelas                                              |
|         UH         |    PFU    | Porto Fluvial                                                   |
|         GR         |    PAD    | Prédio Administrativo                                           |
|         LT         |    RAM    | Ramal de LT                                                     |
|         LT         |    RMT    | Rede de Média Tensão                                            |
|         GR         |    REF    | Refeitórios                                                     |
|         UH         |    RSV    | Reservatório                                                    |
|         UH         |    RPR    | Rio Principal                                                   |
|         EO         |    SDV    | Sensor de direção de vento                                      |
|         UH         |    CTA    | Setor de Captação, Armazenamento e Tratamento de Água           |
|         GR         |    RCO    | Setor de Recebimento, Armazenamento e Tratamento de Combustível |
|         UH         |    STP    | Sistema de Transposição de Peixes                               |
|         GR         |    SAP    | Sítio do Aproveitamento                                         |
|         SE         |    SEU    | Subestação da Usina                                             |
|         UH         |    TAG    | Tomada d'Água                                                   |
|         UH         |    TOR    | Torre                                                           |
|         EO         |    TOM    | Torre de Medição                                                |
|         UH         |    TRE    | Transformador de Elevação                                       |
|         UH         |    TBS    | Tubo de Sucção                                                  |
|         UH         |    TAD    | Túneis de Adução                                                |
|         UH         |    TUD    | Túneis de Desvio                                                |
|         UH         |    TAC    | Túnel de Acesso                                                 |
|         UH         |    TDR    | Túnel de Drenagem                                               |
|         UH         |    FUG    | Túnel de Fuga                                                   |
|         UH         |    TUR    | Turbina                                                         |
|         UH         |    UNG    | Unidade Geradora                                                |
|         UH         |    USN    | Usina                                                           |
|         UH         |    VAZ    | Vazão Sanitária                                                 |
|         UH         |    VTD    | Vertedouro                                                      |
|         UH         |    VTC    | Vertedouro Complementar                                         |
|         GR         |    VRE    | Vilas Residenciais                                              |

# FINALIDADE DO PROJETO

## AABBB.CC-DDD-**EE**-FF.GGG-HHHH-III

Texto descritivo

### **Tabela 5**: EE – Finalidade do Projeto

| Campo EE | Descrição                       |
| :------: | :------------------------------ |
|    AP    | Anteprojeto/ Estudo para leilão |
|    PB    | Projeto básico                  |
|    FA    | Projeto de fabricação           |
|    PE    | Projeto executivo               |
|    CC    | Conforme construído             |
|    SB    | Segurança de barragem           |

# DISCIPLINA

## AABBB.CC-DDD-EE-**FF**.GGG-HHHH-III

Texto descritivo

### **Tabela 6**: FF - Identificação da Disciplina

**Disciplina geral**: arquitetura (main), civil, eletromecânica, equipamento, rede de dados, telecomunicações, proteção (controle e automação), elétrica, mecânica, meio-ambiente, fundiário, coordenação, gestão, inspeção, etc.

| Campo FF | Descrição                           |
| :------: | :---------------------------------- |
|    AQ    | Arquitetura, Urbanismo e Paisagismo |
|    CV    | Civil                               |
|    EM    | Eletromecânica                      |
|    PC    | Proteção, Controle e Supervisão     |
|    SA    | Serviços Auxiliares                 |
|    IT    | Iluminação, tomadas e SPDA          |
|    EQ    | Equipamentos                        |
|    GR    | Geral*                              |
|    ME    | Mecânica                            |
|    QL    | Qualidade                           |
|    MA    | Meio ambiente                       |
|    TL    | Telecomunicações                    |
|    ES    | Estudos e planejamento              |
|    MT    | Materiais                           |
|    IN    | Proteção contra incêndio            |
|   ...    | ...                                 |

> __*__ Em Caso de Disciplina ‘Geral’ localizar o sistema mais próximo na tabela 7.
 
# TIPOLOGIA

## AABBB.CC-DDD-EE-FF.**GGG**-HHHH-III

Texto descritivo

### **Tabela 7**: GGG - Tipologia do documento

**Tipo do documento**: desenho, arranjo, vista, corte, padrão, modelo, uniformização, nota técnica, relatório, certificado, ata, R3, R4, etc.

| Campo GGG | Documento                                                                                                    |
| :-------: | :----------------------------------------------------------------------------------------------------------- |
|    AQL    | Certificado - Atestado de Qualidade                                                                          |
|    CCM    | Certificado - Conclusão de Comissionamento                                                                   |
|    CMT    | Certificado - Conclusão de Montagem                                                                          |
|    CTF    | Certificado - Outros                                                                                         |
|    ACB    | Desenho Técnico - Acabamento                                                                                 |
|    AST    | Desenho Técnico - Arquitetura de Sistema                                                                     |
|    ARJ    | Desenho Técnico - Arranjo                                                                                    |
|    CCT    | Desenho Técnico - Caderno Construtivo                                                                        |
|    CTE    | Desenho Técnico - Corte                                                                                      |
|    DDM    | Desenho Técnico - Desenho Dimencional                                                                        |
|    DMT    | Desenho Técnico - Detalhamento de Montagem                                                                   |
|    DFA    | Desenho Técnico - Diagrama de Fiação                                                                         |
|    DIT    | Desenho Técnico - Diagrama de Interligação                                                                   |
|    DFC    | Desenho Técnico - Diagrama Funcional                                                                         |
|    DLG    | Desenho Técnico - Diagrama Lógico                                                                            |
|    DTF    | Desenho Técnico - Diagrama Trifilar                                                                          |
|    DUF    | Desenho Técnico - Diagrama Unifilar                                                                          |
|    ELV    | Desenho Técnico - Elevação                                                                                   |
|    FCD    | Desenho Técnico - Fachada                                                                                    |
|    ISM    | Desenho Técnico - Isometria                                                                                  |
|    DSN    | Desenho Técnico - Outros                                                                                     |
|    PPT    | Desenho Técnico - Perspectiva                                                                                |
|    PTA    | Desenho Técnico - Planta                                                                                     |
|    SCO    | Desenho Técnico - Seção                                                                                      |
|    VTA    | Desenho Técnico - Vista                                                                                      |
|    ATA    | Diversos - Ata de Reunião                                                                                    |
|    DIF    | Diversos - Documento Informativo                                                                             |
|    EAN    | Diversos - Edital ANEEL                                                                                      |
|    FML    | Diversos - Formulário                                                                                        |
|    DVS    | Diversos - Outros                                                                                            |
|    PTN    | Diversos - Programa de Treinamento                                                                           |
|    AVR    | Documento Legal - Alvará                                                                                     |
|    LCC    | Documento Legal - Licença                                                                                    |
|    LLI    | Documento Legal - Licenciamento Ambiental - Licença de Instalação                                            |
|    LLP    | Documento Legal - Licenciamento Ambiental - Licença Prévia                                                   |
|    LGL    | Documento Legal - Outros                                                                                     |
|    ARC    | Documento Técnico - Análise de Riscos                                                                        |
|    BDS    | Documento Técnico - Base de Dados do Sistema Supervisório                                                    |
|    CEC    | Documento Técnico - Caderno de Encargos                                                                      |
|    COB    | Documento Técnico - Canteiro de Obras                                                                        |
|    CST    | Documento Técnico - Configuração de Sistema                                                                  |
|    CEX    | Documento Técnico - Cronograma de Execução                                                                   |
|    CFF    | Documento Técnico - Cronograma Físico-Financeiro                                                             |
|    DTB    | Documento Técnico - Databook                                                                                 |
|    WSM    | Documento Técnico - Detalhamento de Fornecimento - Workstatement                                             |
|    DOB    | Documento Técnico - Diário de Obra                                                                           |
|    DEA    | Documento Técnico - Dicionário EAP                                                                           |
|    ETN    | Documento Técnico - Especificação Técnica                                                                    |
|    EAP    | Documento Técnico - Estrutura Analítica do Projeto (EAP)                                                     |
|    EOP    | Documento Técnico - Estrutura Organizacional do Projeto                                                      |
|    FDD    | Documento Técnico - Folha de Dados                                                                           |
|    LCB    | Documento Técnico - Lista de Cabos                                                                           |
|    LDC    | Documento Técnico - Lista de Documentos                                                                      |
|    LEQ    | Documento Técnico - Lista de Equipamentos                                                                    |
|    LFR    | Documento Técnico - Lista de Ferros                                                                          |
|    LPS    | Documento Técnico - Lista de Pontos e Sinais do Sistema                                                      |
|    LSB    | Documento Técnico - Lista de Sobressalentes                                                                  |
|    MMT    | Documento Técnico - Manual de Montagem                                                                       |
|    MUS    | Documento Técnico - Manual de Uso                                                                            |
|    MRP    | Documento Técnico - Matriz de Responsabilidade                                                               |
|    MCC    | Documento Técnico - Memória de Cálculo                                                                       |
|    ODT    | Documento Técnico - Orçamento Detalhado                                                                      |
|    OET    | Documento Técnico - Orçamento Estimado                                                                       |
|    DCM    | Documento Técnico - Outros                                                                                   |
|    PIC    | Documento Técnico - Plano de Inspeção e Controle da Qualidade (PICQ)                                         |
|    QMT    | Documento Técnico - Quantitativo de Materiais                                                                |
|    RTT    | Documento Técnico - Roteiro de Testes                                                                        |
|    TED    | Documento Técnico - Tabela de Eletrodutos                                                                    |
|    TSS    | Documento Técnico - Telas do Sistema Supervisório                                                            |
|    TAP    | Documento Técnico - Termo de Abertura do Projeto                                                             |
|    AVB    | Estudos Preliminares - Análise de Viabilidade                                                                |
|    CQS    | Estudos Preliminares - Croquis                                                                               |
|    ETR    | Estudos Preliminares - Escolha de Terreno                                                                    |
|    EIA    | Estudos Preliminares - Estudo de Impacto Ambiental (EIA)                                                     |
|    LCD    | Estudos Preliminares - Levantamento Cadastral                                                                |
|    LGT    | Estudos Preliminares - Levantamento Geotécnico                                                               |
|    LTG    | Estudos Preliminares - Levantamento Topográfico                                                              |
|    OMD    | Estudos Preliminares - Orçamento Modular                                                                     |
|    ETD    | Estudos Preliminares - Outros                                                                                |
|    BIP    | Relatório Técnico - Boletim de Inspeção                                                                      |
|    RLT    | Relatório Técnico - Outros                                                                                   |
|    RR1    | Relatório Técnico - R1 - Análise Técnico-Econômica das Alternativas                                          |
|    RR2    | Relatório Técnico - R2 - Detalhamento da Alternativa de Referência                                           |
|    RR3    | Relatório Técnico - R3 - Definição da Diretriz de Traçado e Análise Socioambiental para Linha de Transmissão |
|    RR4    | Relatório Técnico - R4 - Caracterização do Sistema de Transmissão                                            |
|    RAT    | Relatório Técnico - Relatório de Análise Técnica                                                             |
|    RIA    | Relatório Técnico - Relatório de Impacto Ambiental (RIMA)                                                    |
|    RNC    | Relatório Técnico - Relatório de Não Conformidade                                                            |
|    RRS    | Relatório Técnico - Relatório de Resistividade                                                               |
|    RSD    | Relatório Técnico - Relatório de Sondagem                                                                    |
|    TFD    | Relatório Técnico - Relatório Fotográfico Descritivo                                                         |
|    TAF    | Relatório Técnico - Teste de Aceitação em Fábrica                                                            |

# NUMERO SEQUENCIAL

## AABBB.CC-DDD-EE-FF.GGG-**HHHH**-III

A numeração sequencial poderá ser utilizada para melhor definir subtipos de documentos.

# REVISÃO

## AABBB.CC-DDD-EE-FF.GGG-HHHH-**III**

Codificação para Revisões.

1. Documentos para aprovação serão emitidos com codificação alfanumérica.

2. Documentos Aprovados serão emitidos com codificação numérica.
    
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