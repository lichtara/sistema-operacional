# Catálogo de Requisitos da Arquitetura Organizacional

**Identificação técnica no repositório**

```yaml
id_catalogo: CAT-REQ-AAAA-NNN
id_arquitetura: ARQ-AAAA-NNN
titulo: "[Nome da arquitetura — Catálogo de Requisitos]"
organizacao:
area_ou_processo:
id_plano: PLA-ARQ-AAAA-NNN
id_termo_de_abertura:
id_diagnostico: DIA-AAAA-NNN
id_transicao: TRA-AAAA-NNN
responsavel_pelo_catalogo:
responsavel_pela_arquitetura:
data_de_criacao: AAAA-MM-DD
data_de_aprovacao:
estado: em_consolidacao
nivel_sensibilidade: "publica | interna | confidencial | sensivel"
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Template operacional  
**Função:** Consolidação, qualificação, priorização, decisão, cobertura e governança dos requisitos da arquitetura  
**Documento de referência:** Protocolo de Arquitetura Organizacional  
**Documentos de entrada:** Transição para Arquitetura, Termo de Abertura e Plano de Arquitetura  
**Ponto de controle imediato:** PC-2 — Prontidão para desenhar

**Documentos relacionados:**

- Fundamentos da Arquitetura Organizacional;
- Protocolo de Arquitetura Organizacional;
- Matriz de Rastreabilidade da Arquitetura;
- Transição para Arquitetura Organizacional;
- Termo de Abertura da Arquitetura;
- Plano de Arquitetura;
- Matriz de Evidências;
- registros de decisão;
- registros de validação;
- Arquitetura Integrada;
- Transição para Implantação.

---

## 1. Finalidade

O Catálogo de Requisitos é a fonte oficial das condições que a arquitetura organizacional precisa atender, preservar, limitar, permitir ou preparar.

Sua função é transformar necessidades recebidas de diferentes origens em requisitos:

- identificáveis;
- necessários;
- claros;
- delimitados;
- rastreáveis;
- priorizados;
- verificáveis;
- decididos;
- governáveis ao longo do ciclo.

O catálogo deve permitir responder, para cada requisito:

1. qual condição está sendo exigida;
2. por que ela é necessária;
3. de onde surgiu;
4. quem é afetado;
5. que capacidade deverá sustentá-la;
6. qual é sua prioridade;
7. que limites e dependências existem;
8. como seu atendimento será reconhecido;
9. quem verificará e quem aprovará;
10. que alternativas e componentes procuram atendê-la;
11. qual grau de cobertura foi alcançado;
12. que decisão explica sua aprovação, alteração, adiamento ou rejeição;
13. que parte da implantação dependerá dela;
14. como seu funcionamento será observado na operação;
15. que aprendizado poderá modificá-la no futuro.

O catálogo protege o projeto contra dois erros opostos:

- desenhar elementos que não possuem necessidade demonstrável;
- esquecer necessidades que nunca chegaram ao desenho.

## 2. Posição do catálogo no ciclo

O catálogo começa com os requisitos recebidos da transição e da abertura. Ele é consolidado antes do PC-2 e continua ativo durante toda a arquitetura.

```text
Evidências, achados, riscos e exigências
                ↓
       Requisitos iniciais
                ↓
  Catálogo consolidado e aprovado
                ↓
   PC-2 — Prontidão para desenhar
                ↓
 Capacidades, alternativas e componentes
                ↓
 Cobertura, decisão e validação
                ↓
 Arquitetura aprovada e implantação
                ↓
 Operação, indicadores e aprendizagem
