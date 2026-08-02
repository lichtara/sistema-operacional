# Registro de Arquitetura — Manifesto Mestre do Dossiê

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Diretório de origem:** `registros-de-arquitetura/`  
**Tipo:** Modelo controlado, preenchível e reutilizável  
**Versão do modelo:** 0.1  
**Estado do arquivo-fonte:** Modelo — não preencher com dados reais  
**Data de criação:** 02/08/2026

> [!IMPORTANT]
> Este arquivo é a fonte controlada do manifesto mestre. Para abrir uma arquitetura real, copie seu conteúdo para `AAAA/ARQ-AAAA-NNN-nome-curto/README.md` e preencha somente a cópia. Não renomeie nem preencha este arquivo na raiz.

**Documentos relacionados:**

- `README.md` deste diretório;
- `01-indice-de-arquiteturas.md`;
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
- `../templates/09-retrospectiva-da-arquitetura.md`.

---

## 1. Finalidade

Este manifesto é a porta de entrada de um dossiê real de arquitetura organizacional. Ele preserva a identidade do projeto, informa seu estado vigente, explicita responsabilidade e autoridade, aponta para as fontes oficiais e torna visíveis linha de base, condições, riscos, próxima ação, transição e encerramento.

Seu propósito é permitir que uma pessoa autorizada compreenda rapidamente:

- o que esta arquitetura procura transformar;
- por que o projeto existe;
- quem pode decidir, executar, validar e aprovar;
- qual configuração está vigente;
- onde estão os registros oficiais;
- que condição impede ou limita o avanço;
- qual ação deve ocorrer em seguida;
- como reconstruir o ciclo sem depender da memória individual.

## 2. Pergunta central

> O que é esta arquitetura, em que estado ela se encontra, qual referência está vigente, quem responde pelo próximo movimento e por quais fontes, decisões, condições e evidências seu ciclo pode ser reconstruído?

## 3. Natureza do manifesto

Este documento é:

- o mapa principal do dossiê;
- a fonte oficial dos metadados do projeto;
- o registro do estado vigente e de seu histórico;
- o manifesto das fontes e versões;
- o ponto de coordenação da linha de base;
- o resumo governado de pendências e próximas ações;
- a rota de passagem entre os módulos.

Este documento não é:

- o relatório final;
- a arquitetura integrada;
- o catálogo oficial de requisitos;
- a matriz de rastreabilidade;
- o repositório de todas as evidências;
- um cronograma detalhado;
- uma cópia dos nove artefatos do projeto;
- um substituto para decisões formalmente registradas.

## 4. Regra de cópia e uso

1. reserve o ID no `01-indice-de-arquiteturas.md`;
2. crie `AAAA/ARQ-AAAA-NNN-nome-curto/`;
3. copie este conteúdo para o `README.md` da pasta criada;
4. registre a versão do modelo de origem;
5. substitua marcadores somente na cópia;
6. mantenha os títulos necessários ao controle;
7. remova seções não aplicáveis apenas com justificativa de proporcionalidade;
8. aponte para fontes oficiais, sem reproduzi-las;
9. atualize manifesto e índice no mesmo ciclo de cada evento material;
10. preserve o histórico quando uma informação for substituída.

## 5. Resultado esperado

O manifesto estará apto ao uso quando:

- possuir identidade única;
- corresponder à pasta e à linha do índice;
- apresentar um único estado vigente;
- indicar responsável, próxima ação e prazo ou gatilho;
- distinguir síntese de fonte oficial;
- resolver links para os artefatos aplicáveis;
- declarar a linha de base vigente ou registrar que ainda não existe;
- tornar condições, riscos e decisões pendentes visíveis;
- informar acesso, retenção e custódia;
- sustentar transição, reabertura ou encerramento sem ambiguidade.

## 6. Fronteiras de autoridade

| Informação | Fonte oficial | Papel do manifesto |
| --- | --- | --- |
| Identidade, estado e próxima ação | Este manifesto | Manter |
| Portfólio e localização transversal | `01-indice-de-arquiteturas.md` | Sincronizar |
| Requisitos | Catálogo de Requisitos | Apontar e resumir |
| Relações entre objetos | Matriz de Rastreabilidade | Apontar e indicar integridade |
| Configuração consolidada | Arquitetura Integrada | Apontar e sintetizar a tese |
| Decisão | Registro `DEC-AAAA-NNN` | Referenciar |
| Validação | Registro de Validação | Referenciar e resumir resultado |
| Linha de base | Manifesto da linha de base neste dossiê | Identificar vigência |
| Implantação | Transição e registros do Módulo 4 | Registrar passagem e aceite |
| Aprendizagem | Retrospectiva e Módulo 6 | Encaminhar |

Em caso de divergência, não escolha silenciosamente a informação mais recente. Identifique a autoridade do objeto, registre a divergência e corrija todas as derivações.

## 7. Princípios de preenchimento

1. **Síntese com endereço** — toda afirmação material aponta para sua fonte.
2. **Estado observável** — avanço resulta de critério e evidência, não de impressão.
3. **Próxima ação executável** — use verbo, objeto, responsável e condição temporal.
4. **Uma referência vigente** — linha de base e versão não podem ser inferidas.
5. **Histórico sem apagamento** — mudança substitui vigência, não destrói memória.
6. **Acesso mínimo necessário** — localização não autoriza exposição.
7. **Proporcionalidade explícita** — o que não se aplica recebe justificativa.
8. **Responsabilidade humana** — IA pode apoiar; não se torna aprovadora.
9. **Portabilidade** — links, IDs e descrições devem sobreviver à troca de ferramenta.
10. **Encerramento demonstrável** — pendências, custódia e aprendizagem recebem destino.

## 8. Proporcionalidade do dossiê

Marque uma classificação e justifique.

- [ ] **Focal** — mudança delimitada, poucas interfaces e risco controlado.
- [ ] **Funcional** — mudança entre processos ou funções, com múltiplos papéis e dependências.
- [ ] **Sistêmica** — transformação ampla, interdependente, regulada ou de alto impacto.

| Campo | Registro |
| --- | --- |
| Classificação | [Focal, funcional ou sistêmica] |
| Critérios utilizados | [Impacto, risco, complexidade, alcance e reversibilidade] |
| Artefatos combinados | [IDs/N/A] |
| Artefatos não aplicáveis | [IDs/N/A] |
| Justificativa da redução ou expansão | [Preencher] |
| Autoridade que aceitou a proporcionalidade | [Nome/papel/decisão] |
| Data de revisão | [DD/MM/AAAA] |

Reduzir significa combinar estruturas preservando função. Não significa omitir requisito material, decisão, risco, responsável, validação ou versão.

## 9. Convenções de preenchimento

| Marcador | Uso |
| --- | --- |
| `[Preencher]` | Informação obrigatória ainda não registrada |
| `[Selecionar]` | Escolha dentro de vocabulário controlado |
| `N/A — [justificativa]` | Item legitimamente não aplicável |
| `[Não disponível — condição]` | Informação exigida, mas indisponível |
| `[ID/link]` | Referência resolvível à fonte oficial |
| `[DD/MM/AAAA]` | Data completa |
| `[AAAA-MM-DD]` | Data usada em nome ou ordenação técnica |

Não use `TBD`, `a definir` ou células vazias em campo material sem responsável e prazo ou gatilho.

## 10. Convenções de identificação

