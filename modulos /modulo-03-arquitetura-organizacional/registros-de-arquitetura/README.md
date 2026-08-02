# Registros de Arquitetura — Guia do Diretório

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Diretório:** `registros-de-arquitetura/`  
**Tipo:** Guia de governança, organização, ciclo de vida e preservação dos dossiês  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data de criação:** 02/08/2026

**Documentos relacionados:**

- `../README.md`;
- `../01-fundamentos-da-arquitetura-organizacional.md`;
- `../02-protocolo-de-arquitetura-organizacional.md`;
- `../03-matriz-de-rastreabilidade.md`;
- `../ferramentas/README.md`;
- `../templates/01-termo-de-abertura-da-arquitetura.md`;
- `../templates/02-plano-de-arquitetura.md`;
- `../templates/03-catalogo-de-requisitos.md`;
- `../templates/04-matriz-de-rastreabilidade.md`;
- `../templates/05-arquitetura-integrada.md`;
- `../templates/06-registro-de-validacao.md`;
- `../templates/07-relatorio-de-arquitetura.md`;
- `../templates/08-transicao-para-implantacao.md`;
- `../templates/09-retrospectiva-da-arquitetura.md`;
- `indice-de-arquiteturas.md`;
- `registro-de-arquitetura.md`.

---

## 1. Finalidade

Este diretório preserva cada projeto de arquitetura organizacional como um dossiê identificável, rastreável, versionado e recuperável ao longo de seu ciclo de vida.

Ele permite ao Estúdio LICHTARA:

- abrir uma arquitetura sem dispersar seus registros;
- atribuir identificador único e estável;
- localizar rapidamente projetos por ano, estado, cliente, escopo ou responsável;
- distinguir metodologia permanente de aplicação real;
- manter juntos contexto, requisitos, alternativas, desenhos, decisões, validações e transição;
- reconhecer qual versão constitui a linha de base aprovada;
- preservar fontes oficiais sem duplicá-las;
- reconstruir como e por que uma configuração foi escolhida;
- controlar mudanças depois da aprovação;
- acompanhar suspensão, cancelamento, reabertura, substituição e encerramento;
- proteger conteúdos confidenciais e restringir acessos;
- transferir a arquitetura ao Módulo 4 sem perder contexto;
- comparar previsão e realização nos módulos seguintes;
- transformar projetos concluídos em aprendizagem reutilizável;
- demonstrar a evolução do próprio método.

## 2. Pergunta central

> Onde estão os registros oficiais desta arquitetura, que objeto cada arquivo representa, qual versão está vigente, qual linha de base foi aprovada, quem responde por ela, que condições permanecem abertas e como outra pessoa autorizada poderá reconstruir seu ciclo sem depender da memória individual?

## 3. Resultado esperado

Quando este guia é aplicado corretamente, cada arquitetura possui:

1. identificador estável;
2. pasta própria;
3. manifesto mestre;
4. entrada e origem reconhecíveis;
5. artefatos proporcionais ao escopo;
6. relações entre requisitos, componentes, decisões e validações;
7. estados e versões atualizados;
8. linha de base inequívoca quando aprovada;
9. condições de acesso e manutenção;
10. transição, retrospectiva e encerramento verificáveis;
11. aprendizagem destinada aos módulos responsáveis;
12. histórico preservado sem fontes concorrentes.

## 4. Natureza do diretório

`registros-de-arquitetura/` é a camada de aplicação e memória do Módulo 3.

| Camada | Conteúdo | Função |
| --- | --- | --- |
| Raiz do Módulo 3 | Fundamentos, protocolo e matriz de rastreabilidade | Define o método |
| `ferramentas/` | Fichas operacionais de desenho e comparação | Orienta como investigar e desenhar |
| `templates/` | Estruturas reutilizáveis e não preenchidas | Oferece formas controladas de registro |
| `registros-de-arquitetura/` | Aplicações reais, versões, decisões e evidências | Preserva o que ocorreu em cada projeto |

### 4.1 Regra de separação

Templates não recebem dados de cliente, decisões reais ou versões de projeto. Registros reais não se tornam modelos gerais por terem funcionado em um caso.

## 5. O que o diretório contém

- índice geral das arquiteturas;
- modelo do manifesto mestre;
- pastas anuais;
- dossiês de projetos ativos e encerrados;
- artefatos preenchidos;
- referências para entradas externas;
- registros de decisão;
- avaliações de alternativas;
- desenhos dimensionais;
- arquitetura integrada;
- validações e evidências;
- linhas de base;
- transições para implantação;
- retrospectivas;
- históricos de mudança e reabertura.

## 6. O que o diretório não contém

Não deve conter:

- cópia preenchida dos templates na raiz do diretório;
- arquivos sem relação com uma arquitetura identificada;
- credenciais, chaves ou segredos;
- exportações temporárias tratadas como fontes oficiais;
- anexos recebidos sem origem ou finalidade;
- dados pessoais ou sensíveis além do necessário;
- rascunhos dispersos sem responsável;
- múltiplas cópias concorrentes do mesmo objeto;
- documentação de implantação que pertence ao Módulo 4;
- acompanhamento operacional cotidiano que pertence ao Módulo 5;
- aprendizagem consolidada que já foi destinada ao Módulo 6;
- alterações no método sem governança do Módulo 8.

## 7. Princípios

1. **Uma arquitetura, um identificador** — o código permanece estável durante todo o ciclo.
2. **Um dossiê, uma porta de entrada** — o manifesto mestre orienta a leitura.
3. **Uma fonte oficial por objeto** — índices e relatórios apontam; não competem.
4. **Versão antes de validade** — nenhum artefato é considerado vigente sem versão identificável.
5. **Linha de base explícita** — aprovação indica o conjunto exato de versões autorizadas.
6. **Estado observável** — o estágio do projeto não depende de lembrança informal.
7. **Proporcionalidade** — registros crescem conforme risco, impacto e complexidade.
8. **Rastreabilidade seletiva** — preservar relações materiais, não burocracia indiscriminada.
9. **Histórico íntegro** — substituir não significa apagar.
10. **Acesso mínimo necessário** — informação circula segundo finalidade e responsabilidade.
11. **Encerramento demonstrável** — conclusão exige destino para pendências e aprendizagem.
12. **Reabertura governada** — mudança material retoma o ponto adequado sem destruir a linha de base anterior.
13. **Portabilidade** — o dossiê deve permanecer compreensível fora da memória de ferramentas específicas.
14. **Responsabilidade humana** — automações e IA apoiam organização, nunca assumem autoridade documental.

## 8. Invariantes

- `ARQ-AAAA-NNN` nunca é reutilizado;
- todo dossiê pertence a um único identificador principal;
- toda pasta real possui manifesto mestre;
- o índice geral aponta para o manifesto, não para arquivos aleatórios;
- todo artefato material possui estado e versão;
- toda decisão aponta para seu registro oficial;
- toda linha de base identifica as versões que a compõem;
- versões substituídas permanecem recuperáveis;
- mudança material após aprovação exige análise de impacto;
- divergência entre fontes é registrada e corrigida;
- arquivos confidenciais não são expostos para facilitar busca;
- projetos suspensos ou cancelados não desaparecem do índice;
- encerramento inclui retrospectiva ou justificativa de sua ausência;
- o Módulo 4 recebe somente a linha de base autorizada;
- o conhecimento reutilizável recebe destino, responsável e estado.

## 9. Distinções essenciais

### 9.1 Projeto de arquitetura

Ciclo governado que transforma uma base diagnóstica ou necessidade equivalente em configuração organizacional validada e transferível. Recebe ID `ARQ-AAAA-NNN`.

### 9.2 Registro de arquitetura

Manifesto mestre que identifica o projeto, seu estado, responsáveis, versões, fontes e principais vínculos.

### 9.3 Dossiê de arquitetura

Conjunto organizado de registros que permite compreender e reconstruir o projeto. O dossiê é a pasta completa; não um único relatório.

### 9.4 Artefato

Documento, modelo, matriz, desenho, decisão, evidência ou registro produzido ou incorporado ao projeto.

### 9.5 Fonte oficial

Local autorizado para manter o conteúdo vigente de um objeto. Pode ser um arquivo do dossiê ou referência externa governada.

### 9.6 Manifesto mestre

Arquivo de entrada do dossiê que sintetiza identidade, estado, governança, linha de base e rotas de leitura.

### 9.7 Índice geral

Catálogo transversal de todas as arquiteturas. Ajuda a localizar e acompanhar; não substitui o manifesto de cada projeto.

### 9.8 Versão

Estado identificável de um artefato em determinado momento.

### 9.9 Linha de base

Conjunto de versões aprovado como referência para implantação e controle de mudanças. Recebe ID `LB-ARQ-NNN` dentro do projeto.

### 9.10 Estado

Condição vigente do projeto ou artefato segundo vocabulário controlado.

### 9.11 Histórico

Sequência preservada de estados, versões, decisões e mudanças.

### 9.12 Arquivo de trabalho

Material intermediário que ainda não constitui fonte oficial. Deve possuir responsável e destinação.

### 9.13 Exportação

Representação derivada para leitura, apresentação, impressão ou intercâmbio. Deve apontar para a versão de origem.

### 9.14 Arquivamento

Mudança controlada de um dossiê ou conteúdo para condição de baixa atividade, sem perda de recuperabilidade.

### 9.15 Eliminação

Descarte autorizado conforme finalidade, obrigação, retenção e segurança. Não se confunde com encerramento do projeto.

## 10. Modelo de três níveis

| Nível | Arquivo/unidade | Pergunta respondida |
| --- | --- | --- |
| Portfólio | `indice-de-arquiteturas.md` | Que arquiteturas existem e onde estão? |
| Projeto | `AAAA/ARQ-.../README.md` | O que é esta arquitetura, em que estado está e qual é sua referência vigente? |
| Objeto | Artefatos do dossiê | O que foi definido, decidido, validado ou transferido? |

### 10.1 Regra