```

O catálogo não é encerrado depois do PC-2. Ele recebe atualizações quando:

- o desenho revela nova necessidade legítima;
- um especialista apresenta exigência aplicável;
- uma alternativa demonstra conflito;
- um teste revela condição ausente;
- uma decisão altera prioridade ou horizonte;
- a implantação exige desdobramento verificável;
- a operação contradiz premissa anterior.

## 3. O que o catálogo governa

O catálogo governa:

- formulação dos requisitos;
- classificação;
- origem e justificativa;
- prioridade;
- decisão de aprovação;
- critérios de atendimento;
- métodos de verificação;
- relações com capacidades;
- relações com alternativas e componentes;
- conflitos e compensações;
- cobertura;
- mudanças e versões;
- passagem para implantação;
- continuidade operacional.

Ele não substitui:

- documentos de origem;
- Matriz de Evidências;
- Matriz de Rastreabilidade;
- registros de decisão;
- modelos e mapas de arquitetura;
- registros de teste e validação;
- plano de implantação;
- indicadores operacionais.

O catálogo declara e governa o requisito. Os demais artefatos demonstram sua origem, seu tratamento, sua decisão e seu resultado.

## 4. Instruções de uso

1. Duplique este arquivo para cada arquitetura real.
2. Não preencha diretamente o template-mestre.
3. Mantenha um único catálogo oficial por linha de base da arquitetura.
4. Utilize o registro mestre para visão do conjunto e uma ficha detalhada para cada requisito material.
5. Reutilize identificadores recebidos; não crie novo requisito para representar o mesmo objeto.
6. Não reutilize identificadores encerrados ou cancelados.
7. Registre a origem real; não atribua origem diagnóstica a exigência surgida depois.
8. Separe necessidade, preferência, solução, critério de desenho e atividade.
9. Divida requisitos que reúnam condições independentes.
10. Não classifique todos os requisitos como obrigatórios.
11. Não declare atendimento sem critério e verificação.
12. Não apague requisitos rejeitados, substituídos ou cancelados.
13. Atualize a Matriz de Rastreabilidade quando houver mudança material.
14. Preserve versões aprovadas e decisões relacionadas.
15. Submeta requisitos novos ou alterados à autoridade proporcional ao impacto.

### 4.1 Convenções

| Convenção | Significado |
| --- | --- |
| `[Preencher]` | Registro necessário. |
| `Não aplicável` | O campo foi examinado e não se aplica. |
| `Não determinado` | Informação ainda insuficiente. |
| `A confirmar` | Indicação provisória dependente de validação. |
| `Pendente` | Tratamento futuro com responsável e limite. |
| `REQ-ARQ-NNN` | Requisito da arquitetura. |
| `VNC-NNN` | Vínculo rastreável. |
| `VAL-NNN` | Validação. |
| `TST-NNN` | Teste ou simulação. |
| `DEC-AAAA-NNN` | Decisão formal. |
| `ITM-NNN` | Item de implantação. |
| `IND-NNN` | Indicador operacional. |

### 4.2 Regra de concisão

O registro mestre deve permitir governar o conjunto. A ficha detalhada deve conter contexto suficiente para interpretar o requisito. Evidências extensas, pareceres, testes e decisões permanecem em seus documentos oficiais.

## 5. Identificação do catálogo

| Campo | Registro |
| --- | --- |
| ID do catálogo | CAT-REQ-AAAA-NNN |
| ID da arquitetura | ARQ-AAAA-NNN |
| Título | [Nome] |
| Organização | [Nome] |
| Área ou processo | [Quando aplicável] |
| Responsável pelo catálogo | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Patrocinador | [Nome e função] |
| Data de criação | [DD/MM/AAAA] |
| Data de aprovação | [DD/MM/AAAA] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Versão | [0.1] |
| Estado | [Selecionar na seção 6] |

### 5.1 Identificadores relacionados

| Objeto | Identificador | Versão | Estado | Referência |
| --- | --- | --- | --- | --- |
| Diagnóstico | DIA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Transição | TRA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Termo de Abertura | [ID] | [Versão] | [Estado] | [Link] |
| Plano de Arquitetura | PLA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Matriz de Rastreabilidade | [ID] | [Versão] | [Estado] | [Link] |
| Registro do PC-2 | [ID] | [Versão] | [Estado] | [Link] |

## 6. Estado do catálogo

Selecione um único estado vigente.

- [ ] **Em preparação** — fontes e estrutura estão sendo reunidas.
- [ ] **Em consolidação** — requisitos estão sendo formulados, classificados e relacionados.
- [ ] **Em revisão** — qualidade, origem, prioridade e conflitos estão sendo verificados.
- [ ] **Aguardando decisão** — existem aprovações ou conflitos materiais pendentes.
- [ ] **Aprovado para desenho** — versão apta a compor o PC-2.
- [ ] **Aprovado com condições** — versão utilizável dentro dos limites registrados.
- [ ] **Em atualização** — mudanças decorrentes do desenho estão sendo incorporadas.
- [ ] **Linha de base candidata** — cobertura final está sendo verificada antes do PC-4.
- [ ] **Linha de base aprovada** — requisitos vigentes correspondem à arquitetura aprovada.
- [ ] **Em transição para implantação** — requisitos estão sendo vinculados aos itens do Módulo 4.
- [ ] **Encerrado** — ciclo concluído e histórico preservado.
- [ ] **Substituído** — outra versão constitui a referência vigente.
- [ ] **Suspenso** — tratamento temporariamente interrompido.
- [ ] **Cancelado** — catálogo não será continuado.

**Data da última mudança:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Motivo ou referência:** [Preencher]

## 7. Princípios do catálogo

### 7.1 O requisito precede o componente

Processo, papel, documento, ferramenta, automação, IA, indicador ou controle somente deve entrar na arquitetura quando existir necessidade, capacidade, risco ou decisão que o justifique.

### 7.2 A origem precisa ser localizável

Todo requisito deve derivar de:

- achado diagnóstico;
- capacidade a preservar;
- problema;
- risco;
- restrição;
- exigência externa;
- decisão legítima;
- orientação especializada;
- aprendizagem do desenho;
- condição de implantação ou operação.

### 7.3 Aprovação não demonstra atendimento

Um requisito aprovado foi aceito como condição válida. Isso não significa que a arquitetura já o atende.

### 7.4 Componente não demonstra cobertura

A existência de um componente relacionado não comprova que o critério do requisito foi atendido.

### 7.5 Verificação exige objeto e critério

Uma validação genérica da arquitetura não substitui a verificação dos requisitos obrigatórios e de maior risco.

### 7.6 Mudança não apaga história

Reformulações, rejeições, adiamentos e substituições precisam permanecer reconstruíveis.

### 7.7 A prioridade é uma decisão

Urgência, poder da pessoa solicitante e entusiasmo com uma solução não definem, isoladamente, prioridade.

### 7.8 A linguagem deve preservar abertura de desenho

O requisito descreve condição ou capacidade antes de fixar ferramenta, salvo quando a ferramenta específica constituir exigência legítima e rastreável.

## 8. O que é um requisito

Requisito de arquitetura é uma condição necessária, delimitada e verificável que a configuração futura precisa atender, preservar, impedir ou preparar.

Um requisito adequado responde:

- o que precisa ser possível ou verdadeiro;
- para quem ou em que contexto;
- dentro de que limite;
- por que isso importa;
- como será possível reconhecer atendimento.

Estrutura recomendada:

> A arquitetura deve **[verbo observável] [objeto ou condição]**, para **[resultado ou finalidade]**, respeitando **[limite, prazo, qualidade ou restrição]**.

Exemplo:

> A arquitetura deve permitir que toda demanda ativa possua responsável, estado e próxima ação localizáveis, preservando histórico e acesso compatível com o papel da pessoa usuária.

## 9. O que não é requisito

| Item recebido | O que representa | Tratamento correto |
| --- | --- | --- |
| “Implantar o sistema X” | Solução ou restrição possível | Investigar a necessidade; registrar a ferramenta apenas se sua obrigatoriedade tiver origem legítima. |
| “Fazer uma reunião semanal” | Atividade ou componente possível | Formular a condição de coordenação que precisa ser atendida. |
| “Melhorar a comunicação” | Intenção ampla | Definir informação, público, momento, confirmação e resultado necessários. |
| “Ter mais organização” | Desejo genérico | Identificar manifestação observável e capacidade requerida. |
| “Reduzir atrasos” | Resultado esperado | Definir condição arquitetural que influencia o resultado e como será verificada. |
| “A equipe não atualiza o sistema” | Sintoma ou achado | Localizar causa e formular requisito de funcionamento. |
| “Automatizar tudo” | Preferência ou promessa | Delimitar atividades elegíveis, exceções, controles e responsabilidade humana. |
| “Criar um manual” | Artefato possível | Definir que conhecimento ou continuidade precisa ser sustentado. |
| “O indicador deve ser 95%” | Meta ou critério possível | Confirmar definição, fonte, decisão e viabilidade antes de formalizar. |

### 9.1 Pergunta de conversão

> Que condição precisa existir para que a necessidade seja atendida, independentemente da primeira solução imaginada?

## 10. Arquitetura do catálogo

O catálogo possui duas camadas.

### 10.1 Registro mestre

Oferece visão governável de todos os requisitos e permite:

- ordenar;
- filtrar;
- contar;
- localizar responsáveis;
- identificar conflitos;
- acompanhar cobertura;
- preparar controles.

### 10.2 Fichas detalhadas

Preservam o contexto necessário para:

- interpretar a declaração;
- compreender origem e justificativa;
- decidir prioridade;
- avaliar alternativas;
- definir atendimento e verificação;
- analisar mudança.

### 10.3 Registros derivados

Podem ser produzidas visões por:

- prioridade;
- tipo;
- dimensão;
- capacidade;
- estado;
- cobertura;
- responsável;
- validação;
- decisão;
- implantação;
- operação.

As visões derivadas não criam novas fontes oficiais. Elas apresentam os mesmos requisitos sob perguntas diferentes.

## 11. Identificação dos requisitos

### 11.1 Padrão

```text
REQ-ARQ-NNN
```

Exemplo:

```text
REQ-ARQ-001
```

Quando o projeto exigir qualificação:

```text
ARQ-2026-001-REQ-007
```

### 11.2 Regras

- o ID é único dentro da arquitetura;
- o ID permanece estável quando a redação muda;
- o ID não deve carregar prioridade ou estado;
- um ID encerrado não pode ser reutilizado;
- requisitos importados preservam o identificador original quando possível;
- desdobramentos recebem novos IDs e vínculo com o requisito de origem.

### 11.3 Título curto

O título deve permitir localizar o requisito sem substituir sua declaração.

**Exemplo:** `Acompanhamento compartilhado de demandas`

Evitar títulos como:

- melhoria;
- sistema;
- processo;
- requisito geral;
- item 1.

## 12. Registro mestre

| ID | Título | Declaração resumida | Natureza | Dimensão | Origem | Prioridade | Estado | Cobertura | Capacidade | Responsável | Validação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-ARQ-001 | [Título] | [A arquitetura deve...] | [Tipo] | [Dimensão] | [ID] | [Obrigatório/Alta/Média/Baixa/Futuro] | Proposto | Não avaliada | [CAP-ID] | [Nome/papel] | [VAL/TST planejado] |

### 12.1 Colunas mínimas para arquitetura focal

| ID | Requisito | Origem | Prioridade | Critério | Cobertura | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-001 | [Preencher] | [ID] | [Preencher] | [Preencher] | [Estado] | [Estado] |

### 12.2 Regra da fonte oficial

O registro mestre referencia a ficha detalhada e os documentos oficiais. Quando houver divergência, prevalece:

1. a versão vigente aprovada da ficha;
2. o registro de decisão aplicável;
3. a linha de base identificada;
4. a fonte externa obrigatória, dentro de sua competência.

## 13. Ficha detalhada do requisito

Duplique esta ficha para cada requisito material.

### 13.1 Identidade

| Campo | Registro |
| --- | --- |
| ID | REQ-ARQ-NNN |
| Título | [Nome curto] |
| Versão | [0.1] |
| Estado | [Selecionar na seção 25] |
| Cobertura | [Selecionar na seção 26] |
| Sensibilidade | [Nível] |
| Data de criação | [DD/MM/AAAA] |
| Data da última revisão | [DD/MM/AAAA] |
| Responsável pelo registro | [Nome] |

### 13.2 Declaração

> A arquitetura deve [verbo observável] [objeto ou condição], para [resultado], respeitando [limites].

### 13.3 Contexto

[Explique apenas o necessário para interpretar corretamente a condição.]

### 13.4 Justificativa

[Por que o requisito é necessário?]

### 13.5 Consequência da ausência

[O que poderá ocorrer se não for atendido?]

### 13.6 Origem

| Campo | Registro |
| --- | --- |
| Objeto de origem | [ACH, CAP, PRB, RSC, RES, DEC, norma ou outro] |
| ID | [Identificador] |
| Documento oficial | [Referência e versão] |
| Trecho, seção ou localização | [Referência mínima] |
| Natureza da origem | [Diagnóstica, externa, decisória, especializada, arquitetural ou operacional] |
| Confiança | [Alta, média, baixa ou não aplicável] |

### 13.7 Classificação

| Campo | Registro |
| --- | --- |
| Natureza arquitetural | [Funcional, operacional, qualidade, limite, transição ou evolutivo] |
| Dimensão primária | [Selecionar na seção 16] |
| Dimensões secundárias | [Preencher] |
| Prioridade | [Obrigatório, alta, média, baixa ou futuro] |
| Fundamento da prioridade | [Preencher] |
| Horizonte | [Primeiro ciclo, ciclo posterior, contínuo ou condição] |

### 13.8 Relações

| Objeto | Identificadores | Vínculo canônico esperado |
| --- | --- | --- |
| Problemas | [IDs] | `REQ deriva_de PRB` |
| Capacidades a preservar | [IDs] | `REQ é_justificado_por CAP` |
| Capacidades futuras | [IDs] | `CAP responde_a REQ` |
| Critérios de desenho | [IDs] | [Vínculo definido no projeto] |
| Alternativas | [IDs] | `ALT responde_a REQ` |
| Componentes | [IDs] | `CMP atende` ou `CMP atende_parcialmente REQ` |
| Interfaces | [IDs] | [Vínculo de atendimento ou dependência] |
| Riscos | [IDs] | `REQ trata RSC` ou vínculo inverso justificado |
| Restrições | [IDs] | `REQ é_restringido_por RES` |
| Decisões | [IDs] | `REQ é_adiado_por`, `é_rejeitado_por` ou `substitui` conforme o caso |

### 13.9 Critério de atendimento

[Descreva a condição observável que deve ser verdadeira para considerar o requisito atendido.]

### 13.10 Método de verificação

| Campo | Registro |
| --- | --- |
| Método | [Revisão, inspeção, simulação, teste, demonstração, análise ou validação com pessoa] |
| Objeto verificado | [Documento, modelo, componente, interface ou resultado] |
| Cenário | [Normal, exceção, falha ou limite] |
| Evidência esperada | [Registro produzido] |
| Responsável pela verificação | [Nome/papel] |
| Momento | [PC-2, desenho, PC-3, PC-4, PC-5, implantação ou operação] |

### 13.11 Dependências e condições

| Tipo | ID/descrição | Efeito | Responsável | Prazo/gatilho |
| --- | --- | --- | --- | --- |
| Dependência | [Preencher] | [Preencher] | [Nome] | [Data/condição] |
| Premissa | [Preencher] | [Preencher] | [Nome] | [Data/condição] |
| Condição | [Preencher] | [Preencher] | [Nome] | [Data/condição] |

### 13.12 Conflitos e compensações

| Requisito ou critério | Natureza do conflito | Compensação possível | Decisão necessária |
| --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [DEC-ID] |

### 13.13 Implantação e operação

| Campo | Registro |
| --- | --- |
| Item de implantação | [ITM-ID ou a definir] |
| Critério de aceite no Módulo 4 | [Preencher] |
| Responsável futuro | [Papel] |
| Indicador ou observação operacional | [IND-ID ou método] |
| Frequência de observação | [Preencher] |
| Gatilho de revisão | [Preencher] |

### 13.14 Aprovação

**Recomendação:** [Aprovar / Aprovar com condição / Adiar / Rejeitar / Reformular]  
**Responsável pela arquitetura:** [Nome e data]  
**Validador:** [Nome e data]  
**Aprovador:** [Nome, função e data]  
**Decisão:** [DEC-ID ou referência]  
**Condições:** [Preencher]

## 14. Registro estruturado para automação

Quando o catálogo for processado por sistemas ou IA, cada requisito pode possuir representação estruturada equivalente à ficha humana.

```yaml
id: REQ-ARQ-001
titulo: "[Título curto]"
declaracao: "A arquitetura deve [...]"
natureza: funcional
dimensao_primaria: processos
dimensoes_secundarias: []
origens:
  - id: ACH-001
    relacao: deriva_de
