# Guia das Ferramentas de Arquitetura Organizacional

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Diretório:** `ferramentas/`  
**Tipo:** Guia de seleção, combinação, aplicação e governança  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data de criação:** 02/08/2026

**Documentos relacionados:**

- `../README.md`;
- `../fundamentos-da-arquitetura.md`;
- `../protocolo-de-arquitetura.md`;
- `../matriz-de-rastreabilidade.md`;
- `../templates/plano-de-arquitetura.md`;
- `../templates/05-arquitetura-integrada.md`;
- `../templates/06-registro-de-validacao.md`;
- `../templates/08-transicao-para-implantacao.md`;
- `../templates/09-retrospectiva-da-arquitetura.md`.

---

## 1. Finalidade

Este guia estabelece como o Estúdio LICHTARA seleciona, combina, aplica, valida e desenvolve as ferramentas utilizadas no Módulo 3 — Arquitetura Organizacional.

Sua função é permitir que cada ferramenta possua:

- uma pergunta arquitetural reconhecível;
- relação com requisito, capacidade ou risco;
- momento adequado de aplicação;
- nível de profundidade proporcional;
- entradas suficientes;
- pessoas necessárias;
- saída definida;
- vínculo com decisão, integração ou validação;
- tratamento de dados e sensibilidade;
- responsabilidade humana;
- condição de conclusão;
- destino na Arquitetura Integrada;
- registro na Matriz de Rastreabilidade;
- aprendizado para uso futuro.

A pergunta central é:

> Qual é o menor conjunto de ferramentas capaz de tornar visíveis as relações, alternativas, decisões e condições necessárias para uma arquitetura responsável?

## 2. Tese central

Ferramenta arquitetural é um meio estruturado de investigar, representar, comparar, testar ou decidir uma parte do desenho organizacional.

Ela não possui valor por sua sofisticação, popularidade ou aparência visual. Seu valor depende da capacidade de:

1. responder a uma pergunta real;
2. revelar relações relevantes;
3. reduzir incerteza material;
4. apoiar uma escolha;
5. tornar um componente integrável;
6. permitir validação;
7. preparar implantação responsável.

A capacidade precede a ferramenta. O requisito justifica seu uso. A decisão define a utilidade. A integração demonstra se sua saída faz sentido no conjunto.

## 3. Lugar das ferramentas no método

| Elemento | Função |
| --- | --- |
| Diagnóstico | Explica a realidade que exige transformação |
| Requisito | Declara condição que precisa ser atendida |
| Capacidade | Define o que a organização precisa conseguir realizar |
| Pergunta de desenho | Delimita o que precisa ser compreendido ou decidido |
| Ferramenta | Estrutura a investigação ou o desenho |
| Saída dimensional | Registra uma resposta parcial |
| Componente | Integra a configuração futura |
| Arquitetura Integrada | Demonstra o funcionamento conjunto |
| Validação | Confronta o desenho com requisitos, pessoas e cenários |
| Decisão | Autoriza escolha, condição, risco ou continuidade |
| Implantação | Transforma o desenho aprovado em realidade |

Ferramentas entram depois que problema, decisão, escopo, requisitos e capacidades possuem clareza suficiente. Podem voltar a ser usadas em ciclos quando integração, avaliação ou validação revelar uma lacuna.

## 4. O que é uma ferramenta neste módulo

Uma ferramenta pode assumir a forma de:

- mapa;
- matriz;
- modelo;
- roteiro de perguntas;
- oficina estruturada;
- comparação;
- simulação;
- protótipo;
- análise de relações;
- ficha de componente;
- teste de cenário;
- representação visual;
- registro tabular;
- combinação dessas formas.

O nome da ferramenta não determina seu formato final. A representação deve ser escolhida pela clareza que produz e pela capacidade real de manutenção da organização.

## 5. O que uma ferramenta não é

Ferramenta não deve ser confundida com:

- método completo;
- arquitetura integrada;
- requisito;
- decisão;
- evidência diagnóstica;
- componente futuro;
- software específico;
- template preenchido sem análise;
- diagrama produzido para apresentação;
- prova automática de qualidade;
- substituição da participação humana;
- autorização para implantação.

Uma matriz de responsabilidades pode revelar lacunas de autoridade. Ela não atribui autoridade por si mesma. Um fluxo pode mostrar uma sequência. Ele não garante que pessoas, informação e recursos permitirão executá-la.

## 6. Distinção entre ferramenta, artefato e componente

| Conceito | Definição | Exemplo |
| --- | --- | --- |
| Ferramenta | Meio utilizado para investigar ou desenhar | Arquitetura de processos e fluxos |
| Artefato | Registro produzido durante o trabalho | Mapa do fluxo futuro v0.3 |
| Componente | Elemento que integrará a arquitetura aprovada | Processo de aprovação de conteúdo |
| Registro de decisão | Evidência da escolha autorizada | DEC-ARQ-012 |
| Linha de base | Conjunto de versões aprovado | LB-ARQ-003 |

Uma saída de ferramenta somente se torna parte da arquitetura quando:

- foi interpretada;
- possui vínculos rastreáveis;
- foi integrada às demais dimensões;
- recebeu validação proporcional;
- foi aprovada ou incluída em linha de base por autoridade competente.

## 7. Unidade de seleção

A unidade de seleção não é a dimensão isolada. É a combinação:

> pergunta + requisito ou capacidade + decisão + saída + validação

Para cada uso, registrar:

| Campo | Pergunta |
| --- | --- |
| Pergunta | O que precisa ser compreendido ou definido? |
| Origem | Que requisito, capacidade, risco ou decisão justifica o trabalho? |
| Dimensão | Em que parte da arquitetura a questão se manifesta? |
| Ferramenta | Que estrutura ajudará a produzir resposta? |
| Saída | Que registro ou modelo será produzido? |
| Uso | Quem utilizará a saída e para quê? |
| Validação | Como saberemos se a saída é suficiente? |
| Integração | Em que componente ou relação ela será incorporada? |

## 8. Princípios de seleção

1. **Pergunta antes da ferramenta** — primeiro delimitar a questão.
2. **Capacidade antes da solução** — não escolher meio técnico antes da função.
3. **Critério antes da comparação** — não calibrar avaliação depois da preferência.
4. **Menor conjunto suficiente** — evitar instrumentos sem uso decisório.
5. **Integração desde o início** — toda saída deve prever relações com outras dimensões.
6. **Proporcionalidade** — detalhe acompanha risco, impacto e novidade.
7. **Participação pertinente** — envolver quem conhece, utiliza, decide ou será afetado.
8. **Exceções visíveis** — não representar apenas o caminho esperado.
9. **Manutenção considerada** — o artefato precisa ter função e custodiante.
10. **Responsabilidade humana** — IA apoia; pessoas interpretam e decidem.
11. **Rastreabilidade** — origem e destino permanecem localizáveis.
12. **Validação** — representação plausível não equivale a desenho adequado.
13. **Reversibilidade** — decisões técnicas e organizacionais devem considerar retorno.
14. **Aprendizagem** — uso real melhora as fichas e o próprio catálogo.

## 9. Arquitetura do portfólio de ferramentas

O portfólio possui cinco funções complementares.

| Função | Pergunta | Ferramentas principais |
| --- | --- | --- |
| Referenciar e contrastar | O que existe, o que precisa existir e o que muda? | Estado atual e estado futuro; mapa de capacidades |
| Desenhar o trabalho e a governança | Como o trabalho acontece e quem responde? | Processos e fluxos; papéis, responsabilidades e alçadas |
| Desenhar memória e coordenação | Que informação, conhecimento, comunicação e documentação sustentam o trabalho? | Informação e conhecimento; comunicação; documental |
| Desenhar suporte técnico e inteligência | Que tecnologia, integração, IA, indicador e controle são necessários? | Tecnologia e integrações; IA; indicadores |
| Comparar e decidir | Que configuração atende melhor aos critérios e impactos? | Avaliação de alternativas; protótipo; simulação |

Nenhuma função substitui a integração. As saídas convergem para a Arquitetura Integrada.

## 10. Catálogo oficial

| Arquivo | Função principal | Pergunta central | Saída típica |
| --- | --- | --- | --- |
| `01-estado-atual-e-estado-futuro.md` | Delimitar referência, mudança e capacidades | O que deve ser preservado, alterado, criado ou encerrado? | Comparação atual–futuro e mapa de capacidades |
| `02-arquitetura-de-processos-e-fluxos.md` | Desenhar trabalho, transferências e exceções | Como resultados, informação e responsabilidade se movimentam? | Processos e fluxos futuros |
| `03-papeis-responsabilidades-e-alcadas.md` | Distribuir participação, responsabilidade e autoridade | Quem executa, responde, decide, consulta, verifica e mantém? | Matriz de papéis e alçadas |
| `04-arquitetura-de-informacao-e-conhecimento.md` | Organizar objetos informacionais e conhecimento crítico | O que precisa ser produzido, encontrado, compreendido e preservado? | Arquitetura de informação e conhecimento |
| `05-arquitetura-da-comunicacao.md` | Desenhar coordenação e passagem de contexto | Que comunicação sustenta decisão, alinhamento e mudança? | Sistema de eventos, públicos e confirmações |
| `06-arquitetura-documental.md` | Definir memória formal e ciclo de vida documental | Que documento precisa existir, para cumprir qual função e sob qual controle? | Arquitetura de documentos e registros |
| `07-arquitetura-de-indicadores.md` | Relacionar observação, interpretação e decisão | O que precisa ser observado para operar, decidir, aprender e proteger? | Sistema de indicadores, controles e respostas |
| `08-arquitetura-de-tecnologia-e-integracoes.md` | Definir capacidades técnicas e interfaces | Que suporte técnico é necessário e como sistemas e dados se conectam? | Arquitetura técnica e de integrações |
| `09-arquitetura-de-inteligencia-artificial.md` | Definir funções de IA, limites e supervisão | Que capacidade pode ser ampliada por IA e sob qual responsabilidade? | Arquitetura de funções e controles de IA |
| `10-avaliacao-de-alternativas.md` | Comparar configurações por critérios prévios | Que alternativa oferece a melhor relação entre atendimento, impacto e sustentabilidade? | Avaliação comparativa e recomendação |

