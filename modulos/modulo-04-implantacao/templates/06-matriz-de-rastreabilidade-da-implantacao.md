# Matriz de Rastreabilidade da Implantação

**Identificação técnica no repositório**

```yaml
id_matriz: MTR-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Matriz de Rastreabilidade]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_plano_de_implantacao: PLA-IMP-AAAA-NNN
versao_plano_de_implantacao:
id_estrutura_analitica: EAI-IMP-AAAA-NNN
versao_estrutura_analitica:
id_cronograma_mestre: CRM-IMP-AAAA-NNN
versao_cronograma_mestre:
id_sistema_de_fluxo: BLG-IMP-AAAA-NNN
versao_sistema_de_fluxo:
id_projeto_arquitetura: ARQ-AAAA-NNN
id_matriz_arquitetural: MTR-ARQ-AAAA-NNN
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base_arquitetural:
data_de_status: AAAA-MM-DD
responsavel_pela_implantacao:
responsavel_pela_rastreabilidade:
responsavel_pela_arquitetura:
autoridade_da_implantacao:
custodiante_da_matriz:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado_da_matriz: em_configuracao
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 1.0
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Registro dos vínculos que conectam origem arquitetural, realização, evidência, decisão, configuração e continuidade operacional  
**Documento metodológico de referência:** `../03-matriz-de-rastreabilidade-da-implantacao.md`  
**Documentos de entrada:** transição e linha de base do Módulo 3; Termo de Abertura; Plano de Implantação; Estrutura Analítica; Cronograma Mestre; Backlog e Quadro Kanban vigentes  
**Documento seguinte na ordem de construção:** `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md`  
**Pontos de controle relacionados:** `PI-1` a `PI-5`, com início na preparação e atualização durante todo o ciclo

---

## 1. Finalidade

Este template materializa a Matriz de Rastreabilidade da Implantação como fonte preenchível do dossiê real.

Sua finalidade é tornar demonstrável:

- de onde deriva cada obrigação e cada trabalho material;
- que parte da linha de base arquitetural está sendo realizada;
- como capacidades, requisitos, componentes e interfaces chegam a incrementos, entregas, pacotes e itens de fluxo;
- que preparação técnica, humana, informacional, documental e operacional condiciona o avanço;
- que critério antecede cada declaração de atendimento;
- que evidência demonstra ou contradiz o resultado;
- que autoridade decidiu preparação, liberação, aceite, contenção, adaptação, reversão ou retorno;
- que diferença surgiu entre desenho e realidade;
- que versão integra a configuração implantada;
- que condições, riscos e responsabilidades seguem para a operação;
- que aprendizagem possui destino definido.

A matriz registra relações. Ela não substitui os objetos relacionados nem transforma referência em evidência.

---

## 2. Pergunta central

> Como registrar e manter os vínculos materiais da implantação de modo que outra pessoa autorizada consiga reconstruir origem, realização, evidência, decisão, configuração e continuidade sem depender da memória privada de quem executou o trabalho?

A matriz é suficiente quando revela simultaneamente:

1. o caminho regressivo da configuração até sua origem;
2. o caminho progressivo da obrigação até seu destino;
3. as relações horizontais de interface, risco, dependência e responsabilidade;
4. o histórico temporal de versões, estados e substituições;
5. a autoridade que permitiu cada passagem material;
6. a sustentação operacional da capacidade aceita.

---

## 3. Posição no protocolo

Este documento é iniciado na Etapa 10 do Protocolo de Implantação e permanece vigente até a transição e o encerramento.

```text
PI-1 — transição aceita
  → objetos e versões recebidos
  → decomposição da realização
  → matriz inicial do dossiê
  → preparação e PI-2
  → execução, evidências e PI-3
  → validação, diferenças e PI-4
  → estabilização, transferência e PI-5
  → aprendizagem e continuidade
```

O preenchimento da matriz não autoriza execução, liberação, aceite ou transferência. Ele torna visíveis os elementos que uma autoridade humana deverá considerar no gate aplicável.

---

## 4. Distinções que este template preserva

| Elemento | Pergunta principal | Fonte oficial |
| --- | --- | --- |
| Matriz de Rastreabilidade da Arquitetura | Por que a configuração foi desenhada e autorizada? | Módulo 3 |
| Matriz de Rastreabilidade da Implantação — método | Que objetos, relações, coberturas e verificações governam a implantação? | `../03-matriz-de-rastreabilidade-da-implantacao.md` |
| Matriz de Rastreabilidade da Implantação — registro | Que vínculos existem nesta implantação real e em que estado? | Este documento preenchido no dossiê |
| Estrutura Analítica | O que compõe a realização? | `03-estrutura-analitica-da-implantacao.md` |
| Cronograma Mestre | Quando e sob quais restrições temporais? | `04-cronograma-mestre-da-implantacao.md` |
| Backlog e Kanban | Que trabalho está apto, comprometido e em fluxo? | `05-backlog-e-quadro-kanban-da-implantacao.md` |
| Registro integrado | Que riscos, impedimentos, dependências e mudanças exigem tratamento? | `07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |
| Evidência | O que foi observado, em qual contexto e com que limite? | Fonte especializada da evidência |
| Gate | Que decisão humana foi tomada sobre objeto e versão delimitados? | Registro da ocorrência de gate |
| Configuração implantada | O que foi efetivamente instalado, aceito e estabilizado? | `15-registro-da-configuracao-implantada.md` |

### 4.1 Objeto não é vínculo

O requisito, a entrega, a evidência e a decisão são objetos. `Atende`, `demonstra` e `autoriza` são vínculos entre objetos.

### 4.2 Vínculo não é demonstração

Registrar que uma entrega `atende` a um requisito somente é válido quando o critério e a evidência exigidos pelo estágio podem ser localizados.

### 4.3 Cobertura não é menção

Dois IDs presentes no mesmo documento não se tornam relacionados por proximidade textual.

### 4.4 Visão não é fonte concorrente

Visões de gate, requisito, configuração ou auditoria são recortes da matriz canônica. Alterar uma exportação não altera a fonte oficial.

---

## 5. Natureza do documento

Este arquivo é:

- template duplicável;
- instrumento vivo de planejamento, execução e continuidade;
- fonte canônica dos vínculos vigentes da implantação quando preenchido no dossiê;
- índice de resolução para fontes especializadas;
- base de visões, verificações e análises de impacto;
- registro histórico de estados e versões materiais.

Este arquivo não é:

- inventário geral de documentos;
- cópia do catálogo de requisitos;
- segunda Estrutura Analítica;
- quadro de tarefas;
- repositório de evidências brutas;
- registro integral de decisão;
- relatório narrativo de progresso;
- substituto para gate;
- declaração autônoma de conformidade;
- autorização para redesenhar a arquitetura.

---

## 6. Autoridade e limites

| Ato | Pode ser apoiado pela matriz? | Autoridade necessária |
| --- | --- | --- |
| Registrar vínculo proposto | Sim | Responsável pela rastreabilidade |
| Confirmar relação factual ou documental | Sim | Pessoa competente pela fonte e pelo objeto |
| Classificar cobertura | Sim, como preparação | Responsabilidade humana competente |
| Aceitar risco ou condição | Não pela matriz | Autoridade definida no registro especializado |
| Autorizar execução ou liberação | Não pela matriz | Autoridade do gate aplicável |
| Declarar mudança não material | Não automaticamente | Autoridade e teste de materialidade aplicáveis |
| Alterar linha de base arquitetural | Não | Retorno e decisão do Módulo 3 |
| Aceitar configuração | Não pela matriz | Autoridade de `PI-4` |
| Transferir responsabilidade operacional | Não pela matriz | Aceite bilateral de `PI-5` |

### 6.1 Limite de interpretação

A matriz pode apontar que todos os campos previstos estão preenchidos. Isso não prova que a relação é semanticamente correta, que a evidência é suficiente ou que o risco é aceitável.

### 6.2 Limite de atualização

O custodiante mantém integridade, sincronização e histórico. Não se torna autor ou decisor universal dos objetos referenciados.

---

## 7. Instruções de uso

1. Duplique este template no dossiê da implantação.
2. Preencha a identificação técnica e declare a fonte oficial.
3. Registre as versões recebidas no `PI-1` antes de criar vínculos de realização.
4. Importe IDs do Módulo 3 sem renumerá-los.
5. Cadastre por referência somente os objetos materiais à implantação.
6. Registre uma relação por linha na matriz principal.
7. Utilize o vocabulário controlado antes de propor nova relação.
8. Informe versões de origem e destino quando a formulação ou configuração puder mudar.
9. Registre critério, evidência e decisão somente como referências localizáveis.
10. Classifique cobertura separadamente por dimensão e estágio.
11. Atualize a matriz quando eventos materiais ocorrerem.
12. Preserve fotografia ou versão considerada em cada gate.
13. Abra lacuna quando um caminho necessário não puder ser confirmado.
14. Mantenha diferenças, evidências negativas e discordâncias visíveis.
15. Execute testes de reconstrução antes de `PI-3`, `PI-4` e `PI-5`.
16. Encerre vínculos sem apagar seu histórico.

### 7.1 Convenções de preenchimento

| Convenção | Uso |
| --- | --- |
| `[Preencher]` | Campo obrigatório ainda não preenchido. |
| `N.A.` | Não aplicável, com fundamento registrado. |
| `Nenhum` | Verificação realizada e ausência confirmada. |
| `Pendente` | Tratamento esperado, com responsável e limite. |
| `Desconhecido` | Informação ainda não determinada e registrada como lacuna. |
| `ID/link` | Referência recuperável à fonte oficial. |

Não use campo vazio para representar `N.A.`, `Nenhum`, `Pendente` ou `Desconhecido`.

### 7.2 Uma linha por relação

Se uma entrega atende três requisitos, registre três vínculos. Se três evidências demonstram uma capacidade, registre três vínculos. Uma célula com lista indistinta impede estado, critério e validade específicos.

---

## 8. Identificação da matriz

| Campo | Registro |
| --- | --- |
| ID da matriz | `MTR-IMP-AAAA-NNN` |
| ID da implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área ou contexto | [Preencher] |
| Linha de base arquitetural | [ID e versão] |
| Matriz arquitetural de origem | [ID e versão] |
| Termo de Abertura | [ID e versão] |
| Plano de Implantação | [ID e versão] |
| Estrutura Analítica | [ID e versão] |
| Cronograma Mestre | [ID e versão] |
| Sistema de fluxo | [ID e versão] |
| Responsável pela implantação | [Nome/papel] |
| Responsável pela rastreabilidade | [Nome/papel] |
| Autoridade da implantação | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Classificação | [Focal/funcional/sistêmica] |
| Sensibilidade | [Pública/interna/confidencial/sensível] |
| Fonte oficial | [Caminho/link] |
| Versão | [N.N] |
| Data de status | [Data] |

---

## 9. Estado da matriz

| Estado | Significado | Próximo movimento típico |
| --- | --- | --- |
| Em configuração | Identidade, fontes e regras estão sendo estabelecidas. | Completar entrada e governança. |
| Em preenchimento inicial | Objetos e vínculos da linha de base estão sendo registrados. | Verificar cobertura de planejamento. |
| Ativa | Matriz acompanha preparação ou execução. | Sincronizar por evento e cadência. |
| Em revisão de gate | Fotografia e lacunas estão sendo examinadas. | Recomendar, corrigir ou submeter. |
| Condicionada | Uso continua sob condições explícitas. | Tratar condições e reavaliar. |
| Bloqueada | Lacuna impede uso responsável para decisão material. | Corrigir fonte, vínculo ou versão. |
| Em consolidação | Configuração, transição e histórico estão sendo fechados. | Testar reconstrução e destinar lacunas. |
| Transferida | Vínculos de continuidade foram recebidos pela operação. | Manter referência e monitoramento. |
| Encerrada | Ciclo da matriz foi concluído com destino dos vínculos. | Preservar e revisar por evento. |
| Substituída | Outra fonte oficial assumiu a função. | Manter referência à sucessora. |

### 9.1 Registro do estado atual

| Campo | Registro |
| --- | --- |
| Estado | [Selecionar] |
| Data de início | [Data/hora] |
| Horizonte coberto | [Planejamento/incremento/onda/configuração/transição] |
| Objeto e versão mais recentes examinados | [IDs/versões] |
| Gate em preparação | [`PI-1`/`PI-2`/`PI-3`/`PI-4`/`PI-5`/nenhum] |
| Lacunas impeditivas | [IDs/nenhuma] |
| Condições | [IDs/nenhuma] |
| Próxima sincronização | [Data/evento] |
| Responsável | [Nome/papel] |

---

## 10. Fonte oficial e localização no dossiê

Local sugerido:

```text
registros-de-implantacao/
└── AAAA/
    └── IMP-AAAA-NNN-nome-curto/
        └── planejamento/
            └── matriz-de-rastreabilidade.md
```

| Campo | Registro |
| --- | --- |
| Fonte oficial dos vínculos | [Caminho, sistema ou banco] |
| Formato canônico | [Markdown/planilha/banco/ferramenta/outro] |
| Fonte das versões históricas | [Caminho/sistema] |
| Regra de atualização | [Evento/cadência] |
| Regra de versionamento | [Preencher] |
| Regra de exportação | [Preencher] |
| Política de acesso | [ID/link] |
| Retenção | [Regra] |
| Portabilidade | [Formato/procedimento] |
| Responsável pela continuidade | [Nome/papel] |

### 10.1 Fonte única

Uma implantação pode utilizar planilha, banco, documento e ferramenta visual. Somente uma fonte governa os vínculos vigentes. As demais são interfaces ou exportações declaradas.