Uma informação deve ser mantida no nível em que possui autoridade. O índice pode repetir título e estado para localização; requisitos detalhados permanecem no catálogo oficial do projeto.

## 11. Arquivos permanentes da raiz

| Arquivo | Natureza | Pode ser preenchido com dados reais? | Função |
| --- | --- | --- | --- |
| `README.md` | Norma do diretório | Não | Governar estrutura, ciclo e qualidade |
| `indice-de-arquiteturas.md` | Registro transversal | Sim | Listar e acompanhar projetos reais |
| `registro-de-arquitetura.md` | Modelo controlado | Não na fonte | Originar o manifesto de cada dossiê |

### 11.1 Proibição de uso indevido

Não preencha `registro-de-arquitetura.md` diretamente para um cliente. Copie seu conteúdo para o `README.md` da pasta real e registre o novo projeto no índice.

## 12. Estrutura canônica

```text
registros-de-arquitetura/
|-- README.md
|-- indice-de-arquiteturas.md
|-- registro-de-arquitetura.md
`-- AAAA/
    `-- ARQ-AAAA-NNN-nome-curto/
        |-- README.md
        |-- 01-termo-de-abertura.md
        |-- 02-plano-de-arquitetura.md
        |-- entrada/
        |-- requisitos/
        |-- alternativas/
        |-- desenhos/
        |-- decisoes/
        |-- 05-arquitetura-integrada.md
        |-- validacoes/
        |-- linhas-de-base/
        |-- 07-relatorio-de-arquitetura.md
        |-- 08-transicao-para-implantacao.md
        `-- 09-retrospectiva-da-arquitetura.md
