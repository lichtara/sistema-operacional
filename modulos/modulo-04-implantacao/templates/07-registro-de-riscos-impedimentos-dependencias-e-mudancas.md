# Registro de Riscos, Impedimentos, Dependências e Mudanças

**Identificação técnica no repositório**

```yaml
id_registro: RIC-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Registro Integrado de Controle]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_plano_de_implantacao: PLA-IMP-AAAA-NNN
versao_plano_de_implantacao:
id_estrutura_analitica: EAI-IMP-AAAA-NNN
versao_estrutura_analitica:
id_cronograma_mestre: CRM-IMP-AAAA-NNN
versao_cronograma_mestre:
id_sistema_de_fluxo: BLG-IMP-AAAA-NNN
versao_sistema_de_fluxo:
id_matriz_de_rastreabilidade: MTR-IMP-AAAA-NNN
versao_matriz_de_rastreabilidade:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base_arquitetural:
data_de_status: AAAA-MM-DD
responsavel_pela_implantacao:
responsavel_pelo_registro:
autoridade_da_implantacao:
responsavel_pela_arquitetura:
responsavel_operacional:
custodiante_do_registro:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado_do_registro: em_configuracao
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 1.0
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Qualificar, relacionar, tratar, decidir e destinar condições que afetam a realização da implantação  
**Documentos de entrada:** linha de base aceita; Termo de Abertura; Plano de Implantação; Estrutura Analítica; Cronograma Mestre; Backlog e Quadro Kanban; Matriz de Rastreabilidade vigentes  
**Documento anterior:** `templates/06-matriz-de-rastreabilidade-da-implantacao.md`  
**Documento seguinte na ordem de construção:** `templates/08-plano-de-comunicacao-e-engajamento.md`  
**Pontos de controle relacionados:** `PI-1` a `PI-5`, com atualização durante todo o ciclo

---

## 1. Finalidade

Este template materializa o Registro Integrado de Controle da implantação.

Sua finalidade é tornar governáveis as condições que podem alterar, bloquear, condicionar ou redirecionar a realização, sem reduzir objetos diferentes a uma lista genérica de problemas.

O registro deve permitir demonstrar:

- que incertezas futuras foram reconhecidas como riscos;
- que condições presentes foram registradas como problemas;
- que objetos estão efetivamente impedidos de avançar;
- de que entregas, decisões, recursos, eventos ou condições cada objeto depende;
- que restrições limitam as alternativas disponíveis;
- que premissas sustentam o planejamento e como serão verificadas;
- que condições foram associadas a gates, liberações, aceites ou transferências;
- que alterações foram propostas, classificadas, analisadas e decididas;
- que autoridade podia aceitar exposição, aprovar resposta ou decidir mudança;
- que ações, prazos, gatilhos, evidências e destinos foram definidos;
- que condições residuais permaneceram após cada gate;
- que itens foram transferidos à operação, devolvidos ao Módulo 3 ou destinados a outro módulo.

Registrar um item não significa tratá-lo. Planejar uma resposta não significa executá-la. Classificar uma mudança não significa aprová-la.

---

## 2. Pergunta central

> Como manter riscos, problemas, impedimentos, dependências, restrições, premissas, condições e mudanças visíveis, relacionados e submetidos à autoridade correta, de modo que a implantação possa avançar, conter-se, retornar ou encerrar-se sem perder sua linha de base?

O registro é suficiente quando outra pessoa autorizada consegue reconstruir:

1. o que foi identificado;
2. qual objeto e versão foram afetados;
3. de onde a condição surgiu;
4. que efeito real ou potencial existia;
5. quem possuía responsabilidade de tratamento;
6. que autoridade era necessária;
7. que resposta foi planejada e realizada;
8. que evidência sustentou a decisão;
9. que gate, linha de base ou configuração foi afetado;
10. que condição permaneceu depois da decisão.

---

## 3. Posição no protocolo

Este documento é aberto depois da consolidação inicial da Matriz de Rastreabilidade e permanece vigente até o encerramento da implantação.

Seu uso se intensifica na Etapa 21 do Protocolo de Implantação, quando fluxo, riscos, impedimentos, dependências e decisões precisam ser acompanhados conjuntamente, e na Etapa 22, quando aprendizagem e mudanças são classificadas.

```text
PI-1 — transição aceita
  → registro inicial de condições
  → planejamento e preparação
  → revisão para PI-2
  → execução e acompanhamento
  → mudança governada e PDCA
  → revisão para PI-3
  → liberação, validação e PI-4
  → estabilização
  → condições residuais e PI-5
  → destino e encerramento