## 11. Técnicas transversais

O protocolo também prevê três técnicas que não constituem, neste estágio, fichas autônomas do diretório.

| Técnica | Onde é governada | Uso |
| --- | --- | --- |
| Mapa de capacidades | `01-estado-atual-e-estado-futuro.md` e Arquitetura Integrada | Relacionar capacidades existentes, futuras, dependências e horizontes |
| Protótipo | Ficha dimensional pertinente e Registro de Validação | Materializar parte do desenho para obter evidência antes da aprovação |
| Simulação | Ficha dimensional pertinente, Arquitetura Integrada e Registro de Validação | Executar cenários normais, excepcionais, de falha e retorno |

Uma técnica transversal pode receber arquivo próprio no futuro quando recorrência, complexidade e aprendizagem demonstrarem necessidade. A criação exige proposta, análise de duplicação, teste e decisão de governança.

## 12. Fluxo de uso

```text
Problema e decisão
        ↓
Requisitos, capacidades, riscos e perguntas
        ↓
Seleção proporcional das ferramentas
        ↓
Saídas dimensionais e alternativas
        ↓
Integração de componentes e interfaces
        ↓
Avaliação, simulação e validação
        ↓
Decisão, linha de base e implantação
```

O fluxo é iterativo. Uma incompatibilidade encontrada na integração pode devolver o trabalho a qualquer ferramenta necessária. O retorno deve registrar a lacuna, os objetos afetados e a nova versão.

## 13. Porta de seleção

Uma ferramenta somente deve entrar no plano quando todas as perguntas aplicáveis possuírem resposta suficiente.

| Condição | Registro |
| --- | --- |
| Que pergunta responderá? | [Preencher] |
| Que requisito, capacidade, risco ou decisão a justifica? | [IDs] |
| Por que a pergunta não pode ser respondida com registro já existente? | [Preencher] |
| Que saída verificável produzirá? | [Preencher] |
| Quem utilizará essa saída? | [Nome/papel] |
| Que decisão, integração ou validação ela apoiará? | [Preencher] |
| Quem precisa participar? | [Nomes/papéis] |
| Que dados ou documentos serão necessários? | [Preencher] |
| Que nível de detalhe é suficiente? | [Preencher] |
| Quem validará? | [Nome/papel] |

Se a ferramenta não possui usuário, decisão, integração ou validação identificável, sua seleção deve ser suspensa.

## 14. Teste de necessidade

- [ ] Existe pergunta relevante ainda não respondida.
- [ ] A resposta pode alterar componente, relação, alternativa ou decisão.
- [ ] O requisito ou capacidade de origem está identificado.
- [ ] A saída será incorporada a artefato oficial.
- [ ] A equipe possui competência para aplicar e interpretar.
- [ ] Participantes necessários podem contribuir.
- [ ] A profundidade é compatível com o impacto.
- [ ] Não existe saída equivalente válida.
- [ ] O custo de aplicação é proporcional à incerteza reduzida.
- [ ] A manutenção posterior está prevista quando necessária.

### 14.1 Motivos legítimos para não utilizar

- questão fora do escopo;
- dimensão sem efeito material;
- informação já disponível e validada;
- saída não altera decisão;
- detalhe pertence à implantação;
- ferramenta redundante;
- custo superior ao valor esperado;
- competência necessária indisponível;
- risco ou sensibilidade impede aplicação responsável;
- projeto focal pode utilizar representação mais simples.

## 15. Árvore decisória por pergunta

| Se a pergunta principal é... | Comece por... | Combine com... |
| --- | --- | --- |
| O que precisa mudar? | Estado atual e estado futuro | Capacidades e avaliação de alternativas |
| Como o trabalho deverá acontecer? | Processos e fluxos | Papéis, informação, documentos e indicadores |
| Quem pode fazer ou decidir? | Papéis, responsabilidades e alçadas | Processos, comunicação e controles |
| Que informação precisa circular? | Informação e conhecimento | Processos, comunicação, documentos e tecnologia |
| Como preservar conhecimento? | Informação e conhecimento | Documental, comunicação e IA |
| Que coordenação é necessária? | Comunicação | Papéis, processos e documentos |
| Que registros sustentam continuidade? | Documental | Informação, papéis, tecnologia e retenção |
| Como saber se funciona? | Indicadores | Processos, requisitos, riscos e validação |
| Que sistema ou integração é necessário? | Tecnologia e integrações | Informação, processos, segurança e continuidade |
| Onde IA pode ampliar capacidade? | Inteligência artificial | Processos, dados, papéis, tecnologia e indicadores |
| Qual configuração escolher? | Avaliação de alternativas | Todas as dimensões materiais |

## 16. Seleção por tipo de incerteza

| Incerteza | Ferramenta primária | Evidência esperada |
| --- | --- | --- |
| Fronteira entre atual e futuro | Estado atual e estado futuro | Diferenças, preservações e transição |
| Capacidade necessária | Estado atual e estado futuro | Mapa de capacidades e manifestações observáveis |
| Sequência ou exceção | Processos e fluxos | Casos, regras e transferências |
| Responsabilidade ou autoridade | Papéis, responsabilidades e alçadas | Matriz de participação e decisão |
| Origem, destino ou qualidade de informação | Informação e conhecimento | Modelo de objetos e fluxos informacionais |
| Coordenação ou alinhamento | Comunicação | Eventos, públicos, mensagens e confirmação |
| Memória, versão ou retenção | Documental | Tipos documentais e ciclos de vida |
| Métrica ou resposta | Indicadores | Definições, fontes, limites e decisões |
| Compatibilidade ou continuidade técnica | Tecnologia e integrações | Componentes, interfaces, falhas e recuperação |
| Função, supervisão ou risco de IA | Inteligência artificial | Funções, dados, critérios e autoridade humana |
| Compensação entre configurações | Avaliação de alternativas | Comparação por critérios e impactos |

## 17. Seleção por dimensão

| Dimensão principal | Ferramenta primária | Ferramentas de integração frequentes |
| --- | --- | --- |
| Capacidades | Estado atual e estado futuro | Alternativas, indicadores e processos |
| Processos | Processos e fluxos | Papéis, informação, documentos, tecnologia e IA |
| Fluxos | Processos e fluxos | Comunicação, informação, integrações e indicadores |
| Papéis | Papéis, responsabilidades e alçadas | Processos, comunicação e conhecimento |
| Decisões | Papéis, responsabilidades e alçadas | Informação, indicadores e alternativas |
| Informação | Informação e conhecimento | Processos, documentos, tecnologia e IA |
| Conhecimento | Informação e conhecimento | Comunicação, documentos, papéis e IA |
| Comunicação | Comunicação | Papéis, processos e documentos |
| Documentação | Documental | Informação, tecnologia, papéis e segurança |
| Tecnologia | Tecnologia e integrações | Processos, informação, continuidade e alternativas |
| IA | Inteligência artificial | Tecnologia, informação, papéis, processos e indicadores |
| Indicadores | Indicadores | Requisitos, processos, decisões e riscos |
| Alternativas | Avaliação de alternativas | Todas as ferramentas materiais |

## 18. Seleção por etapa do protocolo

| Etapa | Ferramentas mais prováveis | Uso |
| --- | --- | --- |
| Estado atual de referência | Estado atual e estado futuro | Delimitar referência sem repetir diagnóstico |
| Capacidades futuras | Estado atual e estado futuro | Formular capacidade, resultado e dependências |
| Geração de alternativas | Todas conforme espaços de variação | Produzir configurações materialmente distintas |
| Aprofundamento dimensional | Fichas dimensionais pertinentes | Desenhar componentes suficientes |
| Integração | Processos, papéis, informação, tecnologia, IA e indicadores | Examinar interfaces e efeitos cruzados |
| Avaliação | Avaliação de alternativas | Comparar critérios, impactos e compensações |
| Consolidação | Ferramentas das dimensões selecionadas | Detalhar arquitetura mínima e evolução |
| Validação | Protótipo, simulação e fichas pertinentes | Confrontar cenários, pessoas e requisitos |
| Transição | Estado atual/futuro, processos, papéis e tecnologia conforme escopo | Explicitar sequência, dependências e aceite |
| Retrospectiva | Registros de uso das ferramentas | Avaliar utilidade, ruído, carga e aprendizagem |

## 19. Seleção por decisão apoiada

| Decisão | Ferramentas mínimas prováveis | Complementos conforme risco |
| --- | --- | --- |
| Redesenhar um fluxo | Estado atual/futuro; processos; papéis | Informação, comunicação, documentos, indicadores |
| Criar uma nova função | Papéis e alçadas; processos | Conhecimento, comunicação, indicadores |
| Escolher ferramenta digital | Tecnologia e integrações; alternativas | Processos, informação, dados, continuidade |
| Introduzir IA | IA; tecnologia; processos; papéis | Informação, indicadores, documentação e alternativas |
| Organizar conhecimento | Informação e conhecimento | Documental, comunicação, IA e tecnologia |
| Criar sistema de indicadores | Indicadores | Processos, decisões, informação e tecnologia |
| Integrar áreas | Estado atual/futuro; processos; papéis | Comunicação, informação, tecnologia e indicadores |
| Padronizar documentos | Documental | Processos, papéis, informação e tecnologia |
| Manter estado atual conscientemente | Estado atual/futuro; alternativas | Riscos, indicadores e condição de revisão |

