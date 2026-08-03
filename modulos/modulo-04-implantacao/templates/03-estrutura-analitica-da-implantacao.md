# Estrutura Analítica da Implantação

**Identificação técnica no repositório**

```yaml
id_estrutura_analitica: EAI-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Estrutura Analítica]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_plano_de_implantacao: PLA-IMP-AAAA-NNN
versao_plano_de_implantacao:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base:
responsavel_pela_implantacao:
responsavel_pela_decomposicao:
responsavel_pela_arquitetura:
custodiante_da_estrutura:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado_da_estrutura: em_elaboracao
nivel_de_elaboracao: macro | intermediario | detalhado | horizonte_executavel
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Decomposição da linha de base arquitetural em unidades governáveis de realização, entrega e trabalho  
**Documentos de referência:** Fundamentos da Implantação; Protocolo de Implantação; Matriz de Rastreabilidade da Implantação  
**Documentos de entrada:** Termo de Abertura e Plano de Implantação vigentes  
**Documento seguinte na ordem de construção:** `templates/04-cronograma-mestre-da-implantacao.md`  
**Ponto de controle relacionado:** PI-2 — Prontidão para executar

---

## 1. Finalidade

Este template transforma o escopo autorizado e a linha de base arquitetural em uma estrutura explícita de capacidades, componentes ou condições, incrementos, entregas e pacotes de trabalho.

Sua finalidade é tornar demonstrável:

- o que precisa existir para que a implantação produza a capacidade pretendida;
- por que cada unidade de realização ou trabalho existe;
- que objetos arquiteturais ela realiza, preserva, prepara ou protege;
- como as partes se integram sem perder interfaces e dependências;
- quem responde por cada resultado local;
- que critério define conclusão;
- que evidência deverá ser produzida;
- que lacunas, sobreposições, exclusões e incertezas permanecem;
- quais unidades estão suficientemente elaboradas para alimentar cronograma e backlog;
- que condições precisam ser demonstradas antes do `PI-2`.

A estrutura analítica organiza o conteúdo da realização. Ela não substitui decisão de gate, cronograma, backlog, matriz de rastreabilidade, registro de riscos ou configuração implantada.

---

## 2. Pergunta central

> Como decompor a arquitetura autorizada em unidades controláveis de realização e trabalho sem perder capacidades, critérios, interfaces, proteções, responsabilidades e relações que dão sentido ao conjunto?

Uma estrutura analítica é suficiente quando permite reconstruir a passagem entre a linha de base recebida e cada pacote de trabalho sem transformar decomposição em fragmentação.

---

## 3. Posição no protocolo

Este documento materializa a Etapa 9 do Protocolo de Implantação — decompor a arquitetura em unidades de realização — e prepara as condições para:

1. iniciar a matriz do dossiê real;
2. construir o cronograma mestre;
3. organizar o backlog e o quadro Kanban;
4. planejar recursos, competências, verificações e evidências;
5. examinar a prontidão do objeto submetido ao `PI-2`.

```text
PI-1 aceito
  → Termo de Abertura aprovado
  → Plano de Implantação vigente
  → Estrutura Analítica da Implantação
  → Matriz, cronograma, backlog e planos especializados
  → Verificação de prontidão
  → PI-2
```

A aprovação desta estrutura autoriza seu uso no planejamento detalhado. Não autoriza iniciar execução, liberar incremento, aceitar capacidade ou transferir operação.

---

## 4. Distinções que este template preserva

| Elemento | Pergunta principal | Fonte oficial |
| --- | --- | --- |
| Termo de Abertura | O que foi autorizado a planejar e dentro de quais limites? | `templates/01-termo-de-abertura-da-implantacao.md` |
| Plano de Implantação | Como estratégia, governança, preparação, execução e transição serão integradas? | `templates/02-plano-de-implantacao.md` |
| Estrutura Analítica | O que compõe a realização e em que unidades governáveis o trabalho será decomposto? | Este documento |
| Cronograma Mestre | Quando unidades, marcos e dependências temporais deverão ocorrer? | `templates/04-cronograma-mestre-da-implantacao.md` |
| Backlog e Kanban | Que objetos atravessam o fluxo real e em que estado estão? | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` |
| Matriz de Rastreabilidade | Que vínculos formais conectam origem, realização, evidência, decisão e configuração? | `templates/06-matriz-de-rastreabilidade-da-implantacao.md` |
| Registro integrado | Que riscos, impedimentos, dependências e mudanças afetam o trabalho? | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |

### 4.1 Estrutura não é cronograma

A posição de um nó na estrutura expressa composição ou pertencimento. Não expressa data, duração, caminho crítico ou precedência temporal.

### 4.2 Pacote de trabalho não é item de backlog

Pacote de trabalho é unidade de planejamento. Item de backlog é unidade de fluxo. Um pacote pode originar vários itens; um item pode representar teste, decisão, risco ou correção sem constituir novo pacote.

### 4.3 Entrega não é capacidade

Entrega é objeto produzido. Capacidade é aquilo que a organização consegue realizar no contexto definido. Uma entrega concluída pode ser necessária e ainda insuficiente para demonstrar capacidade.

### 4.4 Incremento não é onda

Incremento é parcela coerente e verificável da configuração. Onda organiza exposição, mobilização ou liberação de um ou mais incrementos.

### 4.5 Decomposição não é rastreabilidade completa

Esta estrutura preserva referências necessárias ao entendimento. O registro canônico dos vínculos, suas versões, estados e evidências pertence à matriz de rastreabilidade.

---

## 5. Natureza do documento

A Estrutura Analítica da Implantação é, simultaneamente:

- **orientada a resultados**, porque começa por capacidades e incrementos;
- **arquiteturalmente vinculada**, porque preserva requisitos, componentes, condições e interfaces;
- **hierárquica**, porque decompõe objetos agregados em unidades menores;
- **relacional**, porque reconhece relações muitos-para-muitos que uma árvore isolada não representa;
- **progressivamente elaborada**, porque o horizonte próximo recebe detalhe maior que horizontes incertos;
- **versionada**, porque a decomposição muda sem apagar a história;
- **proporcional**, porque profundidade e controles respondem ao risco e à complexidade;
- **preparatória**, porque sustenta planejamento e prontidão, sem constituir autorização de execução.

Sua fonte real é a cópia preenchida no dossiê da implantação. Este arquivo permanece como template-mestre.

---

## 6. Autoridade e limites

Este documento pode:

- detalhar como o escopo autorizado será realizado;
- criar identificadores próprios do Módulo 4;
- agrupar trabalho em incrementos, entregas e pacotes;
- revelar lacunas, conflitos e dependências;
- propor divisão ou combinação de unidades dentro do envelope aprovado;
- registrar exclusões já autorizadas e elaboração futura;
- sustentar decisões de planejamento e preparação.

Este documento não pode:

- alterar requisito, capacidade, componente, interface ou decisão arquitetural material;
- ampliar silenciosamente escopo, público, dado, automação, autoridade ou risco;
- presumir que objeto planejado existe na realidade;
- transformar estimativa em compromisso temporal;
- atribuir aceite, liberação ou transferência sem decisão competente;
- substituir o retorno ao Módulo 3 quando a decomposição revelar mudança material.

Quando houver conflito entre conveniência de execução e linha de base, a linha de base prevalece até decisão formal.

---

## 7. Instruções de uso

1. Duplique este template no dossiê `IMP-AAAA-NNN`.
2. Não preencha diretamente o arquivo-mestre.
3. Utilize o Termo de Abertura, o Plano de Implantação e a linha de base nas versões vigentes.
4. Preserve os identificadores e namespaces dos Módulos 1, 2 e 3.
5. Crie identificadores do Módulo 4 somente para objetos realmente distintos.
6. Registre `Não aplicável` apenas depois de examinar a função do campo.
7. Registre `Pendente` somente com responsável, limite e consequência.
8. Use `Não determinado` quando a informação ainda não existe e declare como será obtida.
9. Detalhe o horizonte próximo até pacotes controláveis; mantenha horizontes posteriores no nível permitido pela incerteza.
10. Não crie pacote sem saída ou condição verificável.
11. Não duplique uma entrega para representar contribuições a múltiplas capacidades; utilize relações e visões de cobertura.
12. Atualize plano, matriz, cronograma e backlog quando a estrutura vigente mudar materialmente.
13. Preserve versões substituídas e o fundamento de cada mudança.
14. Submeta qualquer alteração arquitetural ao fluxo de retorno ao Módulo 3.

### 7.1 Convenções de preenchimento

| Valor | Uso |
| --- | --- |
| `[Preencher]` | Campo obrigatório ainda não preenchido na cópia. |
| `Não aplicável — [fundamento]` | Função examinada e inaplicável ao objeto. |
| `Pendente — [responsável] — [limite]` | Definição futura já governada. |
| `Não determinado — [método de descoberta]` | Informação ainda inexistente ou insuficiente. |
| `Nenhum identificado — [data/método]` | Exame realizado sem ocorrência encontrada. |

### 7.2 Regra de concisão rastreável

Quando outra fonte oficial contiver o detalhe, registre aqui:

- identificador;
- versão;
- síntese necessária à decomposição;
- localização;
- responsável pela sincronização;
- estado ou lacuna relevante.

Copiar tabelas completas entre documentos cria concorrência de fontes e deve ser evitado.

---

## 8. Identificação da estrutura

| Campo | Registro |
| --- | --- |
| ID da estrutura | `EAI-IMP-AAAA-NNN` |
| ID da implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área ou contexto | [Preencher] |
| Classificação | Focal / funcional / sistêmica |
| Responsável pela decomposição | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Versão | [N.N] |
| Estado | [Vocabulário da seção 9] |
| Localização oficial | [Caminho] |
| Data de criação | [AAAA-MM-DD] |
| Última revisão | [AAAA-MM-DD] |
| Próxima revisão | [Evento/condição] |

### 8.1 Correspondência de identificadores

Quando houver correspondência inequívoca entre implantação e estrutura:

```text
IMP-2026-001
EAI-IMP-2026-001
```

Nova versão preserva o ID da estrutura. Uma estrutura para objeto independente pode receber outro sequencial, desde que a relação com a implantação principal permaneça explícita.

---

## 9. Estado da estrutura

Selecione uma condição vigente.

- [ ] Em elaboração
- [ ] Em revisão
- [ ] Aprovada para planejamento detalhado
- [ ] Vigente
- [ ] Vigente com condições
- [ ] Suspensa
- [ ] Substituída
- [ ] Encerrada

| Estado | Significado mínimo |
| --- | --- |
| Em elaboração | A decomposição ainda recebe nós ou relações materiais. |
| Em revisão | O conteúdo foi submetido a verificação de cobertura, coerência e responsabilidade. |
| Aprovada para planejamento detalhado | Pode alimentar cronograma, backlog e planos especializados; execução permanece não autorizada. |
| Vigente | É a referência atual da decomposição para o escopo declarado. |
| Vigente com condições | Pode ser usada dentro de condições explícitas e sem avançar objetos bloqueados. |
| Suspensa | O uso está interrompido por decisão, lacuna ou mudança. |
| Substituída | Outra versão ou estrutura assumiu sua função. |
| Encerrada | Não recebe novos movimentos, mas permanece recuperável. |

### 9.1 Estado da estrutura não é estado da execução

Uma estrutura vigente pode conter trabalho ainda não iniciado. Um pacote concluído não encerra a estrutura. Estados de execução devem ser obtidos das fontes operacionais correspondentes.

---

## 10. Documentos de entrada e precedência

### 10.1 Entradas obrigatórias

| Documento ou objeto | ID | Versão | Estado | Localização | Uso nesta estrutura |
| --- | --- | --- | --- | --- | --- |
| Transição do Módulo 3 | [ID] | [N.N] | [Estado] | [Caminho] | Delimitar o pacote recebido. |
| Linha de base arquitetural | `LB-ARQ-NNN` | [N.N] | [Estado] | [Caminho] | Fixar a configuração autorizada. |
| Matriz arquitetural | [ID] | [N.N] | [Estado] | [Caminho] | Preservar vínculos de origem. |
| Termo de Abertura | `TER-IMP-AAAA-NNN` | [N.N] | [Estado] | [Caminho] | Fixar autorização, escopo e envelope. |
| Plano de Implantação | `PLA-IMP-AAAA-NNN` | [N.N] | [Estado] | [Caminho] | Fixar estratégia e estrutura de realização. |
| Decisões e condições vigentes | [IDs] | [Versões] | [Estados] | [Caminhos] | Restringir ou orientar a decomposição. |

### 10.2 Ordem de autoridade

Em caso de divergência:

1. decisão humana válida e registrada;
2. linha de base arquitetural autorizada;
3. Termo de Abertura aprovado;
4. Plano de Implantação vigente;
5. esta estrutura analítica;
6. cronograma, backlog e planos especializados derivados.

Fonte posterior pode detalhar a anterior. Não pode contrariá-la sem mudança autorizada.

### 10.3 Divergências de entrada

| ID | Fontes divergentes | Objeto | Diferença | Contenção | Autoridade | Destino |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [ID] | [Preencher] | [Preencher] | [Nome/papel] | [Decisão/retorno] |

---

## 11. Fronteira de decomposição

### 11.1 Escopo recebido

| Elemento | Referência | Síntese | Incluído nesta estrutura? | Fundamento |
| --- | --- | --- | --- | --- |
| Resultado da implantação | [ID/seção] | [Preencher] | Sim | [Referência] |
| Capacidades | [IDs] | [Preencher] | [Sim/parcial] | [Referência] |
| Áreas, públicos ou contextos | [IDs/descrição] | [Preencher] | [Sim/parcial] | [Referência] |
| Componentes e interfaces | [IDs] | [Preencher] | [Sim/parcial] | [Referência] |
| Condições vinculantes | [IDs] | [Preencher] | [Sim/parcial] | [Referência] |

### 11.2 Exclusões e não objetivos

| ID ou referência | Exclusão | Origem | Consequência para a decomposição | Tratamento futuro |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Termo/plano/decisão] | [Preencher] | [Destino ou nenhum] |

### 11.3 Teste de pertencimento

Uma unidade pertence à estrutura quando, cumulativamente:

1. contribui para capacidade, condição, proteção ou resultado autorizado;
2. encontra-se dentro da fronteira da implantação;
3. possui saída, condição ou efeito verificável;
4. possui relação recuperável com objeto de origem;
5. demanda planejamento ou coordenação no Módulo 4.

Trabalho útil, mas fora desses critérios, deve receber destino próprio. Não deve ser absorvido apenas porque surgiu durante a decomposição.

---

## 12. Resultado e capacidades de referência

### 12.1 Resultado da implantação

> [Declarar o que a organização deverá conseguir realizar, para quem, em que contexto, dentro de quais limites e com que continuidade.]

**Fonte:** [ID/versão/seção]

### 12.2 Capacidades incluídas

| Capacidade | Declaração | Público/contexto | Limites | Critério de manifestação | Fonte |
| --- | --- | --- | --- | --- | --- |
| `CAP-ARQ-NNN` | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID/versão] |

### 12.3 Capacidades preservadas

| Capacidade existente | O que deve permanecer | Risco de ruptura | Unidades protetoras | Evidência prevista |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID/descrição] | [IDs] | [ID/tipo] |

---

## 13. Modelo lógico da estrutura

Uma única árvore não representa todas as relações da implantação. Este template utiliza três eixos complementares.

### 13.1 Eixo de resultado

```text
capacidade
  → incremento
    → entrega
```

Responde: que parcela verificável da configuração tornará a capacidade possível e que objetos a compõem?

### 13.2 Eixo de origem arquitetural

```text
linha de base
  → requisito, componente, interface ou condição
    → entrega ou pacote de preparação
```

Responde: que objeto autorizado justifica a existência da unidade de implantação?

### 13.3 Eixo de trabalho

```text
entrega ou condição
  → pacote de trabalho
    → item de backlog referenciado
```

Responde: que agrupamento controlável produz a entrega ou prepara a condição e como o trabalho entrará no fluxo?

### 13.4 Integração dos eixos

A árvore primária governa composição. As visões de cobertura e a matriz preservam relações muitos-para-muitos. A mesma entrega pode contribuir para mais de uma capacidade sem receber IDs duplicados.

---

## 14. Unidades da estrutura

| Unidade | Função | Identidade | Condição mínima |
| --- | --- | --- | --- |
| Implantação | Governar o conjunto | `IMP-AAAA-NNN` | Escopo, autoridade e linha de base. |
| Capacidade | Representar resultado organizacional | ID herdado, como `CAP-ARQ-NNN` | Manifestação, contexto e limite. |
| Componente arquitetural | Representar elemento da configuração | ID herdado, como `CMP-ARQ-NNN` | Função e interfaces reconhecíveis. |
| Condição de implantação | Delimitar pré-condição ou proteção | ID herdado ou estável da fonte | Critério e consequência. |
| Incremento | Organizar parcela verificável da configuração | `IMP-AAAA-NNN-INC-NNN` | Fronteira, critérios, responsáveis e reversibilidade. |
| Entrega | Identificar objeto produzido | `IMP-AAAA-NNN-ENT-NNN` | Finalidade, critério e integração. |
| Pacote de trabalho | Tornar planejamento controlável | `IMP-AAAA-NNN-PT-NNN` | Saída ou condição, responsável e definição de concluído. |
| Item de backlog | Atravessar o fluxo real | `IMP-AAAA-NNN-ITM-NNN` | Tipo, política de entrada e critério local. |
| Evidência | Demonstrar resultado delimitado | `IMP-AAAA-NNN-EVD-NNN` | Objeto, método, origem e integridade. |

### 14.1 Objeto herdado não recebe novo ID

Capacidade, requisito, componente, interface, controle ou condição recebidos do Módulo 3 preservam o identificador original. A estrutura acrescenta vínculos; não renumera a arquitetura.

### 14.2 Objeto de implantação recebe namespace completo

Abreviações podem ser usadas em visualização interna quando não houver colisão. O registro canônico utiliza o ID completo.

---

## 15. Árvore primária e relações complementares

### 15.1 Regra da árvore primária

Cada nó possui um único pai estrutural na árvore escolhida. Esse pai responde pela agregação do nó naquele recorte.

### 15.2 Relações complementares

Contribuições adicionais são registradas como vínculos, não como duplicações físicas.

Exemplo:

```text
IMP-2026-001-ENT-004 pertence_a IMP-2026-001-INC-001
IMP-2026-001-ENT-004 realiza CAP-ARQ-004
IMP-2026-001-ENT-004 atende_parcialmente REQ-ARQ-007
```

### 15.3 Hierarquia não transmite autorização

Se um pacote pertence a uma entrega e a entrega pertence a um incremento, a decisão sobre o incremento não autoriza automaticamente mudança material em cada pacote.

### 15.4 Hierarquia não elimina interface

Uma interface entre ramos permanece objeto explícito. Agrupamento comum não substitui contrato, dependência, responsável ou critério de integração.

---

## 16. Regras de decomposição

1. Começar pelo resultado e pelas capacidades autorizadas.
2. Preservar componentes, requisitos, interfaces, condições, critérios e riscos herdados.
3. Definir incrementos como parcelas verificáveis, não como coleções arbitrárias de tarefas.
4. Definir entregas por resultado produzido, não por área ou pessoa que trabalha.
5. Definir pacotes por saída ou condição controlável.
6. Decompor apenas até o nível necessário à responsabilização, estimativa, coordenação e verificação.
7. Manter relações transversais fora da árvore quando a duplicação criaria ambiguidade.
8. Não confundir ausência de detalhe futuro com ausência de escopo.
9. Não converter hipótese em unidade comprometida sem marcar seu estado.
10. Interromper a decomposição e escalar quando surgir mudança arquitetural material.

