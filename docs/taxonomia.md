# BRAINSTORM

XXX - P - VVNN - SUU - ZZ - YYY - RKK : Colocar a ordenação por letras em ordem alfabética.

## **AABBB.CC-DD-EEEFFF-GGG.HH-II.JJJ-KKK** (automatizado pelo GED)

O campo de revisão e extensão não precisam ser apontadas na taxonomia.

Instalações/ Unidade seriam tabeladas por letras com a denominação (usina, subestação, etc.) (uma sugestão seria utilizar os dígitos do ONS)

Existe a necessidade de desenvolver a taxonomia compatível com projetos simultâneos?

Ou as etapas concomitantes poderiam permanecer apenas como metadata e informação no carimbo?

AABBB, onde AA representa o tipo da instalação (UH Usina Hid., ST sub. trans., LT Lin. trans.) e BBB representa a nome da instalação (TUC Tucuruí, FUR Furnas, etc.)

### **Tabela 0**: AA – Tipo da instalação

| Campo AA | Descrição                 |
| :------: | :------------------------ |
|    GR    | Geral                     |
|    UH    | Usina hidroelétrica       |
|    ST    | Subestação de transmissão |
|    LT    | Linha de transmissão      |
|    UT    | Usina termoelétrica       |
|   ...    | ...                       |

### **Tabela 1**: BBB – Nome da instalação

| Campo BBB | Descrição        |
| :-------: | :--------------- |
|    ELB    | Geral Eletrobras |
|    TUC    | Tucuruí          |
|    CNU    | Coaracy Nunes    |
|    FUR    | Furnas           |
|    IGT    | Igaporã III      |
|    ...    | ...              |

.CC é o número da etapa, onde o 'CC' (tabela abaixo, conforme construído) é etapa 00.

### **Tabela 2**: CC – Número do empreendimento

| Campo CC | Descrição       |
| :------: | :-------------- |
|    00    | Como construído |
| 01 a 99  | Demais etapas   |

### **Tabela 3**: DD – Finalidade do Projeto

| Campo DD | Descrição                       |
| :------: | :------------------------------ |
|    AP    | Anteprojeto/ Estudo para leilão |
|    PB    | Projeto básico                  |
|    FA    | Projeto de fabricação           |
|    PE    | Projeto executivo               |
|    CC    | Como Construído (As Built)      |

```
_
|____ST Igaporã III
    |
    |____Etapa IGT01
    |   |
    |   |____Documento STIGT.01
    |
    |____Etapa IGT02
        |
        |____Documento STIGT.02
```

![Figura 0](img/brainstorm_figura0.jpg)


### **Tabela 7**: EEE - Identificação da Disciplina

| Campo EEE | Descrição                           |
| :-------: | :---------------------------------- |
|    ARQ    | Arquitetura, Urbanismo e Paisagismo |
|    CIV    | Civil                               |
|    ELE    | Elétrica                            |
|    EQP    | Equipamentos de Levantamento        |
|    GRL    | Geral*                              |
|    MEC    | Mecânica                            |
|    OEM    | O&M da Usina                        |
|    PLN    | Planejamento                        |
|    QUA    | Qualidade                           |
|    TEC    | Documentação Técnica                |
|    ...    | ...                                 |

> __*__ Em Caso de Disciplina ‘Geral’ localizar o sistema mais próximo na tabela 8.

### **Tabela 8**: HH - Identificação da subdisciplina

