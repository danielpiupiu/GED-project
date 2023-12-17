Chesf - GERAÇÃO - D.E.PE.GH.01.00 - Requisitos Elaboração de Documentos

# Critérios para Codificação de desenhos e documentos

Todos os desenhos e documentos deverão ser identificados de acordo com os requisitos determinados a seguir.

## Codificação para Revisões:

1. Documentos para Aprovação:
    
    Revisão alfanumérica.<br>
    ``Ex: VISÃO GERAL DOS PARQUES - W-09661-DE-1-D14-0001``<br>
    CÓDIGO CHESF: ECND-E-GE00-CAR-DE-001-RA (Emissão Inicial para aprovação revisão A).<br>
    Após a emissão inicial para aprovação RA prosseguirá RB,RC,RD...<br>
    Após aprovação CHESF será emitida a emissão inicial aprovada R0.<br>
    Depois de aprovada a emissão inicial R0, caso haja novos comentários futuros, inicia-se a R0A, R0B...<br>
    ECND-E-GE00-CAR-DE-001-R0A (em elaboração na revisão R0A, após a R0).

2. Documentos Aprovados:
    
    Após a aprovação da CHESF deverá ser gerada Revisão apenas numérica.<br>
    ``Ex: VISÃO GERAL DOS PARQUES - W-09661-DE-1-D14-0001``<br>
    CÓDIGO CHESF: ECND-E-GE00-CAR-DE-001-R0 (emissão inicial aprovada) ECND-E-GE00-CAR-DE-001-R1 (Após aprovação da versão 0A, 0B... será gerada a revisão R1).<br>
    Desta forma teremos sempre documentos aprovados com revisão apenas numérica, enquanto que para aprovação teremos sempre documentos alfanuméricos.

A identificação deve ser dada pela codificação:

**``XXX - P - VVNN - SUU - ZZ - YYY - RKK``**

Onde:

|    XXX    |          P           |                  VVNN                   |                  SUU                   |               ZZ                |    YYY     |                               RKK                                |
| :-------: | :------------------: | :-------------------------------------: | :------------------------------------: | :-----------------------------: | :--------: | :--------------------------------------------------------------: |
| **Usina** | **Etapa do Projeto** |           **Setor/Estrutura**           | **Disciplina, Sistema ou equipamento** | **Tipo ou função do documento** | **Número** |                           **Revisão**                            |
| Tabela 1  |       Tabela 2       | **VV**: Tabela 3 <br> **NN**: Tabela 4  | **S**: Tabela 5 <br> **UU**: Tabela 6  |            Tabela 7             |     -      |                        Aprovados R0 a R99                        |
|           |                      |      **VV**: Setor da Instalação.       |           **S**: Disciplina.           |                                 |            |                         Para Aprovação:                          |
|           |                      | **NN**: Número da unidade vão ou bloco. |    **UU**: Sistema ou equipamento.     |                                 |            | RA, RB...(Inicial) <br> Após: R0A, R0B... <br> Após: R1A, R1B... |

### **Tabela 1**: XXX - Identificação da Usina

| Código | Usina                            |
| :----: | :------------------------------- |
|  UAS   | Usina Apolônio Sales             |
|  UBE   | Usina Boa Esperança              |
|  ULG   | Usina Luiz Gonzaga               |
|  USD   | Usina de Paulo Afonso II         |
|  USQ   | Usina de Paulo Afonso IV         |
|  UST   | Usina de Paulo Afonso III        |
|  USU   | Usina de Paulo Afonso I          |
|  UTC   | Usina Térmica de Camaçari        |
|  USB   | Usina de Sobradinho              |
|  UXG   | Usina de Xingó                   |
|  ECNU  | Usina Eólica de Casa Nova I      |
|  ECND  | Usina Eólica de Casa Nova II     |
|  ECNT  | Usina Eólica de Casa Nova III    |
|  FPTL  | Usina Fotovoltaica de Petrolina  |
|  FSOB  | Usina Fotovoltaica de Sobradinho |
|  HPTL  | Usina Heliotérmica de Petrolina  |

### **Tabela 2**: P – Etapa do Projeto

| Código | Etapa                      |
| :----: | :------------------------- |
|   B    | Projeto Básico             |
|   E    | Projeto Executivo          |
|   C    | Como Construído (As Built) |

### **Tabela 3**: VV - Identificação do setor da Instalação

