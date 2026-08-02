# Matriz de Rastreabilidade da Arquitetura

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Tipo:** Método de conexão, cobertura e rastreabilidade arquitetural  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data de criação:** 02/08/2026

**Documentos relacionados:**

- Guia do Módulo 3;
- Fundamentos da Arquitetura Organizacional;
- Protocolo de Arquitetura Organizacional;
- Transição para Arquitetura Organizacional;
- Matriz de Evidências;
- Protocolo de Decisão;
- registros de decisão;
- template da Matriz de Rastreabilidade.

## 1. Finalidade

A Matriz de Rastreabilidade da Arquitetura é o mecanismo utilizado pelo Estúdio LICHTARA para tornar reconstruível o percurso entre a realidade diagnosticada e a configuração organizacional futura.

Ela relaciona:

- fontes;
- evidências;
- achados;
- problemas;
- capacidades existentes;
- riscos;
- restrições;
- dependências;
- requisitos;
- capacidades futuras;
- critérios de desenho;
- alternativas;
- decisões;
- componentes;
- interfaces;
- validações;
- itens de implantação;
- indicadores;
- aprendizados.

Sua função é impedir que a arquitetura seja produzida apenas a partir de:

- memória;
- preferência da pessoa que desenha;
- ferramenta previamente escolhida;
- modelo reproduzido de outro contexto;
- requisito sem origem;
- componente sem justificativa;
- decisão sem alternativas;
- validação sem objeto definido;
- resumo produzido por inteligência artificial;
- alteração cujo impacto não foi examinado.

A matriz deve permitir responder:

> De onde veio este elemento, por que ele existe, o que atende, quem o autorizou, como foi validado e que parte da implantação ou da operação dependerá dele?

## 2. Posição da matriz no Sistema Operacional

A matriz está localizada entre o diagnóstico, a arquitetura, a implantação e a operação.

O fluxo ampliado é:

```text
Fonte
  ↓
Evidência
  ↓
Achado diagnóstico
  ↓
Problema, capacidade, risco ou restrição
  ↓
Requisito
  ↓
Capacidade futura
  ↓
Alternativas
  ↓
Decisão
  ↓
Componentes e interfaces
  ↓
Validação
  ↓
Item de implantação
  ↓
Indicador operacional
  ↓
Aprendizado
```

A matriz recebe referências do Módulo 2, organiza as relações produzidas no Módulo 3 e prepara continuidade para os Módulos 4, 5 e 6.

Ela não substitui:

- a Matriz de Evidências;
- a Transição para Arquitetura;
- o catálogo de requisitos;
- os mapas dimensionais;
- os registros de decisão;
- a arquitetura integrada;
- os registros de validação;
- o plano de implantação;
- os indicadores operacionais;
- os documentos originais.

Ela funciona como camada de conexão entre esses materiais.

## 3. O que a matriz deve permitir

Uma matriz adequadamente mantida deve permitir que outra pessoa compreenda:

1. qual diagnóstico originou a arquitetura;
2. que achados sustentam cada requisito;
3. que requisitos não possuem origem diagnóstica e por quê;
4. que capacidades precisam ser preservadas ou desenvolvidas;
5. que alternativas foram consideradas;
6. que critérios orientaram a escolha;
7. que decisão autorizou a arquitetura;
8. que componentes atendem cada requisito;
9. que requisitos possuem atendimento parcial;
10. que componentes não possuem justificativa suficiente;
11. que interfaces conectam componentes;
12. que riscos, restrições e dependências afetam o desenho;
13. que validações foram realizadas;
14. que lacunas permanecem abertas;
15. que elementos foram adiados, rejeitados ou substituídos;
16. que itens deverão ser implantados;
17. como o funcionamento será observado;
18. que objetos serão afetados por uma mudança;
19. qual versão constitui a linha de base;
20. que aprendizado retornou ao sistema.

## 4. Tese da rastreabilidade

Rastreabilidade é a capacidade de reconstruir relações de origem, justificação, atendimento, decisão, verificação e continuidade.

Ela não consiste apenas em inserir identificadores em documentos.

Uma referência como `REQ-003` somente possui valor quando permite localizar:

- a declaração do requisito;
- sua origem;
- sua prioridade;
- os componentes que o atendem;
- a decisão relacionada;
- a forma de validação;
- seu estado atual.

A rastreabilidade é completa quando permite dois movimentos.

### 4.1 Rastreabilidade regressiva

Parte de um componente, decisão ou item de implantação e retorna às razões que o justificam.

Pergunta:

> Por que este elemento existe?

### 4.2 Rastreabilidade progressiva

Parte de uma evidência, achado ou requisito e acompanha seus efeitos sobre desenho, decisão, implantação e operação.

Pergunta:

> O que aconteceu com esta necessidade?

Uma arquitetura pode possuir rastreabilidade regressiva e ainda perder requisitos que nunca chegaram ao desenho. Por isso, os dois movimentos são necessários.

## 5. Princípios da matriz

### 5.1 O vínculo precisa possuir significado

Relacionar dois identificadores sem declarar a natureza da relação produz ambiguidade.

`REQ-001 → CMP-004` pode significar:

- atendimento completo;
- atendimento parcial;
- dependência;
- conflito;
- simples associação temática.

Cada vínculo deve indicar que relação existe.

### 5.2 Objetos e vínculos devem permanecer separados

Um objeto possui identidade, descrição, estado e origem.

Um vínculo declara como dois objetos se relacionam.

Essa separação permite representar relações muitos-para-muitos sem duplicar conteúdo.

### 5.3 Um vínculo não demonstra automaticamente atendimento

Relacionar requisito e componente não comprova que o requisito foi atendido.

O atendimento precisa indicar:

- grau de cobertura;
- justificativa;
- critério de atendimento;
- validação;
- estado.

### 5.4 Identificadores devem permanecer estáveis

Descrições podem ser corrigidas, detalhadas ou substituídas. O identificador não deve ser reutilizado para outro objeto.

### 5.5 Elementos retirados não devem desaparecer

Requisitos rejeitados, alternativas descartadas, componentes substituídos e vínculos invalidados devem permanecer registrados com motivo, data e decisão.

### 5.6 A matriz referencia a fonte oficial

Conteúdo extenso não deve ser copiado quando uma referência segura e localizável for suficiente.

### 5.7 Cobertura parcial deve permanecer explícita

Atendimento parcial não deve ser apresentado como completo para produzir aparência de prontidão.

### 5.8 Divergências e conflitos devem permanecer visíveis

Requisitos incompatíveis, decisões contestadas e validações divergentes precisam ser registrados até que recebam tratamento.

### 5.9 A profundidade deve ser proporcional

Arquiteturas focais podem utilizar uma versão reduzida. Arquiteturas sistêmicas exigem cobertura, impacto e versionamento ampliados.

### 5.10 A matriz deve apoiar decisão

O registro deve tornar lacunas, impactos e escolhas mais claros. Detalhamento sem uso reconhecível deve ser reduzido.

## 6. Estrutura lógica

A matriz possui duas camadas principais e visões derivadas.

### 6.1 Camada 1 — Registro de objetos

Armazena os elementos rastreáveis do projeto.

Exemplos:

- `ACH-003` — achado diagnóstico;
- `REQ-007` — requisito;
- `CAP-004` — capacidade;
- `ALT-002` — alternativa;
- `DEC-2026-005` — decisão;
- `CMP-011` — componente;
- `VAL-003` — validação.