### 16.1 Teste de tamanho do pacote

Um pacote está em tamanho governável quando:

- possui uma saída ou condição principal;
- pode ter responsável inequívoco;
- permite reconhecer entradas e dependências;
- admite critério observável de conclusão;
- pode ser acompanhado sem virar programa interno;
- não precisa ser dividido apenas para mostrar movimento;
- não reúne resultados independentes demais para receber um único estado.

### 16.2 Sinais de detalhe insuficiente

- pacote com múltiplas saídas sem relação de integração;
- responsável genérico ou coletivo sem responsabilização inequívoca;
- critério como “concluir atividades”;
- dependências invisíveis;
- esforço ou risco impossível de estimar;
- entrega que só pode ser julgada no encerramento total;
- diferentes tipos de trabalho condensados em “implantação”.

### 16.3 Sinais de detalhe excessivo

- uma unidade por microação;
- decomposição que replica itens do backlog;
- nós que mudam apenas porque muda a pessoa;
- pacotes sem decisão, saída ou evidência própria;
- manutenção documental maior que o controle produzido;
- duplicação de objetos para cada visão ou equipe.

---

## 17. Regra de cobertura integral

A estrutura deve cobrir integralmente o escopo autorizado da realização, incluindo trabalho de produção, integração, preparação, proteção, validação, estabilização e transição que seja necessário ao resultado.

Cobertura integral não significa executar tudo de uma vez. Significa que todo objeto obrigatório possui um destino explícito:

- unidade de realização;
- pacote de preparação;
- exclusão autorizada;
- elaboração futura governada;
- lacuna;
- retorno ao Módulo 3.

### 17.1 Base de cobertura

| Objeto obrigatório | Total no escopo | Com caminho válido | Parcial | Sem caminho | Não aplicável fundamentado |
| --- | ---: | ---: | ---: | ---: | ---: |
| Capacidades | [N] | [N] | [N] | [N] | [N] |
| Requisitos | [N] | [N] | [N] | [N] | [N] |
| Componentes | [N] | [N] | [N] | [N] | [N] |
| Interfaces | [N] | [N] | [N] | [N] | [N] |
| Condições | [N] | [N] | [N] | [N] | [N] |
| Controles e proteções | [N] | [N] | [N] | [N] | [N] |

### 17.2 Indicador auxiliar de cobertura

Quando útil:

```text
cobertura_planejada = objetos obrigatórios com caminho válido / objetos obrigatórios aplicáveis
```

O indicador ajuda a localizar lacunas. Não substitui exame de materialidade: um único requisito crítico sem caminho pode bloquear o `PI-2` mesmo com cobertura percentual elevada.

---

## 18. Identificadores e vocabulário

### 18.1 Objetos próprios da implantação

| Objeto | Padrão |
| --- | --- |
| Estrutura analítica | `EAI-IMP-AAAA-NNN` |
| Projeto | `IMP-AAAA-NNN-PRJ-NNN` |
| Onda | `IMP-AAAA-NNN-OND-NNN` |
| Incremento | `IMP-AAAA-NNN-INC-NNN` |
| Entrega | `IMP-AAAA-NNN-ENT-NNN` |
| Pacote de trabalho | `IMP-AAAA-NNN-PT-NNN` |
| Item de backlog | `IMP-AAAA-NNN-ITM-NNN` |
| Evidência | `IMP-AAAA-NNN-EVD-NNN` |
| Lacuna de rastreabilidade | `IMP-AAAA-NNN-LAC-NNN` |

### 18.2 Nome dos nós

| Tipo | Forma recomendada | Exemplo genérico |
| --- | --- | --- |
| Capacidade | Verbo de capacidade + objeto + contexto | Decidir solicitações com critérios recuperáveis. |
| Incremento | Resultado verificável | Fluxo mínimo de decisão disponível para piloto. |
| Entrega | Substantivo do objeto produzido | Matriz de alçadas configurada. |
| Pacote | Verbo + objeto | Configurar regras e exceções da decisão. |

Nomes como “fase 1”, “diversos”, “ajustes” ou “time técnico” não comunicam resultado suficiente.

### 18.3 Não reutilização

ID retirado, cancelado ou substituído permanece reservado. Nova unidade recebe novo identificador quando representa objeto materialmente diferente.

---

## 19. Versionamento dos nós

| Mudança | Tratamento de identidade | Tratamento de versão |
| --- | --- | --- |
| Correção textual sem mudança semântica | Preserva ID | Incremento editorial conforme regra local. |
| Detalhamento do mesmo objeto | Preserva ID | Nova versão menor. |
| Mudança material de critério, fronteira ou saída | Avaliar novo ID ou retorno arquitetural | Nova versão controlada. |
| Divisão de pacote | Pacote anterior é substituído; novos IDs são criados | Registrar relação `decompõe_em` e histórico. |
| Combinação de pacotes | IDs anteriores permanecem recuperáveis; novo ID é criado | Registrar substituição e fundamento. |
| Cancelamento | Preserva ID | Estado cancelado e motivo. |

### 19.1 Registro de alteração do nó

| Nó | Versão anterior | Nova versão | Alteração | Fundamento | Autoridade | Efeito em fontes derivadas |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [N.N] | [N.N] | [Preencher] | [ID] | [Nome/papel] | [Cronograma/backlog/matriz/outros] |

---

## 20. Níveis de elaboração

| Nível | Conteúdo mínimo | Uso permitido |
| --- | --- | --- |
| Macro | Capacidades, incrementos candidatos e fronteiras. | Estratégia e visão do conjunto. |
| Intermediário | Entregas, relações, condições e responsáveis principais. | Coordenação e planejamento integrado. |
| Detalhado | Pacotes, critérios, dependências, evidências e riscos. | Cronograma, recursos e planos especializados. |
| Horizonte executável | Entradas confirmáveis, definição de concluído, responsáveis, interfaces e itens derivados identificados. | Submissão do objeto à prontidão do `PI-2`. |

### 20.1 Elaboração desigual é permitida

O primeiro horizonte pode estar executável enquanto ondas futuras permanecem intermediárias. A diferença deve ser visível e não pode ser interpretada como autorização implícita.

### 20.2 Registro do horizonte

| Horizonte | Objetos | Nível requerido | Nível atual | Lacunas | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [IDs] | [Nível] | [Nível] | [IDs/nenhuma] | [Nome] | [Data/gatilho] |

---

## 21. Mapa sintético da decomposição

```text
IMP-AAAA-NNN — [Título]
├── CAP-ARQ-NNN — [Capacidade]
│   ├── IMP-AAAA-NNN-INC-NNN — [Incremento]
│   │   ├── IMP-AAAA-NNN-ENT-NNN — [Entrega]
│   │   │   ├── IMP-AAAA-NNN-PT-NNN — [Pacote]
│   │   │   └── IMP-AAAA-NNN-PT-NNN — [Pacote]
│   │   └── IMP-AAAA-NNN-ENT-NNN — [Entrega]
│   └── IMP-AAAA-NNN-INC-NNN — [Incremento]
└── CAP-ARQ-NNN — [Capacidade]
    └── IMP-AAAA-NNN-INC-NNN — [Incremento]
```

O mapa é uma visão. A tabela mestra e os dicionários são registros mais precisos.

---

## 22. Tabela mestra dos nós

| Código analítico | ID canônico | Tipo | Nome | Pai estrutural | Nível | Versão | Estado de definição | Horizonte | Responsável |
| --- | --- | --- | --- | --- | ---: | --- | --- | --- | --- |
| `1` | `IMP-AAAA-NNN` | Implantação | [Nome] | N/A | 0 | [N.N] | [Estado] | [Horizonte] | [Nome] |
| `1.1` | `CAP-ARQ-NNN` | Capacidade | [Nome] | `IMP-AAAA-NNN` | 1 | [N.N] | [Estado] | [Horizonte] | [Nome] |
| `1.1.1` | `IMP-AAAA-NNN-INC-NNN` | Incremento | [Nome] | `CAP-ARQ-NNN` | 2 | [N.N] | [Estado] | [Horizonte] | [Nome] |
| `1.1.1.1` | `IMP-AAAA-NNN-ENT-NNN` | Entrega | [Nome] | `IMP-AAAA-NNN-INC-NNN` | 3 | [N.N] | [Estado] | [Horizonte] | [Nome] |
| `1.1.1.1.1` | `IMP-AAAA-NNN-PT-NNN` | Pacote | [Nome] | `IMP-AAAA-NNN-ENT-NNN` | 4 | [N.N] | [Estado] | [Horizonte] | [Nome] |

### 22.1 Código analítico e ID canônico

O código analítico mostra posição na árvore e pode mudar quando a visualização for reorganizada. O ID canônico representa identidade e permanece estável.

### 22.2 Estado de definição

Utilize:

- proposto;
- definido;
- em revisão;
- confirmado;
- condicionado;
- bloqueado;
- substituído;
- cancelado.

Esses estados descrevem a definição do nó. O estado do trabalho pertence ao backlog ou registro operacional.

---

## 23. Dicionário geral dos nós

Preencha uma ficha para cada nó material ou mantenha registro equivalente em sistema estruturado.

| Campo | Registro |
| --- | --- |
| Código analítico | [Código] |
| ID canônico | [ID] |
| Tipo | [Capacidade/incremento/entrega/pacote/outro permitido] |
| Nome | [Preencher] |
| Descrição | [Fronteira e resultado] |
| Pai estrutural | [ID] |
| Objetos de origem | [IDs e versões] |
| Relações complementares | [Relação + IDs] |
| Incluído | [Preencher] |
| Excluído | [Preencher] |
| Resultado ou saída | [Preencher] |
| Critério de conclusão | [Preencher] |
| Verificação | [Método e responsável] |
| Evidência prevista | [ID/tipo] |
| Responsável | [Nome/papel] |
| Validador ou autoridade | [Nome/papel] |
| Dependências | [IDs] |
| Interfaces | [IDs] |
| Riscos e controles | [IDs] |
| Configuração afetada | [IDs/descrição] |
| Reversibilidade ou correção | [Preencher] |
| Projeto, onda ou incremento relacionado | [IDs] |
| Nível de elaboração | [Nível] |
| Estado de definição | [Estado] |
| Observações | [Preencher] |