```

A estrutura representa a versão ampliada. Arquiteturas focais podem manter vários conteúdos no mesmo arquivo quando preservarem clareza, fonte e rastreabilidade.

## 13. Função das pastas do dossiê

| Pasta | Conteúdo | Fonte oficial típica |
| --- | --- | --- |
| `entrada/` | Transição do diagnóstico e referências recebidas | Documento de origem ou referência governada |
| `requisitos/` | Catálogo e rastreabilidade | `catalogo-de-requisitos.md` e matriz |
| `alternativas/` | Configurações, comparação e recomendação | Registros `ALT` e avaliação `AVA` |
| `desenhos/` | Saídas dimensionais e mapas | Arquivos correspondentes às ferramentas |
| `decisoes/` | Decisões do projeto e vínculos ao Módulo 1 | Registros `DEC` |
| `validacoes/` | Ciclos, testes, evidências e tratamentos | Registros `VAL`, `TST` e evidências |
| `linhas-de-base/` | Manifestos de versões aprovadas | `LB-ARQ-NNN.md` |

## 14. Unidade de registro

A unidade principal é um projeto de arquitetura identificado por `ARQ-AAAA-NNN`.

Abra projetos distintos quando houver diferença material em:

- decisão patrocinadora;
- escopo ou fronteira;
- organização ou cliente;
- autoridade decisória;
- linha de base;
- ciclo de aprovação;
- transição para implantação;
- obrigação de confidencialidade;
- encerramento independente.

### 14.1 Não fragmentar indevidamente

Frentes de processo, papéis, informação, tecnologia ou IA pertencem ao mesmo projeto quando convergem para uma única configuração integrada e decisão arquitetural.

## 15. Identificador principal

Utilize:

```text
ARQ-AAAA-NNN
```

| Parte | Significado | Exemplo |
| --- | --- | --- |
| `ARQ` | Classe do objeto | Projeto de arquitetura |
| `AAAA` | Ano de abertura | `2026` |
| `NNN` | Sequencial anual | `001` |

Exemplo:

```text
ARQ-2026-001
```

### 15.1 Estabilidade

O ID não muda quando título, estado, escopo refinado, responsável ou versão mudam. Se o objeto se torna outro projeto com decisão e ciclo próprios, atribua novo ID e registre a relação.

## 16. Atribuição do sequencial

1. consulte `indice-de-arquiteturas.md`;
2. filtre o ano de abertura;
3. identifique o maior sequencial efetivamente atribuído;
4. utilize o próximo número disponível;
5. registre imediatamente uma reserva provisória no índice;
6. crie a pasta e o manifesto;
7. confirme a abertura ou libere a reserva com histórico.

### 16.1 Concorrência

Quando duas pessoas puderem abrir registros simultaneamente, uma única pessoa ou rotina deve controlar a atribuição do sequencial. Nunca resolva colisão sobrescrevendo um dossiê.

## 17. Nome da pasta

Padrão:

```text
ARQ-AAAA-NNN-nome-curto
```

Exemplo:

```text
ARQ-2026-001-sistema-editorial
```

### 17.1 Regras do nome curto

- usar letras minúsculas;
- não usar acentos;
- separar palavras por hífen;
- descrever o objeto, não a solução escolhida;
- evitar nome completo de pessoa;
- evitar informação confidencial;
- manter legibilidade;
- preservar o ID no início.

## 18. Pasta anual

Crie a pasta do ano somente quando houver o primeiro registro real daquele período.

| Situação | Tratamento |
| --- | --- |
| Primeiro projeto de 2026 | Criar `2026/` e `ARQ-2026-001-.../` |
| Projeto atravessa anos | Permanece no ano de abertura |
| Projeto reaberto em ano posterior | Permanece na pasta original |
| Nova arquitetura derivada | Recebe ID e pasta do novo ano |

## 19. Identificadores dos artefatos principais

| Objeto | Padrão |
| --- | --- |
| Projeto de arquitetura | `ARQ-AAAA-NNN` |
| Termo de abertura | `TER-ARQ-AAAA-NNN` |
| Plano | `PLA-ARQ-AAAA-NNN` |
| Catálogo de requisitos | `CAT-REQ-AAAA-NNN` |
| Matriz de rastreabilidade | `MTR-ARQ-AAAA-NNN` |
| Avaliação de alternativas | `AVA-ARQ-AAAA-NNN` |
| Arquitetura integrada | `ARQ-INT-AAAA-NNN` |
| Ciclo de validação | `VAL-ARQ-AAAA-NNN` |
| Relatório | `REL-ARQ-AAAA-NNN` |
| Transição para implantação | `TRA-IMP-AAAA-NNN` |
| Retrospectiva | `RET-ARQ-AAAA-NNN` |
| Linha de base | `LB-ARQ-NNN` dentro do projeto |

### 19.1 Qualificação externa

Quando um ID interno puder ser ambíguo fora do dossiê, qualifique-o:

```text
ARQ-2026-001-LB-ARQ-001
ARQ-2026-001-REQ-007
```

## 20. Identificadores derivados

Reutilize os códigos definidos nos documentos do Módulo 3, como:

- `CAP` — capacidade;
- `REQ` — requisito;
- `ALT` — alternativa;
- `CMP` — componente;
- `INT` — interface;
- `PRC` e `FLX` — processo e fluxo;
- `PAP` — papel;
- `INF` e `CON` — informação e conhecimento;
- `COM` — comunicação;
- `DOC` e `RGT` — documento e registro;
- `IND` e `CTL` — indicador e controle;
- `TEC` e `ITG` — tecnologia e integração;
- `FIA` e `SIA` — função e sistema de IA;
- `RSC`, `DEP` e `PRE` — risco, dependência e premissa;
- `TST`, `VAL` e `EVD` — teste, validação e evidência.

O mesmo objeto preserva o mesmo ID em todos os artefatos.

## 21. Relação com decisões do Módulo 1

Decisões arquiteturais devem apontar para o registro oficial do Módulo 1 quando esse for o mecanismo adotado pelo Sistema Operacional.

| No dossiê | No Módulo 1 | Regra |
| --- | --- | --- |
| Referência `DEC-AAAA-NNN` | Registro completo da decisão | Não duplicar justificativa integral |
| Síntese da decisão | Resultado necessário para leitura | Manter fidelidade |
| Link relativo | Fonte oficial | Atualizar se a estrutura mudar |

Se houver decisão local provisória ainda não incorporada ao registro oficial, marque-a como pendente e atribua responsável e prazo.

## 22. Manifesto mestre

Cada dossiê possui um `README.md` criado a partir de `registro-de-arquitetura.md`.

Ele deve permitir compreender, em poucos minutos:

- identidade do projeto;
- problema e decisão apoiada;
- escopo e não objetivos;
- origem e transição recebida;
- estado vigente;
- responsáveis e autoridades;
- artefatos existentes;
- linha de base vigente;
- riscos, condições e questões abertas;
- próxima ação;
- restrições de acesso;
- relação com implantação, operação e aprendizagem.

### 22.1 Manifesto não é relatório

O manifesto orienta e aponta. O relatório comunica a arquitetura aprovada. A arquitetura integrada define a configuração. A linha de base determina as versões válidas.

## 23. Conteúdo mínimo do manifesto

| Campo | Obrigatório | Fonte |
| --- | --- | --- |
| ID e título | Sim | Abertura/índice |
| Estado | Sim | Protocolo |
| Cliente/unidade | Sim, com proteção adequada | Termo |
| Responsável pela arquitetura | Sim | Termo/plano |
| Decisor/patrocinador | Sim | Termo |
| Problema e decisão | Sim | Termo |
| Escopo | Sim | Termo/plano |
| Data de abertura | Sim | Registro |
| Próxima ação | Enquanto ativo | Plano/estado |
| Artefatos e versões | Sim | Fontes oficiais |
| Linha de base | Quando existir | Manifesto `LB` |
| Condições e pendências | Quando existirem | Decisões/validação |
| Acesso | Sim | Classificação |
| Encerramento | Ao concluir | Transição/retrospectiva |

## 24. Índice geral

`indice-de-arquiteturas.md` é o catálogo oficial para descoberta e acompanhamento transversal.

Ele deve responder:

- que arquiteturas existem;
- qual é o ID e título de cada uma;
- em que ano foram abertas;
- qual é o estado vigente;
- quem responde pelo próximo movimento;
- qual é a linha de base atual;
- onde está o manifesto;
- se há restrição de acesso;
- quando ocorreu a última atualização;
- que projeto substitui ou deriva de outro.

### 24.1 Índice não é fonte substantiva

Se o estado do índice divergir do manifesto, interrompa o uso da informação, identifique a fonte correta e corrija a divergência. Não escolha silenciosamente a versão mais conveniente.

## 25. Campos mínimos do índice

| Campo | Exemplo |
| --- | --- |
| ID | `ARQ-2026-001` |
| Título | Sistema editorial |
| Cliente/unidade protegida | [Nome ou código autorizado] |
| Escopo | [Síntese curta] |
| Estado | Em validação |
| Responsável | [Papel/nome autorizado] |
| Abertura | 02/08/2026 |
| Última atualização | [Data] |
| Linha de base | `LB-ARQ-001` ou N/A |
| Próxima ação | [Síntese] |
| Acesso | Interno/confidencial/restrito |
| Manifesto | `[link relativo]` |

## 26. Reserva de ID

| ID reservado | Data | Solicitante | Objeto provisório | Prazo de confirmação | Resultado |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Data] | [Nome/papel] | [Síntese] | [Data] | [Confirmado/liberado] |

IDs liberados não devem ser reaproveitados quando já apareceram em comunicação, proposta, decisão ou arquivo. Registre-os como não utilizados para preservar integridade.

## 27. Relações entre arquiteturas

| Relação | Significado |
| --- | --- |
| `deriva_de` | Novo projeto nasce de arquitetura anterior |
| `complementa` | Projetos distintos cobrem capacidades relacionadas |
| `depende_de` | Um projeto requer resultado de outro |
| `substitui` | Nova arquitetura assume a referência vigente |
| `é_substituída_por` | Relação inversa de substituição |
| `reabre` | Projeto retoma linha de base anterior |
| `compartilha_componente_com` | Componente é governado entre projetos |

### 27.1 Registro

| Origem | Relação | Destino | Motivo | Decisão | Estado |
| --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [Relação] | ARQ-AAAA-NNN | [Preencher] | DEC-AAAA-NNN | [Proposta/aprovada/encerrada] |

## 28. Estados do projeto

Use o vocabulário do Protocolo de Arquitetura:

| Grupo | Estados |
| --- | --- |
| Entrada | Transição recebida; em aceite; aceita; aceita com condições; devolvida ao diagnóstico |
| Abertura e planejamento | Em abertura; aguardando aprovação de abertura; planejada |
| Desenho | Em requisitos; em alternativas; em desenho; em integração; em avaliação |
| Decisão e consolidação | Aguardando decisão; em consolidação; em validação; em revisão; aguardando aprovação |
| Aprovação e passagem | Aprovada; aprovada com condições; em transição para implantação |
| Encerramento e exceção | Encerrada; suspensa; cancelada; reaberta; substituída |

### 28.1 Estado único vigente

O manifesto e o índice devem apresentar um único estado vigente. O histórico pode conter todos os estados anteriores.

## 29. Histórico de estados

| Estado anterior | Novo estado | Data | Gatilho/critério | Decisão | Responsável | Próxima condição |
| --- | --- | --- | --- | --- | --- | --- |
| [Estado] | [Estado] | [Data] | [Preencher] | [ID/N/A] | [Nome/papel] | [Preencher] |

### 29.1 Mudança material

Atualize o estado quando a mudança altera quem pode agir, que atividade deve ocorrer, que gate foi atingido ou que condição impede avanço.

## 30. Estado do projeto e estado dos artefatos

Não confunda:

| Objeto | Exemplo de estado |
| --- | --- |
| Projeto | Em validação |
| Arquitetura integrada | Candidata à linha de base |
| Ciclo de validação | Em tratamento |
| Relatório | Em preparação |
| Transição | Aguardando aceite |
| Requisito | Atendido com condição |

O estado do projeto é síntese governada; não resulta automaticamente do último arquivo editado.

## 31. Portões de controle

| Ponto | Pergunta | Evidência mínima |
| --- | --- | --- |
| PC-1 — Entrada | Existe base suficiente para abrir? | Aceite e condições |
| PC-2 — Direção | Problema, decisão, escopo e requisitos orientam o desenho? | Termo, plano e catálogo |
| PC-3 — Integração | Existe configuração coerente e comparável? | Alternativas e arquitetura integrada |
| PC-4 — Aprovação | A arquitetura foi validada e pode formar linha de base? | Validação, decisão e manifesto `LB` |
| PC-5 — Transição | O Módulo 4 recebeu e aceitou o pacote? | Transição e aceite |

### 31.1 Registro do gate

| Ponto | Data | Resultado | Condições | Autoridade | Evidência |
| --- | --- | --- | --- | --- | --- |
| PC-N | [Data] | [Aprovado, condicionado ou não aprovado] | [IDs] | [Nome/papel] | [Referência] |

## 32. Linha de base

A linha de base é um manifesto de versões autorizadas, não uma cópia indiscriminada de todos os arquivos.

| Campo | Registro |
| --- | --- |
| ID | LB-ARQ-NNN |
| Projeto | ARQ-AAAA-NNN |
| Versão da linha de base | [Número] |
| Data | [Data] |
| Escopo | [Preencher] |
| Artefatos e versões | [Manifesto] |
| Decisões | [IDs] |
| Condições | [IDs] |
| Riscos aceitos | [IDs] |
| Aprovador | [Nome/papel] |
| Estado | [Candidata, aprovada, substituída ou encerrada] |

### 32.1 Uma referência vigente

Pode existir histórico de várias linhas de base, mas somente uma deve ser declarada vigente para determinado escopo e momento.

## 33. Manifesto da linha de base

| Artefato | ID | Versão | Estado | Fonte oficial | Incluído? | Observação |
| --- | --- | --- | --- | --- | --- | --- |
| Catálogo de Requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |
| Matriz de Rastreabilidade | MTR-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |
| Avaliação de Alternativas | AVA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |
| Arquitetura Integrada | ARQ-INT-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |
| Registro de Validação | VAL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |
| Relatório | REL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Preencher] |

## 34. Versão reduzida e ampliada

| Tipo de arquitetura | Estrutura aceitável |
| --- | --- |
| Focal | Manifesto, termo/plano combinável, requisitos essenciais, desenho, decisão, validação e transição |
| Funcional | Nove artefatos principais, desenhos dimensionais pertinentes e linha de base |
| Sistêmica | Dossiê completo, rastreabilidade ampliada, ciclos de validação, linhas de base e anexos governados |

### 34.1 Redução legítima

Reduzir significa combinar estruturas preservando função. Não significa omitir decisão, requisito, risco, responsável, validação ou versão.

## 35. Pacote mínimo de um dossiê

- [ ] manifesto mestre;
- [ ] identificação e estado;
- [ ] entrada ou origem;
- [ ] problema, decisão e escopo;
- [ ] requisitos materiais;
- [ ] configuração ou desenho;
- [ ] alternativas quando houver escolha material;
- [ ] decisão registrada;
- [ ] validação proporcional;
- [ ] linha de base quando aprovada;
- [ ] transição ou destino do trabalho;
- [ ] retrospectiva ou justificativa;
- [ ] atualização do índice.

## 36. Pacote ampliado

| Grupo | Conteúdo provável |
| --- | --- |
| Controle | Manifesto, termo, plano, índice, histórico de estados |
| Entrada | Diagnóstico, transição, fontes e aceite |
| Direção | Problema, decisão, escopo, princípios e requisitos |
| Alternativas | Configurações, critérios, evidências, comparação e recomendação |
| Desenhos | Capacidades, processos, papéis, informação, comunicação, documentos, indicadores, tecnologia e IA |
| Integração | Componentes, interfaces, riscos, arquitetura integrada e matriz |
| Validação | Planos, sessões, testes, evidências, divergências e tratamentos |
| Aprovação | Decisões, linha de base e relatório |
| Passagem | Transição, aceite do Módulo 4 e pendências |
| Aprendizagem | Retrospectiva, previsões, correções e destinos |

## 37. Relação com os nove templates

| Template | Uso no dossiê | Momento típico |
| --- | --- | --- |
| `01-termo-de-abertura-da-arquitetura.md` | Formalizar objeto, autoridade e limites | Abertura |
| `02-plano-de-arquitetura.md` | Governar trabalho, frentes, marcos e participação | Planejamento |
| `03-catalogo-de-requisitos.md` | Consolidar e controlar requisitos | Direção/desenho |
| `04-matriz-de-rastreabilidade.md` | Relacionar origem, desenho, validação e implantação | Todo o ciclo |
| `05-arquitetura-integrada.md` | Consolidar a configuração | Integração/consolidação |
| `06-registro-de-validacao.md` | Preservar ciclos e resultados | Validação |
| `07-relatorio-de-arquitetura.md` | Comunicar a linha de base | Após aprovação |
| `08-transicao-para-implantacao.md` | Transferir ao Módulo 4 | Passagem |
| `09-retrospectiva-da-arquitetura.md` | Destinar aprendizagem | Encerramento |

### 37.1 Copiar somente quando necessário

Não copie todos os templates automaticamente. Primeiro defina proporcionalidade e plano. Arquivos vazios não demonstram controle; aumentam ruído e produzem falsa sensação de completude.

## 38. Criação a partir de template

Ao criar um artefato real:

1. copie a versão vigente do template;
2. registre a versão de origem;
3. substitua marcadores pelo contexto real;
4. remova instruções apenas quando isso não eliminar controle necessário;
5. atribua ID e versão do artefato;
6. registre responsável e estado;
7. vincule-o ao manifesto;
8. atualize a matriz quando houver objetos materiais.

### 38.1 Evolução independente

O template pode evoluir depois que o projeto começou. A cópia real não é atualizada automaticamente. Avalie impacto, registre decisão e migre apenas o necessário.

## 39. Registro da origem do template

| Artefato real | Template de origem | Versão de origem | Data da cópia | Adaptações materiais | Responsável |
| --- | --- | --- | --- | --- | --- |
| [Arquivo/ID] | [Template] | [Versão] | [Data] | [Preencher] | [Nome/papel] |

## 40. Abertura do dossiê

Um dossiê pode ser criado em condição provisória para receber a transição, mas não deve avançar sem os critérios de entrada do protocolo.

### 40.1 Sequência

1. receber solicitação ou transição;
2. verificar se já existe arquitetura para o mesmo objeto;
3. reservar ID;
4. criar pasta anual e pasta do projeto;
5. copiar o manifesto mestre;
6. registrar entrada e classificação de acesso;
7. incluir o projeto no índice;
8. atribuir responsável e próxima ação;
9. avaliar aceite;
10. confirmar ou encerrar a abertura provisória.

## 41. Verificação de duplicidade

| Pergunta | Resultado | Ação |
| --- | --- | --- |
| Existe arquitetura ativa para o mesmo objeto? | [Sim/não] | [Vincular, ampliar, reabrir ou criar] |
| Existe linha de base vigente relacionada? | [Sim/não] | [Analisar mudança] |
| O pedido é implantação de arquitetura já aprovada? | [Sim/não] | [Encaminhar ao Módulo 4] |
| O pedido é ajuste operacional? | [Sim/não] | [Encaminhar ao Módulo 5] |
| A mudança exige novo projeto independente? | [Sim/não] | [Justificar novo ID] |

Duplicidade deve ser resolvida antes da criação de registros concorrentes.

## 42. Registro da entrada

| Campo | Registro |
| --- | --- |
| Origem | [Diagnóstico, decisão, operação, obrigação ou outro] |
| Documento principal | [ID/link] |
| Data de recebimento | [Data] |
| Remetente | [Nome/papel] |
| Escopo recebido | [Preencher] |
| Restrições de uso | [Preencher] |
| Lacunas aparentes | [Preencher] |
| Estado inicial | Transição recebida |
| Responsável pelo aceite | [Nome/papel] |

## 43. Aceite da transição

| Resultado | Significado | Registro exigido |
| --- | --- | --- |
| Aceita | Base suficiente | Critério e responsável |
| Aceita com condições | Trabalho pode começar com pendências governadas | Condições, prazos e limites |
| Devolvida ao diagnóstico | Lacuna impede desenho responsável | Motivos e evidências |
| Suspensa | Falta decisão, acesso ou recurso | Gatilho de retomada |
| Cancelada | O objeto não seguirá | Autoridade e destino dos registros |

### 43.1 Condição de aceite

| Condição | Impacto | Responsável | Prazo/gatilho | Restrição enquanto aberta | Estado |
| --- | --- | --- | --- | --- | --- |
| COND-ARQ-___ | [Preencher] | [Papel] | [Data/evento] | [Preencher] | [Aberta/tratada] |

## 44. Termo e plano

O termo responde **o que está sendo aberto e por qual autoridade**. O plano responde **como o trabalho de arquitetura será conduzido**.

| Verificação | Termo | Plano |
| --- | --- | --- |
| Problema e decisão | Define | Detalha abordagem |
| Escopo e não objetivos | Autoriza | Organiza frentes |
| Papéis principais | Nomeia | Distribui participação |
| Prazo | Delimita | Estrutura marcos |
| Riscos iniciais | Reconhece | Define tratamento |
| Artefatos | Indica | Seleciona e agenda |

## 45. Catálogo de requisitos

O catálogo é a fonte oficial das condições que a arquitetura precisa atender. O manifesto registra apenas versão, estado, localização e síntese de pendências.

| Situação | Ação no dossiê |
| --- | --- |
| Requisito novo | Criar ID e registrar origem |
| Requisito alterado | Versionar e analisar impacto |
| Requisito rejeitado | Preservar decisão e motivo |
| Requisito obrigatório não atendido | Impedir ou condicionar aprovação |
| Requisito surgido na implantação | Avaliar retorno ao Módulo 3 |

## 46. Matriz de rastreabilidade

A matriz deve acompanhar o ciclo, não ser produzida somente no encerramento.

Ela relaciona, conforme materialidade:

- diagnóstico e achados;
- capacidades;
- requisitos;
- alternativas;
- decisões;
- componentes;
- interfaces;
- riscos e controles;
- validações;
- itens de implantação;
- linhas de base.

### 46.1 Fonte e visão

Uma matriz consolidada pode possuir visões derivadas. Declare qual arquivo mantém os vínculos oficiais.

## 47. Alternativas

| Conteúdo | Fonte |
| --- | --- |
| Identidade e tese | Registro `ALT` |
| Configuração | Desenhos relacionados |
| Critérios | Catálogo da avaliação |
| Evidências | Registros `EVD` |
| Comparação | `AVA-ARQ-AAAA-NNN` |
| Recomendação | Avaliação |
| Decisão | Registro `DEC` |

Alternativa rejeitada permanece no dossiê quando sua análise contribui para justificar a decisão ou pode retornar sob nova condição.

## 48. Desenhos dimensionais

| Dimensão | Arquivo sugerido | Aplicar quando material? |
| --- | --- | --- |
| Estado atual e futuro | `estado-atual-e-futuro.md` | Sim |
| Processos e fluxos | `processos-e-fluxos.md` | Sim |
| Papéis e alçadas | `papeis-e-alcadas.md` | Sim |
| Informação e conhecimento | `informacao-e-conhecimento.md` | Sim |
| Comunicação | `comunicacao.md` | Sim |
| Documentação | `documentacao.md` | Sim |
| Indicadores e controles | `indicadores-e-controles.md` | Sim |
| Tecnologia e integrações | `tecnologia-e-integracoes.md` | Sim |
| Inteligência artificial | `inteligencia-artificial.md` | Sim |

Não crie um desenho dimensional apenas porque existe uma ficha no diretório de ferramentas.

## 49. Arquitetura integrada

`arquitetura-integrada.md` é a fonte oficial da configuração consolidada, quando adotada no projeto.

O manifesto deve registrar:

- ID;
- versão;
- estado;
- alternativa de origem;
- decisão relacionada;
- linha de base;
- responsável;
- link;
- condições abertas.

### 49.1 Não duplicação

O manifesto pode resumir a tese de transformação, mas não deve manter uma segunda lista oficial de componentes.

## 50. Validações

Cada ciclo de validação representa uma versão identificada e um conjunto governado de verificações.

| Elemento | Registro |
| --- | --- |
| Ciclo | VAL-ARQ-AAAA-NNN |
| Objeto e versão | [IDs] |
| Perguntas | [IDs/síntese] |
| Métodos | [Preencher] |
| Participantes | [Nomes/papéis] |
| Evidências | [IDs] |
| Resultado | [Estado] |
| Tratamentos | [IDs] |
| Decisão | [ID] |

### 50.1 Separar ciclos

Abra novo ciclo quando mudar materialmente a versão, o escopo, a pergunta, o método decisório ou a condição de reabertura.

## 51. Decisões

| Classe | Exemplo | Fonte oficial |
| --- | --- | --- |
| Abertura | Autorizar o projeto | Registro de decisão/termo |
| Escopo | Incluir ou excluir capacidade | Registro `DEC` |
| Alternativa | Selecionar configuração | Registro `DEC` e avaliação |
| Risco | Aceitar exposição residual | Registro `DEC` |
| Aprovação | Estabelecer linha de base | Registro `DEC` |
| Mudança | Alterar linha de base | Registro `DEC` e impacto |
| Encerramento | Concluir, cancelar ou substituir | Registro `DEC` |

Decisão registrada em reunião ou mensagem deve ser incorporada à fonte oficial ou marcada como não formalizada.

## 52. Relatório e dossiê

| Objeto | Função |
| --- | --- |
| Relatório | Comunicar a arquitetura aprovada aos públicos definidos |
| Dossiê | Preservar o conjunto que sustenta a arquitetura |
| Manifesto mestre | Orientar a navegação e o estado do dossiê |

O relatório não encerra o dossiê nem substitui a linha de base.

## 53. Transição para implantação

O dossiê deve registrar tanto a entrega quanto o aceite do Módulo 4.

| Marco | Evidência | Estado |
| --- | --- | --- |
| Pacote preparado | Manifesto de transição | [Estado] |
| Versões conferidas | Linha de base | [Estado] |
| Reunião realizada | Registro/participantes | [Estado] |
| Dúvidas e condições | Lista governada | [Estado] |
| Aceite do Módulo 4 | Declaração/decisão | [Estado] |
| Devoluções | Tratamentos | [Estado] |

### 53.1 Passagem não encerra responsabilidade

Pendências arquiteturais continuam sob governança do Módulo 3 até tratamento, aceitação explícita ou transferência legítima.

## 54. Retrospectiva

A retrospectiva deve ser localizada dentro do dossiê e vinculada aos aprendizados destinados.

| Destino | Conteúdo |
| --- | --- |
| Projeto | Ação ainda necessária |
| Módulo 3 | Melhoria de protocolo, ferramenta ou template |
| Módulo 4 | Aprendizagem de passagem e implantabilidade |
| Módulo 6 | Conhecimento reutilizável |
| Módulo 7 | Aprendizado sobre funções de IA |
| Módulo 8 | Proposta de evolução do Sistema Operacional |

## 55. Papéis do diretório

| Papel | Responsabilidade | Autoridade | Limite |
| --- | --- | --- | --- |
| Curador do diretório | Manter estrutura, índice e regras | Corrigir inconsistência estrutural | Não altera conteúdo sem responsável |
| Responsável pela arquitetura | Manter manifesto e dossiê | Propor versões e estados | Não aprova fora da alçada |
| Responsável por artefato | Manter fonte específica | Atualizar dentro do escopo | Não cria fonte paralela |
| Decisor/aprovador | Autorizar decisões e linha de base | Aprovar dentro da alçada | Não torna evidência inválida em válida |
| Revisor | Verificar integridade e rastreabilidade | Solicitar correção | Não substitui autoria ou decisão |
| Responsável pela implantação | Conferir recebimento e implantabilidade | Aceitar ou devolver passagem | Não altera arquitetura silenciosamente |
| Curador de conhecimento | Receber aprendizagem | Destinar e consolidar | Não expõe informação confidencial |

## 56. Matriz de responsabilidade

| Ação | Executa | Responde | Consulta | Informa |
| --- | --- | --- | --- | --- |
| Atribuir ID | [Papel] | [Papel] | [Papel] | [Papel] |
| Criar dossiê | [Papel] | [Papel] | [Papel] | [Papel] |
| Atualizar manifesto | [Papel] | [Papel] | [Papel] | [Papel] |
| Atualizar índice | [Papel] | [Papel] | [Papel] | [Papel] |
| Estabelecer linha de base | [Papel] | [Papel] | [Papel] | [Papel] |
| Aprovar acesso | [Papel] | [Papel] | [Papel] | [Papel] |
| Encerrar dossiê | [Papel] | [Papel] | [Papel] | [Papel] |
| Reabrir arquitetura | [Papel] | [Papel] | [Papel] | [Papel] |

## 57. Responsável pelo manifesto

O manifesto possui um responsável nominal ou funcional durante toda a atividade do projeto.

| Situação | Tratamento |
| --- | --- |
| Responsável muda | Registrar transferência, data e pendências |
| Responsável se ausenta | Designar substituto e limitar ações |
| Projeto suspenso | Manter curador mínimo |
| Projeto encerrado | Atribuir custodiante do histórico |
| Cliente assume manutenção | Registrar fronteira e acesso |

## 58. Próxima ação

Todo projeto não encerrado deve possuir próxima ação ou condição de espera.

| Campo | Registro |
| --- | --- |
| Ação/condição | [Preencher] |
| Responsável | [Nome/papel] |
| Prazo/gatilho | [Data/evento] |
| Dependência | [ID/N/A] |
| Estado se não ocorrer | [Suspender, escalar, devolver ou outro] |

“Aguardando” sem objeto, pessoa e prazo não é estado operacional suficiente.

## 59. Classificação de acesso

Adote a classificação definida pelo projeto ou contrato. Na ausência de taxonomia específica, utilize:

| Classe | Conteúdo típico | Acesso |
| --- | --- | --- |
| Público | Método e materiais autorizados | Livre conforme licença |
| Interno | Trabalho do Estúdio sem dado confidencial | Pessoas autorizadas do Estúdio |
| Confidencial | Estratégia, cliente, pessoas ou negócio | Equipe e cliente conforme necessidade |
| Restrito | Dados sensíveis, segurança, parecer ou segredo | Lista nominal e finalidade específica |

### 59.1 Classificação por arquivo

O dossiê pode ter classificação geral e exceções por arquivo. A classificação mais restritiva não deve ser reduzida por conveniência de compartilhamento.

## 60. Registro de acesso

| Conteúdo | Classe | Pessoas/papéis autorizados | Finalidade | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- |
| [Pasta/arquivo] | [Classe] | [Preencher] | [Preencher] | [Papel] | [Data] |

### 60.1 Credenciais

Nunca armazene senhas, tokens, chaves privadas ou segredos operacionais no dossiê. Registre apenas onde o mecanismo autorizado de gestão está governado.

## 61. Dados pessoais e sensíveis

| Pergunta | Registro |
| --- | --- |
| O dado é necessário à finalidade? | [Sim/não/justificativa] |
| Pode ser representado por código ou papel? | [Preencher] |
| Quem pode acessar? | [Preencher] |
| Qual é o prazo de retenção? | [Preencher] |
| Que obrigação ou base se aplica? | [Validar com competência adequada] |
| Como ocorrerá correção ou eliminação? | [Preencher] |

Use nomes e detalhes pessoais somente quando sua presença for necessária para responsabilidade, participação, decisão ou obrigação legítima.

## 62. Documentos externos

| Documento | Origem | Responsável externo | Versão/data | Condição de acesso | Cópia ou referência | Uso |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Fonte] | [Nome/papel] | [Preencher] | [Classe] | [Preencher] | [Finalidade] |

### 62.1 Referência preferível

Quando outra fonte governada mantém o documento, prefira referência estável a cópia. Se cópia for necessária para preservar evidência, identifique data, versão e limites de atualização.

## 63. Fornecedores e terceiros

Registre:

- artefatos produzidos;
- direitos de uso e acesso;
- dependência de formatos ou contas;
- versões entregues;
- responsabilidades de correção;
- prazo de disponibilidade;
- obrigação de devolução ou eliminação;
- condição de saída;
- conflito de interesse.

## 64. Uso de inteligência artificial

IA pode apoiar:

- classificação inicial de arquivos;
- extração de metadados;
- verificação de links e campos;
- comparação de versões;
- localização de lacunas;
- síntese com referências;
- geração de listas de conferência;
- detecção de inconsistências aritméticas ou estruturais.

IA não deve:

- decidir estado, aprovação ou linha de base;
- inferir classificação de acesso sem regra e verificação;
- modificar fonte oficial sem responsável;
- preencher lacuna com conteúdo inventado;
- eliminar arquivo ou histórico;
- atribuir autoria, decisão ou aceite a pessoa;
- processar conteúdo incompatível com autorização;
- transformar rascunho em registro oficial por automação.

### 64.1 Registro de contribuição

| Função de IA | Objeto | Entrada autorizada | Saída | Verificador | Correção material | Destino |
| --- | --- | --- | --- | --- | --- | --- |
| FIA-ARQ-___ | [Preencher] | [Referências] | [Preencher] | [Nome/papel] | [Sim/não] | [Arquivo] |

## 65. Autoria e responsabilidade

| Contribuição | Autor/responsável | Evidência | Aprovação |
| --- | --- | --- | --- |
| Levantamento factual | [Nome/papel] | [Fonte] | [Papel] |
| Desenho arquitetural | [Nome/papel] | [Artefatos] | [Papel] |
| Revisão | [Nome/papel] | [Registro] | [Papel] |
| Apoio de IA | [Função/modelo quando necessário] | [Registro] | Verificador humano |
| Decisão | [Autoridade] | DEC-AAAA-NNN | [Instância] |

Ferramenta utilizada não substitui autoria responsável nem autoridade institucional.

## 66. Nomes de arquivos

Regras:

- usar minúsculas;
- separar palavras por hífen;
- evitar acentos quando a compatibilidade exigir;
- descrever o objeto;
- manter numeração apenas quando houver sequência governada;
- não incluir `final`, `final-2`, `novo` ou `corrigido` como controle de versão;
- não expor nome confidencial no caminho;
- não renomear fonte oficial sem atualizar referências.

### 66.1 Exemplos

| Evitar | Preferir |
| --- | --- |
| `arquitetura-final-v3-agora-vai.md` | `05-arquitetura-integrada.md` com versão interna |
| `cliente-secreto-problemas.md` | `entrada/achados-restritos.md` |
| `decisao-nova.md` | `decisoes/DEC-2026-014.md` |

## 67. Links internos

Prefira links relativos dentro do repositório.

| Origem | Destino | Forma recomendada |
| --- | --- | --- |
| Manifesto do projeto | Artefato local | Caminho relativo |
| Índice geral | Manifesto | Caminho relativo à raiz do índice |
| Artefato | Decisão do Módulo 1 | Caminho relativo entre módulos |
| Dossiê | Fonte externa | URL ou identificador governado |

### 67.1 Link quebrado

Link quebrado em objeto material é pendência documental. Corrija, substitua ou registre indisponibilidade e impacto.

## 68. Formatos

Markdown é o formato preferencial para registros textuais versionáveis. Outros formatos podem ser utilizados quando sua função exigir.

| Formato | Uso | Proteção |
| --- | --- | --- |
| `.md` | Textos, matrizes e manifestos | Fonte editável |
| `.csv`/`.xlsx` | Dados e cálculos | Definição de campos e versão |
| `.pdf` | Emissão e preservação visual | Referência à fonte editável |
| Imagem | Evidência ou diagrama | Legenda, origem e data |
| Arquivo técnico | Modelo, configuração ou código | Ambiente, versão e instrução |

## 69. Fonte editável e exportação

| Exportação | Fonte | Versão | Data | Finalidade | Válida até |
| --- | --- | --- | --- | --- | --- |
| [Arquivo] | [Arquivo/ID] | [Versão] | [Data] | [Apresentação, assinatura ou arquivo] | [Data/evento] |

Uma exportação assinada ou emitida pode ter valor próprio, mas deve continuar ligada à fonte e à linha de base que representa.

## 70. Versionamento

Adote versão semântica documental proporcional:

| Mudança | Exemplo | Tratamento |
| --- | --- | --- |
| Rascunho incremental | Preenchimento inicial | `0.1`, `0.2` |
| Candidata a aprovação | Conteúdo consolidado | Estado explícito e versão |
| Primeira aprovada | Linha de base inicial | `1.0` ou padrão decidido |
| Editorial | Ortografia sem mudança de sentido | Incremento menor |
| Material | Requisito, componente, decisão ou risco | Análise de impacto e nova aprovação |

### 70.1 Versão do arquivo e do objeto

Histórico do repositório registra alterações técnicas. O cabeçalho ou manifesto registra a versão semântica do objeto. Ambos são complementares.

## 71. Histórico de versões

| Versão | Data | Alteração | Materialidade | Motivo | Responsável | Aprovador |
| --- | --- | --- | --- | --- | --- | --- |
| [Versão] | [Data] | [Síntese] | [Editorial/material] | [Preencher] | [Nome] | [Nome/N/A] |

## 72. Congelamento para validação

Antes de validar:

1. identifique objeto e versão;
2. registre data de corte;
3. impeça alteração silenciosa durante o ciclo;
4. trate correções por registro;
5. determine se a mudança exige reinício parcial;
6. vincule o resultado à versão examinada.

## 73. Mudança editorial e material

| Tipo | Exemplos | Efeito |
| --- | --- | --- |
| Editorial | Ortografia, legibilidade, link sem mudança de objeto | Atualizar versão do artefato |
| Material local | Critério, responsabilidade ou componente limitado | Analisar objetos relacionados |
| Material sistêmica | Escopo, alternativa, risco, linha de base ou decisão | Reabrir avaliação/validação e aprovar |

### 73.1 Proibição

Não classifique como editorial uma alteração que muda interpretação, obrigação, autoridade, comportamento ou proteção.

## 74. Registro de mudança

| ID | Objeto | Versão anterior | Mudança | Motivo | Impactos | Decisão | Nova versão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MUD-ARQ-___ | [ID] | [Versão] | [Preencher] | [Preencher] | [IDs] | DEC-AAAA-NNN | [Versão] |

## 75. Análise de impacto

| Objeto alterado | Requisitos | Componentes | Interfaces | Riscos | Validações | Implantação | Linha de base |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/efeito] | [IDs/efeito] | [IDs/efeito] | [IDs/efeito] | [Repetir/dispensar] | [Efeito] | [Manter/substituir] |

## 76. Divergência entre fontes

| Conteúdo | Fonte A | Fonte B | Versões | Autoridade semântica | Tratamento | Efeito |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Arquivo] | [Arquivo] | [Versões] | [Papel/fonte] | [Corrigir, decidir ou revalidar] | [IDs] |

### 76.1 Sequência de tratamento

1. não escolher silenciosamente;
2. suspender uso decisório se a diferença for material;
3. identificar versões e responsáveis;
4. consultar a linha de base;
5. determinar a fonte oficial;
6. corrigir derivações;
7. analisar impacto;
8. registrar decisão quando necessário.

## 77. Edição concorrente

| Risco | Proteção |
| --- | --- |
| Duas pessoas alteram a mesma fonte | Responsável definido e revisão antes da integração |
| Versão local desatualizada | Conferir versão vigente antes de editar |
| Alterações incompatíveis | Resolver conteúdo com autoridade semântica |
| Aprovação durante mudança | Congelar candidata e registrar corte |
| Automação sobrescreve edição humana | Exigir revisão e operação reversível |

Conflito técnico não decide conflito semântico. A resolução precisa preservar a intenção autorizada e o histórico.

## 78. Revisão periódica do dossiê

| Momento | Foco | Responsável |
| --- | --- | --- |
| Abertura | ID, estrutura, acesso e entrada | Curador/responsável |
| Mudança de gate | Estado, artefatos e pendências | Responsável pela arquitetura |
| Antes da validação | Versões e congelamento | Responsável/revisor |
| Antes da linha de base | Completude e decisões | Aprovador/revisor |
| Antes da transição | Manifesto do pacote e acessos | Arquitetura/implantação |
| Encerramento | Destinos, índice e retenção | Curador |
| Revisão anual | Acessos, links e vigência | Custodiante |

## 79. Verificação de integridade

| Verificação | Resultado | Evidência | Ação |
| --- | --- | --- | --- |
| Pasta corresponde ao ID? | [Sim/não] | [Caminho] | [Preencher] |
| Manifesto existe e está atualizado? | [Sim/não] | [Versão] | [Preencher] |
| Índice aponta para o manifesto? | [Sim/não] | [Link] | [Preencher] |
| Estado coincide entre fontes? | [Sim/não] | [Referências] | [Preencher] |
| Artefatos materiais possuem versão? | [Sim/não] | [Lista] | [Preencher] |
| Linha de base resolve as versões? | [Sim/não/N/A] | [LB] | [Preencher] |
| Decisões estão localizáveis? | [Sim/não] | [IDs] | [Preencher] |
| Acesso está classificado? | [Sim/não] | [Registro] | [Preencher] |

## 80. Verificações automatizáveis

Rotinas podem verificar:

- padrão do nome das pastas;
- unicidade de `ARQ-AAAA-NNN`;
- existência de manifesto;
- presença de campos obrigatórios;
- links relativos quebrados;
- IDs citados sem objeto correspondente;
- artefatos sem versão;
- estados fora do vocabulário;
- divergência entre índice e manifesto;
- linha de base com arquivo ausente;
- credenciais acidentalmente incluídas;
- marcadores não preenchidos em versão aprovada.

### 80.1 Limite

Conformidade estrutural não demonstra qualidade arquitetural, validade da evidência, legitimidade da decisão ou adequação ética.

## 81. Completude proporcional

| Pergunta | Focal | Funcional | Sistêmica |
| --- | --- | --- | --- |
| Manifesto e ID | Obrigatório | Obrigatório | Obrigatório |
| Termo e plano | Combináveis | Separados | Ampliados |
| Requisitos | Essenciais | Catálogo | Catálogo e governança ampliada |
| Rastreabilidade | Relações críticas | Matriz | Visões e análises de impacto |
| Alternativas | Quando escolha material | Estruturadas | Ampliadas e sensíveis |
| Desenhos | Dimensões materiais | Conjunto necessário | Conjunto integrado |
| Validação | Proporcional | Formal | Múltiplos ciclos |
| Linha de base | Manifesto mínimo | Completa | Completa e versionada |

## 82. Objeto órfão

| Objeto | Ausência | Risco | Investigação | Resultado |
| --- | --- | --- | --- | --- |
| [Arquivo/ID] | [Sem requisito, decisão, responsável, versão ou uso] | [Preencher] | [Preencher] | [Vincular, corrigir, arquivar ou eliminar] |

Um arquivo não se torna necessário apenas porque foi produzido.

## 83. Duplicidade de objeto

| Objeto A | Objeto B | Conteúdo sobreposto | Fonte correta | Ação | Referências a corrigir |
| --- | --- | --- | --- | --- | --- |
| [ID/arquivo] | [ID/arquivo] | [Preencher] | [Preencher] | [Fundir, derivar ou encerrar] | [Lista] |

### 83.1 Cópia deliberada

Cópia para emissão, evidência ou contingência deve ser marcada como derivada, informar fonte, versão e finalidade e não aceitar edição independente.

## 84. Sincronização do índice

Atualize o índice quando houver:

- reserva ou confirmação de ID;
- mudança de título público;
- mudança de estado;
- troca de responsável;
- nova linha de base;
- suspensão ou cancelamento;
- reabertura;
- substituição;
- encerramento;
- mudança de acesso;
- movimentação do caminho.

### 84.1 Prazo

Atualize no mesmo ciclo da mudança ou registre uma pendência com responsável. Índice desatualizado reduz confiança em todo o portfólio.

## 85. Recuperabilidade

Um dossiê recuperável permite:

- localizar o projeto pelo índice;
- abrir o manifesto sem conhecimento prévio;
- identificar a linha de base vigente;
- acessar as fontes autorizadas;
- reconstruir decisões e validações;
- distinguir versão atual de histórica;
- compreender restrições de acesso;
- retomar o trabalho após ausência de pessoa-chave.

### 85.1 Teste de recuperação

| Cenário | Participante | Tempo-alvo | Resultado | Lacuna | Ação |
| --- | --- | --- | --- | --- | --- |
| Pessoa autorizada sem contexto localiza a linha de base | [Nome/papel] | [Tempo] | [Preencher] | [Preencher] | [Preencher] |

## 86. Portabilidade

| Elemento | Condição de portabilidade |
| --- | --- |
| Texto | Formato aberto e legível |
| IDs | Estáveis e explicados |
| Links | Relativos ou acompanhados de referência |
| Diagramas | Fonte ou descrição preservada |
| Dados | Dicionário e formato exportável |
| Decisões | Contexto e autoridade identificados |
| Linha de base | Manifesto independente de ferramenta |
| IA | Prompts, avaliações e limites funcionais quando materiais |

Portabilidade não exige expor conteúdo a quem não possui autorização.

## 87. Continuidade do repositório

| Falha | Continuidade |
| --- | --- |
| Pessoa-chave ausente | Manifesto, responsáveis substitutos e rotas de leitura |
| Ferramenta indisponível | Cópia versionada e formato portátil conforme governança |
| Link externo perdido | Metadados, evidência preservada ou ação de recuperação |
| Arquivo corrompido | Histórico e mecanismo de restauração |
| Acesso revogado | Transferência autorizada de custódia |
| Fornecedor encerrado | Plano de saída e exportação |

## 88. Retenção

| Classe de registro | Retenção | Gatilho inicial | Autoridade | Destino |
| --- | --- | --- | --- | --- |
| Decisões e linha de base | [Período/obrigação] | Aprovação/encerramento | [Papel] | [Preservar/revisar] |
| Evidências | [Período] | Coleta/uso | [Papel] | [Preservar/eliminar] |
| Dados pessoais | [Período mínimo] | Finalidade concluída | [Papel] | [Eliminar/anonimizar] |
| Rascunhos | [Período curto] | Objeto consolidado | [Papel] | [Eliminar/arquivar] |
| Exportações | [Período] | Emissão | [Papel] | [Preservar/eliminar] |

Prazos devem respeitar obrigações contratuais, legais e legítimas validadas por competência adequada.

## 89. Arquivamento

Arquivar quando:

- o projeto foi encerrado;
- a transição foi aceita e não há ação ativa do Módulo 3;
- a arquitetura foi substituída;
- o projeto foi cancelado com registro suficiente;
- a manutenção ativa não é mais necessária.

### 89.1 Ações

1. confirmar estado e autoridade;
2. atualizar manifesto e índice;
3. fechar questões ou destinar pendências;
4. confirmar linha de base ou última versão válida;
5. revisar acessos;
6. eliminar temporários autorizados;
7. preservar histórico e retrospectiva;
8. registrar custodiante e revisão futura.

## 90. Suspensão

| Campo | Registro |
| --- | --- |
| Motivo | [Preencher] |
| Autoridade | [Nome/papel] |
| Data | [Data] |
| Estado dos artefatos | [Preencher] |
| Risco durante suspensão | [Preencher] |
| Ação de proteção | [Preencher] |
| Responsável mínimo | [Nome/papel] |
| Gatilho de retomada | [Evento] |
| Data de revisão | [Data] |

Suspensão sem revisão tende a se transformar em abandono invisível.

## 91. Cancelamento

Cancelar significa decidir que o projeto não continuará dentro do objeto aberto.

Registre:

- decisão e autoridade;
- motivo;
- versão alcançada;
- trabalho concluído e não concluído;
- compromissos externos;
- dados e acessos a encerrar;
- ativos reutilizáveis;
- riscos remanescentes;
- comunicação;
- aprendizagem possível.

## 92. Reabertura

Reabra quando uma nova evidência ou condição material exige revisar arquitetura encerrada, aprovada ou suspensa.

| Campo | Registro |
| --- | --- |
| Linha de base anterior | LB-ARQ-NNN |
| Gatilho | [Evento/evidência] |
| Objetos afetados | [IDs] |
| Autoridade | [Nome/papel] |
| Escopo da reabertura | [Preencher] |
| Etapa retomada | [Requisitos, alternativas, desenho, validação ou outra] |
| Estado | Reaberta |
| Próximo gate | [PC] |

### 92.1 Mesmo ID ou novo projeto

Mantenha o mesmo ID quando a reabertura revisa a mesma arquitetura e sua continuidade histórica. Crie novo ID quando houver nova decisão patrocinadora, fronteira, autoridade, linha de base autônoma ou implantação independente.

## 93. Substituição

| Elemento | Arquitetura anterior | Nova arquitetura |
| --- | --- | --- |
| ID | ARQ-AAAA-NNN | ARQ-AAAA-NNN |
| Linha de base | LB-ARQ-NNN | LB-ARQ-NNN |
| Data de vigência | [Data final] | [Data inicial] |
| Componentes preservados | [IDs] | [IDs] |
| Pendências transferidas | [IDs] | [IDs] |
| Decisão | DEC-AAAA-NNN | DEC-AAAA-NNN |

### 93.1 Vigência

Declare a partir de quando a nova linha de base substitui a anterior. Até esse marco, a operação e a implantação precisam saber qual referência usar.

## 94. Encerramento

O projeto pode ser encerrado quando:

- seu resultado está definido;
- a linha de base ou última versão válida está identificada;
- decisões estão registradas;
- transição foi aceita ou possui destino alternativo;
- condições remanescentes têm responsáveis;
- acessos e retenção foram revistos;
- retrospectiva foi realizada ou justificada;
- índice e manifesto foram atualizados;
- próxima responsabilidade está clara.

### 94.1 Declaração

> A arquitetura `ARQ-AAAA-NNN` foi encerrada em **[data]** no estado **[resultado]**, sob autoridade de **[nome/papel]**. Sua referência final é **[linha de base ou versão]**. O Módulo 4 recebeu **[pacote/aceite]**; permanecem **[condições e responsáveis]**; os aprendizados foram destinados a **[módulos/objetos]**; e a custódia do dossiê pertence a **[papel]**.

## 95. Encerramento antecipado

Mesmo sem linha de base aprovada, preserve:

- última versão identificável;
- razão da interrupção;
- evidências obtidas;
- decisões emitidas;
- riscos descobertos;
- trabalho que não deve ser reutilizado sem revisão;
- condição de retomada;
- destino de dados e acessos;
- aprendizagem proporcional.

## 96. Eliminação controlada

Antes de eliminar qualquer conteúdo material:

1. confirme autoridade e obrigação de retenção;
2. verifique referências e linhas de base;
3. determine se é fonte, derivação ou temporário;
4. preserve evidência da decisão de eliminação;
5. proteja dados durante o descarte;
6. atualize manifesto, índice e links;
7. confirme que a reconstrução necessária permanece possível.

### 96.1 Registro

| Conteúdo | Motivo | Autoridade | Data | Método/destino | Referências afetadas | Confirmação |
| --- | --- | --- | --- | --- | --- | --- |
| [Arquivo/objeto] | [Preencher] | [Nome/papel] | [Data] | [Preencher] | [Lista] | [Nome/data] |

## 97. Incidente documental

Considere incidente:

- acesso indevido;
- perda ou corrupção;
- exposição de informação;
- alteração não autorizada;
- linha de base ambígua;
- decisão atribuída incorretamente;
- eliminação indevida;
- fonte oficial indisponível;
- envio de versão incorreta para implantação;
- segredo inserido no repositório.

### 97.1 Registro inicial

| Incidente | Detecção | Conteúdo | Impacto | Contenção | Responsável | Escalonamento |
| --- | --- | --- | --- | --- | --- | --- |
| INC-ARQ-___ | [Data/canal] | [IDs] | [Preencher] | [Preencher] | [Papel] | [Papel/prazo] |

## 98. Resposta ao incidente

1. conter exposição ou alteração;
2. preservar evidências;
3. identificar versões e pessoas afetadas;
4. acionar competência adequada;
5. restaurar fonte confiável;
6. corrigir índice, manifesto e linha de base;
7. comunicar segundo obrigação e impacto;
8. testar integridade;
9. registrar causa e melhoria;
10. decidir reabertura quando a arquitetura foi afetada.

## 99. Passagem para o Módulo 4

O registro de arquitetura entrega ao Módulo 4:

- identidade e linha de base;
- escopo autorizado;
- componentes e interfaces;
- prioridades e estados temporais;
- decisões e limites;
- riscos e controles;
- dependências e pré-condições;
- critérios de aceite;
- validações concluídas e pendentes;
- operação alternativa e retorno;
- responsáveis e acessos;
- gatilhos que exigem retorno ao Módulo 3.

### 99.1 Recebimento

| Pergunta do Módulo 4 | Resultado | Pendência | Responsável |
| --- | --- | --- | --- |
| A linha de base é inequívoca? | [Preencher] | [Preencher] | [Papel] |
| Componentes são implementáveis? | [Preencher] | [Preencher] | [Papel] |
| Critérios de aceite são observáveis? | [Preencher] | [Preencher] | [Papel] |
| Condições e riscos estão compreendidos? | [Preencher] | [Preencher] | [Papel] |
| Há autoridade para dúvidas e mudanças? | [Preencher] | [Preencher] | [Papel] |

## 100. Relação com o Módulo 5

O Módulo 5 consulta o dossiê para compreender:

- funcionamento pretendido;
- limites da arquitetura;
- indicadores e respostas;
- riscos residuais;
- papéis de manutenção;
- operação alternativa;
- condições de revisão;
- critérios que distinguem ajuste operacional de mudança arquitetural.

### 100.1 Retorno à arquitetura

Mudança de requisito, finalidade, autoridade, componente crítico, uso de dados, autonomia de IA ou risco aceitável pode exigir reabertura do Módulo 3.

## 101. Relação com o Módulo 6

O dossiê fornece matéria-prima para aprendizagem organizacional:

- decisões e seus fundamentos;
- alternativas descartadas;
- premissas confirmadas ou refutadas;
- estimativas e resultados;
- padrões de risco;
- evidências úteis;
- correções de percurso;
- critérios de arquitetura;
- práticas que reduziram ou aumentaram carga.

O Módulo 6 recebe sínteses governadas, não acesso indiscriminado a conteúdo confidencial.

## 102. Relação com o Módulo 7

Quando houver IA, preserve o necessário para o Ecossistema de IA compreender:

- função e responsabilidade;
- tarefa e limites;
- modelos e fornecedores materiais;
- dados e contexto;
- avaliações;
- guardrails;
- supervisão e contestação;
- incidentes e correções;
- custos e capacidade;
- condição de suspensão e portabilidade.

## 103. Relação com o Módulo 8

Propostas de mudança no método devem apontar para:

- projeto de origem;
- evidência;
- problema recorrente;
- parte do módulo afetada;
- impacto esperado;
- risco da mudança;
- teste sugerido;
- autoridade de incorporação.

Um projeto real pode propor evolução. Não altera diretamente fundamentos, protocolo, ferramentas ou templates.

## 104. Indicadores do portfólio

| Indicador | Pergunta | Fonte | Resposta |
| --- | --- | --- | --- |
| Arquiteturas por estado | Onde o trabalho está concentrado? | Índice | Ajustar capacidade |
| Tempo por gate | Onde há espera ou retrabalho? | Históricos | Investigar causa |
| Dossiês sem próxima ação | Que projeto perdeu continuidade? | Manifestos | Atribuir ou suspender |
| Linhas de base vigentes | Que configurações orientam implantação? | Manifestos `LB` | Confirmar referência |
| Reaberturas | Que condições mudaram? | Índice/decisões | Aprender padrões |
| Links materiais quebrados | O conhecimento continua recuperável? | Verificação | Corrigir |
| Pendências de acesso | Que risco documental existe? | Registros | Tratar |
| Retrospectivas destinadas | O projeto gerou aprendizagem utilizável? | Retrospectivas | Cobrar destino |

### 104.1 Indicador com resposta

O diretório não deve produzir métricas apenas para parecer controlado. Cada indicador precisa apoiar manutenção, decisão, proteção ou aprendizagem.

## 105. Revisão do portfólio

| Frequência | Objetivo | Participantes | Saída |
| --- | --- | --- | --- |
| Semanal/quinzenal durante atividade | Próximas ações e bloqueios | Responsáveis ativos | Atualização de estados |
| Mensal | Capacidade, riscos e decisões pendentes | Coordenação | Priorização |
| Trimestral | Integridade, acessos e linhas de base | Curadoria/governança | Correções |
| Anual | Retenção, portabilidade e aprendizagem | Governança ampliada | Arquivamento/evolução |

## 106. Pesquisa e recuperação

Metadados que favorecem busca:

- ID;
- título não confidencial;
- ano;
- cliente ou código autorizado;
- capacidade;
- processo/unidade;
- estado;
- responsável;
- linha de base;
- palavras-chave;
- relações com outras arquiteturas;
- classificação de acesso.

### 106.1 Busca sem exposição

O índice pode usar código ou descrição reduzida quando o próprio título revelar informação confidencial.

## 107. Reconstrução de decisão

Outra pessoa autorizada deve conseguir seguir:

```text
origem
  -> problema e decisão
  -> requisitos e critérios
  -> alternativas
  -> evidências e compensações
  -> decisão
  -> configuração integrada
  -> validação
  -> linha de base
  -> transição