### 6.2 Camada 2 — Registro de vínculos

Armazena relações entre objetos.

Exemplos:

- `REQ-007 deriva_de ACH-003`;
- `CAP-004 responde_a REQ-007`;
- `CMP-011 realiza CAP-004`;
- `CMP-011 atende_parcialmente REQ-007`;
- `VAL-003 verifica CMP-011`.

### 6.3 Visões derivadas

São relatórios ou recortes produzidos a partir das duas camadas.

Podem incluir:

- cobertura de requisitos;
- cobertura de capacidades;
- componentes sem justificativa;
- requisitos sem tratamento;
- decisões sem validação;
- riscos sem controle;
- impactos de mudança;
- prontidão para aprovação;
- prontidão para implantação.

## 7. Unidades de registro

A matriz trabalha com diferentes unidades.

### 7.1 Objeto rastreável

Elemento identificado que participa do percurso arquitetural.

### 7.2 Vínculo

Relação dirigida ou simétrica entre dois objetos.

### 7.3 Caminho

Sequência de vínculos que permite reconstruir uma origem ou consequência.

Exemplo:

```text
ACH-003 → REQ-007 → CAP-004 → CMP-011 → VAL-003
```

### 7.4 Cobertura

Grau em que um objeto recebe tratamento por outro.

### 7.5 Lacuna de rastreabilidade

Ausência de vínculo necessário para justificar, atender, validar ou encaminhar um objeto.

### 7.6 Órfão

Objeto que deveria possuir relação e permanece isolado.

Exemplos:

- requisito sem achado, exigência ou decisão de origem;
- componente sem requisito ou decisão;
- risco sem tratamento;
- item de implantação sem componente;
- indicador sem capacidade ou decisão operacional.

### 7.7 Linha de base

Conjunto versionado de objetos e vínculos aprovado como referência.

### 7.8 Impacto

Conjunto de objetos e relações potencialmente afetados por alteração.

## 8. Classes de objetos rastreáveis

As classes estão organizadas por posição no ciclo.

### 8.1 Objetos de origem diagnóstica

| Prefixo | Objeto | Função |
| --- | --- | --- |
| `ENT` | Entrevista | Fonte humana registrada no diagnóstico |
| `OBS` | Observação | Fonte produzida por observação diagnóstica |
| `DOC` | Documento | Fonte documental |
| `DAD` | Conjunto de dados | Fonte quantitativa ou estruturada |
| `SIS` | Sistema | Registro originado de sistema ou ferramenta |
| `EXT` | Material externo | Fonte externa utilizada na investigação |
| `EVD` | Evidência | Informação que sustenta ou questiona um achado |
| `ACH` | Achado | Conclusão diagnóstica estruturada |
| `PRB` | Problema | Condição que precisa ser tratada |
| `CAP` | Capacidade | Capacidade existente, preservada ou futura |
| `RSC` | Risco | Possibilidade de impacto relevante |
| `RES` | Restrição | Limite imposto ao desenho |
| `DEP` | Dependência | Condição necessária |
| `LAC` | Lacuna | Informação ou condição ausente |
| `QAB` | Questão aberta | Pergunta ainda não resolvida |

Os identificadores existentes no Módulo 2 devem ser reutilizados. A matriz não deve criar novo ID para representar o mesmo objeto.

### 8.2 Objetos de arquitetura

| Prefixo | Objeto | Função |
| --- | --- | --- |
| `ARQ` | Projeto de arquitetura | Unidade principal do projeto |
| `REQ` | Requisito | Condição que a arquitetura deve atender |
| `CAP` | Capacidade | Aquilo que a organização precisa conseguir realizar |
| `CRT` | Critério de desenho | Referência para criar ou comparar alternativas |
| `PRE` | Premissa | Condição provisoriamente assumida |
| `ALT` | Alternativa | Configuração possível |
| `DEC` | Decisão | Escolha formal registrada no Módulo 1 |
| `CMP` | Componente | Elemento da arquitetura |
| `INT` | Interface | Ponto de contato ou transferência |
| `CTL` | Controle | Mecanismo de prevenção, detecção ou correção |

### 8.3 Objetos de validação e continuidade

| Prefixo | Objeto | Função |
| --- | --- | --- |
| `VAL` | Validação | Verificação realizada sobre objeto ou caminho |
| `TST` | Teste | Caso, simulação, protótipo ou verificação específica |
| `ITM` | Item de implantação | Elemento que o Módulo 4 deverá implantar |
| `IND` | Indicador | Representação usada para observar funcionamento |
| `APD` | Aprendizado | Conhecimento produzido pelo ciclo |

### 8.4 Prefixos locais e conflitos

Quando um prefixo já estiver em uso no projeto, deve-se:

- preservar o identificador original;
- registrar o tipo completo do objeto;
- utilizar identificador qualificado quando necessário;
- evitar criar sinônimos para o mesmo elemento.

Exemplo qualificado:

```text
ARQ-2026-001-REQ-007
```

## 9. Natureza das capacidades

O prefixo `CAP` pode representar capacidades em diferentes condições.

Cada capacidade deve possuir natureza explícita:

- existente;
- preservar;
- fortalecer;
- desenvolver;
- substituir;
- futura;
- descontinuar.

Exemplo:

| ID | Capacidade | Natureza | Estado |
| --- | --- | --- | --- |
| `CAP-001` | Comunicar conhecimento oralmente | Preservar | Validada no diagnóstico |
| `CAP-002` | Acompanhar conteúdos por estado | Desenvolver | Em desenho |

Isso evita tratar uma capacidade existente e uma capacidade futura como objetos equivalentes apenas porque utilizam o mesmo prefixo.

## 10. Registro de objetos

Cada objeto deve possuir, de forma proporcional:

| Campo | Função |
| --- | --- |
| ID | Identificar o objeto |
| Tipo | Declarar sua classe |
| Título | Nome curto e compreensível |
| Descrição | Registrar sua condição ou função |
| Projeto | Vincular ao diagnóstico, transição ou arquitetura |
| Origem oficial | Indicar documento ou registro de referência |
| Estado | Mostrar condição atual |
| Prioridade | Indicar importância ou momento |
| Responsável | Definir quem responde pelo registro |
| Versão | Identificar a formulação vigente |
| Sensibilidade | Definir proteção necessária |
| Data de criação | Situar temporalmente |
| Data de revisão | Indicar última atualização |
| Observações | Preservar limites ou contexto |

### 10.1 Modelo do registro de objetos

| ID | Tipo | Título | Origem oficial | Estado | Prioridade | Responsável | Versão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `REQ-001` | Requisito | Acompanhamento compartilhado | Transição | Aprovado | Obrigatório | Responsável pela arquitetura | 1.0 |
| `CAP-002` | Capacidade | Acompanhar conteúdos | Catálogo de capacidades | Em desenho | Alta | Arquiteta | 0.2 |
| `CMP-004` | Componente | Quadro editorial | Arquitetura integrada | Proposto | Alta | Arquiteta | 0.1 |

### 10.2 Regra de conteúdo

O registro de objetos deve conter descrição suficiente para reconhecer o elemento. Detalhamento extenso permanece no documento oficial correspondente.

## 11. Registro de vínculos

Cada linha do registro representa uma relação entre dois objetos.