```

O registro acompanha decisões. Ele não substitui os gates nem concede autorização.

---

## 4. Natureza do documento

Este é um template-mestre duplicável.

Na implantação real:

1. duplique-o para o dossiê `IMP-AAAA-NNN`;
2. atribua identidade e versão;
3. defina a fonte oficial;
4. registre cada item material com ID próprio;
5. preserve vínculos e histórico;
6. atualize por evento e por cadência;
7. emita visões derivadas sem criar fontes concorrentes;
8. destine itens abertos antes de encerrar.

| Camada | Conteúdo | Natureza |
| --- | --- | --- |
| Template | Campos, vocabulários e regras reutilizáveis. | Não preenchido como caso real. |
| Registro mestre | Índice canônico dos itens e de seus estados. | Fonte oficial do dossiê. |
| Ficha especializada | Detalhe necessário ao tipo do item. | Parte do mesmo sistema de registro. |
| Visão derivada | Recorte por gate, objeto, responsável, prazo ou gravidade. | Não altera a fonte. |
| Evidência | Registro do fato observado e de seu contexto. | Fonte especializada, apenas referenciada. |
| Decisão | Ato humano de autoridade. | Fonte decisória, apenas referenciada. |

---

## 5. Distinções fundamentais

| Elemento | Pergunta principal | Tratamento esperado |
| --- | --- | --- |
| Risco | O que pode ocorrer e afetar o objeto? | Avaliar exposição, responder e monitorar. |
| Problema | O que já ocorre e produz efeito? | Diagnosticar, conter, corrigir ou decidir. |
| Impedimento | O que bloqueia agora o avanço de qual objeto? | Desbloquear, escalar, redirecionar ou encerrar. |
| Dependência | De que outro objeto, evento, recurso ou decisão este objeto necessita? | Confirmar, coordenar, atender ou criar alternativa. |
| Restrição | Que limite reduz alternativas ou condiciona a execução? | Respeitar, negociar, compensar ou escalar. |
| Premissa | O que está sendo provisoriamente assumido como verdadeiro? | Verificar antes do limite e tratar se falsa. |
| Condição | Que obrigação precisa ser satisfeita para validade ou avanço? | Cumprir, verificar, dispensar com autoridade ou conter. |
| Mudança | Que alteração deliberada está sendo proposta? | Classificar, analisar, decidir, incorporar e verificar. |
| Diferença | Que distância existe entre referência e realidade? | Comparar, classificar e decidir no registro próprio. |
| Incidente | Que ocorrência produziu ou poderia produzir dano? | Conter, responder e seguir o protocolo aplicável. |
| Pendência | Que obrigação ou questão aberta possui tratamento definido? | Resolver, decidir, transferir ou encerrar. |

### 5.1 Risco não é problema

Risco trata de evento incerto. Quando o evento ocorre, registre a materialização e abra ou relacione o problema, impedimento, incidente ou diferença correspondente. O risco não deve ser apagado nem ter seu ID convertido.

### 5.2 Problema não é impedimento automático

Uma condição presente pode produzir efeito sem bloquear o avanço. O impedimento exige objeto bloqueado, estado factual e condição de desbloqueio identificáveis.

### 5.3 Dependência não é atraso

Dependência existe antes de vencer. Atraso é um efeito temporal possível quando sua condição não é atendida no momento necessário.

### 5.4 Premissa não é fato

Premissa precisa de fundamento, sensibilidade, responsável, método de verificação e consequência se falsa.

### 5.5 Condição não é recomendação

Condição vinculada a gate ou decisão limita legitimamente o avanço. Recomendação orienta sem possuir, por si, efeito autorizativo.

### 5.6 Mudança não é diferença

Mudança é proposta ou decisão de alteração. Diferença é comparação entre referência e realidade. Uma diferença pode exigir correção, adaptação, mudança ou decisão de não avançar.

### 5.7 Urgência não é autoridade

Urgência pode justificar contenção ou uso de alçada emergencial predefinida. Não cria autoridade para incorporar permanentemente uma alteração.

---

## 6. Fronteiras com os instrumentos relacionados

| Instrumento | Fonte oficial do quê | O que este registro recebe | O que devolve |
| --- | --- | --- | --- |
| Termo de Abertura | Envelope, linha de base, autoridades e tolerâncias iniciais. | Restrições, condições e riscos iniciais. | Lacunas e necessidade de revisão. |
| Plano de Implantação | Estratégia integrada e compromissos de preparação. | Síntese de tratamento e pressupostos. | Exposição, ações e decisões materiais. |
| Estrutura Analítica | Decomposição e dependências estruturais. | Objetos e relações de necessidade. | Condições, riscos e mudanças que afetam a decomposição. |
| Cronograma Mestre | Datas, janelas, marcos e dependências temporais. | Referências temporais e caminho crítico. | Vencimentos, efeitos e necessidade de replanejamento. |
| Backlog e Kanban | Estado factual e fluxo cotidiano do trabalho. | Bloqueios, ações e itens relacionados. | Causa, tratamento, escalonamento e decisão. |
| Matriz de Rastreabilidade | Objetos, vínculos e cobertura. | IDs e relações controladas. | Novos vínculos, invalidações e efeitos sobre cobertura. |
| Registro de PDCA | Hipótese, ciclo, verificação e aprendizagem. | Resultado e proposta de ação. | Classificação e rota de mudança. |
| Registro de Configuração | Realidade implantada e diferenças. | Versões e diferenças observadas. | Mudanças incorporadas, condições e riscos residuais. |
| Registro de Gate | Decisão sobre objeto, versão e escopo. | Resultado e condições. | Evidências, exposições e pendências aplicáveis. |

Este registro governa qualificação, tratamento, autoridade e destino. Ele não deve copiar integralmente cronogramas, backlogs, decisões ou evidências.

---

## 7. Autoridade e limites

| Ato | Autoridade mínima | Pode ser apoiado por IA? | Pode ser delegado integralmente? |
| --- | --- | --- | --- |
| Identificar item | Responsável pelo trabalho ou pessoa autorizada a registrar. | Sim. | Sim, com verificação quando material. |
| Fazer triagem preliminar | Responsável pelo registro. | Sim. | Não quando houver efeito material. |
| Avaliar exposição | Responsável competente e especialistas aplicáveis. | Sim. | Não. |
| Definir resposta | Responsável pelo item dentro de sua alçada. | Sim. | Não quando comprometer recursos ou terceiros. |
| Aceitar risco | Autoridade explicitamente competente. | Não como decisão. | Não. |
| Declarar impedimento | Responsável pelo objeto ou autoridade de fluxo. | Sim, como detecção. | Não quando contestado ou material. |
| Dispensar dependência ou condição | Autoridade que responde pelo critério afetado. | Não como decisão. | Não. |
| Classificar mudança | Responsável metodológico e autoridades aplicáveis. | Sim, preliminarmente. | Não para classe material. |
| Aprovar mudança de plano | Autoridade definida por impacto e alçada. | Não como decisão. | Não. |
| Alterar arquitetura | Módulo 3 e autoridade arquitetural aplicável. | Não como decisão. | Não. |
| Incorporar mudança | Responsável autorizado pela implementação. | Sim, na execução. | Não sem decisão localizável. |
| Transferir condição residual | Autoridades dos Módulos 4 e 5, bilateralmente. | Não como aceite. | Não. |

O Estúdio preserva autoridade metodológica para:

- registrar evidência insuficiente;
- declarar classificação inconclusiva;
- não recomendar avanço;
- exigir especialista;
- preservar divergência;
- recusar aceitação de risco fora de sua competência;
- suspender sua participação diante de risco incompatível;
- impedir que documento preenchido seja tratado como autorização.

---

## 8. Instruções de uso

1. Preencha a identificação antes de registrar itens.
2. Importe IDs existentes sem renumerá-los.
3. Crie ID próprio para cada novo item.
4. Use a classe `a_classificar` quando a informação for insuficiente.
5. Registre um objeto afetado por vínculo, não apenas no texto.
6. Separe descrição factual de avaliação e recomendação.
7. Relacione ação, evidência e decisão sem incorporá-las na mesma célula.
8. Atualize o item quando ocorrer evento material.
9. Preserve estado anterior no histórico.
10. Não encerre risco apenas porque um gate foi aprovado.
11. Não retire impedimento do Kanban sem evidência de desbloqueio.
12. Não marque dependência como atendida por promessa informal.
13. Não considere premissa confirmada sem verificação.
14. Não incorpore mudança antes da decisão aplicável.
15. Não transfira condição sem responsável e aceite.
16. Restrinja dados pessoais ou sensíveis ao mínimo necessário.
17. Registre participação material da IA.
18. Verifique o registro antes de cada gate.

### 8.1 Convenções de preenchimento

| Convenção | Uso |
| --- | --- |
| `[Preencher]` | Campo obrigatório ainda não preenchido. |
| `[N.A. — justificativa]` | Campo não aplicável com fundamento. |
| `[Não determinado]` | Informação ainda insuficiente. |
| `[ID]` | Identificador canônico de fonte ou objeto. |
| `[ID/versão]` | Objeto cuja versão altera a interpretação. |
| `[Link/caminho]` | Localização estável da fonte. |
| `[Data/hora]` | Momento relevante com fuso quando necessário. |
| `[Nome/papel]` | Pessoa e capacidade em que atua. |

### 8.2 Qualidade mínima da descrição

Evite rótulos como “atraso”, “resistência”, “problema técnico” ou “mudança de escopo” sem:

- objeto;
- condição observada ou evento incerto;
- causa conhecida ou hipótese;
- efeito;
- horizonte;
- fonte;
- limite da afirmação.

---

## 9. Identificação do registro

| Campo | Registro |
| --- | --- |
| ID do registro | `RIC-IMP-AAAA-NNN` |
| Implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área ou contexto | [Preencher] |
| Linha de base arquitetural | [ID/versão] |
| Termo de Abertura | [ID/versão] |
| Plano de Implantação | [ID/versão] |
| Estrutura Analítica | [ID/versão] |
| Cronograma Mestre | [ID/versão] |
| Backlog e Kanban | [ID/versão] |
| Matriz de Rastreabilidade | [ID/versão] |
| Classificação da implantação | [Focal/funcional/sistêmica] |
| Responsável pelo registro | [Nome/papel] |
| Autoridade da implantação | [Nome/papel] |
| Fonte oficial | [Caminho/link] |
| Sensibilidade | [Pública/interna/confidencial/sensível] |
| Data de status | [Data/hora] |
| Versão | [N.N] |

---

## 10. Estado do registro

| Estado | Significado |
| --- | --- |
| Em configuração | Identidade, fontes e políticas estão sendo estabelecidas. |
| Ativo | Recebe e atualiza itens durante a implantação. |
| Em revisão de gate | Fotografia e consistência estão sendo verificadas. |
| Condicionado | Lacuna limita o uso do registro em decisão delimitada. |
| Bloqueado | Fonte, acesso ou autoridade impede atualização material. |
| Em transição | Itens residuais e responsabilidades estão sendo transferidos. |
| Encerrado para a implantação | Inclusões ordinárias terminaram e destinos foram definidos. |
| Reaberto | Nova evidência ou obrigação exigiu nova atualização. |
| Substituído | Nova fonte oficial assumiu a vigência. |

| Campo | Registro |
| --- | --- |
| Estado vigente | [Selecionar] |
| Motivo | [Preencher] |
| Escopo coberto | [Objetos/período] |
| Lacunas de uso | [IDs/nenhuma] |
| Próximo evento | [Gate/revisão/transição/outro] |
| Responsável | [Nome/papel] |
| Data | [Data/hora] |

---

## 11. Fonte oficial, versões e precedência

| Elemento | Fonte | ID/versão | Responsável | Última sincronização | Divergência |
| --- | --- | --- | --- | --- | --- |
| Linha de base | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Escopo e envelope | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Decomposição | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Temporalidade | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Fluxo | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Vínculos | [Link/caminho] | [ID/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Decisões | [Link/caminho] | [Índice/versão] | [Nome] | [Data] | [ID/nenhuma] |
| Evidências | [Link/caminho] | [Índice/versão] | [Nome] | [Data] | [ID/nenhuma] |

### 11.1 Regra de precedência

Quando houver divergência:

1. preserve as versões conflitantes;
2. identifique o objeto e o efeito;
3. consulte a fonte competente;
4. registre a decisão ou lacuna;
5. sincronize os instrumentos afetados;
6. não altere este registro apenas para produzir coerência aparente.

### 11.2 Exportações e painéis

Exportação, filtro ou painel é derivado. Deve indicar fonte, versão, data de corte, filtros e limitações.

---

## 12. Governança do registro

| Elemento | Definição |
| --- | --- |
| Fonte canônica | [Caminho/sistema] |
| Custodiante | [Nome/papel] |
| Responsável pela qualificação | [Nome/papel] |
| Responsável pela atualização | [Nome/papel] |
| Autoridade de risco | [Nome/papel/alçada] |
| Autoridade de mudança | [Nome/papel/alçada] |
| Autoridade de emergência | [Nome/papel/alçada] |
| Prazo de triagem | [Duração] |
| Prazo de escalonamento | [Por nível/tipo] |
| Cadência operacional | [Frequência] |
| Cadência executiva | [Frequência] |
| Cadência de gate | [Evento] |
| Regra de versionamento | [Preencher] |
| Regra de retenção | [Preencher] |
| Regra de acesso | [Preencher] |

---

## 13. Unidades de registro e identificadores

Cada item possui identidade própria durante todo o ciclo.

| Objeto | Padrão canônico sugerido |
| --- | --- |
| Registro integrado | `RIC-IMP-AAAA-NNN` |
| Risco | `IMP-AAAA-NNN-RIS-NNN` |
| Problema | `IMP-AAAA-NNN-PRB-NNN` |
| Impedimento | `IMP-AAAA-NNN-IPD-NNN` |
| Dependência | `IMP-AAAA-NNN-DEP-NNN` |
| Restrição | `IMP-AAAA-NNN-RST-NNN` |
| Premissa | `IMP-AAAA-NNN-PRE-NNN` |
| Condição | `IMP-AAAA-NNN-CON-NNN` |
| Mudança | `IMP-AAAA-NNN-MUD-NNN` |
| Ação de tratamento | `IMP-AAAA-NNN-ACA-NNN` |
| Ocorrência ou evento | `IMP-AAAA-NNN-EVT-NNN` |
| Lacuna do registro | `IMP-AAAA-NNN-LAC-NNN` |

IDs herdados do diagnóstico, da arquitetura ou de outra fonte não são renumerados.

### 13.1 Não conversão de IDs

Se um risco se materializar:

- preserve `RIS-NNN`;
- registre `EVT-NNN`;
- crie `PRB-NNN`, `IPD-NNN`, incidente ou diferença quando aplicável;
- relacione os objetos;
- reavalie exposição e resposta;
- preserve o histórico do risco.

### 13.2 Não reutilização

ID encerrado, cancelado ou substituído não é reutilizado. O sucessor recebe novo ID e referência ao anterior.

### 13.3 Registro de namespaces

| Prefixo | Fonte | Objeto | Responsável | Regra de unicidade |
| --- | --- | --- | --- | --- |
| [Prefixo] | [Documento/sistema] | [Tipo] | [Nome/papel] | [Preencher] |

---

## 14. Registro mestre — fonte canônica dos itens

Uma linha representa um item, não uma cadeia completa.

| ID | Tipo | Título factual | Objeto afetado | Origem | Responsável | Autoridade | Estado | Nível | Próximo gatilho | Gate/decisão | Última atualização |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Risco/problema/impedimento/dependência/restrição/premissa/condição/mudança] | [Preencher] | [ID/versão] | [ID/fonte] | [Nome/papel] | [Nome/papel] | [Estado controlado] | [Nível/N.A.] | [Data/evento] | [ID/N.A.] | [Data/hora] |

### 14.1 Campos mínimos obrigatórios

Todo item material deve possuir:

- ID e tipo;
- objeto afetado;
- origem;
- descrição concreta;
- efeito real ou potencial;
- responsável;
- autoridade necessária;
- tratamento;
- prazo ou gatilho;
- estado;
- evidência ou limite da evidência;
- vínculo com gate, decisão ou linha de base quando aplicável;
- próximo movimento.

### 14.2 Um item, múltiplos objetos

Quando um item afetar vários objetos:

1. mantenha um item se a condição e o tratamento forem indivisíveis;
2. registre cada vínculo separadamente na Matriz de Rastreabilidade;
3. desdobre itens quando responsáveis, exposições, prazos ou decisões diferirem;
4. evite listas de IDs que ocultem efeitos distintos.

---

## 15. Triagem e qualificação

| Campo | Registro |
| --- | --- |
| ID recebido | [ID/provisório] |
| Data/hora da identificação | [Data/hora] |
| Identificado por | [Nome/papel/canal] |
| Descrição original | [Preencher] |
| Evidência inicial | [ID/link/relato protegido] |
| Objeto possivelmente afetado | [ID/versão] |
| Classe preliminar | [Selecionar/a_classificar] |
| Urgência de triagem | [Imediata/até N horas/até N dias/ordinária] |
| Necessidade de contenção | [Sim/não/a verificar] |
| Especialista necessário | [Nome/papel/não] |
| Responsável pela triagem | [Nome/papel] |
| Prazo | [Data/hora] |
| Resultado | [ID/classificação] |

### 15.1 Perguntas de triagem

- O evento já ocorreu?
- Há efeito presente?
- Algum objeto está bloqueado?
- Existe relação de necessidade entre objetos?
- Há limite que reduz alternativas?
- Algo está sendo assumido sem confirmação?
- Existe obrigação de gate ou decisão?
- Há alteração deliberada proposta?
- Existe risco imediato a pessoa, dado, segurança, continuidade ou conformidade?
- A autoridade competente está disponível?

### 15.2 Classe inconclusiva

Use `a_classificar` quando a evidência for insuficiente. Defina responsável, prazo, contenção e consequência da demora. Não force classificação para cumprir indicador.

---

## 16. Objetos e dimensões afetadas

| ID do item | Objeto afetado | Versão | Dimensão | Efeito | Horizonte | Criticidade do objeto | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Versão] | [Selecionar] | [Preencher] | [Atual/futuro/transição/operação] | [Baixa/média/alta/crítica] | [ID/link] |

Dimensões mínimas:

- objetivo e resultado;
- capacidade;
- escopo;
- requisito;
- componente;
- interface;
- prazo e janela;
- custo e recurso;
- qualidade;
- pessoa, trabalho e autonomia;
- comunicação e competência;
- informação, dado e conhecimento;
- documento;
- indicador e controle;
- tecnologia e integração;
- inteligência artificial;
- segurança, ética e conformidade;
- fornecedor e contrato;
- continuidade, reversão e sustentação;
- reputação e confiança.

---

## 17. Origem, causa e gatilho

| ID do item | Origem | Causa conhecida | Hipótese causal | Evento ou gatilho | Fonte | Grau de confiança | Revisão necessária |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Diagnóstico/arquitetura/planejamento/preparação/execução/validação/operação/externa] | [Preencher/não determinada] | [Preencher/N.A.] | [ID/descrição] | [ID/link] | [Baixo/médio/alto/N.A.] | [Data/evento] |

Não apresente hipótese causal como fato. Quando a causa não estiver determinada, registre isso e preserve respostas que reduzam dano enquanto a investigação ocorre.

---

## 18. Materialidade, severidade e exposição

O método padrão é qualitativo. Escalas numéricas são opcionais e precisam de definição local.

| Nível | Referência qualitativa | Resposta mínima |
| --- | --- | --- |
| Baixo | Efeito limitado, reversível e dentro da alçada operacional. | Tratar ou monitorar na cadência ordinária. |
| Moderado | Efeito relevante, porém contível e com alternativas viáveis. | Responsável, resposta e revisão definida. |
| Alto | Compromete objetivo, capacidade, gate, pessoa, dado, controle ou caminho crítico. | Escalonamento, contenção e decisão tempestiva. |
| Crítico | Pode causar dano grave, ilegalidade, perda de controle, irreversibilidade ou inviabilidade. | Ação imediata, autoridade competente e possível suspensão. |
| Não determinado | Evidência insuficiente para avaliação responsável. | Investigar sob precaução proporcional. |

### 18.1 Critérios de materialidade

Avalie:

- magnitude;
- probabilidade ou certeza;
- urgência;
- duração;
- reversibilidade;
- detectabilidade;
- propagação;
- número e vulnerabilidade das pessoas afetadas;
- sensibilidade dos dados;
- efeito sobre autoridade e direitos;
- dependência de terceiros;
- efeito sobre gates;
- efeito sobre linha de base;
- capacidade de recuperação;
- exposição residual.

### 18.2 Avaliação multidimensional

| ID | Dimensão | Probabilidade/certeza | Impacto | Urgência | Reversibilidade | Nível | Fundamento | Avaliador |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Dimensão] | [Escala definida/N.A.] | [Escala definida] | [Escala definida] | [Alta/média/baixa] | [Nível] | [ID/síntese] | [Nome/papel] |

### 18.3 Agregação protegida

Não use média para esconder uma dimensão crítica. O nível consolidado deve preservar o maior efeito que exija autoridade, contenção ou proteção específica.

---

## 19. Tolerâncias e escalonamento

| Dimensão | Tolerância autorizada | Unidade/critério | Autoridade | Gatilho de escalonamento | Resposta enquanto decide | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| [Prazo/custo/escopo/qualidade/risco/dado/pessoa/outro] | [Preencher] | [Preencher] | [Nome/papel] | [Evento/limite] | [Conter/manter condição segura] | [ID/versão] |

### 19.1 Ausência de tolerância

Ausência de tolerância explícita não autoriza a equipe a inventá-la. Escale ou permaneça na última condição autorizada.

### 19.2 Prazo de escalonamento

| Nível | Prazo máximo | Destinatário | Canal | Substituto | Consequência se indisponível |
| --- | --- | --- | --- | --- | --- |
| [Nível/tipo] | [Duração] | [Nome/papel] | [Canal] | [Nome/papel] | [Contenção/suspensão/outro] |

---

## 20. Registro de riscos

Risco é evento incerto que pode afetar objetivo, capacidade, prazo, custo, qualidade, pessoa, dado, segurança, continuidade ou reputação.

| Campo | Registro |
| --- | --- |
| ID do risco | `IMP-AAAA-NNN-RIS-NNN` |
| Título | [Causa ou contexto — evento — efeito] |
| Objeto e versão | [ID/versão] |
| Causa ou condição | [Preencher] |
| Evento incerto | [Preencher] |
| Efeito potencial | [Preencher] |
| Natureza | [Adversa/favorável/mista] |
| Horizonte | [Data/período/evento] |
| Probabilidade | [Escala/fundamento] |
| Impacto por dimensão | [IDs/síntese] |
| Exposição inerente | [Nível] |
| Tolerância aplicável | [ID/limite] |
| Proprietário do risco | [Nome/papel] |
| Autoridade para aceitar | [Nome/papel] |
| Estratégia | [Selecionar] |
| Ações de resposta | [IDs] |
| Gatilhos | [Eventos/indicadores] |
| Plano de contingência | [ID/ação] |
| Risco residual | [Nível/fundamento] |
| Estado | [Estado controlado] |
| Gate/decisão | [ID/N.A.] |
| Evidências | [IDs/links] |
| Próxima revisão | [Data/evento] |

### 20.1 Estados do risco

| Estado | Significado |
| --- | --- |
| Identificado | Risco foi registrado, ainda sem avaliação suficiente. |
| Em análise | Exposição, tolerância ou resposta estão sendo avaliadas. |
| Resposta planejada | Estratégia e ações foram definidas, ainda não realizadas. |
| Em tratamento | Ações de resposta estão em execução. |
| Em monitoramento | Gatilhos e exposição estão sendo observados. |
| Escalado | Decisão ou resposta depende de autoridade superior ou externa. |
| Aceito | Exposição residual foi aceita por autoridade competente. |
| Materializado | Evento incerto ocorreu e gerou efeito observável. |
| Transferido | Responsabilidade de acompanhamento foi aceita por outro contexto. |
| Encerrado | Horizonte terminou ou exposição deixou de existir, com fundamento. |
| Invalidado | Formulação se mostrou incorreta ou duplicada, com sucessor quando aplicável. |
| Substituído | Outro risco passou a representar a exposição de forma mais adequada. |

Aceito não significa seguro, resolvido ou encerrado.

---

## 21. Formulação do risco

Use, quando útil:

> Devido a **[causa ou condição]**, pode ocorrer **[evento incerto]**, afetando **[objeto e versão]** por meio de **[efeito]**.

### 21.1 Teste de qualidade

- A causa já existe?
- O evento permanece incerto?
- O efeito está relacionado ao objeto?
- O horizonte é relevante?
- A formulação evita linguagem vaga?
- Há evidência ou fundamento?
- O risco é distinto de problema já materializado?

### 21.2 Riscos agregados

Risco agregado somente deve ser usado quando os componentes compartilham proprietário, tratamento e decisão. Caso contrário, mantenha riscos separados e relacione-os a uma visão comum.

---

## 22. Probabilidade, impacto e exposição do risco

### 22.1 Escala local

| Nível | Probabilidade — definição local | Impacto — definição local |
| --- | --- | --- |
| 1 | [Preencher] | [Preencher] |
| 2 | [Preencher] | [Preencher] |
| 3 | [Preencher] | [Preencher] |
| 4 | [Preencher] | [Preencher] |
| 5 | [Preencher] | [Preencher] |

### 22.2 Matriz opcional

| Risco | Probabilidade | Impacto dominante | Exposição calculada | Exposição qualitativa | Limitação |
| --- | --- | --- | --- | --- | --- |
| [ID] | [1–5] | [1–5/dimensão] | [P × I] | [Nível] | [Preencher] |

O produto numérico não substitui julgamento. Impacto crítico em segurança, legalidade, direitos, dados ou autoridade pode exigir resposta independentemente da frequência estimada.

### 22.3 Incerteza da avaliação

| Risco | Informação ausente | Sensibilidade | Cenários | Ação para reduzir incerteza | Prazo |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Alta/média/baixa] | [IDs/síntese] | [ID/ação] | [Data] |

---

## 23. Estratégias e respostas a riscos

| Estratégia | Uso |
| --- | --- |
| Evitar | Alterar o plano autorizado para eliminar a exposição, dentro da alçada. |
| Reduzir | Diminuir probabilidade, impacto ou tempo de exposição. |
| Transferir | Alocar consequência contratual sem transferir responsabilidade final indevida. |
| Compartilhar | Distribuir resposta e exposição entre partes identificadas. |
| Aceitar ativamente | Autorizar exposição com reserva, gatilho e contingência. |
| Aceitar passivamente | Autorizar observação sem ação adicional, com fundamento. |
| Explorar | Aumentar a chance de efeito favorável. |
| Ampliar | Fortalecer condições de uma oportunidade. |
| Escalar | Encaminhar a autoridade ou módulo competente. |
| Monitorar | Observar quando informação ainda é insuficiente para outra resposta. |

| Ação | Risco | Estratégia | Entrega esperada | Responsável | Recursos | Prazo/gatilho | Estado | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Selecionar] | [Preencher] | [Nome/papel] | [Preencher] | [Data/evento] | [Estado] | [ID/link] |

### 23.1 Resposta não é mudança autorizada

Quando a resposta alterar plano, configuração, requisito, interface, autoridade, uso de dados, tecnologia ou IA, abra ou relacione uma mudança e siga sua alçada.

---

## 24. Risco residual e aceitação

| Campo | Registro |
| --- | --- |
| Risco | [ID/versão da avaliação] |
| Exposição inerente | [Nível/fundamento] |
| Respostas realizadas | [IDs] |
| Evidência de eficácia | [IDs] |
| Exposição residual | [Nível/fundamento] |
| Tolerância aplicável | [ID/limite] |
| Condições da aceitação | [IDs/descrição] |
| Prazo ou validade | [Data/evento] |
| Gatilho de reavaliação | [Preencher] |
| Autoridade competente | [Nome/papel] |
| Decisão | [ID] |
| Data | [Data/hora] |
| Divergência | [ID/nenhuma] |

### 24.1 Regras de aceitação

- aceitação é explícita;
- identifica objeto, versão, horizonte e exposição;
- respeita alçada;
- não transfere responsabilidade silenciosamente;
- não se presume de aprovação de cronograma ou gate;
- permanece visível depois do gate;
- é reavaliada quando condição, exposição ou contexto muda.

### 24.2 Aceitação fora da tolerância

Exposição fora da tolerância exige escalonamento, mudança de resposta, contenção, suspensão ou retorno ao módulo competente. O registro não regulariza decisão inválida.

---

## 25. Materialização do risco

| Risco | Evento | Data/hora | Objeto afetado | Efeito observado | Novo registro | Contenção | Autoridade notificada | Estado do risco |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/descrição] | [Data/hora] | [ID/versão] | [Preencher] | [PRB/IPD/incidente/DIF/outro] | [ID/ação] | [Nome/data] | [Materializado/encerrado/monitorado] |

### 25.1 Aprendizagem após materialização

Reavalie:

- precisão da formulação;
- qualidade dos gatilhos;
- tempo de detecção;
- eficácia da resposta;
- efeitos não previstos;
- riscos secundários;
- necessidade de PDCA;
- necessidade de mudança;
- aplicabilidade da aprendizagem.

---

## 26. Registro de problemas

Problema é condição presente que já produz efeito.

| Campo | Registro |
| --- | --- |
| ID do problema | `IMP-AAAA-NNN-PRB-NNN` |
| Título factual | [Preencher] |
| Objeto e versão | [ID/versão] |
| Condição observada | [Preencher] |
| Início conhecido | [Data/hora/não determinado] |
| Efeito atual | [Preencher] |
| Gravidade | [Nível/fundamento] |
| Causa conhecida | [Preencher/não determinada] |
| Hipóteses causais | [IDs/síntese] |
| Contenção | [ID/ação] |
| Correção | [ID/ação] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Prazo/gatilho | [Data/evento] |
| Estado | [Identificado/em análise/contido/em tratamento/resolvido/aceito/transferido/encerrado] |
| Evidência | [IDs/links] |
| Riscos relacionados | [IDs/nenhum] |
| Impedimentos relacionados | [IDs/nenhum] |
| Mudanças relacionadas | [IDs/nenhuma] |
| Próximo movimento | [Preencher] |

### 26.1 Problema resolvido

“Resolvido” exige evidência de que o efeito foi removido ou reduzido ao critério aceito. A causa pode permanecer não determinada somente quando isso estiver explicitamente aceito e não comprometer prevenção, segurança ou continuidade.

---

## 27. Registro de impedimentos

Impedimento é condição presente que bloqueia o avanço de objeto identificado.

| Campo | Registro |
| --- | --- |
| ID do impedimento | `IMP-AAAA-NNN-IPD-NNN` |
| Objeto bloqueado | [ID/versão] |
| Estado anterior do objeto | [Estado/data] |
| Condição bloqueadora | [Preencher] |
| Início do bloqueio | [Data/hora] |
| Detectado por | [Nome/papel/sistema] |
| Efeito sobre fluxo | [Preencher] |
| Efeito sobre gate ou caminho crítico | [ID/síntese/N.A.] |
| Gravidade | [Nível/fundamento] |
| Responsável pelo objeto | [Nome/papel] |
| Responsável pelo desbloqueio | [Nome/papel] |
| Autoridade de escalonamento | [Nome/papel] |
| Condição de desbloqueio | [Critério verificável] |
| Ações | [IDs] |
| Limite de envelhecimento | [Duração] |
| Próximo escalonamento | [Data/hora/evento] |
| Estado | [Identificado/confirmado/em desbloqueio/escalado/desbloqueado/contido/cancelado/transferido] |
| Evidência | [IDs/links] |
| Item de backlog | [ID] |
| Dependência relacionada | [ID/N.A.] |

---

## 28. Envelhecimento e escalonamento de impedimentos

| Impedimento | Idade atual | Limite | Faixa | Causa da permanência | Ação seguinte | Escalonado a | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Duração] | [Duração] | [Dentro/atenção/excedido/crítico] | [Preencher] | [ID/ação] | [Nome/papel] | [Data/hora] |

### 28.1 Proteção humana

Bloqueio é condição do sistema de trabalho, não atributo moral da pessoa. O registro não deve:

- culpar quem tornou o impedimento visível;
- expor relato sensível sem necessidade;
- usar tempo bloqueado como medida individual de desempenho;
- pressionar início de trabalho substituto sem capacidade;
- esconder dependência de autoridade como falha da equipe.

### 28.2 Escalonamento tempestivo

O prazo de escalonamento considera gravidade, caminho crítico, segurança, reversibilidade e custo de espera. A cadência ordinária não deve atrasar resposta urgente.

---

## 29. Desbloqueio, permanência e encerramento do impedimento

| Campo | Registro |
| --- | --- |
| Impedimento | [ID] |
| Condição de desbloqueio definida | [Critério] |
| Condição observada | [Resultado] |
| Evidência | [IDs/links] |
| Objeto liberado para qual estado | [Estado] |
| Restrições remanescentes | [IDs/nenhuma] |
| Riscos remanescentes | [IDs/nenhum] |
| Decisão necessária | [ID/N.A.] |
| Verificador | [Nome/papel] |
| Data/hora | [Data/hora] |
| Resultado | [Desbloqueado/permanece bloqueado/contido/cancelado/transferido] |

### 29.1 Desbloqueado não significa autorizado

Remover uma condição bloqueadora devolve o objeto ao estado permitido pela política de fluxo. Não concede autorização de gate, liberação, aceite ou transferência.

### 29.2 Impedimento recorrente

Recorrência pode indicar:

- causa não tratada;
- dependência estrutural omitida;
- capacidade insuficiente;
- política inadequada;
- autoridade indisponível;
- mudança não decidida;
- necessidade de retorno ao Módulo 3.

Abra PDCA ou análise adicional quando a recorrência for material.

---

## 30. Registro de dependências

Dependência é relação em que um objeto necessita de entrega, decisão, recurso, evento, pessoa, sistema ou condição externa.

| Campo | Registro |
| --- | --- |
| ID da dependência | `IMP-AAAA-NNN-DEP-NNN` |
| Objeto dependente | [ID/versão] |
| Objeto ou condição predecessora | [ID/versão/descrição externa] |
| Natureza da necessidade | [Preencher] |
| Tipo | [Selecionar] |
| Origem | [ID/fonte] |
| Condição de atendimento | [Critério verificável] |
| Necessária em | [Data/janela/evento] |
| Disponibilidade prevista | [Data/janela/evento] |
| Folga referenciada | [Duração/ID no cronograma/N.A.] |
| Responsável pelo objeto dependente | [Nome/papel] |
| Responsável pela predecessora | [Nome/papel/externo] |
| Autoridade de coordenação | [Nome/papel] |
| Criticidade | [Baixa/média/alta/crítica] |
| Alternativa | [ID/descrição/nenhuma] |
| Resposta se não atendida | [ID/ação] |
| Riscos relacionados | [IDs] |
| Estado | [Estado controlado] |
| Evidência de atendimento | [ID/link] |
| Cronograma | [ID/versão] |
| Matriz de Rastreabilidade | [IDs de vínculos] |

---

## 31. Tipos de dependência

| Tipo | Exemplo | Fonte primária |
| --- | --- | --- |
| Estrutural | Uma entrega exige componente ou interface anterior. | Estrutura Analítica. |
| Temporal | Uma atividade só pode ocorrer depois de outra. | Cronograma Mestre. |
| Decisória | Trabalho depende de decisão ou autorização. | Registro de decisão ou gate. |
| Recurso | Execução depende de orçamento, equipamento ou capacidade. | Plano de Implantação. |
| Pessoa ou competência | Objeto depende de disponibilidade ou habilidade. | Planos humanos e de recursos. |
| Informação ou dado | Trabalho exige fonte, qualidade, acesso ou migração. | Plano e fonte de dados. |
| Documental | Liberação depende de documento vigente. | Sistema documental. |
| Técnica ou integração | Componente depende de ambiente, serviço ou interface. | Plano técnico e configuração. |
| Contratual | Execução depende de licença, termo ou obrigação. | Fonte contratual. |
| Fornecedor | Entrega depende de parte externa. | Contrato e gestão de fornecedor. |
| Gate | Avanço depende de decisão formal. | Registro de gate. |
| Operacional | Sustentação depende de suporte, acesso ou responsável. | Transição para operação. |
| Externa | Evento fora do controle direto condiciona o objeto. | Fonte externa identificada. |

### 31.1 Relações muitos-para-muitos

Uma predecessora pode atender vários objetos e um objeto pode depender de várias condições. Registre cada relação material separadamente na Matriz de Rastreabilidade.

### 31.2 Dependência interna não é irrelevante

Mesmo quando os dois lados pertencem à mesma equipe, a relação precisa de condição, momento e responsável se puder afetar fluxo, gate ou capacidade.

---

## 32. Estados e atendimento de dependências

| Estado | Significado |
| --- | --- |
| Identificada | Relação foi registrada, ainda sem confirmação suficiente. |
| Em confirmação | Partes, condição ou compromisso estão sendo verificados. |
| Confirmada | Responsáveis e condição foram reconhecidos. |
| Em atendimento | A predecessora está sendo preparada ou produzida. |
| Atendida | Critério foi demonstrado na versão necessária. |
| Vencida | Momento necessário passou sem atendimento. |
| Rompida | A condição deixou de poder ser atendida como planejado. |
| Substituída | Nova dependência válida ocupa seu lugar. |
| Dispensada | Autoridade competente retirou a necessidade. |
| Transferida | Responsabilidade e condição foram aceitas por outro contexto. |
| Encerrada | Relação deixou de produzir obrigação. |

| Dependência | Estado anterior | Novo estado | Evento | Evidência | Efeito | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado] | [Estado] | [ID/descrição] | [ID/link] | [Preencher] | [Nome] | [Data/hora] |

### 32.1 Atendimento não se presume

Data alcançada, mensagem recebida ou entrega declarada não demonstram atendimento. Compare a saída real com a condição exigida pelo objeto dependente.

---

## 33. Dependências externas e de fornecedor

| Dependência | Parte externa | Compromisso | Evidência do compromisso | Acesso a dados | SLA/janela | Substituição | Custo de saída | Responsável interno | Escalonamento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Organização/papel] | [Preencher] | [Contrato/registro] | [Preencher/N.A.] | [Preencher] | [Plano/nenhuma] | [Preencher] | [Nome/papel] | [Nome/canal] |

### 33.1 Responsável interno

Dependência externa não fica “com o fornecedor”. A organização identifica responsável interno por coordenação, verificação, escalonamento e continuidade.

### 33.2 Mudança do fornecedor

Mudança de preço, política, versão, disponibilidade, termos, modelo de IA ou acesso a dados exige reavaliação de dependência, risco, contrato, configuração e eventual mudança.

---

## 34. Falha, contingência e substituição de dependência

| Dependência | Gatilho de falha | Efeito | Contenção | Alternativa | Autoridade | Decisão | Novo vínculo | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Evento/limite] | [Objetos/gates] | [ID/ação] | [ID/descrição] | [Nome/papel] | [ID] | [ID/N.A.] | [IDs] |

### 34.1 Dependência sem alternativa

Registre:

- motivo;
- criticidade;
- irreversibilidade;
- reserva ou contingência;
- autoridade que aceitou a exposição;
- ponto de não retorno;
- condição de suspensão ou cancelamento.

### 34.2 Substituição

Substituir a predecessora pode alterar método, plano ou arquitetura. Classifique a mudança antes da incorporação e preserve a dependência anterior.

---

## 35. Registro de restrições

Restrição é limite que reduz alternativas ou condiciona a execução.

| Campo | Registro |
| --- | --- |
| ID da restrição | `IMP-AAAA-NNN-RST-NNN` |
| Declaração do limite | [Preencher] |
| Origem | [Legal/contratual/arquitetural/técnica/financeira/temporal/humana/outra] |
| Fonte | [ID/link] |
| Objetos afetados | [IDs/versões] |
| Alternativas excluídas | [Preencher] |
| Alternativas permitidas | [Preencher] |
| Vigência | [Período/evento] |
| Responsável por observar | [Nome/papel] |
| Autoridade para negociar ou dispensar | [Nome/papel/N.A.] |
| Consequência da violação | [Preencher] |
| Controles | [IDs] |
| Estado | [Proposta/vigente/em revisão/superada/violada/encerrada] |
| Evidência | [IDs/links] |

### 35.1 Restrição ilegítima ou contestada

Preserve divergência e base da contestação. Uma restrição percebida não deve limitar a implantação sem fonte, autoridade ou decisão verificável.

---

## 36. Registro de premissas

Premissa é condição assumida provisoriamente como verdadeira para planejar ou agir.

| Campo | Registro |
| --- | --- |
| ID da premissa | `IMP-AAAA-NNN-PRE-NNN` |
| Declaração | [Preencher] |
| Origem | [ID/fonte/pessoa] |
| Base atual | [Evidência/razão] |
| Objetos dependentes | [IDs/versões] |
| Sensibilidade | [Baixa/média/alta/crítica] |
| Consequência se falsa | [Preencher] |
| Método de verificação | [Teste/fonte/evento] |
| Responsável por verificar | [Nome/papel] |
| Prazo ou validade | [Data/evento] |
| Estado | [Registrada/em verificação/confirmada/refutada/expirada/substituída/encerrada] |
| Resultado | [ID/evidência/pendente] |
| Ação se refutada | [IDs] |
| Gate afetado | [ID/N.A.] |

### 36.1 Premissa material

Premissa é material quando sua falsidade pode:

- invalidar escopo, critério ou arquitetura;
- impedir trabalho crítico;
- alterar risco ou custo significativamente;
- afetar pessoas, direitos, dados ou segurança;
- comprometer liberação, aceite ou sustentação.

---

## 37. Verificação e refutação de premissas

| Premissa | Método | Contexto | Data | Resultado | Evidência | Objetos afetados | Decisão | Próxima ação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Ambiente/amostra] | [Data] | [Confirmada/refutada/parcial/inconclusiva] | [ID] | [IDs] | [ID/N.A.] | [ID/ação] |

### 37.1 Resultado parcial

Confirmação em um contexto não universaliza a premissa. Registre escopo, período, amostra e condições.

### 37.2 Premissa refutada

Ao refutar:

1. preserve a declaração original;
2. identifique objetos e vínculos dependentes;
3. avalie evidências e decisões anteriores;
4. contenha avanço quando necessário;
5. abra problema, risco ou mudança;
6. reavalie gates afetados;
7. comunique as partes aplicáveis.

---

## 38. Registro de condições

Condição é obrigação que precisa ser satisfeita para validade, avanço, liberação, aceite ou transferência.

| Campo | Registro |
| --- | --- |
| ID da condição | `IMP-AAAA-NNN-CON-NNN` |
| Origem | [Gate/decisão/linha de base/contrato/outro] |
| Objeto e versão | [ID/versão] |
| Obrigação | [Preencher] |
| Critério de atendimento | [Critério verificável] |
| Responsável | [Nome/papel] |
| Autoridade que impôs | [Nome/papel] |
| Autoridade para dispensar | [Nome/papel/N.A.] |
| Prazo ou evento | [Data/evento] |
| Monitoramento | [Método/cadência] |
| Consequência do descumprimento | [Preencher] |
| Estado | [Aberta/em atendimento/atendida/vencida/descumprida/dispensada/transferida/encerrada] |
| Evidência | [IDs/links] |
| Decisão relacionada | [ID] |
| Próximo movimento | [Preencher] |

### 38.1 Condição aceita em gate

Avanço com condição exige:

- objeto delimitado;
- motivo;
- risco;
- responsável;
- autoridade;
- vencimento;
- critério;
- monitoramento;
- consequência do descumprimento;
- vínculo com a ocorrência do gate.

---

## 39. Atendimento, vencimento e descumprimento de condição

| Condição | Situação | Data | Evidência | Efeito sobre objeto | Efeito sobre gate | Resposta | Autoridade | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Atendida/vencida/descumprida/dispensada] | [Data] | [ID/link] | [Preencher] | [Manter/reabrir/conter/N.A.] | [ID/ação] | [Nome/papel] | [ID] |

### 39.1 Dispensa

Dispensa não apaga a condição. Registre fundamento, autoridade, efeitos, riscos, documentos afetados e validade.

### 39.2 Descumprimento

Condição descumprida aciona a consequência registrada. Se a consequência não for mais adequada, abra mudança ou nova decisão antes de substituí-la.

---

## 40. Registro de mudanças

Mudança é alteração deliberada proposta em escopo, configuração, critério, método, sequência, recurso, compromisso ou plano.

| Campo | Registro |
| --- | --- |
| ID da mudança | `IMP-AAAA-NNN-MUD-NNN` |
| Título | [Objeto — alteração proposta] |
| Solicitante | [Nome/papel] |
| Data da solicitação | [Data/hora] |
| Situação que motivou | [ID/fato/evidência] |
| Objeto e versão atuais | [ID/versão] |
| Alteração proposta | [Preencher] |
| Resultado pretendido | [Preencher] |
| Classe preliminar | [Selecionar/a_classificar] |
| Urgência | [Emergencial/alta/ordinária] |
| Contenção necessária | [ID/ação/N.A.] |
| Objetos afetados | [IDs/versões] |
| Análise de impacto | [ID/seção] |
| Autoridade necessária | [Nome/papel/módulo] |
| Decisão | [ID/pendente] |
| Versão aprovada | [ID/versão/N.A.] |
| Ações de incorporação | [IDs] |
| Verificação | [IDs] |
| Estado | [Estado controlado] |
| Comunicação | [IDs] |
| Próximo movimento | [Preencher] |

### 40.1 Estados da mudança

| Estado | Significado |
| --- | --- |
| Proposta | Solicitação foi registrada. |
| Em triagem | Identidade, completude, urgência e rota estão sendo verificadas. |
| Devolvida para complemento | Informação insuficiente impede análise responsável. |
| Em análise | Impactos, classe, alternativas e riscos estão sendo examinados. |
| Aguardando decisão | Análise suficiente foi submetida à autoridade. |
| Retornada ao Módulo 3 | Materialidade exige decisão arquitetural. |
| Aprovada | Decisão permite incorporação delimitada. |
| Aprovada com condições | Incorporação depende de condições identificadas. |
| Rejeitada | Autoridade não autorizou a proposta. |
| Adiada | Decisão ou incorporação foi postergada com gatilho de revisão. |
| Em incorporação | Ações autorizadas estão em execução. |
| Em verificação | Resultado incorporado está sendo comparado com critérios. |
| Incorporada | Versões, evidências e fontes foram atualizadas e verificadas. |
| Revertida | Alteração foi desfeita por decisão ou gatilho autorizado. |
| Cancelada | Proposta deixou de prosseguir antes da incorporação. |
| Substituída | Nova mudança assumiu seu objeto, com referência à anterior. |

---

## 41. Classes de mudança

| Classe | O que altera | Autoridade típica | Rota |
| --- | --- | --- | --- |
| Correção de execução | Restaura atendimento ao desenho aprovado. | Módulo 4 dentro da alçada. | Corrigir, verificar e atualizar registros. |
| Adaptação autorizada | Ajusta método, sequência, recurso, detalhe técnico ou forma dentro da tolerância. | Autoridade definida no envelope. | Analisar, aprovar, incorporar e refletir na configuração. |
| Mudança de plano | Altera compromisso de execução sem alterar arquitetura. | Autoridade de plano, orçamento, contrato ou risco. | Replanejar com preservação da linha de base anterior. |
| Mudança arquitetural | Altera requisito, componente, relação, interface, autoridade, controle, risco, dados, tecnologia ou IA material. | Módulo 3 e autoridade aplicável. | Conter e retornar formalmente. |
| Mudança emergencial | Ação temporária para evitar dano imediato. | Autoridade emergencial predefinida. | Conter, registrar, revisar e decidir permanência ou reversão. |
| Aprendizagem sem alteração | Produz conhecimento, sem incorporação atual. | Responsável pela aprendizagem. | Destinar a PDCA, retrospectiva ou módulo competente. |

### 41.1 Classe proposta não é decisão

A classificação orienta a rota. Somente decisão válida autoriza incorporação.

---

## 42. Teste de classificação da mudança

| Pergunta | Sim | Não | Evidência |
| --- | --- | --- | --- |
| Restaura atendimento ao desenho sem alterar obrigação material? | [ ] | [ ] | [ID] |
| Altera apenas método, sequência, recurso ou detalhe dentro da tolerância? | [ ] | [ ] | [ID] |
| Altera prazo, orçamento, pacote ou estratégia sem alterar arquitetura? | [ ] | [ ] | [ID] |
| Altera requisito material? | [ ] | [ ] | [ID] |
| Modifica princípio ou tese arquitetural? | [ ] | [ ] | [ID] |
| Cria, remove ou redefine componente estrutural? | [ ] | [ ] | [ID] |
| Altera interface crítica? | [ ] | [ ] | [ID] |
| Redistribui autoridade ou alçada? | [ ] | [ ] | [ID] |
| Introduz risco não autorizado? | [ ] | [ ] | [ID] |
| Modifica uso material de dados, tecnologia ou IA? | [ ] | [ ] | [ID] |
| Invalida parte da linha de base? | [ ] | [ ] | [ID] |
| Excede tolerância concedida ao Módulo 4? | [ ] | [ ] | [ID] |

| Campo | Registro |
| --- | --- |
| Classe recomendada | [Selecionar] |
| Fundamento | [Preencher] |
| Classificador | [Nome/papel] |
| Revisor | [Nome/papel] |
| Divergência | [ID/nenhuma] |
| Rota | [Módulo 4/Módulo 3/outro] |

### 42.1 Dúvida de materialidade

Quando houver dúvida razoável entre adaptação e mudança arquitetural, preserve a configuração atual, limite a execução e consulte a autoridade arquitetural.

---

## 43. Solicitação e completude da mudança

| Verificação | Resultado | Lacuna | Responsável | Prazo |
| --- | --- | --- | --- | --- |
| Situação e evidência estão identificadas? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Estado atual e versão estão identificados? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Alteração e resultado pretendido estão claros? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Objetos e públicos afetados foram mapeados? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Alternativas, inclusive não mudar, foram consideradas? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Riscos, custos e perdas estão visíveis? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Reversão e continuidade foram examinadas? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |
| Autoridade e rota foram identificadas? | [Sim/não/parcial] | [Preencher] | [Nome] | [Data] |

Solicitação incompleta pode ser devolvida para complemento. Isso não equivale a rejeição do mérito.

---

## 44. Análise de impacto da mudança

| Dimensão | Estado atual | Estado proposto | Objetos e versões | Benefício | Custo/perda | Risco | Evidência | Especialista |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Dimensão] | [Preencher] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [IDs] | [IDs] | [Nome/papel/N.A.] |

### 44.1 Cobertura mínima

Examinar, conforme aplicável:

- linha de base, escopo e resultado;
- capacidades, requisitos, componentes e interfaces;
- pessoas, papéis, autoridade, carga e autonomia;
- comunicação, treinamento e competência;
- processos, exceções e controles;
- dados, documentos, acesso e retenção;
- tecnologia, integrações, IA e fornecedores;
- segurança, ética, legalidade e propriedade intelectual;
- prazo, custo, recurso e contrato;
- testes, evidências e critérios;
- piloto, liberação, reversão e estabilização;
- configuração e diferenças;
- operação, manutenção e saída;
- gates e decisões anteriores;
- rastreabilidade e documentação.

### 44.2 Impacto em cadeia

| Objeto inicial | Relação | Objeto afetado | Profundidade | Efeito | Atualização | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [Relação] | [ID/versão] | [1/2/3/...] | [Preencher] | [Documento/ação] | [Nome] |

### 44.3 Resultado inconclusivo

Se o impacto não puder ser determinado:

- registre lacuna;
- defina investigação;
- aplique precaução proporcional;
- não declare ausência de impacto;
- mantenha contenção quando necessária.

---

## 45. Autoridade, alçada e rota da mudança

| Mudança | Classe | Materialidade | Alçada requerida | Autoridade disponível | Segregação | Rota | Prazo de decisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Classe] | [Nível] | [Fonte/limite] | [Nome/papel] | [Suficiente/combinar papéis/exigir revisor] | [M4/M3/outro] | [Data] |

### 45.1 Combinação de papéis

Em implantação focal, papéis podem ser combinados quando:

- a combinação é explícita;
- a pessoa possui competência e autoridade;
- conflito de interesse é tratado;
- decisão de alto impacto recebe revisão independente proporcional;
- solicitante não converte sua própria proposta em aprovação automática.

### 45.2 Autoridade indisponível

Indisponibilidade de autoridade não autoriza incorporação. Preserve estado seguro, use substituto formal ou suspenda o objeto.

---

## 46. Decisão da mudança

| Campo | Registro |
| --- | --- |
| Mudança | [ID/versão] |
| Objeto e versão decididos | [IDs/versões] |
| Classe confirmada | [Classe] |
| Alternativas consideradas | [IDs/síntese] |
| Critérios | [IDs] |
| Evidências | [IDs] |
| Riscos e compensações | [IDs] |
| Resultado | [Aprovada/aprovada com condições/rejeitada/adiada/devolvida/cancelada/retornada ao M3] |
| Condições | [IDs/nenhuma] |
| Autoridade | [Nome/papel] |
| Data/hora | [Data/hora] |
| Vigência | [Data/evento] |
| Decisão | [ID/link] |
| Divergência preservada | [ID/nenhuma] |
| Próximo movimento | [Preencher] |

### 46.1 Aprovação condicionada

Condições possuem IDs próprios e não permanecem apenas no texto da decisão.

### 46.2 Rejeição

Rejeição não apaga a solicitação. Registre fundamento, efeitos, comunicação e possibilidade de nova proposta.

---

## 47. Incorporação e verificação da mudança

| Ação | Mudança | Objeto | Versão anterior | Versão nova | Responsável | Janela | Estado | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [ID/versão] | [ID/versão] | [Nome/papel] | [Data/período] | [Estado] | [ID/link] |

| Verificação | Critério | Método | Resultado | Evidência | Revisor | Data | Ação seguinte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/critério] | [Preencher] | [Atende/parcial/não atende/inconclusivo] | [ID] | [Nome/papel] | [Data] | [Manter/corrigir/reverter/escalar] |

### 47.1 Incorporação completa

Uma mudança somente pode ser marcada como incorporada quando:

- a decisão válida é localizável;
- a execução corresponde à decisão;
- critérios foram verificados;
- riscos foram reavaliados;
- documentos e versões afetados foram atualizados;
- matriz e configuração foram sincronizadas;
- pessoas afetadas foram preparadas;
- gates foram reavaliados quando necessário;
- condição temporária recebeu destino.

---

## 48. Mudança emergencial

| Campo | Registro |
| --- | --- |
| Mudança | [ID] |
| Emergência | [Situação e evidência] |
| Dano que se buscou evitar | [Preencher] |
| Autoridade emergencial | [Nome/papel/fonte] |
| Objeto delimitado | [ID/versão] |
| Ação temporária | [Preencher] |
| Proteções mantidas | [IDs] |
| Proteções suspensas | [IDs/nenhuma] |
| Início | [Data/hora] |
| Validade máxima | [Data/hora/evento] |
| Revisão posterior | [Data/autoridade] |
| Resultado | [Manter formalmente/reverter/substituir/encerrar/escalar] |
| Decisão posterior | [ID] |
| Evidências | [IDs] |

### 48.1 Limite

Emergência não transforma alteração temporária em arquitetura permanente. Se a permanência for proposta, percorra classificação, análise, autoridade e decisão ordinárias.

---

## 49. Retorno ao Módulo 3

Retorne formalmente quando a mudança:

- alterar requisito material;
- modificar princípio ou tese da arquitetura;
- criar, remover ou redefinir componente estrutural;
- alterar interface crítica;
- redistribuir autoridade ou alçada;
- introduzir risco não autorizado;
- modificar uso material de dados, tecnologia ou IA;
- invalidar parte da linha de base;
- exceder tolerância concedida ao Módulo 4.

| Mudança | Gatilho | Objeto/versão | Evidência | Contenção | Registro de retorno | Responsável M4 | Recebedor M3 | Estado | Nova referência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Selecionar] | [ID/versão] | [IDs] | [ID/ação] | [ID/link] | [Nome] | [Nome] | [Preparando/enviado/recebido/em análise/decidido] | [ID/versão/pendente] |

### 49.1 Enquanto a decisão permanece aberta

O objeto deve permanecer:

- contido;
- suspenso;
- fora do público ou ambiente não autorizado;
- na última condição segura;
- ou operando sob condição explicitamente autorizada.

### 49.2 Recebimento da decisão do Módulo 3

| Decisão | Linha de base anterior | Nova linha de base | Efeito | Trabalho afetado | Evidências a reavaliar | Gates a reabrir | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [ID/versão] | [Preencher] | [IDs] | [IDs] | [IDs/nenhum] | [Data] |

---

## 50. Correção de execução e adaptação autorizada

| Item | Classe | Desenho preservado | Tolerância | Autoridade | Efeito na configuração | Evidência | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Correção/adaptação] | [IDs/versões] | [ID/limite] | [Nome/papel] | [DIF/CFG/nenhum] | [IDs] | [Preencher] |

### 50.1 Correção

Correção restaura atendimento. Não deve ser usada para normalizar requisito impossível ou arquitetura inadequada.

### 50.2 Adaptação

Adaptação precisa permanecer dentro da tolerância e registrar fundamento, efeito, aprovador e reflexo na configuração.

---

## 51. Mudança de plano e replanejamento

| Mudança | Compromisso afetado | Linha de base do plano | Previsão anterior | Previsão nova | Causa | Efeito | Aprovação | Documentos atualizados |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Prazo/recurso/sequência/pacote/estratégia] | [ID/versão] | [Preencher] | [Preencher] | [ID/síntese] | [Risco/custo/escopo/contrato] | [ID] | [IDs/versões] |

Replanejamento legítimo preserva a linha de base anterior e a variação. Não transforma atraso em conformidade histórica.

---

## 52. Mudança, diferença e configuração

| Mudança | Diferença observada | Configuração anterior | Configuração resultante | Autorização | Critério | Evidência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [DIF-ID/N.A.] | [CFG/linha de base] | [CFG-ID/versão/N.A.] | [ID] | [IDs] | [IDs] | [Preencher] |

### 52.1 Diferença não autorizada

Se a realidade divergir antes da decisão:

1. preserve evidência;
2. contenha efeito;
3. registre diferença;
4. classifique a causa;
5. abra correção ou mudança;
6. reavalie testes e gates;
7. não atualize a referência para fazer a realidade parecer conforme.

---

## 53. Relações entre itens

Cada linha representa uma relação material. A expressão operacional facilita a leitura deste registro; a coluna canônica indica como o vínculo deve ser formalizado na Matriz de Rastreabilidade.

| Relação operacional | Origem | Destino | Significado | Relação canônica aplicável | Estado | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| Pode materializar | [RIS] | [Evento prospectivo descrito] | Risco pode produzir ocorrência. | [N.A.; formalizar `deriva_de` quando a ocorrência existir] | [Estado] | [ID] |
| Materializou | [EVT/PRB/IPD] | [RIS] | Ocorrência deriva do risco registrado. | `deriva_de` | [Confirmado] | [ID] |
| Causa ou contribui | [PRB/condição] | [IPD/risco/outro] | Objeto participa da origem do efeito. | [`deriva_de`, com direção validada] | [Proposto/confirmado/contestado] | [ID] |
| Depende de | [Objeto] | [Predecessora] | Objeto necessita da condição. | `depende_de` | [Estado] | [ID] |
| Gera risco | [RIS] | [DEP/PRE/RST] | Risco deriva da condição identificada. | `deriva_de` | [Estado] | [ID] |
| Exige mudança | [MUD] | [PRB/IPD/DIF/PDCA] | Proposta deriva de condição ou aprendizagem. | `deriva_de` ou `exige_revisão_de` | [Estado] | [ID] |
| Cria dependência | [DEP] | [MUD] | Nova necessidade deriva da alteração. | `deriva_de` | [Estado] | [ID] |
| Satisfaz condição | [EVD] | [CON] | Evidência sustenta atendimento. | `demonstra` | [Estado] | [ID] |
| Refuta premissa | [EVD/EVT] | [PRE] | Evidência contradiz premissa. | `contradiz` | [Estado] | [ID] |
| Trata | [ACA/controle] | [RIS/PRB/IPD] | Ação responde ao item. | `trata` | [Estado] | [ID] |
| Autoriza | [DEC/gate] | [resposta/MUD/aceitação] | Decisão permite ato delimitado. | `autoriza` | [Estado] | [ID] |
| Transfere | [item/configuração] | [responsável operacional] | Responsabilidade foi aceita. | `transfere_responsabilidade_para` | [Estado] | [ID] |

### 53.1 Relação não substitui objeto

A Matriz de Rastreabilidade é a fonte canônica dos vínculos. Esta seção é visão operacional e deve sincronizar IDs sem criar vocabulário concorrente.

---

## 54. Ações de tratamento

| Ação | Item tratado | Tipo | Resultado esperado | Responsável | Participantes | Recursos | Início | Prazo | Estado | Evidência | Próxima ação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Investigar/conter/corrigir/prevenir/monitorar/escalar/comunicar/reverter/outro] | [Preencher] | [Nome] | [Nomes] | [Preencher] | [Data] | [Data/evento] | [Não iniciada/em curso/bloqueada/concluída/cancelada] | [ID/link] | [ID/N.A.] |

### 54.1 Ação concluída

Conclusão da ação não encerra automaticamente o item. Verifique efeito, risco residual, condição de desbloqueio ou critério de atendimento.

### 54.2 Ação como trabalho

Quando exigir fluxo material, crie item no backlog e preserve vínculo com `ACA-NNN`.

---

## 55. Decisões relacionadas

| Decisão | Item | Pergunta decidida | Alternativas | Critérios | Evidências | Autoridade | Resultado | Condições | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [IDs/síntese] | [IDs] | [IDs] | [Nome/papel] | [Preencher] | [IDs/nenhuma] | [Data/hora] |

### 55.1 Decisão oral ou emergencial

Registre fonte, autoridade, objeto, validade e confirmação posterior. Conversa dispersa não permanece como única fonte de decisão material.

### 55.2 Divergência

| Divergência | Item | Posições | Evidências | Efeito | Destino | Decisão | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Nomes/papéis/síntese] | [IDs] | [Preencher] | [Revisão/especialista/autoridade] | [ID/pendente] | [Aberta/preservada/decidida] |

---

## 56. Evidências e limitações

| Evidência | Item | Objeto e versão | Afirmação sustentada | Fonte | Método | Contexto | Data | Limitação | Custodiante |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID/versão] | [Preencher] | [Link/caminho] | [Preencher] | [Ambiente/amostra/período] | [Data] | [Preencher] | [Nome/papel] |

### 56.1 Evidência negativa ou divergente

Não suprima evidência que:

- aumente exposição;
- contradiga premissa;
- demonstre falha de resposta;
- mantenha impedimento;
- mostre dependência não atendida;
- indique mudança inadequada;
- contrarie recomendação de avanço.

### 56.2 Link não é evidência

O link apenas localiza. A evidência precisa de objeto, contexto, método, resultado, fonte e limite.

---

## 57. Diário cronológico de eventos

| Evento | Data/hora | Item | Estado anterior | Novo estado | Fato | Evidência | Responsável | Autoridade/decisão | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/hora] | [ID] | [Estado] | [Estado] | [Preencher] | [ID/link] | [Nome] | [ID/N.A.] | [Preencher] |

O diário preserva sequência. O registro mestre mostra estado vigente. Um não substitui o outro.

---

## 58. Sincronização geral

| Fonte | Evento de sincronização | Conteúdo recebido | Conteúdo devolvido | Responsável | Última execução | Divergências |
| --- | --- | --- | --- | --- | --- | --- |
| Termo de Abertura | [Aprovação/revisão] | Envelope, tolerâncias, riscos e condições iniciais. | Lacunas e necessidades de autoridade. | [Nome] | [Data] | [IDs/nenhuma] |
| Plano de Implantação | [Revisão] | Estratégia, riscos, premissas e respostas. | Estado, exposição e decisões. | [Nome] | [Data] | [IDs/nenhuma] |
| Estrutura Analítica | [Inclusão/revisão] | Objetos e dependências estruturais. | Riscos, impedimentos e mudanças na decomposição. | [Nome] | [Data] | [IDs/nenhuma] |
| Cronograma Mestre | [Replanejamento/evento] | Janelas, marcos, caminho crítico e DEP-IDs. | Vencimentos, exposição e necessidade de replanejar. | [Nome] | [Data] | [IDs/nenhuma] |
| Backlog e Kanban | [Movimento/bloqueio] | Estado factual, trabalho e bloqueios. | Qualificação, causa, ação e escalonamento. | [Nome] | [Data] | [IDs/nenhuma] |
| Matriz de Rastreabilidade | [Evento material] | Objetos, relações e coberturas. | Novos vínculos, invalidações e efeitos. | [Nome] | [Data] | [IDs/nenhuma] |
| Planos humanos | [Revisão/evidência] | Riscos, impactos, condições e ações humanas. | Decisões, prioridades e requisitos de resposta. | [Nome] | [Data] | [IDs/nenhuma] |
| Piloto e reversão | [Preparação/liberação] | Gatilhos, contingências e autoridades. | Exposição, impedimentos e mudanças. | [Nome] | [Data] | [IDs/nenhuma] |
| PDCA | [Conclusão de ciclo] | Hipótese, resultado e aprendizagem. | Classificação e rota da alteração. | [Nome] | [Data] | [IDs/nenhuma] |
| Configuração implantada | [Nova versão] | Diferenças e realidade vigente. | Mudanças autorizadas e riscos residuais. | [Nome] | [Data] | [IDs/nenhuma] |
| Transição para operação | [Preparação/aceite] | Condições de sustentação e retorno. | Itens residuais e responsabilidades. | [Nome] | [Data] | [IDs/nenhuma] |

### 58.1 Divergência de sincronização

| Divergência | Fontes | Objeto | Efeito | Fonte competente | Ação | Responsável | Prazo | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [ID] | [Preencher] | [Documento] | [ID/ação] | [Nome] | [Data] | [Aberta/em tratamento/resolvida] |

---

## 59. Sincronização com a Estrutura Analítica

| Objeto da EAI | Versão | Dependências estruturais | Riscos | Restrições | Mudanças | Efeito na decomposição | Atualização |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [DEP-IDs] | [RIS-IDs] | [RST-IDs] | [MUD-IDs] | [Nenhum/revisar/desdobrar/conter] | [ID/ação] |

### 59.1 Regra de fonte

A Estrutura Analítica governa o que compõe a realização. Este registro governa condição, exposição, resposta e autoridade. Alteração da árvore ou do dicionário ocorre na EAI depois da decisão aplicável.

### 59.2 Novo trabalho de tratamento

Risco ou impedimento não cria escopo silencioso. A ação necessária precisa de origem, autorização, pacote ou item de backlog proporcional.

---

## 60. Sincronização com o Cronograma Mestre

| Dependência/item | Objeto temporal | Linha de base | Previsão vigente | Data realizada | Efeito | Resposta | Mudança de plano |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Marco/janela/atividade] | [ID/versão/data] | [Data/janela] | [Data/N.A.] | [Caminho crítico/folga/gate] | [ID/ação] | [MUD-ID/N.A.] |

### 60.1 Fonte temporal

Datas, folgas, caminho crítico e versões temporais permanecem no Cronograma Mestre. Este registro referencia a condição e governa sua consequência.

### 60.2 Marco não é decisão

Ocorrência temporal prevista de gate não substitui o gate. Mudança de data não altera automaticamente autoridade ou critério.

---

## 61. Sincronização com o Backlog e o Quadro Kanban

| Item de fluxo | Estado factual | Bloqueio | Registro detalhado | Ação relacionada | Classe de serviço | Próxima atualização |
| --- | --- | --- | --- | --- | --- | --- |
| [ITM-ID] | [Estado] | [Sim/não] | [IPD/PRB/RIS/DEP/MUD] | [ACA/ITM] | [Classe] | [Evento/data] |

### 61.1 Fonte do bloqueio

O quadro mostra que o item está bloqueado agora. Este registro preserva condição bloqueadora, início, efeito, responsável, escalonamento e critério de desbloqueio.

### 61.2 Prioridade não é aceitação de risco

Ordenar ou puxar item não autoriza exposição, mudança ou início fora do `PI-2` aplicável.

### 61.3 Concluído não encerra o controle

Item de tratamento concluído pode deixar risco residual, condição aberta ou mudança ainda não verificada.

---

## 62. Sincronização com a Matriz de Rastreabilidade

| Item | Objeto relacionado | Relação canônica | Vínculo na matriz | Estado | Cobertura afetada | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [`trata`/`controla`/`depende_de`/`é_condicionado_por`/`retorna_a`/outro controlado] | [VNC-ID] | [Estado] | [Dimensão/objeto] | [Criar/atualizar/invalidar/nenhuma] |

### 62.1 Eventos que exigem atualização

- risco material ou residual;
- materialização;
- impedimento de objeto rastreado;
- dependência criada, atendida, rompida ou substituída;
- premissa refutada;
- condição de gate;
- mudança proposta com efeito material;
- decisão de mudança;
- nova versão ou invalidação;
- retorno ao Módulo 3;
- transferência de item residual;
- reabertura de gate.

### 62.2 Cobertura não é ausência de risco

Objeto rastreado pode permanecer exposto. A matriz mostra relações; este registro mostra tratamento e exposição.

---

## 63. Sincronização com PDCA e planos especializados

| Instrumento | ID/versão | Conteúdo recebido | Item relacionado | Efeito | Decisão/ação | Próximo evento |
| --- | --- | --- | --- | --- | --- | --- |
| Comunicação e engajamento | [ID] | [Risco/condição/evidência] | [IDs] | [Preencher] | [IDs] | [Data/evento] |
| Treinamento e capacitação | [ID] | [Lacuna/competência/condição] | [IDs] | [Preencher] | [IDs] | [Data/evento] |
| Gestão da mudança organizacional | [ID] | [Impacto/contestação/adoção] | [IDs] | [Preencher] | [IDs] | [Data/evento] |
| Piloto, ondas, virada e reversão | [ID] | [Gatilho/contingência/risco] | [IDs] | [Preencher] | [IDs] | [Data/evento] |
| Ciclo PDCA | [ID] | [Hipótese/resultado] | [IDs] | [Correção/adaptação/mudança/aprendizagem] | [IDs] | [Data/evento] |
| Verificação de prontidão | [ID] | [Lacuna/condição/risco residual] | [IDs] | [Gate] | [IDs] | [Data/evento] |
| Validação e aceite | [ID] | [Resultado/divergência] | [IDs] | [Mudança/risco/diferença] | [IDs] | [Data/evento] |
| Configuração implantada | [ID] | [Versão/diferença] | [IDs] | [Atualização/retorno] | [IDs] | [Data/evento] |

### 63.1 Contestação não é impedimento automático

Discordância legítima, denúncia ou pergunta pode revelar risco, problema ou lacuna. Preserve a manifestação e investigue sem classificá-la automaticamente como resistência ou bloqueio.

---

## 64. Verificação para o `PI-1`

Pergunta oficial:

> A linha de base arquitetural, suas condições e seus critérios são suficientes para mobilizar a implantação?

| Verificação | Resultado | Itens | Evidência | Efeito |
| --- | --- | --- | --- | --- |
| Riscos recebidos estão identificados? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Restrições e premissas materiais estão explícitas? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Dependências e condições da transição são compreensíveis? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Decisões abertas possuem autoridade e destino? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Mudanças ou diferenças pendentes afetam a base? | [Sim/não] | [IDs] | [IDs] | [Preencher] |
| Há condição que impede mobilização responsável? | [Sim/não] | [IDs] | [IDs] | [Preencher] |

| Campo | Registro |
| --- | --- |
| Ocorrência do gate | [ID] |
| Fotografia do registro | [ID/versão/data] |
| Itens considerados | [IDs] |
| Condições do resultado | [IDs/nenhuma] |
| Resultado | [Aceitar/aceitar com condições/devolver/rejeitar/suspender] |
| Decisão | [ID] |

---

## 65. Verificação para o `PI-2`

Pergunta oficial:

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

| Verificação | Resultado | Itens | Evidência | Consequência |
| --- | --- | --- | --- | --- |
| Riscos inerentes e residuais foram avaliados? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Aceitações de risco possuem autoridade? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Impedimentos do objeto estão resolvidos ou tratados? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Dependências críticas foram confirmadas? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Premissas materiais foram verificadas ou protegidas? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Condições possuem responsável, prazo, critério e consequência? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Mudanças abertas não invalidam a linha de base? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Contingência e reversão tratam exposições críticas? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |
| Planos humanos cobrem riscos e impactos conhecidos? | [Sim/parcial/não] | [IDs] | [IDs] | [Preencher] |

### 65.1 Distinção entre pendência e impedimento

Pendência tratável pode acompanhar a autorização quando possui responsável, prazo, limite, monitoramento e consequência. Impedimento material do objeto impede o avanço correspondente.

| Campo | Registro |
| --- | --- |
| Objeto delimitado | [IDs/versões] |
| Fotografia do registro | [ID/versão/data] |
| Itens impeditivos | [IDs/nenhum] |
| Itens condicionantes | [IDs/nenhum] |
| Riscos aceitos | [IDs/nenhum] |
| Resultado do gate | [ID/resultado] |

---

## 66. Verificação para o `PI-3`

Pergunta oficial:

> Este incremento, piloto, onda ou virada possui condições técnicas, humanas, documentais e operacionais para ser liberado?

| Verificação | Resultado | Itens | Evidência |
| --- | --- | --- | --- |
| Riscos da versão e do escopo de liberação estão atualizados? | [Sim/parcial/não] | [IDs] | [IDs] |
| Problemas e defeitos remanescentes foram classificados? | [Sim/parcial/não] | [IDs] | [IDs] |
| Impedimentos de liberação foram removidos? | [Sim/parcial/não] | [IDs] | [IDs] |
| Dependências de janela, suporte e monitoramento estão atendidas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Condições anteriores permanecem atendidas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Mudanças foram incorporadas e verificadas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Riscos residuais de exposição foram aceitos pela autoridade? | [Sim/parcial/não] | [IDs] | [IDs] |
| Gatilhos de parada e reversão estão executáveis? | [Sim/parcial/não] | [IDs] | [IDs] |

| Campo | Registro |
| --- | --- |
| Objeto, versão, público e ambiente | [Preencher] |
| Fotografia do registro | [ID/versão/data] |
| Itens de parada | [IDs/nenhum] |
| Condições de liberação | [IDs] |
| Resultado | [Liberar/liberar com condições/não liberar/adiar/reverter] |
| Decisão | [ID] |

---

## 67. Verificação para o `PI-4`

Pergunta oficial:

> A capacidade foi efetivamente implantada, validada e aceita dentro dos critérios autorizados?

| Verificação | Resultado | Itens | Evidência |
| --- | --- | --- | --- |
| Riscos e problemas observados durante uso foram tratados? | [Sim/parcial/não] | [IDs] | [IDs] |
| Dependências reais correspondem ao desenho e ao plano? | [Sim/parcial/não] | [IDs] | [IDs] |
| Premissas relevantes foram confirmadas ou refutadas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Condições de aceite foram satisfeitas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Mudanças e diferenças possuem decisão e versão? | [Sim/parcial/não] | [IDs] | [IDs] |
| Exposição residual é compatível com o aceite? | [Sim/parcial/não] | [IDs] | [IDs] |
| Itens que seguem para estabilização possuem responsável? | [Sim/parcial/não] | [IDs] | [IDs] |

| Campo | Registro |
| --- | --- |
| Objeto e versão | [IDs/versões] |
| Fotografia do registro | [ID/versão/data] |
| Diferenças | [DIF-IDs/nenhuma] |
| Condições de aceite | [CON-IDs/nenhuma] |
| Riscos residuais | [RIS-IDs/nenhum] |
| Resultado | [Aceitar/aceitar com condição/corrigir/rejeitar/reverter] |
| Decisão | [ID] |

---

## 68. Verificação para o `PI-5`

Pergunta oficial:

> O Módulo 5 recebeu a configuração implantada, compreendeu suas condições e possui capacidade para sustentá-la?

| Verificação | Resultado | Itens | Evidência |
| --- | --- | --- | --- |
| Riscos residuais possuem responsável operacional? | [Sim/parcial/não] | [IDs] | [IDs] |
| Problemas e pendências abertas possuem destino? | [Sim/parcial/não] | [IDs] | [IDs] |
| Dependências operacionais estão aceitas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Restrições e premissas vigentes são compreendidas? | [Sim/parcial/não] | [IDs] | [IDs] |
| Condições transferidas possuem limite e retorno? | [Sim/parcial/não] | [IDs] | [IDs] |
| Mudanças incorporadas constam da configuração? | [Sim/parcial/não] | [IDs] | [IDs] |
| Gatilhos de retorno aos Módulos 3 e 4 estão explícitos? | [Sim/parcial/não] | [IDs] | [IDs] |
| A operação possui acesso ao registro necessário? | [Sim/parcial/não] | [IDs] | [IDs] |

| Campo | Registro |
| --- | --- |
| Configuração transferida | [CFG-ID/versão] |
| Fotografia do registro | [ID/versão/data] |
| Itens residuais propostos | [IDs] |
| Itens aceitos pelo Módulo 5 | [IDs] |
| Itens devolvidos | [IDs/nenhum] |
| Resultado | [Aceitar/aceitar parcialmente/devolver/estender estabilização/suspender] |
| Decisão bilateral | [ID] |

---

## 69. Fotografias históricas de gates

| Fotografia | Ocorrência | Registro e versão | Data de status | Escopo | Itens abertos | Itens aceitos | Itens impeditivos | Resultado | Fonte preservada |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [PI-ID] | [RIC-ID/versão] | [Data/hora] | [IDs/versões] | [IDs] | [IDs] | [IDs] | [ID/resultado] | [Link/exportação] |

### 69.1 Não reescrever o passado

Atualizar o item vigente não altera a fotografia considerada por decisão anterior. Se nova evidência afetar a decisão, registre reabertura e nova ocorrência.

### 69.2 Reprodutibilidade

A fotografia deve preservar:

- fonte e versão;
- filtros;
- objetos e versões;
- avaliação vigente;
- ações e evidências;
- decisões e condições;
- itens omitidos ou não avaliados;
- data e responsável pela extração.

---

## 70. Suspensão, contenção, reversão, cancelamento e reabertura

| Ação | Objeto | Motivo | Evidência | Autoridade | Estado preservado | Comunicação | Dados/ativos | Riscos remanescentes | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Conter/suspender/reverter/cancelar/reabrir] | [ID/versão] | [ID/síntese] | [IDs] | [Nome/papel] | [Estado/versão] | [ID] | [Destino] | [IDs] | [Preencher] |

### 70.1 Gatilhos de suspensão

- perda de autoridade;
- linha de base inválida;
- risco acima da tolerância;
- violação ética, legal ou de segurança;
- dado ou acesso não autorizado;
- dependência crítica não atendida;
- reversão requerida e indisponível;
- evidência de dano material;
- condição de gate descumprida;
- mudança arquitetural indecidida;
- impossibilidade de validação responsável;
- operação sem capacidade de receber.

### 70.2 Reabertura

Reabertura preserva:

- item e decisão anteriores;
- motivo e nova evidência;
- objeto e versão;
- autoridade;
- efeitos sobre gates e configuração;
- novo horizonte de tratamento.

---

## 71. Condições residuais e transferência

| Item residual | Tipo | Origem | Objeto/versão | Exposição/efeito | Limite | Resposta | Responsável M4 | Responsável M5 | Gatilho de retorno | Aceite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo] | [ID] | [ID/versão] | [Preencher] | [Data/evento/nível] | [ID/ação] | [Nome] | [Nome] | [Preencher] | [ID/pendente] |

### 71.1 Transferência bilateral

Uma condição somente é transferida quando o recebedor:

- compreende o objeto e a exposição;
- possui autoridade e capacidade;
- aceita responsabilidade;
- conhece resposta, limite e escalonamento;
- possui acesso a evidências e fontes;
- conhece o gatilho de retorno.

### 71.2 Operação não é depósito

Pendência ou risco não pode ser enviado ao Módulo 5 apenas para permitir encerramento administrativo.

---

## 72. Papéis e responsabilidades

| Papel | Responsabilidades no registro |
| --- | --- |
| Autoridade da implantação | Decide alçadas, exposições e mudanças dentro de sua competência. |
| Responsável pela implantação | Integra tratamento ao plano, fluxo, gates e transição. |
| Responsável pelo registro | Mantém qualidade, estados, histórico e sincronização. |
| Proprietário do risco | Acompanha exposição, resposta e gatilhos. |
| Responsável pelo objeto | Informa efeito, bloqueio e condição de avanço. |
| Responsável pelo desbloqueio | Coordena ações para remover impedimento. |
| Responsável pela dependência | Coordena atendimento e escalonamento. |
| Responsável pela arquitetura | Classifica materialidade arquitetural e recebe retornos. |
| Responsável operacional | Avalia sustentação e aceita itens residuais. |
| Especialista | Avalia dimensão dentro de sua competência. |
| Pessoa afetada | Contribui com evidência situada e efeitos reais. |
| Custodiante | Protege acesso, retenção e disponibilidade. |
| IA | Apoia organização e análise, sem autoridade decisória. |

### 72.1 Pessoa que identifica

Qualquer pessoa autorizada pelo canal aplicável pode tornar item visível. Falta de poder decisório não invalida a observação.

---

## 73. Matriz de autoridade

| Ato | Executa | Verifica | Decide | Deve ser informado | Segregação requerida |
| --- | --- | --- | --- | --- | --- |
| Registrar item | [Papel] | [Papel] | [N.A.] | [Papéis] | [Quando material] |
| Classificar | [Papel] | [Papel] | [Papel] | [Papéis] | [Conforme impacto] |
| Avaliar risco | [Papel] | [Papel/especialista] | [N.A.] | [Papéis] | [Conforme impacto] |
| Aceitar risco | [Papel] | [Papel] | [Autoridade] | [Papéis] | [Sim quando alto/crítico] |
| Declarar impedimento | [Papel] | [Papel] | [Papel/autoridade] | [Papéis] | [Conforme disputa] |
| Dispensar dependência | [Papel] | [Papel] | [Autoridade] | [Papéis] | [Conforme materialidade] |
| Classificar mudança | [Papel] | [Arquitetura/especialista] | [Autoridade] | [Papéis] | [Sim quando material] |
| Incorporar mudança | [Papel] | [Papel] | [Conforme decisão] | [Papéis] | [Separar decisão de execução] |
| Transferir condição | [M4] | [M5] | [Autoridades bilaterais] | [Papéis] | [Sim] |
| Encerrar item | [Papel] | [Papel] | [Autoridade quando residual] | [Papéis] | [Conforme impacto] |

---

## 74. Cadências e eventos de revisão

| Cadência/evento | Escopo | Participantes | Entrada | Saída | Prazo de atualização |
| --- | --- | --- | --- | --- | --- |
| Triagem | Novos itens. | [Papéis] | [Fila/canais] | Classificação e responsável. | [Duração] |
| Revisão operacional | Itens ativos e vencimentos. | [Papéis] | Registro, Kanban, cronograma. | Ações e escalonamentos. | [Duração] |
| Revisão de risco | Exposição e respostas. | [Papéis] | Avaliações e evidências. | Risco residual e decisões. | [Duração] |
| Revisão de mudança | Solicitações e incorporações. | [Papéis] | Análises e versões. | Decisão e rota. | [Duração] |
| Revisão de gate | Objeto e versão delimitados. | [Autoridades] | Fotografia do registro. | Condições e decisão. | Antes do gate. |
| Revisão de estabilização | Itens observados após liberação. | [Papéis] | Ocorrências e indicadores. | Respostas e transição. | [Duração] |
| Revisão de transição | Itens residuais. | [M4 e M5] | Pacote de transferência. | Aceite bilateral. | Antes do PI-5. |
| Revisão por evento | Item crítico ou mudança material. | [Papéis] | Evidência nova. | Contenção, decisão ou reabertura. | Imediata/proporcional. |

### 74.1 Atualização por evento

Não espere a reunião ordinária quando houver:

- risco crítico;
- impedimento em caminho crítico;
- violação de segurança ou direito;
- dependência rompida;
- premissa material refutada;
- condição de gate descumprida;
- mudança arquitetural;
- dano ou quase falha material.

---

## 75. Indicadores do registro

| Indicador | Pergunta | Definição | Fonte | Frequência | Limite | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| Tempo de triagem | Novos itens são qualificados a tempo? | [Fórmula] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Itens sem responsável | Existem condições sem dono? | [Contagem e denominador] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Riscos acima da tolerância | Que exposições exigem decisão? | [Critério] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Respostas vencidas | Tratamentos perderam prazo? | [Critério] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Idade de impedimentos | Bloqueios persistem além do limite? | [Mediana/faixas] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Dependências vencidas | Condições necessárias não chegaram? | [Contagem/criticidade] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Premissas materiais não verificadas | Planejamento depende de afirmações frágeis? | [Contagem/criticidade] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Condições descumpridas | Avanços perderam base autorizadora? | [Contagem/efeito] | [Fonte] | [Evento] | [Zero/limite] | [Ação] |
| Tempo de decisão de mudança | Mudanças ficam indecididas? | [Fórmula por classe] | [Fonte] | [Cadência] | [Limite] | [Ação] |
| Mudanças devolvidas ao M3 | Que aprendizagem excedeu o envelope? | [Contagem/causa] | [Fonte] | [Período] | [Referência] | [Ação] |
| Mudanças sem atualização documental | A realidade diverge da fonte? | [Contagem] | [Fonte] | [Cadência] | [Zero] | [Ação] |
| Itens residuais sem aceite | A transição tenta deslocar responsabilidade? | [Contagem] | [Fonte] | [PI-5] | [Zero] | [Ação] |

### 75.1 Proteções dos indicadores

- quantidade de riscos não mede incompetência;
- poucos riscos podem indicar baixa visibilidade;
- tempo de resolução não justifica fechamento prematuro;
- bloqueio não é produtividade individual;
- mudança rejeitada não é desperdício automático;
- aceitação de risco não é sucesso;
- indicador sem próxima ação não governa.

---

## 76. Visões e relatórios derivados

| Visão | Filtro mínimo | Público | Finalidade | Fonte/versão | Sensibilidade |
| --- | --- | --- | --- | --- | --- |
| Operacional | Itens ativos por objeto e responsável. | Equipe. | Coordenar tratamento. | [ID/versão] | [Nível] |
| Executiva | Exposições, decisões e vencimentos materiais. | Autoridades. | Decidir e alocar recursos. | [ID/versão] | [Nível] |
| Gate | Objeto, versão e condições aplicáveis. | Autoridade do gate. | Deliberar. | [Fotografia] | [Nível] |
| Mudanças | Propostas, classes, decisões e incorporações. | Governança. | Controlar linha de base. | [ID/versão] | [Nível] |
| Dependências críticas | Caminho crítico e condições externas. | Coordenação. | Escalonar e antecipar falhas. | [ID/versão] | [Nível] |
| Transição | Itens residuais e responsáveis propostos. | M4 e M5. | Aceitar responsabilidade. | [ID/versão] | [Nível] |
| Auditoria | Histórico, evidências, decisões e versões. | Revisor autorizado. | Reconstruir percurso. | [ID/versão] | [Nível] |

### 76.1 Semáforo

Cor pode apoiar leitura, mas nunca ser o único portador de significado. Exiba estado, critério e data em texto.

---

## 77. Sensibilidade, acesso e proteção

| Classe | Conteúdo típico | Acesso | Forma de referência |
| --- | --- | --- | --- |
| Pública | Riscos e mudanças já divulgados. | Conforme publicação. | Conteúdo direto. |
| Interna | Planejamento e tratamento ordinário. | Equipe autorizada. | Conteúdo necessário. |
| Confidencial | Estratégia, contrato, vulnerabilidade ou negociação. | Papéis delimitados. | Síntese e fonte protegida. |
| Sensível | Dados pessoais, saúde, denúncia, segurança ou segredo crítico. | Necessidade estrita. | ID, estado e localização protegida. |

### 77.1 Minimização

Registre no quadro comum apenas o necessário para governar. Relato detalhado sensível permanece em fonte protegida com acesso, retenção e responsável.

### 77.2 Segredo não é ausência

Mesmo quando o conteúdo não puder ser exposto, preserve:

- ID;
- tipo;
- objeto afetado quando possível;
- nível;
- responsável autorizado;
- estado;
- efeito sobre decisão;
- localização protegida.

### 77.3 Retaliação e segurança psicológica

O processo deve proteger quem relata risco, falha, impacto humano ou divergência de boa-fé. Registro não é instrumento de vigilância ou retaliação.

---

## 78. Participação da inteligência artificial

A IA pode apoiar:

- identificar duplicações;
- sugerir classificação preliminar;
- comparar versões e fontes;
- detectar campos ausentes;
- organizar cenários;
- analisar relações e dependências;
- resumir histórico;
- sinalizar vencimentos;
- preparar visões;
- apoiar análise de impacto;
- verificar consistência;
- sugerir perguntas de revisão.

A IA não pode:

- aceitar risco;
- declarar exposição tolerável;
- dispensar condição ou dependência;
- definir materialidade final;
- aprovar mudança;
- alterar linha de base;
- autorizar execução, liberação ou reversão;
- avaliar sozinha impacto humano;
- encerrar item material;
- transferir responsabilidade;
- ocultar incerteza ou divergência;
- assumir responsabilidade final.

### 78.1 Registro da participação

| Campo | Registro |
| --- | --- |
| Sistema, agente ou modelo | [Nome/versão] |
| Função | [Preencher] |
| Itens processados | [IDs] |
| Dados e contexto | [Descrição/classificação] |
| Ferramentas e permissões | [Preencher] |
| Saída | [ID/link] |
| Limitações | [Preencher] |
| Verificação humana | [Nome/papel/método] |
| Correções | [Preencher/nenhuma] |
| Decisão humana relacionada | [ID/N.A.] |
| Incidente | [ID/nenhum] |
| Data | [Data/hora] |

### 78.2 Inferência não confirmada

Sinal produzido por IA entra como hipótese, alerta ou item `a_classificar` até verificação humana proporcional.

---

## 79. Automação e regras processáveis

Automação pode:

- validar padrão e unicidade de IDs;
- exigir campos conforme o tipo;
- calcular idade e vencimento;
- sinalizar responsável ausente;
- detectar condição vencida;
- comparar tolerância e exposição;
- localizar mudança sem decisão;
- localizar item encerrado com ação aberta;
- comparar dependências entre fontes;
- gerar fotografia de gate;
- verificar item residual sem aceite;
- registrar trilha de atualização.

### 79.1 Regras sugeridas

| Regra | Condição | Resultado automático | Ação humana |
| --- | --- | --- | --- |
| ID duplicado | Mesmo ID em itens distintos. | Bloquear gravação ou sinalizar. | Corrigir identidade. |
| Item sem objeto | Campo obrigatório vazio. | Marcar incompleto. | Qualificar ou justificar. |
| Risco crítico | Nível crítico. | Alertar imediatamente. | Avaliar, conter e decidir. |
| Impedimento envelhecido | Idade acima do limite. | Escalonar alerta. | Rever resposta. |
| Dependência vencida | Data necessária passou. | Marcar vencida. | Confirmar efeito e decidir. |
| Premissa expirada | Validade passou. | Marcar para revisão. | Verificar ou conter. |
| Condição descumprida | Prazo passou sem atendimento. | Alertar gate/objeto. | Aplicar consequência. |
| Mudança sem autoridade | Classe requer alçada ausente. | Impedir estado “aprovada”. | Resolver autoridade. |
| Item residual sem aceite | Transferência proposta sem decisão bilateral. | Bloquear encerramento. | Obter aceite ou manter no M4. |

### 79.2 Limite da automação

Regra automática pode bloquear transição de estado técnico. Não decide mérito, tolerância, materialidade, aceite ou autoridade.

---

## 80. Proporcionalidade

### 80.1 Implantação focal

Pode utilizar:

- uma tabela mestre;
- fichas apenas para itens materiais;
- escala qualitativa simples;
- uma cadência combinada;
- ações no mesmo backlog;
- uma fotografia por gate aplicável;
- transferência simplificada.

Campos irredutíveis:

- ID e tipo;
- objeto;
- descrição;
- responsável;
- autoridade;
- estado;
- tratamento;
- prazo ou gatilho;
- evidência;
- decisão quando necessária;
- destino.

### 80.2 Implantação funcional

Utiliza:

- registros especializados;
- avaliação multidimensional;
- dependências internas e externas;
- fluxo formal de mudança;
- sincronização completa;
- gates repetíveis;
- planos humanos relacionados;
- transferência de condições residuais.

### 80.3 Implantação sistêmica

Acrescenta:

- registros por programa, projeto, onda e incremento;
- múltiplas autoridades e linhas de controle;
- análise de propagação;
- riscos agregados e cenários;
- fornecedores e contratos complexos;
- mudanças arquiteturais formais;
- fotografias automatizadas;
- auditoria e segregação ampliadas;
- transição por configuração ou capacidade.

### 80.4 Intensificadores

Aumente o controle quando houver:

- impacto humano significativo;
- dados sensíveis;
- regulação;
- segurança;
- IA com autonomia ou ação externa;
- irreversibilidade;
- múltiplas interfaces;
- fornecedor crítico;
- alto custo de falha;
- baixa detectabilidade;
- transição entre organizações;
- conhecimento concentrado.

### 80.5 Regra de redução

Reduzir campos ou combinar papéis não pode retirar:

- autoridade;
- rastreabilidade;
- condição de avanço;
- proteção humana;
- decisão de mudança;
- destino residual;
- responsabilidade final.

---

## 81. Revisão consolidada e teste de reconstrução

### 81.1 Identidade e fonte

- [ ] O registro possui ID, implantação, versão e fonte oficial.
- [ ] As referências aos instrumentos vigentes estão atualizadas.
- [ ] IDs não foram reutilizados ou convertidos.
- [ ] Exportações indicam versão e data de corte.

### 81.2 Qualificação

- [ ] Risco, problema, impedimento e dependência estão distintos.
- [ ] Restrições, premissas e condições possuem tratamento próprio.
- [ ] Mudança e diferença não foram confundidas.
- [ ] Itens inconclusivos possuem prazo e responsável.

### 81.3 Tratamento

- [ ] Itens materiais possuem objeto, origem, efeito e responsável.
- [ ] Ações têm resultado esperado, prazo e evidência.
- [ ] Riscos residuais foram avaliados.
- [ ] Impedimentos possuem condição de desbloqueio.
- [ ] Dependências possuem dois lados e critério de atendimento.
- [ ] Premissas materiais possuem verificação.
- [ ] Condições possuem consequência.

### 81.4 Autoridade e mudança

- [ ] Aceitações de risco possuem autoridade.
- [ ] Classes de mudança foram verificadas.
- [ ] Mudanças arquiteturais retornaram ao Módulo 3.
- [ ] Incorporações resolvem para decisão e versão.
- [ ] Mudanças emergenciais receberam revisão posterior.
- [ ] Divergências foram preservadas.

### 81.5 Gates e continuidade

- [ ] Fotografias de gates são reproduzíveis.
- [ ] Itens aceitos permanecem visíveis depois do gate.
- [ ] Condições descumpridas acionaram consequência.
- [ ] Configuração reflete mudanças autorizadas.
- [ ] Itens residuais possuem responsável, limite e aceite.
- [ ] Gatilhos de retorno estão explícitos.

### 81.6 Percurso do risco

Parta de `RIS-NNN` e localize:

1. objeto e versão;
2. causa, evento e efeito;
3. avaliação e tolerância;
4. respostas e ações;
5. evidências;
6. risco residual;
7. aceitação ou escalonamento;
8. materialização, encerramento ou transferência.

### 81.7 Percurso do impedimento

Parta de `IPD-NNN` e localize:

1. objeto bloqueado;
2. início e estado factual no Kanban;
3. condição bloqueadora;
4. dependência ou problema relacionado;
5. responsável e escalonamento;
6. condição e evidência de desbloqueio;
7. estado posterior do objeto.

### 81.8 Percurso da dependência

Parta de `DEP-NNN` e localize:

1. objeto dependente;
2. predecessora;
3. condição de atendimento;
4. responsáveis;
5. momento necessário;
6. risco e alternativa;
7. evidência de atendimento;
8. efeito no cronograma e na matriz.

### 81.9 Percurso da mudança

Parta de `MUD-NNN` e localize:

1. situação e evidência;
2. estado atual e proposta;
3. classe;
4. análise de impacto;
5. autoridade;
6. decisão;
7. ações e versões;
8. verificação;
9. configuração e gates afetados;
10. comunicação e destino.

### 81.10 Registro do teste

| Teste | Item inicial | Objeto final esperado | Resultado | Ponto de bloqueio | Lacuna | Correção | Revisor | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Risco/impedimento/dependência/mudança/condição residual] | [ID] | [ID/decisão/configuração] | [Suficiente/parcial/bloqueado/fonte indisponível/versão ambígua] | [ID/etapa] | [ID/nenhuma] | [ID/ação] | [Nome] | [Data] |

---

## 82. Antipadrões e sinais de qualidade

### 82.1 Antipadrões

- registrar tudo como risco;
- converter risco materializado em outro ID e apagar o original;
- tratar problema como “atraso” sem objeto;
- culpar pessoas por impedimentos;
- manter dependência sem responsável interno;
- marcar dependência atendida por promessa;
- apresentar premissa como fato;
- aceitar condição sem consequência;
- usar urgência como autoridade;
- chamar mudança arquitetural de ajuste;
- atualizar linha de base antes da decisão;
- aceitar risco implicitamente por aprovação de gate;
- encerrar item porque a ação terminou;
- usar pontuação como verdade objetiva;
- ocultar evidência divergente;
- deixar mudança aprovada sem versão incorporada;
- reescrever fotografias históricas;
- transferir pendência para encerrar projeto;
- permitir que IA aprove, aceite ou encerre;
- aumentar carga documental sem uso decisório.

### 82.2 Sinais de qualidade

- cada item responde a uma pergunta própria;
- objetos e versões estão identificados;
- descrição separa fato, hipótese e decisão;
- ações possuem resultado e evidência;
- estados correspondem à realidade;
- escalonamento ocorre antes do dano evitável;
- dependências são tratadas antes de vencer;
- premissas frágeis ficam visíveis;
- mudança resolve para autoridade e versão;
- configuração preserva diferenças autorizadas;
- gates consideram fotografia reproduzível;
- pessoas podem contestar classificação;
- riscos residuais chegam à operação com aceite;
- outra pessoa reconstrói o percurso sem memória privada.

---

## 83. Exemplo aplicado — sistema editorial

### 83.1 Contexto

A implantação `IMP-2026-001` realiza um fluxo editorial com estados visíveis, aprovação explícita, preservação de arquivos e suporte à operação.

Objetos de referência:

| Objeto | ID |
| --- | --- |
| Capacidade editorial | [CAP-ID herdado] |
| Incremento piloto | `IMP-2026-001-INC-001` |
| Entrega do fluxo configurado | `IMP-2026-001-ENT-001` |
| Pacote de configuração | `IMP-2026-001-PT-003` |
| Item de fluxo | `IMP-2026-001-ITM-008` |
| Linha de base | [LB-ARQ-ID/versão] |

### 83.2 Risco

| Campo | Exemplo |
| --- | --- |
| ID | `IMP-2026-001-RIS-001` |
| Formulação | Devido à sincronização ainda não testada entre ferramenta e pasta oficial, pode ocorrer perda de referência de arquivo durante o piloto, afetando integridade e continuidade editorial. |
| Objeto | `IMP-2026-001-INC-001` |
| Exposição inerente | Alta. |
| Resposta | Reduzir por teste de cenários, cópia controlada e regra de fonte oficial. |
| Gatilho | Arquivo não localizado ou duas versões concorrentes. |
| Contingência | Retornar ao fluxo manual e preservar a última versão confirmada. |
| Autoridade para aceitar residual | Responsável designado no `PI-3`. |

### 83.3 Dependência

| Campo | Exemplo |
| --- | --- |
| ID | `IMP-2026-001-DEP-004` |
| Objeto dependente | `IMP-2026-001-INC-001` |
| Predecessora | Confirmação da ferramenta, dos acessos e da pasta oficial. |
| Condição de atendimento | Duas pessoas localizam, atualizam e recuperam o mesmo arquivo sem ambiguidade no ambiente de teste. |
| Momento necessário | Antes do `PI-2` do piloto. |
| Responsável interno | Responsável pela implantação. |
| Alternativa | Fluxo manual documentado. |

### 83.4 Impedimento

Na preparação, uma das pessoas críticas não possui permissão para editar a pasta oficial.

| Campo | Exemplo |
| --- | --- |
| ID | `IMP-2026-001-IPD-002` |
| Objeto bloqueado | `IMP-2026-001-PT-003` |
| Condição bloqueadora | Acesso de edição ausente. |
| Início | [Data/hora] |
| Condição de desbloqueio | Acesso autorizado, testado e registrado pela pessoa afetada. |
| Item no Kanban | `IMP-2026-001-ITM-008` marcado como bloqueado. |
| Escalonamento | Responsável pelo acesso até [data]. |

O impedimento se relaciona à dependência `IMP-2026-001-DEP-004`. Ele não substitui a dependência nem se reduz a atraso.

### 83.5 Mudança

Durante o teste, observa-se que a aprovação desenhada como estado único precisa distinguir `em revisão` de `ajustes solicitados`.

| Campo | Exemplo |
| --- | --- |
| ID | `IMP-2026-001-MUD-003` |
| Situação | Testes demonstram perda de clareza sobre quem deve agir depois de uma devolução. |
| Proposta | Incluir dois estados e suas políticas de entrada e saída. |
| Classe preliminar | Adaptação autorizada, se não alterar requisito, autoridade, interface crítica ou risco. |
| Teste de materialidade | Verificar se a separação redistribui autoridade ou altera o requisito de aprovação. |
| Rota | Permanecer no Módulo 4 dentro da tolerância; retornar ao Módulo 3 se houver redistribuição de autoridade. |
| Evidência | [EVD-IDs dos testes] |
| Decisão | [DEC-ID] |

### 83.6 Materialização e resposta

Se um arquivo deixar de ser localizado:

1. registre o evento;
2. relacione a materialização de `IMP-2026-001-RIS-001`;
3. abra problema ou impedimento conforme o efeito;
4. acione contingência;
5. preserve evidência;
6. avalie diferença de configuração;
7. reavalie `PI-3` ou liberação vigente;
8. decida correção, reversão ou mudança.

### 83.7 Visão consolidada

| Item | Tipo | Objeto | Estado | Ação/decisão | Gate afetado |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-RIS-001` | Risco | `IMP-2026-001-INC-001` | [Em tratamento] | [IMP-2026-001-ACA-NNN/DEC-AAAA-NNN] | `PI-3` |
| `IMP-2026-001-DEP-004` | Dependência | `IMP-2026-001-INC-001` | [Confirmada/em atendimento] | [IMP-2026-001-ACA-NNN] | `PI-2` |
| `IMP-2026-001-IPD-002` | Impedimento | `IMP-2026-001-PT-003` | [Em desbloqueio] | [IMP-2026-001-ACA-NNN] | `PI-2` |
| `IMP-2026-001-MUD-003` | Mudança | Fluxo editorial | [Em análise/decidida] | [DEC-AAAA-NNN] | `PI-3`/`PI-4` |

