# Plano de Arquitetura Organizacional

**Identificação técnica no repositório**

```yaml
id_plano: PLA-ARQ-AAAA-NNN
id_arquitetura: ARQ-AAAA-NNN
titulo: "[Nome claro e específico do projeto de arquitetura]"
organizacao:
area_ou_processo:
id_termo_de_abertura:
id_diagnostico: DIA-AAAA-NNN
id_transicao: TRA-AAAA-NNN
responsavel_pela_arquitetura:
patrocinador:
data_de_criacao: AAAA-MM-DD
data_de_aprovacao:
inicio_previsto:
conclusao_prevista:
estado: em_elaboracao
classificacao: "focal | funcional | sistemica"
nivel_sensibilidade: "publica | interna | confidencial | sensivel"
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Template operacional  
**Função:** Planejamento do desenho, integração, decisão, validação e consolidação da arquitetura  
**Documento de referência:** Protocolo de Arquitetura Organizacional  
**Documento de entrada:** Termo de Abertura da Arquitetura Organizacional  
**Ponto de controle imediato:** PC-2 — Prontidão para desenhar

**Documentos relacionados:**

- Termo de Abertura da Arquitetura Organizacional;
- Transição para Arquitetura Organizacional;
- Catálogo de Requisitos;
- Matriz de Rastreabilidade da Arquitetura;
- Protocolo de Decisão;
- ferramentas de arquitetura organizacional;
- registros de validação;
- registros de decisão;
- políticas de confidencialidade, segurança e uso de inteligência artificial aplicáveis.

---

## 1. Finalidade

O Plano de Arquitetura define como o projeto produzirá, integrará, comparará, decidirá, validará e documentará a configuração organizacional futura.

Ele transforma:

- uma abertura autorizada;
- um problema de arquitetura;
- uma decisão a apoiar;
- um escopo delimitado;
- requisitos iniciais;
- capacidades a preservar;
- riscos, restrições e dependências;

em um percurso governável composto por:

- frentes de arquitetura;
- perguntas de desenho;
- pacotes de trabalho;
- atividades;
- participantes;
- ferramentas;
- alternativas;
- interfaces;
- decisões;
- artefatos;
- marcos;
- validações;
- controles;
- critérios de qualidade e conclusão.

O plano deve permitir que qualquer pessoa autorizada compreenda:

1. o que será desenhado;
2. por que cada frente e atividade é necessária;
3. que requisitos e capacidades cada trabalho atenderá;
4. quem realizará, participará, validará e decidirá;
5. que entradas e acessos serão necessários;
6. que ferramentas serão utilizadas e para qual finalidade;
7. como alternativas materialmente distintas serão produzidas;
8. como os componentes serão integrados;
9. como impactos, riscos e compensações serão examinados;
10. quando ocorrerão marcos e pontos de controle;
11. que evidência demonstrará a conclusão de cada etapa;
12. como dados e inteligência artificial serão tratados;
13. em que condições o projeto poderá avançar, mudar, suspender ou encerrar;
14. como o trabalho preparará uma decisão e, posteriormente, a implantação.

## 2. Posição do plano no protocolo

Este plano é elaborado depois da aprovação do Termo de Abertura e antes do **PC-2 — Prontidão para desenhar**.

```text
Termo de Abertura aprovado
        ↓
Plano de Arquitetura
        ↓
Requisitos e critérios consolidados
        ↓
PC-2 — Prontidão para desenhar
        ↓
Capacidades e alternativas
        ↓
Desenho dimensional e integração
        ↓
Avaliação, decisão e consolidação
        ↓
Validação e aprovação
        ↓