| Campo | Função |
| --- | --- |
| ID do vínculo | Identificar a relação quando necessário |
| Objeto de origem | Indicar onde a relação começa |
| Tipo da origem | Facilitar verificação |
| Relação | Declarar o significado do vínculo |
| Objeto de destino | Indicar onde a relação chega |
| Tipo do destino | Facilitar verificação |
| Cobertura | Registrar grau de atendimento quando aplicável |
| Justificativa | Explicar por que a relação existe |
| Estado | Indicar condição do vínculo |
| Validação | Relacionar verificação |
| Responsável | Definir quem registrou ou aprovou |
| Versão | Relacionar à linha de base |

### 11.1 Modelo do registro de vínculos

| Origem | Relação | Destino | Cobertura | Estado | Justificativa |
| --- | --- | --- | --- | --- | --- |
| `REQ-001` | deriva_de | `ACH-003` | Não aplicável | Aprovado | O achado demonstra perda de continuidade |
| `CAP-002` | responde_a | `REQ-001` | Completa | Em revisão | A capacidade permite acompanhar demandas |
| `CMP-004` | realiza | `CAP-002` | Parcial | Proposto | O quadro sustenta estados e próximas ações |
| `VAL-002` | verifica | `CMP-004` | Não aplicável | Planejado | Simulação do fluxo editorial |

### 11.2 Identificação dos vínculos

Em projetos pequenos, o vínculo pode ser identificado pela combinação origem–relação–destino.

Quando for necessário versionar ou referenciar relações individualmente, utilizar:

```text
VNC-NNN
```

O identificador deve ser único dentro da arquitetura.

## 12. Vocabulário controlado de relações

O vocabulário reduz ambiguidades e melhora verificações automáticas.

### 12.1 Relações de origem e justificação

| Relação | Significado |
| --- | --- |
| `deriva_de` | O objeto foi formulado a partir de outro |
| `é_justificado_por` | Outro objeto fornece razão para sua existência |
| `formaliza` | Transforma necessidade ou decisão em registro explícito |
| `responde_a` | Procura tratar uma necessidade, problema ou requisito |
| `preserva` | Protege capacidade ou elemento existente |
| `trata` | Atua sobre problema, risco, lacuna ou restrição |

### 12.2 Relações de atendimento

| Relação | Significado |
| --- | --- |
| `atende` | Produz cobertura completa conforme critério vigente |
| `atende_parcialmente` | Produz cobertura incompleta ou condicionada |
| `não_atende` | Foi avaliado e não produz cobertura suficiente |
| `realiza` | Componente torna uma capacidade operacionalmente possível |
| `implementa` | Item de implantação materializa componente ou decisão |
| `monitora` | Indicador observa capacidade, requisito ou risco |

### 12.3 Relações estruturais

| Relação | Significado |
| --- | --- |
| `depende_de` | Necessita de outro objeto para funcionar |
| `é_restringido_por` | Possui alternativas limitadas por restrição |
| `é_composto_por` | Agrega objetos menores |
| `é_conectado_por` | Possui passagem definida por interface |
| `transfere_para` | Move trabalho, informação, dado ou responsabilidade |
| `controla` | Reduz, detecta ou corrige risco ou desvio |
| `conflita_com` | Possui incompatibilidade ou tensão material |

### 12.4 Relações decisórias e temporais

| Relação | Significado |
| --- | --- |
| `é_selecionado_por` | Alternativa ou componente foi escolhido por decisão |
| `é_rejeitado_por` | Objeto foi excluído por decisão |
| `é_adiado_por` | Atendimento ou implantação foi postergado |
| `substitui` | Nova versão ou objeto assume função anterior |
| `é_substituído_por` | Objeto deixa de ser referência vigente |
| `é_reaberto_por` | Nova condição exige retomada |

### 12.5 Relações de verificação e aprendizagem

| Relação | Significado |
| --- | --- |
| `é_verificado_por` | Objeto recebeu validação ou teste |
| `é_contradito_por` | Evidência, validação ou resultado questiona o objeto |
| `gera` | Produz outro objeto, resultado ou aprendizado |
| `gera_aprendizado` | Experiência retorna ao sistema como conhecimento |

### 12.6 Direção da relação

A direção deve permanecer consistente.

Exemplo recomendado:

```text
CMP-004 atende REQ-001
```

Evitar alternar entre:

```text
REQ-001 é_atendido_por CMP-004
CMP-004 atende REQ-001
```

Uma única direção facilita filtros e análises.

## 13. Estados dos vínculos

Um vínculo pode possuir os seguintes estados:

- proposto;
- em revisão;
- aprovado;
- aprovado com condição;
- validado;
- suspenso;
- rejeitado;
- invalidado;
- substituído;
- encerrado.

### 13.1 Vínculo proposto

Relação identificada durante o desenho e ainda não revisada.

### 13.2 Vínculo aprovado

Relação aceita para compor a linha de base.

### 13.3 Vínculo validado

Relação confrontada com critério, teste, usuário, especialista ou resultado.

### 13.4 Vínculo invalidado

Relação anteriormente aceita que deixou de possuir sustentação.

Vínculos invalidados não devem ser apagados. A razão e a substituição, quando houver, devem permanecer registradas.

## 14. Cobertura

Cobertura expressa o grau em que um objeto recebe tratamento.

### 14.1 Escala de cobertura

| Estado | Significado |
| --- | --- |
| Não avaliada | A relação ainda não foi examinada |
| Sem tratamento | Nenhum objeto responde adequadamente |
| Candidata | Existe solução possível ainda não consolidada |
| Parcial | Parte da condição foi atendida |
| Completa | O critério vigente foi atendido |
| Completa com condição | O atendimento depende de condição explícita |
| Adiada | O atendimento foi postergado por decisão |
| Rejeitada | A condição não será atendida, com decisão registrada |
| Não aplicável | A ideia de cobertura não se aplica ao vínculo |

### 14.2 Cobertura não é contagem

Um requisito pode possuir cinco componentes e continuar sem atendimento completo.

Outro pode ser atendido por um único componente.

A cobertura deve ser avaliada pelo critério de atendimento, não pela quantidade de vínculos.

### 14.3 Cobertura compartilhada

Um requisito pode ser atendido pelo conjunto de componentes.

Exemplo:

```text
REQ-001 exige responsável, estado, próxima ação e histórico.

CMP-001 define o papel responsável.
CMP-002 define os estados.
CMP-003 registra próxima ação.
CMP-004 preserva histórico.
```

Nesse caso, cada vínculo pode ser parcial e o conjunto produzir cobertura completa.

### 14.4 Cobertura condicionada

Quando o atendimento depender de treinamento, ferramenta, volume, especialista ou decisão futura, a condição deve permanecer explícita.

## 15. Cadeias mínimas obrigatórias

Nem todo projeto utilizará o percurso ampliado completo. Algumas cadeias mínimas devem existir.

### 15.1 Cadeia de justificação

```text
ACH, exigência externa ou DEC
          ↓
         REQ
```

Todo requisito precisa possuir origem.

### 15.2 Cadeia de desenho

```text
REQ → CAP → CMP
```

Todo requisito material precisa chegar a capacidade e componente, ou receber decisão de adiamento, rejeição ou não intervenção.

### 15.3 Cadeia de decisão

```text
ALT → DEC → arquitetura selecionada
```

Toda escolha material deve permitir localizar alternativas e decisão.

