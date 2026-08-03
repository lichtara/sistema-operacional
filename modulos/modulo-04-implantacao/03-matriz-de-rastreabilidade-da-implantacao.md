# Matriz de Rastreabilidade da Implantação

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Método de conexão, cobertura e reconstrução da implantação  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data de criação:** 03/08/2026  
**Documentos relacionados:** `README.md`; `01-fundamentos-da-implantacao.md`; `02-protocolo-de-implantacao.md`; Matriz de Rastreabilidade da Arquitetura; transição para implantação do Módulo 3; Matriz de Evidências; Protocolo de Decisão; registros de decisão  
**Template relacionado:** `templates/06-matriz-de-rastreabilidade-da-implantacao.md`

## 1. Finalidade

A Matriz de Rastreabilidade da Implantação é o mecanismo utilizado pelo Estúdio LICHTARA para tornar reconstruível a transformação de uma linha de base arquitetural autorizada em capacidade organizacional implantada, aceita, estabilizada e transferida à operação.

Ela conecta:

- a origem diagnóstica e arquitetural;
- a linha de base recebida;
- as capacidades que precisam tornar-se reais;
- os requisitos, componentes, interfaces, riscos, condições e decisões herdados;
- a decomposição em incrementos, entregas, pacotes e itens de trabalho;
- a preparação técnica, humana, informacional, documental e operacional;
- os testes, demonstrações e evidências;
- as decisões de gate, liberação e aceite;
- as diferenças entre desenho e realidade;
- a configuração efetivamente implantada;
- a estabilização;
- a transferência de responsabilidade ao Módulo 5;
- os indicadores e aprendizados destinados aos módulos seguintes.

Sua função é impedir que a implantação seja conduzida ou encerrada apenas a partir de:

- memória das pessoas envolvidas;
- cronograma;
- percentual de tarefas concluídas;
- listas de entregas sem origem;
- documentos produzidos sem uso demonstrado;
- ferramenta ou plataforma adotada;
- treinamento realizado sem competência observada;
- comunicação enviada sem compreensão confirmada;
- aceite sem critério ou evidência;
- configuração técnica sem configuração organizacional;
- diferença não registrada;
- decisão tomada em reunião e perdida depois dela;
- síntese produzida por inteligência artificial;
- aparência de sucesso que não possa ser reconstruída.

A matriz deve permitir responder:

> De onde veio este trabalho, que parte da arquitetura ele realiza, sob quais condições avançou, que evidência demonstra o resultado, que diferença surgiu, quem a autorizou e o que a operação recebeu para sustentar?

## 2. Posição no Sistema Operacional

A matriz ocupa o intervalo entre arquitetura aprovada, realização e operação.

```text
Módulo 2 — Diagnóstico
  → fornece origem, evidências, achados, capacidades, problemas e riscos

Módulo 3 — Arquitetura
  → fornece requisitos, configuração, decisões, validações e linha de base

Módulo 4 — Implantação
  → transforma a linha de base em trabalho, evidência, aceite e configuração real

Módulo 5 — Operação
  → sustenta, monitora e corrige a configuração transferida

Módulos 6, 7 e 8
  → recebem aprendizagem, inteligência, evolução e governança especializada
```

A Matriz de Rastreabilidade da Arquitetura preserva o percurso até a configuração aprovada. A Matriz de Rastreabilidade da Implantação preserva o percurso da configuração aprovada até a realidade operacional transferida.

As duas matrizes possuem continuidade, mas não possuem a mesma função.

| Matriz | Pergunta dominante | Fronteira de fechamento |
| --- | --- | --- |
| Matriz de Rastreabilidade da Arquitetura | Por que esta configuração foi desenhada e autorizada? | Linha de base e transição para implantação. |
| Matriz de Rastreabilidade da Implantação | Como esta configuração se tornou realidade e com que resultado? | Configuração estabilizada e transição aceita pela operação. |

O Módulo 4 importa referências do Módulo 3 sem renumerá-las, acrescenta objetos próprios de realização e devolve ao sistema os vínculos que somente a prática poderia produzir.

## 3. Tese da rastreabilidade da implantação

Rastreabilidade da implantação é a capacidade de reconstruir relações de origem, realização, preparação, evidência, decisão, configuração e continuidade ao longo do tempo.

Ela não consiste apenas em inserir identificadores em documentos.

Uma referência como `IMP-2026-001-ENT-004` somente possui valor quando permite compreender:

- por que a entrega existe;
- qual capacidade ela ajuda a instalar;
- que requisitos e componentes a delimitam;
- a que incremento pertence;
- de que outras condições depende;
- qual versão foi produzida;
- que critérios a verificam;
- que evidências foram obtidas;
- que decisão autorizou sua liberação ou correção;
- que parte da configuração real ela afetou;
- que condição residual permaneceu.

A matriz é íntegra quando outra pessoa pode percorrer o caminho sem depender da memória privada de quem implantou.

## 4. Pergunta central

> Como preservar o vínculo entre intenção arquitetural, trabalho realizado, evidência observada, decisão humana e configuração operacional sem transformar a implantação em burocracia desproporcional?

A resposta exige simultaneamente:

- objetos estáveis;
- relações semanticamente explícitas;
- fontes oficiais localizáveis;
- versões conhecidas;
- estados vigentes;
- critérios anteriores ao resultado;
- evidências proporcionais ao risco;
- autoridades identificadas;
- lacunas visíveis;
- atualização durante o ciclo;
- visões compreensíveis para diferentes públicos.

## 5. O que a matriz deve permitir

Uma matriz adequadamente mantida deve permitir compreender:

1. qual implantação está sendo governada;
2. qual transição e linha de base foram recebidas;
3. que versões constituíam a referência aceita no `PI-1`;
4. que capacidades precisavam ser implantadas;
5. que requisitos, componentes e interfaces delimitavam cada capacidade;
6. que condições, premissas, riscos e dependências foram herdados;
7. que elementos ficaram fora do escopo e por quê;
8. como a arquitetura foi decomposta em incrementos, entregas e trabalho;
9. que trabalho não possui origem suficiente;
10. que objeto obrigatório ainda não possui caminho de realização;
11. que preparação humana, técnica, documental ou operacional foi exigida;
12. que critérios precederam cada teste, gate, liberação e aceite;
13. que evidências demonstram atividade, entrega, capacidade, competência, adoção e estabilidade;
14. que evidências negativas ou divergentes surgiram;
15. que decisões permitiram avanço, contenção, correção, adaptação ou reversão;
16. que mudanças permaneceram dentro da alçada do Módulo 4;
17. que mudanças retornaram ao Módulo 3;
18. que diferenças existem entre linha de base e configuração implantada;
19. quais diferenças foram aceitas, corrigidas, revertidas ou mantidas sob condição;
20. que riscos e pendências permanecem abertos;
21. quem responde por cada condição residual;
22. qual configuração foi aceita no `PI-4`;
23. que configuração foi estabilizada;
24. o que foi transferido e aceito no `PI-5`;
25. onde o funcionamento será observado na operação;
26. que aprendizagem foi destinada aos Módulos 3, 4, 6, 7 ou 8;
27. que objetos seriam afetados por uma mudança posterior;
28. qual fonte é vigente em caso de divergência.

## 6. O que a matriz não substitui

A matriz não substitui:

- a transição para implantação do Módulo 3;
- o manifesto da linha de base;
- o catálogo de requisitos;
- a arquitetura integrada;
- os registros de decisão;
- o termo de abertura;
- o plano de implantação;
- a estrutura analítica da implantação;
- o cronograma;
- o backlog ou quadro Kanban;
- os registros de riscos, impedimentos, dependências e mudanças;
- os planos humanos;
- os registros de teste e evidência;
- as verificações de prontidão;
- os registros de gate;
- os registros de validação e aceite;
- o registro da configuração implantada;
- o relatório de implantação;
- a transição para operação;
- os documentos originais.

Ela referencia, conecta e verifica esses materiais.

Também não substitui julgamento humano. Uma relação registrada pode estar incorreta, uma evidência pode ser insuficiente e uma cadeia completa pode realizar uma solução materialmente inadequada. A matriz torna o raciocínio examinável; não transforma registro em verdade automática.

## 7. Contratos herdados

### 7.1 Módulo 1 — decisão governável

Nenhum vínculo decisório material deve existir sem objeto, autoridade, fundamento, consequência e registro recuperável.

A matriz referencia a decisão. Ela não recria uma justificativa concorrente nem reduz a decisão ao nome da pessoa que aprovou.

### 7.2 Módulo 2 — origem reconstruível

Nenhuma afirmação de origem deve ser tratada como evidência quando sua fonte, qualidade e limite não puderem ser localizados.

A matriz de implantação importa referências diagnósticas quando elas forem necessárias para compreender requisito, risco, aceitação, efeito humano ou aprendizagem. Ela não reabre silenciosamente o diagnóstico.

### 7.3 Módulo 3 — linha de base autorizada

A implantação recebe uma configuração autorizada. Ela não recebe permissão implícita para redesenhá-la.

Objetos do Módulo 3 preservam:

- identificador;
- tipo;
- versão;
- estado;
- fonte oficial;
- decisão relacionada;
- posição na linha de base.

Mudança material exige retorno ao Módulo 3, decisão competente e nova referência arquitetural quando aplicável.

### 7.4 Módulo 4 — realidade demonstrável

Atividade concluída, entrega produzida, capacidade disponível, capacidade utilizada, capacidade demonstrada e configuração estabilizada são estados diferentes.

A matriz deve preservar essas diferenças.

## 8. Continuidade com a Matriz de Rastreabilidade da Arquitetura

O Módulo 4 não cria uma segunda identidade para o mesmo requisito, componente, interface, risco ou decisão arquitetural.

Quando a Matriz de Rastreabilidade da Arquitetura utiliza:

- `REQ-ARQ-007`;
- `CAP-ARQ-004`;
- `CMP-ARQ-011`;
- `INT-ARQ-003`;
- `DEC-2026-005`;
- `VAL-ARQ-002`;

a implantação reutiliza essas referências exatamente como recebidas, qualificando o projeto quando houver risco de ambiguidade.

Exemplo:

```text
ARQ-2026-001-REQ-007
```

O vínculo entre matrizes deve permitir:

```text
MTR-ARQ-AAAA-NNN
  → linha de base autorizada
  → MTR-IMP-AAAA-NNN
```

Se o Módulo 4 descobrir que um objeto arquitetural está ausente, ambíguo, inconsistente ou desatualizado, deve registrar lacuna e decidir a rota adequada. Não deve corrigir o objeto de origem dentro da matriz de implantação.

## 9. Princípios da matriz

### 9.1 Todo trabalho material possui origem

Entrega, pacote ou item de backlog sem vínculo com capacidade, requisito, componente, condição, risco ou decisão reconhecível deve ser questionado.

Trabalho administrativo necessário pode derivar da governança da implantação. Essa origem também deve ser declarada.

### 9.2 Toda obrigação aplicável possui destino

Requisito, condição, risco, dependência ou pendência aplicável deve possuir caminho de realização, tratamento, aceitação, adiamento, devolução ou exclusão autorizada.

### 9.3 Objetos e vínculos permanecem separados

Um objeto possui identidade, descrição, estado, versão e fonte.

Um vínculo declara como dois objetos se relacionam.

Essa separação permite relações muitos-para-muitos sem duplicar conteúdo nem transformar colunas em narrativas ambíguas.

### 9.4 O vínculo possui significado

Relacionar dois IDs sem declarar a natureza da relação não produz rastreabilidade suficiente.

```text
REQ-ARQ-007 → IMP-2026-001-ENT-004
```

pode significar que a entrega atende, verifica, depende, contradiz ou apenas menciona o requisito.

A relação precisa ser explícita.

### 9.5 O vínculo não demonstra resultado

Relacionar entrega e requisito não comprova atendimento.

Atendimento exige, conforme materialidade:

- critério;
- grau de cobertura;
- evidência;
- versão;
- validação;
- decisão;
- estado.

### 9.6 A fonte oficial permanece fora da matriz quando apropriado

A matriz referencia conteúdo extenso. Não deve copiar integralmente documentos cuja duplicação crie fontes concorrentes.

### 9.7 Identificadores permanecem estáveis

