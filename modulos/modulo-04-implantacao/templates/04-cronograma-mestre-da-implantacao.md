# Cronograma Mestre da Implantação

**Identificação técnica no repositório**

```yaml
id_cronograma: CRM-IMP-AAAA-NNN
id_implantacao: IMP-AAAA-NNN
titulo: "[Nome claro e específico da implantação — Cronograma Mestre]"
organizacao:
area_ou_contexto:
id_termo_de_abertura: TER-IMP-AAAA-NNN
versao_termo_de_abertura:
id_plano_de_implantacao: PLA-IMP-AAAA-NNN
versao_plano_de_implantacao:
id_estrutura_analitica: EAI-IMP-AAAA-NNN
versao_estrutura_analitica:
id_linha_de_base_arquitetural: LB-ARQ-NNN
versao_linha_de_base_arquitetural:
id_linha_de_base_temporal: IMP-AAAA-NNN-LBT-NNN
data_de_status: AAAA-MM-DD
fuso_horario: "[Identificador IANA]"
responsavel_pela_implantacao:
responsavel_pelo_cronograma:
autoridade_da_implantacao:
custodiante_do_cronograma:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
inicio_planejado:
conclusao_planejada:
estado_do_cronograma: em_elaboracao
classificacao_da_implantacao: focal | funcional | sistemica
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 4 — Implantação  
**Tipo:** Template operacional  
**Função:** Organização dos compromissos temporais, marcos, janelas, dependências, caminho crítico, reservas e ocorrências previstas de gate da implantação  
**Documentos de referência:** Fundamentos da Implantação; Protocolo de Implantação; Matriz de Rastreabilidade da Implantação  
**Documentos de entrada:** Termo de Abertura, Plano de Implantação e Estrutura Analítica da Implantação vigentes  
**Documento seguinte na ordem de construção:** `templates/05-backlog-e-quadro-kanban-da-implantacao.md`  
**Ponto de controle relacionado:** PI-2 — Prontidão para executar

---

## 1. Finalidade

Este template transforma a estrutura de realização aprovada em uma representação temporal governável da implantação.

Sua finalidade é tornar demonstrável:

- quando cada unidade precisa estar disponível, iniciar, terminar ou alcançar condição específica;
- que relações de precedência, coexistência, decisão e disponibilidade limitam a sequência;
- quais marcos representam condições observáveis, e não apenas datas escolhidas;
- quais janelas possuem início, encerramento, pré-condições e consequência de perda;
- que objetos formam o caminho crítico ou quase crítico;
- onde existem folgas, reservas e margens autorizadas;
- que compromissos dependem de pessoas, fornecedores, ambientes, dados, documentos, decisões ou gates;
- como preparação humana, técnica e operacional se integra ao tempo da implantação;
- que variações ocorreram em relação à linha de base temporal;
- quando replanejar, escalar, suspender, renegociar ou retornar ao Módulo 3;
- quais efeitos um atraso produz sobre risco, custo, capacidade, segurança, adoção, estabilização e transição;
- que evidência sustenta a afirmação de prontidão temporal para o `PI-2`.

O cronograma organiza compromissos temporais. Ele não substitui a Estrutura Analítica, o backlog, o quadro Kanban, a matriz de rastreabilidade, os registros de risco e mudança, a verificação de prontidão ou a decisão de gate.

---

## 2. Pergunta central

> Como organizar no tempo a realização da arquitetura autorizada, preservando dependências, capacidade real, segurança, aprendizagem, reversibilidade e autoridade, sem transformar datas em evidência de avanço ou licença para executar?

Um cronograma é suficiente quando permite reconstruir:

1. de que objetos o compromisso temporal deriva;
2. que lógica sustenta sua posição no tempo;
3. que condição define cada marco;
4. que restrição ou premissa influencia cada previsão;
5. quem responde por dependências e decisões;
6. como a previsão vigente difere da linha de base;
7. que consequência acompanha atraso, antecipação ou perda de janela;
8. que gate ainda precisa autorizar o movimento correspondente.

---

## 3. Posição no protocolo

Este documento materializa a Etapa 12 do Protocolo de Implantação — construir cronograma, marcos e dependências — e recebe da Estrutura Analítica as unidades que deverão ser temporalmente organizadas.

```text
Linha de base arquitetural autorizada
  → Termo de Abertura aprovado
  → Plano de Implantação vigente
  → Estrutura Analítica suficientemente elaborada
  → Cronograma Mestre da Implantação
  → Backlog, Kanban e planos especializados sincronizados
  → Verificação de prontidão
  → PI-2
```

Depois do `PI-2`, o cronograma continua vigente como fonte temporal. Ele recebe datas reais, revisões de previsão, ocorrências de gate, variações, suspensões, liberações, estabilização e transição. O documento não se encerra quando a execução começa.

---

## 4. Distinções que este template preserva

| Elemento | Pergunta principal | Fonte oficial |
| --- | --- | --- |
| Plano de Implantação | Como a implantação será integrada e governada? | `templates/02-plano-de-implantacao.md` |
| Estrutura Analítica | O que compõe a realização? | `templates/03-estrutura-analitica-da-implantacao.md` |
| Cronograma Mestre | Quando e em que sequência os compromissos temporais deverão ocorrer? | Este documento |
| Backlog e Kanban | Que trabalho atravessa o fluxo real e em que estado está? | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` |
| Matriz de Rastreabilidade | Que vínculos conectam origem, realização, evidência, decisão e configuração? | `templates/06-matriz-de-rastreabilidade-da-implantacao.md` |
| Registro integrado | Que riscos, impedimentos, dependências e mudanças exigem tratamento? | `templates/07-registro-de-riscos-impedimentos-dependencias-e-mudancas.md` |
| Verificação de prontidão | As condições necessárias foram demonstradas? | `templates/13-verificacao-de-prontidao.md` |
| Registro de gate | Que autoridade decidiu sobre qual objeto, com que evidência e efeito? | Registro decisório aplicável |

### 4.1 Cronograma não é Estrutura Analítica

A Estrutura Analítica representa composição e pertencimento. O cronograma representa sequência, duração, marcos, janelas e compromissos. A posição de um nó na árvore não define automaticamente sua posição no tempo.

### 4.2 Cronograma não é backlog

O cronograma mantém compromissos temporais e lógica de rede. O backlog organiza demanda e prioridade. O Kanban mostra fluxo e bloqueios reais. Um item pode estar atrasado no cronograma e bloqueado no Kanban; as duas informações são complementares.

### 4.3 Data prevista não é autorização

Uma data de início, liberação, aceite ou transição é uma previsão. O movimento depende do gate, decisão, evidência ou condição aplicável. O calendário não aprova o objeto.

### 4.4 Marco não é atividade

Marco representa uma condição verificável com duração nula ou não material. Atividade consome tempo, capacidade ou recursos para produzir uma saída. “Treinamento concluído” só é marco válido quando declara a condição observável que o sustenta.

### 4.5 Duração não é esforço

Duração é o tempo de calendário ou de trabalho entre início e término. Esforço é a quantidade de trabalho humano ou computacional necessária. Oito horas de esforço podem ocupar um dia ou várias semanas, conforme capacidade, dependências e calendário.

### 4.6 Restrição não é compromisso livremente assumido

Data imposta por norma, contrato, evento externo, indisponibilidade ou obrigação deve ser registrada como restrição com origem, negociabilidade e consequência. Ela não pode ser apresentada como estimativa produzida pela equipe.

### 4.7 Linha de base não é previsão vigente

A linha de base temporal preserva o compromisso aprovado para comparação. A previsão vigente incorpora fatos conhecidos. Quando a previsão muda, a linha de base permanece recuperável até que uma alteração autorizada estabeleça nova base.

### 4.8 Progresso temporal não é capacidade implantada

Tempo decorrido, percentual informado ou atividade terminada não demonstram que uma entrega foi integrada, uma competência foi adquirida, uma capacidade foi validada ou uma configuração foi aceita.

---

## 5. Natureza do documento

O Cronograma Mestre é, simultaneamente:

- **integrador**, porque relaciona projetos, ondas, incrementos, pacotes, planos humanos, preparação técnica, gates, estabilização e transição;
- **relacional**, porque cada posição temporal deriva de dependências, restrições, calendários e capacidade;
- **versionado**, porque separa linha de base, previsão vigente e realização observada;
- **progressivamente elaborado**, porque o horizonte próximo recebe detalhe maior que horizontes incertos;
- **condicional**, porque datas dependem de premissas, decisões e evidências;
- **responsável**, porque torna consequências de atraso e compressão visíveis;
- **não autorizativo**, porque não substitui decisão humana ou gate;
- **rastreável**, porque cada elemento temporal referencia objetos oficiais.

O cronograma pode existir como tabela Markdown, planilha, sistema de gestão de projetos ou combinação governada. A ferramenta escolhida deve permitir exportação, preservação de versões e reconstrução por pessoa autorizada.

---

## 6. Autoridade e limites

### 6.1 O cronograma pode

- sequenciar trabalho dentro do envelope arquitetural aprovado;
- detalhar datas, durações e dependências executivas;
- propor paralelismo quando as relações materiais forem preservadas;
- registrar estimativas, intervalos e níveis de confiança;
- alocar folgas e reservas autorizadas;
- produzir cenários de antecipação, atraso ou restrição de capacidade;
- revisar previsões diante de fatos;
- recomendar renegociação, repriorização, suspensão ou escalonamento;
- revelar incompatibilidade entre prazo e preparação necessária;
- informar decisões de `PI-2`, `PI-3`, `PI-4` e `PI-5`.

### 6.2 O cronograma não pode

- alterar requisito, componente, interface, alçada ou princípio arquitetural;
- reduzir critério de prontidão, validação, aceite ou estabilização para cumprir data;
- considerar entrega concluída apenas porque o período terminou;
- transformar indisponibilidade de recurso em trabalho presumidamente executado;
- antecipar liberação sem decisão de `PI-3`;
- presumir aceite em data marcada para `PI-4`;
- transferir responsabilidade operacional por decurso de prazo;
- absorver mudança material como simples replanejamento;
- ocultar atraso por mudança retroativa da linha de base;
- atribuir decisão, aceite de risco ou autoridade à inteligência artificial.

### 6.3 Autonomia de replanejamento

| Tipo de ajuste | Exemplo | Alçada mínima | Registro |
| --- | --- | --- | --- |
| Editorial | Correção de nome ou link sem efeito temporal. | Custodiante | Histórico simples |
| Atualização factual | Inclusão de data real ou estado confirmado. | Responsável pelo cronograma | Versão ou log |
| Ajuste executivo | Sequência ou duração alterada dentro de tolerância aprovada. | Responsável pela implantação | Análise de impacto e previsão vigente |
| Mudança da linha de base temporal | Alteração de marco, janela ou conclusão comprometida. | Autoridade definida no plano | Decisão e nova linha de base |
| Mudança arquitetural | Alteração temporal exige mudar requisito, interface, alçada, risco ou desenho material. | Retorno ao Módulo 3 | Registro de mudança arquitetural |

---

## 7. Instruções de uso

1. Duplique este arquivo para cada implantação real.
2. Não preencha diretamente o template-mestre.
3. Armazene a cópia no dossiê de `IMP-AAAA-NNN`.
4. Preserve os IDs e as versões dos objetos recebidos.
5. Crie elemento temporal somente quando ele representar relação, compromisso ou condição distinta.
6. Utilize datas no formato `AAAA-MM-DD` e declare horário e fuso quando material.
7. Registre calendários de trabalho, exceções e indisponibilidades antes de calcular duração.
8. Diferencie estimativa, restrição, compromisso aprovado, previsão vigente e data real.
9. Registre dependência externa com responsável, limite e resposta.
10. Vincule todo marco a condição observável, autoridade e evidência prevista.
11. Não use percentual como único indicador de progresso.
12. Preserve a linha de base anterior ao replanejar.
13. Sincronize cronograma, backlog, matriz e registro integrado na cadência definida.
14. Submeta compressão, atraso ou alteração material à autoridade competente.
15. Retorne ao Módulo 3 quando a solução temporal exigir mudança arquitetural.
16. Use a versão reduzida somente quando os controles materiais permanecerem presentes.

### 7.1 Convenções de preenchimento

| Convenção | Significado |
| --- | --- |
| [Preencher] | Registro necessário. |
| Não aplicável | O campo foi examinado e não pertence ao objeto. |
| Não determinado | A informação ainda não pode ser estabelecida. |
| Pendente | Existe tratamento, responsável e limite. |
| A confirmar | Há indicação inicial que exige verificação. |
| Nenhuma | O conjunto foi examinado e está vazio. |
| ID/versão | Referência exata ao objeto e à versão. |
| Data/condição | Data definida ou condição observável que determina o evento. |
| Intervalo | Estimativa mínima, mais provável e máxima, ou faixa equivalente. |
| Link/caminho | Localização recuperável por pessoa autorizada. |