### 15.4 Cadeia de validação

```text
REQ ou CMP → VAL/TST
```

Requisitos obrigatórios e componentes de maior risco precisam possuir verificação.

### 15.5 Cadeia de implantação

```text
CMP → ITM
```

Todo componente aprovado deve ser implantado, já existente, adiado, rejeitado ou considerado não aplicável.

### 15.6 Cadeia operacional

```text
CAP, REQ ou RSC → IND
```

Capacidades, requisitos ou riscos que exigem acompanhamento devem possuir indicador ou outra forma de observação.

## 16. Matriz principal

A matriz principal pode ser representada pelo registro de vínculos.

| Origem | Tipo | Relação | Destino | Tipo | Cobertura | Estado | Validação | Observação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `ACH-001` | Achado | formaliza | `PRB-001` | Problema | N/A | Aprovado | Validação diagnóstica | Perda de continuidade |
| `REQ-001` | Requisito | deriva_de | `PRB-001` | Problema | N/A | Aprovado | Revisão interna | Registro compartilhado necessário |
| `CAP-002` | Capacidade | responde_a | `REQ-001` | Requisito | Completa | Em revisão | `VAL-001` | Acompanhar conteúdos |
| `CMP-003` | Componente | realiza | `CAP-002` | Capacidade | Parcial | Proposto | `TST-001` | Quadro editorial |
| `ITM-004` | Implantação | implementa | `CMP-003` | Componente | N/A | Planejado | Aceite do Módulo 4 | Configurar base |

### 16.1 Uma linha representa um vínculo

Quando um objeto se relacionar a três outros, devem existir três linhas.

### 16.2 Descrições permanecem fora da matriz principal

O registro de objetos contém títulos e descrições. A matriz principal prioriza relações e estados.

### 16.3 Colunas opcionais

Podem ser adicionadas:

- prioridade;
- risco;
- responsável;
- data;
- versão;
- sensibilidade;
- condição;
- prazo;
- documento oficial.

## 17. Modelo reduzido

Para arquiteturas focais, utilizar:

| Origem | Relação | Destino | Estado | Próximo passo |
| --- | --- | --- | --- | --- |
| `ACH-001` | origina | `REQ-001` | Aprovado | Desenhar capacidade |
| `CAP-001` | responde_a | `REQ-001` | Em revisão | Validar formulação |
| `CMP-001` | realiza | `CAP-001` | Proposto | Simular fluxo |

A versão reduzida não elimina:

- origem dos requisitos;
- justificação dos componentes;
- registro de decisões materiais;
- validação;
- tratamento de lacunas.

## 18. Visão de cobertura dos requisitos

Essa visão permite acompanhar o destino de cada requisito.

| Requisito | Prioridade | Origem | Capacidades | Componentes | Cobertura | Validação | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `REQ-001` | Obrigatório | `ACH-003` | `CAP-002` | `CMP-003`, `CMP-004` | Parcial | Planejada | Em desenho |

### 18.1 Perguntas de controle

- Todo requisito possui origem?
- Todo requisito obrigatório possui capacidade relacionada?
- Existe componente responsável pelo atendimento?
- O critério de atendimento está definido?
- A cobertura foi validada?
- Requisitos adiados possuem decisão?
- Requisitos rejeitados possuem justificativa e autoridade?

### 18.2 Requisito sem origem diagnóstica

Pode surgir por:

- exigência jurídica;
- exigência técnica;
- decisão do cliente;
- orientação de especialista;
- risco descoberto;
- aprendizagem do desenho;
- condição de implantação.

A nova origem deve ser identificada e aprovada.

## 19. Visão de cobertura das capacidades

Essa visão verifica se as capacidades futuras possuem condições de funcionamento.

| Capacidade | Natureza | Requisitos | Componentes | Responsável | Manifestação observável | Cobertura |
| --- | --- | --- | --- | --- | --- | --- |
| `CAP-002` | Desenvolver | `REQ-001`, `REQ-004` | `CMP-003`, `CMP-005` | Papel editorial | Conteúdos possuem estado e próxima ação | Parcial |

### 19.1 Capacidade existente a preservar

Deve ser vinculada aos componentes que a protegem.

### 19.2 Capacidade futura

Deve possuir:

- requisito;
- condições de funcionamento;
- componentes;
- responsável;
- manifestação observável;
- validação;
- item de implantação.

### 19.3 Capacidade sem componente

Pode indicar:

- desenho incompleto;
- capacidade formulada em nível excessivamente abstrato;
- componente ainda não registrado;
- decisão de adiamento;
- dependência externa;
- capacidade já existente que não exige mudança.

## 20. Visão de componentes

Essa visão verifica por que cada componente existe e o que será necessário para sustentá-lo.

| Componente | Tipo | Capacidades | Requisitos | Dependências | Riscos | Manutenção | Validação | Implantação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `CMP-003` | Processo | `CAP-002` | `REQ-001` | `DEP-002` | `RSC-004` | Semanal | `TST-001` | `ITM-004` |

### 20.1 Componente órfão

Componente sem requisito, capacidade, risco ou decisão de origem deve ser investigado.

Resultados possíveis:

- vincular à origem correta;
- formalizar novo requisito;
- registrar decisão;
- fundir com outro componente;
- retirar do desenho;
- manter como elemento opcional, com justificativa.

### 20.2 Componente excessivamente conectado

Um componente ligado a muitas capacidades críticas pode constituir:

- núcleo arquitetural;
- ponto único de falha;
- dependência excessiva;
- objeto prioritário de validação;
- candidato a decomposição.

## 21. Visão de alternativas e decisões

Essa visão preserva o percurso de escolha.

| Alternativa | Requisitos atendidos | Critérios | Riscos | Decisão | Resultado |
| --- | --- | --- | --- | --- | --- |
| `ALT-001` | `REQ-001`, `REQ-003` | Simplicidade alta | Dependência manual | `DEC-2026-004` | Não selecionada |
| `ALT-002` | `REQ-001` a `REQ-005` | Integração moderada | Preparação inicial | `DEC-2026-004` | Selecionada |

### 21.1 Alternativa não selecionada

Deve permanecer registrada com:

- requisitos atendidos;
- critérios;
- benefícios;
- limitações;
- motivo da não seleção;
- decisão.

### 21.2 Combinação de alternativas

Quando a decisão combinar elementos, os componentes resultantes devem indicar de quais alternativas derivam.

### 21.3 Decisão sem alternativas

Pode ser legítima quando:

- existe exigência obrigatória;
- apenas uma opção é tecnicamente possível;
- a decisão já foi tomada por autoridade competente;
- o objeto é local e reversível.

A justificativa deve permanecer registrada.

## 22. Visão de riscos, restrições e controles

| Objeto | Tipo | Afeta | Tratamento | Controle | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `RSC-004` | Risco | `CMP-003` | Reduzir | `CTL-002` | Responsável pelo processo | Em revisão |
| `RES-002` | Restrição | `ALT-003` | Respeitar | N/A | Patrocinador | Aprovada |

### 22.1 Risco sem tratamento

Pode ser:

- aceito;
- reduzido;
- evitado;
- transferido;
- monitorado;
- encaminhado a especialista.

O resultado precisa possuir decisão ou responsável.

### 22.2 Restrição sem efeito visível

Quando uma restrição não altera alternativa, componente, sequência ou decisão, deve-se verificar se:

- foi registrada de forma genérica;
- perdeu validade;
- seu impacto ainda não foi analisado;
- não pertence ao escopo.

## 23. Visão de validação

| Validação ou teste | Objeto verificado | Critério | Método | Resultado | Pendência | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| `TST-001` | `CMP-003` | Quatro conteúdos percorrem o fluxo | Simulação | Parcial | Ajustar exceção | Arquiteta |
| `VAL-002` | `REQ-001` | Estado e próxima ação localizáveis | Usuária | Aprovado | Nenhuma | Cliente |

### 23.1 Cobertura de validação

Devem possuir validação proporcional:

- requisitos obrigatórios;
- componentes críticos;
- interfaces de alto risco;
- funções de IA;
- controles;
- premissas de alto impacto;
- elementos irreversíveis;
- condições de continuidade.

### 23.2 Resultado contraditório

Quando uma validação contradizer um objeto aprovado, registrar vínculo `é_contradito_por` e avaliar:

- correção;
- revisão;
- nova alternativa;
- mudança de requisito;
- reabertura do diagnóstico;
- aceitação de limitação.

## 24. Visão de implantação

Essa visão conecta arquitetura aprovada ao Módulo 4.

| Item de implantação | Componente | Requisito | Dependências | Critério de aceite | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `ITM-004` | `CMP-003` | `REQ-001` | `DEP-002` | Fluxo configurado e testado | Responsável pela implantação | Planejado |

### 24.1 Destino de cada componente

Todo componente aprovado deve possuir um destino:

- já existe e será preservado;
- será criado;
- será configurado;
- será alterado;
- será migrado;
- será treinado;
- será testado;
- será adiado;
- será substituído;
- será desativado;
- não exige implantação.

### 24.2 Aceite do Módulo 4

O responsável pela implantação deve confirmar:

- componentes localizáveis;
- sequência compreensível;
- dependências explícitas;
- critérios de aceite;
- decisões pendentes;
- restrições;
- riscos;
- versões vigentes.

## 25. Visão operacional e aprendizagem

A rastreabilidade pode continuar depois da implantação.

| Indicador | Observa | Fonte | Decisão apoiada | Frequência | Responsável |
| --- | --- | --- | --- | --- | --- |
| `IND-001` | `CAP-002` | Quadro editorial | Ajustar fluxo | Semanal | Responsável editorial |

Resultados operacionais podem:

- confirmar requisito;
- contradizer premissa;
- revelar risco;
- demonstrar capacidade;
- exigir revisão;
- gerar aprendizado.

Exemplo:

```text
IND-001 contradiz PRE-002
APD-003 deriva_de IND-001
ARQ-2026-001 é_reaberta_por APD-003
```

## 26. Lacunas de rastreabilidade

Lacunas devem ser classificadas.

### 26.1 Crítica

Impede decisão, aprovação, validação ou implantação responsável.

Exemplos:

- requisito obrigatório sem origem;
- componente crítico sem responsável;
- decisão estrutural sem autoridade;
- risco alto sem tratamento;
- função de IA sem verificação.

### 26.2 Relevante

Reduz confiança ou continuidade, sem impedir todo avanço.

### 26.3 Complementar

Ampliaria contexto ou documentação, com baixo impacto sobre a finalidade atual.

### 26.4 Aceita

Lacuna cuja permanência foi reconhecida e aprovada.

### 26.5 Registro da lacuna

| Lacuna | Caminho afetado | Classificação | Impacto | Ação | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `LAC-004` | `REQ-003 → CMP-007` | Relevante | Validação parcial | Testar integração | Especialista | Aberta |

## 27. Objetos órfãos

Objetos órfãos constituem sinais de possível ruptura metodológica.

### 27.1 Tipos

- achado sem encaminhamento;
- requisito sem origem;
- capacidade sem requisito;
- componente sem capacidade ou decisão;
- interface sem componentes definidos;
- controle sem risco;
- validação sem objeto;
- item de implantação sem componente;
- indicador sem finalidade decisória;
- aprendizado sem projeto de origem.

### 27.2 Tratamento

Para cada órfão, deve-se:

1. verificar erro de registro;
2. localizar vínculo existente;
3. avaliar necessidade real;
4. formalizar nova origem quando legítima;
5. criar decisão quando necessária;
6. retirar ou encerrar o objeto quando não justificável;
7. registrar o resultado.

### 27.3 Órfão legítimo temporário

Durante o desenho, objetos podem permanecer temporariamente isolados. Devem possuir prazo, responsável e próximo vínculo esperado.

## 28. Conflitos e divergências

Conflitos podem ocorrer entre:

- requisitos;
- critérios;
- capacidades;
- alternativas;
- componentes;
- decisões;
- validações;
- interesses;
- versões.

### 28.1 Registro

| Conflito | Objeto 1 | Objeto 2 | Natureza | Impacto | Decisão necessária | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `CFL-001` | `REQ-003` | `REQ-006` | Personalização e padronização | Alto | `DEC-2026-006` | Aberto |

### 28.2 Resultado

Um conflito pode ser:

- resolvido;
- equilibrado;
- aceito;
- adiado;
- escalado;
- transformado em experimento;
- preservado como divergência.

### 28.3 Divergência de validação

Diferentes participantes podem avaliar o mesmo componente de modos distintos. As posições devem permanecer vinculadas ao objeto, com contexto e autoridade decisória.

## 29. Análise de impacto

A análise de impacto utiliza vínculos para reconhecer efeitos de uma mudança.

### 29.1 Movimento regressivo

Verifica se a mudança continua coerente com:

- origem;
- evidência;
- achado;
- requisito;
- decisão.

### 29.2 Movimento progressivo

Verifica efeitos sobre:

- capacidades;
- componentes;
- interfaces;
- validações;
- itens de implantação;
- indicadores;
- documentos;
- treinamento;
- operação.

### 29.3 Perguntas

- Que objeto mudou?
- Que vínculos entram ou saem dele?
- Que requisitos podem perder cobertura?
- Que decisões precisam ser reabertas?
- Que testes deixam de ser válidos?
- Que versões precisam ser atualizadas?
- O Módulo 4 precisa ser comunicado?
- Existe impacto sobre dados, pessoas ou autoridade?

### 29.4 Registro de impacto

| Mudança | Objeto alterado | Objetos afetados | Severidade | Ação | Decisão | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `MUD-003` | `CMP-004` | `REQ-001`, `INT-002`, `TST-001`, `ITM-004` | Alta | Revalidar fluxo | `DEC-2026-008` | Em análise |

## 30. Versionamento e linha de base

A matriz deve corresponder à versão oficial da arquitetura.

### 30.1 Versão dos objetos

Mudanças materiais na formulação, prioridade, responsabilidade ou estado devem ser registradas.

### 30.2 Versão dos vínculos

Mudanças de relação, cobertura ou validação também precisam de histórico.

### 30.3 Linha de base

A linha de base deve identificar:

- projeto;
- versão;
- data;
- objetos incluídos;
- vínculos aprovados;
- requisitos abertos;
- condições;
- pendências;
- aprovadores.

### 30.4 Correção

Correções factuais pequenas podem atualizar o registro com histórico simplificado.

### 30.5 Substituição

Quando um objeto assumir a função de outro, utilizar vínculos `substitui` e `é_substituído_por`.

### 30.6 Proibição de sobrescrita silenciosa

