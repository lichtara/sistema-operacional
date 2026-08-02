# Registro de Validação da Arquitetura — Template Preenchível

**Identificação técnica no repositório**

```yaml
id_validacao: VAL-ARQ-AAAA-NNN
id_projeto_arquitetura: ARQ-AAAA-NNN
titulo: "[Nome da arquitetura — Registro de Validação]"
organizacao:
area_ou_processo:
id_arquitetura_integrada: ARQ-INT-AAAA-NNN
versao_do_objeto_validado:
linha_de_base_candidata:
responsavel_pela_validacao:
responsavel_pelo_registro:
data_de_abertura: AAAA-MM-DD
data_de_encerramento:
estado: planejada
resultado:
nivel_sensibilidade: "publica | interna | confidencial | sensivel"
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Template operacional preenchível  
**Função:** Planejar, executar, documentar e consolidar a validação da arquitetura  
**Entrada principal:** Arquitetura Integrada candidata e objetos arquiteturais vinculados  
**Saída principal:** Evidências, apontamentos, divergências, ajustes, condições e recomendação de validação  
**Uso transversal:** PC-3, PC-4 e PC-5

**Documentos relacionados:**

- fundamentos-da-arquitetura.md;
- protocolo-de-arquitetura.md;
- Plano de Arquitetura;
- Catálogo de Requisitos;
- Matriz de Rastreabilidade;
- Arquitetura Integrada;
- mapas dimensionais;
- avaliações de alternativas;
- registros de decisão;
- testes, simulações e protótipos;
- Transição para Implantação;
- Relatório ou Dossiê de Arquitetura.

---

## 1. Finalidade

O Registro de Validação preserva como a arquitetura foi confrontada com requisitos, evidências, pessoas, condições técnicas, cenários e limites antes de sua aprovação e implantação.

Ele registra:

- o que foi validado;
- qual versão foi examinada;
- por que a validação era necessária;
- que perguntas foram formuladas;
- que critérios foram utilizados;
- quem participou e em que papel;
- que métodos e cenários foram aplicados;
- que evidências foram produzidas;
- que divergências apareceram;
- que fragilidades ou condições foram identificadas;
- que ajustes foram realizados;
- que decisões foram exigidas;
- o que precisa ser revalidado;
- qual resultado pode ser sustentado.

O documento deve permitir responder:

> O que foi realmente confrontado, por quem, contra quais critérios, com que evidências, que limitações permaneceram e por que a arquitetura foi considerada apta — ou não — a avançar?

## 2. Resultado esperado

Ao concluir este template, uma pessoa autorizada deve conseguir:

1. identificar a versão exata do objeto validado;
2. reconstruir o plano e a execução da validação;
3. distinguir participação, consulta, validação e aprovação;
4. separar observação, interpretação, apontamento e decisão;
5. verificar se os participantes pertinentes foram incluídos;
6. compreender os critérios usados em cada verificação;
7. localizar as evidências produzidas;
8. reconhecer limitações de método, amostra, tempo ou acesso;
9. identificar divergências sem apagamento de posições;
10. acompanhar cada apontamento até seu tratamento;
11. verificar se mudanças materiais foram revalidadas;
12. compreender riscos e condições remanescentes;
13. sustentar uma recomendação para o PC-4;
14. informar ao Módulo 4 o que ainda precisa ser testado na implantação;
15. preservar aprendizado para projetos futuros.

## 3. Posição no ciclo

```text
Arquitetura candidata
          ↓
Plano de validação
          ↓
Sessões, revisões, testes e simulações
          ↓
Evidências e apontamentos
          ↓
Tratamento, decisão e ajustes
          ↓
Revalidação quando necessária
          ↓
Resultado consolidado
          ↓
Recomendação para aprovação — PC-4
          ↓