| Objeto | Padrão |
| --- | --- |
| Projeto | `ARQ-AAAA-NNN` |
| Linha de base | `LB-ARQ-NNN` |
| Decisão | `DEC-AAAA-NNN` |
| Condição | `COND-ARQ-NNN` |
| Risco | `RIS-ARQ-NNN` |
| Interface | `INT-ARQ-NNN` |
| Componente | `CMP-ARQ-NNN` |
| Mudança | `MUD-ARQ-NNN` |
| Evidência | `EVD-ARQ-NNN` |

Quando um ID circular fora do dossiê, qualifique-o com o ID do projeto sempre que houver risco de ambiguidade.

## 11. Identificação principal

| Campo | Registro |
| --- | --- |
| ID da arquitetura | `ARQ-AAAA-NNN` |
| Título canônico | [Preencher] |
| Título público ou protegido | [Preencher/N/A] |
| Organização/cliente | [Nome ou código autorizado] |
| Unidade/área | [Preencher] |
| Patrocinador | [Nome/papel] |
| Responsável pela arquitetura | [Nome/papel] |
| Custodiante do dossiê | [Nome/papel] |
| Data de recebimento | [DD/MM/AAAA] |
| Data de abertura | [DD/MM/AAAA] |
| Última atualização material | [DD/MM/AAAA — evento] |
| Versão deste manifesto | [Preencher] |
| Versão do modelo de origem | 0.1 |

## 12. Síntese de uma frase

> [Descrever, em uma frase, que capacidade ou forma de trabalho muda, para quem, com qual resultado esperado e sob qual limite principal.]

| Elemento | Síntese |
| --- | --- |
| Situação de origem | [Preencher] |
| Transformação pretendida | [Preencher] |
| Resultado organizacional | [Preencher] |
| Limite principal | [Preencher] |

## 13. Título, descrição pública e proteção

| Campo | Registro |
| --- | --- |
| Título interno | [Preencher] |
| Título autorizado no índice | [Preencher] |
| Código de proteção, se necessário | [Preencher/N/A] |
| Descrição pública permitida | [Preencher/N/A] |
| Termos que não devem aparecer em busca | [Preencher/N/A] |
| Autoridade da classificação | [Nome/papel] |

## 14. Caminho canônico

| Campo | Registro |
| --- | --- |
| Pasta anual | `AAAA/` |
| Nome da pasta | `ARQ-AAAA-NNN-nome-curto/` |
| Caminho do manifesto | `AAAA/ARQ-AAAA-NNN-nome-curto/README.md` |
| Link no índice | [Link relativo] |
| Repositório ou ambiente oficial | [Preencher] |
| Última verificação do caminho | [DD/MM/AAAA — responsável] |

O ID da pasta, deste manifesto e do índice deve ser idêntico.

## 15. Classificação de acesso

Selecione uma classe vigente:

- [ ] Público autorizado;
- [ ] Interno;
- [ ] Confidencial;
- [ ] Restrito;
- [ ] Segregado por arquivo.

| Campo | Registro |
| --- | --- |
| Classe do manifesto | [Selecionar] |
| Público autorizado | [Papéis/grupos] |
| Responsável por conceder acesso | [Nome/papel] |
| Restrições de compartilhamento | [Preencher] |
| Exceções por arquivo | [IDs/caminhos/N/A] |
| Próxima revisão de acesso | [DD/MM/AAAA/evento] |
| Evidência da autorização | [ID/link] |

## 16. Estado vigente do projeto

Marque exatamente um estado.

| Grupo | Estado | Seleção |
| --- | --- | --- |
| Entrada | Transição recebida | [ ] |
| Entrada | Em aceite | [ ] |
| Entrada | Aceita | [ ] |
| Entrada | Aceita com condições | [ ] |
| Entrada | Devolvida ao diagnóstico | [ ] |
| Abertura e planejamento | Em abertura | [ ] |
| Abertura e planejamento | Aguardando aprovação de abertura | [ ] |
| Abertura e planejamento | Planejada | [ ] |
| Desenho | Em requisitos | [ ] |
| Desenho | Em alternativas | [ ] |
| Desenho | Em desenho | [ ] |
| Desenho | Em integração | [ ] |
| Desenho | Em avaliação | [ ] |
| Decisão e consolidação | Aguardando decisão | [ ] |
| Decisão e consolidação | Em consolidação | [ ] |
| Decisão e consolidação | Em validação | [ ] |
| Decisão e consolidação | Em revisão | [ ] |
| Decisão e consolidação | Aguardando aprovação | [ ] |
| Aprovação e passagem | Aprovada | [ ] |
| Aprovação e passagem | Aprovada com condições | [ ] |
| Aprovação e passagem | Em transição para implantação | [ ] |
| Encerramento e exceção | Encerrada | [ ] |
| Encerramento e exceção | Suspensa | [ ] |
| Encerramento e exceção | Cancelada | [ ] |
| Encerramento e exceção | Reaberta | [ ] |
| Encerramento e exceção | Substituída | [ ] |

| Campo | Registro |
| --- | --- |
| Estado vigente | [Selecionar exatamente um] |
| Data de vigência | [DD/MM/AAAA] |
| Gatilho ou critério atendido | [Preencher] |
| Evidência | [ID/link] |
| Autoridade/responsável | [Nome/papel] |

## 17. Histórico de estados

| Estado anterior | Novo estado | Data | Critério/gatilho | Decisão/evidência | Responsável | Condição seguinte |
| --- | --- | --- | --- | --- | --- | --- |
| [Estado/N/A] | [Estado] | [DD/MM/AAAA] | [Preencher] | [ID/link] | [Nome/papel] | [Preencher] |

Não reescreva a linha anterior quando o estado mudar. Acrescente novo evento e atualize a seção 16.

## 18. Atenção, prioridade e atualidade

| Dimensão | Valor | Motivo/evidência | Autoridade | Revisão |
| --- | --- | --- | --- | --- |
| Situação de atenção | [Normal, atenção, bloqueada, decisão pendente ou em escalonamento] | [Preencher] | [Nome/papel] | [Data] |
| Prioridade | [Crítica, alta, média ou baixa] | [Preencher] | [Nome/papel] | [Data] |
| Atualidade do registro | [Atual, revisar ou desatualizado] | [Evento/data] | [Nome/papel] | [Data] |

Prioridade não altera autoridade nem transforma urgência em aprovação.

## 19. Próxima ação

| Campo | Registro |
| --- | --- |
| Ação | [Verbo + objeto verificável] |
| Resultado esperado | [Preencher] |
| Responsável | [Nome/papel] |
| Colaboradores | [Nomes/papéis/N/A] |
| Prazo ou gatilho | [DD/MM/AAAA ou evento observável] |
| Dependência | [ID/condição/N/A] |
| Evidência de conclusão | [Preencher] |
| Consequência se não ocorrer | [Preencher] |
| Escalonamento | [Nome/papel/N/A] |

Projeto ativo sem próxima ação deve ser corrigido, suspenso ou encerrado.

## 20. Origem da arquitetura

| Campo | Registro |
| --- | --- |
| Tipo de origem | [Diagnóstico, decisão, operação, obrigação, incidente, oportunidade ou outro] |
| Documento principal | [ID/link] |
| Organização remetente | [Preencher] |
| Responsável pela entrega | [Nome/papel] |
| Data de recebimento | [DD/MM/AAAA] |
| Escopo recebido | [Preencher] |
| Restrições de uso | [Preencher/N/A] |
| Outras fontes relevantes | [IDs/links] |

## 21. Transição recebida do Módulo 2

