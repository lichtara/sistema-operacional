# Índice de Arquiteturas

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Diretório:** `registros-de-arquitetura/`  
**Tipo:** Registro transversal, catálogo oficial e instrumento de acompanhamento  
**Versão:** 0.1  
**Estado:** Ativo  
**Data de criação:** 02/08/2026  
**Responsável pela manutenção:** [Nome/papel]  
**Última revisão:** [DD/MM/AAAA]

**Documentos relacionados:**

- `README.md` deste diretório;
- `02-registro-de-arquitetura.md`;
- `../01-fundamentos-da-arquitetura-organizacional.md`;
- `../02-protocolo-de-arquitetura-organizacional.md`;
- `../03-matriz-de-rastreabilidade.md`;
- `../templates/01-termo-de-abertura-da-arquitetura.md`;
- `../templates/05-arquitetura-integrada.md`;
- `../templates/07-relatorio-de-arquitetura.md`;
- `../templates/08-transicao-para-implantacao.md`;
- `../templates/09-retrospectiva-da-arquitetura.md`.

---

## 1. Finalidade

Este índice é a porta de entrada para localizar, acompanhar e governar transversalmente todos os projetos de arquitetura organizacional do Estúdio LICHTARA.

Ele permite:

- reservar identificadores sem colisão;
- reconhecer que arquiteturas existem;
- localizar o manifesto mestre de cada dossiê;
- acompanhar estado, responsável e próxima ação;
- identificar linhas de base vigentes;
- visualizar decisões, condições e bloqueios materiais;
- localizar arquiteturas em transição, suspensas, reabertas ou substituídas;
- reconhecer relações e dependências entre projetos;
- revisar integridade e atualidade dos registros;
- apoiar capacidade, priorização, segurança e aprendizagem;
- preservar projetos encerrados sem tratá-los como trabalho ativo.

## 2. Pergunta central

> Que arquiteturas existem, onde estão seus dossiês, em que estado se encontram, quem responde pelo próximo movimento, qual referência está vigente e que condição exige atenção ou decisão?

## 3. Resultado esperado

Uma pessoa autorizada deve conseguir, a partir deste arquivo:

1. encontrar qualquer projeto pelo ID;
2. distinguir projeto ativo, encerrado, suspenso, cancelado, reaberto ou substituído;
3. abrir o manifesto correto;
4. identificar o responsável vigente;
5. conhecer a próxima ação ou condição de espera;
6. localizar a linha de base aprovada;
7. reconhecer restrições de acesso;
8. identificar relações entre arquiteturas;
9. detectar registros desatualizados;
10. iniciar uma nova reserva sem reutilizar ID.

## 4. Natureza do índice

O índice é um registro transversal de descoberta e acompanhamento. Ele replica somente os metadados necessários para localizar e governar o portfólio.

| Objeto | Função | Fonte substantiva? |
| --- | --- | --- |
| Índice | Localizar e acompanhar projetos | Não |
| Manifesto do dossiê | Explicar identidade, estado e rotas de leitura | Sim para metadados do projeto |
| Artefato específico | Manter requisitos, desenho, decisão ou validação | Sim para seu objeto |
| Linha de base | Determinar versões aprovadas | Sim para vigência |

### 4.1 Regra de autoridade

O índice aponta para fontes oficiais. Não altera requisito, decisão, componente, risco, validação ou linha de base.

## 5. O que o índice não é

Este arquivo não é:

- relatório de arquitetura;
- dossiê completo;
- arquitetura integrada;
- matriz de rastreabilidade entre objetos;
- lista de tarefas detalhada;
- cronograma de implantação;
- repositório de dados confidenciais;
- substituto do manifesto mestre;
- fonte para editar a linha de base;
- mecanismo automático de aprovação;
- quadro que elimina registros encerrados para parecer menor.

## 6. Posição no sistema de registros

```text
README do diretório
  -> governa regras
01-indice-de-arquiteturas.md
  -> localiza e acompanha o portfólio
02-registro-de-arquitetura.md
  -> origina o manifesto de cada dossiê
AAAA/ARQ-AAAA-NNN-nome/README.md
  -> governa o projeto real
artefatos e linhas de base
  -> mantêm conteúdo e vigência
```

## 7. Princípios

1. **Descoberta sem duplicação** — o índice mantém metadados, não cópias substantivas.
2. **ID antes do título** — nomes mudam; identificadores permanecem.
3. **Estado único vigente** — cada projeto possui um estado atual.
4. **Próximo movimento visível** — projeto ativo possui ação ou condição de espera.
5. **Fonte localizável** — toda linha aponta para manifesto existente.
6. **Acesso proporcional** — descoberta não justifica exposição.
7. **Histórico preservado** — cancelado, substituído ou encerrado não desaparece.
8. **Atualização no evento** — mudança material atualiza índice e manifesto.
9. **Vocabulário controlado** — estados e relações não são inventados localmente.
10. **Responsabilidade humana** — automações verificam; pessoas autorizam mudanças.

## 8. Invariantes

- nenhum ID é reutilizado;
- toda linha real possui manifesto;
- todo manifesto real possui uma linha no índice;
- uma arquitetura aparece uma única vez na tabela mestra;
- reservas não confirmadas permanecem distinguíveis de projetos abertos;
- estado do índice corresponde ao manifesto;
- linha de base só é informada quando existe manifesto aprovado;
- projeto ativo possui responsável e próxima ação;
- projeto suspenso possui gatilho e revisão;
- projeto substituído aponta para sucessor;
- classificação de acesso usa vocabulário autorizado;
- dados confidenciais são reduzidos ou codificados;
- mudanças deixam histórico;
- views não se tornam fontes paralelas.

## 9. Unidade indexada

Cada linha da tabela mestra representa um projeto de arquitetura identificado por:

```text
ARQ-AAAA-NNN
```

O índice não cria linhas separadas para versões, alternativas, componentes, ciclos de validação ou linhas de base. Esses objetos aparecem como campos ou relações do mesmo projeto.

## 10. Identificação deste arquivo

| Campo | Registro |
| --- | --- |
| Nome canônico | `01-indice-de-arquiteturas.md` |
| Diretório | `registros-de-arquitetura/` |
| Versão | 0.1 |
| Estado | Ativo |
| Responsável | [Nome/papel] |
| Fonte de estados | Protocolo de Arquitetura |
| Fonte de caminhos | Manifestos dos dossiês |
| Frequência de revisão | [Preencher] |

## 11. Estado do próprio índice

Selecione um estado vigente:

- [x] **Ativo** — recebe atualizações e representa o portfólio vigente.
- [ ] **Em revisão estrutural** — campos ou regras estão sendo alterados sob controle.
- [ ] **Substituído** — outro índice passou a ser a referência.
- [ ] **Encerrado** — o diretório deixou de operar e seu histórico foi preservado.

## 12. Governança

| Ação | Executa | Aprova/autoriza | Evidência |
| --- | --- | --- | --- |
| Reservar ID | [Papel] | [Papel/regra] | Registro de reserva |
| Confirmar abertura | [Papel] | [Papel] | Termo/aceite |
| Atualizar metadados | [Papel] | [Papel] | Manifesto |
| Alterar vocabulário | [Papel] | [Governança do Módulo 3] | Decisão |
| Corrigir divergência | [Papel] | [Responsável semântico] | Registro de correção |
| Arquivar visão | [Papel] | [Papel] | Histórico |
| Alterar acesso | [Papel] | [Autoridade] | Decisão/registro |

## 13. Responsabilidades

| Papel | Responsabilidade |
| --- | --- |
| Curador do índice | Integridade, unicidade, estrutura e revisões |
| Responsável pela arquitetura | Correção dos metadados do projeto |
| Aprovador/decisor | Autorizar estados e linhas de base quando aplicável |
| Responsável por acesso | Confirmar classificação e público autorizado |
| Revisor | Verificar sincronização e evidências |
| Responsável pela implantação | Confirmar recebimento quando o estado depende da passagem |

### 13.1 Responsável ausente

Registro ativo sem responsável deve ser tratado como anomalia. Atribua custódia provisória, limite mudanças e escale.

## 14. Instruções de uso

1. consulte a tabela mestra antes de reservar ID;
2. registre reservas na seção própria;
3. crie a pasta e o manifesto antes de confirmar abertura;
4. adicione uma única linha à tabela mestra;
5. use os vocabulários deste arquivo;
6. mantenha descrições curtas e não confidenciais;
7. atualize eventos materiais no mesmo ciclo;
8. derive visões a partir da tabela mestra;
9. corrija divergências com o manifesto;
10. preserve registros encerrados;
11. versiona mudanças estruturais do índice;
12. revise links e atualidade periodicamente.

## 15. Regra de não duplicação

| Conteúdo | Manter no índice? | Fonte completa |
| --- | --- | --- |
| ID, título reduzido, estado e caminho | Sim | Manifesto |
| Próxima ação resumida | Sim | Manifesto/plano |
| Requisito detalhado | Não | Catálogo |
| Componentes | Não, salvo metadado agregado | Arquitetura Integrada |
| Decisão completa | Não | Registro `DEC` |
| Risco detalhado | Não | Artefato de risco/arquitetura |
| Resultado de validação | Apenas síntese/estado | Registro `VAL` |
| Linha de base | ID e versão vigente | Manifesto `LB` |

## 16. Classificação de acesso

Na ausência de taxonomia contratual específica:

| Classe | Significado no índice |
| --- | --- |
| Público | Título, escopo e manifesto podem ser divulgados conforme autorização |
| Interno | Metadados acessíveis apenas ao Estúdio |
| Confidencial | Título ou cliente pode exigir codificação e acesso limitado |
| Restrito | Linha deve revelar somente ID, estado mínimo e guardião autorizado |

### 16.1 Regra de minimização

Se o título ou o nome do cliente revelar informação protegida, utilize código ou descrição neutra. O caminho da pasta também deve respeitar essa proteção.

## 17. Visões e públicos

| Público | Visão adequada | Conteúdo omitido |
| --- | --- | --- |
| Curadoria | Completa | Somente segredos desnecessários |
| Responsáveis ativos | Projetos sob sua atuação | Conteúdo de outros clientes |
| Liderança | Estado, riscos e decisões | Detalhes sensíveis sem uso decisório |
| Implantação | Aprovadas/em transição | Projetos sem relação |
| Conhecimento | Encerradas e aprendizados autorizados | Dados de cliente |
| Auditoria/revisão | Evidências conforme escopo | Conteúdo fora da autorização |

## 18. Vocabulário de estados

Use exclusivamente:

| Grupo | Estados permitidos |
| --- | --- |
| Entrada | Transição recebida; em aceite; aceita; aceita com condições; devolvida ao diagnóstico |
| Abertura e planejamento | Em abertura; aguardando aprovação de abertura; planejada |
| Desenho | Em requisitos; em alternativas; em desenho; em integração; em avaliação |
| Decisão e consolidação | Aguardando decisão; em consolidação; em validação; em revisão; aguardando aprovação |
| Aprovação e passagem | Aprovada; aprovada com condições; em transição para implantação |
| Encerramento e exceção | Encerrada; suspensa; cancelada; reaberta; substituída |

### 18.1 Capitalização

Na tabela mestra, utilize as formas apresentadas. Variação editorial não cria novo estado.

## 19. Relações entre arquiteturas

| Relação | Uso |
| --- | --- |
| `deriva_de` | Nova arquitetura nasce de outra |
| `complementa` | Cobre capacidade relacionada sem substituição |
| `depende_de` | Necessita resultado de outro projeto |
| `substitui` | Assume referência antes governada por outra arquitetura |
| `é_substituída_por` | Aponta para a sucessora |
| `reabre` | Retoma a mesma continuidade histórica quando houver novo ID relacionado |
| `compartilha_componente_com` | Possui componente governado entre dossiês |

## 20. Situação de atenção

Este campo não substitui o estado. Utilize:

| Situação | Significado |
| --- | --- |
| Normal | Próximo movimento e condições estão sob controle |
| Atenção | Existe risco, atraso ou pendência que exige acompanhamento |
| Bloqueada | Condição impede avanço |
| Decisão pendente | Autoridade precisa escolher ou aceitar |
| Em escalonamento | Questão foi elevada à instância competente |
| Sem próxima ação | Continuidade não está governada |

## 21. Prioridade do acompanhamento

| Prioridade | Critério |
| --- | --- |
| Crítica | Direitos, segurança, continuidade ou decisão urgente em risco |
| Alta | Gate, prazo ou dependência material próximo |
| Média | Trabalho ativo dentro do curso esperado |
| Baixa | Acompanhamento sem urgência material |
| Arquivada | Sem acompanhamento ativo; histórico preservado |

Prioridade não altera importância estratégica do projeto; indica necessidade de atenção do portfólio.

## 22. Atualidade do registro

| Situação | Regra sugerida |
| --- | --- |
| Atual | Conferido após o último evento material |
| Revisão próxima | Data de revisão se aproxima |
| Desatualizado | Evento material não foi refletido ou prazo venceu |
| Desconhecido | Não há evidência suficiente para afirmar atualidade |