### 7.2 Regra de concisão rastreável

O cronograma registra referência temporal suficiente para governar compromissos. O detalhe de conteúdo permanece em sua fonte oficial.

Para cada elemento derivado:

- preserve o ID canônico;
- registre a versão aplicável;
- indique a origem;
- declare o calendário e a lógica temporal;
- atribua responsável;
- evite copiar especificações completas.

---

## 8. Identificação do cronograma

| Campo | Registro |
| --- | --- |
| ID do cronograma | `CRM-IMP-AAAA-NNN` |
| ID da implantação | `IMP-AAAA-NNN` |
| Título | [Preencher] |
| Organização | [Preencher] |
| Área ou contexto | [Preencher] |
| Classificação | Focal / funcional / sistêmica |
| Responsável pela implantação | [Nome/papel] |
| Responsável pelo cronograma | [Nome/papel] |
| Autoridade da implantação | [Nome/papel] |
| Custodiante | [Nome/papel] |
| Ferramenta oficial | [Nome/sistema ou Markdown] |
| Localização oficial | [Caminho/link] |
| Fuso horário principal | [Identificador IANA] |
| Data de status | [AAAA-MM-DD e hora, se material] |
| Início do horizonte | [AAAA-MM-DD/condição] |
| Fim do horizonte | [AAAA-MM-DD/condição] |
| Versão | [N.N] |
| Estado | [Vocabulário da seção 9] |
| Sensibilidade | Pública / interna / confidencial / sensível |
| Data de criação | [AAAA-MM-DD] |
| Última revisão | [AAAA-MM-DD] |
| Próxima revisão | [Data/evento/gate] |

### 8.1 Identificadores relacionados

| Objeto | ID/versão | Fonte oficial | Estado |
| --- | --- | --- | --- |
| Linha de base arquitetural | [ID/versão] | [Caminho] | [Estado] |
| Termo de Abertura | [ID/versão] | [Caminho] | [Estado] |
| Plano de Implantação | [ID/versão] | [Caminho] | [Estado] |
| Estrutura Analítica | [ID/versão] | [Caminho] | [Estado] |
| Linha de base temporal | [ID/versão] | [Caminho] | [Estado] |
| Ocorrência prevista de PI-2 | [ID ou a criar] | [Caminho] | [Estado] |

---

## 9. Estado do cronograma

Selecione um único estado principal vigente.

- [ ] Em elaboração
- [ ] Em revisão
- [ ] Aprovado para orientar preparação
- [ ] Vigente
- [ ] Vigente com condições
- [ ] Em replanejamento controlado
- [ ] Suspenso
- [ ] Substituído
- [ ] Encerrado
- [ ] Cancelado

| Estado | Significado mínimo |
| --- | --- |
| Em elaboração | A rede, as estimativas ou os compromissos ainda estão sendo construídos. |
| Em revisão | O cronograma foi submetido a exame de lógica, capacidade, risco e autoridade. |
| Aprovado para orientar preparação | Pode coordenar preparação; não autoriza execução. |
| Vigente | É a referência temporal atual do escopo declarado. |
| Vigente com condições | Pode orientar trabalho dentro de condições explícitas. |
| Em replanejamento controlado | A previsão está sendo revisada; a última versão válida permanece identificada. |
| Suspenso | Nenhum avanço temporal deve ser presumido até nova decisão. |
| Substituído | Outra versão ou cronograma assumiu sua função. |
| Encerrado | O objeto não recebe novos movimentos, mas permanece recuperável. |
| Cancelado | O cronograma deixou de ser executável por decisão registrada. |

### 9.1 Estado do cronograma não é estado do trabalho

Um cronograma vigente pode conter pacotes não iniciados, trabalho bloqueado ou gate não decidido. O estado real dos itens deve ser obtido do backlog e do Kanban; o estado de entregas, das fontes de verificação e aceite.

---

## 10. Documentos de entrada e precedência

### 10.1 Entradas obrigatórias

| Entrada | ID/versão | Localização | Autoridade | Verificação |
| --- | --- | --- | --- | --- |
| Linha de base arquitetural | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Registro do PI-1 | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Termo de Abertura | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Plano de Implantação | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Estrutura Analítica | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Calendários e disponibilidade | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Restrições externas conhecidas | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |
| Riscos e dependências iniciais | [Preencher] | [Caminho] | [Nome/papel] | Conforme / condição |

### 10.2 Ordem de autoridade

1. decisões formalmente aprovadas dentro da alçada;
2. linha de base arquitetural e condições de transição;
3. Termo de Abertura vigente;
4. Plano de Implantação vigente;
5. Estrutura Analítica vigente;
6. linha de base temporal aprovada;
7. previsão vigente deste cronograma;
8. backlog, Kanban e registros operacionais;
9. painéis, relatórios e comunicações derivadas.

Quando houver conflito, a fonte derivada não corrige a fonte superior. A divergência deve ser contida, registrada e encaminhada à autoridade competente.

### 10.3 Divergências de entrada

| ID | Fontes divergentes | Elemento | Efeito temporal | Contenção | Autoridade | Destino |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/versões] | [Preencher] | [Preencher] | [Preencher] | [Nome/papel] | [Decisão/ajuste/retorno] |

---

## 11. Modelo temporal do cronograma

O modelo temporal combina seis elementos:

| Elemento | Função |
| --- | --- |
| Objeto | Unidade oficial a que o compromisso se refere. |
| Lógica | Relação que permite ou impede início, término ou marco. |
| Calendário | Dias, horas, fusos e exceções aplicáveis. |
| Estimativa | Duração ou intervalo produzido com fundamento. |
| Compromisso | Data ou janela aprovada pela autoridade competente. |
| Realização | Datas e fatos observados durante a execução. |

Nenhum desses elementos deve ser inferido silenciosamente a partir dos demais.

### 11.1 Unidade de tempo

| Escopo | Unidade principal | Unidade secundária | Regra de conversão | Responsável |
| --- | --- | --- | --- | --- |
| Cronograma mestre | [Dia útil/semana/mês] | [Hora/dia corrido] | [Preencher] | [Nome] |
| Janela crítica | [Minuto/hora/dia] | [Preencher] | [Preencher] | [Nome] |
| Estabilização | [Dia/semana/ciclo] | [Preencher] | [Preencher] | [Nome] |

### 11.2 Fuso e horário

| Campo | Registro |
| --- | --- |
| Fuso principal | [Identificador IANA] |
| Fusos adicionais | [Identificadores ou Nenhum] |
| Regra para horário de verão | [Preencher] |
| Regra para eventos simultâneos | [Preencher] |
| Fonte oficial de hora | [Sistema/fonte] |

Datas sem horário devem ser interpretadas conforme a regra explícita do cronograma. Eventos críticos entre fusos exigem data, hora e fuso completos.

---

## 12. Horizontes de planejamento

| Horizonte | Conteúdo mínimo | Nível de detalhe | Confiança esperada | Cadência de elaboração |
| --- | --- | --- | --- | --- |
| Imediato | Pacotes executáveis, decisões, recursos, evidências e dependências confirmadas. | Detalhado | [Faixa] | [Cadência] |
| Próximo | Incrementos, entregas, marcos e janelas com lógica suficiente. | Intermediário | [Faixa] | [Cadência] |
| Posterior | Ondas, resultados, restrições e grandes dependências. | Macro | [Faixa] | [Cadência] |
| Condicional | Trabalho dependente de decisão, aprendizagem ou evento ainda não ocorrido. | Cenário | [Faixa] | [Gatilho] |

### 12.1 Elaboração progressiva

Detalhe menor no horizonte posterior não constitui lacuna quando:

- a incerteza está declarada;
- o objeto macro está identificado;
- existe gatilho de detalhamento;
- a decisão futura possui responsável;
- a falta de detalhe não é usada para sustentar o `PI-2` do objeto afetado.

### 12.2 Horizonte congelado

| Campo | Registro |
| --- | --- |
| Período protegido | [Data inicial/final ou condição] |
| Alterações permitidas | [Classes] |
| Autoridade para exceção | [Nome/papel] |
| Motivo da proteção | [Preencher] |
| Tratamento de emergência | [Preencher] |

Congelamento não impede correção de risco, evidência negativa ou condição insegura. Ele protege previsibilidade contra mudança discricionária.

---

## 13. Objetos temporais e identificadores

### 13.1 Padrões recomendados

| Objeto | Padrão |
| --- | --- |
| Cronograma Mestre | `CRM-IMP-AAAA-NNN` |
| Linha de base temporal | `IMP-AAAA-NNN-LBT-NNN` |
| Marco | `IMP-AAAA-NNN-MAR-NNN` |
| Janela | `IMP-AAAA-NNN-JAN-NNN` |
| Calendário específico | `IMP-AAAA-NNN-CAL-NNN` |
| Dependência temporal | `IMP-AAAA-NNN-DEP-NNN` |
| Restrição temporal | `IMP-AAAA-NNN-RES-NNN` |
| Ocorrência de gate | `IMP-AAAA-NNN-GAT-NNN` |
| Reserva temporal | `IMP-AAAA-NNN-RSV-NNN` |

Projeto, onda, incremento, entrega, pacote de trabalho, item de backlog, evidência e demais objetos preservam os IDs definidos em suas fontes oficiais. O cronograma os referencia; não cria cópias temporais.

### 13.2 Não reutilização

IDs cancelados, retirados ou substituídos permanecem reservados. Uma nova versão preserva o ID do objeto; um objeto materialmente distinto recebe novo identificador.

### 13.3 Nome temporal

| Tipo | Forma recomendada | Evitar |
| --- | --- | --- |
| Marco | Condição alcançada | Reunião de terça |
| Janela | Objeto + contexto de disponibilidade | Período importante |
| Dependência | Condição necessária para objeto definido | Aguardar retorno |
| Restrição | Limite + origem | Prazo curto |
| Reserva | Exposição protegida + autoridade | Tempo extra |

---

## 14. Linha de base temporal e previsão vigente

### 14.1 Registro da linha de base

| Campo | Registro |
| --- | --- |
| ID da linha de base temporal | `IMP-AAAA-NNN-LBT-NNN` |
| Versão do cronograma | [N.N] |
| Data de referência | [AAAA-MM-DD] |
| Objeto coberto | [Projetos/ondas/incrementos/IDs] |
| Início aprovado | [Data/condição] |
| Conclusão aprovada | [Data/condição] |
| Marcos comprometidos | [IDs] |
| Janelas comprometidas | [IDs] |
| Reserva aprovada | [ID/quantidade] |
| Premissas críticas | [IDs] |
| Riscos considerados | [IDs] |
| Autoridade | [Nome/papel] |
| Decisão | [ID/link] |
| Localização da cópia preservada | [Caminho] |

### 14.2 Três referências distintas

| Referência | Significado | Pode ser alterada por atualização factual? |
| --- | --- | --- |
| Linha de base | Compromisso aprovado para comparação. | Não |
| Previsão vigente | Melhor projeção atual diante dos fatos conhecidos. | Sim, com governança |
| Realizado | Datas e condições observadas. | Apenas por correção de erro comprovado |

### 14.3 Comparação principal

| Objeto | Início da base | Término da base | Início previsto atual | Término previsto atual | Início real | Término real | Variação | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data] | [Data] | [Data] | [Data] | [Data/NA] | [Data/NA] | [Período] | [Estado] |

---

## 15. Premissas temporais e confiança

| ID | Premissa | Objeto | Fundamento | Confiança | Data-limite de confirmação | Responsável | Efeito se refutada |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | [Fonte] | Alta / média / baixa | [Data/gatilho] | [Nome] | [Preencher] |

### 15.1 Escala de confiança

| Nível | Condição mínima | Uso permitido |
| --- | --- | --- |
| Alta | Dependências, capacidade, calendário e método estão confirmados por evidência suficiente. | Compromisso dentro da alçada definida. |
| Média | Parte relevante está confirmada e a incerteza remanescente possui resposta. | Planejamento com margem e gatilho. |
| Baixa | Existem premissas materiais não confirmadas. | Cenário ou indicação; não compromisso firme. |
| Não determinada | A base de estimativa ainda é insuficiente. | Deve permanecer explícita e não sustentar gate. |

### 15.2 Registro da base de estimativa

| Objeto | Método | Dados usados | Pessoa ou grupo consultado | Intervalo | Confiança | Limitações | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Analogia / paramétrica / três pontos / especialista / experimento / outra | [Fonte] | [Nomes/papéis] | [Faixa] | [Nível] | [Preencher] | [AAAA-MM-DD] |

---

## 16. Calendários de trabalho

### 16.1 Calendário mestre