---

## 24. Cobertura por capacidade

| Capacidade | Incrementos | Entregas principais | Condições habilitadoras | Proteções | Critério de cobertura | Estado | Lacuna |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `CAP-ARQ-NNN` | [IDs] | [IDs] | [IDs] | [IDs] | [Preencher] | [Completa/parcial/ausente/contestada] | [ID/nenhuma] |

### 24.1 Teste de capacidade

Para cada capacidade, verificar:

- há público e contexto definidos;
- manifestações observáveis estão declaradas;
- os incrementos contêm relações suficientes para funcionar;
- entregas técnicas e humanas estão integradas;
- documentos, dados, autoridade e suporte estão contemplados;
- critérios permitem julgar uso, não apenas produção;
- condições de continuidade estão visíveis;
- risco de declarar capacidade por proxy foi tratado.

---

## 25. Cobertura de componentes, requisitos e condições

| Objeto arquitetural | Tipo | Versão | Função ou obrigação | Entregas | Pacotes | Cobertura | Fundamento | Lacuna |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Componente/requisito/condição/controle] | [N.N] | [Preencher] | [IDs] | [IDs] | [Completa/parcial/ausente/N.A.] | [ID] | [ID/nenhuma] |

### 25.1 Condição não é entrega

Uma condição pode demandar trabalho para se tornar verdadeira, mas permanece condição. O pacote prepara ou demonstra a condição; não a renomeia como entrega apenas para facilitar a árvore.

### 25.2 Objeto preservado sem mudança

Quando componente ou prática já existe e deve apenas permanecer:

- registre `preserva`;
- identifique a verificação de não ruptura;
- evite criar entrega fictícia;
- crie pacote somente se houver trabalho real de proteção, integração ou teste.

---

## 26. Preservação de interfaces

| Interface | Objetos conectados | Contrato ou passagem | Entregas dos lados | Pacote de integração | Responsável | Critério | Evidência | Risco |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `INT-ARQ-NNN` | [IDs] | [Preencher] | [IDs] | [ID] | [Nome] | [Preencher] | [ID/tipo] | [ID] |

### 26.1 Interface sem responsável

Interface crítica sem responsável, critério ou pacote de integração constitui lacuna material, mesmo que os componentes dos dois lados possuam entregas concluídas.

### 26.2 Trabalho transversal

Quando uma interface atravessar vários ramos, escolha um pai estrutural para o pacote e registre as demais relações. Não duplique o pacote em cada ramo.

---

## 27. Registro dos incrementos

| Incremento | Nome | Capacidade | Fronteira | Entregas | Contexto de validação | Critério próprio | Reversibilidade | Responsável | Estado de definição |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-INC-NNN` | [Preencher] | [IDs] | [Inclui/exclui] | [IDs] | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Estado] |

### 27.1 Ficha do incremento

| Campo | Registro |
| --- | --- |
| ID e versão | [Preencher] |
| Resultado verificável | [Preencher] |
| Capacidades realizadas | [IDs e tipo de contribuição] |
| Requisitos e condições | [IDs] |
| Componentes e interfaces | [IDs] |
| Público, ambiente e volume | [Preencher] |
| Entregas integrantes | [IDs] |
| Entregas excluídas | [IDs e motivo] |
| Dependências externas | [IDs] |
| Critérios de prontidão | [Referências] |
| Critérios de liberação | [Referências] |
| Critérios de validação e aceite | [Referências] |
| Contenção, correção e reversão | [Referências] |
| Configuração candidata afetada | [IDs] |
| Responsável pelo incremento | [Nome/papel] |
| Autoridades de `PI-3` e `PI-4` | [Nomes/papéis ou a definir] |

### 27.2 Teste de incremento útil

- [ ] Contribui para capacidade reconhecível.
- [ ] Possui fronteira própria.
- [ ] Contém relações suficientes para funcionar.
- [ ] Pode produzir evidência no contexto delimitado.
- [ ] Permite contenção ou reversão proporcional.
- [ ] Não é apenas agrupamento temporal de tarefas.
- [ ] Atualiza parte identificável da configuração.

---

## 28. Registro das entregas

| Entrega | Nome | Incremento | Origem arquitetural | Finalidade | Saída | Critério | Verificação | Evidência | Responsável | Estado de definição |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-ENT-NNN` | [Preencher] | [ID] | [IDs] | [Preencher] | [Preencher] | [Preencher] | [Método/nome] | [ID/tipo] | [Nome] | [Estado] |

### 28.1 Ficha da entrega

| Campo | Registro |
| --- | --- |
| ID e versão | [Preencher] |
| Nome orientado ao objeto | [Preencher] |
| Incremento principal | [ID] |
| Capacidades relacionadas | [IDs] |
| Requisitos atendidos | [IDs e cobertura esperada] |
| Componentes, condições e interfaces | [IDs] |
| Finalidade | [Por que existe] |
| Conteúdo incluído | [Preencher] |
| Conteúdo excluído | [Preencher] |
| Forma ou saída esperada | [Preencher] |
| Critério de conclusão | [Condições observáveis] |
| Critério de integração | [Preencher] |
| Verificação | [Método e responsável] |
| Evidências previstas | [IDs/tipos] |
| Pacotes produtores | [IDs] |
| Dependências | [IDs] |
| Riscos e controles | [IDs] |
| Responsável pela entrega | [Nome/papel] |
| Aceitador técnico ou funcional | [Nome/papel] |
| Configuração afetada | [IDs] |
| Correção ou reversão | [Preencher] |

### 28.2 Estados posteriores não são presumidos

Produzida, integrada, verificada, pronta para liberar, liberada, validada, aceita, estabilizada e transferida são condições diferentes. Esta estrutura define critérios; registros posteriores demonstram os estados.

---

## 29. Registro dos pacotes de trabalho

| Pacote | Nome | Entrega ou condição | Incremento | Saída local | Responsável | Dependências | Definição de concluído | Evidência | Nível de elaboração |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-PT-NNN` | [Preencher] | [ID] | [ID] | [Preencher] | [Nome] | [IDs] | [Preencher] | [ID/tipo] | [Nível] |

### 29.1 Dicionário do pacote

| Campo | Registro |
| --- | --- |
| ID e versão | [Preencher] |
| Código analítico | [Código] |
| Nome | [Verbo + objeto] |
| Pai estrutural | [ID] |
| Finalidade | [Preencher] |
| Justificativa arquitetural | [IDs e relações] |
| Capacidade relacionada | [IDs] |
| Incremento relacionado | [ID] |
| Entrega produzida ou condição preparada | [ID e descrição] |
| Entradas necessárias | [IDs/descrição] |
| Atividades incluídas | [Tipos ou referências] |
| Atividades excluídas | [Preencher] |
| Métodos, técnicas ou ferramentas previstos | [Preencher ou referenciar] |
| Saída local | [Preencher] |
| Definição de concluído | [Condições observáveis] |
| Verificação | [Método e responsável] |
| Evidência esperada | [ID/tipo] |
| Responsável | [Nome/papel] |
| Participantes | [Nomes/papéis] |
| Competências necessárias | [IDs/descrição] |
| Recursos necessários | [IDs/descrição] |
| Dependências | [IDs] |
| Interfaces | [IDs] |
| Riscos e controles | [IDs] |
| Premissas | [IDs] |
| Faixa de esforço ou tamanho | [Faixa e método; opcional] |
| Restrição temporal ou janela referenciada | [ID/referência; detalhe no cronograma] |
| Condições de interrupção | [Preencher] |
| Correção ou reversão | [Preencher] |
| Itens de backlog derivados | [IDs ou a criar] |
| Estado de definição | [Estado] |

### 29.2 Teste de necessidade do pacote

- [ ] Possui fundamento arquitetural ou condição de implantação identificável.
- [ ] Produz saída utilizada por entrega, integração, verificação ou decisão.
- [ ] Seu tamanho permite responsabilização e acompanhamento.
- [ ] Entradas e dependências materiais estão explícitas.
- [ ] A definição de concluído pode ser verificada.
- [ ] Não duplica outro pacote.
- [ ] Não existe apenas para representar reunião, função ou ferramenta.

---

## 30. Fronteira com atividades e backlog

Este template pode registrar tipos de atividade necessários ao entendimento do pacote. O detalhamento e o fluxo dos itens pertencem ao backlog.

### 30.1 Mapa de derivação

| Pacote | Tipo de item necessário | Item de backlog | Critério local | Fonte oficial | Estado de sincronização |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Tarefa/teste/decisão/risco/correção/outro] | [ID ou a criar] | [Preencher] | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` | [Estado] |

### 30.2 Regra de não duplicação

Descrição detalhada, prioridade, classe de serviço, fila, bloqueio e estado de fluxo permanecem no backlog. A estrutura referencia os itens e conserva sua relação com pacote, entrega e incremento.

### 30.3 Item sem pacote

Um item pode não pertencer a pacote quando representa ocorrência transversal, como risco emergente, decisão, incidente ou aprendizagem. O motivo e o vínculo com a implantação devem permanecer explícitos.

---

## 31. Critérios, verificações e evidências

| Objeto | Critério de conclusão | Tipo de julgamento | Método | Verificador | Evidência prevista | Gate relacionado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Conclusão/integração/prontidão/validação/aceite] | [Preencher] | [Nome/papel] | [ID/tipo] | [PI-N/N.A.] |

### 31.1 Qualidade do critério

Um critério adequado declara:

- objeto e versão;
- condição observável;
- contexto ou ambiente;
- limite ou tolerância;
- método de verificação;
- evidência requerida;
- responsável por verificar;
- consequência do não atendimento.