```

### 107.1 Teste

| Pergunta | Referência localizada | Tempo | Lacuna |
| --- | --- | --- | --- |
| Por que esta alternativa foi escolhida? | [IDs] | [Tempo] | [Preencher] |
| Que risco foi aceito? | [IDs] | [Tempo] | [Preencher] |
| Qual versão foi enviada à implantação? | [IDs] | [Tempo] | [Preencher] |
| Quem poderia reabrir? | [Referência] | [Tempo] | [Preencher] |

## 108. Exemplo focal

```text
2026/
`-- ARQ-2026-001-fluxo-de-propostas/
    |-- README.md
    |-- 01-termo-e-plano.md
    |-- 03-requisitos-e-rastreabilidade.md
    |-- alternativas-e-decisao.md
    |-- 05-arquitetura-integrada.md
    |-- 06-validacao.md
    |-- linhas-de-base/
    |   `-- LB-ARQ-001.md
    |-- 08-transicao-para-implantacao.md
    `-- 09-retrospectiva.md
```

### 108.1 Por que é suficiente

O escopo é limitado, as relações críticas permanecem visíveis e funções compatíveis foram combinadas sem eliminar decisão, validação, linha de base ou transição.

## 109. Exemplo sistêmico

```text
2026/
`-- ARQ-2026-002-sistema-de-atendimento/
    |-- README.md
    |-- 01-termo-de-abertura.md
    |-- 02-plano-de-arquitetura.md
    |-- entrada/
    |-- requisitos/
    |-- alternativas/
    |-- desenhos/
    |-- decisoes/
    |-- validacoes/
    |-- linhas-de-base/
    |-- 05-arquitetura-integrada.md
    |-- 07-relatorio-de-arquitetura.md
    |-- 08-transicao-para-implantacao.md
    `-- 09-retrospectiva-da-arquitetura.md
```

