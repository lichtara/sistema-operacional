# Termo de Abertura da Implantação

**Identificação técnica no repositório**

```yaml
id_termo: TER-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação]"
organizacao:
area_ou_contexto:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_transicao_para_implantacao: TRA-IMP-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base:
id_ocorrencia_pi_1: IMP-AAAA-NNN-GAT-NNN
resultado_pi_1:
autoridade_da_implantacao:
responsavel_pela_implantacao:
responsavel_pela_arquitetura:
custodiante_do_dossie:
data_de_abertura: AAAA-MM-DD
data_de_aprovacao:
prazo_ou_condicao_de_conclusao:
estado_do_termo: em_elaboracao
estado_da_implantacao: em_recepcao
classificacao_preliminar: focal | funcional | sistemica | a_confirmar
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Identificação, delimitação, autorização e governança inicial de uma implantação  
**Documentos de referência:** Fundamentos da Implantação; Protocolo de Implantação; Matriz de Rastreabilidade da Implantação  
**Ponto de origem:** PI-1 — Aceite da transição  
**Próximo documento:** Plano de Implantação

**Documentos relacionados:**

- transição para implantação produzida pelo Módulo 3;
- manifesto da linha de base arquitetural;
- arquitetura integrada e seus desenhos dimensionais aplicáveis;
- catálogo de requisitos da arquitetura;
- Matriz de Rastreabilidade da Arquitetura;
- registro da decisão de aprovação da arquitetura;
- registro do PI-1;
- Protocolo de Decisão do Módulo 1;
- políticas, contratos e autorizações aplicáveis;
- Plano de Implantação;
- Matriz de Rastreabilidade da Implantação.

---

## 1. Finalidade

Este termo cria a identidade formal de uma implantação e registra as condições sob as quais o Estúdio LICHTARA está autorizado a planejá-la, mobilizá-la e governá-la.

Sua função é transformar uma transição aceita no PI-1 em uma iniciativa:

- identificável;
- delimitada;
- atribuída;
- autorizada;
- rastreável;
- proporcional;
- governável;
- vinculada à arquitetura aprovada;
- orientada à instalação de capacidade organizacional.

O termo deve permitir que uma pessoa autorizada compreenda, antes da elaboração do plano:

1. qual transição e linha de base foram recebidas;
2. qual resultado organizacional precisa tornar-se real;
3. quais capacidades deverão ser implantadas;
4. quais capacidades e proteções precisam ser preservadas;
5. qual escopo de realização foi autorizado;
6. o que permanece fora do escopo;
7. quais condições do PI-1 vinculam o trabalho;
8. que decisões o Módulo 4 pode tomar;
9. que mudanças devem retornar ao Módulo 3;
10. quem possui autoridade, responsabilidade e custódia;
11. quais recursos e participações precisam ser mobilizados;
12. quais riscos, dependências e restrições já são conhecidos;
13. o que a aprovação deste termo autoriza;
14. o que continua condicionado aos gates seguintes;
15. qual é o próximo movimento governável.

## 2. Posição do termo no protocolo

Este documento é produzido depois da decisão do PI-1 e antes da consolidação do Plano de Implantação.

```text
Transição do Módulo 3 recebida
        ↓
Linha de base e pacote inspecionados
        ↓
PI-1 — Aceite da transição
        ↓
Dossiê IMP-AAAA-NNN aberto
        ↓
Termo de Abertura aprovado
        ↓
Plano de Implantação elaborado
        ↓
Preparação demonstrada
        ↓