### 31.2 Evidência prevista não é evidência produzida

A estrutura declara o que deverá demonstrar o resultado. O dossiê posterior registra origem, integridade, versão, resultado e decisão associados à evidência real.

### 31.3 Critério local e critério de capacidade

Concluir pacote demonstra apenas resultado local. Concluir entrega demonstra objeto produzido conforme seu critério. Julgar capacidade exige evidência integrada no contexto de uso.

---

## 32. Responsabilidade, verificação e autoridade

| Objeto | Responsável pela realização | Participantes | Verificador | Autoridade de decisão | Responsável operacional consultado | Substituto |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/papel] | [Nomes/papéis] | [Nome/papel] | [Nome/papel] | [Nome/papel] | [Nome/papel] |

### 32.1 Responsável único, trabalho coletivo

Cada nó material possui responsável identificável pelo resultado. Várias pessoas podem participar; a participação coletiva não elimina a responsabilização pelo resultado.

### 32.2 Segregação

Quando risco, regulação ou impacto exigirem, produção, verificação, liberação e aceite devem permanecer segregados.

### 32.3 Capacidade real

Atribuição somente é válida quando a pessoa ou papel possui:

- autoridade compatível;
- competência ou suporte;
- disponibilidade;
- acesso às entradas;
- possibilidade de escalar impedimentos;
- substituição ou continuidade proporcional.

---

## 33. Dependências entre nós

| Dependente | Relação | Dependência | Objeto fornecido | Critério de disponibilidade | Responsável | Evidência | Consequência | Registro especializado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | `depende_de` / `é_condicionado_por` / `interfaceia_com` | [ID] | [Preencher] | [Preencher] | [Nome] | [ID/tipo] | [Preencher] | [ID/caminho] |

### 33.1 Dependência estrutural e precedência temporal

Esta seção registra necessidade material. A data e a relação temporal detalhadas pertencem ao cronograma.

### 33.2 Dependência externa

Dependência fora da autoridade da implantação deve declarar:

- responsável externo;
- compromisso ou ausência de compromisso;
- limite;
- evidência de disponibilidade;
- alternativa ou contingência;
- consequência para o objeto dependente.

### 33.3 Ponto único de falha

| Elemento | Dependência única | Objetos afetados | Consequência | Redundância ou contingência | Decisão |
| --- | --- | --- | --- | --- | --- |
| [Pessoa/dado/sistema/fornecedor/decisão] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [ID/pendente] |

---

## 34. Recursos e competências por pacote

| Pacote | Competências | Pessoas ou papéis | Recursos | Acesso ou autorização | Restrição de capacidade | Fonte do compromisso | Lacuna |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/descrição] | [Nomes/papéis] | [IDs/descrição] | [Preencher] | [Preencher] | [Plano/decisão] | [ID/nenhuma] |

### 34.1 Estimativa não é compromisso

Faixa de esforço ou tamanho pode apoiar decomposição e planejamento. Datas, alocações definitivas e compromissos permanecem no cronograma e no plano de recursos.

### 34.2 Competência crítica

Pacote que depende de competência ainda inexistente deve incluir preparação, apoio especializado ou condição explícita. Atribuir a responsabilidade não cria competência.

---

## 35. Riscos, controles e reversibilidade

| Nó | Risco produzido ou tratado | Controle | Limite | Sinal de interrupção | Correção | Reversão | Fonte oficial |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Registro/caminho] |

### 35.1 Risco não cria escopo silencioso

Tratamento necessário deve ser incorporado a pacote existente, novo pacote autorizado ou condição de gate. Se alterar materialmente arquitetura, retorna ao Módulo 3.

### 35.2 Reversibilidade proporcional

Nem todo pacote precisa ser reversível isoladamente. O incremento precisa possuir contenção, correção ou reversão proporcional à exposição que produzirá.

---

## 36. Trabalho humano e organizacional

A estrutura deve incluir trabalho necessário para produzir compreensão, competência, participação, autoridade e suporte. Esses elementos não são anexos da entrega técnica.

| Grupo ou papel afetado | Mudança | Capacidade humana requerida | Entrega ou condição | Pacotes | Critério | Evidência | Plano especializado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [ID] | [IDs] | [Preencher] | [ID/tipo] | [Caminho] |

### 36.1 Comunicação emitida não é compreensão

Pacote de comunicação precisa indicar resultado pretendido, público, retorno e evidência de compreensão quando material.

### 36.2 Treinamento realizado não é competência

Pacote de treinamento deve levar a demonstração de competência ou declarar a limitação da evidência disponível.

### 36.3 Participação não é formalidade

Quando pessoas afetadas precisam influenciar desenho de execução, a estrutura deve reservar unidades, decisões ou verificações que tornem essa participação possível.

---

## 37. Dimensões da configuração

Verifique se a decomposição contempla, quando aplicável:

| Dimensão | Objetos de origem | Entregas ou condições | Pacotes | Critério de integração | Lacuna |
| --- | --- | --- | --- | --- | --- |
| Processos e fluxos | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Papéis e alçadas | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Informação e dados | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Documentos e registros | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Indicadores e controles | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Tecnologia e integrações | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Inteligência artificial | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Pessoas, competência e conhecimento | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |
| Suporte e continuidade | [IDs] | [IDs] | [IDs] | [Preencher] | [ID/nenhuma] |

### 37.1 Integração entre dimensões

Uma dimensão tecnicamente pronta não constitui incremento pronto se papéis, dados, documentos, controles ou suporte necessários estiverem ausentes.

---

## 38. Verificação, testes e integração

| Objeto testado | Tipo de teste | Condições | Casos ou cenários | Resultado esperado | Pacote de preparação | Evidência | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Técnico/funcional/integração/humano/operacional/segurança/outro] | [Preencher] | [IDs/descrição] | [Preencher] | [ID] | [ID/tipo] | [Nome] |

### 38.1 Teste como trabalho explícito

Quando teste exigir ambiente, dados, preparação, execução ou análise material, esses elementos precisam aparecer em pacotes ou itens derivados. “Testar” não deve permanecer como suposição implícita na definição de concluído.

### 38.2 Evidência negativa

Falha, ausência, incerteza e cenário não executado devem poder ser registrados. A estrutura não deve pressupor que todo teste produzirá confirmação.

---

## 39. Configuração afetada

| Nó | Item de configuração desenhada | Versão de referência | Mudança ou preparação pretendida | Registro futuro da configuração | Verificação de correspondência |
| --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [N.N] | [Preencher] | `templates/15-registro-da-configuracao-implantada.md` | [Método/responsável] |

### 39.1 Planejado e existente

Esta tabela declara intenção de realização. Não comprova que o item foi instalado, integrado, utilizado ou aceito.

### 39.2 Diferença futura

Diferença observada entre referência e configuração real receberá registro próprio. A estrutura pode ser atualizada para refletir trabalho corretivo ou adaptação autorizada sem reescrever a história.

---

## 40. Reconciliação de escopo

| Elemento do termo ou plano | Unidades que o realizam | Cobertura | Exclusão ou diferença | Decisão | Ação de sincronização |
| --- | --- | --- | --- | --- | --- |
| [ID/seção] | [IDs] | [Completa/parcial/ausente] | [Preencher] | [ID/pendente] | [Preencher] |

### 40.1 Trabalho sem origem

| Nó | Justificativa declarada | Origem encontrada? | Materialidade | Tratamento | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Sim/não/parcial] | [Preencher] | [Excluir/justificar/retornar/decidir] | [Nome] | [Data/gatilho] |

### 40.2 Origem sem trabalho

| Objeto de origem | Caminho esperado | Caminho encontrado? | Efeito | Tratamento | Gate afetado |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Sim/parcial/não] | [Preencher] | [Preencher] | [PI-N] |

---

## 41. Lacunas de decomposição