Condições e testes para implantação — PC-5
```

A validação pode ocorrer em ciclos durante o desenho e em rodada formal antes da aprovação. Este registro pode consolidar várias sessões quando elas pertencem ao mesmo ciclo, utilizam versões compatíveis e respondem ao mesmo conjunto de decisões.

## 4. Natureza da validação

Validar significa confrontar o desenho com critérios e condições reais no grau necessário para decidir se ele pode avançar.

A validação pode examinar:

- correção da representação;
- clareza;
- completude suficiente;
- rastreabilidade;
- atendimento aos requisitos;
- integração;
- viabilidade;
- carga de trabalho;
- riscos;
- manutenção;
- adequação à maturidade;
- impacto sobre pessoas;
- segurança e privacidade;
- possibilidade de implantação;
- verificabilidade;
- continuidade.

### 4.1 O que validação não significa

Validação não é:

- confirmação ritual de uma decisão já tomada;
- busca forçada de consenso;
- votação sem critério;
- aprovação automática;
- garantia de que o futuro ocorrerá exatamente como previsto;
- substituição de competência especializada;
- transferência de responsabilidade à IA;
- teste de todos os eventos futuros possíveis;
- ocultação de limitações para manter o cronograma.

### 4.2 Limite epistemológico

A validação reduz incerteza e revela fragilidades. A implantação e a operação continuarão produzindo informação nova. O resultado deve afirmar apenas o que as evidências e o método permitem sustentar.

## 5. Princípios da validação

1. **Objeto identificável** — não se valida uma arquitetura abstrata sem versão.
2. **Pergunta explícita** — cada atividade deve responder a uma questão relevante.
3. **Critério anterior ao resultado** — critérios não devem ser inventados para justificar o que ocorreu.
4. **Método proporcional** — profundidade corresponde ao impacto, risco e incerteza.
5. **Participação situada** — pessoas contribuem a partir de sua relação real com o objeto.
6. **Evidência preservada** — conclusões precisam apontar para registros localizáveis.
7. **Divergência visível** — discordância relevante não deve ser apagada.
8. **Limitação declarada** — ausência de dados, acesso ou competência altera o alcance da conclusão.
9. **Mudança rastreável** — ajuste produzido pela validação retorna aos artefatos oficiais.
10. **Revalidação material** — mudança que altera o sentido do objeto exige novo confronto.
11. **Autoridade distinta** — validar, aceitar risco e aprovar são atos diferentes.
12. **Responsabilidade humana** — IA pode apoiar, mas não ocupa responsabilidade de validação.

## 6. Unidade e granularidade do registro

### 6.1 Unidade principal

Cada arquivo preenchido representa um **ciclo de validação**: um conjunto governado de verificações sobre uma versão identificada da arquitetura ou de objetos relacionados.

### 6.2 Unidades internas

| Unidade | Prefixo | Função |
| --- | --- | --- |
| Ciclo de validação | `VAL-ARQ-AAAA-NNN` | Consolida objetivo, sessões, evidências, tratamento e resultado. |
| Sessão | `SES-VAL-NNN` | Registra um encontro, revisão ou atividade delimitada. |
| Verificação | `VRF-NNN` | Relaciona pergunta, critério, método e resultado. |
| Teste ou simulação | `TST-NNN` | Executa cenário ou condição verificável. |
| Evidência de validação | `EVV-NNN` | Preserva observação, dado, documento ou saída produzida. |
| Apontamento | `APT-NNN` | Registra algo que exige avaliação ou tratamento. |
| Divergência | `DIV-NNN` | Preserva posições distintas e decisão necessária. |
| Condição | `COND-NNN` | Limita validade, aprovação ou avanço. |

### 6.3 Quando separar ciclos

Crie outro registro quando houver:

- nova versão material da arquitetura;
- objetivo de validação diferente;
- mudança relevante de escopo;
- grupo de autoridade distinto;
- nível de sensibilidade incompatível;
- necessidade de validação especializada independente;
- reabertura após linha de base;
- volume que impeça manutenção confiável.

## 7. Instruções de uso

1. Duplique este arquivo para cada ciclo real.
2. Não preencha diretamente o template-mestre.
3. Identifique a versão do objeto antes de planejar a validação.
4. Defina perguntas e critérios antes das sessões.
5. Selecione participantes pela relação com o objeto, não apenas por hierarquia.
6. Informe objetivo, uso e limites da participação.
7. Registre uma verificação por linha.
8. Preserve evidências em sua forma original quando possível.
9. Diferencie fala observada de interpretação do facilitador.
10. Não transforme uma preferência isolada em requisito sem análise.
11. Classifique apontamentos com o vocabulário da seção 48.
12. Registre divergências na seção 50.
13. Avalie nova evidência conforme a seção 51.
14. Atualize a Matriz de Rastreabilidade depois de cada mudança material.
15. Revalide o objeto alterado quando os gatilhos da seção 55 forem atendidos.
16. Não confunda recomendação de validação com aprovação.
17. Restrinja acesso a dados e falas sensíveis.
18. Registre qualquer participação da IA.

### 7.1 Convenções

| Convenção | Significado |
| --- | --- |
| `[Preencher]` | Informação necessária. |
| `N/A` | Campo avaliado e não aplicável. |
| `Não determinado` | Evidência insuficiente para concluir. |
| `Pendente` | Tratamento futuro com responsável e limite. |
| `Conforme` | Critério atendido pelas evidências do ciclo. |
| `Parcialmente conforme` | Atendimento incompleto ou condicionado. |
| `Não conforme` | Critério não atendido. |
| `Inconclusivo` | O método ou a evidência não permite concluir. |

## 8. Proporcionalidade

### 8.1 Validação focal

Pode utilizar:

- um objeto principal;
- poucas perguntas;
- uma sessão;
- um método;
- participantes diretamente relacionados;
- registro reduzido da seção 67.

### 8.2 Validação ampliada

É recomendada quando houver:

- alto impacto humano;
- requisitos obrigatórios críticos;
- mudança de autoridade;
- dados sensíveis;
- automação ou IA com efeito material;
- integração técnica complexa;
- dependência de fornecedor;
- baixa reversibilidade;
- risco jurídico, financeiro ou de segurança;
- múltiplas áreas ou grupos afetados;
- incerteza relevante;
- arquitetura sistêmica.

### 8.3 Regra

Reduzir documentação não autoriza reduzir as perspectivas, competências ou controles necessários ao risco.

## 9. Identificação do ciclo

| Campo | Registro |
| --- | --- |
| ID da validação | VAL-ARQ-AAAA-NNN |
| Título | [Nome] |
| ID do projeto de arquitetura | ARQ-AAAA-NNN |
| Organização | [Nome] |
| Área, processo ou sistema | [Preencher] |
| Responsável pela validação | [Nome/papel] |
| Responsável pelo registro | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Data de abertura | [DD/MM/AAAA] |
| Data de encerramento | [DD/MM/AAAA] |
| Versão do registro | [0.1] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Estado | [Selecionar na seção 10] |
| Resultado | [Selecionar na seção 57] |

### 9.1 Objetos e documentos relacionados

| Documento/objeto | ID | Versão | Estado | Referência |
| --- | --- | --- | --- | --- |
| Arquitetura Integrada | ARQ-INT-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Catálogo de Requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Matriz de Rastreabilidade | MTR-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Decisão da configuração | DEC-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Linha de base candidata | LB-ARQ-NNN | [Versão] | [Estado] | [Link] |
| Plano de Arquitetura | PLA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] |

## 10. Estado do ciclo

Selecione um único estado vigente.

- [ ] **Em preparação** — objetos, perguntas e participantes estão sendo definidos.
- [ ] **Planejada** — plano aprovado e execução ainda não iniciada.
- [ ] **Em execução** — sessões, revisões ou testes estão ocorrendo.
- [ ] **Em análise** — evidências e apontamentos estão sendo consolidados.
- [ ] **Aguardando tratamento** — ajustes ou decisões são necessários.
- [ ] **Em revalidação** — mudanças materiais estão sendo novamente confrontadas.
- [ ] **Consolidada** — resultado e limitações estão registrados.
- [ ] **Consolidada com pendências** — resultado utilizável dentro de condições.
- [ ] **Suspensa** — continuidade impedida por condição registrada.
- [ ] **Cancelada** — ciclo encerrado sem conclusão.
- [ ] **Substituída** — outro ciclo constitui a referência vigente.
- [ ] **Encerrada** — tratamento concluído e registros preservados.

**Data da última mudança:** [DD/MM/AAAA]  
**Responsável:** [Nome]  
**Motivo:** [Preencher]

## 11. Governança do ciclo

### 11.1 Fonte oficial

**Local oficial das evidências:** [Referência]  
**Local oficial dos apontamentos:** [Referência]  
**Local oficial das decisões:** [Referência]  
**Local oficial das mudanças arquiteturais:** [Referência]  
**Frequência de sincronização:** [Preencher]

### 11.2 Autoridades

| Ação | Papel autorizado | Substituto | Evidência de autoridade |
| --- | --- | --- | --- |
| Planejar validação | [Papel] | [Papel] | [Referência] |
| Conduzir sessão | [Papel] | [Papel] | [Referência] |
| Confirmar evidência | [Papel] | [Papel] | [Referência] |
| Classificar apontamento | [Papel] | [Papel] | [Referência] |
| Determinar ajuste | [Papel] | [Papel] | [Referência] |
| Aceitar risco | [Papel] | [Papel] | [Referência] |
| Declarar resultado | [Papel] | [Papel] | [Referência] |
| Aprovar arquitetura | [Papel] | [Papel] | [Referência] |

### 11.3 Divergência entre fontes

Quando o registro, a arquitetura e a evidência divergirem:

1. preservar as versões envolvidas;
2. não corrigir retroativamente a evidência;
3. registrar a divergência;
4. avaliar impacto;
5. atribuir autoridade para decidir;
6. atualizar a fonte correta;
7. revalidar quando necessário.

## 12. Papéis e responsabilidades

| Papel | Responsabilidade no ciclo | Autoridade | Limite |
| --- | --- | --- | --- |
| Responsável pela validação | Planejar, garantir método e consolidar resultado | Recomendar resultado | Não aprova automaticamente a arquitetura |
| Facilitador | Conduzir sessão e preservar participação | Organizar interação | Não substituir falas por sua interpretação |
| Relator | Registrar evidências, apontamentos e decisões | Solicitar confirmação factual | Não alterar sentido sem registro |
| Pessoa afetada | Confrontar rotina, carga, clareza e exceções | Confirmar sua experiência | Não representa grupos ausentes sem mandato |
| Responsável por processo/capacidade | Confrontar finalidade, responsabilidade e manutenção | Validar funcionamento de sua esfera | Não aceitar riscos fora de sua autoridade |
| Decisor | Confrontar direção, prioridade, recursos e compensações | Decidir dentro de sua alçada | Não elimina limite técnico ou ético |
| Especialista | Examinar matéria de sua competência | Emitir parecer técnico | Não decide arquitetura fora de sua esfera |
| Responsável pela implantação | Confrontar sequência, recursos, testes e transição | Recomendar prontidão | Não altera arquitetura silenciosamente |
| Aprovador | Autorizar ou recusar avanço | Aprovar dentro da alçada | Não transforma não conformidade em adequação |
| Custodiante | Preservar registros, acesso e versões | Administrar documentação | Não modificar conteúdo técnico |

### 12.1 Participação da IA

A IA pode executar funções instrumentais. Ela não é participante responsável, validadora, aprovadora, especialista nem autoridade.

## 13. Independência e conflitos de interesse

### 13.1 Registro

| Pessoa/papel | Relação com o objeto | Interesse ou dependência | Risco de viés | Proteção adotada |
| --- | --- | --- | --- | --- |
| [Nome/papel] | [Autor, usuário, decisor, fornecedor ou outro] | [Preencher] | [Preencher] | [Revisor adicional, transparência, segregação ou outra] |

### 13.2 Perguntas

- Quem desenhou está validando sozinho o próprio trabalho?
- Quem se beneficia da decisão controla a evidência?
- Algum participante pode sofrer consequência por discordar?
- Algum fornecedor está avaliando sua própria solução?
- A liderança pode inibir relatos sobre carga ou risco?
- Existe perspectiva ausente capaz de alterar o resultado?

### 13.3 Impedimento

| Situação | Pessoa/papel | Efeito | Substituição ou proteção | Decisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Referência] |

## 14. Condições de entrada

- [ ] objeto está identificado;
- [ ] versão está congelada para o ciclo;
- [ ] escopo da validação está definido;
- [ ] perguntas e critérios foram formulados;
- [ ] fontes necessárias estão acessíveis;
- [ ] participantes pertinentes foram identificados;
- [ ] métodos correspondem às perguntas;
- [ ] limitações conhecidas estão registradas;
- [ ] dados sensíveis possuem proteção;
- [ ] responsável pela decisão está definido;
- [ ] tempo e recursos são suficientes;
- [ ] mudança durante o ciclo possui regra de tratamento.

### 14.1 Entrada incompleta

| Condição ausente | Efeito | Tratamento | Responsável | Limite | Pode iniciar? |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Complementar, aceitar condição, suspender ou devolver] | [Nome] | [Data/evento] | [Sim, não ou condicionado] |

## 15. Objeto da validação

### 15.1 Registro mestre

| ID do objeto | Classe | Nome | Versão | Estado | Fonte oficial | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ARQ/REQ/CAP/CMP/INT/FLX/CEN/IA/IND/CTL/outro] | [Preencher] | [Nome] | [Versão] | [Candidato, aprovado com condição ou outro] | [Referência] | [Papel] |

### 15.2 Objetos possíveis

- problema de arquitetura;
- requisitos;
- capacidades;
- alternativas;
- componentes;
- processos e fluxos;
- papéis, responsabilidades e autoridades;
- relações e interfaces;
- informação, conhecimento e documentos;
- comunicação;
- tecnologia e integrações;
- funções de IA;
- indicadores;
- riscos e controles;
- Arquitetura Integrada;
- condições de transição;
- critérios de aceite.

### 15.3 Congelamento da versão

**Data e hora do congelamento:** [Preencher]  
**Versão ou hash:** [Preencher]  
**Responsável:** [Nome]  
**Mudanças permitidas durante o ciclo:** [Nenhuma ou regra]  
**Local da cópia examinada:** [Referência]

## 16. Escopo e limites da validação

### 16.1 Incluído

| Objeto/dimensão | Profundidade | Pergunta central | Método previsto |
| --- | --- | --- | --- |
| [Preencher] | [Exploratória, confirmatória ou decisória] | [Preencher] | [Preencher] |

### 16.2 Fora do escopo

| Tema | Motivo | Risco da exclusão | Onde será tratado | Autoridade que aceitou |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Ciclo, módulo ou especialista] | [Papel] |

### 16.3 Limites de competência

| Tema especializado | Competência necessária | Profissional consultado | Parecer esperado | Restrição enquanto ausente |
| --- | --- | --- | --- | --- |
| [Jurídico, contábil, financeiro, trabalhista, clínico, segurança ou outro] | [Preencher] | [Nome/N/A] | [Preencher] | [Preencher] |

## 17. Objetivo e perguntas de validação

### 17.1 Objetivo

> [Verificar se o objeto atende a quais requisitos e possui quais condições reais de funcionamento?]

### 17.2 Perguntas mestras

- O desenho atende à necessidade?
- As capacidades estão corretamente formuladas?
- Os requisitos obrigatórios possuem tratamento?
- Alguma capacidade existente será perdida?
- As responsabilidades são realistas?
- As autoridades são suficientes?
- As interfaces estão claras?
- O fluxo funciona em casos normais?
- O fluxo funciona em exceções?
- A carga é sustentável?
- A tecnologia corresponde à rotina?
- A IA possui limites e verificação?
- Os dados estão protegidos?
- Os indicadores são produzíveis e utilizáveis?
- A implantação é possível?
- A manutenção está atribuída?
- Que efeito ainda não foi considerado?

### 17.3 Registro das perguntas

| ID | Pergunta | Objeto | Decisão apoiada | Critério | Método | Prioridade |
| --- | --- | --- | --- | --- | --- | --- |
| PER-VAL-NNN | [Preencher] | [ID] | [DEC/questão] | [CRT/REQ] | [Método] | [Obrigatória, alta, média ou baixa] |

### 17.4 Pergunta sem uso

Uma pergunta somente deve permanecer quando seu resultado puder alterar compreensão, desenho, risco, condição, decisão, implantação ou aprendizagem.

## 18. Critérios e escala de verificação

### 18.1 Registro de critérios

| ID | Critério | Origem | Evidência necessária | Regra de atendimento | Impeditivo? |
| --- | --- | --- | --- | --- | --- |
| CRT-VAL-NNN | [Preencher] | [REQ, princípio, norma, decisão ou risco] | [Preencher] | [Condição observável] | [Sim ou não] |

### 18.2 Escala por verificação

| Resultado | Definição |
| --- | --- |
| Conforme | Evidências suficientes sustentam o atendimento do critério. |
| Parcialmente conforme | Parte do critério foi atendida ou depende de condição. |
| Não conforme | Evidências demonstram ausência ou insuficiência. |
| Inconclusivo | Evidências ou método não permitem conclusão responsável. |
| Não aplicável | Critério foi examinado e não corresponde ao objeto. |

### 18.3 Suficiência da evidência

| Critério | Quantidade necessária | Diversidade de fonte | Atualidade | Confirmação | Limitação aceita |
| --- | --- | --- | --- | --- | --- |
| CRT-VAL-NNN | [Preencher] | [Preencher] | [Data/período] | [Quem confirma] | [Preencher] |

### 18.4 Proibição de deslocamento

Se um critério mudar depois que o resultado for conhecido, registre a mudança, o motivo e a necessidade de repetir a verificação. Não substitua silenciosamente o critério original.

## 19. Perspectivas de validação

| Perspectiva | O que examina | Participantes necessários | Objeto | Método |
| --- | --- | --- | --- | --- |
| Interna do Estúdio | Escopo, rastreabilidade, coerência, integração, proporcionalidade e registros | [Nomes/papéis] | [IDs] | [Preencher] |
| Pessoas afetadas | Compreensão, rotina, carga, acessibilidade, exceções e adoção | [Nomes/papéis] | [IDs] | [Preencher] |
| Responsável pelo funcionamento | Finalidade, responsabilidade, autoridade, entradas, manutenção e indicadores | [Nome/papel] | [IDs] | [Preencher] |
| Decisória | Direção, prioridades, recursos, compensações, riscos e condições | [Nomes/papéis] | [IDs] | [Preencher] |
| Técnica | Integração, dados, segurança, desempenho, continuidade e manutenção | [Especialistas] | [IDs] | [Preencher] |
| Especializada | Matéria fora da competência do Estúdio | [Especialistas] | [IDs] | [Preencher] |
| Implantação | Sequência, recursos, testes, treinamento, retorno e aceite | [Responsável] | [IDs] | [Preencher] |

### 19.1 Perspectiva ausente

| Perspectiva | Motivo da ausência | Impacto | Proteção alternativa | Limite da conclusão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 20. Seleção de métodos

| Método | Adequado para | Limite principal | Selecionado? | Justificativa |
| --- | --- | --- | --- | --- |
| Walkthrough | Examinar sequência e compreensão | Pode não reproduzir pressão real | [Sim ou não] | [Preencher] |
| Simulação | Observar comportamento em cenário | Depende da qualidade do cenário | [Sim ou não] | [Preencher] |
| Caso normal | Verificar fluxo esperado | Não revela exceções | [Sim ou não] | [Preencher] |
| Caso extremo | Examinar limites e carga | Pode representar evento raro | [Sim ou não] | [Preencher] |
| Caso de exceção | Verificar desvios e escalada | Exceções desconhecidas permanecem | [Sim ou não] | [Preencher] |
| Protótipo | Tornar interação ou artefato observável | Não prova sustentação operacional | [Sim ou não] | [Preencher] |
| Teste de conceito | Verificar viabilidade específica | Não valida o sistema completo | [Sim ou não] | [Preencher] |
| Revisão documental | Verificar consistência e completude | Não observa prática | [Sim ou não] | [Preencher] |
| Teste de rastreabilidade | Reconstruir origem e cobertura | Não prova funcionamento | [Sim ou não] | [Preencher] |
| Análise de carga | Confrontar trabalho e capacidade | Depende de estimativas e amostra | [Sim ou não] | [Preencher] |
| Revisão técnica | Examinar requisitos especializados | Limitada à competência do revisor | [Sim ou não] | [Preencher] |
| Teste de Coerência | Examinar alinhamento sistêmico | Não substitui testes específicos | [Sim ou não] | [Preencher] |

### 20.1 Combinação de métodos

| Pergunta | Método principal | Método complementar | Por que ambos são necessários |
| --- | --- | --- | --- |
| PER-VAL-NNN | [Preencher] | [Preencher] | [Preencher] |

## 21. Plano mestre de validação

| Verificação | Objeto | Pergunta | Critério | Método | Participantes | Evidência esperada | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VRF-NNN | [ID] | PER-VAL-NNN | CRT-VAL-NNN | [Preencher] | [Papéis] | [Preencher] | [Nome] | [Data] |

### 21.1 Ordem e dependências

| Verificação | Depende de | Deve ocorrer antes de | Condição de entrada | Consequência do atraso |
| --- | --- | --- | --- | --- |
| VRF-NNN | [IDs/N/A] | [IDs/PC] | [Preencher] | [Preencher] |

### 21.2 Marcos

| Marco | Critério | Data | Responsável | Estado |
| --- | --- | --- | --- | --- |
| Plano aprovado | [Perguntas, critérios e participantes definidos] | [Data] | [Nome] | [Estado] |
| Evidências coletadas | [Registros mínimos disponíveis] | [Data] | [Nome] | [Estado] |
| Tratamento concluído | [Apontamentos materiais decididos] | [Data] | [Nome] | [Estado] |
| Resultado consolidado | [Conclusão e limitações registradas] | [Data] | [Nome] | [Estado] |

## 22. Participantes e amostragem

### 22.1 Participantes

| Pessoa/grupo | Papel real | Relação com o objeto | Perspectiva | Sessões | Forma de participação |
| --- | --- | --- | --- | --- | --- |
| [Nome ou grupo] | [Preencher] | [Executa, decide, recebe, mantém ou é afetado] | [Preencher] | [IDs] | [Entrevista, oficina, teste, revisão ou outra] |

### 22.2 Critério de seleção

| Grupo relevante | População/contexto | Amostra | Critério | Lacuna de representação |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [N/perfis] | [Preencher] | [Preencher] |

### 22.3 Saturação e suficiência

| Perspectiva | Sinal de suficiência | Evidência alcançada | Necessidade de ampliar |
| --- | --- | --- | --- |
| [Preencher] | [Critério] | [Preencher] | [Sim, não ou condicionada] |

### 22.4 Ausência de voz

| Grupo ausente | Motivo | Possível efeito | Proteção | Condição de consulta futura |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 23. Participação segura e acessível

### 23.1 Informação aos participantes

Antes da atividade, informar:

- objetivo;
- objeto examinado;
- uso do registro;
- quem terá acesso;
- forma de atribuição ou anonimização;
- possibilidade de discordância;
- limites de confidencialidade;
- uso de gravação, quando houver;
- participação de IA, quando houver;
- canal para correção factual.

### 23.2 Acessibilidade

| Necessidade | Participante/grupo | Adaptação | Responsável | Confirmada? |
| --- | --- | --- | --- | --- |
| [Horário, linguagem, formato, tecnologia, ambiente ou outra] | [Preencher] | [Preencher] | [Nome] | [Sim ou não] |

### 23.3 Segurança para divergência

| Risco de inibição | Contexto | Proteção | Canal alternativo | Responsável |
| --- | --- | --- | --- | --- |
| [Hierarquia, exposição, conflito ou consequência] | [Preencher] | [Sessão separada, anonimização, facilitação ou outra] | [Preencher] | [Nome] |

### 23.4 Registro de concordância

**Forma de concordância para participação e registro:** [Preencher]  
**Restrições solicitadas:** [Preencher]  
**Responsável pelo tratamento:** [Nome]

## 24. Logística e preparação

| Elemento | Registro |
| --- | --- |
| Data e horário | [Preencher] |
| Local ou plataforma | [Preencher] |
| Duração | [Preencher] |
| Facilitador | [Nome] |
| Relator | [Nome] |
| Materiais | [Referências] |
| Versão apresentada | [Preencher] |
| Recursos técnicos | [Preencher] |
| Plano de contingência | [Preencher] |
| Acesso e permissões | [Preencher] |
| Gravação | [Sim, não, finalidade e retenção] |

### 24.1 Preparação do objeto

- [ ] materiais possuem versão;
- [ ] linguagem é compreensível ao público;
- [ ] dados sensíveis foram minimizados;
- [ ] cenário possui condições e resultado esperado;
- [ ] perguntas não induzem resposta;
- [ ] critérios estão disponíveis ao responsável;
- [ ] forma de captura da evidência foi testada;
- [ ] alternativa em caso de falha técnica está pronta.

## 25. Roteiro de abertura da sessão

### 25.1 Abertura mínima

1. apresentar objetivo e objeto;
2. indicar o que já está decidido e o que pode mudar;
3. explicar como as contribuições serão registradas;
4. informar acesso, confidencialidade e uso;
5. declarar papéis e autoridades;
6. explicar que divergência é permitida;
7. distinguir validação de aprovação;
8. confirmar condições de participação;
9. apresentar método e duração;
10. abrir perguntas de compreensão.

### 25.2 Confirmação

| Pergunta | Resultado | Ajuste necessário |
| --- | --- | --- |
| Participantes compreenderam o objetivo? | [Preencher] | [Preencher] |
| Compreenderam o uso do registro? | [Preencher] | [Preencher] |
| Sabem quais decisões podem ser influenciadas? | [Preencher] | [Preencher] |
| Condições de participação são adequadas? | [Preencher] | [Preencher] |

## 26. Registro mestre de sessões

| Sessão | Tipo | Data | Objeto | Participantes | Facilitador | Método | Estado | Evidências |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SES-VAL-NNN | [Interna, afetados, decisória, técnica, especializada ou implantação] | [Data] | [IDs] | [N/perfis] | [Nome] | [Preencher] | [Planejada, realizada, suspensa ou cancelada] | [EVVs] |

### 26.1 Sessão cancelada ou incompleta

| Sessão | Motivo | Efeito | Reagendamento | Evidência utilizável | Decisão |
| --- | --- | --- | --- | --- | --- |
| SES-VAL-NNN | [Preencher] | [Preencher] | [Data/N/A] | [IDs/Nenhuma] | [Preencher] |

## 27. Ficha de sessão

Duplique esta seção para cada sessão.

### 27.1 Identificação

| Campo | Registro |
| --- | --- |
| ID da sessão | SES-VAL-NNN |
| Título | [Preencher] |
| Data e horário | [Preencher] |
| Duração | [Preencher] |
| Tipo | [Preencher] |
| Objeto e versão | [IDs/versão] |
| Facilitador | [Nome] |
| Relator | [Nome] |
| Participantes | [Nomes/papéis ou referência protegida] |
| Método | [Preencher] |
| Registro original | [Link] |

### 27.2 Objetivo e perguntas

**Objetivo:** [Preencher]  
**Perguntas:** [PER-VAL IDs]  
**Critérios:** [CRT-VAL IDs]  
**Decisão apoiada:** [ID/referência]

### 27.3 Execução

**Atividades realizadas:** [Preencher]  
**Desvios do plano:** [Preencher]  
**Incidentes:** [Preencher]  
**Limitações observadas:** [Preencher]

### 27.4 Síntese factual

[Registrar o que ocorreu, sem transformar interpretações em fatos.]

### 27.5 Saídas

| Tipo | IDs | Quantidade | Local |
| --- | --- | --- | --- |
| Evidências | [EVVs] | [N] | [Referência] |
| Verificações | [VRFs] | [N] | [Referência] |
| Apontamentos | [APTs] | [N] | [Referência] |
| Divergências | [DIVs] | [N] | [Referência] |
| Decisões | [DECs] | [N] | [Referência] |

### 27.6 Confirmação do registro

| Pessoa/papel | Trecho ou objeto confirmado | Resultado | Correção solicitada | Data |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Confirmado, corrigido ou sem retorno] | [Preencher] | [Data] |

## 28. Registro de evidências

| ID | Tipo | Descrição factual | Origem | Data | Objeto | Sensibilidade | Integridade | Referência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EVV-NNN | [Fala, observação, documento, dado, teste, imagem, log ou parecer] | [Preencher] | [Pessoa/sistema/documento] | [Data] | [ID] | [Classificação] | [Original, cópia, resumo ou transcrição] | [Link] |

### 28.1 Regras

- evidência não deve ser reescrita para coincidir com a conclusão;
- resumo deve apontar para o registro original quando ele existir;
- dado sem origem ou período precisa ser marcado como limitado;
- fala individual não representa automaticamente um grupo;
- ausência de relato não demonstra ausência de problema;
- evidência contraditória deve permanecer visível;
- informação sensível pode ser segregada sem desaparecer da rastreabilidade.

### 28.2 Evidência retirada ou invalidada

| Evidência | Motivo | Autoridade | Efeito sobre verificações | Nova evidência | Data |
| --- | --- | --- | --- | --- | --- |
| EVV-NNN | [Erro, duplicação, origem inválida ou outro] | [Papel] | [IDs] | [EVV/N/A] | [Data] |

## 29. Qualidade da evidência

| Evidência | Relevância | Confiabilidade | Atualidade | Representatividade | Corroboração | Limitação | Uso permitido |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EVV-NNN | [Alta, média ou baixa] | [Alta, média ou baixa] | [Adequada ou limitada] | [Preencher] | [EVV IDs/Nenhuma] | [Preencher] | [Conclusiva, indicativa ou contextual] |

### 29.1 Perguntas de qualidade

- A evidência responde à pergunta?
- A origem é identificável?
- O registro preserva contexto?
- A informação é atual para a decisão?
- A amostra representa quem será afetado?
- Existe confirmação independente?
- Há incentivo para distorção?
- A ausência de acesso limita a conclusão?

### 29.2 Evidências conflitantes

| Evidência A | Evidência B | Contradição | Hipóteses | Investigação | Resultado |
| --- | --- | --- | --- | --- | --- |
| EVV-NNN | EVV-NNN | [Preencher] | [Preencher] | [Preencher] | [Resolvida, mantida ou inconclusiva] |

## 30. Separação entre observação, interpretação e conclusão

| ID | Observação ou evidência | Interpretação | Hipótese alternativa | Conclusão permitida | Revisor |
| --- | --- | --- | --- | --- | --- |
| ANA-VAL-NNN | [EVV/reprodução factual] | [Leitura inicial] | [Outra explicação plausível] | [O que pode ser afirmado] | [Nome] |

### 30.1 Regra

Utilize marcadores explícitos:

- **Observado:** ocorreu ou foi registrado;
- **Relatado:** uma pessoa ou fonte afirmou;
- **Inferido:** análise propõe interpretação;
- **Não determinado:** evidência não permite concluir;
- **Decidido:** autoridade escolheu tratamento;
- **Validado:** critério foi confrontado e possui resultado.

## 31. Registro mestre de verificações

| Verificação | Objeto | Pergunta | Critério | Método | Evidências | Resultado | Limitação | Apontamentos |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VRF-NNN | [ID] | PER-VAL-NNN | CRT-VAL-NNN | [Preencher] | [EVVs] | [Conforme, parcial, não conforme, inconclusivo ou N/A] | [Preencher] | [APTs] |

### 31.1 Ficha de verificação

| Campo | Registro |
| --- | --- |
| ID | VRF-NNN |
| Objeto e versão | [ID/versão] |
| Pergunta | PER-VAL-NNN |
| Critério | CRT-VAL-NNN |
| Método executado | [Preencher] |
| Participantes/fontes | [Preencher] |
| Evidências favoráveis | [EVVs] |
| Evidências contrárias | [EVVs] |
| Resultado | [Escala da seção 18.2] |
| Justificativa | [Preencher] |
| Limitação | [Preencher] |
| Apontamentos | [APTs] |
| Revalidação | [Sim, não ou condição] |

## 32. Walkthrough do funcionamento

### 32.1 Roteiro

| Etapa | Evento/entrada | Ação esperada | Responsável | Informação | Saída | Pergunta de confronto |
| --- | --- | --- | --- | --- | --- | --- |
| [N] | [Preencher] | [Preencher] | [Papel] | [ID] | [Preencher] | [Preencher] |

### 32.2 Registro

| Etapa | Compreendida? | Executável? | Ambiguidade | Dependência invisível | Exceção | Evidência | Apontamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [N] | [Sim, parcial ou não] | [Sim, parcial ou não] | [Preencher] | [Preencher] | [Preencher] | EVV-NNN | APT-NNN |

### 32.3 Resultado

**Fluxo validado:** [ID]  
**Versão:** [Preencher]  
**Trechos conformes:** [Preencher]  
**Trechos frágeis:** [Preencher]  
**Trechos não examinados:** [Preencher]

## 33. Simulação de cenário

### 33.1 Ficha do teste

| Campo | Registro |
| --- | --- |
| ID | TST-NNN |
| Cenário | [Nome/ID] |
| Tipo | [Normal, exceção, extremo, falha ou transição] |
| Objeto e versão | [IDs] |
| Objetivo | [Preencher] |
| Premissas | [IDs/descrição] |
| Condições de entrada | [Preencher] |
| Dados de teste | [Referência] |
| Participantes | [Papéis] |
| Resultado esperado | [Preencher] |
| Critério | [CRT-VAL] |
| Data | [Preencher] |

### 33.2 Execução

| Passo | Evento/entrada | Ação esperada | Ação observada | Decisão | Saída | Desvio |
| --- | --- | --- | --- | --- | --- | --- |
| [N] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 33.3 Resultado do teste

| Campo | Registro |
| --- | --- |
| Resultado | [Conforme, parcial, não conforme ou inconclusivo] |
| Evidências | [EVVs] |
| Falhas reveladas | [APTs/RSCs] |
| Comportamento degradado | [Preencher] |
| Recuperação observada | [Preencher] |
| Ajuste necessário | [Preencher] |
| Repetição necessária | [Sim, não ou condição] |

## 34. Biblioteca mínima de cenários

| Cenário | Pergunta principal | Objetos | Risco confrontado | Selecionado? | Teste |
| --- | --- | --- | --- | --- | --- |
| Funcionamento normal | O fluxo produz o resultado esperado? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Entrada incompleta | A arquitetura reconhece e trata incompletude? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Exceção de regra | Existe autoridade e registro para decidir? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Pico de volume | Carga, prazo e qualidade permanecem sustentáveis? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Ausência de pessoa-chave | A capacidade continua sem dependência pessoal crítica? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Falha de ferramenta | Existe operação alternativa e recuperação? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Indisponibilidade de IA | O funcionamento essencial continua? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Dado incorreto | O erro é detectado antes de produzir efeito material? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Interface incompleta | A transferência é recusada, corrigida ou escalada? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Acesso negado | Existe tratamento sem exposição indevida? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Incidente de segurança | Contenção, comunicação e recuperação são possíveis? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Mudança de fornecedor | Portabilidade e continuidade são suficientes? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Transição | Estado atual e futuro podem conviver sem conflito impeditivo? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Retorno | É possível interromper ou reverter de forma segura? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |
| Encerramento | Dados, responsabilidades e conhecimento são tratados? | [IDs] | [RSC] | [Sim ou não] | TST-NNN |

## 35. Protótipo e teste de conceito

| Campo | Registro |
| --- | --- |
| ID do teste | TST-NNN |
| Hipótese | [Preencher] |
| Elemento prototipado | [CMP/INT/FLX/IA] |
| Fidelidade | [Baixa, média ou alta] |
| O que o protótipo representa | [Preencher] |
| O que não representa | [Preencher] |
| Usuários/participantes | [Preencher] |
| Tarefa | [Preencher] |
| Critério | [Preencher] |
| Resultado | [Preencher] |

### 35.1 Transferência indevida de conclusão

Um protótipo pode demonstrar compreensão ou viabilidade limitada. Ele não demonstra automaticamente adoção, desempenho, segurança, integração, manutenção ou sustentabilidade em operação.

### 35.2 Próximo passo

| Achado | Conclusão permitida | Validação adicional | Responsável |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Método/objeto] | [Nome] |

## 36. Teste de rastreabilidade

### 36.1 Percurso progressivo

| Origem | Requisito | Capacidade | Componente | Validação | Implantação | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| [EVD/ACH/PRB] | REQ-NNN | CAP-NNN | CMP-NNN | VAL/TST | [ITM/N/A] | [Completo, parcial ou interrompido] |

### 36.2 Percurso regressivo

| Componente | Capacidade | Requisito | Origem | Decisão | Resultado |
| --- | --- | --- | --- | --- | --- |
| CMP-NNN | CAP-NNN | REQ-NNN | [IDs] | DEC-NNN | [Reconstruído, parcial ou não reconstruído] |

### 36.3 Objetos órfãos ou vínculos frágeis

| Objeto/vínculo | Falha | Consequência | Tratamento | Responsável |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

### 36.4 Resultado

**Amostra ou cobertura:** [Preencher]  
**Percursos completos:** [N]  
**Percursos incompletos:** [N]  
**Conclusão:** [Preencher]

## 37. Análise de carga e capacidade

| Papel/componente | Trabalho atual | Trabalho futuro | Volume | Frequência | Tempo | Pico | Capacidade disponível | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Sustentável, condicionado, insustentável ou inconclusivo] |

### 37.1 Trabalho invisível

| Trabalho não representado | Quem realiza | Gatilho | Carga | Risco | Ajuste arquitetural |
| --- | --- | --- | --- | --- | --- |
| [Coordenação, correção, verificação, documentação ou manutenção] | [Papel] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 37.2 Premissas da análise

| Premissa | Fonte | Sensibilidade do resultado | Teste necessário |
| --- | --- | --- | --- |
| PRE-NNN | [Referência] | [Alta, média ou baixa] | [Preencher] |

## 38. Revisão técnica

| Tema | Objeto | Pergunta técnica | Especialista/revisor | Evidência | Resultado | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| Integração | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Dados | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Segurança | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Privacidade | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Desempenho | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Continuidade | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |
| Manutenção | [IDs] | [Preencher] | [Nome/papel] | [EVVs] | [Preencher] | [Preencher] |

### 38.1 Parecer técnico

**Escopo do parecer:** [Preencher]  
**Competência declarada:** [Preencher]  
**Conclusão:** [Preencher]  
**Condições:** [Preencher]  
**Referência:** [Documento]

## 39. Validação especializada

### 39.1 Encaminhamento

| Questão | Especialidade | Motivo | Objeto | Impacto enquanto pendente | Profissional |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Jurídica, contábil, financeira, trabalhista, clínica, segurança, acessibilidade ou outra] | [Preencher] | [IDs] | [Preencher] | [Nome/referência] |

### 39.2 Parecer

| Campo | Registro |
| --- | --- |
| Especialista | [Nome/qualificação] |
| Escopo | [Preencher] |
| Materiais examinados | [Referências/versões] |
| Método | [Preencher] |
| Conclusão | [Preencher] |
| Limitações | [Preencher] |
| Recomendações | [Preencher] |
| Documento oficial | [Referência] |

### 39.3 Limite

O Estúdio registra e integra o parecer dentro do escopo da arquitetura. Não reformula conclusão especializada para produzir adequação aparente.

## 40. Validação com pessoas afetadas

### 40.1 Objetos de confronto

| Tema | Pergunta | Método | Participantes | Evidência | Resultado |
| --- | --- | --- | --- | --- | --- |
| Compreensão | As pessoas entendem o funcionamento e seus limites? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Rotina | As ações correspondem ao trabalho real? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Carga | O esforço é sustentável inclusive em exceções? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Competência | As capacidades necessárias existem ou podem ser desenvolvidas? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Acessibilidade | Barreiras foram reconhecidas e tratadas? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Exceções | O desenho trata situações que ocorrem na prática? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Adoção | Existem condições reais de uso e manutenção? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |
| Efeitos | Benefícios, custos e perdas estão visíveis? | [Preencher] | [Preencher] | [EVVs] | [Preencher] |

### 40.2 Discordância entre grupos

| Tema | Grupo A | Grupo B | Diferença de experiência | Efeito arquitetural | Tratamento |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Posição] | [Posição] | [Preencher] | [Preencher] | [DIV/DEC] |

## 41. Validação com decisores

| Tema | Pergunta | Evidência apresentada | Resultado | Decisão necessária |
| --- | --- | --- | --- | --- |
| Direção | A arquitetura sustenta a transformação desejada? | [Preencher] | [Preencher] | [DEC] |
| Prioridade | O primeiro ciclo corresponde às prioridades? | [Preencher] | [Preencher] | [DEC] |
| Recursos | Existem recursos para implantar e manter? | [Preencher] | [Preencher] | [DEC] |
| Compensações | Benefícios e custos foram compreendidos? | [Preencher] | [Preencher] | [DEC] |
| Riscos aceitos | A autoridade pode e decide aceitar a exposição? | [Preencher] | [Preencher] | [DEC] |
| Autoridade | Responsabilidades futuras possuem alçada? | [Preencher] | [Preencher] | [DEC] |
| Condições | Limites da aprovação estão explícitos? | [Preencher] | [Preencher] | [DEC] |

### 41.1 Registro de entendimento

**Decisor:** [Nome/papel]  
**Síntese compreendida:** [Preencher]  
**Riscos explicitamente reconhecidos:** [IDs]  
**Questões ainda abertas:** [IDs]  
**Registro de decisão:** [DEC/N/A]

## 42. Validação para implantação

| Tema | Pergunta | Responsável pela implantação | Resultado | Condição |
| --- | --- | --- | --- | --- |
| Sequência | Os componentes podem ser convertidos em entregas ordenáveis? | [Nome] | [Preencher] | [Preencher] |
| Dependências | Pré-condições estão visíveis? | [Nome] | [Preencher] | [Preencher] |
| Recursos | Pessoas, tempo, orçamento e ferramentas são reconhecíveis? | [Nome] | [Preencher] | [Preencher] |
| Treinamento | Competências e públicos estão identificados? | [Nome] | [Preencher] | [Preencher] |
| Comunicação | Mudanças e decisões a comunicar estão claras? | [Nome] | [Preencher] | [Preencher] |
| Testes | Testes de implantação podem ser planejados? | [Nome] | [Preencher] | [Preencher] |
| Aceite | Critérios são observáveis e atribuídos? | [Nome] | [Preencher] | [Preencher] |
| Reversibilidade | Interrupção, retorno e operação paralela são possíveis? | [Nome] | [Preencher] | [Preencher] |
| Acesso | Restrições de dados e documentos são compreensíveis? | [Nome] | [Preencher] | [Preencher] |

### 42.1 Itens que permanecem para o Módulo 4

| Item | Por que não pode ser validado integralmente no Módulo 3 | Teste futuro | Critério | Responsável |
| --- | --- | --- | --- | --- |
| [Preencher] | [Depende de implantação ou operação] | [Preencher] | [Preencher] | [Papel] |

## 43. Validação de dados, privacidade e segurança

| Objeto | Pergunta | Evidência | Revisor | Resultado | Condição |
| --- | --- | --- | --- | --- | --- |
| Finalidade do dado | Cada dado possui finalidade legítima e necessária? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| Minimização | O desenho evita coleta e exposição excessivas? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| Acesso | Acesso corresponde à responsabilidade? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| Transferência | Interfaces preservam contexto e proteção? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| Retenção | Atualização, retenção e descarte estão definidos? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| Incidente | Detecção, contenção e recuperação são possíveis? | [EVVs] | [Papel] | [Preencher] | [Preencher] |
| IA | Uso de dados por IA possui limite e verificação? | [EVVs] | [Papel] | [Preencher] | [Preencher] |

### 43.1 Restrição

Quando a validação exigir acesso incompatível com a sensibilidade dos dados, ajuste o método, utilize ambiente controlado ou consulte responsável competente. Não amplie acesso apenas para facilitar o ciclo.

## 44. Validação de funções de IA

### 44.1 Objeto técnico e organizacional

| Elemento | Registro |
| --- | --- |
| Função de IA | IA-NNN |
| Modelo/sistema | [Nome/versão] |
| Configuração relevante | [Prompt, base, ferramentas, regras ou referência] |
| Entrada | [Preencher] |
| Saída | [Preencher] |
| Grau de autonomia | [Preencher] |
| Responsável humano | [Papel] |
| Pessoas afetadas | [Preencher] |

### 44.2 Critérios

| Tema | Pergunta | Método | Evidência | Resultado |
| --- | --- | --- | --- | --- |
| Adequação | A função corresponde à necessidade e ao contexto? | [Preencher] | [EVVs] | [Preencher] |
| Qualidade | Saídas atendem aos critérios definidos? | [Preencher] | [EVVs] | [Preencher] |
| Limites | O sistema recusa ou escala situações proibidas? | [Preencher] | [EVVs] | [Preencher] |
| Verificação | Revisão humana detecta erros materiais? | [Preencher] | [EVVs] | [Preencher] |
| Contestação | Pessoas podem questionar efeitos relevantes? | [Preencher] | [EVVs] | [Preencher] |
| Dados | Entradas e registros possuem proteção? | [Preencher] | [EVVs] | [Preencher] |
| Viés | Diferenças relevantes foram confrontadas? | [Preencher] | [EVVs] | [Preencher] |
| Continuidade | A função essencial continua sem IA? | [Preencher] | [EVVs] | [Preencher] |
| Mudança | Alteração de modelo ou configuração aciona revalidação? | [Preencher] | [EVVs] | [Preencher] |

### 44.3 Conjunto de casos

| Caso | Entrada | Resultado esperado | Resultado observado | Erro material | Tratamento |
| --- | --- | --- | --- | --- | --- |
| Normal | [Preencher] | [Preencher] | [Preencher] | [Sim ou não] | [Preencher] |
| Ambíguo | [Preencher] | [Preencher] | [Preencher] | [Sim ou não] | [Preencher] |
| Limite | [Preencher] | [Preencher] | [Preencher] | [Sim ou não] | [Preencher] |
| Proibido | [Preencher] | [Recusar/escalar] | [Preencher] | [Sim ou não] | [Preencher] |
| Adverso | [Preencher] | [Preencher] | [Preencher] | [Sim ou não] | [Preencher] |

### 44.4 Limite

Desempenho em amostra não autoriza autonomia maior que a aprovada. Mudança de modelo, dados, ferramenta, prompt material ou contexto pode exigir revalidação.

## 45. Validação de indicadores e controles

### 45.1 Indicadores

| Indicador | Dado produzível? | Fórmula compreensível? | Decisão associada? | Frequência viável? | Risco de distorção | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| IND-NNN | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 45.2 Controles

| Controle | Risco tratado | Executável? | Evidência gerada? | Carga proporcional? | Falha tratada? | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| CTL-NNN | RSC-NNN | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 45.3 Controle aparente

| Controle | Aparência de proteção | Fragilidade real | Ajuste | Decisão |
| --- | --- | --- | --- | --- |
| CTL-NNN | [Preencher] | [Preencher] | [Preencher] | DEC-NNN |

## 46. Checklist de dimensões arquiteturais

| Dimensão | Objeto examinado | Pergunta central | Resultado | Evidência | Pendência |
| --- | --- | --- | --- | --- | --- |
| Capacidades | [IDs] | Produzem o resultado necessário e preservam o que funciona? | [Preencher] | [EVVs] | [APT] |
| Processos e fluxos | [IDs] | Funcionam de ponta a ponta em normalidade e exceção? | [Preencher] | [EVVs] | [APT] |
| Papéis e autoridades | [IDs] | Responsabilidade, autoridade, informação e capacidade são congruentes? | [Preencher] | [EVVs] | [APT] |
| Informação e dados | [IDs] | Informação adequada chega ao lugar e momento necessários? | [Preencher] | [EVVs] | [APT] |
| Conhecimento | [IDs] | Conhecimento crítico está disponível e preservado? | [Preencher] | [EVVs] | [APT] |
| Comunicação | [IDs] | Mensagens e decisões preservam contexto e confirmação? | [Preencher] | [EVVs] | [APT] |
| Documentação | [IDs] | Registros possuem finalidade, fonte e manutenção? | [Preencher] | [EVVs] | [APT] |
| Tecnologia | [IDs] | Ferramentas correspondem à rotina e possuem continuidade? | [Preencher] | [EVVs] | [APT] |
| IA | [IDs] | Funções possuem limites, verificação e responsabilidade humana? | [Preencher] | [EVVs] | [APT] |
| Indicadores | [IDs] | Medidas são produzíveis e apoiam decisões? | [Preencher] | [EVVs] | [APT] |
| Riscos e controles | [IDs] | Exposições materiais possuem proteção ou aceitação? | [Preencher] | [EVVs] | [APT] |
| Implantação | [IDs] | O desenho pode ser transformado em trabalho controlável? | [Preencher] | [EVVs] | [APT] |
| Continuidade | [IDs] | Falha, substituição, recuperação e encerramento estão tratados? | [Preencher] | [EVVs] | [APT] |

## 47. Registro mestre de apontamentos

| ID | Título | Classificação | Objeto | Evidência | Impacto | Prioridade | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| APT-NNN | [Nome] | [Selecionar na seção 48] | [ID] | [EVVs] | [Preencher] | [Selecionar na seção 49] | [Nome] | [Aberto, em análise, em tratamento, tratado, aceito, rejeitado ou substituído] |

### 47.1 Ficha de apontamento

| Campo | Registro |
| --- | --- |
| ID | APT-NNN |
| Título | [Preencher] |
| Sessão/verificação | [IDs] |
| Objeto e versão | [ID/versão] |
| Descrição factual | [Preencher] |
| Evidências | [EVVs] |
| Interpretação | [Preencher] |
| Requisito/capacidade | [IDs] |
| Efeito | [Preencher] |
| Classificação | [Seção 48] |
| Prioridade | [Seção 49] |
| Responsável | [Nome] |
| Tratamento | [Preencher] |
| Decisão | [DEC/N/A] |
| Revalidação | [Sim, não ou condição] |
| Estado | [Preencher] |

## 48. Classificação dos apontamentos

| Classificação | Uso | Destino principal |
| --- | --- | --- |
| Correção factual | Representação não corresponde à realidade ou fonte | Corrigir artefato e verificar impacto |
| Ajuste de desenho | Componente, relação ou condição precisa mudar | Arquitetura Integrada e matriz |
| Novo requisito | Necessidade legítima ainda não catalogada | Catálogo e análise de impacto |
| Divergência | Posições relevantes permanecem distintas | Registro de divergência e decisão |
| Risco | Possibilidade de efeito adverso foi revelada | Registro de riscos e controles |
| Restrição | Limite contextual, técnico, legal ou de recurso | Arquitetura, plano ou decisão |
| Pendência de implantação | Tratamento depende do Módulo 4 | Transição para Implantação |
| Questão fora do escopo | Tema não pertence ao ciclo atual | Encaminhar com limite explícito |
| Recomendação futura | Melhoria não necessária ao primeiro ciclo | Arquitetura evolutiva |
| Evidência insuficiente | Não há base para concluir | Complementar ou limitar resultado |

### 48.1 Mudança de classificação

| Apontamento | Classificação anterior | Nova classificação | Motivo | Autoridade | Data |
| --- | --- | --- | --- | --- | --- |
| APT-NNN | [Preencher] | [Preencher] | [Preencher] | [Papel] | [Data] |

## 49. Prioridade e efeito dos apontamentos

| Prioridade | Definição | Efeito sobre avanço |
| --- | --- | --- |
| Impeditiva | Pode tornar a arquitetura insegura, inviável, incompatível ou não rastreável | Impede aprovação ou implantação até decisão competente |
| Crítica | Pode causar efeito material grave ou irreversível | Exige tratamento antes da linha de base, salvo aceitação competente e defensável |
| Alta | Compromete requisito, capacidade ou interface relevante | Exige tratamento ou condição explícita |
| Média | Reduz qualidade ou cria risco administrável | Pode avançar com responsável e prazo |
| Baixa | Melhoria localizada sem efeito material imediato | Pode integrar backlog de evolução |

### 49.1 Avaliação

| Apontamento | Probabilidade/recorrência | Impacto | Reversibilidade | Urgência | Prioridade | Justificativa |
| --- | --- | --- | --- | --- | --- | --- |
| APT-NNN | [Escala] | [Escala] | [Alta, média ou baixa] | [Escala] | [Resultado] | [Preencher] |

### 49.2 Regra

Prioridade não deve ser reduzida apenas para permitir cumprimento de prazo. Mudança exige justificativa e autoridade.

## 50. Registro de divergências

### 50.1 Registro mestre

| ID | Objeto | Posição A | Posição B | Evidências | Impacto | Decisão necessária | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DIV-NNN | [ID] | [Síntese] | [Síntese] | [EVVs] | [Preencher] | [Preencher] | [Aberta, resolvida, aceita ou encaminhada] |

### 50.2 Ficha de divergência

| Campo | Registro |
| --- | --- |
| ID | DIV-NNN |
| Objeto e versão | [Preencher] |
| Pessoas/papéis | [Preencher] |
| Posição do Estúdio | [Preencher] |
| Posição divergente | [Preencher] |
| Outras posições | [Preencher] |
| Evidências de cada posição | [EVVs] |
| Requisito relacionado | [REQ] |
| Impacto | [Preencher] |
| Autoridade decisória | [Papel] |
| Prazo | [Data/evento] |
| Decisão | [DEC/N/A] |
| Condição de revisão | [Preencher] |

### 50.3 Divergência não resolvida

Uma divergência pode permanecer na linha de base somente quando seu efeito, risco, autoridade, condição de revisão e limite sobre a conclusão estiverem explícitos.

## 51. Nova evidência durante a validação

| Evidência | Origem | Qualidade | Impacto no diagnóstico | Impacto nos requisitos | Impacto na decisão | Etapa a reabrir | Tratamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EVV-NNN | [Preencher] | [Preencher] | [Nenhum, local ou material] | [IDs/efeito] | [IDs/efeito] | [M2, requisitos, alternativas, desenho, validação ou nenhuma] | [Preencher] |

### 51.1 Retorno ao diagnóstico

Considere devolver ao Módulo 2 quando a nova evidência:

- contradiz achado central;
- revela realidade não examinada;
- altera o problema;
- invalida premissa diagnóstica material;
- demonstra que o escopo foi formulado sobre base insuficiente;
- exige competência ou coleta não realizada.

### 51.2 Decisão de retorno

| Campo | Registro |
| --- | --- |
| Evidência | EVV-NNN |
| Recomendação | [Continuar, reabrir etapa, devolver ao diagnóstico ou suspender] |
| Autoridade | [Papel] |
| Decisão | DEC-NNN |
| Efeito sobre o ciclo | [Preencher] |

## 52. Riscos e restrições revelados

| Item | Tipo | Origem | Objeto afetado | Efeito | Controle/condição | Responsável | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSC/RES-NNN | [Risco ou restrição] | [EVV/APT] | [ID] | [Preencher] | [CTL/COND] | [Papel] | [DEC] |

### 52.1 Risco sem autoridade presente

| Risco | Autoridade necessária | Ação provisória | Limite | Sessão/decisão futura |
| --- | --- | --- | --- | --- |
| RSC-NNN | [Papel] | [Suspender, limitar, escalar ou outra] | [Preencher] | [Referência] |

## 53. Plano de tratamento

| Apontamento | Tratamento | Artefato afetado | Responsável | Prazo | Evidência de conclusão | Revalidação | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| APT-NNN | [Corrigir, redesenhar, decidir, aceitar, encaminhar ou rejeitar] | [Referência] | [Nome] | [Data] | [EVV/documento] | [Sim, não ou condição] | [Estado] |

### 53.1 Resultados possíveis

- corrigido;
- incorporado ao desenho;
- convertido em requisito;
- convertido em risco ou restrição;
- aceito com condição;
- encaminhado à implantação;
- encaminhado a especialista;
- adiado para evolução;
- rejeitado com justificativa;
- mantido como divergência;
- suspenso por ausência de informação.

### 53.2 Rejeição de apontamento

| Apontamento | Motivo | Evidência considerada | Autoridade | Divergência permanece? |
| --- | --- | --- | --- | --- |
| APT-NNN | [Preencher] | [EVVs] | [Papel] | [Sim ou não] |

## 54. Mudanças decorrentes da validação

| Mudança | Apontamento de origem | Objeto anterior | Nova versão | Artefatos afetados | Impacto | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| IMP-ARQ-NNN | APT-NNN | [ID/versão] | [Versão] | [Referências] | [Preencher] | DEC-NNN |

### 54.1 Verificação de propagação

- [ ] Arquitetura Integrada foi atualizada;
- [ ] Catálogo de Requisitos foi atualizado quando necessário;
- [ ] Matriz de Rastreabilidade foi sincronizada;
- [ ] riscos e controles foram atualizados;
- [ ] decisões foram registradas;
- [ ] diagramas e mapas correspondem à nova versão;
- [ ] critérios de aceite foram revistos;
- [ ] participantes afetados foram informados;
- [ ] necessidade de revalidação foi decidida.

### 54.2 Mudança sem incorporação

| Mudança proposta | Motivo da não incorporação | Risco | Autoridade | Condição de revisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Papel] | [Preencher] |

## 55. Revalidação

### 55.1 Gatilhos

Revalide quando houver mudança material em:

- requisito obrigatório;
- capacidade central;
- componente relevante;
- relação ou interface crítica;
- responsabilidade ou autoridade;
- fluxo ou exceção;
- dado sensível;
- tecnologia ou integração;
- modelo, configuração ou autonomia de IA;
- indicador decisório;
- risco aceito ou controle essencial;
- condição de continuidade;
- critério de aceite;
- fornecedor determinante;
- contexto que sustentava a conclusão.

### 55.2 Decisão de revalidação

| Mudança | Objetos afetados | Critérios afetados | Método necessário | Participantes | Escopo | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| IMP-ARQ-NNN | [IDs] | [CRTs] | [Preencher] | [Papéis] | [Integral ou parcial] | [Revalidar, dispensar ou suspender] |

### 55.3 Dispensa

| Mudança | Motivo da dispensa | Evidência | Autoridade | Risco residual |
| --- | --- | --- | --- | --- |
| [Preencher] | [Não material e sem alteração de critério] | [Referência] | [Papel] | [Preencher] |

### 55.4 Histórico de rodadas

| Rodada | Versão examinada | Motivo | Verificações repetidas | Resultado | Data |
| --- | --- | --- | --- | --- | --- |
| 1 | [Versão] | Validação inicial | [IDs] | [Preencher] | [Data] |
| 2 | [Versão] | [Mudança] | [IDs] | [Preencher] | [Data] |

## 56. Resultado por objeto e critério

| Objeto | Versão | Critérios conformes | Parciais | Não conformes | Inconclusivos | Condições | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [IDs] | [IDs] | [IDs] | [IDs] | [COND IDs] | [Preencher] |

### 56.1 Requisito obrigatório

| Requisito | Objeto validado | Critério | Evidência | Resultado | Efeito sobre aprovação |
| --- | --- | --- | --- | --- | --- |
| REQ-NNN | [IDs] | [CRT] | [EVVs] | [Preencher] | [Nenhum, condiciona ou impede] |

### 56.2 Cobertura do plano

| Indicador | Resultado |
| --- | --- |
| Verificações planejadas | [N] |
| Verificações executadas | [N] |
| Verificações conformes | [N] |
| Verificações parciais | [N] |
| Verificações não conformes | [N] |
| Verificações inconclusivas | [N] |
| Verificações não executadas | [N] |

## 57. Resultado consolidado da validação

Selecione um único resultado principal.

- [ ] **Validada** — critérios materiais foram atendidos e não há impedimento conhecido dentro do escopo.
- [ ] **Validada com ajustes** — ajustes foram incorporados e confirmados no mesmo ciclo.
- [ ] **Validada com condições** — pode avançar dentro de limites, responsáveis e prazos explícitos.
- [ ] **Validada com divergências** — pode avançar, mas posições relevantes permanecem registradas e autorizadas.
- [ ] **Devolvida ao desenho** — não conformidades exigem revisão arquitetural.
- [ ] **Devolvida ao diagnóstico** — a base de realidade é insuficiente ou materialmente contradita.
- [ ] **Limitada por ausência de informação** — conclusão parcial; não autoriza inferência além do alcance.
- [ ] **Encaminhada a especialista** — matéria requer competência externa antes da conclusão.
- [ ] **Suspensa** — risco, acesso, recurso ou autoridade impede continuidade.
- [ ] **Não validada** — o objeto não atende aos critérios necessários.
- [ ] **Cancelada** — ciclo encerrado sem resultado técnico.

### 57.1 Síntese

**Resultado:** [Selecionar]  
**Objetos abrangidos:** [IDs/versões]  
**Critérios determinantes:** [IDs]  
**Evidências principais:** [IDs]  
**Não conformidades materiais:** [IDs]  
**Divergências:** [IDs]  
**Condições:** [IDs]  
**Limitações:** [Preencher]  
**Recomendação:** [Preencher]

### 57.2 Alcance da conclusão

> Esta validação sustenta que **[objetos e versões]**, dentro de **[escopo, contexto e condições]**, foram confrontados por **[métodos e perspectivas]** contra **[critérios]**, resultando em **[resultado]**. A conclusão não abrange **[limites]** e deverá ser revista quando **[gatilhos]**.

## 58. Condições, limitações e incertezas remanescentes

### 58.1 Condições

| Condição | Objeto | Motivo | Responsável | Prazo | Evidência de cumprimento | Verificador |
| --- | --- | --- | --- | --- | --- | --- |
| COND-NNN | [ID] | [Preencher] | [Papel] | [Data] | [Preencher] | [Papel] |

### 58.2 Limitações

| Limitação | Origem | Efeito sobre conclusão | Uso permitido | Tratamento futuro |
| --- | --- | --- | --- | --- |
| [Amostra, tempo, acesso, método, dado, competência ou versão] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 58.3 Incertezas

| Incerteza | Por que permanece | Risco | Evidência futura | Gatilho de revisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 59. Pendências e aceitação de risco

| Item | Tipo | Objeto | Efeito | Autoridade | Decisão | Prazo | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [APT/DIV/RSC/COND] | [Pendência, risco ou condição] | [ID] | [Preencher] | [Papel] | [DEC] | [Data] | [Aberto/fechado] |

### 59.1 Aceitação de risco

| Risco | Evidências | Exposição residual | Motivo | Autoridade | Limite | Condição de revisão |
| --- | --- | --- | --- | --- | --- | --- |
| RSC-NNN | [EVVs] | [Preencher] | [Preencher] | [Papel] | [Tempo, volume ou escopo] | [Preencher] |

### 59.2 Proibição

Uma pendência não pode ser convertida em “condição” apenas para retirar um impedimento formal. O registro deve corresponder ao efeito real sobre segurança, viabilidade, coerência e rastreabilidade.

## 60. Sincronização com a Matriz de Rastreabilidade

### 60.1 Objetos a registrar

| Objeto | ID | Fonte oficial | Incluído na matriz? | Responsável |
| --- | --- | --- | --- | --- |
| Validação | VAL-ARQ-AAAA-NNN | Este registro | [Sim ou não] | [Nome] |
| Sessão material | SES-VAL-NNN | Este registro | [Sim ou não] | [Nome] |
| Teste | TST-NNN | Registro do teste | [Sim ou não] | [Nome] |
| Evidência material | EVV-NNN | Registro de evidências | [Sim ou não] | [Nome] |
| Apontamento material | APT-NNN | Este registro | [Sim ou não] | [Nome] |
| Decisão | DEC-NNN | Registro de Decisão | [Sim ou não] | [Nome] |

### 60.2 Vínculos mínimos

| Origem | Relação | Destino | Estado | Vínculo |
| --- | --- | --- | --- | --- |
| VAL/TST | `verifica` | [REQ/CAP/CMP/INT/ARQ] | [Proposto, confirmado ou invalidado] | VNC-NNN |
| VAL/TST | `é_contradito_por` | [EVV/APT quando aplicável] | [Estado] | VNC-NNN |
| APT | `gera` | [REQ/RSC/DEC/IMP] | [Estado] | VNC-NNN |
| VAL | `gera_aprendizado` | APD-NNN | [Estado] | VNC-NNN |

### 60.3 Sincronização

**Data:** [DD/MM/AAAA]  
**Matriz e versão:** [MTR/versão]  
**Vínculos criados ou alterados:** [IDs]  
**Responsável:** [Nome]  
**Divergências:** [Preencher]

## 61. Relação entre validação, decisão e aprovação

| Ato | Pergunta | Responsável | Registro | Resultado possível |
| --- | --- | --- | --- | --- |
| Validação | O objeto atende aos critérios dentro do escopo? | Responsável pela validação | Este documento | Resultado da seção 57 |
| Recomendação | O que deve acontecer diante do resultado? | Responsável pela arquitetura/validação | Síntese e recomendação | Aprovar, ajustar, devolver, suspender ou encaminhar |
| Aceitação de risco | A exposição residual será assumida dentro da alçada? | Autoridade competente | Registro de Decisão | Aceitar, reduzir, transferir, evitar ou adiar |
| Aprovação | A arquitetura está autorizada a avançar? | Aprovador | Registro de Decisão e linha de base | Aprovar, condicionar, devolver, suspender ou recusar |

### 61.1 Regra

Resultado técnico favorável não substitui aprovação. Aprovação organizacional não transforma resultado técnico desfavorável em conformidade.

## 62. Recomendação para o PC-4

### 62.1 Prontidão para aprovar

- [ ] objetos e versões estão identificados;
- [ ] requisitos obrigatórios foram confrontados;
- [ ] perspectivas necessárias participaram;
- [ ] métodos correspondem às perguntas;
- [ ] evidências principais estão preservadas;
- [ ] integração e cenários críticos foram examinados;
- [ ] impactos humanos foram confrontados;
- [ ] dados, tecnologia e IA receberam validação proporcional;
- [ ] não conformidades materiais foram tratadas;
- [ ] divergências permanecem visíveis;
- [ ] riscos possuem controle ou autoridade para aceitação;
- [ ] mudanças foram propagadas aos artefatos;
- [ ] revalidações necessárias foram concluídas;
- [ ] limitações e condições estão explícitas;
- [ ] linha de base candidata corresponde ao objeto validado.

### 62.2 Recomendação

- [ ] apta para aprovação;
- [ ] apta com condições;
- [ ] requer validação adicional;
- [ ] requer revisão da arquitetura;
- [ ] requer nova decisão;
- [ ] requer retorno ao diagnóstico;
- [ ] requer especialista;
- [ ] suspender;
- [ ] não recomendar aprovação.

**Justificativa:** [Preencher]  
**Condições:** [IDs]  
**Responsável:** [Nome]  
**Data:** [DD/MM/AAAA]

## 63. Prontidão para o PC-5

### 63.1 Passagem à implantação

- [ ] componentes aprovados possuem validação suficiente;
- [ ] testes que permanecem para implantação estão identificados;
- [ ] critérios de aceite são observáveis;
- [ ] riscos de transição foram confrontados;
- [ ] dependências e condições estão visíveis;
- [ ] responsáveis por testes futuros estão definidos;
- [ ] versões aprovadas podem ser reconstruídas;
- [ ] pendências não impedem o planejamento;
- [ ] restrições de acesso acompanham o pacote;
- [ ] Módulo 4 compreende os limites da validação.

### 63.2 Testes transferidos

| Teste | Objeto | Motivo da transferência | Pré-condição | Critério | Responsável futuro |
| --- | --- | --- | --- | --- | --- |
| TST-NNN | [ID] | [Preencher] | [Preencher] | [Preencher] | [Papel] |

### 63.3 Resultado

- [ ] validação apta para compor o pacote de implantação;
- [ ] apta com condições;
- [ ] requer complementação;
- [ ] impede a passagem.

**Justificativa:** [Preencher]

## 64. Participação da inteligência artificial na validação

Esta seção registra IA utilizada para planejar, conduzir, analisar ou documentar a validação. Não se confunde com a validação das funções de IA da arquitetura, tratada na seção 44.

### 64.1 Registro

| Atividade | Sistema/modelo | Entrada | Saída | Uso no ciclo | Revisão humana | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Planejamento, roteiro, síntese, classificação, comparação, simulação, transcrição ou revisão] | [Nome/versão] | [Categoria] | [Preencher] | [Preencher] | [Método] | [Nome] |

### 64.2 Usos permitidos

A IA pode apoiar:

- organização de perguntas;
- preparação de roteiros;
- identificação preliminar de inconsistências;
- geração de cenários candidatos;
- transcrição autorizada;
- agrupamento preliminar de apontamentos;
- comparação entre versões;
- verificação formal de rastreabilidade;
- redação e padronização do registro.

### 64.3 Limites

A IA não deve:

- confirmar sozinha a realidade organizacional;
- inferir consenso por frequência de termos;
- atribuir intenção a participantes;
- classificar fala sensível sem revisão;
- substituir especialista;
- aceitar risco;
- decidir tratamento;
- declarar resultado final;
- aprovar arquitetura.

### 64.4 Proteções

- [ ] participantes foram informados quando necessário;
- [ ] dados sensíveis foram minimizados;
- [ ] transcrição foi verificada;
- [ ] resumo preserva divergências;
- [ ] inferências estão sinalizadas;
- [ ] versão do sistema está registrada;
- [ ] saída utilizada possui responsável humano;
- [ ] decisão não foi atribuída à IA.

## 65. Sensibilidade, acesso e retenção

### 65.1 Classificação dos registros

| Registro | Classificação | Acesso | Autoridade | Retenção | Descarte |
| --- | --- | --- | --- | --- | --- |
| Plano de validação | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Lista de participantes | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Gravações | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Transcrições | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Evidências | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Apontamentos | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |
| Resultado consolidado | [Classificação] | [Papéis] | [Papel] | [Regra] | [Regra] |

### 65.2 Separação de conteúdo sensível

| Conteúdo | Motivo da separação | Referência protegida | Síntese permitida | Responsável |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [ID/local] | [Preencher] | [Nome] |

### 65.3 Correção factual por participante

| Solicitação | Pessoa | Registro | Correção | Efeito analítico | Data |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/referência] | [Trecho/EVV] | [Preencher] | [Nenhum, revisão ou revalidação] | [Data] |

## 66. Versionamento do registro

### 66.1 Controle de versões

| Versão | Data | Estado | Alteração | Motivo | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em preparação | Criação inicial | Abertura do ciclo | [Nome] | N/A |
| 1.0 | [DD/MM/AAAA] | Consolidada | Resultado final | Conclusão da validação | [Nome] | [Referência] |

### 66.2 Versões dos objetos

| Objeto | Versão inicial | Versão após ajustes | Rodada validada | Estado |
| --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Versão] | [N] | [Preencher] |

### 66.3 Integridade

- [ ] versão examinada permanece recuperável;
- [ ] mudanças durante o ciclo estão identificadas;
- [ ] evidências mantêm referência ao objeto correto;
- [ ] rodadas de revalidação não sobrescrevem resultados anteriores;
- [ ] resultado consolidado indica a versão que sustenta;
- [ ] linha de base candidata corresponde à versão validada.

## 67. Versão reduzida para validação focal

### 67.1 Identificação

| Campo | Registro |
| --- | --- |
| ID da validação | VAL-ARQ-AAAA-NNN |
| Objeto e versão | [Preencher] |
| Objetivo | [Preencher] |
| Responsável | [Nome] |
| Data | [Data] |
| Participantes | [Preencher] |
| Método | [Preencher] |

### 67.2 Verificações

| Pergunta | Critério | Evidência | Resultado | Apontamento |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [EVV] | [Conforme, parcial, não conforme ou inconclusivo] | [APT/N/A] |

### 67.3 Tratamento e resultado

**Ajustes:** [Preencher]  
**Divergências:** [Preencher]  
**Condições:** [Preencher]  
**Limitações:** [Preencher]  
**Resultado consolidado:** [Seção 57]  
**Recomendação:** [Preencher]  
**Revalidação necessária:** [Preencher]

### 67.4 Controles mínimos

- [ ] versão do objeto está identificada;
- [ ] pergunta e critério são explícitos;
- [ ] participantes são pertinentes;
- [ ] evidência está preservada;
- [ ] divergências estão visíveis;
- [ ] apontamentos possuem tratamento;
- [ ] resultado não excede o método;
- [ ] matriz foi sincronizada.

## 68. Estrutura ampliada para validação sistêmica

```text
validacao-VAL-ARQ-AAAA-NNN/
|-- README.md
|-- 01-plano-de-validacao.md
|-- 02-objetos-perguntas-e-criterios.md
|-- 03-participantes-e-governanca.md
|-- sessoes/
|   |-- SES-VAL-001.md
|   +-- SES-VAL-NNN.md
|-- evidencias/
|   |-- indice-de-evidencias.md
|   +-- registros-protegidos/
|-- verificacoes/
|   |-- indice-de-verificacoes.md
|   +-- testes-e-simulacoes/
|-- apontamentos/
|   |-- indice-de-apontamentos.md
|   |-- divergencias.md
|   +-- plano-de-tratamento.md
|-- revalidacao/
|   |-- analises-de-impacto.md
|   +-- historico-de-rodadas.md
|-- 04-resultado-consolidado.md
|-- 05-recomendacao-PC-4.md
+-- 06-condicoes-para-PC-5.md
```

### 68.1 Regras

- o README funciona como índice do ciclo;
- cada registro utiliza IDs estáveis;
- as versões examinadas são preservadas;
- evidências sensíveis podem permanecer separadas;
- sessões não substituem a consolidação;
- divergências não ficam escondidas em atas;
- verificações apontam para evidências;
- mudanças apontam para revalidação;
- o resultado declara escopo e limites;
- exportação e reconstrução permanecem possíveis.

## 69. Indicadores de qualidade da validação

### 69.1 Cobertura do plano

$$
\text{Cobertura do plano} = \frac{\text{verificações executadas}}{\text{verificações planejadas aplicáveis}} \times 100
$$

### 69.2 Cobertura de requisitos obrigatórios

$$
\text{Cobertura obrigatória} = \frac{\text{requisitos obrigatórios confrontados}}{\text{requisitos obrigatórios no escopo}} \times 100
$$

### 69.3 Fechamento de apontamentos materiais

$$
\text{Fechamento material} = \frac{\text{apontamentos materiais tratados}}{\text{apontamentos materiais identificados}} \times 100
$$

### 69.4 Registro

| Indicador | Resultado | Fonte | Limitação | Uso decisório |
| --- | --- | --- | --- | --- |
| Cobertura do plano | [%] | [Referência] | [Preencher] | [Preencher] |
| Cobertura obrigatória | [%] | [Referência] | [Preencher] | [Preencher] |
| Fechamento material | [%] | [Referência] | [Preencher] | [Preencher] |
| Verificações inconclusivas | [N/%] | [Referência] | [Preencher] | [Preencher] |
| Perspectivas ausentes | [N] | [Referência] | [Preencher] | [Preencher] |
| Rodadas de revalidação | [N] | [Referência] | [Preencher] | [Preencher] |

### 69.5 Limite dos indicadores

Percentuais não demonstram qualidade por si. Uma única não conformidade impeditiva pode superar alta cobertura quantitativa.

## 70. Retrospectiva e aprendizagem

### 70.1 Sobre o objeto

| Pergunta | Aprendizado | Evidência | Destino |
| --- | --- | --- | --- |
| Que fragilidade só apareceu na validação? | [Preencher] | [EVV/APT] | [Arquitetura/M4] |
| Que capacidade estava subestimada? | [Preencher] | [EVV/APT] | [Arquitetura] |
| Que exceção alterou o desenho? | [Preencher] | [EVV/APT] | [Arquitetura/M4] |
| Que risco permanece para a operação? | [Preencher] | [EVV/RSC] | [M5] |

### 70.2 Sobre o método

| Pergunta | Aprendizado | Mudança proposta | Responsável |
| --- | --- | --- | --- |
| Que método produziu evidência decisiva? | [Preencher] | [Preencher] | [Nome] |
| Que pergunta foi mal formulada? | [Preencher] | [Preencher] | [Nome] |
| Que perspectiva deveria ter entrado antes? | [Preencher] | [Preencher] | [Nome] |
| Onde houve retrabalho evitável? | [Preencher] | [Preencher] | [Nome] |
| Como a IA ajudou ou criou ruído? | [Preencher] | [Preencher] | [Nome] |
| O que deve mudar neste template? | [Preencher] | [Preencher] | [Nome] |

### 70.3 Registro de aprendizado

| ID | Aprendizado | Aplicação futura | Artefato/módulo | Responsável | Revisão |
| --- | --- | --- | --- | --- | --- |
| APD-NNN | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data/evento] |

## 71. Teste de reconstrução

Uma pessoa autorizada que não participou do ciclo deve conseguir responder:

1. que objeto e versão foram validados;
2. que decisões o ciclo apoiava;
3. quais perguntas e critérios foram utilizados;
4. por que os métodos foram escolhidos;
5. quem participou e que perspectivas faltaram;
6. que evidências sustentam cada resultado material;
7. que limitações afetam a conclusão;
8. que apontamentos foram identificados;
9. que divergências permaneceram;
10. que mudanças foram incorporadas;
11. o que foi revalidado;
12. que riscos e condições permanecem;
13. por que o resultado consolidado foi declarado;
14. que autoridade ainda precisa aprovar;
15. que testes foram transferidos ao Módulo 4;
16. que evento exigirá nova validação.

### 71.1 Registro

| Campo | Registro |
| --- | --- |
| Pessoa revisora | [Nome/papel] |
| Data | [DD/MM/AAAA] |
| Questões respondidas | [N/16] |
| Questões parciais | [IDs] |
| Questões não respondidas | [IDs] |
| Evidências inacessíveis | [Preencher] |
| Ambiguidades | [Preencher] |
| Ajustes realizados | [Preencher] |
| Resultado | [Aprovado, aprovado com ajustes ou reprovado] |

## 72. Critérios de conclusão e encerramento

### 72.1 Critérios de conclusão

- [ ] objeto e versão estão identificados;
- [ ] escopo, perguntas e critérios estão completos;
- [ ] participantes e perspectivas estão registrados;
- [ ] métodos e limitações estão explícitos;
- [ ] sessões possuem registros localizáveis;
- [ ] evidências materiais foram preservadas;
- [ ] verificações apontam para evidências;
- [ ] observação e interpretação estão separadas;
- [ ] apontamentos possuem classificação e tratamento;
- [ ] divergências permanecem visíveis;
- [ ] nova evidência recebeu análise de impacto;
- [ ] mudanças foram propagadas aos artefatos;
- [ ] revalidação necessária foi concluída;
- [ ] riscos e condições remanescentes possuem autoridade;
- [ ] resultado consolidado respeita o alcance do método;
- [ ] Matriz de Rastreabilidade foi sincronizada;
- [ ] recomendação ao PC-4 foi registrada;
- [ ] testes transferidos ao PC-5 estão definidos;
- [ ] participação da IA foi documentada;
- [ ] teste de reconstrução foi concluído.

### 72.2 Regra de encerramento

O ciclo pode ser encerrado quando as verificações planejadas aplicáveis foram executadas ou justificadamente retiradas, os apontamentos materiais receberam tratamento, as mudanças necessárias foram revalidadas e o resultado consolidado possui evidência, autoridade e limites explícitos.

Encerrar o registro não encerra a validade condicional de seus resultados. Mudança material, nova evidência, implantação ou operação podem exigir reabertura ou novo ciclo.

### 72.3 Resultado do encerramento

- [ ] ciclo concluído;
- [ ] concluído com condições;
- [ ] transferido à aprovação;
- [ ] transferido à implantação;
- [ ] reaberto;
- [ ] substituído;
- [ ] suspenso;
- [ ] cancelado.

---

## Registro final

**ID da validação:** VAL-ARQ-AAAA-NNN  
**Estado:** [Preencher]  
**Versão:** [Preencher]  
**Objeto e versão validados:** [Preencher]  
**Resultado consolidado:** [Preencher]  
**Condições:** [IDs ou nenhuma]  
**Limitações:** [Preencher]  
**Recomendação para o PC-4:** [Preencher]  
**Resultado para o PC-5:** [Preencher]  
**Responsável pela validação:** [Nome]  
**Data de encerramento:** [DD/MM/AAAA]  
**Próximo artefato:** `07-relatorio-de-arquitetura.md`  
**Observações:** [Preencher]