| Campo | Registro |
| --- | --- |
| ID | `IMP-AAAA-NNN-CAL-NNN` |
| Nome | [Preencher] |
| Dias de trabalho | [Preencher] |
| Horários | [Preencher] |
| Fuso | [Identificador IANA] |
| Feriados e exceções | [Fonte/lista] |
| Período de validade | [Datas] |
| Responsável | [Nome] |
| Última confirmação | [AAAA-MM-DD] |

### 16.2 Calendários específicos

| ID | Recurso, equipe, ambiente ou fornecedor | Calendário | Exceções | Fonte | Responsável | Efeito |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID] | [Preencher] | [Link] | [Nome] | [Objetos] |

### 16.3 Indisponibilidades conhecidas

| ID | Pessoa, serviço ou ambiente | Início | Fim | Motivo | Objetos afetados | Resposta | Confirmação |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Data/hora] | [Data/hora] | [Preencher] | [IDs] | [Preencher] | [Fonte] |

---

## 17. Capacidade, carga e duração

### 17.1 Capacidade temporal disponível

| Período | Pessoa/equipe/recurso | Capacidade bruta | Trabalho não relacionado | Reserva operacional | Capacidade disponível | Fonte | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Período] | [Nome/ID] | [Horas/unidades] | [Quantidade] | [Quantidade] | [Quantidade] | [Fonte] | [Nome] |

### 17.2 Conversão entre esforço e duração

```text
duração estimada depende de esforço, capacidade efetivamente disponível,
calendário, paralelismo permitido, dependências e variabilidade.
```

Não utilizar divisão simples de esforço por pessoas quando:

- o trabalho não pode ser paralelizado;
- existe curva de aprendizagem;
- a coordenação cresce com o número de participantes;
- competência crítica está concentrada;
- decisões ou ambientes limitam o fluxo;
- a carga operacional cotidiana compete com a implantação.

### 17.3 Sustentabilidade da carga

| Pessoa/equipe | Período | Carga da implantação | Carga operacional | Limite sustentável | Excesso | Resposta | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Nome] | [Período] | [Quantidade] | [Quantidade] | [Quantidade] | [Quantidade] | [Preencher] | [Nome/papel] |

Sobrecarga não deve ser usada como reserva oculta do cronograma.

---

## 18. Mapa temporal mestre

| Ordem | Movimento | Objetos | Início | Término | Condição de saída | Marco/gate | Dependências | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Consolidar planejamento | [IDs] | [Data] | [Data] | Plano, estrutura e fontes coerentes | [ID] | [IDs] | [Nome] |
| 2 | Preparar condições | [IDs] | [Data] | [Data] | Recursos, pessoas, acessos e controles demonstráveis | `PI-2` previsto | [IDs] | [Nome] |
| 3 | Produzir e integrar | [IDs] | [Data] | [Data] | Configuração candidata verificável | [ID] | [IDs] | [Nome] |
| 4 | Preparar liberação | [IDs] | [Data] | [Data] | Prontidão de exposição demonstrável | `PI-3` previsto | [IDs] | [Nome] |
| 5 | Liberar e validar | [IDs] | [Data] | [Data] | Evidências de capacidade e efeitos disponíveis | `PI-4` previsto | [IDs] | [Nome] |
| 6 | Estabilizar | [IDs] | [Data] | [Data] | Funcionamento dentro dos limites | [ID] | [IDs] | [Nome] |
| 7 | Transferir à operação | [IDs] | [Data] | [Data] | Sustentação aceita e responsabilidades transferidas | `PI-5` previsto | [IDs] | [Nome] |

O mapa é uma visão derivada. As linhas detalhadas permanecem nas seções correspondentes e na ferramenta oficial.

---

## 19. Projetos e frentes temporais

| Projeto/frente | Resultado | Responsável | Início | Término | Calendário | Marcos | Dependências externas | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Nome] | [Data] | [Data] | [ID] | [IDs] | [IDs] | [Estado] |

### 19.1 Coordenação entre projetos

| Projeto de origem | Projeto dependente | Objeto transferido | Data/condição | Critério | Responsáveis | Risco de desalinhamento |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [Preencher] | [Preencher] | [Nomes] | [ID/síntese] |

---

## 20. Ondas de implantação

| Onda | Escopo e público | Incrementos | Preparação | Início previsto | Janela de liberação | PI-3 | PI-4 | Aprendizagem antes da próxima onda |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs/descrição] | [IDs] | [IDs] | [Data] | [ID/data] | [ID previsto] | [ID previsto] | [Marco/critério] |

### 20.1 Intervalo entre ondas

| Onda anterior | Onda seguinte | Período mínimo | Evidência necessária | Decisão | Pode sobrepor? | Condição para sobreposição |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Período] | [IDs/tipos] | [ID/prevista] | Sim / não / condicional | [Preencher] |

O intervalo entre ondas deve permitir observação, correção e decisão proporcionais ao risco. Não deve ser eliminado apenas para recuperar atraso.

---

## 21. Incrementos

| Incremento | Capacidade | Entregas | Início | Término | Integração | Testes | PI-3 previsto | PI-4 previsto | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [IDs] | [Data] | [Data] | [Marco] | [Período/marco] | [ID/data] | [ID/data] | [Nome] |

### 21.1 Incremento temporalmente completo

Um incremento possui planejamento temporal suficiente quando:

- suas entregas e interfaces estão identificadas;
- produção, integração, teste, correção e evidência têm tempo explícito;
- preparação humana e operacional não está fora do cronograma;
- as ocorrências previstas de `PI-3` e `PI-4` possuem objeto delimitado;
- contingência e reversão possuem janela quando aplicáveis;
- estabilização e transição não foram comprimidas para fora do horizonte.

---

## 22. Entregas e pacotes de trabalho

| Objeto | Tipo | Predecessoras | Início | Término | Duração | Calendário | Responsável | Marco de saída | Fonte |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Entrega / pacote | [IDs] | [Data] | [Data] | [Quantidade] | [ID] | [Nome] | [ID] | [EAI/backlog] |

### 22.1 Regras de agendamento

- pacote sem critério de conclusão não deve receber compromisso firme;
- entrega pode depender de vários pacotes sem duplicá-los;
- atividade necessária à execução deve ser criada no backlog e referenciada;
- duração deve incluir trabalho de verificação quando ele fizer parte do pacote;
- espera material deve aparecer como dependência, calendário, janela ou restrição;
- retrabalho esperado não deve permanecer como margem invisível;
- trabalho emergente deve receber origem, decisão e efeito temporal.

### 22.2 Pacotes não agendados

| Pacote | Motivo | Objeto afetado | Pode sustentar PI-2? | Tratamento | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [IDs] | Sim / não / condicional | [Preencher] | [Nome] | [Data/gatilho] |

---

## 23. Marcos

| Marco | Nome | Condição observável | Objetos | Data-base | Previsão vigente | Data real | Dependências | Evidência | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [IDs] | [Data] | [Data] | [Data/NA] | [IDs] | [ID/tipo] | [Nome/papel] | [Estado] |

### 23.1 Estados de marco

| Estado | Significado |
| --- | --- |
| Planejado | Existe na previsão, ainda sem compromisso aprovado. |
| Comprometido | Integra linha de base temporal aprovada. |
| Em risco | A condição pode não ser alcançada na previsão vigente. |
| Atrasado | A data comprometida passou sem condição demonstrada. |
| Alcançado | A condição foi demonstrada com evidência suficiente. |
| Alcançado com ressalva | A autoridade reconheceu condição limitada e registrou efeito. |
| Não alcançado | A verificação demonstrou insuficiência. |
| Cancelado | O marco deixou de se aplicar por decisão registrada. |
| Substituído | Outro marco passou a representar a condição. |

### 23.2 Qualidade do marco

- [ ] representa condição, não reunião ou intenção;
- [ ] possui objeto e fronteira;
- [ ] declara critério observável;
- [ ] identifica evidência e verificador;
- [ ] possui data-base e previsão vigente distintas;
- [ ] explicita dependências;
- [ ] define autoridade para reconhecer o alcance;
- [ ] declara consequência se não for alcançado.

---

## 24. Janelas críticas

| Janela | Objeto | Tipo | Início | Fim | Fuso | Pré-condições | Ponto de não retorno | Contingência | Responsável | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | Técnica / operacional / humana / contratual / regulatória / outra | [Data/hora] | [Data/hora] | [IANA] | [IDs] | [Preencher] | [ID/plano] | [Nome] | [Estado] |

### 24.1 Tipos de janela

| Tipo | Exemplo de função | Proteção mínima |
| --- | --- | --- |
| Disponibilidade | Ambiente, sistema, fornecedor ou equipe pode atuar. | Confirmação e alternativa |
| Mudança | Alteração pode ser aplicada com impacto controlado. | Comando, comunicação e retorno |
| Migração | Dados ou configurações podem ser convertidos. | Integridade, reconciliação e reversão |
| Comunicação | Pessoas precisam receber e compreender informação antes do efeito. | Público, canal e confirmação |
| Treinamento | Competência precisa ser desenvolvida antes do uso. | Participação, prática e evidência |
| Regulatória/contratual | Ação deve ocorrer dentro de limite externo. | Fonte, autoridade e consequência |
| Estabilização | Configuração deve permanecer observada antes da transferência. | Indicadores, suporte e limites |

### 24.2 Perda de janela

| Janela | Sinal de perda | Efeito imediato | Pode reagendar? | Nova condição | Autoridade | Comunicação | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | Sim / não / condicional | [Preencher] | [Nome/papel] | [Públicos/canal] | [ID] |

---

## 25. Ocorrências previstas de gate

| Ocorrência | Gate | Objeto e versão | Condição de submissão | Data/janela prevista | Preparador | Verificador | Decisor | Trabalho bloqueado até decisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | `PI-2` / `PI-3` / `PI-4` / `PI-5` | [IDs/versões] | [Preencher] | [Data/ID] | [Nome] | [Nome] | [Nome/papel] | [IDs/tipos] |

### 25.1 Gate previsto não é gate decidido

O cronograma pode reservar tempo, participantes e janela para um gate. O registro decisório correspondente deve declarar:

- objeto e versão submetidos;
- evidências examinadas;
- autoridade;
- resultado;
- condições;
- validade;
- próximo movimento permitido.

Se a evidência estiver insuficiente, a ocorrência pode ser adiada, devolvida ou rejeitada sem que a data planejada produza autorização automática.

---

## 26. Dependências temporais

| Dependência | Objeto predecessor | Objeto sucessor | Relação | Condição | Defasagem | Calendário | Responsável | Evidência | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | TI / II / TT / IT | [Preencher] | [Quantidade] | [ID] | [Nome] | [ID/fonte] | [Estado] |

### 26.1 Relações controladas

| Código | Relação | Significado |
| --- | --- | --- |
| TI | Término para início | A sucessora começa depois que a predecessora termina ou satisfaz a condição definida. |
| II | Início para início | A sucessora pode começar depois que a predecessora inicia e cumpre a condição definida. |
| TT | Término para término | A sucessora pode terminar depois que a predecessora termina e cumpre a condição definida. |
| IT | Início para término | A sucessora pode terminar depois que a predecessora inicia; utilizar somente com justificativa explícita. |

O código não basta. Toda relação material deve declarar a condição real. “TI” pode significar término técnico, aprovação, disponibilidade de evidência ou entrega física; essas condições não são intercambiáveis.

### 26.2 Tipos materiais de dependência

| Tipo | Pergunta de controle |
| --- | --- |
| Arquitetural | Que requisito, interface, condição ou decisão limita a sequência? |
| Técnica | Que componente, ambiente, integração, dado ou teste precisa existir? |
| Humana | Que compreensão, competência, participação ou disponibilidade é necessária? |
| Operacional | Que processo, suporte, rotina ou autoridade precisa estar funcional? |
| Decisória | Que decisão humana precisa ser emitida antes do avanço? |
| Contratual | Que contratação, licença, aceite ou obrigação limita o movimento? |
| Externa | Que pessoa, fornecedor, evento ou sistema fora do controle direto participa? |
| Informacional | Que informação, documento ou evidência precisa estar disponível e íntegra? |

### 26.3 Dependência sem sucessora ou predecessora válida

| Dependência | Lacuna | Risco | Contenção | Responsável | Limite | Destino |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [ID/síntese] | [Preencher] | [Nome] | [Data/gatilho] | [Corrigir / aceitar / retirar / retornar] |

---

## 27. Rede lógica

### 27.1 Tabela da rede

| Sequência | Objeto | Predecessoras | Sucessoras | Relações | Duração | Início cedo | Término cedo | Início tarde | Término tarde | Folga total |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [N] | [ID] | [IDs] | [IDs] | [Códigos] | [Quantidade] | [Data] | [Data] | [Data] | [Data] | [Quantidade] |

### 27.2 Regras da rede