Descrição, estado e versão podem mudar. O identificador não deve ser reutilizado para representar outro objeto.

### 9.8 Elementos retirados permanecem recuperáveis

Objeto cancelado, substituído, rejeitado, revertido ou fora de vigência deve preservar estado, motivo, data, decisão e referência sucessora quando houver.

### 9.9 Cobertura parcial permanece parcial

Cobertura incompleta, condicionada, contestada ou não demonstrada não deve ser apresentada como completa.

### 9.10 A matriz acompanha o ciclo

A matriz nasce no planejamento, recebe atualização nos eventos materiais e participa dos gates. Produzi-la apenas no encerramento converte rastreabilidade em reconstrução tardia e vulnerável.

### 9.11 A profundidade é proporcional

Implantação focal pode combinar registros e utilizar visão reduzida. Risco, integração, irreversibilidade, dados sensíveis, IA, impacto humano, múltiplas ondas ou múltiplas autoridades exigem rastreabilidade ampliada.

### 9.12 O registro apoia decisão e continuidade

Detalhamento que não melhora origem, controle, verificação, decisão, transferência ou aprendizagem deve ser reduzido.

## 10. Estrutura lógica

A matriz possui três camadas e visões derivadas.

### 10.1 Camada 1 — objetos

Registra ou referencia os elementos rastreáveis.

Exemplos:

- `REQ-ARQ-007` — requisito herdado;
- `CAP-ARQ-004` — capacidade arquitetural;
- `IMP-2026-001-INC-001` — incremento;
- `IMP-2026-001-ENT-004` — entrega;
- `IMP-2026-001-EVD-012` — evidência;
- `IMP-2026-001-DIF-002` — diferença;
- `IMP-2026-001-CFG-001` — configuração implantada.

### 10.2 Camada 2 — vínculos

Registra relações semanticamente controladas.

Exemplos:

```text
IMP-2026-001-ENT-004 realiza CAP-ARQ-004
IMP-2026-001-EVD-012 demonstra IMP-2026-001-ENT-004
IMP-2026-001-DIF-002 difere_de CMP-ARQ-011
IMP-2026-001-CFG-001 incorpora IMP-2026-001-ENT-004
```

### 10.3 Camada 3 — eventos e decisões

Preserva o que alterou validade, estado, versão ou autoridade dos objetos e vínculos.

Exemplos:

- resultado de gate;
- liberação;
- aceite;
- correção;
- adaptação autorizada;
- mudança de plano;
- retorno ao Módulo 3;
- reversão;
- substituição;
- transferência operacional.

### 10.4 Visões derivadas

São recortes produzidos a partir das camadas oficiais.

Podem mostrar:

- cobertura da linha de base;
- requisitos sem realização;
- trabalho sem origem;
- evidência por gate;
- diferenças abertas;
- decisões sem efeito incorporado;
- configuração por incremento;
- condições transferidas à operação;
- impacto de mudança;
- itens desatualizados.

Visão derivada não se torna fonte independente.

## 11. Unidades de registro

### 11.1 Objeto rastreável

Elemento identificado que participa do percurso da implantação.

### 11.2 Vínculo rastreável

Relação dirigida ou, excepcionalmente, simétrica entre dois objetos.

O vínculo é a unidade mínima da matriz.

### 11.3 Caminho

Sequência de vínculos que permite reconstruir origem, realização ou consequência.

```text
REQ-ARQ-007
  → CAP-ARQ-004
  → IMP-2026-001-ENT-004
  → IMP-2026-001-EVD-012
  → PI-4
  → IMP-2026-001-CFG-001
```

### 11.4 Cadeia

Conjunto de caminhos relacionados que representa uma capacidade, incremento, gate, configuração ou transição.

### 11.5 Cobertura

Condição em que um objeto aplicável possui tratamento rastreável suficiente para o ponto do ciclo avaliado.

### 11.6 Lacuna de rastreabilidade

Ausência, ambiguidade, invalidade ou insuficiência de vínculo necessário.

### 11.7 Órfão

Objeto material que deveria possuir relação e permanece isolado ou ligado apenas de forma temática.

### 11.8 Evento de atualização

Ocorrência que exige revisão de objeto, vínculo, estado, versão ou cobertura.

### 11.9 Linha de base de referência

Conjunto versionado e autorizado de objetos arquiteturais recebido pelo Módulo 4.

### 11.10 Configuração de realização

Conjunto versionado de objetos de implantação produzidos, liberados, aceitos, estabilizados ou transferidos.

### 11.11 Visão

Recorte compreensível da matriz para uma pergunta ou público definido.

## 12. Granularidade

A matriz deve registrar o menor nível que permita decisão, verificação e impacto sem transformar cada gesto em objeto autônomo.

### 12.1 Granularidade insuficiente

Ocorre quando uma linha como “implantar sistema editorial” reúne, sem distinção:

- configuração;
- migração;
- papéis;
- documentação;
- treinamento;
- teste;
- liberação;
- aceite;
- estabilização.

Não é possível reconhecer o que falhou, o que foi aceito ou o que mudou.

### 12.2 Granularidade excessiva

Ocorre quando cada mensagem, clique, reunião, ajuste visual ou microtarefa recebe ID e vínculo permanentes sem efeito material sobre decisão, risco, configuração ou continuidade.

### 12.3 Regra de seleção

Um objeto ou vínculo tende a merecer registro próprio quando pelo menos uma das condições estiver presente:

- possui critério próprio;
- possui responsável ou autoridade própria;
- pode mudar de estado independentemente;
- possui risco ou dependência material;
- participa de gate;
- gera evidência específica;
- altera configuração;
- pode ser aceito parcialmente;
- pode exigir correção, reversão ou retorno;
- será transferido à operação;
- precisa ser localizado em análise de impacto.

## 13. Classes de objetos rastreáveis

As classes se organizam pela posição no ciclo.

| Classe | Função |
| --- | --- |
| Origem diagnóstica | Explicar a realidade, necessidade, capacidade, problema, risco ou restrição que antecedeu a arquitetura. |
| Arquitetura autorizada | Definir o que deve tornar-se realidade, sob quais limites e por qual decisão. |
| Governança da implantação | Delimitar implantação, autoridade, estratégia, gate e condição de avanço. |
| Realização | Representar projeto, onda, incremento, entrega, pacote e item de fluxo. |
| Preparação | Representar condições humanas, técnicas, informacionais, documentais e operacionais. |
| Evidência e validação | Tornar observáveis atividade, entrega, capacidade, competência, adoção, controle e estabilidade. |
| Decisão e mudança | Preservar autorização, correção, adaptação, mudança, contenção, reversão e aceite. |
| Configuração | Registrar o que foi efetivamente instalado, utilizado, aceito e estabilizado. |
| Operação e aprendizagem | Transferir responsabilidade, monitoramento, condição residual e conhecimento. |

## 14. Objetos herdados do Módulo 2

Referências diagnósticas podem incluir, conforme o projeto:

| Objeto | Exemplos de prefixos | Uso na implantação |
| --- | --- | --- |
| Fonte | `ENT`, `OBS`, `DOC`, `DAD`, `SIS`, `EXT` | Localizar origem quando necessária ao entendimento ou à validação. |
| Evidência diagnóstica | `EVD` | Sustentar ou questionar achado, requisito, risco ou efeito. |
| Achado | `ACH` | Explicar necessidade, capacidade, problema, oportunidade ou risco. |
| Problema | `PRB` | Verificar se a capacidade implantada trata a condição relevante. |
| Capacidade existente | `CAP` | Preservar funcionamento necessário durante a transição. |
| Risco, restrição e dependência | `RSC`, `RES`, `DEP` | Delimitar exposição, sequência e condições. |
| Lacuna ou questão aberta | `LAC`, `QAB` | Preservar incerteza ainda material. |

A matriz de implantação não deve copiar toda a origem diagnóstica quando a Matriz de Rastreabilidade da Arquitetura já oferece caminho suficiente. Ela pode referenciar o caminho arquitetural consolidado.

## 15. Objetos herdados do Módulo 3

Objetos arquiteturais podem incluir:

| Objeto | Prefixo frequente | Função na implantação |
| --- | --- | --- |
| Projeto de arquitetura | `ARQ` | Identificar a origem do desenho. |
| Linha de base | `LB-ARQ` | Fixar versões autorizadas. |
| Matriz arquitetural | `MTR-ARQ` | Preservar relações anteriores à implantação. |
| Requisito | `REQ-ARQ` | Definir condição a realizar ou preservar. |
| Capacidade | `CAP-ARQ` | Definir resultado organizacional possível. |
| Critério | `CRT-ARQ` | Delimitar desenho, escolha ou verificação. |
| Premissa e condição | `PRE-ARQ`, `COND-ARQ` | Fixar hipótese, limite ou condição temporal. |
| Alternativa | `ALT-ARQ` | Preservar configuração considerada e selecionada. |
| Decisão | `DEC-AAAA-NNN` | Autorizar escolha ou mudança. |
| Componente | `CMP-ARQ` | Representar elemento da configuração. |
| Interface | `INT-ARQ` | Representar passagem entre componentes. |
| Processo, papel, informação, documento e tecnologia | Prefixos próprios do Módulo 3 | Delimitar dimensões materiais da configuração. |
| Risco e controle | `RSC-ARQ`, `CTL-ARQ` | Delimitar exposição e proteção. |
| Teste e validação | `TST-ARQ`, `VAL-ARQ` | Preservar verificações arquiteturais. |
| Item de implantação | `ITM-ARQ` | Indicar tradução inicial proposta pelo Módulo 3. |
| Indicador | `IND-ARQ` | Preparar observabilidade. |

O prefixo real e a forma qualificada recebidos do repositório oficial prevalecem sobre exemplos deste documento.

## 16. Objetos próprios do Módulo 4

### 16.1 Identificadores definidos pelo protocolo

| Objeto | Padrão canônico |
| --- | --- |
| Implantação | `IMP-AAAA-NNN` |
| Projeto | `IMP-AAAA-NNN-PRJ-NNN` |
| Onda | `IMP-AAAA-NNN-OND-NNN` |
| Incremento | `IMP-AAAA-NNN-INC-NNN` |
| Entrega | `IMP-AAAA-NNN-ENT-NNN` |
| Pacote de trabalho | `IMP-AAAA-NNN-PT-NNN` |
| Item de backlog | `IMP-AAAA-NNN-ITM-NNN` |
| Evidência | `IMP-AAAA-NNN-EVD-NNN` |
| Diferença | `IMP-AAAA-NNN-DIF-NNN` |
| Configuração implantada | `IMP-AAAA-NNN-CFG-NNN` |
| Ciclo PDCA | `IMP-AAAA-NNN-PDCA-NNN` |

### 16.2 Identificadores complementares de rastreabilidade

Quando precisarem de referência individual, utilizar:

| Objeto | Padrão canônico | Uso |
| --- | --- | --- |
| Matriz da implantação | `MTR-IMP-AAAA-NNN` | Identificar a fonte oficial de vínculos. |
| Vínculo | `IMP-AAAA-NNN-VNC-NNN` | Versionar, invalidar ou referenciar relação material. |
| Lacuna de rastreabilidade | `IMP-AAAA-NNN-LAC-NNN` | Governar ausência ou insuficiência de caminho. |
| Ocorrência de gate | `IMP-AAAA-NNN-GAT-NNN` | Distinguir decisões repetidas de `PI-2`, `PI-3`, `PI-4` ou `PI-5`. |

Esses identificadores complementam o protocolo sem renumerar objetos já existentes.

### 16.3 Objetos referenciados por outros registros

Risco, impedimento, dependência, condição, mudança, comunicação, competência, teste, liberação, aceite, estabilização e transição podem utilizar IDs definidos pelos respectivos templates ou dossiê real.

Quando ainda não houver padrão específico, a matriz deve referenciar o identificador estável do registro oficial. Não deve criar um segundo objeto apenas para preencher uma coluna.

## 17. Objetos destinados à operação e à aprendizagem

A matriz pode referenciar, sem antecipar o desenho detalhado dos módulos seguintes:

- responsável operacional;
- procedimento vigente;
- documento oficial;
- indicador operacional;
- limite ou guardrail;
- controle recorrente;
- rotina de suporte;
- plano de manutenção;
- risco residual;
- condição de retorno;
- registro de aprendizagem;
- item de evolução;
- função de IA sujeita a governança específica.