|  GGG  | Campo HH | Descrição                                               |
| :---: | :------: | :------------------------------------------------------ |
|  ARQ  |    AC    | Acabamentos de Arquitetura                              |
|  ARQ  |    AR    | Arranjos Gerais/Layout                                  |
|  ARQ  |    UR    | Urbanismo/Paisagismo                                    |
|  CIV  |    AR    | Arranjos Gerais/Layout                                  |
|  CIV  |    DE    | Sistemas de drenagem                                    |
|  CIV  |    EA    | Armação                                                 |
|  CIV  |    EF    | Estruturas de concreto - Formas                         |
|  CIV  |    EM    | Estruturas metálicas                                    |
|  CIV  |    GG    | Geologia/Geotécnica                                     |
|  CIV  |    HH    | Hidrologia/Hidráulica                                   |
|  CIV  |    IN    | Instrumentação Civil                                    |
|  CIV  |    PV    | Pavimentação e Terraplanagem                            |
|  CIV  |    RS    | Redes de Serviços                                       |
|  CIV  |    TR    | Tratamento de Fundações e Taludes                       |
|  ELE  |    AT    | Aterramento                                             |
|  ELE  |    BB    | Barramento Blindado de fases isoladas                   |
|  ELE  |    BC    | Baterias e Carregadores                                 |
|  ELE  |    BT    | Painel de Serviços Auxiliares de Baixa Tensão (CA/CC)   |
|  ELE  |    CB    | Cablagem                                                |
|  ELE  |    CE    | Condutos para Cabos                                     |
|  ELE  |    CG    | Cubículos Associados ao Gerador                         |
|  ELE  |    CM    | Cubículos de Serviços Auxiliares de Média Tensão        |
|  ELE  |    CP    | Sistema de Proteção                                     |
|  ELE  |    CS    | Sistema de Comando, Controle e Supervisão               |
|  ELE  |    EE    | Estudos Elétricos                                       |
|  ELE  |    ES    | Equipamentos de Pátio da Subestação                     |
|  ELE  |    EX    | Sistema de Excitação                                    |
|  ELE  |    GD    | Grupo Diesel de Emergência                              |
|  ELE  |    GE    | Gerador                                                 |
|  ELE  |    GI    | Barramento Blindado SF6                                 |
|  ELE  |    IE    | Instalação Elétrica                                     |
|  ELE  |    IT    | Iluminação e Tomadas                                    |
|  ELE  |    LT    | Linha de Transmissão                                    |
|  ELE  |    MT    | Cubículo de Média Tensão                                |
|  ELE  |    PE    | Painel de Parada de Emergência                          |
|  ELE  |    PH    | Controle Pitch (Eólica)                                 |
|  ELE  |    RD    | Registrador Digital de Perturbação (Oscilografia)       |
|  ELE  |    RL    | Reator Limitador de Corrente                            |
|  ELE  |    RT    | Regulador de Tensão                                     |
|  ELE  |    RV    | Regulador de Velocidade                                 |
|  ELE  |    SA    | Sistema Auxiliares Elétricos                            |
|  ELE  |    SE    | Sistema de Medição de Energia                           |
|  ELE  |    SL    | Equipamentos de Saída de Linha                          |
|  ELE  |    SM    | Sistemas Auxiliares Mecânicos                           |
|  ELE  |    TE    | Transformador Elevador                                  |
|  ELE  |    TI    | Transformador de Iluminação                             |
|  ELE  |    TL    | Sistema de Telecomunicação                              |
|  ELE  |    TR    | Transformador de Regulação                              |
|  ELE  |    TS    | Transformador de Serviços Auxiliares                    |
|  ELE  |    VE    | Sistema de Vigilância Eletrônica                        |
|  ELE  |    YW    | Controle Yaw (Eólica)                                   |
|  ELE  |    ST    | String Box                                              |
|  ELE  |    IV    | Inversor de frequência                                  |
|  EQP  |    MG    | Máquina Limpa Grades                                    |
|  EQP  |    PA    | Ponte Rolante Auxiliar                                  |
|  EQP  |    PJ    | Pórtico Rolante de Jusante do Vertedouro                |
|  EQP  |    PM    | Pórtico Rolante de Montante do Vertedouro               |
|  EQP  |    PO    | Ponte Rolante da Oficina Eletromecânica                 |
|  EQP  |    PP    | Ponte Rolante Principal                                 |
|  EQP  |    PS    | Pórtico Rolante do Tubo de Sucção                       |
|  EQP  |    PT    | Pórtico Rolante da Tomada d'água                        |
|  EQP  |    TM    | Talha Manual                                            |
|  MEC  |    AC    | Sistema de Ar Comprimido                                |
|  MEC  |    AF    | Arranjo Físico/Layout                                   |
|  MEC  |    AI    | Sistema de Combate a Incêndio                           |
|  MEC  |    AM    | Acabamentos Metálicos                                   |
|  MEC  |    AN    | Sistema de Água Nebulizada dos Transformadores          |
|  MEC  |    AP    | Sistema de Água Potável                                 |
|  MEC  |    AR    | Sistema de Água de Resfriamento                         |
|  MEC  |    AS    | Sistema de Água de Serviço                              |
|  MEC  |    CH    | Centrais Hidráulicas                                    |
|  MEC  |    CO    | Sistema de CO2                                          |
|  MEC  |    CP    | Comportas                                               |
|  MEC  |    DR    | Sistema de Drenagem                                     |
|  MEC  |    EE    | Sistema de Tratamento de Esgoto                         |
|  MEC  |    EL    | Elevador                                                |
|  MEC  |    ES    | Sistema de Esgotamento e Enchimento das Unidades        |
|  MEC  |    GB    | Gear Box (Eólica)                                       |
|  MEC  |    IN    | Instrumentação                                          |
|  MEC  |    MA    | Mancais                                                 |
|  MEC  |    MH    | Sistema de Medições Hidráulicas                         |
|  MEC  |    MO    | Sistema de Monitoramento                                |
|  MEC  |    OM    | Oficina Mecânica                                        |
|  MEC  |    PA    | Pás (Eólica)                                            |
|  MEC  |    PH    | Controle Pitch (Eólica)                                 |
|  MEC  |    RV    | Regulador de Velocidade da Turbina                      |
|  MEC  |    SI    | Sistema de Coleta e Separação de Água/Óleo Isolante     |
|  MEC  |    SL    | Sistema de Tratamento de Óleo Lubrificante              |
|  MEC  |    SR    | Sistema de Rebaixamento de Nível                        |
|  MEC  |    TB    | Tubulação Embutida                                      |
|  MEC  |    TU    | Turbina                                                 |
|  MEC  |    TX    | Tubulação Exposta                                       |
|  MEC  |    VC    | Sistema de Ar Condicionado                              |
|  MEC  |    VE    | Sistema de Ventilação                                   |
|  MEC  |    VS    | Vazão Sanitária                                         |
|  MEC  |    SH    | Sistema Hidráulico de Limpezas dos Módulos Fotovoltaico |
|  OEM  |    GO    | Geral Operação da Usina                                 |
|  PLN  |    AE    | Acompanhamento Executivo                                |
|  PLN  |    CO    | Comissionamento                                         |
|  PLN  |    FE    | Fornecimento Eletromecânico                             |
|  PLN  |    FI    | Financeiro                                              |
|  PLN  |    ME    | Montagem Eletromecânica                                 |
|  PLN  |    OC    | Obra Civil                                              |
|  PLN  |    PJ    | Projeto                                                 |
|  PLN  |    PR    | Programação                                             |
|  QUA  |    QA    | Auditoria de Sistema de Gestão de Qualidade             |
|  QUA  |    PL    | Plano                                                   |
|  QUA  |    PR    | Procedimento                                            |
|  QUA  |    TR    | Treinamento                                             |
|  QUA  |    CI    | Convocação de Inspeção                                  |
|  TEC  |    RG    | Relatório de Gestão de Documentos                       |
|  GRL  |    GG    | Geral                                                   |