| Lacuna | Caminho incompleto | Objeto afetado | Tipo | Materialidade | Tratamento | Responsável | Limite | Consequência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-LAC-NNN` | [Origem → destino] | [IDs] | [Origem/realização/interface/responsabilidade/critério/evidência/outro] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] | [Bloqueio/condição/retorno] |

### 41.1 Lacuna não é campo vazio

Campo vazio pode ser erro de preenchimento. Lacuna é ausência ou insuficiência material de objeto, relação, decisão, condição ou evidência necessária.

### 41.2 Destinos possíveis

- completar a decomposição;
- obter informação;
- criar pacote autorizado;
- aceitar condição com limite;
- excluir com fundamento;
- bloquear o objeto;
- retornar ao plano;
- retornar ao Módulo 3.

---

## 42. Órfãos

| Nó órfão | Tipo | Relação ausente | Como foi identificado | Efeito | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo] | [Pai/origem/responsável/critério/evidência] | [Método] | [Preencher] | [Preencher] | [Estado] |

### 42.1 Tipos de órfão

- pacote sem entrega ou condição;
- entrega sem incremento;
- incremento sem capacidade;
- trabalho sem origem arquitetural;
- critério sem método de verificação;
- evidência prevista sem objeto demonstrado;
- interface sem responsável;
- condição sem consequência;
- objeto obrigatório sem caminho de realização.

Órfão material impede considerar a decomposição completa.

---

## 43. Sobreposições e duplicidades

| Objetos comparados | Sobreposição | Motivo aparente | Risco | Decisão | Objeto preservado | Sincronização |
| --- | --- | --- | --- | --- | --- | --- |
| [IDs] | [Preencher] | [Preencher] | [Retrabalho/conflito/dupla contagem/outro] | [Combinar/separar/manter/excluir] | [ID] | [Fontes] |

### 43.1 Contribuição compartilhada não é duplicidade

Uma entrega que realiza duas capacidades possui relações múltiplas. Duplicidade ocorre quando dois registros pretendem representar o mesmo objeto, resultado e fronteira sem distinção material.

### 43.2 Dupla contagem

Indicadores de quantidade, custo ou progresso não devem somar o mesmo objeto por aparecer em várias visões.

---

## 44. Trabalho transversal e de integração

| Pacote transversal | Ramos atendidos | Resultado | Pai estrutural escolhido | Relações complementares | Responsável | Critério de integração |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Preencher] | [ID] | [IDs/relações] | [Nome] | [Preencher] |

### 44.1 Exemplos possíveis

- preparação de ambiente compartilhado;
- migração ou qualidade de dados;
- controle de acesso;
- comunicação transversal;
- documentação comum;
- integração entre sistemas;
- validação de interface;
- suporte de liberação;
- governança de IA;
- preparação da operação.

O exemplo não cria obrigatoriedade. A necessidade decorre da arquitetura e do plano.

---

## 45. Fornecedores e terceiros

| Nó | Fornecedor ou terceiro | Objeto fornecido | Dependência contratual | Critério de aceite | Responsável interno | Alternativa | Risco |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome] | [Preencher] | [ID/condição] | [Preencher] | [Nome] | [Preencher] | [ID] |

Responsabilidade contratada não elimina responsabilidade interna por integração, verificação, proteção e aceite.

---

## 46. Alocação em projetos, ondas e contextos

| Nó | Projeto | Onda | Incremento | Público ou unidade | Ambiente | Critério de alocação | Fonte oficial |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Plano especializado] |

### 46.1 Alocação não muda identidade

Mover pacote entre ondas ou projetos preserva seu ID quando resultado, fronteira e critério permanecem. Mudança material exige tratamento de versão ou novo objeto.

### 46.2 Onda não substitui decomposição

Agrupar entregas por período ou público não comprova que formam incremento coerente. O incremento precisa permanecer verificável por seu próprio resultado.

---

## 47. Elaboração progressiva

| Nó | Nível atual | Informação ausente | Hipótese vigente | Método de detalhamento | Responsável | Limite | Uso permitido até lá |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nível] | [Preencher] | [ID/descrição] | [Preencher] | [Nome] | [Data/gatilho] | [Preencher] |

### 47.1 Planejamento em ondas sucessivas

O detalhe aumenta conforme informação, compromisso e proximidade. Essa prática é válida quando:

- o escopo macro permanece coberto;
- incertezas estão declaradas;
- objetos futuros não são apresentados como executáveis;
- o primeiro horizonte possui detalhe e evidência suficientes;
- mudanças são sincronizadas entre fontes.

### 47.2 Limite da incerteza

Incerteza material sobre capacidade, requisito, autoridade, interface crítica ou risco não deve ser empurrada para o backlog como detalhe futuro.

---

## 48. Sincronização com o Plano de Implantação

| Elemento no plano | Fonte nesta estrutura | Versões coerentes? | Divergência | Responsável pela sincronização | Próximo evento |
| --- | --- | --- | --- | --- | --- |
| Capacidades | [Seção/IDs] | [Sim/não] | [ID/nenhuma] | [Nome] | [Evento] |
| Projetos, ondas e incrementos | [Seção/IDs] | [Sim/não] | [ID/nenhuma] | [Nome] | [Evento] |
| Entregas | [Seção/IDs] | [Sim/não] | [ID/nenhuma] | [Nome] | [Evento] |
| Dependências | [Seção/IDs] | [Sim/não] | [ID/nenhuma] | [Nome] | [Evento] |
| Preparação do `PI-2` | [Seção/IDs] | [Sim/não] | [ID/nenhuma] | [Nome] | [Evento] |

O plano mantém síntese; esta estrutura mantém detalhe da decomposição.

---

## 49. Sincronização com o Cronograma Mestre

| Nó | Marco ou atividade temporal derivada | Dependência temporal | Versão enviada | Versão no cronograma | Estado de sincronização |
| --- | --- | --- | --- | --- | --- |
| [ID] | [ID ou a criar] | [IDs] | [N.N] | [N.N] | [Sincronizado/pendente/divergente] |

### 49.1 Regra temporal

A estrutura fornece:

- nós que precisam ser planejados;
- dependências materiais;
- critérios de conclusão;
- horizonte e prioridade estratégica referenciada;
- marcos ou gates relacionados.

O cronograma define:

- sequência temporal;
- duração;
- datas e janelas;
- folgas;
- caminho crítico;
- compromissos.

---

## 50. Sincronização com Backlog e Kanban

| Pacote ou entrega | Itens derivados | Versão da origem | Critério local coerente? | Itens sem origem | Responsável | Última reconciliação |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [N.N] | [Sim/não/parcial] | [IDs/nenhum] | [Nome] | [Data] |

### 50.1 Alteração no backlog

Mudança em item de fluxo atualiza a estrutura quando altera saída, fronteira, critério, dependência ou relação do pacote. Reordenação ou estado operacional não exige nova versão da estrutura por si só.

### 50.2 Trabalho emergente

Item emergente deve ser classificado como:

- detalhamento de pacote existente;
- correção;
- risco ou impedimento;
- nova entrega;
- novo pacote;
- mudança de escopo;
- possível mudança arquitetural.

A classificação precede sua absorção como trabalho comprometido.

---

## 51. Sincronização com a Matriz de Rastreabilidade

| Objeto ou relação na estrutura | Vínculo esperado | ID do vínculo | Estado | Cobertura | Lacuna |
| --- | --- | --- | --- | --- | --- |
| [Origem → destino] | [Relação controlada] | [ID ou a criar] | [Proposto/confirmado/outro] | [Completa/parcial/N.A.] | [ID/nenhuma] |

### 51.1 Relações usuais

- capacidade `é_realizada_por` incremento;
- entrega `realiza` capacidade;
- objeto agregado `decompõe_em` unidades menores;
- pacote `produz` entrega ou evidência;
- entrega `pertence_a` incremento;
- unidade `depende_de` outra unidade;
- entrega `atende` ou `atende_parcialmente` requisito;
- objeto `é_verificado_por` ou `é_validado_por` evidência;
- unidade `configura` item da configuração.

Utilize o vocabulário controlado da Matriz de Rastreabilidade da Implantação. Não invente sinônimos recorrentes sem definição.

---

## 52. Sincronização com registros especializados

| Função | Fonte oficial | Objetos desta estrutura | Versão | Responsável | Gatilho de atualização |
| --- | --- | --- | --- | --- | --- |
| Riscos, impedimentos, dependências e mudanças | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` | [IDs] | [N.N] | [Nome] | [Evento] |
| Comunicação e engajamento | `templates/08-plano-de-comunicacao-e-engajamento.md` | [IDs] | [N.N] | [Nome] | [Evento] |
| Treinamento e capacitação | `templates/09-plano-de-treinamento-e-capacitacao.md` | [IDs] | [N.N] | [Nome] | [Evento] |
| Mudança organizacional | `templates/10-plano-de-gestao-da-mudanca-organizacional.md` | [IDs] | [N.N] | [Nome] | [Evento] |
| Piloto, ondas, virada e reversão | `templates/11-plano-de-piloto-ondas-virada-e-reversao.md` | [IDs] | [N.N] | [Nome] | [Evento] |
| Prontidão | `templates/13-verificacao-de-prontidao.md` | [IDs] | [N.N] | [Nome] | [PI-2/PI-3] |
| Validação e aceite | `templates/14-registro-de-validacao-e-aceite.md` | [IDs] | [N.N] | [Nome] | [PI-4] |
| Configuração implantada | `templates/15-registro-da-configuracao-implantada.md` | [IDs] | [N.N] | [Nome] | [Mudança/aceite] |

---

## 53. Preparação para o PI-2

### 53.1 Objeto delimitado

| Campo | Registro |
| --- | --- |
| Ocorrência prevista | [ID ou a criar] |
| Projeto, onda ou incremento | [ID] |
| Capacidades | [IDs] |
| Entregas | [IDs] |
| Pacotes | [IDs] |
| Versões | [Preencher] |
| Horizonte | [Preencher] |
| Trabalho que pode ser submetido | [IDs] |
| Trabalho que permanece fora | [IDs e motivo] |

### 53.2 Verificação da decomposição para prontidão

| Dimensão | Critério | Resultado | Evidência | Lacuna | Consequência |
| --- | --- | --- | --- | --- | --- |
| Origem | Todo trabalho material possui fundamento. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Cobertura | Toda obrigação aplicável possui caminho. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Fronteira | O objeto submetido está delimitado. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Responsabilidade | Cada resultado possui responsável capaz. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Dependências | Entradas e condições materiais estão tratadas. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Critérios | Conclusão, integração e evidência são julgáveis. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Proteções | Risco, controle e reversibilidade são proporcionais. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |
| Integração | Interfaces e trabalho transversal estão cobertos. | [Atende/parcial/não atende] | [ID/tipo] | [ID] | [Preencher] |

### 53.3 Pergunta do PI-2

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

Esta estrutura sustenta parte da resposta. A decisão depende da verificação integrada das demais condições e evidências.

---

## 54. Controle de mudanças da estrutura

| Mudança | Gatilho | Nós afetados | Classe | Dentro da alçada? | Fontes afetadas | Decisão | Responsável pela sincronização |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | [Editorial/detalhamento/executiva/arquitetural] | [Sim/não/duvidoso] | [IDs/caminhos] | [ID/pendente] | [Nome] |

### 54.1 Mudança editorial

Corrige forma sem alterar objeto, relação, fronteira, critério ou responsabilidade material.

### 54.2 Detalhamento

Acrescenta precisão ao mesmo objeto dentro do plano e da linha de base.

### 54.3 Adaptação executiva

Reorganiza a realização dentro do envelope autorizado e precisa atualizar as fontes derivadas afetadas.

### 54.4 Mudança arquitetural

Altera requisito, capacidade, componente, interface crítica, autoridade, risco, uso de dados, automação, IA, proteção, critério de aceite ou outra condição material. Exige retorno ao Módulo 3.

---

## 55. Gatilhos de retorno ao Módulo 3

| Gatilho | Objeto afetado | Descoberta da decomposição | Contenção imediata | Responsável | Registro de retorno |
| --- | --- | --- | --- | --- | --- |
| [Tipo] | [IDs] | [Preencher] | [Preencher] | [Nome] | [ID/caminho] |