### 83.8 Limite do exemplo

O exemplo demonstra relações. Não define tolerâncias, autoridades ou evidências para outra implantação.

---

## 84. Manifestações, controle de versões e encerramento

### 84.1 Responsável pelo registro

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Declaração | [O registro representa os itens conhecidos no horizonte declarado.] |
| Limitações | [Preencher/nenhuma] |
| Itens sem qualificação suficiente | [IDs/nenhum] |
| Versão | [N.N] |
| Data | [Data/hora] |
| Assinatura ou confirmação | [Referência] |

### 84.2 Responsável pela implantação

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Declaração | [Tratamentos, ações e escalonamentos foram integrados ao trabalho.] |
| Restrições | [Preencher/nenhuma] |
| Decisões requeridas | [IDs/nenhuma] |
| Data | [Data/hora] |
| Confirmação | [Referência] |

### 84.3 Responsável pela arquitetura

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Mudanças recebidas | [IDs/nenhuma] |
| Linhas de base afetadas | [IDs/versões] |
| Decisões emitidas | [IDs/nenhuma] |
| Objetos ainda contidos | [IDs/nenhum] |
| Data | [Data/hora] |
| Confirmação | [Referência] |

### 84.4 Responsável operacional

| Campo | Manifestação |
| --- | --- |
| Nome e papel | [Preencher] |
| Itens residuais recebidos | [IDs/nenhum] |
| Itens aceitos | [IDs/nenhum] |
| Itens devolvidos | [IDs/nenhum] |
| Condições e retornos compreendidos | [Sim/não/parcial] |
| Decisão bilateral | [ID] |
| Data | [Data/hora] |
| Confirmação | [Referência] |