## 23. Campos da tabela mestra

| Campo | Função | Obrigatório? |
| --- | --- | --- |
| ID | Identidade estável | Sim |
| Título público/reduzido | Localização compreensível | Sim |
| Cliente/unidade | Contexto protegido | Conforme escopo |
| Ano | Organização e sequência | Sim |
| Estado | Situação no protocolo | Sim |
| Atenção | Condição operacional | Sim para ativos |
| Prioridade | Necessidade de acompanhamento | Sim para ativos |
| Responsável | Próximo movimento | Sim |
| Abertura | Referência temporal | Sim |
| Última atualização | Atualidade | Sim |
| Próxima ação/condição | Continuidade | Sim para não encerrados |
| Prazo/gatilho | Momento da ação | Sim quando aplicável |
| Linha de base | Referência aprovada | Quando existir |
| Relações | Continuidade entre projetos | Quando existir |
| Acesso | Proteção | Sim |
| Manifesto | Porta de entrada | Sim |

## 24. Regras dos campos

### 24.1 ID

Use `ARQ-AAAA-NNN`. Não inclua versão no ID.

### 24.2 Título

Descreva o objeto da arquitetura, não a solução escolhida. Use forma neutra quando necessário.

### 24.3 Responsável

Registre nome ou papel autorizado. Se houver substituto temporário, indique vigência no manifesto.

### 24.4 Próxima ação

Use verbo e objeto: “validar requisitos com a liderança”, não “acompanhamento”.

### 24.5 Prazo ou gatilho

Use data quando conhecida ou evento observável. Evite “em breve”.

### 24.6 Linha de base

Informe `LB-ARQ-NNN`, versão e, quando útil, data. Não preencha antes da aprovação.

### 24.7 Manifesto

Use link relativo para `AAAA/ARQ-.../README.md`.

## 25. Resumo do portfólio

Preencher a partir da tabela mestra.

| Medida | Quantidade | Data de corte | Observação |
| --- | --- | --- | --- |
| Total de arquiteturas | [N] | [Data] | Inclui todos os estados |
| Ativas | [N] | [Data] | Estados anteriores ao encerramento |
| Aguardando decisão/aprovação | [N] | [Data] | [Preencher] |
| Em transição | [N] | [Data] | [Preencher] |
| Suspensas | [N] | [Data] | [Preencher] |
| Reabertas | [N] | [Data] | [Preencher] |
| Encerradas | [N] | [Data] | [Preencher] |
| Canceladas | [N] | [Data] | [Preencher] |
| Substituídas | [N] | [Data] | [Preencher] |
| Com linha de base vigente | [N] | [Data] | [Preencher] |
| Desatualizadas | [N] | [Data] | [Preencher] |

## 26. Próximo sequencial por ano

| Ano | Maior ID atribuído | IDs reservados | Próximo candidato | Conferido em | Responsável |
| --- | --- | --- | --- | --- | --- |
| AAAA | ARQ-AAAA-NNN | [IDs/nenhum] | ARQ-AAAA-NNN | [Data] | [Nome/papel] |

O “próximo candidato” não constitui reserva. Confirme novamente a tabela mestra e as reservas antes de usar.

## 27. Reservas de identificador

| ID | Data | Solicitante | Objeto provisório | Prazo de confirmação | Estado da reserva | Motivo/resultado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Data] | [Nome/papel] | [Descrição neutra] | [Data] | [Reservada, confirmada, liberada ou não utilizada] | [Preencher] |

### 27.1 Regras da reserva

- reserva possui prazo;
- somente papel autorizado confirma;
- confirmação exige pasta e manifesto;
- ID que circulou não é reutilizado;
- liberação preserva histórico;
- reserva vencida exige revisão, não reaproveitamento automático.

## 28. Tabela mestra de arquiteturas

> Substitua a linha de preenchimento por registros reais. Ela não representa uma arquitetura aberta.

| ID | Título público/reduzido | Cliente/unidade | Ano | Estado | Atenção | Prioridade | Responsável | Abertura | Última atualização | Próxima ação/condição | Prazo/gatilho | Linha de base | Relações | Acesso | Manifesto |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Título] | [Nome/código] | AAAA | [Estado] | [Situação] | [Prioridade] | [Nome/papel] | [Data] | [Data] | [Ação ou condição] | [Data/evento] | [LB/versão/N/A] | [IDs/relações] | [Classe] | [Link relativo] |

## 29. Registro expandido de referência

Use quando uma linha precisar de metadados adicionais sem duplicar o manifesto.

| Campo | Registro |
| --- | --- |
| Projeto | ARQ-AAAA-NNN |
| Título completo autorizado | [Preencher] |
| Código público | [Preencher] |
| Capacidade principal | [Síntese/ID] |
| Gate atual | [PC-1 a PC-5/N/A] |
| Decisão pendente | [ID/síntese/N/A] |
| Condição impeditiva | [ID/síntese/N/A] |
| Validação vigente | [VAL/versão/N/A] |
| Transição | [TRA/estado/N/A] |
| Retrospectiva | [RET/estado/N/A] |
| Custodiante histórico | [Nome/papel] |

## 30. Inclusão de uma nova arquitetura

1. investigar duplicidade;
2. consultar tabela mestra e reservas;
3. reservar ID;
4. criar pasta anual e pasta do projeto;
5. copiar `02-registro-de-arquitetura.md` para o `README.md` do dossiê;
6. preencher identificação, acesso, estado e próxima ação;
7. confirmar abertura;
8. adicionar linha à tabela mestra;
9. atualizar próximo sequencial;
10. registrar mudança deste índice.

## 31. Confirmação da abertura

| Verificação | Resultado | Evidência |
| --- | --- | --- |
| ID é único? | [Sim/não] | [Tabela/reserva] |
| Pasta corresponde ao ID? | [Sim/não] | [Caminho] |
| Manifesto existe? | [Sim/não] | [Link] |
| Responsável está atribuído? | [Sim/não] | [Registro] |
| Acesso está classificado? | [Sim/não] | [Registro] |
| Estado é permitido? | [Sim/não] | [Protocolo] |
| Próxima ação está definida? | [Sim/não] | [Manifesto] |

## 32. Gatilhos de atualização

Atualize a linha quando houver:

- confirmação ou liberação de ID;
- mudança de estado;
- alteração de título público;
- troca de responsável;
- mudança de atenção ou prioridade;
- próxima ação concluída ou substituída;
- prazo vencido;
- aprovação de linha de base;
- nova relação entre arquiteturas;
- suspensão, cancelamento ou reabertura;
- substituição;
- aceite da implantação;
- encerramento;
- mudança de acesso;
- alteração do caminho.