Enquanto o módulo de destino não possuir identificador canônico, utilizar referência localizável e tipo completo. Quando o ID posterior existir, acrescentar o vínculo sem apagar o histórico anterior.

## 18. Identidade, namespace e não renumeração

### 18.1 Identidade da matriz

Cada implantação formal possui uma fonte oficial identificada por:

```text
MTR-IMP-AAAA-NNN
```

O sufixo deve corresponder à implantação quando isso não gerar conflito.

Exemplo:

```text
implantação: IMP-2026-001
matriz: MTR-IMP-2026-001
```

### 18.2 Namespace

Dentro do dossiê, formas abreviadas como `INC-001` e `ENT-004` podem ser exibidas. A chave canônica permanece completa.

### 18.3 Colisão

Quando duas fontes utilizarem o mesmo identificador abreviado, qualificar por projeto, módulo ou caminho oficial.

### 18.4 Não renumeração

Objeto importado preserva seu ID. Correção de erro na origem deve ocorrer no módulo competente, com histórico e análise de impacto.

### 18.5 Não reutilização

ID encerrado, cancelado ou substituído não deve representar novo objeto.

## 19. Registro de objetos

Cada objeto referenciado pela matriz deve possuir, diretamente ou por resolução à fonte oficial:

| Campo | Função |
| --- | --- |
| ID | Identificar de modo estável. |
| Tipo | Declarar a classe do objeto. |
| Título | Permitir reconhecimento humano rápido. |
| Descrição curta | Explicar função ou condição sem duplicar a fonte. |
| Módulo de origem | Indicar autoridade metodológica. |
| Projeto ou implantação | Delimitar contexto. |
| Fonte oficial | Localizar registro vigente. |
| Versão | Identificar formulação ou configuração. |
| Estado | Mostrar condição atual. |
| Responsável pelo objeto | Definir custódia ou atualização. |
| Autoridade aplicável | Indicar quem pode aprovar mudança material. |
| Sensibilidade | Definir proteção. |
| Data de criação | Situar início. |
| Data de revisão | Situar atualização vigente. |
| Linha de base ou configuração | Indicar pertencimento quando aplicável. |
| Observações | Preservar limite, ressalva ou contexto. |

### 19.1 Registro por referência

Quando esses campos já existirem na fonte, a matriz pode manter apenas:

- ID;
- tipo;
- título curto;
- versão;
- estado;
- fonte oficial;
- data da última sincronização.

### 19.2 Regra de autoridade

A matriz não se torna autoridade sobre o conteúdo de objeto pertencente a outro registro. Ela governa a relação e a cobertura dentro da implantação.

## 20. Registro de vínculos

Cada vínculo material deve permitir identificar:

| Campo | Função |
| --- | --- |
| ID do vínculo | Identificar a relação quando necessário. |
| Objeto de origem | Indicar onde o vínculo começa. |
| Tipo da origem | Apoiar validação semântica. |
| Versão da origem | Evitar vínculo com formulação ambígua. |
| Relação | Declarar significado controlado. |
| Objeto de destino | Indicar onde o vínculo termina. |
| Tipo do destino | Apoiar validação semântica. |
| Versão do destino | Delimitar configuração relacionada. |
| Cobertura | Registrar grau de realização quando aplicável. |
| Estado do vínculo | Mostrar validade atual. |
| Fundamento | Explicar por que a relação existe. |
| Critério | Indicar condição usada para avaliar a relação. |
| Evidência | Localizar demonstração quando aplicável. |
| Decisão | Localizar autorização quando aplicável. |
| Responsável | Definir manutenção do vínculo. |
| Gate afetado | Mostrar efeito sobre passagem. |
| Vigência | Delimitar início e fim. |
| Fonte | Localizar registro que sustenta o vínculo. |
| Observações | Preservar condição, limite ou divergência. |

### 20.1 Modelo mínimo

| Origem | Relação | Destino | Cobertura | Estado | Fundamento ou evidência |
| --- | --- | --- | --- | --- | --- |
| `CAP-ARQ-004` | `é_realizada_por` | `IMP-2026-001-INC-001` | Planejada | Vigente | Plano e decomposição. |
| `IMP-2026-001-ENT-004` | `atende_parcialmente` | `REQ-ARQ-007` | Parcial | Vigente | Critério ainda não demonstrado em exceção. |
| `IMP-2026-001-EVD-012` | `demonstra` | `IMP-2026-001-ENT-004` | Não aplicável | Validado | Registro de teste. |

### 20.2 Identificação do vínculo

Em implantação focal, a combinação origem–relação–destino pode ser suficiente se não houver necessidade de versionar ou referenciar o vínculo.

Utilizar `IMP-AAAA-NNN-VNC-NNN` quando o vínculo:

- mudar de estado;
- possuir condição própria;
- participar de decisão;
- for contestado;
- exigir histórico;
- for usado em análise de impacto;
- precisar ser citado em gate ou transição.

## 21. Vocabulário controlado de relações

O vocabulário controlado reduz ambiguidade, permite verificações e torna visões derivadas confiáveis.

Uma relação nova pode ser criada quando as existentes não expressarem o significado necessário. Sua definição, direção, objetos permitidos e diferença em relação a termos próximos devem ser registradas antes do uso recorrente.

## 22. Relações por função

### 22.1 Origem e continuidade

| Relação | Significado |
| --- | --- |
| `deriva_de` | O objeto foi formulado a partir de outro. |
| `é_justificado_por` | O destino fornece razão material para a origem. |
| `preserva` | O objeto mantém capacidade, regra, proteção ou valor existente. |
| `formaliza` | O objeto transforma condição em registro explícito. |
| `herda` | O objeto recebe condição, risco, requisito ou decisão anterior. |
| `continua_em` | O objeto prossegue em outro módulo, fase ou configuração. |

### 22.2 Realização e decomposição

| Relação | Significado |
| --- | --- |
| `é_realizada_por` | Capacidade ou configuração recebe realização por objeto de implantação. |
| `realiza` | Objeto de implantação torna capacidade materialmente possível. |
| `decompõe_em` | Objeto agregado origina unidades menores de realização. |
| `pertence_a` | Objeto integra incremento, onda, projeto ou implantação. |
| `produz` | Trabalho gera entrega, evidência ou configuração. |
| `incorpora` | Configuração reúne objeto produzido e aceito. |
| `substitui` | Nova versão ou objeto assume função anterior. |

### 22.3 Atendimento e proteção

| Relação | Significado |
| --- | --- |
| `atende` | Produz cobertura completa conforme critério vigente. |
| `atende_parcialmente` | Produz cobertura incompleta ou condicionada. |
| `não_atende` | Foi avaliado e não produz cobertura suficiente. |
| `trata` | Atua sobre risco, problema, impedimento, lacuna ou condição. |
| `controla` | Previne, detecta, corrige ou compensa exposição. |
| `protege` | Preserva pessoa, dado, continuidade, autoria ou limite material. |
| `restringe` | Limita escopo, uso, público, dado, tempo ou efeito. |

### 22.4 Dependência e estrutura

| Relação | Significado |
| --- | --- |
| `depende_de` | Necessita de outro objeto ou condição. |
| `precede` | Precisa ocorrer antes para o caminho avaliado. |
| `é_condicionado_por` | Somente avança se condição for atendida ou aceita. |
| `interfaceia_com` | Mantém passagem material com outro objeto. |
| `transfere_para` | Move trabalho, informação, dado ou responsabilidade. |
| `conflita_com` | Possui incompatibilidade ou tensão material. |
| `é_limitado_por` | Opera dentro de limite explícito. |

### 22.5 Evidência e validação

| Relação | Significado |
| --- | --- |
| `é_verificado_por` | Objeto recebe comparação com especificação. |
| `é_validado_por` | Objeto recebe julgamento de adequação ao uso ou necessidade. |
| `é_demonstrado_por` | O objeto recebe demonstração por evidência identificada. |
| `demonstra` | Evidência sustenta resultado delimitado. |
| `contradiz` | Evidência ou resultado questiona afirmação ou expectativa. |
| `qualifica` | Evidência acrescenta contexto, limite ou condição. |
| `mede` | Indicador representa manifestação definida. |

### 22.6 Decisão, gate e mudança

| Relação | Significado |
| --- | --- |
| `é_autorizado_por` | Objeto ou movimento recebe autoridade formal. |
| `autoriza` | Decisão permite ação, estado ou versão. |
| `é_liberado_por` | Versão recebe decisão de exposição ou uso. |
| `é_aceito_por` | Resultado recebe aceite formal. |
| `é_rejeitado_por` | Objeto ou resultado não recebe aprovação. |
| `é_contido_por` | Escopo ou efeito é limitado por decisão. |
| `é_revertido_por` | Configuração retorna por decisão ou evento. |
| `retorna_a` | Necessidade ou mudança é encaminhada ao módulo competente. |

### 22.7 Diferença e configuração

| Relação | Significado |
| --- | --- |
| `difere_de` | Configuração real apresenta distância em relação à referência. |
| `corrige` | Ação restaura atendimento sem mudar intenção material. |
| `adapta` | Ação altera execução dentro de tolerância autorizada. |
| `altera_materialmente` | Mudança afeta arquitetura ou proteção material. |
| `configura` | Objeto participa da forma instalada. |
| `estabiliza` | Ação ou período demonstra funcionamento sob exposição suficiente. |
| `transfere_responsabilidade_para` | Autoridade operacional aceita sustentação delimitada. |

### 22.8 Operação e aprendizagem

| Relação | Significado |
| --- | --- |
| `é_monitorado_por` | Funcionamento será acompanhado por indicador ou rotina. |
| `aciona` | Sinal, limite ou evento provoca resposta definida. |
| `é_sustentado_por` | Objeto depende de papel, competência, documento, tecnologia ou rotina operacional. |
| `gera_aprendizagem_para` | Experiência produz conhecimento destinado a módulo ou método. |
| `exige_revisão_de` | Evidência ou mudança demanda reavaliação. |
| `encerra` | Decisão conclui vigência ou ciclo de objeto. |

## 23. Semântica, direção e cardinalidade

### 23.1 Direção

Cada relação possui leitura definida.

```text
IMP-2026-001-ENT-004 realiza CAP-ARQ-004
```

não deve ser invertido silenciosamente para:

```text
CAP-ARQ-004 realiza IMP-2026-001-ENT-004
```

Quando a leitura regressiva for necessária, a visão pode apresentar a relação inversa sem criar vínculo duplicado.

### 23.2 Cardinalidade

Uma capacidade pode ser realizada por múltiplas entregas. Uma entrega pode contribuir para múltiplas capacidades. A matriz deve representar relações muitos-para-muitos sem condensá-las em célula incompreensível.

### 23.3 Relações simétricas

Relações como `conflita_com` podem ser semanticamente simétricas. Registrar uma vez e declarar simetria. Não duplicar apenas para criar aparência de completude.

### 23.4 Relação transitiva

Nem toda relação se transmite ao longo do caminho.

Se uma entrega pertence a um incremento e o incremento pertence a uma onda, é possível derivar pertencimento agregado. Isso não significa que toda decisão da onda autorize automaticamente cada mudança material da entrega.

### 23.5 Relação inferida

Vínculo inferido por regra ou automação deve ser distinguido de vínculo confirmado.

### 23.6 Relação temática

Menção, proximidade de assunto ou presença no mesmo documento não constitui relação material suficiente.

## 24. Estados dos objetos e dos vínculos

### 24.1 Estado do objeto

O estado principal pertence ao registro oficial do objeto.

Exemplos:

- planejado;
- em preparação;
- em execução;
- produzido;
- liberado;
- em validação;
- aceito;
- aceito com condições;
- estabilizado;
- transferido;
- suspenso;
- revertido;
- substituído;
- cancelado;
- encerrado.

### 24.2 Estado do vínculo

