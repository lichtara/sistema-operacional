# Backlog e Quadro Kanban da Implantação

**Identificação técnica no repositório**

```yaml
id_sistema_de_fluxo: BLG-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Backlog e Quadro Kanban]"
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
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base_arquitetural:
data_de_status: AAAA-MM-DD
fuso_horario: "[Identificador IANA]"
responsavel_pela_implantacao:
responsavel_pelo_fluxo:
autoridade_da_implantacao:
custodiante_do_registro:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado_do_sistema_de_fluxo: em_configuracao
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Organização da demanda, seleção do trabalho, visualização dos estados reais, proteção da capacidade e gestão do fluxo da implantação  
**Documentos de referência:** Fundamentos da Implantação; Protocolo de Implantação; Matriz de Rastreabilidade da Implantação  
**Documentos de entrada:** Termo de Abertura, Plano de Implantação, Estrutura Analítica da Implantação e Cronograma Mestre vigentes  
**Documento seguinte na ordem de construção:** `templates/06-matriz-de-rastreabilidade-da-implantacao.md`  
**Ponto de controle relacionado:** PI-2 — Prontidão para executar, com uso continuado durante execução, liberação, validação, estabilização e transição

---

## 1. Finalidade

Este template transforma demanda autorizada e trabalho derivado da implantação em um sistema de fluxo visível, governável e recuperável.

Sua finalidade é tornar demonstrável:

- que trabalho existe e de onde ele deriva;
- que demanda ainda precisa ser qualificada;
- que itens estão aptos a ser selecionados;
- que itens foram comprometidos e por qual política;
- que trabalho está aguardando, pronto, em andamento, em verificação, bloqueado ou concluído;
- quanto trabalho simultâneo o sistema consegue sustentar sem degradar qualidade, segurança ou pessoas;
- que dependências, decisões, riscos e impedimentos afetam o fluxo;
- como urgências e exceções são reconhecidas, limitadas e autorizadas;
- que tempos compõem a travessia de cada item;
- que evidência demonstra a entrada e a saída de cada estado;
- como trabalho emergente é classificado antes de ser absorvido;
- como o fluxo permanece coerente com a Estrutura Analítica e o Cronograma Mestre;
- quando a execução deve ajustar políticas, replanejar, escalar, suspender ou retornar ao Módulo 3;
- que condições do fluxo sustentam a prontidão para o `PI-2` e as decisões posteriores.

O backlog organiza demanda. O quadro Kanban mostra o estado vigente dos itens selecionados. Nenhum dos dois substitui o plano, a decomposição, o cronograma, a rastreabilidade, os registros de controle, as evidências ou os gates.

---

## 2. Pergunta central

> Como fazer o trabalho autorizado atravessar a implantação com origem, prioridade, capacidade, limites, bloqueios, evidências e decisões visíveis, sem transformar o quadro em lista de tarefas, mecanismo de pressão ou licença para avançar?

O sistema de fluxo é suficiente quando permite reconstruir:

1. por que cada item existe;
2. a que objeto, critério ou necessidade ele responde;
3. quando e por que se tornou elegível;
4. quem decidiu sua prioridade ou classe de serviço;
5. quando foi puxado e que capacidade o recebeu;
6. por quais estados passou;
7. onde esperou e por qual motivo;
8. que bloqueio, dependência ou decisão afetou sua travessia;
9. como seu critério local foi verificado;
10. que evidência produziu;
11. que efeito teve sobre pacote, entrega, incremento, gate e configuração;
12. que aprendizagem ou mudança resultou de sua execução.

---

## 3. Posição no protocolo

Este template operacionaliza principalmente:

- a etapa 9 — decompor a arquitetura em unidades de realização;
- a etapa 11 — elaborar o plano integrado;
- a etapa 12 — construir cronograma, marcos e dependências;
- a etapa 13 — construir backlog e políticas de fluxo;
- as etapas 14 a 18 — organizar trabalho de preparação;
- a etapa 19 — verificar prontidão e decidir o `PI-2`;
- a etapa 20 — produzir, integrar e testar o incremento;
- a etapa 21 — acompanhar fluxo, riscos, impedimentos, dependências e decisões;
- a etapa 22 — aprender por PDCA e controlar mudanças;
- as etapas 23 a 31 — apoiar liberação, validação, repetição, estabilização e transição;
- a etapa 32 — destinar trabalho remanescente e aprendizagem.

O backlog nasce durante o planejamento e permanece ativo enquanto houver demanda da implantação. O quadro passa a representar execução quando existe trabalho comprometido e continua útil até que todos os itens recebam destino explícito.

O preenchimento deste documento não autoriza iniciar trabalho. Antes do `PI-2`, ele organiza preparação e demonstra se o sistema de execução é governável. Depois do `PI-2`, somente o objeto autorizado pode ser puxado para execução.

---

## 4. Distinções que este template preserva

| Conceitos | Distinção necessária |
| --- | --- |
| Backlog e quadro Kanban | Backlog mantém demanda qualificada e ordenada; quadro mostra itens atravessando estados reais. |
| Pacote de trabalho e item de backlog | Pacote é unidade de planejamento; item é unidade de fluxo. |
| Demanda e compromisso | Demanda reconhecida ainda pode aguardar; compromisso ocorre no ponto de puxada definido. |
| Prioridade e autorização | Prioridade ordena escolha; autorização permite agir dentro de limites. |
| Estado e localização visual | Estado depende de política atendida; coluna é sua representação. |
| Pronto e iniciado | Pronto possui entradas verificadas; iniciado consumiu capacidade e cruzou o ponto de compromisso. |
| Em espera e bloqueado | Espera prevista integra a política; bloqueio é impedimento que interrompe avanço esperado. |
| Bloqueado e suspenso | Bloqueio afeta item; suspensão é decisão formal sobre objeto mais amplo ou continuidade. |
| Concluído, validado e aceito | Concluído atende critério local; validado atende critério do objeto; aceito resulta de autoridade. |
| Limite de trabalho em curso e meta de produtividade | Limite protege fluxo, qualidade e pessoas; não é cota de produção. |
| Alta utilização e bom fluxo | Ocupar toda capacidade pode ampliar filas, esperas, falhas e retrabalho. |
| Classe de serviço e importância humana | Classe governa tratamento do item; não classifica o valor das pessoas. |
| Idade do item e desempenho individual | Idade revela condição do sistema; não prova culpa ou baixa produtividade. |
| Trabalho emergente e mudança autorizada | Emergência torna demanda visível; não concede escopo ou alçada. |
| Evidência registrada e resultado implantado | Evidência local sustenta uma afirmação delimitada; não prova a capacidade inteira. |

### 4.1 Backlog não é Estrutura Analítica

A Estrutura Analítica registra a decomposição necessária para produzir capacidades, entregas, incrementos e pacotes. O backlog recebe itens executáveis derivados desses objetos e demandas transversais legitimamente reconhecidas.

### 4.2 Backlog não é Cronograma Mestre

O backlog governa seleção e ordem de puxada. O Cronograma Mestre governa compromissos temporais, dependências, janelas, marcos, caminho crítico, linha de base e previsão.

### 4.3 Quadro não é relatório de status

O quadro é uma visão operacional atualizada por movimento de itens. Sínteses executivas podem ser derivadas dele, mas não devem exigir que toda informação do dossiê seja copiada para cartões.

### 4.4 Item não é pessoa

O sistema acompanha trabalho. Não deve transformar pessoas em unidades de produção, expor comparações descontextualizadas ou usar indicadores de fluxo como medida automática de desempenho individual.

### 4.5 Movimento não é progresso material

Mover um cartão demonstra alteração de estado apenas quando a política da coluna foi atendida. Movimento visual sem mudança factual é distorção do registro.

### 4.6 Conclusão local não é gate

Um item pode estar concluído e o incremento permanecer não integrado, não validado, não liberado ou não aceito. Gates continuam externos ao quadro e exigem decisão humana registrada.

---

## 5. Natureza do documento

Este template é simultaneamente:

- **catálogo de demanda**, porque mantém itens reconhecidos e sua origem;
- **instrumento de seleção**, porque registra elegibilidade, ordem e classes de serviço;
- **sistema puxado**, porque limita início à capacidade disponível e às políticas;
- **representação de estado**, porque mostra a travessia real dos itens;
- **mecanismo de coordenação**, porque torna bloqueios, dependências e decisões visíveis;
- **fonte de fatos de fluxo**, porque preserva eventos, tempos e evidências;
- **objeto versionado**, porque políticas, limites e estrutura do quadro precisam de histórico;
- **entrada de aprendizagem**, porque padrões de espera, retrabalho e sobrecarga informam ajustes.

Ele não é:

- substituto do dossiê;
- agenda de pessoas;
- lista indiferenciada de tarefas;
- cronograma oculto;
- sistema de vigilância;
- ranking de produtividade;
- aprovação automática;
- registro completo de risco, mudança, validação ou aceite;
- autorização para redesenhar a arquitetura;
- depósito indefinido de ideias sem destino.

---

## 6. Autoridade e limites

### 6.1 O sistema de fluxo pode

- qualificar e ordenar demanda dentro das políticas aprovadas;
- declarar que um item atende ou não à política de entrada de um estado;
- limitar novo trabalho quando a capacidade está ocupada;
- revelar bloqueios, esperas, retrabalho e envelhecimento;
- puxar item elegível depois da autorização aplicável;
- reordenar itens não comprometidos dentro da alçada;
- redistribuir trabalho dentro das responsabilidades autorizadas;
- recomendar escalonamento, contenção, correção ou replanejamento;
- produzir dados para previsão e aprendizagem;
- registrar trabalho emergente antes de decidir seu destino.

### 6.2 O sistema de fluxo não pode

- criar escopo apenas porque um cartão foi aberto;
- considerar um item autorizado apenas porque está priorizado;
- iniciar execução antes do `PI-2` aplicável;
- ultrapassar um gate por movimento de coluna;
- reduzir critério de conclusão para melhorar indicador;
- alterar requisito, componente, interface, alçada ou controle material;
- aceitar risco ou dependência fora da alçada;
- mudar a linha de base temporal;
- declarar entrega validada ou configuração aceita sem fonte competente;
- atribuir culpa por bloqueio sem análise contextual;
- ocultar trabalho, espera ou retrabalho para preservar aparência de desempenho;
- conceder à IA autoridade sobre prioridade material, exceção, liberação ou aceite.

### 6.3 Autonomia operacional

| Ação | Pode ocorrer pela política do fluxo? | Condição | Registro |
| --- | --- | --- | --- |
| Detalhar item de pacote vigente | Sim | Não altera saída, critério ou fronteira. | Histórico do item |
| Reordenar item não comprometido | Sim, dentro da alçada | Preserva dependências, janela e prioridade superior. | Registro de ordenação |
| Puxar item elegível | Sim, após autorização aplicável | Há capacidade, política atendida e responsável. | Evento de compromisso |
| Interromper nova entrada por limite | Sim | Limite foi atingido ou segurança exige contenção. | Quadro e cadência |
| Exceder limite de trabalho em curso | Somente por exceção | Motivo, autoridade, prazo e retorno ao limite. | Registro de exceção |
| Alterar critério local | Condicionado | Não reduz critério herdado nem muda objeto. | Versão e fundamento |
| Criar novo pacote ou entrega | Não pelo quadro sozinho | Requer atualização da Estrutura Analítica e análise de escopo. | Decisão e sincronização |
| Mudar arquitetura | Não | Retorno ao Módulo 3. | Registro de mudança |

---

## 7. Instruções de uso

1. Duplique este template no dossiê da implantação.
2. Identifique documentos de entrada, versões e precedência.
3. Defina o escopo do sistema de fluxo e os contextos que serão coordenados.
4. Estabeleça tipos de item e identificadores canônicos.
5. Configure políticas de entrada e saída antes de movimentar itens.
6. Defina limites de trabalho em curso com base em capacidade real.
7. Configure classes de serviço somente quando houver necessidade demonstrável.
8. Registre demanda e qualifique sua origem.
9. Separe itens não qualificados, elegíveis, comprometidos e concluídos.
10. Realize reposição pela cadência e autoridade definidas.
11. Puxe trabalho apenas quando existir capacidade e autorização.
12. Atualize o estado no momento do fato ou na latência permitida.
13. Registre bloqueio sem retirar o item de sua posição factual.
14. Reconcile quadro, cronograma, estrutura e registros especializados.
15. Preserve eventos, exceções, decisões e versões.
16. Revise métricas como sinais do sistema, nunca como julgamento automático de pessoas.
17. Ao encerrar, destine todos os itens abertos, transferidos, cancelados ou arquivados.

### 7.1 Convenções de preenchimento

- `[Preencher]` — informação requerida ainda não registrada;
- `[Selecionar]` — escolher valor do vocabulário indicado;
- `[ID]` — utilizar identificador canônico completo;
- `[Nome/papel]` — identificar pessoa e função exercida;
- `[Data/hora]` — utilizar `AAAA-MM-DDThh:mm` com fuso quando o tempo material exigir;
- `[Período]` — declarar unidade e início do cômputo;
- `[Fonte]` — registrar caminho, link, ID ou sistema verificável;
- `N.A.` — não aplicável, com justificativa quando material;
- `Não determinado` — informação insuficiente, com ação para determiná-la;
- `Nenhum` — verificação realizada e ausência confirmada.

### 7.2 Regra de concisão rastreável

O cartão pode manter somente o necessário para orientar o fluxo, desde que referencie a fonte completa. Não copie requisitos, decisões, riscos ou evidências extensas quando um ID e um resumo suficiente preservarem a relação.

### 7.3 Uso digital ou documental

O sistema pode ser implementado em ferramenta digital, banco de dados, planilha ou documento. A tecnologia escolhida deve permitir:

- identidade estável;
- políticas visíveis;
- histórico de estado;
- controle de acesso;
- exportação recuperável;
- relacionamento com fontes oficiais;
- correção sem apagamento indevido;
- uso acessível pelas pessoas responsáveis.

O recurso visual da ferramenta não substitui os campos e controles deste contrato.

---

## 8. Identificação do sistema de fluxo

| Campo | Registro |
| --- | --- |
| ID do sistema de fluxo | `BLG-IMP-AAAA-NNN` |
| Implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização/contexto | [Preencher] |
| Termo | [ID/versão] |
| Plano | [ID/versão] |
| Estrutura Analítica | [ID/versão] |
| Cronograma Mestre | [ID/versão] |
| Linha de base arquitetural | [ID/versão] |
| Escopo do fluxo | [Implantação/projeto/onda/incremento/outro] |
| Ferramenta ou formato | [Preencher] |
| Localização oficial | [Caminho/link] |
| Responsável pelo fluxo | [Nome/papel] |
| Responsável pela implantação | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Data de status | [AAAA-MM-DD] |
| Fuso horário | [Identificador IANA] |
| Versão/estado | [N.N/estado] |
| Sensibilidade | [Pública/interna/confidencial/sensível] |

### 8.1 Contextos coordenados

| ID do contexto | Tipo | Objeto | Quadro próprio? | Política comum | Responsável | Relação com o sistema mestre |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | Projeto / onda / incremento / frente / equipe | [ID] | [Sim/não] | [ID/versão] | [Nome] | [Consolida/deriva/referencia] |

Um quadro separado deve existir apenas quando escala, acesso, cadência ou fluxo materialmente distinto justificar a divisão. Fragmentação sem regra de consolidação torna o trabalho invisível.

---

## 9. Estado do sistema de fluxo

Utilize um estado por vez:

| Estado | Significado | Entrada | Saída |
| --- | --- | --- | --- |
| `em_configuracao` | Políticas, fontes e estrutura estão sendo definidas. | Dossiê aberto e responsáveis indicados. | Configuração verificável. |
| `configurado` | Sistema está definido, sem reposição operacional concluída. | Políticas e limites aprovados. | Primeira reposição ou reconfiguração. |
| `ativo_para_preparacao` | Organiza trabalho preparatório anterior ao `PI-2`. | Escopo de preparação autorizado. | `PI-2` ou suspensão. |
| `ativo_para_execucao` | Governa trabalho autorizado em execução. | `PI-2` aplicável decidido. | Suspensão, transição ou encerramento. |
| `contido` | Nova puxada foi limitada por condição explícita. | Risco, sobrecarga, incidente ou decisão. | Condição tratada e retomada autorizada. |
| `suspenso` | Continuidade do sistema ou objeto foi formalmente interrompida. | Decisão de suspensão. | Retomada, cancelamento ou encerramento. |
| `em_transicao` | Itens e responsabilidades estão sendo destinados à operação. | Preparação do `PI-5`. | Aceite ou retorno. |
| `encerrado` | Itens receberam destino e fonte foi congelada para memória. | Critérios de encerramento atendidos. | Reabertura formal, se necessária. |
| `cancelado` | Uso foi encerrado antes da conclusão prevista. | Decisão competente. | Reabertura ou arquivo. |
| `substituido` | Outra fonte passou a governar o fluxo. | Nova fonte e decisão identificadas. | Não aplicável. |

### 9.1 Estado do sistema não é estado dos itens

Um sistema `ativo_para_execucao` pode conter itens não qualificados, prontos, bloqueados ou concluídos. O estado global informa a condição de uso da fonte; o estado de cada item informa sua posição factual.

---

## 10. Documentos de entrada e precedência

### 10.1 Entradas obrigatórias

| Entrada | ID/versão | Função recebida | Estado de acesso | Lacuna ou divergência | Tratamento |
| --- | --- | --- | --- | --- | --- |
| Termo de Abertura | [ID/versão] | Limites, autoridade e resultado. | [Estado] | [ID/nenhuma] | [Preencher] |
| Plano de Implantação | [ID/versão] | Estratégia, governança e integração. | [Estado] | [ID/nenhuma] | [Preencher] |
| Estrutura Analítica | [ID/versão] | Pacotes, entregas, incrementos e critérios. | [Estado] | [ID/nenhuma] | [Preencher] |
| Cronograma Mestre | [ID/versão] | Marcos, janelas, dependências e compromissos. | [Estado] | [ID/nenhuma] | [Preencher] |
| Matriz estrutural de rastreabilidade | [ID/versão] | Vocabulário e vínculos esperados. | [Estado] | [ID/nenhuma] | [Preencher] |
| Decisão do `PI-1` | [ID/data] | Autoriza abertura delimitada. | [Estado] | [ID/nenhuma] | [Preencher] |
| Decisão do `PI-2`, quando existente | [ID/data/objeto] | Autoriza execução delimitada. | [Estado] | [ID/nenhuma] | [Preencher] |

### 10.2 Ordem de autoridade

Quando houver divergência:

1. princípios, decisões e linhas de base autorizadas prevalecem sobre representações derivadas;
2. a Estrutura Analítica prevalece para composição, saída e critério de pacote;
3. o Cronograma Mestre prevalece para linha de base temporal, janela, marco e previsão;
4. este sistema prevalece para demanda qualificada, prioridade operacional, compromisso e estado atual do item;
5. registros especializados prevalecem para risco, impedimento, mudança, validação, aceite e configuração;
6. a matriz preserva os vínculos canônicos entre objetos e fontes.

### 10.3 Divergências de entrada

| ID | Fontes divergentes | Objeto | Divergência | Materialidade | Fonte aplicável | Ação | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [ID] | [Preencher] | [Editorial/executiva/arquitetural] | [Fonte/regra] | [Preencher] | [Nome] | [Data/condição] |

O quadro não deve resolver divergência material apenas selecionando o valor mais conveniente.

---

## 11. Modelo operacional integrado

O sistema utiliza cinco zonas lógicas:

```text
demanda reconhecida
  -> demanda qualificada
    -> item elegível
      -> item comprometido em fluxo
        -> item concluído com destino