## 33. Atualização coordenada

| Evento | Atualizar primeiro | Atualizar em seguida | Evidência |
| --- | --- | --- | --- |
| Mudança de estado | Manifesto | Índice | Histórico/decisão |
| Nova linha de base | Manifesto `LB` e projeto | Índice | Aprovação |
| Troca de responsável | Manifesto | Índice | Transferência |
| Reabertura | Decisão e manifesto | Índice | Gatilho |
| Substituição | Projetos relacionados | Índice | Decisão/vigência |
| Mudança de acesso | Fonte de autorização | Manifesto e índice | Registro |

## 34. Histórico de estados no índice

O histórico detalhado permanece no manifesto. Registre aqui eventos transversais quando úteis ao portfólio.

| Projeto | Estado anterior | Novo estado | Data | Motivo/gate | Responsável | Índice atualizado por |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [Estado] | [Data] | [Preencher] | [Nome/papel] | [Nome/data] |

## 35. Visão de projetos ativos

| ID | Estado | Gate | Responsável | Próxima ação | Prazo/gatilho | Atenção | Manifesto |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [PC] | [Nome/papel] | [Preencher] | [Preencher] | [Situação] | [Link] |

## 36. Visão de entrada e aceite

| ID | Estado | Origem | Responsável pelo aceite | Lacuna/condição | Prazo | Resultado esperado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Transição recebida/em aceite/aceita com condições/devolvida] | [ID/referência] | [Nome/papel] | [Síntese/ID] | [Data] | [Aceitar, condicionar, devolver ou encerrar] |

## 37. Visão de abertura e planejamento

| ID | Estado | Termo | Plano | Decisor/patrocinador | Próximo marco | Pendência |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [ID/versão] | [ID/versão] | [Nome/papel] | [Preencher] | [Preencher] |

## 38. Visão de requisitos e alternativas

| ID | Estado | Catálogo | Requisitos impeditivos abertos | Alternativas | Avaliação | Decisão necessária |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [ID/versão] | [N/IDs] | [N/IDs] | [ID/estado] | [Síntese/ID] |

## 39. Visão de desenho e integração

| ID | Estado | Dimensões materiais | Arquitetura integrada | Interface crítica aberta | Responsável | Próximo gate |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [Lista/quantidade] | [ID/versão/estado] | [Síntese/ID] | [Nome/papel] | [PC] |

## 40. Visão de decisão

| ID | Decisão | Autoridade | Data necessária | Alternativas admissíveis | Risco/condição | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [ID/síntese] | [Nome/papel] | [Data] | [IDs] | [IDs/síntese] | [Aguardando, emitida ou escalada] |

### 40.1 Decisão pendente

Uma decisão somente entra nesta visão quando possui objeto, autoridade e consequência identificáveis. “Precisamos alinhar” não constitui decisão formulada.

## 41. Visão de validação

| ID | Arquitetura/objeto | Ciclo | Versão examinada | Resultado | Apontamentos impeditivos | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [ID] | VAL-ARQ-AAAA-NNN | [Versão] | [Estado] | [N/IDs] | [Tratar, revalidar ou aprovar] |

## 42. Visão de aprovação e linha de base

| ID | Estado | Arquitetura integrada | Linha de base | Versão | Aprovador | Condições | Vigência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Aprovada/aprovada com condições] | [ID/versão] | LB-ARQ-NNN | [Versão] | [Nome/papel] | [IDs/nenhuma] | [Data] |

## 43. Visão de transição para implantação

| ID | Linha de base | Transição | Responsável M3 | Responsável M4 | Recebimento | Pendências | Próximo gate |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [LB/versão] | [TRA/estado] | [Nome/papel] | [Nome/papel] | [Resultado/data] | [IDs/síntese] | PC-5 |

## 44. Visão de condições e bloqueios

| ID | Condição/bloqueio | Tipo | Impacto | Responsável | Prazo/gatilho | Escalonamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [ID/síntese] | [Entrada, decisão, recurso, validação, acesso ou outro] | [Preencher] | [Nome/papel] | [Preencher] | [Nome/papel/N/A] | [Aberta/tratada] |

## 45. Visão por responsável

| Responsável | Projetos ativos | Próximas ações | Decisões pendentes | Bloqueios | Capacidade/observação |
| --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [IDs] | [N/síntese] | [N/IDs] | [N/IDs] | [Preencher] |

### 45.1 Carga não é contagem simples

Quantidade de projetos não representa esforço sem considerar estado, risco, profundidade e proximidade dos gates.

## 46. Visão por ano

| Ano de abertura | Total | Ativas | Encerradas | Canceladas | Substituídas | Próximo sequencial |
| --- | --- | --- | --- | --- | --- | --- |
| AAAA | [N] | [N] | [N] | [N] | [N] | ARQ-AAAA-NNN |

Projetos reabertos permanecem no ano do ID original.

## 47. Visão por cliente ou unidade

| Cliente/unidade autorizada | Projetos | Ativos | Linhas de base vigentes | Relações | Acesso |
| --- | --- | --- | --- | --- | --- |
| [Nome/código] | [IDs] | [N] | [IDs] | [Síntese] | [Classe] |

### 47.1 Proteção

Use código quando a própria existência do cliente, unidade ou projeto for confidencial.

## 48. Visão por capacidade

| Capacidade | Projetos | Estado consolidado | Arquitetura vigente | Dependência | Observação |
| --- | --- | --- | --- | --- | --- |
| CAP-___/[síntese] | [ARQ IDs] | [Preencher] | [ARQ/LB] | [IDs] | [Preencher] |

Esta visão apoia descoberta e relações. A definição oficial da capacidade permanece no dossiê correspondente.

## 49. Visão de próximas ações

| Prazo/gatilho | ID | Ação | Responsável | Dependência | Atenção | Consequência se não ocorrer |
| --- | --- | --- | --- | --- | --- | --- |
| [Data/evento] | ARQ-AAAA-NNN | [Verbo e objeto] | [Nome/papel] | [ID/N/A] | [Situação] | [Preencher] |

## 50. Visão de prazos vencidos

| ID | Ação/condição | Prazo | Dias/condição de atraso | Responsável | Impacto | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Preencher] | [Data] | [Preencher] | [Nome/papel] | [Preencher] | [Atualizar, escalar, suspender ou revisar] |

Prazo vencido exige nova informação no índice; não deve permanecer como se ainda orientasse o trabalho.

## 51. Visão de registros sem próxima ação

| ID | Estado | Última atualização | Responsável vigente | Motivo da ausência | Ação corretiva |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado] | [Data] | [Nome/papel/N/A] | [Preencher] | [Atribuir, suspender, encerrar ou corrigir] |