### 10.2 Exportações

Toda exportação deve indicar:

- ID e versão da matriz;
- data e hora de extração;
- filtros;
- versões consideradas;
- finalidade;
- limitações;
- caráter dinâmico ou congelado.

---

## 11. Documentos de entrada e precedência

| Fonte | ID e versão | Estado | Função na matriz | Autoridade sobre o conteúdo | Última sincronização |
| --- | --- | --- | --- | --- | --- |
| Transição para implantação | [ID/versão] | [Estado] | Entrega do Módulo 3. | Módulo 3 | [Data/responsável] |
| Linha de base arquitetural | [ID/versão] | [Estado] | Referência autorizada. | Módulo 3 | [Data/responsável] |
| Matriz arquitetural | [ID/versão] | [Estado] | Caminho anterior à implantação. | Módulo 3 | [Data/responsável] |
| Termo de Abertura | [ID/versão] | [Estado] | Escopo, envelope e autoridades. | Autoridade da implantação | [Data/responsável] |
| Plano de Implantação | [ID/versão] | [Estado] | Estratégia e integração. | Responsável e autoridade | [Data/responsável] |
| Estrutura Analítica | [ID/versão] | [Estado] | Decomposição da realização. | Responsável pela decomposição | [Data/responsável] |
| Cronograma Mestre | [ID/versão] | [Estado] | Compromissos temporais. | Responsável pelo cronograma | [Data/responsável] |
| Backlog e Kanban | [ID/versão] | [Estado] | Trabalho e fluxo real. | Responsável pelo fluxo | [Data/responsável] |
| Registros especializados | [IDs/versões] | [Estado] | Evidências, riscos, decisões e configuração. | Responsabilidades próprias | [Data/responsável] |

### 11.1 Regra de precedência

Em divergência:

1. a fonte oficial do objeto governa seu conteúdo;
2. a matriz governa o vínculo e a cobertura declarados nesta implantação;
3. a decisão de gate governa a passagem delimitada;
4. a linha de base vigente governa a arquitetura autorizada;
5. mudança material retorna ao Módulo 3.

### 11.2 Divergência entre matriz e fonte

A divergência não deve ser corrigida por escolha silenciosa. Registre o conflito, o efeito, o responsável pela resolução e a autoridade competente.

---

## 12. Governança da rastreabilidade

| Elemento | Regra vigente | Responsável | Autoridade | Evidência da regra | Revisão |
| --- | --- | --- | --- | --- | --- |
| Inclusão de objetos | [Critério de materialidade] | [Papel] | [Papel] | [ID/link] | [Cadência] |
| Criação de vínculos | [Regra] | [Papel] | [Papel] | [ID/link] | [Cadência] |
| Confirmação semântica | [Regra] | [Papel] | [Papel] | [ID/link] | [Cadência] |
| Classificação de cobertura | [Regra] | [Papel] | [Papel] | [ID/link] | [Cadência] |
| Proposição de relação nova | [Regra] | [Papel] | [Papel] | [ID/link] | [Evento] |
| Atualização por mudança | [Regra] | [Papel] | [Papel] | [ID/link] | [Evento] |
| Fotografia de gate | [Regra] | [Papel] | [Papel] | [ID/link] | [Gate] |
| Controle de acesso | [Regra] | [Papel] | [Papel] | [ID/link] | [Cadência] |
| Arquivamento | [Regra] | [Papel] | [Papel] | [ID/link] | [Encerramento] |

---

## 13. Unidade de registro

O vínculo rastreável é a unidade mínima da matriz.

```text
origem e versão
  → relação controlada
  → destino e versão
  → estado, cobertura, fundamento e responsável
```

| Unidade | Função | Registro neste template |
| --- | --- | --- |
| Objeto | Elemento que participa do percurso. | Catálogo mínimo ou referência. |
| Vínculo | Relação material entre dois objetos. | Matriz principal. |
| Caminho | Sequência de vínculos para uma pergunta. | Visão derivada ou teste. |
| Cadeia | Conjunto de caminhos de uma capacidade, gate ou configuração. | Verificação consolidada. |
| Cobertura | Suficiência rastreável para dimensão e estágio. | Registro de cobertura. |
| Lacuna | Ausência, ambiguidade ou insuficiência. | Registro de lacunas. |
| Evento | Ocorrência que altera validade, versão ou estado. | Histórico de eventos. |
| Fotografia | Recorte congelado para decisão. | Registro de gate. |

---

## 14. Identificadores, namespace e não reutilização

### 14.1 Identificadores próprios

| Objeto | Padrão |
| --- | --- |
| Matriz | `MTR-IMP-AAAA-NNN` |
| Vínculo material | `IMP-AAAA-NNN-VNC-NNN` |
| Lacuna de rastreabilidade | `IMP-AAAA-NNN-LAC-NNN` |
| Ocorrência de gate | `IMP-AAAA-NNN-GAT-NNN` |

### 14.2 Identificadores importados

Objetos dos Módulos 2 e 3 preservam seus IDs canônicos. Formas abreviadas podem ser exibidas no dossiê, mas a chave resolvível permanece qualificada.

### 14.3 Registro de namespaces

| Namespace | Módulo/fonte | Padrão | Exemplo | Regra de resolução | Colisão conhecida |
| --- | --- | --- | --- | --- | --- |
| [Nome] | [Fonte] | [Padrão] | [ID] | [Caminho/regra] | [ID/nenhuma] |

### 14.4 Regras

- não renumerar objeto importado;
- não reutilizar ID encerrado, cancelado ou substituído;
- não criar novo objeto quando a fonte especializada já possui ID estável;
- qualificar colisões por módulo, projeto ou caminho;
- registrar sucessão sem apagar o identificador anterior;
- manter o ID do vínculo quando apenas seu estado mudar;
- criar novo vínculo quando origem, relação ou destino mudarem materialmente.

---

## 15. Catálogo mínimo de objetos

| ID canônico | Tipo | Título curto | Módulo de origem | Projeto/implantação | Fonte oficial | Versão | Estado | Responsável | Autoridade | Sensibilidade | Última sincronização |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo] | [Título] | [Módulo] | [ID] | [Link] | [Versão] | [Estado] | [Nome/papel] | [Nome/papel] | [Classe] | [Data] |

### 15.1 Registro por referência

O catálogo não duplica descrições integrais. Deve conter dados suficientes para resolver o objeto e reconhecer a versão utilizada.

### 15.2 Critério de inclusão

Inclua objeto quando ele:

- possuir critério próprio;
- mudar de estado independentemente;
- participar de gate;
- gerar ou exigir evidência específica;
- alterar risco, autoridade ou configuração;
- depender de decisão material;
- puder ser aceito parcialmente;
- puder exigir correção, reversão ou retorno;
- for transferido à operação;
- precisar ser localizado em análise de impacto.

---

## 16. Classes de objetos rastreáveis

| Classe | Tipos presentes | Fonte principal | Aplicabilidade | Responsável por confirmar |
| --- | --- | --- | --- | --- |
| Origem diagnóstica | [Achados/problemas/capacidades/riscos/outros] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Arquitetura autorizada | [Requisitos/capacidades/componentes/interfaces/decisões] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Governança da implantação | [Termo/plano/gates/condições] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Realização | [Projeto/onda/incremento/entrega/pacote/item] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Preparação | [Humana/técnica/documental/operacional] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Evidência e validação | [Critério/teste/evidência/validação] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Decisão e mudança | [Decisão/mudança/correção/adaptação/reversão] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Configuração | [Versão/manifesto/diferença/estabilização] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |
| Operação e aprendizagem | [Responsável/indicador/suporte/lição/destino] | [ID/link] | [Aplicável/N.A.] | [Nome/papel] |

---

## 17. Objetos herdados da origem diagnóstica

| ID | Tipo | Síntese necessária | Caminho arquitetural existente | Uso na implantação | Versão/fonte | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Fonte/evidência/achado/problema/capacidade/risco/restrição/dependência/lacuna] | [Síntese] | [ID da matriz/caminho] | [Justifica/preserva/delimita/outro] | [Versão/link] | [Estado] |

### 17.1 Regra de seletividade

Quando a Matriz de Rastreabilidade da Arquitetura já oferece caminho suficiente, referencie o caminho consolidado. Não copie toda a cadeia diagnóstica para produzir volume.

---

## 18. Objetos herdados da arquitetura

| ID e versão | Tipo | Obrigatoriedade | Função na implantação | Linha de base | Fonte | Condição recebida | Tratamento inicial |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [Requisito/capacidade/critério/componente/interface/controle/outro] | [Obrigatório/condicionado/opcional] | [Realizar/preservar/proteger/monitorar] | [ID/versão] | [Link] | [Condição/nenhuma] | [ID/síntese] |

### 18.1 Manifesto da linha de base recebida

| Artefato | ID e versão | Incluído na linha de base? | Estado no `PI-1` | Condições | Fonte | Verificado por |
| --- | --- | --- | --- | --- | --- | --- |
| Matriz arquitetural | [ID/versão] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |
| Catálogo de requisitos | [ID/versão] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |
| Arquitetura integrada | [ID/versão] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |
| Registro de validação | [ID/versão] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |
| Transição para implantação | [ID/versão] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |
| Outros artefatos materiais | [IDs/versões] | [Sim/não] | [Estado] | [IDs/nenhuma] | [Link] | [Nome/data] |

---

## 19. Objetos próprios da implantação

| ID | Tipo | Pertence a | Origem arquitetural | Critério ou função | Fonte oficial | Versão | Estado | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Implantação/projeto/onda/incremento/entrega/pacote/item/evidência/diferença/configuração/PDCA/outro] | [ID] | [ID] | [Síntese] | [Link] | [Versão] | [Estado] | [Nome/papel] |

### 19.1 Padrões canônicos frequentes

| Objeto | Padrão |
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

---

## 20. Objetos destinados à operação e à aprendizagem

| Objeto de destino | Tipo | Fonte ou referência temporária | Configuração relacionada | Responsável | Limite/condição | Aceite | ID posterior |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Procedimento/indicador/controle/suporte/risco residual/aprendizagem/outro] | [Link] | [ID/versão] | [Nome/papel] | [ID/síntese] | [ID/pendente] | [ID/N.A.] |

Enquanto o módulo de destino não possuir ID canônico, utilize referência localizável e tipo completo. Quando o ID posterior existir, acrescente o vínculo sem apagar a referência usada na transição.

---

## 21. Registro de vínculo

Cada vínculo material deve possuir:

| Campo | Preenchimento |
| --- | --- |
| ID do vínculo | `IMP-AAAA-NNN-VNC-NNN` ou chave composta autorizada |
| Origem | [ID canônico] |
| Tipo da origem | [Tipo] |
| Versão da origem | [Versão/data/N.A.] |
| Relação | [Vocabulário controlado] |
| Destino | [ID canônico] |
| Tipo do destino | [Tipo] |
| Versão do destino | [Versão/data/N.A.] |
| Dimensão de cobertura | [Origem/realização/evidência/decisão/configuração/continuidade/N.A.] |
| Estado de cobertura | [Estado] |
| Estado do vínculo | [Estado] |
| Fundamento | [Síntese ou ID] |
| Critério | [ID/versão/N.A. neste estágio] |
| Evidência | [ID/versão/N.A. neste estágio] |
| Decisão | [ID/versão/pendente/N.A.] |
| Responsável | [Nome/papel] |
| Gate afetado | [Ocorrência/PI/N.A.] |
| Vigência | [Início/fim/condição] |
| Fonte | [ID/link] |
| Sensibilidade | [Classe] |
| Observação | [Limite, divergência ou contexto] |

### 21.1 Quando identificar o vínculo

Utilize ID próprio quando a relação:

- mudar de estado;
- possuir condição própria;
- participar de decisão;
- for contestada;
- exigir histórico;
- for usada em análise de impacto;
- precisar ser citada em gate ou transição.

Em implantação focal, a combinação origem–relação–destino pode ser suficiente quando permanece inequívoca e historicamente recuperável.

---

## 22. Matriz principal — fonte canônica dos vínculos