```

| Zona | Pergunta | Fonte principal | Pode consumir limite de trabalho em curso? |
| --- | --- | --- | --- |
| Reconhecida | Há uma necessidade que merece registro? | Caixa de entrada | Não |
| Qualificada | Origem, tipo, objeto e consequência são compreensíveis? | Backlog | Não |
| Elegível | Entradas e critérios permitem seleção? | Fila pronta | Não, salvo política explícita de preparação |
| Comprometida | O item foi puxado por capacidade autorizada? | Quadro Kanban | Sim |
| Concluída | O critério local foi atendido e o destino registrado? | Quadro/histórico/evidência | Não |

### 11.1 Uma fonte, múltiplas visões

Backlog, fila pronta, quadro por estado, visão de bloqueios, visão por classe e histórico podem ser projeções da mesma fonte. Quando ferramentas distintas forem inevitáveis, identifique a fonte de cada fato e a cadência de sincronização.

### 11.2 Ponto de compromisso

O ponto de compromisso é o evento em que o sistema assume que o item consumirá capacidade para atravessar o fluxo definido. Deve ser identificado antes do uso.

| Campo | Registro |
| --- | --- |
| Estado anterior | [Elegível/pronto/outro] |
| Estado posterior | [Em andamento/selecionado/outro] |
| Evento de compromisso | [Puxada/aceite da equipe/alocação/outro] |
| Condições | [Política] |
| Autoridade ou regra | [Nome/papel/política] |
| Início do tempo de ciclo | [Evento] |
| Evidência | [Log/registro] |

---

## 12. Escopo e fronteira do fluxo

### 12.1 Objetos incluídos

| Tipo de objeto | IDs ou critério | Motivo de inclusão | Período/onda | Responsável | Observação |
| --- | --- | --- | --- | --- | --- |
| [Projeto/onda/incremento/pacote/entrega/condição] | [IDs] | [Preencher] | [Preencher] | [Nome] | [Preencher] |

### 12.2 Objetos excluídos

| Objeto | Motivo | Fonte/autoridade | Destino | Risco da exclusão | Revisão |
| --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [Preencher] | [ID/nome] | [Outro fluxo/futuro/operação/M3/arquivado] | [Preencher] | [Data/condição] |

### 12.3 Teste de pertencimento

Antes de registrar um item, responda:

1. Ele pertence à implantação identificada?
2. Sua origem é arquitetural, executiva, corretiva, decisória ou de governança reconhecível?
3. O sistema possui autoridade para tratá-lo?
4. Existe outro sistema de fluxo que deva governá-lo?
5. Sua inclusão altera escopo, capacidade, interface ou risco material?

Item fora da fronteira recebe destino. Não deve permanecer indefinidamente no backlog apenas porque foi lembrado durante a implantação.

---

## 13. Unidade de fluxo e tipos de item

Cada item recebe ID `IMP-AAAA-NNN-ITM-NNN` e um tipo explícito.

| Tipo | Objeto representado | Origem mínima | Critério local típico | Registro especializado relacionado |
| --- | --- | --- | --- | --- |
| `atividade` | Ação delimitada necessária a pacote ou condição. | Pacote/plano. | Saída ou condição produzida. | EAI/cronograma |
| `entrega` | Objeto produzido que atravessa o fluxo como unidade. | Entrega identificada. | Especificação local atendida. | EAI/matriz |
| `teste` | Execução de verificação definida. | Critério e objeto. | Resultado e evidência registrados. | Validação/prontidão |
| `correcao` | Trabalho para restaurar critério ou desenho aprovado. | Falha/desvio/evidência. | Condição restaurada. | Controle/validação |
| `decisao` | Preparação ou obtenção de decisão necessária. | Questão, autoridade e limite. | Decisão registrada ou destino formal. | Registro de decisão |
| `risco` | Ação delimitada de resposta a evento incerto. | Risco identificado. | Resposta executada ou condição atualizada. | Registro integrado |
| `impedimento` | Trabalho para remover condição que bloqueia. | Bloqueio e itens afetados. | Fluxo restabelecido ou decisão tomada. | Registro integrado |
| `dependencia` | Trabalho para obter ou confirmar condição externa. | Objeto dependente. | Condição satisfeita, substituída ou escalada. | Cronograma/registro integrado |
| `pendencia` | Questão reconhecida com tratamento futuro delimitado. | Fonte e consequência. | Resolvida, convertida ou destinada. | Fonte pertinente |
| `preparacao` | Condição humana, técnica ou operacional anterior à exposição. | Plano/critério de prontidão. | Condição demonstrada. | Planos especializados |
| `mudanca` | Análise ou implementação de mudança autorizada. | Solicitação e decisão. | Mudança aplicada e fontes sincronizadas. | Controle de mudança |
| `aprendizagem` | Investigação ou ação derivada de evidência. | PDCA/retrospectiva. | Conhecimento verificado e destinado. | Registro PDCA |

### 13.1 Tipo não substitui relação

Um item `risco` não é o risco inteiro; representa trabalho sobre ele. Um item `decisao` não é a decisão; representa sua preparação ou obtenção. O objeto completo permanece na fonte especializada.

### 13.2 Itens compostos

Evite itens que misturem produção, decisão, validação e liberação. Quando essas partes atravessam políticas ou autoridades diferentes, devem ser separadas e relacionadas.

---

## 14. Identificadores, versão e não reutilização

| Objeto | Padrão |
| --- | --- |
| Sistema de fluxo | `BLG-IMP-AAAA-NNN` |
| Item de backlog | `IMP-AAAA-NNN-ITM-NNN` |
| Política de fluxo | `IMP-AAAA-NNN-PFL-NNN` |
| Exceção de fluxo | `IMP-AAAA-NNN-EXF-NNN` |
| Evento de fluxo | `IMP-AAAA-NNN-EFL-NNN` |
| Classe de serviço local | `IMP-AAAA-NNN-CLS-NNN` |
| Limite de trabalho em curso | `IMP-AAAA-NNN-LTC-NNN` |
| Expectativa de nível de serviço | `IMP-AAAA-NNN-ENS-NNN` |

### 14.1 Não reutilização

ID encerrado, cancelado, dividido ou substituído não deve ser atribuído a outro objeto. A relação entre itens anteriores e posteriores deve ser registrada.

### 14.2 Alteração do item

| Tipo de alteração | Exige nova versão do item? | Exige novo item? | Tratamento |
| --- | --- | --- | --- |
| Correção editorial | Não, se histórico do sistema for suficiente. | Não | Corrigir com autoria e data. |
| Detalhamento sem mudar objeto | Conforme ferramenta. | Não | Preservar critério e origem. |
| Mudança material do critério ou saída | Sim | Avaliar | Atualizar fontes e autoridade. |
| Divisão em itens menores | Não para o item de origem congelado. | Sim | Relacionar `divide_se_em`. |
| Combinação de itens | Não para itens de origem encerrados. | Sim | Relacionar `consolida`. |
| Novo objeto ou nova entrega | Não aplicável. | Sim | Atualizar EAI e escopo. |

---

## 15. Registro mestre do item

| Campo | Registro |
| --- | --- |
| ID | `IMP-AAAA-NNN-ITM-NNN` |
| Título orientado a resultado | [Verbo + objeto + condição] |
| Tipo | [Vocabulário da seção 13] |
| Descrição | [Preencher] |
| Origem principal | [ID/tipo] |
| Outras origens | [IDs/nenhuma] |
| Pacote de trabalho | [ID/N.A. justificado] |
| Entrega | [ID/N.A.] |
| Incremento | [ID/N.A.] |
| Capacidade | [ID/N.A.] |
| Projeto/onda/contexto | [IDs] |
| Critério local de conclusão | [Preencher] |
| Método de verificação | [Preencher] |
| Evidência esperada | [ID/tipo] |
| Responsável atual | [Nome/papel] |
| Participantes | [Nomes/papéis] |
| Prioridade | [Valor e fundamento] |
| Classe de serviço | [ID/nome] |
| Estado atual | [Vocabulário] |
| Posição/fila | [Preencher] |
| Dependências | [IDs/nenhuma] |
| Bloqueio atual | [ID/nenhum] |
| Risco associado | [IDs/nenhum] |
| Sensibilidade | [Classificação] |
| Gate relacionado | [ID/PI-N/N.A.] |
| Janela ou compromisso | [ID/data/N.A.] |
| Estimativa ou tamanho | [Método/valor/faixa] |
| Data de entrada | [Data/hora] |
| Data de elegibilidade | [Data/hora/NA] |
| Data de compromisso | [Data/hora/NA] |
| Data de conclusão | [Data/hora/NA] |
| Última movimentação | [Data/hora] |
| Próxima ação | [Ação, responsável e limite] |
| Fonte oficial | [Caminho/link] |
| Versão | [N.N] |

### 15.1 Qualidade do título

O título deve permitir compreender o resultado local sem abrir o cartão. Prefira `Validar acesso do grupo editorial no ambiente piloto` a `Acessos`.

### 15.2 Campo vazio não é estado

Ausência de responsável, origem, critério ou dependência não deve ser interpretada como “a definir depois” sem que a lacuna possua tratamento. O item permanece não elegível enquanto informação material faltar.

---

## 16. Origem, justificativa e rastreabilidade

Todo item material deve derivar de pelo menos uma origem reconhecida:

- capacidade, requisito, componente ou condição arquitetural;
- entrega, incremento ou pacote de trabalho;
- risco, impedimento, dependência ou restrição;
- decisão ou condição de gate;
- evidência, falha, diferença ou validação;
- obrigação de governança da implantação;
- ciclo PDCA autorizado;
- trabalho de transição ou encerramento.

| Item | Origem | Relação | Versão da origem | Fundamento | Cobertura na matriz | Lacuna |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Deriva de/trata/verifica/corrige/prepara/outro] | [N.N] | [Preencher] | [ID/pendente] | [ID/nenhuma] |

### 16.1 Trabalho administrativo

Coordenação, documentação, reunião, aquisição ou manutenção de ferramenta pode ser necessária. Sua origem deve ser uma necessidade de governança, decisão, evidência ou coordenação identificável. A atividade não existe apenas porque o método a nomeia.

### 16.2 Trabalho sem origem

Item sem origem permanece `em_qualificacao`. Se a investigação revelar novo escopo, novo pacote ou mudança material, aplique a rota de mudança antes de priorizá-lo.

---

## 17. Canais de entrada de demanda

| Canal | Demandas permitidas | Produtor | Informação mínima | Triagem | Prazo de resposta | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| Decomposição planejada | Itens derivados de pacotes. | Responsável pela EAI | Origem, critério, contexto. | [Papel] | [Período] | [Fonte] |
| Execução | Correção, impedimento, dependência, dúvida. | Equipe autorizada | Objeto, fato e efeito. | [Papel] | [Período] | [Fonte] |
| Validação | Defeito, lacuna, evidência negativa. | Verificador | Critério, resultado e evidência. | [Papel] | [Período] | [Fonte] |
| Governança | Decisão, condição, ação de gate. | Autoridade/fórum | Objeto, limite e autoridade. | [Papel] | [Período] | [Fonte] |
| Pessoas afetadas | Impacto, objeção, acessibilidade, risco humano. | Canal protegido | Contexto e tratamento de identidade. | [Papel] | [Período] | [Fonte segura] |
| Fornecedor/externo | Dependência, entrega, falha ou mudança. | Parte identificada | Contrato, objeto e responsável. | [Papel] | [Período] | [Fonte] |
| IA ou automação | Sinal, inconsistência ou sugestão. | Sistema identificado | Proveniência, versão e critério. | Humana | [Período] | [Log] |

### 17.1 Caixa de entrada não é backlog comprometido

Registrar uma demanda protege sua visibilidade. Não significa concordar com ela, priorizá-la ou prometer execução.

### 17.2 Canal seguro

Demandas que contenham informação pessoal, objeção sensível, incidente, conflito ou risco ético podem exigir acesso restrito. O quadro compartilhado deve exibir somente o necessário para coordenar a resposta.

---

## 18. Triagem e qualificação

| Pergunta | Resultado possível | Consequência |
| --- | --- | --- |
| A demanda pertence à implantação? | Sim / não / incerto | Qualificar, destinar ou investigar. |
| O objeto já existe? | Sim / não / duplicidade possível | Relacionar, criar rota ou consolidar. |
| A origem é reconstruível? | Sim / parcial / não | Tornar elegível ou manter em qualificação. |
| O tipo está correto? | Sim / corrigir | Aplicar política adequada. |
| Há risco, bloqueio ou urgência? | Sim / não | Registrar e avaliar classe/resposta. |
| Exige nova entrega ou pacote? | Sim / não / incerto | Atualizar EAI antes do compromisso. |
| Pode alterar arquitetura? | Sim / não / incerto | Conter e avaliar retorno ao Módulo 3. |
| Há autoridade para tratar? | Sim / não | Prosseguir ou escalar. |
| Informação sensível está protegida? | Sim / não | Restringir antes de compartilhar. |

### 18.1 Resultado da triagem

| Demanda/ID provisório | Resultado | Item criado | Duplicidade relacionada | Destino | Responsável | Data | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Aceita / consolidada / devolvida / destinada / rejeitada / requer análise | [ID/NA] | [ID/nenhuma] | [Fonte/contexto] | [Nome] | [Data] | [ID/link] |

Rejeição deve registrar fundamento. A visibilidade do pedido original pode ser necessária para reconstruir decisões e evitar reapresentação sem contexto.

---

## 19. Política de elegibilidade

Um item torna-se elegível para a fila pronta quando:

- possui ID, tipo e título compreensível;
- pertence ao escopo autorizado ou à preparação permitida;
- possui origem reconstruível;
- referencia pacote ou justifica por que não se aplica;
- declara critério local observável;
- possui entradas e dependências conhecidas;
- tem responsável possível e competência acessível;
- contém estimativa suficiente para a política utilizada;
- possui riscos e sensibilidades visíveis;
- respeita janela, gate e autorização aplicáveis;
- pode atravessar o fluxo sem depender de decisão material não reconhecida;
- não oculta possível mudança arquitetural.

### 19.1 Checklist de elegibilidade

| Critério | Estado | Evidência | Lacuna | Responsável | Limite |
| --- | --- | --- | --- | --- | --- |
| Identidade e tipo | [Atendido/parcial/não] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Origem e pertencimento | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Critério de conclusão | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Entradas e dependências | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Responsabilidade e competência | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Risco, dados e segurança | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |
| Autorização aplicável | [Estado] | [Fonte] | [ID/nenhuma] | [Nome] | [Data] |

### 19.2 Elegível não significa comprometido

Elegibilidade indica que o item pode ser selecionado. Puxada depende de prioridade, capacidade, dependências, classe de serviço e autorização no momento do compromisso.

---

## 20. Critério local de conclusão

Todo item deve declarar uma condição observável que encerra seu trabalho local.

| Elemento | Registro |
| --- | --- |
| Objeto e versão | [ID/versão] |
| Condição observável | [Preencher] |
| Contexto ou ambiente | [Preencher] |
| Limite ou tolerância | [Preencher] |
| Método de verificação | [Preencher] |
| Evidência requerida | [ID/tipo] |
| Verificador | [Nome/papel] |
| Consequência do não atendimento | [Corrigir/bloquear/reclassificar/escalar/outro] |

### 20.1 Distinção entre níveis de conclusão

| Nível | Afirmação permitida | Fonte competente |
| --- | --- | --- |
| Item concluído | Critério local do item foi atendido. | Quadro/evidência local |
| Pacote concluído | Saída e definição de concluído do pacote foram atendidas. | EAI/verificação |
| Entrega concluída | Especificação e integração aplicáveis foram atendidas. | Registro de validação |
| Incremento pronto para liberar | Evidências de prontidão sustentam submissão ao `PI-3`. | Verificação/gate |
| Capacidade validada | Resultado funciona no contexto e critérios definidos. | Validação competente |
| Configuração aceita | Autoridade aceitou a configuração e condições. | `PI-4`/registro de aceite |

### 20.2 Critério reduzido durante execução

Reduzir o critério para encerrar item exige avaliar efeito sobre pacote, entrega, risco, cronograma e arquitetura. O item não pode ser marcado como concluído segundo uma definição substituída silenciosamente.

---

## 21. Granularidade e divisão dos itens

Um item deve ser pequeno o suficiente para atravessar o fluxo de modo observável e grande o suficiente para produzir resultado local significativo.

### 21.1 Sinais de item grande demais

- permanece vários períodos sem mudança factual verificável;
- contém responsáveis ou competências independentes;
- mistura produção, integração, decisão e validação;
- possui múltiplos critérios não relacionados;
- bloqueio de uma parte paralisa visualmente tudo;
- só pode ser estimado como intervalo excessivamente amplo;
- atravessa mais de uma ocorrência de gate sem necessidade.

### 21.2 Sinais de item pequeno demais

- não produz saída ou condição identificável;
- representa gesto administrativo sem valor de coordenação;
- exige movimentação maior que o trabalho;
- fragmenta um critério indivisível;
- aumenta contagem sem ampliar visibilidade;
- perde a relação com pacote ou resultado.

### 21.3 Registro de divisão ou combinação

| Item de origem | Ação | Itens resultantes | Critério preservado | Motivo | Efeito temporal | Autoridade | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Dividir / combinar | [IDs] | [Preencher] | [Preencher] | [Preencher] | [Nome/política] | [Data] |

---

## 22. Relações entre itens

| Relação | Significado | Regra |
| --- | --- | --- |
| `deriva_de` | Item nasce de pacote, entrega, condição ou decisão. | Origem obrigatória. |
| `depende_de` | Avanço requer outro item, objeto ou evento. | Responsável e limite. |
| `bloqueia` | Condição impede avanço de outro item. | Bloqueio registrado. |
| `verifica` | Item testa critério de objeto. | Método e evidência. |
| `corrige` | Item restaura condição esperada. | Falha de origem. |
| `prepara` | Item cria condição para gate, liberação ou operação. | Objeto preparado. |
| `divide_se_em` | Item foi decomposto em sucessores. | Origem congelada. |
| `consolida` | Item agrega predecessores sem apagar identidade. | Critério integrado. |
| `substitui` | Novo item ocupa função de item encerrado. | Motivo e decisão. |
| `gera` | Item produz evidência, decisão, risco ou novo trabalho. | Destino explícito. |

### 22.1 Dependência não é bloqueio automático

Uma dependência conhecida pode estar satisfeita, prevista ou ainda não exigida. Torna-se bloqueio quando impede o avanço esperado segundo a política vigente.

### 22.2 Relações canônicas

A nomenclatura oficial dos vínculos pertence à Matriz de Rastreabilidade. Termos desta seção são orientações operacionais e devem ser mapeados ao vocabulário canônico quando a matriz do dossiê for preenchida.

---

## 23. Estrutura do backlog

Organize a demanda em camadas suficientes para evitar que ideias remotas concorram visualmente com trabalho elegível.

| Camada | Conteúdo | Ordenação | Revisão | Saída |
| --- | --- | --- | --- | --- |
| Caixa de entrada | Demandas ainda não triadas. | Ordem de chegada e urgência aparente. | Triagem | Qualificar, destinar ou rejeitar. |
| Em qualificação | Demandas com informação incompleta. | Risco e limite de resposta. | Refinamento | Elegível ou destinada. |
| Backlog qualificado | Itens válidos ainda não selecionáveis. | Valor, risco, dependências e horizonte. | Revisão de backlog | Fila elegível. |
| Fila elegível | Itens que atendem política de entrada. | Política explícita de reposição. | Reposição | Compromisso. |
| Fluxo comprometido | Itens consumindo capacidade. | Política de puxada. | Gestão diária | Conclusão ou retorno governado. |
| Concluídos com destino | Itens localmente concluídos, cancelados ou transferidos. | Data e relação. | Revisão/arquivo | Evidência, validação ou memória. |

### 23.1 Horizonte do backlog

| Horizonte | Grau de detalhe | Compromisso permitido | Revisão |
| --- | --- | --- | --- |
| Atual | Critério, origem, dependências e capacidade suficientemente definidos. | Conforme `PI-2` e ponto de compromisso. | Frequente |
| Próximo | Qualificação suficiente para preparar reposição. | Não, salvo decisão específica. | Regular |
| Futuro | Resultado ou necessidade reconhecida, com incerteza explícita. | Não | Por marco/onda |
| Estacionado | Relevante, sem condição atual de avanço. | Não | Gatilho definido |

Item estacionado deve possuir motivo, responsável por revisão e gatilho. Sem isso, arquive ou destine.

---

## 24. Ordenação do backlog

Ordenação é uma decisão contextual sobre qual item deve ser considerado antes de outro. Deve integrar:

- valor para a capacidade pretendida;
- obrigação ou condição arquitetural;
- risco tratado ou criado;
- dependência e possibilidade de desbloqueio;
- janela e compromisso temporal;
- aprendizagem necessária;
- reversibilidade;
- capacidade e competência disponíveis;
- impacto humano e capacidade de absorção;
- custo de atraso ou de antecipação;
- classe de serviço;
- consequência de não realizar.

| Item | Posição | Fundamentos | Dependências | Janela/marco | Classe | Autoridade/política | Data da decisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [N/faixa] | [IDs/resumo] | [IDs] | [ID/N.A.] | [ID] | [Nome/política] | [Data] |

### 24.1 Prioridade não é número isolado

Uma pontuação pode apoiar comparação, mas deve conservar seus fatores, escala, data e limitações. Resultado matemático não substitui decisão quando itens possuem impactos incomensuráveis.

### 24.2 Reordenação

| Evento | Itens afetados | Ordem anterior | Nova ordem | Fundamento | Efeito em cronograma | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/data] | [IDs] | [Preencher] | [Preencher] | [ID/motivo] | [Preencher] | [Nome/política] | [Fonte] |

Reordenar item comprometido exige avaliar interrupção, perda, troca de contexto, segurança e impacto em dependências. Não é equivalente a reordenar fila não iniciada.

---

## 25. Critérios de priorização

| Critério | Pergunta | Escala | Fonte | Peso, se usado | Proteção |
| --- | --- | --- | --- | --- | --- |
| Capacidade | Quanto o item contribui para resultado autorizado? | [Escala] | [ID] | [Valor/N.A.] | Não confundir entrega com capacidade. |
| Obrigação | Existe condição legal, ética, contratual ou de gate? | [Escala] | [ID] | [Valor/N.A.] | Obrigação deve ser competente. |
| Risco | Que exposição reduz ou amplia? | [Escala] | [ID] | [Valor/N.A.] | Risco possui fonte própria. |
| Tempo | Que janela, marco ou dependência afeta? | [Escala] | [ID] | [Valor/N.A.] | Cronograma é fonte temporal. |
| Aprendizagem | Que incerteza material pode reduzir? | [Escala] | [ID] | [Valor/N.A.] | Experimento precisa de limite. |
| Reversibilidade | Realizar agora preserva capacidade de retorno? | [Escala] | [ID] | [Valor/N.A.] | Irreversibilidade exige autoridade. |
| Impacto humano | Que carga, participação ou proteção exige? | [Escala] | [ID] | [Valor/N.A.] | Eficiência não apaga custo concentrado. |
| Viabilidade | Entradas, competência e ambiente estão disponíveis? | [Escala] | [ID] | [Valor/N.A.] | Facilidade não substitui valor. |

### 25.1 Método de pontuação opcional

| Item | Capacidade | Obrigação | Risco | Tempo | Aprendizagem | Impacto humano | Viabilidade | Resultado | Julgamento final |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Valor] | [Valor] | [Valor] | [Valor] | [Valor] | [Valor] | [Valor] | [Cálculo] | [Posição e fundamento] |

Documente fórmula, escalas e pesos antes de calcular. Não use precisão decimal maior que a qualidade das entradas.

---

## 26. Classes de serviço

Classe de serviço define como um item elegível recebe tratamento no fluxo. Use o menor número de classes capaz de representar diferenças reais.

| Classe | Finalidade | Critério de entrada | Política de puxada | Limite | Expectativa | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Padrão | Trabalho previsível do horizonte. | Elegibilidade atendida. | Ordem do backlog e capacidade. | [N/regra] | [ID/valor] | [Política] | [Cadência] |
| Data fixa | Condição vinculada a janela ou obrigação. | Data e consequência verificadas. | Proteger sequência necessária. | [N/regra] | [ID/valor] | [Papel] | [Cadência] |
| Expedita | Resposta excepcional a dano ou interrupção material. | Critério estrito e autoridade. | Preferência limitada com impacto explícito. | [N, normalmente 1] | [ID/valor] | [Papel] | Imediata |
| Intangível | Reduz risco futuro, dívida ou perda de capacidade. | Efeito e limite reconhecidos. | Reserva de capacidade ou política. | [N/regra] | [ID/valor] | [Papel] | [Cadência] |

### 26.1 Classe não é rótulo livre

Cada classe deve possuir política. “Urgente”, “alta” ou “VIP” sem critério e consequência apenas transfere disputa para o quadro.

### 26.2 Classe expedita

Antes de aplicar:

- declare o dano ou risco de não interromper a ordem;
- identifique quem autoriza;
- registre o item deslocado e o efeito temporal;
- limite a quantidade simultânea;
- defina condição de saída;
- revise causa quando a exceção encerrar.

Urgências recorrentes indicam falha de capacidade, planejamento, qualidade, dependência ou política. Não devem ser normalizadas por uma faixa permanente sem investigação.

---

## 27. Reposição do sistema

Reposição é a cadência em que demanda qualificada é examinada e itens elegíveis são colocados à disposição do sistema.

| Campo | Registro |
| --- | --- |
| Cadência | [Frequência/gatilho] |
| Horizonte | [Período/onda/contexto] |
| Participantes | [Nomes/papéis] |
| Preparador | [Nome/papel] |
| Autoridade ou política | [Preencher] |
| Capacidade disponível | [Fonte/valor] |
| Entradas | [Backlog, cronograma, riscos, decisões] |
| Saídas | [Fila elegível, condições, reordenações] |
| Registro | [Caminho/link] |

### 27.1 Perguntas de reposição

1. O horizonte e o objeto possuem autorização aplicável?
2. Quais itens atendem integralmente à política de elegibilidade?
3. Que capacidade real estará disponível?
4. Que dependências, janelas e marcos condicionam a seleção?
5. Que trabalho humano e organizacional precisa avançar junto?
6. Que riscos ou itens intangíveis precisam de capacidade protegida?
7. Que itens envelhecem sem razão legítima?
8. Que itens devem ser divididos, destinados, estacionados ou removidos?
9. Que exceções exigem decisão?

### 27.2 Resultado da reposição

| Item | Resultado | Posição | Condições | Capacidade prevista | Classe | Responsável | Próxima revisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Elegível / condicionado / não elegível / destinado / estacionado | [N/faixa] | [IDs/nenhuma] | [Faixa/unidade] | [ID] | [Nome] | [Data] |

Reposição prepara escolha. Não reserva silenciosamente toda a capacidade nem inicia itens.

---

## 28. Sistema puxado e compromisso

O trabalho deve ser puxado quando o estado seguinte possui capacidade e o item atende à política aplicável.

### 28.1 Condições de puxada

- autorização do objeto está vigente;
- item está elegível;
- limite do estado seguinte permite entrada;
- responsável ou conjunto responsável está disponível;
- entradas materiais estão acessíveis;
- dependências necessárias estão satisfeitas ou tratadas;
- não existe bloqueio impeditivo oculto;
- classe de serviço e ordem foram respeitadas ou a exceção está registrada;
- troca de contexto não produz risco desproporcional;
- evento de compromisso pode ser registrado.

| Item | Estado de origem | Estado de destino | Política atendida | Capacidade | Responsável | Evento/data | Exceção |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado] | [Estado] | [ID/versão] | [Disponível] | [Nome] | [ID/data-hora] | [ID/nenhuma] |

### 28.2 Puxar, não empurrar

Pressão de prazo, senioridade, cliente ou ferramenta não substitui capacidade. Se uma obrigação exigir início apesar do limite, trate-a como decisão de exceção com consequência visível.

### 28.3 Autoatribuição

Autoatribuição pode ser permitida quando competências, segregação, capacidade e prioridade estiverem claras. Ela não elimina responsabilidade pelo resultado nem autoridade sobre exceções.

---

## 29. Desenho do quadro Kanban

Configure o quadro para representar o fluxo real do contexto, com o menor número de estados que preserve políticas e esperas materiais.

### 29.1 Quadro mestre preenchível

| Não qualificado | Backlog qualificado | Pronto | Em andamento | Em verificação | Concluído |
| --- | --- | --- | --- | --- | --- |
| [IDs] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs] |

Itens bloqueados permanecem no estado factual e recebem marcador explícito. Quando a ferramenta exigir coluna própria, registre também o estado de origem para não perder a posição no fluxo.

### 29.2 Faixas opcionais

| Faixa | Finalidade | Critério de pertencimento | Limite próprio | Responsável |
| --- | --- | --- | --- | --- |
| [Projeto/onda/incremento/classe/tipo] | [Preencher] | [Política] | [N/regra] | [Nome] |

Faixas não devem fragmentar a leitura de dependências ou criar hierarquia humana implícita.

### 29.3 Representação mínima do cartão

| Elemento visível | Conteúdo |
| --- | --- |
| Identidade | ID e título |
| Tipo | Ícone, rótulo ou campo acessível |
| Origem | Pacote/objeto principal |
| Responsável | Nome ou papel |
| Classe/prioridade | Valor vigente |
| Bloqueio | Sinal e ID, se houver |
| Idade | Data de compromisso ou entrada no estado |
| Critério | Resumo ou link |
| Janela/gate | Sinal quando material |
| Próxima ação | Quando o item não puder falar por seu estado |

Cor não deve ser o único meio de transmitir estado, risco ou bloqueio.

---

## 30. Vocabulário de estados

Vocabulário padrão recomendado:

| Estado | Definição | Consome limite? | Estado terminal? |
| --- | --- | --- | --- |
| `capturado` | Demanda registrada sem triagem. | Não | Não |
| `em_qualificacao` | Origem, tipo, critério ou destino estão sendo definidos. | Conforme política específica | Não |
| `backlog_qualificado` | Item válido, ainda não elegível ou selecionado. | Não | Não |
| `pronto` | Política de elegibilidade atendida e item disponível à puxada. | Não | Não |
| `em_andamento` | Trabalho real iniciou após compromisso. | Sim | Não |
| `em_verificacao` | Saída foi produzida e está sob verificação local. | Sim | Não |
| `concluido` | Critério local foi atendido e evidência registrada. | Não | Sim para o fluxo local |
| `cancelado` | Item não será realizado por decisão registrada. | Não | Sim |
| `substituido` | Outro item assumiu sua função. | Não | Sim |
| `transferido` | Tratamento passou formalmente a outra fonte ou módulo. | Não | Sim |

### 30.1 Atributos transversais

Os seguintes atributos não devem ser convertidos automaticamente em estados:

- bloqueado;
- expedito;
- em risco;
- aguardando janela;
- aguardando decisão;
- sensível;
- candidato a gate;
- retrabalho.

Eles qualificam a condição do item e podem coexistir com seu estado factual.

### 30.2 Vocabulário adaptado

| Estado local | Mapeamento canônico | Política de entrada | Política de saída | Limite | Motivo da adaptação |
| --- | --- | --- | --- | --- | --- |
| [Nome] | [Estado padrão] | [ID/política] | [ID/política] | [N/regra] | [Preencher] |

Adaptação não pode fazer `concluído` significar também validado, liberado ou aceito.

---

## 31. Políticas de entrada e saída por estado

| Estado | Pode entrar quando | Pode sair quando | Evidência | Limite | Autoridade de exceção |
| --- | --- | --- | --- | --- | --- |
| Capturado | Demanda e produtor são registráveis. | Triagem definiu destino. | Registro de entrada | [N/tempo] | [Nome/papel] |
| Em qualificação | Pertencimento possível e lacuna explícita. | Origem, tipo, critério e destino suficientes. | Registro da triagem | [N/tempo] | [Nome/papel] |
| Backlog qualificado | Item é válido e pertence ao escopo. | Política de elegibilidade atendida. | Item mestre | [N/tempo] | [Nome/papel] |
| Pronto | Entradas, responsabilidade, risco e autorização são suficientes. | Há puxada válida ou elegibilidade foi retirada. | Checklist de elegibilidade | [N/tempo] | [Nome/papel] |
| Em andamento | Compromisso foi registrado e há capacidade. | Saída produzida ou retorno governado. | Evento de compromisso | [N] | [Nome/papel] |
| Em verificação | Saída e evidência candidata existem. | Critério local atendido ou correção aberta. | Evidência de verificação | [N] | [Nome/papel] |
| Concluído | Verificador confirmou critério local e destino. | Não aplicável; pode gerar trabalho relacionado. | Evidência e data | N.A. | Correção formal |

### 31.1 Retorno de estado

| Item | Estado anterior | Estado de retorno | Motivo | Evidência | Efeito temporal | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado] | [Estado] | Falha / nova informação / dependência / correção | [ID] | [Preencher] | [Nome] | [Data/hora] |

Retorno não deve apagar a passagem anterior. Reabertura recorrente indica critério inadequado, verificação tardia, dependência instável ou pressão por conclusão prematura.

---

## 32. Fila pronta

A fila pronta contém apenas itens cuja política de elegibilidade foi atendida. Deve ser pequena o suficiente para preservar atualidade e grande o suficiente para evitar ociosidade causada por ausência de opção compatível.

| Item | Data de elegibilidade | Posição | Classe | Competência requerida | Dependências satisfeitas | Janela | Validade da prontidão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/hora] | [N/faixa] | [ID] | [Preencher] | [Sim/condição] | [ID/N.A.] | [Data/condição] |

### 32.1 Prontidão expira

Mudança de versão, tempo decorrido, indisponibilidade, nova evidência, alteração de risco ou perda de acesso pode invalidar elegibilidade. A política deve definir quando rever itens prontos.

### 32.2 Fila pronta inflada

Muitos itens prontos podem gerar envelhecimento, requalificação frequente e falsa expectativa. Reduza o horizonte ou fortaleça reposição quando a fila exceder a capacidade de absorção definida.

---

## 33. Trabalho em andamento

Um item entra em andamento somente quando trabalho real começou no objeto delimitado.

| Item | Compromisso | Responsável | Capacidade | Critério em foco | Dependências | Idade | Próxima ação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/hora] | [Nome] | [Faixa/unidade] | [Resumo] | [IDs/nenhuma] | [Período] | [Ação] |

### 33.1 Início simbólico

Abrir arquivo, agendar reunião ou atribuir pessoa não constitui início se nenhuma transformação do objeto ocorreu. A data de compromisso pode preceder o primeiro trabalho; ambas devem permanecer distinguíveis quando a espera for material.

### 33.2 Troca de responsável

| Item | Responsável anterior | Novo responsável | Motivo | Estado preservado | Transferência realizada | Data |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome] | [Nome] | [Preencher] | [Estado] | [Evidência] | [Data/hora] |

Trocar nome no cartão sem transferência de contexto, acesso, critério e responsabilidade cria falsa continuidade.

---

## 34. Verificação no fluxo

O estado `em_verificacao` representa julgamento local sobre o critério do item. Pode ser omitido somente quando a verificação ocorre na própria execução e a segregação não é material.

| Item | Objeto/versão | Verificador | Método | Evidência | Resultado | Correção necessária | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [Nome/papel] | [Preencher] | [ID/link] | Atendido / parcial / não atendido / inconclusivo | [ID/nenhuma] | [Data] |

### 34.1 Verificador e executor

Segregação deve aumentar conforme risco, impacto, sensibilidade, irreversibilidade e conflito de interesse. Quando a mesma pessoa executar e verificar, registre fundamento e controles compensatórios.

### 34.2 Fila de verificação

Limite próprio para verificação evita que produção exceda capacidade de julgamento e acumule entregas não confirmadas.

---

## 35. Conclusão e destino

Antes de concluir um item:

- o critério local foi verificado;
- a evidência está acessível e íntegra;
- resultado negativo ou limitação foi preservado;
- relações e fontes afetadas foram sinalizadas;
- correção ou trabalho sucessor recebeu ID;
- risco, dependência e bloqueio foram atualizados;
- a próxima condição de pacote, entrega, gate ou configuração é compreensível;
- o destino do item está registrado.

| Item | Resultado local | Evidência | Data de conclusão | Destino | Objetos atualizados | Trabalho gerado | Verificador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Atendido/resultado] | [ID] | [Data/hora] | [Pacote/entrega/gate/arquivo/outro] | [IDs] | [IDs/nenhum] | [Nome] |

### 35.1 Concluído não é apagado

Itens concluídos devem sair da visão operacional corrente quando apropriado, mas permanecer recuperáveis por ID, período, objeto e versão.

### 35.2 Conclusão com limitação

Se o critério admite limite ou ressalva, registre a condição e sua autoridade. Se o critério não foi atendido, o item não deve ser encerrado como concluído para evitar retrabalho visível.

---

## 36. Bloqueios

Bloqueio é uma condição presente que impede o avanço esperado de um item segundo sua política vigente.

Quando um item for bloqueado, registre:

- estado factual em que permanece;
- início do bloqueio;
- condição bloqueadora;
- itens, entregas, incrementos e marcos afetados;
- responsável pela remoção ou coordenação;
- autoridade necessária;
- ação imediata;
- limite de escalonamento;
- efeito sobre capacidade e compromissos;
- data de revisão;
- encerramento e evidência.

### 36.1 Registro de bloqueio no item

| Campo | Registro |
| --- | --- |
| ID do bloqueio | [ID do registro integrado] |
| Item | [ID] |
| Estado factual | [Estado] |
| Início | [Data/hora] |
| Condição | [Preencher] |
| Causa conhecida | [Fonte/hipótese/não determinada] |
| Objetos afetados | [IDs] |
| Responsável | [Nome/papel] |
| Autoridade requerida | [Nome/papel/N.A.] |
| Ação imediata | [Preencher] |
| Limite de resposta | [Data/hora/condição] |
| Escalonamento | [Papel/fórum] |
| Efeito temporal | [ID/resumo] |
| Próxima revisão | [Data/hora] |
| Estado do bloqueio | [Aberto/em tratamento/escalado/removido/aceito] |

### 36.2 Bloqueio sem responsável

Bloqueio sem responsável por coordenar a resposta deve ser escalado no mesmo ciclo em que for identificado. O responsável não precisa controlar a causa externa, mas precisa tornar o tratamento governável.

### 36.3 Item bloqueado continua consumindo sistema

O item pode ou não consumir o limite numérico da coluna, conforme política. Porém, sempre consome atenção, risco, coordenação e memória. Retirá-lo do limite apenas para abrir novo trabalho exige uma política que evite sobrecarga oculta.

### 36.4 Remoção do bloqueio

| Bloqueio | Item | Condição restabelecida | Evidência | Tempo bloqueado | Efeito remanescente | Trabalho gerado | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [ID/link] | [Período] | [Risco/atraso/nenhum] | [IDs/nenhum] | [Data/hora] |

Remover o marcador sem demonstrar a condição restabelecida não encerra o bloqueio.

---

## 37. Esperas, filas e estados de dependência

Espera é período em que o item não recebe trabalho ativo. Pode ser necessária, previsível ou disfuncional.

| Tipo de espera | Exemplo | Representação | Tratamento |
| --- | --- | --- | --- |
| Prevista pela política | Revisão independente, janela ou tempo de observação. | Estado ou atributo explícito. | Medir e dimensionar. |
| Dependência conhecida | Aguardar entrada, fornecedor ou decisão. | Dependência e limite. | Confirmar, acompanhar e escalar. |
| Capacidade indisponível | Fila diante de competência ou ambiente. | Fila e limite. | Proteger capacidade ou replanejar. |
| Bloqueio | Condição impede avanço que deveria ocorrer. | Marcador e registro de bloqueio. | Remover, conter ou decidir. |
| Desconhecida | Item permanece sem movimento e sem causa. | Anomalia. | Investigar imediatamente. |

### 37.1 Registro de espera material

| Item | Início | Fim | Tipo | Motivo | Objeto esperado | Responsável | Limite | Efeito |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/hora] | [Data/hora/aberta] | [Tipo] | [Preencher] | [ID/evento] | [Nome] | [Data/condição] | [Preencher] |

### 37.2 Espera não deve desaparecer no tempo de ciclo

Quando o sistema mede travessia, espera integra o tempo percebido e o compromisso real. Separar tempo ativo e tempo de espera ajuda a compreender o fluxo; excluir espera produz uma imagem artificial.

### 37.3 Fila de decisão

Decisões pendentes devem possuir autoridade, informação necessária, data limite e consequência. A fila não pode depender apenas da próxima reunião disponível.

---

## 38. Limites de trabalho em curso

Limites de trabalho em curso protegem foco, qualidade, tempo de resposta, capacidade humana e conclusão. Devem corresponder à realidade do sistema, não a um número copiado de outra equipe.

| ID | Contexto/estado | Limite | Unidade | Motivo | Inclui bloqueados? | Exceção | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-LTC-NNN` | [Estado/faixa/quadro] | [N/faixa] | Itens / esforço / outra | [Capacidade/segurança/qualidade] | [Sim/não/regra] | [ID/política] | [Papel] | [Cadência] |