Não se deve alterar uma relação aprovada de modo que o raciocínio anterior deixe de poder ser reconstruído.

## 31. Revisão da matriz

A matriz deve ser revisada em momentos definidos.

### 31.1 Após o aceite da transição

Verificar objetos de origem e requisitos iniciais.

### 31.2 Antes da geração de alternativas

Verificar cobertura diagnóstica e qualidade dos requisitos.

### 31.3 Antes da decisão

Verificar alternativas, critérios, riscos e conflitos.

### 31.4 Antes da validação

Verificar componentes, interfaces e requisitos sem tratamento.

### 31.5 Antes da aprovação

Verificar cobertura, validações, decisões e lacunas.

### 31.6 Antes da implantação

Verificar itens de implantação, dependências, versões e critérios de aceite.

### 31.7 Após mudança material

Executar análise de impacto e atualizar a linha de base quando aprovada.

## 32. Indicadores de rastreabilidade

Indicadores podem apoiar a revisão, sem substituir julgamento.

### 32.1 Cobertura de requisitos obrigatórios

```text
Requisitos obrigatórios com cobertura completa
------------------------------------------------ × 100
Total de requisitos obrigatórios aprovados
```

Requisitos parciais devem permanecer em categoria separada.

### 32.2 Requisitos sem tratamento

Quantidade por prioridade, estado e responsável.

### 32.3 Componentes justificados

```text
Componentes com requisito, capacidade, risco ou decisão de origem
--------------------------------------------------------------- × 100
Total de componentes ativos
```

### 32.4 Cobertura de validação

Quantidade de requisitos obrigatórios e componentes críticos com validação concluída.

### 32.5 Órfãos

Quantidade por tipo e tempo sem tratamento.

### 32.6 Vínculos invalidados

Quantidade e causa por versão.

### 32.7 Mudanças com impacto aberto

Quantidade de alterações cuja análise ainda não foi concluída.

### 32.8 Atenção à aparência de completude

Percentuais elevados podem coexistir com vínculos incorretos, critérios frágeis ou validação insuficiente. Indicadores devem sempre ser acompanhados por revisão qualitativa.

## 33. Sensibilidade e controle de acesso

A matriz geral deve utilizar identificadores e descrições mínimas quando a fonte contiver dados confidenciais ou sensíveis.

### 33.1 Classificação

- pública;
- interna;
- confidencial;
- sensível.

### 33.2 Separação de registros

Pode existir:

- matriz geral com identificadores;
- registro restrito de fontes;
- anexos sensíveis;
- versão de cliente;
- versão interna do Estúdio.

### 33.3 Princípios

- acesso mínimo necessário;
- referência em vez de reprodução;
- anonimização;
- segregação de dados;
- retenção definida;
- descarte adequado;
- proteção de autoria;
- registro de uso por IA.

### 33.4 Vínculo sensível

Quando a própria relação revelar informação sensível, a matriz geral pode utilizar descrição abstrata e apontar para registro restrito.

## 34. Minimização documental

A matriz deve registrar somente o necessário para:

- identificar objetos;
- compreender relações;
- avaliar cobertura;
- localizar decisões;
- verificar validações;
- analisar impacto;
- sustentar continuidade.

Não devem ser inseridos integralmente:

- entrevistas;
- documentos;
- mensagens;
- especificações extensas;
- dados pessoais;
- transcrições;
- conteúdos sensíveis;

quando uma referência for suficiente.

A matriz não deve se transformar em cópia de todos os documentos do projeto.

## 35. Participação da inteligência artificial

A IA pode apoiar a construção e a revisão da matriz.

### 35.1 Atividades permitidas

- normalizar identificadores;
- sugerir tipos de relação;
- localizar objetos órfãos;
- detectar referências quebradas;
- identificar duplicações;
- verificar cadeias mínimas;
- agrupar requisitos;
- resumir cobertura;
- apontar conflitos;
- apoiar análise de impacto;
- comparar versões;
- gerar perguntas de revisão.

### 35.2 Limites

A IA não deve:

- criar origem inexistente;
- declarar atendimento sem critério;
- transformar associação temática em vínculo causal;
- assumir que dois termos representam o mesmo objeto;
- alterar identificadores;
- apagar vínculos invalidados;
- decidir prioridade;
- aceitar risco;
- aprovar cobertura;
- receber dados desnecessários;
- substituir validação humana.

### 35.3 Saídas de IA não constituem origem organizacional

Uma sugestão da IA pode gerar pergunta, alternativa ou hipótese. Ela não deve ser registrada como evidência do funcionamento da organização.

### 35.4 Verificação humana

Deve confirmar:

- existência dos objetos;
- significado da relação;
- direção do vínculo;
- grau de cobertura;
- origem;
- versão;
- sensibilidade;
- impacto.

### 35.5 Registro da participação

Registrar:

- sistema ou agente;
- data;
- função;
- objetos examinados;
- dados fornecidos;
- saída utilizada;
- correções;
- responsável pela revisão;
- limitações.

## 36. Automação da matriz

A matriz pode ser implementada em:

- documento estruturado;
- planilha;
- banco de dados;
- ferramenta de gestão;
- grafo;
- sistema próprio.

### 36.1 Condições anteriores à automação

Antes de automatizar, devem estar suficientemente definidos:

- classes de objetos;
- identificadores;
- vocabulário de relações;
- estados;
- regras de cobertura;
- responsáveis;
- controle de versão;
- acesso;
- exceções.

### 36.2 Automação possível

Pode incluir:

- validação de formato de ID;
- detecção de duplicidade;
- alerta de órfãos;
- verificação de vínculos obrigatórios;
- painéis de cobertura;
- filtros por versão;
- relatórios de impacto;
- histórico de alterações;
- exportação para implantação.

### 36.3 Regra de continuidade

A organização deve conseguir exportar, compreender e manter os registros essenciais sem dependência absoluta da ferramenta.

## 37. Critérios de prontidão

### 37.1 Prontidão para gerar alternativas

- [ ] requisitos possuem origem;
- [ ] capacidades a preservar estão registradas;
- [ ] riscos e restrições estão vinculados;
- [ ] lacunas críticas possuem tratamento;
- [ ] critérios de desenho estão identificados.

### 37.2 Prontidão para decidir

- [ ] alternativas estão vinculadas a requisitos;
- [ ] critérios foram aplicados;
- [ ] riscos e compensações estão visíveis;
- [ ] conflitos possuem encaminhamento;
- [ ] decisões necessárias estão formuladas.

### 37.3 Prontidão para aprovar

- [ ] requisitos obrigatórios possuem tratamento;
- [ ] capacidades possuem componentes;
- [ ] componentes possuem justificativa;
- [ ] interfaces críticas estão registradas;
- [ ] validações necessárias foram realizadas;
- [ ] vínculos da linha de base estão aprovados;
- [ ] lacunas remanescentes foram aceitas.

### 37.4 Prontidão para implantar

- [ ] componentes aprovados possuem destino;
- [ ] itens de implantação estão relacionados;
- [ ] dependências e responsáveis estão definidos;
- [ ] critérios de aceite estão vinculados;
- [ ] versões vigentes estão claras;
- [ ] mudanças abertas foram tratadas;
- [ ] o Módulo 4 consegue reconstruir o desenho.

## 38. Critérios de qualidade

Uma matriz de qualidade deve ser:

### 38.1 Completa no grau necessário

Os objetos e caminhos críticos estão representados.

### 38.2 Correta

Os vínculos expressam relações reais e revisadas.

### 38.3 Consistente

Identificadores, direções, estados e vocabulário são utilizados de forma uniforme.

### 38.4 Bidirecionalmente reconstruível

É possível avançar da origem à operação e retornar do componente à justificativa.

### 38.5 Atual

Corresponde à versão vigente dos documentos e decisões.

### 38.6 Proporcional

O detalhe corresponde ao risco, ao impacto e ao uso.

### 38.7 Compreensível

Pessoas autorizadas conseguem interpretar objetos, vínculos e estados.

### 38.8 Decisória

Lacunas, conflitos, cobertura e impactos apoiam ações concretas.

### 38.9 Segura

Dados e relações sensíveis recebem proteção adequada.

### 38.10 Revisável

Alterações, invalidações e substituições podem ser reconstruídas.

## 39. Antipadrões

### 39.1 Matriz como inventário

Listar objetos sem registrar relações.

### 39.2 Relação sem significado

Vincular IDs com setas ou células sem declarar o tipo do vínculo.

### 39.3 Componente como prova de atendimento

Assumir que a existência de um componente comprova cobertura do requisito.

### 39.4 Cobertura por contagem

Avaliar atendimento pela quantidade de componentes.

### 39.5 IDs instáveis

Renumerar objetos a cada versão e romper referências anteriores.

### 39.6 Objetos removidos sem histórico

Apagar alternativas, requisitos ou componentes que deixaram de ser vigentes.

### 39.7 Cópia excessiva

Reproduzir conteúdo integral de outros documentos na matriz.

### 39.8 Rastreabilidade apenas regressiva

Justificar componentes existentes sem verificar requisitos esquecidos.

### 39.9 Rastreabilidade apenas progressiva

Acompanhar requisitos sem permitir retornar à evidência ou decisão de origem.

### 39.10 Cobertura total artificial

Classificar atendimento parcial como completo para liberar aprovação.

### 39.11 Vínculo criado pela IA sem revisão

Aceitar associação sem confirmar significado, contexto e origem.

### 39.12 Matriz desatualizada

Manter relações de versão anterior como se representassem a linha de base vigente.

### 39.13 Complexidade sem uso

Criar centenas de relações que não apoiam decisão, validação, impacto ou continuidade.

### 39.14 Segurança pela omissão

Retirar vínculos relevantes da matriz geral sem criar referência protegida correspondente.

## 40. Perguntas de controle

Antes de consolidar a matriz, perguntar:

1. Todo objeto relevante possui identificador estável?
2. Os objetos reutilizam IDs dos documentos de origem?
3. Cada requisito possui origem?
4. Requisitos novos possuem justificativa e aprovação?
5. Cada capacidade futura responde a requisito real?
6. Cada componente possui finalidade e origem?
7. O tipo de cada vínculo está explícito?
8. A direção das relações está consistente?
9. A cobertura foi avaliada por critério?
10. Coberturas parciais estão visíveis?
11. Alternativas descartadas permanecem registradas?
12. Decisões materiais podem ser localizadas?
13. Riscos possuem tratamento ou decisão?
14. Restrições alteram o desenho de forma visível?
15. Interfaces críticas estão relacionadas aos componentes?
16. Requisitos obrigatórios possuem validação?
17. Componentes críticos possuem item de implantação?
18. Existem objetos órfãos?
19. Existem vínculos quebrados?
20. Conflitos e divergências estão registrados?
21. Mudanças materiais receberam análise de impacto?
22. A matriz corresponde à linha de base vigente?
23. Informações sensíveis estão protegidas?
24. A participação da IA foi registrada?
25. O Módulo 4 consegue utilizar a matriz?
26. O detalhamento possui utilidade real?
27. Outra pessoa conseguiria reconstruir o percurso?

## 41. Invariantes da matriz

### 41.1 Invariante 1

Nenhum requisito deve permanecer sem origem identificada ou decisão explícita sobre sua origem externa.

### 41.2 Invariante 2

Nenhum componente material deve permanecer sem requisito, capacidade, risco ou decisão que o justifique.

### 41.3 Invariante 3

O tipo de relação deve ser explícito.

### 41.4 Invariante 4

Atendimento parcial não deve ser registrado como completo.

### 41.5 Invariante 5

Identificadores não devem ser reutilizados para objetos diferentes.

### 41.6 Invariante 6

Objetos e vínculos retirados da linha de base devem preservar histórico.

### 41.7 Invariante 7

Decisões materiais devem permanecer vinculadas às alternativas e aos objetos afetados.

### 41.8 Invariante 8

Requisitos obrigatórios e componentes críticos devem possuir verificação proporcional.

### 41.9 Invariante 9

Mudanças materiais devem produzir análise de impacto.

### 41.10 Invariante 10

Saídas de IA não devem ser tratadas como evidência organizacional nem como validação final.

### 41.11 Invariante 11

A matriz deve corresponder à versão oficial da arquitetura.

### 41.12 Invariante 12

O nível de detalhe deve permanecer proporcional ao uso, ao impacto e ao risco.

## 42. Exemplo de aplicação

### 42.1 Situação

O diagnóstico de um sistema editorial identificou que ideias, gravações e arquivos existem, porém não possuem fluxo compartilhado até a publicação.

### 42.2 Objetos de origem

| ID | Tipo | Síntese |
| --- | --- | --- |
| `EVD-021` | Evidência | Conteúdos ativos estavam distribuídos em três ambientes |
| `EVD-026` | Evidência | Não havia próxima ação registrada para sete conteúdos |
| `ACH-007` | Achado | O fluxo depende de memória e decisões repetidas |
| `PRB-001` | Problema | Perda de continuidade editorial |
| `CAP-001` | Capacidade existente | Comunicação oral autêntica |

### 42.3 Requisitos

| ID | Declaração | Origem |
| --- | --- | --- |
| `REQ-001` | Conteúdos ativos devem possuir estado, responsável e próxima ação localizáveis | `ACH-007` |
| `REQ-002` | A arquitetura deve preservar a voz da profissional | `CAP-001` |
| `REQ-003` | O fluxo deve funcionar com duas tardes mensais de gravação | Restrição temporal |

### 42.4 Capacidades e componentes

| ID | Tipo | Síntese |
| --- | --- | --- |
| `CAP-002` | Capacidade futura | Acompanhar conteúdos por estado |
| `CAP-003` | Capacidade futura | Transferir arquivos sem perder contexto |
| `CMP-001` | Processo | Fluxo editorial por estados |
| `CMP-002` | Papel | Responsável editorial |
| `CMP-003` | Documento | Template de pauta |
| `CMP-004` | Tecnologia | Base editorial compartilhada |
| `INT-001` | Interface | Transferência entre gravação e edição |

### 42.5 Vínculos principais

| Origem | Relação | Destino | Cobertura | Estado |
| --- | --- | --- | --- | --- |
| `REQ-001` | deriva_de | `ACH-007` | N/A | Aprovado |
| `CAP-002` | responde_a | `REQ-001` | Completa | Aprovado |
| `CMP-001` | realiza | `CAP-002` | Parcial | Aprovado |
| `CMP-002` | realiza | `CAP-002` | Parcial | Aprovado |
| `CMP-004` | realiza | `CAP-002` | Parcial | Em validação |
| `CMP-001` | preserva | `CAP-001` | Completa com condição | Em validação |
| `CMP-001` | é_conectado_por | `INT-001` | N/A | Proposto |
| `TST-001` | verifica | `CMP-001` | N/A | Planejado |