| Estado | Significado |
| --- | --- |
| Proposto | Relação identificada, ainda não confirmada. |
| Confirmado | Relação examinada e válida para o estágio atual. |
| Condicionado | Relação depende de condição explícita. |
| Contestada | Existe divergência material sobre significado ou validade. |
| Parcial | Relação produz cobertura incompleta. |
| Bloqueada | Relação necessária não pode avançar. |
| Invalidada | Evidência ou mudança retirou sua validade. |
| Substituída | Outro vínculo passou a cumprir sua função. |
| Encerrada | Relação deixou de vigorar sem substituição necessária. |

### 24.3 Mudança de estado

Toda mudança material registra:

- objeto ou vínculo;
- estado anterior;
- novo estado;
- data;
- evento;
- fundamento ou evidência;
- responsável pelo registro;
- autoridade quando aplicável;
- efeito sobre cobertura e gate;
- próximo movimento.

### 24.4 Estado não herdado automaticamente

Entrega aceita não torna capacidade aceita. Incremento liberado não torna implantação liberada. Configuração estabilizada em um público não se torna estabilizada em todos os públicos.

## 25. Direções da rastreabilidade

A matriz precisa permitir seis movimentos.

### 25.1 Regressivo — origem

Parte de trabalho, decisão ou configuração e retorna às razões que justificam sua existência.

Pergunta:

> Por que isto existe?

### 25.2 Progressivo — realização

Parte de requisito, capacidade ou condição e acompanha o que ocorreu durante a implantação.

Pergunta:

> O que aconteceu com esta obrigação?

### 25.3 Horizontal — integração

Percorre dependências, interfaces, transferências, riscos e responsabilidades no mesmo estágio.

Pergunta:

> De que relações este resultado depende?

### 25.4 Temporal — mudança

Percorre versões, estados, substituições, reversões e vigências.

Pergunta:

> Como este objeto chegou à condição atual?

### 25.5 Decisório — autoridade

Percorre critérios, evidências, recomendações, decisões, condições e consequências.

Pergunta:

> Quem autorizou este movimento e com que fundamento?

### 25.6 Operacional — continuidade

Parte da configuração aceita e identifica sustentação, monitoramento, limite, suporte, retorno e aprendizagem.

Pergunta:

> Como esta capacidade continuará existindo depois da implantação?

## 26. Cadeias mínimas obrigatórias

As cadeias aplicáveis dependem do objeto e do estágio. A ausência material deve ser tratada, não ocultada.

### 26.1 Cadeia de origem e realização

```text
origem diagnóstica ou obrigação legítima
  → requisito
  → capacidade
  → componente ou interface
  → linha de base
  → incremento ou entrega
  → configuração implantada
```

### 26.2 Cadeia de trabalho

```text
capacidade ou condição
  → incremento
  → entrega
  → pacote de trabalho
  → item de backlog
  → resultado produzido
```

### 26.3 Cadeia de evidência e aceite

```text
objeto e versão
  → critério
  → método de verificação
  → evidência
  → validação
  → recomendação
  → decisão de gate ou aceite
```

### 26.4 Cadeia de risco e proteção

```text
risco ou falha possível
  → objeto exposto
  → controle ou resposta
  → responsável
  → evidência de funcionamento
  → risco residual
  → decisão
```

### 26.5 Cadeia de diferença

```text
linha de base e versão
  → configuração observada
  → diferença
  → classificação
  → impacto
  → decisão
  → correção, adaptação, retorno, aceite ou reversão
```

### 26.6 Cadeia de competência

```text
atividade ou decisão real
  → competência necessária
  → preparação
  → prática assistida
  → demonstração
  → autonomia ou suporte
  → responsabilidade operacional
```

### 26.7 Cadeia de transição

```text
configuração estabilizada
  → documento e procedimento vigente
  → responsável operacional
  → suporte e manutenção
  → indicador e limite
  → risco ou condição residual
  → aceite operacional
```

### 26.8 Cadeia de aprendizagem

```text
evento ou evidência
  → interpretação
  → decisão ou lição
  → destino metodológico
  → responsável por avaliar incorporação
```

## 27. Cobertura

Cobertura é a condição em que um objeto aplicável possui tratamento rastreável suficiente para a decisão ou estágio avaliado.

Cobertura não é simples existência de vínculo.

Para ser considerada válida, a cobertura deve possuir, conforme materialidade:

- objeto e versão identificados;
- relação semanticamente adequada;
- destino compatível;
- critério conhecido;
- estado atual;
- fundamento localizável;
- evidência quando o estágio exigir demonstração;
- decisão quando o vínculo alterar autoridade, risco, escopo ou configuração;
- responsável;
- ausência de contradição não tratada.

### 27.1 Cobertura de origem

Permite compreender por que o objeto existe.

### 27.2 Cobertura de realização

Permite compreender como requisito, capacidade ou condição será ou foi realizado.

### 27.3 Cobertura de evidência

Permite compreender como o resultado foi demonstrado.

### 27.4 Cobertura decisória

Permite compreender que autoridade autorizou movimento, mudança, liberação ou aceite.

### 27.5 Cobertura de configuração

Permite compreender em que versão e forma o resultado integrou a configuração real.

### 27.6 Cobertura de continuidade

Permite compreender como o objeto será sustentado, monitorado, corrigido, substituído ou encerrado.

## 28. Estados de cobertura

| Estado | Significado |
| --- | --- |
| Não avaliada | A cobertura ainda não foi examinada. |
| Planejada | Existe caminho previsto, ainda sem realização. |
| Em realização | Trabalho iniciou e permanece incompleto. |
| Demonstrada | Evidência suficiente foi produzida para o critério avaliado. |
| Completa | Todos os vínculos exigidos pelo estágio estão válidos. |
| Parcial | Parte material está atendida e a fronteira é explícita. |
| Condicionada | Cobertura depende de condição aceita, com responsável e consequência. |
| Contestada | Existe divergência material não resolvida. |
| Bloqueada | Lacuna impede avanço responsável. |
| Não coberta | Não existe tratamento suficiente. |
| Não aplicável | Exclusão possui fundamento, autoridade e escopo delimitado. |
| Substituída | Outra realização ou vínculo passou a produzir cobertura. |
| Invalidada | Evidência, versão ou mudança retirou validade anterior. |

### 28.1 Cobertura completa não é perfeição

Uma cobertura pode estar completa para um gate e permanecer condicionada para um horizonte posterior, desde que a fronteira, a autoridade e a consequência estejam registradas.

### 28.2 Classificação única por pergunta

O mesmo objeto pode possuir cobertura completa de origem e cobertura parcial de evidência. A matriz não deve condensar dimensões distintas em um único rótulo otimista.

## 29. Matriz principal

A fonte oficial dos vínculos pode utilizar a seguinte estrutura lógica:

| Vínculo | Origem e versão | Relação | Destino e versão | Cobertura | Estado | Critério | Evidência | Decisão | Responsável | Gate | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-VNC-001` | `CAP-ARQ-004 v1.0` | `é_realizada_por` | `IMP-2026-001-INC-001 v0.2` | Planejada | Confirmado | Capacidade delimitada | N/A neste estágio | Plano aprovado | Responsável pela implantação | `PI-2` | Estrutura analítica |
| `IMP-2026-001-VNC-002` | `IMP-2026-001-ENT-004 v1.0` | `atende_parcialmente` | `REQ-ARQ-007 v1.0` | Parcial | Condicionado | Critério do requisito | `IMP-2026-001-EVD-012` | `IMP-2026-001-GAT-004` | Responsável pelo incremento | `PI-4` | Registro de aceite |

A ordem física das colunas pode variar. As funções não devem desaparecer.

### 29.1 Uma linha por relação

Quando uma entrega atende três requisitos, registrar três vínculos ou representação estruturada equivalente. Uma célula com lista indistinta não permite estado, critério e evidência específicos por relação.

### 29.2 Conteúdo humano e estrutura processável

A matriz precisa ser legível por pessoas e suficientemente estruturada para filtros, verificações ou automações proporcionais.

## 30. Modelo reduzido

Implantação focal e de baixo risco pode utilizar:

| Origem | Relação | Destino | Estado de cobertura | Evidência ou decisão | Responsável |
| --- | --- | --- | --- | --- | --- |

O modelo reduzido somente é aceitável quando ainda permite:

- localizar a linha de base;
- reconstruir a origem do trabalho;
- reconhecer requisitos e capacidades aplicáveis;
- localizar critérios e evidências;
- identificar decisão e responsável;
- registrar diferenças;
- transferir configuração e condições.

Não reduzir:

- autoridade;
- versão;
- condição de gate;
- diferença material;
- risco residual;
- evidência de capacidade;
- responsabilidade operacional.

## 31. Visões derivadas

Uma matriz oficial pode gerar múltiplas visões.

| Visão | Pergunta |
| --- | --- |
| Origem e linha de base | O que foi recebido e por que é aplicável? |
| Requisitos e capacidades | O que precisa tornar-se real e com que cobertura? |
| Realização e fluxo | Que trabalho realiza cada obrigação? |
| Prontidão e gates | Que objetos, critérios e evidências sustentam a passagem? |
| Evidência, validação e aceite | O que foi demonstrado, por quem e com que resultado? |
| Decisão e mudança | Que autoridade alterou estado, plano ou configuração? |
| Configuração e diferenças | O que foi instalado e como difere do desenho? |
| Transição e operação | O que foi transferido e como será sustentado? |
| Impacto | O que uma mudança pode afetar? |
| Auditoria | Que lacunas, órfãos, conflitos ou vínculos inválidos existem? |

Visões derivadas devem declarar:

- matriz de origem;
- data de extração;
- filtros;
- versões consideradas;
- limitações;
- se o conteúdo é dinâmico ou congelado para decisão.

## 32. Visão de origem e linha de base

Deve permitir verificar:

- transição recebida;
- projeto de arquitetura;
- decisão de aprovação;
- linha de base;
- versões integrantes;
- requisitos obrigatórios;
- capacidades;
- componentes e interfaces;
- riscos, condições e dependências;
- validações e pendências;
- itens de implantação sugeridos;
- envelope de autonomia;
- resultado do `PI-1`.

Modelo:

| Objeto recebido | ID e versão | Pertence à linha de base? | Condição | Fonte | Tratamento na implantação | Estado |
| --- | --- | --- | --- | --- | --- | --- |

Objeto ausente não deve ser inventado. Registrar lacuna, efeito e rota.

## 33. Visão de requisitos e capacidades

Deve responder:

- todo requisito aplicável possui capacidade ou tratamento?
- toda capacidade possui manifestação verificável?
- requisitos parciais possuem fronteira explícita?
- capacidades existentes a preservar possuem proteção durante a transição?
- requisitos excluídos possuem autoridade e fundamento?
- novas necessidades surgidas na prática foram encaminhadas?

Modelo:

| Requisito | Capacidade | Componente | Incremento ou entrega | Critério | Cobertura atual | Evidência | Diferença | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

## 34. Visão de realização e fluxo

Relaciona:

- implantação;
- projeto;
- onda;
- incremento;
- entrega;
- pacote de trabalho;
- item de backlog;
- dependência;
- marco;
- responsável;
- configuração afetada;
- evidência esperada;
- estado real.

Modelo:

| Unidade | Pertence a | Origem arquitetural | Produz | Dependência | Responsável | Critério de conclusão | Estado | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

### 34.1 Trabalho sem origem

Pode representar:

- necessidade administrativa legítima;
- trabalho de implantação esquecido na arquitetura;
- expansão indevida de escopo;
- preferência de ferramenta;
- retrabalho;
- correção;
- descoberta material.

Cada caso recebe classificação e decisão.

### 34.2 Origem sem trabalho

Pode representar:

- requisito fora do incremento atual;
- dependência de outra onda;
- item adiado;
- lacuna de decomposição;
- exclusão autorizada;
- incapacidade de realização.

A matriz torna a condição visível antes do gate aplicável.

## 35. Visão de prontidão e gates

Relaciona objeto submetido, versão, critérios, evidências, lacunas, riscos, condições, recomendação, decisão, autoridade e consequência.

Modelo:

| Ocorrência | Gate | Objeto e versão | Critérios | Evidências | Lacunas | Risco residual | Recomendação | Decisão | Condições | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

### 35.1 Repetição

`PI-2`, `PI-3`, `PI-4` e `PI-5` podem ocorrer por projeto, onda, incremento, capacidade ou transição parcial.

Cada ocorrência precisa distinguir:

- escopo;
- versão;
- data;
- evidência disponível;
- resultado;
- validade;
- relação com ocorrência anterior.

### 35.2 Gate reaberto

Nova evidência, mudança de contexto, diferença material ou invalidade pode reabrir gate. O resultado anterior permanece no histórico.

## 36. Visão de evidência, validação e aceite

Relaciona:

- objeto e versão;
- afirmação ou critério;
- método;
- contexto;
- evidência;
- qualidade;
- resultado;
- divergência;
- validador;
- recomendação;
- autoridade de aceite;
- estado posterior.

Modelo:

| Objeto | Critério | Método | Evidência | Contexto | Resultado | Qualidade | Divergência | Validador | Aceite | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

### 36.1 Evidência múltipla

Capacidade sociotécnica pode exigir combinação de:

- teste de entrega;
- observação de uso;
- demonstração de competência;
- caso normal;
- exceção;
- falha e recuperação;
- indicador;
- percepção de carga;
- revisão de segurança ou especialidade.

Uma única evidência não deve receber peso universal.

## 37. Visão de decisão e mudança

Deve distinguir:

- decisão de planejamento;
- decisão de gate;
- correção de execução;
- adaptação autorizada;
- mudança de plano;
- mudança arquitetural;
- ação emergencial;
- contenção;
- suspensão;
- reversão;
- aceite de risco;
- transferência.

Modelo:

| Decisão | Tipo | Objeto afetado | Estado anterior | Evidência | Autoridade | Consequência | Nova versão | Retorno | Vigência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

Mudança tomada em reunião somente passa a integrar a matriz depois de registro recuperável.

## 38. Visão de configuração e diferenças

Compara:

- linha de base arquitetural;
- versão preparada;
- versão produzida;
- versão liberada;
- versão aceita;
- versão estabilizada;
- versão transferida.

Modelo:

| Objeto arquitetural | Versão de referência | Configuração observada | Diferença | Classificação | Impacto | Evidência | Decisão | Estado final |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

### 38.1 Toda diferença recebe destino

Destinos possíveis:

- corrigir;
- aceitar como adaptação autorizada;
- incorporar sob condição;
- retornar ao Módulo 3;
- reverter;
- substituir;
- observar durante estabilização;
- transferir como risco ou pendência aceita;
- rejeitar a configuração.

### 38.2 Ausência de diferença declarada

“Nenhuma diferença identificada” somente é válida quando houve comparação entre versões e objetos materiais. Não deve ser campo automático.

## 39. Visão de transição, operação e aprendizagem

Relaciona:

- configuração transferida;
- capacidade correspondente;
- responsáveis operacionais;
- documentos e procedimentos vigentes;
- competências demonstradas;
- acessos e permissões;
- suporte e manutenção;
- indicadores e limites;
- riscos e condições residuais;
- critérios de retorno;
- aceite `PI-5`;
- aprendizagem e destino.

Modelo:

| Configuração | Capacidade | Responsável operacional | Sustentação | Indicador | Limite e resposta | Risco ou condição | Aceite | Destino da aprendizagem |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

Responsabilidade não deve ser inferida pela presença de nome em reunião, organograma ou comunicação.

## 40. Contrato da evidência na matriz

A matriz referencia evidência; não redefine a epistemologia do Módulo 2 nem substitui o registro detalhado.

Evidência material deve permitir localizar:

- ID;
- objeto;
- critério;
- contexto;
- método;
- fonte;
- data;
- versão;
- resultado;
- responsável pela coleta;
- responsável pela interpretação;
- ressalvas;
- localização;
- decisão apoiada.

### 40.1 Classes de evidência

| Classe | Demonstra | Não demonstra isoladamente |
| --- | --- | --- |
| Atividade | Ação ocorreu. | Entrega suficiente ou capacidade. |
| Entrega | Objeto foi produzido conforme especificação. | Uso real ou resultado organizacional. |
| Integração | Elementos funcionam em conjunto no contexto testado. | Estabilidade futura universal. |
| Prontidão | Condições conhecidas existem para avançar. | Resultado após exposição. |
| Capacidade | Combinação produz resultado sob condições definidas. | Benefício sustentado em qualquer contexto. |
| Competência | Pessoa ou grupo demonstra atuação suficiente. | Autonomia irrestrita ou permanência da competência. |
| Adoção | Uso material ocorre. | Validade, segurança ou benefício. |
| Controle | Proteção funciona no cenário avaliado. | Eliminação do risco. |
| Estabilidade | Funcionamento se mantém sob exposição suficiente. | Ausência permanente de falha. |
| Transferência | Operação recebeu e compreendeu responsabilidade delimitada. | Sustentação futura sem acompanhamento. |

### 40.2 Evidência negativa

Falha, atalho, recusa, não uso, divergência, sobrecarga, dado incorreto, recuperação impossível e resultado inesperado também integram a matriz quando materiais.

## 41. Lacunas de rastreabilidade

Uma lacuna existe quando:

- objeto obrigatório não possui origem;
- requisito aplicável não possui realização;
- entrega não possui capacidade ou critério;
- evidência não resolve para fonte;
- gate não possui objeto ou versão;
- diferença não possui decisão;
- mudança não possui autoridade;
- configuração não possui manifesto;
- risco residual não possui responsável;
- transição não possui aceite;
- link aponta para arquivo inexistente;
- objeto de origem mudou sem sincronização;
- relação está ambígua;
- cobertura foi declarada sem demonstração suficiente.

### 41.1 Registro da lacuna

Cada lacuna material registra:

- ID;
- descrição;
- objetos afetados;
- cadeia interrompida;
- classificação;
- efeito;
- gate afetado;
- ação;
- responsável;
- autoridade;
- prazo ou gatilho;
- estado;
- resultado;
- decisão de aceitação quando aplicável.

### 41.2 Classificação

| Classe | Efeito típico |
| --- | --- |
| Crítica | Impede decisão, liberação, aceite ou transferência responsável. |
| Material | Reduz segurança, governança ou reconstrução e exige tratamento ou aceite. |
| Relevante | Não bloqueia isoladamente, mas precisa de plano e responsável. |
| Editorial | Afeta forma, link ou clareza sem alterar conteúdo material. |

### 41.3 Estado

- aberta;
- em análise;
- em tratamento;
- parcialmente resolvida;
- resolvida;
- aceita com condição;
- não obtível;
- fora do escopo por decisão;
- substituída;
- encerrada.

## 42. Objetos órfãos

Exemplos:

- requisito sem origem ou decisão de legitimidade;
- capacidade sem requisito, problema, valor ou obrigação;
- componente sem capacidade;
- entrega sem origem arquitetural ou de governança;
- item de backlog sem pacote, entrega ou correção;
- teste sem objeto e critério;
- evidência sem contexto;
- decisão sem objeto;
- risco sem exposição relacionada;
- controle sem risco ou requisito;
- diferença sem referência comparada;
- configuração sem entregas aceitas;
- indicador sem capacidade, limite ou resposta;
- aprendizagem sem evento ou destino;
- responsável sem autoridade ou objeto.

### 42.1 Órfão legítimo temporário

Durante descoberta, um objeto pode anteceder a definição de seu vínculo. Deve possuir estado temporário, responsável e prazo de classificação.

### 42.2 Órfão material persistente

Exige:

- vinculação;
- exclusão fundamentada;
- retorno ao módulo competente;
- cancelamento;
- decisão de risco ou lacuna.

## 43. Conflitos e divergências

A matriz deve preservar:

- requisitos incompatíveis;
- versões concorrentes;
- critérios divergentes;
- evidências contraditórias;
- autoridades em conflito;
- diferença de interpretação;
- operação prescrita e prática real;
- aceite técnico sem aceite humano ou operacional;
- pressão de prazo incompatível com prontidão;
- interesse de fornecedor incompatível com continuidade;
- decisão que não corresponde à linha de base.

### 43.1 Registro

| Campo | Conteúdo |
| --- | --- |
| Objetos | IDs e versões em tensão. |
| Natureza | Semântica, técnica, humana, decisória, temporal ou documental. |
| Evidências | Fontes de cada posição. |
| Efeito | Cobertura, risco, gate ou configuração afetados. |
| Autoridade | Quem decide ou encaminha. |
| Tratamento | Verificação, especialista, decisão, retorno ou aceitação. |
| Estado | Aberto, contido, resolvido, aceito ou transferido. |

Resolver não significa apagar. O histórico preserva posições e decisão.

## 44. Exceção e não aplicabilidade

“Não aplicável” exige:

- objeto ou classe excluída;
- escopo da exclusão;
- fundamento;
- autoridade;
- evidência contextual quando necessária;
- efeito sobre risco e cobertura;
- evento que reabre a avaliação.

Não aplicabilidade não deve ser usada para:

- ocultar trabalho não realizado;
- reduzir escopo depois do resultado;
- dispensar requisito obrigatório;
- evitar validação difícil;
- excluir pessoas afetadas;
- converter falta de evidência em ausência de necessidade.

Exceção operacional recorrente pode revelar componente, interface, competência ou requisito ausente e exigir retorno ao Módulo 3.

## 45. Análise de impacto

Antes de alterar objeto ou vínculo material, percorrer:

1. objetos regressivos que justificam sua existência;
2. objetos progressivos que dependem dele;
3. interfaces e dependências horizontais;
4. versões e estados relacionados;
5. critérios e evidências que podem perder validade;
6. gates já decididos;
7. riscos e controles;
8. configuração liberada ou aceita;
9. pessoas, competências e documentos afetados;
10. operação e suporte;
11. retorno ao Módulo 3;
12. necessidade de revalidação, nova liberação ou reversão.

Modelo:

| Mudança proposta | Objeto direto | Caminhos afetados | Evidências invalidadas | Gate afetado | Risco | Autoridade | Ação |
| --- | --- | --- | --- | --- | --- | --- | --- |

### 45.1 Profundidade

Correção editorial pode exigir verificação local. Mudança de requisito, interface crítica, autoridade, uso de dados, IA, segurança ou configuração aceita exige análise ampliada.

### 45.2 Resultado

- sem impacto material;
- correção de execução;
- adaptação autorizada;
- mudança de plano;
- mudança arquitetural;
- revalidação necessária;
- gate reaberto;
- reversão ou contenção;
- especialidade necessária.

## 46. Linha de base, configuração e versionamento

A matriz deve distinguir:

- linha de base arquitetural recebida;
- versão de trabalho;
- versão candidata à liberação;
- versão liberada;
- versão aceita;
- versão estabilizada;
- versão transferida;
- versão substituída;
- versão revertida.

### 46.1 Vínculo com versão

Relação material deve indicar a versão relevante dos objetos. “Requisito atendido” sem versão pode tornar-se falso depois de mudança.

### 46.2 Linha de base arquitetural

A matriz referencia o manifesto autorizado. Não mantém uma segunda lista oficial concorrente.

### 46.3 Configuração implantada

O registro da configuração implantada governa sua descrição. A matriz governa relações de origem, realização, evidência, decisão e transferência.

### 46.4 Substituição

Nova versão não apaga a anterior. Deve indicar:

- objeto substituído;
- motivo;
- decisão;
- data de vigência;
- migração;
- efeito sobre evidências;
- efeito sobre operação;
- possibilidade de retorno.

## 47. Temporalidade e histórico

A matriz representa a implantação em movimento.

### 47.1 Estado atual

Mostra vínculos e cobertura vigentes.

### 47.2 Histórico

Preserva mudanças materiais de estado, versão, relação, evidência e decisão.

### 47.3 Fotografia de gate

Cada gate deve ser capaz de resolver a visão da matriz considerada no momento da decisão.

### 47.4 Vigência

Vínculo pode possuir:

- início de vigência;
- fim de vigência;
- evento de ativação;
- evento de encerramento;
- condição de reabertura.

### 47.5 Não reescrever o passado

Atualização posterior não deve fazer parecer que uma evidência, critério ou relação já existia quando a decisão anterior foi tomada.

## 48. Eventos de sincronização

A matriz deve ser revisada quando ocorrer:

- aceite ou devolução no `PI-1`;
- nova versão da linha de base;
- alteração de escopo;
- decomposição ou recomposição de incremento;
- criação, divisão, fusão ou cancelamento de entrega;
- mudança de requisito, componente ou interface;
- identificação de risco ou dependência material;
- prontidão para `PI-2`;
- resultado de teste material;
- prontidão para `PI-3`;
- liberação, contenção ou reversão;
- evidência negativa ou divergente;
- mudança de plano;
- correção ou adaptação autorizada;
- descoberta de mudança arquitetural;
- decisão de `PI-4`;
- consolidação da configuração implantada;
- conclusão de período de estabilização;
- preparação e decisão de `PI-5`;
- transferência de risco ou condição;
- encerramento ou reabertura;
- substituição de fonte oficial;
- aprendizagem que altere método ou arquitetura.

### 48.1 Responsabilidade de atualização

Cada evento possui responsável por registrar e prazo ou condição de sincronização. Atualização “ao final” não é suficiente para objeto que participa de gate anterior.

### 48.2 Verificação de sincronização

Antes de gate, confirmar:

- fontes acessíveis;
- versões correspondentes;
- estados atualizados;
- vínculos materiais presentes;
- lacunas classificadas;
- decisões incorporadas;
- visões derivadas regeneradas quando aplicável.

## 49. Cobertura nos gates

### 49.1 `PI-1` — aceite da transição

Verificar se:

- implantação resolve para transição identificada;
- transição resolve para linha de base autorizada;
- linha de base resolve para versões exatas;
- capacidades, requisitos, componentes e interfaces materiais estão localizáveis;
- riscos, dependências, condições e decisões abertas possuem referência;
- critérios de aceite e envelope de autonomia estão claros;
- lacunas de entrada possuem classificação e rota;
- autoridade da transição está registrada.

Lacuna que impede compreender o que será implantado bloqueia ou condiciona o `PI-1`.

### 49.2 `PI-2` — prontidão para executar

Verificar se:

- obrigações aplicáveis possuem caminho de realização;
- trabalho material possui origem;
- incrementos e entregas possuem responsáveis, critérios e dependências;
- riscos e condições possuem tratamento;
- preparação humana, técnica, documental e operacional foi planejada;
- evidências e validações esperadas estão definidas;
- liberação, contenção e reversão possuem caminho;
- lacunas materiais possuem decisão;
- nenhuma mudança arquitetural está sendo absorvida como detalhe de execução.

### 49.3 `PI-3` — prontidão para liberar

Verificar se:

- objeto e versão estão identificados;
- entregas integrantes estão produzidas e verificadas;
- critérios de liberação possuem evidência;
- pessoas, dados, documentos, acessos, controles e suporte estão vinculados;
- riscos residuais possuem decisão;
- escopo de exposição e critérios de parada estão claros;
- reversão ou contingência é realizável;
- divergências materiais receberam tratamento;
- configuração candidata está registrada.

### 49.4 `PI-4` — aceite da implantação

Verificar se:

- capacidade possui evidência suficiente no contexto delimitado;
- competência, efeito humano, uso e controles foram examinados quando materiais;
- diferenças foram comparadas e classificadas;
- mudanças possuem autoridade correspondente;
- evidências negativas permanecem visíveis;
- aceite parcial possui fronteira verificável;
- configuração aceita possui versão;
- riscos e condições residuais possuem destino.

### 49.5 `PI-5` — transição para operação

Verificar se:

- configuração estabilizada resolve para capacidades, entregas e decisões;
- responsáveis operacionais aceitaram objetos delimitados;
- documentos, dados, acessos e procedimentos vigentes estão localizáveis;
- competências necessárias foram demonstradas;
- suporte, manutenção, fornecedor e escalonamento estão definidos;
- indicadores possuem fonte, limite, responsável e resposta;
- riscos, pendências e condições possuem aceite e gatilho;
- critérios de retorno ao Módulo 3 ou 4 estão claros;
- aprendizagem possui destino;
- aceite operacional está registrado.

### 49.6 Regra comum

Cobertura não substitui o julgamento do gate. Ela demonstra se o material necessário pode ser reconstruído e onde permanecem lacunas.

## 50. Papéis e autoridade

| Papel | Responsabilidade na matriz |
| --- | --- |
| Responsável pela implantação | Assegurar que a matriz exista, acompanhe o ciclo e participe dos gates. |
| Custodiante da matriz | Manter estrutura, IDs, fontes, versões, estados e histórico. |
| Responsável pelo incremento | Atualizar realização, evidências, diferenças e estado do escopo sob sua coordenação. |
| Responsável pela arquitetura | Interpretar linha de base e receber retornos materiais ao Módulo 3. |
| Responsável por evidência ou validação | Preservar método, resultado, ressalvas e referência. |
| Autoridade de gate | Decidir sobre objeto e versão com base em critérios e evidências. |
| Responsável operacional | Validar sustentação, condições e transferência no `PI-5`. |
| Especialista | Verificar matéria que excede competência do projeto. |
| Pessoa afetada ou representante | Contribuir com experiência, efeito, divergência e validação situada. |
| IA | Apoiar organização e verificação sem autoridade decisória. |

### 50.1 Custódia não é autoria universal

O custodiante pode corrigir forma, link e consistência. Não pode alterar silenciosamente conteúdo de requisito, decisão, evidência, risco ou configuração cuja autoridade pertença a outro papel.

### 50.2 Segregação

Quando a mesma pessoa registra, valida e decide, a combinação deve ser visível e receber controle proporcional.

### 50.3 Discordância

Responsável pela matriz não pode apagar posição divergente para produzir visão única. Deve registrar estado, evidência e autoridade de tratamento.

## 51. Proporcionalidade

### 51.1 Implantação focal

Pode utilizar:

- uma matriz reduzida;
- objetos e vínculos no mesmo arquivo;
- um conjunto pequeno de visões;
- abreviações dentro do dossiê;
- verificação manual.

Deve preservar:

- linha de base;
- origem do trabalho;
- capacidade e requisito;
- critério e evidência;
- decisão e responsável;
- diferença;
- configuração aceita;
- transferência.

### 51.2 Implantação funcional

Exige normalmente:

- matriz principal;
- visões de requisitos, realização, gates, evidência e configuração;
- sincronização com riscos e mudanças;
- múltiplos incrementos;
- histórico de gate;
- rastreabilidade de competência e transição.

### 51.3 Implantação sistêmica

Pode exigir:

- registros estruturados separados;
- programa, projetos e ondas;
- matrizes por frente com consolidação governada;
- controle de interfaces;
- versionamento ampliado;
- análise automatizada;
- validações especializadas;
- rastreabilidade por público, unidade, ambiente ou jurisdição;
- fotografias formais por gate;
- auditoria independente.

### 51.4 Intensificadores

Ampliar controle quando houver:

- alto impacto humano;
- redistribuição de autoridade;
- dados pessoais, sensíveis ou confidenciais;
- segurança ou obrigação jurídica;
- IA com autonomia relevante;
- múltiplos sistemas e integrações;
- migração irreversível;
- dependência de fornecedor;
- continuidade crítica;
- público amplo;
- múltiplas organizações;
- baixa reversibilidade;
- grande incerteza;
- conflito material.

### 51.5 Regra de redução

Reduzir quantidade de campos, visões ou arquivos antes de reduzir origem, autoridade, evidência, diferença, responsabilidade ou memória.

## 52. Indicadores de rastreabilidade

Indicadores podem apoiar gestão da matriz. Não devem transformar cobertura em nota de sucesso da implantação.

### 52.1 Cobertura de origem

```text
objetos materiais com caminho regressivo válido
÷ objetos materiais aplicáveis
```

### 52.2 Cobertura de realização

```text
obrigações aplicáveis com caminho de realização válido
÷ obrigações aplicáveis
```

### 52.3 Cobertura de evidência

```text
critérios vencidos com evidência suficiente vinculada
÷ critérios vencidos aplicáveis
```

### 52.4 Cobertura de decisão

```text
movimentos materiais com decisão recuperável
÷ movimentos materiais que exigem decisão
```

### 52.5 Cobertura de configuração

```text
objetos aceitos resolvidos na configuração versionada
÷ objetos aceitos aplicáveis
```

### 52.6 Cobertura de transição

```text
objetos transferidos com responsável, sustentação e aceite
÷ objetos previstos para transferência
```

### 52.7 Indicadores de qualidade

- vínculos inválidos;
- objetos órfãos;
- links quebrados;
- versões ambíguas;
- lacunas críticas abertas;
- vínculos sem responsável;
- cobertura declarada sem evidência;
- decisões sem incorporação;
- diferenças sem destino;
- condições vencidas;
- tempo entre evento material e atualização;
- gates reabertos por informação já disponível e não vinculada.

### 52.8 Regras

1. Denominador deve ser explícito.
2. “Não aplicável” exige fundamento.
3. Objeto duplicado não aumenta cobertura.
4. Vínculo inválido não conta.
5. Cobertura parcial não conta como completa.
6. Percentual não substitui análise de materialidade.
7. Um único requisito crítico descoberto pode impedir gate mesmo com alta cobertura numérica.
8. Não combinar dimensões em índice composto sem necessidade, pesos e limites explícitos.

## 53. Fonte oficial e armazenamento

Cada dossiê deve declarar:

- ID da matriz;
- arquivo ou sistema oficial;
- formato;
- responsável;
- regra de atualização;
- regra de versionamento;
- fonte dos objetos importados;
- visões derivadas;
- política de acesso;
- forma de exportação;
- forma de preservação;
- fotografia ou versão usada em cada gate.

### 53.1 Uma fonte oficial

Planilha, banco, documento estruturado ou ferramenta pode ser utilizado. Somente uma fonte governa os vínculos vigentes.

### 53.2 Visão exportada

Exportação para reunião, PDF, relatório ou apresentação deve indicar data e origem. Alteração na exportação não atualiza a matriz oficial.

### 53.3 Link recuperável

Fonte deve permanecer acessível às pessoas autorizadas durante o período necessário. Link que depende de conta pessoal, mensagem privada ou sessão temporária exige correção.

### 53.4 Continuidade

Estrutura não deve depender de conhecimento privado do custodiante nem de ferramenta sem portabilidade proporcional.

## 54. Sensibilidade, acesso e proteção

A matriz pode revelar:

- riscos;
- vulnerabilidades;
- dados pessoais;
- decisões estratégicas;
- custos;
- fornecedores;
- credenciais ou acessos;
- conflitos;
- desempenho individual;
- propriedade intelectual;
- configuração de IA;
- informação jurídica ou de segurança.

### 54.1 Minimização de conteúdo sensível

Referenciar fonte protegida quando copiar conteúdo ampliaria exposição.

### 54.2 Acesso por necessidade

Visões podem possuir públicos distintos. A existência de recorte não deve romper a fonte oficial nem ocultar condição material de quem decide.

### 54.3 Segredo não é ausência de registro

Informação restrita pode utilizar classificação, referência protegida e registro mínimo. Não deve desaparecer quando necessária à governança.

### 54.4 IA e conteúdo sensível

Dados inseridos em sistema de IA devem respeitar finalidade, autorização, minimização, contrato, retenção, proteção e política aplicável.

## 55. Minimização documental

A matriz deve reduzir repetição por meio de referências, não reduzir capacidade de reconstrução.

### 55.1 Não copiar

- descrição integral de requisito;
- justificativa integral de decisão;
- evidência bruta;
- conteúdo completo de teste;
- documento operacional;
- relatório de risco;
- narrativa de reunião.

### 55.2 Registrar

- ID;
- tipo;
- versão;
- relação;
- estado;
- cobertura;
- fonte;
- critério;
- evidência ou decisão aplicável;
- responsável;
- ressalva material.

### 55.3 Critério de suficiência

Outra pessoa deve conseguir localizar e compreender o caminho sem pedir reconstrução oral a quem criou a matriz.

## 56. Participação da inteligência artificial

A IA pode apoiar:

- extração inicial de referências;
- normalização de IDs;
- sugestão de tipos de relação;
- identificação de objetos órfãos;
- detecção de duplicidades;
- comparação de versões;
- identificação de links quebrados;
- busca de vínculos sem evidência;
- verificação de cardinalidade;
- geração de visões derivadas;
- análise preliminar de impacto;
- detecção de inconsistência entre matriz, cronograma, backlog e registros;
- preparação de perguntas de gate;
- síntese de lacunas e divergências.

### 56.1 A IA não deve

- inventar objeto ausente;
- criar origem inexistente;
- renumerar objeto herdado;
- transformar menção em vínculo material;
- declarar cobertura completa;
- avaliar suficiência de evidência sem revisão competente;
- classificar mudança como não material de modo autônomo;
- aceitar risco;
- aprovar gate;
- autorizar liberação;
- aceitar diferença;
- transferir responsabilidade;
- apagar divergência;
- alterar fonte oficial sem controle humano.

### 56.2 Registro da participação

Quando material, registrar:

- sistema e versão;
- função;
- escopo de entrada;
- dados ou classes de dados;
- regra ou instrução utilizada;
- resultado produzido;
- limitações;
- pessoa revisora;
- correções humanas;
- decisão final;
- data.

### 56.3 Resultado probabilístico

Sugestão de relação ou lacuna produzida por IA permanece proposta até verificação humana e resolução à fonte.

## 57. Automação da matriz

Automação pode:

- validar formato de ID;
- verificar existência de arquivo;
- comparar versão declarada e fonte;
- sinalizar objeto órfão;
- listar requisitos sem realização;
- listar entregas sem origem;
- identificar vínculo vencido;
- gerar visão por gate;
- detectar condição sem responsável;
- apontar diferença sem decisão;
- calcular indicadores com denominador explícito;
- preservar fotografia versionada.

### 57.1 Regras automatizáveis

Regra deve declarar:

- objeto;
- condição;
- fonte;
- resultado;
- severidade;
- exceção;
- responsável por tratar;
- limite da automação.

### 57.2 Resultado da automação

Classificações possíveis:

- válida;
- inválida;
- aviso;
- informação insuficiente;
- exceção registrada;
- revisão humana necessária.

### 57.3 Automação não substitui semântica

Uma ferramenta pode confirmar que dois IDs existem. Não pode concluir, apenas por isso, que a relação entre eles é correta ou material.

## 58. Critérios de qualidade

### 58.1 Identidade

Objetos e vínculos materiais possuem identificação estável.

### 58.2 Correção

Relações correspondem ao conteúdo das fontes.

### 58.3 Completude suficiente

Cadeias necessárias ao estágio estão cobertas ou possuem lacuna tratada.

### 58.4 Atualidade

Estados, versões e fontes correspondem à realidade vigente.

### 58.5 Consistência

O mesmo objeto não recebe estados incompatíveis sem explicação.

### 58.6 Semântica

Relações possuem significado controlado e direção correta.

### 58.7 Reconstrução

Outra pessoa consegue percorrer origem, realização, evidência, decisão e destino.

### 58.8 Materialidade

Detalhamento se concentra no que altera resultado, risco, autoridade, configuração ou continuidade.

### 58.9 Proporcionalidade

Controle corresponde a escopo, risco e reversibilidade.

### 58.10 Transparência

Cobertura parcial, lacuna, divergência e diferença permanecem visíveis.

### 58.11 Responsabilidade

Objetos, vínculos, condições e atualizações materiais possuem responsáveis.

### 58.12 Governabilidade

Autoridades, decisões e efeitos podem ser localizados.

### 58.13 Verificabilidade

Afirmações de atendimento, capacidade, estabilidade e transferência resolvem para evidência.

### 58.14 Temporalidade

Histórico e vigência permitem compreender mudança ao longo do ciclo.

### 58.15 Continuidade

Configuração aceita resolve para sustentação operacional.

### 58.16 Segurança

Acesso, sensibilidade e dados recebem proteção proporcional.

### 58.17 Compreensibilidade

Pessoas autorizadas conseguem interpretar a matriz sem depender de código privado ou jargão indefinido.

### 58.18 Portabilidade

Os vínculos podem ser preservados ou exportados sem aprisionamento desnecessário.

## 59. Teste de reconstrução

Selecionar amostra proporcional de objetos materiais e realizar percursos.

### 59.1 Percurso regressivo

Partir da configuração transferida e localizar:

1. entrega ou incremento de origem;
2. critério e evidência;
3. gate e decisão;
4. componente e capacidade;
5. requisito;
6. linha de base;
7. origem diagnóstica ou obrigação legítima.

### 59.2 Percurso progressivo

Partir de requisito ou condição e localizar:

1. capacidade;
2. realização;
3. preparação;
4. evidência;
5. decisão;
6. configuração;
7. operação.

### 59.3 Percurso de mudança

Partir de diferença ou decisão e localizar:

1. versão anterior;
2. objeto afetado;
3. impacto;
4. autoridade;
5. nova versão;
6. revalidação;
7. efeito operacional.

### 59.4 Percurso de condição residual

Partir de risco ou pendência transferida e localizar:

1. origem;
2. decisão de aceitação;
3. responsável;
4. limite;
5. resposta;
6. gatilho de retorno;
7. aceite operacional.

### 59.5 Resultado

- reconstrução suficiente;
- reconstrução parcial;
- reconstrução bloqueada;
- fonte indisponível;
- versão ambígua;
- relação incorreta;
- atualização necessária.

Falha material no teste deve gerar lacuna e tratamento antes do gate correspondente.

## 60. Antipadrões

### 60.1 Matriz de encerramento

Criar vínculos depois das decisões para justificar retrospectivamente o que ocorreu.

### 60.2 Matriz como inventário

Listar objetos sem relações semanticamente explícitas.

### 60.3 Matriz como relatório

Copiar narrativas extensas e perder estrutura de origem, relação e destino.

### 60.4 Um requisito por linha com listas em todas as colunas

Condensar múltiplos objetos e impedir estado, evidência e decisão por vínculo.

### 60.5 Link como evidência

Presumir que arquivo existente demonstra atendimento.

### 60.6 Cobertura por menção

Contar objeto citado no mesmo documento como coberto.

### 60.7 Cem por cento como objetivo isolado

Forçar classificação otimista, criar vínculos artificiais ou excluir itens difíceis para melhorar percentual.

### 60.8 Versão flutuante

Relacionar objetos sem saber que formulação foi avaliada.

### 60.9 Trabalho sem origem

Executar preferência, ferramenta ou expansão de escopo como se fossem consequência inevitável da arquitetura.

### 60.10 Origem sem destino

Preservar requisito obrigatório sem realização, adiamento ou decisão.

### 60.11 Evidência sem critério

Coletar registros e escolher depois o que parecem demonstrar.

### 60.12 Gate sem fotografia

Atualizar a matriz e perder o conjunto de informações considerado na decisão anterior.

### 60.13 Diferença silenciosa

Alterar configuração e manter vínculo como se a linha de base tivesse sido realizada literalmente.

### 60.14 Retorno informal ao Módulo 3

Conversar sobre mudança arquitetural sem registro, decisão e nova referência.

### 60.15 Responsável nominal

Inserir nome sem objeto, autoridade, aceite, capacidade ou disponibilidade.

### 60.16 Não aplicável defensivo

Usar exclusão para esconder ausência de trabalho ou evidência.

### 60.17 Automação sem semântica

Gerar vínculos por similaridade textual e tratá-los como confirmados.

### 60.18 IA como autora da cobertura

Aceitar classificação produzida por modelo sem resolução à fonte e julgamento humano.

### 60.19 Matriz paralela

Manter planilha, documento e ferramenta com vínculos divergentes sem fonte oficial declarada.

### 60.20 Herança sem atualização

Continuar usando versão arquitetural substituída.

### 60.21 Burocracia de baixa utilidade

Registrar microtarefas sem melhorar decisão, risco, configuração ou continuidade.

### 60.22 Operação como coluna final

Escrever “Operação” como destino sem responsável, sustentação, indicador, limite e aceite.

## 61. Perguntas de controle

### 61.1 Identidade e fonte

1. A implantação e a matriz possuem IDs inequívocos?
2. A fonte oficial está declarada?
3. Objetos importados preservam IDs e versões?
4. Links resolvem para fontes acessíveis às pessoas autorizadas?
5. Visões derivadas declaram data, filtro e origem?

### 61.2 Origem e linha de base

6. A transição resolve para linha de base autorizada?
7. As versões da linha de base são exatas?
8. Toda obrigação material possui origem ou legitimidade explícita?
9. O envelope de autonomia está localizável?
10. Lacunas de entrada foram tratadas no `PI-1`?

### 61.3 Realização

11. Toda capacidade aplicável possui caminho de realização?
12. Todo trabalho material possui origem?
13. Decomposição preserva componentes e interfaces?
14. Dependências possuem responsáveis e estados?
15. Entregas possuem critérios anteriores à produção?

### 61.4 Evidência e decisão

16. Cada afirmação de atendimento resolve para evidência suficiente?
17. Evidências negativas permanecem visíveis?
18. Gate identifica objeto e versão?
19. Condições possuem responsável, prazo ou gatilho e consequência?
20. Autoridade corresponde ao tipo de decisão?

### 61.5 Mudança e configuração

21. Diferenças entre desenho e realidade foram comparadas?
22. Correção, adaptação e mudança arquitetural estão distinguidas?
23. Mudança material retornou ao Módulo 3?
24. Configuração aceita possui manifesto e versão?
25. Evidências invalidadas por mudança foram reavaliadas?

### 61.6 Transição e continuidade

26. Responsáveis operacionais aceitaram objetos delimitados?
27. Documentos, acessos, suporte e manutenção estão vigentes?
28. Indicadores possuem limite e resposta?
29. Riscos e condições residuais possuem destino?
30. Critérios de retorno estão claros?

### 61.7 Qualidade e proporcionalidade

31. Existem objetos órfãos?
32. Existem vínculos sem significado ou sem responsável?
33. Cobertura parcial está explícita?
34. O nível de detalhe é útil à decisão e à continuidade?
35. A matriz pode ser reconstruída por outra pessoa?
36. Conteúdo sensível está protegido?
37. A participação da IA está registrada quando material?
38. O histórico preserva o que se sabia em cada gate?
39. A matriz revela lacunas ou apenas confirma sucesso?
40. Algum campo pode ser removido sem perder governança?

## 62. Invariantes da matriz

### 62.1 Invariante 1

Nenhum objeto herdado deve ser renumerado para caber na implantação.

### 62.2 Invariante 2

Nenhum trabalho material deve permanecer sem origem, classificação ou decisão.

### 62.3 Invariante 3

Nenhuma obrigação aplicável deve permanecer sem destino explícito.

### 62.4 Invariante 4

Nenhum vínculo material deve existir apenas como associação temática.

### 62.5 Invariante 5

Nenhuma declaração de cobertura completa deve existir sem critério e verificação suficientes ao estágio.

### 62.6 Invariante 6

Nenhuma evidência deve perder sua fonte, contexto, data, versão e limite.

### 62.7 Invariante 7

Nenhum gate deve ser decidido sobre objeto ou versão ambíguos.

### 62.8 Invariante 8

Nenhuma condição deve autorizar avanço sem responsável, prazo ou gatilho e consequência.

### 62.9 Invariante 9

Nenhuma diferença material deve permanecer sem classificação, impacto e destino.

### 62.10 Invariante 10

Nenhuma mudança arquitetural deve ser incorporada silenciosamente pelo Módulo 4.

### 62.11 Invariante 11

Nenhuma versão nova deve apagar a versão considerada por decisão anterior.

### 62.12 Invariante 12

Nenhuma configuração deve ser declarada aceita apenas porque suas entregas foram concluídas.

### 62.13 Invariante 13

Nenhum risco ou pendência deve ser transferido sem objeto, responsável, autoridade, limite, resposta e aceite.

### 62.14 Invariante 14

Nenhuma responsabilidade operacional deve ser inferida sem transição bilateral.

### 62.15 Invariante 15

Nenhuma divergência material deve ser apagada para produzir cobertura aparente.

### 62.16 Invariante 16

Nenhuma automação deve transformar inferência em vínculo confirmado sem verificação.

### 62.17 Invariante 17

Nenhuma IA possui autoridade para declarar cobertura, aceitar risco, decidir gate, autorizar mudança ou transferir responsabilidade.

### 62.18 Invariante 18

Nenhuma visão derivada deve tornar-se fonte concorrente sem decisão explícita de migração.

### 62.19 Invariante 19

Nenhuma simplificação deve remover origem, autoridade, evidência, diferença ou continuidade material.

### 62.20 Invariante 20

Nenhum encerramento deve ocorrer quando a configuração transferida não puder ser reconstruída até sua origem e seu aceite.

## 63. Exemplo resumido de aplicação

### 63.1 Contexto

A implantação `IMP-2026-001` realiza uma linha de base de sistema editorial para registrar ideias, preparar pautas, gravar conteúdos, organizar arquivos, revisar, aprovar, publicar e acompanhar próxima ação.

### 63.2 Referências recebidas

| Objeto | Referência |
| --- | --- |
| Projeto de arquitetura | `ARQ-2026-001` |
| Linha de base | `LB-ARQ-001 v1.0` |
| Matriz arquitetural | `MTR-ARQ-2026-001` |
| Capacidade | `CAP-ARQ-004` — acompanhar conteúdo por estado e próxima ação. |
| Requisito | `REQ-ARQ-007` — cada conteúdo ativo possui estado, responsável e próxima ação localizáveis. |
| Componente | `CMP-ARQ-011` — base editorial controlada. |
| Decisão | `DEC-2026-005` — aprovar configuração mínima com operação exportável. |

### 63.3 Realização planejada

```text
CAP-ARQ-004
  → IMP-2026-001-INC-001
  → IMP-2026-001-ENT-001 — configurar base e estados
  → IMP-2026-001-ENT-002 — definir responsável e próxima ação
  → IMP-2026-001-ENT-003 — criar pasta e nomenclatura
  → IMP-2026-001-ENT-004 — migrar quatro conteúdos ativos