## 20. Seleção por saída esperada

| Saída necessária | Ferramenta |
| --- | --- |
| Comparação entre condições | Estado atual e estado futuro |
| Mapa de capacidades | Estado atual e estado futuro |
| Processo futuro | Processos e fluxos |
| Fluxo de exceção | Processos e fluxos |
| Matriz de responsabilidade | Papéis, responsabilidades e alçadas |
| Matriz de decisão e alçada | Papéis, responsabilidades e alçadas |
| Modelo de objetos informacionais | Informação e conhecimento |
| Sistema de preservação do conhecimento | Informação e conhecimento |
| Arquitetura de eventos de comunicação | Comunicação |
| Catálogo documental e ciclo de vida | Documental |
| Árvore de indicadores e respostas | Indicadores |
| Mapa técnico e de integrações | Tecnologia e integrações |
| Ficha de função de IA | Inteligência artificial |
| Matriz comparativa | Avaliação de alternativas |
| Evidência de funcionamento | Protótipo ou simulação |

## 21. Seleção por risco

Quanto maior o risco, maior deve ser a qualidade da evidência e da validação, não necessariamente a quantidade de ferramentas.

| Risco dominante | Ferramentas essenciais | Proteção adicional |
| --- | --- | --- |
| Impacto humano | Papéis; processos; comunicação | Participação das pessoas afetadas e análise de carga |
| Dados pessoais ou sensíveis | Informação; tecnologia; IA; documental | Especialista, minimização e validação de acesso |
| Decisão crítica | Papéis e alçadas; indicadores; alternativas | Registro formal, cenários e autoridade |
| Continuidade | Processos; tecnologia; informação | Falhas, retorno, substituição e teste |
| Dependência de fornecedor | Tecnologia; alternativas | Portabilidade, saída e operação alternativa |
| Conhecimento concentrado | Informação e conhecimento; papéis | Transferência, documentação e redundância |
| Automação | Processos; tecnologia; indicadores | Exceções, supervisão, reversibilidade e logs |
| IA | IA; informação; papéis; indicadores | Avaliação, supervisão humana e interrupção |
| Mudança sistêmica | Estado atual/futuro; todas as dimensões materiais | Arquitetura integrada ampliada e validação transversal |

## 22. Seleção por escopo

### 22.1 Arquitetura focal

Utilizar uma representação central e apenas as integrações materiais.

Exemplo de conjunto:

- estado atual e futuro reduzido;
- uma ferramenta dimensional principal;
- registro de papéis ou decisões quando necessário;
- avaliação simples de alternativas;
- teste de cenário;
- integração focal.

### 22.2 Arquitetura funcional

Selecionar ferramentas para todas as dimensões que sustentam a capacidade ampla, normalmente incluindo:

- estado atual e futuro;
- processos e fluxos;
- papéis e alçadas;
- informação e conhecimento;
- uma ou mais fichas de suporte;
- indicadores;
- avaliação de alternativas;
- protótipo ou simulação conforme risco.

### 22.3 Arquitetura sistêmica

Utilizar frentes dimensionais coordenadas, modelos de interface e integração progressiva. Não significa aplicar todas as ferramentas automaticamente. Cada frente continua sujeita ao teste de necessidade.

## 23. Conjuntos mínimos recomendados

| Situação | Núcleo mínimo | Condição para ampliar |
| --- | --- | --- |
| Mudança simples de fluxo | Atual/futuro + processos + papéis + alternativas | Informação, tecnologia ou risco material |
| Organização documental | Atual/futuro + documental + papéis | Integração técnica, retenção ou conhecimento crítico |
| Comunicação interna | Atual/futuro + comunicação + papéis | Fluxo, documentos, indicadores ou múltiplos canais |
| Sistema de conhecimento | Informação/conhecimento + papéis + documental | IA, tecnologia, comunicação ou risco de perda |
| Seleção de sistema | Processos + informação + tecnologia + alternativas | Migração, integrações, segurança ou IA |
| Introdução de IA | Processos + papéis + informação + tecnologia + IA + indicadores + alternativas | Alto impacto, dados sensíveis ou autonomia relevante |
| Sistema de gestão | Atual/futuro + processos + papéis + informação + indicadores + alternativas | Tecnologia, comunicação, documentos e IA conforme desenho |

Esses conjuntos são pontos de partida. O projeto deve justificar inclusões e exclusões.

## 24. Conjuntos expandidos

| Configuração | Quando utilizar | Componentes adicionais |
| --- | --- | --- |
| Foco em pessoas | Mudança altera carga, autonomia ou autoridade | Papéis, comunicação, conhecimento e cenários humanos |
| Foco em dados | Fluxo depende de qualidade, acesso e proteção | Informação, documental, tecnologia, IA e controles |
| Foco em continuidade | Falha interrompe capacidade crítica | Processos, tecnologia, conhecimento, papéis e simulação |
| Foco em escala | Volume, canais ou unidades mudarão | Processos, tecnologia, indicadores e alternativas |
| Foco em aprendizagem | Capacidade precisa evoluir por evidências | Conhecimento, indicadores, comunicação e documentação |
| Foco em ecossistema | Múltiplas áreas e sistemas interagem | Todas as dimensões materiais e matriz de interfaces |

## 25. Ordem de integração

Uma sequência frequente é:

1. delimitar atual e futuro;
2. formular capacidades;
3. desenhar processos e fluxos;
4. atribuir papéis, responsabilidades e alçadas;
5. definir informação e conhecimento;
6. desenhar comunicação e documentação;
7. definir indicadores e controles;
8. desenhar tecnologia e integrações;
9. inserir IA apenas onde a função estiver clara;
10. integrar interfaces;
11. comparar alternativas completas;
12. prototipar ou simular pontos críticos;
13. validar;
14. consolidar a linha de base.

A ordem pode variar. O projeto deve registrar dependências e ciclos de retorno.

## 26. Relações frequentes entre ferramentas

| Origem | Saída | Ferramenta de destino | Uso |
| --- | --- | --- | --- |
| Estado atual/futuro | Capacidade futura | Processos | Definir trabalho necessário |
| Processos | Atividade/decisão | Papéis | Atribuir execução e autoridade |
| Processos | Entrada/saída | Informação | Definir objeto e qualidade |
| Informação | Necessidade de coordenação | Comunicação | Desenhar passagem de contexto |
| Informação | Memória exigida | Documental | Criar registro e ciclo de vida |
| Processo/informação | Necessidade técnica | Tecnologia | Definir suporte e integração |
| Processo/papel | Função ampliável | IA | Definir tarefa e supervisão |
| Requisito/risco | Sinal observável | Indicadores | Definir medição e resposta |
| Todas as dimensões | Configuração integrada | Alternativas | Comparar atendimento e impacto |
| Alternativa | Ponto incerto | Protótipo/simulação | Produzir evidência |

## 27. Estado atual e estado futuro

**Arquivo:** `01-estado-atual-e-estado-futuro.md`

### 27.1 Utilizar quando

- houver confusão entre diagnóstico e solução;
- for necessário preservar capacidades existentes;
- alternativas precisarem de referência comum;
- mudanças, encerramentos ou transições precisarem ser explícitos;
- capacidades futuras ainda estiverem vagas;
- diferentes públicos possuírem imagens incompatíveis do futuro.

### 27.2 Não utilizar para

- repetir todo o diagnóstico;
- detalhar procedimentos operacionais;
- apresentar futuro ideal sem requisitos;
- justificar uma solução já escolhida;
- congelar o estado atual como única referência possível.

### 27.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Síntese diagnóstica, capacidades, requisitos, riscos, restrições e horizonte | Comparação atual–futuro, mapa de capacidades, mudanças, preservações e questões de transição |

### 27.4 Integrações críticas

- requisitos definem o que precisa mudar;
- capacidades orientam processos e componentes;
- alternativas representam futuros distintos;
- transição explicita o intervalo entre os estados;
- indicadores tornam manifestações futuras observáveis.

## 28. Arquitetura de processos e fluxos

**Arquivo:** `02-arquitetura-de-processos-e-fluxos.md`

### 28.1 Utilizar quando

- uma capacidade depende de sequência recorrente;
- existem transferências, decisões ou esperas;
- o trabalho atravessa papéis ou sistemas;
- exceções precisam de tratamento;
- automação, tecnologia ou IA será considerada;
- a implantação precisa compreender o funcionamento esperado.

### 28.2 Não utilizar para

- documentar cada gesto sem efeito arquitetural;
- transformar exceção rara em processo central;
- automatizar antes de compreender finalidade e regra;
- substituir definição de autoridade;
- impor notação que participantes não conseguem interpretar.

### 28.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Capacidades, requisitos, eventos, casos, papéis atuais, informação e riscos | Processos futuros, fluxos, decisões, exceções, interfaces, controles e critérios de aceite |

### 28.4 Integrações críticas

- cada atividade possui finalidade e responsável;
- cada decisão possui autoridade e informação;
- cada transferência possui confirmação;
- cada exceção possui tratamento;
- cada automação possui supervisão e retorno.

## 29. Papéis, responsabilidades e alçadas

**Arquivo:** `03-papeis-responsabilidades-e-alcadas.md`

