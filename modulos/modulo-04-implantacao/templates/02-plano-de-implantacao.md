# Plano de Implantação

**Identificação técnica no repositório**

```yaml
id_plano: PLA-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Plano de Implantação]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_transicao_para_implantacao: TRA-IMP-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base:
responsavel_pela_implantacao:
autoridade_da_implantacao:
responsavel_pela_arquitetura:
responsavel_operacional_indicado:
custodiante_do_plano:
custodiante_do_dossie:
data_de_criacao: AAAA-MM-DD
data_de_aprovacao:
inicio_planejado:
conclusao_planejada:
estado_do_plano: em_elaboracao
estado_da_implantacao: em_planejamento
classificacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Integração da estratégia, governança, realização, preparação, controle, validação, estabilização e transição de uma implantação  
**Documentos de referência:** Fundamentos da Implantação; Protocolo de Implantação; Matriz de Rastreabilidade da Implantação  
**Documento de entrada:** `templates/01-termo-de-abertura-da-implantacao.md` aprovado  
**Ponto de controle seguinte:** PI-2 — Prontidão para executar

**Documentos relacionados:**

- transição para implantação produzida pelo Módulo 3;
- manifesto da linha de base arquitetural;
- arquitetura integrada e desenhos dimensionais aplicáveis;
- catálogo de requisitos da arquitetura;
- registro da decisão arquitetural e condições de aprovação;
- registro do PI-1;
- Termo de Abertura da Implantação;
- Estrutura Analítica da Implantação;
- Cronograma Mestre da Implantação;
- Backlog e Quadro Kanban da Implantação;
- Matriz de Rastreabilidade da Implantação;
- registro de riscos, impedimentos, dependências e mudanças;
- planos de comunicação, treinamento e mudança organizacional;
- plano de piloto, ondas, virada e reversão;
- verificações de prontidão;
- registros de validação, aceite, configuração, estabilização e transição;
- Protocolo de Decisão do Módulo 1;
- políticas, contratos, licenças e autorizações aplicáveis.

---

## 1. Finalidade

Este plano define como uma arquitetura organizacional autorizada será transformada em capacidade implantada, verificável, estabilizada e transferível à operação.

Sua função é integrar, em uma fonte governável:

- o resultado organizacional pretendido;
- a linha de base arquitetural recebida;
- a estratégia de realização;
- os projetos, ondas e incrementos;
- as entregas e condições de implantação;
- as responsabilidades e autoridades;
- os recursos, competências e dependências;
- a preparação humana, processual, informacional, documental e técnica;
- a produção, integração, teste e liberação;
- os controles, evidências e decisões;
- a validação, o aceite e a estabilização;
- a configuração efetivamente implantada;
- a transição bilateral para a operação.

O plano deve permitir que uma pessoa autorizada reconstrua:

1. o que será implantado e por que esse objeto existe;
2. qual capacidade organizacional deverá tornar-se real;
3. que linha de base, requisitos e critérios vinculam o trabalho;
4. como o escopo foi decomposto em projetos, ondas, incrementos e entregas;
5. que estratégia limita a exposição e preserva aprendizagem e reversibilidade;
6. quem coordena, produz, participa, verifica, decide, aceita, sustenta e interrompe;
7. quando ocorrerão marcos, janelas e gates;
8. que recursos, acessos, competências, contratos e ambientes são necessários;
9. como pessoas, comunicação, treinamento e mudança serão preparados;
10. como processos, dados, documentos, controles, tecnologia e IA serão preparados;
11. como riscos, impedimentos, dependências, condições e mudanças serão governados;
12. que evidência demonstrará prontidão, conclusão, liberação, capacidade e estabilidade;
13. como contingência, reversão e continuidade serão realizadas;
14. como a operação participará e receberá a configuração;
15. que condições permitem avançar, retornar, suspender, corrigir ou encerrar.

## 2. Posição do plano no protocolo

Este plano é elaborado depois da aprovação do Termo de Abertura e permanece ativo durante planejamento, preparação, execução, validação, estabilização e transição.

```text
PI-1 — Transição aceita
        ↓
Termo de Abertura aprovado
        ↓
Plano de Implantação elaborado
        ↓
Decomposição, cronograma, backlog e rastreabilidade consolidados
        ↓
Recursos e planos humanos, técnicos e operacionais preparados
        ↓
PI-2 — Prontidão para executar
        ↓
Execução, integração e testes
        ↓
PI-3 — Prontidão para liberar
        ↓
Liberação, validação e aceite no PI-4
        ↓