| Item  |  VV   | Setor                |
| :---: | :---: | :------------------- |
|   1   |  GE   | Geral                |
|   2   |  US   | Usina                |
|   3   |  CF   | Casa de Força        |
|   4   |  EC   | Edifício de Comando  |
|   5   |  TA   | Tomada d'Água        |
|   6   |  TS   | Tubo de Sucção       |
|   7   |  CA   | Canal de Adução      |
|   8   |  CG   | Canal de Fuga        |
|   9   |  VT   | Vertedouro           |
|  10   |  BP   | Barragem Principal   |
|  11   |  RE   | Reservatório         |
|  12   |  SE   | Subestação           |
|  13   |  NC   | Nacele               |
|  14   |  TO   | Torre                |
|  15   |  HB   | Hub                  |
|  16   |  AE   | Aerogerador          |
|  17   |  FD   | Fundação             |
|  18   |  AP   | Acesso/Plataforma    |
|  19   |  LT   | Linha de Transmissão |
|  20   |  UG   | Unidade Geradora     |
|  21   |  MF   | Módulo Fotovoltaico  |
|  22   |  ET   | Eletrocentro         |

### **Tabela 4**: NN - Identificação do número da estrutura

|   Código   | Estrutura                                                  |
| :--------: | :--------------------------------------------------------- |
|     00     | Geral                                                      |
| 01, 02,... | Específico para unidade, bloco, vão, etc.                  |
|     99     | Atenda a mais de uma unidade, bloco, vão, mas não a todos. |

### **Tabela 5**: S - Identificação da Disciplina

| Item  |   S   | Disciplina                          |
| :---: | :---: | :---------------------------------- |
|  1.   |   A   | Arquitetura, Urbanismo e Paisagismo |
|  2.   |   C   | Civil                               |
|  3.   |   E   | Elétrica                            |
|  4.   |   L   | Equipamentos de Levantamento        |
|  5.   |   G   | Geral*                              |
|  6.   |   M   | Mecânica                            |
|  7.   |   O   | O&M da Usina                        |
|  8.   |   P   | Planejamento                        |
|  9.   |   Q   | Qualidade                           |
|  10.  |   T   | Documentação Técnica                |

> __*__ Em Caso de Disciplina ‘Geral’ localizar o sistema mais próximo na tabela 6.

### **Tabela 6**: UU - Identificação do sistema ou do equipamento