| Vínculo | Origem | Versão origem | Tipo origem | Relação | Destino | Versão destino | Tipo destino | Dimensão | Cobertura | Estado | Critério | Evidência | Decisão | Responsável | Gate | Vigência | Fonte | Observação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-VNC-NNN` | [ID] | [Versão] | [Tipo] | [Relação] | [ID] | [Versão] | [Tipo] | [Dimensão/N.A.] | [Estado] | [Estado] | [ID/N.A.] | [ID/N.A.] | [ID/N.A.] | [Nome/papel] | [ID/N.A.] | [Período] | [ID/link] | [Preencher] |

### 22.1 Regras da matriz principal

- uma linha representa uma relação;
- origem, relação e destino não podem ficar ambíguos;
- listas podem aparecer em visões, não na relação canônica;
- versões devem ser declaradas quando alteram significado;
- `N.A.` precisa corresponder ao estágio, não à conveniência;
- evidência negativa permanece vinculada;
- vínculo proposto não conta como cobertura confirmada;
- decisão posterior não reescreve a fotografia anterior;
- encerramento mantém o vínculo recuperável.

---

## 23. Modelo mínimo e modelo reduzido

### 23.1 Modelo mínimo operacional

| Vínculo | Origem e versão | Relação | Destino e versão | Dimensão | Cobertura | Estado | Fundamento/evidência | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [Relação] | [ID/versão] | [Dimensão] | [Estado] | [Estado] | [ID/síntese] | [Nome/papel] |

### 23.2 Modelo focal reduzido

| Origem | Relação | Destino | Cobertura | Evidência ou decisão | Responsável |
| --- | --- | --- | --- | --- | --- |
| [ID/versão] | [Relação] | [ID/versão] | [Dimensão/estado] | [ID/N.A.] | [Nome/papel] |

O modelo reduzido não pode remover:

- linha de base e versão;
- origem do trabalho;
- requisito ou capacidade aplicável;
- critério e evidência material;
- autoridade de decisão;
- diferença material;
- condição de gate;
- risco residual;
- responsabilidade operacional.

---

## 24. Vocabulário controlado — origem e continuidade

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `deriva_de` | O objeto foi formulado a partir de outro. | Objeto derivado | Objeto anterior | [Aplicável/N.A.] |
| `é_justificado_por` | O destino fornece razão material para a origem. | Trabalho/decisão | Origem | [Aplicável/N.A.] |
| `preserva` | Mantém capacidade, regra, proteção ou valor existente. | Controle/realização | Objeto protegido | [Aplicável/N.A.] |
| `formaliza` | Transforma condição em registro explícito. | Documento/decisão | Condição | [Aplicável/N.A.] |
| `herda` | Recebe condição, risco, requisito ou decisão anterior. | Objeto do Módulo 4 | Objeto anterior | [Aplicável/N.A.] |
| `continua_em` | Prossegue em outro módulo, fase ou configuração. | Objeto atual | Objeto posterior | [Aplicável/N.A.] |

---

## 25. Vocabulário controlado — realização e decomposição

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `é_realizada_por` | Capacidade ou configuração recebe realização. | Capacidade/configuração | Incremento/entrega | [Aplicável/N.A.] |
| `realiza` | Objeto de implantação torna capacidade possível. | Incremento/entrega | Capacidade | [Aplicável/N.A.] |
| `decompõe_em` | Objeto agregado origina unidades menores. | Implantação/onda/entrega | Unidade menor | [Aplicável/N.A.] |
| `pertence_a` | Objeto integra agregado identificado. | Unidade | Incremento/onda/projeto | [Aplicável/N.A.] |
| `produz` | Trabalho gera entrega, evidência ou configuração. | Pacote/item/atividade | Resultado | [Aplicável/N.A.] |
| `incorpora` | Configuração reúne objeto produzido e aceito. | Configuração | Entrega/componente | [Aplicável/N.A.] |
| `substitui` | Nova versão ou objeto assume função anterior. | Objeto novo | Objeto anterior | [Aplicável/N.A.] |

---

## 26. Vocabulário controlado — atendimento e proteção

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `atende` | Produz cobertura completa conforme critério vigente. | Realização/configuração | Requisito/critério | [Aplicável/N.A.] |
| `atende_parcialmente` | Produz cobertura incompleta ou condicionada. | Realização/configuração | Requisito/critério | [Aplicável/N.A.] |
| `não_atende` | Foi avaliado e não produz cobertura suficiente. | Realização/configuração | Requisito/critério | [Aplicável/N.A.] |
| `trata` | Atua sobre risco, problema, impedimento, lacuna ou condição. | Resposta/trabalho | Exposição | [Aplicável/N.A.] |
| `controla` | Previne, detecta, corrige ou compensa exposição. | Controle | Risco/falha | [Aplicável/N.A.] |
| `protege` | Preserva pessoa, dado, continuidade, autoria ou limite. | Controle/regra | Objeto protegido | [Aplicável/N.A.] |
| `restringe` | Limita escopo, uso, público, dado, tempo ou efeito. | Condição/regra | Objeto limitado | [Aplicável/N.A.] |

---

## 27. Vocabulário controlado — dependência e estrutura

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `depende_de` | Necessita de outro objeto ou condição. | Unidade dependente | Objeto necessário | [Aplicável/N.A.] |
| `precede` | Precisa ocorrer antes no caminho avaliado. | Objeto anterior | Objeto posterior | [Aplicável/N.A.] |
| `é_condicionado_por` | Somente avança se condição for atendida ou aceita. | Objeto condicionado | Condição | [Aplicável/N.A.] |
| `interfaceia_com` | Mantém passagem material com outro objeto. | Componente/unidade | Componente/unidade | [Aplicável/N.A.] |
| `transfere_para` | Move trabalho, informação, dado ou responsabilidade. | Origem da transferência | Destino | [Aplicável/N.A.] |
| `conflita_com` | Possui incompatibilidade ou tensão material. | Objeto | Objeto | [Aplicável/N.A.] |
| `é_limitado_por` | Opera dentro de limite explícito. | Objeto limitado | Limite/guardrail | [Aplicável/N.A.] |

---

## 28. Vocabulário controlado — evidência e validação

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `é_verificado_por` | Recebe comparação com especificação. | Objeto/critério | Evidência/teste | [Aplicável/N.A.] |
| `é_validado_por` | Recebe julgamento de adequação ao uso. | Capacidade/configuração | Evidência/validação | [Aplicável/N.A.] |
| `é_demonstrado_por` | Recebe demonstração por evidência identificada. | Objeto/afirmação | Evidência | [Aplicável/N.A.] |
| `demonstra` | Evidência sustenta resultado delimitado. | Evidência | Objeto/afirmação | [Aplicável/N.A.] |
| `contradiz` | Evidência questiona afirmação ou expectativa. | Evidência/resultado | Afirmação/critério | [Aplicável/N.A.] |
| `qualifica` | Acrescenta contexto, limite ou condição. | Evidência/decisão | Objeto/afirmação | [Aplicável/N.A.] |
| `mede` | Indicador representa manifestação definida. | Indicador | Capacidade/resultado | [Aplicável/N.A.] |

---

## 29. Vocabulário controlado — decisão, gate e mudança

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `é_autorizado_por` | Objeto ou movimento recebe autoridade formal. | Objeto/movimento | Decisão | [Aplicável/N.A.] |
| `autoriza` | Decisão permite ação, estado ou versão. | Decisão | Objeto/movimento | [Aplicável/N.A.] |
| `é_liberado_por` | Versão recebe decisão de exposição ou uso. | Incremento/configuração | Gate/decisão | [Aplicável/N.A.] |
| `é_aceito_por` | Resultado recebe aceite formal. | Resultado/configuração | Gate/decisão | [Aplicável/N.A.] |
| `é_rejeitado_por` | Objeto ou resultado não recebe aprovação. | Objeto/resultado | Decisão | [Aplicável/N.A.] |
| `é_contido_por` | Escopo ou efeito é limitado por decisão. | Exposição/objeto | Decisão/controle | [Aplicável/N.A.] |
| `é_revertido_por` | Configuração retorna por decisão ou evento. | Configuração | Decisão/evento | [Aplicável/N.A.] |
| `retorna_a` | Necessidade ou mudança é encaminhada ao módulo competente. | Mudança/lacuna | Módulo/registro | [Aplicável/N.A.] |

---

## 30. Vocabulário controlado — diferença, configuração, operação e aprendizagem

### 30.1 Diferença e configuração

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `difere_de` | Configuração real apresenta distância da referência. | Configuração/diferença | Linha de base/componente | [Aplicável/N.A.] |
| `corrige` | Restaura atendimento sem mudar intenção material. | Ação/versão | Falha/diferença | [Aplicável/N.A.] |
| `adapta` | Altera execução dentro de tolerância autorizada. | Ação/configuração | Referência | [Aplicável/N.A.] |
| `altera_materialmente` | Afeta arquitetura ou proteção material. | Mudança/diferença | Objeto arquitetural | [Aplicável/N.A.] |
| `configura` | Participa da forma instalada. | Entrega/componente | Configuração | [Aplicável/N.A.] |
| `estabiliza` | Demonstra funcionamento sob exposição suficiente. | Ação/período | Configuração/capacidade | [Aplicável/N.A.] |
| `transfere_responsabilidade_para` | Autoridade operacional aceita sustentação delimitada. | Configuração/objeto | Responsável operacional | [Aplicável/N.A.] |

### 30.2 Operação e aprendizagem

| Relação | Significado | Origem típica | Destino típico | Uso nesta matriz |
| --- | --- | --- | --- | --- |
| `é_monitorado_por` | Funcionamento será acompanhado. | Configuração/capacidade | Indicador/rotina | [Aplicável/N.A.] |
| `aciona` | Sinal, limite ou evento provoca resposta definida. | Indicador/evento | Resposta/decisão | [Aplicável/N.A.] |
| `é_sustentado_por` | Depende de papel, competência, documento, tecnologia ou rotina. | Capacidade/configuração | Objeto de sustentação | [Aplicável/N.A.] |
| `gera_aprendizagem_para` | Experiência produz conhecimento destinado. | Evento/evidência | Módulo/método | [Aplicável/N.A.] |
| `exige_revisão_de` | Evidência ou mudança demanda reavaliação. | Evidência/mudança | Objeto/decisão | [Aplicável/N.A.] |
| `encerra` | Decisão conclui vigência ou ciclo. | Decisão/evento | Objeto/vínculo | [Aplicável/N.A.] |

---

## 31. Validação semântica dos vínculos

Antes de confirmar um vínculo, verifique:

| Verificação | Pergunta | Resultado | Evidência/fonte | Responsável |
| --- | --- | --- | --- | --- |
| Existência | Origem e destino existem em fontes oficiais? | [Sim/não/parcial] | [ID/link] | [Nome] |
| Identidade | IDs resolvem para objetos inequívocos? | [Sim/não/parcial] | [ID/link] | [Nome] |
| Versão | As versões relacionadas são conhecidas? | [Sim/não/N.A.] | [ID/link] | [Nome] |
| Direção | A leitura origem–relação–destino está correta? | [Sim/não] | [Regra] | [Nome] |
| Compatibilidade | Os tipos de objeto admitem a relação? | [Sim/não/condicionado] | [Regra] | [Nome] |
| Materialidade | A relação afeta decisão, risco, configuração ou continuidade? | [Sim/não] | [Síntese] | [Nome] |
| Fundamento | A relação possui razão recuperável? | [Sim/não] | [ID/link] | [Nome] |
| Critério | Há critério quando a relação declara atendimento? | [Sim/não/N.A.] | [ID] | [Nome] |
| Evidência | O estágio exige e possui evidência? | [Sim/não/N.A.] | [ID] | [Nome] |
| Autoridade | A decisão aplicável foi emitida por quem possui alçada? | [Sim/não/N.A.] | [ID] | [Nome] |
| Contradição | Existe evidência ou vínculo incompatível não tratado? | [Sim/não] | [IDs/nenhum] | [Nome] |
| Atualidade | O vínculo continua válido para a data de status? | [Sim/não/condicionado] | [Fonte] | [Nome] |

### 31.1 Resultado da validação

- [ ] Proposto
- [ ] Confirmado
- [ ] Condicionado
- [ ] Contestada
- [ ] Bloqueada
- [ ] Invalidada
- [ ] Substituída
- [ ] Encerrada

| Campo | Registro |
| --- | --- |
| Vínculo examinado | [ID] |
| Resultado | [Selecionar] |
| Limites | [Preencher/nenhum] |
| Tratamento | [ID/ação/N.A.] |
| Próxima revisão | [Data/evento] |
| Responsável | [Nome/papel] |
| Autoridade, quando aplicável | [Nome/papel/N.A.] |

---

## 32. Direção, cardinalidade e inferência

### 32.1 Direção

| Vínculo | Leitura canônica | Leitura inversa permitida em visão? | Regra |
| --- | --- | --- | --- |
| [ID] | `[origem] [relação] [destino]` | [Sim/não] | [Preencher] |

A visão pode apresentar relação inversa para leitura humana. Não crie vínculo duplicado apenas para inverter a frase.

### 32.2 Cardinalidade

| Relação | Cardinalidade esperada | Caso real | Exceção | Verificação |
| --- | --- | --- | --- | --- |
| [Relação] | [1:1/1:N/N:1/N:N] | [IDs] | [ID/nenhuma] | [Resultado] |

### 32.3 Relações simétricas

`conflita_com` e outras relações declaradamente simétricas são registradas uma vez. A simetria pertence à definição, não a uma segunda linha artificial.

### 32.4 Relação inferida

| Vínculo sugerido | Regra ou sistema | Confiança técnica | Fonte examinada | Revisão humana | Estado final |
| --- | --- | --- | --- | --- | --- |
| [Origem–relação–destino] | [Regra/IA] | [Faixa/N.A.] | [IDs] | [Nome/data/resultado] | [Proposto/confirmado/rejeitado] |

Inferência permanece proposta até verificação humana e resolução à fonte.

---

## 33. Estados dos objetos

O estado principal pertence à fonte oficial do objeto. A matriz o referencia para avaliar atualidade e efeito sobre o vínculo.

| Objeto | Versão | Estado oficial | Fonte | Data do estado | Efeito nos vínculos | Sincronizado? |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Planejado/em preparação/em execução/produzido/liberado/em validação/aceito/aceito com condições/estabilizado/transferido/suspenso/revertido/substituído/cancelado/encerrado] | [Link] | [Data] | [IDs/síntese] | [Sim/não] |

### 33.1 Estado não é herdado automaticamente

- entrega aceita não torna capacidade aceita;
- incremento liberado não torna implantação aceita;
- configuração estabilizada em um público não se torna estabilizada em todos;
- item concluído não torna requisito atendido;
- documento publicado não demonstra uso;
- treinamento realizado não demonstra competência.

---

## 34. Estados dos vínculos

| Estado | Significado | Conta como cobertura confirmada? | Tratamento |
| --- | --- | --- | --- |
| Proposto | Relação identificada, ainda não confirmada. | Não | Verificar. |
| Confirmado | Relação examinada e válida para o estágio. | Conforme cobertura | Manter atualizada. |
| Condicionado | Depende de condição explícita. | Somente no limite aceito | Acompanhar condição. |
| Contestada | Existe divergência material. | Não como conclusão plena | Resolver ou decidir. |
| Parcial | Produz cobertura incompleta. | Parcial | Delimitar fronteira. |
| Bloqueada | Relação necessária não pode avançar. | Não | Tratar lacuna. |
| Invalidada | Evidência ou mudança retirou validade. | Não | Reavaliar impactos. |
| Substituída | Outro vínculo passou a cumprir a função. | Pelo sucessor | Preservar histórico. |
| Encerrada | Deixou de vigorar sem substituição necessária. | Não vigente | Preservar razão. |

### 34.1 Mudança de estado

| Evento | Vínculo | Estado anterior | Novo estado | Data | Fundamento/evidência | Autoridade | Efeito sobre cobertura/gate | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/data] | [ID] | [Estado] | [Estado] | [Data/hora] | [ID/link] | [Nome/papel/N.A.] | [Preencher] | [Preencher] |

---

## 35. Dimensões de cobertura

Cobertura deve ser avaliada por pergunta e estágio. Não utilize um único percentual para condensar as seis dimensões.

| Dimensão | Pergunta | Objeto/horizonte | Estado | Limite | Evidência | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Origem | Por que isto existe? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |
| Realização | Como a obrigação será ou foi realizada? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |
| Evidência | Como o resultado foi demonstrado? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |
| Decisão | Que autoridade permitiu o movimento? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |
| Configuração | Em que versão o resultado integra a realidade? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |
| Continuidade | Como será sustentado, monitorado ou encerrado? | [IDs] | [Estado] | [Síntese] | [ID/link] | [Nome] |

### 35.1 Denominador explícito

Quando houver contagem, declare:

- universo de objetos aplicáveis;
- exclusões e fundamento;
- estágio avaliado;
- versão da matriz;
- data de status;
- tratamento de estados parciais ou condicionados.

---

## 36. Estados de cobertura

| Estado | Significado | Pode sustentar gate? |
| --- | --- | --- |
| Não avaliada | Cobertura ainda não examinada. | Não. |
| Planejada | Caminho previsto, ainda sem realização. | Somente gates de planejamento, se suficiente. |
| Em realização | Trabalho iniciado e incompleto. | Conforme objeto e gate. |
| Demonstrada | Evidência suficiente para o critério avaliado. | Sim, dentro do limite. |
| Completa | Vínculos exigidos pelo estágio estão válidos. | Sim, se não houver contradição impeditiva. |
| Parcial | Parte material atendida e fronteira explícita. | Somente com decisão compatível. |
| Condicionada | Depende de condição aceita, com responsável e consequência. | Sim, quando o gate admite condição. |
| Contestada | Divergência material não resolvida. | Não como conclusão plena. |
| Bloqueada | Lacuna impede avanço responsável. | Não. |
| Não coberta | Não existe tratamento suficiente. | Não. |
| Não aplicável | Exclusão possui fundamento, autoridade e escopo. | Sim, se legítima. |
| Substituída | Outra realização passou a produzir cobertura. | Pelo sucessor. |
| Invalidada | Evidência, versão ou mudança retirou validade. | Não. |

### 36.1 Cobertura por objeto e dimensão

| Objeto | Versão | Origem | Realização | Evidência | Decisão | Configuração | Continuidade | Limite comum | Próxima revisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Estado] | [Estado] | [Estado] | [Estado] | [Estado] | [Estado] | [Síntese/nenhum] | [Data/evento] |

---

## 37. Cadeias mínimas aplicáveis

### 37.1 Origem e realização

```text
origem legítima
  → requisito
  → capacidade
  → componente ou interface
  → linha de base
  → incremento ou entrega
  → configuração implantada