### 29.1 Utilizar quando

- responsabilidade estiver concentrada ou ambígua;
- decisões sofrerem atraso ou conflito;
- novos processos, ferramentas ou agentes alterarem participação;
- houver delegação, aprovação, supervisão ou manutenção;
- uma pessoa exercer múltiplas funções;
- responsabilidade precisar ser acompanhada de autoridade.

### 29.2 Não utilizar para

- produzir organograma sem relação com o trabalho;
- transformar nomes de pessoas em arquitetura permanente;
- distribuir responsabilidade sem recurso ou informação;
- confundir consulta com veto;
- usar matriz como substituta de negociação real.

### 29.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Processos, decisões, requisitos, capacidades, riscos, carga e conhecimento | Papéis, responsabilidades, participação, alçadas, substituição, escalonamento e manutenção |

### 29.4 Integrações críticas

- processo define onde a participação ocorre;
- informação sustenta decisão;
- comunicação coordena passagens;
- conhecimento permite execução;
- indicadores precisam de dono e autoridade de resposta.

## 30. Arquitetura de informação e conhecimento

**Arquivo:** `04-arquitetura-de-informacao-e-conhecimento.md`

### 30.1 Utilizar quando

- trabalho depende de informação correta e oportuna;
- conhecimento está concentrado ou implícito;
- diferentes fontes disputam autoridade;
- decisões perdem contexto;
- tecnologia, IA ou documentação depende de dados estruturados;
- continuidade exige transferência e atualização.

### 30.2 Não utilizar para

- coletar informação sem finalidade;
- transformar todo conhecimento em documento;
- armazenar dados sem base, acesso ou retenção;
- confundir volume de informação com qualidade;
- eliminar julgamento humano por formalização excessiva.

### 30.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Processos, decisões, papéis, objetos existentes, fontes, riscos e requisitos de dados | Objetos informacionais, fontes de verdade, fluxos, qualidade, acessos, conhecimentos críticos, curadoria e proteção |

### 30.4 Integrações críticas

- informação circula por processos e integrações;
- conhecimento depende de pessoas, prática e memória;
- documentos registram parte do conhecimento;
- IA depende de dados adequados e contexto;
- indicadores dependem de definições e fontes confiáveis.

## 31. Arquitetura da comunicação

**Arquivo:** `05-arquitetura-da-comunicacao.md`

### 31.1 Utilizar quando

- coordenação depender de eventos recorrentes;
- decisões não alcançarem públicos afetados;
- passagens perderem contexto;
- mudança exigir compreensão, participação ou confirmação;
- múltiplos canais criarem dispersão;
- exceções precisarem de escalonamento.

### 31.2 Não utilizar para

- criar reuniões sem decisão ou trabalho associado;
- enviar mais mensagens para compensar autoridade ambígua;
- tratar comunicação como transmissão unilateral;
- substituir documentação necessária;
- impor canal sem considerar acesso e hábito.

### 31.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Processos, decisões, públicos, eventos, mudanças, canais, riscos e documentos | Eventos de comunicação, mensagens mínimas, emissores, destinatários, canais, confirmações e escalonamentos |

### 31.4 Integrações críticas

- papéis definem quem comunica e recebe;
- processos definem o momento;
- documentos preservam decisões;
- indicadores acionam comunicação;
- implantação transforma desenho em plano de comunicação e mudança.

## 32. Arquitetura documental

**Arquivo:** `06-arquitetura-documental.md`

### 32.1 Utilizar quando

- continuidade depende de registro persistente;
- versões causam conflito;
- decisões, aprovações ou evidências precisam ser preservadas;
- informação precisa de forma oficial;
- obrigações exigem retenção ou descarte;
- implantação precisará criar, migrar ou encerrar documentos.

### 32.2 Não utilizar para

- documentar tudo;
- criar procedimento para corrigir falta de autoridade;
- duplicar fonte de verdade;
- preservar conteúdo sem uso ou obrigação;
- escolher plataforma antes de definir função documental.

### 32.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Processos, informação, decisões, requisitos, obrigações, públicos e tecnologia | Catálogo documental, função, autoria, estados, versões, acesso, retenção, descarte e migração |

### 32.4 Integrações críticas

- documentos apoiam processos e decisões;
- informação define conteúdo e qualidade;
- tecnologia sustenta armazenamento e acesso;
- papéis definem autoria, aprovação e custódia;
- IA pode apoiar produção, classificação e recuperação dentro de limites.

## 33. Arquitetura de indicadores

**Arquivo:** `07-arquitetura-de-indicadores.md`

### 33.1 Utilizar quando

- capacidade precisa de manifestação observável;
- decisão recorrente depende de sinal;
- risco ou controle precisa de acompanhamento;
- operação deverá reconhecer desvio;
- implantação exige critério de aceite;
- aprendizagem futura depende de evidência.

### 33.2 Não utilizar para

- medir o que não apoia decisão;
- criar metas sem linha de referência ou autoridade;
- usar quantidade como substituta de qualidade;
- comparar públicos ou períodos incompatíveis;
- automatizar coleta sem definir interpretação e resposta.

### 33.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Capacidades, requisitos, processos, decisões, riscos, controles, dados e critérios de aceite | Indicadores, definições, fontes, frequência, limites, responsáveis, respostas e guardrails |

### 33.4 Integrações críticas

- indicador possui objeto e decisão;
- fonte de dados possui qualidade e acesso;
- desvio possui responsável e resposta;
- limite de interpretação está explícito;
- implantação e operação sabem como verificar.

## 34. Arquitetura de tecnologia e integrações

**Arquivo:** `08-arquitetura-de-tecnologia-e-integracoes.md`

### 34.1 Utilizar quando

- capacidade depende de sistema, plataforma ou automação;
- dados precisam circular entre componentes;
- seleção de fornecedor será decidida;
- continuidade, segurança ou acesso são materiais;
- migração ou portabilidade será necessária;
- IA depende de infraestrutura técnica.

### 34.2 Não utilizar para

- começar pela ferramenta preferida;
- reproduzir catálogo de funcionalidades;
- detalhar implementação antes da decisão;
- assumir integração porque existe API;
- ignorar operação manual ou retorno;
- aceitar dependência sem saída e manutenção.

### 34.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Capacidades, processos, informação, requisitos técnicos, riscos, recursos e alternativas | Componentes técnicos, dados, integrações, acessos, segurança, continuidade, portabilidade e critérios de seleção |

### 34.4 Integrações críticas

- tecnologia sustenta capacidade definida;
- processos determinam uso e exceções;
- informação determina dados e interfaces;
- papéis determinam administração e suporte;
- indicadores monitoram disponibilidade e qualidade.

## 35. Arquitetura de inteligência artificial

**Arquivo:** `09-arquitetura-de-inteligencia-artificial.md`

### 35.1 Utilizar quando

- uma função cognitiva pode ser ampliada;
- pesquisa, análise, redação, classificação, documentação ou gestão pode receber apoio;
- automação probabilística é considerada;
- a organização precisa separar papéis de IA;
- dados, verificação, autoria e responsabilidade precisam de desenho;
- mais de um agente ou função interage.

### 35.2 Não utilizar para

- adicionar IA sem tarefa específica;
- substituir responsabilidade, autoridade ou cuidado humano;
- processar dado sem autorização adequada;
- tratar fluência como confiabilidade;
- implantar sem critério de qualidade, supervisão e interrupção;
- criar persona antes de definir função operacional.

### 35.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Capacidade, tarefa, processo, dados, risco, papel humano, tecnologia e critério de qualidade | Funções de IA, entradas, saídas, permissões, limites, supervisão, avaliação, logs, falhas e encerramento |

### 35.4 Integrações críticas

- processo delimita tarefa e momento;
- papéis preservam responsabilidade;
- informação define contexto e dados permitidos;
- tecnologia define ambiente e integrações;
- indicadores verificam qualidade e risco;
- documentação preserva versão, uso e decisão.

## 36. Avaliação de alternativas

**Arquivo:** `10-avaliacao-de-alternativas.md`

### 36.1 Utilizar quando

- existir escolha material;
- configurações produzirem impactos diferentes;
- ferramenta, fornecedor ou grau de automação precisar ser escolhido;
- critérios entrarem em tensão;
- risco, custo, manutenção ou reversibilidade forem relevantes;
- não intervenção permanecer como opção real.

### 36.2 Não utilizar para

- legitimar decisão já tomada;
- comparar alternativas apenas nominais;
- atribuir pesos sem justificativa;
- converter julgamento em soma automática;
- esconder condição impeditiva em média;
- excluir opção simples por aparência de menor sofisticação.

### 36.3 Entradas e saídas

| Entradas | Saídas |
| --- | --- |
| Alternativas integradas, requisitos, critérios, riscos, custos, impactos, manutenção e maturidade | Matriz comparativa, compensações, condições impeditivas, incertezas e recomendação |

### 36.4 Integrações críticas

- critérios são definidos antes da avaliação;
- alternativas possuem detalhe comparável;
- requisitos obrigatórios não desaparecem na pontuação;
- incerteza é registrada;
- decisão final permanece humana e formal.

## 37. Mapa de capacidades

O mapa de capacidades integra a ficha `01-estado-atual-e-estado-futuro.md`.

### 37.1 Função

Relacionar o que a organização consegue realizar hoje, o que precisa conseguir realizar, que resultados demonstram essa capacidade e que dependências existem.

### 37.2 Estrutura mínima