### 42.6 Alternativas e decisão

| Alternativa | Síntese | Resultado |
| --- | --- | --- |
| `ALT-001` | Fluxo manual mínimo | Não selecionada |
| `ALT-002` | Base editorial integrada com IA limitada | Selecionada |
| `ALT-003` | Automação ampliada | Adiada por complexidade |

```text
ALT-002 é_selecionado_por DEC-2026-004
ALT-003 é_adiado_por DEC-2026-004
```

### 42.7 Validação e implantação

```text
TST-001 verifica CMP-001
VAL-002 verifica REQ-002
ITM-001 implementa CMP-004
ITM-002 implementa INT-001
IND-001 monitora CAP-002
```

### 42.8 Percurso reconstruído

```text
EVD-021 + EVD-026
        ↓
      ACH-007
        ↓
      PRB-001
        ↓
      REQ-001
        ↓
      CAP-002
        ↓
CMP-001 + CMP-002 + CMP-004
        ↓
      TST-001
        ↓
ITM-001 + ITM-002
        ↓
      IND-001
```

Esse percurso permite compreender por que a base editorial existe, que problema trata, que capacidade produz, como será validada, o que deverá ser implantado e como o funcionamento será observado.

## 43. Critérios de conclusão

A matriz pode ser considerada consolidada quando:

- [ ] os objetos relevantes possuem identificadores;
- [ ] os documentos oficiais estão referenciados;
- [ ] os requisitos possuem origem;
- [ ] requisitos novos possuem justificativa;
- [ ] capacidades estão relacionadas a requisitos;
- [ ] componentes estão relacionados a capacidades ou decisões;
- [ ] o tipo dos vínculos está explícito;
- [ ] a direção das relações é consistente;
- [ ] coberturas foram avaliadas;
- [ ] atendimentos parciais permanecem visíveis;
- [ ] requisitos obrigatórios possuem tratamento;
- [ ] decisões materiais estão vinculadas;
- [ ] alternativas não selecionadas permanecem registradas;
- [ ] riscos e restrições possuem efeito rastreável;
- [ ] interfaces críticas estão representadas;
- [ ] validações necessárias estão relacionadas;
- [ ] objetos órfãos foram tratados;
- [ ] conflitos e lacunas estão registrados;
- [ ] componentes aprovados possuem destino de implantação;
- [ ] a linha de base está identificada;
- [ ] mudanças materiais receberam análise de impacto;
- [ ] dados sensíveis estão protegidos;
- [ ] a participação da IA foi registrada;
- [ ] a revisão final foi realizada;
- [ ] o Módulo 4 consegue utilizar os vínculos.

### 43.1 Estados finais

- consolidada;
- consolidada com limitações;
- aguardando validação;
- requer complementação;
- reaberta;
- substituída;
- encerrada.

## 44. Estrutura sugerida nos registros reais

```text
registros-de-arquitetura/
+-- AAAA/
    +-- ARQ-AAAA-NNN-nome/
        |-- requisitos/
        |   |-- catalogo-de-requisitos.md
        |   +-- matriz-de-rastreabilidade.md
        |-- rastreabilidade/
        |   |-- objetos.md
        |   |-- vinculos.md
        |   |-- cobertura-de-requisitos.md
        |   |-- cobertura-de-capacidades.md
        |   |-- objetos-orfaos.md
        |   |-- conflitos-e-lacunas.md
        |   |-- analises-de-impacto.md
        |   +-- linhas-de-base/
        |-- decisoes/
        |-- validacoes/
        +-- transicao-para-implantacao.md
```

Em projetos pequenos, `objetos.md`, `vinculos.md` e as visões podem permanecer em um único arquivo.

## 45. Relação com a arquitetura integrada

A arquitetura integrada apresenta como a configuração futura deverá funcionar.

A matriz deve permitir que cada elemento relevante da arquitetura integrada seja relacionado a:

- capacidade;
- requisito;
- origem;
- decisão;
- risco;
- validação;
- implantação.

A arquitetura integrada comunica o desenho. A matriz demonstra sua justificação e cobertura.

Quando houver divergência entre os documentos, a linha de base aprovada deve indicar qual versão constitui a referência e acionar correção.

## 46. Relação com a transição para implantação

A transição utiliza a matriz para produzir:

- lista de componentes aprovados;
- requisitos atendidos e pendentes;
- prioridades;
- dependências;
- riscos;
- decisões;
- itens de implantação;
- critérios de aceite;
- versões;
- condições de revalidação.

O Módulo 4 pode acrescentar vínculos de implantação sem alterar silenciosamente a justificação arquitetural.

Mudanças produzidas durante a implantação devem retornar à matriz por análise de impacto.

## 47. Aprendizagem metodológica

Ao final do projeto, registrar:

- que classes de objetos foram úteis;
- que vínculos foram difíceis de definir;
- que objetos órfãos apareceram;
- que requisitos perderam cobertura;
- que mudanças geraram maior impacto;
- que visões apoiaram decisão;
- que indicadores de rastreabilidade produziram valor;
- que detalhamento foi excessivo;
- que automações ajudaram;
- que erros de IA foram identificados;
- que vocabulário precisa ser ajustado;
- que padrão pode ser reutilizado;
- que alteração o método exige.

A aprendizagem deve distinguir falha do desenho, falha de registro e mudança legítima de contexto.

## 48. Princípio de encerramento

A matriz não existe para demonstrar que todos os documentos estão conectados.

Ela existe para tornar governável o percurso entre necessidade e funcionamento.

Seu preenchimento cumpre função quando permite:

- localizar a origem de uma escolha;
- reconhecer requisitos esquecidos;
- identificar componentes sem justificativa;
- distinguir cobertura parcial e completa;
- tornar decisões e compensações visíveis;
- verificar o que foi validado;
- compreender impactos de mudança;
- preparar implantação;
- devolver aprendizados ao sistema.

## 49. Síntese

A Matriz de Rastreabilidade preserva a continuidade do raciocínio organizacional.

Ela conecta quatro movimentos:

1. **compreender**, por meio de fontes, evidências e achados;
2. **justificar**, por meio de problemas, capacidades, riscos e requisitos;
3. **desenhar e decidir**, por meio de alternativas, componentes, interfaces e decisões;
4. **verificar e realizar**, por meio de validações, implantação, indicadores e aprendizagem.

Sua estrutura possui:

- um registro de objetos, que identifica o que existe;
- um registro de vínculos, que declara como os objetos se relacionam;
- visões derivadas, que mostram cobertura, lacunas, órfãos, conflitos, impactos e prontidão.

Uma arquitetura torna-se rastreável quando outra pessoa autorizada consegue percorrer o caminho completo sem depender da memória de quem a desenhou.

## 50. Histórico de versões

| Data | Versão | Alteração | Motivo | Responsável | Aprovador |
| --- | --- | --- | --- | --- | --- |
| 02/08/2026 | 0.1 | Criação da Matriz de Rastreabilidade da Arquitetura | Conectar diagnóstico, requisitos, desenho, decisão, validação, implantação e operação | Débora Lutz | Em validação |
