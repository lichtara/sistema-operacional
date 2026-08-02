# Matriz de Rastreabilidade da Arquitetura — Template Preenchível

**Identificação técnica no repositório**

```yaml
id_matriz: MTR-ARQ-AAAA-NNN
id_arquitetura: ARQ-AAAA-NNN
titulo: "[Nome da arquitetura — Matriz de Rastreabilidade]"
organizacao:
area_ou_processo:
id_catalogo_requisitos: CAT-REQ-AAAA-NNN
id_plano: PLA-ARQ-AAAA-NNN
id_diagnostico: DIA-AAAA-NNN
id_transicao: TRA-AAAA-NNN
responsavel_pela_matriz:
responsavel_pela_arquitetura:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado: em_construcao
linha_de_base:
nivel_sensibilidade: "publica | interna | confidencial | sensivel"
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Template operacional preenchível  
**Função:** Registro de objetos, vínculos, cobertura, lacunas, impactos e continuidade da arquitetura  
**Documento de referência:** Matriz de Rastreabilidade da Arquitetura  
**Documento de entrada principal:** Catálogo de Requisitos  
**Uso transversal:** PC-2, PC-3, PC-4 e PC-5

**Documentos relacionados:**

- Matriz de Rastreabilidade da Arquitetura — método;
- Matriz de Evidências;
- Transição para Arquitetura Organizacional;
- Termo de Abertura da Arquitetura;
- Plano de Arquitetura;
- Catálogo de Requisitos;
- registros de capacidades;
- alternativas de arquitetura;
- registros de decisão;
- Arquitetura Integrada;
- registros de validação;
- Transição para Implantação;
- registros de indicadores e aprendizagem.

---

## 1. Finalidade

Esta matriz torna preenchível e governável o percurso entre a realidade diagnosticada e o funcionamento organizacional futuro.

Ela registra:

- que objetos existem;
- como esses objetos se relacionam;
- que origem justifica cada requisito;
- que capacidades respondem às necessidades;
- que alternativas foram consideradas;
- que decisões selecionaram ou rejeitaram possibilidades;
- que componentes realizam capacidades;
- que componentes atendem requisitos;
- que grau de cobertura foi alcançado;
- que validações confrontaram o desenho;
- que itens deverão ser implantados;
- que indicadores observarão o funcionamento;
- que aprendizados retornam ao sistema.

A matriz deve permitir responder:

> De onde veio este elemento, por que ele existe, o que atende, quem o autorizou, como foi verificado e que parte da implantação ou da operação dependerá dele?

## 2. Resultado esperado

Ao utilizar este template, outra pessoa autorizada deve conseguir:

1. partir de uma evidência ou achado e acompanhar seu destino;
2. partir de um componente e retornar à sua justificativa;
3. localizar requisitos sem tratamento;
4. localizar componentes sem origem suficiente;
5. distinguir cobertura parcial de completa;
6. reconstruir escolhas e alternativas rejeitadas;
7. identificar riscos sem controle;
8. reconhecer interfaces críticas;
9. verificar o que foi validado;
10. compreender o impacto de uma mudança;
11. preparar implantação e critérios de aceite;
12. ligar a operação ao aprendizado;
13. identificar a versão vigente da arquitetura.

## 3. Posição no ciclo

```text
Diagnóstico e evidências
          ↓
Objetos de origem
          ↓
Requisitos e capacidades
          ↓
Alternativas e critérios
          ↓
Decisões
          ↓
Componentes e interfaces
          ↓
Validação
          ↓
Implantação
          ↓