```

### 63.4 Vínculos iniciais

| Vínculo | Origem | Relação | Destino | Cobertura | Gate |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-VNC-001` | `CAP-ARQ-004` | `é_realizada_por` | `IMP-2026-001-INC-001` | Planejada | `PI-2` |
| `IMP-2026-001-VNC-002` | `IMP-2026-001-ENT-001` | `realiza` | `CAP-ARQ-004` | Parcial | `PI-2` |
| `IMP-2026-001-VNC-003` | `IMP-2026-001-ENT-002` | `atende_parcialmente` | `REQ-ARQ-007` | Planejada | `PI-2` |
| `IMP-2026-001-VNC-004` | `IMP-2026-001-ENT-004` | `depende_de` | `IMP-2026-001-ENT-003` | Não aplicável | `PI-2` |

### 63.5 Evidência do piloto

Critério:

> Quatro conteúdos percorrem o fluxo delimitado com estado, responsável, arquivos e próxima ação localizáveis, sem perda de contexto ou voz autoral.

Evidências:

- `IMP-2026-001-EVD-001` — registros dos quatro conteúdos;
- `IMP-2026-001-EVD-002` — amostra das pastas;
- `IMP-2026-001-EVD-003` — observação de transferência;
- `IMP-2026-001-EVD-004` — demonstração da responsável;
- `IMP-2026-001-EVD-005` — registro de exceções e correções;
- `IMP-2026-001-EVD-006` — indicador de item sem próxima ação.