### 38.1 Definição do limite

Considere:

- capacidade efetiva, não nominal;
- trabalho operacional simultâneo;
- competência rara;
- capacidade de verificação;
- dependências e troca de contexto;
- variabilidade dos itens;
- necessidade de colaboração;
- impacto de urgências;
- carga de aprendizagem e mudança;
- folga necessária para incidentes e suporte;
- risco e sensibilidade do objeto.

### 38.2 Limite atingido

Quando um limite for atingido:

1. não iniciar automaticamente outro item;
2. verificar se é possível concluir ou desbloquear trabalho existente;
3. redistribuir ajuda dentro das competências e alçadas;
4. tratar dependências e verificações;
5. avaliar item expedito somente pela política aprovada;
6. escalar se o sistema não puder restabelecer fluxo.

### 38.3 Exceção ao limite

| Exceção | Contexto | Limite | Valor temporário | Motivo | Itens afetados | Risco | Autoridade | Expiração | Retorno |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-EXF-NNN` | [Estado/faixa] | [N] | [N] | [Preencher] | [IDs] | [ID] | [Nome/papel] | [Data/condição] | [Ação] |

Exceção sem expiração converte desvio em política silenciosa.

### 38.4 Limite não é punição

Não utilize o limite para impedir registro de trabalho já iniciado, ocultar ajuda necessária ou responsabilizar pessoa por uma condição estrutural. O quadro precisa refletir a realidade antes de corrigi-la.

---

## 39. Capacidade e carga sustentáveis

Capacidade é a condição real de realizar e verificar trabalho em determinado contexto e período.

| Contexto/competência | Capacidade disponível | Trabalho operacional reservado | Trabalho de implantação | Reserva | Restrições | Fonte | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Equipe/papel/ambiente] | [Faixa/unidade] | [Faixa] | [Faixa] | [Faixa] | [Preencher] | [ID] | [Nome] |

### 39.1 Carga invisível

Inclua, quando material:

- operação corrente;
- suporte e incidentes;
- reuniões e coordenação;
- aprendizagem e treinamento;
- revisão e validação;
- documentação;
- trabalho emocional e relacional da mudança;
- cuidado com dados e segurança;
- transição de conhecimento;
- ausências e indisponibilidades.

### 39.2 Capacidade de verificação

Produção não deve ser acelerada acima da capacidade de integrar, revisar, testar e decidir. Fila crescente em verificação é sinal de desequilíbrio do sistema.

### 39.3 Saturação

| Sinal | Fonte | Limite | Estado | Resposta | Responsável | Data de revisão |
| --- | --- | --- | --- | --- | --- | --- |
| Fila crescente / horas adicionais / troca de contexto / falha / ausência | [ID] | [Preencher] | [Normal/atenção/crítico] | [Reduzir entrada/realocar/replanejar/outro] | [Nome] | [Data] |

Saturação recorrente não deve ser resolvida apenas aumentando cobrança ou automatizando entrada.

---

## 40. Política de urgência e exceção

| Situação | Critério | Classe/rota | Pode interromper ordem? | Autoridade | Efeito obrigatório | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| Dano atual ou continuidade ameaçada | [Condição] | Expedita/contingência | [Sim/condicionado] | [Papel] | Conter e atualizar compromissos. | [Fonte] |
| Janela rígida próxima | [Condição] | Data fixa | [Conforme política] | [Papel] | Proteger dependências. | [Fonte] |
| Solicitação executiva sem dano demonstrado | [Condição] | Avaliação normal | Não automaticamente | [Papel] | Tornar trade-off visível. | [Fonte] |
| Falha crítica descoberta | [Condição] | Correção/impedimento | Sim, se autorizado | [Papel] | Conter exposição e registrar risco. | [Fonte] |

### 40.1 Custo da interrupção

Antes de interromper trabalho comprometido, registre:

- itens que serão pausados;
- perda de contexto ou trabalho descartado;
- dependências e marcos afetados;
- risco de qualidade ou segurança;
- comunicação necessária;
- condição de retomada;
- autoridade que aceitou o trade-off.

### 40.2 Urgência humana

Risco à saúde, dignidade, segurança, privacidade ou direito de contestação pode exigir resposta imediata mesmo quando não ameaça prazo ou tecnologia. A política deve reconhecer esses objetos materialmente.

---

## 41. Envelhecimento dos itens

Idade é o tempo decorrido desde um evento definido. Declare qual relógio está sendo observado.

| Item | Estado | Início do relógio | Idade atual | Faixa esperada | Sinal | Causa/hipótese | Ação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado] | [Data/hora/evento] | [Período] | [Faixa] | [Normal/atenção/excedido] | [Preencher] | [Ação, responsável, limite] |

### 41.1 Relógios possíveis

- idade desde captura;
- idade desde elegibilidade;
- idade desde compromisso;
- tempo no estado atual;
- tempo bloqueado;
- tempo aguardando decisão;
- tempo desde conclusão até validação ou destino.

### 41.2 Política de envelhecimento

| Faixa | Condição | Resposta | Autoridade | Registro |
| --- | --- | --- | --- | --- |
| Normal | Dentro da expectativa contextual. | Acompanhar. | Política | Quadro |
| Atenção | Aproxima-se do limite ou desvia de semelhantes. | Examinar causa e próxima ação. | Responsável pelo fluxo | Revisão |
| Excedida | Ultrapassa expectativa ou ameaça compromisso. | Escalar, dividir, desbloquear, replanejar ou decidir. | [Papel] | Registro de ação |

Idade não deve ser usada isoladamente para cobrar a pessoa responsável. Itens podem envelhecer por dependência, tamanho, prioridade interrompida, espera legítima ou desenho inadequado do fluxo.

---

## 42. Tempos do fluxo

| Medida | Início | Fim | Inclui espera? | Uso | Proteção |
| --- | --- | --- | --- | --- | --- |
| Tempo de resposta | Captura | Primeiro movimento reconhecível | Sim | Acesso e confiança. | Movimento precisa ser material. |
| Tempo de elegibilidade | Captura/qualificação | Item pronto | Sim | Qualidade da preparação. | Não premiar triagem superficial. |
| Tempo de ciclo | Compromisso | Conclusão local | Sim | Previsibilidade do fluxo. | Não equivale a implantação. |
| Tempo de atravessamento | Captura | Destino final local | Sim | Experiência ponta a ponta. | Declarar fronteira. |
| Tempo ativo | Início de trabalho | Soma dos períodos ativos | Não | Compreender esforço e espera. | Requer qualidade de registro. |
| Tempo bloqueado | Início do bloqueio | Remoção | N.A. | Exposição a impedimento. | Distinguir múltiplos bloqueios. |
| Tempo de verificação | Entrada em verificação | Resultado local | Sim | Capacidade de julgamento. | Preservar reaberturas. |

### 42.1 Unidade e calendário

Declare se a medição utiliza horas corridas, horas úteis, dias corridos, dias úteis ou outro calendário. Comparações exigem mesma definição, contexto e fronteira.

### 42.2 Correção de eventos

| Evento | Valor anterior | Valor corrigido | Motivo | Evidência | Autor da correção | Data |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [Data/hora] | [Data/hora] | [Preencher] | [ID] | [Nome] | [Data] |

Corrigir fato não significa apagar o registro original.

---

## 43. Indicadores de fluxo

Utilize indicadores apenas quando cada um apoiar uma decisão definida.

| Indicador | Definição | Fonte | Frequência | Segmentação | Limite/sinal | Decisão apoiada | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Trabalho em curso | Itens comprometidos nos estados incluídos. | Quadro | [Cadência] | [Contexto/tipo] | [Preencher] | Limitar entrada/ajudar | [Nome] |
| Vazão | Itens concluídos por período e fronteira. | Histórico | [Cadência] | [Tipo/tamanho] | [Preencher] | Prever capacidade | [Nome] |
| Tempo de ciclo | Distribuição do compromisso à conclusão. | Eventos | [Cadência] | [Classe/tipo] | [Preencher] | Ajustar expectativa | [Nome] |
| Idade em curso | Idade dos itens ainda abertos. | Quadro | [Cadência] | [Estado/classe] | [Preencher] | Intervir cedo | [Nome] |
| Tempo bloqueado | Duração e proporção de bloqueios. | Registro integrado | [Cadência] | [Causa] | [Preencher] | Remover restrição | [Nome] |
| Taxa de retrabalho | Itens reabertos ou correções relacionadas. | Histórico | [Cadência] | [Origem/tipo] | [Preencher] | Melhorar qualidade | [Nome] |
| Fila de verificação | Itens aguardando ou sob verificação. | Quadro | [Cadência] | [Verificador/contexto] | [Preencher] | Equilibrar capacidade | [Nome] |
| Urgências | Itens expeditos e interrupções por período. | Exceções | [Cadência] | [Causa] | [Preencher] | Tratar recorrência | [Nome] |
| Demanda descartada/destinada | Itens não absorvidos e motivos. | Triagem | [Cadência] | [Canal/motivo] | [Preencher] | Ajustar escopo/canal | [Nome] |

### 43.1 Distribuição antes da média

Média pode ocultar itens muito antigos, classes distintas e mudança de comportamento. Examine distribuição, percentis ou faixas contextuais quando houver volume suficiente e qualidade de dados.

### 43.2 Leituras protegidas

- maior vazão não prova maior valor;
- menor tempo não prova qualidade;
- mais itens concluídos não prova capacidade implantada;
- menos bloqueios registrados pode significar invisibilidade;
- variação não deve ser atribuída automaticamente a indivíduos;
- comparar contextos diferentes exige natureza, tamanho, classe e período compatíveis;
- metas não devem incentivar fragmentação artificial, encerramento prematuro ou ocultação de retrabalho.

---

## 44. Expectativa de nível de serviço

Expectativa de nível de serviço expressa uma previsão baseada em histórico ou hipótese explícita sobre a travessia de uma classe de itens. Não é garantia automática nem substitui compromisso do Cronograma Mestre.

| ID | População de referência | Evento inicial | Evento final | Expectativa | Confiança/base | Período dos dados | Exclusões | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-ENS-NNN` | [Tipo/classe/contexto] | [Evento] | [Evento] | [X% em até Y unidade] | [Método/amostra/hipótese] | [Período] | [Preencher] | [Cadência] |