| Campo | Conteúdo |
| --- | --- |
| ID | CAP-NNN |
| Capacidade | Verbo e resultado organizacional |
| Estado atual | Existente, parcial, ausente ou desconhecida |
| Estado futuro | Condição necessária |
| Manifestação | Sinal observável de funcionamento |
| Requisitos | IDs relacionados |
| Dependências | Outras capacidades/componentes |
| Horizonte | Mínima, próximo ciclo ou futura |
| Responsável futuro | Papel |

### 37.3 Limites

Capacidade não é departamento, cargo, atividade isolada, ferramenta ou lista de recursos. Ela expressa aquilo que a organização precisa conseguir realizar de modo suficientemente confiável e contínuo.

## 38. Protótipo e simulação

### 38.1 Protótipo

Representação limitada criada para aprender antes da implantação completa.

Pode materializar:

- tela;
- formulário;
- estrutura documental;
- fluxo;
- interação;
- agente de IA;
- painel;
- ritual;
- pequeno ciclo manual.

### 38.2 Simulação

Execução representada de um cenário para verificar relações, decisões, transferências, exceções e recuperação.

### 38.3 Registro mínimo

| Campo | Protótipo/simulação |
| --- | --- |
| ID | PRT-NNN ou SIM-NNN |
| Pergunta | [Preencher] |
| Hipótese | [Preencher] |
| Objetos | [IDs] |
| Participantes | [Papéis] |
| Cenários | [Normal, exceção, falha, retorno] |
| Limite de exposição | [Preencher] |
| Evidência | [Preencher] |
| Resultado | [Confirmou, contrariou ou inconclusivo] |
| Efeito | [Ajuste, validação, decisão ou nova investigação] |

### 38.4 Limites

Protótipo não é produto final. Simulação não prova desempenho futuro. Ambos reduzem incerteza dentro das condições testadas.

## 39. Registro de seleção de ferramenta

| Campo | Registro |
| --- | --- |
| ID de uso | FER-ARQ-NNN |
| Ferramenta | [Nome] |
| Projeto/frente | [IDs] |
| Pergunta | [Preencher] |
| Requisito/capacidade/risco | [IDs] |
| Decisão apoiada | [ID/descrição] |
| Entradas | [IDs/fontes] |
| Participantes | [Nomes/papéis] |
| Responsável | [Nome] |
| Profundidade | [Reduzida, padrão ou ampliada] |
| Saída | SAI-FER-NNN |
| Validador | [Nome/papel] |
| Integração | [Componente/seção] |
| Sensibilidade | [Classificação] |
| Estado | [Selecionada, preparada, em uso, concluída, validada, cancelada] |

### 39.1 Ferramentas não selecionadas

| Ferramenta | Motivo | Risco da exclusão | Condição para reconsiderar |
| --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Evento/evidência] |

## 40. Plano de aplicação

| Etapa | Atividade | Responsável | Participantes | Entrada | Saída | Duração | Critério |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Preparar | [Preencher] | [Nome] | [Papéis] | [IDs] | [Material] | [Faixa] | [Preencher] |
| Aplicar | [Preencher] | [Nome] | [Papéis] | [Material] | [Rascunho] | [Faixa] | [Preencher] |
| Revisar | [Preencher] | [Nome] | [Papéis] | [Rascunho] | [Versão] | [Faixa] | [Preencher] |
| Integrar | [Preencher] | [Nome] | [Papéis] | [Versão] | [Componente] | [Faixa] | [Preencher] |
| Validar | [Preencher] | [Nome] | [Papéis] | [Componente] | [Resultado] | [Faixa] | [Preencher] |

## 41. Preparação

- [ ] pergunta está formulada;
- [ ] escopo está delimitado;
- [ ] requisitos e capacidades estão disponíveis;
- [ ] fontes e versões foram confirmadas;
- [ ] participantes pertinentes foram convocados;
- [ ] autoridade de decisão é conhecida;
- [ ] sensibilidade e acesso foram tratados;
- [ ] formato é compreensível ao público;
- [ ] nível de detalhe foi definido;
- [ ] saída e destino estão claros;
- [ ] validação foi planejada;
- [ ] tempo e ambiente estão disponíveis.

### 41.1 Insuficiência de entrada

| Entrada ausente | Efeito | Tratamento | Prosseguir? | Responsável |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Complementar, devolver ou assumir com condição] | [Sim, não ou limitado] | [Papel] |

## 42. Participação e facilitação

| Papel | Contribuição esperada | Momento | Autoridade | Proteção |
| --- | --- | --- | --- | --- |
| Responsável pela arquitetura | Formula pergunta e integra saídas | Todo o ciclo | Coordena o desenho | Não substitui especialistas |
| Responsável dimensional | Conduz aplicação e interpretação | Preparação e uso | Recomenda componentes | Não aprova fora da alçada |
| Pessoa afetada | Informa prática, impacto e exceção | Desenho e validação | Contesta inadequação | Não representa todos os públicos |
| Responsável futuro | Avalia manutenção e operação | Desenho e validação | Confirma implantabilidade | Não altera requisito sozinho |
| Especialista | Avalia matéria específica | Quando necessário | Emite parecer/recomendação | Limite da competência explícito |
| Decisor | Define escolhas e riscos | Marcos de decisão | Decide dentro da alçada | Decisão registrada |
| IA | Organiza, compara, simula e redige | Apoio controlado | Nenhuma autoridade | Revisão humana obrigatória |

### 42.1 Oficina

| Campo | Registro |
| --- | --- |
| ID | OFI-ARQ-NNN |
| Objetivo | [Preencher] |
| Pergunta | [Preencher] |
| Participantes | [Nomes/papéis] |
| Preparação | [Materiais] |
| Método | [Preencher] |
| Saída | [ID] |
| Divergências | [IDs] |
| Decisões | [IDs] |
| Próximo movimento | [Preencher] |

## 43. Entradas e evidências

### 43.1 Hierarquia funcional

| Entrada | Pode apoiar | Não deve ser tratada automaticamente como |
| --- | --- | --- |
| Evidência diagnóstica validada | Requisito, capacidade e referência atual | Solução futura |
| Percepção de participante | Caso, risco, necessidade e hipótese | Fato universal |
| Requisito aprovado | Critério obrigatório ou negociável | Componente predeterminado |
| Prática de mercado | Alternativa ou comparação | Melhor prática aplicável |
| Saída de IA | Hipótese, estrutura ou revisão | Evidência ou decisão |
| Protótipo | Evidência limitada | Prova de escala e operação |
| Preferência do decisor | Critério ou restrição legítima quando explicitada | Justificativa suficiente |

### 43.2 Controle de fonte

| Entrada | Fonte | Versão/data | Validação | Limitação | Uso autorizado |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Referência] | [Preencher] | [Estado] | [Preencher] | [Preencher] |

## 44. Nível de detalhe

O detalhe é suficiente quando permite:

- comparar alternativas;
- reconhecer componentes e relações;
- atribuir responsabilidade e autoridade;
- avaliar risco, impacto e manutenção;
- testar cenários relevantes;
- validar requisitos;
- preparar implantação sem ambiguidade material.

### 44.1 Escala de profundidade

| Nível | Uso | Conteúdo |
| --- | --- | --- |
| 0 — referência | Confirmar se a dimensão é material | Síntese e vínculos |
| 1 — reduzido | Arquitetura focal ou baixo risco | Componentes, relações e decisões principais |
| 2 — padrão | Arquitetura funcional | Fluxos, exceções, responsabilidades, critérios e manutenção |
| 3 — ampliado | Alto risco ou arquitetura sistêmica | Cenários, interfaces, falhas, alternativas e validação especializada |

### 44.2 Sinais de detalhe excessivo

- campos sem usuário;
- decomposição que não altera decisão;
- procedimento pertencente à implantação;
- notação incompreensível aos validadores;
- manutenção superior ao valor;
- repetição da mesma informação em vários artefatos;
- adiamento da integração ou da decisão.

## 45. Saídas e identificadores

| Objeto | Prefixo sugerido | Exemplo |
| --- | --- | --- |
| Uso de ferramenta | FER-ARQ | FER-ARQ-012 |
| Saída de ferramenta | SAI-FER | SAI-FER-019 |
| Oficina | OFI-ARQ | OFI-ARQ-004 |
| Protótipo | PRT | PRT-003 |
| Simulação | SIM | SIM-006 |
| Cenário | CEN | CEN-009 |
| Componente | CMP | CMP-021 |
| Interface | INT | INT-014 |
| Validação | VAL | VAL-008 |
| Decisão | DEC | DEC-ARQ-011 |

### 45.1 Ficha da saída

| Campo | Registro |
| --- | --- |
| ID | SAI-FER-NNN |
| Ferramenta de origem | FER-ARQ-NNN |
| Título | [Preencher] |
| Versão | [Número] |
| Pergunta respondida | [Preencher] |
| Requisitos/capacidades | [IDs] |
| Conteúdo | [Referência] |
| Limitações | [Preencher] |
| Divergências | [IDs] |
| Componentes derivados | [IDs] |
| Validação | [ID/estado] |
| Destino | [Arquitetura/decisão/transição] |
| Custodiante | [Nome/papel] |

## 46. Rastreabilidade

Cada aplicação deve permitir reconstruir:

```text
evidência → requisito → capacidade → pergunta → ferramenta
          → saída → componente/interface → validação → decisão
```

### 46.1 Vínculos mínimos

| Origem | Relação | Destino |
| --- | --- | --- |
| REQ-NNN | `justifica` | FER-ARQ-NNN |
| CAP-NNN | `orienta` | FER-ARQ-NNN |
| FER-ARQ-NNN | `produz` | SAI-FER-NNN |
| SAI-FER-NNN | `propõe` | CMP/INT-NNN |
| VAL-NNN | `verifica` | SAI/CMP/INT-NNN |
| DEC-NNN | `aprova`, `rejeita` ou `condiciona` | CMP/INT/ALT-NNN |