Transição para implantação
```

O plano constitui a referência de condução do projeto. Ele pode evoluir quando novas informações surgirem, desde que mudanças materiais sejam avaliadas, decididas e versionadas.

### 2.1 O que este plano governa

- produção da arquitetura;
- consolidação dos requisitos;
- formulação das capacidades futuras;
- criação e comparação de alternativas;
- escolha das ferramentas de desenho;
- produção dos artefatos dimensionais;
- integração entre componentes;
- decisões arquiteturais;
- validação e aprovação;
- preparação do pacote para o Módulo 4.

### 2.2 O que este plano não substitui

Este documento não substitui:

- o Catálogo de Requisitos;
- a Matriz de Rastreabilidade;
- os mapas e modelos dimensionais;
- os registros de decisão;
- a Arquitetura Integrada;
- o Registro de Validação;
- o Relatório de Arquitetura;
- a Transição para Implantação;
- o plano detalhado de implantação do Módulo 4.

### 2.3 Limite entre arquitetura e implantação

O plano pode definir:

- condições de implantabilidade;
- dependências de transição;
- sequência recomendada de alto nível;
- experimentos arquiteturais;
- critérios de aceite futuro;
- necessidades de treinamento, migração e mudança;
- arquitetura mínima e ondas possíveis.

O plano ainda não deve definir, como compromisso executivo do Módulo 4:

- cronograma detalhado de implantação;
- alocação diária da equipe operacional;
- plano completo de treinamento;
- configuração definitiva de produção;
- aquisição ou contratação não autorizada;
- migração integral;
- entrada em operação;
- sustentação operacional continuada.

## 3. Instruções de uso

1. Duplique este arquivo para cada projeto real.
2. Não preencha diretamente o template-mestre.
3. Utilize a versão aprovada do Termo de Abertura como referência de entrada.
4. Remova seções condicionais somente na cópia do projeto e registre `não aplicável` no índice ou na síntese.
5. Não crie frente, atividade, reunião, ferramenta ou artefato sem finalidade arquitetural reconhecível.
6. Relacione cada pacote de trabalho a requisito, capacidade, pergunta, decisão ou risco.
7. Planeje em detalhe o ciclo próximo e mantenha os ciclos posteriores em nível proporcional à incerteza.
8. Atualize o plano quando uma descoberta alterar materialmente escopo, sequência, risco, participação ou decisão.
9. Preserve a linha de base aprovada e o histórico das mudanças.
10. Registre dependências externas com responsável e data ou condição.
11. Diferencie elaboração, validação, decisão e aprovação.
12. Não atribua responsabilidade, autoridade ou aprovação à inteligência artificial.
13. Submeta o plano e os requisitos consolidados ao PC-2 antes de iniciar desenho material de alternativas.

### 3.1 Convenções de preenchimento

| Convenção | Significado |
| --- | --- |
| `[Preencher]` | Registro necessário. |
| `Não aplicável` | O elemento foi examinado e não se aplica. |
| `Não determinado` | Ainda não existe informação suficiente. |
| `A confirmar` | Existe indicação inicial dependente de validação. |
| `Pendente` | Existe definição futura com responsável e limite. |
| `PLA-ARQ-AAAA-NNN` | Identificador do plano. |
| `FRT-ARQ-NNN` | Frente de arquitetura. |
| `PCT-ARQ-NNN` | Pacote de trabalho. |
| `ATV-ARQ-NNN` | Atividade. |
| `ENT-ARQ-NNN` | Entrega ou artefato. |
| `MAR-ARQ-NNN` | Marco. |
| `INT-ARQ-NNN` | Interface. |
| `VAL-ARQ-NNN` | Validação. |
| `DEC-AAAA-NNN` | Decisão formal. |

### 3.2 Duas escalas de planejamento

O plano deve operar em duas escalas.

**Plano integral**

Mantém visíveis:

- percurso completo;
- frentes;
- dependências;
- marcos;
- decisões;
- validações;
- entregas finais.

**Plano do ciclo próximo**

Detalha:

- atividades imediatas;
- responsáveis;
- duração ou esforço;
- entradas;
- saídas;
- bloqueios;
- critérios de conclusão.

Essa combinação evita tanto a ausência de direção quanto a falsa precisão.

### 3.3 Regra de proporcionalidade

**Arquitetura focal**

Pode utilizar a versão reduzida da seção 57, desde que preserve:

- problema e decisão;
- requisito e capacidade;
- atividades essenciais;
- responsáveis;
- alternativa ou justificativa para solução única;
- validação;
- rastreabilidade;
- riscos;
- aprovação.

**Arquitetura funcional**

Deve utilizar:

- frentes relacionadas;
- requisitos consolidados;
- ferramentas dimensionais pertinentes;
- matriz de dependências;
- alternativas;
- plano de integração;
- validação com pessoas afetadas;
- Matriz de Rastreabilidade.

**Arquitetura sistêmica**

Deve incluir:

- governança ampliada;
- planejamento por ciclos;
- responsáveis dimensionais;
- portfólio de decisões;
- integração em múltiplos níveis;
- validação progressiva;
- especialistas quando necessários;
- controle explícito de dados e IA;
- arquitetura mínima e roteiro de evolução;
- preparação ampliada para implantação.

## 4. Identificação do plano

| Campo | Registro |
| --- | --- |
| ID do plano | PLA-ARQ-AAAA-NNN |
| ID da arquitetura | ARQ-AAAA-NNN |
| Título | [Nome do projeto] |
| Organização | [Nome] |
| Unidade, área ou processo | [Quando aplicável] |
| Classificação | [Focal, funcional ou sistêmica] |
| Patrocinador | [Nome e função] |
| Responsável pela arquitetura | [Nome] |
| Responsável pelo planejamento | [Nome] |
| Custodiante dos registros | [Nome] |
| Data de criação | [DD/MM/AAAA] |
| Início previsto | [DD/MM/AAAA] |
| Conclusão prevista | [DD/MM/AAAA] |
| Data de aprovação | [DD/MM/AAAA] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Versão | [0.1] |
| Estado | [Selecionar na seção 5] |

### 4.1 Identificadores relacionados

| Objeto | Identificador | Versão | Estado | Referência |
| --- | --- | --- | --- | --- |
| Diagnóstico | DIA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Transição | TRA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Termo de Abertura | [ID] | [Versão] | Aprovado | [Link] |
| Registro do PC-1 | [ID] | [Versão] | [Resultado] | [Link] |
| Catálogo de Requisitos | [ID] | [Versão] | [Estado] | [Link] |
| Matriz de Rastreabilidade | [ID] | [Versão] | [Estado] | [Link] |
| Contrato ou proposta | [ID] | [Versão] | [Estado] | [Link] |

## 5. Estado do plano

Selecione um único estado vigente.

- [ ] **Em elaboração** — estrutura, frentes e atividades estão sendo definidas.
- [ ] **Em revisão** — o conteúdo está sendo verificado por responsáveis e participantes.
- [ ] **Aguardando aprovação** — o plano está completo e depende de autorização.
- [ ] **Aprovado** — o plano constitui referência vigente.
- [ ] **Aprovado com condições** — pode ser executado dentro dos limites registrados.
- [ ] **Em execução** — atividades planejadas estão em andamento.
- [ ] **Em atualização** — mudança material está sendo incorporada.
- [ ] **Suspenso** — a execução foi temporariamente interrompida.
- [ ] **Substituído** — outra versão ou outro plano constitui a referência vigente.
- [ ] **Encerrado** — o percurso planejado foi concluído ou formalmente encerrado.
- [ ] **Cancelado** — o plano não será executado.

**Data da última mudança:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Motivo ou referência:** [Preencher]

## 6. Documentos de entrada e linha de base

### 6.1 Entradas obrigatórias

| Documento | ID | Versão | Data | Elemento recebido | Fonte oficial? | Referência |
| --- | --- | --- | --- | --- | --- | --- |
| Termo de Abertura | [ID] | [Versão] | [Data] | Autorização, escopo e governança | Sim | [Link] |
| Transição para Arquitetura | TRA-AAAA-NNN | [Versão] | [Data] | Requisitos e contexto diagnóstico | [Sim/Não] | [Link] |
| Matriz de Evidências | [ID] | [Versão] | [Data] | Evidências e achados | [Sim/Não] | [Link] |
| Síntese diagnóstica | [ID] | [Versão] | [Data] | Compreensão validada | [Sim/Não] | [Link] |
| Registro do PC-1 | [ID] | [Versão] | [Data] | Condições do aceite | Sim | [Link] |
| Outros | [ID] | [Versão] | [Data] | [Preencher] | [Sim/Não] | [Link] |

### 6.2 Linha de base de entrada

**Versão do Termo de Abertura:** [Preencher]

**Versão da Transição:** [Preencher]

**Data de corte das informações:** [DD/MM/AAAA]

**Regra em caso de divergência:** [Indicar fonte que prevalece ou autoridade que decidirá.]

### 6.3 Alterações em relação ao Termo de Abertura

- [ ] O plano preserva integralmente a abertura aprovada.
- [ ] O plano detalha elementos sem alterar a abertura.
- [ ] O plano propõe mudança material registrada abaixo.

| Elemento | Termo aprovado | Plano proposto | Motivo | Impacto | Aprovação necessária | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [Escopo, prazo, entrega, dado, autoridade ou outro] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/função] | [ID/pendente] |

### 6.4 Documentos provisórios

| Documento | Elemento provisório | Uso permitido | Uso proibido | Condição de substituição |
| --- | --- | --- | --- | --- |
| [Nome] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 7. Condições herdadas da abertura

### 7.1 Resultado da abertura

- [ ] Aprovado para planejamento.
- [ ] Aprovado para planejamento com condições.

**Registro:** [ID ou referência]

### 7.2 Condições vinculantes

| ID | Condição | Origem | Responsável | Limite de resolução | Atividade relacionada | Etapa bloqueada | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CON-ARQ-001 | [Preencher] | [PC-1/Termo] | [Nome] | [Data/condição] | ATV-ARQ-___ | [PC-2 ou outra] | Aberta |

### 7.3 Autorizações recebidas

| Autorização | Escopo permitido | Limite | Autoridade | Evidência |
| --- | --- | --- | --- | --- |
| Acesso a pessoas | [Preencher] | [Preencher] | [Nome/função] | [Referência] |
| Acesso a dados | [Preencher] | [Preencher] | [Nome/função] | [Referência] |
| Uso de IA | [Preencher] | [Preencher] | [Nome/função] | [Referência] |
| Consulta a sistemas | [Preencher] | [Preencher] | [Nome/função] | [Referência] |

### 7.4 Proibições vigentes

- [Proibição 1]
- [Proibição 2]

## 8. Síntese do projeto

### 8.1 Situação de origem

[Síntese da condição atual necessária à compreensão do plano.]

### 8.2 Transformação necessária

> [Reproduzir a formulação aprovada.]

### 8.3 Problema de arquitetura

> A organização precisa desenvolver a capacidade de **[realizar algo]** para **[produzir resultado]**, preservando **[capacidade ou identidade]** e respeitando **[limites principais]**.

### 8.4 Decisão principal apoiada

> [Preencher]

**Autoridade:** [Nome e função]  
**Prazo ou condição:** [Preencher]  
**Registro previsto:** DEC-AAAA-NNN

### 8.5 Objetivo do projeto

> [Preencher]

### 8.6 Resultado projetual esperado

[Que arquitetura, decisão e pacote deverão existir ao final do Módulo 3?]

### 8.7 Resultado organizacional esperado

[Que capacidade deverá tornar-se possível depois da implantação e estabilização?]

### 8.8 Capacidade principal a preservar

[Preencher]

### 8.9 Requisito central

[Preencher]

### 8.10 Risco principal

[Preencher]

## 9. Objetivos do planejamento

### 9.1 Objetivo geral

Planejar como a arquitetura será produzida, integrada, comparada, decidida e validada de forma proporcional, rastreável e compatível com a capacidade real da organização.

### 9.2 Objetivos específicos

1. consolidar requisitos e critérios antes da geração de alternativas;
2. definir as capacidades futuras que orientarão o desenho;
3. organizar frentes e relações de dependência;
4. selecionar ferramentas por sua função arquitetural;
5. distribuir responsabilidades e autoridades;
6. definir atividades, marcos, artefatos e critérios de conclusão;
7. planejar alternativas materialmente distintas;
8. planejar integração e tratamento de interfaces;
9. organizar decisões e validações conforme risco e impacto;
10. proteger dados, pessoas e responsabilidades humanas;
11. preparar as condições que o Módulo 4 precisará detalhar;
12. tornar o projeto apto ao PC-2.

### 9.3 O que não constitui objetivo deste plano

- escolher antecipadamente a alternativa final;
- executar a implantação;
- produzir documentos sem uso definido;
- eliminar toda incerteza antes do trabalho;
- descrever atividades operacionais em detalhe superior ao necessário;
- substituir decisões humanas por pontuação automática;
- [Outro não objetivo].

## 10. Estratégia geral de arquitetura

### 10.1 Abordagem selecionada

- [ ] Sequencial — frentes dependem fortemente da conclusão anterior.
- [ ] Iterativa — desenhos serão aprofundados por ciclos sucessivos.
- [ ] Paralela coordenada — frentes trabalharão simultaneamente com marcos de integração.
- [ ] Experimental — hipóteses arquiteturais serão testadas antes da consolidação.
- [ ] Híbrida — combinação descrita abaixo.

**Descrição da abordagem:** [Preencher]

### 10.2 Por que a abordagem é adequada

[Relacione classificação, incerteza, dependências, maturidade, prazo e risco.]

### 10.3 Unidade primária de desenho

**Capacidade principal:** [ID e descrição]

**Capacidades relacionadas:** [IDs]

**Regra de decomposição:** [Quando uma capacidade será desdobrada em subcapacidades?]

### 10.4 Unidade de integração

**Relações que receberão atenção prioritária:** [Preencher]

### 10.5 Unidade de justificação

**Fonte oficial dos requisitos:** [Catálogo e versão]

### 10.6 Unidade de fechamento

**Decisões que encerrarão escolhas materiais:** [IDs previstos ou classes de decisão]

### 10.7 Ciclos previstos

| Ciclo | Finalidade | Pergunta principal | Saída verificável | Condição de entrada | Condição de saída |
| --- | --- | --- | --- | --- | --- |
| C1 | Preparar desenho | [Preencher] | PC-2 decidido | Abertura aprovada | Prontidão confirmada |
| C2 | Formular possibilidades | [Preencher] | Capacidades e alternativas | PC-2 | Alternativas comparáveis |
| C3 | Aprofundar e integrar | [Preencher] | Arquiteturas integradas | Alternativas selecionadas para análise | PC-3 |
| C4 | Consolidar e validar | [Preencher] | Linha de base candidata | Decisão de arquitetura | PC-4 |
| C5 | Preparar implantação | [Preencher] | Pacote de transição | Arquitetura aprovada | PC-5 |

### 10.8 Premissas do planejamento

| ID | Premissa | Base atual | Consequência se falsa | Como será verificada | Limite de validade | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| PRE-PLA-001 | [Preencher] | [Fonte ou razão] | [Impacto sobre plano ou desenho] | [Atividade, consulta ou decisão] | [Data/etapa] | [Nome] |

Premissas não devem permanecer invisíveis dentro de estimativas, cronogramas ou alternativas. Quando uma premissa for refutada, o impacto deve ser analisado antes da continuidade do item dependente.

### 10.9 Questões abertas de planejamento

| ID | Questão | Por que importa | Método de resposta | Responsável | Prazo | Etapa bloqueada | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| QUE-PLA-001 | [Preencher] | [Preencher] | [Investigação, consulta, experimento ou decisão] | [Nome] | [Data] | [Preencher ou nenhuma] | Aberta |

### 10.10 Incerteza e nível de compromisso

| Elemento | Grau de incerteza | Nível de compromisso possível | Condição para detalhar |
| --- | --- | --- | --- |
| Escopo | [Baixo/Médio/Alto] | [Firme/Condicionado/Exploratório] | [Preencher] |
| Requisitos | [Baixo/Médio/Alto] | [Firme/Condicionado/Exploratório] | [Preencher] |
| Alternativas | [Baixo/Médio/Alto] | [Firme/Condicionado/Exploratório] | [Preencher] |
| Cronograma | [Baixo/Médio/Alto] | [Firme/Condicionado/Exploratório] | [Preencher] |
| Recursos | [Baixo/Médio/Alto] | [Firme/Condicionado/Exploratório] | [Preencher] |

O plano não deve apresentar como compromisso aquilo que ainda constitui hipótese de trabalho.

## 11. Escopo operacional do plano

### 11.1 Capacidades incluídas

| ID | Capacidade | Tipo de trabalho | Profundidade | Entrega relacionada |
| --- | --- | --- | --- | --- |
| CAP-ARQ-001 | [Preencher] | [Preservar, desenvolver, fortalecer ou integrar] | [Preliminar, intermediária ou detalhada] | ENT-ARQ-___ |

### 11.2 Dimensões incluídas

| Dimensão | Estado | Pergunta de desenho | Nível de detalhe | Frente responsável |
| --- | --- | --- | --- | --- |
| Processos e fluxos | [Incluída/Condicional/Excluída] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Papéis e autoridades | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Informação e dados | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Conhecimento | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Comunicação | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Documentação | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Tecnologia e integrações | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Inteligência artificial | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Indicadores e controles | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |
| Transição e manutenção | [Estado] | [Preencher] | [Nível] | FRT-ARQ-___ |

### 11.3 Fronteira

| Elemento | Limite aprovado | Tratamento no plano |
| --- | --- | --- |
| Ponto de entrada | [Preencher] | [Atividade/modelo] |
| Ponto de saída | [Preencher] | [Atividade/modelo] |
| Pessoas ou grupos | [Preencher] | [Participação] |
| Áreas ou unidades | [Preencher] | [Frentes] |
| Sistemas | [Preencher] | [Interfaces] |
| Canais ou localidades | [Preencher] | [Tratamento] |
| Período de referência | [Preencher] | [Estado atual] |
| Horizonte futuro | [Preencher] | [Arquitetura mínima/evolução] |

### 11.4 Não objetivos e exclusões

| Elemento | Motivo da exclusão | Relação com o projeto | Risco | Encaminhamento |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Monitorar, investigar ou abrir outro projeto] |

### 11.5 Controle do nível de detalhe

O nível de detalhe será considerado suficiente quando permitir:

- comparar alternativas;
- reconhecer responsáveis e autoridades;
- compreender entradas, saídas e interfaces;
- avaliar viabilidade e impacto;
- validar atendimento aos requisitos;
- preparar implantação sem ambiguidade material;
- identificar manutenção e exceções críticas.

Não será aprofundado detalhe que:

- não altere decisão;
- não afete requisito;
- pertença exclusivamente à execução do Módulo 4;
- possa ser definido com segurança durante a implantação;
- gere custo de manutenção superior ao valor produzido.

## 12. Plano de consolidação dos requisitos

### 12.1 Objetivo

Transformar requisitos recebidos e surgidos na abertura em um catálogo claro, priorizado, rastreável e verificável.

### 12.2 Situação inicial

| Categoria | Quantidade ou estado | Fonte | Lacuna principal |
| --- | --- | --- | --- |
| Requisitos obrigatórios | [Preencher] | [Fonte] | [Preencher] |
| Requisitos negociáveis | [Preencher] | [Fonte] | [Preencher] |
| Requisitos desejáveis | [Preencher] | [Fonte] | [Preencher] |
| Requisitos em conflito | [Preencher] | [Fonte] | [Preencher] |
| Requisitos sem origem suficiente | [Preencher] | [Fonte] | [Preencher] |

### 12.3 Atividades de consolidação

| ID | Atividade | Entrada | Saída | Responsável | Participantes | Critério de conclusão |
| --- | --- | --- | --- | --- | --- | --- |
| ATV-REQ-001 | Revisar declarações | Requisitos iniciais | Requisitos atômicos | [Nome] | [Nomes/papéis] | Cada requisito expressa uma condição verificável |
| ATV-REQ-002 | Verificar origem | Matriz e transição | Vínculos confirmados | [Nome] | [Nomes/papéis] | Origem localizada ou exceção aprovada |
| ATV-REQ-003 | Classificar e priorizar | Catálogo revisado | Prioridades propostas | [Nome] | [Nomes/papéis] | Critério de prioridade aplicado |
| ATV-REQ-004 | Resolver conflitos | Pares conflitantes | Decisões ou compensações | [Nome] | [Decisor/especialista] | Conflitos decididos ou preservados |
| ATV-REQ-005 | Definir verificação | Requisitos aprovados | Critérios verificáveis | [Nome] | [Validador] | Forma de validação atribuída |

### 12.4 Perguntas de qualidade

- [ ] O requisito é necessário?
- [ ] Declara uma condição, não uma solução prematura?
- [ ] Possui origem localizável?
- [ ] Pode ser compreendido sem interpretação excessiva?
- [ ] Reúne apenas uma condição principal?
- [ ] Possui prioridade justificada?
- [ ] Pode ser verificado?
- [ ] É compatível com maturidade, limites e recursos?
- [ ] Conflita com outro requisito?
- [ ] Possui responsável pela validação?

### 12.5 Saída oficial

**Documento:** `catalogo-de-requisitos.md`  
**Responsável:** [Nome]  
**Versão necessária para o PC-2:** [Preencher]  
**Aprovador ou validador:** [Nome/função]

## 13. Plano de definição dos critérios de desenho

### 13.1 Fontes

- princípios do Módulo 1;
- identidade e propósito da organização;
- capacidades a preservar;
- requisitos;
- riscos e restrições;
- maturidade;
- exigências externas;
- condições de manutenção e implantação.

### 13.2 Registro dos critérios

| ID | Critério | Significado neste projeto | Origem | Prioridade | Forma de avaliação | Condição impeditiva | Compensação possível |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CRI-ARQ-001 | [Preencher] | [Preencher] | [Fonte] | [Obrigatório/Alta/Média/Baixa] | [Preencher] | [Preencher] | [Preencher] |

### 13.3 Atividades

| Atividade | Participantes | Produto | Validação |
| --- | --- | --- | --- |
| Interpretar critérios no contexto | [Preencher] | Definições locais | [Nome/papel] |
| Priorizar critérios | [Preencher] | Ordem ou pesos justificados | [Decisor] |
| Definir condições impeditivas | [Preencher] | Limites de exclusão | [Especialista/decisor] |
| Testar aplicação em exemplo | [Preencher] | Critérios calibrados | [Responsável] |

### 13.4 Proteção contra ajuste oportunista

Os critérios devem ser aprovados antes da escolha da alternativa. Mudança posterior precisa registrar:

- motivo;
- informação nova;
- alternativas afetadas;
- autoridade;
- efeito sobre avaliação anterior;
- necessidade de reavaliação.

## 14. Plano do estado atual de referência

### 14.1 Finalidade

Selecionar do diagnóstico o contexto necessário para comparar o funcionamento atual às alternativas futuras, sem repetir toda a investigação.

### 14.2 Elementos a representar

| Elemento | Fonte | Ferramenta | Nível de detalhe | Produto | Validador |
| --- | --- | --- | --- | --- | --- |
| Capacidades atuais | [Fonte] | [Mapa] | [Nível] | [Artefato] | [Nome/papel] |
| Processos e fluxos | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Papéis e autoridades | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Informação e conhecimento | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Comunicação e documentos | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Tecnologia e IA | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Indicadores e controles | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |
| Rupturas e exceções | [Fonte] | [Ferramenta] | [Nível] | [Artefato] | [Nome/papel] |

### 14.3 Critério de suficiência

O estado atual estará suficientemente delimitado quando permitir:

- identificar o que deve ser preservado;
- reconhecer o que precisa mudar;
- comparar impactos;
- localizar dependências e pontos de ruptura;
- compreender a transição necessária;
- evitar desenho baseado em suposição.

### 14.4 Questões que retornam ao diagnóstico

| ID | Questão ausente | Por que é diagnóstica | Impacto | Encaminhamento | Prazo |
| --- | --- | --- | --- | --- | --- |
| QDI-001 | [Preencher] | [Preencher] | [Preencher] | [Complementação/devolução] | [Data] |

## 15. Plano de formulação das capacidades futuras

### 15.1 Pergunta central

> O que a organização precisa conseguir realizar, com que consistência, em qual escala e dentro de quais limites?

### 15.2 Atividades

| ID | Atividade | Entrada | Participantes | Saída | Critério de conclusão |
| --- | --- | --- | --- | --- | --- |
| ATV-CAP-001 | Formular capacidades | Requisitos e problema | [Preencher] | Capacidades propostas | Declarações orientadas a resultado |
| ATV-CAP-002 | Relacionar capacidades | Capacidades propostas | [Preencher] | Mapa de dependências | Relações críticas explícitas |
| ATV-CAP-003 | Definir manifestação | Capacidades propostas | [Preencher] | Sinais observáveis | Cada capacidade pode ser reconhecida |
| ATV-CAP-004 | Priorizar horizontes | Mapa de capacidades | [Preencher] | Mínima e futuras | Entrada justificada por ciclo |
| ATV-CAP-005 | Validar | Catálogo de capacidades | [Preencher] | Capacidades validadas | Linguagem e necessidade confirmadas |

### 15.3 Registro planejado

| ID | Capacidade | Resultado | Requisitos | Dependências | Manifestação observável | Horizonte | Validador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CAP-FUT-001 | [Preencher] | [Preencher] | [IDs] | [IDs] | [Preencher] | [Mínima/Futuro] | [Nome/papel] |

### 15.4 Proteções

- capacidade não deve ser nome de ferramenta;
- capacidade não deve ser apenas atividade isolada;
- capacidade precisa produzir resultado reconhecível;
- capacidade futura deve preservar relações relevantes com capacidades atuais;
- escala e consistência devem ser compatíveis com o contexto;
- dependências não devem permanecer implícitas.

## 16. Frentes de arquitetura

### 16.1 Critério de criação

Uma frente somente deve existir quando reunir trabalho com:

- pergunta própria;
- requisitos relacionados;
- saída reconhecível;
- responsável;
- relação definida com outras frentes.

### 16.2 Registro principal

| ID | Frente | Objetivo | Pergunta de desenho | Requisitos | Capacidades | Responsável | Participantes | Saída | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FRT-ARQ-001 | [Preencher] | [Preencher] | [Preencher] | [IDs] | [IDs] | [Nome] | [Nomes/papéis] | ENT-ARQ-___ | Planejada |

### 16.3 Ficha de cada frente

**ID:** FRT-ARQ-___  
**Nome:** [Preencher]  
**Responsável:** [Nome]  
**Objetivo:** [Preencher]  
**Pergunta central:** [Preencher]  
**Requisitos relacionados:** [IDs]  
**Capacidades relacionadas:** [IDs]  
**Entradas:** [Preencher]  
**Atividades principais:** [IDs]  
**Ferramentas:** [Preencher]  
**Interfaces:** [IDs]  
**Decisões previstas:** [IDs]  
**Saídas:** [IDs]  
**Validação:** [Forma e responsável]  
**Riscos:** [IDs]  
**Condição de entrada:** [Preencher]  
**Condição de conclusão:** [Preencher]

### 16.4 Frentes sem responsável ou saída

| Frente | Lacuna | Tratamento | Limite de resolução |
| --- | --- | --- | --- |
| [Preencher] | [Responsável, saída ou validação ausente] | [Preencher] | [Data/condição] |

## 17. Dependências entre frentes

### 17.1 Mapa de dependências

| Frente de origem | Objeto fornecido | Frente de destino | Momento necessário | Responsável pela entrega | Critério de aceite | Risco de atraso |
| --- | --- | --- | --- | --- | --- | --- |
| FRT-ARQ-001 | [Requisito, mapa, decisão ou componente] | FRT-ARQ-002 | [Marco/data] | [Nome] | [Preencher] | [Preencher] |

### 17.2 Relações simultâneas

| Frentes | Relação recíproca | Ritual de integração | Frequência | Registro |
| --- | --- | --- | --- | --- |
| FRT-ARQ-___ / FRT-ARQ-___ | [Preencher] | [Revisão/oficina] | [Preencher] | [Artefato] |

### 17.3 Pontos únicos de falha no planejamento

| Elemento | Dependência única | Consequência | Redundância ou contingência |
| --- | --- | --- | --- |
| [Pessoa, dado, sistema ou decisão] | [Preencher] | [Preencher] | [Preencher] |

## 18. Pacotes de trabalho

Pacote de trabalho é um conjunto governável de atividades que produz uma saída verificável.

### 18.1 Registro principal

| ID | Pacote | Frente | Finalidade | Entradas | Saída | Responsável | Dependências | Esforço | Início | Fim | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| PCT-ARQ-001 | [Preencher] | FRT-ARQ-___ | [Preencher] | [IDs] | ENT-ARQ-___ | [Nome] | [IDs] | [Horas/dias/faixa] | [Data] | [Data] | Planejado |

### 18.2 Ficha do pacote

**ID:** PCT-ARQ-___  
**Finalidade:** [Preencher]  
**Justificativa:** [Requisito, capacidade, pergunta, risco ou decisão]  
**Entradas necessárias:** [Preencher]  
**Atividades incluídas:** [IDs]  
**Atividades excluídas:** [Preencher]  
**Responsável:** [Nome]  
**Participantes:** [Nomes/papéis]  
**Ferramentas:** [Preencher]  
**Saída:** [ID e descrição]  
**Definição de pronto:** [Condições observáveis]  
**Validador:** [Nome/papel]  
**Dependências:** [IDs]  
**Riscos:** [IDs]  
**Esforço previsto:** [Preencher]  
**Janela:** [Preencher]

### 18.3 Teste de necessidade

- [ ] O pacote atende requisito, capacidade, pergunta, decisão ou risco identificável.
- [ ] A saída será utilizada por outra atividade, validação ou decisão.
- [ ] O tamanho permite acompanhamento e responsabilização.
- [ ] A dependência de entrada está explícita.
- [ ] A definição de pronto pode ser verificada.
- [ ] Não duplica outro pacote.

## 19. Registro de atividades

| ID | Atividade | Pacote | Entrada | Método ou ferramenta | Responsável | Participantes | Saída | Duração/esforço | Dependência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ATV-ARQ-001 | [Verbo + objeto] | PCT-ARQ-___ | [Preencher] | [Preencher] | [Nome] | [Nomes/papéis] | [ID] | [Preencher] | [ID] | Backlog |

### 19.1 Estados das atividades

- **Backlog** — necessária, ainda não preparada.
- **Pronta** — entradas e responsável confirmados.
- **Em andamento** — trabalho iniciado.
- **Aguardando entrada** — dependência externa pendente.
- **Aguardando decisão** — escolha formal necessária.
- **Em revisão** — saída produzida e sob verificação.
- **Concluída** — definição de pronto atendida.
- **Bloqueada** — impedimento ativo.
- **Cancelada** — deixou de ser necessária por decisão registrada.

### 19.2 Definição de pronta para iniciar

- [ ] finalidade compreendida;
- [ ] entrada disponível;
- [ ] responsável confirmado;
- [ ] participantes disponíveis;
- [ ] acesso autorizado;
- [ ] ferramenta preparada;
- [ ] risco e sensibilidade conhecidos;
- [ ] saída e critério de conclusão definidos.

### 19.3 Definição de concluída

- [ ] saída produzida;
- [ ] fonte e versão identificadas;
- [ ] requisito ou capacidade vinculados;
- [ ] revisão realizada;
- [ ] divergências registradas;
- [ ] decisão necessária encaminhada;
- [ ] Matriz de Rastreabilidade atualizada;
- [ ] armazenamento e acesso adequados.

### 19.4 Limite de trabalho em andamento

**Número máximo de pacotes simultâneos:** [Preencher]

**Exceção permitida por:** [Nome/função]

**Regra para item bloqueado:** [Preencher]

## 20. Sequência dos movimentos arquiteturais

| Movimento | Finalidade | Atividades | Saída | Dependência | Marco ou controle |
| --- | --- | --- | --- | --- | --- |
| 1. Consolidar requisitos | Criar base governável | [IDs] | Catálogo aprovado | Abertura | PC-2 |
| 2. Definir critérios | Orientar alternativas | [IDs] | Critérios aprovados | Requisitos | PC-2 |
| 3. Delimitar estado atual | Preservar referência | [IDs] | Modelo atual | Diagnóstico | PC-2/Ciclo 2 |
| 4. Formular capacidades | Definir o que deve existir | [IDs] | Mapa de capacidades | Requisitos | [Marco] |
| 5. Gerar alternativas | Criar possibilidades distintas | [IDs] | Alternativas | Capacidades e critérios | [Marco] |
| 6. Aprofundar dimensões | Desenhar componentes | [IDs] | Mapas dimensionais | Alternativas | [Marco] |
| 7. Integrar | Examinar funcionamento conjunto | [IDs] | Arquiteturas integradas | Componentes | PC-3 |
| 8. Avaliar | Comparar atendimento e impactos | [IDs] | Avaliação | Alternativas integradas | PC-3 |
| 9. Decidir | Selecionar configuração | [IDs] | Registro de decisão | Avaliação | [Decisão] |
| 10. Consolidar mínima e evolução | Detalhar linha de base candidata | [IDs] | Arquitetura consolidada | Decisão | PC-4 |
| 11. Validar e aprovar | Verificar e autorizar | [IDs] | Linha de base aprovada | Consolidação | PC-4 |
| 12. Preparar implantação | Transferir condições | [IDs] | Pacote de transição | Aprovação | PC-5 |

### 20.1 Desvios da sequência

[Explique atividades paralelas, ciclos de retorno ou ordem diferente e por que não comprometem a integridade do método.]

## 21. Plano de geração de alternativas

### 21.1 Pergunta de geração

> Que configurações materialmente distintas podem produzir as capacidades necessárias e atender aos requisitos dentro dos limites reais da organização?

### 21.2 Espaços de variação

| Dimensão de escolha | Opção A | Opção B | Opção C | Limite aplicável |
| --- | --- | --- | --- | --- |
| Distribuição de responsabilidade | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Grau de padronização | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Centralização | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Uso de tecnologia | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Uso de IA | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Complexidade | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Ritmo de evolução | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 21.3 Alternativas mínimas a considerar

- [ ] não intervenção ou manutenção consciente do estado atual;
- [ ] configuração mínima;
- [ ] configuração intermediária;
- [ ] configuração ampliada;
- [ ] experimento limitado, quando pertinente;
- [ ] alternativa manual ou de baixa tecnologia;
- [ ] alternativa apoiada por tecnologia;
- [ ] alternativa apoiada por IA, quando autorizada.

Somente devem ser mantidas alternativas pertinentes ao problema e à decisão.

### 21.4 Plano das alternativas

| ID | Alternativa | Hipótese de funcionamento | Responsável | Atividades | Saída | Validação preliminar |
| --- | --- | --- | --- | --- | --- | --- |
| ALT-001 | [Preencher] | [Preencher] | [Nome] | [IDs] | [Artefato] | [Forma] |

### 21.5 Proteções contra predeterminação

- [ ] critérios serão definidos antes da escolha;
- [ ] solução preferida será tratada como alternativa;
- [ ] pessoas diferentes poderão propor configurações;
- [ ] alternativa simples não será descartada por aparência de menor sofisticação;
- [ ] novidade não será tratada automaticamente como valor;
- [ ] opções artificialmente diferentes serão consolidadas;
- [ ] exclusões possuirão justificativa;
- [ ] efeitos de não intervir serão examinados quando relevantes.

## 22. Plano de seleção das ferramentas

### 22.1 Regra

Cada ferramenta deve estar vinculada a:

- pergunta;
- requisito ou capacidade;
- frente;
- decisão;
- saída esperada;
- forma de validação.

### 22.2 Ferramentas selecionadas

| Ferramenta | Frente | Pergunta que ajudará a responder | Requisito/capacidade | Entrada | Produto | Responsável | Validação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Estado atual e estado futuro | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Arquitetura de processos e fluxos | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Papéis, responsabilidades e alçadas | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Informação e conhecimento | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Arquitetura da comunicação | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Arquitetura documental | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Tecnologia e integrações | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Inteligência artificial | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Indicadores e controles | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Avaliação de alternativas | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |
| Protótipo ou simulação | [ID] | [Preencher] | [IDs] | [Preencher] | [Artefato] | [Nome] | [Forma] |

### 22.3 Ferramentas consideradas e não utilizadas

| Ferramenta | Motivo da exclusão | Risco decorrente | Condição para reconsiderar |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] |

### 22.4 Teste de proporcionalidade

- [ ] Cada ferramenta responde a uma pergunta.
- [ ] O produto será usado em decisão, integração ou validação.
- [ ] Não existem ferramentas redundantes.
- [ ] O nível de detalhe é compatível com o risco.
- [ ] A carga de participação é sustentável.
- [ ] A ferramenta não impõe uma solução.
- [ ] Existe pessoa capaz de interpretar a saída.

## 23. Planos dimensionais

Esta seção define o foco de cada dimensão. Devem permanecer apenas os blocos pertinentes ao escopo.

### 23.1 Processos e fluxos

**Pergunta:** [Como o trabalho deverá acontecer de ponta a ponta?]

| Elemento | Planejamento |
| --- | --- |
| Processos incluídos | [IDs ou nomes] |
| Eventos de entrada e saída | [Preencher] |
| Fluxos a representar | [Trabalho, valor, informação, decisão, documento ou dados] |
| Exceções prioritárias | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-de-processos-e-fluxos.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.2 Papéis, responsabilidades e alçadas

**Pergunta:** [Quem deverá responder, executar, decidir, aprovar, verificar e manter?]

| Elemento | Planejamento |
| --- | --- |
| Papéis incluídos | [Preencher] |
| Decisões críticas | [IDs] |
| Conflitos de autoridade | [Preencher] |
| Substituições e exceções | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `papeis-responsabilidades-e-alcadas.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.3 Informação, dados e conhecimento