1. Todo objeto agendado possui predecessor, marco inicial justificado ou condição de entrada.
2. Todo objeto que produz efeito material possui sucessor, marco final ou destino explícito.
3. Dependências circulares devem ser resolvidas ou tratadas como ciclo iterativo delimitado.
4. Defasagens positivas ou negativas exigem fundamento material.
5. Paralelismo não pode antecipar uso antes de integração, autoridade ou segurança.
6. Relações criadas apenas para fixar uma data devem ser substituídas por restrição declarada.
7. A ferramenta de cálculo não substitui a revisão humana da lógica.

### 27.3 Ciclos iterativos

| Ciclo | Objetos | Condição de entrada | Iteração prevista | Limite | Critério de saída | Efeito no cronograma |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Preencher] | [N/faixa] | [Tempo/evento] | [Preencher] | [Preencher] |

Iteração não deve ser representada como sequência infinita ou margem oculta. O limite e a decisão diante de insuficiência precisam estar definidos.

---

## 28. Estimativas de duração

### 28.1 Registro de estimativa

| Objeto | Unidade | Otimista | Mais provável | Pessimista | Estimativa adotada | Método | Base | Confiança | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Horas/dias/semanas] | [N] | [N] | [N] | [N/faixa] | [Método] | [Fonte] | [Nível] | [Nome] |

### 28.2 Estimativa de três pontos opcional

Quando o contexto permitir, uma estimativa ponderada pode apoiar a comparação:

```text
estimativa_ponderada = (otimista + 4 × mais_provavel + pessimista) / 6
```

O resultado é auxiliar. Ele não elimina riscos correlacionados, eventos raros, calendários, capacidade, dependências ou necessidade de julgamento especializado.

### 28.3 Inclusões da duração

| Elemento | Incluído? | Fonte | Tratamento quando excluído |
| --- | --- | --- | --- |
| Produção | Sim / não / parcial | [Fonte] | [Objeto separado] |
| Revisão | Sim / não / parcial | [Fonte] | [Objeto separado] |
| Correção esperada | Sim / não / parcial | [Fonte] | [Reserva/objeto] |
| Aprovação | Sim / não / parcial | [Fonte] | [Dependência/marco] |
| Espera externa | Sim / não / parcial | [Fonte] | [Dependência] |
| Documentação | Sim / não / parcial | [Fonte] | [Objeto separado] |
| Produção de evidência | Sim / não / parcial | [Fonte] | [Objeto separado] |

---

## 29. Antecipações e esperas entre objetos

| Relação | Predecessora | Sucessora | Antecipação/espera | Unidade | Fundamento | Risco | Autoridade | Revisão |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [ID] | [Quantidade] | [Unidade] | [Preencher] | [ID/síntese] | [Nome/papel] | [Data/gatilho] |

### 29.1 Proteções

- antecipação não autoriza usar saída ainda não verificada;
- espera não substitui critério observável;
- intervalo regulatório ou contratual preserva sua fonte;
- tempo para aprendizagem entre ondas não deve ser reduzido sem análise de risco;
- tempo de estabilização não pode ser convertido em folga livre;
- defasagem negativa em atividade crítica exige revisão independente quando o risco justificar.

---

## 30. Caminho crítico

### 30.1 Registro principal

| Ordem | Objeto | Predecessora crítica | Sucessora crítica | Duração | Folga total | Motivo da criticidade | Consequência do atraso | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [N] | [ID] | [ID] | [ID] | [Quantidade] | [Quantidade] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

### 30.2 Regra de identificação

O caminho crítico deve ser calculado sobre:

- a rede vigente;
- os calendários aplicáveis;
- as durações e defasagens vigentes;
- as restrições declaradas;
- a data de status;
- os fatos realizados;
- as condições ainda não satisfeitas.

O caminho crítico pode mudar durante a execução. O histórico deve registrar quando, por que e com que efeito.

### 30.3 Caminhos quase críticos

| Caminho | Objetos | Folga | Risco de se tornar crítico | Gatilho | Resposta | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID/localizador] | [IDs] | [Quantidade] | [Preencher] | [Preencher] | [Preencher] | [Nome] |

### 30.4 Criticidade não é prioridade

Um objeto pode ser prioritário por valor, risco ou obrigação e não integrar o caminho crítico. Outro pode estar no caminho crítico sem possuir alto valor isolado. Prioridade pertence ao plano e ao backlog; criticidade temporal pertence à rede.

---

## 31. Folgas

| Objeto | Folga total | Folga livre | Data de cálculo | Calendário | Pode ser consumida por | Autoridade | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Quantidade] | [Quantidade] | [AAAA-MM-DD] | [ID] | [Regra] | [Nome/papel] | [Estado] |

### 31.1 Proteção contra uso indevido

- folga não é atraso autorizado sem consequência;
- folga de um objeto não pertence automaticamente ao responsável local;
- consumo de folga que afeta caminho quase crítico deve ser comunicado;
- folga negativa exige ação, decisão ou renegociação;
- cálculo desatualizado não sustenta compromisso;
- folga não substitui reserva de risco aprovada.

### 31.2 Folga negativa

| Objeto | Quantidade | Origem | Compromisso afetado | Alternativas | Risco | Decisão necessária | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Quantidade] | [Preencher] | [ID/data] | [Preencher] | [ID] | [Nome/papel] | [Data] |

---

## 32. Reservas temporais

| Reserva | Tipo | Protege | Quantidade | Localização na rede | Critério de uso | Autoridade | Consumo | Saldo |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Contingência / gestão / estabilização / outra | [Objetos/riscos] | [Período] | [Preencher] | [Preencher] | [Nome/papel] | [Período] | [Período] |

### 32.1 Reserva e trabalho

Reserva protege exposição a incerteza. Ela não representa pacote de trabalho sem nome, correção omitida, sobrecarga presumida ou período disponível para ampliar escopo.

### 32.2 Uso da reserva

| Data | Reserva | Motivo | Objeto | Risco ocorrido | Quantidade | Autoridade | Efeito | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [AAAA-MM-DD] | [ID] | [Preencher] | [IDs] | [ID] | [Período] | [Nome/papel] | [Preencher] | [ID/link] |

### 32.3 Sinais de consumo inadequado

- reserva usada para incluir escopo não autorizado;
- consumo sem evento ou fundamento;
- margem distribuída e invisível em todas as durações;
- saldo alterado sem histórico;
- reserva de estabilização usada para terminar produção atrasada;
- pressão para eliminar reserva sem reduzir risco.

---

## 33. Dependências externas

| Dependência | Fornecedor/pessoa/sistema | Objeto necessário | Objeto afetado | Data/condição | Confirmação | Plano alternativo | Responsável interno | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [IDs] | [Preencher] | [ID/fonte] | [Preencher] | [Nome] | [Estado] |

### 33.1 Compromisso externo

| Campo | Registro |
| --- | --- |
| Quem confirmou | [Nome/papel] |
| O que foi confirmado | [Objeto/serviço/data] |
| Canal ou documento | [Fonte] |
| Limitações | [Preencher] |
| Validade | [Data/condição] |
| Regra de reconfirmação | [Preencher] |

Ausência de confirmação não deve ser convertida em data firme. O cronograma deve representar a dependência como condicionada e explicitar o efeito sobre o objeto afetado.

---

## 34. Decisões como dependências

| Decisão | Objeto | Insumo necessário | Autoridade | Data-limite | Fórum/canal | Efeito da espera | Escalonamento | Estado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID ou a criar] | [IDs] | [IDs/fontes] | [Nome/papel] | [Data/condição] | [Preencher] | [Preencher] | [Nome/papel e limite] | [Estado] |

### 34.1 Tempo de decisão

O tempo necessário para preparar, convocar, examinar e registrar decisão deve aparecer no cronograma quando material. Apenas marcar a data da reunião oculta trabalho e risco decisório.

### 34.2 Ausência de manifestação

Ausência de resposta não equivale automaticamente a concordância. O tratamento depende de:

- papel e alçada;
- obrigação de participação;
- materialidade;
- prazo comunicado;
- política aplicável;
- risco de avançar sem manifestação.

---

## 35. Preparação humana no cronograma

| Grupo/papel | Mudança | Participação | Comunicação | Treinamento | Prática | Evidência de compreensão/competência | Pronto antes de | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [ID/síntese] | [Período] | [Marco/ID] | [Período/ID] | [Período] | [ID/tipo] | [Marco/gate] | [Nome] |

### 35.1 Regras temporais humanas

- pessoas afetadas participam antes de decisões cujo efeito dependa de sua experiência;
- comunicação ocorre antes do efeito material, com tempo para compreensão e manifestação;
- treinamento ocorre próximo o suficiente do uso real para permitir retenção e prática;
- competência é verificada antes da atuação autônoma, quando exigida;
- suporte reforçado existe durante liberação e estabilização;
- férias, carga operacional, fusos, acessibilidade e ritmos de aprendizagem integram o planejamento;
- urgência não converte presença em competência.

### 35.2 Compressão e impacto humano

| Proposta de compressão | Pessoas afetadas | Efeito sobre carga, participação ou competência | Risco | Alternativa | Autoridade | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Grupos] | [Preencher] | [ID/síntese] | [Preencher] | [Nome/papel] | [ID/pendente] |

---

## 36. Comunicação e engajamento

| Evento | Objeto | Públicos | Deve ocorrer antes de | Data/janela | Canal | Confirmação necessária | Responsável | Plano oficial |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [IDs] | [Grupos] | [Marco/efeito] | [Data/ID] | [Preencher] | [Método] | [Nome] | `templates/08-plano-de-comunicacao-e-engajamento.md` |

### 36.1 Eventos obrigatórios

Registrar, quando aplicável:

- abertura e mobilização;
- mudança material do plano ou cronograma;
- risco crítico ou bloqueio do caminho crítico;
- alteração de público, escopo, janela ou condição;
- convocação e resultado de gate;
- liberação, suspensão, reversão ou cancelamento;
- início e saída da estabilização;
- transição para operação;
- destino de pendências e aprendizagem.

---

## 37. Treinamento, capacitação e conhecimento

| Ação | Competência/conhecimento | Público | Pré-requisitos | Início | Término | Prática | Verificação | Necessária antes de | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Grupo] | [IDs] | [Data] | [Data] | [Data/período] | [ID/método] | [Marco/gate] | [Nome] |

### 37.1 Sequência mínima

```text
compreensão do contexto
  → contato com procedimento ou ferramenta
  → prática orientada
  → correção e nova prática
  → demonstração de competência
  → suporte no trabalho real
```

O plano especializado permanece em `templates/09-plano-de-treinamento-e-capacitacao.md`. Este cronograma registra apenas compromissos e dependências temporais.

---

## 38. Processos, informação e documentação

| Objeto | Tipo | Produção/revisão | Vigência necessária | Publicação | Acesso confirmado | Treinamento relacionado | Marco de prontidão | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Processo / política / procedimento / instrução / formulário / registro / informação | [Período] | [Data/condição] | [Data] | [Data/evidência] | [ID] | [ID] | [Nome] |

### 38.1 Regra documental

Documento produzido não está necessariamente vigente, acessível, compreendido ou aplicado. O cronograma deve distinguir cada condição quando material.

---

## 39. Dados, tecnologia, integrações e IA

| Objeto | Ambiente | Preparação | Acesso | Configuração/desenvolvimento | Integração | Teste | Avaliação/controle | Disponível antes de | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Ambiente] | [Período] | [Marco/data] | [Período] | [Período] | [Período] | [ID/período] | [Marco/gate] | [Nome] |

### 39.1 Inteligência artificial como parte da configuração

Quando houver IA material, prever tempo para:

- confirmação de finalidade e limites;
- preparação e autorização de dados;
- seleção ou configuração de modelo;
- avaliação de desempenho e comportamento;
- análise de vieses, segurança, privacidade e propriedade intelectual;
- definição de supervisão e escalonamento;
- preparação das pessoas que utilizarão ou serão afetadas;
- monitoramento inicial e possibilidade de desativação;
- documentação de versão, proveniência e limitações.

Pressão temporal não autoriza suprimir avaliação ou supervisão aplicável.

---

## 40. Migração, conversão e coexistência

| Movimento | Objeto | Origem | Destino | Preparação | Ensaio | Reconciliação | Janela real | Coexistência | Desativação | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Sistema/processo] | [Sistema/processo] | [Período] | [Data] | [Período] | [ID/data] | [Período] | [Data/condição] | [Nome] |

### 40.1 Proteções temporais

- janela de migração possui pré-condições e comando;
- cópia ou condição segura é preservada antes do ponto de não retorno;
- reconciliação ocorre antes de aceite quando material;
- coexistência possui término, autoridade e risco explícitos;
- desativação não ocorre antes de evidência e decisão aplicáveis;
- retenção, descarte e acesso seguem políticas vigentes.

---