Retornar quando a decomposição revelar, entre outros:

- requisito material inexistente ou incompatível;
- capacidade impossível dentro da configuração aprovada;
- componente estrutural ausente ou redundante;
- interface crítica sem solução autorizada;
- redistribuição de autoridade;
- risco não autorizado;
- uso materialmente diferente de dados, tecnologia ou IA;
- critério de aceite inadequado;
- custo ou condição de manutenção que inviabiliza a arquitetura;
- necessidade de exceder tolerância concedida.

### 55.1 Continuidade durante o retorno

Somente trabalho independente e expressamente seguro pode continuar. Objetos afetados permanecem bloqueados até decisão.

---

## 56. Participação da inteligência artificial

A IA pode apoiar:

- extração inicial de objetos da linha de base;
- sugestão de decomposição candidata;
- comparação entre versões;
- detecção de órfãos, duplicidades e lacunas;
- verificação preliminar de identificadores e relações;
- geração de visões derivadas;
- análise de cobertura;
- preparação de perguntas de revisão;
- sincronização assistida entre estrutura, cronograma, backlog e matriz.

### 56.1 Condições de uso

| Uso | Entradas autorizadas | Saída da IA | Validação humana | Registro |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs/versões] | [Candidata/alerta/síntese] | [Nome/papel e método] | [ID/caminho] |

### 56.2 Limites

A IA não pode:

- decidir que mudança arquitetural é imaterial;
- aprovar escopo ou decomposição;
- atribuir responsabilidade sem manifestação humana;
- criar fato, compromisso, competência ou evidência inexistente;
- autorizar execução ou gate;
- ocultar incerteza por preenchimento plausível;
- substituir revisão de pessoas afetadas ou especialistas.

### 56.3 Proveniência

Sugestão aceita precisa resolver para fontes autorizadas e decisão humana. Saída não confirmada permanece proposta.

---

## 57. Proporcionalidade

| Classificação | Estrutura mínima | Intensificação esperada |
| --- | --- | --- |
| Focal | Capacidade, entrega ou incremento, pacotes, origem, responsável, critério, dependência, risco e evidência. | Aumentar detalhe se houver interface crítica, IA, dado sensível, irreversibilidade ou alto impacto humano. |
| Funcional | Árvore completa, dicionários, interfaces, cobertura, dependências, sincronização e prontidão. | Ampliar governança entre áreas, integração e preparação humana. |
| Sistêmica | Múltiplas capacidades, incrementos, ondas, visões transversais, controle de configuração e revisões formais. | Segregação, validação especializada, linhas de base intermediárias e controle ampliado. |

### 57.1 Intensificadores de controle

- impacto sobre direitos, segurança ou privacidade;
- mudança de autoridade;
- automação ou IA com efeito material;
- migração crítica;
- alta interdependência;
- irreversibilidade;
- obrigação legal, regulatória ou contratual;
- público vulnerável;
- baixa capacidade de absorção;
- fornecedor único;
- continuidade operacional crítica.

Pequeno escopo não neutraliza intensificador material.

---

## 58. Versão reduzida para implantação focal

Use esta versão somente quando a classificação e os riscos permitirem combinar funções sem perder controle.

### 58.1 Identificação e origem

| Campo | Registro |
| --- | --- |
| Estrutura | `EAI-IMP-AAAA-NNN` |
| Implantação | `IMP-AAAA-NNN` |
| Linha de base | [ID/versão] |
| Termo e plano | [IDs/versões] |
| Capacidade | [ID] |
| Responsável | [Nome] |
| Classificação e fundamento | [Preencher] |

### 58.2 Estrutura focal

| Código | ID | Tipo | Resultado | Origem | Responsável | Critério | Dependência | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | `IMP-AAAA-NNN` | Implantação | [Preencher] | [ID] | [Nome] | [Preencher] | [IDs] | [ID/tipo] |
| 1.1 | [ID] | Capacidade/incremento | [Preencher] | [IDs] | [Nome] | [Preencher] | [IDs] | [ID/tipo] |
| 1.1.1 | [ID] | Entrega | [Preencher] | [IDs] | [Nome] | [Preencher] | [IDs] | [ID/tipo] |
| 1.1.1.1 | [ID] | Pacote | [Preencher] | [IDs] | [Nome] | [Preencher] | [IDs] | [ID/tipo] |

### 58.3 Controles mínimos

- [ ] Toda unidade possui origem.
- [ ] Escopo e exclusões estão claros.
- [ ] Entrega e capacidade permanecem distintas.
- [ ] Pacote possui saída e definição de concluído.
- [ ] Responsabilidade e verificação são identificáveis.
- [ ] Dependências e riscos materiais estão tratados.
- [ ] Interfaces necessárias estão cobertas.
- [ ] Trabalho humano e operacional foi examinado.
- [ ] Critérios e evidências são julgáveis.
- [ ] Mudança material retorna ao Módulo 3.
- [ ] O objeto do `PI-2` possui fronteira.

### 58.4 Limite da combinação

Combinar termo, plano e estrutura em um registro focal é permitido quando cada função permanecer identificável. A simplificação não autoriza omitir linha de base, trabalho, risco, prontidão, aceite, configuração ou transição.

---

## 59. Revisão consolidada

### 59.1 Origem e escopo

- [ ] Linha de base, termo e plano estão identificados por versão.
- [ ] A fronteira coincide com o escopo autorizado.
- [ ] Exclusões e não objetivos possuem fundamento.
- [ ] Todo trabalho material possui origem recuperável.
- [ ] Nenhum objeto arquitetural foi renumerado.

### 59.2 Estrutura e cobertura

- [ ] Capacidades possuem caminho de realização.
- [ ] Incrementos são verificáveis e não meros agrupamentos temporais.
- [ ] Entregas possuem objeto, finalidade e critério.
- [ ] Pacotes possuem saída ou condição controlável.
- [ ] Interfaces críticas permanecem explícitas.
- [ ] Trabalho transversal não foi duplicado.
- [ ] Órfãos, lacunas e sobreposições foram tratados.

### 59.3 Responsabilidade e condições

- [ ] Cada resultado possui responsável.
- [ ] Verificação e autoridade estão definidas quando aplicáveis.
- [ ] Recursos e competências críticas foram examinados.
- [ ] Dependências externas possuem responsável e consequência.
- [ ] Riscos, controles e reversibilidade são proporcionais.
- [ ] Trabalho humano, documental, informacional e operacional está incluído.

### 59.4 Integração e decisão

- [ ] Critérios permitem julgamento observável.
- [ ] Evidências previstas estão ligadas a objetos.
- [ ] Plano, cronograma, backlog e matriz possuem regra de sincronização.
- [ ] O primeiro horizonte está detalhado no nível requerido.
- [ ] Mudanças arquiteturais foram devolvidas ao Módulo 3.
- [ ] Aprovação da estrutura não foi confundida com `PI-2`.

---

## 60. Teste de reconstrução

Uma pessoa autorizada que não participou da elaboração consegue reconstruir:

1. que resultado e capacidades orientam a implantação;
2. que linha de base e condições foram recebidas;
3. qual escopo está incluído e excluído;
4. como capacidades se relacionam a incrementos;
5. que entregas compõem cada incremento;
6. que pacotes produzem cada entrega ou preparam cada condição;
7. por que cada unidade existe;
8. que interfaces e dependências precisam ser preservadas;
9. quem responde, verifica e decide;
10. que critérios e evidências serão utilizados;
11. como riscos, controles e reversibilidade aparecem na realização;
12. que trabalho humano e operacional é necessário;
13. que itens podem alimentar cronograma e backlog;
14. que lacunas ou condições permanecem;
15. que objeto pode ser submetido ao `PI-2`;
16. que descoberta exige retorno ao Módulo 3?

### 60.1 Resultado

- [ ] Reconstrução suficiente
- [ ] Reconstrução parcial
- [ ] Reconstrução insuficiente

| Lacuna de reconstrução | Efeito | Correção | Responsável | Limite |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] |

---

## 61. Antipadrões

| Antipadrão | Sinal | Consequência | Correção |
| --- | --- | --- | --- |
| Árvore por organograma | Ramos recebem nomes de equipes sem resultado. | Responsabilidade substitui lógica de realização. | Reorientar por capacidade, incremento e entrega. |
| Lista de tarefas | A estrutura começa em microações. | Origem e integração desaparecem. | Reconstruir do resultado para o trabalho. |
| Cronograma disfarçado | Nós são fases ou meses. | Tempo substitui composição. | Separar estrutura e fonte temporal. |
| Backlog totalizante | Todo registro vira tarefa. | Risco, decisão, teste e entrega perdem tipo. | Preservar unidades e classificações. |
| Capacidade por proxy | Documento produzido é chamado de capacidade. | Sucesso é declarado sem funcionamento. | Definir manifestação no contexto. |
| Entrega sem integração | Objetos são concluídos isoladamente. | Interfaces falham na liberação. | Criar critério e pacote de integração. |
| Pacote sem saída | Critério é “executar atividades”. | Conclusão não pode ser verificada. | Definir saída ou condição observável. |
| Trabalho órfão | Nó não possui origem. | Escopo cresce silenciosamente. | Justificar, decidir, excluir ou retornar. |
| Obrigação órfã | Requisito não possui caminho. | Lacuna fica invisível até validação. | Criar realização ou bloquear o objeto. |
| Duplicação transversal | Mesmo pacote aparece em vários ramos. | Dupla contagem e versões conflitantes. | Usar pai único e relações complementares. |
| Preparação humana tardia | Comunicação e treinamento aparecem depois da técnica. | Adoção é tratada como reação. | Integrar desde a decomposição. |
| Precisão fictícia | Horizontes incertos recebem detalhe arbitrário. | Plano aparenta certeza inexistente. | Elaborar progressivamente. |
| IA como decisora | Sugestão automática vira estrutura aprovada. | Autoridade e contexto desaparecem. | Exigir validação e decisão humana. |