### 109.1 Por que exige expansão

Múltiplas capacidades, públicos, sistemas, dados, decisões e ciclos de validação tornam necessário separar fontes sem perder o manifesto comum.

## 110. Checklist de criação

- [ ] duplicidade foi investigada;
- [ ] ID foi reservado sem colisão;
- [ ] pasta anual e nome canônico foram criados;
- [ ] manifesto mestre foi copiado do modelo vigente;
- [ ] entrada e origem foram registradas;
- [ ] classificação de acesso foi definida;
- [ ] responsável e decisor foram identificados;
- [ ] estado inicial e próxima ação estão explícitos;
- [ ] projeto foi incluído no índice;
- [ ] condições de aceite possuem dono e prazo;
- [ ] templates necessários foram selecionados proporcionalmente.

## 111. Checklist de manutenção ativa

- [ ] estado corresponde ao protocolo;
- [ ] próxima ação possui responsável e prazo/gatilho;
- [ ] manifesto aponta para fontes oficiais;
- [ ] índice está sincronizado;
- [ ] artefatos materiais possuem versão;
- [ ] decisões estão formalizadas;
- [ ] matriz acompanha mudanças;
- [ ] questões abertas possuem tratamento;
- [ ] acessos continuam necessários;
- [ ] links materiais funcionam;
- [ ] arquivos de trabalho possuem destino;
- [ ] apoio de IA está dentro dos limites.