```

| Cadeia | Objeto inicial | Caminho | Objeto final | Estado | Lacuna |
| --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [ID] | [IDs de vínculos] | [ID] | [Completa/parcial/bloqueada] | [ID/nenhuma] |

### 37.2 Trabalho

```text
capacidade ou condição
  → incremento
  → entrega
  → pacote de trabalho
  → item de backlog
  → resultado produzido
```

### 37.3 Evidência e aceite

```text
objeto e versão
  → critério
  → método
  → evidência
  → validação
  → recomendação
  → decisão
```

### 37.4 Risco e proteção

```text
risco ou falha possível
  → objeto exposto
  → controle ou resposta
  → responsável
  → evidência de funcionamento
  → risco residual
  → decisão
```

### 37.5 Diferença

```text
linha de base
  → configuração observada
  → diferença
  → classificação
  → impacto
  → decisão
  → correção, adaptação, retorno, aceite ou reversão
```

### 37.6 Competência

```text
atividade ou decisão
  → competência necessária
  → preparação
  → prática assistida
  → demonstração
  → autonomia ou suporte
  → responsabilidade operacional
```

### 37.7 Transição

```text
configuração estabilizada
  → documento vigente
  → responsável operacional
  → suporte e manutenção
  → indicador e limite
  → condição residual
  → aceite operacional
```

### 37.8 Aprendizagem

```text
evento ou evidência
  → interpretação
  → decisão ou lição
  → destino metodológico
  → responsável por avaliar incorporação