### 44.1 Base insuficiente

Quando não houver histórico comparável, registre uma hipótese com faixa, premissas e data de revisão. Não apresente um número escolhido como desempenho demonstrado.

### 44.2 Uso

A expectativa pode apoiar:

- seleção de horizonte;
- comunicação de risco;
- identificação de envelhecimento;
- previsão probabilística;
- dimensionamento de fila pronta;
- revisão de capacidade.

Ela não autoriza prometer data incompatível com dependências, janela ou gate.

---

## 45. Previsão de fluxo

| Previsão | Objeto | Método | Dados de entrada | Premissas | Faixa/resultado | Data de status | Limitação | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Itens/horizonte] | Histórico / cenário / simulação / julgamento | [Fonte] | [Preencher] | [Faixa] | [Data] | [Preencher] | [Nome] |

### 45.1 Perguntas legítimas

- Quantos itens comparáveis podem concluir em determinado período?
- Quando uma quantidade delimitada tende a concluir sob as premissas atuais?
- Que probabilidade existe de atender uma janela?
- Que efeito a classe expedita ou o bloqueio produz sobre a faixa?

### 45.2 Fronteira com o cronograma

O sistema de fluxo produz sinal e faixa. O Cronograma Mestre integra esses dados à rede, às datas, aos marcos e à linha de base temporal. Alteração da previsão de fluxo não reescreve compromisso aprovado.