## 112. Checklist da linha de base

- [ ] decisão de aprovação está registrada;
- [ ] escopo e versão estão congelados;
- [ ] catálogo e matriz correspondem à configuração;
- [ ] arquitetura integrada está validada;
- [ ] artefatos e versões estão manifestados;
- [ ] condições e riscos aceitos estão explícitos;
- [ ] autoridade e data estão registradas;
- [ ] existe apenas uma referência vigente para o escopo;
- [ ] versões anteriores permanecem recuperáveis;
- [ ] índice e manifesto foram atualizados.

## 113. Checklist da transição

- [ ] linha de base está identificada;
- [ ] pacote corresponde ao manifesto;
- [ ] versões e acessos foram conferidos;
- [ ] prioridades, dependências e riscos estão visíveis;
- [ ] critérios de aceite são observáveis;
- [ ] pendências possuem destino;
- [ ] operação alternativa e retorno foram comunicados;
- [ ] autoridade para dúvidas e mudanças está clara;
- [ ] Módulo 4 registrou recebimento e resultado;
- [ ] devoluções foram tratadas.

## 114. Checklist de encerramento

- [ ] estado final foi decidido;
- [ ] linha de base ou última versão válida está identificada;
- [ ] decisões e divergências estão localizáveis;
- [ ] transição foi aceita ou recebeu destino alternativo;
- [ ] condições remanescentes possuem responsáveis;
- [ ] retrospectiva foi realizada ou justificada;
- [ ] aprendizados receberam destino;
- [ ] dados, acessos e retenção foram revistos;
- [ ] temporários foram tratados;
- [ ] manifesto e índice foram atualizados;
- [ ] custodiante e revisão futura estão definidos;
- [ ] declaração de encerramento foi registrada.