## 41. Piloto, liberação, virada e ampliação

| Evento | Escopo | Público | Ambiente | Janela | Pré-condições | PI-3 | Comando | Critério de parada | Retorno | PI-4 | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Grupo] | [Preencher] | [ID/data] | [IDs] | [ID] | [Nome/papel] | [Preencher] | [ID/plano] | [ID] | [Nome] |

### 41.1 Sequência protegida

```text
preparação demonstrada
  → PI-3 decidido
  → liberação no escopo autorizado
  → observação e suporte
  → validação e registro de diferenças
  → PI-4 decidido
  → estabilização ou correção/reversão
```

O plano detalhado pertence a `templates/11-plano-de-piloto-ondas-virada-e-reversao.md`.

---

## 42. Contingência, reversão e continuidade

| Cenário | Gatilho | Decisão até | Ação | Duração estimada | Estado seguro | Janela de retorno | Responsável | Comunicação | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Tempo/data] | [Preencher] | [Período] | [ID/descrição] | [ID/data] | [Nome] | [ID/evento] | [ID/tipo] |

### 42.1 Tempo máximo de resposta

| Objeto/risco | Tempo para detectar | Tempo para decidir | Tempo para interromper | Tempo para restaurar | Fundamento | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Período] | [Período] | [Período] | [Período] | [Fonte] | [Nome] |

Reversão planejada deve ser executável dentro da janela real. Uma instrução que exige mais tempo, acesso ou competência do que o cenário permite não constitui reversibilidade demonstrável.

---

## 43. Validação e aceite

| Objeto | Contexto | Período de observação | Casos/cenários | Evidências | Revisão | PI-4 previsto | Autoridade | Consequência de insuficiência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Início/fim] | [IDs] | [IDs/tipos] | [Data/período] | [ID/data] | [Nome/papel] | [Corrigir / ampliar / rejeitar / reverter] |

### 43.1 Tempo para produzir evidência

O cronograma deve considerar:

- volume mínimo de ocorrências;
- diversidade de cenários;
- sazonalidade ou ciclos operacionais;
- latência de efeito;
- tempo de coleta e análise;
- disponibilidade de verificadores e participantes;
- repetição após correção;
- preservação de evidência negativa.

Não comprimir o período de observação apenas para alcançar data de aceite.

---

## 44. Estabilização

| Configuração/escopo | Início | Duração mínima | Indicadores | Limites | Suporte reforçado | Revisões | Critério de saída | PI-5 previsto | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/condição] | [Período] | [IDs] | [IDs/valores] | [Período] | [Cadência] | [Preencher] | [ID/data] | [Nome] |

### 44.1 Reinício ou extensão

| Evento | Efeito sobre estabilização | Novo início ou extensão | Critério | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- |
| [Incidente/correção/mudança/interrupção] | [Preencher] | [Data/período] | [Preencher] | [Nome/papel] | [ID] |

Estabilização não é tempo ocioso após o projeto. É período de observação e sustentação com trabalho, indicadores, limites, suporte e decisão.

---

## 45. Transição para operação

| Objeto | Preparação bilateral | Entrega documental | Conhecimento | Suporte | Pendências | Início da transferência | PI-5 previsto | Conclusão | Responsável de implantação | Responsável operacional |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Período/marco] | [IDs/data] | [IDs/data] | [Período] | [IDs] | [Data] | [ID/data] | [Data/condição] | [Nome] | [Nome] |

### 45.1 Proteção contra transferência automática

Fim do cronograma, encerramento contratual ou término do período de estabilização não transferem responsabilidade automaticamente. A operação precisa:

- receber a configuração identificada;
- compreender condições e limites;
- possuir pessoas, acessos e competências;
- conhecer suporte, incidentes e escalonamento;
- aceitar riscos e pendências dentro de sua alçada;
- manifestar aceite no `PI-5`.

---

## 46. Restrições temporais

| Restrição | Tipo | Origem | Objeto afetado | Data/condição | Negociável? | Consequência | Autoridade para alterar | Tratamento |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | Legal / contratual / técnica / humana / operacional / financeira / outra | [Fonte] | [IDs] | [Preencher] | Sim / não / condicional | [Preencher] | [Nome/papel] | [Preencher] |

### 46.1 Categorias de restrição

| Categoria | Uso |
| --- | --- |
| Não iniciar antes de | Existe impedimento real anterior à data ou condição. |
| Não terminar depois de | Existe limite externo ou decisão formal. |
| Deve iniciar em | Evento está vinculado a janela específica e justificada. |
| Deve terminar em | Compromisso rígido aprovado com consequência explícita. |
| O quanto antes | A rede e a capacidade determinam a primeira data possível. |
| O quanto depois | A rede preserva o objeto até o último momento permitido, com justificativa. |

Restrições rígidas devem ser exceção justificada. Fixar datas para fazer a ferramenta produzir o resultado desejado destrói a utilidade diagnóstica da rede.

---

## 47. Riscos temporais

| Risco | Objeto | Causa temporal | Evento | Efeito | Probabilidade | Impacto | Janela de exposição | Resposta | Reserva | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [Preencher] | [Preencher] | [Preencher] | [Escala] | [Escala] | [Período] | [ID/síntese] | [ID/nenhuma] | [Nome] |

### 47.1 Risco de prazo não se reduz a atraso

Inclua riscos de:

- antecipação indevida;
- perda de janela;
- sobreposição insegura;
- ausência de tempo para participação, aprendizagem ou estabilização;
- decisão tardia;
- indisponibilidade sazonal;
- correção sem tempo suficiente;
- dependências correlacionadas;
- fornecedor com compromisso incerto;
- mudança regulatória durante o horizonte;
- obsolescência tecnológica ou de modelo de IA;
- fadiga e sobrecarga.

---

## 48. Cenários de cronograma

| Cenário | Premissas | Capacidade | Sequência | Início | Conclusão | Marcos afetados | Riscos | Custo/efeito | Decisão apoiada |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Referência | [IDs/síntese] | [Preencher] | [Síntese] | [Data] | [Data] | [IDs] | [IDs] | [Preencher] | [Preencher] |
| Restrito | [IDs/síntese] | [Preencher] | [Síntese] | [Data] | [Data] | [IDs] | [IDs] | [Preencher] | [Preencher] |
| Acelerado | [IDs/síntese] | [Preencher] | [Síntese] | [Data] | [Data] | [IDs] | [IDs] | [Preencher] | [Preencher] |
| Evento crítico | [IDs/síntese] | [Preencher] | [Síntese] | [Data] | [Data] | [IDs] | [IDs] | [Preencher] | [Preencher] |

### 48.1 Compressão do cronograma

| Alternativa | Objetos | Método | Ganho estimado | Custo | Risco | Impacto humano | Efeito em qualidade/reversão | Autoridade |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/síntese] | [IDs] | Paralelismo / capacidade adicional / redução autorizada / outra | [Período] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [Nome/papel] |

Compressão só é válida quando preserva escopo autorizado, critérios, segurança, participação, competência, evidência e autoridade. Redução material desses elementos exige decisão própria e, quando arquitetural, retorno ao Módulo 3.

---

## 49. Linha de base temporal para o PI-2

### 49.1 Objeto da aprovação

| Campo | Registro |
| --- | --- |
| Linha de base proposta | [ID/versão] |
| Escopo temporal | [IDs] |
| Horizonte detalhado | [Período] |
| Horizonte macro | [Período] |
| Início comprometido | [Data/condição] |
| Conclusão comprometida | [Data/condição] |
| Marcos comprometidos | [IDs] |
| Janelas críticas | [IDs] |
| Caminho crítico | [IDs/localização] |
| Reservas | [IDs] |
| Premissas críticas | [IDs] |
| Riscos residuais | [IDs] |
| Condições propostas | [IDs ou Nenhuma] |

### 49.2 Verificação antes da aprovação

- [ ] o escopo está vinculado à estrutura vigente;
- [ ] a lógica de rede foi revisada;
- [ ] calendários e capacidade foram confirmados;
- [ ] durações possuem base e confiança;
- [ ] dependências externas possuem responsáveis e respostas;
- [ ] preparação humana e operacional está integrada;
- [ ] gates são previsões, não autorizações presumidas;
- [ ] janelas críticas possuem contingência proporcional;
- [ ] caminho crítico e caminhos quase críticos foram examinados;
- [ ] reservas não escondem trabalho;
- [ ] riscos e consequências de atraso estão visíveis;
- [ ] o horizonte imediato possui detalhe suficiente;
- [ ] mudanças arquiteturais foram devolvidas ao Módulo 3;
- [ ] divergências possuem destino;
- [ ] a autoridade compreende o compromisso assumido.

### 49.3 Pergunta do PI-2

> Escopo, entregas, recursos, responsabilidades, dependências, riscos e planos humanos estão preparados para iniciar a execução?

O cronograma responde apenas pela dimensão temporal dessa pergunta. A verificação integral pertence a `templates/13-verificacao-de-prontidao.md` e a decisão, ao registro da ocorrência aplicável.

### 49.4 Limite da aprovação

Aprovar a linha de base temporal autoriza utilizá-la como referência de planejamento e controle. Não autoriza executar, liberar, aceitar ou transferir operação. Essas decisões permanecem nos gates aplicáveis.

---

## 50. Data de status e atualização factual

| Campo | Registro |
| --- | --- |
| Data de status | [AAAA-MM-DD e hora, se material] |
| Período coberto pela atualização | [Datas] |
| Fonte dos fatos | [Backlog, Kanban, evidências, sistemas] |
| Responsável pela coleta | [Nome] |
| Responsável pela validação | [Nome] |
| Data da última sincronização | [AAAA-MM-DD] |
| Próxima atualização | [Data/cadência] |

### 50.1 Regra da data de status

- fatos anteriores devem estar incorporados ou explicitamente pendentes;
- trabalho futuro não deve aparecer como realizado;
- datas reais exigem fonte;
- trabalho iniciado sem autorização deve ser registrado como desvio, não normalizado;
- ausência de atualização deve aparecer como lacuna de confiança;
- previsão deve ser recalculada a partir da realidade conhecida.

---

## 51. Datas realizadas e variações

| Objeto | Início real | Término real | Fonte | Variação de início | Variação de término | Causa | Efeito | Responsável pelo registro |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Data/hora] | [Data/hora/NA] | [ID/link] | [Período] | [Período] | [ID/síntese] | [Preencher] | [Nome] |

### 51.1 Classes de variação

| Classe | Descrição | Tratamento mínimo |
| --- | --- | --- |
| Sem efeito material | Alteração não afeta marco, janela, risco, gate, custo ou capacidade. | Atualização factual e histórico. |
| Dentro da tolerância | Efeito permanece no envelope temporal autorizado. | Reprevisão, responsável e comunicação definida. |
| Fora da tolerância | Compromisso, caminho crítico ou reserva excede alçada. | Análise, decisão e possível nova linha de base. |
| Arquiteturalmente material | O tratamento exigiria mudar requisito, interface, alçada, risco ou desenho. | Contenção e retorno ao Módulo 3. |

### 51.2 Antecipação

Antecipação também deve ser analisada. Concluir trabalho antes da data pode:

- criar espera ou perda de validade;
- expor pessoas antes da comunicação;
- usar ambiente ainda não autorizado;
- gerar custo de coexistência;
- pressionar liberação sem prontidão;
- alterar sequência de evidências;
- consumir capacidade prevista para outro objeto.

---

## 52. Medição de progresso temporal

### 52.1 Estados preferenciais

| Estado | Critério mínimo | Fonte |
| --- | --- | --- |
| Não iniciado | Condição de entrada ainda não foi acionada. | Backlog/Kanban |
| Pronto | Entrada satisfeita e capacidade disponível, sem execução iniciada. | Backlog/Kanban |
| Em andamento | Trabalho real começou no objeto delimitado. | Registro operacional |
| Bloqueado | O fluxo está interrompido por impedimento explícito. | Kanban/registro integrado |
| Em verificação | Saída candidata está sendo examinada. | Registro de verificação |
| Concluído | Critério local foi atendido com evidência. | Evidência/validação aplicável |
| Rejeitado ou em retrabalho | A saída não atendeu critério e possui tratamento. | Registro de resultado |
| Cancelado | O trabalho deixou de prosseguir por decisão. | Registro decisório |

### 52.2 Percentual auxiliar

Percentual pode ser usado quando houver regra objetiva e estável.

| Objeto | Regra de cálculo | Numerador | Denominador | Fonte | Limitação | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Preencher] | [Preencher] | [Preencher] | [Fonte] | [Preencher] | [Nome] |

É proibido utilizar percentual subjetivo como única prova de conclusão, capacidade, prontidão ou aceite.

### 52.3 Progresso por marco e condição