```

### 37.9 Verificação consolidada

| Cadeia | Aplicável? | Objeto/horizonte | Completa? | Vínculos faltantes | Efeito | Tratamento | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Origem e realização | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Trabalho | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Evidência e aceite | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Risco e proteção | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Diferença | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Competência | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Transição | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |
| Aprendizagem | [Sim/N.A.] | [IDs] | [Sim/parcial/não] | [IDs/síntese] | [Gate/risco] | [ID/ação] | [Nome] |

---

## 38. Visão de origem e linha de base

| Objeto recebido | ID e versão | Pertence à linha de base? | Obrigatoriedade | Condição | Fonte | Tratamento na implantação | Estado de origem |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Objeto] | [ID/versão] | [Sim/não] | [Obrigatório/condicionado/opcional] | [ID/síntese] | [Link] | [ID/síntese] | [Estado] |

### 38.1 Perguntas de verificação

- a transição resolve para a linha de base autorizada?
- todas as versões integrantes estão identificadas?
- requisitos, capacidades, componentes e interfaces materiais estão localizáveis?
- riscos, controles, condições e pendências do Módulo 3 foram recebidos?
- o envelope de autonomia está explícito?
- lacunas do `PI-1` possuem tratamento?

---

## 39. Visão de requisitos e capacidades

| Requisito | Versão | Capacidade | Componente/interface | Incremento/entrega | Critério | Cobertura | Evidência | Diferença | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [ID] | [ID] | [ID] | [ID] | [Estado] | [ID/N.A.] | [ID/nenhuma] | [ID/pendente] |

### 39.1 Requisito sem realização

| Requisito | Causa | Classificação | Efeito | Decisão necessária | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Fora da onda/lacuna/exclusão/dependência/inviabilidade/outro] | [Estado] | [Gate/benefício/risco] | [ID/pergunta] | [Nome] | [Data/condição] |

### 39.2 Capacidade existente a preservar

| Capacidade | Exposição da transição | Proteção | Evidência | Responsável | Critério de retorno |
| --- | --- | --- | --- | --- | --- |
| [ID] | [Síntese] | [ID] | [ID] | [Nome/papel] | [Condição] |

---

## 40. Visão de realização e fluxo

| Unidade | Tipo | Pertence a | Origem arquitetural | Produz | Dependência | Critério de conclusão | Estado factual | Responsável | Próximo movimento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Projeto/onda/incremento/entrega/pacote/item] | [ID] | [ID] | [ID] | [ID/nenhuma] | [ID/síntese] | [Estado] | [Nome] | [Preencher] |

### 40.1 Trabalho sem origem

| Trabalho | Possível classificação | Origem confirmada? | Decisão | Destino | Pode continuar? | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Administrativo legítimo/correção/retrabalho/descoberta/expansão/preferência/outro] | [ID/não] | [ID/pendente] | [EAI/backlog/registro/Módulo 3/outro] | [Sim/não/condicionado] | [Nome] |

### 40.2 Objeto arquitetural sem trabalho

| Objeto | Motivo | Horizonte | Efeito | Tratamento | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Outra onda/adiado/lacuna/exclusão/inviabilidade/outro] | [Período/onda] | [Preencher] | [ID/ação] | [Nome/papel] | [Estado] |

---

## 41. Visão de prontidão e gates

| Ocorrência | Gate | Objeto e versão | Critérios | Evidências | Lacunas | Riscos/condições | Recomendação | Decisão | Autoridade | Consequência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| `IMP-AAAA-NNN-GAT-NNN` | [`PI-1` a `PI-5`] | [IDs/versões] | [IDs] | [IDs] | [IDs/nenhuma] | [IDs/nenhuma] | [Avançar/condicionar/devolver/suspender/rejeitar] | [ID/pendente] | [Nome/papel] | [Preencher] |

### 41.1 Ocorrência repetível

`PI-3`, `PI-4` e, quando necessário, outros gates podem ocorrer por incremento, onda, público, ambiente ou versão. Cada ocorrência deve declarar objeto, escopo e versão; o código genérico do gate não é identificador suficiente.

### 41.2 Gate reaberto

| Ocorrência original | Evento de reabertura | Objeto afetado | Evidência invalidada | Nova ocorrência | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/data] | [ID/versão] | [IDs/nenhuma] | [ID] | [Nome/papel] | [Estado] |

---

## 42. Visão de evidência, validação e aceite

| Objeto e versão | Critério | Método | Evidência | Contexto/escopo | Resultado | Limite | Validação | Decisão/aceite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [ID/versão] | [ID/síntese] | [ID/versão] | [Ambiente/público/período] | [Atende/parcial/não atende] | [Síntese] | [ID/resultado] | [ID/pendente] |

### 42.1 Evidência negativa ou divergente

| Evidência | Afirmação afetada | Contradição | Severidade | Efeito sobre vínculo | Efeito sobre gate | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Síntese] | [Baixa/média/alta/crítica] | [Confirmar/condicionar/invalidar] | [Preencher] | [ID/ação] |

### 42.2 Evidência múltipla

Múltiplas evidências relacionadas ao mesmo objeto permanecem vínculos separados. A visão pode reuni-las para julgamento humano, sem apagar contexto, autoria, data, versão e limite.

---

## 43. Visão de decisão e mudança

| Decisão/mudança | Objeto afetado | Versão anterior | Evidência/fundamento | Autoridade | Resultado | Nova versão | Revalidação | Efeito nos vínculos |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Versão] | [IDs] | [Nome/papel] | [Corrigir/adaptar/retornar/conter/reverter/aceitar/outro] | [Versão/N.A.] | [IDs/N.A.] | [IDs/síntese] |

### 43.1 Decisão pendente

| Pergunta | Objetos | Autoridade | Insumos faltantes | Limite | Efeito da espera | Escalonamento |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Nome/papel] | [IDs/síntese] | [Data/condição] | [Preencher] | [Papel/fórum] |

### 43.2 Mudança material

Quando a mudança afetar requisito material, princípio, componente estrutural, interface crítica, autoridade, risco não autorizado, uso material de dados, tecnologia ou IA, validade da linha de base ou tolerância concedida, registre retorno ao Módulo 3.

---

## 44. Visão de configuração e diferenças

| Configuração | Versão | Referência arquitetural | Entregas incorporadas | Diferenças | Decisões | Evidências | Estado | Manifesto/fonte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [LB/objetos] | [IDs] | [IDs/nenhuma declarada] | [IDs] | [IDs] | [Produzida/liberada/aceita/estabilizada/transferida] | [ID/link] |

### 44.1 Registro de diferença

| Campo | Registro |
| --- | --- |
| ID da diferença | `IMP-AAAA-NNN-DIF-NNN` |
| Linha de base e versão | [ID/versão] |
| Objeto de referência | [ID/versão] |
| Configuração observada | [ID/versão] |
| Descrição factual | [Preencher] |
| Classificação inicial | [Correção/adaptação/mudança material/incerteza] |
| Impacto | [IDs/síntese] |
| Evidências | [IDs] |
| Autoridade | [Nome/papel] |
| Decisão | [ID/pendente] |
| Destino | [Corrigir/aceitar/retornar/reverter/outro] |
| Revalidação | [IDs/N.A.] |
| Estado | [Aberta/em análise/decidida/incorporada/revertida/encerrada] |

### 44.2 Ausência de diferença declarada

| Objeto comparado | Linha de base | Configuração | Método de comparação | Data | Responsável | Resultado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Versão] | [ID/síntese] | [Data] | [Nome] | [Nenhuma diferença material/diferenças IDs] |

---

## 45. Visão de transição, operação e aprendizagem

| Configuração/objeto | Responsável operacional | Sustentação | Documento vigente | Indicador | Limite e resposta | Condição residual | Aceite `PI-5` | Aprendizagem/destino |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [Nome/papel] | [ID] | [ID/link] | [ID] | [ID/síntese] | [ID/nenhuma] | [ID/pendente] | [ID/destino] |

### 45.1 Responsabilidade transferida

| Objeto | Responsabilidade anterior | Responsabilidade posterior | Escopo | Data | Aceite bilateral | Limites | Critério de retorno |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome/papel] | [Nome/papel] | [Preencher] | [Data] | [ID] | [IDs/síntese] | [Condição] |

### 45.2 Aprendizagem

| Evento/evidência | Lição | Validade local | Destino | Responsável por avaliar | Decisão de incorporação | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Contexto/limite] | [Módulo 3/4/6/7/8/outro] | [Nome/papel] | [ID/pendente/N.A.] | [Estado] |

---

## 46. Visão de análise de impacto

| Mudança proposta | Objeto inicial | Vínculos percorridos | Objetos afetados | Gates | Evidências a rever | Configuração | Operação | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [ID/versão] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs/papéis] | [Baixo/médio/alto/crítico/inconclusivo] |

### 46.1 Profundidade

- local: um objeto e seus vínculos diretos;
- de cadeia: origem até configuração ou operação;
- sistêmica: múltiplas capacidades, interfaces, gates ou módulos;
- regulada ou sensível: inclui proteção, dados, IA, direitos, contratos e continuidade.

### 46.2 Resultado inconclusivo

Quando fontes, versões ou relações não permitirem análise suficiente, registre `inconclusivo` e abra lacuna. Não reduza o impacto por ausência de informação.

---

## 47. Visão de auditoria e integridade

| Verificação | Universo | Resultado | Itens afetados | Severidade | Tratamento | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- |
| IDs inválidos ou não resolvidos | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Objetos órfãos | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Trabalho sem origem | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Obrigações sem destino | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Vínculos sem versão | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Cobertura sem critério | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Evidência sem fonte | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Condição sem responsável | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Diferença sem decisão | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Gate sem fotografia | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Fonte indisponível | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |
| Vínculo desatualizado | [N/escopo] | [N] | [IDs] | [Nível] | [ID/ação] | [Nome] | [Data] |

---

## 48. Lacunas de rastreabilidade

| Campo | Registro |
| --- | --- |
| ID | `IMP-AAAA-NNN-LAC-NNN` |
| Objeto ou vínculo afetado | [ID] |
| Dimensão | [Origem/realização/evidência/decisão/configuração/continuidade] |
| Tipo | [Ausência/ambiguidade/invalidade/insuficiência/conflito/indisponibilidade] |
| Descrição factual | [Preencher] |
| Fonte esperada | [ID/link] |
| Efeito | [Gate/risco/configuração/continuidade] |
| Severidade | [Baixa/média/alta/crítica] |
| Tratamento | [ID/ação] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel/N.A.] |
| Limite | [Data/condição] |
| Estado | [Aberta/em tratamento/condicionada/resolvida/aceita/encerrada] |
| Evidência de resolução | [ID/link/N.A.] |

### 48.1 Lacuna aceita

Aceitar uma lacuna exige:

- escopo explícito;
- fundamento;
- risco conhecido;
- autoridade competente;
- condição, prazo ou gatilho;
- consequência;
- efeito sobre gate;
- destino após a implantação.

---

## 49. Objetos órfãos

| Objeto | Tipo | Relação esperada | Motivo aparente | Materialidade | Efeito | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Tipo] | [Relação/tipo de destino] | [Síntese] | [Baixa/média/alta/crítica] | [Preencher] | [ID/ação] | [Estado] |

### 49.1 Órfão temporário legítimo

Pode ocorrer durante elaboração progressiva, desde que possua responsável, limite e destino previsto.

### 49.2 Órfão material persistente

Objeto material isolado antes de gate deve ser vinculado, excluído por decisão ou registrado como lacuna impeditiva ou condicionante.

---

## 50. Conflitos, divergências e contestação

| ID | Objetos/vínculos | Natureza | Posições preservadas | Evidências | Autoridade de resolução | Efeito | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Semântica/fonte/versão/cobertura/decisão/outro] | [Referências/síntese] | [IDs] | [Nome/papel] | [Gate/configuração/outro] | [Aberta/em análise/decidida/encerrada] |

### 50.1 Preservação da discordância

Discordância competente não é falha de preenchimento. Mantenha posições, fontes, limites e autoridade até decisão. A decisão encerra a pergunta prática; não apaga a existência histórica da divergência.

---

## 51. Exceção e não aplicabilidade

| Objeto/regra | Exceção ou N.A. | Escopo | Fundamento | Autoridade | Risco | Compensação | Vigência | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/regra] | [Tipo] | [Objeto/horizonte] | [ID/síntese] | [Nome/papel] | [ID/síntese] | [ID/ação/N.A.] | [Período] | [Data/evento] |

### 51.1 Não aplicabilidade defensiva

`N.A.` não pode ocultar falta de planejamento, ausência de evidência, restrição de acesso ou incapacidade de realizar. Deve declarar fundamento, escopo e autoridade.

---

## 52. Contrato da evidência na matriz

| Campo da evidência | Registro mínimo |
| --- | --- |
| ID | [ID canônico] |
| Objeto demonstrado | [ID/versão] |
| Critério | [ID/versão] |
| Método | [ID/síntese] |
| Fonte | [Link/sistema] |
| Data/período | [Preencher] |
| Contexto | [Ambiente/público/condição] |
| Responsável pela produção | [Nome/papel] |
| Responsável pela verificação | [Nome/papel] |
| Resultado | [Síntese estruturada] |
| Limite | [Preencher/nenhum] |
| Sensibilidade | [Classe] |
| Estado | [Coletada/verificada/validada/contestada/invalidada/substituída] |

### 52.1 Classes de evidência

| Classe | Exemplo de função | Limite típico |
| --- | --- | --- |
| Atividade | Demonstra que ação ocorreu. | Não demonstra resultado. |
| Entrega | Demonstra que artefato existe e atende critério local. | Não demonstra uso. |
| Capacidade | Demonstra que resultado pode ser produzido no contexto. | Pode não demonstrar estabilidade. |
| Competência | Demonstra atuação humana em situação delimitada. | Treinamento concluído não basta. |
| Adoção | Demonstra uso real por público definido. | Uso pontual não demonstra continuidade. |
| Controle | Demonstra prevenção, detecção ou resposta. | Existência documental não prova funcionamento. |
| Estabilidade | Demonstra comportamento sob tempo e exposição suficientes. | Janela precisa ser explicitada. |

### 52.2 Link não é evidência

O link localiza a fonte. A afirmação precisa declarar o que a evidência demonstra, em qual versão, contexto e limite.

---

## 53. Linha de base, configuração e versionamento

### 53.1 Referências vigentes

| Tipo | ID | Versão | Estado | Data de vigência | Decisão | Fonte | Substitui |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Linha de base arquitetural | [ID] | [Versão] | [Vigente/substituída] | [Data] | [ID] | [Link] | [ID/versão/N.A.] |
| Configuração candidata | [ID] | [Versão] | [Estado] | [Data] | [ID/N.A.] | [Link] | [ID/versão/N.A.] |
| Configuração aceita | [ID] | [Versão] | [Estado] | [Data] | [ID] | [Link] | [ID/versão/N.A.] |
| Configuração transferida | [ID] | [Versão] | [Estado] | [Data] | [ID] | [Link] | [ID/versão/N.A.] |

### 53.2 Versão no vínculo

Quando origem ou destino mudarem de formulação material, reavalie o vínculo. Alterar a versão na célula sem evento, impacto e verificação é proibido.

### 53.3 Substituição

| Objeto/vínculo anterior | Sucessor | Motivo | Decisão | Data | Evidências reavaliadas | Gates afetados | Estado histórico |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/versão] | [ID/versão] | [ID/síntese] | [ID] | [Data] | [IDs] | [IDs/nenhum] | [Preservado] |

---

## 54. Eventos de atualização

Eventos que exigem revisão incluem:

- nova versão de objeto;
- inclusão, exclusão ou reclassificação de trabalho;
- produção ou invalidação de evidência;
- decisão de gate;
- abertura ou resolução de lacuna;
- risco, impedimento, dependência ou mudança material;
- diferença entre desenho e realidade;
- correção, adaptação, reversão ou substituição;
- mudança de responsável ou autoridade;
- liberação, aceite, estabilização ou transferência;
- alteração de fonte, acesso ou retenção.

| Evento | Data/hora | Fonte | Objetos | Vínculos afetados | Ação na matriz | Responsável | Verificação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [Data/hora] | [ID/link] | [IDs] | [IDs] | [Criar/atualizar/invalidar/substituir/encerrar] | [Nome] | [Nome/data] |

---

## 55. Fotografias e histórico de gate

| Fotografia | Ocorrência de gate | Matriz e versão | Data de status | Filtros/escopo | Objetos e versões | Lacunas | Resultado | Fonte preservada |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID/versão] | [Data/hora] | [Preencher] | [IDs/versões] | [IDs/nenhuma] | [ID/resultado] | [Link] |

### 55.1 Reprodutibilidade

A fotografia deve permitir reconstruir o conjunto considerado pela autoridade. Se a fonte for dinâmica, preserve exportação, commit, versão ou consulta equivalente.

### 55.2 Não reescrever o passado

Corrigir a matriz vigente não altera a fotografia de uma decisão anterior. Se o erro afetar a decisão, registre reabertura, revisão ou nova ocorrência.

---

## 56. Sincronização geral

| Fonte | Evento de sincronização | Conteúdo recebido | Conteúdo devolvido | Responsável | Última execução | Divergências |
| --- | --- | --- | --- | --- | --- | --- |
| Termo de Abertura | [Aprovação/revisão] | Escopo, envelope, autoridade. | Lacunas e impactos. | [Nome] | [Data] | [IDs/nenhuma] |
| Plano de Implantação | [Revisão] | Estratégia, gates, condições. | Cobertura e dependências. | [Nome] | [Data] | [IDs/nenhuma] |
| Estrutura Analítica | [Inclusão/revisão] | Capacidades, entregas, pacotes. | Órfãos e lacunas. | [Nome] | [Data] | [IDs/nenhuma] |
| Cronograma Mestre | [Replanejamento] | Marcos, janelas, versões temporais. | Impactos e objetos críticos. | [Nome] | [Data] | [IDs/nenhuma] |
| Backlog e Kanban | [Movimento material] | Itens, estados, bloqueios, resultados. | Origem e destino de evidências. | [Nome] | [Data] | [IDs/nenhuma] |
| Registro integrado | [Evento] | Riscos, impedimentos, dependências, mudanças. | Objetos e vínculos afetados. | [Nome] | [Data] | [IDs/nenhuma] |
| Planos humanos | [Revisão/evidência] | Comunicação, competência, adoção. | Cobertura e lacunas. | [Nome] | [Data] | [IDs/nenhuma] |
| Configuração implantada | [Nova versão] | Manifesto, diferenças, estado. | Origem, evidência e decisões. | [Nome] | [Data] | [IDs/nenhuma] |
| Transição para operação | [Preparação/aceite] | Responsabilidades e condições. | Cadeias de continuidade. | [Nome] | [Data] | [IDs/nenhuma] |

---

## 57. Sincronização com a Estrutura Analítica

| Objeto da EAI | Versão | Vínculos esperados | Vínculos confirmados | Lacunas | Última sincronização | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Capacidade/componente/entrega/pacote] | [Versão] | [Relações] | [IDs] | [IDs/nenhuma] | [Data] | [Nome] |

### 57.1 Regra

A EAI governa decomposição. A matriz governa relações e cobertura. Corrija cada divergência na fonte competente; não altere uma para fazer a outra parecer coerente.

---

## 58. Sincronização com o Cronograma Mestre

| Objeto temporal | Objeto rastreado | Relação | Versão temporal | Evento | Efeito | Atualização necessária |
| --- | --- | --- | --- | --- | --- | --- |
| [Marco/janela/dependência/gate previsto] | [ID] | [Precede/depende/condiciona/outro] | [Versão] | [ID/data] | [Gate/cobertura] | [Sim/não/ação] |

Datas previstas não autorizam passagem. A matriz registra o vínculo com o evento ou condição; o gate registra a decisão.

---

## 59. Sincronização com o Backlog e o Quadro Kanban

| Item de fluxo | Origem rastreada | Resultado produzido | Evidência | Estado factual | Vínculos a atualizar | Data |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [ID/N.A.] | [Estado] | [IDs/ação] | [Data] |

### 59.1 Eventos materiais do fluxo

Movimentação ordinária não exige nova linha de rastreabilidade. Atualize quando o item:

- produzir objeto ou evidência material;
- revelar diferença;
- alterar dependência, risco ou condição;
- gerar correção, retrabalho ou mudança;
- invalidar vínculo;
- mudar destino de entrega ou configuração;
- afetar gate ou transição.

---

## 60. Sincronização com registros e planos especializados

| Registro/plano | ID e versão | Objeto material | Relações usadas | Estado | Efeito sobre cobertura | Próxima sincronização |
| --- | --- | --- | --- | --- | --- | --- |
| Riscos, impedimentos, dependências e mudanças | [ID/versão] | [IDs] | [Trata/controla/depende/retorna/outro] | [Estado] | [Preencher] | [Evento/data] |
| Comunicação e engajamento | [ID/versão] | [Públicos/objetos] | [Preencher] | [Estado] | [Preencher] | [Evento/data] |
| Treinamento e capacitação | [ID/versão] | [Competências] | [Preencher] | [Estado] | [Preencher] | [Evento/data] |
| Gestão da mudança | [ID/versão] | [Impactos/adoção] | [Preencher] | [Estado] | [Preencher] | [Evento/data] |
| Piloto, ondas, virada e reversão | [ID/versão] | [Incrementos/configurações] | [Preencher] | [Estado] | [Preencher] | [Evento/data] |
| Ciclo PDCA | [ID/versão] | [Hipótese/resultado] | [Gera aprendizagem/corrige/adapta] | [Estado] | [Preencher] | [Evento/data] |
| Prontidão | [ID/versão] | [Objeto/gate] | [É condicionado/é demonstrado] | [Estado] | [Preencher] | [Evento/data] |
| Validação e aceite | [ID/versão] | [Objeto/versão] | [É validado/é aceito] | [Estado] | [Preencher] | [Evento/data] |
| Configuração implantada | [ID/versão] | [Configuração] | [Incorpora/configura/difere] | [Estado] | [Preencher] | [Evento/data] |
| Transição para operação | [ID/versão] | [Objetos transferidos] | [Transfere/é sustentado] | [Estado] | [Preencher] | [Evento/data] |

---

## 61. Cobertura no `PI-1` — aceite da transição

Pergunta oficial:

> A linha de base arquitetural, suas condições e seus critérios são suficientes para mobilizar a implantação?

| Verificação | Objeto/versão | Estado | Evidência/fonte | Lacuna/condição | Responsável |
| --- | --- | --- | --- | --- | --- |
| Transição recebida e identificada | [ID/versão] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Linha de base exata | [ID/versão] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Matriz arquitetural resolvível | [ID/versão] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Requisitos e capacidades aplicáveis | [IDs/versões] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Componentes e interfaces críticos | [IDs/versões] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Critérios, riscos e controles | [IDs/versões] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Pendências e condições | [IDs] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |
| Envelope de autonomia | [ID/versão] | [Estado] | [Link] | [ID/nenhuma] | [Nome] |

| Campo | Registro |
| --- | --- |
| Ocorrência | `IMP-AAAA-NNN-GAT-NNN` |
| Fotografia | [ID/link] |
| Resultado | [Aceita/aceita com condições/devolvida] |
| Decisão | [ID] |
| Autoridade | [Nome/papel] |
| Condições | [IDs/nenhuma] |
| Efeito na matriz | [Ativar/corrigir/bloquear/outro] |

---

## 62. Cobertura no `PI-2` — prontidão para executar

Pergunta oficial:

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

| Dimensão | Objetos examinados | Cobertura | Evidência | Lacunas/condições | Efeito |
| --- | --- | --- | --- | --- | --- |
| Escopo e realização | [EAI/entregas/pacotes] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Recursos e capacidade | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Responsabilidades e autoridade | [IDs/papéis] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Dependências e tempo | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Riscos, controles e reversão | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Preparação humana | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Preparação técnica e operacional | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |
| Evidências e critérios previstos | [IDs] | [Estado] | [IDs] | [IDs/nenhuma] | [Preencher] |

### 62.1 Objeto autorizado

| Ocorrência | Objeto/versão | Escopo/horizonte | Exclusões | Condições | Decisão | Autoridade | Próximo movimento permitido |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [Onda/incremento/ambiente/público] | [IDs/nenhuma] | [IDs/nenhuma] | [ID] | [Nome/papel] | [Executar objeto delimitado/reparar/devolver/outro] |

---

## 63. Cobertura no `PI-3` — prontidão para liberar

Pergunta oficial:

> Este incremento, piloto, onda ou virada possui condições técnicas, humanas, documentais e operacionais para ser liberado?

| Ocorrência | Objeto/versão | Ambiente/público | Critérios | Evidências | Riscos e condições | Reversão | Cobertura | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/versão] | [Preencher] | [IDs] | [IDs] | [IDs/nenhuma] | [ID/condição] | [Síntese por dimensão] | [ID/pendente] |

### 63.1 Verificação detalhada

| Verificação | Estado | Evidência | Lacuna/condição | Responsável |
| --- | --- | --- | --- | --- |
| Objeto e versão estão identificados. | [Estado] | [ID] | [ID/nenhuma] | [Nome] |
| Entregas integrantes estão produzidas e verificadas. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Critérios de liberação possuem evidência. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Pessoas, dados, documentos, acessos, controles e suporte estão vinculados. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Riscos residuais possuem decisão. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Escopo de exposição e critérios de parada estão claros. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Reversão ou contingência é realizável. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Divergências materiais receberam tratamento. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Configuração candidata está registrada. | [Estado] | [ID/versão] | [ID/nenhuma] | [Nome] |

### 63.2 Condições de liberação

| Condição | Responsável | Limite | Evidência de atendimento | Consequência se não atendida | Estado |
| --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [Nome/papel] | [Data/gatilho] | [ID/pendente] | [Conter/adiar/reverter/outro] | [Estado] |

Liberação é delimitada por objeto, versão, ambiente, público e janela. Não se propaga automaticamente para outra ocorrência.

---

## 64. Cobertura no `PI-4` — aceite da implantação

Pergunta oficial:

> A capacidade foi efetivamente implantada, validada e aceita dentro dos critérios autorizados?

| Ocorrência | Capacidade/configuração | Versão | Critérios | Evidências | Diferenças | Riscos residuais | Cobertura | Aceite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Versão] | [IDs] | [IDs] | [IDs/nenhuma] | [IDs/nenhum] | [Síntese por dimensão] | [ID/pendente] |

### 64.1 Verificação detalhada

| Verificação | Estado | Evidência | Lacuna/condição | Responsável |
| --- | --- | --- | --- | --- |
| Capacidade possui evidência suficiente no contexto delimitado. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Competência, efeito humano, uso e controles foram examinados quando materiais. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Diferenças foram comparadas e classificadas. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Mudanças possuem autoridade correspondente. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Evidências negativas permanecem visíveis. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Aceite parcial possui fronteira verificável. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |
| Configuração aceita possui versão. | [Estado] | [ID/versão] | [ID/nenhuma] | [Nome] |
| Riscos e condições residuais possuem destino. | [Estado] | [IDs] | [ID/nenhuma] | [Nome] |

### 64.2 Fronteira do aceite

| Campo | Registro |
| --- | --- |
| Objeto aceito | [ID/versão] |
| Escopo e público | [Preencher] |
| Resultado | [Aceito/aceito com condições/rejeitado/revertido] |
| Limites | [Preencher/nenhum] |
| Condições | [IDs/nenhuma] |
| Diferenças incorporadas | [IDs/nenhuma] |
| Evidências que permanecem válidas | [IDs] |
| Evidências invalidadas | [IDs/nenhuma] |
| Configuração resultante | [ID/versão] |
| Decisão e autoridade | [ID; nome/papel] |

---

## 65. Cobertura no `PI-5` — transição para operação

Pergunta oficial:

> O Módulo 5 recebeu a configuração implantada, compreendeu suas condições e possui capacidade para sustentá-la?

| Objeto transferido | Versão | Responsável operacional | Sustentação | Indicador/limite | Risco/condição residual | Aceite bilateral | Cobertura de continuidade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [Nome/papel] | [IDs] | [IDs/síntese] | [IDs/nenhuma] | [ID] | [Estado] |

### 65.1 Verificação de continuidade

| Verificação | Estado | Evidência | Limite | Responsável |
| --- | --- | --- | --- | --- |
| Configuração e manifesto recebidos | [Estado] | [ID] | [Preencher] | [Nome] |
| Procedimentos e documentos vigentes | [Estado] | [IDs] | [Preencher] | [Nome] |
| Acessos e ambientes transferidos | [Estado] | [IDs] | [Preencher] | [Nome] |
| Competência operacional demonstrada | [Estado] | [IDs] | [Preencher] | [Nome] |
| Suporte e manutenção definidos | [Estado] | [IDs] | [Preencher] | [Nome] |
| Indicadores, limites e respostas definidos | [Estado] | [IDs] | [Preencher] | [Nome] |
| Riscos e condições residuais aceitos | [Estado] | [IDs] | [Preencher] | [Nome] |
| Critérios de retorno compreendidos | [Estado] | [IDs] | [Preencher] | [Nome] |

---

## 66. Retorno ao Módulo 3

| Gatilho | Objeto afetado | Evidência | Materialidade | Contenção no Módulo 4 | Registro de retorno | Estado no Módulo 3 | Nova referência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Requisito/componente/interface/autoridade/risco/dados/IA/linha de base/tolerância] | [ID/versão] | [IDs] | [Síntese] | [ID/ação] | [ID/link] | [Recebido/em análise/decidido] | [ID/versão/pendente] |

### 66.1 Efeito sobre a matriz

Ao retornar:

1. preserve a referência anterior;
2. marque vínculos afetados como condicionados, contestados ou invalidados;
3. identifique trabalho, evidência, gates e configurações afetados;
4. contenha avanço fora da alçada;
5. sincronize a nova decisão ou linha de base quando emitida;
6. reavalie evidências e coberturas;
7. registre eventual reabertura de gate.

---

## 67. Passagem ao Módulo 5 e destinação aos Módulos 6, 7 e 8

### 67.1 Objetos transferidos ao Módulo 5

| Objeto | Versão | Vínculos de sustentação | Condições | Responsável | Fonte no Módulo 5 | Aceite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Versão] | [IDs] | [IDs/nenhuma] | [Nome/papel] | [ID/link] | [ID] |

### 67.2 Aprendizagem e inteligência

| Aprendizagem | Origem | Destino | Motivo | Evidência | Responsável por avaliar | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [ID] | [Módulo 6/7/8/outro] | [Preencher] | [IDs] | [Nome/papel] | [Proposta/recebida/avaliada/incorporada/rejeitada] |

A destinação não transforma experiência local em regra universal. O módulo receptor decide eventual incorporação.

---

## 68. Papéis e responsabilidades

| Papel | Responsabilidade na matriz | Pode | Não pode | Evidência de aceite |
| --- | --- | --- | --- | --- |
| Responsável pela implantação | Integrar rastreabilidade ao ciclo. | Solicitar correção e submeter gates. | Aprovar além da própria alçada. | [ID] |
| Responsável pela rastreabilidade | Manter objetos, vínculos, estados e visões. | Propor e verificar relações. | Alterar conteúdo das fontes por conveniência. | [ID] |
| Responsável pela arquitetura | Confirmar herança e materialidade. | Recomendar retorno ao Módulo 3. | Autorizar execução no Módulo 4 sem alçada. | [ID] |
| Responsável pelo incremento | Atualizar realização, evidências, diferenças e estado do escopo. | Confirmar fatos sob sua coordenação. | Aceitar a própria entrega fora da governança. | [ID] |
| Responsável pela fonte | Manter objeto e versão oficiais. | Confirmar conteúdo e estado. | Declarar cobertura fora de competência. | [ID] |
| Responsável por evidência | Preservar proveniência e limite. | Corrigir registro factual. | Decidir aceite. | [ID] |
| Revisor | Verificar integridade e reconstrução. | Contestar e solicitar tratamento. | Substituir autoria ou autoridade. | [ID] |
| Especialista | Verificar matéria que excede a competência do projeto. | Emitir avaliação delimitada. | Ampliar a própria alçada pela expertise. | [ID] |
| Pessoa afetada ou representante | Contribuir com experiência, efeito e validação situada. | Registrar divergência e contestar. | Ser tratada como única representante sem legitimidade. | [ID] |
| Autoridade de gate | Decidir passagem delimitada. | Aceitar, condicionar, devolver, suspender ou rejeitar. | Tornar evidência inválida em válida. | [ID] |
| Responsável operacional | Avaliar sustentação e receber responsabilidade. | Aceitar ou devolver transição. | Alterar arquitetura silenciosamente. | [ID] |
| Custodiante | Preservar acesso, histórico e portabilidade. | Administrar fonte e retenção. | Reinterpretar decisões materiais. | [ID] |
| IA | Apoiar extração, comparação e verificação estrutural. | Sugerir vínculo ou lacuna como proposta. | Decidir cobertura, gate, risco, mudança ou transferência. | [ID/N.A.] |

---

## 69. Matriz de autoridade da rastreabilidade

| Ato | Prepara | Verifica | Recomenda | Decide | Registra | Deve ser informado |
| --- | --- | --- | --- | --- | --- | --- |
| Incluir objeto material | [Papel] | [Papel] | [Papel] | [Papel/regra] | [Papel] | [Papéis] |
| Confirmar vínculo | [Papel] | [Papel] | [Papel] | [Papel/regra] | [Papel] | [Papéis] |
| Classificar cobertura | [Papel] | [Papel] | [Papel] | [Autoridade do uso] | [Papel] | [Papéis] |
| Abrir/encerrar lacuna | [Papel] | [Papel] | [Papel] | [Papel/regra] | [Papel] | [Papéis] |
| Criar relação nova | [Papel] | [Papel] | [Papel] | [Autoridade metodológica] | [Papel] | [Papéis] |
| Invalidar vínculo | [Papel] | [Papel] | [Papel] | [Papel/autoridade] | [Papel] | [Papéis] |
| Congelar fotografia de gate | [Papel] | [Papel] | [Papel] | [Autoridade de gate] | [Papel] | [Papéis] |
| Alterar fonte oficial | [Papel] | [Papel] | [Papel] | [Autoridade definida] | [Papel] | [Papéis] |
| Encerrar matriz | [Papel] | [Papel] | [Papel] | [Autoridade da implantação] | [Papel] | [Papéis] |

### 69.1 Segregação

Em implantação sistêmica ou sensível, quem produz evidência, confirma cobertura e decide gate deve possuir segregação proporcional ao risco. Quando isso não for possível, registre compensações e revisão independente.

---

## 70. Cadências de manutenção

| Cadência/evento | Objetivo | Entradas | Saídas | Participantes | Responsável | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| Início da implantação | Configurar fonte e importar linha de base. | Transição e `PI-1`. | Matriz inicial. | [Papéis] | [Nome] | [ID] |
| Revisão de planejamento | Verificar origem e realização. | EAI, cronograma, backlog. | Lacunas e cobertura `PI-2`. | [Papéis] | [Nome] | [ID] |
| Revisão de fluxo | Capturar eventos materiais. | Resultados, bloqueios, mudanças. | Vínculos atualizados. | [Papéis] | [Nome] | [ID] |
| Pré-gate | Congelar fotografia e testar reconstrução. | Matriz vigente e fontes. | Visão de gate. | [Papéis] | [Nome] | [ID] |
| Pós-gate | Registrar decisão e consequência. | Registro de gate. | Estados e próximos movimentos. | [Papéis] | [Nome] | [ID] |
| Mudança/versionamento | Avaliar impacto. | Nova versão ou decisão. | Vínculos reavaliados. | [Papéis] | [Nome] | [ID] |
| Transição | Completar continuidade. | Configuração e sustentação. | Cadeias de `PI-5`. | [Papéis] | [Nome] | [ID] |
| Encerramento | Verificar reconstrução e destino. | Dossiê completo. | Matriz encerrada e preservada. | [Papéis] | [Nome] | [ID] |

Cadência periódica não substitui atualização por evento urgente ou material.

---

## 71. Indicadores de rastreabilidade

### 71.1 Indicadores de cobertura

| Indicador | Numerador | Denominador | Escopo | Estado tratado como coberto | Resultado | Limite | Decisão apoiada |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Cobertura de origem | [N] | [N de objetos aplicáveis] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |
| Cobertura de realização | [N] | [N de obrigações aplicáveis] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |
| Cobertura de evidência | [N] | [N de critérios exigíveis] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |
| Cobertura decisória | [N] | [N de movimentos que exigem decisão] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |
| Cobertura de configuração | [N] | [N de objetos aceitos] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |
| Cobertura de continuidade | [N] | [N de objetos transferíveis] | [Objeto/horizonte] | [Estados] | [N/%] | [Preencher] | [Preencher] |

### 71.2 Indicadores de qualidade

| Indicador | Definição | Fonte | Resultado | Tendência | Interpretação protegida | Ação |
| --- | --- | --- | --- | --- | --- | --- |
| Objetos órfãos materiais | [N/total aplicável] | [Consulta] | [Valor] | [Tendência] | Não excluir objetos para melhorar índice. | [Ação] |
| Vínculos propostos envelhecidos | [N/faixa] | [Consulta] | [Valor] | [Tendência] | Pode indicar falta de revisão, não falha individual. | [Ação] |
| Lacunas impeditivas abertas | [N] | [Registro] | [Valor] | [Tendência] | Gravidade prevalece sobre quantidade. | [Ação] |
| Diferenças sem decisão | [N] | [Registro] | [Valor] | [Tendência] | Uma diferença crítica pode impedir gate. | [Ação] |
| Fontes indisponíveis | [N] | [Teste] | [Valor] | [Tendência] | Acesso indevido e ausência são problemas distintos. | [Ação] |
| Vínculos desatualizados | [N] | [Consulta] | [Valor] | [Tendência] | Declarar janela de sincronização. | [Ação] |
| Reconstruções bloqueadas | [N/testes] | [Teste] | [Valor] | [Tendência] | Investigar caminho, não culpar custodiante isoladamente. | [Ação] |

### 71.3 Regras de cálculo

- não misturar dimensões;
- não contar `proposto` como confirmado;
- declarar tratamento de `parcial` e `condicionada`;
- excluir somente com fundamento e autoridade;
- preservar evidência negativa;
- não usar cem por cento como objetivo isolado;
- apresentar contagem absoluta junto ao percentual;
- impedir comparação entre universos incompatíveis.

---

## 72. Visões, filtros e exportações

| Visão | Pergunta | Filtro | Público | Matriz/versão | Data de extração | Dinâmica/congelada | Limitação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Origem e linha de base | O que foi recebido? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Requisitos e capacidades | O que precisa tornar-se real? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Realização e fluxo | Que trabalho realiza cada obrigação? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Prontidão e gates | O que sustenta a passagem? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Evidência e aceite | O que foi demonstrado? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Decisão e mudança | O que alterou o percurso? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Configuração e diferenças | O que foi instalado? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Transição e operação | Como continuará existindo? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Impacto | O que uma mudança afeta? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |
| Auditoria | Que lacunas e inconsistências existem? | [Preencher] | [Papéis] | [ID/versão] | [Data/hora] | [Tipo] | [Preencher] |

---

## 73. Estrutura de dados, portabilidade e continuidade

| Requisito | Solução adotada | Formato | Teste | Resultado | Responsável | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| IDs estáveis | [Preencher] | [Formato] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Vocabulários controlados | [Preencher] | [Formato] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Exportação completa | [Preencher] | [CSV/JSON/Markdown/outro] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Histórico recuperável | [Preencher] | [Formato] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Links resolvíveis | [Preencher] | [Formato] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Fotografias reproduzíveis | [Preencher] | [Formato] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Migração de ferramenta | [Preencher] | [Procedimento] | [ID/data] | [Resultado] | [Nome] | [Data] |
| Leitura sem conhecimento privado | [Preencher] | [Procedimento] | [ID/data] | [Resultado] | [Nome] | [Data] |

### 73.1 Modelo lógico mínimo exportável

```text
objeto(id, tipo, titulo, fonte, versao, estado, responsavel)
vinculo(id, origem, relacao, destino, cobertura, estado, vigencia, responsavel)
evento(id, data, objeto_ou_vinculo, estado_anterior, estado_novo, fundamento)
fotografia(id, gate, matriz_versao, data_status, escopo, fonte_preservada)
lacuna(id, objeto_ou_vinculo, dimensao, severidade, tratamento, estado)
```

O modelo lógico não obriga ferramenta específica.

---

## 74. Sensibilidade, acesso e proteção

| Classe/conteúdo | Necessidade de acesso | Público autorizado | Forma de proteção | Referência na matriz | Retenção | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Dado pessoal/risco/segurança/PI/custo/IA/outro] | [Finalidade] | [Papéis] | [Controle] | [ID mínimo/link protegido] | [Regra] | [Nome] |

### 74.1 Minimização

Referencie a fonte protegida quando copiar conteúdo ampliar exposição. A matriz precisa registrar o suficiente para governar existência, efeito, autoridade e destino.

### 74.2 Segredo não é ausência

Informação restrita pode ser representada por ID, classe, efeito e referência protegida. Não deve desaparecer quando necessária a uma decisão.

### 74.3 Acesso de gate

Quem decide deve receber informação material suficiente. Se parte do conteúdo permanecer restrita, defina revisão competente, síntese autorizada e limite da decisão.

---

## 75. Participação da inteligência artificial

A IA pode apoiar:

- extração inicial de referências;
- normalização de IDs;
- sugestão de relações;
- detecção de objetos órfãos;
- comparação de versões;
- busca de vínculos sem critério, evidência ou decisão;
- identificação de links quebrados;
- geração de visões derivadas;
- análise preliminar de impacto;
- verificação de consistência entre documentos;
- preparação de perguntas de gate.

A IA não pode:

- inventar objeto ou origem;
- transformar semelhança textual em vínculo confirmado;
- declarar cobertura completa;
- avaliar evidência material sem revisão competente;
- aceitar risco ou diferença;
- classificar mudança material autonomamente;
- aprovar gate ou liberação;
- transferir responsabilidade;
- apagar divergência;
- alterar a fonte oficial sem controle humano.

### 75.1 Registro da participação

| ID/data | Sistema/versão | Função | Escopo de entrada | Dados/classes | Regra/instrução | Saída | Limitações | Revisor humano | Correções | Decisão final |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/data] | [Preencher] | [Extrair/comparar/sugerir/verificar/sintetizar] | [IDs] | [Classes] | [ID/link/síntese] | [ID/link] | [Preencher] | [Nome/papel] | [Síntese] | [ID/resultado] |

---

## 76. Automação e verificações processáveis

| Regra | Objeto | Condição | Fonte | Resultado esperado | Severidade | Exceção | Responsável | Limite da automação |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Formato de ID | [Classe] | [Padrão] | [Matriz] | [Válido/inválido] | [Nível] | [Regra] | [Nome] | Não valida existência sem consulta. |
| Existência de fonte | [Objeto] | [Link resolvível] | [Repositório] | [Válido/aviso] | [Nível] | [Regra] | [Nome] | Não valida conteúdo. |
| Objeto órfão | [Classe] | [Sem vínculo material] | [Matriz] | [Aviso] | [Nível] | [Regra] | [Nome] | Materialidade exige revisão. |
| Obrigação sem realização | [Requisito/capacidade] | [Sem caminho] | [Matriz] | [Aviso/bloqueio] | [Nível] | [Regra] | [Nome] | Horizonte pode justificar. |
| Trabalho sem origem | [Unidade] | [Sem origem] | [Matriz/EAI] | [Aviso/bloqueio] | [Nível] | [Regra] | [Nome] | Trabalho administrativo pode ser legítimo. |
| Condição sem responsável | [Condição] | [Campo ausente] | [Matriz/registro] | [Inválida] | [Nível] | [Regra] | [Nome] | Não avalia autoridade. |
| Diferença sem decisão | [Diferença] | [Estado incompatível] | [Matriz/registro] | [Aviso/bloqueio] | [Nível] | [Regra] | [Nome] | Decisão pode estar protegida. |
| Versão divergente | [Objeto] | [Matriz ≠ fonte] | [Fontes] | [Aviso] | [Nível] | [Regra] | [Nome] | Precisa distinguir atraso de erro. |

### 76.1 Classificação de resultado

- válida;
- inválida;
- aviso;
- informação insuficiente;
- exceção registrada;
- revisão humana necessária.

Automação confirma estrutura. Não confirma materialidade nem semântica por si só.

---

## 77. Proporcionalidade

### 77.1 Implantação focal

Pode utilizar:

- catálogo por referência;
- matriz principal reduzida;
- relações críticas;
- uma visão consolidada de cobertura;
- fotografias de gate no mesmo arquivo;
- registro compacto de lacunas, diferenças e histórico.

### 77.2 Implantação funcional

Deve utilizar:

- matriz principal completa;
- visões de origem, realização, evidência, mudança e transição;
- controle de versões e sincronização;
- fotografias por gate;
- análise de impacto para mudanças materiais;
- testes de reconstrução por incremento ou onda.

### 77.3 Implantação sistêmica

Exige, conforme risco:

- segregação de funções;
- fontes estruturadas ou automatizadas;
- namespaces ampliados;
- múltiplas visões por público e domínio;
- auditoria de integridade;
- fotografias reproduzíveis por ocorrência;
- controle formal de configuração;
- análise de impacto sistêmica;
- revisão independente;
- proteção reforçada de dados e IA.

### 77.4 Intensificadores

Amplie o controle quando houver:

- impacto sobre direitos ou segurança;
- uso material de dados pessoais;
- IA em decisão ou produção crítica;
- regulação, contrato ou auditoria;
- múltiplos sistemas, fornecedores ou unidades;
- baixa reversibilidade;
- dependência crítica;
- mudança de autoridade;
- alta exposição pública ou reputacional.

### 77.5 Regra de redução

| Controle | Completo | Reduzido | Justificativa | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- |
| [Campo/visão/cadência] | [Sim/não] | [Forma] | [ID/síntese] | [Nome/papel] | [Data/evento] |

Simplificação reduz forma, não origem, evidência, autoridade, diferença ou continuidade material.

---

## 78. Revisão consolidada e teste de reconstrução

### 78.1 Revisão de identidade e fonte

- [ ] Matriz e implantação possuem IDs inequívocos.
- [ ] Fonte oficial e localização estão declaradas.
- [ ] Objetos importados preservam IDs e versões.
- [ ] Links são acessíveis às pessoas autorizadas.
- [ ] Visões declaram versão, data e filtro.

### 78.2 Revisão de origem e realização

- [ ] Transição resolve para linha de base autorizada.
- [ ] Toda obrigação material possui origem e destino.
- [ ] Todo trabalho material possui origem ou classificação.
- [ ] Componentes e interfaces permanecem rastreáveis.
- [ ] Dependências e condições possuem responsáveis.

### 78.3 Revisão de evidência e decisão

- [ ] Critérios antecedem afirmações de atendimento.
- [ ] Evidências possuem fonte, contexto, versão e limite.
- [ ] Evidências negativas permanecem visíveis.
- [ ] Gates identificam objetos e versões.
- [ ] Autoridades correspondem aos atos praticados.

### 78.4 Revisão de mudança e configuração

- [ ] Diferenças foram comparadas e classificadas.
- [ ] Correção, adaptação e mudança material estão distintas.
- [ ] Mudanças materiais retornaram ao Módulo 3.
- [ ] Configuração aceita possui manifesto e versão.
- [ ] Evidências afetadas por mudança foram reavaliadas.

### 78.5 Revisão de continuidade

- [ ] Responsabilidades operacionais foram aceitas bilateralmente.
- [ ] Documentos, acessos, suporte e manutenção estão vigentes.
- [ ] Indicadores possuem limite e resposta.
- [ ] Riscos e condições residuais possuem destino.
- [ ] Critérios de retorno estão explícitos.

### 78.6 Percurso regressivo

Parta de uma configuração transferida e localize:

1. entrega ou incremento de origem;
2. critério e evidência;
3. gate e decisão;
4. componente e capacidade;
5. requisito;
6. linha de base;
7. origem diagnóstica ou obrigação legítima.

### 78.7 Percurso progressivo

Parta de requisito ou condição e localize:

1. capacidade;
2. realização;
3. preparação;
4. evidência;
5. decisão;
6. configuração;
7. operação.

### 78.8 Percurso de mudança

Parta de diferença ou decisão e localize versão anterior, impacto, autoridade, nova versão, revalidação e efeito operacional.

### 78.9 Percurso de condição residual

Parta de risco ou pendência transferida e localize origem, aceitação, responsável, limite, resposta, gatilho de retorno e aceite operacional.

### 78.10 Registro do teste

| Teste | Objeto inicial | Objeto final esperado | Resultado | Ponto de bloqueio | Lacuna | Correção | Revisor | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Regressivo/progressivo/mudança/condição residual] | [ID] | [ID] | [Suficiente/parcial/bloqueado/fonte indisponível/versão ambígua/relação incorreta] | [ID/etapa] | [ID/nenhuma] | [ID/ação] | [Nome] | [Data] |

---

## 79. Antipadrões e sinais de qualidade

### 79.1 Antipadrões

| Antipadrão | Sinal observável | Efeito | Tratamento |
| --- | --- | --- | --- |
| Matriz de encerramento | Vínculos criados apenas depois das decisões. | Justificação retrospectiva. | Atualizar durante o ciclo. |
| Matriz como inventário | Objetos sem relações. | Origem e consequência invisíveis. | Registrar vínculos materiais. |
| Matriz como relatório | Narrativas extensas sem estrutura. | Baixa filtragem e verificabilidade. | Referenciar fontes e estruturar relações. |
| Listas em uma linha | Vários requisitos e evidências numa célula. | Estado e critério indistintos. | Uma relação por linha. |
| Link como evidência | Arquivo existente tratado como demonstração. | Cobertura aparente. | Declarar critério, resultado e limite. |
| Cobertura por menção | IDs no mesmo documento contados como relacionados. | Relação não comprovada. | Confirmar semântica. |
| Cem por cento isolado | Pressão para excluir ou classificar otimisticamente. | Distorção. | Mostrar estados, contagens e lacunas. |
| Versão flutuante | Objeto relacionado sem formulação conhecida. | Decisão ambígua. | Fixar versão. |
| Gate sem fotografia | Fonte dinâmica apaga o conjunto considerado. | Irreprodutibilidade. | Congelar recorte. |
| Diferença silenciosa | Configuração diverge sem registro. | Mudança implícita. | Abrir diferença e decidir. |
| Retorno informal | Arquitetura muda por conversa. | Perda de autoridade e linha de base. | Registrar retorno ao Módulo 3. |
| Não aplicável defensivo | Exclusão sem fundamento. | Lacuna escondida. | Exigir escopo e autoridade. |
| IA como autora da cobertura | Sugestão automática tratada como conclusão. | Falsa confiança. | Revisão humana e fonte. |
| Matriz paralela | Planilha, documento e ferramenta divergem. | Múltiplas verdades. | Declarar e sincronizar fonte única. |
| Operação como coluna final | Destino genérico sem sustentação. | Transferência nominal. | Registrar responsável, indicador, limite e aceite. |

### 79.2 Sinais de qualidade

| Dimensão | Sinal | Estado | Evidência | Ação |
| --- | --- | --- | --- | --- |
| Identidade | IDs e versões resolvem sem ambiguidade. | [Estado] | [ID] | [Ação] |
| Semântica | Relações expressam significado material. | [Estado] | [ID] | [Ação] |
| Completude suficiente | Cadeias aplicáveis podem ser percorridas. | [Estado] | [ID] | [Ação] |
| Atualidade | Eventos materiais estão sincronizados. | [Estado] | [ID] | [Ação] |
| Transparência | Lacunas e divergências permanecem visíveis. | [Estado] | [ID] | [Ação] |
| Governabilidade | Responsáveis e autoridades estão claros. | [Estado] | [ID] | [Ação] |
| Verificabilidade | Evidências e critérios são localizáveis. | [Estado] | [ID] | [Ação] |
| Temporalidade | Fotografias e versões preservam o passado. | [Estado] | [ID] | [Ação] |
| Continuidade | Configuração chega a sustentação e retorno. | [Estado] | [ID] | [Ação] |
| Segurança | Acesso e minimização são proporcionais. | [Estado] | [ID] | [Ação] |
| Portabilidade | Fonte pode ser exportada e reconstruída. | [Estado] | [ID] | [Ação] |

---

## 80. Exemplo aplicado — sistema editorial

### 80.1 Contexto

A implantação `IMP-2026-001` realiza a linha de base `LB-ARQ-001 v1.0` de um sistema editorial. A capacidade `CAP-ARQ-004` estabelece que conteúdos ativos possam ser acompanhados por estado, responsabilidade e próxima ação.

O exemplo é ilustrativo. IDs, fontes, critérios e autoridades devem ser substituídos pelos registros reais.

### 80.2 Objetos de referência

| Objeto | ID e versão | Função |
| --- | --- | --- |
| Projeto de arquitetura | `ARQ-2026-001` | Origem do desenho. |
| Linha de base | `LB-ARQ-001 v1.0` | Referência autorizada. |
| Matriz arquitetural | `MTR-ARQ-2026-001 v1.0` | Caminho anterior. |
| Capacidade | `CAP-ARQ-004 v1.0` | Acompanhar conteúdo por estado e próxima ação. |
| Requisito | `REQ-ARQ-007 v1.0` | Estado, responsável e próxima ação localizáveis. |
| Componente | `CMP-ARQ-011 v1.0` | Base editorial controlada. |
| Incremento | `IMP-2026-001-INC-001 v0.2` | Piloto com quatro conteúdos. |
| Configuração | `IMP-2026-001-CFG-001 v1.0` | Forma implantada candidata. |

### 80.3 Vínculos iniciais

| Vínculo | Origem | Relação | Destino | Dimensão | Cobertura | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-VNC-001` | `CAP-ARQ-004 v1.0` | `é_realizada_por` | `IMP-2026-001-INC-001 v0.2` | Realização | Planejada | Confirmado |
| `IMP-2026-001-VNC-002` | `IMP-2026-001-ENT-001 v0.3` | `realiza` | `CAP-ARQ-004 v1.0` | Realização | Em realização | Confirmado |
| `IMP-2026-001-VNC-003` | `IMP-2026-001-ENT-002 v0.2` | `atende_parcialmente` | `REQ-ARQ-007 v1.0` | Realização | Parcial | Condicionado |
| `IMP-2026-001-VNC-004` | `IMP-2026-001-ENT-004 v0.1` | `depende_de` | `IMP-2026-001-ENT-003 v0.2` | N.A. | N.A. | Confirmado |