### **Tabela 9**: II - Tipologia do documento

| Campo II | Descrição                                              |
| :------: | :----------------------------------------------------- |
|    AA    | Arquitetura / Topologia de Redes                       |
|    AC    | Ação Corretiva e Preventiva                            |
|    AQ    | Atestado de Qualidade                                  |
|    BI    | Boletim de Inspeção                                    |
|    CA    | Certificado de Materiais                               |
|    CC    | Certificado de Conclusão de Comissionamento            |
|    CM    | Certificado de Conclusão de Montagem                   |
|    CP    | Critério de Projeto                                    |
|    CQ    | Croquis                                                |
|    CR    | Cronograma                                             |
|    CT    | Catálogo                                               |
|    DB    | Data Book                                              |
|    DD    | Diagrama Dimensional                                   |
|    DE    | Desenhos Civil, Elétrico e Mecânico                    |
|    DF    | Diagrama Funcional                                     |
|    DI    | Diagrama de Interligação de Equipamentos e Painéis     |
|    DL    | Diagrama Lógico                                        |
|    DM    | Detalhes de Montagem de Equipamentos                   |
|    DO    | Diário de Obra                                         |
|    DT    | Detalhes Típicos/Padrões                               |
|    DU    | Diagramas Unifilares e Esquemáticos                    |
|    ET    | Especificação Técnica                                  |
|    FD    | Folha de Dados do Equipamento                          |
|    FI    | Diagrama de Fiação                                     |
|    FL    | Fluxograma                                             |
|    FR    | Formulário                                             |
|    FT    | Diagrama Funcional Integrado                           |
|    IE    | Instruções Executivas                                  |
|    IT    | Instruções de Trabalho                                 |
|    LA    | Lista de Aprovisionamento de Materiais                 |
|    LC    | Lista de Cabos                                         |
|    LD    | Lista de Documentos                                    |
|    LE    | Lista de Estimativas de Materiais                      |
|    LF    | Lista de Ferro                                         |
|    LI    | Lista de Instrumentos                                  |
|    LM    | Lista de Materiais                                     |
|    LP    | Lista de Pontos / Sinais                               |
|    LQ    | Lista de Equipamentos                                  |
|    MC    | Memória de Cálculo                                     |
|    MD    | Memorial Descritivo                                    |
|    MM    | Manual de Montagem                                     |
|    MN    | Manual de Comissionamento                              |
|    MO    | Manual de Operação e Manutenção                        |
|    MP    | Modificação de Projeto no Campo                        |
|    MQ    | Manual de Qualidade                                    |
|    NC    | Não Conformidades                                      |
|    OC    | Orçamento                                              |
|    OR    | Organograma                                            |
|    PC    | Plano de Comissionamento                               |
|    PE    | Programa de Ensaios                                    |
|    PI    | Plano de Inspeção e Controle da Qualidade (PICQ)       |
|    PL    | Programa de Treinamento                                |
|    PN    | Procedimento de Inspeção                               |
|    PQ    | Plano ou Procedimento de Qualidade                     |
|    PT    | Procedimento de Teste                                  |
|    RA    | Relatório de Análise de Documentos Recebidos           |
|    RD    | Relatório de Documentos                                |
|    RE    | Relatório de Alteração de Especificação Técnica (RAET) |
|    RF    | Relatório de Inspeção em Fábrica                       |
|    RI    | Relatório de Inspeção em Campo                         |
|    RN    | Ata de Reunião                                         |
|    RP    | Relatório de Progresso                                 |
|    RQ    | Relatório de Qualidade                                 |
|    RT    | Relatório Técnico                                      |
|    RV    | Relatório de Viagem                                    |
|    SB    | Lista de Sobressalentes                                |
|    SX    | Sumário Executivo                                      |
|    TA    | Teste de Aceitação                                     |
|    TI    | Tabela de Interligação Externa                         |
|    PB    | Projeto Básico                                         |