### 46.2 Regra

A ficha da ferramenta explica como desenhar. A Matriz de Rastreabilidade permanece como fonte oficial dos vínculos do projeto.

## 47. Integração das saídas

| Pergunta de integração | Verificação |
| --- | --- |
| O processo possui papel responsável? | [Resultado/IDs] |
| O papel possui autoridade e informação? | [Resultado/IDs] |
| A informação possui origem, qualidade e destino? | [Resultado/IDs] |
| O conhecimento possui curador e forma de preservação? | [Resultado/IDs] |
| A comunicação ocorre no momento necessário? | [Resultado/IDs] |
| O documento possui função e manutenção? | [Resultado/IDs] |
| A tecnologia sustenta o fluxo e a continuidade? | [Resultado/IDs] |
| A IA possui função, dados, verificação e interrupção? | [Resultado/IDs] |
| O indicador possui decisão e resposta? | [Resultado/IDs] |
| A alternativa permanece implantável e sustentável? | [Resultado/IDs] |

### 47.1 Conflito entre saídas

| Saída A | Saída B | Conflito | Requisitos afetados | Tratamento | Decisão |
| --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [IDs] | [Revisar, conciliar ou escolher] | DEC-NNN |

## 48. Validação

Toda saída deve ser validada conforme sua natureza.

| Saída | Validação mínima | Validador provável |
| --- | --- | --- |
| Estado atual/futuro | Revisão com fontes e pessoas conhecedoras | Diagnóstico, responsáveis e afetados |
| Processo/fluxo | Walkthrough de casos e exceções | Executores e responsáveis futuros |
| Papéis/alçadas | Simulação de decisão e conflito | Decisores e responsáveis |
| Informação/conhecimento | Teste de localização, qualidade e transferência | Usuários, curadores e especialistas |
| Comunicação | Cenário de passagem e confirmação | Emissores e destinatários |
| Documental | Teste de criação, uso, versão e recuperação | Autores, usuários e custodiante |
| Indicadores | Cálculo, interpretação e resposta | Dono do indicador e decisor |
| Tecnologia/integrações | Revisão técnica, falha e continuidade | Especialista e operação |
| IA | Avaliação de qualidade, risco e supervisão | Especialista, usuário e responsável humano |
| Alternativas | Revisão de critérios, impactos e incerteza | Decisor, afetados e especialistas |

### 48.1 Resultados

- [ ] validada;
- [ ] validada com condições;
- [ ] validada parcialmente;
- [ ] devolvida para ajuste;
- [ ] exige especialista;
- [ ] exige evidência adicional;
- [ ] rejeitada;
- [ ] suspensa.

## 49. Participação da inteligência artificial

### 49.1 Funções permitidas

| Função | Apoio possível |
| --- | --- |
| Pesquisadora | Localizar referências autorizadas e alternativas |
| Analista | Agrupar requisitos, comparar versões e identificar lacunas candidatas |
| Modeladora | Sugerir estruturas, componentes, fluxos e cenários |
| Redatora | Produzir rascunhos a partir de conteúdo aprovado |
| Documental | Organizar IDs, metadados, versões e vínculos |
| Revisora | Verificar consistência, cobertura e contradições candidatas |
| Simuladora | Representar casos e perguntas de estresse |

### 49.2 Responsabilidades humanas

Pessoas devem:

- definir a pergunta;
- interpretar contexto;
- selecionar a ferramenta;
- autorizar dados;
- confirmar fatos;
- atribuir papéis e autoridade;
- avaliar impacto humano;
- decidir critérios;
- validar a saída;
- aceitar risco;
- aprovar componente;
- autorizar implantação.

### 49.3 Registro

| Uso | Função de IA | Entrada | Saída | Revisão | Correção | Aprovador |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Função] | [Fonte/dados] | [Referência] | [Nome/papel] | [Preencher] | [Nome/papel] |

## 50. Dados, confidencialidade e acesso

| Questão | Registro |
| --- | --- |
| Que dados entram na ferramenta? | [Categorias] |
| Existe dado pessoal ou sensível? | [Sim/não/classificação] |
| Quem pode acessar entradas e saídas? | [Públicos] |
| A IA receberá algum conteúdo? | [Descrição/nenhum] |
| A minimização foi aplicada? | [Preencher] |
| Onde a saída será armazenada? | [Fonte oficial] |
| Qual é a retenção? | [Regra] |
| Como ocorrerá descarte ou anonimização? | [Regra] |

### 50.1 Proteções

- utilizar apenas dados necessários;
- separar anexos sensíveis;
- limitar acesso por função;
- não inserir conteúdo em IA sem autorização;
- registrar fonte e versão;
- evitar exposição em oficinas;
- preservar obrigações legais e contratuais;
- permitir correção de registro factual.

## 51. Manutenção e ciclo de vida das saídas

| Saída | Natureza | Fonte oficial | Responsável | Gatilho de atualização | Encerramento |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Temporária, decisória, linha de base ou operacional] | [Referência] | [Papel] | [Evento] | [Regra] |

### 51.1 Saídas temporárias

Rascunhos, notas de oficina, hipóteses e comparações intermediárias podem ser preservados quando explicam decisão ou aprendizado. Não devem competir com a versão oficial.

### 51.2 Saídas que seguem para operação

Quando mapa, matriz ou especificação precisar ser mantido depois da implantação, a transição deve definir:

- responsável;
- frequência;
- fonte;
- acesso;
- evento de atualização;
- relação com o trabalho real;
- condição de substituição ou encerramento.

## 52. Critérios de qualidade

Uma aplicação é de qualidade quando:

- responde à pergunta definida;
- usa entradas adequadas;
- envolve participantes pertinentes;
- diferencia fato, hipótese e escolha;
- representa exceções relevantes;
- produz detalhe suficiente;
- revela relações e compensações;
- evita solução predeterminada;
- pode ser compreendida pelos validadores;
- possui limitações explícitas;
- integra-se às demais dimensões;
- possui rastreabilidade;
- recebe validação proporcional;
- prepara decisão ou implantação.

### 52.1 Teste de utilidade

| Pergunta | Resultado |
| --- | --- |
| Que decisão a saída alterou ou sustentou? | [Preencher] |
| Que relação tornou visível? | [Preencher] |
| Que risco ou incerteza reduziu? | [Preencher] |
| Que componente ajudou a definir? | [IDs] |
| Quem confirmou sua utilidade? | [Nome/papel] |
| Que parte pode ser removida sem perda? | [Preencher] |

## 53. Antipadrões

### 53.1 Arquitetura pela ferramenta

Começar pelo software, agente, diagrama ou matriz desejada.

### 53.2 Ferramenta sem pergunta

Aplicar técnica porque faz parte do repertório, sem incerteza ou decisão associada.

### 53.3 Coleção de mapas

Produzir representações que não convergem para componentes integrados.

### 53.4 Notação como barreira

Utilizar linguagem técnica que impede participação e validação.

### 53.5 Caminho feliz

Representar funcionamento normal e omitir exceção, falha, indisponibilidade e retorno.

### 53.6 Matriz como decisão automática

Tratar pontuação como substituta de julgamento, contexto e condição impeditiva.

### 53.7 RACI ornamental

Preencher letras sem negociar responsabilidade e autoridade reais.

### 53.8 Documento para todo problema

Criar registro para compensar falta de prioridade, competência, ferramenta ou decisão.

### 53.9 IA como autora da arquitetura

Aceitar estrutura plausível sem verificar contexto, evidências, impacto e responsabilidade.

### 53.10 Profundidade sem limite

Detalhar para evitar integração, decisão ou implantação.

## 54. Redundância e conflito

### 54.1 Sinais de redundância

- mesmos campos mantidos em vários artefatos;
- dois mapas com a mesma finalidade;
- oficinas repetidas sem informação nova;
- descrição textual e visual divergente;
- ferramenta cuja saída não é utilizada;
- avaliação duplicada sem decisão distinta.

### 54.2 Registro

| Ferramenta/saída A | Ferramenta/saída B | Sobreposição | Fonte oficial | Tratamento |
| --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [Referência] | [Fundir, vincular, diferenciar ou encerrar] |

### 54.3 Regra de fonte

Cada objeto crítico deve possuir fonte oficial. Outras representações referenciam essa fonte e apresentam apenas o detalhe necessário ao seu uso.

## 55. Lacunas e omissões

| Lacuna | Ferramenta em que apareceu | Objetos afetados | Impacto | Tratamento |
| --- | --- | --- | --- | --- |
| [Preencher] | [FER-ARQ] | [IDs] | [Preencher] | [Complementar, devolver, decidir ou aceitar] |

### 55.1 Destinos

- ao Módulo 2, quando falta compreensão diagnóstica;
- ao Catálogo de Requisitos, quando surge condição nova;
- ao Plano de Arquitetura, quando muda trabalho ou participação;
- à Matriz de Rastreabilidade, quando falta vínculo;
- ao especialista, quando excede competência;
- ao Registro de Decisão, quando exige escolha;
- ao Módulo 4, quando pertence ao detalhamento de implantação;
- ao backlog futuro, quando é relevante e não impede o ciclo atual.

## 56. Condições de pausa e retorno

Pausar a aplicação quando:

- a pergunta mudou materialmente;
- a entrada crítica é contraditória;
- participante indispensável está ausente;
- autoridade necessária não está definida;
- dado não pode ser utilizado legitimamente;
- risco excede a competência;
- ferramenta começou a impor solução;
- profundidade ultrapassou o uso decisório;
- nova evidência exige retorno ao diagnóstico;
- conflito entre requisitos impede continuidade.