Vínculos:

```text
IMP-2026-001-EVD-001 demonstra REQ-ARQ-007
IMP-2026-001-EVD-003 demonstra CAP-ARQ-004
REQ-ARQ-007 é_verificado_por IMP-2026-001-EVD-001
REQ-ARQ-007 é_verificado_por IMP-2026-001-EVD-006
CAP-ARQ-004 é_validado_por IMP-2026-001-EVD-001
CAP-ARQ-004 é_validado_por IMP-2026-001-EVD-003
CAP-ARQ-004 é_validado_por IMP-2026-001-EVD-004
```

### 63.6 Diferença observada

A arquitetura previa uma etapa de aprovação. O uso revelou necessidade de dois estados:

- `em revisão`;
- `ajustes solicitados`.

Registrar:

| Campo | Registro |
| --- | --- |
| Diferença | `IMP-2026-001-DIF-001` |
| Referência | `CMP-ARQ-011 v1.0` |
| Configuração observada | Dois estados de revisão. |
| Classificação inicial | Adaptação autorizada candidata. |
| Teste de materialidade | Não altera requisito nem autoridade se o aprovador permanecer o mesmo. |
| Evidência | Histórico dos quatro conteúdos. |
| Decisão | Aceitar dentro da tolerância e atualizar documentação da configuração. |
| Retorno | Retornar ao Módulo 3 se os estados redistribuírem autoridade de aprovação. |