| Item | Fonte/versão | Recebido? | Integridade | Uso autorizado | Observação |
| --- | --- | --- | --- | --- | --- |
| Síntese diagnóstica | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |
| Matriz de evidências | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |
| Relatório de diagnóstico | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |
| Registro de validação | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |
| Transição para arquitetura | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |
| Restrições e pendências | [ID/link] | [Sim/não/N/A] | [Íntegra/parcial] | [Sim/não] | [Preencher] |

## 22. Aceite da entrada

Selecione o resultado vigente:

- [ ] Aceita;
- [ ] Aceita com condições;
- [ ] Devolvida ao diagnóstico;
- [ ] Suspensa;
- [ ] Cancelada.

| Campo | Registro |
| --- | --- |
| Resultado | [Selecionar] |
| Data | [DD/MM/AAAA] |
| Critério aplicado | [Preencher] |
| Lacunas identificadas | [IDs/síntese/Nenhuma] |
| Limites enquanto houver lacuna | [Preencher/N/A] |
| Responsável pelo aceite | [Nome/papel] |
| Evidência/decisão | [ID/link] |

## 23. Condições de entrada

| ID | Condição | Impacto | Responsável | Prazo/gatilho | Restrição enquanto aberta | Estado | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| COND-ARQ-NNN | [Preencher] | [Preencher] | [Nome/papel] | [Data/evento] | [Preencher] | [Aberta, em tratamento, atendida, aceita ou vencida] | [ID/link] |

## 24. Problema de arquitetura

> [Descrever a tensão estrutural que exige desenho organizacional, evitando formular apenas um sintoma ou uma solução antecipada.]

| Pergunta | Resposta |
| --- | --- |
| Que resultado está comprometido? | [Preencher] |
| Que configuração atual contribui para o problema? | [Preencher] |
| Quem é afetado? | [Preencher] |
| Que evidência sustenta a formulação? | [IDs/links] |
| O que permanece incerto? | [Preencher] |
| O que aconteceria sem intervenção? | [Preencher] |

## 25. Decisão que a arquitetura deve sustentar

| Campo | Registro |
| --- | --- |
| Pergunta decisória | [Preencher] |
| Autoridade decisora | [Nome/papel/instância] |
| Data ou gatilho da decisão | [Preencher] |
| Alternativas admissíveis | [IDs/critério] |
| Critérios determinantes | [IDs/síntese] |
| Informação ainda necessária | [Preencher/N/A] |
| Consequência da não decisão | [Preencher] |

## 26. Tese de transformação

> Se [mudança de configuração], então [capacidade/resultado] poderá ocorrer porque [mecanismo causal], desde que [condições e limites].

| Elemento | Registro |
| --- | --- |
| Mudança estrutural | [Preencher] |
| Mecanismo esperado | [Preencher] |
| Resultado | [Preencher] |
| Condições | [IDs/síntese] |
| Hipótese mais frágil | [Preencher] |
| Evidência que poderá refutá-la | [Preencher] |

## 27. Escopo incluído

| ID | Elemento incluído | Tipo | Resultado esperado | Limite | Responsável semântico |
| --- | --- | --- | --- | --- | --- |
| ESC-ARQ-NNN | [Processo, papel, informação, comunicação, documento, indicador, tecnologia, IA ou outro] | [Tipo] | [Preencher] | [Preencher] | [Nome/papel] |

## 28. Fora de escopo e não objetivos

| Elemento | Motivo | Destino correto | Risco de confusão | Reavaliação |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Módulo/projeto/operação] | [Preencher] | [Data/evento/N/A] |

Fora de escopo não significa irrelevante. Registre interfaces e dependências quando o elemento puder afetar a configuração.

## 29. Interfaces externas ao escopo

| ID | Interface | Sistema/unidade externa | Entrada | Saída | Responsável | Risco | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| INT-ARQ-NNN | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [ID/síntese] | [ID/link] |

## 30. Premissas e restrições

| ID | Tipo | Enunciado | Evidência/origem | Efeito no desenho | Validade | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| PRE/RES-ARQ-NNN | [Premissa ou restrição] | [Preencher] | [ID/link] | [Preencher] | [Confirmada, provisória ou refutada] | [Nome/papel] |

## 31. Riscos iniciais

| ID | Evento de risco | Causa | Consequência | Probabilidade | Impacto | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RIS-ARQ-NNN | [Preencher] | [Preencher] | [Preencher] | [Baixa/média/alta] | [Baixo/médio/alto] | [Evitar, reduzir, transferir ou aceitar] | [Nome/papel] |

## 32. Capacidades organizacionais afetadas

| ID | Capacidade | Situação atual | Situação necessária | Criticidade | Arquitetura relacionada | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| CAP-ARQ-NNN | [Preencher] | [Preencher] | [Preencher] | [Baixa/média/alta] | [ARQ ID/N/A] | [ID/link] |

## 33. Requisitos — resumo governado

| Campo | Registro |
| --- | --- |
| Fonte oficial | [Link para CAT-REQ-AAAA-NNN] |
| Versão | [Preencher] |
| Estado | [Preencher] |
| Total de requisitos materiais | [N] |
| Obrigatórios abertos | [N/IDs] |
| Atendidos com condição | [N/IDs] |
| Rejeitados | [N/IDs] |
| Última revisão | [DD/MM/AAAA] |
| Responsável | [Nome/papel] |

Não reproduza aqui o catálogo. Registre apenas o necessário para governar estado e decisão.

## 34. Critérios de arquitetura e decisão

| ID | Critério | Tipo | Peso/regra | Evidência esperada | Autoridade | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| CRI-ARQ-NNN | [Preencher] | [Obrigatório, desejável ou guardrail] | [Peso/limiar] | [Preencher] | [Nome/papel] | [ID/link] |

## 35. Partes interessadas

| Parte/grupo | Interesse | Impacto | Poder de decisão | Participação necessária | Representante | Restrição |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Baixo/médio/alto] | [Nenhum, consulta, veto ou decisão] | [Informar, consultar, cocriar, validar ou aprovar] | [Nome/papel] | [Preencher/N/A] |

## 36. Pessoas e grupos afetados

| Grupo | Mudança percebida | Benefício esperado | Custo/risco | Proteção necessária | Escuta/validação | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Método/data] | [Nome/papel] |

## 37. Governança do projeto

| Instância | Mandato | Composição | Frequência/gatilho | Decisões permitidas | Registro oficial |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Nomes/papéis] | [Preencher] | [Preencher] | [ID/link] |

## 38. Papéis do projeto

| Papel | Pessoa/unidade | Responsabilidade | Entregas | Substituto | Início/fim |
| --- | --- | --- | --- | --- | --- |
| Patrocinador | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Responsável pela arquitetura | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Decisor | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Revisor | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Validador | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Custodiante documental | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |
| Responsável pela implantação | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Datas] |

## 39. Autoridade, responsabilidades e alçadas

| Objeto/decisão | Propõe | Analisa | Decide | Valida | Deve ser consultado | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| Abertura | [Papel] | [Papel] | [Papel] | [Papel/N/A] | [Papéis] | [ID/link] |
| Requisitos | [Papel] | [Papel] | [Papel] | [Papel] | [Papéis] | [ID/link] |
| Alternativa | [Papel] | [Papel] | [Papel] | [Papel] | [Papéis] | [ID/link] |
| Arquitetura integrada | [Papel] | [Papel] | [Papel] | [Papel] | [Papéis] | [ID/link] |
| Linha de base | [Papel] | [Papel] | [Papel] | [Papel] | [Papéis] | [ID/link] |
| Mudança pós-aprovação | [Papel] | [Papel] | [Papel] | [Papel] | [Papéis] | [ID/link] |