**Pergunta:** [Que informação e conhecimento deverão existir, circular, ser encontrados e permanecer protegidos?]

| Elemento | Planejamento |
| --- | --- |
| Objetos informacionais | [Preencher] |
| Conhecimentos críticos | [Preencher] |
| Fontes e destinos | [Preencher] |
| Qualidade e atualização | [Preencher] |
| Acesso e proteção | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-de-informacao-e-conhecimento.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.4 Comunicação e coordenação

**Pergunta:** [Que comunicação sustentará decisões, transferências, exceções e alinhamento?]

| Elemento | Planejamento |
| --- | --- |
| Situações comunicacionais | [Preencher] |
| Públicos e papéis | [Preencher] |
| Canais | [Preencher] |
| Ritmo ou gatilho | [Preencher] |
| Confirmação e escalonamento | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-da-comunicacao.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.5 Documentação e registros

**Pergunta:** [Que registros sustentarão execução, decisão, memória, prova e manutenção?]

| Elemento | Planejamento |
| --- | --- |
| Documentos necessários | [Preencher] |
| Finalidade de cada registro | [Preencher] |
| Autoria e aprovação | [Preencher] |
| Versionamento | [Preencher] |
| Retenção e descarte | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-documental.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.6 Tecnologia e integrações

**Pergunta:** [Que suporte tecnológico é necessário e como os sistemas deverão se relacionar?]