### 56.1 Registro

| Motivo | Estado | Objetos | Responsável | Condição de retorno | Prazo |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Pausada, devolvida ou suspensa] | [IDs] | [Papel] | [Preencher] | [Data] |

## 57. Especialistas e competência

| Tema | Sinal de necessidade | Especialidade possível | Decisão enquanto pendente |
| --- | --- | --- | --- |
| Jurídico/regulatório | Obrigação ou risco não interpretável | Jurídico/privacidade | Suspender ou condicionar |
| Segurança | Acesso, integração ou ameaça relevante | Segurança da informação | Revisão obrigatória |
| Dados | Qualidade, modelagem ou migração complexa | Dados/engenharia | Limitar desenho técnico |
| Pessoas | Impacto laboral, acessibilidade ou saúde | RH/ergonomia/especialista | Não aprovar impacto sem revisão |
| Tecnologia | Arquitetura, integração ou continuidade complexa | Arquitetura técnica | Registrar premissa e dependência |
| IA | Avaliação, risco ou governança especializada | IA, dados, jurídico ou domínio | Limitar função e exposição |
| Financeiro | Custo, retorno ou compromisso material | Financeiro | Tratar estimativa como preliminar |

### 57.1 Limite de competência

Ferramenta ajuda a formular perguntas e organizar informação. Ela não cria competência profissional ausente.

## 58. Controle de mudanças

| Mudança | Gatilho | Objetos afetados | Reaplicação necessária | Revalidação | Decisão |
| --- | --- | --- | --- | --- | --- |
| Requisito | [Novo/conflito] | [Ferramentas/saídas] | [Completa/parcial] | [Sim/não] | [ID] |
| Escopo | [Ampliação/redução] | [Frentes] | [Preencher] | [Preencher] | [ID] |
| Alternativa | [Nova configuração] | [Avaliações] | [Preencher] | [Preencher] | [ID] |
| Linha de base | [Mudança material] | [Componentes] | [Preencher] | [Preencher] | [ID] |
| Contexto | [Evidência externa] | [Objetos] | [Preencher] | [Preencher] | [ID] |

### 58.1 Versionamento

Nova aplicação ou versão não apaga a anterior. O histórico deve mostrar pergunta, entradas, participantes, interpretação, mudanças, validação e efeito decisório.

## 59. Indicadores do uso das ferramentas

### 59.1 Justificação da seleção

$$
\text{Seleção justificada} = \frac{\text{ferramentas com pergunta, origem, saída e validação}}{\text{ferramentas selecionadas}} \times 100
$$

### 59.2 Absorção das saídas

$$
\text{Absorção} = \frac{\text{saídas utilizadas em integração, decisão ou validação}}{\text{saídas concluídas}} \times 100
$$

### 59.3 Registro

| Indicador | Resultado | Fonte | Limite | Uso |
| --- | --- | --- | --- | --- |
| Seleção justificada | [%] | Plano/registros | Não mede qualidade da aplicação | Revisão do plano |
| Absorção das saídas | [%] | Rastreabilidade | Uso não significa utilidade | Retrospectiva |
| Ferramentas excluídas | [N] | Plano | Exclusão pode ser sinal de proporcionalidade | Aprendizagem |
| Reaplicações | [N] | Versões | Ciclo pode ser legítimo | Análise de retrabalho |
| Saídas devolvidas | [N] | Validação | Precisa de motivo | Melhoria da aplicação |
| Horas/faixa por ferramenta | [Valor/N/A] | Registros | Comparação exige contexto | Planejamento futuro |

### 59.4 Limite

O objetivo não é maximizar ferramentas, saídas ou cobertura documental. Um conjunto menor que sustenta decisões e implantação pode ser superior a um portfólio completo sem utilidade.

## 60. Aprendizagem e evolução do catálogo

Ao final de cada projeto, a retrospectiva deve registrar:

- ferramentas selecionadas e excluídas;
- perguntas efetivamente respondidas;
- saídas utilizadas;
- técnicas que criaram clareza;
- técnicas que criaram ruído;
- carga de aplicação e manutenção;
- participação necessária;
- integrações difíceis;
- validações decisivas;
- correções de saídas de IA;
- campos redundantes;
- lacunas recorrentes;
- padrões de combinação;
- propostas de melhoria.

### 60.1 Maturidade de uma melhoria

| Nível | Condição |
| --- | --- |
| Ideia | Proposta sem evidência suficiente |
| Observada | Valor ou problema visto em um projeto |
| Repetida | Evidência em mais de um caso comparável |
| Validada | Resultado consistente e limites conhecidos |
| Aprovada | Mudança incorporada por governança |

## 61. Ordem de construção das fichas

As fichas devem ser construídas nesta sequência:

1. `01-estado-atual-e-estado-futuro.md`;
2. `02-arquitetura-de-processos-e-fluxos.md`;
3. `03-papeis-responsabilidades-e-alcadas.md`;
4. `04-arquitetura-de-informacao-e-conhecimento.md`;
5. `05-arquitetura-da-comunicacao.md`;
6. `06-arquitetura-documental.md`;
7. `07-arquitetura-de-indicadores.md`;
8. `08-arquitetura-de-tecnologia-e-integracoes.md`;
9. `09-arquitetura-de-inteligencia-artificial.md`;
10. `10-avaliacao-de-alternativas.md`.

### 61.1 Razão da sequência

A ordem parte da transformação e do trabalho, passa por responsabilidade, informação, coordenação e memória, chega à observação e ao suporte técnico, delimita IA e termina com a comparação integrada das alternativas.

Ela é ordem de construção do acervo, não sequência obrigatória de uso em todo projeto.

## 62. Ordem recomendada de uso

1. consultar problema, decisão, escopo e requisitos;
2. formular perguntas de desenho;
3. classificar dimensões materiais;
4. aplicar o teste de necessidade;
5. selecionar o menor conjunto suficiente;
6. registrar ferramentas excluídas e risco da exclusão;
7. planejar entradas, participantes, saídas e validação;
8. aplicar ferramentas de referência e capacidades;
9. aprofundar dimensões materiais;
10. integrar saídas progressivamente;
11. comparar alternativas completas;
12. prototipar ou simular incertezas críticas;
13. validar com pessoas e especialistas;
14. atualizar rastreabilidade;
15. consolidar componentes aprovados;
16. transferir condições ao Módulo 4;
17. avaliar o uso na retrospectiva.

## 63. Estrutura obrigatória de cada ficha

Cada arquivo deste diretório deve responder, no mínimo:

1. O que é?
2. Que dimensão ajuda a desenhar?
3. Que pergunta arquitetural responde?
4. Quando utilizar?
5. Quando não utilizar?
6. Que entradas exige?
7. Que pessoas participam?
8. Como preparar?
9. Como aplicar?
10. Que decisões apoia?
11. Que saída produz?
12. Como se integra às demais dimensões?
13. Que riscos e antipadrões apresenta?
14. Como a IA pode apoiar?
15. O que deve permanecer humano?
16. Como tratar dados e confidencialidade?
17. Como validar?
18. Como registrar rastreabilidade?
19. Como preparar implantação?
20. Como avaliar proporcionalidade e manutenção?

### 63.1 Seções adicionais recomendadas

- exemplos;
- versão reduzida;
- versão ampliada;
- casos de exceção;
- checklist de preparação;
- checklist de conclusão;
- indicadores de qualidade;
- participação de especialista;
- histórico de versões;
- aprendizados de uso.

## 64. Padrão editorial das fichas

| Elemento | Regra |
| --- | --- |
| Título | Nome funcional da ferramenta |
| Finalidade | Explicar que incerteza reduz ou decisão apoia |
| Linguagem | Compreensível para quem aplica e valida |
| Exemplos | Contextualizados e não tratados como modelo universal |
| Tabelas | Utilizadas para relações e registros exatos |
| Diagramas | Utilizados quando topologia ou sequência melhora compreensão |
| IDs | Compatíveis com o Módulo 3 |
| IA | Apoio e responsabilidade humana separados |
| Saída | Vinculada à Arquitetura Integrada |
| Implantação | Condições transferíveis ao Módulo 4 |
| Manutenção | Responsável, gatilho e encerramento quando aplicável |

### 64.1 Proibições editoriais

- lista de passos sem explicar decisão;
- jargão sem definição;
- notação obrigatória sem razão;
- exemplo apresentado como verdade geral;
- promessa de eliminação de risco;
- uso de IA sem limites;
- campos sem função;
- repetição integral dos fundamentos ou do protocolo.

## 65. Versão reduzida para arquitetura focal

### 65.1 Registro

| Campo | Conteúdo |
| --- | --- |
| Problema/decisão | [Preencher] |
| Requisito/capacidade | [IDs] |
| Pergunta principal | [Preencher] |
| Ferramenta central | [Nome] |
| Integrações mínimas | [Nomes] |
| Saída | [Artefato] |
| Participantes | [Papéis] |
| Validação | [Forma] |
| Risco da simplificação | [Preencher] |
| Condição para aprofundar | [Preencher] |

### 65.2 Checklist

- [ ] uma pergunta central;
- [ ] uma capacidade delimitada;
- [ ] uma representação principal;
- [ ] papéis e autoridade suficientes;
- [ ] exceção material considerada;
- [ ] integração externa visível;
- [ ] alternativa simples examinada;
- [ ] validação proporcional;
- [ ] passagem implantável.

## 66. Estrutura ampliada para arquitetura sistêmica