prioridade: alta
estado: proposto
cobertura: nao_avaliada
capacidades: []
componentes: []
criterio_atendimento: "[Condição observável]"
verificacao:
  metodo: "[Método]"
  responsavel: "[Papel humano]"
  evidencia: "[Registro esperado]"
dependencias: []
restricoes: []
riscos: []
conflitos: []
decisoes: []
sensibilidade: interna
versao: 0.1
```

### 14.1 Regras de equivalência

- o registro estruturado não pode conter significado diferente da ficha aprovada;
- campos controlados devem utilizar o vocabulário oficial;
- valores ausentes permanecem explícitos;
- atualização automática exige revisão quando alterar formulação, prioridade, cobertura ou estado;
- a versão humana aprovada e a versão estruturada precisam ser correlacionáveis.

## 15. Natureza arquitetural dos requisitos

Cada requisito possui uma natureza primária.

| Natureza | Pergunta | Exemplo |
| --- | --- | --- |
| Funcional | O que a organização precisa conseguir realizar? | Toda demanda ativa deve possuir responsável e próxima ação. |
| Operacional | Em que condição o funcionamento deve ocorrer? | A atualização deve poder ser realizada durante a rotina normal. |
| Qualidade | Que atributo o funcionamento precisa possuir? | A informação crítica deve estar disponível no momento da decisão. |
| Limite ou preservação | O que deve ser impedido, restringido ou protegido? | Dados sensíveis não devem ser enviados a ferramenta não autorizada. |
| Transição | O que precisa existir para passar do atual ao futuro? | Registros ativos devem ser migrados com histórico verificável. |
| Evolutivo | Que capacidade futura entrará sob qual condição? | A automação avançada poderá entrar quando o volume justificar manutenção. |

### 15.1 Natureza não é dimensão

Um requisito funcional pode pertencer à dimensão de informação. Um requisito de limite pode pertencer à IA. Os dois eixos devem permanecer separados.

### 15.2 Requisito com mais de uma natureza

Quando duas condições puderem ser verificadas ou priorizadas separadamente, crie dois requisitos relacionados.

## 16. Dimensões dos requisitos

| Dimensão | Objeto principal | Perguntas de formulação |
| --- | --- | --- |
| Capacidades | Resultado organizacional possível | O que a organização precisa conseguir realizar? |
| Processos e fluxos | Sequência e transformação | Que entrada, trabalho, decisão e saída devem existir? |
| Papéis e autoridades | Responsabilidade e poder legítimo | Quem responde, decide, aprova, verifica e mantém? |
| Informação e dados | Conteúdo estruturado e acesso | Que informação deve existir, com que qualidade e proteção? |
| Conhecimento | Compreensão e competência preservadas | O que precisa ser aprendido, encontrado, transmitido ou atualizado? |
| Comunicação | Coordenação e sentido compartilhado | Quem precisa saber o quê, quando, por qual canal e com confirmação? |
| Documentação | Registro e memória | Que prova, instrução ou histórico precisa permanecer? |
| Tecnologia | Suporte técnico | Que capacidade técnica, disponibilidade ou integração é necessária? |
| Integrações | Relação entre sistemas e componentes | O que será transferido, em que formato e com qual tratamento de falha? |
| Inteligência artificial | Função instrumental e supervisão | Que tarefa pode ser ampliada, com quais entradas, limites e revisão? |
| Indicadores e controles | Observação e resposta | Que sinal apoiará qual decisão ou tratamento? |
| Governança | Regra e autoridade | Quem pode alterar, aceitar risco ou autorizar exceção? |
| Segurança e privacidade | Proteção | Que acesso, uso, retenção ou exposição deve ser impedido? |
| Humana e acessibilidade | Viabilidade para pessoas | Que carga, autonomia, inclusão ou condição de uso deve ser respeitada? |
| Financeira | Sustentabilidade econômica | Que limite de custo ou esforço recorrente deve ser atendido? |
| Manutenção e continuidade | Sustentação no tempo | Quem manterá, como falhas serão tratadas e quando haverá revisão? |
| Identidade | Coerência organizacional | Que valor, relação ou característica não pode ser destruído? |
| Transição | Passagem entre estados | Que migração, preparação, treinamento ou reversão será necessária? |

### 16.1 Dimensão primária e secundárias

A dimensão primária indica onde o requisito será governado. Dimensões secundárias indicam impactos ou interfaces. Repetir o requisito em vários blocos cria duplicação; relacioná-lo preserva unidade.

## 17. Fontes dos requisitos

| Fonte | Prefixo ou referência | Condição de uso |
| --- | --- | --- |
| Achado diagnóstico | ACH | Deve preservar o vínculo com evidências. |
| Problema | PRB | Deve declarar que condição precisa ser tratada. |
| Capacidade existente | CAP | Requisito de preservação ou fortalecimento. |
| Risco | RSC | Requisito pode prevenir, detectar, limitar ou responder. |
| Restrição | RES | Deve limitar alternativas de forma explícita. |
| Dependência | DEP | Requisito pode formalizar condição de funcionamento. |
| Questão aberta | QAB | Somente vira requisito quando respondida ou decidida. |
| Decisão | DEC | Deve indicar autoridade e alcance. |
| Exigência jurídica ou regulatória | Norma, artigo ou parecer | Requer fonte vigente e interpretação competente. |
| Contrato | Cláusula ou compromisso | Requer aplicabilidade ao escopo. |
| Especialista | Parecer ou orientação | Requer competência e limite da orientação. |
| Arquitetura | Teste, alternativa ou integração | Requer justificativa e aprovação posterior à abertura. |
| Implantação | Condição de transição | Deve evitar transformar tarefa em requisito arquitetural. |
| Operação | Indicador, incidente ou aprendizado | Pode exigir revisão ou reabertura. |

### 17.1 Fonte não significa autoridade automática

Uma solicitação do cliente, parecer técnico ou prática existente pode originar análise sem determinar aprovação. Origem, recomendação e decisão são registros distintos.

## 18. Rastreabilidade de origem

### 18.1 Cadeia mínima

```text
ACH, CAP, RSC, RES, exigência externa ou DEC
                         ↓
                        REQ
```

### 18.2 Registro de origem

| Requisito | Objeto de origem | Relação | Documento | Localização | Confiança | Validação da origem |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-ARQ-001 | ACH-003 | deriva_de | [Documento e versão] | [Seção/linha] | Alta | [Registro] |

### 18.3 Requisito sem origem suficiente

O requisito deve permanecer `proposto` e receber uma das ações:

- localizar a origem;
- reformular como questão aberta;
- solicitar evidência;
- registrar exigência externa;
- obter decisão legítima;
- rejeitar;
- cancelar por duplicação ou ausência de necessidade.

Requisito obrigatório sem origem suficiente constitui lacuna crítica para o PC-2.

### 18.4 Origem múltipla

Um requisito pode derivar de vários achados, riscos ou exigências. Cada origem deve possuir vínculo próprio; a ficha não deve reuni-las em texto impossível de filtrar.

## 19. Entrada dos requisitos da transição

### 19.1 Inventário inicial

| ID recebido | Declaração recebida | Fonte | Qualidade inicial | Ação necessária | Novo ID? |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Transição/seção] | [Adequado, composto, ambíguo, solução, duplicado ou sem origem] | [Manter, reformular, dividir, investigar ou rejeitar] | [Sim/Não] |

### 19.2 Preservação do sentido

Reformular um requisito para aumentar clareza não autoriza alterar sua necessidade, prioridade ou alcance sem decisão.

### 19.3 Resultado da importação

| Resultado | Quantidade | Observação |
| --- | --- | --- |
| Mantidos | [Número] | [Preencher] |
| Reformulados | [Número] | [Preencher] |
| Desdobrados | [Número] | [Preencher] |
| Fundidos | [Número] | [Preencher] |
| Devolvidos | [Número] | [Preencher] |
| Rejeitados | [Número] | [Preencher] |
| Novos | [Número] | [Preencher] |

## 20. Requisitos surgidos durante a arquitetura

### 20.1 Origens legítimas

- integração entre componentes;
- exigência técnica descoberta;
- risco revelado por alternativa;
- impacto humano identificado;
- parecer especializado;
- teste ou protótipo;
- condição de manutenção;
- necessidade de implantação;
- obrigação externa aplicável;
- decisão formal.

### 20.2 Fluxo de inclusão

```text
Necessidade descoberta
        ↓