Indicadores e aprendizagem
```

A matriz começa a ser preenchida depois do aceite da transição, recebe a primeira revisão completa antes do PC-2 e permanece ativa até a operação e a aprendizagem.

## 4. Instruções de uso

1. Duplique este arquivo para cada arquitetura real.
2. Não preencha diretamente o template-mestre.
3. Reutilize identificadores dos documentos de origem.
4. Mantenha objetos e vínculos em camadas separadas.
5. Registre uma relação por linha.
6. Utilize o vocabulário controlado da seção 18.
7. Preserve a direção canônica dos vínculos.
8. Não copie conteúdo extenso quando referência segura for suficiente.
9. Não declare cobertura apenas porque existe vínculo.
10. Não apague objetos ou vínculos retirados da linha de base.
11. Atualize a matriz junto com a mudança material, não somente no encerramento.
12. Produza apenas as visões derivadas que apoiem decisão, validação ou continuidade.
13. Separe registros sensíveis quando necessário.
14. Submeta sugestões produzidas por IA à revisão humana.
15. Verifique a matriz antes de cada ponto de controle.

### 4.1 Convenções

| Convenção | Significado |
| --- | --- |
| `[Preencher]` | Registro necessário. |
| `N/A` | Cobertura ou campo não aplicável ao vínculo. |
| `Não determinado` | Informação ainda insuficiente. |
| `Pendente` | Tratamento futuro com responsável e limite. |
| `VNC-NNN` | Identificador do vínculo. |
| `MTR-ARQ-AAAA-NNN` | Identificador da matriz. |
| `LB-ARQ-NNN` | Linha de base. |
| `IMP-ARQ-NNN` | Análise de impacto. |

### 4.2 Princípio de proporcionalidade

Arquiteturas focais podem utilizar as seções essenciais e a versão reduzida da seção 55.

Arquiteturas funcionais ou sistêmicas devem separar registros quando o volume comprometer:

- leitura;
- filtragem;
- controle de acesso;
- manutenção;
- análise de impacto;
- automação.

## 5. Formas de implementação

Este template pode ser utilizado em:

- documento Markdown;
- planilha;
- banco de dados;
- ferramenta de gestão;
- grafo;
- sistema próprio.

### 5.1 Requisitos da implementação

Independentemente da ferramenta, deve ser possível:

- exportar os registros;
- preservar IDs estáveis;
- manter histórico;
- filtrar objetos e vínculos;
- identificar versões;
- controlar acesso;
- localizar fontes oficiais;
- revisar sugestões automáticas;
- reconstruir caminhos sem depender da ferramenta original.

### 5.2 Fonte de verdade

**Implementação oficial:** [Documento, planilha, sistema ou banco]  
**Local:** [Referência]  
**Responsável:** [Nome]  
**Formato de exportação:** [Markdown, CSV, JSON, outro]  
**Frequência de backup/exportação:** [Preencher]

## 6. Identificação da matriz

| Campo | Registro |
| --- | --- |
| ID da matriz | MTR-ARQ-AAAA-NNN |
| ID da arquitetura | ARQ-AAAA-NNN |
| Título | [Nome] |
| Organização | [Nome] |
| Área ou processo | [Quando aplicável] |
| Responsável pela matriz | [Nome] |
| Responsável pela arquitetura | [Nome] |
| Custodiante | [Nome] |
| Data de criação | [DD/MM/AAAA] |
| Data da última revisão | [DD/MM/AAAA] |
| Linha de base | [LB-ARQ-NNN ou não aplicável] |
| Sensibilidade | [Pública, interna, confidencial ou sensível] |
| Versão | [0.1] |
| Estado | [Selecionar na seção 7] |

### 6.1 Documentos relacionados

| Documento | ID | Versão | Estado | Referência |
| --- | --- | --- | --- | --- |
| Diagnóstico | DIA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Transição | TRA-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Plano | PLA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Catálogo de Requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] |
| Arquitetura Integrada | [ID] | [Versão] | [Estado] | [Link] |
| Transição para Implantação | [ID] | [Versão] | [Estado] | [Link] |

## 7. Estado da matriz

Selecione um único estado vigente.

- [ ] **Em preparação** — fontes, classes e responsáveis estão sendo definidos.
- [ ] **Em construção** — objetos e vínculos estão sendo registrados.
- [ ] **Em revisão** — consistência, cobertura e lacunas estão sendo verificadas.
- [ ] **Consolidada** — matriz utilizável na etapa atual.
- [ ] **Consolidada com limitações** — utilizável dentro das condições registradas.
- [ ] **Aguardando validação** — vínculos ou coberturas materiais dependem de verificação.
- [ ] **Linha de base candidata** — conjunto preparado para aprovação.
- [ ] **Linha de base aprovada** — versão oficial da arquitetura.
- [ ] **Em atualização** — mudança material está sendo incorporada.
- [ ] **Reaberta** — nova informação exige revisão de vínculos.
- [ ] **Substituída** — outra versão constitui a referência vigente.
- [ ] **Suspensa** — manutenção temporariamente interrompida.
- [ ] **Encerrada** — ciclo concluído e histórico preservado.

**Data da última mudança:** [DD/MM/AAAA]  
**Responsável:** [Nome]  
**Motivo ou referência:** [Preencher]

## 8. Governança e fontes oficiais

### 8.1 Regra

A matriz referencia os documentos oficiais; não substitui seu conteúdo.

### 8.2 Fonte por classe

| Classe | Fonte oficial | Responsável | Regra em caso de divergência |
| --- | --- | --- | --- |
| Evidências e achados | Matriz de Evidências / diagnóstico | [Nome] | [Preencher] |
| Requisitos | Catálogo de Requisitos | [Nome] | [Preencher] |
| Capacidades | Registro de capacidades | [Nome] | [Preencher] |
| Critérios | Plano / registro de critérios | [Nome] | [Preencher] |
| Alternativas | Registro de alternativas | [Nome] | [Preencher] |
| Decisões | Registro de decisão | [Nome] | Decisão aprovada prevalece dentro de seu alcance |
| Componentes e interfaces | Arquitetura Integrada | [Nome] | [Preencher] |
| Validações | Registro de Validação | [Nome] | [Preencher] |
| Implantação | Transição / plano do Módulo 4 | [Nome] | [Preencher] |
| Indicadores | Arquitetura / operação | [Nome] | [Preencher] |
| Aprendizados | Retrospectiva / Módulo 6 | [Nome] | [Preencher] |

### 8.3 Divergência entre matriz e fonte

| ID | Objeto/vínculo | Matriz registra | Fonte registra | Efeito | Responsável | Prazo | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DIV-MTR-001 | [ID] | [Preencher] | [Preencher] | [Preencher] | [Nome] | [Data] | Aberta |

## 9. Estrutura lógica

A matriz possui:

1. **registro de objetos** — declara o que existe;
2. **registro de vínculos** — declara como os objetos se relacionam;
3. **visões derivadas** — apresentam cobertura, lacunas, impactos e prontidão.

### 9.1 Por que separar

Separar objetos e vínculos permite:

- relações muitos-para-muitos;
- descrição única por objeto;
- mudanças sem duplicação;
- filtros confiáveis;
- direção explícita;
- análise de impacto;
- automação proporcional.

### 9.2 Unidade da matriz principal

Uma linha representa um vínculo.

```text
Objeto de origem + relação + objeto de destino
```

## 10. Ordem de preenchimento

1. identificar documentos e versões de entrada;
2. importar ou referenciar objetos diagnósticos;
3. registrar requisitos e capacidades;
4. verificar IDs e duplicações;
5. criar vínculos de origem e justificação;
6. criar vínculos de desenho;
7. relacionar alternativas e decisões;
8. relacionar componentes e interfaces;
9. registrar cobertura;
10. relacionar validações;
11. preparar implantação e operação;
12. gerar visões derivadas;
13. localizar lacunas, órfãos e conflitos;
14. revisar a linha de base.

### 10.1 Primeiro conjunto mínimo

Antes do PC-2, devem existir, no mínimo:

- objetos de origem relevantes;
- requisitos;
- capacidades a preservar;
- riscos e restrições;
- critérios de desenho;
- vínculos de origem;
- responsáveis;
- lacunas conhecidas.

## 11. Classes de objetos

### 11.1 Origem diagnóstica

| Prefixo | Objeto | Fonte oficial |
| --- | --- | --- |
| ENT | Entrevista | Registro diagnóstico |
| OBS | Observação | Registro de observação |
| DOC | Documento | Inventário documental |
| DAD | Conjunto de dados | Registro de dados |
| SIS | Sistema | Inventário de sistemas |
| EXT | Material externo | Fonte externa |
| EVD | Evidência | Matriz de Evidências |
| ACH | Achado | Síntese ou relatório |
| PRB | Problema | Transição / diagnóstico |
| CAP | Capacidade existente | Transição / diagnóstico |
| RSC | Risco | Diagnóstico / arquitetura |
| RES | Restrição | Transição / arquitetura |
| DEP | Dependência | Transição / arquitetura |
| LAC | Lacuna | Registro de lacunas |
| QAB | Questão aberta | Transição / plano |

### 11.2 Arquitetura

| Prefixo | Objeto | Fonte oficial |
| --- | --- | --- |
| ARQ | Projeto de arquitetura | Termo de Abertura |
| REQ | Requisito | Catálogo de Requisitos |
| CAP | Capacidade futura | Registro de capacidades |
| CRT | Critério de desenho | Plano / avaliação |
| PRE | Premissa | Plano / artefato dimensional |
| ALT | Alternativa | Registro de alternativas |
| DEC | Decisão | Registro do Módulo 1 |
| CMP | Componente | Arquitetura Integrada |
| INT | Interface | Arquitetura Integrada |
| CTL | Controle | Arquitetura / riscos |

### 11.3 Validação e continuidade

| Prefixo | Objeto | Fonte oficial |
| --- | --- | --- |
| VAL | Validação | Registro de Validação |
| TST | Teste | Registro de teste/simulação |
| ITM | Item de implantação | Transição / Módulo 4 |
| IND | Indicador | Arquitetura / Módulo 5 |
| APD | Aprendizado | Retrospectiva / Módulo 6 |

### 11.4 Prefixos locais

| Prefixo existente | Conflito | Identificador qualificado adotado | Regra |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Ex.: ARQ-2026-001-REQ-007] | [Preencher] |

## 12. Registro de objetos

| ID | Tipo | Título | Descrição mínima | Projeto | Origem oficial | Estado | Prioridade | Responsável | Versão | Sensibilidade | Revisão | Referência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-001 | Requisito | [Título] | [Condição resumida] | ARQ-AAAA-NNN | [Documento] | [Estado oficial] | [Prioridade] | [Nome/papel] | [Versão] | [Nível] | [Data] | [Link] |

### 12.1 Regras

- reutilize IDs existentes;
- não invente estado diferente da fonte oficial;
- registre descrição mínima suficiente;
- preserve versão e data;
- utilize referência, não cópia extensa;
- indique sensibilidade por objeto quando necessário;
- mantenha objetos retirados com estado correspondente.

### 12.2 Estado do objeto

O campo `Estado` reproduz o estado definido no documento oficial daquela classe. A matriz não cria uma taxonomia genérica concorrente.

### 12.3 Objeto sem fonte oficial

| ID provisório | Tipo | Motivo | Responsável por formalizar | Prazo | Uso permitido | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| OBJ-P01 | [Tipo] | [Preencher] | [Nome] | [Data] | [Exploração / não pode compor linha de base] | Provisório |

## 13. Ficha de objeto

Utilize quando o registro mestre não for suficiente para interpretar ou governar o objeto.

**ID:** [Preencher]  
**Tipo:** [Preencher]  
**Título:** [Preencher]  
**Descrição:** [Preencher]  
**Projeto:** [ID]  
**Origem oficial:** [Documento, versão e localização]  
**Estado:** [Estado oficial]  
**Prioridade:** [Preencher ou N/A]  
**Responsável:** [Nome/papel]  
**Sensibilidade:** [Nível]  
**Data de criação:** [DD/MM/AAAA]  
**Data de revisão:** [DD/MM/AAAA]  
**Versão:** [Preencher]  
**Vínculos esperados:** [Tipos de relação]  
**Observações:** [Preencher]

### 13.1 Identidade estável

Alterações de descrição, prioridade ou estado não criam novo ID quando o objeto continua representando a mesma entidade ou condição.

### 13.2 Novo objeto

Crie novo ID quando:

- a condição foi desdobrada em objeto independente;
- o elemento possui ciclo próprio;
- a decisão pode divergir;
- a verificação precisa ser separada;
- o objeto substitui outro materialmente.

## 14. Natureza das capacidades

| ID | Capacidade | Natureza | Estado | Origem | Manifestação observável | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| CAP-001 | [Preencher] | [Existente, preservar, fortalecer, desenvolver, substituir, futura ou descontinuar] | [Estado] | [Documento] | [Preencher] | [Papel] |

### 14.1 Regra

O mesmo prefixo `CAP` pode representar condições diferentes. A natureza impede que capacidade existente e futura sejam tratadas como equivalentes.

### 14.2 Capacidade existente

Deve possuir vínculo com evidência ou achado e, quando relevante, com componente que a preserva.

### 14.3 Capacidade futura

Deve possuir requisito, condições de funcionamento, componentes, responsável, manifestação observável, validação e destino de implantação.

## 15. Registro de vínculos

| ID | Origem | Tipo origem | Relação | Destino | Tipo destino | Cobertura | Justificativa | Estado | Validação | Condição | Responsável | Versão | Referência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VNC-001 | REQ-001 | Requisito | deriva_de | ACH-003 | Achado | N/A | [Por que a relação existe] | Proposto | [VAL/N/A] | [Preencher/N/A] | [Nome] | 0.1 | [Link] |

### 15.1 Regra de granularidade

Uma linha representa um vínculo. Quando um requisito derivar de três achados, registre três linhas.

### 15.2 Justificativa

A justificativa deve explicar o significado local da relação quando o vocabulário sozinho não for suficiente.

### 15.3 Cobertura

Preencha somente quando a relação representar tratamento ou atendimento. Utilize `N/A` em relações de origem, decisão, substituição ou verificação.

### 15.4 Identificação opcional

Em projetos focais, o vínculo pode ser identificado pela combinação origem–relação–destino. Use `VNC-NNN` quando for necessário versionar, decidir ou referenciar a relação.

## 16. Ficha de vínculo

**ID:** VNC-___  
**Objeto de origem:** [ID e tipo]  
**Relação:** [Vocabulário controlado]  
**Objeto de destino:** [ID e tipo]  
**Direção verificada:** [Sim/Não]  
**Justificativa:** [Preencher]  
**Cobertura:** [Estado ou N/A]  
**Critério de cobertura:** [Referência ou N/A]  
**Estado do vínculo:** [Selecionar na seção 19]  
**Validação:** [ID, método ou planejada]  
**Condição:** [Preencher ou N/A]  
**Decisão:** [ID ou N/A]  
**Responsável:** [Nome]  
**Sensibilidade:** [Nível]  
**Versão:** [Preencher]  
**Data de criação:** [DD/MM/AAAA]  
**Data de revisão:** [DD/MM/AAAA]  
**Fonte oficial:** [Referência]

### 16.1 Teste do vínculo

- [ ] os dois objetos existem;
- [ ] os IDs correspondem às fontes oficiais;
- [ ] a relação possui significado;
- [ ] a direção está correta;
- [ ] a justificativa é localizável;
- [ ] a cobertura não foi presumida;
- [ ] o estado corresponde à revisão realizada;
- [ ] a versão está correta;
- [ ] a sensibilidade foi considerada.

## 17. Direção canônica

Utilize uma única direção por tipo de relação.

| Declaração canônica | Exemplo |
| --- | --- |
| Requisito deriva de origem | `REQ-001 deriva_de ACH-003` |
| Capacidade responde a requisito | `CAP-002 responde_a REQ-001` |
| Componente realiza capacidade | `CMP-004 realiza CAP-002` |
| Componente atende requisito | `CMP-004 atende REQ-001` |
| Item implementa componente | `ITM-004 implementa CMP-004` |
| Validação ou teste verifica objeto | `VAL-002 verifica REQ-001` |
| Indicador monitora objeto | `IND-001 monitora CAP-002` |
| Alternativa é selecionada por decisão | `ALT-002 é_selecionado_por DEC-001` |

### 17.1 Evitar inversões

Não alterne entre:

```text
CMP-004 atende REQ-001
REQ-001 é_atendido_por CMP-004
```

A uniformidade permite filtros, verificações e automação.

### 17.2 Relações simétricas

Conflito pode ser tratado como relação simétrica. Defina regra única para ordenar IDs e evitar duplicação.

**Regra adotada:** [Ex.: menor ID na origem]

## 18. Vocabulário controlado de relações

### 18.1 Origem e justificação

| Relação | Preenchimento |
| --- | --- |
| `deriva_de` | [Objetos permitidos e observação local] |
| `é_justificado_por` | [Preencher] |
| `formaliza` | [Preencher] |
| `responde_a` | [Preencher] |
| `preserva` | [Preencher] |
| `trata` | [Preencher] |

### 18.2 Atendimento

| Relação | Preenchimento |
| --- | --- |
| `atende` | Cobertura completa conforme critério. |
| `atende_parcialmente` | Cobertura incompleta ou condicionada. |
| `não_atende` | Avaliado e insuficiente. |
| `realiza` | Componente torna capacidade possível. |
| `implementa` | Item de implantação materializa componente ou decisão. |
| `monitora` | Indicador observa capacidade, requisito ou risco. |

### 18.3 Estruturais

| Relação | Preenchimento |
| --- | --- |
| `depende_de` | [Preencher] |
| `é_restringido_por` | [Preencher] |
| `é_composto_por` | [Preencher] |
| `é_conectado_por` | [Preencher] |
| `transfere_para` | [Preencher] |
| `controla` | [Preencher] |
| `conflita_com` | [Preencher] |

### 18.4 Decisórias e temporais

| Relação | Preenchimento |
| --- | --- |
| `é_selecionado_por` | [Preencher] |
| `é_rejeitado_por` | [Preencher] |
| `é_adiado_por` | [Preencher] |
| `substitui` | [Preencher] |
| `é_substituído_por` | [Preencher] |
| `é_reaberto_por` | [Preencher] |

### 18.5 Verificação e aprendizagem

| Relação | Preenchimento |
| --- | --- |
| `verifica` | [Validação ou teste verifica objeto] |
| `é_verificado_por` | [Utilizar apenas se a implementação adotar direção inversa; não misturar com `verifica`] |
| `é_contradito_por` | [Preencher] |
| `gera` | [Preencher] |
| `gera_aprendizado` | [Preencher] |

### 18.6 Extensões locais

| Relação nova | Necessidade | Definição | Direção | Aprovador | Data |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Origem → destino] | [Nome] | [Data] |

Extensões devem ser criadas somente quando o vocabulário existente não representar a relação sem ambiguidade.

## 19. Estados dos vínculos

| Estado | Significado |
| --- | --- |
| Proposto | Relação identificada e ainda não revisada. |
| Em revisão | Significado, direção, cobertura ou origem estão sendo examinados. |
| Aprovado | Relação aceita para a etapa vigente. |
| Aprovado com condição | Relação aceita dentro de condição explícita. |
| Validado | Relação confrontada com critério, teste, pessoa ou resultado. |
| Suspenso | Relação temporariamente sem efeito. |
| Rejeitado | Relação proposta não foi aceita. |
| Invalidado | Relação anteriormente aceita perdeu sustentação. |
| Substituído | Outro vínculo assumiu sua função. |
| Encerrado | Relação concluiu seu ciclo e permanece histórica. |

### 19.1 Vínculo invalidado

| Vínculo | Razão | Evidência/decisão | Vínculo substituto | Data |
| --- | --- | --- | --- | --- |
| VNC-___ | [Preencher] | [ID] | [VNC-ID ou nenhum] | [Data] |

### 19.2 Proibição de exclusão silenciosa

Vínculos rejeitados, invalidados e substituídos permanecem no histórico.

## 20. Escala de cobertura

| Cobertura | Significado |
| --- | --- |
| Não avaliada | A relação ainda não foi examinada. |
| Sem tratamento | Nenhum objeto responde adequadamente. |
| Candidata | Existe solução possível ainda não consolidada. |
| Parcial | Parte da condição foi atendida. |
| Completa | O critério vigente foi atendido. |
| Completa com condição | Atendimento depende de condição explícita. |
| Adiada | Atendimento foi postergado por decisão. |
| Rejeitada | A condição não será atendida, com decisão. |
| Não aplicável | Cobertura não se aplica à relação. |

### 20.1 Registro da condição

| Vínculo | Cobertura | Condição | Responsável | Prazo/gatilho | Risco | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| VNC-___ | Completa com condição | [Preencher] | [Nome] | [Data/condição] | [ID] | [DEC-ID] |

### 20.2 Cobertura compartilhada

| Requisito | Componentes | Cobertura de cada vínculo | Critério do conjunto | Cobertura do conjunto | Validação |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | [CMP-___, CMP-___] | [Parcial, Parcial] | [Referência] | [Completa/Parcial] | [VAL/TST] |

### 20.3 Regra

Cobertura é avaliada pelo critério de atendimento, não pela quantidade de vínculos.

## 21. Matriz principal de vínculos

Esta é a camada operacional central.

| Origem | Tipo | Relação | Destino | Tipo | Cobertura | Estado | Justificativa | Validação | Condição | Versão | Referência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-001 | Requisito | deriva_de | ACH-003 | Achado | N/A | Aprovado | [Preencher] | [N/A/ID] | [N/A] | [Versão] | [Link] |
| CAP-002 | Capacidade | responde_a | REQ-001 | Requisito | Completa | Em revisão | [Preencher] | [VAL-ID] | [N/A] | [Versão] | [Link] |
| CMP-004 | Componente | realiza | CAP-002 | Capacidade | Parcial | Proposto | [Preencher] | [TST-ID] | [Preencher] | [Versão] | [Link] |

### 21.1 Colunas opcionais

- ID do vínculo;
- prioridade;
- risco;
- responsável;
- data;
- sensibilidade;
- documento oficial;
- linha de base;
- comentário de revisão.

### 21.2 Descrições

Descrições completas permanecem no registro de objetos ou documento oficial.

## 22. Cadeias mínimas obrigatórias

### 22.1 Justificação

| Objeto de origem | Vínculo | Requisito | Estado |
| --- | --- | --- | --- |
| [ACH, exigência externa ou DEC] | [deriva_de/é_justificado_por] | REQ-___ | [Estado] |

### 22.2 Desenho

| Requisito | Capacidade | Componentes | Cobertura | Lacuna |
| --- | --- | --- | --- | --- |
| REQ-___ | CAP-___ | [CMP-IDs] | [Estado] | [ID ou nenhuma] |

### 22.3 Decisão

| Alternativas | Decisão | Resultado | Estado |
| --- | --- | --- | --- |
| [ALT-IDs] | DEC-___ | [Selecionada, combinada, rejeitada, adiada ou experimento] | [Estado] |

### 22.4 Validação

| Requisito/componente | Validação/teste | Critério | Resultado | Pendência |
| --- | --- | --- | --- | --- |
| [ID] | [VAL/TST-ID] | [Referência] | [Preencher] | [ID ou nenhuma] |

### 22.5 Implantação

| Componente | Item de implantação | Destino | Critério de aceite | Estado |
| --- | --- | --- | --- | --- |
| CMP-___ | ITM-___ | [Criar, alterar, configurar, migrar, preservar, adiar ou N/A] | [Preencher] | [Estado] |

### 22.6 Operação

| Objeto observado | Indicador/método | Decisão apoiada | Frequência | Responsável |
| --- | --- | --- | --- | --- |
| [CAP/REQ/RSC-ID] | [IND-ID/método] | [DEC operacional] | [Preencher] | [Papel] |

## 23. Registro de caminhos

Use para caminhos críticos que precisam ser auditados como conjunto.

| ID | Finalidade | Sequência de objetos e vínculos | Início | Fim | Responsável | Estado | Linha de base |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CAM-001 | [Justificar componente crítico] | [ACH → REQ → CAP → CMP → VAL → ITM] | [ID] | [ID] | [Nome] | [Estado] | [LB-ID] |

### 23.1 Caminho incompleto

| Caminho | Vínculo ausente | Impacto | Classificação | Ação | Prazo |
| --- | --- | --- | --- | --- | --- |
| CAM-___ | [Preencher] | [Preencher] | [Crítica/Relevante/Complementar] | [Preencher] | [Data] |

## 24. Visão de cobertura dos requisitos

| Requisito | Prioridade | Origem | Capacidades | Componentes | Cobertura | Critério | Validação | Estado | Próxima ação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REQ-001 | Obrigatório | ACH-003 | CAP-002 | CMP-003, CMP-004 | Parcial | [Referência] | Planejada | Em desenho | [Ação, responsável e data] |

### 24.1 Perguntas

- [ ] todo requisito possui origem;
- [ ] obrigatórios possuem capacidade ou exceção;
- [ ] existe componente responsável pelo atendimento;
- [ ] o critério está definido;
- [ ] a cobertura foi avaliada;
- [ ] adiamentos e rejeições possuem decisão;
- [ ] validação proporcional está relacionada.

### 24.2 Requisito sem origem diagnóstica

| Requisito | Origem externa | Tipo | Justificativa | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- |
| REQ-___ | [Norma, decisão, especialista, risco ou implantação] | [Tipo] | [Preencher] | [Nome/função] | [Estado] |

## 25. Visão de cobertura das capacidades

| Capacidade | Natureza | Requisitos | Componentes | Responsável | Manifestação observável | Validação | Implantação | Cobertura |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CAP-002 | Desenvolver | REQ-001, REQ-004 | CMP-003, CMP-005 | [Papel] | [Preencher] | [VAL-ID] | [ITM-IDs] | Parcial |

### 25.1 Capacidade sem componente

| Capacidade | Possível causa | Análise | Decisão/ação | Responsável |
| --- | --- | --- | --- | --- |
| CAP-___ | [Desenho incompleto, abstração, adiada, externa, já existente ou erro] | [Preencher] | [Preencher] | [Nome] |

### 25.2 Capacidade a preservar

| Capacidade | Evidência de valor | Componente que preserva | Risco de perda | Validação |
| --- | --- | --- | --- | --- |
| CAP-___ | [EVD/ACH] | [CMP-ID] | [RSC-ID] | [VAL-ID] |

## 26. Visão de componentes

| Componente | Tipo | Capacidades | Requisitos | Dependências | Riscos | Responsável | Manutenção | Validação | Implantação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CMP-003 | [Processo/papel/documento/sistema/IA/outro] | CAP-002 | REQ-001 | DEP-002 | RSC-004 | [Papel] | [Condição] | TST-001 | ITM-004 |

### 26.1 Componente órfão

| Componente | Ausência | Investigação | Resultado | Decisão |
| --- | --- | --- | --- | --- |
| CMP-___ | [Sem requisito, capacidade, risco ou decisão] | [Preencher] | [Vincular, formalizar, fundir, retirar ou manter opcional] | [ID] |

### 26.2 Componente excessivamente conectado

| Componente | Objetos críticos relacionados | Risco | Necessidade de decomposição | Tratamento |
| --- | --- | --- | --- | --- |
| CMP-___ | [IDs] | [Ponto único de falha/dependência] | [Sim/Não] | [Preencher] |

## 27. Visão de interfaces

| Interface | Origem | Destino | Objeto transferido | Requisitos | Riscos | Confirmação | Exceção | Responsável | Validação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| INT-001 | CMP-001 | CMP-002 | [Informação, trabalho, decisão ou responsabilidade] | [REQ-IDs] | [RSC-IDs] | [Forma] | [Tratamento] | [Papel] | [VAL/TST] |

### 27.1 Interface sem tratamento

| Interface | Lacuna | Consequência | Componente afetado | Ação |
| --- | --- | --- | --- | --- |
| INT-___ | [Objeto, formato, momento, responsável, confirmação ou exceção] | [Preencher] | [IDs] | [Preencher] |

## 28. Visão de alternativas e decisões

| Alternativa | Requisitos atendidos | Critérios | Capacidades preservadas | Riscos | Decisão | Resultado | Componentes derivados |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ALT-001 | [REQ-IDs] | [CRT-IDs] | [CAP-IDs] | [RSC-IDs] | DEC-___ | [Selecionada/Não selecionada/Adiada] | [CMP-IDs] |

### 28.1 Alternativa não selecionada

| Alternativa | Benefícios | Limitações | Motivo da não seleção | Decisão | Reutilização possível |
| --- | --- | --- | --- | --- | --- |
| ALT-___ | [Preencher] | [Preencher] | [Preencher] | [DEC-ID] | [Condição] |

### 28.2 Decisão sem alternativas

| Decisão | Objeto | Justificativa | Autoridade | Condição de revisão |
| --- | --- | --- | --- | --- |
| DEC-___ | [Preencher] | [Exigência, única opção, decisão anterior ou objeto local/reversível] | [Nome/função] | [Preencher] |

## 29. Visão de riscos, restrições e controles

| Objeto | Tipo | Afeta | Tratamento | Controle | Decisão | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSC-004 | Risco | CMP-003 | Reduzir | CTL-002 | [DEC-ID] | [Papel] | [Estado] |
| RES-002 | Restrição | ALT-003 | Respeitar | N/A | [DEC-ID] | [Papel] | [Estado] |

### 29.1 Risco sem tratamento

| Risco | Objetos afetados | Exposição | Decisão necessária | Responsável | Prazo |
| --- | --- | --- | --- | --- | --- |
| RSC-___ | [IDs] | [Preencher] | [Aceitar, reduzir, evitar, transferir ou monitorar] | [Nome] | [Data] |

### 29.2 Controle sem risco

| Controle | Origem ausente | Possível explicação | Ação |
| --- | --- | --- | --- |
| CTL-___ | [Preencher] | [Erro, requisito, obrigação ou componente opcional] | [Preencher] |

### 29.3 Restrição sem efeito visível

| Restrição | Alternativa/componente esperado | Efeito encontrado | Análise | Resultado |
| --- | --- | --- | --- | --- |
| RES-___ | [IDs] | [Nenhum/Preencher] | [Preencher] | [Manter, corrigir, encerrar ou retirar do escopo] |

## 30. Visão de validação

| Validação/teste | Objeto verificado | Critério | Método | Resultado | Contradição | Pendência | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TST-001 | CMP-003 | [Preencher] | Simulação | [Aprovado/Parcial/Reprovado] | [ID/Nenhuma] | [Preencher] | [Nome] | [Data] |

### 30.1 Cobertura de validação

| Classe | Objetos obrigatórios/críticos | Validados | Planejados | Sem validação | Ação |
| --- | --- | --- | --- | --- | --- |
| Requisitos obrigatórios | [IDs/N] | [IDs/N] | [IDs/N] | [IDs/N] | [Preencher] |
| Componentes críticos | [IDs/N] | [IDs/N] | [IDs/N] | [IDs/N] | [Preencher] |
| Interfaces de risco | [IDs/N] | [IDs/N] | [IDs/N] | [IDs/N] | [Preencher] |
| Funções de IA | [IDs/N] | [IDs/N] | [IDs/N] | [IDs/N] | [Preencher] |

### 30.2 Resultado contraditório

| Validação | Objeto contradito | Efeito | Decisão/ação | Vínculos afetados | Estado |
| --- | --- | --- | --- | --- | --- |
| VAL-___ | [ID] | [Preencher] | [Corrigir, revisar, reabrir, aceitar limitação] | [VNC-IDs] | [Estado] |

## 31. Visão de implantação

| Item | Componente | Requisito | Dependências | Critério de aceite | Responsável | Onda | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ITM-004 | CMP-003 | REQ-001 | DEP-002 | [Preencher] | [Responsável M4] | [Onda] | Planejado |

### 31.1 Destino dos componentes

| Componente | Destino | Item | Decisão | Observação |
| --- | --- | --- | --- | --- |
| CMP-___ | [Preservar, criar, configurar, alterar, migrar, treinar, testar, adiar, substituir, desativar ou N/A] | [ITM-ID] | [DEC-ID] | [Preencher] |

### 31.2 Aceite pelo Módulo 4

- [ ] componentes são localizáveis;
- [ ] sequência é compreensível;
- [ ] dependências estão explícitas;
- [ ] critérios de aceite estão vinculados;
- [ ] responsáveis estão identificados;
- [ ] versões vigentes estão claras;
- [ ] decisões pendentes estão registradas;
- [ ] riscos e restrições são rastreáveis.

## 32. Visão operacional e aprendizagem

| Indicador/método | Observa | Fonte | Decisão apoiada | Frequência | Responsável | Aprendizado relacionado |
| --- | --- | --- | --- | --- | --- | --- |
| IND-001 | CAP-002 | [Fonte] | [Ajustar/manter/revisar] | [Frequência] | [Papel] | [APD-ID] |

### 32.1 Resultado operacional

| Resultado | Objeto afetado | Relação | Efeito | Ação | Decisão/reabertura |
| --- | --- | --- | --- | --- | --- |
| [IND/incidente/feedback] | [REQ/CAP/CMP/PRE/RSC] | [confirma, contradiz ou gera aprendizado] | [Preencher] | [Preencher] | [ID] |

### 32.2 Aprendizado

| Aprendizado | Origem | Objeto que modifica | Aplicabilidade | Responsável | Estado |
| --- | --- | --- | --- | --- | --- |
| APD-___ | [IND/VAL/ITM/projeto] | [ID] | [Local/método/futuro projeto] | [Nome] | [Estado] |

## 33. Premissas e condições

| Premissa | Objeto dependente | Base | Verificação | Resultado | Consequência | Responsável | Validade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PRE-001 | [IDs] | [Fonte/razão] | [VAL/TST/atividade] | [Pendente/Confirmada/Refutada] | [Preencher] | [Nome] | [Data/etapa] |

### 33.1 Premissa refutada

| Premissa | Objetos e vínculos afetados | Severidade | Ação | Decisão | Estado |
| --- | --- | --- | --- | --- | --- |
| PRE-___ | [IDs/VNC-IDs] | [Baixa/Média/Alta/Crítica] | [Preencher] | [DEC-ID] | [Estado] |

### 33.2 Condição de cobertura

Condições precisam estar vinculadas ao objeto, ao responsável, ao prazo ou gatilho e à decisão que aceitou o limite.

## 34. Lacunas de rastreabilidade

| ID | Caminho afetado | Vínculo/objeto ausente | Classificação | Impacto | Ação | Responsável | Prazo | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LAC-MTR-001 | REQ-003 → CMP-007 | Validação ausente | Relevante | Cobertura não confirmada | Testar integração | [Nome] | [Data] | Aberta |

### 34.1 Classificação

| Classe | Significado |
| --- | --- |
| Crítica | Impede decisão, aprovação, validação ou implantação responsável. |
| Relevante | Reduz confiança ou continuidade sem impedir todo avanço. |
| Complementar | Ampliaria contexto com baixo impacto atual. |
| Aceita | Permanência reconhecida e aprovada. |

### 34.2 Lacuna aceita

| Lacuna | Autoridade | Justificativa | Risco | Condição de revisão | Data |
| --- | --- | --- | --- | --- | --- |
| LAC-___ | [Nome/função] | [Preencher] | [ID] | [Preencher] | [Data] |

## 35. Objetos órfãos

| ID | Tipo | Objeto | Vínculo esperado | Tempo sem vínculo | Impacto | Ação | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ORF-001 | [Requisito/componente/validação/item/indicador] | [ID] | [Origem, atendimento, validação etc.] | [Período] | [Preencher] | [Preencher] | [Nome] | Aberto |

### 35.1 Tratamento

- localizar vínculo existente;
- corrigir erro de registro;
- formalizar nova origem;
- criar decisão;
- fundir;
- retirar ou encerrar;
- manter temporariamente com prazo.

### 35.2 Órfão temporário legítimo

| Objeto | Motivo | Próximo vínculo esperado | Responsável | Prazo | Uso permitido |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Tipo e objeto] | [Nome] | [Data] | [Exploração / não compõe linha de base] |

## 36. Conflitos e divergências

| ID | Objeto 1 | Relação | Objeto 2 | Natureza | Impacto | Decisão necessária | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CFL-001 | REQ-003 | conflita_com | REQ-006 | [Preencher] | [Preencher] | DEC-___ | [Nome] | Aberto |

### 36.1 Resultados

- resolvido;
- equilibrado;
- aceito;
- adiado;
- escalado;
- transformado em experimento;
- preservado como divergência.

### 36.2 Divergência de validação

| Objeto | Participante 1 | Resultado 1 | Participante 2 | Resultado 2 | Contexto | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/grupo] | [Preencher] | [Nome/grupo] | [Preencher] | [Preencher] | [Preencher] |

## 37. Análise de impacto

### 37.1 Identificação

| Campo | Registro |
| --- | --- |
| ID da análise | IMP-ARQ-NNN |
| Mudança | [ID/descrição] |
| Objeto alterado | [ID] |
| Data | [DD/MM/AAAA] |
| Responsável | [Nome] |
| Linha de base afetada | [LB-ID] |

### 37.2 Movimento regressivo

| Objeto alterado | Vínculos anteriores | Origens afetadas | Justificação permanece válida? | Ação |
| --- | --- | --- | --- | --- |
| [ID] | [VNC-IDs] | [EVD/ACH/REQ/DEC] | [Sim/Parcial/Não] | [Preencher] |

### 37.3 Movimento progressivo

| Objeto alterado | Capacidades | Componentes | Interfaces | Validações | Implantação | Indicadores | Ação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs] | [Preencher] |

### 37.4 Resultado

- [ ] sem impacto material;
- [ ] atualização editorial;
- [ ] revalidar vínculos;
- [ ] reavaliar cobertura;
- [ ] reabrir decisão;
- [ ] revisar arquitetura;
- [ ] comunicar Módulo 4;
- [ ] reabrir diagnóstico;
- [ ] criar nova linha de base.

**Decisão:** [ID]  
**Prazo:** [Data]  
**Responsável:** [Nome]

## 38. Registro de mudanças

| ID | Data | Objeto/vínculo | Tipo de mudança | Antes | Depois | Motivo | Impacto | Decisão | Responsável | Versão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MUD-MTR-001 | [Data] | [ID/VNC-ID] | [Criar, alterar, invalidar, substituir ou encerrar] | [Preencher] | [Preencher] | [Preencher] | [IMP-ID] | [DEC-ID] | [Nome] | [Versão] |

### 38.1 Correção simples

Correção factual sem alteração de significado pode utilizar histórico simplificado, desde que não altere objeto, relação, direção, cobertura, estado ou linha de base.

### 38.2 Mudança material

Exige análise de impacto quando alterar:

- objeto;
- relação;
- direção;
- cobertura;
- validação;
- prioridade;
- decisão;
- responsabilidade;
- sensibilidade;
- versão oficial.

## 39. Versionamento e linha de base

### 39.1 Registro das linhas de base

| ID | Versão matriz | Versão arquitetura | Data | Objetos | Vínculos | Requisitos abertos | Condições | Aprovador | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LB-ARQ-001 | [Versão] | [Versão] | [Data] | [N] | [N] | [N/IDs] | [N/IDs] | [Nome/função] | Candidata |

### 39.2 Conteúdo da linha de base

- objetos incluídos;
- vínculos aprovados;
- versões das fontes;
- requisitos abertos;
- coberturas;
- conflitos;
- lacunas;
- condições;
- decisões;
- validações;
- aprovadores.

### 39.3 Substituição

| Objeto/vínculo anterior | Substituto | Relação | Motivo | Decisão | Data |
| --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [substitui/é_substituído_por] | [Preencher] | [DEC-ID] | [Data] |

### 39.4 Linha de base vigente

**ID:** [LB-ARQ-NNN]  
**Data:** [DD/MM/AAAA]  
**Versão da matriz:** [Preencher]  
**Versão da arquitetura:** [Preencher]  
**Local oficial:** [Referência]  
**Aprovação:** [ID]

## 40. Sensibilidade e separação dos registros

### 40.1 Classificação

- pública;
- interna;
- confidencial;
- sensível.

### 40.2 Estrutura possível

| Registro | Conteúdo | Sensibilidade | Acesso | Referência cruzada |
| --- | --- | --- | --- | --- |
| Matriz geral | IDs e relações mínimas | [Nível] | [Papéis] | [Preencher] |
| Fontes restritas | Evidências e dados | [Nível] | [Papéis] | [IDs] |
| Vínculos sensíveis | Relações protegidas | [Nível] | [Papéis] | [Descrição abstrata] |
| Versão do cliente | Recorte autorizado | [Nível] | [Papéis] | [Linha de base] |

### 40.3 Vínculo sensível

| Vínculo | O que a relação revela | Registro geral | Registro restrito | Aprovador |
| --- | --- | --- | --- | --- |
| VNC-___ | [Preencher] | [Descrição mínima] | [Referência] | [Nome/função] |

### 40.4 Minimização

Não inserir transcrições, dados pessoais, mensagens, documentos completos ou especificações extensas quando referência segura for suficiente.

## 41. Controle de acesso

| Ação | Papéis autorizados | Autoridade | Registro | Revisão |
| --- | --- | --- | --- | --- |
| Ler matriz geral | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Ler anexos sensíveis | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Criar objetos | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Criar vínculos | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Aprovar cobertura | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Invalidar vínculo | [Papéis] | [Nome/função] | [Forma] | [Frequência] |
| Exportar | [Papéis] | [Nome/função] | [Forma] | [Frequência] |

### 41.1 Incidente

**Canal:** [Preencher]  
**Responsável:** [Nome]  
**Ação imediata:** [Preencher]  
**Autoridade para suspender acesso:** [Nome/função]

## 42. Participação da inteligência artificial

### 42.1 Usos permitidos

- normalizar identificadores;
- sugerir tipos de relação;
- localizar objetos órfãos;
- detectar referências quebradas;
- identificar duplicações;
- verificar cadeias mínimas;
- resumir cobertura;
- apontar conflitos;
- apoiar análise de impacto;
- comparar versões;
- gerar perguntas de revisão.

### 42.2 Limites

A IA não deve:

- criar origem inexistente;
- declarar atendimento sem critério;
- transformar associação temática em relação causal;
- decidir que objetos são equivalentes;
- alterar IDs;
- apagar histórico;
- decidir prioridade;
- aceitar risco;
- aprovar cobertura;
- substituir validação humana.

### 42.3 Registro

| ID | Sistema/agente | Data | Função | Objetos/vínculos examinados | Dados fornecidos | Saída utilizada | Correções | Revisor humano |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| IA-MTR-001 | [Preencher] | [Data] | [Preencher] | [IDs] | [Categoria] | [Preencher] | [Preencher] | [Nome] |

### 42.4 Saída provisória

| Sugestão | Objeto/vínculo | Razão | Revisor | Resultado | Data |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID/VNC-ID] | [Preencher] | [Nome] | [Aceita, corrigida ou rejeitada] | [Data] |

## 43. Representação estruturada para automação

### 43.1 Objeto

```yaml
id: REQ-001
tipo: requisito
titulo: "[Título]"
origem_oficial: "[Referência]"
estado: aprovado
prioridade: obrigatorio
responsavel: "[Papel humano]"
versao: 1.0
sensibilidade: interna
```

### 43.2 Vínculo

```yaml
id: VNC-001
origem: REQ-001
tipo_origem: requisito
relacao: deriva_de
destino: ACH-003
tipo_destino: achado
cobertura: nao_aplicavel
estado: aprovado
justificativa: "[Razão local]"
validacao: null
responsavel: "[Nome ou papel]"
versao: 1.0
```

### 43.3 Regras

- utilizar vocabulário controlado;
- não reduzir descrições a códigos incompreensíveis;
- preservar equivalência com o registro humano;
- rejeitar IDs inexistentes;
- sinalizar campos obrigatórios ausentes;
- registrar data e versão;
- revisar alterações automáticas materialmente relevantes.

### 43.4 Validações automáticas possíveis

| Regra | Resultado esperado | Responsável pela revisão |
| --- | --- | --- |
| Formato do ID | IDs fora do padrão listados | [Nome] |
| Existência dos objetos | Referências quebradas listadas | [Nome] |
| Relação permitida | Relações inválidas listadas | [Nome] |
| Direção | Inversões possíveis listadas | [Nome] |
| Cadeias mínimas | Lacunas listadas | [Nome] |
| Duplicidade | Objetos/vínculos repetidos listados | [Nome] |
| Linha de base | Versões divergentes listadas | [Nome] |

## 44. Papéis e responsabilidades

| Papel | Pessoa | Responsabilidade | Autoridade | Substituto |
| --- | --- | --- | --- | --- |
| Responsável pela matriz | [Nome] | Integridade e atualização | [Preencher] | [Nome] |
| Responsável pela arquitetura | [Nome] | Coerência metodológica | [Preencher] | [Nome] |
| Responsável pelo catálogo | [Nome] | Objetos de requisito | [Preencher] | [Nome] |
| Responsável dimensional | [Nome] | Objetos e vínculos da dimensão | [Preencher] | [Nome] |
| Responsável pela validação | [Nome] | Evidência de verificação | [Preencher] | [Nome] |
| Responsável pela implantação | [Nome] | Itens e critérios de aceite | [Preencher] | [Nome] |
| Custodiante | [Nome] | Versão, acesso e arquivo | [Preencher] | [Nome] |
| Aprovador | [Nome] | Linha de base e condições | [Preencher] | [Nome] |

### 44.1 Autoridade

Use **P** para propor, **E** para elaborar, **R** para recomendar, **V** para validar, **D** para decidir, **A** para aprovar, **C** para consultar e **I** para informar.

| Ação | Matriz | Arquitetura | Catálogo | Dimensional | Validação | Implantação | Aprovador |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Criar objeto | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Criar vínculo | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aprovar vínculo | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Declarar cobertura | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Validar | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Invalidar vínculo | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |
| Aprovar linha de base | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] | [Código] |

## 45. Ritmo de manutenção

| Gatilho | Atualização necessária | Responsável | Prazo | Revisão |
| --- | --- | --- | --- | --- |
| Requisito criado ou alterado | Objeto e origem | [Nome] | [Prazo] | [Nome] |
| Capacidade formulada | Objeto e vínculo com REQ | [Nome] | [Prazo] | [Nome] |
| Alternativa criada | Objeto e cobertura candidata | [Nome] | [Prazo] | [Nome] |
| Decisão tomada | Vínculos decisórios | [Nome] | [Prazo] | [Nome] |
| Componente desenhado | Objeto, CAP e REQ | [Nome] | [Prazo] | [Nome] |
| Validação concluída | Vínculo e resultado | [Nome] | [Prazo] | [Nome] |
| Implantação preparada | ITM e critério | [Nome] | [Prazo] | [Nome] |
| Mudança material | Impacto e nova versão | [Nome] | Imediato | [Nome] |

### 45.1 Proibição de atualização tardia

Reconstruir a matriz somente no encerramento aumenta o risco de justificar retrospectivamente decisões e perder requisitos esquecidos.

## 46. Revisão antes do PC-2

- [ ] objetos de origem foram importados sem duplicação;
- [ ] requisitos possuem origem;
- [ ] capacidades a preservar estão registradas;
- [ ] riscos e restrições estão vinculados;
- [ ] critérios de desenho estão identificados;
- [ ] lacunas críticas possuem tratamento;
- [ ] IDs e versões estão consistentes;
- [ ] responsáveis estão definidos;
- [ ] vínculos propostos foram revisados no grau necessário;
- [ ] a matriz corresponde ao Catálogo de Requisitos vigente.

### 46.1 Resultado

- [ ] Apta para gerar alternativas.
- [ ] Apta com condições.
- [ ] Requer complementação.
- [ ] Retornar ao catálogo.
- [ ] Retornar ao diagnóstico.

**Condições:** [IDs ou nenhuma]  
**Responsável:** [Nome]  
**Data:** [DD/MM/AAAA]

## 47. Revisão antes do PC-3

- [ ] alternativas estão vinculadas a requisitos;
- [ ] critérios foram aplicados;
- [ ] coberturas candidatas estão visíveis;
- [ ] capacidades preservadas estão relacionadas;
- [ ] riscos e compensações estão registrados;
- [ ] conflitos possuem encaminhamento;
- [ ] alternativas rejeitadas não desapareceram;
- [ ] decisões necessárias estão formuladas;
- [ ] versões comparadas são equivalentes.

### 47.1 Resultado

- [ ] Apta para decidir.
- [ ] Apta com condições.
- [ ] Requer nova alternativa.
- [ ] Requer integração adicional.
- [ ] Requer revisão de critérios ou requisitos.

**Condições:** [IDs ou nenhuma]  
**Responsável:** [Nome]  
**Data:** [DD/MM/AAAA]

## 48. Revisão antes do PC-4

- [ ] requisitos obrigatórios possuem tratamento;
- [ ] capacidades possuem componentes;
- [ ] componentes possuem justificação;
- [ ] interfaces críticas estão registradas;
- [ ] coberturas parciais permanecem visíveis;
- [ ] validações necessárias foram realizadas;
- [ ] resultados contraditórios foram tratados;
- [ ] decisões materiais estão vinculadas;
- [ ] lacunas remanescentes foram aceitas ou bloqueiam aprovação;
- [ ] linha de base candidata está identificada.

### 48.1 Resultado

- [ ] Apta para aprovação.
- [ ] Apta com condições.
- [ ] Requer validação adicional.
- [ ] Requer revisão da arquitetura.
- [ ] Requer nova decisão.

**Condições:** [IDs ou nenhuma]  
**Responsável:** [Nome]  
**Data:** [DD/MM/AAAA]

## 49. Revisão antes do PC-5

- [ ] componentes aprovados possuem destino;
- [ ] itens de implantação estão relacionados;
- [ ] dependências e responsáveis estão definidos;
- [ ] critérios de aceite estão vinculados;
- [ ] versões vigentes estão claras;
- [ ] mudanças abertas foram tratadas;
- [ ] requisitos adiados e condições estão visíveis;
- [ ] riscos de transição estão relacionados;
- [ ] o Módulo 4 consegue reconstruir o desenho.

### 49.1 Resultado

- [ ] Apta para implantação.
- [ ] Apta com condições.
- [ ] Requer complementação do pacote.
- [ ] Requer correção de rastreabilidade.
- [ ] Requer reabertura da arquitetura.

**Condições:** [IDs ou nenhuma]  
**Responsável pelo aceite do Módulo 4:** [Nome]  
**Data:** [DD/MM/AAAA]

## 50. Indicadores de rastreabilidade

### 50.1 Cobertura de requisitos obrigatórios

```text
Requisitos obrigatórios com cobertura completa
------------------------------------------------ × 100
Total de requisitos obrigatórios aprovados
```

### 50.2 Componentes justificados

```text
Componentes com requisito, capacidade, risco ou decisão de origem
--------------------------------------------------------------- × 100
Total de componentes ativos
```

### 50.3 Painel

| Indicador | Resultado | Limite/sinal | Objetos críticos | Ação | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- |
| Requisitos sem tratamento | [N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Requisitos obrigatórios com cobertura completa | [%] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Componentes justificados | [%] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Cobertura de validação | [%/N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Órfãos | [N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Vínculos invalidados | [N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Conflitos abertos | [N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |
| Impactos abertos | [N] | [Preencher] | [IDs] | [Preencher] | [Nome] | [Data] |

### 50.4 Limite dos indicadores

Percentuais elevados não compensam vínculos incorretos, critérios frágeis ou validação insuficiente. Revisão qualitativa permanece obrigatória.

## 51. Critérios de qualidade

| Critério | Pergunta | Resultado | Evidência | Ação |
| --- | --- | --- | --- | --- |
| Completude proporcional | Caminhos críticos estão representados? | [Sim/Parcial/Não] | [Referência] | [Preencher] |
| Correção | Relações representam o projeto real? | [Resultado] | [Referência] | [Preencher] |
| Consistência | IDs, direção, estados e vocabulário são uniformes? | [Resultado] | [Referência] | [Preencher] |
| Bidirecionalidade | É possível avançar e retornar? | [Resultado] | [Referência] | [Preencher] |
| Atualidade | Corresponde às versões vigentes? | [Resultado] | [Referência] | [Preencher] |
| Proporcionalidade | O detalhe possui uso? | [Resultado] | [Referência] | [Preencher] |
| Compreensibilidade | Outra pessoa consegue interpretar? | [Resultado] | [Referência] | [Preencher] |
| Utilidade decisória | Lacunas e impactos apoiam ação? | [Resultado] | [Referência] | [Preencher] |
| Segurança | Dados e relações estão protegidos? | [Resultado] | [Referência] | [Preencher] |
| Revisabilidade | Histórico e impacto podem ser reconstruídos? | [Resultado] | [Referência] | [Preencher] |

## 52. Verificações de consistência

### 52.1 Referências quebradas

| Vínculo | ID inexistente | Lado | Ação | Responsável |
| --- | --- | --- | --- | --- |
| VNC-___ | [ID] | [Origem/Destino] | [Corrigir/criar/invalidar] | [Nome] |

### 52.2 Duplicidades

| Tipo | Registros | Análise | Resultado |
| --- | --- | --- | --- |
| [Objeto/vínculo] | [IDs] | [Preencher] | [Fundir, manter ou corrigir] |

### 52.3 Direções divergentes

| Relação | Forma canônica | Forma encontrada | Vínculos | Ação |
| --- | --- | --- | --- | --- |
| [Preencher] | [Origem → destino] | [Preencher] | [IDs] | [Preencher] |

### 52.4 Versões incompatíveis

| Objeto/vínculo | Versão matriz | Versão oficial | Efeito | Ação |
| --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Versão] | [Preencher] | [Preencher] |

### 52.5 Cobertura sem critério

| Vínculo/requisito | Cobertura declarada | Critério ausente | Ação |
| --- | --- | --- | --- |
| [ID] | [Estado] | [Preencher] | [Reverter para não avaliada/definir critério] |

## 53. Checklist de invariantes

- [ ] nenhum requisito vigente permanece sem origem ou decisão de origem externa;
- [ ] nenhum componente material permanece sem requisito, capacidade, risco ou decisão;
- [ ] todo vínculo possui tipo explícito;
- [ ] a direção das relações é uniforme;
- [ ] atendimento parcial não aparece como completo;
- [ ] identificadores não foram reutilizados;
- [ ] objetos e vínculos retirados preservam histórico;
- [ ] decisões materiais permanecem ligadas às alternativas e aos objetos afetados;
- [ ] obrigatórios e críticos possuem verificação proporcional;
- [ ] mudanças materiais possuem análise de impacto;
- [ ] saídas de IA não constituem evidência nem validação final;
- [ ] a matriz corresponde à versão oficial da arquitetura;
- [ ] o detalhe permanece proporcional ao uso, impacto e risco.

### 53.1 Violações

| Invariante | Objeto/vínculo | Impacto | Correção | Responsável | Prazo |
| --- | --- | --- | --- | --- | --- |
| [Número] | [ID] | [Preencher] | [Preencher] | [Nome] | [Data] |

## 54. Revisões por marco

| Marco | Data | Escopo da revisão | Objetos | Vínculos | Lacunas | Resultado | Responsável | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Aceite da transição | [Data] | Origem e entrada | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Antes das alternativas | [Data] | Requisitos e capacidades | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Antes da decisão | [Data] | Alternativas, critérios e riscos | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Antes da validação | [Data] | Componentes e interfaces | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Antes da aprovação | [Data] | Cobertura e linha de base | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Antes da implantação | [Data] | Destinos, dependências e aceite | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |
| Após mudança material | [Data] | Impacto | [N] | [N] | [N] | [Preencher] | [Nome] | [Link] |

## 55. Versão reduzida para arquitetura focal

### 55.1 Objetos

| ID | Tipo | Título | Fonte | Estado | Responsável |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo] | [Título] | [Referência] | [Estado] | [Nome] |

### 55.2 Vínculos

| Origem | Relação | Destino | Cobertura | Estado | Próxima ação |
| --- | --- | --- | --- | --- | --- |
| ACH-001 | [relação canônica] | REQ-001 | N/A | Aprovado | [Preencher] |
| CAP-001 | responde_a | REQ-001 | [Estado] | Em revisão | [Preencher] |
| CMP-001 | realiza | CAP-001 | [Estado] | Proposto | [Preencher] |
| TST-001 | verifica | CMP-001 | N/A | Planejado | [Preencher] |

### 55.3 Controles mínimos

- [ ] origem dos requisitos;
- [ ] justificação dos componentes;
- [ ] decisão material;
- [ ] cobertura explícita;
- [ ] validação proporcional;
- [ ] lacunas e órfãos;
- [ ] destino de implantação;
- [ ] versão vigente.

## 56. Estrutura ampliada para arquitetura sistêmica

```text
rastreabilidade/
|-- objetos.md
|-- vinculos.md
|-- caminhos-criticos.md
|-- cobertura-de-requisitos.md
|-- cobertura-de-capacidades.md
|-- componentes-e-interfaces.md
|-- alternativas-e-decisoes.md
|-- riscos-restricoes-e-controles.md
|-- validacoes.md
|-- implantacao-e-operacao.md
|-- lacunas-orfaos-e-conflitos.md
|-- analises-de-impacto.md
|-- participacao-da-ia.md
+-- linhas-de-base/
```

### 56.1 Regra de separação

Separar arquivos não deve separar a identidade dos objetos nem criar fontes concorrentes. Todos os recortes precisam indicar versão e linha de base.

### 56.2 Índice

| Registro | Finalidade | Versão | Responsável | Sensibilidade | Referência |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Versão] | [Nome] | [Nível] | [Link] |

## 57. Aprovação da linha de base

### 57.1 Síntese

| Elemento | Registro |
| --- | --- |
| ID da linha de base | LB-ARQ-NNN |
| Versão da matriz | [Versão] |
| Versão da arquitetura | [Versão] |
| Objetos ativos | [N] |
| Vínculos ativos | [N] |
| Requisitos obrigatórios sem cobertura completa | [N/IDs] |
| Componentes órfãos | [N/IDs] |
| Lacunas críticas | [N/IDs] |
| Conflitos abertos | [N/IDs] |
| Condições aceitas | [N/IDs] |
| Impactos abertos | [N/IDs] |

### 57.2 Recomendação

**Responsável pela matriz:** [Nome]  
**Manifestação:** [Aprovar / Aprovar com condições / Não aprovar]  
**Fundamentação:** [Preencher]  
**Data:** [DD/MM/AAAA]

### 57.3 Validação

**Responsável:** [Nome/grupo]  
**Escopo:** [Objetos, vínculos, cobertura ou versões]  
**Resultado:** [Validada / Validada com ressalvas / Não validada]  
**Evidência:** [Referência]  
**Data:** [DD/MM/AAAA]

### 57.4 Aprovação

**Aprovador:** [Nome e função]  
**Resultado:** [Aprovada / Aprovada com condições / Devolvida / Rejeitada]  
**Condições:** [IDs ou nenhuma]  
**Decisão:** [DEC-ID]  
**Data:** [DD/MM/AAAA]

## 58. Teste de reconstrução

Selecione amostra proporcional de:

- requisito obrigatório;
- componente crítico;
- alternativa não selecionada;
- decisão material;
- risco alto;
- validação;
- item de implantação;
- indicador.

### 58.1 Teste regressivo

| Objeto inicial | Caminho até a origem | Completo? | Lacuna | Ação |
| --- | --- | --- | --- | --- |
| [CMP/ITM/IND-ID] | [Sequência] | [Sim/Parcial/Não] | [ID/Nenhuma] | [Preencher] |

### 58.2 Teste progressivo

| Objeto inicial | Caminho até implantação/operação | Completo? | Lacuna | Ação |
| --- | --- | --- | --- | --- |
| [EVD/ACH/REQ-ID] | [Sequência] | [Sim/Parcial/Não] | [ID/Nenhuma] | [Preencher] |

### 58.3 Resultado

- [ ] caminhos podem ser reconstruídos sem memória da equipe;
- [ ] fontes oficiais foram localizadas;
- [ ] tipos de relação são compreensíveis;
- [ ] coberturas correspondem aos critérios;
- [ ] decisões e validações são localizáveis;
- [ ] versões são consistentes;
- [ ] lacunas foram registradas.

## 59. Aprendizagem da rastreabilidade

| Pergunta | Registro |
| --- | --- |
| Que classes de objeto foram úteis? | [Preencher] |
| Que classes não produziram valor? | [Preencher] |
| Que vínculos foram difíceis de definir? | [Preencher] |
| Que órfãos apareceram com frequência? | [Preencher] |
| Que mudanças causaram maior impacto? | [Preencher] |
| Que visões apoiaram decisões reais? | [Preencher] |
| Que detalhe foi excessivo? | [Preencher] |
| Que automações ajudaram? | [Preencher] |
| Que erros de IA foram encontrados? | [Preencher] |
| Que vocabulário precisa mudar? | [Preencher] |
| Que padrão deve ser reutilizado? | [Preencher] |

### 59.1 Destino do aprendizado

| Aprendizado | Projeto de origem | Aplicação futura | Responsável | Decisão/atualização |
| --- | --- | --- | --- | --- |
| APD-___ | ARQ-___ | [Método, template, ferramenta ou novo projeto] | [Nome] | [ID] |

## 60. Síntese executiva

| Elemento | Síntese |
| --- | --- |
| Arquitetura | [ID e título] |
| Versão da matriz | [Preencher] |
| Linha de base | [ID/estado] |
| Objetos | [N ativos / N históricos] |
| Vínculos | [N ativos / N históricos] |
| Cobertura de obrigatórios | [Resultado] |
| Principal requisito sem tratamento | [ID] |
| Principal componente órfão | [ID/Nenhum] |
| Principal conflito | [ID/Nenhum] |
| Principal lacuna | [ID/Nenhuma] |
| Validações pendentes | [IDs] |
| Itens sem destino de implantação | [IDs] |
| Impactos abertos | [IDs] |
| Próximo controle | [PC e data] |
| Responsável | [Nome] |

## 61. Controle de versões

| Versão | Data | Estado | Alteração | Motivo | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Em construção | Criação inicial | Início da rastreabilidade | [Nome] | N/A |
| 1.0 | [DD/MM/AAAA] | Consolidada | Linha de base | [PC/marco] | [Nome] | [Referência] |

### 61.1 Controle dos registros

| Registro | Versão | Linha de base | Data | Responsável |
| --- | --- | --- | --- | --- |
| Objetos | [Versão] | [LB-ID] | [Data] | [Nome] |
| Vínculos | [Versão] | [LB-ID] | [Data] | [Nome] |
| Visões derivadas | [Versão] | [LB-ID] | [Data] | [Nome] |

## 62. Critérios de conclusão

- [ ] objetos relevantes possuem IDs estáveis;
- [ ] documentos oficiais estão referenciados;
- [ ] requisitos possuem origem;
- [ ] capacidades respondem a requisitos;
- [ ] componentes possuem justificação;
- [ ] vínculos possuem significado e direção consistente;
- [ ] coberturas foram avaliadas por critério;
- [ ] atendimentos parciais permanecem visíveis;
- [ ] alternativas e decisões permanecem localizáveis;
- [ ] riscos, restrições e controles estão relacionados;
- [ ] interfaces críticas estão representadas;
- [ ] validações necessárias estão vinculadas;
- [ ] lacunas, órfãos e conflitos foram tratados;
- [ ] componentes aprovados possuem destino;
- [ ] mudanças materiais receberam análise de impacto;
- [ ] linha de base está identificada;
- [ ] sensibilidade e acesso foram tratados;
- [ ] participação da IA foi registrada;
- [ ] Módulo 4 consegue utilizar a matriz;
- [ ] teste de reconstrução foi concluído.

### 62.1 Resultado final

- [ ] Consolidada.
- [ ] Consolidada com limitações.
- [ ] Aguardando validação.
- [ ] Requer complementação.
- [ ] Reaberta.
- [ ] Substituída.
- [ ] Encerrada.

## 63. Regra de encerramento

A matriz pode encerrar seu ciclo arquitetural quando a linha de base estiver aprovada, os componentes possuírem destino de implantação e as lacunas remanescentes tiverem decisão.

Ela não deixa de existir depois do Módulo 3. A implantação, a operação e a aprendizagem podem:

- confirmar vínculos;
- invalidar premissas;
- alterar cobertura;
- revelar novos riscos;
- exigir reabertura;
- gerar aprendizado metodológico.

Toda atualização posterior deve preservar a linha de base anterior e permitir reconstruir por que o sistema mudou.

---

## Registro final

**Estado da matriz:** [Preencher]  
**Versão vigente:** [Preencher]  
**Linha de base:** [ID]  
**Data da última revisão:** [DD/MM/AAAA]  
**Responsável:** [Nome]  
**Resultado no ponto de controle:** [Preencher]  
**Próximo artefato:** `arquitetura-integrada.md`  
**Observações:** [Preencher]