| Objeto agregado | Marcos/condições | Atendidos | Não atendidos | Em risco | Bloqueados | Leitura responsável |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [IDs] | [IDs] | [IDs] | [IDs] | [IDs] | [Síntese] |

---

## 53. Previsão vigente

| Objeto | Previsão anterior | Previsão vigente | Diferença | Fatos incorporados | Premissas | Confiança | Efeito em marcos/gates | Data |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Início/fim] | [Início/fim] | [Período] | [IDs/síntese] | [IDs] | [Nível] | [IDs/síntese] | [AAAA-MM-DD] |

### 53.1 Reprevisão

A previsão deve ser revista quando:

- fato realizado difere materialmente da hipótese anterior;
- dependência muda de estado;
- capacidade ou calendário muda;
- risco ocorre ou muda de exposição;
- decisão é adiada, condicionada ou rejeitada;
- trabalho emergente é autorizado;
- evidência exige correção ou nova observação;
- janela é alterada ou perdida;
- caminho crítico muda;
- reserva é consumida;
- o horizonte posterior entra em detalhamento.

### 53.2 Previsão sem alteração da base

Atualizar a previsão não autoriza alterar a linha de base. A variação permanece visível até decisão de rebaselining aplicável.

---

## 54. Replanejamento e controle de mudanças

| Mudança | Gatilho | Objetos | Tipo | Previsão anterior | Proposta | Efeito | Dentro da alçada? | Autoridade | Decisão | Sincronização |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/evento] | [IDs] | Factual / executiva / linha de base / arquitetural | [Preencher] | [Preencher] | [Preencher] | Sim / não / condicional | [Nome/papel] | [ID/pendente] | [Fontes] |

### 54.1 Perguntas de impacto

1. Que marco, janela ou gate muda?
2. O caminho crítico ou quase crítico muda?
3. Que folga ou reserva será consumida?
4. Que pessoas, fornecedores ou ambientes serão afetados?
5. A carga permanece sustentável?
6. Comunicação, treinamento ou participação perderão tempo necessário?
7. Segurança, privacidade, conformidade, reversão ou evidência serão reduzidas?
8. A estabilização ou transição será comprimida?
9. O custo ou risco excede alçada?
10. A solução exige alterar arquitetura?

### 54.2 Nova linha de base temporal

| Campo | Registro |
| --- | --- |
| Linha de base anterior | [ID/versão] |
| Nova linha de base | [ID/versão] |
| Motivo | [ID/síntese] |
| Comparação | [Caminho/relatório] |
| Objetos alterados | [IDs] |
| Riscos e condições | [IDs] |
| Autoridade | [Nome/papel] |
| Decisão | [ID/link] |
| Data de vigência | [AAAA-MM-DD] |
| Destino da base anterior | [Caminho preservado] |

Rebaselining não deve ser usado para transformar atraso em conformidade histórica.

---

## 55. Marco atrasado ou janela perdida

### 55.1 Resposta mínima

| Campo | Registro |
| --- | --- |
| Marco/janela | [ID] |
| Compromisso original | [Data/condição] |
| Estado real | [Preencher] |
| Causa | [ID/síntese] |
| Efeito imediato | [Preencher] |
| Objetos afetados | [IDs] |
| Risco adicional | [IDs] |
| Proteção aplicada | [Preencher] |
| Nova previsão | [Data/condição ou não determinada] |
| Autoridade necessária | [Nome/papel] |
| Comunicação | [ID/canal] |
| Decisão | [ID/pendente] |

### 55.2 Alternativas legítimas

- remover impedimento sem mudar arquitetura;
- reordenar trabalho dentro da lógica e alçada;
- utilizar reserva conforme critério;
- mobilizar capacidade adicional sustentável;
- reduzir escopo somente mediante decisão aplicável;
- reagendar janela com efeitos explícitos;
- suspender objeto afetado;
- reverter ou cancelar;
- retornar ao Módulo 3.

“Trabalhar mais rápido” sem indicar mecanismo, capacidade e risco não constitui resposta governável.

---

## 56. Suspensão, cancelamento, reversão e retomada

| Ação | Objeto | Início | Motivo | Estado preservado | Trabalho interrompido | Proteções | Condição de retomada/encerramento | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Tipo] | [IDs] | [Data/hora] | [ID/síntese] | [Preencher] | [IDs] | [Preencher] | [Preencher] | [Nome/papel] | [ID/link] |

### 56.1 Efeito temporal

| Objeto | Previsão antes da ação | Tratamento durante a ação | Nova previsão | Calendário | Dependências afetadas | Próxima revisão |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Datas] | Congelado / continua / encerrado / condicional | [Datas/ND] | [ID] | [IDs] | [Data/gatilho] |

Retomada exige verificar se entradas, pessoas, acessos, versões, riscos e condições permanecem válidos. O tempo decorrido pode invalidar preparação anterior.

---

## 57. Sincronização com a Estrutura Analítica

| Evento na estrutura | Efeito esperado no cronograma | Responsável | Limite de sincronização | Registro |
| --- | --- | --- | --- | --- |
| Novo pacote autorizado | Avaliar duração, dependências, capacidade e posição temporal. | [Nome] | [Período] | [ID/versão] |
| Pacote dividido ou combinado | Preservar critérios e recalcular a rede. | [Nome] | [Período] | [ID/versão] |
| Entrega retirada | Remover apenas com decisão e avaliar sucessoras. | [Nome] | [Período] | [ID] |
| Interface descoberta | Criar trabalho e dependências sem duplicar objeto. | [Nome] | [Período] | [ID] |
| Mudança arquitetural | Suspender trecho afetado e retornar ao Módulo 3. | [Nome] | Imediato | [ID] |

### 57.1 Teste de cobertura temporal

| Tipo de nó | Total aplicável | Agendado | Condicional | Não agendado com tratamento | Lacuna |
| --- | --- | --- | --- | --- | --- |
| Incremento | [N] | [N] | [N] | [N] | [N] |
| Entrega | [N] | [N] | [N] | [N] | [N] |
| Pacote de trabalho | [N] | [N] | [N] | [N] | [N] |
| Trabalho humano/organizacional | [N] | [N] | [N] | [N] | [N] |
| Trabalho técnico/informacional | [N] | [N] | [N] | [N] | [N] |

Cobertura percentual não substitui materialidade. Um único pacote crítico sem posição temporal pode impedir o `PI-2` do objeto afetado.

---

## 58. Sincronização com backlog e Kanban

| Elemento | Cronograma | Backlog/Kanban | Regra de sincronização |
| --- | --- | --- | --- |
| Pacote/entrega | Mantém compromisso temporal e rede. | Mantém itens executáveis e fluxo. | IDs canônicos comuns. |
| Prioridade | Recebe efeito sobre sequência e marcos. | Governa ordem de puxada conforme políticas. | Divergência material exige decisão. |
| Estado | Usa fatos confirmados na data de status. | É fonte do fluxo atual. | Atualização na cadência definida. |
| Bloqueio | Mostra efeito em previsão e caminho. | Mostra impedimento e envelhecimento. | Bloqueio crítico é escalado. |
| Data | Mantém base, previsão e realizado. | Pode manter compromisso local. | Cronograma é fonte temporal mestre. |
| Trabalho emergente | Avalia efeito antes de compromisso. | Registra demanda e estado. | Origem e autorização obrigatórias. |

### 58.1 Registro de divergências

| ID | Objeto | Cronograma informa | Kanban informa | Risco | Fonte prevalente | Ação | Responsável | Limite |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID] | [Preencher] | [Preencher] | [Preencher] | [Regra] | [Preencher] | [Nome] | [Data] |

### 58.2 Regra contra atualização dupla

Não manter manualmente o mesmo estado detalhado em duas fontes quando integração ou referência resolver. Defina qual fonte registra o fato e qual consome a informação.

---

## 59. Sincronização com a Matriz de Rastreabilidade

| Objeto temporal | Vínculos esperados | Destino | Estado | Responsável |
| --- | --- | --- | --- | --- |
| Marco | Objetos realizados, evidência, decisão e gate. | [IDs] | [Estado] | [Nome] |
| Janela | Objeto, risco, contingência e autoridade. | [IDs] | [Estado] | [Nome] |
| Dependência | Origem, predecessor, sucessor e resposta. | [IDs] | [Estado] | [Nome] |
| Restrição | Fonte, objeto afetado e autoridade. | [IDs] | [Estado] | [Nome] |
| Linha de base temporal | Plano, estrutura, decisão e versão. | [IDs] | [Estado] | [Nome] |
| Variação material | Causa, objetos, decisão e nova previsão. | [IDs] | [Estado] | [Nome] |

### 59.1 Relações usuais

- objeto **é_agendado_em** compromisso temporal;
- marco **verifica_condição_de** objeto;
- dependência **condiciona** início ou término;
- janela **permite_exposição_de** objeto;
- restrição **limita** objeto;
- evidência **demonstra** marco;
- decisão **autoriza** linha de base ou mudança;
- variação **afeta** marco, gate ou transição.

O vocabulário canônico dos vínculos pertence à matriz. Este template apenas indica relações necessárias.

---

## 60. Sincronização com registros e planos especializados

| Fonte especializada | Informação recebida | Informação devolvida | Responsável | Cadência/gatilho |
| --- | --- | --- | --- | --- |
| Registro integrado de controle | Riscos, impedimentos, dependências e mudanças. | Efeito temporal, caminho e limites. | [Nome] | [Cadência/evento] |
| Plano de comunicação | Públicos, eventos e confirmação. | Marcos e janelas que exigem comunicação. | [Nome] | [Marco/evento] |
| Plano de treinamento | Competências, públicos e verificação. | Datas necessárias antes de uso/gate. | [Nome] | [Onda] |
| Plano de mudança | Impactos, participação e adoção. | Sequência e tempo de absorção. | [Nome] | [Onda/evento] |
| Plano de piloto/virada/reversão | Comando, contingência e critérios. | Janelas, gates e reservas. | [Nome] | [PI-3/liberação] |
| Verificação de prontidão | Lacunas e condições. | Objeto e data pretendida. | [Nome] | [PI-2/PI-3] |
| Validação e aceite | Evidências e resultados. | Períodos de observação e ocorrências de PI-4. | [Nome] | [Incremento] |
| Transição para operação | Preparação e aceite bilateral. | Estabilização e ocorrência de PI-5. | [Nome] | [PI-5] |

### 60.1 Divergência entre fontes

Quando um plano especializado exigir tempo incompatível com o cronograma:

1. preserve o requisito ou critério material;
2. registre a divergência;
3. analise capacidade, sequência, risco e alternativas;
4. atualize a previsão;
5. submeta mudança de compromisso à autoridade;
6. não comprima silenciosamente o plano especializado.

---

## 61. Governança e cadências

| Cadência/fórum | Finalidade | Participantes | Entradas | Saídas | Frequência/gatilho | Autoridade | Registro |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Atualização factual | Incorporar fatos e recalcular previsão. | [Papéis] | Kanban/evidências | Previsão vigente | [Cadência] | [Papel] | [Fonte] |
| Revisão do cronograma | Examinar rede, variações, riscos e capacidade. | [Papéis] | Cronograma/registro | Ações e escalonamentos | [Cadência] | [Papel] | [Fonte] |
| Revisão executiva | Decidir compromissos e tolerâncias. | [Papéis] | Síntese/decisões | Decisões | [Cadência/evento] | [Papel] | [Fonte] |
| Revisão de onda | Autorizar próximo detalhamento e exposição. | [Papéis] | Evidências/aprendizagem | Replanejamento/gate | [Evento] | [Papel] | [Fonte] |

### 61.1 Cadência por criticidade

| Condição | Cadência mínima | Escalonamento |
| --- | --- | --- |
| Caminho crítico estável | [Período] | [Regra] |
| Marco em risco | [Período menor/evento] | [Nome/papel] |
| Janela crítica próxima | [Período/evento] | [Nome/papel] |
| Dependência externa não confirmada | [Período] | [Nome/papel] |
| Suspensão ou reversão | Imediata e conforme plano | [Nome/papel] |

---

## 62. Papéis e responsabilidades

| Papel | Responsabilidade temporal | Pode decidir | Não pode decidir |
| --- | --- | --- | --- |
| Autoridade da implantação | Aprovar compromisso, tolerância, nova base e resposta dentro da alçada. | Prioridade, recurso, risco e compromisso autorizados. | Mudança arquitetural reservada ao Módulo 3. |
| Responsável pela implantação | Integrar cronograma, capacidade, riscos e planos. | Ajustes executivos dentro da alçada. | Reduzir critérios ou aceitar risco fora da alçada. |
| Responsável pelo cronograma | Construir rede, incorporar fatos, calcular previsão e revelar variações. | Atualização factual conforme política. | Alterar compromissos ou fatos por conveniência. |
| Responsável pela arquitetura | Esclarecer dependências e avaliar materialidade. | Recomendar retorno ou correção. | Controlar execução cotidiana. |
| Responsável por pacote | Estimar, confirmar capacidade e informar fatos. | Organizar trabalho local dentro da política. | Ocultar atraso ou redefinir marco. |
| Custodiante | Preservar versões, acessos e linha de base. | Aplicar controle documental. | Modificar conteúdo material sem autoridade. |
| Responsável operacional | Informar janelas, capacidade e condições de sustentação. | Manifestar prontidão e aceite na alçada. | Receber responsabilidade silenciosamente. |
| Verificador | Examinar lógica, evidência ou condição. | Declarar resultado de verificação. | Aprovar quando houver segregação. |