| Elemento | Planejamento |
| --- | --- |
| Capacidades tecnológicas | [Preencher] |
| Sistemas atuais | [Preencher] |
| Integrações | [Preencher] |
| Requisitos não funcionais | [Preencher] |
| Continuidade e reversibilidade | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-de-tecnologia-e-integracoes.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas, especialista e forma] |

### 23.7 Inteligência artificial

**Pergunta:** [Em que funções a IA pode ampliar capacidade, com quais limites e supervisão?]

| Elemento | Planejamento |
| --- | --- |
| Papéis instrumentais da IA | [Preencher] |
| Entradas permitidas | [Preencher] |
| Saídas esperadas | [Preencher] |
| Revisão humana | [Preencher] |
| Limites e proibições | [Preencher] |
| Falha e contingência | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-de-inteligencia-artificial.md` |
| Produto | [ID do artefato] |
| Responsável humano | [Nome] |
| Validação | [Pessoas, cenários e forma] |

### 23.8 Indicadores e controles

**Pergunta:** [Como o funcionamento será observado e que decisão cada sinal deverá apoiar?]

| Elemento | Planejamento |
| --- | --- |
| Resultados a observar | [Preencher] |
| Indicadores candidatos | [Preencher] |
| Decisões apoiadas | [IDs] |
| Limites e guardrails | [Preencher] |
| Fonte e frequência | [Preencher] |
| Requisitos relacionados | [IDs] |
| Ferramenta | `arquitetura-de-indicadores.md` |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Pessoas e forma] |

### 23.9 Transição, manutenção e evolução

**Pergunta:** [Que condições permitirão implantar, operar, manter e evoluir a arquitetura?]

| Elemento | Planejamento |
| --- | --- |
| Dependências de implantação | [Preencher] |
| Competências e treinamento | [Preencher] |
| Migração | [Preencher] |
| Responsáveis por manutenção | [Preencher] |
| Gatilhos de revisão | [Preencher] |
| Requisitos relacionados | [IDs] |
| Produto | [ID do artefato] |
| Responsável | [Nome] |
| Validação | [Responsável pela implantação/operação] |

## 24. Plano de componentes e interfaces

### 24.1 Componentes

Cada componente material deverá registrar:

- identificação;
- finalidade;
- capacidade relacionada;
- requisitos atendidos;
- descrição;
- responsável;
- entradas e saídas;
- relações;
- regras e exceções;
- riscos e controles;
- manutenção;
- critério de atendimento;
- condição de revisão.

### 24.2 Registro planejado de componentes

| ID | Componente | Tipo | Capacidade | Requisitos | Frente | Responsável | Artefato oficial | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CMP-ARQ-001 | [Preencher] | [Processo, papel, regra, documento, sistema, IA, indicador ou outro] | [ID] | [IDs] | [ID] | [Nome/papel] | [Referência] | Proposto |

### 24.3 Interfaces críticas

| ID | Origem | Destino | Objeto transferido | Formato | Momento | Entrega | Recebimento | Confirmação | Exceção | Risco |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| INT-ARQ-001 | [Componente/papel] | [Componente/papel] | [Informação, decisão, documento ou trabalho] | [Preencher] | [Gatilho] | [Responsável] | [Responsável] | [Forma] | [Tratamento] | [ID] |

### 24.4 Oficinas ou revisões de integração

| ID | Objetivo | Frentes | Entradas | Participantes | Saída | Momento |
| --- | --- | --- | --- | --- | --- | --- |
| OFI-INT-001 | [Preencher] | [IDs] | [Artefatos] | [Nomes/papéis] | [Decisões/ajustes] | [Data/marco] |

### 24.5 Testes de integração

- [ ] Todo processo possui papel responsável.
- [ ] Toda responsabilidade possui autoridade compatível.
- [ ] Toda atividade possui informação necessária.
- [ ] Todo documento possui autoria, uso e manutenção.
- [ ] Todo indicador apoia decisão ou controle.
- [ ] Toda automação possui tratamento de exceção.
- [ ] Toda função de IA possui supervisão humana adequada.
- [ ] Toda transferência crítica preserva contexto.
- [ ] Pontos únicos de falha foram tratados.
- [ ] Requisitos permanecem cobertos após integração.
- [ ] Duplicações e conflitos estão explícitos.
- [ ] A carga recorrente é sustentável.

## 25. Plano de avaliação das alternativas

### 25.1 Objetivo

Comparar configurações por critérios definidos antes da escolha, tornando visíveis atendimento, impactos, riscos e compensações.

### 25.2 Dimensões de avaliação

| Dimensão | Critério específico | Evidência necessária | Avaliador | Condição impeditiva |
| --- | --- | --- | --- | --- |
| Atendimento aos requisitos | [Preencher] | [Matriz] | [Nome/papel] | [Preencher] |
| Preservação de capacidades | [Preencher] | [Evidência] | [Nome/papel] | [Preencher] |
| Coerência e integração | [Preencher] | [Teste] | [Nome/papel] | [Preencher] |
| Viabilidade humana | [Preencher] | [Validação] | [Nome/papel] | [Preencher] |
| Segurança e privacidade | [Preencher] | [Parecer/teste] | [Nome/papel] | [Preencher] |
| Custo e esforço | [Preencher] | [Estimativa] | [Nome/papel] | [Preencher] |
| Manutenção | [Preencher] | [Análise] | [Nome/papel] | [Preencher] |
| Reversibilidade | [Preencher] | [Cenário] | [Nome/papel] | [Preencher] |
| Adequação à maturidade | [Preencher] | [Avaliação] | [Nome/papel] | [Preencher] |
| Evolução | [Preencher] | [Roteiro] | [Nome/papel] | [Preencher] |

### 25.3 Escala

- **Não atende** — condição ausente ou incompatível.
- **Atende parcialmente** — cobertura insuficiente ou dependente de ajuste material.
- **Atende** — condição contemplada de forma suficiente.
- **Atende com condição** — cobertura depende de condição explícita.
- **Não determinado** — evidência insuficiente.

### 25.4 Compensações

| ID | Alternativa | Benefício obtido | Custo ou perda criada | Pessoas afetadas | Reversibilidade | Decisão necessária |
| --- | --- | --- | --- | --- | --- | --- |
| COM-001 | ALT-___ | [Preencher] | [Preencher] | [Preencher] | [Alta/Média/Baixa] | DEC-___ |

### 25.5 Saída

**Ferramenta:** `avaliacao-de-alternativas.md`  
**Artefato:** [ID e referência]  
**Responsável:** [Nome]  
**Revisores:** [Nomes/papéis]  
**Marco:** PC-3 — Prontidão para decidir

## 26. Plano de decisões

### 26.1 Portfólio inicial

| ID provisório | Decisão | Por que é necessária | Alternativas | Critérios | Autoridade | Participantes | Dependência | Data/marco |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| DEC-P01 | [Preencher] | [Preencher] | [IDs/A definir] | [IDs] | [Nome/função] | [Nomes/papéis] | [ID] | [Data/marco] |

### 26.2 Sequência decisória

| Decisão anterior | Habilita | Consequência do atraso | Tratamento |
| --- | --- | --- | --- |
| DEC-___ | DEC-___ / pacote / frente | [Preencher] | [Preencher] |

### 26.3 Preparação de cada decisão

- [ ] objeto da decisão formulado;
- [ ] autoridade confirmada;
- [ ] alternativas admissíveis apresentadas;
- [ ] critérios definidos antes da escolha;
- [ ] requisitos atendidos e não atendidos visíveis;
- [ ] riscos e compensações registrados;
- [ ] pessoas afetadas consultadas;
- [ ] parecer especializado obtido quando necessário;
- [ ] reversibilidade e condição de revisão examinadas;
- [ ] registro formal preparado.

### 26.4 Resultados possíveis

- selecionar uma alternativa;
- combinar elementos de alternativas;
- autorizar experimento;
- solicitar novo desenho;
- aprofundar investigação;
- adiar;
- manter a condição atual;
- encerrar sem arquitetura.

### 26.5 Registro oficial

**Template:** `modulo-01-fundamentos/registros-de-decisao/registro-de-decisao.md`  
**Custodiante:** [Nome]  
**Local:** [Referência]

## 27. Plano da arquitetura mínima e da evolução

### 27.1 Pergunta

> Qual é o menor arranjo capaz de atender aos requisitos obrigatórios, produzir a capacidade necessária e manter risco aceitável?

### 27.2 Componentes mínimos a examinar

| Dimensão | Elemento essencial | Requisito | Condição para primeiro ciclo | Responsável futuro |
| --- | --- | --- | --- | --- |
| Capacidade | [Preencher] | [ID] | [Preencher] | [Papel] |
| Processo | [Preencher] | [ID] | [Preencher] | [Papel] |
| Papel e autoridade | [Preencher] | [ID] | [Preencher] | [Papel] |
| Informação | [Preencher] | [ID] | [Preencher] | [Papel] |
| Documento | [Preencher] | [ID] | [Preencher] | [Papel] |
| Tecnologia | [Preencher] | [ID] | [Preencher] | [Papel] |
| IA | [Preencher] | [ID] | [Preencher] | [Papel] |
| Indicador e controle | [Preencher] | [ID] | [Preencher] | [Papel] |

### 27.3 Evolução futura

| ID | Elemento futuro | Justificativa | Requisito | Dependência | Condição de entrada | Evidência de prontidão | Risco do adiamento | Horizonte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EVO-001 | [Preencher] | [Preencher] | [ID] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Período/condição] |

### 27.4 Verificação de superdimensionamento

- [ ] Cada componente do primeiro ciclo possui uso imediato.
- [ ] O volume atual justifica a solução.
- [ ] O custo recorrente é sustentável.
- [ ] A manutenção possui responsável e capacidade.
- [ ] Não existe alternativa temporária mais simples com risco aceitável.
- [ ] A arquitetura mínima continua compreensível.
- [ ] Elementos futuros possuem condição de entrada, não apenas desejo.

## 28. Protótipos, simulações e experimentos

### 28.1 Necessidade

- [ ] Não são necessários.
- [ ] Protótipo conceitual.
- [ ] Simulação de fluxo ou decisão.
- [ ] Teste técnico limitado.
- [ ] Experimento de uso com pessoas.
- [ ] Prova de conceito de IA.
- [ ] Outro: [Preencher].

### 28.2 Plano

| ID | Hipótese | Objeto | Escopo | Participantes | Dados | Critério de sucesso | Critério de interrupção | Responsável | Período |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EXP-001 | [Preencher] | [Preencher] | [Limite] | [Nomes/papéis] | [Categoria] | [Preencher] | [Preencher] | [Nome] | [Data] |

### 28.3 Limites

Um experimento arquitetural:

- não constitui implantação definitiva;
- não autoriza uso operacional além do escopo;
- deve possuir reversibilidade;
- deve proteger participantes e dados;
- deve registrar falhas e resultados contrários;
- deve indicar que decisão será apoiada;
- deve possuir responsável humano.

### 28.4 Aprendizado esperado

| Experimento | Questão respondida | Evidência esperada | Efeito possível sobre o desenho |
| --- | --- | --- | --- |
| EXP-___ | [Preencher] | [Preencher] | [Manter, alterar, rejeitar ou aprofundar] |

## 29. Plano de validação

### 29.1 Objetivo

Confrontar o desenho com requisitos, realidade operacional, pessoas afetadas, condições técnicas e limites aplicáveis antes da aprovação.

### 29.2 Camadas

| Camada | Objeto | Pergunta | Responsáveis | Método | Evidência | Momento |
| --- | --- | --- | --- | --- | --- | --- |
| Factual | Estado atual e premissas | Representa a realidade? | [Nomes/papéis] | [Revisão] | [Registro] | [Marco] |
| Requisitos | Cobertura | O desenho atende? | [Nomes/papéis] | [Matriz/teste] | [Registro] | [Marco] |
| Operacional | Fluxos, papéis e exceções | Pode funcionar? | [Pessoas afetadas] | [Cenário/simulação] | [Registro] | [Marco] |
| Técnica | Tecnologia, dados e IA | É seguro e viável? | [Especialista] | [Revisão/teste] | [Parecer] | [Marco] |
| Humana | Carga, autonomia e acessibilidade | É sustentável e responsável? | [Pessoas afetadas] | [Oficina/teste] | [Registro] | [Marco] |
| Integrada | Arquitetura completa | As partes funcionam juntas? | [Grupo] | [Teste de integração] | [Registro] | [Marco] |
| Implantabilidade | Transição | Pode ser transformada em plano? | [Responsável M4] | [Revisão] | [Aceite] | PC-5 |

### 29.3 Casos e cenários

| ID | Cenário | Condição normal ou exceção | Componentes envolvidos | Resultado esperado | Validador |
| --- | --- | --- | --- | --- | --- |
| CEN-001 | [Preencher] | [Normal/Exceção/Falha] | [IDs] | [Preencher] | [Nome/papel] |

### 29.4 Participantes

| Pessoa ou grupo | O que validará | Forma | Momento | Acessibilidade ou cuidado necessário |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Oficina, revisão, teste ou entrevista] | [Data/marco] | [Preencher] |

### 29.5 Tratamento das divergências

| ID | Divergência | Origem | Impacto | Exige decisão? | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| DIV-001 | [Preencher] | [Pessoa/grupo] | [Preencher] | [Sim/Não] | [Ajustar, preservar ou decidir] | Aberta |

### 29.6 Critérios de conclusão da validação

- [ ] requisitos obrigatórios foram confrontados;
- [ ] pessoas afetadas pertinentes participaram;
- [ ] cenários normais, exceções e falhas foram examinados;
- [ ] riscos altos e críticos receberam tratamento;
- [ ] limites técnicos e especializados foram verificados;
- [ ] divergências foram registradas;
- [ ] lacunas remanescentes possuem consequência explícita;
- [ ] arquitetura foi ajustada ou decisão de não ajustar foi registrada.

## 30. Plano de aprovação e linha de base

### 30.1 Objetos de aprovação

| Objeto | Versão esperada | Recomendador | Validador | Aprovador | Condição |
| --- | --- | --- | --- | --- | --- |
| Alternativa selecionada | [Versão] | [Nome] | [Nome/papel] | [Nome/função] | PC-3 concluído |
| Arquitetura consolidada | [Versão] | [Nome] | [Nome/papel] | [Nome/função] | PC-4 |
| Riscos aceitos | [Versão] | [Nome] | [Especialista] | [Autoridade] | Registro formal |
| Pacote de implantação | [Versão] | [Nome] | [Responsável M4] | [Nome/função] | PC-5 |

### 30.2 Linha de base

A linha de base deverá incluir:

- arquitetura integrada aprovada;
- catálogo de requisitos vigente;
- Matriz de Rastreabilidade vigente;
- registros de decisão;
- riscos e condições;
- registros de validação;
- arquitetura mínima e evolução;
- pacote de transição para implantação;
- índice de versões.

### 30.3 Condições de aprovação com ressalvas

| ID | Ressalva | Responsável | Prazo/gatilho | Impacto | Pode implantar antes? | Verificador |
| --- | --- | --- | --- | --- | --- | --- |
| RSL-001 | [Preencher] | [Nome] | [Data/condição] | [Preencher] | [Sim/Não/Parcialmente] | [Nome] |

### 30.4 Evidência

- [ ] assinatura;
- [ ] registro de decisão;
- [ ] ata;
- [ ] aprovação em sistema;
- [ ] mensagem identificada;
- [ ] outro: [Preencher].

## 31. Preparação da transição para implantação

### 31.1 Objetivo

Planejar a produção das condições que o Módulo 4 precisará transformar em cronograma, atividades executivas, treinamento, gestão da mudança e controle de implantação.

### 31.2 Conteúdo a preparar

| Elemento | Fonte na arquitetura | Responsável por consolidar | Validador do Módulo 4 | Marco |
| --- | --- | --- | --- | --- |
| Capacidades e componentes | [Artefatos] | [Nome] | [Nome/papel] | [Data] |
| Sequência recomendada | [Análise] | [Nome] | [Nome/papel] | [Data] |
| Dependências anteriores | [Matriz] | [Nome] | [Nome/papel] | [Data] |
| Critérios de aceite | [Requisitos] | [Nome] | [Nome/papel] | [Data] |
| Riscos de transição | [Registro] | [Nome] | [Nome/papel] | [Data] |
| Migração de dados | [Arquitetura] | [Nome] | [Nome/papel] | [Data] |
| Treinamento e competências | [Papéis] | [Nome] | [Nome/papel] | [Data] |
| Comunicação e mudança | [Arquitetura] | [Nome] | [Nome/papel] | [Data] |
| Testes e reversão | [Validação] | [Nome] | [Nome/papel] | [Data] |
| Manutenção e operação | [Arquitetura] | [Nome] | [Nome/papel] | [Data] |

### 31.3 Limite

O Plano de Arquitetura identifica **o que a implantação deverá preparar e respeitar**. O Módulo 4 decidirá **como, por quem e em que sequência executiva isso será realizado**.

## 32. Entregas e artefatos

### 32.1 Registro principal

| ID | Entrega | Finalidade | Frente/pacote | Requisitos | Responsável | Revisor | Aprovador/validador | Data | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ENT-ARQ-001 | [Preencher] | [Preencher] | [ID] | [IDs] | [Nome] | [Nome] | [Nome/papel] | [Data] | Planejada |

### 32.2 Artefatos obrigatórios

- [ ] Plano de Arquitetura aprovado.
- [ ] Catálogo de Requisitos.
- [ ] registro das capacidades futuras.
- [ ] alternativas de arquitetura.
- [ ] avaliação de alternativas.
- [ ] registros das decisões materiais.
- [ ] arquitetura selecionada e consolidada.
- [ ] Registro de Validação.
- [ ] linha de base aprovada.
- [ ] Transição para Implantação.
- [ ] retrospectiva.

### 32.3 Artefatos condicionais

- [ ] mapa do estado atual e futuro;
- [ ] arquitetura de processos e fluxos;
- [ ] matriz de papéis, responsabilidades e alçadas;
- [ ] arquitetura de informação e conhecimento;
- [ ] arquitetura da comunicação;
- [ ] arquitetura documental;
- [ ] arquitetura de tecnologia e integrações;
- [ ] arquitetura de inteligência artificial;
- [ ] arquitetura de indicadores e controles;
- [ ] protótipos ou simulações;
- [ ] pareceres especializados;
- [ ] Relatório de Arquitetura;
- [ ] roteiro de evolução.

### 32.4 Definição de pronto do artefato

Cada artefato deve:

- possuir ID, título, versão, estado e responsável;
- declarar finalidade e escopo;
- indicar fontes e vínculos;
- diferenciar proposta, recomendação, decisão e aprovação;
- registrar limitações e lacunas;
- possuir critério de validação;
- estar armazenado no local oficial;
- atualizar a Matriz de Rastreabilidade quando material.

### 32.5 Artefatos deliberadamente não produzidos

| Artefato possível | Motivo | Risco da ausência | Como a necessidade será atendida |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 33. Plano de rastreabilidade

### 33.1 Percurso mínimo

```text
Fonte e evidência
        ↓