## 52. Visão de atenção e escalonamento

| ID | Situação | Questão | Impacto | Instância | Data de escalonamento | Resultado esperado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Atenção/bloqueada/decisão pendente/em escalonamento] | [Síntese] | [Preencher] | [Papel] | [Data] | [Preencher] |

## 53. Visão de acesso

| ID | Classe | Título protegido? | Manifesto acessível a | Exceções | Responsável por acesso | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Classe] | [Sim/não] | [Papéis] | [Preencher] | [Nome/papel] | [Data] |

## 54. Visão de arquiteturas suspensas

| ID | Data da suspensão | Motivo | Risco durante suspensão | Guardião | Gatilho de retomada | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Data] | [Síntese/decisão] | [Preencher] | [Nome/papel] | [Evento] | [Data] |

## 55. Visão de arquiteturas canceladas

| ID | Data | Autoridade | Motivo | Última versão válida | Ativos reutilizáveis | Destino dos registros |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Data] | [Nome/papel] | [Síntese] | [Versão/N/A] | [Referências] | [Arquivar/eliminar conforme regra] |

## 56. Visão de arquiteturas reabertas

| ID | Linha de base anterior | Gatilho | Data | Escopo reaberto | Etapa retomada | Autoridade | Próximo gate |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [LB/versão] | [Evento/evidência] | [Data] | [Preencher] | [Etapa] | [Nome/papel] | [PC] |

## 57. Visão de arquiteturas substituídas

| ID substituído | Linha de base anterior | ID sucessor | Nova linha de base | Data de vigência | Decisão | Pendências transferidas |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [LB/versão] | ARQ-AAAA-NNN | [LB/versão] | [Data] | DEC-AAAA-NNN | [IDs] |

## 58. Visão de arquiteturas encerradas

| ID | Data de encerramento | Referência final | Transição | Retrospectiva | Custodiante | Revisão futura |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Data] | [LB/versão] | [Aceita/N/A] | [RET/estado] | [Nome/papel] | [Data/evento] |

## 59. Relações entre projetos

| Origem | Relação | Destino | Estado da relação | Decisão/evidência | Impacto |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Relação controlada] | ARQ-AAAA-NNN | [Proposta/aprovada/encerrada] | [ID] | [Preencher] |

## 60. Dependências entre arquiteturas

| Projeto dependente | Depende de | Resultado necessário | Data/condição | Responsável | Risco | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | ARQ-AAAA-NNN | [Capacidade, decisão ou componente] | [Preencher] | [Nome/papel] | [Síntese/ID] | [Aberta/tratada] |

### 60.1 Dependência circular

Se dois projetos dependem do resultado um do outro, registre o estado temporário, a sequência de desbloqueio ou a decisão de integração.

## 61. Componentes compartilhados

| Componente/capacidade | Arquiteturas | Fonte governante | Responsável | Mudança exige consulta a | Estado |
| --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [ARQ IDs] | [Dossiê/linha de base] | [Papel] | [Projetos/papéis] | [Preencher] |

O índice revela compartilhamento; a governança do componente permanece no artefato autorizado.

## 62. Capacidade do portfólio

| Período | Pessoas/papéis | Projetos simultâneos | Gates próximos | Restrições | Decisão de capacidade |
| --- | --- | --- | --- | --- | --- |
| [Período] | [Preencher] | [IDs/N] | [Lista] | [Preencher] | [Priorizar, pausar, ampliar ou redistribuir] |

## 63. Marcos do portfólio

| Data/período | Projeto | Marco | Gate | Dependência | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [Data] | ARQ-AAAA-NNN | [Preencher] | [PC/N/A] | [ID/N/A] | [Nome/papel] | [Planejado/concluído/revisto] |

## 64. Atualidade por evento

| Projeto | Último evento material | Data | Índice atualizado? | Manifesto atualizado? | Responsável |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Mudança de estado, decisão, LB ou outro] | [Data] | [Sim/não] | [Sim/não] | [Nome/papel] |

## 65. Registros desatualizados

| ID | Evidência de desatualização | Campo afetado | Risco | Correção | Prazo |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Evento/contradição] | [Estado, ação, LB, acesso ou outro] | [Preencher] | [Preencher] | [Data] |

## 66. Integridade dos links

| ID | Manifesto | Resultado do link | Última verificação | Ação |
| --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Caminho] | [Válido, quebrado ou acesso indisponível] | [Data] | [Corrigir, restaurar ou registrar] |

## 67. Sincronização com o manifesto

| ID | Campo | Valor no índice | Valor no manifesto | Fonte correta | Tratamento | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Estado, responsável, LB, acesso ou outro] | [Valor] | [Valor] | [Preencher] | [Corrigir/decidir] | [Nome/papel] |

### 67.1 Regra de divergência

Não escolha automaticamente o valor mais recente. Confirme autoridade, evento e versão; depois corrija todas as derivações.

## 68. Verificação da linha de base

| ID | LB indicada | Manifesto localizado? | Versões resolvidas? | Estado aprovado? | Divergência | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [LB/versão] | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] | [Preencher] |

## 69. Qualidade mínima de uma linha

- [ ] ID segue o padrão;
- [ ] título é compreensível e autorizado;
- [ ] estado pertence ao vocabulário;
- [ ] responsável existe;
- [ ] data de atualização está presente;
- [ ] projeto ativo possui próxima ação;
- [ ] prazo ou gatilho é observável;
- [ ] linha de base não foi inventada;
- [ ] relação usa vocabulário controlado;
- [ ] acesso está classificado;
- [ ] manifesto abre o dossiê correto.

## 70. Registro incompleto

| ID | Campo ausente | Motivo | Efeito | Responsável | Prazo | Estado permitido enquanto incompleto |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Campo] | [Preencher] | [Preencher] | [Nome/papel] | [Data] | [Preencher] |

Campo obrigatório ausente não deve ser preenchido por suposição apenas para “limpar” a tabela.

## 71. Correção factual

| ID | Campo | Valor incorreto | Valor correto | Evidência | Data | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Campo] | [Valor] | [Valor] | [Fonte] | [Data] | [Nome/papel] |

Correção de grafia ou link pode ser editorial. Mudança de estado, linha de base, acesso ou relação é material para o índice.

## 72. Registro de mudança do índice

| Versão | Data | Tipo | Alteração | Projetos afetados | Motivo/evidência | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Versão] | [Data] | [Editorial, metadado ou estrutural] | [Síntese] | [IDs/todos/nenhum] | [Preencher] | [Nome] | [Nome/N/A] |