|   S   |  UU   | Sistema ou Equipamento A AC                             |
| :---: | :---: | :------------------------------------------------------ |
|   A   |  AC   | Acabamentos de Arquitetura                              |
|   A   |  AR   | Arranjos Gerais/Layout                                  |
|   A   |  UR   | Urbanismo/Paisagismo                                    |
|   C   |  AR   | Arranjos Gerais/Layout                                  |
|   C   |  DE   | Sistemas de drenagem                                    |
|   C   |  EA   | Armação                                                 |
|   C   |  EF   | Estruturas de concreto - Formas                         |
|   C   |  EM   | Estruturas metálicas                                    |
|   C   |  GG   | Geologia/Geotécnica                                     |
|   C   |  HH   | Hidrologia/Hidráulica                                   |
|   C   |  IN   | Instrumentação Civil                                    |
|   C   |  PV   | Pavimentação e Terraplanagem                            |
|   C   |  RS   | Redes de Serviços                                       |
|   C   |  TR   | Tratamento de Fundações e Taludes                       |
|   E   |  AT   | Aterramento                                             |
|   E   |  BB   | Barramento Blindado de fases isoladas                   |
|   E   |  BC   | Baterias e Carregadores                                 |
|   E   |  BT   | Painel de Serviços Auxiliares de Baixa Tensão (CA/CC)   |
|   E   |  CB   | Cablagem                                                |
|   E   |  CE   | Condutos para Cabos                                     |
|   E   |  CG   | Cubículos Associados ao Gerador                         |
|   E   |  CM   | Cubículos de Serviços Auxiliares de Média Tensão        |
|   E   |  CP   | Sistema de Proteção                                     |
|   E   |  CS   | Sistema de Comando, Controle e Supervisão               |
|   E   |  EE   | Estudos Elétricos                                       |
|   E   |  ES   | Equipamentos de Pátio da Subestação                     |
|   E   |  EX   | Sistema de Excitação                                    |
|   E   |  GD   | Grupo Diesel de Emergência                              |
|   E   |  GE   | Gerador                                                 |
|   E   |  GI   | Barramento Blindado SF6                                 |
|   E   |  IE   | Instalação Elétrica                                     |
|   E   |  IT   | Iluminação e Tomadas                                    |
|   E   |  LT   | Linha de Transmissão                                    |
|   E   |  MT   | Cubículo de Média Tensão                                |
|   E   |  PE   | Painel de Parada de Emergência                          |
|   E   |  PH   | Controle Pitch (Eólica)                                 |
|   E   |  RD   | Registrador Digital de Perturbação (Oscilografia)       |
|   E   |  RL   | Reator Limitador de Corrente                            |
|   E   |  RT   | Regulador de Tensão                                     |
|   E   |  RV   | Regulador de Velocidade                                 |
|   E   |  SA   | Sistema Auxiliares Elétricos                            |
|   E   |  SE   | Sistema de Medição de Energia                           |
|   E   |  SL   | Equipamentos de Saída de Linha                          |
|   E   |  SM   | Sistemas Auxiliares Mecânicos                           |
|   E   |  TE   | Transformador Elevador                                  |
|   E   |  TI   | Transformador de Iluminação                             |
|   E   |  TL   | Sistema de Telecomunicação                              |
|   E   |  TR   | Transformador de Regulação                              |
|   E   |  TS   | Transformador de Serviços Auxiliares                    |
|   E   |  VE   | Sistema de Vigilância Eletrônica                        |
|   E   |  YW   | Controle Yaw (Eólica)                                   |
|   E   |  ST   | String Box                                              |
|   E   |  IV   | Inversor de frequência                                  |
|   L   |  MG   | Máquina Limpa Grades                                    |
|   L   |  PA   | Ponte Rolante Auxiliar                                  |
|   L   |  PJ   | Pórtico Rolante de Jusante do Vertedouro                |
|   L   |  PM   | Pórtico Rolante de Montante do Vertedouro               |
|   L   |  PO   | Ponte Rolante da Oficina Eletromecânica                 |
|   L   |  PP   | Ponte Rolante Principal                                 |
|   L   |  PS   | Pórtico Rolante do Tubo de Sucção                       |
|   L   |  PT   | Pórtico Rolante da Tomada d'água                        |
|   L   |  TM   | Talha Manual                                            |
|   M   |  AC   | Sistema de Ar Comprimido                                |
|   M   |  AF   | Arranjo Físico/Layout                                   |
|   M   |  AI   | Sistema de Combate a Incêndio                           |
|   M   |  AM   | Acabamentos Metálicos                                   |
|   M   |  AN   | Sistema de Água Nebulizada dos Transformadores          |
|   M   |  AP   | Sistema de Água Potável                                 |
|   M   |  AR   | Sistema de Água de Resfriamento                         |
|   M   |  AS   | Sistema de Água de Serviço                              |
|   M   |  CH   | Centrais Hidráulicas                                    |
|   M   |  CO   | Sistema de CO2                                          |
|   M   |  CP   | Comportas                                               |
|   M   |  DR   | Sistema de Drenagem                                     |
|   M   |  EE   | Sistema de Tratamento de Esgoto                         |
|   M   |  EL   | Elevador                                                |
|   M   |  ES   | Sistema de Esgotamento e Enchimento das Unidades        |
|   M   |  GB   | Gear Box (Eólica)                                       |
|   M   |  IN   | Instrumentação                                          |
|   M   |  MA   | Mancais                                                 |
|   M   |  MH   | Sistema de Medições Hidráulicas                         |
|   M   |  MO   | Sistema de Monitoramento                                |
|   M   |  OM   | Oficina Mecânica                                        |
|   M   |  PA   | Pás (Eólica)                                            |
|   M   |  PH   | Controle Pitch (Eólica)                                 |
|   M   |  RV   | Regulador de Velocidade da Turbina                      |
|   M   |  SI   | Sistema de Coleta e Separação de Água/Óleo Isolante     |
|   M   |  SL   | Sistema de Tratamento de Óleo Lubrificante              |
|   M   |  SR   | Sistema de Rebaixamento de Nível                        |
|   M   |  TB   | Tubulação Embutida                                      |
|   M   |  TU   | Turbina                                                 |
|   M   |  TX   | Tubulação Exposta                                       |
|   M   |  VC   | Sistema de Ar Condicionado                              |
|   M   |  VE   | Sistema de Ventilação                                   |
|   M   |  VS   | Vazão Sanitária                                         |
|   M   |  SH   | Sistema Hidráulico de Limpezas dos Módulos Fotovoltaico |
|   O   |  GO   | Geral Operação da Usina                                 |
|   P   |  AE   | Acompanhamento Executivo                                |
|   P   |  CO   | Comissionamento                                         |
|   P   |  FE   | Fornecimento Eletromecânico                             |
|   P   |  FI   | Financeiro                                              |
|   P   |  ME   | Montagem Eletromecânica                                 |
|   P   |  OC   | Obra Civil                                              |
|   P   |  PJ   | Projeto                                                 |
|   P   |  PR   | Programação                                             |
|   Q   |  QA   | Auditoria de Sistema de Gestão de Qualidade             |
|   Q   |  PL   | Plano                                                   |
|   Q   |  PR   | Procedimento                                            |
|   Q   |  TR   | Treinamento                                             |
|   Q   |  CI   | Convocação de Inspeção                                  |
|   T   |  RG   | Relatório de Gestão de Documentos                       |
|   G   |  GG   | Geral                                                   |