### 45.3 Simulação assistida

Quando IA ou cálculo automatizado apoiar previsão, preserve algoritmo ou método, população, versão dos dados, exclusões, data de status e revisão humana.

---

## 46. Gargalos e restrições do fluxo

| ID | Contexto | Evidência | Efeito | Natureza | Hipótese de causa | Resposta | Responsável | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado/competência/recurso] | [Indicadores/observação] | Fila / espera / falha / risco | Temporária / recorrente / estrutural / externa | [Preencher] | [Preencher] | [Nome] | [ID/pendente] |

### 46.1 Restrições frequentes

- decisão com autoridade concentrada;
- competência rara;
- ambiente ou acesso compartilhado;
- fornecedor externo;
- verificação independente;
- janela operacional;
- qualidade insuficiente na entrada;
- excesso de trabalho simultâneo;
- dependência de informação;
- sobrecarga de pessoas afetadas;
- ferramenta que limita visibilidade ou integração.

### 46.2 Proteções

- não aumentar entrada quando a restrição já está saturada;
- não automatizar etapa anterior apenas para ampliar fila posterior;
- não confundir pessoa situada na restrição com causa exclusiva do sistema;
- não transferir gargalo sem avaliar efeito total;
- não remover controle necessário apenas para acelerar fluxo;
- distinguir restrição de execução de mudança arquitetural.

---

## 47. Defeitos, correções e retrabalho

Retrabalho é trabalho adicional necessário porque uma condição antes considerada suficiente precisa ser refeita, corrigida ou completada.

| Item de origem | Resultado observado | Item de correção | Classe | Estado de origem reaberto? | Causa/hipótese | Evidência | Efeito | Destino |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID] | [Padrão/expedita/outra] | [Sim/não] | [Preencher] | [ID] | [Prazo/risco/capacidade] | [PDCA/controle/outro] |

### 47.1 Correção não apaga conclusão anterior

Se nova evidência invalidar o resultado, relacione eventos e corrija a afirmação. O histórico deve mostrar por que o item foi concluído e o que posteriormente exigiu reabertura ou correção.

### 47.2 Causa não determinada

Não atribua automaticamente retrabalho a erro de execução. Critério ambíguo, mudança, dependência, decisão tardia, entrada incompleta e falha de arquitetura também podem produzi-lo.

### 47.3 Dívida conhecida

Trabalho deliberadamente adiado deve registrar objeto, efeito, risco, responsável, limite e decisão. “Depois melhoramos” não constitui destino governado.

---

## 48. Trabalho emergente

Trabalho emergente é demanda descoberta depois do planejamento do horizonte.

### 48.1 Classificação antes da absorção

| Demanda | Classificação | Origem | Pode entrar na alçada? | Efeito em escopo | Efeito temporal | Risco | Decisão/rota |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Detalhamento / correção / risco / impedimento / dependência / novo pacote / nova entrega / mudança arquitetural / outro | [ID] | [Sim/não/condicionado] | [Preencher] | [Preencher] | [ID] | [ID/rota] |

### 48.2 Absorção legítima

Um item emergente pode ser comprometido quando:

- sua origem foi verificada;
- o tipo e a materialidade foram classificados;
- a autoridade aplicável foi identificada;
- o efeito sobre trabalho atual e compromissos foi registrado;
- a capacidade ou exceção foi decidida;
- fontes afetadas serão sincronizadas;
- não existe mudança arquitetural escondida.

### 48.3 Descoberta não é falha automática

Implantação produz conhecimento novo. O controle deve permitir descoberta sem punir sua visibilidade, preservando responsabilidade sobre análise e destino.

---

## 49. Trabalho humano e organizacional no fluxo

Comunicação, participação, aprendizagem, preparação, adaptação de rotina e transferência de conhecimento devem ser representadas como trabalho real quando necessárias à capacidade.

| Item | Dimensão humana | Público/grupo | Resultado local | Participação | Critério | Evidência | Carga/limite | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Comunicação / engajamento / treinamento / mudança / suporte | [IDs/grupos] | [Preencher] | [Forma] | [Preencher] | [ID/tipo] | [Preencher] | [Nome] |

### 49.1 Proteções

- comunicação enviada não é compreensão;
- presença não é competência;
- uso observado não é adoção;
- silêncio não é consentimento;
- discordância não é impedimento por definição;
- sobrecarga não deve ser ocultada como resistência;
- participação requer tempo, informação, segurança e destino.

### 49.2 Capacidade de absorção

Itens humanos não devem ser empilhados apenas porque não consomem ambiente técnico. Pessoas podem participar simultaneamente da operação, aprendizagem, transição e sustentação de outras mudanças.

### 49.3 Objeção ou impacto sensível

Crie item operacional somente com informação necessária. Preserve o relato completo em fonte protegida e evite exposição da pessoa no quadro.

---

## 50. Decisões, riscos, impedimentos e dependências como itens

O quadro pode acompanhar trabalho associado a objetos de controle, sem substituir seus registros oficiais.

| Tipo de item | Deve conter | Considera-se concluído quando | Fonte oficial externa |
| --- | --- | --- | --- |
| Decisão | Questão, opções, informação, autoridade e limite. | Resultado e consequência foram registrados. | Registro de decisão |
| Risco | Risco, resposta delimitada, responsável e gatilho. | Ação foi executada ou risco atualizado por autoridade. | Registro integrado |
| Impedimento | Condição, itens afetados, dono da resposta e escalonamento. | Condição foi removida, aceita ou destinada. | Registro integrado |
| Dependência | Objeto requerido, provedor, compromisso e contingência. | Dependência foi satisfeita, substituída ou decidida. | Cronograma/registro integrado |
| Mudança | Solicitação, impacto, classe e autoridade. | Decisão foi implementada e fontes sincronizadas. | Controle de mudança |

### 50.1 Não fechar o objeto pelo fechamento da ação

Concluir uma ação de mitigação não encerra automaticamente o risco. Obter resposta do fornecedor não conclui a dependência se a condição ainda não foi satisfeita. Preparar recomendação não conclui a decisão.

### 50.2 Vínculo obrigatório

| Item | Objeto de controle | Registro oficial | Estado do objeto | Estado do item | Sincronização | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Fonte] | [Estado] | [Estado] | [Data/resultado] | [Nome] |

---

## 51. Dados, confidencialidade e ética no quadro

| Classe de informação | Pode aparecer no cartão? | Forma permitida | Fonte completa | Acesso | Retenção |
| --- | --- | --- | --- | --- | --- |
| Pública | Sim | Conteúdo necessário. | [Fonte] | [Regra] | [Período] |
| Interna | Conforme necessidade | Resumo e referência. | [Fonte] | Equipe autorizada | [Período] |
| Confidencial | Somente metadado necessário | ID, estado e responsável. | Repositório restrito | Lista autorizada | [Período] |
| Sensível/pessoal | Evitar conteúdo | Identificador pseudonimizado e ação. | Fonte protegida | Menor privilégio | [Período/regra] |
| Segredo/credencial | Não | Apenas necessidade de acesso, nunca valor. | Cofre/sistema competente | Autorizado | Conforme política |

### 51.1 Minimização

O cartão deve conter informação suficiente para coordenar o trabalho, não todo o conteúdo necessário para executá-lo. Dados, evidências e relatos permanecem em fontes apropriadas.

### 51.2 Transparência proporcional

Restringir conteúdo sensível não autoriza tornar o trabalho invisível. O quadro pode mostrar que existe item restrito, seu estado, responsável, dependência e consequência sem expor conteúdo.

### 51.3 Exclusão e retenção

Encerramento do item não autoriza apagar registro sujeito a memória, auditoria, obrigação legal ou aprendizagem. Da mesma forma, histórico de quadro não deve conservar dados pessoais além da finalidade e do período autorizados.

---

## 52. Tecnologia e IA como objetos da implantação

Quando a configuração implantada inclui tecnologia ou IA, o backlog deve representar trabalho material de:

- acesso e ambiente;
- dados e qualidade;
- configuração e versão;
- integração;
- avaliação e teste;
- guardrails e permissões;
- supervisão humana;
- tratamento de erro e exceção;
- segurança e privacidade;
- continuidade, degradação e desativação;
- documentação e competência;
- monitoramento e suporte.

| Item | Sistema/modelo | Função | Versão | Dados | Controle | Supervisão | Critério | Evidência | Risco |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/nome] | [Preencher] | [Versão] | [ID/classe] | [ID] | [Papel] | [Preencher] | [ID] | [ID] |

### 52.1 Saída de IA não é item concluído

Geração automática pode produzir rascunho, classificação ou sinal. O item conclui somente depois da verificação e da condição definida para o objeto.

### 52.2 Automação do quadro

Movimentação automática precisa declarar evento, regra, versão, exceção e forma de correção. Um sistema não deve marcar `concluído` apenas porque execução técnica retornou sucesso quando o critério exige julgamento humano ou operacional.