## 73. Versionamento

| Mudança | Exemplo | Versão |
| --- | --- | --- |
| Atualização de linha de projeto | Estado, responsável ou próxima ação | Registrar no histórico; incremento conforme política |
| Correção editorial | Ortografia sem mudança de sentido | Incremento menor quando necessário |
| Campo novo | Inclusão de metadado | Nova versão do índice |
| Vocabulário ou regra | Mudança estrutural | Decisão e nova versão |
| Substituição do índice | Novo instrumento oficial | Encerrar versão anterior |

## 74. Frequência de atualização

| Evento/frequência | Ação |
| --- | --- |
| Evento material | Atualizar no mesmo ciclo |
| Revisão de trabalho | Conferir projetos ativos |
| Revisão mensal | Verificar atenção, prazos, responsáveis e decisões |
| Revisão trimestral | Verificar links, acessos, linhas de base e encerrados recentes |
| Revisão anual | Sequenciais, retenção, relações, portabilidade e estrutura |

## 75. Ritual de revisão

1. confirmar data de corte;
2. comparar índice e manifestos ativos;
3. examinar próximas ações vencidas;
4. identificar responsáveis sobrecarregados ou ausentes;
5. revisar decisões e gates próximos;
6. conferir linhas de base e transições;
7. revisar suspensos e gatilhos;
8. tratar divergências e links;
9. atualizar resumo do portfólio;
10. registrar mudanças e decisões.

## 76. Registro da revisão

| Revisão | Data de corte | Escopo | Participantes | Divergências | Correções | Decisões | Próxima revisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| REV-IDX-___ | [Data] | [Ativos, anual, acesso ou outro] | [Nomes/papéis] | [N/IDs] | [N/IDs] | [IDs] | [Data] |

## 77. Pesquisa

Campos adequados para busca:

- ID;
- título público;
- cliente ou código autorizado;
- ano;
- estado;
- responsável;
- capacidade principal;
- linha de base;
- relação;
- classificação de acesso;
- palavra-chave não confidencial.

### 77.1 Busca segura

O índice não deve incluir detalhes sensíveis apenas para melhorar recuperação. Use códigos e acesse o manifesto conforme autorização.

## 78. Filtros recomendados

| Necessidade | Filtro mínimo |
| --- | --- |
| Trabalho atual | Estados ativos + responsável |
| Decisões | Estado `Aguardando decisão` ou campo de decisão pendente |
| Aprovações | `Aguardando aprovação` e condições |
| Implantação | `Aprovada`, `Aprovada com condições` e `Em transição` |
| Continuidade | Suspensas, sem próxima ação e desatualizadas |
| Histórico | Encerradas, canceladas e substituídas |
| Aprendizagem | Encerradas com retrospectiva autorizada |
| Segurança | Classe de acesso e revisão vencida |

## 79. Ordenação

Ordene conforme a pergunta:

| Pergunta | Ordenação |
| --- | --- |
| O que exige ação primeiro? | Atenção, prioridade e prazo |
| O que está parado? | Última atualização ascendente |
| Que IDs estão disponíveis? | Ano e sequencial |
| O que vai à implantação? | Estado, gate e vigência |
| Que histórico é mais recente? | Encerramento descendente |

Não trate ordem de linhas como prioridade implícita.

## 80. Exportações e visões derivadas

| Exportação | Fonte | Data de corte | Filtros | Campos omitidos | Responsável | Validade |
| --- | --- | --- | --- | --- | --- | --- |
| [Nome] | 01-indice-de-arquiteturas.md [versão] | [Data] | [Preencher] | [Preencher] | [Nome/papel] | [Data/evento] |

Exportação não recebe atualização independente. Gere novamente a partir da fonte vigente.

## 81. Automação de verificações

Pode-se automatizar:

- validação do padrão `ARQ-AAAA-NNN`;
- detecção de IDs duplicados;
- cálculo do maior sequencial por ano;
- verificação de links para manifestos;
- detecção de estado fora do vocabulário;
- identificação de próxima ação ausente;
- alerta de prazo vencido;
- comparação entre estado do índice e manifesto;
- verificação de linha de base inexistente;
- geração de contagens e visões;
- identificação de placeholders em linhas reais.

### 81.1 Autoridade

Automação pode sinalizar e propor. Inclusão, mudança de estado, linha de base, acesso, cancelamento, substituição ou encerramento exigem regra e responsabilidade humana.

## 82. Apoio de inteligência artificial

IA pode apoiar:

- classificar solicitações para revisão;
- localizar divergências textuais;
- resumir próxima ação a partir do manifesto;
- sugerir relações entre projetos para verificação;
- identificar linhas potencialmente desatualizadas;
- produzir visões autorizadas;
- explicar o vocabulário do índice;
- gerar perguntas de revisão.

IA não deve:

- inventar projeto ou ID;
- preencher campo ausente por inferência não verificada;
- alterar estado ou prioridade;
- declarar linha de base;
- expor título confidencial;
- decidir cancelamento, reabertura ou substituição;
- eliminar histórico;
- atribuir responsabilidade a pessoa sem confirmação.

### 82.1 Registro de uso material

| Função | Entrada | Saída | Verificador | Correção | Efeito no índice |
| --- | --- | --- | --- | --- | --- |
| FIA-ARQ-___ | [Referências autorizadas] | [Preencher] | [Nome/papel] | [Sim/não] | [Nenhum/proposta/atualização validada] |

## 83. Indicadores de integridade

| Indicador | Definição | Fonte | Resposta |
| --- | --- | --- | --- |
| IDs duplicados | Quantidade de colisões | Tabela/reservas | Suspender e corrigir |
| Manifestos ausentes | Linhas sem porta de entrada | Links | Criar, restaurar ou encerrar |
| Divergência de estado | Índice diferente do manifesto | Verificação | Identificar fonte e corrigir |
| Ativos sem próxima ação | Projetos ativos sem continuidade | Tabela | Atribuir, suspender ou encerrar |
| Prazos vencidos | Ações com data ultrapassada | Tabela | Revisar e decidir |
| LB não resolvida | Referência aprovada sem manifesto válido | Tabela/dossiê | Impedir uso e restaurar |
| Acesso sem revisão | Classificação não conferida | Registro | Revisar autorização |

## 84. Indicadores de fluxo

| Indicador | Pergunta | Limite de interpretação |
| --- | --- | --- |
| Projetos por estado | Onde está o trabalho? | Não demonstra qualidade |
| Tempo entre estados | Onde há espera? | Exige contexto e complexidade |
| Decisões pendentes | Que autoridade precisa agir? | Não mede produtividade |
| Reaberturas | Que realidade mudou ou foi mal prevista? | Reabertura pode ser legítima |
| Cancelamentos | Que objeto deixou de seguir? | Não implica fracasso isoladamente |
| Transições aceitas | Que arquitetura chegou ao Módulo 4? | Aceite não demonstra implantação concluída |