```text
ferramentas-do-projeto/
|-- README.md
|-- 01-registro-de-selecao.md
|-- 02-perguntas-e-vinculos.md
|-- 03-estado-atual-e-futuro/
|-- 04-processos-e-fluxos/
|-- 05-papeis-e-alcadas/
|-- 06-informacao-e-conhecimento/
|-- 07-comunicacao-e-documentacao/
|-- 08-indicadores-e-controles/
|-- 09-tecnologia-integracoes-e-ia/
|-- 10-alternativas/
|-- 11-prototipos-e-simulacoes/
|-- integracao/
|   |-- interfaces.md
|   |-- conflitos.md
|   +-- lacunas.md
|-- validacao/
|   |-- plano.md
|   +-- resultados.md
+-- anexos-protegidos/
```

### 66.1 Regras

- arquivos oficiais são identificados;
- saídas mantêm vínculos de origem;
- frentes dimensionais possuem responsáveis;
- integração ocorre durante o desenho;
- conflitos não são resolvidos por edição silenciosa;
- conteúdo sensível permanece segregado;
- versões anteriores são preservadas;
- linha de base aponta apenas para saídas aprovadas.

## 67. Checklist de seleção

- [ ] problema e decisão estão claros;
- [ ] escopo e não objetivos estão definidos;
- [ ] requisitos e capacidades estão disponíveis;
- [ ] perguntas de desenho foram formuladas;
- [ ] dimensões materiais foram classificadas;
- [ ] cada ferramenta possui justificativa;
- [ ] ferramentas excluídas foram consideradas;
- [ ] não há redundância conhecida;
- [ ] participantes e responsáveis estão definidos;
- [ ] entradas e acessos estão disponíveis;
- [ ] saídas e destinos estão definidos;
- [ ] profundidade é proporcional;
- [ ] validação está planejada;
- [ ] riscos e especialistas foram considerados;
- [ ] participação da IA possui limites;
- [ ] carga é sustentável.

## 68. Checklist de aplicação

- [ ] fontes e versões foram confirmadas;
- [ ] participantes compreenderam a pergunta;
- [ ] método e formato foram explicados;
- [ ] fatos, hipóteses e preferências foram diferenciados;
- [ ] divergências foram preservadas;
- [ ] exceções e falhas foram consideradas;
- [ ] relações com outras dimensões foram registradas;
- [ ] saída possui identificador e versão;
- [ ] limitações estão explícitas;
- [ ] dados sensíveis foram protegidos;
- [ ] saídas de IA foram revisadas;
- [ ] decisões foram registradas por autoridade;
- [ ] rastreabilidade foi atualizada;
- [ ] próxima integração está definida.

## 69. Checklist de conclusão

- [ ] pergunta foi respondida no grau necessário;
- [ ] requisitos e capacidades permanecem vinculados;
- [ ] saída possui utilidade demonstrável;
- [ ] componentes derivados estão identificados;
- [ ] interfaces foram examinadas;
- [ ] contradições e lacunas foram tratadas;
- [ ] validação proporcional foi concluída;
- [ ] divergências e condições estão registradas;
- [ ] fonte oficial está definida;
- [ ] manutenção ou encerramento foi atribuído;
- [ ] conteúdo foi integrado à Arquitetura Integrada;
- [ ] Matriz de Rastreabilidade foi atualizada;
- [ ] condições de implantação estão visíveis;
- [ ] aprendizado de uso foi preservado.

## 70. Exemplo integrado resumido

### 70.1 Situação

Uma organização precisa criar capacidade compartilhada de acompanhar demandas de clientes sem depender da memória de uma única pessoa.

### 70.2 Perguntas e ferramentas

| Pergunta | Ferramenta | Saída |
| --- | --- | --- |
| O que funciona hoje e precisa ser preservado? | Estado atual e futuro | Capacidades e práticas preservadas |
| Como a demanda entrará e avançará? | Processos e fluxos | Fluxo com estados, decisões e exceções |
| Quem registra, acompanha e decide prioridade? | Papéis e alçadas | Responsabilidades e limites |
| Que informação acompanha cada demanda? | Informação e conhecimento | Objeto demanda e fonte oficial |
| Que avisos e confirmações são necessários? | Comunicação | Eventos e destinatários |
| Que registros precisam permanecer? | Documental | Histórico, decisão e encerramento |
| Como observar demandas sem próxima ação? | Indicadores | Indicador e resposta |
| Que suporte técnico é proporcional? | Tecnologia e integrações | Alternativas manual, planilha e sistema |
| Há função útil para IA? | Inteligência artificial | Classificação sugerida com revisão humana |
| Que configuração escolher? | Avaliação de alternativas | Comparação e recomendação |

### 70.3 Integração

O fluxo define quando a demanda muda de estado. O papel responsável mantém a próxima ação. A informação possui fonte oficial. A comunicação confirma a passagem. O documento preserva decisões. O indicador identifica ausência de movimento. A tecnologia sustenta o conjunto. A IA somente sugere classificação; não define prioridade nem compromisso com o cliente.

### 70.4 Validação

Simular:

- demanda completa;
- dado ausente;
- urgência conflitante;
- responsável indisponível;
- sugestão incorreta da IA;
- falha da ferramenta;
- necessidade de reconstruir histórico.

## 71. Glossário mínimo

| Termo | Definição |
| --- | --- |
| Ferramenta | Meio estruturado de investigar, desenhar, comparar ou testar |
| Técnica transversal | Recurso aplicado dentro de diferentes fichas |
| Pergunta de desenho | Questão que delimita a incerteza arquitetural |
| Saída dimensional | Resultado parcial produzido por ferramenta |
| Componente | Elemento da configuração futura |
| Interface | Relação ou passagem entre componentes |
| Profundidade | Grau de detalhe necessário |
| Validação | Confronto da saída com requisitos, pessoas, casos e condições |
| Fonte oficial | Registro autorizado de um objeto |
| Absorção | Uso de uma saída em integração, decisão ou validação |
| Protótipo | Materialização limitada para aprender |
| Simulação | Execução representada de cenário |

## 72. Governança do diretório

Mudanças nas fichas devem considerar efeitos sobre:

- fundamentos do Módulo 3;
- fluxo do protocolo;
- Plano de Arquitetura;
- Arquitetura Integrada;
- Matriz de Rastreabilidade;
- Registro de Validação;
- passagem ao Módulo 4;
- conhecimento do Módulo 6;
- funções do Ecossistema de IA;
- evolução do Sistema Operacional.

### 72.1 Mudança material

Exige análise e decisão quando altera:

- finalidade da ferramenta;
- pergunta central;
- autoridade ou responsabilidade;
- entrada obrigatória;
- saída oficial;
- integração com outra dimensão;
- proteção de dados;
- função permitida de IA;
- critério de validação;
- condição de implantação.

### 72.2 Histórico

| Versão | Data | Alteração | Evidência | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- |
| 0.1 | 02/08/2026 | Criação do guia e catálogo inicial | Estrutura do Módulo 3 | [Nome] | [Registro] |

## 73. Critérios de conclusão deste guia

- [ ] finalidade do diretório está definida;
- [ ] ferramenta, artefato e componente estão diferenciados;
- [ ] regra de seleção está explícita;
- [ ] catálogo oficial contém os dez arquivos previstos;
- [ ] mapa de capacidades, protótipo e simulação possuem localização metodológica;
- [ ] seleção por pergunta, dimensão, etapa, decisão, saída, risco e escopo está disponível;
- [ ] combinações mínimas e ampliadas estão definidas;
- [ ] cada ferramenta possui perfil inicial;
- [ ] aplicação, rastreabilidade, integração e validação estão governadas;
- [ ] participação humana e uso de IA estão separados;
- [ ] dados, manutenção e mudanças estão tratados;
- [ ] padrões editoriais das fichas estão definidos;
- [ ] checklists permitem uso operacional;
- [ ] ordem de construção está explícita;
- [ ] exemplo integrado demonstra o conjunto.

## 74. Princípio de encerramento

O valor de uma ferramenta não está no desenho que produz isoladamente, mas na compreensão, na decisão e na capacidade de implantação que ajuda a construir.

O Estúdio LICHTARA utiliza ferramentas para tornar relações visíveis, testar possibilidades e preservar responsabilidade. Quando uma ferramenta deixa de apoiar uma pergunta, uma decisão, uma integração ou uma validação, sua aplicação deve ser simplificada, substituída ou encerrada.

O portfólio cumpre sua função quando permite responder:

1. por que cada ferramenta foi escolhida;
2. que pergunta ela respondeu;
3. que saída produziu;
4. como essa saída se integrou à arquitetura;
5. quem a validou;
6. que decisão apoiou;
7. que condição transferiu à implantação;
8. que aprendizado deixou para o próximo projeto.

---

## Registro final

**Diretório:** `modulos/modulo-03-arquitetura-organizacional/ferramentas/`  
**Documento:** `README.md`  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Quantidade de fichas centrais previstas:** 10  
**Técnicas transversais reconhecidas:** mapa de capacidades, protótipo e simulação  
**Fichas construídas:** `01-estado-atual-e-estado-futuro.md`, `02-arquitetura-de-processos-e-fluxos.md`, `03-papeis-responsabilidades-e-alcadas.md`, `04-arquitetura-de-informacao-e-conhecimento.md`, `05-arquitetura-da-comunicacao.md`, `06-arquitetura-documental.md` e `07-arquitetura-de-indicadores.md`  
**Próxima ficha a construir:** `08-arquitetura-de-tecnologia-e-integracoes.md`  
**Observações:** [Preencher]