PI-2 — Prontidão para executar
```

A aprovação deste termo significa:

> Existe uma implantação suficientemente identificada, delimitada, atribuída e autorizada para ser planejada e mobilizada dentro das condições registradas.

A aprovação deste termo ainda não autoriza:

- executar alteração na operação vigente;
- produzir ou ativar configuração em ambiente real;
- iniciar piloto, onda ou virada;
- liberar incremento;
- aceitar capacidade implantada;
- transferir responsabilidade à operação;
- alterar requisito ou componente estrutural;
- introduzir uso material de dados, tecnologia ou IA fora da linha de base;
- aceitar risco sem autoridade competente.

Essas autorizações pertencem aos gates, decisões e alçadas correspondentes.

## 3. Distinção entre PI-1, termo e PI-2

| Mecanismo | Objeto | Pergunta | Efeito |
| --- | --- | --- | --- |
| PI-1 | Transição e linha de base | A base é suficiente para mobilizar a implantação? | Aceita, condiciona, suspende, recusa ou devolve a transição. |
| Termo de Abertura | Implantação identificada | Sob quais condições esta implantação pode ser planejada e mobilizada? | Cria identidade, atribui responsabilidade e delimita autorização inicial. |
| PI-2 | Escopo preparado para execução | Existem condições para iniciar a execução do objeto definido? | Autoriza, condiciona ou impede o início da execução. |

O termo registra o resultado do PI-1 por referência. Ele não reabre a decisão arquitetural nem substitui o registro do gate.

Uma implantação aceita com condições pode ter seu termo aberto quando estiver explícito:

- o que pode ser planejado;
- o que pode ser mobilizado;
- o que permanece bloqueado;
- quem responde por cada condição;
- qual evidência demonstra atendimento;
- qual autoridade confirma a resolução;
- que consequência decorre do descumprimento.

## 4. Natureza do documento

Este documento é:

- o registro de abertura de uma implantação real;
- a fonte oficial da delimitação inicial do objeto;
- o vínculo entre a transição aceita e o planejamento;
- a declaração inicial de autoridade e responsabilidade;
- a referência para escopo, não objetivos e envelope de autonomia;
- a base para o Plano de Implantação;
- um registro histórico versionado.

Este documento não substitui:

- a transição para implantação;
- o manifesto da linha de base;
- o registro do PI-1;
- o Plano de Implantação;
- a Estrutura Analítica da Implantação;
- a Matriz de Rastreabilidade da Implantação;
- o registro integrado de riscos, impedimentos, dependências e mudanças;
- verificações de prontidão;
- registros de validação e aceite;
- o registro da configuração implantada;
- a transição para operação.

## 5. Autoridade do termo

O termo pode:

- identificar a implantação;
- registrar a base recebida;
- delimitar o escopo autorizado;
- atribuir papéis confirmados;
- incorporar condições do PI-1;
- estabelecer limites de planejamento e mobilização;
- registrar o envelope executivo recebido;
- definir gatilhos de escalonamento;
- autorizar a elaboração dos documentos seguintes.

O termo não pode:

- modificar a linha de base arquitetural;
- criar requisito material ausente;
- redefinir capacidade aprovada;
- alterar interface crítica;
- redistribuir autoridade estrutural;
- dispensar critério de aceite;
- ampliar tolerância concedida pelo Módulo 3;
- transformar lacuna em premissa por conveniência;
- autorizar execução que depende do PI-2.

## 6. Instruções de uso

1. Duplique este arquivo para cada implantação real.
2. Não preencha diretamente o template-mestre.
3. Armazene a cópia no dossiê correspondente a IMP-AAAA-NNN.
4. Substitua os campos entre colchetes.
5. Utilize Não aplicável quando o campo tiver sido examinado e não se aplicar.
6. Utilize Não determinado quando ainda não existir informação suficiente.
7. Utilize Pendente apenas com responsável e prazo ou gatilho.
8. Preserve os identificadores e as versões dos objetos herdados.
9. Referencie fontes oficiais em vez de reproduzir seu conteúdo integral.
10. Registre divergências sem convertê-las em consenso presumido.
11. Mantenha uma única opção vigente em campos de estado ou resultado.
12. Registre a evidência de toda manifestação de autoridade.
13. Versione alterações materiais e preserve o estado anteriormente aprovado.
14. Submeta mudança arquitetural ao Módulo 3.
15. Use a versão reduzida apenas quando todos os controles materiais permanecerem presentes.

### 6.1 Convenções de preenchimento

| Convenção | Significado |
| --- | --- |
| [Preencher] | Registro necessário. |
| Não aplicável | O campo foi examinado e não pertence ao objeto. |
| Não determinado | A informação ainda não pode ser estabelecida. |
| Pendente | A definição possui tratamento, responsável e limite. |
| A confirmar | Existe indicação inicial que exige verificação. |
| Nenhuma | O conjunto foi examinado e está vazio. |
| ID/versão | Referência exata ao objeto e à versão. |
| Link ou caminho | Endereço recuperável por pessoa autorizada. |

### 6.2 Princípio de concisão rastreável

O termo registra o suficiente para abrir e delimitar a implantação. O conteúdo detalhado permanece no artefato que possui autoridade sobre ele.

Sempre que houver fonte oficial:

- sintetize o necessário;
- preserve o identificador;
- registre a versão;
- indique a localização;
- declare o estado;
- evite criar uma fonte concorrente.

## 7. Identificação da implantação

| Campo | Registro |
| --- | --- |
| ID da implantação | IMP-AAAA-NNN |
| ID do termo | TER-IMP-AAAA-NNN |
| Título | [Nome específico e compreensível] |
| Organização | [Nome] |
| Unidade, área, processo ou contexto | [Preencher] |
| Cliente ou responsável contratual | [Nome ou referência] |
| Solicitante | [Nome e função] |
| Autoridade da implantação | [Nome e função] |
| Responsável pela implantação | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Responsável operacional indicado | [Nome ou A confirmar] |
| Custodiante do dossiê | [Nome] |
| Data de abertura | [DD/MM/AAAA] |
| Data de aprovação | [DD/MM/AAAA] |
| Prazo ou condição de conclusão | [Data, período ou condição] |
| Classificação preliminar | [Focal, funcional, sistêmica ou a confirmar] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Versão do termo | [0.1] |
| Estado do termo | [Selecionar na seção 8] |
| Estado da implantação | [Estado controlado do protocolo] |

### 7.1 Regra para o título

O título deve indicar a capacidade ou configuração que será tornada operacional.

**Evitar:**

> Implantação do novo sistema

**Preferir:**

> Implantação da capacidade de registrar, priorizar e acompanhar oportunidades comerciais

### 7.2 Dossiê oficial

| Campo | Registro |
| --- | --- |
| Pasta oficial | registros-de-implantacao/AAAA/IMP-AAAA-NNN-nome-curto/ |
| Manifesto do dossiê | README.md |
| Fonte oficial do termo | [Link ou caminho] |
| Repositório ou sistema | [Nome] |
| Regra de acesso | [Papéis ou grupos autorizados] |
| Regra de retenção | [Período, evento ou norma] |
| Cópia de preservação | [Local ou Não aplicável] |

### 7.3 Correspondência entre identificadores

Quando houver correspondência inequívoca, o termo utiliza o mesmo ano e sequencial da implantação:

```text
IMP-2026-001
TER-IMP-2026-001
```

Nova versão do termo preserva o identificador e altera a versão. O identificador não deve ser reutilizado por outra implantação.

## 8. Estado do termo

Selecione um único estado vigente.

- [ ] **Em elaboração** — o registro inicial está sendo consolidado.
- [ ] **Aguardando informação** — falta elemento necessário à abertura.
- [ ] **Aguardando aprovação** — o termo está pronto para decisão.
- [ ] **Aprovado** — a implantação pode avançar ao planejamento e à mobilização autorizada.
- [ ] **Aprovado com condições** — o avanço está limitado pelas condições registradas.
- [ ] **Devolvido para ajuste** — o próprio termo precisa ser corrigido.
- [ ] **Devolvido ao PI-1** — a base da abertura exige nova decisão sobre a transição.
- [ ] **Suspenso** — a abertura foi interrompida temporariamente.
- [ ] **Recusado** — a implantação não será aberta nas condições apresentadas.
- [ ] **Cancelado** — a iniciativa deixou de prosseguir antes da abertura.
- [ ] **Substituído** — outro termo passou a constituir a referência vigente.
- [ ] **Encerrado sem planejamento** — a abertura foi concluída sem produzir plano.

| Campo | Registro |
| --- | --- |
| Data da última mudança | [DD/MM/AAAA] |
| Estado anterior | [Estado] |
| Estado vigente | [Estado] |
| Evento ou fundamento | [ID, decisão ou síntese] |
| Responsável pelo registro | [Nome] |
| Autoridade, quando material | [Nome e função] |
| Próximo movimento | [Ação, responsável e condição] |

O estado do termo e o estado da implantação são objetos distintos. Ambos devem permanecer coerentes e recuperáveis.

## 9. Referências de origem

| Objeto | ID | Versão | Estado | Fonte oficial | Função neste termo |
| --- | --- | --- | --- | --- | --- |
| Projeto de arquitetura | ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | Origem arquitetural |
| Transição para implantação | TRA-IMP-AAAA-NNN | [Versão] | [Estado] | [Link] | Pacote de entrada |
| Linha de base arquitetural | LB-ARQ-NNN | [Versão] | [Aprovada] | [Link] | Referência vinculante |
| Arquitetura integrada | ARQ-INT-AAAA-NNN | [Versão] | [Estado] | [Link] | Configuração autorizada |
| Catálogo de requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] | Obrigações aplicáveis |
| Matriz de rastreabilidade da arquitetura | MTR-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | Origem e relações |
| Registro de validação | VAL-ARQ-AAAA-NNN | [Versão] | [Resultado] | [Link] | Evidência de validação |
| Decisão de aprovação | DEC-AAAA-NNN | [Versão] | [Vigente] | [Link] | Autoridade da base |
| Registro do PI-1 | [ID da ocorrência] | [Versão] | [Resultado] | [Link] | Aceite da transição |
| Contrato ou autorização | [ID] | [Versão] | [Estado] | [Link] | Limite institucional |
| Outro | [ID] | [Versão] | [Estado] | [Link] | [Função] |

### 9.1 Regra de precedência

| Informação | Fonte com autoridade | Papel do termo |
| --- | --- | --- |
| Linha de base e versões | Manifesto da linha de base | Referenciar |
| Requisito arquitetural | Catálogo de Requisitos | Referenciar e sintetizar |
| Configuração desenhada | Arquitetura Integrada | Referenciar e delimitar realização |
| Decisão arquitetural | Registro de decisão | Referenciar |
| Aceite da transição | Registro do PI-1 | Incorporar resultado e condições |
| Identidade e abertura da implantação | Este termo | Manter |
| Plano, recursos e execução | Plano de Implantação | Encaminhar |
| Relações de realização | Matriz de Rastreabilidade da Implantação | Encaminhar |

Em caso de divergência, registre o conflito, identifique a autoridade do objeto e suspenda o uso da informação ambígua quando ela puder alterar decisão material.

## 10. Registro do PI-1 — Aceite da transição

### 10.1 Objeto examinado

| Campo | Registro |
| --- | --- |
| ID da ocorrência de gate | IMP-AAAA-NNN-GAT-NNN |
| Gate | PI-1 — Aceite da transição |
| Transição examinada | [ID e versão] |
| Linha de base examinada | [ID e versão] |
| Data | [DD/MM/AAAA] |
| Responsável pela verificação | [Nome] |
| Responsável pela arquitetura participante | [Nome] |
| Autoridade do gate | [Nome e função] |
| Registro oficial | [Link ou caminho] |

### 10.2 Resultado

Selecione o resultado que consta no registro oficial.

- [ ] Aceita.
- [ ] Aceita com condições.
- [ ] Aguardando esclarecimento ou complementação.
- [ ] Devolvida ao Módulo 3.
- [ ] Suspensa.
- [ ] Recusada por impossibilidade responsável de implantação.

### 10.3 Fundamentação resumida

[Sintetizar a decisão sem substituir o registro oficial.]

### 10.4 Condições do PI-1

| ID de origem | Condição | Responsável | Prazo ou gatilho | Evidência esperada | Autoridade de confirmação | Efeito se não atendida | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome] | [Data ou condição] | [ID, registro ou evento] | [Nome e função] | [Bloqueio, retorno, suspensão ou outro] | [Aberta, em tratamento, atendida, dispensada ou vencida] |

### 10.5 Limite da aceitação condicional

| Pode começar | Permanece proibido | Condição de liberação | Responsável pelo controle |
| --- | --- | --- | --- |
| [Atividade de planejamento ou mobilização] | [Objeto bloqueado] | [Evidência e autoridade] | [Nome] |

Condição do PI-1 permanece vinculante até ser atendida, dispensada por autoridade competente ou substituída por nova decisão.

## 11. Integridade da linha de base recebida

### 11.1 Identificação

| Campo | Registro |
| --- | --- |
| ID da linha de base | LB-ARQ-NNN |
| Versão | [Versão exata] |
| Data de aprovação | [DD/MM/AAAA] |
| Data ou evento de vigência | [Preencher] |
| Decisão de aprovação | DEC-AAAA-NNN |
| Escopo de vigência | [Preencher] |
| Referência substituída | [ID/versão ou Nenhuma] |
| Fonte oficial | [Link ou caminho] |

### 11.2 Manifesto dos itens integrantes

| Objeto integrante | ID | Versão | Estado | Obrigatoriedade | Fonte | Observação de implantação |
| --- | --- | --- | --- | --- | --- | --- |
| [Objeto] | [ID] | [Versão] | [Estado] | [Obrigatório, condicionado ou informativo] | [Link] | [Síntese] |

### 11.3 Lacunas ou ambiguidades conhecidas

| ID | Elemento | Natureza | Efeito | Tratamento decidido no PI-1 | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Ausência, ambiguidade, conflito ou desatualização] | [Preencher] | [Preencher] | [Nome] | [Data ou condição] |

Se a lacuna impedir compreender o que será implantado, o termo deve retornar ao PI-1 ou ao Módulo 3.

## 12. Declaração do resultado da implantação

Utilize a formulação:

> Esta implantação deverá tornar a organização capaz de **[realizar]** no contexto **[delimitação]**, dentro dos critérios **[referências]**, preservando **[capacidades ou proteções]** e respeitando **[limites]**.

**Declaração registrada:**

> [Preencher]

### 12.1 Verificação da declaração

- [ ] descreve capacidade, não apenas entrega;
- [ ] corresponde à linha de base recebida;
- [ ] possui contexto delimitado;
- [ ] aponta para critérios recuperáveis;
- [ ] reconhece preservações;
- [ ] reconhece limites;
- [ ] pode ser demonstrada por evidência;
- [ ] não cria requisito novo;
- [ ] não antecipa benefício que pertence à operação;
- [ ] pode orientar decomposição e planejamento.

## 13. Capacidades a implantar

| ID herdado | Capacidade | Manifestação observável esperada | Contexto | Critério de referência | Fonte oficial | Prioridade de realização |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [O que pessoas, processo ou sistema conseguirão realizar] | [Preencher] | [ID] | [Link] | [Obrigatória, condicionada ou posterior] |

### 13.1 Capacidade principal

[Identificar a capacidade sem a qual a implantação perderia sua finalidade.]

### 13.2 Capacidades habilitadoras

| Capacidade | Por que é necessária | Relação com a capacidade principal | Fonte |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [ID/link] |

### 13.3 Resultado que uma entrega não pode substituir

[Declarar qual capacidade precisa funcionar e não pode ser presumida pela mera produção de documentos, configurações, treinamentos ou tecnologias.]

## 14. Capacidades, identidades e proteções a preservar

| Elemento a preservar | Motivo | Sinal de preservação | Risco de perda | Controle inicial | Fonte |
| --- | --- | --- | --- | --- | --- |
| [Capacidade, relação, princípio, identidade ou proteção] | [Preencher] | [Evidência observável] | [Preencher] | [Preencher] | [ID/link] |

Preservar não significa impedir mudança. Significa impedir que a realização de uma capacidade destrua silenciosamente outra condição necessária.

## 15. Escopo inicial de realização

### 15.1 Incluído

| Dimensão | Objeto incluído | Fronteira | Resultado esperado | Fonte arquitetural |
| --- | --- | --- | --- | --- |
| Capacidade | [Preencher] | [Preencher] | [Preencher] | [ID/link] |
| Componente arquitetural | [Preencher] | [Responsabilidade e interfaces] | [Preencher] | [ID/link] |
| Processo ou fluxo | [Preencher] | [Início e término] | [Preencher] | [ID/link] |
| Papel ou equipe | [Preencher] | [Participação] | [Preencher] | [ID/link] |
| Informação ou dado | [Preencher] | [Uso e ciclo] | [Preencher] | [ID/link] |
| Documento | [Preencher] | [Criação, revisão ou vigência] | [Preencher] | [ID/link] |
| Indicador ou controle | [Preencher] | [Aplicação] | [Preencher] | [ID/link] |
| Tecnologia ou integração | [Preencher] | [Ambiente ou interface] | [Preencher] | [ID/link] |
| Inteligência artificial | [Preencher] | [Função autorizada] | [Preencher] | [ID/link] |

### 15.2 Fronteira temporal e ambiental

| Campo | Registro |
| --- | --- |
| Período abrangido | [Preencher] |
| Ambientes abrangidos | [Desenvolvimento, teste, homologação, produção ou outros] |
| Localidades ou unidades | [Preencher] |
| Público ou população | [Preencher] |
| Volume ou faixa de aplicação | [Preencher] |
| Interfaces externas | [IDs ou descrição] |

### 15.3 Critério de pertencimento

Um objeto pertence ao escopo quando:

- realiza capacidade incluída;
- atende requisito aplicável;
- protege condição necessária;
- prepara, valida ou transfere a configuração;
- possui vínculo rastreável com a linha de base;
- foi incluído por decisão competente.

## 16. Não objetivos e exclusões

| Objeto excluído | Motivo | Autoridade ou fonte | Relação com o escopo | Risco da exclusão | Destino |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Fora da linha de base, fase posterior, outra iniciativa ou outro] | [ID/nome] | [Preencher] | [Preencher] | [Projeto, operação, Módulo 3, backlog futuro ou N/A] |

### 16.1 O que não constituirá sucesso

- concluir cronograma sem capacidade demonstrada;
- produzir entregas sem adoção ou sustentação compatível;
- realizar treinamento sem competência observável;
- emitir comunicação sem compreensão suficiente;
- instalar tecnologia sem processo, responsabilidade e controle;
- cumprir prazo ocultando diferença material;
- transferir risco ou pendência sem responsável;
- alterar a arquitetura para facilitar execução;
- [Outro critério específico].

### 16.2 Melhorias futuras reconhecidas

| Melhoria | Relação com a implantação | Motivo para não incluir agora | Destino | Gatilho de revisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Backlog futuro, Módulo 3, Módulo 5, Módulo 8 ou outra iniciativa] | [Data, evidência ou evento] |

Melhoria futura não deve entrar silenciosamente no escopo por proximidade temática.

## 17. Interfaces e dependências de escopo

| ID | Origem | Destino | Objeto trocado | Regra ou condição | Responsável | Criticidade | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Área, papel, sistema ou componente] | [Área, papel, sistema ou componente] | [Informação, decisão, serviço ou outro] | [Preencher] | [Nome] | [Baixa, média, alta ou crítica] | [ID/link] |

Interface crítica ausente ou indefinida deve ser tratada antes de o escopo correspondente alcançar o PI-2.

## 18. Classificação e proporcionalidade

### 18.1 Classificação

- [ ] **Focal** — mudança delimitada, poucas interfaces e baixo risco relativo.
- [ ] **Funcional** — mudança entre processos, equipes, sistemas ou funções.
- [ ] **Sistêmica** — transformação ampla, interdependente, regulada ou de alto impacto.
- [ ] **A confirmar no plano** — existe informação insuficiente para classificação final.

### 18.2 Justificativa

[Explique por que a classificação é proporcional ao alcance, risco, dependências e dificuldade de reversão.]

### 18.3 Intensificadores

| Fator | Baixo | Médio | Alto | Evidência ou justificativa |
| --- | :---: | :---: | :---: | --- |
| Amplitude organizacional | [ ] | [ ] | [ ] | [Preencher] |
| Número de capacidades | [ ] | [ ] | [ ] | [Preencher] |
| Número de interfaces | [ ] | [ ] | [ ] | [Preencher] |
| Impacto humano | [ ] | [ ] | [ ] | [Preencher] |
| Redistribuição de trabalho | [ ] | [ ] | [ ] | [Preencher] |
| Sensibilidade dos dados | [ ] | [ ] | [ ] | [Preencher] |
| Dependência tecnológica | [ ] | [ ] | [ ] | [Preencher] |
| Participação de IA | [ ] | [ ] | [ ] | [Preencher] |
| Exigência regulatória | [ ] | [ ] | [ ] | [Preencher] |
| Dependência de fornecedor | [ ] | [ ] | [ ] | [Preencher] |
| Dificuldade de reversão | [ ] | [ ] | [ ] | [Preencher] |
| Irreversibilidade potencial | [ ] | [ ] | [ ] | [Preencher] |
| Criticidade operacional | [ ] | [ ] | [ ] | [Preencher] |
| Incerteza residual | [ ] | [ ] | [ ] | [Preencher] |

### 18.4 Efeito da classificação

| Elemento | Tratamento proporcional previsto |
| --- | --- |
| Governança | [Preencher] |
| Segregação de decisão | [Preencher] |
| Profundidade documental | [Preencher] |
| Frequência de controle | [Preencher] |
| Estratégia de piloto ou ondas | [Preencher] |
| Evidência de prontidão | [Preencher] |
| Validação | [Preencher] |
| Reversão | [Preencher] |
| Estabilização | [Preencher] |

## 19. Estratégia inicial de realização

Este termo registra apenas a direção inicial. A estratégia completa pertence ao Plano de Implantação.

### 19.1 Forma preliminar

- [ ] Implantação única e delimitada.
- [ ] Projeto com incrementos.
- [ ] Piloto seguido de ampliação.
- [ ] Ondas sucessivas.
- [ ] Virada planejada.
- [ ] Operação paralela temporária.
- [ ] Programa com projetos relacionados.
- [ ] Combinação a definir no plano.

### 19.2 Justificativa inicial

[Explique a relação entre estratégia, risco, aprendizagem, reversibilidade e continuidade.]

### 19.3 Unidade mínima de valor ou aprendizagem

[Que menor incremento permitirá demonstrar capacidade ou reduzir incerteza relevante?]

### 19.4 Decisões que o plano deverá completar

| Decisão | Autoridade | Insumo necessário | Prazo ou marco | Efeito da espera |
| --- | --- | --- | --- | --- |
| [Preencher] | [Nome e função] | [ID ou informação] | [Data/condição] | [Preencher] |

## 20. Requisitos e critérios vinculantes

| ID | Requisito ou critério | Aplicabilidade | Negociabilidade | Evidência esperada | Fonte | Efeito se não atendido |
| --- | --- | --- | --- | --- | --- | --- |
| [ID herdado] | [Síntese] | [Aplicável, condicionado ou N/A] | [Não negociável, negociável por autoridade ou informativo] | [Tipo de evidência] | [Link] | [Bloqueio, condição, retorno ou outro] |

Não aplicabilidade precisa de fundamento e autoridade compatíveis com o objeto.

## 21. Envelope de autonomia executiva

### 21.1 Adaptações permitidas

| Dimensão | Tolerância ou liberdade | Limite | Autoridade local | Registro exigido |
| --- | --- | --- | --- | --- |
| Sequenciamento | [Preencher] | [Preencher] | [Nome/papel] | [Artefato] |
| Técnica de execução | [Preencher] | [Preencher] | [Nome/papel] | [Artefato] |
| Alocação de recursos | [Preencher] | [Preencher] | [Nome/papel] | [Artefato] |
| Prazo | [Faixa] | [Limite] | [Nome/papel] | [Artefato] |
| Custo | [Faixa] | [Limite] | [Nome/papel] | [Artefato] |
| Detalhe de implementação | [Preencher] | [Preencher] | [Nome/papel] | [Artefato] |
| Composição de incremento | [Preencher] | [Preencher] | [Nome/papel] | [Artefato] |

### 21.2 Decisões reservadas

| Objeto | Autoridade competente | Instância ou módulo | Registro |
| --- | --- | --- | --- |
| Alteração de requisito material | [Nome/papel] | Módulo 3 | [Decisão e nova referência] |
| Redefinição de componente estrutural | [Nome/papel] | Módulo 3 | [Decisão e arquitetura] |
| Mudança de interface crítica | [Nome/papel] | Módulo 3 | [Decisão e arquitetura] |
| Redistribuição de autoridade | [Nome/papel] | Módulo 3 ou governança competente | [Decisão] |
| Aceite de risco material | [Nome/papel] | Autoridade competente | [Decisão de risco] |
| Liberação | [Nome/papel] | PI-3 | [Registro do gate] |
| Aceite de capacidade | [Nome/papel] | PI-4 | [Registro do gate] |
| Transferência à operação | [Nome/papel] | PI-5 | [Registro bilateral] |

## 22. Gatilhos de retorno ao Módulo 3

Retornar ao Módulo 3 quando a mudança proposta ou a evidência encontrada:

- alterar requisito material;
- modificar princípio ou tese da arquitetura;
- criar, remover ou redefinir componente estrutural;
- alterar interface crítica;
- redistribuir autoridade ou alçada;
- introduzir risco não autorizado;
- modificar uso material de dados, tecnologia ou IA;
- invalidar parte da linha de base;
- exceder tolerância concedida à implantação;
- demonstrar que a capacidade desenhada é inviável nas condições autorizadas.

### 22.1 Registro dos gatilhos específicos

| Gatilho | Sinal observável | Ação imediata | Responsável | Autoridade de encaminhamento | Fonte |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Evento ou evidência] | [Conter, suspender, registrar ou devolver] | [Nome] | [Nome e função] | [ID/link] |

### 22.2 Continuidade durante o retorno

| Objeto | Pode continuar? | Condição | Quem decide | Registro |
| --- | --- | --- | --- | --- |
| [Frente, incremento ou atividade] | [Sim, não ou parcialmente] | [Preencher] | [Nome e função] | [ID/link] |

Retorno de um objeto material não suspende automaticamente toda a implantação. A decisão deve considerar isolamento, dependências, risco e integridade da linha de base.

## 23. Governança inicial

### 23.1 Papéis

| Papel | Pessoa ou instância | Responsabilidade neste termo | Autoridade | Limite | Evidência de aceite do papel |
| --- | --- | --- | --- | --- | --- |
| Autoridade da implantação | [Nome] | Autorizar abertura, plano e recursos dentro da alçada | [Preencher] | [Preencher] | [Registro] |
| Responsável pela implantação | [Nome] | Coordenar, integrar, rastrear e escalar | [Preencher] | [Preencher] | [Registro] |
| Responsável pela arquitetura | [Nome] | Interpretar a base e receber retornos materiais | [Preencher] | [Preencher] | [Registro] |
| Responsável operacional indicado | [Nome] | Participar de requisitos de sustentação e transferência | [Preencher] | [Preencher] | [Registro] |
| Custodiante do dossiê | [Nome] | Manter fontes, versões, acesso e histórico | [Preencher] | [Preencher] | [Registro] |
| Responsável por segurança, dados ou conformidade | [Nome] | Verificar matéria especializada | [Preencher] | [Preencher] | [Registro] |
| Representante de pessoas afetadas | [Nome ou grupo] | Tornar impactos e condições de uso visíveis | [Preencher] | [Preencher] | [Registro] |

### 23.2 Segregações necessárias

| Decisão | Prepara | Valida ou recomenda | Decide | Conflito a evitar |
| --- | --- | --- | --- | --- |
| Aprovação do termo | Responsável pela implantação | Responsáveis pertinentes | Autoridade da implantação | Autorização pelo próprio executor sem alçada |
| Plano e PI-2 | Responsável pela implantação | Validadores competentes | Autoridade definida | Início pela pressão de prazo |
| Mudança arquitetural | Módulo 4 formula necessidade | Responsável pela arquitetura | Autoridade do Módulo 3 | Redesenho por conveniência |
| Aceite de risco | Responsável pelo risco | Especialista | Autoridade competente | Aceite por quem produz a exposição |

## 24. Matriz inicial de autoridade

| Objeto | Pode propor | Pode preparar | Pode validar | Pode decidir | Deve ser informado | Registro oficial |
| --- | --- | --- | --- | --- | --- | --- |
| Escopo de realização | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Plano | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Recurso ou orçamento | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Prontidão | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Mudança de execução | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Mudança de plano | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Mudança arquitetural | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Risco residual | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Liberação | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Aceite | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Reversão | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |
| Transferência operacional | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Artefato] |

Autoridade nominal sem disponibilidade, competência ou fundamento deve ser tratada como lacuna.

## 25. Partes interessadas e pessoas afetadas

| Pessoa ou grupo | Relação com a implantação | Interesse legítimo | Impacto potencial | Participação necessária | Momento | Responsável pela relação |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Decide, executa, usa, sustenta, é afetada ou outra] | [Preencher] | [Preencher] | [Informar, consultar, cocriar, validar, aceitar ou outra] | [Etapa] | [Nome] |

### 25.1 Pessoas ausentes ou sub-representadas

| Pessoa ou grupo | Motivo da ausência | Risco produzido | Forma de representação ou escuta | Responsável |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

### 25.2 Conflitos de interesse ou poder

| Situação | Pessoas ou papéis envolvidos | Efeito possível | Proteção | Instância de decisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome ou fórum] |

## 26. Recursos e condições de mobilização

| Recurso ou condição | Quantidade ou disponibilidade | Responsável | Data necessária | Fonte de autorização | Lacuna | Efeito |
| --- | --- | --- | --- | --- | --- | --- |
| Pessoas | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Tempo | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Orçamento | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Ambiente | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Dados ou conteúdo | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Tecnologia | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Especialidade | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |
| Suporte operacional | [Preencher] | [Nome] | [Data] | [ID] | [Preencher/Nenhuma] | [Preencher] |

### 26.1 Limite da mobilização autorizada

| Atividade | Autorizada agora? | Limite | Autoridade | Evidência |
| --- | --- | --- | --- | --- |
| Elaborar plano | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Consultar participantes | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Solicitar orçamento | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Reservar capacidade de equipe | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Contratar fornecedor | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Acessar dados ou ambiente | [Sim/Não/Condicionada] | [Preencher] | [Nome] | [Registro] |
| Executar mudança | Não, até PI-2 | [Exceção somente por decisão competente] | [Nome] | [Registro] |

## 27. Prazo, marcos e condições temporais

O cronograma detalhado pertence ao documento próprio. O termo registra compromissos e limites necessários à abertura.

| Marco ou condição | Data ou janela | Natureza | Dependência | Autoridade | Consequência do atraso |
| --- | --- | --- | --- | --- | --- |
| Aprovação do termo | [Data] | [Compromisso ou estimativa] | [Preencher] | [Nome] | [Preencher] |
| Plano pronto para decisão | [Data] | [Compromisso ou estimativa] | [Preencher] | [Nome] | [Preencher] |
| PI-2 previsto | [Data/condição] | [Previsão] | [Preencher] | [Nome] | [Preencher] |
| Conclusão pretendida | [Data/condição] | [Compromisso ou objetivo] | [Preencher] | [Nome] | [Preencher] |

Prazo incompatível com prontidão, validação ou reversibilidade exige redução de escopo, ampliação de recursos, mudança de estratégia, adiamento ou recusa responsável.

## 28. Premissas, restrições, dependências e condições

| ID | Tipo | Declaração | Fonte | Responsável | Data de revisão | Estado | Efeito se inválida ou não atendida |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Premissa, restrição, dependência ou condição] | [Preencher] | [ID/link] | [Nome] | [Data/gatilho] | [Estado] | [Preencher] |

### 28.1 Regra para premissas

Premissa:

- possui fundamento;
- permanece verificável;
- tem prazo ou gatilho de revisão;
- registra o efeito de sua invalidação;
- não ocupa o lugar de uma lacuna impeditiva.

## 29. Riscos iniciais da implantação

| ID | Evento de risco | Causa | Consequência | Exposição inicial | Controle existente | Tratamento inicial | Responsável | Gatilho |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Baixa, média, alta ou crítica] | [ID/síntese] | [Evitar, reduzir, compartilhar, aceitar ou investigar] | [Nome] | [Sinal] |

### 29.1 Riscos que impedem o planejamento

| ID | Motivo do impedimento | Decisão necessária | Autoridade | Prazo ou condição |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Nome e função] | [Preencher] |

### 29.2 Riscos que podem impedir o PI-2

| ID | Critério de prontidão afetado | Evidência necessária | Responsável | Tratamento previsto |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Nome] | [Preencher] |

O registro detalhado será mantido em templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md.

## 30. Impactos humanos e organizacionais

| Grupo ou papel | Mudança esperada | Benefício potencial | Custo ou perda potencial | Risco humano | Participação necessária | Proteção |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 30.1 Hipóteses sobre adoção

| Hipótese | Evidência atual | Como será testada | Responsável | Momento |
| --- | --- | --- | --- | --- |
| [Preencher] | [ID ou Não determinada] | [Observação, piloto, entrevista, uso assistido ou outra] | [Nome] | [Etapa] |

### 30.2 Discordâncias conhecidas

| Pessoa ou grupo | Objeto da discordância | Fundamento | Efeito | Tratamento | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preservar, investigar, decidir ou escalar] | [Nome/fórum] |

Resistência, impedimento e discordância legítima devem permanecer distinguíveis.

## 31. Comunicação e compreensão

| Público | Informação necessária | Finalidade | Canal previsto | Confirmação de compreensão | Responsável | Momento |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Pergunta aplicada, demonstração, decisão ou outra] | [Nome] | [Preencher] |

### 31.1 Canais oficiais

| Finalidade | Canal | Participantes | Fonte oficial do registro | Custodiante |
| --- | --- | --- | --- | --- |
| Coordenação | [Preencher] | [Preencher] | [Local] | [Nome] |
| Decisões | [Preencher] | [Preencher] | [Local] | [Nome] |
| Documentos | [Preencher] | [Preencher] | [Local] | [Nome] |
| Riscos e impedimentos | [Preencher] | [Preencher] | [Local] | [Nome] |
| Incidentes | [Preencher] | [Preencher] | [Local] | [Nome] |

O plano detalhado será mantido em templates/08-plano-de-comunicacao-e-engajamento.md.

## 32. Treinamento, competência e conhecimento

| Público ou papel | Capacidade a desenvolver | Estado inicial conhecido | Evidência de competência esperada | Responsável | Momento |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Conhecida, a verificar ou não determinada] | [Execução, cenário, simulação ou outra] | [Nome] | [Preencher] |

### 32.1 Conhecimento crítico

| Conhecimento | Fonte atual | Pessoa ou sistema detentor | Risco de concentração ou perda | Estratégia inicial |
| --- | --- | --- | --- | --- |
| [Preencher] | [ID/local] | [Nome/sistema] | [Preencher] | [Documentar, transferir, praticar ou outra] |

Presença em treinamento não constitui competência. O plano detalhado será mantido em templates/09-plano-de-treinamento-e-capacitacao.md.

## 33. Informação, dados e documentação

| Objeto | Finalidade autorizada | Fonte oficial | Sensibilidade | Acesso necessário | Responsável | Regra de ciclo de vida |
| --- | --- | --- | --- | --- | --- | --- |
| [Informação, dado ou documento] | [Preencher] | [Sistema/link] | [Nível] | [Papéis] | [Nome] | [Criar, usar, revisar, reter e eliminar] |

### 33.1 Condições de acesso

| Acesso | Pessoa ou papel | Ambiente | Autoridade concedente | Validade | Revogação | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/evento] | [Regra] | [Registro] |

### 33.2 Documentos que precisarão tornar-se vigentes

| Documento | Estado atual | Estado esperado | Aprovador | Evento de vigência | Destino do anterior |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] | [Arquivar, substituir ou manter] |

## 34. Tecnologia e integrações

| Componente ou sistema | Função na implantação | Ambiente | Integração crítica | Responsável | Restrição | Dependência externa |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [ID/sistema] | [Nome] | [Segurança, legado, custo ou outra] | [Preencher] |

### 34.1 Decisões tecnológicas já tomadas

| ID | Decisão | Escopo de vigência | Pode ser adaptada? | Autoridade para revisão | Fonte |
| --- | --- | --- | --- | --- | --- |
| [DEC] | [Preencher] | [Preencher] | [Sim, não ou condição] | [Nome] | [Link] |

### 34.2 Elementos ainda não autorizados

| Elemento | Motivo | Decisão necessária | Autoridade | Marco limite |
| --- | --- | --- | --- | --- |
| [Ferramenta, integração, ambiente ou acesso] | [Preencher] | [Preencher] | [Nome] | [Data/etapa] |

## 35. Participação da inteligência artificial

### 35.1 IA como apoio à implantação

| Função de IA | Finalidade | Entrada autorizada | Saída esperada | Verificação humana | Registro material | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [Pesquisa, análise, redação, documentação, revisão, automação ou outra] | [Preencher] | [Dados/fontes] | [Preencher] | [Nome/papel/ato] | [Artefato] | [Preencher] |

### 35.2 IA como parte da configuração implantada

| Sistema ou agente | Função organizacional | Modelo ou serviço | Dados utilizados | Supervisão humana | Falha segura | Fonte arquitetural |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Interrupção, fallback ou reversão] | [ID/link] |

### 35.3 Responsabilidades não delegáveis

Nenhuma IA pode:

- aceitar a transição;
- aprovar o termo;
- atribuir autoridade a pessoa;
- aceitar risco;
- autorizar acesso;
- declarar prontidão;
- liberar implantação;
- aprovar mudança arquitetural;
- validar competência humana sem critério e verificação;
- aceitar capacidade;
- receber ou transferir responsabilidade operacional;
- encerrar a implantação.

A participação da IA permanece subordinada à responsabilidade humana identificada. Toda saída material deve possuir pessoa verificadora, fonte recuperável, limite de uso e correção possível.

## 36. Ética, segurança, privacidade e propriedade intelectual

| Domínio | Obrigação ou risco | Fonte | Controle inicial | Especialista ou autoridade | Gate afetado |
| --- | --- | --- | --- | --- | --- |
| Ética | [Preencher] | [ID/link] | [Preencher] | [Nome] | [PI-2, PI-3, PI-4 ou PI-5] |
| Segurança | [Preencher] | [ID/link] | [Preencher] | [Nome] | [Gate] |
| Privacidade | [Preencher] | [ID/link] | [Preencher] | [Nome] | [Gate] |
| Propriedade intelectual | [Preencher] | [ID/link] | [Preencher] | [Nome] | [Gate] |
| Conformidade | [Preencher] | [ID/link] | [Preencher] | [Nome] | [Gate] |
| Acessibilidade | [Preencher] | [ID/link] | [Preencher] | [Nome] | [Gate] |

### 36.1 Condições impeditivas

| Condição | Objeto bloqueado | Tratamento | Autoridade de liberação | Evidência |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome e função] | [ID/registro] |

## 37. Fornecedores e dependências externas

| Fornecedor ou parte externa | Objeto | Estado contratual | Dependência | Responsável interno | Risco | Saída ou substituição |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Produto, serviço ou especialidade] | [Preencher] | [Preencher] | [Nome] | [Preencher] | [Plano inicial] |

### 37.1 Autorizações ainda necessárias

| Objeto | Autoridade | Insumos | Data limite | Efeito se ausente |
| --- | --- | --- | --- | --- |
| [Contratação, licença, acesso ou outro] | [Nome] | [Preencher] | [Data] | [Preencher] |

Fornecedor executa dentro do contrato e da governança. A responsabilidade organizacional permanece atribuída a pessoas e instâncias competentes.

## 38. Validação, aceite e estabilização previstos

Este termo registra a arquitetura inicial de verificação. Métodos, amostras e planos detalhados serão desenvolvidos nos documentos próprios.

| Objeto | Critério de referência | Evidência prevista | Validador | Autoridade de aceite | Gate |
| --- | --- | --- | --- | --- | --- |
| Entrega | [ID] | [Teste, inspeção ou registro] | [Nome/papel] | [Nome/papel] | PI-3 ou controle interno |
| Capacidade | [ID] | [Execução observada, cenário ou resultado] | [Nome/papel] | [Nome/papel] | PI-4 |
| Competência | [ID] | [Demonstração] | [Nome/papel] | [Nome/papel] | PI-4 ou condição |
| Adoção | [ID] | [Uso qualificado e sustentado] | [Nome/papel] | [Nome/papel] | PI-4 ou estabilização |
| Sustentação | [ID] | [Operação assistida e resposta a exceção] | [Nome/papel] | [Responsável operacional] | PI-5 |

### 38.1 Horizonte de estabilização

| Campo | Registro |
| --- | --- |
| Período ou critério preliminar | [Preencher] |
| Condições a observar | [Preencher] |
| Responsável pelo acompanhamento | [Nome] |
| Indicadores ou sinais | [IDs ou síntese] |
| Condição de extensão | [Preencher] |
| Condição de correção ou reversão | [Preencher] |

## 39. Reversibilidade, contingência e continuidade

| Objeto | Falha ou condição | Ação de contenção | Estratégia de continuidade | Estratégia de reversão | Autoridade | Tempo tolerável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Período] |

### 39.1 Irreversibilidades conhecidas

| Decisão ou ação | Por que é irreversível ou custosa | Proteção prévia | Autoridade necessária | Evidência |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome] | [ID/registro] |

O plano detalhado será mantido em templates/11-plano-de-piloto-ondas-virada-e-reversao.md.

## 40. Benefícios e indicadores iniciais

### 40.1 Resultado da implantação

| Resultado | Sinal de realização | Horizonte | Responsável pela evidência |
| --- | --- | --- | --- |
| [Capacidade disponível e utilizável] | [Preencher] | [Período] | [Nome] |

### 40.2 Benefício operacional esperado

| Benefício | Beneficiário | Indicador ou sinal | Horizonte operacional | Dono após transição |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID/síntese] | [Período] | [Nome/papel] |

O Módulo 4 demonstra a capacidade implantada. A realização continuada de benefício pertence à operação e às camadas de inteligência correspondentes.

### 40.3 Proteções de medição

- progresso percentual não substitui fluxo real;
- volume de entrega não substitui capacidade;
- presença em treinamento não substitui competência;
- envio de comunicação não substitui compreensão;
- login ou acesso não substitui adoção;
- ausência de incidente não demonstra estabilidade;
- satisfação isolada não substitui validação técnica, humana ou operacional.

## 41. Rastreabilidade inicial

### 41.1 Matriz oficial

| Campo | Registro |
| --- | --- |
| ID previsto | MTR-IMP-AAAA-NNN |
| Fonte oficial | [Link ou caminho] |
| Custodiante | [Nome] |
| Data de abertura prevista | [DD/MM/AAAA] |
| Matriz arquitetural de origem | MTR-ARQ-AAAA-NNN — [versão] |

### 41.2 Vínculos mínimos de abertura

| Origem | Relação | Destino | Fonte | Estado | Responsável |
| --- | --- | --- | --- | --- | --- |
| TRA-IMP-AAAA-NNN | origina | IMP-AAAA-NNN | [Link] | [Vigente] | [Nome] |
| LB-ARQ-NNN — [versão] | referencia | IMP-AAAA-NNN | [Link] | [Vigente] | [Nome] |
| [Capacidade herdada] | será realizada por | IMP-AAAA-NNN | [Link] | [Planejada] | [Nome] |
| [Condição do PI-1] | condiciona | IMP-AAAA-NNN | [Link] | [Aberta] | [Nome] |
| TER-IMP-AAAA-NNN | delimita | IMP-AAAA-NNN | [Link] | [Em elaboração] | [Nome] |

### 41.3 Lacunas de rastreabilidade

| ID | Caminho incompleto | Efeito | Tratamento | Responsável | Limite |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Origem, realização, evidência, decisão, configuração ou continuidade] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] |

## 42. Artefatos previstos

| Artefato | Aplicabilidade | Estado inicial | Responsável | Prazo ou marco | Possibilidade de combinação | Fonte futura |
| --- | --- | --- | --- | --- | --- | --- |
| Plano de Implantação | [Aplicável] | [Não iniciado] | [Nome] | [Data] | [Regra] | templates/02-plano-de-implantacao.md |
| Estrutura Analítica | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/03-estrutura-analitica-da-implantacao.md |
| Cronograma Mestre | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/04-cronograma-mestre-da-implantacao.md |
| Backlog e Kanban | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/05-backlog-e-quadro-kanban-da-implantacao.md |
| Matriz de Rastreabilidade | [Aplicável] | [Estado] | [Nome] | [Data] | [Regra] | templates/06-matriz-de-rastreabilidade-da-implantacao.md |
| Registro integrado de controle | [Aplicável] | [Estado] | [Nome] | [Data] | [Regra] | templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md |
| Plano de Comunicação | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/08-plano-de-comunicacao-e-engajamento.md |
| Plano de Treinamento | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/09-plano-de-treinamento-e-capacitacao.md |
| Plano de Gestão da Mudança | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/10-plano-de-gestao-da-mudanca-organizacional.md |
| Plano de Piloto, Ondas, Virada e Reversão | [Aplicável/condicional] | [Estado] | [Nome] | [Data] | [Regra] | templates/11-plano-de-piloto-ondas-virada-e-reversao.md |

Combinação documental preserva função, autoridade, evidência, localização e atualização de cada controle.

## 43. Controle de mudanças do termo

### 43.1 Mudanças que exigem nova aprovação

- alteração do resultado da implantação;
- mudança da linha de base de referência;
- ampliação ou redução material do escopo;
- alteração do envelope de autonomia;
- mudança de autoridade ou responsável principal;
- inclusão de risco material;
- alteração relevante de prazo, custo ou recurso;
- inclusão de novo contexto de dados sensíveis;
- introdução de uso material de IA;
- mudança na estratégia que altere risco ou reversibilidade;
- modificação de condição vinculante do PI-1.

### 43.2 Classificação da mudança

| Classe | Exemplo | Tratamento |
| --- | --- | --- |
| Editorial | Ortografia, formatação ou link sem mudança de objeto | Corrigir e registrar quando necessário. |
| Metadado | Responsável de contato, localização ou data administrativa | Atualizar com evidência. |
| Executiva | Sequência, técnica ou recurso dentro do envelope | Decidir na alçada e atualizar registros. |
| De plano | Escopo de incremento, cronograma ou estratégia dentro da arquitetura | Analisar impacto e obter decisão competente. |
| Arquitetural | Requisito, componente, interface, autoridade ou proteção material | Retornar ao Módulo 3. |

### 43.3 Registro

| ID | Data | Mudança | Classe | Impacto | Decisão | Versão anterior | Versão nova | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data] | [Preencher] | [Classe] | [Preencher] | [ID] | [Versão] | [Versão] | [Nome] |

Mudança posterior não reescreve a autorização histórica. Ela produz nova versão, decisão e rastreabilidade.

## 44. Suspensão, recusa, cancelamento, substituição e reabertura

### 44.1 Condições possíveis

| Evento | Condição típica | Quem recomenda | Quem decide | Registro | Destino dos objetos |
| --- | --- | --- | --- | --- | --- |
| Suspensão | Risco, lacuna, ausência de autoridade ou recurso | [Papel] | [Papel] | [ID] | [Conter e preservar] |
| Recusa | Impossibilidade responsável ou incompatibilidade | [Papel] | [Papel] | [ID] | [Devolver ou encerrar] |
| Cancelamento | Finalidade retirada antes da execução | [Papel] | [Papel] | [ID] | [Preservar e destinar] |
| Substituição | Outra implantação passa a realizar o objeto | [Papel] | [Papel] | [ID] | [Vincular sucessora] |
| Reabertura | Nova evidência torna a abertura anterior insuficiente | [Papel] | [Papel] | [ID] | [Versionar ou abrir complemento] |

### 44.2 Condições de retomada

| Condição suspensa | Evidência para retomada | Verificador | Autoridade | Prazo ou gatilho |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Nome] | [Nome e função] | [Preencher] |

### 44.3 Preservação

Mesmo quando a implantação não prosseguir, preservar:

- versão vigente do termo;
- transição e linha de base recebidas;
- resultado do PI-1;
- fundamento e autoridade da decisão;
- riscos e pendências;
- dados, documentos e ativos recebidos;
- destino de acessos e contratos;
- condição de eventual reabertura;
- aprendizagem produzida.

## 45. Condições mínimas de abertura

### 45.1 Identidade e origem

- [ ] existe ID único para a implantação;
- [ ] o dossiê oficial está localizado;
- [ ] a transição está identificada por versão;
- [ ] a linha de base está identificada por versão;
- [ ] o PI-1 possui resultado e autoridade registrados;
- [ ] as condições do PI-1 foram incorporadas.

### 45.2 Delimitação

- [ ] o resultado da implantação está formulado como capacidade;
- [ ] as capacidades incluídas são recuperáveis na arquitetura;
- [ ] o escopo e os não objetivos são compreensíveis;
- [ ] preservações e limites estão explícitos;
- [ ] o envelope de autonomia foi registrado;
- [ ] os gatilhos de retorno ao Módulo 3 estão definidos;
- [ ] a classificação preliminar foi justificada.

### 45.3 Responsabilidade e viabilidade

- [ ] existe autoridade da implantação;
- [ ] existe responsável pela implantação;
- [ ] existe responsável pela arquitetura;
- [ ] existe custodiante do dossiê;
- [ ] papéis críticos aceitaram sua atribuição;
- [ ] recursos mínimos para planejar estão disponíveis ou condicionados;
- [ ] riscos impeditivos possuem tratamento;
- [ ] dependências e restrições materiais estão visíveis;
- [ ] acesso, sensibilidade e proteção receberam tratamento inicial;
- [ ] usos de IA foram delimitados.

### 45.4 Próximo movimento

- [ ] a aprovação autoriza apenas movimentos explícitos;
- [ ] o Plano de Implantação possui responsável;
- [ ] decisões pendentes possuem autoridade e limite;
- [ ] nenhuma execução foi presumida antes do PI-2;
- [ ] pendências foram transferidas ao mecanismo de acompanhamento.

## 46. Verificação de coerência

| Pergunta | Resultado | Evidência | Tratamento de lacuna |
| --- | --- | --- | --- |
| O termo corresponde ao objeto aceito no PI-1? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| A linha de base resolve para versões exatas? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| O resultado deriva de capacidade autorizada? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| O escopo cabe no envelope de autonomia? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| As exclusões possuem destino? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| Autoridade e responsabilidade estão separadas quando necessário? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| Prazo e recursos permitem planejamento responsável? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| Riscos e condições possuem consequência? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| Dados, tecnologia e IA respeitam a base aprovada? | [Sim, parcial ou não] | [ID/link] | [Preencher] |
| O termo evita autorizar execução antes do PI-2? | [Sim, parcial ou não] | [ID/link] | [Preencher] |

## 47. Pendências remanescentes

| ID | Pendência | Por que não impede a abertura | Responsável | Limite | Evidência de resolução | Consequência do descumprimento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Nome] | [Data/etapa] | [Preencher] | [Bloquear, suspender, devolver ou outro] | [Aberta] |

Pendência sem responsável, limite e consequência permanece lacuna; não constitui condição controlada.

## 48. Decisão de abertura

### 48.1 Objeto da decisão

| Campo | Registro |
| --- | --- |
| Termo examinado | TER-IMP-AAAA-NNN — [versão] |
| Implantação | IMP-AAAA-NNN |
| Transição | TRA-IMP-AAAA-NNN — [versão] |
| Linha de base | LB-ARQ-NNN — [versão] |
| PI-1 relacionado | IMP-AAAA-NNN-GAT-NNN |
| Data | [DD/MM/AAAA] |

### 48.2 Resultado

- [ ] Aprovado.
- [ ] Aprovado com condições.
- [ ] Devolvido para ajuste.
- [ ] Devolvido ao PI-1.
- [ ] Suspenso.
- [ ] Recusado.
- [ ] Cancelado.

### 48.3 Fundamentação

[Registre por que a implantação deve ou não ser aberta nas condições apresentadas.]

### 48.4 A decisão autoriza

- [ ] abrir e manter o dossiê da implantação;
- [ ] elaborar o Plano de Implantação;
- [ ] detalhar estrutura analítica, cronograma e backlog;
- [ ] consolidar a Matriz de Rastreabilidade da Implantação;
- [ ] consultar participantes dentro das regras registradas;
- [ ] mobilizar recursos expressamente autorizados;
- [ ] preparar propostas de contratação ou acesso;
- [ ] realizar atividades exploratórias delimitadas abaixo;
- [ ] outro: [Preencher].

**Atividades exploratórias autorizadas e limites:**

[Preencher ou registrar Nenhuma.]

### 48.5 A decisão ainda não autoriza

- executar mudança na operação;
- ativar configuração em produção;
- iniciar piloto, onda ou virada;
- utilizar dados ou acessos ainda não concedidos;
- assumir compromisso financeiro fora da alçada;
- liberar incremento;
- aceitar risco material;
- aceitar capacidade implantada;
- transferir responsabilidade operacional;
- alterar a linha de base.

### 48.6 Condições vinculantes da abertura

| ID | Condição | Responsável | Prazo ou gatilho | Verificador | Efeito sobre a implantação | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome] | [Data/condição] | [Nome] | [Preencher] | [Aberta] |

## 49. Manifestações e aprovações

### 49.1 Responsável pela implantação

**Nome:** [Preencher]  
**Manifestação:** [Recomendo / Recomendo com condições / Não recomendo]  
**Fundamentação:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Assinatura, mensagem, ata ou registro]

### 49.2 Responsável pela arquitetura

**Nome:** [Preencher]  
**Manifestação sobre correspondência com a linha de base:** [Confirmo / Confirmo com ressalvas / Não confirmo]  
**Ressalvas:** [Preencher ou Nenhuma]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Registro]

### 49.3 Autoridade da implantação

**Nome e função:** [Preencher]  
**Manifestação:** [Aprovo / Aprovo com condições / Não aprovo]  
**Condições:** [IDs ou Nenhuma]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Assinatura, mensagem, ata ou registro]

### 49.4 Responsável operacional indicado

**Nome e função:** [Preencher]  
**Manifestação:** [Ciente / Ciente com ressalvas / Ainda não indicado]  
**Objeto da manifestação:** [Condições de participação no planejamento e futura sustentação]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Registro]

### 49.5 Aprovações especializadas

| Pessoa ou instância | Especialidade | Objeto | Manifestação | Condições | Data | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Segurança, dados, jurídico, finanças ou outra] | [Preencher] | [Preencher] | [IDs/Nenhuma] | [Data] | [Registro] |

### 49.6 Divergências preservadas

| Pessoa ou grupo | Divergência | Efeito sobre a decisão | Tratamento | Decisão relacionada |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID] |

Ausência de manifestação não equivale a concordância.

## 50. Próximo movimento autorizado

### 50.1 Documento seguinte

**Plano de Implantação:** templates/02-plano-de-implantacao.md

### 50.2 Responsável

[Nome]

### 50.3 Data ou condição de início

[Preencher]

### 50.4 Insumos transferidos

- [ ] termo aprovado;
- [ ] transição aceita;
- [ ] linha de base e manifesto;
- [ ] arquitetura integrada e desenhos aplicáveis;
- [ ] requisitos e critérios;
- [ ] condições do PI-1;
- [ ] resultado e escopo da implantação;
- [ ] não objetivos;
- [ ] preservações;
- [ ] envelope de autonomia;
- [ ] gatilhos de retorno ao Módulo 3;
- [ ] autoridades e papéis;
- [ ] riscos, restrições, premissas e dependências;
- [ ] regras de dados, tecnologia e IA;
- [ ] prazo, recurso e estratégia iniciais;
- [ ] decisões pendentes.

### 50.5 Questões que o plano deverá resolver

| Questão | Responsável pela formulação | Insumo | Limite |
| --- | --- | --- | --- |
| Como decompor capacidades em incrementos, entregas e trabalho? | [Nome] | [IDs] | [Data/marco] |
| Que estratégia, ondas e marcos serão utilizados? | [Nome] | [IDs] | [Data/marco] |
| Que recursos e dependências precisam ser mobilizados? | [Nome] | [IDs] | [Data/marco] |
| Como pessoas, comunicação, treinamento e mudança serão preparados? | [Nome] | [IDs] | [Data/marco] |
| Como prontidão, validação, reversão e estabilização serão demonstradas? | [Nome] | [IDs] | [Data/marco] |
| Que evidências sustentarão o PI-2? | [Nome] | [IDs] | [Data/marco] |

## 51. Síntese executiva da abertura

Preencha esta seção ao final. Ela orienta leitura rápida e não substitui o termo.

| Elemento | Síntese |
| --- | --- |
| Implantação | [ID e título] |
| Origem | [Projeto, transição e linha de base] |
| Resultado | [Uma frase de capacidade] |
| Escopo | [Capacidades e fronteira] |
| Não objetivos | [Principais exclusões] |
| Preservação principal | [Preencher] |
| Condição principal do PI-1 | [ID/síntese ou Nenhuma] |
| Classificação | [Focal, funcional ou sistêmica] |
| Estratégia inicial | [Preencher] |
| Prazo ou condição | [Preencher] |
| Risco principal | [ID/síntese] |
| Autoridade | [Nome] |
| Responsável pela implantação | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Envelope de autonomia | [Síntese] |
| Gatilho principal de retorno | [Preencher] |
| Resultado da abertura | [Estado] |
| Condições pendentes | [IDs ou Nenhuma] |
| Próximo movimento | Elaborar Plano de Implantação |

## 52. Teste de reconstrução

Antes da aprovação, uma pessoa autorizada que não participou da elaboração deve tentar responder:

1. Qual implantação está sendo aberta?
2. De que transição ela se origina?
3. Qual linha de base e versão a vinculam?
4. Qual foi o resultado do PI-1?
5. Que condições do PI-1 permanecem abertas?
6. Que capacidade deverá tornar-se real?
7. O que está incluído e excluído?
8. O que precisa ser preservado?
9. Que decisões o Módulo 4 pode tomar?
10. Que mudança deve retornar ao Módulo 3?
11. Quem possui autoridade e responsabilidade?
12. Que pessoas serão afetadas e como participarão?
13. Que riscos, dependências e restrições já são materiais?
14. Que usos de dados, tecnologia e IA estão autorizados?
15. O que a aprovação do termo permite?
16. O que depende do PI-2?
17. Quem elaborará o plano?
18. Qual é a próxima ação, seu responsável e sua condição temporal?

### 52.1 Resultado

- [ ] Todas as respostas puderam ser reconstruídas.
- [ ] Existem lacunas não impeditivas registradas.
- [ ] Existem lacunas impeditivas; o termo retorna ao estado Em elaboração.
- [ ] A base do termo é insuficiente; o objeto retorna ao PI-1 ou ao Módulo 3.

| Questão | Lacuna | Materialidade | Correção | Responsável | Prazo |
| --- | --- | --- | --- | --- | --- |
| [Número] | [Preencher] | [Impeditiva ou não impeditiva] | [Preencher] | [Nome] | [Data] |

## 53. Critérios de qualidade

O termo está apto à aprovação quando é:

- **identificável** — ID, título, estado e fonte oficial são inequívocos;
- **originado** — transição, linha de base e PI-1 são recuperáveis;
- **delimitado** — escopo, fronteiras e não objetivos são claros;
- **orientado à capacidade** — resultado não se reduz a entrega;
- **proporcional** — profundidade e governança correspondem ao risco;
- **atribuído** — responsabilidades e autoridades foram aceitas;
- **governável** — condições possuem consequência e decisão;
- **rastreável** — objetos e versões apontam para fontes oficiais;
- **protegido** — dados, pessoas, segurança, ética e PI receberam tratamento;
- **controlado** — autonomia e retorno ao Módulo 3 estão definidos;
- **realizável** — planejamento pode ocorrer com os recursos disponíveis;
- **reconstruível** — outra pessoa consegue compreender a abertura;
- **versionado** — mudanças preservam histórico;
- **humano** — decisões não delegáveis permanecem humanas;
- **preparatório** — o termo encaminha ao plano sem antecipar execução.

## 54. Antipadrões

Evitar:

1. abrir implantação sem linha de base identificada;
2. copiar toda a arquitetura para o termo;
3. tratar o PI-1 como aprovação da execução;
4. utilizar o termo para redesenhar requisito;
5. definir escopo por lista de tarefas;
6. formular resultado como entrega;
7. registrar prazo sem condição de prontidão;
8. atribuir responsabilidade sem aceite;
9. indicar autoridade sem fundamento;
10. deixar condição sem consequência;
11. transformar lacuna em premissa;
12. esconder exclusão que cria dependência;
13. usar classificação focal para reduzir controle material;
14. registrar todo uso como adoção;
15. tratar treinamento como competência;
16. tratar envio como compreensão;
17. autorizar IA por expressão genérica;
18. permitir que fornecedor defina sozinho a configuração;
19. aceitar risco pela urgência;
20. presumir reversibilidade;
21. aprovar termo com duas linhas de base vigentes;
22. alterar versão aprovada sem histórico;
23. confundir aprovação do termo com PI-2;
24. deixar o próximo movimento sem responsável.

## 55. Versão reduzida para implantação focal

Esta versão pode ser utilizada quando a implantação for focal, de baixo risco relativo, com poucas interfaces e alta reversibilidade. A redução concentra o registro e preserva os controles materiais.

### 55.1 Identificação e origem

| Campo | Registro |
| --- | --- |
| ID e título | [Preencher] |
| Organização e contexto | [Preencher] |
| Transição | [ID e versão] |
| Linha de base | [ID e versão] |
| PI-1 | [ID, resultado e data] |
| Autoridade | [Nome] |
| Responsável pela implantação | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Prazo ou condição | [Preencher] |
| Sensibilidade | [Nível] |

### 55.2 Núcleo da abertura

| Elemento | Registro |
| --- | --- |
| Capacidade a implantar | [Preencher] |
| Manifestação observável | [Preencher] |
| Escopo e fronteira | [Preencher] |
| Não objetivos | [Preencher] |
| Preservações | [Preencher] |
| Requisitos e critérios | [IDs] |
| Condições do PI-1 | [IDs ou Nenhuma] |
| Envelope de autonomia | [Preencher] |
| Gatilhos de retorno ao Módulo 3 | [Preencher] |
| Estratégia inicial | [Preencher] |
| Pessoas afetadas | [Preencher] |
| Risco principal | [Preencher] |
| Dados, tecnologia e IA | [Condições] |
| Reversão inicial | [Preencher] |
| Pendências | [IDs ou Nenhuma] |

### 55.3 Condições mínimas

- [ ] identidade e dossiê existem;
- [ ] PI-1 está registrado;
- [ ] linha de base possui versão exata;
- [ ] capacidade deriva da arquitetura;
- [ ] escopo e exclusões estão claros;
- [ ] autoridade e responsável aceitaram seus papéis;
- [ ] autonomia e retorno ao Módulo 3 estão definidos;
- [ ] risco, dados e IA receberam tratamento;
- [ ] prazo permite planejamento responsável;
- [ ] a aprovação foi evidenciada;
- [ ] o próximo movimento é elaborar o plano;
- [ ] execução permanece condicionada ao PI-2.

### 55.4 Decisão

**Resultado:** [Aprovado / Aprovado com condições / Não aprovado]  
**Condições:** [IDs ou Nenhuma]  
**Responsável pela implantação:** [Nome, manifestação e data]  
**Responsável pela arquitetura:** [Nome, manifestação e data]  
**Autoridade:** [Nome, decisão e data]  
**Evidência:** [Referência]

### 55.5 Regra de uso

Se a versão reduzida deixar de permitir reconstruir origem, capacidade, escopo, autoridade, risco, autonomia, retorno, proteção ou próximo movimento, utilize a versão integral.

## 56. Controle de versões

| Versão | Data | Estado | Alteração | Responsável | Decisão ou aprovação relacionada |
| --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em elaboração | Criação inicial | [Nome] | Não aplicável |
| 1.0 | [DD/MM/AAAA] | Aprovado | Linha de base da abertura | [Nome] | [ID/registro] |

### 56.1 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão aprovada | [Versão] |
| Data de vigência | [DD/MM/AAAA] |
| Fonte oficial | [Link ou caminho] |
| Versão substituída | [Versão ou Não aplicável] |
| Motivo da substituição | [Preencher ou Não aplicável] |

### 56.2 Origem do template

| Campo | Registro |
| --- | --- |
| Template | templates/01-termo-de-abertura-da-implantacao.md |
| Versão ou commit de origem | [Preencher] |
| Data da cópia | [DD/MM/AAAA] |
| Adaptação material | [ID/descrição ou Nenhuma] |
| Responsável | [Nome] |

Mudanças futuras no template-mestre não alteram automaticamente esta cópia.

## 57. Regra de conclusão do termo

O termo está concluído quando:

- possui identidade única e dossiê;
- referencia transição, linha de base e PI-1 por versão;
- declara o resultado como capacidade;
- delimita escopo, não objetivos e preservações;
- registra o envelope de autonomia;
- define gatilhos de retorno ao Módulo 3;
- atribui autoridade, responsabilidade e custódia;
- incorpora riscos, condições e dependências iniciais;
- delimita dados, tecnologia e IA;
- registra aprovação e divergências;
- transfere pendências a mecanismo de acompanhamento;
- autoriza o próximo movimento;
- mantém a execução condicionada ao PI-2;
- constitui versão vigente recuperável.

O termo permanece como registro histórico durante todo o ciclo. Mudanças posteriores atualizam a versão vigente sem apagar a autorização original.

## 58. Registro final

**ID do termo:** TER-IMP-AAAA-NNN  
**ID da implantação:** IMP-AAAA-NNN  
**Estado do termo:** [Preencher]  
**Estado da implantação:** [Preencher]  
**Versão vigente:** [Preencher]  
**Transição de origem:** [ID e versão]  
**Linha de base:** [ID e versão]  
**Resultado do PI-1:** [Preencher]  
**Resultado da abertura:** [Preencher]  
**Condições abertas:** [IDs ou Nenhuma]  
**Data da conclusão:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Autoridade da abertura:** [Nome e função]  
**Próximo documento:** templates/02-plano-de-implantacao.md  
**Próxima ação:** [Verbo, objeto, responsável e data ou condição]  
**Observações finais:** [Preencher]

---

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação do Termo de Abertura da Implantação | Estúdio LICHTARA |