### **Tabela 7**: ZZ - Tipo ou função do documento

| Item  |  ZZ   | Documento                                              |
| :---: | :---: | :----------------------------------------------------- |
|   1   |  AA   | Arquitetura / Topologia de Redes                       |
|   2   |  AC   | Ação Corretiva e Preventiva                            |
|   3   |  AQ   | Atestado de Qualidade                                  |
|   4   |  BI   | Boletim de Inspeção                                    |
|   5   |  CA   | Certificado de Materiais                               |
|   6   |  CC   | Certificado de Conclusão de Comissionamento            |
|   7   |  CM   | Certificado de Conclusão de Montagem                   |
|   8   |  CP   | Critério de Projeto                                    |
|   9   |  CQ   | Croquis                                                |
|  10   |  CR   | Cronograma                                             |
|  11   |  CT   | Catálogo                                               |
|  12   |  DB   | Data Book                                              |
|  13   |  DD   | Diagrama Dimensional                                   |
|  14   |  DE   | Desenhos Civil, Elétrico e Mecânico                    |
|  15   |  DF   | Diagrama Funcional                                     |
|  16   |  DI   | Diagrama de Interligação de Equipamentos e Painéis     |
|  17   |  DL   | Diagrama Lógico                                        |
|  18   |  DM   | Detalhes de Montagem de Equipamentos                   |
|  19   |  DO   | Diário de Obra                                         |
|  20   |  DT   | Detalhes Típicos/Padrões                               |
|  21   |  DU   | Diagramas Unifilares e Esquemáticos                    |
|  22   |  ET   | Especificação Técnica                                  |
|  23   |  FD   | Folha de Dados do Equipamento                          |
|  24   |  FI   | Diagrama de Fiação                                     |
|  25   |  FL   | Fluxograma                                             |
|  26   |  FR   | Formulário                                             |
|  27   |  FT   | Diagrama Funcional Integrado                           |
|  28   |  IE   | Instruções Executivas                                  |
|  29   |  IT   | Instruções de Trabalho                                 |
|  30   |  LA   | Lista de Aprovisionamento de Materiais                 |
|  31   |  LC   | Lista de Cabos                                         |
|  32   |  LD   | Lista de Documentos                                    |
|  33   |  LE   | Lista de Estimativas de Materiais                      |
|  34   |  LF   | Lista de Ferro                                         |
|  35   |  LI   | Lista de Instrumentos                                  |
|  36   |  LM   | Lista de Materiais                                     |
|  37   |  LP   | Lista de Pontos / Sinais                               |
|  38   |  LQ   | Lista de Equipamentos                                  |
|  39   |  MC   | Memória de Cálculo                                     |
|  40   |  MD   | Memorial Descritivo                                    |
|  41   |  MM   | Manual de Montagem                                     |
|  42   |  MN   | Manual de Comissionamento                              |
|  43   |  MO   | Manual de Operação e Manutenção                        |
|  44   |  MP   | Modificação de Projeto no Campo                        |
|  45   |  MQ   | Manual de Qualidade                                    |
|  46   |  NC   | Não Conformidades                                      |
|  47   |  OC   | Orçamento                                              |
|  48   |  OR   | Organograma                                            |
|  49   |  PC   | Plano de Comissionamento                               |
|  50   |  PE   | Programa de Ensaios                                    |
|  51   |  PI   | Plano de Inspeção e Controle da Qualidade (PICQ)       |
|  52   |  PL   | Programa de Treinamento                                |
|  53   |  PN   | Procedimento de Inspeção                               |
|  54   |  PQ   | Plano ou Procedimento de Qualidade                     |
|  55   |  PT   | Procedimento de Teste                                  |
|  56   |  RA   | Relatório de Análise de Documentos Recebidos           |
|  57   |  RD   | Relatório de Documentos                                |
|  58   |  RE   | Relatório de Alteração de Especificação Técnica (RAET) |
|  59   |  RF   | Relatório de Inspeção em Fábrica                       |
|  60   |  RI   | Relatório de Inspeção em Campo                         |
|  61   |  RN   | Ata de Reunião                                         |
|  62   |  RP   | Relatório de Progresso                                 |
|  63   |  RQ   | Relatório de Qualidade                                 |
|  64   |  RT   | Relatório Técnico                                      |
|  65   |  RV   | Relatório de Viagem                                    |
|  66   |  SB   | Lista de Sobressalentes                                |
|  67   |  SX   | Sumário Executivo                                      |
|  68   |  TA   | Teste de Aceitação                                     |
|  69   |  TI   | Tabela de Interligação Externa                         |
|  70   |  PB   | Projeto Básico                                         |