## 115. Antipadrões

- preencher o modelo da raiz como se fosse um projeto;
- criar pasta sem ID;
- atribuir novo ID a cada versão;
- reutilizar sequencial liberado que já circulou;
- colocar nome confidencial no caminho;
- copiar todos os templates vazios;
- registrar estado apenas no nome do arquivo;
- usar `final`, `finalíssimo` ou `versão-correta` como versionamento;
- manter duas arquiteturas integradas oficiais;
- aprovar sem manifesto de linha de base;
- enviar versão diferente da aprovada ao Módulo 4;
- apagar alternativa rejeitada que sustenta a decisão;
- tratar exportação como fonte editável;
- manter decisão apenas em mensagem;
- guardar credenciais no dossiê;
- abrir acesso total para facilitar colaboração;
- automatizar mudança de estado sem autoridade;
- manter projeto ativo sem próxima ação;
- suspender sem data de revisão;
- encerrar sem destino para pendências;
- reabrir apagando a linha de base anterior;
- produzir índice que não corresponde aos manifestos.

## 116. Sinais de qualidade

Um diretório de registros funciona bem quando:

- uma pessoa autorizada encontra um projeto pelo ID ou objeto;
- o manifesto explica rapidamente o estado e a próxima ação;
- a linha de base pode ser reconstruída sem suposição;
- decisões e riscos aceitos têm autoridade identificável;
- versões históricas permanecem compreensíveis;
- o Módulo 4 recebe exatamente o que foi aprovado;
- conteúdo confidencial não aparece em índices abertos;
- suspensão, reabertura e substituição deixam trilha;
- projetos encerrados geram aprendizagem utilizável;
- manutenção não depende de uma única pessoa.