---

## 53. Cadências de gestão do fluxo

| Cadência | Finalidade | Participantes | Entrada | Saída | Frequência/gatilho | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Triagem | Dar destino à demanda capturada. | [Papéis] | Caixa de entrada | Itens qualificados/destinados | [Cadência] | [Papel/política] | [Fonte] |
| Refinamento | Tornar itens elegíveis sem antecipar execução. | [Papéis] | Backlog qualificado | Critérios e lacunas | [Cadência] | [Papel] | [Fonte] |
| Reposição | Ordenar e disponibilizar trabalho elegível. | [Papéis] | Backlog/capacidade/cronograma | Fila pronta | [Cadência] | [Papel] | [Fonte] |
| Coordenação de fluxo | Ver trabalho, limites, idade e bloqueios. | [Papéis] | Quadro atual | Ações e escalonamentos | [Cadência] | [Política] | [Fonte] |
| Revisão de entrega | Examinar conclusão e qualidade do fluxo. | [Papéis] | Evidências/indicadores | Decisões de melhoria | [Cadência] | [Papel] | [Fonte] |
| Revisão de risco | Integrar riscos, dependências e mudanças. | [Papéis] | Registro integrado | Respostas e decisões | [Cadência] | [Papel] | [Fonte] |
| Retrospectiva de fluxo | Aprender sobre políticas e sistema. | [Papéis] | Histórico e experiência | Experimentos/PDCA | [Cadência] | [Papel] | [Fonte] |

### 53.1 Cadência não é cerimônia obrigatória

Cada encontro ou mecanismo deve produzir triagem, coordenação, decisão, evidência ou aprendizagem identificável. Pode ser assíncrono quando acesso, compreensão, autoridade e registro permanecerem suficientes.

### 53.2 Cadência por criticidade

| Condição | Frequência mínima | Participação adicional | Escalonamento |
| --- | --- | --- | --- |
| Fluxo estável | [Período] | [Papéis] | [Regra] |
| Item envelhecido | [Período menor] | Responsável/dependência | [Papel] |
| Bloqueio crítico | Imediata e recorrente até destino | Autoridade/área afetada | [Papel] |
| Janela próxima | [Período/evento] | Cronograma/operação | [Papel] |
| Expedita ativa | [Alta frequência] | Autoridade e afetados | [Papel] |
| Suspensão/reversão | Conforme plano e evento | Comando competente | [Papel] |

---

## 54. Coordenação cotidiana

A coordenação de fluxo deve responder, de forma proporcional:

1. Que itens estão comprometidos?
2. Que limite foi atingido ou se aproxima?
3. Que item envelhece e por quê?
4. Que bloqueio exige ajuda ou decisão?
5. Que verificação ou dependência precisa ser puxada?
6. Que item pode concluir antes de iniciar outro?
7. Que fato altera cronograma, risco, escopo ou gate?
8. Que pessoa ou grupo está sobrecarregado ou sem condição?
9. Que trabalho emergente precisa ser triado?
10. Qual é o próximo movimento verificável?

### 54.1 Registro de coordenação

| Data | Data de status | Itens examinados | Limites | Bloqueios | Decisões/ações | Responsáveis | Próxima revisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Data/hora] | [Data/hora] | [IDs] | [Estado] | [IDs] | [IDs/resumo] | [Nomes] | [Data/hora] |

### 54.2 Não exigir relato performático

O quadro deve reduzir a necessidade de cada pessoa narrar atividades já visíveis. A conversa se concentra em coordenação, condição, ajuda, decisão, impacto e próximo movimento.

---

## 55. Revisão e aprendizagem do fluxo

| Dimensão | Pergunta | Evidência | Resultado | Ação/PDCA | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| Demanda | Entradas são compreensíveis e recebem destino? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Elegibilidade | Itens prontos permanecem atuais? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Capacidade | Limites protegem conclusão e pessoas? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Bloqueios | Causas recorrentes são tratadas? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Qualidade | Retrabalho e verificação revelam padrão? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Tempo | Previsões e expectativas permanecem úteis? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Humanidade | Ritmo, poder e exposição são sustentáveis? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |
| Governança | Exceções, mudanças e decisões são recuperáveis? | [Fonte] | [Preencher] | [ID] | [Nome] | [Data] |

### 55.1 Mudança de política

| Política | Versão anterior | Nova versão | Evidência | Hipótese | Autoridade | Início | Revisão | Reversão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [N.N] | [N.N] | [IDs] | [Preencher] | [Nome/papel] | [Data] | [Data/condição] | [Forma] |

Mudança de política deve ser tratada como hipótese quando seus efeitos ainda não foram demonstrados. Não reescreva retrospectivamente dados para aparentar aderência à regra nova.

---

## 56. Sincronização com a Estrutura Analítica

| Evento no backlog | Efeito esperado na Estrutura Analítica | Responsável | Limite | Registro |
| --- | --- | --- | --- | --- |
| Item derivado de pacote | Referenciar sem alterar o pacote. | [Nome] | [Período] | [IDs] |
| Item dividido | Preservar relação com pacote e critério. | [Nome] | [Período] | [IDs] |
| Novo pacote necessário | Conter compromisso até atualizar e autorizar a estrutura. | [Nome] | [Data/condição] | [ID] |
| Nova entrega descoberta | Avaliar escopo, origem e arquitetura. | [Nome] | Imediato se material | [ID] |
| Critério local altera saída do pacote | Atualizar EAI ou rejeitar alteração. | [Nome] | Antes da execução afetada | [ID] |
| Item sem pacote legítimo | Registrar origem transversal e justificativa. | [Nome] | [Período] | [ID] |

### 56.1 Reconciliação de cobertura

| Pacote/entrega | Itens previstos | Itens existentes | Itens concluídos | Itens sem origem | Lacuna | Responsável | Última reconciliação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Quantidade/IDs] | [IDs] | [IDs] | [IDs/nenhum] | [ID/nenhuma] | [Nome] | [Data] |

Quantidade não substitui materialidade. Um único critério crítico sem item ou tratamento pode impedir prontidão.

---

## 57. Sincronização com o Cronograma Mestre

| Elemento | Backlog/Kanban | Cronograma Mestre | Regra |
| --- | --- | --- | --- |
| Estado atual | Fonte operacional do item. | Consome fato na data de status. | Sincronizar na cadência. |
| Ordem de puxada | Política do backlog. | Recebe efeito sobre sequência e marcos. | Divergência material exige decisão. |
| Data e janela | Pode exibir compromisso local. | Fonte temporal oficial. | Não duplicar linha de base. |
| Bloqueio | Fonte do item e idade. | Registra efeito sobre previsão e caminho. | Escalar bloqueio crítico. |
| Vazão/tempo de ciclo | Produz dados e faixas. | Usa para previsão contextual. | Declarar população e período. |
| Trabalho emergente | Registra demanda e decisão. | Avalia efeito antes de novo compromisso. | Origem e autoridade obrigatórias. |
| Conclusão | Registra evento local. | Atualiza realizado quando critério temporal correspondente for atendido. | Marco não é cartão. |

### 57.1 Registro de divergências

| ID | Item/objeto | Fluxo informa | Cronograma informa | Fonte prevalente | Risco | Ação | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [Preencher] | [Regra] | [Preencher] | [Preencher] | [Nome] | [Data] |

### 57.2 Regra contra dupla atualização

Estado detalhado do item permanece no sistema de fluxo. Datas-base, previsão mestre e realizado dos objetos temporais permanecem no cronograma. Integração ou referência deve substituir cópia manual quando possível.

---

## 58. Sincronização com a Matriz de Rastreabilidade

| Objeto do fluxo | Vínculos esperados | Destino | Estado | Responsável |
| --- | --- | --- | --- | --- |
| Item | Origem, pacote, entrega, incremento e capacidade. | [IDs] | [Estado] | [Nome] |
| Critério | Objeto, método, evidência e verificador. | [IDs] | [Estado] | [Nome] |
| Bloqueio | Condição, objetos afetados, resposta e decisão. | [IDs] | [Estado] | [Nome] |
| Evento de conclusão | Item, evidência, resultado e objetos atualizados. | [IDs] | [Estado] | [Nome] |
| Exceção de fluxo | Política, autoridade, risco, período e efeito. | [IDs] | [Estado] | [Nome] |
| Trabalho emergente | Evidência de origem, classificação, decisão e destino. | [IDs] | [Estado] | [Nome] |

### 58.1 Verificação de órfãos

| Item | Origem encontrada? | Objeto realizado? | Evidência prevista? | Destino posterior? | Lacuna | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Sim/não/parcial] | [IDs/nenhum] | [ID/nenhuma] | [ID/nenhum] | [ID/nenhuma] | [Preencher] |

O vocabulário canônico dos vínculos pertence à matriz. Este template conserva fatos suficientes para que os vínculos possam ser criados sem reconstrução especulativa.

---

## 59. Sincronização com o registro integrado de controle

| Fato no fluxo | Registro especializado necessário | Gatilho | Responsável | Limite de sincronização |
| --- | --- | --- | --- | --- |
| Risco novo ou alterado | Risco | Materialidade ou mudança de exposição. | [Nome] | [Período] |
| Bloqueio | Impedimento/problema/dependência | Interrupção do avanço esperado. | [Nome] | Imediato conforme criticidade |
| Dependência nova | Dependência | Outro objeto, pessoa ou evento condiciona avanço. | [Nome] | [Período] |
| Premissa invalidada | Premissa/condição/mudança | Evidência contradiz base do trabalho. | [Nome] | [Período] |
| Exceção de limite | Condição/mudança | Trabalho em curso excede política. | [Nome] | No evento |
| Mudança de critério ou saída | Mudança | Pode afetar plano, escopo ou arquitetura. | [Nome] | Antes de continuar |

### 59.1 Fonte oficial de cada estado