### 80.4 Critério e evidências

Critério:

> Quatro conteúdos percorrem o fluxo delimitado com estado, responsável, arquivos e próxima ação localizáveis, sem perda de contexto ou voz autoral.

| Evidência | Demonstra | Contexto | Resultado | Limite |
| --- | --- | --- | --- | --- |
| `IMP-2026-001-EVD-001` | `REQ-ARQ-007` | Quatro conteúdos piloto. | Atendido nos quatro casos. | Não demonstra escala maior. |
| `IMP-2026-001-EVD-003` | `CAP-ARQ-004` | Uso assistido. | Capacidade observada. | Autonomia ainda não avaliada. |
| `IMP-2026-001-EVD-004` | Competência da responsável | Demonstração prática. | Suficiente com suporte. | Reavaliar após estabilização. |
| `IMP-2026-001-EVD-006` | Indicador de item sem próxima ação | Período do piloto. | Uma exceção detectada e corrigida. | Janela curta. |

### 80.5 Diferença

A arquitetura previa uma etapa de aprovação. O piloto revelou necessidade de dois estados: `em revisão` e `ajustes solicitados`.

| Campo | Registro de exemplo |
| --- | --- |
| Diferença | `IMP-2026-001-DIF-001` |
| Referência | `CMP-ARQ-011 v1.0` |
| Configuração observada | Dois estados de revisão. |
| Classificação inicial | Adaptação autorizada candidata. |
| Teste de materialidade | Não altera autoridade se o aprovador permanecer o mesmo. |
| Evidência | Histórico dos quatro conteúdos. |
| Decisão | Aceitar dentro da tolerância e atualizar documentação. |
| Gatilho de retorno | Redistribuição da autoridade de aprovação. |