Achado, capacidade, risco ou restrição
        ↓
Requisito
        ↓
Capacidade futura
        ↓
Alternativa
        ↓
Decisão
        ↓
Componente e interface
        ↓
Validação
        ↓
Item de implantação
        ↓
Indicador e aprendizado
```

### 33.2 Responsabilidades

| Ação | Responsável | Frequência/gatilho | Evidência |
| --- | --- | --- | --- |
| Criar identificadores | [Nome] | Ao criar objeto | Registro |
| Registrar vínculos | [Nome] | Ao concluir atividade | Matriz atualizada |
| Verificar órfãos | [Nome] | Antes de cada controle | Relatório de lacunas |
| Aprovar vínculo excepcional | [Nome/função] | Quando não houver origem diagnóstica | Decisão |
| Congelar versão | [Nome] | Na linha de base | Versão aprovada |

### 33.3 Verificações planejadas

- [ ] requisitos sem origem;
- [ ] capacidades sem requisito ou justificativa;
- [ ] componentes sem capacidade;
- [ ] alternativas sem critérios;
- [ ] decisões sem autoridade;
- [ ] requisitos sem atendimento;
- [ ] interfaces sem responsável;
- [ ] validações sem objeto;
- [ ] itens de implantação sem componente de origem;
- [ ] indicadores sem decisão associada.

### 33.4 Fonte oficial

**Documento:** `matriz-de-rastreabilidade.md`  
**Responsável:** [Nome]  
**Frequência de atualização:** [Preencher]  
**Marco de revisão completa:** [PC-2, PC-3, PC-4 e PC-5]

## 34. Governança do projeto

### 34.1 Papéis

| Papel | Pessoa | Responsabilidade | Autoridade | Substituto | Disponibilidade |
| --- | --- | --- | --- | --- | --- |
| Patrocinador | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável pela arquitetura | [Nome] | Integridade metodológica e integração | [Preencher] | [Nome] | [Condição] |
| Arquiteta ou analista | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável de frente | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável dimensional | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável pela validação | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Responsável pela implantação | [Nome/A definir] | Avaliar implantabilidade | [Preencher] | [Nome] | [Condição] |
| Especialista | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |
| Custodiante | [Nome] | Registros e versões | [Preencher] | [Nome] | [Condição] |
| Aprovador | [Nome] | [Preencher] | [Preencher] | [Nome] | [Condição] |

### 34.2 Instâncias

| Instância | Finalidade | Participantes | Frequência/gatilho | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- |
| Coordenação | Acompanhar trabalho e bloqueios | [Preencher] | [Preencher] | [Preencher] | [Registro] |
| Integração | Resolver interfaces | [Preencher] | [Preencher] | [Preencher] | [Registro] |
| Validação | Confrontar desenho | [Preencher] | [Preencher] | [Preencher] | [Registro] |
| Decisão | Escolher ou aceitar compensações | [Preencher] | [Gatilho] | [Preencher] | DEC-___ |

### 34.3 Escalonamento

| Situação | Primeiro responsável | Prazo de resposta | Instância seguinte | Consequência |
| --- | --- | --- | --- | --- |
| Bloqueio de acesso | [Nome] | [Prazo] | [Patrocinador] | [Preencher] |
| Conflito de requisito | [Nome] | [Prazo] | [Decisor] | [Preencher] |
| Risco alto ou crítico | [Nome] | [Prazo] | [Autoridade] | [Preencher] |
| Divergência entre frentes | [Nome] | [Prazo] | [Integração] | [Preencher] |
| Mudança de escopo | [Nome] | [Prazo] | [Aprovador] | [Preencher] |

## 35. Autoridade e responsabilidade

Use:

- **P** — propõe;
- **E** — elabora ou executa;
- **R** — recomenda;
- **V** — valida;
- **D** — decide;
- **A** — aprova;
- **C** — consultado;
- **I** — informado.

| Objeto | Patrocinador | Responsável pela arquitetura | Frente | Validador | Especialista | Responsável M4 | Aprovador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Aprovar plano | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Alterar escopo | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aprovar requisito | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Definir critério | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Excluir alternativa | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Selecionar arquitetura | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aceitar risco | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aprovar linha de base | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aceitar pacote de implantação | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Suspender projeto | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |

### 35.1 Verificação

- [ ] Cada decisão material possui uma autoridade final.
- [ ] Responsabilidade técnica e autoridade organizacional estão distintas.
- [ ] Aceitação de risco possui competência legítima.
- [ ] A pessoa que produz não é automaticamente a única que valida.
- [ ] A IA não ocupa nenhuma coluna de autoridade.
- [ ] Ausências e acúmulos de papéis foram avaliados.

## 36. Participação das pessoas

### 36.1 Mapa de participação

| Pessoa ou grupo | Relação com a arquitetura | Conhecimento ou impacto | Atividade | Forma de participação | Carga prevista | Momento | Risco de ausência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Executa, usa, recebe, mantém, decide ou é afetado] | [Preencher] | [ID] | [Entrevista, oficina, revisão, teste ou decisão] | [Horas] | [Data/marco] | [Preencher] |

### 36.2 Participação mínima por impacto

| Impacto | Participação mínima |
| --- | --- |
| Baixo e reversível | Revisão por representante informado. |
| Médio | Consulta e validação de cenário. |
| Alto | Participação direta no desenho e validação. |
| Alto e pouco reversível | Participação ampliada, decisão formal e revisão especializada. |

### 36.3 Pessoas sub-representadas

| Grupo | Barreira | Medida de inclusão | Responsável |
| --- | --- | --- | --- |
| [Preencher] | [Tempo, hierarquia, idioma, acesso, medo ou outra] | [Preencher] | [Nome] |

### 36.4 Carga de participação

| Grupo | Carga total prevista | Janela | Limite acordado | Ajuste necessário |
| --- | --- | --- | --- | --- |
| [Preencher] | [Horas/encontros] | [Período] | [Preencher] | [Preencher] |

## 37. Especialidades e revisões independentes

| Especialidade | Questão | Risco sem revisão | Profissional/fonte | Entrada necessária | Momento | Produto | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Jurídica, contábil, segurança, privacidade, acessibilidade, tecnologia ou outra] | [Preencher] | [Preencher] | [Nome/A contratar] | [Preencher] | [Marco] | [Parecer/validação] | [Estado] |

### 37.1 Limites de competência

[Registre o que o projeto não poderá concluir sem especialista.]

### 37.2 Independência necessária

[Indique objetos que não devem ser validados apenas por quem os produziu.]

### 37.3 Ausência de especialista

- [ ] suspender o objeto afetado;
- [ ] limitar a conclusão;
- [ ] utilizar referência oficial aplicável;
- [ ] excluir do escopo por decisão;
- [ ] aceitar risco por autoridade competente;
- [ ] outro: [Preencher].

## 38. Colaboração, oficinas e reuniões

### 38.1 Regra

Uma reunião somente deve ser planejada quando possuir:

- pergunta ou decisão;
- participantes necessários;
- entradas distribuídas;
- facilitação;
- tempo definido;
- saída esperada;
- responsável pelo registro.

### 38.2 Agenda de encontros

| ID | Encontro | Finalidade | Participantes | Pré-requisitos | Duração | Data | Facilitador | Saída |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ENC-001 | [Preencher] | [Preencher] | [Nomes/papéis] | [Artefatos] | [Tempo] | [Data] | [Nome] | [Registro/decisão] |

### 38.3 Trabalho assíncrono

| Atividade | Participantes | Canal | Prazo | Critério de resposta | Consolidador |
| --- | --- | --- | --- | --- | --- |
| [Revisão, proposta ou validação] | [Nomes/papéis] | [Canal] | [Data] | [Preencher] | [Nome] |

### 38.4 Ausência de manifestação

Ausência de resposta:

- não será interpretada automaticamente como concordância;
- será tratada conforme impacto e papel da pessoa;
- poderá bloquear validação quando a participação for obrigatória;
- deverá ser registrada quando alterar confiança ou abrangência.

## 39. Cronograma e marcos

### 39.1 Horizonte geral

**Início previsto:** [DD/MM/AAAA]  
**Conclusão prevista:** [DD/MM/AAAA]  
**Prazo da decisão principal:** [DD/MM/AAAA ou condição]  
**Margem para revisão:** [Preencher]

### 39.2 Cronograma por ciclo

| Ciclo | Início | Fim | Frentes | Pacotes | Entrega principal | Marco |
| --- | --- | --- | --- | --- | --- | --- |
| C1 | [Data] | [Data] | [IDs] | [IDs] | Plano, requisitos e critérios | PC-2 |
| C2 | [Data] | [Data] | [IDs] | [IDs] | Capacidades e alternativas | [Marco] |
| C3 | [Data] | [Data] | [IDs] | [IDs] | Integração e avaliação | PC-3 |
| C4 | [Data] | [Data] | [IDs] | [IDs] | Arquitetura validada | PC-4 |
| C5 | [Data] | [Data] | [IDs] | [IDs] | Pacote de implantação | PC-5 |

### 39.3 Marcos

| ID | Marco | Condição observável | Data | Dependências | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| MAR-ARQ-001 | PC-2 — Prontidão para desenhar | [Critérios da seção 53] | [Data] | [IDs] | [Nome/função] | Planejado |
| MAR-ARQ-002 | Alternativas comparáveis | [Preencher] | [Data] | [IDs] | [Nome/função] | Planejado |
| MAR-ARQ-003 | PC-3 — Prontidão para decidir | [Preencher] | [Data] | [IDs] | [Nome/função] | Planejado |
| MAR-ARQ-004 | PC-4 — Prontidão para aprovar | [Preencher] | [Data] | [IDs] | [Nome/função] | Planejado |
| MAR-ARQ-005 | PC-5 — Prontidão para implantar | [Preencher] | [Data] | [IDs] | [Nome/função] | Planejado |

### 39.4 Progresso

O progresso será medido por saídas aceitas e condições atendidas, não apenas por tempo consumido ou número de documentos.

| Frente/pacote | Saída esperada | Estado | Critério atendido | Bloqueio | Próxima ação |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Estado] | [Sim/Parcial/Não] | [Preencher] | [Ação, responsável e data] |

### 39.5 Indicadores de saúde do projeto

Esses indicadores observam a condução da arquitetura. Eles não substituem os indicadores da organização futura.

| Indicador | Definição | Fonte | Frequência | Limite ou sinal | Decisão apoiada | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Cobertura de requisitos | Requisitos com tratamento planejado sobre requisitos vigentes | Catálogo e matriz | [Frequência] | [Preencher] | Replanejar cobertura | [Nome] |
| Objetos órfãos | Componentes, atividades ou entregas sem justificação | Matriz | [Frequência] | [Preencher] | Corrigir ou retirar | [Nome] |
| Trabalho bloqueado | Pacotes bloqueados e tempo de bloqueio | Quadro de atividades | [Frequência] | [Preencher] | Escalonar dependência | [Nome] |
| Atraso decisório | Decisões vencidas ou próximas do limite | Portfólio de decisões | [Frequência] | [Preencher] | Escalonar autoridade | [Nome] |
| Participação crítica | Validações essenciais com participação confirmada | Plano de validação | [Frequência] | [Preencher] | Reagendar ou limitar conclusão | [Nome] |
| Retrabalho material | Saídas refeitas por falha de entrada, integração ou decisão | Histórico | [Frequência] | [Preencher] | Revisar método | [Nome] |
| Incidentes de dados ou IA | Ocorrências de uso inadequado, exposição ou falha | Registro de incidentes | Imediata | Qualquer ocorrência material | Suspender e tratar | [Nome] |

Indicadores não devem ser usados para pressionar volume documental ou ocultar trabalho de compreensão, integração e validação.

## 40. Dependências e caminho crítico

### 40.1 Dependências externas

| ID | Dependência | Fornecedor | Necessidade | Data/condição | Atividade afetada | Plano alternativo | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DEP-ARQ-001 | [Preencher] | [Pessoa, projeto ou sistema] | [Preencher] | [Data] | [ID] | [Preencher] | [Estado] |

### 40.2 Caminho crítico

| Sequência | Atividade ou marco | Motivo da criticidade | Margem | Responsável |
| --- | --- | --- | --- | --- |
| 1 | [ID] | [Preencher] | [Tempo] | [Nome] |

### 40.3 Gatilhos de replanejamento

- atraso em dependência crítica;
- indisponibilidade de decisor ou participante essencial;
- mudança da data de decisão;
- descoberta que amplie o escopo;
- requisito obrigatório novo;
- risco alto ou crítico;
- resultado de experimento contrário à hipótese;
- inviabilidade de alternativa principal;
- mudança regulatória ou contratual;
- indisponibilidade de ferramenta ou especialista.

### 40.4 Restrições do plano

| ID | Restrição | Tipo | Origem | Efeito sobre atividade ou alternativa | Pode ser negociada? | Autoridade | Tratamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RES-PLA-001 | [Preencher] | [Prazo, recurso, humana, técnica, jurídica, contratual ou outra] | [Fonte] | [Preencher] | [Sim/Não/Condição] | [Nome/função] | [Preencher] |

### 40.5 Dependências entre decisões e restrições

| Decisão | Restrição relacionada | O que precisa ser resolvido primeiro | Consequência |
| --- | --- | --- | --- |
| DEC-___ | RES-PLA-___ | [Preencher] | [Preencher] |

## 41. Recursos, carga e disponibilidade

### 41.1 Pessoas

| Pessoa/papel | Atividades | Esforço previsto | Janela | Capacidade confirmada | Conflito de agenda | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [IDs] | [Horas/dias] | [Período] | [Sim/Não] | [Preencher] | [Preencher] |

### 41.2 Recursos de trabalho

| Recurso | Finalidade | Responsável por fornecer | Disponibilidade | Data limite | Contingência |
| --- | --- | --- | --- | --- | --- |
| Documentos | [Preencher] | [Nome] | [Estado] | [Data] | [Preencher] |
| Dados | [Preencher] | [Nome] | [Estado] | [Data] | [Preencher] |
| Ambiente de modelagem | [Preencher] | [Nome] | [Estado] | [Data] | [Preencher] |
| Ambiente de teste | [Preencher] | [Nome] | [Estado] | [Data] | [Preencher] |
| Especialista | [Preencher] | [Nome] | [Estado] | [Data] | [Preencher] |

### 41.3 Reserva

**Reserva de tempo para revisão e retrabalho:** [Preencher]

**Reserva para risco:** [Preencher]

**Autoridade para utilizar a reserva:** [Nome/função]

## 42. Custos e aquisições da arquitetura

Esta seção trata do custo de produzir e validar o desenho. Custos de implantação serão detalhados no Módulo 4.

### 42.1 Estimativas

| Categoria | Base da estimativa | Faixa ou valor | Responsável | Aprovação | Observação |
| --- | --- | --- | --- | --- | --- |
| Trabalho do Estúdio | [Horas/escopo] | [Preencher] | [Nome] | [Nome] | [Preencher] |
| Participação do cliente | [Horas] | [Preencher] | [Nome] | [Nome] | [Preencher] |
| Especialistas | [Cotação/faixa] | [Preencher] | [Nome] | [Nome] | [Preencher] |
| Ferramentas temporárias | [Plano/licença] | [Preencher] | [Nome] | [Nome] | [Preencher] |
| Protótipos/testes | [Estimativa] | [Preencher] | [Nome] | [Nome] | [Preencher] |

### 42.2 Aquisições necessárias antes do PC-2

| Item | Justificativa | Custo | Autoridade | Prazo | Alternativa |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Valor/faixa] | [Nome/função] | [Data] | [Preencher] |

### 42.3 Custos futuros não autorizados

Estimativas de implantação podem apoiar a comparação de alternativas, mas não constituem autorização de compra, contratação ou execução.

## 43. Ferramentas e ambiente de trabalho

### 43.1 Ambiente oficial

| Finalidade | Ferramenta/repositório | Regra de uso | Responsável | Acesso |
| --- | --- | --- | --- | --- |
| Documentos oficiais | [Preencher] | [Preencher] | [Nome] | [Papéis] |
| Modelagem | [Preencher] | [Preencher] | [Nome] | [Papéis] |
| Coordenação | [Preencher] | [Preencher] | [Nome] | [Papéis] |
| Decisões | [Preencher] | [Preencher] | [Nome] | [Papéis] |
| Dados | [Preencher] | [Preencher] | [Nome] | [Papéis] |
| Protótipos | [Preencher] | [Preencher] | [Nome] | [Papéis] |

### 43.2 Fonte de verdade

**Repositório oficial:** [Preencher]

**Convenção de nomes:** [Referência]

**Responsável por versões:** [Nome]

### 43.3 Ferramentas auxiliares

| Ferramenta | Uso | Dados permitidos | Saída oficial? | Plano de contingência |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Categorias] | [Sim/Não] | [Preencher] |

## 44. Informação, dados e confidencialidade

### 44.1 Inventário de dados do projeto

| ID | Categoria | Finalidade | Fonte | Sensibilidade | Acesso | Armazenamento | Retenção | Descarte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| DAD-ARQ-001 | [Preencher] | [Preencher] | [Preencher] | [Nível] | [Papéis] | [Local] | [Regra] | [Forma] |

### 44.2 Minimização

| Atividade | Dado inicialmente imaginado | Dado mínimo suficiente | Redução aplicada |
| --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] |

### 44.3 Autorizações e restrições

- [ ] finalidade comunicada;
- [ ] acesso aprovado;
- [ ] categorias sensíveis identificadas;
- [ ] gravação autorizada quando aplicável;
- [ ] uso em IA autorizado separadamente;
- [ ] compartilhamento externo limitado;
- [ ] retenção e descarte definidos;
- [ ] resposta a incidente definida.

### 44.4 Incidente

**Canal:** [Preencher]  
**Responsável:** [Nome]  
**Ação imediata:** [Preencher]  
**Autoridade para suspender tratamento:** [Nome/função]

## 45. Participação da inteligência artificial na execução

### 45.1 Registro de usos

| ID | Atividade | Função da IA | Entrada permitida | Saída | Ferramenta | Revisor humano | Verificação | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| IA-ARQ-001 | [Pesquisa, classificação, síntese, modelagem, redação ou revisão] | [Preencher] | [Categoria] | [Preencher] | [Nome] | [Nome/papel] | [Método] | [Referência] |

### 45.2 Papéis instrumentais possíveis

- IA pesquisadora;
- IA analista;
- IA redatora;
- IA documental;
- IA gestora de registros;
- IA revisora;
- IA de apoio financeiro;
- IA de apoio à modelagem;
- IA de apoio à verificação de rastreabilidade.

Esses nomes descrevem funções operacionais, não pessoas, autoridades ou agentes responsáveis.

### 45.3 Usos proibidos

- aprovar requisitos, critérios, alternativas ou arquitetura;
- decidir em nome do Estúdio ou do cliente;
- aceitar risco;
- inventar fonte ou evidência;
- acessar dado incompatível com autorização;
- substituir validação por pessoa afetada;
- ocultar incerteza ou divergência;
- executar ação externa não autorizada;
- emitir conclusão especializada sem revisão competente.

### 45.4 Verificação humana

| Tipo de saída | Verificação mínima | Responsável | Evidência |
| --- | --- | --- | --- |
| Pesquisa | Fonte primária e pertinência | [Nome] | Referências |
| Síntese | Correspondência com o original | [Nome] | Revisão |
| Classificação | Amostra e critérios | [Nome] | Registro |
| Modelo | Requisitos e interfaces | [Nome] | Validação |
| Texto | Exatidão, clareza e autoria | [Nome] | Aprovação |
| Cálculo | Fórmula, entrada e reprodução | [Nome] | Memória de cálculo |

### 45.5 Contingência sem IA

[Como a atividade será realizada ou limitada se a ferramenta não puder ser utilizada?]

## 46. Plano de qualidade

### 46.1 Critérios gerais

- necessidade;
- clareza;
- coerência;
- rastreabilidade;
- integração;
- proporcionalidade;
- verificabilidade;
- implantabilidade;
- manutenibilidade;
- responsabilidade humana;
- segurança;
- capacidade de evolução.

### 46.2 Revisões

| Revisão | Objeto | Revisor | Momento | Critérios | Registro |
| --- | --- | --- | --- | --- | --- |
| Autorrevisão | [Artefato] | [Autor] | Antes de compartilhar | [Preencher] | [Registro] |
| Revisão por par | [Artefato] | [Nome] | [Marco] | [Preencher] | [Registro] |
| Revisão dimensional | [Artefato] | [Especialista] | [Marco] | [Preencher] | [Registro] |
| Revisão integrada | Arquitetura | [Grupo] | Antes do PC-3/PC-4 | [Preencher] | [Registro] |
| Revisão executiva | Pacote | [Aprovador] | [Marco] | [Preencher] | [Registro] |

### 46.3 Amostragem e profundidade

[Defina quando revisão total é obrigatória e quando amostragem é proporcional.]

### 46.4 Não conformidades

| ID | Objeto | Critério não atendido | Gravidade | Responsável pela correção | Prazo | Revalidação |
| --- | --- | --- | --- | --- | --- | --- |
| NCF-001 | [Preencher] | [Preencher] | [Baixa/Média/Alta/Crítica] | [Nome] | [Data] | [Nome/forma] |

### 46.5 Condições impeditivas

- requisito obrigatório sem tratamento;
- decisão material sem autoridade;
- risco crítico sem resposta;
- componente sem responsável;
- interface crítica sem tratamento;
- uso de dados ou IA fora da autorização;
- validação essencial não realizada;
- divergência material ocultada;
- arquitetura incompatível com a capacidade de manutenção.

## 47. Riscos do projeto de arquitetura

### 47.1 Registro

| ID | Evento | Causa | Consequência | Probabilidade | Impacto | Exposição | Resposta | Responsável | Gatilho | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RSK-ARQ-001 | [Preencher] | [Preencher] | [Preencher] | [Baixa/Média/Alta] | [Baixo/Médio/Alto/Crítico] | [Classificação] | [Evitar, reduzir, transferir, aceitar ou investigar] | [Nome] | [Sinal] | Aberto |

### 47.2 Categorias a examinar

- escopo e prazo;
- disponibilidade;
- qualidade das entradas;
- decisão e autoridade;
- integração;
- impacto humano;
- segurança e privacidade;
- tecnologia;
- IA;
- dependência de fornecedor;
- manutenção;
- implantação futura;
- viés e predeterminação;
- mudança de contexto.

### 47.3 Reserva e resposta

| Risco | Ação preventiva | Ação se ocorrer | Recurso reservado | Autoridade |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Tempo/orçamento/pessoa] | [Nome/função] |

### 47.4 Aceitação

Risco somente será considerado aceito quando houver:

- descrição e consequência;
- alternativas de tratamento consideradas;
- autoridade competente;
- data e evidência;
- limite da aceitação;
- condição de revisão.

## 48. Questões, impedimentos e pendências

### 48.1 Registro

| ID | Tipo | Descrição | Impacto | Responsável | Próxima ação | Prazo | Escalonamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| IMP-001 | [Questão, impedimento ou pendência] | [Preencher] | [Preencher] | [Nome] | [Ação concreta] | [Data] | [Instância] | Aberto |

### 48.2 Prioridade

- **Imediata** — bloqueia atividade crítica ou controle.
- **Alta** — ameaça marco, requisito obrigatório ou decisão.
- **Média** — reduz qualidade ou aumenta esforço.
- **Baixa** — pode ser tratada no ciclo adequado sem dano material.

### 48.3 Regra de envelhecimento

| Prioridade | Prazo sem atualização | Ação automática |
| --- | --- | --- |
| Imediata | [Período] | Escalonar ao patrocinador ou responsável |
| Alta | [Período] | Revisar caminho crítico |
| Média | [Período] | Incluir na revisão do ciclo |
| Baixa | [Período] | Reavaliar necessidade |

## 49. Controle de mudanças

### 49.1 Mudanças materiais

Exigem análise e decisão:

- transformação ou problema;
- decisão apoiada;
- escopo ou não objetivos;
- requisito obrigatório;
- critério impeditivo;
- autoridade ou governança;
- prazo da decisão;
- frente ou entrega principal;
- uso de dado sensível;
- participação de IA;
- risco alto ou crítico;
- linha de base ou arquitetura mínima.

### 49.2 Fluxo

```text
Solicitação
    ↓