Registro provisório
        ↓
Origem e impacto verificados
        ↓
Declaração e critério formulados
        ↓
Prioridade proposta
        ↓
Decisão proporcional
        ↓
Catálogo, plano e matriz atualizados
```

### 20.3 Registro

| ID provisório | Necessidade | Origem | Impacto | Responsável pela análise | Autoridade | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-P01 | [Preencher] | [ID/fonte] | [Escopo, prazo, risco, custo ou alternativa] | [Nome] | [Nome/função] | [Pendente] |

### 20.4 Proibição de inclusão silenciosa

Nenhum componente deve receber justificativa retroativa por requisito criado apenas para legitimar uma solução já escolhida.

## 21. Conversão de soluções solicitadas

### 21.1 Registro

| Solução recebida | Quem solicitou | Necessidade subjacente | Classificação | Requisito resultante | Tratamento da solução |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Nome/função] | [Preencher] | [Hipótese, preferência, restrição ou decisão] | [REQ-ID] | [Alternativa, obrigatória ou descartada] |

### 21.2 Ferramenta específica como requisito legítimo

Pode ocorrer quando houver:

- integração obrigatória;
- contrato vigente;
- padrão técnico institucional;
- decisão estratégica legítima;
- necessidade de continuidade;
- restrição de interoperabilidade;
- exigência regulatória.

Nesse caso, registrar:

- origem da obrigação;
- autoridade;
- prazo de validade;
- alternativas examinadas, quando cabíveis;
- riscos de dependência;
- condição de revisão.

### 21.3 Teste

> Se o nome da ferramenta fosse retirado, que condição ainda precisaria ser atendida?

## 22. Formulação dos requisitos

### 22.1 Estrutura afirmativa

> A arquitetura deve [verbo] [objeto] [condição] [resultado ou limite].

### 22.2 Estrutura de preservação

> A arquitetura deve preservar [capacidade, relação ou identidade] durante [mudança], demonstrado por [critério].

### 22.3 Estrutura de limite

> A arquitetura deve impedir ou restringir [evento, acesso ou efeito] quando [condição], mantendo [controle ou evidência].

### 22.4 Estrutura de transição

> Antes de [mudança], devem existir [condições], verificadas por [método].

### 22.5 Estrutura evolutiva

> [Capacidade futura] poderá integrar a arquitetura quando [evidência de prontidão], desde que [limites].

### 22.6 Verbos úteis

- permitir;
- registrar;
- localizar;
- transferir;
- preservar;
- restringir;
- verificar;
- alertar;
- recuperar;
- integrar;
- confirmar;
- atribuir;
- manter;
- revisar;
- descontinuar.

### 22.7 Verbos frágeis sem qualificação

- melhorar;
- otimizar;
- facilitar;
- modernizar;
- organizar;
- agilizar;
- potencializar;
- tornar inteligente.

Esses verbos precisam ser traduzidos em condição observável.

## 23. Atomicidade, hierarquia e desdobramento

### 23.1 Requisito atômico

Expressa uma condição principal que pode ser priorizada, atendida e verificada como unidade.

### 23.2 Sinais de requisito composto

- utiliza vários `e` conectando condições independentes;
- reúne segurança, velocidade e acessibilidade em uma frase;
- exige vários responsáveis ou métodos de verificação;
- uma parte pode ser aprovada e outra rejeitada;
- componentes distintos atenderão partes sem relação obrigatória.

### 23.3 Desdobramento

| Requisito pai | Requisito filho | Condição desdobrada | Relação | Cobertura do pai |
| --- | --- | --- | --- | --- |
| REQ-001 | REQ-001A | [Preencher] | é_composto_por | [Calculada pelo conjunto, não automaticamente] |

### 23.4 Regra

O requisito pai pode funcionar como necessidade agregadora. Os filhos devem possuir critérios e estados próprios quando puderem divergir.

### 23.5 Fusão

Requisitos duplicados podem ser fundidos. Os IDs anteriores permanecem com estado `substituído` e vínculo para o requisito vigente.

## 24. Priorização

### 24.1 Escala oficial

| Prioridade | Significado | Consequência típica |
| --- | --- | --- |
| Obrigatório | Sem atendimento, a arquitetura não pode ser aprovada ou utilizada dentro do escopo. | Bloqueia PC-4 ou exige exceção formal legítima. |
| Alta | Ausência compromete materialmente valor, segurança, continuidade ou decisão. | Exige tratamento no primeiro ciclo ou decisão explícita. |
| Média | Produz benefício relevante, mas pode admitir compensação ou sequência posterior. | Deve ser comparada com custo e dependências. |
| Baixa | Melhoria útil sem impacto material imediato. | Pode ser adiada sem comprometer finalidade central. |
| Futuro | Pertence a evolução condicionada por evidência de prontidão. | Não entra no primeiro ciclo sem reavaliação. |

### 24.2 Fundamentos da prioridade

- obrigação jurídica ou regulatória;
- segurança ou ética;
- requisito contratual;
- capacidade essencial;
- risco de continuidade;
- impacto sobre pessoas;
- dependência arquitetural;
- valor para decisão;
- urgência temporal legítima;
- custo do adiamento;
- reversibilidade;
- maturidade e capacidade de manutenção.

### 24.3 Matriz de priorização

| Requisito | Necessidade | Impacto da ausência | Urgência legítima | Dependência | Reversibilidade | Esforço | Prioridade proposta | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Alta/Média/Baixa] | [Preencher] | [Preencher] | [IDs] | [Alta/Média/Baixa] | [Faixa] | [Categoria] | [Nome/função] |

### 24.4 Proteções

- quantidade não define prioridade;
- pessoa hierarquicamente superior não torna item obrigatório sem fundamento;
- prazo artificial não transforma desejo em requisito essencial;
- alto esforço não reduz sozinho a necessidade;
- baixo esforço não justifica inclusão;
- prioridade deve ser revista quando a origem ou o contexto mudar.

## 25. Estados do requisito

| Estado | Significado | Condição de uso |
| --- | --- | --- |
| Proposto | Requisito formulado e ainda não decidido. | Possui origem e responsável provisórios. |
| Em revisão | Qualidade, prioridade, conflito ou viabilidade estão sendo examinados. | Revisores identificados. |
| Aprovado | Condição aceita para orientar a arquitetura. | Autoridade e versão registradas. |
| Aprovado com condição | Condição aceita dentro de limite explícito. | Condição, responsável e prazo definidos. |
| Atendido | Arquitetura demonstra cobertura completa conforme critério. | Verificação registrada ou planejada conforme etapa. |
| Parcialmente atendido | Parte da condição recebeu cobertura. | Lacuna e consequência explícitas. |
| Adiado | Atendimento foi movido para outro horizonte. | Decisão, risco e gatilho de retorno registrados. |
| Rejeitado | Condição não será incorporada. | Justificativa e autoridade registradas. |
| Substituído | Outro requisito assumiu sua função. | Vínculo de substituição registrado. |
| Cancelado | A necessidade deixou de existir ou saiu do escopo. | Motivo e data preservados. |

### 25.1 Estado não é cobertura

`Aprovado` significa que o requisito é válido. `Atendido` significa que o desenho o cobre. A validação demonstra se essa afirmação procede.

### 25.2 Requisitos encerrados

Rejeitados, substituídos e cancelados permanecem no histórico e não entram nas contagens vigentes sem indicação de estado.

## 26. Cobertura

Cobertura expressa o grau em que a arquitetura trata o requisito.

| Cobertura | Significado |
| --- | --- |
| Não avaliada | Nenhum tratamento foi examinado. |
| Sem tratamento | Não existe capacidade, alternativa ou componente suficiente. |
| Candidata | Existe proposta ainda não consolidada. |
| Parcial | Parte do critério foi atendida. |
| Completa | O critério vigente foi atendido. |
| Completa com condição | O atendimento depende de condição explícita. |
| Adiada | O tratamento foi postergado por decisão. |
| Rejeitada | O requisito não será atendido, por decisão. |
| Não aplicável | Cobertura não se aplica ao tipo de vínculo examinado. |

### 26.1 Registro de cobertura

| Requisito | Alternativa/componente | Relação | Cobertura individual | Cobertura do conjunto | Condição | Validação |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-001 | CMP-001 | atende_parcialmente | Parcial | [Parcial/Completa] | [Preencher] | [VAL/TST] |

### 26.2 Cobertura compartilhada

Um conjunto de componentes pode atender integralmente um requisito. Cada vínculo individual permanece parcial quando nenhum componente isolado satisfaz o critério.

### 26.3 Proibição de contagem substitutiva

Quantidade de componentes não demonstra cobertura. A avaliação deve confrontar o conjunto com o critério de atendimento.

## 27. Critério de atendimento

O critério de atendimento descreve o que precisa ser verdadeiro para afirmar que a arquitetura cobre o requisito.

### 27.1 Estrutura

> Considera-se atendido quando [objeto ou pessoa] consegue [resultado observável], sob [condição], sem [limite proibido], demonstrado por [evidência].

### 27.2 Exemplo

**Requisito**

> Toda demanda ativa deve possuir responsável, estado e próxima ação localizáveis.

**Critério**

> Considera-se atendido quando uma pessoa autorizada consegue localizar, em até [tempo acordado], o responsável, o estado vigente e a próxima ação de qualquer demanda ativa da amostra, com histórico de atualização preservado.

### 27.3 Elementos possíveis

- objeto observado;
- condição de uso;
- resultado;
- limite;
- qualidade;
- exceção;
- amostra;
- tempo;
- evidência;
- responsável.

### 27.4 Critérios frágeis

- “o cliente gostou”;
- “o sistema funciona”;
- “o documento foi criado”;
- “a ferramenta foi instalada”;
- “a equipe foi treinada”;
- “parece adequado”.

Esses registros podem compor evidência, mas não definem sozinhos atendimento.

## 28. Método de verificação

### 28.1 Métodos

| Método | Uso | Evidência possível |
| --- | --- | --- |
| Inspeção | Verificar presença, consistência ou configuração. | Checklist, revisão ou registro. |
| Análise | Examinar modelo, cálculo, risco ou compatibilidade. | Parecer ou memória analítica. |
| Demonstração | Mostrar funcionamento em cenário conhecido. | Registro da demonstração. |
| Simulação | Percorrer fluxo normal, exceção ou falha. | Resultado por cenário. |
| Teste | Confrontar entrada, comportamento e saída. | Caso e resultado de teste. |
| Validação com pessoa | Verificar uso, clareza, carga ou adequação. | Registro de validação. |
| Parecer especializado | Verificar condição técnica ou normativa. | Parecer identificado. |
| Indicador operacional | Observar sustentação depois da implantação. | Série, evento ou análise. |

### 28.2 Plano de verificação

| Requisito | Método | Cenário | Entrada | Resultado esperado | Evidência | Responsável | Momento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Método] | [Normal/Exceção/Falha/Limite] | [Preencher] | [Preencher] | [VAL/TST] | [Nome/papel] | [Marco] |

### 28.3 Proporcionalidade

Requisitos obrigatórios, de alto risco, pouco reversíveis, relacionados a IA, dados, segurança ou impacto humano exigem verificação mais forte e, quando cabível, independente.

## 29. Três níveis de verificação

### 29.1 Arquitetura — Módulo 3

Verifica se o desenho contém componentes e relações capazes de atender ao requisito.

### 29.2 Implantação — Módulo 4

Verifica se a configuração aprovada foi criada, alterada, migrada, treinada ou testada conforme o critério de aceite.

### 29.3 Operação — Módulo 5

Verifica se a capacidade permanece funcionando no uso real e produz o resultado esperado.

### 29.4 Registro integrado

| Requisito | Critério arquitetural | Critério de implantação | Observação operacional | Responsáveis |
| --- | --- | --- | --- | --- |
| REQ-___ | [Preencher] | [Preencher] | [IND-ID ou método] | [Papéis por módulo] |

Uma arquitetura pode atender conceitualmente a um requisito e ainda falhar na implantação ou na operação. Os três níveis não devem ser tratados como uma única aprovação.

## 30. Relação com capacidades

### 30.1 Cadeia de desenho

```text
REQ → CAP → condições de funcionamento → CMP
```

### 30.2 Registro

| Requisito | Capacidade | Natureza da capacidade | Resultado | Manifestação observável | Cobertura |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | CAP-___ | [Preservar, fortalecer ou desenvolver] | [Preencher] | [Preencher] | [Estado] |

### 30.3 Requisito sem capacidade

Pode indicar:

- requisito excessivamente técnico ou local;
- capacidade ainda não formulada;
- requisito de limite transversal;
- condição de transição;
- erro de modelagem;
- item que não é requisito arquitetural.

O resultado da análise deve ser registrado.

### 30.4 Capacidade sem requisito

Deve ser investigada como possível:

- capacidade existente a preservar;
- necessidade sem registro;
- desejo de desenho;
- componente abstrato;
- objeto órfão.

## 31. Relação com alternativas

### 31.1 Cobertura por alternativa

| Requisito | Prioridade | ALT-001 | ALT-002 | ALT-003 | Observação |
| --- | --- | --- | --- | --- | --- |
| REQ-001 | Obrigatório | Parcial | Completa | Completa com condição | [Preencher] |

### 31.2 Regra

Alternativas devem ser comparadas contra a mesma versão dos requisitos e critérios.

### 31.3 Requisito impeditivo

Uma alternativa que não atende requisito obrigatório deve:

- ser ajustada;
- ser excluída;
- receber exceção legítima;
- demonstrar que o requisito deixou de ser aplicável;
- ou motivar revisão formal do requisito.

### 31.4 Mudança durante a comparação

Quando requisito ou prioridade mudar, alternativas afetadas precisam ser reavaliadas. A comparação anterior não permanece válida por conveniência.

## 32. Relação com componentes e interfaces

### 32.1 Registro

| Requisito | Componente/interface | Relação | Contribuição | Cobertura | Responsável | Validação |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | CMP-___ | atende | [Preencher] | [Estado] | [Nome/papel] | [VAL/TST] |

### 32.2 Componente órfão

Componente sem requisito, capacidade, risco ou decisão de origem deve ser:

- relacionado à origem legítima;
- convertido em novo requisito aprovado;
- fundido;
- retirado;
- ou mantido como opcional, com justificativa explícita.

### 32.3 Interface como condição de atendimento

Quando o requisito depender da passagem entre componentes, o critério deve examinar a interface e não apenas cada parte isolada.

### 32.4 Cobertura condicionada por conjunto

Liste todos os componentes necessários e declare o que falta. Não marque `completa` antes que o conjunto satisfaça o critério.

## 33. Dependências

| Requisito | Dependência | Tipo | Fornecedor | Condição | Consequência da ausência | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | DEP-___ | [Dado, decisão, sistema, pessoa, recurso ou requisito] | [Nome/papel/projeto] | [Preencher] | [Preencher] | [Preencher] | [Estado] |

### 33.1 Dependência entre requisitos

| Requisito dependente | Depende de | Motivo | Ordem de atendimento |
| --- | --- | --- | --- |
| REQ-002 | REQ-001 | [Preencher] | REQ-001 antes de REQ-002 |

### 33.2 Dependência circular

Quando requisitos dependem mutuamente, definir:

- condição mínima inicial;
- sequência iterativa;
- experimento;
- decisão de prioridade;
- risco de bloqueio.

## 34. Restrições

| Requisito | Restrição | Origem | Efeito | Pode ser negociada? | Autoridade | Validade |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | RES-___ | [Fonte] | [Limita alternativa, componente, dado, prazo ou custo] | [Sim/Não/Condição] | [Nome/função] | [Data/condição] |

### 34.1 Restrição não é requisito automaticamente

A restrição limita o espaço de desenho. Um requisito descreve condição que a arquitetura precisa atender. Quando a restrição produzir condição verificável, os dois objetos podem ser relacionados sem serem confundidos.

### 34.2 Restrição sem efeito

Se a restrição não altera alternativa, critério, componente ou decisão, verificar se:

- perdeu validade;
- foi registrada de forma genérica;
- seu impacto não foi analisado;
- não pertence ao escopo.

## 35. Riscos e controles

| Requisito | Risco tratado ou criado | Tipo de relação | Controle | Responsável | Decisão |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | RSC-___ | [Trata, reduz, cria ou é afetado por] | CTL-___ | [Nome/papel] | [DEC-ID] |

### 35.1 Requisito derivado de risco

Deve indicar:

- evento de risco;
- causa ou condição;
- consequência;
- resposta pretendida;
- critério de eficácia;
- risco residual;
- autoridade para aceitar o residual.

### 35.2 Controle como componente

Um controle precisa possuir risco de origem, responsável, frequência ou gatilho, evidência e tratamento quando falhar.

### 35.3 Segurança aparente

Criar documento, aprovação ou alerta não demonstra redução de risco sem mecanismo de uso e resposta.

## 36. Conflitos entre requisitos

### 36.1 Registro

| ID | Requisito 1 | Requisito 2 | Natureza | Impacto | Compensação | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CFL-REQ-001 | REQ-___ | REQ-___ | [Personalização/padronização, velocidade/controle, acesso/privacidade ou outra] | [Preencher] | [Preencher] | [Nome/função] | Aberto |

### 36.2 Resultados possíveis

- resolver por reformulação;
- priorizar um requisito;
- criar condição;
- aceitar compensação;
- separar horizontes;
- criar experimento;
- adiar;
- rejeitar um requisito;
- preservar divergência e escalar.

### 36.3 Conflito não é erro

Conflitos podem revelar escolhas reais da organização. O erro consiste em ocultá-los ou permitir que sejam resolvidos implicitamente por quem desenha.

### 36.4 Decisão

Todo conflito material deve possuir responsável, prazo e autoridade. A resolução deve atualizar requisitos, critérios, alternativas e rastreabilidade afetados.

## 37. Duplicações, sobreposições e lacunas

### 37.1 Duplicação

Dois requisitos expressam a mesma condição.

### 37.2 Sobreposição

Requisitos compartilham parte da condição, mas possuem diferenças legítimas.

### 37.3 Lacuna

Uma capacidade, risco, obrigação ou pessoa afetada não possui requisito correspondente quando deveria.

### 37.4 Registro

| ID | Tipo | Objetos | Diagnóstico | Ação | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| LAC-REQ-001 | [Duplicação/Sobreposição/Lacuna] | [IDs] | [Preencher] | [Fundir, dividir, criar, relacionar ou manter] | [Nome] | Aberta |

### 37.5 Requisito órfão temporário

Durante a consolidação, um requisito pode permanecer temporariamente sem capacidade ou componente. Deve possuir responsável, prazo e próximo vínculo esperado.

## 38. Premissas e condições

### 38.1 Premissa

Condição provisoriamente assumida como verdadeira.

### 38.2 Condição de atendimento

Fato, recurso, decisão ou comportamento necessário para que a cobertura declarada permaneça válida.

### 38.3 Registro

| Requisito | Premissa/condição | Base | Verificação | Prazo | Consequência se falsa | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | PRE-___ | [Fonte/razão] | [Método] | [Data/etapa] | [Preencher] | [Nome] |

### 38.4 Cobertura completa com condição

Somente utilizar quando:

- o critério está atendido sob condição identificada;
- a condição possui responsável;
- existe prazo ou gatilho;
- o risco da condição foi avaliado;
- a autoridade aceitou o limite.

## 39. Requisitos humanos e de acessibilidade

### 39.1 Aspectos

- carga cognitiva;
- carga de trabalho;
- autonomia;
- clareza;
- acessibilidade;
- inclusão;
- segurança psicológica;
- vigilância;
- explicabilidade;
- possibilidade de contestação;
- competência e aprendizagem;
- substituição e continuidade.

### 39.2 Registro

| Requisito | Pessoas afetadas | Impacto esperado | Risco humano | Critério | Forma de participação | Validador |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Grupo] | [Preencher] | [Preencher] | [Preencher] | [Oficina, teste ou revisão] | [Nome/grupo] |

### 39.3 Participação proporcional

Requisitos de alto impacto sobre rotina, autonomia, avaliação ou acesso não devem ser validados somente por patrocinadores ou responsáveis técnicos.

### 39.4 Ausência de voz

A falta de participação de grupo afetado deve reduzir a confiança, limitar a conclusão ou motivar validação posterior explícita.

## 40. Requisitos de informação, privacidade e segurança

### 40.1 Elementos mínimos

| Elemento | Pergunta |
| --- | --- |
| Finalidade | Por que a informação é necessária? |
| Conteúdo mínimo | Qual dado é suficiente? |
| Fonte | De onde vem e quem responde por sua qualidade? |
| Acesso | Quem pode ver, criar, alterar, exportar ou excluir? |
| Atualização | Quando e por quem será mantida? |
| Retenção | Por quanto tempo deve existir? |
| Descarte | Como será eliminada? |
| Transferência | Para onde pode circular? |
| Incidente | O que ocorre em caso de exposição, perda ou uso inadequado? |

### 40.2 Registro

| Requisito | Categoria de dado | Sensibilidade | Finalidade | Acesso | Limite | Verificação |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Preencher] | [Nível] | [Preencher] | [Papéis] | [Preencher] | [Método] |

### 40.3 Minimização

Um requisito que peça coleta ou acesso deve demonstrar por que a finalidade não pode ser atendida com menos dados, menor precisão, menor retenção ou acesso mais restrito.

## 41. Requisitos de inteligência artificial

### 41.1 Estrutura mínima

Todo requisito relacionado à IA deve examinar:

- finalidade;
- tarefa;
- entradas permitidas;
- saída esperada;
- ferramenta ou classe de modelo;
- responsabilidade humana;
- revisão;
- erro previsível;
- viés;
- segurança e privacidade;
- registro;
- contingência sem IA;
- condição de interrupção.

### 41.2 Registro

| Requisito | Função da IA | Entrada | Saída | Revisor humano | Limite | Falha e contingência | Validação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-IA-001 | [Preencher] | [Categoria permitida] | [Preencher] | [Nome/papel] | [Preencher] | [Preencher] | [VAL/TST] |

### 41.3 Requisitos humanos obrigatórios

Quando a IA participar materialmente, devem existir requisitos para:

- responsabilidade humana final;
- possibilidade de revisão;
- rastreabilidade proporcional;
- proteção de dados;
- tratamento de incerteza;
- contestação quando pessoas forem afetadas;
- fallback ou interrupção segura;
- avaliação de desempenho no contexto real.

### 41.4 Proibição

“Usar IA” não constitui requisito. É uma alternativa tecnológica até que finalidade, condição, limites e autoridade sejam demonstrados.

## 42. Requisitos financeiros e de sustentabilidade

| Requisito | Custo inicial | Custo recorrente | Trabalho de manutenção | Limite | Horizonte | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Faixa] | [Faixa/período] | [Horas/papel] | [Valor/condição] | [Preencher] | [Nome/papel] |

### 42.1 Custo total de sustentação

Considere:

- licenças;
- integrações;
- manutenção;
- atualização de documentos;
- revisão humana;
- armazenamento;
- treinamento;
- suporte;
- monitoramento;
- substituição futura;
- custo de saída.

### 42.2 Requisito financeiro legítimo

Deve indicar fonte do limite, período, itens incluídos e autoridade. “Ser barato” não é verificável.

## 43. Requisitos de manutenção e continuidade

| Requisito | Objeto mantido | Responsável futuro | Frequência/gatilho | Competência | Evidência | Falha e substituição |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-___ | [Processo, documento, sistema, IA ou indicador] | [Papel] | [Preencher] | [Preencher] | [Registro] | [Preencher] |

### 43.1 Perguntas

- Quem manterá?
- Com que frequência?
- Que informação será necessária?
- Que carga recorrente será criada?
- O que acontece quando a pessoa está ausente?
- Como a falha será percebida?
- Quem pode alterar?
- Quando o elemento deverá ser revisto ou encerrado?

### 43.2 Requisito sem mantenedor

Não deve ser classificado como completamente atendido quando o funcionamento depender de manutenção sem responsável ou capacidade reconhecida.

## 44. Requisitos de transição

| Requisito | Estado atual | Estado futuro | Condição de passagem | Dependência | Critério de aceite | Reversibilidade |
| --- | --- | --- | --- | --- | --- | --- |
| REQ-TRN-001 | [Preencher] | [Preencher] | [Migração, treinamento, comunicação, teste ou decisão] | [IDs] | [Preencher] | [Alta/Média/Baixa] |

### 44.1 Objetos possíveis

- migração de dados;
- preservação de histórico;
- preparação de papéis;
- treinamento;
- comunicação;
- configuração;
- teste;
- convivência temporária entre sistemas;
- reversão;
- desativação;
- aceite.

### 44.2 Limite com o Módulo 4

O requisito declara a condição que a implantação deve atender. O Módulo 4 define atividades, cronograma e coordenação para realizá-la.

## 45. Requisitos evolutivos

| Requisito | Capacidade futura | Justificativa | Condição de entrada | Evidência de prontidão | Risco de antecipar | Risco de adiar | Revisor |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-EVO-001 | [Preencher] | [Preencher] | [Volume, maturidade, resultado ou recurso] | [Indicador/evidência] | [Preencher] | [Preencher] | [Nome/papel] |

### 45.1 Evolução não é depósito de desejos

Um requisito futuro precisa possuir:

- razão;
- condição de entrada;
- forma de reconhecer prontidão;
- dependência;
- responsável pela revisão;
- decisão de inclusão.

### 45.2 Gatilho

Quando a condição ocorrer, o requisito retorna a `em revisão`; não se torna automaticamente aprovado ou implantado.

## 46. Responsabilidades e autoridades

### 46.1 Papéis

| Papel | Pessoa | Responsabilidade | Autoridade |
| --- | --- | --- | --- |
| Responsável pelo catálogo | [Nome] | Integridade, atualização e consistência | [Preencher] |
| Responsável pela arquitetura | [Nome] | Qualidade metodológica e recomendação | [Preencher] |
| Responsável dimensional | [Nome] | Conteúdo específico | [Preencher] |
| Responsável pela validação | [Nome] | Verificar critério | [Preencher] |
| Especialista | [Nome] | Examinar exigência especializada | [Preencher] |
| Patrocinador | [Nome] | Prioridade e recursos | [Preencher] |
| Aprovador | [Nome] | Aceitar requisitos e condições | [Preencher] |
| Custodiante | [Nome] | Versões, acesso e arquivo | [Preencher] |

### 46.2 Matriz de autoridade

Use **P** para propor, **E** para elaborar, **R** para recomendar, **V** para validar, **D** para decidir, **A** para aprovar, **C** para consultar e **I** para informar.

| Ação | Responsável pelo catálogo | Responsável pela arquitetura | Dimensional | Validador | Especialista | Patrocinador | Aprovador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Criar requisito | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Reformular | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Priorizar | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aprovar | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Alterar prioridade | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Declarar cobertura | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Validar atendimento | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Adiar | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Rejeitar | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aceitar exceção | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |

### 46.3 Limites

- a IA não ocupa função de autoridade;
- especialista recomenda dentro de sua competência, salvo autoridade formal adicional;
- responsável pela arquitetura não aceita risco organizacional em nome do cliente;
- patrocinador não transforma solução inadequada em requisito tecnicamente válido;
- aprovação não elimina limite ético, jurídico ou metodológico.

## 47. Revisão de qualidade dos requisitos

Para cada requisito, verificar:

### 47.1 Necessidade

- [ ] a ausência produz consequência relevante;
- [ ] existe relação com problema, capacidade, risco, obrigação ou decisão;
- [ ] não foi incluído apenas porque é fácil ou tradicional.

### 47.2 Clareza

- [ ] pessoas diferentes compreendem a mesma condição;
- [ ] termos ambíguos foram definidos;
- [ ] o sujeito e o objeto estão reconhecíveis.

### 47.3 Rastreabilidade

- [ ] a origem está localizada;
- [ ] a versão da fonte está registrada;
- [ ] origem posterior ao diagnóstico está corretamente classificada.

### 47.4 Verificabilidade

- [ ] existe critério observável;
- [ ] existe método possível;
- [ ] responsável e momento estão definidos.

### 47.5 Viabilidade

- [ ] existe caminho plausível de atendimento;
- [ ] restrições e dependências foram consideradas;
- [ ] o requisito é compatível com maturidade ou possui evolução condicionada.

### 47.6 Priorização

- [ ] a prioridade possui fundamento;
- [ ] o horizonte está definido;
- [ ] a autoridade está identificada.

### 47.7 Delimitação

- [ ] expressa uma condição principal;
- [ ] escopo e limites estão claros;
- [ ] pode ser desdobrado quando necessário.

### 47.8 Neutralidade de solução

- [ ] não fixa solução prematura;
- [ ] ferramenta obrigatória possui origem legítima;
- [ ] atividade não foi confundida com condição.

### 47.9 Resultado da revisão

- [ ] Adequado.
- [ ] Adequado com ajuste editorial.
- [ ] Deve ser reformulado.
- [ ] Deve ser desdobrado.
- [ ] Deve ser fundido.
- [ ] Deve retornar à origem.
- [ ] Deve ser submetido a especialista.
- [ ] Deve ser rejeitado ou cancelado.

## 48. Mudanças e análise de impacto

### 48.1 Mudanças materiais

- declaração;
- origem;
- prioridade;
- escopo;
- critério de atendimento;
- método de verificação;
- responsabilidade;
- cobertura;
- estado;
- condição;
- vínculo com capacidade, componente ou decisão.

### 48.2 Registro

| ID da mudança | Requisito | Campo alterado | Antes | Depois | Motivo | Objetos afetados | Autoridade | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MUD-REQ-001 | REQ-___ | [Campo] | [Valor] | [Valor] | [Preencher] | [CAP, ALT, CMP, VAL, ITM, IND] | [Nome/função] | [Data] |

### 48.3 Impacto regressivo

Verificar se o requisito continua coerente com:

- origem;
- evidência;
- achado;
- problema;
- decisão.

### 48.4 Impacto progressivo

Verificar efeitos sobre:

- capacidades;
- alternativas;
- componentes;
- interfaces;
- validações;
- implantação;
- indicadores;
- documentos;
- treinamento;
- operação.

### 48.5 Mudança depois da aprovação

Requisitos alterados depois do PC-4 podem exigir reabertura de decisão, validação, linha de base e pacote de implantação.

## 49. Versionamento e linha de base

### 49.1 Versão do catálogo

Identifica o conjunto vigente de requisitos.

### 49.2 Versão do requisito

Identifica a formulação vigente de um requisito específico.

### 49.3 Linha de base

Deve registrar:

- projeto;
- versão do catálogo;
- data;
- requisitos incluídos;
- estados;
- prioridades;
- condições;
- conflitos;
- cobertura;
- lacunas;
- aprovadores;
- decisões relacionadas.

### 49.4 Proibição de sobrescrita silenciosa

Uma versão aprovada não deve ser alterada de modo que o raciocínio anterior deixe de poder ser reconstruído.

### 49.5 Substituição

| Requisito anterior | Requisito vigente | Motivo | Decisão | Data |
| --- | --- | --- | --- | --- |
| REQ-___ | REQ-___ | [Preencher] | DEC-___ | [Data] |

## 50. Visões de gestão

### 50.1 Por prioridade

| Prioridade | Total vigente | Sem tratamento | Parcial | Completa | Condicionada | Adiada |
| --- | --- | --- | --- | --- | --- | --- |
| Obrigatório | [N] | [N] | [N] | [N] | [N] | [N] |
| Alta | [N] | [N] | [N] | [N] | [N] | [N] |
| Média | [N] | [N] | [N] | [N] | [N] | [N] |
| Baixa | [N] | [N] | [N] | [N] | [N] | [N] |
| Futuro | [N] | [N] | [N] | [N] | [N] | [N] |

### 50.2 Por dimensão

| Dimensão | Requisitos | Responsável | Lacuna principal | Próxima ação |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs/quantidade] | [Nome/papel] | [Preencher] | [Preencher] |

### 50.3 Por capacidade

| Capacidade | Requisitos | Cobertura agregada | Componentes | Validação |
| --- | --- | --- | --- | --- |
| CAP-___ | [IDs] | [Estado] | [IDs] | [Estado] |

### 50.4 Por responsável

| Responsável | Requisitos | Pendências | Decisões | Prazo mais próximo |
| --- | --- | --- | --- | --- |
| [Nome/papel] | [IDs] | [IDs] | [IDs] | [Data] |

### 50.5 Por validação

| Requisito | Prioridade | Método | Responsável | Estado | Resultado |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | [Categoria] | [Preencher] | [Nome] | [Planejada/Concluída] | [Preencher] |

### 50.6 Por implantação

| Requisito | Item de implantação | Critério de aceite | Dependência | Estado |
| --- | --- | --- | --- | --- |
| REQ-___ | ITM-___ | [Preencher] | [IDs] | [Estado] |

## 51. Sincronização com a Matriz de Rastreabilidade

### 51.1 Objetos

O catálogo governa a descrição oficial do requisito. A matriz governa suas relações com outros objetos.

### 51.2 Vínculos mínimos

| Vínculo canônico | Regra |
| --- | --- |
| `REQ deriva_de` ou `é_justificado_por origem` | Todo requisito possui origem. |
| `CAP responde_a REQ` | Todo requisito material chega a capacidade ou possui exceção. |
| `CMP realiza CAP` | Capacidade futura possui componentes ou destino decidido. |
| `CMP atende` ou `atende_parcialmente REQ` | Atendimento possui cobertura e critério. |
| `VAL/TST verifica REQ/CMP` | Obrigatórios e críticos possuem verificação. |
| `ITM implementa CMP` | Componentes aprovados possuem destino de implantação. |
| `IND monitora REQ/CAP/RSC` | Condições que exigem acompanhamento possuem observação. |

### 51.3 Frequência de sincronização

- ao criar ou aprovar requisito;
- ao alterar prioridade;
- ao relacionar capacidade;
- ao avaliar alternativa;
- ao declarar cobertura;
- ao concluir validação;
- ao adiar, rejeitar ou substituir;
- antes de cada ponto de controle;
- depois de mudança material.

### 51.4 Responsável

**Catálogo:** [Nome]  
**Matriz:** [Nome]  
**Verificação cruzada:** [Nome/papel]

## 52. Pontos de controle

### 52.1 PC-2 — Prontidão para desenhar

Verificar:

- requisitos obrigatórios possuem origem;
- declarações são claras e suficientemente atômicas;
- prioridades possuem fundamento;
- critérios de atendimento estão definidos;
- métodos de verificação são possíveis;
- conflitos impeditivos possuem tratamento;
- capacidades a preservar estão representadas;
- condições e lacunas estão explícitas.

### 52.2 PC-3 — Prontidão para decidir

Verificar:

- alternativas foram comparadas contra a mesma linha de base;
- requisitos obrigatórios possuem cobertura conhecida;
- atendimentos parciais permanecem visíveis;
- compensações e exceções exigem decisão;
- mudanças ocorridas durante o desenho foram incorporadas.

### 52.3 PC-4 — Prontidão para aprovar

Verificar:

- arquitetura selecionada trata os requisitos vigentes;
- requisitos obrigatórios foram validados proporcionalmente;
- condições, adiamentos e rejeições possuem autoridade;
- catálogo, matriz e arquitetura integrada correspondem à mesma versão;
- não existem lacunas críticas ocultas.

### 52.4 PC-5 — Prontidão para implantar

Verificar:

- requisitos possuem critérios de aceite transferíveis;
- itens de implantação estão vinculados;
- dependências e condições estão explícitas;
- responsáveis futuros estão identificados;
- requisitos operacionais possuem forma de observação.

## 53. Checklist de prontidão do catálogo para o PC-2

### 53.1 Completude

- [ ] requisitos da transição foram inventariados;
- [ ] requisitos novos possuem origem legítima;
- [ ] nenhuma capacidade a preservar ficou sem representação;
- [ ] riscos e restrições materiais foram examinados;
- [ ] exigências externas aplicáveis foram incorporadas.

### 53.2 Qualidade

- [ ] requisitos são necessários;
- [ ] requisitos são claros;
- [ ] requisitos são rastreáveis;
- [ ] requisitos são verificáveis;
- [ ] requisitos são viáveis ou condicionados;
- [ ] requisitos são priorizados;
- [ ] requisitos são suficientemente delimitados;
- [ ] soluções prematuras foram tratadas.

### 53.3 Governança

- [ ] cada requisito possui responsável;
- [ ] prioridades possuem autoridade;
- [ ] conflitos possuem encaminhamento;
- [ ] condições possuem responsável e prazo;
- [ ] versões e estados estão atualizados;
- [ ] sensibilidade e acesso foram tratados.

### 53.4 Desenho

- [ ] requisitos materiais estão relacionados a capacidades;
- [ ] critérios de desenho relacionados foram identificados;
- [ ] estratégia de alternativas pode utilizar o catálogo;
- [ ] métodos de verificação estão planejados;
- [ ] a Matriz de Rastreabilidade foi atualizada.

### 53.5 Pendências

| ID | Pendência | Classificação | Por que não impede PC-2 | Responsável | Limite | Consequência |
| --- | --- | --- | --- | --- | --- | --- |
| PEN-REQ-001 | [Preencher] | [Crítica/Relevante/Complementar/Aceita] | [Preencher] | [Nome] | [Data/etapa] | [Preencher] |

### 53.6 Resultado

- [ ] Pronto para compor o PC-2.
- [ ] Pronto com condições.
- [ ] Retornar à consolidação.
- [ ] Retornar à origem diagnóstica.
- [ ] Suspender.

**Responsável pela verificação:** [Nome]  
**Data:** [DD/MM/AAAA]  
**Registro:** [Referência]

## 54. Indicadores do catálogo

Indicadores apoiam revisão; não substituem julgamento sobre qualidade e atendimento.

### 54.1 Cobertura de requisitos obrigatórios

```text
Requisitos obrigatórios com cobertura completa
------------------------------------------------ × 100
Total de requisitos obrigatórios aprovados
```

Requisitos com cobertura parcial ou condicionada permanecem em categorias próprias.

### 54.2 Requisitos sem origem

Quantidade de requisitos vigentes cuja origem ainda não pode ser reconstruída.

### 54.3 Requisitos sem critério

Quantidade de requisitos aprovados sem condição de atendimento verificável.

### 54.4 Requisitos sem tratamento

Quantidade por prioridade, responsável e tempo de permanência.

### 54.5 Cobertura de validação

Quantidade de requisitos obrigatórios e de alto risco com validação concluída.

### 54.6 Conflitos abertos

Quantidade por impacto, autoridade e prazo.

### 54.7 Mudanças materiais

Quantidade por causa e etapa, acompanhada do impacto produzido.

### 54.8 Fórmulas não decidem

Percentuais elevados podem coexistir com origem frágil, critério inadequado ou validação superficial. Toda visão quantitativa deve receber revisão qualitativa.

## 55. Participação da inteligência artificial no catálogo

### 55.1 Usos permitidos

A IA pode apoiar:

- extração provisória de necessidades de documentos;
- sugestão de formulação mais clara;
- detecção de requisitos compostos;
- identificação de duplicações e sobreposições;
- classificação preliminar;
- verificação de campos ausentes;
- proposta de vínculos;
- comparação entre versões;
- análise preliminar de impacto;
- preparação de visões e indicadores;
- revisão de consistência terminológica.

### 55.2 Usos que permanecem humanos

- interpretar legitimidade da origem;
- decidir se algo é requisito;
- definir prioridade;
- aprovar, adiar ou rejeitar;
- aceitar conflito, compensação ou risco;
- declarar cobertura final;
- validar impacto sobre pessoas;
- aprovar mudança e linha de base.

### 55.3 Registro

| Atividade | Função da IA | Entrada permitida | Saída | Revisor humano | Decisão humana necessária |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Categoria] | [Proposta/análise] | [Nome/papel] | [Preencher] |

### 55.4 Proteções

- saídas da IA entram como propostas;
- fontes originais permanecem localizáveis;
- dados respeitam sensibilidade e autorização;
- reescrita não altera sentido sem decisão;
- classificação automática não define prioridade;
- sugestão de cobertura não substitui teste;
- requisitos inventados pela IA sem origem devem ser descartados ou legitimados por processo humano.

## 56. Sensibilidade e controle de acesso

### 56.1 Classificação por requisito

| Requisito | Sensibilidade | Motivo | Acesso | Descrição reduzida necessária? |
| --- | --- | --- | --- | --- |
| REQ-___ | [Pública/Interna/Confidencial/Sensível] | [Preencher] | [Papéis] | [Sim/Não] |

### 56.2 Minimização no registro mestre

Quando a origem contiver dados sensíveis, o catálogo pode utilizar:

- identificador;
- descrição mínima;
- referência protegida;
- nível de confiança;
- condição arquitetural sem dado pessoal desnecessário.

### 56.3 Acesso

| Ação | Papéis autorizados | Autoridade | Registro |
| --- | --- | --- | --- |
| Ler catálogo completo | [Papéis] | [Nome/função] | [Forma] |
| Alterar requisito | [Papéis] | [Nome/função] | [Forma] |
| Aprovar | [Papéis] | [Nome/função] | [Forma] |
| Exportar | [Papéis] | [Nome/função] | [Forma] |
| Compartilhar externamente | [Papéis] | [Nome/função] | [Forma] |

### 56.4 Incidente

**Canal:** [Preencher]  
**Responsável:** [Nome]  
**Ação imediata:** [Preencher]  
**Autoridade para suspender acesso:** [Nome/função]

## 57. Versão reduzida para arquitetura focal

### 57.1 Registro mestre reduzido

| ID | Requisito | Origem | Prioridade | Capacidade | Critério | Componente | Cobertura | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-F01 | [Preencher] | [ID] | [Categoria] | [CAP-ID] | [Preencher] | [CMP-ID] | [Estado] | [Estado] |

### 57.2 Ficha reduzida

**ID e título:** [Preencher]  
**Declaração:** [A arquitetura deve...]  
**Origem e justificativa:** [ID e síntese]  
**Prioridade:** [Categoria e fundamento]  
**Capacidade:** [ID]  
**Critério de atendimento:** [Preencher]  
**Método de verificação:** [Preencher]  
**Responsável:** [Nome/papel]  
**Cobertura:** [Estado]  
**Decisão:** [ID ou pendente]  
**Condição ou risco:** [Preencher]  
**Implantação/operação:** [ITM/IND ou condição]

### 57.3 Controles mínimos

- [ ] origem localizável;
- [ ] requisito necessário e claro;
- [ ] prioridade justificada;
- [ ] critério observável;
- [ ] capacidade ou exceção registrada;
- [ ] cobertura não presumida;
- [ ] validação proporcional;
- [ ] decisão e versão preservadas.

## 58. Aprovação da linha de base do catálogo

### 58.1 Síntese

| Elemento | Registro |
| --- | --- |
| Versão | [Preencher] |
| Total de requisitos vigentes | [N] |
| Obrigatórios | [N] |
| Altos | [N] |
| Médios | [N] |
| Baixos | [N] |
| Futuros | [N] |
| Conflitos abertos | [N/IDs] |
| Lacunas críticas | [N/IDs] |
| Condições | [N/IDs] |
| Cobertura completa | [N] |
| Cobertura parcial | [N] |
| Sem tratamento | [N] |

### 58.2 Recomendação do responsável pela arquitetura

**Nome:** [Preencher]  
**Manifestação:** [Aprovar / Aprovar com condições / Não aprovar]  
**Fundamentação:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Referência]

### 58.3 Validação

**Responsável ou grupo:** [Preencher]  
**Escopo da validação:** [Preencher]  
**Resultado:** [Validado / Validado com ressalvas / Não validado]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Referência]

### 58.4 Aprovação

**Aprovador:** [Nome e função]  
**Resultado:** [Aprovado / Aprovado com condições / Devolvido / Rejeitado]  
**Condições:** [IDs ou nenhuma]  
**Data:** [DD/MM/AAAA]  
**Registro:** [DEC-ID, assinatura, ata ou referência]

### 58.5 Limite da aprovação

A aprovação da linha de base declara os requisitos vigentes para a etapa correspondente. Ela não comprova automaticamente atendimento, implantação ou funcionamento operacional.

## 59. Síntese executiva

| Elemento | Síntese |
| --- | --- |
| Arquitetura | [ID e título] |
| Versão do catálogo | [Preencher] |
| Problema e decisão | [Síntese] |
| Requisito central | [ID e declaração] |
| Capacidades principais | [IDs] |
| Obrigatórios | [Quantidade e principais IDs] |
| Conflito principal | [ID e situação] |
| Lacuna principal | [ID e situação] |
| Cobertura atual | [Síntese] |
| Validação | [Síntese] |
| Requisitos adiados | [IDs] |
| Requisitos futuros | [IDs e gatilhos] |
| Condições para próximo controle | [Preencher] |
| Responsável | [Nome] |

## 60. Controle de versões

| Versão | Data | Estado | Alteração | Motivo | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em consolidação | Criação inicial | Entrada da arquitetura | [Nome] | Não aplicável |
| 1.0 | [DD/MM/AAAA] | Aprovado para desenho | Linha de base do PC-2 | [Preencher] | [Nome] | [Referência] |

### 60.1 Mudanças por requisito

| Requisito | Versão anterior | Versão nova | Mudança | Decisão | Data |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | [Versão] | [Versão] | [Preencher] | [ID] | [Data] |

### 60.2 Linha de base vigente

**Versão:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Local oficial:** [Referência]  
**Aprovação:** [ID]  
**Versão substituída:** [Versão ou não aplicável]

## 61. Teste de reconstrução

Uma pessoa autorizada que não participou da consolidação deve conseguir responder:

1. de onde veio cada requisito obrigatório;
2. por que cada requisito é necessário;
3. o que exatamente precisa ser atendido;
4. que capacidade se relaciona a ele;
5. qual é sua prioridade e quem a decidiu;
6. que critério demonstra atendimento;
7. como e por quem será verificado;
8. que alternativas e componentes procuram atendê-lo;
9. que conflitos, riscos e dependências existem;
10. qual é sua cobertura atual;
11. que decisão explica adiamento, rejeição ou condição;
12. que item de implantação dependerá dele;
13. como será observado na operação;
14. que versão constitui a referência vigente.

### 61.1 Resultado

- [ ] Todas as respostas puderam ser reconstruídas.
- [ ] Existem lacunas não impeditivas registradas.
- [ ] Existem lacunas impeditivas; o catálogo retorna a `em revisão`.

| Requisito | Lacuna | Classificação | Correção | Responsável | Prazo |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | [Preencher] | [Crítica/Relevante/Complementar] | [Preencher] | [Nome] | [Data] |

## 62. Regra de encerramento

O catálogo permanece ativo até que:

- a arquitetura tenha linha de base aprovada;
- requisitos vigentes possuam destino rastreável;
- requisitos obrigatórios tenham cobertura e validação compatíveis;
- adiamentos, rejeições e condições possuam decisão;
- itens de implantação estejam vinculados;
- observações operacionais necessárias estejam definidas;
- versões e histórico estejam preservados;
- o pacote do Módulo 4 tenha sido aceito.

O encerramento do ciclo não congela definitivamente os requisitos. Evidências da implantação, da operação e da aprendizagem podem exigir revisão ou reabertura. Toda evolução deve preservar a linha de base anterior e a razão da mudança.

---

## Registro final

**Estado do catálogo:** [Preencher]  
**Versão vigente:** [Preencher]  
**Resultado no PC-2:** [Preencher]  
**Data da última aprovação:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Próximo artefato:** `matriz-de-rastreabilidade.md`  
**Observações:** [Preencher]