### 80.6 Cobertura no `PI-4`

| Dimensão | Estado | Limite |
| --- | --- | --- |
| Origem | Completa | Linha de base e decisão localizáveis. |
| Realização | Completa para o piloto | Quatro conteúdos; não representa escala maior. |
| Evidência | Demonstrada | Exceção foi corrigida; janela curta. |
| Decisão | Completa | Diferença recebeu classificação e aceite delimitado. |
| Configuração | Completa para `CFG-001 v1.0` | Versão ainda em estabilização. |
| Continuidade | Planejada | Responsável e suporte serão confirmados no `PI-5`. |

### 80.7 Limite do exemplo

A existência dos vínculos não autoriza o `PI-4`. A autoridade examina critérios, evidências, diferenças, riscos e limites da fotografia aplicável.

---

## 81. Manifestações, controle de versões e encerramento

### 81.1 Responsável pela rastreabilidade

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Matriz suficiente / suficiente com condições / insuficiente |
| Escopo e versão examinados | [IDs/versões] |
| Lacunas | [IDs/nenhuma] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 81.2 Responsável pela implantação

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Integrada / integrada com condições / requer revisão |
| Riscos ou ressalvas | [IDs/nenhuma] |
| Próximo movimento recomendado | [Preencher] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 81.3 Responsável pela arquitetura

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação sobre herança e diferenças | [Preencher] |
| Retornos ao Módulo 3 | [IDs/nenhum] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 81.4 Responsável operacional

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação sobre continuidade | [Suficiente/suficiente com condições/insuficiente] |
| Objetos e versões recebidos | [IDs/versões] |
| Condições | [IDs/nenhuma] |
| Data | [Data] |
| Assinatura ou referência | [Preencher] |