### 62.1 Matriz de autoridade temporal

| Decisão | Propõe | Analisa | Decide | Registra | Comunica | Limite |
| --- | --- | --- | --- | --- | --- | --- |
| Aprovar linha de base temporal | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Consumir reserva | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Alterar marco comprometido | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Suspender caminho afetado | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |
| Retornar ao Módulo 3 | [Papel] | [Papéis] | [Papel] | [Papel] | [Papel] | [Alçada] |

---

## 63. Indicadores de saúde temporal

| Indicador | Definição | Fonte | Frequência | Limite/sinal | Decisão apoiada | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Marcos no prazo | Marcos alcançados até compromisso / marcos vencidos aplicáveis. | Cronograma/evidências | [Cadência] | [Preencher] | Replanejar/escalonar | [Nome] |
| Variação de conclusão | Diferença entre base e previsão vigente. | Cronograma | [Cadência] | [Preencher] | Renegociar/ajustar | [Nome] |
| Consumo de reserva | Reserva consumida e saldo por exposição. | Registro de reserva | [Cadência] | [Preencher] | Conter/escalonar | [Nome] |
| Dependências críticas sem confirmação | Quantidade e proximidade do limite. | Registro integrado | [Cadência] | [Preencher] | Escalonar/alternar | [Nome] |
| Folga do caminho quase crítico | Menor folga fora do caminho crítico. | Rede | [Cadência] | [Preencher] | Proteger sequência | [Nome] |
| Idade de bloqueio crítico | Tempo desde o início do bloqueio. | Kanban | [Cadência] | [Preencher] | Remover/escalonar | [Nome] |
| Estabilidade de previsão | Mudança da previsão entre revisões. | Histórico | [Cadência] | [Preencher] | Revisar estimativa/lógica | [Nome] |
| Trabalho não agendado crítico | Pacotes críticos sem posição ou tratamento. | EAI/cronograma | [Cadência] | Qualquer lacuna material | Completar/bloquear PI-2 | [Nome] |

### 63.1 Leituras protegidas

- indicador não substitui exame de causas;
- cumprimento de prazo não prova qualidade ou capacidade;
- atraso não deve ser atribuído automaticamente a desempenho individual;
- metas não devem incentivar ocultação de bloqueios;
- comparação entre equipes exige contexto, calendário e natureza do trabalho;
- indicador deve apoiar decisão definida.

### 63.2 Síntese de saúde

| Dimensão | Estado | Evidência | Tendência | Limite | Ação | Responsável |
| --- | --- | --- | --- | --- | --- | --- |
| Rede e caminho crítico | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Marcos e janelas | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Capacidade e carga | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Dependências externas | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Preparação humana | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |
| Reserva e risco | [Estado] | [Fonte] | [Tendência] | [Preencher] | [Preencher] | [Nome] |

---

## 64. Evidências e proveniência

| Registro temporal | Objeto | Afirmação | Fonte | Data/período | Produtor | Verificador | Limitação | Localização |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/tipo] | [ID] | [Preencher] | [ID/link] | [Data] | [Nome/sistema] | [Nome/NA] | [Preencher] | [Caminho] |

### 64.1 Fatos que exigem fonte

- data real de início ou término;
- marco alcançado;
- dependência confirmada;
- capacidade disponível;
- calendário ou indisponibilidade;
- risco ocorrido;
- reserva consumida;
- gate decidido;
- janela aberta, encerrada ou perdida;
- suspensão, reversão ou retomada;
- conclusão da estabilização;
- aceite operacional.

### 64.2 Correção de fato

| Registro | Valor anterior | Valor correto | Evidência | Motivo do erro | Efeito | Responsável | Data |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [ID/campo] | [Preencher] | [Preencher] | [ID/link] | [Preencher] | [Preencher] | [Nome] | [AAAA-MM-DD] |

Correção legítima preserva histórico. Ela não deve ser usada para aproximar o realizado da linha de base.

---

## 65. Participação da inteligência artificial

A IA pode apoiar:

- detecção de dependências ausentes ou circulares;
- verificação de identificadores e referências;
- cálculo ou conferência de rede, folgas e caminhos;
- comparação entre linha de base, previsão e realizado;
- simulação de cenários;
- identificação de conflitos de calendário e capacidade;
- síntese de variações e riscos;
- preparação de perguntas de revisão;
- sincronização assistida entre cronograma, backlog e matriz;
- detecção de inconsistências e campos não atualizados.

### 65.1 Condições de uso

| Uso | Entradas autorizadas | Saída esperada | Validação humana | Registro |
| --- | --- | --- | --- | --- |
| Conferência de rede | [Dados/limites] | [Alertas/cálculo] | Responsável pelo cronograma | [Fonte] |
| Cenário | [Dados/limites] | [Alternativas] | Responsável e especialistas | [Fonte] |
| Síntese | [Fontes autorizadas] | [Resumo] | Autor do registro | [Fonte] |
| Sincronização | [Fontes autorizadas] | [Proposta de atualização] | Custodiante/responsável | [Fonte] |

### 65.2 Limites não delegáveis

A IA não pode:

- assumir compromisso;
- confirmar disponibilidade sem fonte;
- alterar linha de base;
- decidir prioridade, risco ou tolerância;
- autorizar compressão;
- declarar prontidão;
- decidir gate;
- liberar, aceitar ou transferir operação;
- redefinir arquitetura;
- ocultar incerteza sob uma data precisa.

### 65.3 Proveniência de cálculo assistido

| Campo | Registro |
| --- | --- |
| Sistema/modelo | [Nome/versão] |
| Data | [AAAA-MM-DD] |
| Entradas | [Fontes/versões] |
| Transformação | [Descrição] |
| Saída utilizada | [Localização] |
| Limitações | [Preencher] |
| Revisor humano | [Nome/papel] |
| Decisão humana | [ID/NA] |

---

## 66. Proporcionalidade

| Escala | Forma do cronograma | Controles mínimos |
| --- | --- | --- |
| Focal | Tabela reduzida de objetos, marcos, dependências, janela e fatos. | Origem, responsável, linha de base, previsão, realizado, risco, gate e histórico. |
| Funcional | Rede completa por incrementos, planos humanos e técnicos sincronizados. | Calendários, capacidade, caminho crítico, reservas, variações e governança. |
| Sistêmica | Cronogramas coordenados por programa, projetos e ondas, com cenários e controles ampliados. | Múltiplas bases, interfaces, dependências externas, gates repetidos e auditoria. |

### 66.1 Intensificadores de controle

Utilize maior detalhe quando houver:

- impacto sobre muitas pessoas ou unidades;
- janela rígida ou ponto de não retorno;
- operação crítica;
- obrigação legal, contratual ou regulatória;
- dados sensíveis;
- tecnologia ou IA material;
- migração ou desativação irreversível;
- dependências externas numerosas;
- múltiplos fusos ou calendários;
- competência rara;
- baixa reversibilidade;
- período de estabilização longo;
- custo elevado de atraso ou antecipação.

### 66.2 Combinação de artefatos

Uma implantação focal pode combinar cronograma, backlog e registro integrado em um único arquivo, desde que permaneçam distinguíveis:

- compromisso temporal;
- estado do fluxo;
- risco, impedimento, dependência ou mudança;
- fonte oficial de cada fato;
- autoridade e histórico.

---

## 67. Versão reduzida para implantação focal

### 67.1 Identificação

| Campo | Registro |
| --- | --- |
| ID do cronograma | `CRM-IMP-AAAA-NNN` |
| Implantação | `IMP-AAAA-NNN` |
| Plano/EAI | [IDs/versões] |
| Linha de base temporal | [ID/versão] |
| Fuso/calendário | [Preencher] |
| Data de status | [AAAA-MM-DD] |
| Responsável | [Nome] |
| Autoridade | [Nome/papel] |
| Versão/estado | [Preencher] |

### 67.2 Cronograma focal

| Objeto | Origem | Responsável | Predecessora/condição | Início-base | Término-base | Previsão atual | Realizado | Estado/evidência |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [ID] | [ID/fonte] | [Nome] | [ID/condição] | [Data] | [Data] | [Datas] | [Datas/NA] | [Estado/ID] |

### 67.3 Marcos, janela e gates

| Tipo | ID | Condição | Data/janela | Autoridade | Evidência | Consequência se não atendido |
| --- | --- | --- | --- | --- | --- | --- |
| Marco | [ID] | [Preencher] | [Data] | [Nome/papel] | [ID/tipo] | [Preencher] |
| Janela | [ID] | [Preencher] | [Início/fim] | [Nome/papel] | [ID/tipo] | [Preencher] |
| Gate | [ID] | [Objeto/condição] | [Data prevista] | [Nome/papel] | [Fonte] | [Trabalho bloqueado] |

### 67.4 Dependências, riscos e variações

| ID | Tipo | Objeto | Limite | Resposta | Responsável | Estado/decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | Dependência / risco / variação / mudança | [IDs] | [Data/condição] | [Preencher] | [Nome] | [Estado/ID] |

### 67.5 Regra de uso

A versão reduzida não se aplica quando a simplificação impede reconstruir caminho crítico, janelas, preparação humana, reversão, gates repetidos ou transição operacional.

---

## 68. Revisão consolidada

### 68.1 Origem e escopo

- [ ] implantação, termo, plano, estrutura e linha de base estão identificados;
- [ ] versões e localizações são recuperáveis;
- [ ] objetos agendados pertencem ao escopo ou possuem autorização;
- [ ] trabalho sem origem possui tratamento;
- [ ] objetos críticos sem posição temporal estão visíveis.

### 68.2 Lógica e calendário

- [ ] predecessoras e sucessoras representam condições reais;
- [ ] não existem ciclos não governados;
- [ ] calendários, fusos e exceções estão declarados;
- [ ] durações possuem método, base e confiança;
- [ ] esperas e antecipações possuem fundamento;
- [ ] restrições não estão disfarçadas de dependências;
- [ ] capacidade e carga foram examinadas.

### 68.3 Marcos, janelas e caminho

- [ ] marcos possuem condição observável e evidência;
- [ ] janelas possuem pré-condições, ponto de não retorno e contingência;
- [ ] gates aparecem como ocorrências previstas, não decisões presumidas;
- [ ] caminho crítico foi calculado e revisado;
- [ ] caminhos quase críticos estão visíveis;
- [ ] folgas e reservas possuem regra de uso;
- [ ] consequências de atraso e antecipação estão explícitas.

### 68.4 Pessoas, operação e segurança

- [ ] participação, comunicação e treinamento estão no tempo da implantação;
- [ ] carga humana é sustentável;
- [ ] dados, documentos, tecnologia e IA possuem tempo de preparação e controle;
- [ ] migração, reversão e continuidade são executáveis;
- [ ] validação possui período suficiente;
- [ ] estabilização não foi removida para acomodar atraso;
- [ ] transição depende de aceite operacional.

### 68.5 Controle e memória

- [ ] linha de base, previsão e realizado estão separados;
- [ ] data de status está clara;
- [ ] fatos possuem fonte;
- [ ] variações e mudanças possuem decisão ou destino;
- [ ] cronograma e Kanban estão sincronizados;
- [ ] matriz e registros especializados receberam os vínculos necessários;
- [ ] versões anteriores permanecem preservadas;
- [ ] participação da IA está registrada.

---

## 69. Teste de reconstrução

Uma pessoa autorizada que não participou da elaboração deve conseguir responder:

1. Que implantação e arquitetura este cronograma realiza?
2. Qual linha de base temporal foi aprovada?
3. Qual é a previsão vigente e a data de status?
4. Que fatos já ocorreram e onde estão evidenciados?
5. Quais objetos integram o caminho crítico?
6. Que marcos e janelas são decisivos?
7. Que dependências externas permanecem abertas?
8. Que capacidade e calendários foram considerados?
9. Que premissas sustentam as principais datas?
10. Que preparação humana e operacional antecede a execução e a liberação?
11. Que gates estão previstos e que trabalho permanece bloqueado?
12. Que reservas existem e quem pode utilizá-las?
13. Que variações ocorreram e como foram tratadas?
14. O que exigiria nova linha de base?
15. O que exigiria retorno ao Módulo 3?
16. Como o cronograma se sincroniza com o fluxo real?
17. Quando a estabilização pode terminar?
18. Que condição permite a transição para operação?