## 40. Agenda de decisões

| ID | Decisão | Autoridade | Insumos obrigatórios | Data/gatilho | Estado | Consequência |
| --- | --- | --- | --- | --- | --- | --- |
| DEC-AAAA-NNN | [Preencher] | [Nome/papel] | [IDs] | [Preencher] | [Preparação, aguardando, emitida ou revista] | [Preencher] |

## 41. Comunicação do projeto

| Público | Conteúdo | Canal | Frequência/gatilho | Emissor | Confirmação necessária | Registro |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Sim/não] | [ID/link/N/A] |

## 42. Conflitos de interesse e impedimentos

| Pessoa/papel | Situação | Objeto afetado | Medida de proteção | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- |
| [Preencher/Nenhum identificado] | [Preencher] | [ID/decisão] | [Abstenção, revisão independente ou outra] | [Nome/papel] | [Aberta/tratada] |

## 43. Plano de trabalho — referência

| Campo | Registro |
| --- | --- |
| Fonte oficial | [Link para PLA-ARQ-AAAA-NNN] |
| Versão | [Preencher] |
| Estado | [Preencher] |
| Horizonte | [Datas] |
| Marco vigente | [Preencher] |
| Desvio material | [ID/síntese/Nenhum] |
| Responsável pela atualização | [Nome/papel] |
| Próxima revisão | [Data/evento] |

## 44. Portões de controle

| Gate | Pergunta | Evidência mínima | Resultado vigente | Data | Autoridade |
| --- | --- | --- | --- | --- | --- |
| PC-1 — Entrada | Existe base suficiente para abrir? | Aceite e condições | [Não avaliado, aprovado, condicionado ou não aprovado] | [Data] | [Nome/papel] |
| PC-2 — Direção | Problema, decisão, escopo e requisitos orientam o desenho? | Termo, plano e catálogo | [Resultado] | [Data] | [Nome/papel] |
| PC-3 — Integração | Existe configuração coerente e comparável? | Alternativas e arquitetura integrada | [Resultado] | [Data] | [Nome/papel] |
| PC-4 — Aprovação | A arquitetura validada pode formar linha de base? | Validação, decisão e manifesto LB | [Resultado] | [Data] | [Nome/papel] |
| PC-5 — Transição | O Módulo 4 recebeu e aceitou o pacote? | Transição e aceite | [Resultado] | [Data] | [Nome/papel] |

## 45. Histórico dos gates

| Gate | Ciclo | Data | Resultado | Condições | Evidência | Autoridade | Próxima ação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PC-N | [N] | [DD/MM/AAAA] | [Aprovado, condicionado ou não aprovado] | [IDs/Nenhuma] | [ID/link] | [Nome/papel] | [Preencher] |

## 46. Manifesto dos artefatos

| Artefato | ID | Versão | Estado | Fonte oficial | Responsável | Aplicabilidade | Linha de base |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Termo de Abertura | TER-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Plano de Arquitetura | PLA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Catálogo de Requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Matriz de Rastreabilidade | MTR-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Avaliação de Alternativas | AVA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Arquitetura Integrada | ARQ-INT-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Registro de Validação | VAL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Relatório de Arquitetura | REL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Transição para Implantação | TRA-IMP-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |
| Retrospectiva | RET-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Nome/papel] | [Aplicável/combinado/N/A] | [LB/N/A] |

## 47. Mapa de fontes e precedência

| Objeto | Fonte oficial | Derivações autorizadas | Regra de precedência | Última verificação |
| --- | --- | --- | --- | --- |
| [Objeto/ID] | [Link] | [Índice, relatório, exportação ou outra] | [Preencher] | [Data/responsável] |

Se uma fonte estiver externa ao repositório, registre proprietário, versão, condição de acesso e cópia de preservação autorizada, quando aplicável.

## 48. Origem dos templates

| Artefato real | Template | Versão de origem | Data da cópia | Adaptação material | Decisão/responsável |
| --- | --- | --- | --- | --- | --- |
| [ID/link] | [Nome do template] | [Versão] | [DD/MM/AAAA] | [Preencher/Nenhuma] | [ID/nome] |

Mudanças posteriores no template não alteram automaticamente a cópia do projeto.

## 49. Termo de Abertura