### **JJJJ**, número sequencial de 0000 a 9999.

### **Tabela 10**: KKK - Identificação da revisão

|                        Campo KKK                        | Descrição                                      |
| :-----------------------------------------------------: | :--------------------------------------------- |
|                        R00 a R99                        | Revisão numérica - Documentos aprovados        |
| R0A, R0B, R0C, ...<br> R1A, R1B, ... <br> R2A, R3A, ... | Revisão alfanumérica - Documentos em aprovação |

X - XX - Não
A - B - 00 - 0A - 0B - 01

XXX - Sim
00A - 00B - 000 - 01A - 01B - 001

____________________________________________________________________________
### **Tabela 6**: FFF - Identificação do número da estrutura/ tensão

|     Campo FFF     | Descrição                                                  |
| :---------------: | :--------------------------------------------------------- |
|        000        | Geral                                                      |
| 001, 002,..., 299 | Específico para unidade, bloco, vão, etc.                  |
|        3XX        | >= 69 kV                                                   |
|        4XX        | >= 138 kV                                                  |
|        5XX        | >= 230 kV                                                  |
|        6XX        | >= 345 kV                                                  |
|        7XX        | >= 500 kV                                                  |
|        8XX        | >= 750 kV                                                  |
|        900        | <= 125 Vcc                                                 |
|        901        | 127, 220, 380, 440 Vca - 1 kV                              |
|        915        | 13,8-15 kV                                                 |
|        935        | 34,5-35 kV                                                 |
|        972        | 69-72 kV                                                   |
|        999        | Atenda a mais de uma unidade, bloco, vão, mas não a todos. |