## 85. Indicadores de aprendizagem

| Indicador | Fonte | Uso |
| --- | --- | --- |
| Retrospectivas concluídas | Dossiês encerrados | Cobrar fechamento do ciclo |
| Aprendizados destinados | RET e Módulo 6 | Verificar absorção |
| Critérios recorrentes | Avaliações | Melhorar templates |
| Premissas refutadas | Dossiês/operação | Melhorar previsões |
| Mudanças pós-LB | Controle de mudanças | Avaliar qualidade e contexto |
| Problemas documentais recorrentes | Revisões/incidentes | Evoluir governança |

## 86. Painel mínimo de revisão

| Pergunta executiva | Valor | Tendência/contexto | Ação |
| --- | --- | --- | --- |
| Quantos projetos exigem decisão? | [N] | [Preencher] | [Preencher] |
| Quantos estão bloqueados? | [N] | [Preencher] | [Preencher] |
| Que gates ocorrerão no próximo período? | [Lista] | [Preencher] | [Preencher] |
| Existe responsável sobrecarregado? | [Resultado] | [Preencher] | [Preencher] |
| Há linha de base ambígua? | [N] | [Preencher] | [Preencher] |
| Que suspensão precisa ser revista? | [IDs] | [Preencher] | [Preencher] |

## 87. Decisões apoiadas pelo índice

O índice pode apoiar:

- atribuição de responsável;
- priorização de atenção;
- escalonamento;
- revisão de capacidade;
- abertura ou integração de projetos;
- revisão de suspensão;
- necessidade de auditoria documental;
- planejamento de gates;
- seleção de dossiês para aprendizagem.

O índice não decide mérito técnico da arquitetura nem substitui autoridade do projeto.

## 88. Comunicação do portfólio

| Público | Pergunta | Visão | Responsável |
| --- | --- | --- | --- |
| Equipe de arquitetura | O que precisa avançar? | Ativos, ações e gates | [Papel] |
| Liderança | Onde há decisão, risco e capacidade? | Painel mínimo | [Papel] |
| Implantação | O que está autorizado para passagem? | Aprovação/transição | [Papel] |
| Curadoria | O que está inconsistente? | Integridade e atualidade | [Papel] |
| Conhecimento | Que projetos podem ensinar? | Encerrados autorizados | [Papel] |

## 89. Incidente no índice

Considere incidente:

- ID duplicado;
- linha removida indevidamente;
- estado alterado sem autoridade;
- linha de base incorreta;
- acesso ou título confidencial exposto;
- link direcionado ao dossiê errado;
- projeto substituído apresentado como vigente;
- automação sobrescrevendo registro;
- exportação desatualizada usada para decidir.

### 89.1 Registro

| ID do incidente | Data | Projeto(s) | Natureza | Impacto | Contenção | Responsável | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| INC-IDX-___ | [Data] | [ARQ IDs] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Preencher] |

## 90. Recuperação

1. interromper alterações não autorizadas;
2. preservar a versão afetada;
3. consultar manifestos e decisões;
4. restaurar a última referência confiável;
5. reconciliar eventos posteriores;
6. verificar todos os projetos afetados;
7. atualizar exportações;
8. registrar causa, impacto e melhoria.

## 91. Retenção das linhas

Uma linha não é eliminada apenas porque o projeto foi encerrado, cancelado ou substituído.

| Estado final | Tratamento no índice |
| --- | --- |
| Encerrada | Preservar com referência final |
| Cancelada | Preservar decisão, última versão e destino |
| Substituída | Preservar e apontar sucessor |
| Reserva não utilizada | Preservar no registro de reservas |

Eliminação depende de obrigação, finalidade e autoridade; o histórico mínimo de IDs deve permanecer suficiente para impedir reutilização e explicar lacunas.

## 92. Arquivamento de visões

Visões periódicas podem ser exportadas como evidência de determinado corte. Registre:

- fonte e versão;
- data de corte;
- filtros;
- finalidade;
- público;
- validade;
- condição de descarte.

Não arquive cópias sucessivas sem uso ou política de retenção.

## 93. Exemplo de linha ativa

| ID | Título público/reduzido | Cliente/unidade | Ano | Estado | Atenção | Prioridade | Responsável | Abertura | Última atualização | Próxima ação/condição | Prazo/gatilho | Linha de base | Relações | Acesso | Manifesto |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-2026-001 | Sistema editorial | Unidade A | 2026 | Em validação | Atenção | Alta | Arquiteta responsável | 02/08/2026 | 15/08/2026 | Tratar apontamentos impeditivos | 20/08/2026 | N/A | depende_de ARQ-2026-002 | Confidencial | `2026/ARQ-2026-001-sistema-editorial/README.md` |

### 93.1 Leitura do exemplo

A linha informa onde agir e onde buscar contexto. Não informa os apontamentos, a configuração ou os requisitos; esses conteúdos permanecem no manifesto e nos artefatos.

## 94. Exemplo de linha encerrada

| ID | Título público/reduzido | Cliente/unidade | Ano | Estado | Atenção | Prioridade | Responsável | Abertura | Última atualização | Próxima ação/condição | Prazo/gatilho | Linha de base | Relações | Acesso | Manifesto |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ARQ-2026-003 | Fluxo de propostas | Unidade B | 2026 | Encerrada | Normal | Arquivada | Custodiante documental | 05/08/2026 | 30/09/2026 | Revisão de retenção | 30/09/2027 | LB-ARQ-001 v1.0 | complementa ARQ-2026-004 | Interno | `2026/ARQ-2026-003-fluxo-de-propostas/README.md` |

## 95. Checklist de reserva e abertura

- [ ] duplicidade foi investigada;
- [ ] ano e maior sequencial foram conferidos;
- [ ] reservas existentes foram examinadas;
- [ ] papel autorizado reservou o ID;
- [ ] prazo da reserva foi definido;
- [ ] pasta e manifesto foram criados;
- [ ] classificação de acesso foi confirmada;
- [ ] responsável e próxima ação estão definidos;
- [ ] abertura foi confirmada;
- [ ] linha única foi incluída na tabela mestra;
- [ ] próximo sequencial foi recalculado.

## 96. Checklist de atualização