### 81.5 Divergências preservadas

| Pessoa/papel | Divergência | Objeto/vínculo | Evidência | Destino | Decisão relacionada |
| --- | --- | --- | --- | --- | --- |
| [Nome/papel] | [Preencher] | [IDs] | [IDs] | [Preencher] | [ID/pendente] |

### 81.6 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de status | [Data/hora] |
| Fonte oficial | [Caminho/link] |
| Linha de base referenciada | [ID/versão] |
| Configuração mais recente | [ID/versão/N.A.] |
| Gate mais recente | [ID/N.A.] |
| Decisão/aprovação | [ID/N.A.] |
| Versão substituída | [N.N/N.A.] |

### 81.7 Histórico de versões da matriz preenchida

| Versão | Data | Alteração | Evento/motivo | Objetos/vínculos afetados | Responsável | Aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| [N.N] | [Data] | [Preencher] | [ID/síntese] | [IDs] | [Nome] | [ID/N.A.] |

### 81.8 Critérios de conclusão

A matriz pode ser considerada suficientemente concluída quando:

- possui identidade e fonte oficial;
- resolve para transição e linha de base autorizada;
- preserva IDs e versões herdados;
- toda obrigação material possui origem e destino;
- todo trabalho material possui origem ou classificação;
- cadeias aplicáveis estão completas ou possuem lacuna tratada;
- critérios, evidências e decisões de gates são recuperáveis;
- resultados de gates identificam objeto e versão;
- diferenças foram comparadas, classificadas e decididas;
- configuração aceita e estabilizada possui versão;
- riscos e condições residuais possuem responsável e aceite;
- transição operacional possui vínculos de sustentação;
- objetos órfãos materiais foram tratados;
- vínculos inválidos foram corrigidos ou encerrados;
- histórico preserva decisões e versões anteriores;
- participação material da IA está registrada;
- acesso e sensibilidade estão adequados;
- testes de reconstrução foram realizados;
- aprendizagem possui destino;
- outra pessoa autorizada consegue reconstruir o percurso sem memória privada.

### 81.9 Resultado de conclusão

- [ ] Concluída para o horizonte declarado
- [ ] Concluída com condições
- [ ] Requer complementação
- [ ] Requer correção de vínculos
- [ ] Requer decisão de autoridade
- [ ] Requer retorno ao Módulo 3
- [ ] Bloqueada
- [ ] Suspensa
- [ ] Substituída

| Campo | Registro |
| --- | --- |
| Objeto/horizonte | [IDs/período] |
| Resultado | [Selecionar] |
| Versão da matriz | [N.N] |
| Cobertura por dimensão | [Síntese/IDs] |
| Lacunas e condições | [IDs/nenhuma] |
| Fotografias de gate | [IDs] |
| Configuração final relacionada | [ID/versão/N.A.] |
| Próximo movimento | [Verificar gate/corrigir/transferir/preservar/retornar/outro] |
| Responsável | [Nome/papel] |
| Autoridade | [Nome/papel] |
| Data | [Data] |
| Evidência | [ID/link] |

Conclusão da matriz não encerra vínculos que continuam vigentes na operação. Ela confirma que o percurso da implantação está suficientemente preservado para o horizonte declarado.

### 81.10 Registro final do template

| Campo | Registro |
| --- | --- |
| Identificador do template | `templates/06-matriz-de-rastreabilidade-da-implantacao.md` |
| Módulo | 4 — Implantação |
| Tipo | Template operacional |
| Função | Registrar e verificar vínculos entre arquitetura, realização, evidência, decisão, configuração e operação |
| Entrada principal | Linha de base arquitetural aceita e instrumentos de implantação vigentes |
| Saída principal | Fonte canônica dos vínculos, coberturas, lacunas, fotografias e caminhos reconstruíveis |
| Gates relacionados | `PI-1` a `PI-5` |
| Documento anterior | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` |
| Documento seguinte | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |
| Fonte oficial | Repositório do Sistema Operacional do Estúdio LICHTARA |
| Responsabilidade final | Humana |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação integral da Matriz de Rastreabilidade da Implantação como instrumento preenchível do dossiê real. | Estúdio LICHTARA |