| Campo | Registro |
| --- | --- |
| ID e versão | [TER-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Autoridade de abertura | [Nome/papel] |
| Data | [DD/MM/AAAA] |
| Condições | [IDs/Nenhuma] |
| Divergências com este manifesto | [IDs/Nenhuma] |

## 50. Plano de Arquitetura

| Campo | Registro |
| --- | --- |
| ID e versão | [PLA-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Marcos vigentes | [Síntese/IDs] |
| Participação crítica | [Síntese] |
| Desvio atual | [ID/síntese/Nenhum] |
| Próxima revisão | [Data/evento] |

## 51. Catálogo de Requisitos

| Campo | Registro |
| --- | --- |
| ID e versão | [CAT-REQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Requisitos impeditivos | [IDs/Nenhum] |
| Requisitos condicionados | [IDs/Nenhum] |
| Última decisão material | [ID/data] |
| Responsável | [Nome/papel] |

## 52. Matriz de Rastreabilidade

| Campo | Registro |
| --- | --- |
| ID e versão | [MTR-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Cobertura declarada | [Objetos relacionados] |
| Vínculos órfãos | [N/IDs/Nenhum] |
| Divergências | [N/IDs/Nenhuma] |
| Última verificação | [Data/responsável] |

## 53. Avaliação de Alternativas

| Campo | Registro |
| --- | --- |
| ID e versão | [AVA-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Alternativas examinadas | [IDs] |
| Alternativa recomendada | [ID/N/A] |
| Critérios determinantes | [IDs] |
| Decisão associada | [DEC-AAAA-NNN/N/A] |
| Alternativas preservadas | [IDs/motivo] |

## 54. Desenhos dimensionais

| Dimensão | Aplicabilidade | ID/versão | Fonte oficial | Estado | Questão material aberta |
| --- | --- | --- | --- | --- | --- |
| Estado atual e futuro | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Processos e fluxos | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Papéis, responsabilidades e alçadas | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Informação e conhecimento | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Comunicação | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Documentação | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Indicadores | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Tecnologia e integrações | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |
| Inteligência artificial | [Aplicável/N/A] | [ID/versão] | [Link] | [Estado] | [ID/síntese/Nenhuma] |

## 55. Arquitetura Integrada

| Campo | Registro |
| --- | --- |
| ID e versão | [ARQ-INT-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Rascunho, candidata, validada, aprovada ou substituída] |
| Alternativa de origem | [ID] |
| Tese da configuração | [Síntese] |
| Decisão relacionada | [DEC-AAAA-NNN/N/A] |
| Condições abertas | [IDs/Nenhuma] |
| Linha de base | [LB-ARQ-NNN/N/A] |
| Responsável | [Nome/papel] |

## 56. Registro de Validação

| Campo | Registro |
| --- | --- |
| ID e versão | [VAL-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Objeto e versão examinados | [IDs/versões] |
| Método | [Preencher] |
| Resultado | [Validada, validada com condições ou não validada] |
| Apontamentos impeditivos | [IDs/Nenhum] |
| Tratamentos abertos | [IDs/Nenhum] |
| Próximo ciclo | [ID/data/N/A] |

## 57. Relatório de Arquitetura

| Campo | Registro |
| --- | --- |
| ID e versão | [REL-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preencher] |
| Público autorizado | [Papéis/grupos] |
| Linha de base comunicada | [LB/versão/N/A] |
| Decisão principal | [ID] |
| Data de emissão | [DD/MM/AAAA] |

O relatório comunica a arquitetura; não substitui o dossiê nem altera sua linha de base.

## 58. Transição para Implantação

| Campo | Registro |
| --- | --- |
| ID e versão | [TRA-IMP-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Preparação, enviada, recebida, aceita, aceita com condições ou devolvida] |
| Linha de base transferida | [LB/versão] |
| Responsável no Módulo 3 | [Nome/papel] |
| Responsável no Módulo 4 | [Nome/papel] |
| Data de envio | [DD/MM/AAAA] |
| Data de aceite | [DD/MM/AAAA/N/A] |
| Condições | [IDs/Nenhuma] |

## 59. Retrospectiva da Arquitetura

| Campo | Registro |
| --- | --- |
| ID e versão | [RET-ARQ-AAAA-NNN — versão] |
| Fonte oficial | [Link] |
| Estado | [Planejada, em preparação, realizada ou justificada como N/A] |
| Data | [DD/MM/AAAA] |
| Aprendizagens destinadas | [IDs/síntese] |
| Mudanças propostas ao método | [IDs/Nenhuma] |
| Responsável | [Nome/papel] |

## 60. Decisões emitidas

| ID | Objeto | Decisão | Data | Autoridade | Alternativa escolhida | Condições | Fonte oficial |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DEC-AAAA-NNN | [Preencher] | [Síntese] | [DD/MM/AAAA] | [Nome/papel] | [ID/N/A] | [IDs/Nenhuma] | [Link] |

O texto integral e a fundamentação permanecem no registro de decisão do Módulo 1.

## 61. Decisões pendentes

| ID provisório | Pergunta | Autoridade | Insumos faltantes | Data/gatilho | Impacto da espera | Escalonamento |
| --- | --- | --- | --- | --- | --- | --- |
| DEC-PEND-ARQ-NNN | [Preencher] | [Nome/papel] | [IDs/síntese] | [Preencher] | [Preencher] | [Nome/papel/N/A] |

## 62. Configuração selecionada — tese

> [Sintetizar como os principais componentes funcionam juntos, que problema resolvem e sob quais condições. Não repetir a lista oficial da Arquitetura Integrada.]

| Campo | Registro |
| --- | --- |
| Alternativa selecionada | [ID] |
| Decisão | [DEC-AAAA-NNN] |
| Arquitetura integrada | [ARQ-INT/versão] |
| Resultado esperado | [Preencher] |
| Limite principal | [Preencher] |
| Condição crítica | [ID/síntese] |

## 63. Componentes — visão de governança

| ID | Componente | Função | Responsável futuro | Fonte oficial | Estado | Linha de base |
| --- | --- | --- | --- | --- | --- | --- |
| CMP-ARQ-NNN | [Preencher] | [Preencher] | [Nome/papel] | [ID/link] | [Proposto, validado, aprovado ou substituído] | [LB/N/A] |

Esta tabela é uma visão de localização. A definição completa permanece na Arquitetura Integrada.

## 64. Interfaces — visão de governança

| ID | Origem | Destino | Objeto trocado | Regra/controle | Responsável | Estado | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| INT-ARQ-NNN | [ID/unidade] | [ID/unidade] | [Informação, decisão, serviço ou outro] | [Preencher] | [Nome/papel] | [Proposta, validada ou aprovada] | [ID/link] |

## 65. Estado atual e estado futuro

| Campo | Estado atual | Estado futuro | Evidência/decisão |
| --- | --- | --- | --- |
| Configuração dominante | [Síntese] | [Síntese] | [ID/link] |
| Resultado observado/esperado | [Síntese] | [Síntese] | [ID/link] |
| Fricção principal | [Síntese] | [Tratamento] | [ID/link] |
| Continuidade preservada | [Preencher] | [Preencher] | [ID/link] |

## 66. Processos e fluxos — síntese

| Processo/fluxo | Mudança essencial | Dono futuro | Interface crítica | Indicador | Fonte |
| --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [Nome/papel] | [ID] | [ID] | [ID/link] |

## 67. Papéis, responsabilidades e alçadas — síntese

| Papel | Responsabilidade futura | Decisão/alçada | Limite | Interface | Fonte |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [ID/papel] | [ID/link] |

## 68. Informação e conhecimento — síntese

| Objeto | Finalidade | Fonte de verdade | Responsável | Acesso | Ciclo de vida | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [Sistema/documento] | [Nome/papel] | [Classe] | [Criar, usar, revisar, reter, eliminar] | [ID/link] |

## 69. Comunicação — síntese

| Evento | Emissor | Público | Mensagem/decisão | Canal | Confirmação | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Papel] | [Público] | [Preencher] | [Canal] | [Evidência] | [ID/link] |

## 70. Documentação — síntese

| Documento | Finalidade | Fonte oficial | Responsável | Aprovação | Revisão | Retenção |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [Link/sistema] | [Nome/papel] | [Regra] | [Frequência/gatilho] | [Regra] |

## 71. Indicadores e controles — síntese

| ID | Indicador/controle | Pergunta | Fórmula/regra | Fonte | Responsável | Resposta prevista |
| --- | --- | --- | --- | --- | --- | --- |
| IND/CON-ARQ-NNN | [Preencher] | [Preencher] | [Preencher] | [Sistema/registro] | [Nome/papel] | [Decisão/ação] |

## 72. Tecnologia e integrações — síntese

| Componente | Função | Integração | Dado | Responsável | Restrição | Fonte |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/nome] | [Preencher] | [ID/sistema] | [Objeto] | [Nome/papel] | [Segurança, legado, custo ou outra] | [ID/link] |

## 73. Inteligência artificial — síntese

| Papel de IA | Finalidade | Entrada autorizada | Saída | Supervisão humana | Proibição/limite | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Pesquisadora, analista, redatora, documental, gestora, revisora, financeira ou outra] | [Preencher] | [Dados/fontes] | [Preencher] | [Nome/papel/ato] | [Preencher] | [ID/link] |

Nenhuma IA recebe autoridade para aprovar arquitetura, aceitar risco, conceder acesso ou assumir autoria responsável.

## 74. Impactos e controles

| Impacto | Grupo/objeto | Natureza | Intensidade | Controle/mitigação | Responsável | Validação |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Humano, operacional, financeiro, tecnológico, informacional ou regulatório] | [Baixa/média/alta] | [ID/síntese] | [Nome/papel] | [ID/link] |

## 75. Riscos residuais e aceites

| ID | Risco residual | Exposição | Controle existente | Autoridade do aceite | Data | Validade | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RIS-ARQ-NNN | [Preencher] | [Baixa/média/alta] | [ID/síntese] | [Nome/papel] | [Data] | [Data/evento] | [DEC/link] |

Risco residual sem autoridade competente não está aceito; permanece aberto.

## 76. Condições da aprovação

| ID | Condição | Origem | Restrição | Responsável | Prazo/gatilho | Evidência de atendimento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| COND-ARQ-NNN | [Preencher] | [Gate/decisão/validação] | [Preencher] | [Nome/papel] | [Preencher] | [ID/link] | [Aberta, em tratamento, atendida, dispensada ou vencida] |

## 77. Dependências

| ID | Dependência | Tipo | Projeto/sistema | Resultado necessário | Data/gatilho | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DEP-ARQ-NNN | [Preencher] | [Entrada, decisão, recurso, componente, fornecedor ou outra] | [ID/nome] | [Preencher] | [Preencher] | [Nome/papel] | [Aberta/tratada] |

## 78. Questões abertas

| ID | Questão | Por que importa | Responsável pela resposta | Fonte necessária | Prazo | Efeito enquanto aberta |
| --- | --- | --- | --- | --- | --- | --- |
| QST-ARQ-NNN | [Preencher] | [Preencher] | [Nome/papel] | [ID/síntese] | [Data] | [Preencher] |

## 79. Exceções e desvios

| ID | Regra/referência | Exceção ou desvio | Motivo | Impacto | Autoridade | Validade | Tratamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EXC-ARQ-NNN | [ID/seção] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Data/evento] | [Regularizar, manter, substituir ou encerrar] |

## 80. Referência vigente da configuração

| Campo | Registro |
| --- | --- |
| Arquitetura integrada vigente | [ARQ-INT/versão/N/A] |
| Alternativa selecionada | [ID/N/A] |
| Decisão de aprovação | [DEC/N/A] |
| Linha de base vigente | [LB/versão/N/A] |
| Data de vigência | [DD/MM/AAAA/N/A] |
| Escopo da vigência | [Preencher/N/A] |
| Condições abertas | [IDs/Nenhuma] |
| Referência substituída | [LB/versão/N/A] |

Enquanto não houver aprovação, declare `N/A — linha de base ainda não constituída`.

## 81. Identificação da linha de base

| Campo | Registro |
| --- | --- |
| ID | `LB-ARQ-NNN` |
| Projeto | `ARQ-AAAA-NNN` |
| Versão | [Preencher] |
| Estado | [Candidata, aprovada, substituída ou encerrada] |
| Data | [DD/MM/AAAA] |
| Escopo | [Preencher] |
| Decisão de aprovação | [DEC-AAAA-NNN] |
| Aprovador | [Nome/papel] |
| Riscos aceitos | [IDs/Nenhum] |
| Condições | [IDs/Nenhuma] |
| Fonte do manifesto da LB | [Link] |

## 82. Manifesto da linha de base

| Artefato | ID | Versão exata | Estado | Fonte oficial | Incluído? | Integridade verificada? |
| --- | --- | --- | --- | --- | --- | --- |
| Termo de Abertura | TER-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Plano de Arquitetura | PLA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Catálogo de Requisitos | CAT-REQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Matriz de Rastreabilidade | MTR-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Avaliação de Alternativas | AVA-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Arquitetura Integrada | ARQ-INT-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Registro de Validação | VAL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Relatório | REL-ARQ-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |
| Transição | TRA-IMP-AAAA-NNN | [Versão] | [Estado] | [Link] | [Sim/não] | [Data/responsável] |

## 83. Histórico de linhas de base

| ID | Versão | Estado | Vigência inicial | Vigência final | Escopo | Substituída por | Decisão |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LB-ARQ-NNN | [Versão] | [Aprovada, substituída ou encerrada] | [Data] | [Data/N/A] | [Preencher] | [LB/versão/N/A] | [DEC] |

Uma arquitetura pode possuir várias linhas de base históricas, mas apenas uma referência vigente para o mesmo escopo e momento.

## 84. Histórico de versões do manifesto

| Versão | Data | Tipo | Alteração | Motivo/evidência | Autor | Revisão/aprovação |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | [DD/MM/AAAA] | Criação do manifesto real | Abertura do dossiê | [TER/entrada] | [Nome] | [Nome/N/A] |

## 85. Registro de mudanças materiais

| ID | Data | Objeto/versão de origem | Mudança | Motivo | Impacto | Decisão | Nova referência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MUD-ARQ-NNN | [Data] | [ID/versão] | [Preencher] | [ID/evidência] | [Requisitos, componentes, interfaces, riscos, validação, implantação] | [DEC] | [ID/versão] |

## 86. Divergências entre fontes

| ID | Objeto | Fonte A | Fonte B | Divergência | Autoridade correta | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DIV-ARQ-NNN | [ID/campo] | [Link/valor] | [Link/valor] | [Preencher] | [Fonte/papel] | [Corrigir, decidir ou suspender uso] | [Aberta/tratada] |

## 87. Revisões do dossiê

| ID | Data de corte | Escopo | Responsáveis | Links | Versões | Acessos | Pendências | Resultado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| REV-ARQ-NNN | [Data] | [Integral, pré-gate, acesso ou outro] | [Nomes/papéis] | [Íntegros/falhas] | [Íntegras/falhas] | [Adequados/falhas] | [IDs] | [Conforme, condicionado ou não conforme] |

## 88. Aprovação da arquitetura

| Campo | Registro |
| --- | --- |
| Resultado | [Aprovada, aprovada com condições ou não aprovada] |
| Objeto e versão | [ARQ-INT/versão] |
| Linha de base | [LB/versão/N/A] |
| Data | [DD/MM/AAAA] |
| Autoridade | [Nome/papel] |
| Decisão | [DEC-AAAA-NNN] |
| Condições | [IDs/Nenhuma] |
| Riscos aceitos | [IDs/Nenhum] |
| Vigência | [Data/evento] |

## 89. Preparação da transição ao Módulo 4

| Item | Referência | Responsável M3 | Responsável M4 | Pronto? | Condição |
| --- | --- | --- | --- | --- | --- |
| Linha de base | [LB/versão] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Escopo de implantação | [ID/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Itens de trabalho | [IDs/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Dependências e riscos | [IDs/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Critérios de aceite | [IDs/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Conhecimento e treinamento | [IDs/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |
| Governança de mudança | [ID/link] | [Nome/papel] | [Nome/papel] | [Sim/não] | [ID/N/A] |

## 90. Recebimento e aceite pelo Módulo 4

| Campo | Registro |
| --- | --- |
| Data de envio | [DD/MM/AAAA] |
| Data de recebimento | [DD/MM/AAAA] |
| Resultado | [Aceita, aceita com condições ou devolvida] |
| Responsável pelo aceite | [Nome/papel] |
| Condições de implantação | [IDs/Nenhuma] |
| Pendências retidas no Módulo 3 | [IDs/Nenhuma] |
| Evidência | [TRA/link] |
| Resultado do PC-5 | [Aprovado, condicionado ou não aprovado] |

Aceite da passagem não transfere silenciosamente autoria, risco ou pendência.

## 91. Relação com o Módulo 5 — Operação

| Objeto a observar | Indicador/sinal | Limite esperado | Responsável operacional | Gatilho de retorno ao Módulo 3 | Fonte |
| --- | --- | --- | --- | --- | --- |
| [Componente/capacidade] | [ID/métrica] | [Limiar] | [Nome/papel] | [Evento] | [ID/link] |

Mudança operacional dentro da linha de base pertence ao Módulo 5. Alteração material de requisito, componente, interface ou princípio pode exigir retorno ao Módulo 3.

## 92. Destino ao Módulo 6 — Inteligência Organizacional

| ID | Conhecimento gerado | Evidência | Grau de confiança | Reutilização possível | Responsável pela curadoria | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| APR-ARQ-NNN | [Preencher] | [IDs/links] | [Baixo/médio/alto] | [Preencher] | [Nome/papel] | [Proposto, validado, incorporado ou rejeitado] |

## 93. Destino ao Módulo 7 — Ecossistema de IA

| Necessidade/papel | Capacidade esperada | Limites | Evidência do projeto | Responsável humano | Destino |
| --- | --- | --- | --- | --- | --- |
| [Papel de IA] | [Preencher] | [Preencher] | [ID/link] | [Nome/papel] | [Backlog, experimento, padrão ou N/A] |

## 94. Destino ao Módulo 8 — Evolução

| ID | Proposta de evolução | Problema observado | Evidência | Impacto no método | Experimento/revisão | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| EVO-ARQ-NNN | [Preencher] | [Preencher] | [ID/link] | [Baixo/médio/alto] | [Preencher] | [Nome/papel] |

Uma prática bem-sucedida em um projeto é uma hipótese de evolução, não uma regra geral automática.

## 95. Matriz de acesso

| Grupo/papel | Manifesto | Artefatos de desenho | Evidências | Decisões | Linha de base | Permissão |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Sim/não] | [Sim/não/parcial] | [Sim/não/parcial] | [Sim/não] | [Sim/não] | [Ler, comentar, editar ou aprovar] |

## 96. Dados pessoais, sensíveis e confidenciais

| Categoria | Finalidade | Local autorizado | Acesso | Retenção | Proteção | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher/Nenhuma] | [Preencher] | [Link/sistema] | [Papéis] | [Regra] | [Minimização, pseudonimização, segregação ou outra] | [Nome/papel] |

Não registre credenciais, segredos ou dados excessivos neste manifesto.

## 97. Documentos externos e fornecedores

| Objeto | Proprietário | Fonte oficial | Versão/data | Condição de acesso | Dependência | Cópia de preservação |
| --- | --- | --- | --- | --- | --- | --- |
| [Documento/sistema/fornecedor] | [Nome/unidade] | [Link/referência] | [Preencher] | [Preencher] | [ID/síntese] | [Link/N/A — motivo] |

## 98. Contribuições de inteligência artificial

| Data | Sistema/papel de IA | Atividade | Entradas autorizadas | Saída utilizada | Verificação humana | Impacto material | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Data] | [Preencher] | [Pesquisa, análise, redação, organização ou revisão] | [Fontes/dados] | [ID/trecho] | [Nome/papel/método] | [Sim/não — qual] | [ID/link] |

Saída de IA sem verificação proporcional permanece material de trabalho, não evidência ou decisão.

## 99. Autoria e responsabilidade

| Objeto | Autor/contribuidores | Responsável semântico | Revisor | Aprovador | Data |
| --- | --- | --- | --- | --- | --- |
| Manifesto | [Nomes/papéis] | [Nome/papel] | [Nome/papel] | [Nome/papel/N/A] | [Data] |
| Arquitetura integrada | [Nomes/papéis] | [Nome/papel] | [Nome/papel] | [Nome/papel] | [Data] |
| Linha de base | [Nomes/papéis] | [Nome/papel] | [Nome/papel] | [Nome/papel] | [Data] |

Autoria assistida não reduz a responsabilidade de quem verifica, decide e aprova.

## 100. Retenção, portabilidade e recuperação

| Campo | Registro |
| --- | --- |
| Regra de retenção | [Preencher] |
| Autoridade da regra | [ID/norma/papel] |
| Formatos portáveis | [Markdown, PDF, CSV ou outros] |
| Dependências de ferramenta | [Preencher/Nenhuma] |
| Cópia de preservação | [Local/rotina] |
| Último teste de recuperação | [Data/resultado] |
| Custodiante histórico | [Nome/papel] |
| Próxima revisão | [Data/evento] |

## 101. Suspensão

Preencher quando o estado for `Suspensa`.

| Campo | Registro |
| --- | --- |
| Data | [DD/MM/AAAA] |
| Motivo | [Preencher] |
| Autoridade | [Nome/papel/decisão] |
| Última referência válida | [ID/versão] |
| Risco durante a suspensão | [IDs/síntese] |
| Guardião | [Nome/papel] |
| Gatilho de retomada | [Evento observável] |
| Data de revisão | [DD/MM/AAAA] |

## 102. Cancelamento

Preencher quando o estado for `Cancelada`.

| Campo | Registro |
| --- | --- |
| Data | [DD/MM/AAAA] |
| Motivo | [Preencher] |
| Autoridade | [Nome/papel/decisão] |
| Última versão válida | [ID/versão/N/A] |
| Ativos reutilizáveis | [IDs/Nenhum] |
| Pendências encerradas ou transferidas | [IDs/destino] |
| Destino dos registros | [Arquivar/reter/eliminar conforme regra] |
| Comunicação | [ID/link] |

## 103. Reabertura

Preencher quando o estado for `Reaberta`.

| Campo | Registro |
| --- | --- |
| Data | [DD/MM/AAAA] |
| Gatilho/evidência | [ID/link] |
| Autoridade | [Nome/papel/decisão] |
| Linha de base anterior | [LB/versão/N/A] |
| Escopo reaberto | [Preencher] |
| Etapa retomada | [Entrada, requisitos, desenho, integração, validação ou outra] |
| Artefatos impactados | [IDs] |
| Próximo gate | [PC-N] |
| Mesmo ID justificado por | [Preencher] |

Crie novo projeto quando o objeto, a autoridade ou a transformação forem materialmente diferentes.

## 104. Substituição

Preencher quando o estado for `Substituída`.

| Campo | Registro |
| --- | --- |
| Arquitetura substituta | [ARQ-AAAA-NNN] |
| Linha de base substituta | [LB/versão] |
| Data de vigência | [DD/MM/AAAA] |
| Decisão | [DEC-AAAA-NNN] |
| Escopo substituído | [Preencher] |
| Partes ainda vigentes | [IDs/Nenhuma] |
| Pendências transferidas | [IDs/Nenhuma] |
| Comunicação | [ID/link] |

## 105. Encerramento

| Campo | Registro |
| --- | --- |
| Tipo | [Regular ou antecipado] |
| Data | [DD/MM/AAAA] |
| Autoridade | [Nome/papel/decisão] |
| Referência final | [LB/versão ou última versão válida] |
| Resultado do PC-5 | [Aprovado, condicionado, não aprovado ou N/A] |
| Pendências e destino | [IDs/destinos/Nenhuma] |
| Retrospectiva | [RET/versão/N/A — motivo] |
| Conhecimento transferido | [IDs/Nenhum] |
| Custodiante | [Nome/papel] |
| Revisão futura | [Data/evento/N/A] |

Encerrar não significa apagar. O dossiê permanece localizável conforme acesso e retenção.

## 106. Relações com outras arquiteturas

| Origem | Relação | Destino | Motivo | Decisão/evidência | Impacto | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| ARQ-AAAA-NNN | [deriva_de, complementa, depende_de, substitui, é_substituída_por, reabre ou compartilha_componente_com] | ARQ-AAAA-NNN | [Preencher] | [ID/link] | [Preencher] | [Proposta, aprovada ou encerrada] |

| Componente compartilhado | Fonte governante | Projetos afetados | Responsável | Consulta obrigatória | Regra de mudança |
| --- | --- | --- | --- | --- | --- |
| [ID/nome] | [ARQ/LB/artefato] | [ARQ IDs] | [Nome/papel] | [Papéis/projetos] | [Preencher] |

## 107. Rotas de leitura

| Necessidade | Começar por | Seguir para | Público |
| --- | --- | --- | --- |
| Compreender rapidamente | Seções 11, 16, 19, 62 e 80 | Relatório e Arquitetura Integrada | Liderança/autorizados |
| Tomar decisão | Seções 25, 34, 53, 60, 61, 75 e 76 | Avaliação, evidências e registros DEC | Decisor |
| Revisar coerência | Seções 46, 47, 52, 54, 55 e 86 | Matriz e fontes oficiais | Revisor |
| Validar | Seções 55, 56, 74 e 75 | Registro de Validação | Validador |
| Implantar | Seções 80–82 e 89–90 | Transição e linha de base | Módulo 4 |
| Operar e medir | Seções 71, 74 e 91 | Arquitetura Integrada e Módulo 5 | Operação |
| Aprender e evoluir | Seções 59 e 92–94 | Retrospectiva e Módulos 6–8 | Curadoria |
| Auditar o ciclo | Seções 17, 44–48, 60, 81–88 e 99 | Evidências e decisões | Auditoria autorizada |

## 108. Resumo executivo e fotografia vigente

### 108.1 Resumo executivo

> [Em até cinco parágrafos: contexto; problema; configuração escolhida; evidências e limites; decisão/próximo movimento.]

### 108.2 Fotografia vigente

| Pergunta | Resposta |
| --- | --- |
| Em que estado estamos? | [Estado/data] |
| Qual gate foi alcançado? | [PC/resultado/data] |
| Qual referência está vigente? | [ARQ-INT e LB/versões/N/A] |
| Que decisão está pendente? | [ID/síntese/Nenhuma] |
| Que condição limita o avanço? | [IDs/Nenhuma] |
| Qual é a próxima ação? | [Ação/responsável/prazo] |
| O que mudou desde a última atualização? | [Evento/ID] |
| Onde está a principal fonte? | [Link] |

### 108.3 Declaração de integridade

| Verificação | Resultado | Data | Responsável |
| --- | --- | --- | --- |
| Manifesto e índice estão sincronizados | [Sim/não] | [Data] | [Nome/papel] |
| Links materiais resolvem | [Sim/não/condições] | [Data] | [Nome/papel] |
| Uma única linha de base está vigente por escopo | [Sim/não/N/A] | [Data] | [Nome/papel] |
| Condições abertas possuem responsável | [Sim/não] | [Data] | [Nome/papel] |
| Acesso corresponde à autorização | [Sim/não] | [Data] | [Nome/papel] |

## 109. Checklists de controle

### 109.1 Abertura

- [ ] ID reservado e não duplicado;
- [ ] pasta e manifesto criados;
- [ ] cópia identificada com versão do modelo;
- [ ] origem e entrada registradas;
- [ ] acesso classificado;
- [ ] responsável e próxima ação atribuídos;
- [ ] linha incluída no índice;
- [ ] aceite e PC-1 registrados.

### 109.2 Direção e integração

- [ ] problema e decisão estão formulados;
- [ ] escopo, não objetivos e interfaces estão claros;
- [ ] requisitos e critérios possuem fonte;
- [ ] alternativas materiais foram comparadas;
- [ ] desenhos aplicáveis foram produzidos;
- [ ] configuração integrada é coerente;
- [ ] rastreabilidade cobre relações materiais;
- [ ] PC-2 e PC-3 possuem resultado.

### 109.3 Aprovação e linha de base

- [ ] objeto e versão validados estão inequívocos;
- [ ] apontamentos impeditivos foram tratados;
- [ ] decisão foi emitida por autoridade competente;
- [ ] riscos aceitos possuem autoridade;
- [ ] condições possuem responsável e prazo/gatilho;
- [ ] manifesto da linha de base resolve versões exatas;
- [ ] uma única referência está declarada vigente;
- [ ] PC-4 foi registrado;
- [ ] índice foi atualizado.

### 109.4 Transição

- [ ] pacote usa a linha de base aprovada;
- [ ] escopo e itens de implantação estão identificados;
- [ ] dependências, riscos e condições acompanham o pacote;
- [ ] critérios de aceite estão explícitos;
- [ ] responsáveis dos Módulos 3 e 4 estão nomeados;
- [ ] recebimento e aceite foram registrados;
- [ ] pendências retidas possuem dono;
- [ ] PC-5 foi registrado.

### 109.5 Checklist de encerramento

- [ ] referência final está identificada;
- [ ] pendências receberam destino;
- [ ] retrospectiva foi realizada ou justificada;
- [ ] aprendizagem foi encaminhada;
- [ ] mudanças do método foram propostas, não presumidas;
- [ ] retenção, acesso e custódia estão definidos;
- [ ] índice apresenta estado final;
- [ ] recuperação futura é possível.

## 110. Qualidade, conclusão e princípio de encerramento

### 110.1 Antipadrões

Evite:

- preencher o modelo permanente com dados reais;
- transformar este manifesto em relatório duplicado;
- registrar estado sem evidência ou data;
- declarar linha de base sem versões exatas;
- manter projeto ativo sem próxima ação;
- copiar todos os templates por aparência de completude;
- apagar versões, alternativas ou condições substituídas;
- guardar segredos ou dados excessivos;
- usar IA como fonte não verificada ou autoridade;
- encerrar sem destino para pendências e aprendizagem.

### 110.2 Sinais de qualidade

Um bom manifesto:

- pode ser compreendido em poucos minutos;
- leva às fontes oficiais em poucos passos;
- distingue estado, atenção, prioridade e atualidade;
- torna decisão, condição e responsabilidade observáveis;
- preserva uma referência vigente e um histórico íntegro;
- permite passagem ao próximo módulo sem reconstrução informal;
- permanece utilizável mesmo com troca de pessoas e ferramentas;
- contém a menor síntese capaz de governar o dossiê.

### 110.3 Critérios de conclusão

- [ ] todas as seções materiais foram preenchidas ou justificadas como N/A;
- [ ] identidade, pasta e índice correspondem;
- [ ] estado vigente é único;
- [ ] próxima ação ou encerramento está explícito;
- [ ] fontes e versões são resolvíveis;
- [ ] linha de base está correta ou declarada inexistente;
- [ ] divergências estão tratadas;
- [ ] acesso, autoria e custódia estão definidos;
- [ ] transição ou destino final possui evidência;
- [ ] histórico permite reconstruir o ciclo.

### 110.4 Princípio de encerramento

O manifesto não existe para concentrar todos os conteúdos da arquitetura. Existe para manter sua identidade, autoridade, vigência e inteligibilidade.

Quando cumpre sua função, qualquer pessoa autorizada consegue distinguir o que é fato, decisão, hipótese, condição, versão e próxima ação; localizar a fonte correta; reconhecer os limites da configuração; e continuar o trabalho sem depender da memória de quem o iniciou.

No Estúdio LICHTARA, o dossiê preserva a arquitetura e o manifesto preserva o caminho para compreendê-la.

---

## Registro final

**Diretório do projeto:** `modulos/modulo-03-arquitetura-organizacional/registros-de-arquitetura/AAAA/ARQ-AAAA-NNN-nome-curto/`  
**Documento no projeto real:** `README.md`  
**Projeto:** `ARQ-AAAA-NNN`  
**Versão do manifesto:** [Preencher]  
**Versão do modelo de origem:** 0.1  
**Estado vigente:** [Selecionar]  
**Linha de base vigente:** [LB/versão ou N/A — ainda não constituída]  
**Responsável:** [Nome/papel]  
**Última atualização material:** [DD/MM/AAAA — evento]  
**Próxima ação ou condição de encerramento:** [Preencher]  
**Observações:** [Preencher/Nenhuma]