### 63.7 Cobertura no `PI-4`

| Dimensão | Estado | Limite |
| --- | --- | --- |
| Origem | Completa | Linha de base e decisão localizáveis. |
| Realização | Completa para o piloto | Quatro conteúdos; não representa escala maior. |
| Evidência | Demonstrada | Exceção de arquivo duplicado foi corrigida. |
| Decisão | Completa | Diferença recebeu classificação e aceite. |
| Configuração | Completa para `IMP-2026-001-CFG-001` | Versão aceita ainda em estabilização. |
| Continuidade | Planejada | Responsável operacional e suporte serão confirmados no `PI-5`. |

### 63.8 Transição

Depois de ciclo adicional, `IMP-2026-001-CFG-001` é estabilizada e vinculada a:

- responsável operacional;
- procedimento vigente;
- fonte oficial;
- suporte;
- indicador de conteúdo sem próxima ação;
- limite de resposta;
- regra de retorno ao Módulo 4;
- aceite `PI-5`.

### 63.9 Aprendizagem

A implantação registra que:

- demonstração por conteúdo completo foi mais informativa que percentual de tarefas;
- nomenclatura preparada antes da migração reduziu retrabalho;
- uma única etapa de aprovação escondia estado operacional necessário;
- diferença de execução precisa ser testada quanto à autoridade antes de ser classificada como adaptação.

## 64. Relação com o protocolo, o template e o dossiê

### 64.1 Relação com os fundamentos

`01-fundamentos-da-implantacao.md` define o que deve permanecer verdadeiro: natureza da capacidade, níveis de existência, evidência, diferença, autonomia e configuração.

### 64.2 Relação com o protocolo

`02-protocolo-de-implantacao.md` define quando os vínculos devem ser produzidos, atualizados, verificados e utilizados em decisão.

Em especial:

- Etapa 9 produz decomposição;
- Etapa 10 inicia a matriz;
- etapas de preparação acrescentam condições;
- execução acrescenta estados e evidências;
- `PI-3` verifica liberação;
- validação acrescenta demonstração;
- comparação acrescenta diferenças;
- `PI-4` acrescenta aceite;
- estabilização acrescenta exposição e continuidade;
- `PI-5` acrescenta transferência;
- retrospectiva acrescenta aprendizagem.

### 64.3 Relação com o template

`templates/06-matriz-de-rastreabilidade-da-implantacao.md` materializará este método como instrumento preenchível.

O template deverá preservar, de forma proporcional:

- identificação;
- fontes;
- registro de objetos;
- registro de vínculos;
- cobertura;
- lacunas;
- visões de gate;
- diferenças;
- transição;
- histórico;
- teste de reconstrução.

Este documento não deve ser preenchido para uma implantação real.

### 64.4 Relação com o dossiê

Local sugerido da fonte preenchida:

```text
registros-de-implantacao/
└── AAAA/
    └── IMP-AAAA-NNN-nome-curto/
        └── planejamento/
            └── matriz-de-rastreabilidade.md
```

Evidências, decisões, gates, diferenças e configurações permanecem em seus registros próprios e são referenciados pela matriz.

### 64.5 Relação com o Módulo 3

A matriz envia retorno quando a prática revelar:

- requisito novo ou alterado;
- componente estrutural ausente;
- interface crítica diferente;
- redistribuição de autoridade;
- risco não autorizado;
- mudança material de dados, tecnologia ou IA;
- inviabilidade da linha de base;
- diferença fora da tolerância.

### 64.6 Relação com o Módulo 5

A matriz prepara a reconstrução da configuração, mas a transição formal ocorre pelo registro próprio e pelo `PI-5`.

### 64.7 Relação com os Módulos 6, 7 e 8

A matriz aponta o destino da aprendizagem. Ela não incorpora automaticamente uma experiência local como regra universal.

## 65. Critérios de conclusão

A matriz de uma implantação pode ser considerada suficientemente concluída quando:

1. possui identidade e fonte oficial;
2. resolve para transição e linha de base autorizada;
3. preserva IDs e versões herdados;
4. toda obrigação material possui origem e destino;
5. todo trabalho material possui origem ou classificação;
6. cadeias mínimas aplicáveis estão completas ou possuem lacuna tratada;
7. critérios e evidências dos gates são recuperáveis;
8. resultados de gates identificam objeto e versão;
9. diferenças foram comparadas, classificadas e decididas;
10. configuração aceita e estabilizada possui versão;
11. riscos e condições residuais possuem responsáveis e aceite;
12. transição operacional possui vínculos de sustentação;
13. objetos órfãos materiais foram tratados;
14. vínculos inválidos foram corrigidos ou encerrados;
15. histórico preserva decisões e versões anteriores;
16. participação material da IA está registrada;
17. acesso e sensibilidade estão adequados;
18. teste de reconstrução foi realizado;
19. aprendizagem possui destino;
20. outra pessoa autorizada consegue reconstruir o percurso sem memória privada.

Conclusão da matriz não significa encerramento de toda relação. Vínculos destinados à operação podem permanecer vigentes e ser referenciados pelos módulos seguintes.

## 66. Aprendizagem metodológica

Ao concluir a implantação, registrar:

- que classes de objeto foram realmente úteis;
- que relações causaram ambiguidade;
- que campos permaneceram sem uso;
- que lacunas foram detectadas tarde;
- que verificações evitaram erro;
- que indicadores produziram distorção;
- que automações foram confiáveis;
- que revisões humanas foram indispensáveis;
- onde a Matriz de Rastreabilidade da Arquitetura chegou insuficiente;
- onde o protocolo exigiu detalhe desproporcional;
- que visão apoiou melhor cada gate;
- que informação a operação precisou e não recebeu inicialmente;
- que regra pode ser simplificada;
- que mudança metodológica precisa ser testada em outros contextos.

Aprendizagem local não altera este documento automaticamente.

Mudança metodológica exige:

- problema observado;
- evidência;
- contextos de ocorrência;
- impacto;
- alternativa;
- decisão;
- versão;
- relação com outros módulos.

## 67. Princípio de encerramento e síntese

Rastreabilidade não é a quantidade de linhas preenchidas.

É a preservação das relações que tornam a implantação compreensível, governável e transferível.

Uma matriz cumpre sua função quando permite reconhecer:

- por que a implantação existe;
- o que ela recebeu;
- o que deveria tornar real;
- como o trabalho foi organizado;
- que condições permitiram avançar;
- que evidências demonstraram o resultado;
- que decisões alteraram o percurso;
- que diferenças surgiram;
- que configuração foi aceita;
- quem recebeu responsabilidade;
- como o funcionamento será sustentado;
- que aprendizagem retornará ao sistema.

O percurso essencial é:

```text
origem
  → arquitetura autorizada
  → linha de base
  → realização
  → preparação
  → evidência
  → decisão
  → configuração
  → estabilização
  → operação
  → aprendizagem
```

Quando esse percurso pode ser reconstruído sem suposição, a matriz deixa de ser um documento de controle isolado e torna-se memória verificável da transformação organizacional.

## 68. Registro final do documento

| Campo | Registro |
| --- | --- |
| Documento | Matriz de Rastreabilidade da Implantação |
| Módulo | 4 — Implantação |
| Tipo | Método de conexão, cobertura e reconstrução da implantação |
| Versão | 0.1 |
| Data | 03/08/2026 |
| Estado | Em desenvolvimento e validação pela prática |
| Fonte oficial | Repositório `arquitetura-organizacional-adaptativa` |
| Documento anterior | `02-protocolo-de-implantacao.md` |
| Próximo documento na ordem de construção | `templates/01-termo-de-abertura-da-implantacao.md` |

### Histórico de versões

| Versão | Data | Alteração | Responsabilidade |
| --- | --- | --- | --- |
| 0.1 | 03/08/2026 | Criação do método de rastreabilidade da implantação, com objetos, vínculos, estados, cobertura, visões, gates, diferenças, transição e controles. | Estúdio LICHTARA |