### **Tabela 4**: EEE - Identificação do setor da Instalação

| Campo EEE | Descrição                |
| :-------: | :----------------------- |
|    GRL    | Geral                    |
|    USN    | Usina                    |
|    CSF    | Casa de Força            |
|    EDC    | Edifício de Comando      |
|    TMA    | Tomada d'Água            |
|    TBS    | Tubo de Sucção           |
|    CNA    | Canal de Adução          |
|    CNF    | Canal de Fuga            |
|    VRT    | Vertedouro               |
|    BGP    | Barragem Principal       |
|    RSV    | Reservatório             |
|    SES    | Barramento de Subestação |
|    CSR    | Casa de relés            |
|    SLR    | Sala de relés            |
|    NCL    | Nacele                   |
|    TOR    | Torre                    |
|    HUB    | Hub                      |
|    AEG    | Aerogerador              |
|    FND    | Fundação                 |
|    APT    | Acesso/Plataforma        |
|    TOR    | Torre de Transmissão     |
|    UNG    | Unidade Geradora         |
|    MDF    | Módulo Fotovoltaico      |
|    ETC    | Eletrocentro             |

Tipo do sistema: (G) geração, (T) transmissão, (D) distribuição **Definido no campo AA**

**Tipo da instalação**: hidro, termo, eólica, solar, nuclear; subestação, linha, estação repetidora; PCH, subestação, LD, etc

Local de instalação: UF, município, transnacional, interestadual, etc. **Entrar como metadado**

**Módulo ANEEL ?**

**Nível de tensão/isolamento**: 800 kV, 500 kV, 230 kV, etc.

**Disciplina geral**: arquitetura (main), civil, eletromecânica, equipamento, rede de dados, telecomunicações, proteção (controle e automação), elétrica, mecânica, meio-ambiente, fundiário, coordenação, gestão, inspeção, etc.

**Subdisciplina**: Edificação, fundação, galeria de cabos, barramento aéreo, instalação, barramento de processos, barramento de estação, arquitetura de rede, SDH, SAX, ar condicionado, TAF (CFI), etc.

**Tipo do documento**: desenho, arranjo, vista, corte, pradrão, modelo, uniformização, nota técnica, relatório, certificado, ata, R3, R4, etc.

Outros:

Unificar os status: aprovado, aprovado com cometários, reprovado, aprovado para fabricação, etc.
Separar fluxos de G&T.

- Projetos básicos
- Projetos executivos
- R4
- Especificações e memórias
- Inspeção
- Relatórios EPE