---

## 62. Sinais de qualidade

Uma estrutura de boa qualidade apresenta:

- nomes orientados a resultados;
- escopo coberto sem trabalho sem origem;
- incrementos coerentes e verificáveis;
- entregas distintas de capacidades;
- pacotes controláveis e com definição de concluído;
- interfaces e trabalho transversal visíveis;
- relações muitos-para-muitos sem duplicação física;
- critérios observáveis e evidências previstas;
- responsabilidades compatíveis com autoridade e competência;
- incerteza e elaboração futura explicitadas;
- proporcionalidade sem perda de proteção;
- sincronização clara com fontes derivadas;
- fronteira nítida entre adaptação executiva e mudança arquitetural;
- capacidade de reconstrução por pessoa externa ao trabalho.

### 62.1 Métricas auxiliares

| Métrica | Uso | Proteção de interpretação |
| --- | --- | --- |
| Objetos obrigatórios sem caminho | Detectar lacunas. | Uma única lacuna crítica pode bloquear avanço. |
| Pacotes sem responsável | Detectar impossibilidade de compromisso. | Nome atribuído não prova disponibilidade. |
| Pacotes sem critério | Detectar trabalho não verificável. | Critério genérico conta como insuficiente. |
| Interfaces sem integração | Detectar fragmentação. | Quantidade não expressa criticidade. |
| Nós duplicados | Detectar concorrência e dupla contagem. | Relação múltipla não é duplicidade. |
| Percentual do horizonte executável | Acompanhar elaboração. | Não equivale a prontidão do `PI-2`. |

---

## 63. Exemplo aplicado — sistema editorial

O exemplo demonstra a lógica de preenchimento. Deve ser substituído por dados reais na cópia do dossiê.

### 63.1 Referências

| Objeto | Registro |
| --- | --- |
| Implantação | `IMP-2026-001` |
| Linha de base | `LB-ARQ-001 v1.0` |
| Capacidade | `CAP-ARQ-004` — acompanhar conteúdo por estado e próxima ação. |
| Requisito | `REQ-ARQ-007` — cada conteúdo ativo possui estado, responsável e próxima ação localizáveis. |
| Componente | `CMP-ARQ-011` — base editorial controlada. |
| Interface | `INT-ARQ-003` — passagem entre produção, revisão e publicação. |

### 63.2 Árvore primária

```text
IMP-2026-001 — Implantar fluxo editorial controlado
└── CAP-ARQ-004 — Acompanhar conteúdo por estado e próxima ação
    └── IMP-2026-001-INC-001 — Fluxo mínimo disponível para piloto
        ├── IMP-2026-001-ENT-001 — Base editorial configurada
        │   ├── IMP-2026-001-PT-001 — Configurar campos e estados
        │   └── IMP-2026-001-PT-002 — Configurar permissões e histórico
        ├── IMP-2026-001-ENT-002 — Responsabilidade e próxima ação definidas
        │   └── IMP-2026-001-PT-003 — Formalizar regras de atribuição
        └── IMP-2026-001-ENT-003 — Passagem de revisão verificada
            ├── IMP-2026-001-PT-004 — Integrar produção e revisão
            └── IMP-2026-001-PT-005 — Executar cenários de integração
```

### 63.3 Relações complementares

| Origem | Relação | Destino | Motivo |
| --- | --- | --- | --- |
| `IMP-2026-001-INC-001` | `realiza` | `CAP-ARQ-004` | Disponibiliza parcela verificável da capacidade. |
| `IMP-2026-001-ENT-001` | `configura` | `CMP-ARQ-011` | Materializa a base controlada. |
| `IMP-2026-001-ENT-002` | `atende_parcialmente` | `REQ-ARQ-007` | Define responsável e próxima ação; a evidência de uso ainda será produzida. |
| `IMP-2026-001-ENT-003` | `realiza` | `INT-ARQ-003` | Torna a passagem entre produção e revisão verificável. |
| `IMP-2026-001-PT-005` | `produz` | `IMP-2026-001-EVD-001` | Gera registro dos cenários de integração. |

### 63.4 Dicionário resumido de um pacote

| Campo | Registro de exemplo |
| --- | --- |
| Pacote | `IMP-2026-001-PT-005 v0.1` |
| Nome | Executar cenários de integração. |
| Entrega | `IMP-2026-001-ENT-003` |
| Finalidade | Demonstrar a passagem de produção para revisão com estado, responsável e histórico. |
| Entradas | Base configurada; regras de atribuição; perfis de acesso; casos aprovados. |
| Saída | Resultado dos cenários e não conformidades registradas. |
| Definição de concluído | Casos previstos executados; resultados preservados; falhas classificadas; evidência vinculada. |
| Responsável | Responsável de validação da integração. |
| Verificador | Representante da operação editorial. |
| Evidência | `IMP-2026-001-EVD-001`. |
| Dependências | `IMP-2026-001-PT-001`, `IMP-2026-001-PT-002` e `IMP-2026-001-PT-003`. |
| Risco | Histórico não preservar autoria da mudança. |
| Condição de interrupção | Perda de rastreabilidade ou exposição indevida de conteúdo. |

### 63.5 Limite do exemplo

Mesmo que todas as entregas sejam produzidas, a capacidade somente poderá ser validada quando pessoas autorizadas utilizarem o fluxo no contexto e os critérios definidos forem demonstrados.

---

## 64. Manifestações e aprovações

### 64.1 Responsável pela decomposição

| Campo | Registro |
| --- | --- |
| Nome e papel | [Preencher] |
| Manifestação | Concluída / concluída com condições / incompleta |
| Condições ou lacunas | [IDs/nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 64.2 Responsável pela implantação

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Manifestação | Aprova para planejamento / aprova com condições / não aprova |
| Condições | [IDs/nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 64.3 Responsável pela arquitetura

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Verificação | Preserva linha de base / requer retorno / possui ressalvas |
| Objetos examinados | [IDs/versões] |
| Ressalvas | [IDs/nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 64.4 Responsável operacional indicado

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Manifestação | Participação confirmada / condições / não confirmada |
| Condições | [IDs/nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 64.5 Aprovações especializadas

| Especialidade | Pessoa ou instância | Objeto | Manifestação | Condições | Data | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Nome] | [IDs] | [Aprova/condiciona/rejeita] | [IDs] | [Data] | [ID/link] |

### 64.6 Divergências preservadas

| Pessoa ou grupo | Divergência | Objeto | Efeito | Tratamento | Decisão relacionada |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [ID/pendente] |

### 64.7 Limite da aprovação

Aprovar a estrutura significa aceitar sua decomposição como base de planejamento. Não constitui decisão do `PI-2` nem aprovação antecipada de cronograma, recursos, liberação ou aceite.

---

## 65. Controle de versões

### 65.1 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de vigência | [AAAA-MM-DD] |
| Decisão ou aprovação | [ID] |
| Linha de base de entrada | [ID/versão] |
| Plano de referência | [ID/versão] |
| Substitui | [Versão/N.A.] |
| Localização | [Caminho] |

### 65.2 Histórico

| Versão | Data | Estado | Alteração | Motivo | Autor | Aprovador | Referência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [AAAA-MM-DD] | Em elaboração | Criação da estrutura do dossiê. | Decomposição inicial. | [Nome] | [Nome/N.A.] | [ID] |

### 65.3 Substituição

Quando nova versão entrar em vigor:

- preservar a anterior;
- registrar decisão e motivo;
- indicar nós adicionados, alterados, divididos, combinados ou retirados;
- sincronizar fontes derivadas;
- reavaliar cobertura e prontidão;
- comunicar responsáveis afetados.

---

## 66. Critérios de conclusão da estrutura

A estrutura pode ser considerada concluída para o horizonte declarado quando:

1. entradas e versões estão identificadas;
2. escopo e exclusões coincidem com a autorização;
3. capacidades e obrigações aplicáveis possuem caminho de realização;
4. incrementos possuem fronteira e resultado verificável;
5. entregas possuem origem, finalidade, critério e responsável;
6. pacotes possuem saída ou condição e definição de concluído;
7. interfaces, dependências e trabalho transversal estão visíveis;
8. riscos, controles, competências e recursos críticos foram examinados;
9. trabalho humano e operacional necessário está incluído;
10. critérios e evidências previstos permitem julgamento;
11. órfãos, lacunas, duplicidades e divergências possuem tratamento;
12. regras de sincronização estão definidas;
13. mudanças materiais receberam retorno ou decisão adequada;
14. o teste de reconstrução foi suficiente;
15. manifestações necessárias foram registradas.

### 66.1 Resultado

- [ ] Concluída e aprovada para planejamento detalhado
- [ ] Concluída com condições
- [ ] Necessita complementação
- [ ] Bloqueada
- [ ] Devolvida ao plano
- [ ] Retornada ao Módulo 3
- [ ] Suspensa

**Fundamentação:** [Preencher]

**Condições:** [IDs ou nenhuma]

**Próximo movimento permitido:** [Construir cronograma / iniciar matriz / organizar backlog / completar decomposição / retornar / outro]

---

## 67. Registro final do template

| Campo | Registro |
| --- | --- |
| Template | Estrutura Analítica da Implantação |
| Identificador do template | `templates/03-estrutura-analitica-da-implantacao.md` |
| Módulo | 4 — Implantação |
| Versão do template | 0.1 |
| Estado | Em desenvolvimento |
| Data de criação | 03/08/2026 |
| Responsabilidade metodológica | Estúdio LICHTARA |
| Documento anterior | `templates/02-plano-de-implantacao.md` |
| Documento seguinte | `templates/04-cronograma-mestre-da-implantacao.md` |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 0.1 | 03/08/2026 | Criação integral do template de decomposição da implantação. | Estúdio LICHTARA |

---

> Uma decomposição é adequada quando torna o trabalho governável sem romper as relações que fazem a capacidade existir.