| Objeto | Fonte oficial | Campo referenciado no item | Cadência | Custodiante |
| --- | --- | --- | --- | --- |
| Risco | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` | [ID/estado] | [Cadência] | [Nome] |
| Impedimento | Mesmo registro integrado | [ID/estado] | [Cadência] | [Nome] |
| Dependência | Cronograma/registro integrado | [ID/estado] | [Cadência] | [Nome] |
| Mudança | Registro integrado/decisão | [ID/estado] | [Cadência] | [Nome] |

Enquanto o template seguinte ainda não estiver construído, utilize a fonte provisória identificada no dossiê sem inventar vocabulário concorrente; migre ou referencie quando a fonte oficial existir.

---

## 60. Sincronização com planos especializados

| Plano ou registro | Itens que pode originar | Fato que recebe do fluxo | Regra de não duplicação |
| --- | --- | --- | --- |
| Comunicação e engajamento | Preparar mensagem, participação, escuta e confirmação. | Estado e evidência da ação. | Público, mensagem e estratégia permanecem no plano. |
| Treinamento e capacitação | Produzir material, realizar prática, verificar competência. | Trabalho e conclusão local. | Competência e avaliação permanecem no plano. |
| Gestão da mudança | Tratar impacto, apoio, adoção e contestação. | Sinais, bloqueios e ações. | Análise humana permanece na fonte protegida. |
| Piloto, ondas, virada e reversão | Preparar ambiente, executar teste, conter ou retornar. | Estado dos itens e dependências. | Comando, janela e contingência permanecem no plano. |
| PDCA | Executar ação delimitada do ciclo. | Fatos e itens gerados. | Hipótese, verificação e decisão permanecem no registro PDCA. |
| Prontidão | Tratar lacunas anteriores a execução ou liberação. | Estado e evidência local. | Resultado de prontidão permanece na verificação. |
| Validação e aceite | Preparar caso, coletar evidência, corrigir falha. | Conclusões locais. | Julgamento e aceite permanecem no registro. |
| Configuração implantada | Corrigir, documentar ou reconciliar configuração. | Fatos de execução. | Estado real e diferenças permanecem no registro de configuração. |

### 60.1 Relação de sincronização

| Item | Plano/registro | Objeto relacionado | Estado na fonte | Estado no fluxo | Divergência | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Caminho/ID] | [ID] | [Estado] | [Estado] | [Preencher/nenhuma] | [Preencher] |

---

## 61. Relação com os gates da implantação

O sistema de fluxo apoia gates ao tornar trabalho e condições visíveis. Ele não decide gates.

| Gate | Contribuição do sistema de fluxo | Não pode afirmar sozinho |
| --- | --- | --- |
| `PI-1` | Registrar ações e condições decorrentes do aceite da transição. | Que a linha de base foi aceita. |
| `PI-2` | Demonstrar demanda qualificada, trabalho elegível, capacidade, políticas, limites e bloqueios. | Que todas as dimensões estão prontas ou que execução está autorizada. |
| `PI-3` | Mostrar itens de produção, integração, teste, correção e prontidão da versão. | Que a versão pode ser liberada. |
| `PI-4` | Relacionar trabalho concluído, evidências, correções e diferenças. | Que capacidade e configuração foram aceitas. |
| `PI-5` | Organizar pendências, transferência, documentação e destino do trabalho. | Que a operação aceitou responsabilidade. |

### 61.1 Itens condicionados por gate

| Item | Gate | Objeto delimitado | Pode avançar antes? | Até qual estado? | Evidência/decisão | Regra de desbloqueio |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [PI-N/ocorrência] | [ID/versão] | [Sim/não/condicionado] | [Estado] | [ID] | [Preencher] |

### 61.2 Data prevista de gate

Data ou coluna associada ao gate não equivale à decisão. O item permanece condicionado até que o resultado competente seja registrado.

---

## 62. Preparação do PI-2

Antes de submeter o objeto ao `PI-2`, verifique o sistema de fluxo do horizonte correspondente.

### 62.1 Verificação de prontidão do fluxo

| Dimensão | Pergunta | Resultado | Evidência | Lacuna/condição | Responsável |
| --- | --- | --- | --- | --- | --- |
| Escopo | O backlog contém somente demanda pertencente ou destinada? | [Atendido/parcial/não] | [ID] | [ID/nenhuma] | [Nome] |
| Origem | Itens materiais possuem origem e relações? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Critério | Trabalho elegível possui conclusão verificável? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Políticas | Entrada, saída, puxada, bloqueio e exceção estão explícitas? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Capacidade | Limites correspondem à capacidade real e à verificação? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Prioridade | Ordem, classes e urgência possuem autoridade? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Dependências | Condições e responsáveis estão visíveis? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Pessoas | Trabalho humano, carga e contestação estão tratados? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Segurança | Dados, acessos e sensibilidades estão protegidos? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Sincronização | EAI, cronograma e fontes de controle estão reconciliados? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Ferramenta | Histórico, acesso, exportação e recuperação funcionam? | [Estado] | [ID] | [ID/nenhuma] | [Nome] |

### 62.2 Pergunta do PI-2

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

O sistema de fluxo responde apenas à parte que lhe cabe: se demanda, trabalho, capacidade, estados, políticas e exceções podem ser governados no objeto delimitado.

### 62.3 Resultado da preparação

| Campo | Registro |
| --- | --- |
| Objeto/horizonte examinado | [IDs/período] |
| Estado do sistema | [Estado] |
| Itens elegíveis | [IDs/quantidade] |
| Trabalho que pode ser preparado | [IDs] |
| Trabalho condicionado ao `PI-2` | [IDs] |
| Lacunas impeditivas | [IDs/nenhuma] |
| Condições tratáveis | [IDs/nenhuma] |
| Recomendação | Pronto / pronto com condições / não pronto / suspender / retornar |
| Responsável pela verificação | [Nome/papel] |
| Data/evidência | [Data/ID] |

Recomendação não é decisão do gate.

---

## 63. Uso entre PI-3, PI-4 e PI-5

### 63.1 Preparação do PI-3

| Objeto | Itens necessários | Concluídos | Bloqueados | Correções abertas | Evidências | Lacuna |
| --- | --- | --- | --- | --- | --- | --- |
| [Versão/incremento] | [IDs] | [IDs] | [IDs/nenhum] | [IDs/nenhuma] | [IDs] | [ID/nenhuma] |

Itens concluídos apoiam a verificação de prontidão para liberar. Não autorizam a liberação.

### 63.2 Apoio ao PI-4

| Capacidade/configuração | Itens relacionados | Evidências | Diferenças | Validação | Pendências | Fonte de aceite |
| --- | --- | --- | --- | --- | --- | --- |
| [IDs] | [IDs] | [IDs] | [IDs] | [ID/resultado] | [IDs/nenhuma] | [ID/pendente] |

### 63.3 Apoio ao PI-5

| Condição de transição | Itens | Estado | Responsável atual | Responsável futuro | Evidência | Destino |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Estado] | [Nome/papel] | [Nome/papel] | [ID] | [Operação/implantação/outro] |

Trabalho transferido deixa o fluxo da implantação apenas quando a fonte de destino, a responsabilidade e o aceite aplicáveis estão registrados.

---

## 64. Controle de escopo, mudança e configuração

Movimentos no backlog devem ser classificados quando alterarem mais que prioridade ou estado operacional.

| Alteração | Classe | Pode ser decidida no fluxo? | Atualizações necessárias |
| --- | --- | --- | --- |
| Corrigir descrição sem mudar objeto | Editorial | Sim | Histórico do item. |
| Detalhar atividade de pacote | Detalhamento | Sim, pela política | Item e relação. |
| Reordenar item não comprometido | Executiva | Sim, dentro da alçada | Registro de ordem e cronograma se material. |
| Alterar método sem mudar critério | Adaptação executiva | Condicionada | Plano/fonte pertinente. |
| Alterar saída ou critério de pacote | Mudança de plano/estrutura | Não pelo quadro sozinho | EAI, cronograma, matriz e decisão. |
| Criar entrega ou capacidade | Mudança material | Não | Análise de escopo e possível Módulo 3. |
| Alterar requisito, componente, interface, autoridade ou risco material | Mudança arquitetural | Não | Retorno ao Módulo 3. |

### 64.1 Solicitação de mudança originada no fluxo

| Item/fato | Mudança proposta | Objetos afetados | Materialidade preliminar | Trabalho contido | Análise | Autoridade | Destino |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | [Editorial/executiva/arquitetural/incerta] | [IDs/nenhum] | [ID] | [Nome/papel] | [Aprovar/rejeitar/M3/outro] |

### 64.2 Continuidade durante análise

Trabalho não afetado pode continuar quando sua separação for demonstrada. Itens dependentes da mudança permanecem contidos; sua pressão temporal não reduz a necessidade de decisão.

### 64.3 Configuração real

Concluir item de configuração exige registrar versão ou condição aplicada. O quadro não deve presumir que a configuração desenhada passou a existir apenas porque o trabalho técnico terminou.

---

## 65. Integração com ciclos PDCA

Um padrão de fluxo pode originar um ciclo PDCA quando houver hipótese testável dentro da alçada.

| Sinal | Hipótese | Escopo do teste | Item(s) | Critério | Limite | Registro PDCA | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Fila/bloqueio/retrabalho/idade/outro] | [Preencher] | [Contexto/período] | [IDs] | [Preencher] | [Condição] | [ID] | [Nome/papel] |

### 65.1 Plan — Planejar

Declare problema, hipótese, mudança de política ou ação, população, período, critério, risco e forma de reversão.

### 65.2 Do — Executar

Implemente em escopo controlado e identifique os itens atravessados sob a política experimental.

### 65.3 Check — Verificar

Compare fluxo, qualidade, carga humana, risco, efeitos inesperados e limitações. Não selecione apenas indicadores favoráveis.

### 65.4 Act — Agir

| Resultado | Decisão | Efeito na política | Efeito nos itens | Destino da aprendizagem | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Confirmado/parcial/refutado/inconclusivo] | Manter / ajustar / repetir / reverter / escalar | [Versão/nenhum] | [IDs/ação] | [M6/M7/M8/local] | [Nome/papel] |

PDCA não autoriza alterar arquitetura silenciosamente.

---

## 66. Contenção, suspensão, cancelamento e reversão

### 66.1 Contenção de fluxo

| Objeto | Gatilho | Nova entrada permitida? | Trabalho em curso | Evidência preservada | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| [Quadro/faixa/itens] | [Risco/bloqueio/decisão] | [Não/condicionado] | Concluir / pausar / proteger / outro | [Fonte] | [Nome/papel] | [Data/condição] |

### 66.2 Suspensão

Suspensão formal deve congelar a condição necessária para retomada, registrar itens afetados, proteger dados e ambientes, comunicar responsáveis e atualizar cronograma e riscos.

| Item | Estado na suspensão | Trabalho parcial | Ativos/evidências | Risco | Condição de retomada | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Estado] | [Preencher] | [Fonte] | [ID] | [Preencher] | [Nome] |

### 66.3 Cancelamento

| Item | Motivo | Autoridade | Trabalho produzido | Destino | Dependentes afetados | Comunicação | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID/nome] | [Fonte] | [Arquivar/reutilizar/descartar/outro] | [IDs] | [ID] | [Data] |

### 66.4 Reversão

Itens de reversão devem ser previamente reconhecidos quando a estratégia exigir retorno. Durante a reversão, eles recebem prioridade e autoridade conforme o plano de virada e reversão, preservando o estado que motivou a ação.

### 66.5 Retomada

Retomada exige rever elegibilidade, versões, acessos, capacidade, riscos, dependências, validade de evidências e autorização. O tempo decorrido pode tornar a fila pronta obsoleta.

---

## 67. Evidências e proveniência do fluxo

| Fato | Item | Evento | Data/hora | Produtor | Fonte | Integridade/versão | Verificador | Limitação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Entrada/movimento/bloqueio/conclusão/exceção] | [ID] | [ID] | [Data/hora/fuso] | [Nome/sistema] | [Link/log] | [Hash/versão/NA] | [Nome/NA] | [Preencher] |

### 67.1 Eventos mínimos preservados

- captura;
- resultado da triagem;
- elegibilidade;
- compromisso;
- entrada e saída dos estados que medem tempo material;
- início e remoção de bloqueio;
- exceção de limite ou ordem;
- troca material de responsável;
- conclusão, cancelamento, substituição ou transferência;
- correção de fato;
- mudança de política.

### 67.2 Histórico da ferramenta

Histórico automático pode ser fonte de eventos quando acesso, retenção, fuso, identidade e exportação forem adequados. Caso contrário, mantenha registro complementar proporcional.

### 67.3 Evidência de movimento

O log de mudança de coluna demonstra que o sistema registrou um movimento. Para demonstrar que a condição foi atendida, é necessário o critério e a evidência do objeto.

---

## 68. Acesso, custódia e continuidade da ferramenta

| Controle | Regra | Responsável | Evidência | Revisão |
| --- | --- | --- | --- | --- |
| Criação de item | [Quem/quais canais] | [Nome/papel] | [Fonte] | [Cadência] |
| Alteração de prioridade | [Alçada] | [Nome/papel] | [Log] | [Cadência] |
| Movimento de estado | [Pessoas/automação] | [Nome/papel] | [Log] | [Cadência] |
| Conclusão/cancelamento | [Política] | [Nome/papel] | [Log/evidência] | [Cadência] |
| Acesso a conteúdo sensível | Menor privilégio. | [Nome/papel] | [Lista/log] | [Cadência] |
| Exportação e backup | [Formato/período] | [Custodiante] | [Local] | [Cadência] |
| Recuperação | [Procedimento] | [Nome/papel] | [Teste] | [Cadência] |
| Encerramento de acesso | [Gatilho] | [Nome/papel] | [Registro] | [Cadência] |

### 68.1 Indisponibilidade

| Cenário | Modo contingencial | Fonte temporária | Reconciliação | Limite | Responsável |
| --- | --- | --- | --- | --- | --- |
| Ferramenta indisponível / acesso perdido / integração falha | [Preencher] | [Caminho/formato] | [Procedimento] | [Tempo] | [Nome] |

### 68.2 Migração de ferramenta

Migração deve preservar IDs, campos essenciais, estados, eventos materiais, relações, anexos necessários, acessos e fonte anterior. Novo quadro não deve iniciar histórico fictício como se a implantação começasse na migração.

---

## 69. Papéis e responsabilidades

| Papel | Responsabilidade no fluxo | Pode decidir | Não pode decidir |
| --- | --- | --- | --- |
| Autoridade da implantação | Aprovar políticas materiais, exceções, prioridades superiores e contenção dentro da alçada. | Trade-offs e respostas autorizadas. | Mudança arquitetural reservada. |
| Responsável pela implantação | Integrar fluxo, capacidade, cronograma, riscos e planos. | Ajustes executivos dentro do envelope. | Reduzir critérios ou aceitar risco fora da alçada. |
| Responsável pelo fluxo | Manter políticas, estados, cadências, métricas e reconciliação. | Aplicar políticas vigentes. | Criar autorização por movimento. |
| Responsável pelo item | Conduzir próximo movimento, revelar condição e produzir evidência. | Organizar execução local. | Ocultar bloqueio ou redefinir objeto material. |
| Responsável pela EAI | Preservar relação com pacotes, entregas e critérios. | Detalhamento autorizado. | Controlar prioridade cotidiana sozinho. |
| Responsável pelo cronograma | Integrar fatos de fluxo à previsão e aos compromissos. | Atualização factual. | Alterar estado operacional por conveniência. |
| Verificador | Julgar critério local com competência. | Declarar resultado da verificação. | Aceitar gate quando segregação exigir outra autoridade. |
| Custodiante | Preservar acesso, versões, eventos e exportações. | Aplicar controle documental. | Alterar conteúdo material. |
| Responsável operacional | Informar capacidade, janelas e condições futuras. | Manifestar prontidão e aceite na alçada. | Receber trabalho silenciosamente. |
| Pessoa afetada/participante | Informar contexto, efeito, risco, compreensão e objeção. | Participar conforme objeto e alçada. | Ser tratada como responsável por decisão que não possui. |

### 69.1 Responsável não é executor único

Cada item possui uma pessoa responsável por manter seu avanço governável. Trabalho pode ser coletivo e exigir colaboração. A responsabilidade não deve ocultar dependências ou transferir toda a carga para um indivíduo.

---

## 70. Matriz de autoridade do fluxo

| Decisão | Propõe | Analisa | Decide | Executa/atualiza | Comunica | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| Configurar estados e políticas | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Definir limite de trabalho em curso | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Ordenar backlog | [Papel] | [Papéis] | [Papel/política] | [Papel] | [Papel] | [Alçada] |
| Conceder classe expedita | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Exceder limite | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Tempo/quantidade] |
| Cancelar item comprometido | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Conter nova entrada | [Papel] | [Papéis] | [Papel/política] | [Papel] | [Papel] | [Alçada] |
| Alterar critério local | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Retornar ao Módulo 3 | [Papel] | [Papéis] | [Papel competente] | [Papel] | [Papel] | [Contrato] |

### 70.1 Ausência de autoridade

Quando a autoridade necessária estiver indisponível, registre decisão pendente, limite e consequência. Não converta silêncio em aprovação.

---

## 71. Participação da inteligência artificial

A IA pode apoiar:

- detecção de duplicidades;
- classificação inicial de demanda;
- verificação de campos obrigatórios;
- análise de vínculos e dependências;
- identificação de itens envelhecidos;
- cálculo de tempos e distribuições;
- geração de cenários e previsões;
- detecção de inconsistências entre fontes;
- preparação de sínteses de fluxo;
- sugestão de perguntas para cadências;
- consolidação de histórico e aprendizagem.

### 71.1 Condições de uso

| Uso | Dados/escopo | Sistema/modelo | Versão | Critério | Revisão humana | Registro | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Classificação/análise/previsão/outro] | [Preencher] | [Identificação] | [Versão] | [Preencher] | [Nome/papel] | [Fonte/log] | [Preencher] |

### 71.2 Limites não delegáveis

A IA não deve:

- decidir pertencimento material sem revisão;
- criar escopo;
- autorizar puxada antes de gate;
- alterar prioridade material ou classe expedita por conta própria;
- exceder limite de trabalho em curso;
- aceitar risco;
- reduzir critério;
- concluir item que exige julgamento humano;
- interpretar silêncio como concordância;
- avaliar pessoas por métricas de fluxo;
- decidir mudança arquitetural;
- autorizar liberação, aceite, reversão ou transição;
- assumir responsabilidade final.

### 71.3 Erro e correção

Item movido, classificado ou resumido por IA deve poder ser corrigido por pessoa autorizada. A correção preserva o evento automático, o motivo e o valor validado.

### 71.4 IA no quadro não é IA implantada

O uso de IA para apoiar gestão do fluxo é distinto da IA que integra a configuração organizacional. Ambos exigem registro quando materiais, mas possuem objetos, riscos e critérios diferentes.

---

## 72. Proporcionalidade

| Escala | Forma do sistema | Controles mínimos |
| --- | --- | --- |
| Focal | Backlog e quadro reduzidos em uma tabela única. | Origem, tipo, critério, responsável, prioridade, estado, bloqueio, datas, evidência e destino. |
| Funcional | Backlog por horizontes, quadro com limites, classes e cadências. | Políticas, eventos, métricas, sincronização e governança completas. |
| Sistêmica | Sistema mestre e quadros coordenados por projetos, ondas ou contextos. | Consolidação, dependências cruzadas, múltiplos gates, acesso, auditoria e previsão ampliada. |

### 72.1 Intensificadores de controle

Amplie detalhe quando houver:

- múltiplas equipes ou organizações;
- operação crítica;
- dados pessoais, confidenciais ou sensíveis;
- IA ou automação com efeito material;
- muitas dependências externas;
- janela rígida ou baixa reversibilidade;
- alto impacto humano;
- obrigação regulatória ou contratual;
- fornecedor crítico;
- grande variabilidade de demanda;
- urgências recorrentes;
- segregação de funções;
- transferência complexa para operação.

### 72.2 Combinação de artefatos

Uma implantação focal pode combinar backlog, cronograma e registro integrado no mesmo arquivo, desde que permaneçam distinguíveis:

- estado do fluxo;
- compromisso temporal;
- risco, impedimento, dependência ou mudança;
- fonte oficial de cada fato;
- autoridade e histórico.

---

## 73. Versão reduzida para implantação focal

### 73.1 Identificação

| Campo | Registro |
| --- | --- |
| Sistema de fluxo | `BLG-IMP-AAAA-NNN` |
| Implantação | `IMP-AAAA-NNN` |
| Plano/EAI/Cronograma | [IDs/versões] |
| Objeto/horizonte | [Preencher] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Data de status | [Data] |
| Estado/versão | [Preencher] |

### 73.2 Políticas focais

| Estado | Entrada | Saída | Limite | Exceção |
| --- | --- | --- | --- | --- |
| Backlog | Origem e tipo identificados. | Critério e entradas suficientes. | [N/tempo] | [Regra] |
| Pronto | Elegibilidade verificada. | Capacidade e puxada autorizada. | [N] | [Regra] |
| Em andamento | Compromisso registrado. | Saída pronta para verificação. | [N] | [Regra] |
| Em verificação | Evidência candidata disponível. | Critério atendido ou correção aberta. | [N] | [Regra] |
| Concluído | Critério local e destino registrados. | N.A. | N.A. | Correção formal |

### 73.3 Backlog e quadro focal

| Item | Tipo/origem | Critério | Responsável | Prioridade/classe | Estado | Bloqueio | Entrada/compromisso | Evidência/destino |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo/ID] | [Preencher] | [Nome] | [Preencher] | [Estado] | [ID/nenhum] | [Datas] | [IDs] |

### 73.4 Controle focal

| Condição | Estado | Ação | Responsável | Limite | Registro |
| --- | --- | --- | --- | --- | --- |
| Limite atingido / bloqueio / urgência / item envelhecido / trabalho emergente | [Preencher] | [Preencher] | [Nome] | [Data/condição] | [ID] |

### 73.5 Regra de uso

A versão reduzida não se aplica quando a simplificação impede distinguir classes, dependências críticas, múltiplos contextos, trabalho sensível, gates repetidos, capacidade de verificação ou histórico necessário.

---

## 74. Revisão consolidada

### 74.1 Origem e escopo

- [ ] Sistema, implantação, fontes e versões estão identificados.
- [ ] Fronteira de fluxo e contextos estão delimitados.
- [ ] Itens possuem origem, tipo e pertencimento.
- [ ] Trabalho sem pacote possui justificativa transversal.
- [ ] Duplicidades, exclusões e itens estacionados receberam tratamento.

### 74.2 Políticas e estados

- [ ] Ponto de compromisso está explícito.
- [ ] Estados representam condições reais e possuem políticas.
- [ ] Elegibilidade está separada de prioridade e autorização.
- [ ] Conclusão local está separada de validação e aceite.
- [ ] Retorno, cancelamento, substituição e transferência preservam histórico.

### 74.3 Capacidade e fluxo

- [ ] Limites correspondem à capacidade real.
- [ ] Capacidade de verificação foi incluída.
- [ ] Bloqueios, esperas, filas e envelhecimento estão visíveis.
- [ ] Urgências possuem critérios, autoridade e efeito registrado.
- [ ] Trabalho humano e operacional corrente integram a leitura de carga.

### 74.4 Integração e governança

- [ ] EAI, cronograma, matriz e registro integrado podem ser reconciliados.
- [ ] Gates condicionam os itens aplicáveis.
- [ ] Trabalho emergente passa por classificação e autoridade.
- [ ] Mudanças materiais não entram como tarefas comuns.
- [ ] Papéis, alçadas, acessos e custódia estão definidos.

### 74.5 Evidência, aprendizagem e humanidade

- [ ] Eventos materiais são recuperáveis.
- [ ] Métricas possuem definição, contexto e decisão apoiada.
- [ ] Políticas não incentivam ocultação ou fragmentação.
- [ ] Pessoas não são comparadas automaticamente por vazão ou tempo.
- [ ] Dados e relatos sensíveis estão protegidos.
- [ ] Participação material da IA é registrada e revisada.
- [ ] Aprendizagem possui rota de PDCA e limite arquitetural.

---

## 75. Teste de reconstrução

Selecione amostra que inclua:

- um item padrão concluído;
- um item bloqueado ou envelhecido;
- um item expedito ou de data fixa, se utilizado;
- um item emergente;
- um item que produziu correção, mudança ou retorno;
- um item humano ou organizacional;
- um item apoiado por IA, quando aplicável.

Para cada item, reconstrua:

| Pergunta | Resultado | Evidência | Lacuna |
| --- | --- | --- | --- |
| Por que o item existiu? | [Preencher] | [ID] | [ID/nenhuma] |
| Que objeto e critério justificaram sua execução? | [Preencher] | [ID] | [ID/nenhuma] |
| Quando se tornou elegível e comprometido? | [Preencher] | [ID] | [ID/nenhuma] |
| Que autoridade permitiu avançar? | [Preencher] | [ID] | [ID/nenhuma] |
| Que estados, esperas e bloqueios atravessou? | [Preencher] | [ID] | [ID/nenhuma] |
| Que capacidade e classe recebeu? | [Preencher] | [ID] | [ID/nenhuma] |
| Como o critério local foi verificado? | [Preencher] | [ID] | [ID/nenhuma] |
| Que evidência e trabalho sucessor produziu? | [Preencher] | [ID] | [ID/nenhuma] |
| Que fontes foram atualizadas? | [Preencher] | [ID] | [ID/nenhuma] |
| Que efeito teve sobre entrega, incremento, gate e configuração? | [Preencher] | [ID] | [ID/nenhuma] |

### 75.1 Resultado

- [ ] Reconstrução integral satisfatória
- [ ] Reconstrução satisfatória com limitações
- [ ] Reconstrução insuficiente
- [ ] Inconsistência material encontrada
- [ ] Requer correção das fontes
- [ ] Requer retorno ao Módulo 3

| Campo | Registro |
| --- | --- |
| Amostra | [IDs] |
| Resultado | [Selecionar] |
| Lacunas | [IDs/nenhuma] |
| Correções | [IDs/nenhuma] |
| Responsável | [Nome/papel] |
| Verificador | [Nome/papel] |
| Data | [Data] |

---

## 76. Antipadrões

### 76.1 Quadro como lista de tarefas

Itens não possuem origem, critério, relação ou destino.

### 76.2 Tudo em andamento

Trabalho é iniciado para aparentar atividade, ampliando troca de contexto e atraso de conclusão.

### 76.3 Coluna bloqueado como estacionamento

Itens saem do estado factual, deixam de consumir limite e perdem responsável pela resposta.

### 76.4 Pronto sem prontidão

Fila pronta contém itens com entrada, decisão, acesso ou critério ainda ausentes.

### 76.5 Concluído por movimentação

Cartão é encerrado sem verificação ou evidência.

### 76.6 Urgência permanente

Classe expedita substitui planejamento e torna o custo das interrupções invisível.

### 76.7 Limite decorativo

Excessos são frequentes, não possuem autoridade ou nunca retornam à política.

### 76.8 Métrica como meta individual

Vazão, tempo ou quantidade de itens são usados para comparar pessoas sem contexto.

### 76.9 Fragmentação para aumentar contagem

Itens perdem resultado local apenas para melhorar indicador.

### 76.10 Fila inflada

Centenas de itens futuros concorrem com trabalho do horizonte e envelhecem sem revisão.

### 76.11 Repriorização invisível

Ordem muda por influência informal sem fundamento, autoridade ou efeito temporal.

### 76.12 Dependência como nota

Item aguarda pessoa, fornecedor ou decisão sem responsável e limite.

### 76.13 Trabalho emergente como atalho

Nova demanda entra em execução antes de classificação de escopo e mudança.

### 76.14 Automação do sucesso

Integração técnica move item para concluído sem julgamento exigido.

### 76.15 Quadro como vigilância

Detalhe e métricas servem para pressão individual, reduzindo segurança para revelar bloqueios.

### 76.16 Trabalho humano invisível

Comunicação, aprendizagem, participação e transição são tratados como externos ao plano de capacidade.

### 76.17 Cartão como fonte universal

Requisitos, riscos, evidências e decisões são copiados para o quadro e divergem das fontes oficiais.

### 76.18 Fluxo sem gate

Colunas permitem executar, liberar ou aceitar sem decisão competente.

### 76.19 Backlog eterno

Itens permanecem indefinidamente sem revisão, gatilho, destino ou exclusão.

### 76.20 Melhoria como redesenho

Política de fluxo altera silenciosamente critério, controle ou arquitetura.

---

## 77. Sinais de qualidade

Um sistema de fluxo de qualidade:

- permite compreender trabalho atual, próximo, bloqueado e concluído;
- torna demanda visível antes de prometer execução;
- preserva a origem e o tipo de cada item;
- utiliza critérios locais observáveis;
- distingue elegibilidade, prioridade, compromisso e autorização;
- limita trabalho em curso com base em capacidade real;
- revela espera, bloqueio, idade e retrabalho;
- protege capacidade de verificação e integração;
- trata urgências como exceções governadas;
- integra trabalho humano, técnico e operacional;
- mantém sincronização com EAI, cronograma, matriz e registros;
- preserva fatos e histórico sem sobrecarregar cartões;
- produz indicadores contextualizados para decisões;
- permite aprender sem ocultar resultados negativos;
- protege dados, pessoas, contestação e responsabilidade humana;
- mantém mudanças arquiteturais fora da autonomia do quadro.

### 77.1 Síntese de saúde

| Dimensão | Estado | Evidência | Tendência | Limite | Ação | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Demanda e elegibilidade | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Trabalho em curso | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Bloqueios e idade | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Verificação e qualidade | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Capacidade humana | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Dependências e tempo | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Governança e fontes | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |

---

## 78. Exemplo aplicado — sistema editorial

### 78.1 Contexto

A implantação `IMP-2026-001` prepara um sistema editorial aprovado na linha de base `LB-ARQ-014`. O incremento `IMP-2026-001-INC-001` deve permitir que uma pauta atravesse elaboração, revisão humana, aprovação e publicação com versões e responsabilidades recuperáveis.

O exemplo é ilustrativo. IDs, critérios e valores precisam ser substituídos pelo dossiê real.

### 78.2 Itens derivados

| Item | Tipo | Origem | Critério local | Classe | Estado |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-ITM-011` | Preparação | `IMP-2026-001-PT-004` | Perfis editoriais acessam o ambiente piloto segundo matriz aprovada. | Padrão | Concluído |
| `IMP-2026-001-ITM-012` | Atividade | `IMP-2026-001-PT-005` | Fluxo de revisão está configurado na versão candidata. | Padrão | Em verificação |
| `IMP-2026-001-ITM-013` | Teste | `TST-ARQ-031` | Cenários normal e de rejeição produzem estados e registros esperados. | Padrão | Pronto |
| `IMP-2026-001-ITM-014` | Decisão | `DEC-ARQ-019` | Autoridade decide limite de publicação assistida por IA. | Data fixa | `em_andamento` com bloqueio |