- [ ] evento material possui evidência;
- [ ] manifesto foi atualizado primeiro quando necessário;
- [ ] estado pertence ao vocabulário;
- [ ] responsável está confirmado;
- [ ] próxima ação é observável;
- [ ] prazo ou gatilho é válido;
- [ ] linha de base resolve para manifesto aprovado;
- [ ] relações são recíprocas quando necessário;
- [ ] acesso continua proporcional;
- [ ] visões derivadas foram atualizadas ou regeneradas;
- [ ] mudança foi registrada.

## 97. Checklist de revisão periódica

- [ ] data de corte está explícita;
- [ ] ativos foram comparados aos manifestos;
- [ ] projetos sem próxima ação foram tratados;
- [ ] prazos vencidos foram revistos;
- [ ] decisões e gates próximos estão visíveis;
- [ ] suspensões possuem revisão e gatilho;
- [ ] linhas de base foram verificadas;
- [ ] links materiais funcionam;
- [ ] divergências foram corrigidas;
- [ ] acessos foram revistos conforme calendário;
- [ ] resumo do portfólio foi atualizado;
- [ ] decisões da revisão foram registradas.

## 98. Checklist de encerramento, cancelamento ou substituição

- [ ] autoridade e data estão registradas;
- [ ] estado final corresponde ao manifesto;
- [ ] referência final está identificada;
- [ ] próxima ação ativa foi removida ou convertida em revisão histórica;
- [ ] prioridade foi ajustada para arquivada quando aplicável;
- [ ] custodiante está identificado;
- [ ] sucessor foi vinculado quando houver;
- [ ] retrospectiva ou justificativa está localizada;
- [ ] acesso e retenção foram revistos;
- [ ] a linha permaneceu no índice.

## 99. Antipadrões

- criar ID sem consultar reservas;
- apagar linha para reutilizar sequencial;
- registrar versões como projetos independentes;
- colocar vários projetos na mesma linha;
- criar uma linha por componente;
- copiar requisitos e riscos para o índice;
- usar título confidencial para facilitar busca;
- inventar estado como “quase pronto”;
- manter dois estados vigentes;
- alterar prioridade para manipular percepção;
- preencher linha de base antes da aprovação;
- registrar próxima ação como “acompanhar”;
- manter prazo vencido sem revisão;
- marcar projeto ativo sem responsável;
- tratar view manual como fonte oficial;
- usar exportação antiga para decisão atual;
- permitir que automação encerre ou reabra projeto;
- remover cancelados e substituídos;
- corrigir divergência sem consultar o manifesto;
- contar projetos sem considerar profundidade e gate.

## 100. Sinais de qualidade

O índice funciona quando:

- IDs são únicos e sequenciais;
- cada linha abre o manifesto correto;
- estado, responsável e próxima ação são confiáveis;
- linhas de base vigentes podem ser localizadas;
- projetos sem continuidade aparecem como exceção;
- decisões pendentes chegam à autoridade certa;
- informação confidencial permanece protegida;
- views podem ser regeneradas da tabela mestra;
- cancelamentos e substituições preservam história;
- o portfólio pode ser compreendido sem abrir todos os dossiês;
- abrir o dossiê continua sendo necessário para compreender o conteúdo.

## 101. Retrospectiva do índice

| Pergunta | Registro |
| --- | --- |
| Que campo apoiou decisões reais? | [Preencher] |
| Que campo foi mantido sem uso? | [Preencher] |
| Que divergência ocorreu com frequência? | [Preencher] |
| Que view reduziu trabalho? | [Preencher] |
| Que informação expôs risco desnecessário? | [Preencher] |
| Que regra de atualização falhou? | [Preencher] |
| Que automação pode ser testada? | [Preencher] |
| Que aprendizagem deve ir ao Módulo 6? | [Preencher] |
| Que mudança deve ser proposta ao Módulo 8? | [Preencher] |

## 102. Governança de mudanças estruturais

Exigem decisão:

- alterar o padrão de ID;
- incluir ou remover campo obrigatório;
- mudar vocabulário de estados;
- mudar classificação de acesso;
- alterar relação com o manifesto;
- mudar regra de reserva;
- alterar tratamento de encerrados;
- tornar automação autorizada a escrever;
- substituir a tabela mestra por outro sistema.

### 102.1 Migração

Mudança estrutural precisa informar:

- versão de origem e destino;
- mapeamento de campos;
- registros afetados;
- testes;
- tratamento de valores ausentes;
- plano de retorno;
- autoridade;
- data de vigência.

## 103. Histórico do índice

| Versão | Data | Alteração | Tipo | Projetos afetados | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | 02/08/2026 | Criação do índice e de suas visões operacionais | Estrutural | Nenhum registro real | [Nome] | [Registro] |

## 104. Critérios de conclusão

- [ ] finalidade, autoridade e limites estão explícitos;
- [ ] tabela mestra possui uma linha por projeto;
- [ ] reservas e próximo sequencial estão governados;
- [ ] estados correspondem ao protocolo;
- [ ] atenção, prioridade e atualidade estão diferenciadas;
- [ ] campos obrigatórios possuem regras;
- [ ] visões cobrem o ciclo e as exceções;
- [ ] índice, manifesto e linha de base mantêm funções distintas;
- [ ] acesso e minimização estão tratados;
- [ ] atualização, divergência e versionamento estão governados;
- [ ] automação e IA possuem limites humanos;
- [ ] indicadores possuem resposta associada;
- [ ] incidentes, recuperação e retenção estão definidos;
- [ ] exemplos e checklists permitem uso imediato;
- [ ] próximo documento do diretório está indicado.

## 105. Princípio de encerramento

Um índice confiável reduz a distância entre saber que um projeto existe e compreender onde a responsabilidade precisa agir.

Seu valor não está na quantidade de campos, mas na fidelidade com que preserva identidade, estado, próxima ação, vigência e caminho para a fonte oficial. Quando o índice tenta conter toda a arquitetura, duplica o dossiê; quando contém pouco demais, deixa de orientar. Sua forma adequada é a menor estrutura capaz de manter o portfólio visível, seguro e governável.

No Estúdio LICHTARA, nenhum projeto desaparece por ter mudado de estado. Ele permanece localizável na medida necessária para sustentar continuidade, responsabilidade e aprendizagem.

---

## Registro final

**Diretório:** `modulos/modulo-03-arquitetura-organizacional/registros-de-arquitetura/`  
**Documento:** `01-indice-de-arquiteturas.md`  
**Versão:** 0.1  
**Estado:** Ativo  
**Data:** 02/08/2026  
**Unidade indexada:** projeto `ARQ-AAAA-NNN`  
**Fonte de governança:** `README.md` deste diretório  
**Próximo documento previsto:** `02-registro-de-arquitetura.md`  
**Observações:** [Preencher]