## 117. Retrospectiva do próprio diretório

| Pergunta | Registro |
| --- | --- |
| Que campo do manifesto foi mais útil? | [Preencher] |
| Que campo gerou carga sem uso? | [Preencher] |
| Que arquivo foi difícil localizar? | [Preencher] |
| Onde houve duplicidade? | [Preencher] |
| Que estado ficou ambíguo? | [Preencher] |
| Que link ou fonte falhou? | [Preencher] |
| Que acesso foi excessivo ou insuficiente? | [Preencher] |
| Que automação poderia reduzir trabalho com segurança? | [Preencher] |
| Que regra precisa ser testada no próximo projeto? | [Preencher] |

## 118. Governança de mudanças deste guia

Mudanças neste `README.md` exigem análise quando alteram:

- unidade de registro;
- padrão de ID;
- estrutura canônica;
- função do índice ou manifesto;
- estados;
- requisitos de linha de base;
- classificação de acesso;
- retenção ou eliminação;
- responsabilidades;
- relação com outros módulos;
- critérios de encerramento ou reabertura.

### 118.1 Histórico

| Versão | Data | Alteração | Evidência | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- |
| 0.1 | 02/08/2026 | Criação do guia do diretório | Estrutura do Módulo 3 | [Nome] | [Registro] |

## 119. Critérios de conclusão deste guia

- [ ] finalidade e fronteiras do diretório estão explícitas;
- [ ] metodologia, template e registro real estão separados;
- [ ] índice, manifesto e linha de base possuem funções distintas;
- [ ] unidade, identificador, sequencial e nome de pasta estão governados;
- [ ] estrutura focal, funcional e sistêmica está disponível;
- [ ] estados e gates correspondem ao protocolo;
- [ ] artefatos e fontes oficiais estão localizáveis;
- [ ] papéis, acesso, dados e IA possuem limites;
- [ ] versionamento, congelamento e mudanças estão tratados;
- [ ] suspensão, cancelamento, reabertura e substituição estão definidos;
- [ ] transição, encerramento, retenção e eliminação estão governados;
- [ ] relação com os Módulos 4, 5, 6, 7 e 8 está explícita;
- [ ] checklists permitem aplicação operacional;
- [ ] exemplos demonstram proporcionalidade;
- [ ] antipadrões e sinais de qualidade apoiam revisão.

## 120. Princípio de encerramento

Um registro de arquitetura não existe para acumular arquivos. Existe para preservar a inteligibilidade de uma transformação: o que precisava mudar, quais possibilidades foram consideradas, que configuração foi autorizada, sob quais limites, por quais razões e com que consequências.

O dossiê cumpre sua função quando torna possível agir no presente, reconstruir o passado e revisar o futuro sem depender da memória de uma pessoa, da permanência de uma ferramenta ou da aparência de completude documental.

No Estúdio LICHTARA, registrar é manter responsabilidade, contexto e aprendizagem disponíveis durante todo o ciclo da arquitetura.

---

## Registro final

**Diretório:** `modulos/modulo-03-arquitetura-organizacional/registros-de-arquitetura/`  
**Documento:** `README.md`  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data:** 02/08/2026  
**Arquivos permanentes previstos:** `README.md`, `indice-de-arquiteturas.md` e `registro-de-arquitetura.md`  
**Unidade de registro:** `ARQ-AAAA-NNN`  
**Próximo documento previsto:** `indice-de-arquiteturas.md`  
**Observações:** [Preencher]