### 69.1 Resultado

| Dimensão | Resultado | Evidência | Lacuna | Responsável | Limite |
| --- | --- | --- | --- | --- | --- |
| Origem | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |
| Lógica temporal | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |
| Compromissos | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |
| Realidade e variação | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |
| Autoridade e gates | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |
| Continuidade | Conforme / parcial / não conforme | [Fonte] | [Preencher] | [Nome] | [Data] |

---

## 70. Antipadrões

Evitar:

- agendar antes de compreender o objeto;
- copiar a árvore analítica e preencher datas sem rede;
- iniciar todos os pacotes na mesma data;
- fixar datas para forçar o cálculo;
- omitir calendários, férias e carga operacional;
- tratar espera por decisão como tempo de produção;
- usar duração como sinônimo de esforço;
- esconder dependência externa em uma atividade genérica;
- chamar reunião de marco sem condição observável;
- considerar gate aprovado porque a data chegou;
- registrar “100%” sem critério e evidência;
- mover a linha de base quando surge atraso;
- distribuir reserva invisível em todas as tarefas;
- consumir estabilização para concluir produção;
- comprimir comunicação, participação ou treinamento;
- sobrepor trabalho incompatível para aparentar recuperação;
- ignorar antecipação problemática;
- deixar caminho crítico desatualizado;
- usar cronograma sem comparar com bloqueios reais;
- transformar toda urgência em prioridade máxima;
- responsabilizar pessoas por restrições sistêmicas ocultas;
- planejar reversão sem tempo executável;
- transferir operação na data final sem aceite;
- permitir que IA assuma compromisso ou decisão;
- replanejar mudança arquitetural sem retorno ao Módulo 3.

---

## 71. Sinais de qualidade

Um cronograma de qualidade:

- possui identidade, versão, estado, linha de base e data de status;
- referencia objetos oficiais sem duplicá-los;
- declara calendários, capacidade e base de estimativa;
- representa relações reais e não apenas datas;
- distingue marco, janela, gate, entrega e atividade;
- torna caminho crítico e quase crítico compreensíveis;
- preserva folgas e reservas com autoridade;
- integra preparação humana, técnica e operacional;
- mostra fatos, previsões e variações sem reescrever o passado;
- comunica incerteza sem produzir falsa precisão;
- revela consequências de atraso, antecipação e compressão;
- permanece coerente com backlog, matriz e registros;
- prepara decisão sem substituí-la;
- protege estabilização, reversão e transição;
- pode ser reconstruído por outra pessoa autorizada.

### 71.1 Métricas auxiliares de qualidade

| Métrica | Cálculo ou teste | Uso | Limite |
| --- | --- | --- | --- |
| Cobertura temporal | Objetos aplicáveis com posição ou tratamento / objetos aplicáveis. | Localizar lacunas. | Materialidade prevalece. |
| Dependências qualificadas | Dependências com condição, responsável e resposta / dependências materiais. | Avaliar governabilidade. | Não mede qualidade da condição. |
| Marcos verificáveis | Marcos com critério, evidência e autoridade / marcos totais. | Revisar qualidade. | Não prova alcance. |
| Fatos com fonte | Datas reais com evidência / datas reais registradas. | Avaliar confiabilidade. | Fonte pode exigir exame. |
| Estabilidade da previsão | Variação entre previsões em período definido. | Detectar incerteza ou falha de atualização. | Mudança legítima pode ser alta. |

---

## 72. Exemplo aplicado — sistema editorial

### 72.1 Contexto

Uma linha de base autorizada define a capacidade de transformar ideias em conteúdos planejados, produzidos, revisados, aprovados e publicados com autoria, critérios recuperáveis e disponibilidade real da equipe.

| Referência | ID |
| --- | --- |
| Implantação | `IMP-2026-001` |
| Capacidade | `CAP-ARQ-004` |
| Incremento | `IMP-2026-001-INC-001` |
| Entrega central | `IMP-2026-001-ENT-003` |
| Pacote de trabalho | `IMP-2026-001-PT-005` |
| Cronograma | `CRM-IMP-2026-001` |
| Linha de base temporal | `IMP-2026-001-LBT-001` |

### 72.2 Marcos e janela

| ID | Condição | Compromisso | Dependências | Evidência | Autoridade |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-MAR-001` | Fluxo mínimo configurado e verificado no ambiente de teste. | 2026-09-10 | `IMP-2026-001-ENT-001`, `IMP-2026-001-ENT-002` | [ID de evidência] | Responsável pela implantação |
| `IMP-2026-001-MAR-002` | Pessoas do piloto demonstraram a competência definida. | 2026-09-17 | Plano de treinamento | [ID de evidência] | Autoridade definida |
| `IMP-2026-001-GAT-003` | PI-3 do piloto decidido. | Previsão: 2026-09-18 | Marcos 001 e 002, suporte e reversão | Registro de prontidão | Decisor de PI-3 |

| Janela | Objeto | Início | Fim | Pré-condições | Retorno |
| --- | --- | --- | --- | --- | --- |
| `IMP-2026-001-JAN-001` | Liberação do piloto editorial | 2026-09-21 09:00 | 2026-09-21 11:00 | PI-3 aprovado; cópia segura; suporte disponível | [Plano de retorno] |

### 72.3 Dependência qualificada

| Campo | Registro |
| --- | --- |
| ID | `IMP-2026-001-DEP-004` |
| Predecessora | `IMP-2026-001-PT-005` |
| Sucessora | `IMP-2026-001-MAR-001` |
| Relação | TI |
| Condição | Regras e exceções configuradas, verificadas e documentadas. |
| Responsável | [Nome] |
| Efeito se não atendida | Marco 001 entra em risco; PI-3 permanece bloqueado. |

### 72.4 Variação sem apagamento da base

Se a competência do grupo não for demonstrada até 17 de setembro, o cronograma deverá:

1. registrar o resultado e a evidência negativa;
2. manter 17 de setembro como compromisso da linha de base;
3. calcular a nova previsão;
4. avaliar a janela de piloto e o suporte disponível;
5. decidir entre reforço, nova prática, reagendamento ou redução autorizada do escopo;
6. impedir que a data prevista do PI-3 produza liberação automática.

### 72.5 Limite do exemplo

O exemplo demonstra relações temporais. Ele não prescreve duração universal, não decide os gates e não transforma um sistema editorial específico em modelo obrigatório para outras implantações.

---

## 73. Manifestações e aprovações

### 73.1 Responsável pelo cronograma

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Conforme / conforme com ressalvas / não conforme |
| Escopo examinado | [Preencher] |
| Ressalvas | [IDs ou Nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 73.2 Responsável pela implantação

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Manifestação | Aprovar para submissão / devolver / condicionar / suspender |
| Compromissos reconhecidos | [IDs] |
| Riscos e condições | [IDs] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 73.3 Autoridade da implantação

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Alçada | [Preencher] |
| Resultado | Aprovar base / aprovar com condições / rejeitar / devolver |
| Linha de base aprovada | [ID/versão] |
| Condições | [IDs ou Nenhuma] |
| Tolerâncias | [Preencher] |
| Data | [AAAA-MM-DD] |
| Decisão | [ID/link] |

### 73.4 Responsável pela arquitetura

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Verificação | Intenção preservada / ressalva / retorno necessário |
| Objetos examinados | [IDs] |
| Ressalvas | [IDs ou Nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 73.5 Responsável operacional indicado

| Campo | Registro |
| --- | --- |
| Nome/papel | [Preencher] |
| Verificação | Calendários, janelas, carga e transição examinados? |
| Condições | [IDs ou Nenhuma] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

### 73.6 Aprovações especializadas

| Especialidade | Pessoa/papel | Escopo | Resultado | Condições | Data | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Segurança/jurídico/dados/IA/finanças/outra] | [Nome] | [IDs] | [Resultado] | [IDs] | [AAAA-MM-DD] | [ID/link] |

### 73.7 Divergências preservadas

| ID | Pessoa/papel | Divergência | Fundamento | Efeito temporal | Tratamento | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| [ID] | [Nome] | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Estado] |

### 73.8 Limite da aprovação

As manifestações aprovam o cronograma dentro de seus objetos e alçadas. Elas não substituem `PI-2`, `PI-3`, `PI-4`, `PI-5` nem decisões especializadas futuras.

---

## 74. Controle de versões

### 74.1 Versão vigente

| Campo | Registro |
| --- | --- |
| Versão | [N.N] |
| Estado | [Estado] |
| Data de status | [AAAA-MM-DD] |
| Linha de base aplicável | [ID/versão] |
| Previsão calculada em | [AAAA-MM-DD] |
| Escopo coberto | [IDs] |
| Alteração principal | [Síntese] |
| Responsável | [Nome] |
| Aprovação | [ID/NA] |
| Localização | [Caminho] |

### 74.2 Histórico

| Versão | Data | Estado | Linha de base | Alteração | Motivo | Responsável | Decisão | Substitui |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [N.N] | [AAAA-MM-DD] | [Estado] | [ID/versão] | [Síntese] | [ID/síntese] | [Nome] | [ID/NA] | [Versão] |

### 74.3 Regras de versionamento

- atualização factual pode utilizar incremento menor conforme política;
- alteração de lógica, previsão material, calendário ou capacidade deve produzir versão recuperável;
- nova linha de base exige decisão e cópia de preservação;
- datas reais corrigidas preservam valor anterior e evidência;
- arquivo substituído não deve ser apagado;
- exportações derivadas devem declarar versão, data de status e linha de base.

---

## 75. Critérios de conclusão do cronograma

O cronograma pode ser considerado concluído para planejamento do horizonte declarado quando:

- possui identidade, versão, estado e fonte oficial;
- entradas e precedência foram verificadas;
- linha de base temporal está proposta ou aprovada conforme o estágio;
- objetos materiais possuem posição temporal ou tratamento;
- rede, calendários, durações e capacidade são suficientes para o horizonte;
- marcos, janelas e gates previstos estão delimitados;
- dependências críticas possuem responsáveis e respostas;
- caminho crítico e caminhos quase críticos estão visíveis;
- folgas, reservas, premissas, restrições e riscos estão governados;
- preparação humana, técnica e operacional está integrada;
- reversão, validação, estabilização e transição possuem tempo proporcional;
- cronograma, backlog e matriz podem ser sincronizados;
- fatos, previsão e linha de base permanecem distintos;
- aprovações, ressalvas e divergências estão registradas;
- o teste de reconstrução é satisfatório;
- nenhuma mudança arquitetural permanece escondida em replanejamento.

### 75.1 Resultado

- [ ] Concluído para o horizonte declarado
- [ ] Concluído com condições
- [ ] Requer complementação
- [ ] Requer replanejamento
- [ ] Requer decisão de autoridade
- [ ] Requer retorno ao Módulo 3
- [ ] Suspenso
- [ ] Cancelado

| Campo | Registro |
| --- | --- |
| Horizonte examinado | [Período/objetos] |
| Resultado | [Selecionar] |
| Condições/lacunas | [IDs ou Nenhuma] |
| Trabalho que pode avançar | [IDs/tipos] |
| Trabalho que permanece bloqueado | [IDs/tipos] |
| Próximo movimento permitido | [Organizar backlog / completar planos / verificar prontidão / submeter PI-2 / replanejar / retornar / outro] |
| Responsável | [Nome] |
| Autoridade | [Nome/papel] |
| Data | [AAAA-MM-DD] |
| Evidência | [ID/link] |

Conclusão do cronograma demonstra suficiência do instrumento temporal para o horizonte. Não demonstra prontidão material, execução, capacidade implantada, aceite ou transição.

---

## 76. Registro final do template

| Campo | Registro |
| --- | --- |
| Identificador do template | `templates/04-cronograma-mestre-da-implantacao.md` |
| Módulo | 4 — Implantação |
| Tipo | Template operacional |
| Função | Governar compromissos e relações temporais da implantação |
| Entrada principal | Plano e Estrutura Analítica vigentes |
| Saída principal | Cronograma Mestre preenchido, versionado e sincronizável |
| Gate relacionado | `PI-2`, com uso continuado em `PI-3`, `PI-4` e `PI-5` |
| Documento anterior | `templates/03-estrutura-analitica-da-implantacao.md` |
| Documento seguinte | `templates/05-backlog-e-quadro-kanban-da-implantacao.md` |
| Fonte oficial | Repositório do Sistema Operacional do Estúdio LICHTARA |
| Responsabilidade final | Humana |

### Histórico de versões do template

| Versão | Data | Alteração | Responsável |
| --- | --- | --- | --- |
| 1.0 | 2026-08-03 | Criação integral do Cronograma Mestre da Implantação. | Estúdio LICHTARA |