Registro e classificação
    ↓
Análise de impacto
    ↓
Recomendação técnica
    ↓
Decisão da autoridade
    ↓
Plano, artefatos e matriz atualizados
    ↓
Comunicação e nova linha de base
```

### 49.3 Registro

| ID | Mudança | Origem | Motivo | Impacto em escopo, prazo, custo, risco e qualidade | Recomendação | Decisão | Versão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MUD-ARQ-001 | [Preencher] | [Pessoa/fato] | [Preencher] | [Preencher] | [Preencher] | [ID/estado] | [Versão] |

### 49.4 Mudanças não materiais

Correções editoriais, detalhamento sem alteração de compromisso e atualização de estado podem ser aprovados por [Nome/papel], desde que não alterem significado, autoridade, requisito, risco ou linha de base.

## 50. Comunicação do projeto

### 50.1 Plano

| Público | Necessidade | Conteúdo | Canal | Frequência/gatilho | Responsável | Registro | Sensibilidade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Patrocinador | [Preencher] | [Decisão, risco, avanço] | [Canal] | [Preencher] | [Nome] | [Forma] | [Nível] |
| Participantes | [Preencher] | [Preencher] | [Canal] | [Preencher] | [Nome] | [Forma] | [Nível] |
| Pessoas afetadas | [Preencher] | [Preencher] | [Canal] | [Preencher] | [Nome] | [Forma] | [Nível] |
| Especialistas | [Preencher] | [Preencher] | [Canal] | [Preencher] | [Nome] | [Forma] | [Nível] |
| Implantação | [Preencher] | [Preencher] | [Canal] | [Preencher] | [Nome] | [Forma] | [Nível] |

### 50.2 Eventos obrigatórios de comunicação

- aprovação ou mudança do plano;
- bloqueio do caminho crítico;
- risco alto ou crítico;
- mudança de escopo;
- decisão material;
- resultado de validação com ressalva;
- suspensão ou retomada;
- aprovação da linha de base;
- aceite da transição para implantação.

### 50.3 Linguagem

A comunicação deve distinguir:

- fato;
- interpretação;
- hipótese;
- alternativa;
- recomendação;
- decisão;
- condição;
- risco;
- aprovação.

## 51. Documentação, versões e custódia

### 51.1 Estrutura do registro

```text
registros-de-arquitetura/
+-- AAAA/
    +-- ARQ-AAAA-NNN-nome/
        |-- README.md
        |-- termo-de-abertura.md
        |-- plano-de-arquitetura.md
        |-- entrada/
        |-- requisitos/
        |-- alternativas/
        |-- arquitetura/
        |-- validacoes/
        |-- decisoes/
        |-- transicao-para-implantacao/
        +-- retrospectiva.md