Estabilização e PI-5 — Transição para operação
```

### 2.1 O que este plano governa

O plano governa a integração entre:

- origem arquitetural;
- estratégia executiva;
- unidades de realização;
- trabalho e fluxo;
- preparação das condições;
- exposição ao contexto real;
- evidência e decisão;
- configuração e continuidade.

### 2.2 O que este plano não substitui

O plano não substitui:

- a linha de base arquitetural;
- o Termo de Abertura;
- a Estrutura Analítica da Implantação;
- o cronograma detalhado;
- o backlog ativo;
- a matriz de rastreabilidade;
- os registros especializados de riscos, mudanças, pessoas, treinamento, piloto ou reversão;
- a verificação de prontidão;
- qualquer decisão de gate;
- a evidência produzida pela execução;
- o registro da configuração implantada;
- o aceite operacional.

### 2.3 Regra de integração sem duplicação

Quando um elemento possuir fonte oficial especializada, este plano deve registrar somente:

- síntese necessária à decisão;
- identificador e versão;
- localização recuperável;
- responsável pela sincronização;
- estado;
- efeito sobre marcos, riscos ou gates.

O detalhe permanece no artefato especializado. Divergências entre fontes devem ser declaradas e resolvidas; não podem coexistir silenciosamente.

## 3. Distinção entre termo, plano, preparação e PI-2

| Mecanismo | Pergunta | Resultado legítimo | Limite |
| --- | --- | --- | --- |
| Termo de Abertura | O que foi autorizado a planejar e mobilizar? | Identidade, delimitação e autoridade inicial. | Não demonstra prontidão. |
| Plano de Implantação | Como o objeto será realizado, preparado, controlado, validado e transferido? | Caminho integrado, responsabilidades e critérios. | Não comprova que as condições já existem. |
| Preparação | As condições planejadas foram materializadas e verificadas? | Evidências de recursos, competência, acesso, controles, suporte e reversão. | Não decide o gate. |
| PI-2 | O objeto delimitado pode iniciar execução? | Autorização, condição, devolução, suspensão ou retorno. | Não autoriza liberação, aceite ou transição. |

Preenchimento não equivale a prontidão. Aprovação do plano autoriza orientar e concluir a preparação dentro das alçadas registradas; o início da execução depende do `PI-2` correspondente.

## 4. Natureza do documento

Este documento é:

- o plano-mestre da implantação real;
- a fonte oficial da integração entre os planos especializados;
- uma referência viva e versionada;
- o registro da estratégia aprovada de realização;
- o mapa dos compromissos e controles;
- a base de submissão ao `PI-2`;
- a referência para replanejamento controlado;
- um componente do dossiê histórico da implantação.

Este documento não é:

- uma declaração de intenção sem responsáveis;
- uma reprodução da arquitetura;
- uma lista isolada de tarefas;
- um cronograma disfarçado;
- um relatório de progresso;
- uma autorização automática para executar;
- evidência de capacidade implantada;
- substituto para julgamento humano e decisões formais.

## 5. Autoridade e limites do plano

O plano pode:

- detalhar a mecânica de execução dentro do envelope aprovado;
- organizar projetos, ondas, incrementos e entregas;
- sequenciar trabalho e dependências;
- atribuir responsabilidade confirmada;
- selecionar meios compatíveis com a arquitetura;
- combinar ou simplificar artefatos de forma proporcional;
- incorporar condições de gates e decisões;
- atualizar previsões, respostas e caminhos dentro da alçada;
- interromper progressão quando critérios não forem atendidos.

O plano não pode:

- alterar requisito ou capacidade material;
- redefinir componente ou interface estrutural;
- ampliar escopo sem autoridade;
- reduzir critério de aceite por conveniência;
- converter falta de recurso em premissa silenciosa;
- presumir concordância, adoção ou competência;
- aceitar risco reservado a outra autoridade;
- introduzir tecnologia, dados ou IA fora da linha de base sem decisão aplicável;
- substituir o `PI-2`, `PI-3`, `PI-4` ou `PI-5`;
- absorver mudança arquitetural como replanejamento executivo.

## 6. Instruções de uso

1. Duplique este arquivo para cada implantação real.
2. Não preencha diretamente o template-mestre.
3. Armazene a cópia no dossiê `IMP-AAAA-NNN` correspondente.
4. Use o Termo de Abertura aprovado como autoridade de entrada.
5. Preserve identificadores e versões dos objetos herdados.
6. Registre `Não aplicável` somente após exame explícito.
7. Registre `Pendente` apenas com responsável e limite.
8. Planeje em detalhe o horizonte próximo e mantenha horizontes posteriores no nível de compromisso possível.
9. Não crie entrega, reunião, ferramenta ou controle sem finalidade rastreável.
10. Relacione trabalho material a capacidade, requisito, componente, risco ou decisão.
11. Diferencie planejamento, preparação, conclusão, verificação, validação, aceite e transferência.
12. Atualize o plano quando fatos alterarem sequência, risco, recurso, janela ou estratégia.
13. Submeta mudança arquitetural ao Módulo 3 antes da execução afetada.
14. Preserve o histórico de versões e das decisões de replanejamento.
15. Não atribua autoridade, responsabilidade ou aprovação à inteligência artificial.
16. Submeta somente objeto delimitado e demonstrado ao `PI-2`.

### 6.1 Convenções de preenchimento

| Convenção | Significado |
| --- | --- |
| [Preencher] | Registro necessário. |
| Não aplicável | O elemento foi examinado e não se aplica. |
| Não determinado | Ainda não há informação suficiente. |
| A confirmar | Há indicação inicial dependente de verificação. |
| Pendente | Existe tratamento, responsável e limite. |
| Nenhuma | O conjunto foi examinado e está vazio. |
| ID/versão | Referência canônica exata. |
| Link ou caminho | Localização recuperável por pessoa autorizada. |

### 6.2 Duas escalas de planejamento

| Escala | Conteúdo | Atualização |
| --- | --- | --- |
| Plano-mestre | Estratégia, ondas, marcos, recursos, riscos, preparação, gates e transição. | Em marco, decisão ou mudança material. |
| Horizonte próximo | Itens executáveis, responsáveis, dependências, evidências e critérios do ciclo imediato. | Na cadência operacional definida. |

Detalhe prematuro não deve criar falsa certeza. Ausência de detalhe no horizonte imediato também não deve esconder falta de prontidão.

## 7. Identificação do plano

| Campo | Registro |
| --- | --- |
| ID do plano | `PLA-IMP-AAAA-NNN` |
| ID da implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área, processo ou contexto | [Preencher] |
| Responsável pela implantação | [Nome, papel e contato] |
| Autoridade da implantação | [Nome, papel e alçada] |
| Custodiante do plano | [Nome, papel e contato] |
| Custodiante do dossiê | [Nome, papel e contato] |
| Período de planejamento | [Data/condição inicial e final] |
| Classificação | [Focal / funcional / sistêmica] |
| Sensibilidade | [Pública / interna / confidencial / sensível] |
| Versão | [Preencher] |
| Estado | [Preencher] |

### 7.1 Identificadores relacionados

| Objeto | ID e versão | Fonte oficial | Estado |
| --- | --- | --- | --- |
| Termo de Abertura | [ID/versão] | [Caminho] | [Estado] |
| Transição para implantação | [ID/versão] | [Caminho] | [Estado] |
| Linha de base arquitetural | [ID/versão] | [Caminho] | [Estado] |
| Projeto de arquitetura | [ID] | [Caminho] | [Estado] |
| Matriz de rastreabilidade | [ID/versão] | [Caminho] | [Estado] |
| Ocorrência do PI-1 | [ID] | [Caminho] | [Resultado] |
| Ocorrência prevista do PI-2 | [ID ou a criar] | [Caminho previsto] | [Estado] |

## 8. Estado do plano

Selecione um único estado principal vigente.

- [ ] Em elaboração
- [ ] Em revisão
- [ ] Aguardando complementação
- [ ] Aprovado para orientar preparação
- [ ] Aprovado com condições
- [ ] Em atualização controlada
- [ ] Suspenso
- [ ] Substituído
- [ ] Encerrado
- [ ] Cancelado

| Campo | Registro |
| --- | --- |
| Estado vigente | [Preencher] |
| Data | [AAAA-MM-DD] |
| Autoridade ou responsável | [Nome e papel] |
| Evidência da mudança | [ID/link] |
| Condições | [IDs ou nenhuma] |
| Próxima revisão | [Data, evento ou gate] |

O estado do plano não substitui o estado da implantação, de projeto, onda, incremento, entrega ou gate.

## 9. Documentos de entrada e precedência

### 9.1 Entradas obrigatórias

| Entrada | ID e versão | Localização | Autoridade | Verificação |
| --- | --- | --- | --- | --- |
| Termo de Abertura aprovado | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Transição do Módulo 3 | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Manifesto da linha de base | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Arquitetura integrada | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Requisitos e critérios | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Decisão arquitetural | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Registro do PI-1 | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |
| Políticas e obrigações aplicáveis | [Preencher] | [Caminho] | [Nome/papel] | [Conforme / condição] |

### 9.2 Ordem de autoridade

1. decisões formalmente aprovadas dentro da alçada;
2. linha de base arquitetural e suas condições;
3. Termo de Abertura vigente;
4. este plano aprovado;
5. artefatos especializados vigentes;
6. registros operacionais e evidências;
7. sínteses, painéis e comunicações derivadas.

Quando houver conflito, interrompa o uso da informação afetada, registre a divergência e acione a autoridade definida.

## 10. Linha de base de entrada e alterações

### 10.1 Linha de base recebida

| Campo | Registro |
| --- | --- |
| ID | [Preencher] |
| Versão | [Preencher] |
| Data de corte | [AAAA-MM-DD] |
| Autoridade de aprovação | [Nome/papel] |
| Manifesto | [Link/caminho] |
| Condições de uso | [Preencher] |
| Lacunas conhecidas | [IDs ou nenhuma] |

### 10.2 Relação do plano com a linha de base

- [ ] O plano preserva integralmente a linha de base.
- [ ] O plano detalha a mecânica de execução sem alterar a arquitetura.
- [ ] O plano incorpora condições autorizadas e rastreáveis.
- [ ] Existe divergência que precisa de decisão antes do `PI-2`.
- [ ] Existe possível mudança arquitetural devolvida ao Módulo 3.

### 10.3 Alterações em relação ao Termo de Abertura

| Elemento | Registro no termo | Detalhamento no plano | Classificação | Autoridade | Evidência |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Síntese/ID] | [Preencher] | [Detalhamento / mudança de plano / mudança arquitetural] | [Nome/papel] | [ID/link] |

Detalhamento não pode ampliar silenciosamente escopo, tolerância, recurso, risco ou autonomia.

## 11. Condições herdadas da abertura

### 11.1 Resultado da abertura

| Campo | Registro |
| --- | --- |
| Resultado | [Aprovada / aprovada com condições / outro] |
| Data | [AAAA-MM-DD] |
| Autoridade | [Nome/papel] |
| Registro da decisão | [ID/link] |

### 11.2 Condições vinculantes

| ID | Condição | Objeto afetado | Tratamento no plano | Evidência exigida | Responsável | Limite | Consequência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID] | [Preencher] | [ID/tipo] | [Nome] | [Data/gatilho] | [Bloqueio, retorno ou outra] |

### 11.3 Autorizações recebidas

| Autorização | Escopo | Limite | Autoridade | Evidência |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID/link] |

### 11.4 Proibições e reservas vigentes

| Proibição ou reserva | Escopo | Gatilho de consulta | Autoridade competente | Fonte |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID/link] |

## 12. Síntese da implantação

| Elemento | Síntese rastreável |
| --- | --- |
| Situação de origem | [Preencher] |
| Resultado organizacional | [Preencher] |
| Capacidade principal | [ID e descrição] |
| Capacidades habilitadoras | [IDs] |
| Pessoas ou operações afetadas | [Preencher] |
| Estratégia de realização | [Preencher] |
| Unidade inicial de valor ou aprendizagem | [ID e descrição] |
| Critério central de sucesso | [ID] |
| Risco principal | [ID e resposta] |
| Dependência principal | [ID e tratamento] |
| Condição principal do PI-1 | [ID ou nenhuma] |
| Horizonte de transição | [Preencher] |

### 12.1 Transformação pretendida

> Ao final desta implantação, [grupo ou operação] será capaz de [atividade ou decisão] em [contexto], com [critérios de qualidade, controle e limite], sustentada por [papéis, processo, informação, tecnologia ou competência].

### 12.2 O que não pode ser confundido com sucesso

- [ ] documento produzido;
- [ ] ferramenta configurada;
- [ ] treinamento realizado;
- [ ] comunicação enviada;
- [ ] entrega tecnicamente concluída;
- [ ] piloto iniciado;
- [ ] uso sem validação;
- [ ] prazo cumprido com capacidade não demonstrada;
- [ ] outro: [Preencher].

## 13. Resultado, capacidades e benefícios

### 13.1 Resultado da implantação

| ID ou referência | Declaração | Contexto | Critério | Evidência prevista | Autoridade de aceite |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [ID/descrição] | [Tipo/ID previsto] | [Nome/papel] |

### 13.2 Capacidades a implantar

| Capacidade | Tipo | Estado de origem | Estado pretendido | Incrementos | Critério de capacidade | Responsável pelo aceite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Principal / habilitadora / operacional / de controle] | [Preencher] | [Preencher] | [IDs] | [ID/descrição] | [Nome/papel] |

### 13.3 Benefícios esperados

| Benefício | Relação com capacidade | Hipótese causal | Indicador | Horizonte | Responsável pela realização | Proteção |
| --- | --- | --- | --- | --- | --- | --- |
| [ID ou referência] | [ID] | [Preencher] | [ID] | [Data/período] | [Nome/papel] | [Risco de métrica ou efeito adverso] |

Benefício esperado não substitui capacidade demonstrada. Benefício futuro deve ser transferido ao mecanismo de acompanhamento que possuirá autoridade após o encerramento da implantação.

## 14. Escopo, não objetivos e fronteiras

### 14.1 Escopo incluído

| Objeto | ID | Versão ou estado | Fronteira | Justificativa | Critério de pertencimento |
| --- | --- | --- | --- | --- | --- |
| [Capacidade, componente, unidade, local, público ou processo] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 14.2 Não objetivos e exclusões

| Elemento excluído | Motivo | Risco da exclusão | Dependência criada | Destino | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID/descrição] | [ID ou nenhuma] | [Operação, evolução, outro projeto ou encerramento] | [Nome/papel] |

### 14.3 Fronteiras da implantação

| Dimensão | Limite vigente |
| --- | --- |
| Organizacional | [Preencher] |
| Processual | [Preencher] |
| Humana | [Preencher] |
| Informacional | [Preencher] |
| Tecnológica | [Preencher] |
| Geográfica | [Preencher] |
| Temporal | [Preencher] |
| Regulatória ou contratual | [Preencher] |
| Dados e sensibilidade | [Preencher] |

### 14.4 Melhorias futuras reconhecidas

| Melhoria | Por que não integra o escopo | Condição de reconsideração | Destino | Responsável |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Backlog futuro/Módulo 8/outro] | [Nome/papel] |

## 15. Classificação e proporcionalidade

### 15.1 Classificação

- [ ] Focal
- [ ] Funcional
- [ ] Sistêmica

**Justificativa:** [Preencher]

### 15.2 Intensificadores de controle

| Fator | Nível | Evidência | Efeito sobre o plano |
| --- | --- | --- | --- |
| Impacto humano | [Baixo/médio/alto] | [ID/link] | [Preencher] |
| Irreversibilidade | [Baixa/média/alta] | [ID/link] | [Preencher] |
| Sensibilidade de dados | [Baixa/média/alta] | [ID/link] | [Preencher] |
| Criticidade operacional | [Baixa/média/alta] | [ID/link] | [Preencher] |
| Dependência externa | [Baixa/média/alta] | [ID/link] | [Preencher] |
| Uso material de IA | [Não/baixo/médio/alto] | [ID/link] | [Preencher] |
| Amplitude organizacional | [Baixa/média/alta] | [ID/link] | [Preencher] |
| Exigência legal ou contratual | [Baixa/média/alta] | [ID/link] | [Preencher] |

### 15.3 Adaptação proporcional dos artefatos

| Artefato ou controle | Forma adotada | Elementos combinados | Elementos preservados | Justificativa | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Integral / reduzida / combinada / não aplicável] | [Preencher] | [Fonte, vínculo, autoridade, evidência e memória] | [Preencher] | [Nome/papel] |

Simplificação deve reduzir carga documental, não proteção material.

## 16. Estratégia de realização

### 16.1 Alternativas examinadas

| Alternativa | Descrição | Valor | Risco | Reversibilidade | Aprendizagem | Continuidade | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Única / piloto / ondas / paralela / progressiva / virada / outra] | [Preencher] | [Preencher] | [ID/síntese] | [Preencher] | [Preencher] | [Preencher] | [Selecionada / descartada / condicionada] |

### 16.2 Estratégia selecionada

| Campo | Registro |
| --- | --- |
| Forma principal | [Preencher] |
| Justificativa | [Preencher] |
| Unidade inicial de exposição | [ID/descrição] |
| Unidade inicial de aprendizagem | [ID/descrição] |
| Regra de ampliação | [Preencher] |
| Regra de contenção | [Preencher] |
| Regra de reversão | [Preencher] |
| Condição de encerramento | [Preencher] |

### 16.3 Hipóteses da estratégia

| ID | Hipótese | Como será testada | Evidência esperada | Responsável | Limite | Consequência se refutada |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Tipo/ID previsto] | [Nome] | [Data/gatilho] | [Adaptar, conter, devolver ou encerrar] |

### 16.4 Irreversibilidades e compromissos

| Elemento | Momento de compromisso | Possibilidade de retorno | Compensação | Autoridade | Evidência |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Marco/janela] | [Preencher] | [Preencher] | [Nome/papel] | [ID/link] |

## 17. Portfólio, projetos, ondas e incrementos

### 17.1 Estrutura de realização

| Unidade | ID | Finalidade | Escopo | Capacidade | Responsável | Dependências | Gate aplicável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Programa/projeto/onda/incremento] | [ID canônico] | [Preencher] | [IDs] | [IDs] | [Nome] | [IDs] | [PI-2/PI-3/PI-4/PI-5] | [Estado] |

### 17.2 Relações entre unidades

| Origem | Relação | Destino | Efeito | Fonte oficial |
| --- | --- | --- | --- | --- |
| [ID] | [depende de / habilita / contém / precede / compartilha / bloqueia] | [ID] | [Preencher] | [Matriz/caminho] |

### 17.3 Critérios de criação de uma unidade

Crie projeto, onda ou incremento distinto somente quando houver pelo menos uma diferença material de:

- resultado ou capacidade;
- autoridade;
- risco;
- público ou contexto;
- ambiente ou janela;
- dependência;
- estratégia de liberação;
- critério de validação;
- configuração ou transição operacional.

## 18. Decomposição da arquitetura em realização

O detalhamento pertence a `templates/03-estrutura-analitica-da-implantacao.md`.

### 18.1 Percurso mínimo

```text
linha de base
  → capacidade
  → componente ou condição
  → entrega
  → incremento
  → pacote de trabalho
  → item de backlog
  → evidência
  → configuração implantada