### 84.5 Divergências preservadas

| Pessoa/papel | Divergência | Item | Evidência | Destino | Decisão relacionada |
| --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [Preencher] | [ID] | [IDs] | [Preencher] | [ID/pendente] |

### 84.6 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de status | [Data/hora] |
| Fonte oficial | [Caminho/link] |
| Linha de base referenciada | [ID/versão] |
| Gate mais recente | [ID/N.A.] |
| Fotografia mais recente | [ID/N.A.] |
| Decisão/aprovação | [ID/N.A.] |
| Versão substituída | [N.N/N.A.] |

### 84.7 Histórico de versões do registro preenchido

| Versão | Data | Alteração | Evento/motivo | Itens afetados | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| [N.N] | [Data] | [Preencher] | [ID/síntese] | [IDs] | [Nome] | [ID/N.A.] |

### 84.8 Critérios de conclusão

O registro pode ser considerado concluído para a implantação quando:

- possui identidade, versão e fonte oficial;
- itens materiais estão qualificados;
- responsáveis e autoridades são localizáveis;
- riscos possuem exposição e destino;
- problemas e impedimentos possuem resultado;
- dependências possuem atendimento, substituição ou decisão;
- restrições e premissas vigentes seguem para fonte competente;
- condições possuem cumprimento, dispensa ou transferência;
- mudanças possuem decisão e efeito documental;
- retornos ao Módulo 3 foram concluídos ou destinados;
- ações abertas possuem destino;
- fotografias de gates foram preservadas;
- matriz e configuração foram sincronizadas;
- itens residuais possuem aceite bilateral;
- evidências e divergências permanecem localizáveis;
- participação material da IA está registrada;
- outra pessoa autorizada consegue reconstruir os percursos aplicáveis.