```

### 51.2 Regras

- identificadores permanecem estáveis;
- versões aprovadas não são sobrescritas sem histórico;
- arquivos provisórios possuem estado identificável;
- documentos substituídos permanecem localizáveis;
- acesso acompanha sensibilidade;
- decisões e validações possuem evidência;
- links da Matriz de Rastreabilidade apontam para fontes oficiais;
- descarte segue regra aplicável.

### 51.3 Responsabilidades

| Registro | Responsável por criar | Responsável por manter | Frequência | Local oficial |
| --- | --- | --- | --- | --- |
| Plano | [Nome] | [Nome] | A cada mudança | [Referência] |
| Catálogo | [Nome] | [Nome] | Contínua | [Referência] |
| Matriz | [Nome] | [Nome] | Por pacote/marco | [Referência] |
| Decisões | [Nome] | [Nome] | Por decisão | [Referência] |
| Validações | [Nome] | [Nome] | Por evento | [Referência] |
| Índice | [Nome] | [Nome] | Por versão | [Referência] |

## 52. Pontos de controle

### 52.1 Registro geral

| Controle | Pergunta | Evidências previstas | Responsável por preparar | Autoridade | Data |
| --- | --- | --- | --- | --- | --- |
| PC-2 — Prontidão para desenhar | Existe base clara e governável para produzir alternativas? | Plano, requisitos, critérios, escopo e riscos | [Nome] | [Nome/função] | [Data] |
| PC-3 — Prontidão para decidir | Existem alternativas comparáveis e impactos conhecidos? | Alternativas integradas e avaliação | [Nome] | [Nome/função] | [Data] |
| PC-4 — Prontidão para aprovar | A configuração escolhida foi consolidada, rastreada e validada? | Linha de base candidata | [Nome] | [Nome/função] | [Data] |
| PC-5 — Prontidão para implantar | O Módulo 4 recebeu condições suficientes? | Pacote de transição | [Nome] | [Nome/função] | [Data] |

### 52.2 Regra

Nenhum controle será aprovado apenas porque os documentos existem. O conteúdo precisa demonstrar as condições verificadas.

### 52.3 Resultados possíveis

- aprovado;
- aprovado com condições;
- devolvido para ajuste;
- devolvido a etapa anterior;
- suspenso;
- cancelado.

### 52.4 Condições de retorno

| Controle | Condição de retorno | Etapa ou artefato | Responsável |
| --- | --- | --- | --- |
| PC-2 | [Preencher] | [Plano/requisito/diagnóstico] | [Nome] |
| PC-3 | [Preencher] | [Alternativas/integração] | [Nome] |
| PC-4 | [Preencher] | [Consolidação/validação] | [Nome] |
| PC-5 | [Preencher] | [Pacote/arquitetura] | [Nome] |

## 53. PC-2 — Prontidão para desenhar

### 53.1 Condições obrigatórias

- [ ] o Termo de Abertura está aprovado;
- [ ] o resultado do PC-1 e suas condições foram incorporados;
- [ ] o problema de arquitetura está claro e não impõe solução;
- [ ] a decisão apoiada e sua autoridade estão identificadas;
- [ ] escopo, fronteiras e não objetivos estão definidos;
- [ ] requisitos estão consolidados no grau necessário;
- [ ] requisitos obrigatórios possuem origem e verificação;
- [ ] conflitos de requisito possuem tratamento;
- [ ] princípios e critérios de desenho estão definidos;
- [ ] capacidades a preservar estão explícitas;
- [ ] a estratégia de formulação das capacidades futuras está definida;
- [ ] frentes, perguntas e saídas estão definidas;
- [ ] responsáveis e participantes estão confirmados;
- [ ] dependências e interfaces de trabalho estão visíveis;
- [ ] ferramentas possuem finalidade reconhecível;
- [ ] estratégia de alternativas está definida;
- [ ] estratégia de integração está definida;
- [ ] decisões e autoridades estão planejadas;
- [ ] validações estão planejadas conforme impacto;
- [ ] marcos e controles estão definidos;
- [ ] riscos, restrições e lacunas estão tratados;
- [ ] dados e acessos possuem tratamento;
- [ ] usos de IA estão limitados e supervisionados;
- [ ] prazo e recursos são compatíveis com o trabalho;
- [ ] critérios de qualidade e conclusão estão claros;
- [ ] o plano possui aprovação ou condição explícita.

### 53.2 Verificações de coerência

- [ ] cada frente possui pergunta, responsável e saída;
- [ ] cada pacote possui justificativa e definição de pronto;
- [ ] cada ferramenta atende pergunta ou decisão;
- [ ] cada entrega será utilizada;
- [ ] o cronograma respeita dependências;
- [ ] a participação é compatível com impacto;
- [ ] o nível de detalhe é proporcional;
- [ ] o plano não antecipa a escolha da arquitetura;
- [ ] o plano não confunde desenho com implantação;
- [ ] pendências condicionais possuem limite de resolução.

### 53.3 Pendências remanescentes

| ID | Pendência | Por que não impede o desenho | Responsável | Prazo/gatilho | Etapa bloqueada se não resolvida |
| --- | --- | --- | --- | --- | --- |
| PEN-PC2-001 | [Preencher] | [Preencher] | [Nome] | [Data/condição] | [Preencher] |

### 53.4 Resultado do PC-2

- [ ] **Pronto para desenhar.**
- [ ] **Pronto para desenhar com condições.**
- [ ] **Devolvido para ajuste do plano.**
- [ ] **Devolvido para consolidação de requisitos.**
- [ ] **Devolvido à abertura.**
- [ ] **Devolvido ao diagnóstico.**
- [ ] **Suspenso.**
- [ ] **Cancelado.**

### 53.5 Fundamentação

[Preencher]

### 53.6 Autoridade e evidência

**Responsável pela verificação:** [Nome]  
**Autoridade do controle:** [Nome e função]  
**Data:** [DD/MM/AAAA]  
**Registro:** [ID, link ou caminho]  
**Próximo movimento autorizado:** [Preencher]

## 54. Critérios de conclusão do plano

O plano está concluído quando:

- [ ] identificação, estado e linha de base estão registrados;
- [ ] condições da abertura foram incorporadas;
- [ ] problema, decisão, objetivo e escopo são coerentes;
- [ ] estratégia e ciclos estão definidos;
- [ ] requisitos e critérios possuem plano de consolidação;
- [ ] estado atual e capacidades futuras possuem plano;
- [ ] frentes e dependências estão definidas;
- [ ] pacotes e atividades essenciais possuem responsáveis;
- [ ] alternativas, integração e avaliação estão planejadas;
- [ ] decisões, validações e aprovações estão planejadas;
- [ ] entregas e definições de pronto estão claras;
- [ ] rastreabilidade possui responsável e ritmo;
- [ ] governança e autoridade estão definidas;
- [ ] participantes e especialistas estão previstos;
- [ ] cronograma e caminho crítico estão compreensíveis;
- [ ] recursos e acessos são suficientes ou condicionados;
- [ ] dados, confidencialidade e IA possuem controle;
- [ ] qualidade, riscos, impedimentos e mudanças possuem tratamento;
- [ ] pontos de controle foram agendados;
- [ ] o PC-2 foi decidido;
- [ ] a versão aprovada constitui linha de base.

### 54.1 Teste de reconstrução

Uma pessoa autorizada que não participou do planejamento deve conseguir responder:

1. o que será desenhado e por quê;
2. que decisão será apoiada;
3. que requisitos e capacidades orientam o trabalho;
4. que frentes existem e como se relacionam;
5. que atividades produzirão quais saídas;
6. quem responde, participa, valida e decide;
7. que ferramentas serão utilizadas e para quê;
8. como alternativas serão produzidas e comparadas;
9. como componentes serão integrados;
10. como dados e IA serão tratados;
11. que riscos e dependências podem interromper o percurso;
12. quando ocorrerão os controles;
13. o que demonstra prontidão para desenhar;
14. o que o projeto entregará ao Módulo 4.

### 54.2 Resultado

- [ ] Todas as respostas puderam ser reconstruídas.
- [ ] Existem lacunas não impeditivas registradas.
- [ ] Existem lacunas impeditivas; o plano retorna a `em elaboração`.

## 55. Aprovações do plano

### 55.1 Elaborado por

**Nome:** [Preencher]  
**Função:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Manifestação:** [Plano completo / Plano completo com pendências]

### 55.2 Revisado pelo responsável pela arquitetura

**Nome:** [Preencher]  
**Manifestação:** [Recomendo / Recomendo com condições / Não recomendo]  
**Condições:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Referência]

### 55.3 Aprovado pelo patrocinador ou responsável do cliente

**Nome:** [Preencher]  
**Função:** [Preencher]  
**Manifestação:** [Aprovo / Aprovo com condições / Não aprovo]  
**Condições:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Evidência:** [Referência]

### 55.4 Aprovações especializadas

| Objeto | Especialista | Manifestação | Condição | Data | Evidência |
| --- | --- | --- | --- | --- | --- |
| [Dados, segurança, jurídico, tecnologia ou outro] | [Nome] | [Aprovo/Valido/Com ressalvas] | [Preencher] | [Data] | [Referência] |

### 55.5 Divergências preservadas

| Pessoa ou grupo | Divergência | Efeito | Tratamento | Decisão |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID] |

## 56. Síntese executiva do plano

Preencha esta seção depois da aprovação.

| Elemento | Síntese |
| --- | --- |
| Projeto | [ID e título] |
| Transformação | [Uma frase] |
| Problema | [Uma frase] |
| Decisão | [Uma frase e autoridade] |
| Escopo | [Capacidades e dimensões] |
| Estratégia | [Abordagem e ciclos] |
| Frentes | [IDs e nomes] |
| Entregas principais | [IDs] |
| Alternativas previstas | [Síntese] |
| Validação | [Pessoas e métodos] |
| Prazo | [Período] |
| Caminho crítico | [Síntese] |
| Risco principal | [ID e resposta] |
| Dados e IA | [Limite principal] |
| Resultado do PC-2 | [Estado] |
| Condições pendentes | [IDs ou nenhuma] |
| Próximo movimento | [Preencher] |

## 57. Versão reduzida para arquitetura focal

Esta versão pode ser utilizada quando o projeto for focal, de baixa complexidade e risco controlado.

### 57.1 Identificação

| Campo | Registro |
| --- | --- |
| ID e título | [Preencher] |
| Termo de Abertura | [ID e versão] |
| Responsável | [Nome] |
| Patrocinador | [Nome] |
| Período | [Preencher] |
| Sensibilidade | [Nível] |

### 57.2 Núcleo do plano

| Elemento | Registro |
| --- | --- |
| Problema | [Preencher] |
| Decisão e autoridade | [Preencher] |
| Capacidade | [ID e descrição] |
| Requisitos | [IDs] |
| Critérios | [IDs] |
| Escopo e exclusões | [Preencher] |
| Estado atual necessário | [Preencher] |
| Alternativas | [Preencher] |
| Ferramenta | [Preencher] |
| Atividades | [IDs e sequência] |
| Participantes | [Preencher] |
| Entregas | [IDs] |
| Validação | [Forma e pessoa] |
| Risco principal | [ID e resposta] |
| Dados e IA | [Condição] |
| Prazo | [Preencher] |

### 57.3 Plano de trabalho focal

| ID | Atividade | Responsável | Entrada | Saída | Data | Conclusão |
| --- | --- | --- | --- | --- | --- | --- |
| ATV-F01 | [Preencher] | [Nome] | [Preencher] | [Preencher] | [Data] | [Critério] |

### 57.4 Controles mínimos

- [ ] requisitos e critérios definidos;
- [ ] alternativa ou justificativa para caminho único registrada;
- [ ] decisão e autoridade identificadas;
- [ ] validação proporcional planejada;
- [ ] dados e IA controlados;
- [ ] rastreabilidade possível;
- [ ] PC-2 decidido;
- [ ] aprovação evidenciada.

## 58. Primeiro ciclo detalhado

Esta seção deve ser atualizada no início de cada ciclo, preservando o histórico anterior.

### 58.1 Objetivo do ciclo

[Preencher]

### 58.2 Pergunta

> [Preencher]

### 58.3 Período

**Início:** [DD/MM/AAAA]  
**Fim:** [DD/MM/AAAA]

### 58.4 Itens comprometidos

| ID | Atividade/pacote | Responsável | Entrada confirmada? | Saída | Critério | Dependência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome] | [Sim/Não] | [Preencher] | [Preencher] | [ID] | Pronta |

### 58.5 Decisões do ciclo

| Decisão | Autoridade | Informação necessária | Data limite |
| --- | --- | --- | --- |
| [Preencher] | [Nome/função] | [Preencher] | [Data] |

### 58.6 Riscos e bloqueios

| ID | Situação | Responsável | Ação imediata | Escalonamento |
| --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome] | [Preencher] | [Preencher] |

### 58.7 Revisão do ciclo

**Saídas concluídas:** [IDs]

**Saídas não concluídas:** [IDs e motivo]

**Aprendizado:** [Preencher]

**Mudança necessária no plano:** [Preencher]

**Próximo ciclo:** [Preencher]

## 59. Controle de versões

| Versão | Data | Estado | Alteração | Motivo | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em elaboração | Criação inicial | Planejamento | [Nome] | Não aplicável |
| 1.0 | [DD/MM/AAAA] | Aprovado | Linha de base | PC-2 | [Nome] | [Referência] |

### 59.1 Linha de base vigente

**Versão:** [Preencher]  
**Data:** [DD/MM/AAAA]  
**Local oficial:** [Referência]  
**Decisão ou aprovação:** [ID]  
**Versão substituída:** [Versão ou não aplicável]

## 60. Regra de encerramento do plano

O Plano de Arquitetura permanece ativo durante a produção, integração, decisão, validação e preparação da transição para implantação.

Ele pode ser encerrado quando:

- o percurso foi concluído;
- a linha de base foi aprovada;
- o pacote do Módulo 4 foi aceito;
- pendências foram transferidas;
- registros e versões foram consolidados;
- a retrospectiva foi programada ou concluída;
- ou uma decisão formal encerrou o projeto antes da conclusão.

O encerramento não elimina desvios, alternativas rejeitadas, decisões, riscos ou versões anteriores. Esses elementos preservam a inteligibilidade do percurso e alimentam a aprendizagem organizacional.

---

## Registro final

**Estado do plano:** [Preencher]  
**Versão vigente:** [Preencher]  
**Resultado do PC-2:** [Preencher]  
**Data da aprovação:** [DD/MM/AAAA]  
**Responsável pelo registro:** [Nome]  
**Próximo artefato:** `catalogo-de-requisitos.md`  
**Próximo movimento autorizado:** [Preencher]  
**Observações:** [Preencher]