```

### 18.2 Síntese da decomposição

| Capacidade | Componentes ou condições | Entregas | Incrementos | Pacotes | Critério de cobertura | Lacunas |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [IDs] | [IDs] | [IDs] | [Preencher] | [IDs ou nenhuma] |

### 18.3 Fonte oficial

| Campo | Registro |
| --- | --- |
| Documento | Estrutura Analítica da Implantação |
| ID ou referência | [Preencher] |
| Versão | [Preencher] |
| Localização | [Caminho] |
| Responsável pela sincronização | [Nome] |
| Estado | [Preencher] |

Trabalho sem origem ou obrigação sem caminho de realização constitui lacuna de rastreabilidade.

## 19. Plano de rastreabilidade

O registro do dossiê real pertence a `templates/06-matriz-de-rastreabilidade-da-implantacao.md` e deve seguir o método definido em `03-matriz-de-rastreabilidade-da-implantacao.md`.

### 19.1 Fonte oficial dos vínculos

| Campo | Registro |
| --- | --- |
| ID da matriz | `MTR-IMP-AAAA-NNN` |
| Versão | [Preencher] |
| Localização | [Caminho] |
| Responsável | [Nome] |
| Cadência de atualização | [Evento/período] |
| Última verificação | [Data e resultado] |

### 19.2 Cobertura planejada

| Direção | Pergunta | Método | Marco | Responsável |
| --- | --- | --- | --- | --- |
| Origem | Todo trabalho material possui fundamento? | [Preencher] | [PI-2/outro] | [Nome] |
| Realização | Toda obrigação possui caminho de realização? | [Preencher] | [PI-2/outro] | [Nome] |
| Evidência | Todo critério material possui evidência prevista e produzida? | [Preencher] | [PI-3/PI-4] | [Nome] |
| Decisão | Toda diferença e risco material possui decisão? | [Preencher] | [Gate] | [Nome] |
| Configuração | O realizado resolve para a versão implantada? | [Preencher] | [PI-4] | [Nome] |
| Continuidade | A configuração aceita possui responsável operacional? | [Preencher] | [PI-5] | [Nome] |

### 19.3 Lacunas iniciais

| ID | Caminho incompleto | Efeito | Tratamento | Responsável | Limite | Gate afetado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Origem → destino] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] | [PI-N] |

## 20. Sequência integrada da implantação

| Movimento | Objetivo | Objetos | Saída ou condição | Predecessora | Gate ou marco |
| --- | --- | --- | --- | --- | --- |
| 1. Consolidar o plano | Integrar estratégia e governança | [IDs] | Plano aprovado | Termo | [Marco] |
| 2. Decompor e rastrear | Tornar o trabalho reconstruível | [IDs] | Estrutura e matriz | Plano | [Marco] |
| 3. Organizar tempo e fluxo | Tornar compromissos e capacidade visíveis | [IDs] | Cronograma e backlog | Decomposição | [Marco] |
| 4. Mobilizar condições | Confirmar recursos, acessos e contratos | [IDs] | Compromissos evidenciados | Plano | [Marco] |
| 5. Preparar pessoas e operação | Criar compreensão, competência e suporte | [IDs] | Planos humanos e operacionais | Plano | `PI-2` |
| 6. Preparar configuração | Tornar processos, dados, documentos, controles e tecnologia aptos | [IDs] | Condições verificadas | Plano | `PI-2` |
| 7. Decidir prontidão | Autorizar objeto delimitado | [IDs] | Decisão do `PI-2` | Preparação | `PI-2` |
| 8. Produzir e integrar | Realizar entregas e incremento | [IDs] | Configuração candidata | `PI-2` | [Marco] |
| 9. Testar e preparar liberação | Verificar prontidão de exposição | [IDs] | Decisão do `PI-3` | Execução | `PI-3` |
| 10. Liberar e validar | Observar capacidade no contexto autorizado | [IDs] | Evidência e diferenças | `PI-3` | `PI-4` |
| 11. Aceitar e estabilizar | Confirmar capacidade e funcionamento | [IDs] | Configuração aceita e estável | Validação | `PI-4` |
| 12. Transferir e encerrar | Passar responsabilidade e preservar aprendizagem | [IDs] | Aceite operacional | Estabilização | `PI-5` |

### 20.1 Desvios da sequência

| Desvio | Motivo | Risco | Condição | Autoridade | Efeito sobre a linha de base |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID] | [Preencher] | [Nome/papel] | [Nenhum / detalhamento / retorno ao Módulo 3] |

Paralelismo é permitido quando não antecipa exposição, oculta dependência ou torna a evidência ambígua.

## 21. Entregas e critérios de conclusão

### 21.1 Registro integrado das entregas

| Entrega | Finalidade | Capacidade ou requisito | Incremento | Responsável | Critério de conclusão | Verificação | Evidência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | [ID] | [Nome] | [Preencher] | [Método e responsável] | [ID previsto] | [Estado] |

### 21.2 Definições que devem permanecer distintas

| Estado | Significado mínimo |
| --- | --- |
| Produzida | O objeto foi criado na versão indicada. |
| Integrada | O objeto funciona com as interfaces delimitadas. |
| Verificada | O objeto atende ao critério técnico ou documental definido. |
| Pronta para liberar | As condições de exposição foram demonstradas. |
| Liberada | O objeto foi exposto ao escopo autorizado. |
| Validada | A evidência no contexto permite julgar entrega, capacidade e efeitos. |
| Aceita | A autoridade competente decidiu o aceite do objeto delimitado. |
| Estabilizada | O funcionamento permanece dentro dos limites no período definido. |
| Transferida | A operação aceitou responsabilidade, condições e suporte. |

Conclusão de uma entrega não autoriza usar o estado seguinte.

### 21.3 Entregas deliberadamente não produzidas

| Entrega prevista na origem | Motivo | Efeito | Decisão | Autoridade | Destino |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [ID] | [Nome/papel] | [Preencher] |

## 22. Marcos, janelas e gates

O detalhe temporal pertence a `templates/04-cronograma-mestre-da-implantacao.md`.

### 22.1 Marcos principais

| Marco | Condição representada | Objetos | Data ou janela | Dependências | Autoridade | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [IDs] | [Data/período] | [IDs] | [Nome/papel] | [ID/tipo previsto] |

### 22.2 Janelas críticas

| Janela | Objeto | Motivo | Pré-condições | Ponto de não retorno | Contingência | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [IDs] | [Preencher] | [IDs] | [Preencher] | [ID/plano] | [Nome] |

### 22.3 Ocorrências previstas de gate

| Gate | Ocorrência | Objeto delimitado | Momento ou condição | Preparador | Decisor | Fonte de evidências |
| --- | --- | --- | --- | --- | --- | --- |
| `PI-2` | [ID ou a criar] | [Projeto/onda/incremento] | [Preencher] | [Nome] | [Nome/papel] | [Caminhos] |
| `PI-3` | [ID ou a criar] | [Versão e escopo] | [Preencher] | [Nome] | [Nome/papel] | [Caminhos] |
| `PI-4` | [ID ou a criar] | [Capacidade/configuração] | [Preencher] | [Nome] | [Nome/papel] | [Caminhos] |
| `PI-5` | [ID ou a criar] | [Configuração/pacote] | [Preencher] | [Nome] | [Nome/papel] | [Caminhos] |

Data de gate é previsão. A decisão depende da suficiência do objeto e das evidências.

## 23. Fluxo de trabalho e backlog

O detalhe pertence a `templates/05-backlog-e-quadro-kanban-da-implantacao.md`.

### 23.1 Fonte oficial do trabalho ativo

| Campo | Registro |
| --- | --- |
| Documento ou sistema | [Preencher] |
| Localização | [Caminho/link] |
| Responsável | [Nome] |
| Cadência de reposição | [Preencher] |
| Cadência de revisão | [Preencher] |
| Regra de sincronização com o cronograma | [Preencher] |

### 23.2 Estados e políticas mínimas

| Estado | Entrada | Saída | Limite de trabalho | Evidência | Autoridade para exceção |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Critério] | [Critério] | [Número/regra] | [Tipo] | [Nome/papel] |

### 23.3 Tratamento de urgência e bloqueio

| Situação | Critério | Resposta | Escalonamento | Efeito sobre compromissos | Registro |
| --- | --- | --- | --- | --- | --- |
| [Urgência/bloqueio/envelhecimento/fila crescente] | [Preencher] | [Preencher] | [Nome/papel e limite] | [Preencher] | [Fonte] |

## 24. Dependências, restrições e caminho crítico

### 24.1 Dependências materiais

| ID | Objeto dependente | Dependência | Tipo | Responsável externo ou interno | Limite | Evidência | Resposta | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [Técnica/humana/contratual/decisória/temporal/outra] | [Nome] | [Data/gatilho] | [ID/link] | [Preencher] | [Estado] |

### 24.2 Caminho crítico

| Elemento | Predecessora | Sucessora | Folga | Consequência de atraso | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [Período] | [Preencher] | [Preencher] | [Nome] |

### 24.3 Restrições do plano

| ID | Restrição | Origem | Objeto afetado | Consequência | Autoridade para alterar | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Fonte] | [IDs] | [Preencher] | [Nome/papel ou não alterável] | [Preencher] |

### 24.4 Gatilhos de replanejamento

- dependência crítica não confirmada no limite;
- indisponibilidade de pessoa ou competência crítica;
- janela perdida ou incompatível com preparação;
- risco residual acima da alçada;
- evidência negativa material;
- mudança de prioridade ou recurso;
- diferença entre linha de base e realidade;
- alteração regulatória, contratual ou tecnológica;
- inviabilidade de contingência ou reversão;
- possível mudança arquitetural.

## 25. Governança, papéis e autoridades

### 25.1 Papéis da implantação

| Papel | Pessoa ou grupo | Responsabilidades | Autoridade | Limites | Substituição | Evidência de aceite do papel |
| --- | --- | --- | --- | --- | --- | --- |
| Autoridade da implantação | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Responsável pela implantação | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Responsável pela arquitetura | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Responsável operacional indicado | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Responsável por incremento | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Verificador ou validador | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |
| Custodiante do dossiê | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Nome/regra] | [ID/link] |

### 25.2 Matriz de autoridade

| Objeto ou decisão | Propõe | Produz | Verifica | Recomenda | Decide | Aceita | Pode interromper |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] | [Papel] |

### 25.3 Segregações e conflitos

| Objeto | Segregação requerida | Motivo | Forma adotada | Exceção | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Produção/verificação/decisão/aceite] | [Risco] | [Preencher] | [Nenhuma ou decisão] | [Nome/papel] |

Responsabilidade sem autoridade ou autoridade sem competência deve ser tratada antes do objeto dependente.

## 26. Fóruns, cadências e escalonamento

### 26.1 Instâncias de governança

| Instância | Finalidade | Participantes | Cadência ou gatilho | Entradas | Saídas | Autoridade |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Papéis] | [Preencher] | [IDs/fontes] | [Decisão/registro] | [Preencher] |

### 26.2 Escalonamento

| Situação | Primeiro nível | Limite | Segundo nível | Consequência durante análise | Registro |
| --- | --- | --- | --- | --- | --- |
| [Risco/impedimento/dependência/conflito/incidente/mudança] | [Papel] | [Tempo/condição] | [Papel] | [Continuar/conter/suspender] | [Fonte] |

### 26.3 Trabalho assíncrono e ausência de manifestação

| Objeto | Canal | Prazo de manifestação | Confirmação necessária | Consequência do silêncio | Responsável |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Data/período] | [Preencher] | [Não constitui aceite / outro] | [Nome] |

## 27. Recursos, orçamento e autorizações

### 27.1 Recursos humanos e disponibilidade

| Pessoa ou papel | Competência | Disponibilidade confirmada | Período | Carga | Conflitos | Plano de continuidade | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Sim/não/condição] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID/link] |

### 27.2 Recursos materiais, tecnológicos e informacionais

| Recurso | Finalidade | Quantidade ou capacidade | Disponibilidade | Responsável | Dependência | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Data/condição] | [Nome] | [ID] | [ID/link] |

### 27.3 Orçamento e reservas

| Categoria | Estimativa | Limite autorizado | Reserva | Premissas | Aprovador | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Valor/faixa] | [Valor/faixa] | [Valor/regra] | [Preencher] | [Nome/papel] | [ID/link] |

### 27.4 Recursos ainda não autorizados

| Recurso | Objeto dependente | Decisão necessária | Responsável | Limite | Consequência |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Nome] | [Data/gatilho] | [Bloqueio/redução/retorno] |

## 28. Competências, carga e continuidade das pessoas

### 28.1 Mapa de competências críticas

| Papel | Atividade real | Competência requerida | Nível atual | Lacuna | Tratamento | Evidência requerida | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Capacitar/contratar/apoiar] | [Preencher] | [Nome] |

### 28.2 Concentração e substituição

| Conhecimento ou autoridade concentrada | Pessoa | Risco | Substituto | Transferência necessária | Limite |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Nome] | [ID] | [Nome ou inexistente] | [Preencher] | [Data/gatilho] |

### 28.3 Carga sustentável

| Grupo ou papel | Carga atual | Carga adicional | Período crítico | Sinal de sobrecarga | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Período] | [Preencher] | [Preencher] | [Nome] |

## 29. Fornecedores, contratos, licenças e terceiros

| Terceiro | Objeto fornecido | Dependência | Contrato ou licença | Obrigações | SLA ou limite | Saída ou substituição | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID] | [ID/link] | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Estado] |

### 29.1 Verificações antes do PI-2

- [ ] escopo contratado corresponde ao escopo planejado;
- [ ] responsabilidades e limites estão explícitos;
- [ ] confidencialidade e propriedade intelectual estão tratadas;
- [ ] tratamento de dados está autorizado;
- [ ] licenças cobrem ambientes e usos previstos;
- [ ] suporte, continuidade e encerramento estão definidos;
- [ ] dependência crítica possui resposta alternativa ou decisão de risco;
- [ ] evidências contratuais são recuperáveis.

## 30. Riscos, impedimentos, problemas, premissas e condições

O detalhe pertence a `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md`.

### 30.1 Síntese de controle

| ID | Tipo | Descrição | Objeto | Probabilidade ou estado | Impacto | Resposta | Responsável | Limite | Gate |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Risco/impedimento/problema/premissa/condição] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] | [PI-N] |

### 30.2 Riscos residuais e aceitação

| ID | Resposta concluída | Risco residual | Alçada requerida | Decisão | Condições | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/evidência] | [Preencher] | [Nome/papel] | [ID/pendente] | [IDs] | [Data/gatilho] |

### 30.3 Premissas

Premissa deve conter hipótese, fundamento, teste, responsável, limite e consequência. Premissa não testada que sustenta prontidão deve ser tratada como risco ou impedimento.

## 31. Controle de mudanças e configuração

### 31.1 Classes de mudança

| Classe | Exemplo | Autoridade | Tratamento |
| --- | --- | --- | --- |
| Correção de execução | Ajuste para cumprir o plano vigente. | Alçada executiva definida. | Registrar no fluxo e evidência. |
| Adaptação autorizada | Variação dentro do envelope aprovado. | Autoridade indicada no termo ou plano. | Avaliar impacto, decidir e sincronizar. |
| Mudança de plano | Alteração de sequência, recurso, marco ou resposta. | Autoridade da implantação. | Versionar plano e artefatos afetados. |
| Mudança arquitetural | Alteração material de requisito, capacidade, componente, interface ou critério. | Módulo 3 e autoridades correspondentes. | Conter objeto e devolver formalmente. |
| Mudança emergencial | Ação para conter dano ou restaurar segurança. | Alçada emergencial definida. | Registrar, estabilizar e revisar retrospectivamente. |

### 31.2 Registro de mudanças planejadas

| ID | Solicitação | Classe inicial | Objetos afetados | Análise | Decisão | Autoridade | Versões atualizadas |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [IDs] | [ID/link] | [ID/estado] | [Nome/papel] | [IDs/versões] |

### 31.3 Itens de configuração

| Item | ID | Linha de base | Versão planejada | Custodiante | Método de controle | Gate |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID] | [ID/versão] | [Versão] | [Nome] | [Preencher] | [PI-N] |

O estado efetivamente realizado será consolidado em `templates/15-registro-da-configuracao-implantada.md`; este plano registra apenas a estratégia e os itens sujeitos a controle.

## 32. Qualidade, verificação, testes e não conformidades

### 32.1 Estratégia de qualidade

| Objeto | Critério | Método | Ambiente | Amostra ou cobertura | Verificador | Evidência | Tratamento de falha |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/descrição] | [Revisão/teste/simulação/inspeção/outro] | [Preencher] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |

### 32.2 Tipos de teste aplicáveis

- [ ] funcional;
- [ ] integração;
- [ ] segurança;
- [ ] privacidade e dados;
- [ ] desempenho e capacidade;
- [ ] recuperação e continuidade;
- [ ] usabilidade e acessibilidade;
- [ ] procedimento e papel;
- [ ] controle e indicador;
- [ ] competência humana;
- [ ] modelo, sistema ou função de IA;
- [ ] cenário de exceção;
- [ ] contingência e reversão;
- [ ] outro: [Preencher].

### 32.3 Não conformidades

| ID | Objeto | Critério não atendido | Severidade | Contenção | Correção | Reteste | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Método/data] | [Nome/papel] | [Estado] |

## 33. Pessoas afetadas, participação e poder

### 33.1 Mapa de participação

| Pessoa ou grupo | Efeito da implantação | Interesse ou direito | Forma de participação | Momento | Acessibilidade | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Informar/consultar/cocriar/validar/decidir] | [Marco/cadência] | [Preencher] | [Nome] |

### 33.2 Pessoas ausentes ou sub-representadas

| Grupo | Motivo da ausência | Risco | Forma de inclusão ou proteção | Responsável | Limite |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID] | [Preencher] | [Nome] | [Data/gatilho] |

### 33.3 Poder, conflito e segurança para manifestação

| Situação | Pessoas afetadas | Efeito possível | Proteção | Canal de contestação | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] |

Ausência de manifestação não equivale a concordância. Discordância e baixa adesão devem ser investigadas antes de serem classificadas.

## 34. Impactos humanos, adoção e mudança organizacional

O detalhe pertence a `templates/10-plano-de-gestao-da-mudanca-organizacional.md`.

### 34.1 Mudanças por grupo

| Grupo | Atividade atual | Atividade futura | Papel ou autoridade | Carga | Perdas e ganhos | Apoio | Critério de adoção |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 34.2 Capacidades e práticas a preservar

| Prática ou capacidade | Quem a sustenta | Risco de perda | Proteção | Evidência |
| --- | --- | --- | --- | --- |
| [Preencher] | [Pessoa/grupo] | [ID/descrição] | [Preencher] | [ID/tipo] |

### 34.3 Hipóteses de adoção

| ID | Hipótese | Sinal observável | Método | Limite | Resposta se refutada |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Data/gatilho] | [Preencher] |

Uso não equivale a adoção, e adoção não equivale a capacidade ou legitimidade.

## 35. Comunicação e engajamento

O detalhe pertence a `templates/08-plano-de-comunicacao-e-engajamento.md`.

| Público | Necessidade | Mensagem ou decisão | Momento | Canal | Emissor | Confirmação de compreensão | Retorno |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Método] | [Canal/responsável] |

### 35.1 Eventos obrigatórios de comunicação

- mudança material de escopo, prazo, risco ou estratégia;
- decisão de gate;
- bloqueio ou suspensão;
- alteração que afete atividade, papel, acesso ou autoridade;
- janela de piloto, onda ou virada;
- incidente, contingência ou reversão;
- condição de aceite ou risco residual;
- início e conclusão de estabilização;
- transferência para operação.

Comunicação enviada não demonstra compreensão. O método de confirmação deve ser proporcional ao impacto.

## 36. Treinamento, competência e transferência de conhecimento

O detalhe pertence a `templates/09-plano-de-treinamento-e-capacitacao.md`.

| Público ou papel | Atividade | Competência | Método | Ambiente | Prática assistida | Nível de evidência | Verificador | Suporte posterior |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [1 a 6] | [Nome/papel] | [Preencher] |

### 36.1 Níveis de evidência

1. presença;
2. compreensão declarada;
3. conhecimento demonstrado;
4. desempenho assistido;
5. desempenho autônomo;
6. competência coletiva em situação real.

O nível exigido deve corresponder ao risco e à responsabilidade. Certificado ou presença não substitui desempenho quando este for necessário.

### 36.2 Conhecimento crítico

| Conhecimento | Fonte atual | Destinatário | Método de transferência | Evidência | Custodiante futuro | Risco |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Pessoa/documento] | [Pessoa/grupo] | [Preencher] | [ID/tipo] | [Nome/papel] | [ID] |

## 37. Processos, papéis e rotinas operacionais

| Processo ou rotina | Estado atual | Estado futuro | Papéis | Entradas e saídas | Exceções | Controle | Critério de prontidão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [ID/versão] | [IDs/papéis] | [Preencher] | [Preencher] | [ID] | [Preencher] |

### 37.1 Autoridade nas exceções

| Exceção | Detecção | Primeira resposta | Escalonamento | Decisor | Registro |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Sinal/controle] | [Preencher] | [Preencher] | [Nome/papel] | [Fonte] |

Processo sem responsável, autoridade ou caminho de exceção não está pronto para execução ou operação.

## 38. Informação, dados e conhecimento

### 38.1 Inventário de dados e informações

| Objeto | Fonte oficial | Finalidade | Classificação | Qualidade requerida | Acesso | Retenção | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Sistema/documento] | [Preencher] | [Nível] | [Critério] | [Papéis] | [Regra] | [Nome] |

### 38.2 Migração, conversão ou carga

| Conjunto | Origem | Destino | Transformação | Validação | Reconciliação | Retorno | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Fonte/versão] | [Destino/versão] | [Preencher] | [Método] | [Critério] | [Método] | [Nome] |

### 38.3 Qualidade e autorização

- [ ] fonte oficial identificada;
- [ ] finalidade autorizada;
- [ ] minimização aplicada;
- [ ] qualidade suficiente para o uso;
- [ ] acesso aprovado e testado;
- [ ] retenção e descarte definidos;
- [ ] dados de teste protegidos;
- [ ] migração reconciliável;
- [ ] incidente e recuperação previstos.

## 39. Documentos, registros e custódia

| Documento ou registro | ID | Função | Autor | Aprovador | Versão vigente | Publicação | Desativação anterior | Custodiante |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID] | [Preencher] | [Nome] | [Nome/papel] | [Versão] | [Data/canal] | [Método] | [Nome] |

### 39.1 Estrutura do dossiê

| Área | Localização | Conteúdo | Sensibilidade | Responsável | Regra de versão |
| --- | --- | --- | --- | --- | --- |
| Entrada | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Planejamento | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Controle | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Realização | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Evidências | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Configuração | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |
| Transição | [Caminho] | [Preencher] | [Nível] | [Nome] | [Regra] |

## 40. Indicadores, controles e realização de benefícios

### 40.1 Indicadores da implantação

| Indicador | Pergunta | Fórmula ou regra | Fonte | Frequência | Limite | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

### 40.2 Indicadores de capacidade e benefício

| Indicador | Capacidade ou benefício | Linha de base | Meta ou faixa | Horizonte | Risco de distorção | Responsável futuro |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Valor/estado] | [Valor/faixa] | [Período] | [Preencher] | [Nome/papel] |

### 40.3 Proteções

- percentual de tarefas não substitui estado verificável;
- volume de uso não substitui adoção ou valor;
- satisfação não substitui segurança ou funcionamento;
- indicador sem resposta definida não constitui controle;
- meta não pode estimular ocultação de falha, sobrecarga ou exclusão;
- benefício não demonstrado permanece hipótese.

## 41. Tecnologia, integrações e ambientes

### 41.1 Componentes tecnológicos

| Componente | ID/versão | Finalidade | Ambiente | Integrações | Responsável | Suporte | Critério de prontidão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID/versão] | [Preencher] | [Preencher] | [IDs] | [Nome] | [Preencher] | [Preencher] |

### 41.2 Integrações

| Interface | Origem | Destino | Dados ou evento | Contrato | Teste | Falha e recuperação | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [ID/versão] | [Preencher] | [ID/versão] | [ID/plano] | [Preencher] | [Nome] |

### 41.3 Ambientes e acessos

| Ambiente | Finalidade | Configuração | Acesso | Dados permitidos | Monitoramento | Recuperação | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID/versão] | [Papéis] | [Preencher] | [Preencher] | [Preencher] | [ID/link] |

## 42. Inteligência artificial

### 42.1 IA como apoio à implantação

| Uso | Sistema/modelo e versão | Dados | Saída | Verificação humana | Limite | Registro | Contingência sem IA |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Categorias/fontes] | [Preencher] | [Pessoa/método] | [Preencher] | [Caminho] | [Preencher] |

### 42.2 IA como parte da configuração implantada

| Função | Requisito | Modelo ou sistema | Ferramentas e permissões | Avaliação | Guardrails | Supervisão | Falha e saída |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [IDs] | [Nome/versão] | [Preencher] | [ID/plano] | [Preencher] | [Papel] | [Preencher] |

### 42.3 Responsabilidades não delegáveis

A IA não pode:

- aprovar o plano;
- decidir gates;
- aceitar risco;
- autorizar acesso ou uso de dados;
- alterar linha de base;
- declarar competência humana;
- aceitar capacidade implantada;
- transferir responsabilidade operacional;
- ocultar incerteza, limitação ou origem.

## 43. Ética, segurança, privacidade, conformidade e propriedade intelectual

| Domínio | Obrigação ou critério | Objeto | Controle | Verificador | Evidência | Condição impeditiva |
| --- | --- | --- | --- | --- | --- | --- |
| Ética | [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |
| Segurança | [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |
| Privacidade | [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |
| Conformidade | [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |
| Propriedade intelectual | [Preencher] | [IDs] | [Preencher] | [Nome/papel] | [ID previsto] | [Preencher] |

### 43.1 Aprovações especializadas

| Objeto | Especialidade | Pessoa ou instância | Momento | Resultado possível | Registro |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Jurídica/segurança/privacidade/ética/técnica/outra] | [Nome] | [Marco/gate] | [Aprovar/condicionar/rejeitar] | [Caminho] |

### 43.2 Condições impeditivas

- acesso ou tratamento de dados sem autorização;
- risco de dano material sem controle ou alçada;
- licença incompatível com o uso;
- ausência de supervisão necessária;
- impossibilidade de auditoria ou explicação requerida;
- violação de obrigação legal, ética, contratual ou autoral;
- controle crítico não testado;
- especialista obrigatório ausente.

## 44. Acessos, credenciais e condições de mobilização

| Recurso ou ambiente | Papel | Nível de acesso | Autorizador | Data de concessão | Teste | Revogação | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Papel] | [Preencher] | [Nome/papel] | [Data] | [Resultado] | [Data/condição] | [ID/link] |

### 44.1 Segregação e menor privilégio

| Acesso sensível | Necessidade | Segregação | Monitoramento | Exceção | Autoridade |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nenhuma ou ID] | [Nome/papel] |

Acesso previsto, solicitado ou aprovado não equivale a acesso concedido e testado.

## 45. Migração, conversão e coexistência

### 45.1 Estratégia

| Objeto | Estado de origem | Estado de destino | Método | Coexistência | Reconciliação | Ponto de corte | Retorno |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Dados/processo/documento/tecnologia/responsabilidade] | [ID/versão] | [ID/versão] | [Preencher] | [Regra/período] | [Critério] | [Marco] | [Método] |

### 45.2 Critérios de conclusão

- [ ] inventário de origem encerrado ou destinado;
- [ ] integridade reconciliada;
- [ ] exceções tratadas;
- [ ] duplicidades e versões concorrentes resolvidas;
- [ ] acessos antigos revogados no momento correto;
- [ ] continuidade operacional preservada;
- [ ] retorno possível ou irreversibilidade autorizada;
- [ ] configuração de destino registrada.

## 46. Piloto, ondas, virada e ampliação

O detalhe pertence a `templates/11-plano-de-piloto-ondas-virada-e-reversao.md`.

### 46.1 Unidade de exposição

| Campo | Registro |
| --- | --- |
| Tipo | [Piloto / onda / virada / ativação contínua / outro] |
| Objeto e versão | [IDs/versões] |
| Público ou unidade | [Preencher] |
| Ambiente | [Preencher] |
| Janela | [Data/período] |
| Hipótese ou capacidade | [ID] |
| Autoridade de comando | [Nome/papel] |
| Critérios de parada | [IDs/descrição] |

### 46.2 Ondas previstas

| Onda | Objeto | Público ou contexto | Entrada | Critério de ampliação | Critério de parada | Reversão | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [Preencher] | [Critério] | [Preencher] | [Preencher] | [ID/plano] | [Estado] |

### 46.3 Aprendizagem entre ondas

| Evidência | Interpretação | Adaptação permitida | Decisão necessária | Efeito sobre próxima onda | Responsável |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [ID/nenhuma] | [Preencher] | [Nome] |

Aprendizagem de execução pode ajustar a mecânica dentro da alçada. Alteração material retorna ao Módulo 3.

## 47. Liberação e PI-3

### 47.1 Estratégia de liberação

| Objeto | Versão | Escopo de exposição | Pré-condições | Autoridade de liberar | Monitoramento | Suporte | Reversão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Público/ambiente/período] | [IDs] | [Nome/papel] | [IDs/limites] | [Fonte] | [ID/plano] |

### 47.2 Evidências previstas para o PI-3

| Dimensão | Critério | Evidência prevista | Produtor | Verificador | Fonte oficial |
| --- | --- | --- | --- | --- | --- |
| Entregas e integração | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |
| Pessoas e competência | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |
| Dados e acessos | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |
| Documentos e controles | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |
| Tecnologia e integrações | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |
| Suporte, contingência e reversão | [Preencher] | [ID/tipo] | [Nome] | [Nome] | [Caminho] |

### 47.3 Limite do planejamento de liberação

Este plano prepara o caminho e os critérios. A liberação depende de uma configuração candidata identificada, evidências atuais e decisão humana na ocorrência correspondente do `PI-3`.

## 48. Contingência, reversão e continuidade

### 48.1 Cenários de contingência

| Cenário | Sinal ou gatilho | Contenção | Continuidade temporária | Comando | Comunicação | Critério de saída |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Plano/canal] | [Preencher] |

### 48.2 Reversão

| Objeto | Estado seguro de retorno | Gatilho | Autoridade | Passos | Dados e transações | Teste | Tempo limite |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [ID/versão] | [Preencher] | [Nome/papel] | [ID/plano] | [Tratamento] | [ID/evidência] | [Período] |

### 48.3 Irreversibilidade

| Elemento irreversível | Motivo | Consequência | Compensação | Decisão | Autoridade | Comunicação |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID] | [Nome/papel] | [Plano/canal] |

Contingência não é reversão automática. Cada mecanismo deve declarar que condição preserva, que perdas aceita e como a organização retorna a um estado governável.

## 49. Suporte, incidentes e recuperação

### 49.1 Modelo de suporte

| Nível | Público | Canal | Horário | Responsável | Escalonamento | Base de conhecimento | Critério de encerramento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [N1/N2/N3/outro] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Preencher] | [Caminho] | [Preencher] |

### 49.2 Incidentes

| Categoria | Severidade | Sinal | Primeira resposta | Comando | Comunicação | Evidência | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Plano/canal] | [Fonte] | [Método/prazo] |

### 49.3 Recuperação e retomada

| Objeto | Critério de recuperação | Verificação | Autoridade de retomada | Condições | Evidência |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Método] | [Nome/papel] | [Preencher] | [ID/tipo] |

## 50. Validação, aceite e PI-4

Os resultados reais serão preservados em `templates/14-registro-de-validacao-e-aceite.md`.

### 50.1 Objetos de validação

| Objeto | Pergunta de validação | Critério | Contexto | Método | Participantes | Evidência | Autoridade de aceite |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Entrega | [Preencher] | [ID] | [Preencher] | [Preencher] | [Pessoas/grupos] | [ID previsto] | [Nome/papel] |
| Capacidade | [Preencher] | [ID] | [Preencher] | [Preencher] | [Pessoas/grupos] | [ID previsto] | [Nome/papel] |
| Competência | [Preencher] | [ID] | [Preencher] | [Preencher] | [Pessoas/grupos] | [ID previsto] | [Nome/papel] |
| Efeito humano | [Preencher] | [ID] | [Preencher] | [Preencher] | [Pessoas/grupos] | [ID previsto] | [Nome/papel] |
| Controles | [Preencher] | [ID] | [Preencher] | [Preencher] | [Pessoas/grupos] | [ID previsto] | [Nome/papel] |

### 50.2 Casos e cenários

| Caso | Condição | Resultado esperado | Variação ou exceção | Evidência | Tratamento de divergência |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Tipo/ID] | [Preencher] |

### 50.3 Resultados possíveis

- aceita;
- aceita com condições;
- parcialmente aceita com fronteira verificável;
- devolvida para correção;
- rejeitada;
- revertida;
- suspensa;
- retornada ao Módulo 3.

Aceite parcial deve indicar com precisão objeto, versão, contexto, capacidade demonstrada, capacidade não demonstrada, condições, riscos e destino.

## 51. Estabilização

### 51.1 Horizonte de estabilização

| Objeto | Início | Duração ou condição | Indicadores e limites | Suporte reforçado | Critério de estabilidade | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [Data/gatilho] | [Período/condição] | [IDs] | [Preencher] | [Preencher] | [Nome] |

### 51.2 Sinais de instabilidade

| Sinal | Fonte | Limite | Resposta | Autoridade | Efeito sobre a transição |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Indicador/canal] | [Preencher] | [Preencher] | [Nome/papel] | [Continuar/estender/conter/reverter] |

### 51.3 Saída da estabilização

- [ ] funcionamento observado no período ou condições definidos;
- [ ] incidentes dentro dos limites e com resposta efetiva;
- [ ] suporte e escalonamento funcionando;
- [ ] documentos e configuração atualizados;
- [ ] pessoas operacionais aptas;
- [ ] riscos e pendências destinados;
- [ ] critérios de retorno conhecidos;
- [ ] operação concorda com a preparação da transição.

Ausência de incidente não demonstra estabilidade quando observação, volume ou contexto forem insuficientes.

## 52. Transição para operação e PI-5

A passagem bilateral será formalizada em `templates/17-transicao-para-operacao.md`.

### 52.1 Objeto da transição

| Configuração | Versão | Capacidades | Contexto | Responsável de origem | Responsável de destino | Data ou condição |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [IDs] | [Preencher] | [Nome/papel] | [Nome/papel] | [Preencher] |

### 52.2 Pacote operacional previsto

- [ ] manifesto da configuração implantada;
- [ ] diferenças em relação à linha de base;
- [ ] capacidades e critérios aceitos;
- [ ] procedimentos, documentos e fontes oficiais;
- [ ] papéis, autoridades e escalonamentos;
- [ ] indicadores, limites e respostas;
- [ ] acessos, ambientes e ativos;
- [ ] suporte, manutenção e fornecedores;
- [ ] competências e conhecimento transferidos;
- [ ] riscos, condições e pendências residuais;
- [ ] contingência, reversão e critérios de retorno;
- [ ] histórico de decisões, evidências e gates;
- [ ] itens destinados à evolução.

### 52.3 Preparação bilateral

| Verificação | Responsável pela implantação | Responsável operacional | Evidência | Estado |
| --- | --- | --- | --- | --- |
| Objeto e versão compreendidos | [Nome] | [Nome] | [ID] | [Estado] |
| Capacidade de sustentação | [Nome] | [Nome] | [ID] | [Estado] |
| Conhecimento e documentação | [Nome] | [Nome] | [ID] | [Estado] |
| Riscos e pendências | [Nome] | [Nome] | [ID] | [Estado] |
| Suporte e retorno | [Nome] | [Nome] | [ID] | [Estado] |

Planejar a transferência não obriga a operação a aceitar objeto sem condição de sustentação.

## 53. Evidências e registros

### 53.1 Plano de evidências

| Evidência prevista | Objeto | Critério | Produtor | Método | Momento | Verificador | Custódia | Gate |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [ID] | [ID] | [Nome] | [Preencher] | [Marco] | [Nome] | [Caminho] | [PI-N] |

### 53.2 Requisitos de evidência

Toda evidência material deve permitir identificar:

- objeto e versão;
- critério examinado;
- método e contexto;
- data ou período;
- produtor;
- verificador, quando aplicável;
- resultado positivo, negativo ou inconclusivo;
- limitações;
- integridade e localização;
- decisão que ela sustenta.

### 53.3 Evidência negativa e incerteza

| ID | Objeto | Resultado | Limitação ou incerteza | Efeito | Tratamento | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Negativo/inconclusivo] | [Preencher] | [Preencher] | [Preencher] | [ID/pendente] |

Evidência negativa não deve ser apagada por correção posterior. O histórico preserva o que foi aprendido e por que a decisão mudou.

## 54. Manifesto dos artefatos e fontes oficiais

| Objeto de informação | Fonte oficial | ID/versão | Localização | Responsável pela sincronização | Cadência ou gatilho |
| --- | --- | --- | --- | --- | --- |
| Abertura e autoridade | Termo de Abertura | [ID/versão] | [Caminho] | [Nome] | [Mudança material] |
| Estratégia integrada | Plano de Implantação | [ID/versão] | [Caminho] | [Nome] | [Marco/decisão] |
| Decomposição | Estrutura Analítica | [ID/versão] | [Caminho] | [Nome] | [Mudança de escopo] |
| Tempo e marcos | Cronograma Mestre | [ID/versão] | [Caminho] | [Nome] | [Cadência] |
| Trabalho ativo | Backlog/Kanban | [ID/versão] | [Caminho] | [Nome] | [Cadência] |
| Vínculos | Matriz de Rastreabilidade | [ID/versão] | [Caminho] | [Nome] | [Evento material] |
| Riscos e mudanças | Registro integrado | [ID/versão] | [Caminho] | [Nome] | [Cadência/evento] |
| Pessoas e mudança | Planos humanos | [IDs/versões] | [Caminhos] | [Nome] | [Marco/evento] |
| Liberação e reversão | Plano especializado | [ID/versão] | [Caminho] | [Nome] | [Onda/liberação] |
| Evidências e aceite | Registros correspondentes | [IDs/versões] | [Caminhos] | [Nome] | [Gate] |
| Configuração implantada | Registro da configuração | [ID/versão] | [Caminho] | [Nome] | [Mudança/aceite] |
| Operação | Transição para operação | [ID/versão] | [Caminho] | [Nome] | [PI-5] |

O resultado consolidado da realização será produzido em `templates/16-relatorio-de-implantacao.md` quando o escopo exigir relatório próprio.

### 54.1 Divergências entre fontes

| ID | Fontes divergentes | Elemento | Regra de contenção | Autoridade | Decisão | Sincronização |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [Preencher] | [Preencher] | [Nome/papel] | [ID/pendente] | [Responsável/data] |

## 55. Monitoramento e saúde da implantação

### 55.1 Perguntas de acompanhamento

- O trabalho atual permanece ligado à capacidade e à linha de base?
- O fluxo respeita a capacidade real das pessoas e equipes?
- Dependências e riscos estão envelhecendo sem resposta?
- O plano reflete o que existe ou preserva premissas já refutadas?
- As pessoas afetadas compreendem e conseguem participar?
- A preparação está produzindo evidência ou apenas documentos?
- Mudanças estão dentro da alçada executiva?
- A configuração candidata continua reversível no nível exigido?
- A operação participa antes da transferência?
- Há sinais de dano, exclusão, sobrecarga ou perda de legitimidade?

### 55.2 Painel sintético

| Dimensão | Estado | Evidência | Tendência | Limite | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Escopo e linha de base | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Trabalho e fluxo | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Recursos e dependências | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Pessoas e competência | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Técnica, dados e controles | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Riscos e mudanças | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |
| Operação e transição | [Estado] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

Estado verde sem evidência não constitui condição de avanço.

### 55.3 Ciclos PDCA e aprendizagem controlada

| Gatilho | Objeto | Pergunta do ciclo | Ajuste dentro da alçada | Evidência | Decisão ou retorno | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Preencher] | [Preencher] | [ID/tipo] | [ID/nenhuma] | `templates/12-registro-de-ciclo-pdca.md` |

PDCA corrige ou adapta a execução dentro do envelope autorizado. Não constitui licença para redesenhar a arquitetura.

## 56. Preparação do PI-2

### 56.1 Objeto submetido

| Campo | Registro |
| --- | --- |
| Ocorrência | [ID ou a criar] |
| Projeto, onda ou incremento | [ID] |
| Escopo | [IDs] |
| Versões | [Preencher] |
| Ambiente | [Preencher] |
| Início pretendido | [Data/condição] |
| Trabalho autorizado se aprovado | [IDs/tipos] |
| Trabalho que permanece bloqueado | [IDs/tipos] |

### 56.2 Dimensões de prontidão planejadas

| Dimensão | Critério | Evidência requerida | Fonte | Responsável | Estado preliminar | Lacuna |
| --- | --- | --- | --- | --- | --- | --- |
| Arquitetural | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Trabalho e planejamento | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Pessoas e participação | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Processos e autoridade | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Informação, dados e conhecimento | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Documentação | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Indicadores e controles | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Tecnologia e integrações | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Inteligência artificial | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Segurança, ética e conformidade | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Suporte, contingência e reversão | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |
| Operação futura | [Preencher] | [ID/tipo] | [Caminho] | [Nome] | [Estado] | [ID/nenhuma] |

### 56.3 Pergunta do PI-2

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

### 56.4 Resultado que este plano pode sustentar

O plano pode demonstrar que:

- o caminho de realização está definido;
- os responsáveis aceitaram seus papéis;
- as condições foram identificadas;
- as evidências necessárias são conhecidas;
- a preparação pode ser verificada;
- lacunas e riscos estão visíveis;
- o objeto submetido possui fronteira;
- retornos e consequências estão definidos.

Ele não pode, por si só, demonstrar que cada condição já está materializada.

## 57. Pendências e condições anteriores ao PI-2

| ID | Pendência ou condição | Objeto | Impeditiva? | Tratamento | Evidência | Responsável | Limite | Consequência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | [Sim/não/condicional] | [Preencher] | [ID/tipo] | [Nome] | [Data/gatilho] | [Preencher] |

### 57.1 Regra para condição aceita

Condição submetida a gate deve declarar:

1. objeto e fronteira;
2. motivo;
3. risco residual;
4. responsável;
5. prazo ou gatilho;
6. limite de operação ou execução;
7. evidência de atendimento;
8. autoridade de confirmação;
9. consequência do descumprimento.

Condição sem esses elementos permanece lacuna, não ressalva governável.

## 58. Submissão e resultado referenciado do PI-2

O registro oficial da verificação pertence a `templates/13-verificacao-de-prontidao.md` e ao registro da decisão correspondente.

### 58.1 Submissão

| Campo | Registro |
| --- | --- |
| Ocorrência do gate | [ID] |
| Objeto e versão | [IDs/versões] |
| Data da submissão | [AAAA-MM-DD] |
| Responsável pela preparação | [Nome/papel] |
| Verificação de prontidão | [ID/versão/caminho] |
| Dossiê de evidências | [Caminho] |
| Riscos residuais | [IDs] |
| Condições propostas | [IDs ou nenhuma] |

### 58.2 Resultado referenciado

- [ ] Execução autorizada
- [ ] Execução autorizada com condições
- [ ] Preparação insuficiente
- [ ] Devolução ao planejamento
- [ ] Suspensão
- [ ] Retorno ao Módulo 3
- [ ] Ainda não decidido

| Campo | Registro |
| --- | --- |
| Resultado vigente | [Preencher] |
| Autoridade | [Nome/papel] |
| Data | [AAAA-MM-DD] |
| Registro da decisão | [ID/link] |
| Objeto autorizado | [IDs/versões] |
| Condições | [IDs ou nenhuma] |
| Trabalho que permanece bloqueado | [IDs/tipos] |
| Próximo movimento | [Preencher] |

### 58.3 Proteção contra extrapolação

A decisão do `PI-2` aplica-se somente ao objeto, versão, ambiente, período e condições registrados. Autorização de um incremento não autoriza toda a implantação.

## 59. Critérios de conclusão do plano

O plano pode ser aprovado para orientar preparação quando:

- [ ] identidade, origem e linha de base estão explícitas;
- [ ] condições do Termo e do PI-1 foram incorporadas;
- [ ] resultado, capacidades, escopo e não objetivos são reconstruíveis;
- [ ] estratégia de realização foi comparada e decidida;
- [ ] projetos, ondas, incrementos e entregas possuem lógica;
- [ ] decomposição e rastreabilidade possuem fontes oficiais;
- [ ] marcos, janelas, dependências e gates estão integrados;
- [ ] trabalho ativo possui política e responsável;
- [ ] recursos, competências e autorizações foram examinados;
- [ ] riscos, impedimentos, premissas, condições e mudanças possuem governança;
- [ ] pessoas afetadas, participação, comunicação, treinamento e mudança foram planejados;
- [ ] processos, dados, documentos, indicadores, tecnologia e IA foram examinados;
- [ ] qualidade, testes, segurança, ética e conformidade possuem caminho;
- [ ] piloto, liberação, suporte, contingência e reversão estão planejados;
- [ ] validação, aceite, estabilização e transição possuem critérios;
- [ ] evidências, fontes oficiais e custódia estão definidas;
- [ ] pendências possuem responsável e limite;
- [ ] nenhuma mudança arquitetural está sendo absorvida silenciosamente;
- [ ] o objeto de preparação para o `PI-2` possui fronteira verificável;
- [ ] as aprovações do plano possuem evidência.

### 59.1 Resultado da verificação do plano

- [ ] Concluído e apto a orientar preparação
- [ ] Concluído com condições
- [ ] Necessita complementação
- [ ] Bloqueado
- [ ] Devolvido ao Módulo 3
- [ ] Suspenso

**Fundamentação:** [Preencher]

## 60. Teste de reconstrução

Uma pessoa autorizada que não participou da elaboração consegue reconstruir:

1. o resultado e as capacidades pretendidas;
2. a linha de base e as condições vinculantes;
3. o escopo, as exclusões e o envelope de autonomia;
4. a estratégia e os compromissos de realização;
5. os projetos, ondas, incrementos e entregas;
6. a relação entre arquitetura, trabalho, evidência e configuração;
7. os responsáveis e autoridades;
8. os marcos, janelas, dependências e gates;
9. os recursos, competências, contratos e acessos;
10. os riscos, mudanças, controles e retornos;
11. como pessoas e operação participam;
12. como processos, dados, documentos, tecnologia e IA serão preparados;
13. como o incremento será testado, liberado, contido e revertido;
14. como capacidade, estabilidade e transferência serão julgadas;
15. quais evidências sustentarão cada decisão;
16. o que pode avançar e o que permanece bloqueado?

### 60.1 Resultado

- [ ] Reconstrução suficiente
- [ ] Reconstrução parcial
- [ ] Reconstrução insuficiente

| Lacuna | Efeito | Correção | Responsável | Limite |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/gatilho] |

## 61. Aprovações do plano

### 61.1 Elaborado por

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Papel | [Preencher] |
| Manifestação | [Concluído / concluído com ressalvas] |
| Ressalvas | [IDs ou nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 61.2 Responsável pela implantação

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Manifestação | [Aprova / aprova com condições / não aprova] |
| Condições | [IDs ou nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 61.3 Autoridade da implantação

| Campo | Registro |
| --- | --- |
| Nome e papel | [Preencher] |
| Alçada | [Preencher] |
| Manifestação | [Aprova / aprova com condições / não aprova] |
| Condições | [IDs ou nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 61.4 Responsável pela arquitetura

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Verificação | [Preserva linha de base / requer retorno / ressalvas] |
| Ressalvas | [IDs ou nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 61.5 Responsável operacional indicado

| Campo | Registro |
| --- | --- |
| Nome | [Preencher] |
| Manifestação | [Participação confirmada / condições / não confirmada] |
| Condições | [IDs ou nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 61.6 Aprovações especializadas

| Especialidade | Pessoa ou instância | Objeto | Manifestação | Condições | Data | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Nome] | [IDs] | [Aprova/condiciona/rejeita] | [IDs] | [Data] | [ID/link] |

### 61.7 Divergências preservadas

| Pessoa ou grupo | Divergência | Efeito | Tratamento | Decisão relacionada |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID] |

## 62. Síntese executiva do plano

Preencha esta seção ao final. Ela facilita leitura executiva sem substituir as fontes detalhadas.

| Elemento | Síntese |
| --- | --- |
| Implantação | [ID e título] |
| Resultado | [Preencher] |
| Linha de base | [ID/versão] |
| Escopo | [Síntese] |
| Estratégia | [Preencher] |
| Projetos, ondas e incrementos | [IDs/síntese] |
| Período | [Preencher] |
| Responsável | [Nome] |
| Autoridade | [Nome/papel] |
| Capacidade principal | [ID] |
| Primeiro objeto do PI-2 | [ID/versão] |
| Marco seguinte | [Preencher] |
| Risco principal | [ID e resposta] |
| Dependência principal | [ID e estado] |
| Preparação humana | [Síntese/estado] |
| Preparação técnica e operacional | [Síntese/estado] |
| Reversão | [Síntese/estado] |
| Pendências impeditivas | [IDs ou nenhuma] |
| Condições | [IDs ou nenhuma] |
| Estado do plano | [Preencher] |
| Próximo movimento | [Preencher] |

## 63. Versão reduzida para implantação focal

Esta versão pode ser utilizada quando o objeto for focal, de baixa complexidade, com risco controlado e relações suficientemente simples. A redução não dispensa linha de base, autoridade, rastreabilidade, evidência, proteção humana ou decisão de gate.

### 63.1 Identificação e origem

| Campo | Registro |
| --- | --- |
| ID e título | [Preencher] |
| Termo de Abertura | [ID/versão] |
| Linha de base | [ID/versão] |
| Responsável | [Nome] |
| Autoridade | [Nome/papel] |
| Período | [Preencher] |
| Sensibilidade | [Nível] |

### 63.2 Núcleo do plano

| Elemento | Registro |
| --- | --- |
| Resultado | [Preencher] |
| Capacidade | [ID e descrição] |
| Escopo e exclusões | [Preencher] |
| Estratégia | [Preencher] |
| Incremento | [ID] |
| Entregas | [IDs] |
| Pessoas afetadas | [Preencher] |
| Recursos e acessos | [Preencher] |
| Dependências | [IDs] |
| Risco principal | [ID e resposta] |
| Comunicação e treinamento | [Preencher] |
| Dados, documentos e tecnologia | [Preencher] |
| Testes e evidências | [IDs/tipos] |
| Liberação | [Escopo e critério] |
| Contingência e reversão | [Preencher] |
| Validação e aceite | [Preencher] |
| Estabilização e operação | [Preencher] |

### 63.3 Trabalho focal

| Item | Origem | Responsável | Entrada | Saída | Critério | Data ou condição | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Nome] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Estado] |

### 63.4 Controles mínimos

- [ ] Termo aprovado e linha de base identificada;
- [ ] responsabilidade e autoridade confirmadas;
- [ ] trabalho ligado à capacidade;
- [ ] riscos e dependências tratados;
- [ ] pessoas e operação preparadas;
- [ ] dados, acessos, documentos e controles verificados;
- [ ] evidência de prontidão definida;
- [ ] contingência ou retorno realizável;
- [ ] objeto do `PI-2` delimitado;
- [ ] fontes oficiais e histórico preservados.

### 63.5 Regra de uso

Se a versão reduzida não permitir compreender alguma relação material, utilize as seções integrais correspondentes. A implantação continua focal; o controle necessário apenas se torna mais explícito.

## 64. Primeiro horizonte detalhado

Detalhe somente o próximo horizonte governável. Atividades de execução permanecem bloqueadas até o `PI-2` correspondente.

### 64.1 Objetivo do horizonte

[Preencher]

### 64.2 Período ou condição

| Início | Fim ou condição de conclusão | Cadência de acompanhamento |
| --- | --- | --- |
| [Data/condição] | [Data/condição] | [Preencher] |

### 64.3 Itens comprometidos

| Item | Tipo | Objeto | Responsável | Entrada | Saída | Evidência | Dependência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Planejamento/preparação/verificação/execução autorizada] | [IDs] | [Nome] | [Preencher] | [Preencher] | [ID/tipo] | [IDs] | [Estado] |

### 64.4 Decisões do horizonte

| Decisão | Preparador | Decisor | Insumos | Momento | Registro |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Nome] | [Nome/papel] | [IDs] | [Data/gatilho] | [Caminho] |

### 64.5 Riscos e bloqueios

| ID | Objeto | Resposta imediata | Responsável | Limite | Escalonamento |
| --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Preencher] | [Nome] | [Data/gatilho] | [Nome/papel] |

## 65. Controle de versões

### 65.1 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [Preencher] |
| Estado | [Preencher] |
| Data | [AAAA-MM-DD] |
| Autoridade | [Nome/papel] |
| Linha de base relacionada | [ID/versão] |
| Versão do termo | [ID/versão] |
| Substitui | [Versão ou não aplicável] |

### 65.2 Histórico

| Versão | Data | Alteração | Motivo | Objetos afetados | Autoridade | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [AAAA-MM-DD] | Elaboração inicial | Implantação aberta | [IDs] | [Nome/papel] | [ID/link] |

### 65.3 Regra de versionamento

Nova versão é necessária quando houver mudança material de:

- escopo ou resultado;
- estratégia de realização;
- projeto, onda ou incremento;
- sequência crítica ou janela;
- responsabilidade ou autoridade;
- recurso ou dependência crítica;
- risco, contingência ou reversão;
- critério de prontidão, validação ou aceite;
- tecnologia, dados ou IA material;
- configuração ou transição operacional.

Correções editoriais podem utilizar versão menor quando não alterarem significado, autoridade ou relação.

## 66. Ciclo de vida e encerramento do plano

Este plano permanece ativo enquanto orientar alguma parte da implantação, inclusive preparação, execução, validação, estabilização ou transição.

Ele pode ser encerrado quando:

- a configuração aplicável foi transferida no `PI-5`;
- objetos cancelados ou substituídos receberam destinação;
- riscos, condições e pendências possuem responsável e mecanismo futuro;
- evidências e decisões estão preservadas;
- documentos vigentes foram transferidos ou arquivados;
- o registro final da implantação foi concluído;
- a retrospectiva recebeu destino.

A aprendizagem final será preservada em `templates/18-retrospectiva-da-implantacao.md` ou em registro proporcional explicitamente identificado.

### 66.1 Encerramento antecipado

| Campo | Registro |
| --- | --- |
| Motivo | [Preencher] |
| Objetos concluídos | [IDs] |
| Objetos incompletos | [IDs] |
| Estado preservado | [Preencher] |
| Dados, acessos e ativos | [Destino] |
| Riscos e obrigações | [Destino] |
| Comunicação | [ID/plano] |
| Autoridade | [Nome/papel] |
| Evidência | [ID/link] |

### 66.2 Substituição ou reabertura

| Evento | Documento sucessor ou nova versão | Motivo | Relação preservada | Autoridade | Data |
| --- | --- | --- | --- | --- | --- |
| [Substituição/reabertura] | [ID/versão] | [Preencher] | [Preencher] | [Nome/papel] | [Data] |

## 67. Registro final do template

**Documento:** Plano de Implantação  
**Identificador do template:** `templates/02-plano-de-implantacao.md`  
**Módulo:** 4 — Implantação  
**Sistema:** Sistema Operacional do Estúdio LICHTARA  
**Responsável metodológico:** Estúdio LICHTARA  
**Estado:** Ativo  
**Versão do template:** 1.0  
**Data:** 2026-08-03

Este template torna o planejamento da implantação governável ao integrar arquitetura, trabalho, pessoas, recursos, riscos, evidências, liberação, validação, estabilização e continuidade sem substituir suas fontes especializadas nem as decisões humanas de gate.

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação do Plano de Implantação do Módulo 4 | Estúdio LICHTARA |