### 78.3 Política e limite

| Estado | Limite | Motivo |
| --- | --- | --- |
| Em andamento | 2 itens | Há uma pessoa responsável pela configuração e outra pela preparação humana. |
| Em verificação | 1 item | A verificação editorial independente é a capacidade restritiva. |

O item `ITM-012` permanece em verificação. O sistema não puxa `ITM-013` para verificação até existir capacidade, embora ele esteja pronto para execução do teste em ambiente autorizado.

### 78.4 Bloqueio de decisão

| Campo | Exemplo |
| --- | --- |
| Item | `IMP-2026-001-ITM-014` |
| Estado factual | `em_andamento` |
| Condição bloqueadora | Avaliação de privacidade ainda não foi recebida. |
| Responsável pela resposta | Responsável pela implantação |
| Autoridade requerida | Autoridade da implantação e especialista competente |
| Efeito | `PI-3` da versão com publicação assistida permanece condicionado. |
| Próxima ação | Obter avaliação até a janela registrada no cronograma. |

O cartão não é movido para concluído quando a reunião é agendada. A conclusão ocorre quando a decisão e sua consequência são registradas.

### 78.5 Trabalho emergente

Durante o teste, uma pessoa revisora identifica que o histórico expõe comentário pessoal além do necessário. A demanda é capturada, classificada como possível risco de privacidade e correção. A exposição é contida, o registro especializado é aberto e a autoridade decide se a correção permanece no envelope ou exige revisão arquitetural.

O item não recebe classe expedita apenas porque foi descoberto durante teste; recebe-a se o critério de dano atual e a autoridade previstos forem atendidos.

### 78.6 Limite do exemplo

Conclusão dos quatro itens não demonstra, isoladamente, que o sistema editorial foi liberado, adotado, estabilizado ou aceito. Essas afirmações dependem dos objetos, evidências e gates correspondentes.

---

## 79. Manifestações e aprovações

### 79.1 Responsável pelo fluxo

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Configuração suficiente / suficiente com condições / insuficiente |
| Condições | [IDs/nenhuma] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 79.2 Responsável pela implantação

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Integrado / integrado com condições / requer revisão |
| Riscos ou ressalvas | [IDs/nenhuma] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 79.3 Autoridade da implantação

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Decisão | Aprovar políticas / aprovar com condições / devolver / suspender |
| Escopo e horizonte | [IDs/período] |
| Condições | [IDs/nenhuma] |
| Limites e exceções autorizados | [IDs/nenhum] |
| Data | [Data] |
| Registro | [ID] |

### 79.4 Responsável pela Estrutura Analítica

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação sobre derivação e cobertura | [Preencher] |
| Lacunas | [IDs/nenhuma] |
| Data/referência | [Preencher] |

### 79.5 Responsável pelo Cronograma Mestre

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação sobre sincronização temporal | [Preencher] |
| Divergências | [IDs/nenhuma] |
| Data/referência | [Preencher] |

### 79.6 Responsável operacional indicado

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação sobre capacidade, fluxo e transição | [Preencher] |
| Condições | [IDs/nenhuma] |
| Data/referência | [Preencher] |

### 79.7 Divergências preservadas

| Pessoa/papel | Divergência | Objeto | Evidência | Destino | Decisão relacionada |
| --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [Preencher] | [IDs] | [IDs] | [Preencher] | [ID/pendente] |

### 79.8 Limite da aprovação

Aprovar o sistema de fluxo confirma que suas políticas e controles são adequados ao objeto e ao horizonte declarados. Não autoriza execução antes do `PI-2`, não libera incremento, não valida capacidade e não aceita configuração.

---

## 80. Controle de versões

### 80.1 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de status | [Data] |
| Localização oficial | [Caminho/link] |
| Políticas vigentes | [IDs/versões] |
| Decisão ou aprovação | [ID] |
| Versão substituída | [N.N/N.A.] |

### 80.2 Histórico

| Versão | Data | Data de status | Alteração | Motivo | Políticas afetadas | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [N.N] | [Data] | [Data] | [Preencher] | [ID/motivo] | [IDs] | [Nome] | [ID/N.A.] |

### 80.3 Regras de versionamento

- movimentações ordinárias de item pertencem ao histórico operacional, não a nova versão do template preenchido;
- mudança de estados, políticas, limites, classes, autoridade ou fonte oficial produz versão recuperável;
- correção de evento preserva valor anterior;
- exportações declaram versão das políticas e data de status;
- sistemas substituídos permanecem acessíveis conforme retenção;
- nova ferramenta não redefine IDs dos itens;
- mudança de arquitetura exige referências às decisões e linhas de base correspondentes.

---

## 81. Critérios de conclusão do sistema de fluxo

O sistema pode ser considerado concluído para configuração e uso do horizonte declarado quando:

- identidade, escopo, fontes, versões e responsáveis estão definidos;
- unidade de fluxo, tipos e identificadores estão consistentes;
- canais de entrada, triagem e qualificação possuem regras;
- origem, critério, responsabilidade e evidência são obrigatórios em itens materiais;
- backlog, fila elegível e fluxo comprometido permanecem distintos;
- ponto de compromisso e autorização aplicável estão explícitos;
- estados possuem políticas observáveis de entrada e saída;
- limites correspondem à capacidade e incluem verificação;
- classes de serviço e urgências possuem critérios e autoridade;
- bloqueios, esperas, envelhecimento e retrabalho são registráveis;
- trabalho humano, dados, tecnologia e IA recebem tratamento proporcional;
- cadências produzem coordenação, decisão e aprendizagem identificáveis;
- indicadores possuem definição, fonte, contexto e decisão apoiada;
- EAI, cronograma, matriz e registros especializados podem ser sincronizados;
- mudanças, exceções e trabalho emergente possuem rotas governadas;
- segurança, acesso, histórico, exportação e continuidade estão preparados;
- o teste de reconstrução é satisfatório;
- nenhuma coluna ou política ultrapassa gate ou muda arquitetura.

### 81.1 Resultado

- [ ] Concluído para o horizonte declarado
- [ ] Concluído com condições
- [ ] Requer complementação
- [ ] Requer reconfiguração
- [ ] Requer decisão de autoridade
- [ ] Requer retorno ao Módulo 3
- [ ] Suspenso
- [ ] Cancelado

| Campo | Registro |
| --- | --- |
| Objeto/horizonte examinado | [IDs/período] |
| Resultado | [Selecionar] |
| Condições/lacunas | [IDs/nenhuma] |
| Políticas aprovadas | [IDs/versões] |
| Trabalho que pode ser preparado | [IDs/tipos] |
| Trabalho condicionado ao `PI-2` ou outro gate | [IDs/tipos] |
| Próximo movimento permitido | [Completar planejamento / verificar prontidão / submeter PI-2 / executar objeto autorizado / reconfigurar / retornar / outro] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Data | [Data] |
| Evidência | [ID/link] |

Conclusão deste instrumento demonstra que demanda e fluxo podem ser governados no horizonte. Não demonstra prontidão integral, execução, entrega validada, capacidade implantada, aceite ou transição.

---

## 82. Registro final do template

| Campo | Registro |
| --- | --- |
| Identificador do template | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` |
| Módulo | 4 — Implantação |
| Tipo | Template operacional |
| Função | Governar demanda, compromisso, estados, capacidade, bloqueios e fluxo real da implantação |
| Entrada principal | Plano, Estrutura Analítica e Cronograma Mestre vigentes |
| Saída principal | Backlog qualificado, quadro Kanban e políticas de fluxo ativos e recuperáveis |
| Gate relacionado | `PI-2`, com uso continuado em `PI-3`, `PI-4` e `PI-5` |
| Documento anterior | `templates/04-cronograma-mestre-da-implantacao.md` |
| Documento seguinte | `templates/06-matriz-de-rastreabilidade-da-implantacao.md` |
| Fonte oficial | Repositório do Sistema Operacional do Estúdio LICHTARA |
| Responsabilidade final | Humana |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação integral do Backlog e Quadro Kanban da Implantação. | Estúdio LICHTARA |