### 84.9 Resultado de conclusão

- [ ] Concluído para o horizonte declarado
- [ ] Concluído com itens residuais aceitos
- [ ] Requer complementação
- [ ] Requer decisão de autoridade
- [ ] Requer retorno ao Módulo 3
- [ ] Requer extensão da estabilização
- [ ] Bloqueado
- [ ] Suspenso
- [ ] Reaberto
- [ ] Substituído

| Campo | Registro |
| --- | --- |
| Horizonte | [Objetos/período] |
| Resultado | [Selecionar] |
| Itens abertos | [IDs/nenhum] |
| Itens residuais transferidos | [IDs/nenhum] |
| Itens sem destino | [IDs/nenhum] |
| Gate/decisão | [ID] |
| Próximo movimento | [Transferir/corrigir/reabrir/encerrar/outro] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Data | [Data/hora] |
| Evidência | [ID/link] |

Encerrar o registro para a implantação não apaga itens vigentes na operação. A fonte operacional recebe os objetos aceitos e preserva referência ao dossiê.

### 84.10 Registro final do template

| Campo | Registro |
| --- | --- |
| Identificador do template | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |
| Módulo | 4 — Implantação |
| Tipo | Template operacional |
| Função | Qualificar, relacionar, tratar, decidir e destinar condições que afetam a implantação |
| Entrada principal | Linha de base aceita e instrumentos vigentes da implantação |
| Saída principal | Fonte integrada de riscos, problemas, impedimentos, dependências, restrições, premissas, condições e mudanças |
| Gates relacionados | `PI-1` a `PI-5` |
| Documento anterior | `templates/06-matriz-de-rastreabilidade-da-implantacao.md` |
| Documento seguinte | `templates/08-plano-de-comunicacao-e-engajamento.md` |
| Fonte oficial | Repositório do Sistema Operacional do Estúdio LICHTARA |
| Responsabilidade final | Humana |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação integral do Registro de Riscos, Impedimentos, Dependências e Mudanças como instrumento integrado de controle da implantação. | Estúdio LICHTARA |
