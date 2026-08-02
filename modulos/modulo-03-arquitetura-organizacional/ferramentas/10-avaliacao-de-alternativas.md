# Avaliação de Alternativas — Ficha Operacional

**Sistema Operacional do Estúdio LICHTARA**  
**Módulo:** 3 — Arquitetura Organizacional  
**Ferramenta:** 10 — Avaliação de Alternativas  
**Tipo:** Ficha metodológica, decisória e preenchível  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data de criação:** 02/08/2026

**Documentos relacionados:**

- `README.md` deste diretório;
- `01-estado-atual-e-estado-futuro.md`;
- `02-arquitetura-de-processos-e-fluxos.md`;
- `03-papeis-responsabilidades-e-alcadas.md`;
- `04-arquitetura-de-informacao-e-conhecimento.md`;
- `05-arquitetura-da-comunicacao.md`;
- `06-arquitetura-documental.md`;
- `07-arquitetura-de-indicadores.md`;
- `08-arquitetura-de-tecnologia-e-integracoes.md`;
- `09-arquitetura-de-inteligencia-artificial.md`;
- `../README.md`;
- `../fundamentos-da-arquitetura.md`;
- `../protocolo-de-arquitetura.md`;
- `../matriz-de-rastreabilidade.md`;
- `../templates/plano-de-arquitetura.md`;
- `../templates/03-catalogo-de-requisitos.md`;
- `../templates/04-matriz-de-rastreabilidade.md`;
- `../templates/05-arquitetura-integrada.md`;
- `../templates/06-registro-de-validacao.md`;
- `../templates/07-relatorio-de-arquitetura.md`;
- `../templates/08-transicao-para-implantacao.md`;
- `../templates/09-retrospectiva-da-arquitetura.md`.

---

## 1. Finalidade

Esta ferramenta orienta a geração, a estruturação, a comparação e a recomendação de alternativas arquiteturais quando uma decisão material admite mais de uma configuração possível.

Ela ajuda o Estúdio LICHTARA a:

- formular com precisão a decisão que precisa ser apoiada;
- distinguir alternativa, variante, cenário, estratégia de transição e decisão;
- preservar como opções reais a manutenção, a simplificação, a não intervenção, o adiamento e o piloto;
- impedir que preferência inicial seja apresentada como conclusão analítica;
- definir critérios antes de conhecer o resultado da comparação;
- separar requisito obrigatório de preferência compensável;
- verificar admissibilidade antes de calcular pontuações ou ordenar alternativas;
- produzir configurações materialmente distintas e suficientemente detalhadas;
- comparar atendimento, valor, impacto humano, risco, custo integral, esforço, manutenção e sustentabilidade;
- registrar evidências, estimativas, premissas, incertezas e lacunas;
- evitar falsa precisão, dupla contagem, pesos arbitrários e médias enganosas;
- explicitar compensações, perdas, dependências e riscos residuais;
- testar sensibilidade a pesos, notas, cenários e premissas;
- reconhecer dominância, fragilidade e condições de robustez;
- combinar elementos de alternativas sem destruir a coerência do conjunto;
- estruturar recomendação, dissenso, condições e gatilhos de reavaliação;
- preservar autoridade e responsabilidade humanas pela decisão;
- transferir a configuração selecionada à Arquitetura Integrada;
- preparar validação, implantação, operação e aprendizagem.

## 2. Pergunta central

> Entre configurações materialmente distintas e admissíveis, qual oferece a relação mais coerente entre atendimento aos requisitos, valor produzido, impactos, riscos, custo integral, capacidade de sustentação e reversibilidade, segundo evidências e critérios definidos antes da escolha?

Perguntas complementares:

1. que decisão precisa ser tomada e o que permanece fora dela?
2. quais alternativas reais foram consideradas?
3. qual referência permite compreender o custo de mudar e de não mudar?
4. que condições tornam uma alternativa inadmissível?
5. que critérios diferenciam legitimamente as opções?
6. que evidências sustentam cada julgamento?
7. onde há incerteza, premissa ou informação ausente?
8. que benefício de uma alternativa corresponde a perda ou risco em outra dimensão?
9. a recomendação permanece estável quando pesos, estimativas ou cenários mudam?
10. quem possui autoridade para decidir e aceitar riscos residuais?
11. sob quais condições a decisão deverá ser revista?

## 3. O que é

A Avaliação de Alternativas é um sistema de apoio à decisão que torna comparáveis configurações possíveis sem apagar diferenças materiais, condições impeditivas, incertezas ou responsabilidade humana.

Seu objeto não é a opinião isolada sobre uma ferramenta. É uma unidade decisória formada por:

```text
decisão delimitada
  + referência atual
  + alternativas comparáveis
  + requisitos e restrições
  + critérios prévios
  + evidências e premissas
  + impactos e riscos
  + compensações
  + testes de sensibilidade
  + recomendação condicionada
  + decisão humana registrada
```

A avaliação organiza julgamento; não o automatiza. Seu resultado deve permitir que outra pessoa autorizada compreenda o que foi comparado, por que uma configuração foi recomendada, quais perdas foram aceitas e em que condições a decisão continua válida.

## 4. Distinções essenciais

### 4.1 Problema

Condição atual ou futura que exige compreensão e pode justificar mudança. Um problema ainda não define a decisão nem a solução.

### 4.2 Decisão

Escolha autorizada entre cursos de ação, configurações ou condições. Toda avaliação deve declarar qual decisão apoia.

### 4.3 Opção

Possibilidade ainda não estruturada. Torna-se alternativa quando possui conteúdo suficiente para ser examinada contra os mesmos critérios.

### 4.4 Alternativa

Configuração coerente e identificável que pode ser escolhida, combinada, adiada ou rejeitada. Recebe código `ALT-ARQ-___`.

### 4.5 Variante

Modificação limitada de uma alternativa que preserva sua lógica principal. Variantes não devem inflar artificialmente o número de alternativas.

### 4.6 Configuração

Conjunto integrado de componentes, relações, regras, responsabilidades e condições de operação que faz uma alternativa funcionar.

### 4.7 Referência atual

Condição contra a qual mudanças são comparadas. Pode ser o funcionamento atual, uma linha de base validada ou uma configuração já aprovada.

### 4.8 Não intervenção

Alternativa explícita de manter a condição atual dentro do horizonte da decisão. Precisa revelar consequências, riscos e custos de permanência.

### 4.9 Adiamento

Decisão de não escolher ou implantar agora, acompanhada de motivo, limite temporal, ações de proteção e gatilho de reavaliação.

### 4.10 Piloto

Implantação limitada para reduzir incerteza relevante antes de compromisso ampliado. Piloto não é alternativa incompleta sem pergunta de aprendizagem.

### 4.11 Cenário

Conjunto de condições externas ou operacionais sob o qual uma alternativa é examinada. Cenário não concorre com alternativa; testa seu comportamento.

### 4.12 Critério

Dimensão julgável que ajuda a distinguir alternativas. Recebe código `CRT-ARQ-___` e precisa possuir definição, origem e regra de avaliação.

### 4.13 Subcritério

Decomposição necessária para tornar um critério observável. Não deve duplicar conteúdo já avaliado em outro ramo.

### 4.14 Requisito

Condição que a arquitetura precisa atender. Requisito obrigatório participa da admissibilidade e não pode ser neutralizado por pontuação alta em outro critério.

### 4.15 Restrição

Limite que reduz o espaço possível da decisão, como orçamento máximo, obrigação legal, prazo externo, competência indisponível ou tecnologia incompatível.

### 4.16 Limite impeditivo

Condição cuja violação exclui, suspende ou devolve uma alternativa para redesenho. É avaliado antes da comparação compensatória.

### 4.17 Preferência

Direção desejável, mas negociável, cuja importância precisa ser explicitada. Não deve ser rotulada como obrigatória apenas para vencer a comparação.

### 4.18 Evidência

Registro verificável que sustenta descrição, estimativa ou julgamento. Opinião especializada pode ser evidência quando sua origem, escopo e limite estão identificados.

### 4.19 Premissa

Condição considerada verdadeira para avaliar uma alternativa, mas ainda não confirmada. Recebe código `PRE-ARQ-___` e exige teste ou gatilho.

### 4.20 Estimativa

Valor provável produzido por método declarado. Deve informar faixa, horizonte, fonte e incerteza quando material.

### 4.21 Nota

Representação ordinal ou numérica de julgamento segundo escala previamente definida. Não é a evidência nem a decisão.

### 4.22 Peso

Expressão da importância relativa de um critério dentro de um modelo específico. Peso não converte prioridade política ou ética em verdade matemática.

### 4.23 Pontuação

Resultado de uma regra de agregação entre notas e, quando aplicável, pesos. Serve para organizar comparação, nunca para apagar impedimentos e compensações.

### 4.24 Ranking

Ordenação produzida por determinado método e conjunto de premissas. Pode mudar sem que os fatos mudem, caso o modelo decisório mude.

### 4.25 Compensação

Troca explícita entre benefícios, custos, riscos, impactos ou capacidades. Precisa dizer quem recebe o benefício e quem suporta a perda.

### 4.26 Dominância

Situação em que uma alternativa é igual ou melhor em todos os critérios comparáveis e melhor em pelo menos um, sem violar requisito impeditivo.

### 4.27 Fronteira eficiente

Conjunto de alternativas não dominadas, entre as quais melhorar uma dimensão exige aceitar perda em outra.

### 4.28 Sensibilidade

Grau em que a conclusão muda diante de variação plausível em peso, nota, custo, cenário ou premissa.

### 4.29 Robustez

Capacidade de uma alternativa permanecer aceitável em diferentes condições plausíveis, sem depender de previsão excessivamente precisa.

### 4.30 Recomendação

Proposição fundamentada submetida à autoridade decisória. Pode indicar escolha, combinação, piloto, adiamento ou retorno ao desenho.

### 4.31 Decisão registrada

Ato humano autorizado que aceita uma configuração, condições, compensações e riscos residuais. Recebe código `DEC-ARQ-___`.

### 4.32 Quadro comparativo

| Elemento | Pergunta | Pode excluir alternativa? | Pode ser compensado? |
| --- | --- | --- | --- |
| Requisito obrigatório | A condição mínima foi atendida? | Sim | Não |
| Restrição | A alternativa cabe no limite real? | Sim ou condiciona | Geralmente não |
| Critério comparativo | Qual alternativa apresenta melhor condição relativa? | Não isoladamente | Sim, com justificativa |
| Risco intolerável | A exposição permanece além do aceitável? | Sim | Não sem decisão competente |
| Preferência | Que direção é desejada? | Não | Sim |
| Premissa | De que verdade provisória depende o resultado? | Pode condicionar | Não se crítica e não testada |
| Evidência ausente | O julgamento pode ser sustentado? | Pode impedir decisão | Não deve virar nota zero |

## 5. Arquitetura da decisão comparativa

A cadeia mínima é:

```text
problema e decisão
  -> escopo e autoridade
  -> referência atual
  -> espaço de alternativas
  -> alternativas comparáveis
  -> critérios e impedimentos prévios
  -> plano de evidências
  -> admissibilidade
  -> comparação multidimensional
  -> compensações e impactos
  -> incerteza, cenários e sensibilidade
  -> recomendação
  -> decisão e condições
  -> configuração integrada
  -> validação, implantação e revisão
```

### 5.1 Duas camadas obrigatórias

| Camada | Função | Pergunta | Resultado |
| --- | --- | --- | --- |
| Admissibilidade | Proteger limites não compensáveis | A alternativa pode legitimamente avançar? | Admitida, condicionada, devolvida ou excluída |
| Comparação | Examinar diferenças entre opções admissíveis | Qual configuração oferece melhor relação global? | Síntese comparativa e recomendação |

Uma alternativa excluída não recebe posição favorável por possuir nota alta em benefícios. Uma alternativa condicionada somente participa quando a condição é demonstravelmente tratável antes da decisão ou da implantação.

## 6. Função no protocolo de arquitetura

A ferramenta opera principalmente entre a geração de configurações e a consolidação da Arquitetura Integrada.

| Etapa do protocolo | Contribuição |
| --- | --- |
| Preparação | Delimita decisão, autoridade, prazos e participantes |
| Requisitos | Separa condições obrigatórias, desejáveis e investigativas |
| Geração | Amplia o espaço de alternativas sem escolher prematuramente |
| Desenho dimensional | Exige detalhe suficiente nas dimensões materiais |
| Integração | Compara configurações completas e suas interfaces |
| Avaliação | Aplica admissibilidade, critérios, evidências e sensibilidade |
| Decisão | Produz recomendação, condições e registro rastreável |
| Validação | Identifica hipóteses e diferenças que precisam de teste |
| Transição | Entrega configuração, dependências e critérios de entrada |
| Retrospectiva | Preserva o que a decisão ensinou sobre critérios e previsões |

## 7. Saídas principais

| Saída | Código/referência | Conteúdo mínimo |
| --- | --- | --- |
| Dossiê da avaliação | `AVA-ARQ-___` | Decisão, alternativas, critérios, evidências, análise e conclusão |
| Registro de alternativa | `ALT-ARQ-___` | Configuração, funcionamento, requisitos, impactos e dependências |
| Catálogo de critérios | `CRT-ARQ-___` | Definições, escalas, origem, importância e impedimentos |
| Matriz de admissibilidade | Bloco do `AVA` | Atendimento obrigatório e decisão de entrada |
| Matriz comparativa | Bloco do `AVA` | Julgamentos por alternativa e critério |
| Registro de evidências | `EVD-ARQ-___` | Fonte, qualidade, atualidade, uso e limitação |
| Registro de premissas | `PRE-ARQ-___` | Condição, impacto, teste e gatilho |
| Análise de compensações | Bloco do `AVA` | Ganhos, perdas, afetados e justificativa |
| Análise de sensibilidade | Bloco do `AVA` | Variações testadas e estabilidade da conclusão |
| Recomendação | Bloco do `AVA` | Alternativa, justificativa, condições e ressalvas |
| Registro de decisão | `DEC-ARQ-___` | Autoridade, resultado, riscos aceitos e revisão |
| Pacote de integração | Referência na Arquitetura Integrada | Componentes derivados e vínculos rastreáveis |

### 7.1 Saída proporcional

Nem toda escolha exige pontuação, pesos ou modelo quantitativo. A saída mínima contém:

1. decisão delimitada;
2. alternativas reais;
3. critérios e impedimentos prévios;
4. evidências suficientes;
5. compensações materiais;
6. recomendação justificada;
7. decisão humana e condição de revisão.

## 8. O que a ferramenta não é

Esta ferramenta não é:

- mecanismo para legitimar preferência já escolhida;
- tabela de prós e contras sem critérios comuns;
- cotação de fornecedores isolada da arquitetura;
- competição de funcionalidades;
- votação sem autoridade e evidência;
- soma automática que decide pelo decisor;
- justificativa para escolher a opção mais barata;
- justificativa para escolher a opção mais sofisticada;
- substituta de protótipo, simulação, validação técnica ou jurídica;
- autorização para relativizar direito, segurança ou requisito obrigatório;
- promessa de que toda incerteza pode ser eliminada;
- documento produzido apenas depois da decisão para criar aparência de rigor.

## 9. Fronteiras com outros artefatos

| Artefato | Pergunta própria | Relação com a avaliação |
| --- | --- | --- |
| Catálogo de Requisitos | O que a arquitetura deve atender? | Fornece requisitos e critérios de aceite |
| Fichas dimensionais | Como cada dimensão pode funcionar? | Produzem conteúdo das alternativas |
| Matriz de Rastreabilidade | De onde vem e para onde vai cada decisão? | Preserva vínculos entre alternativas, requisitos e componentes |
| Arquitetura Integrada | Como a configuração aprovada funciona como sistema? | Recebe a alternativa selecionada ou combinada |
| Registro de Validação | O desenho resiste a critérios, pessoas e cenários? | Produz evidência que confirma ou reabre a avaliação |
| Registro de Decisão | O que foi autorizado, por quem e por quê? | Formaliza a escolha e os riscos aceitos |
| Relatório de Arquitetura | O que precisa ser comunicado sobre o resultado? | Sintetiza alternativas e decisão sem substituir o dossiê |
| Transição para Implantação | Como tornar a decisão realidade? | Recebe dependências, condições e critérios de entrada |

## 10. Princípios

1. **Decisão antes da matriz** — primeiro se define o que precisa ser escolhido.
2. **Critério antes do resultado** — critérios não são ajustados para confirmar preferência.
3. **Alternativa antes da pontuação** — opção mal desenhada não se torna comparável por receber nota.
4. **Admissibilidade antes da compensação** — limites obrigatórios não entram em média.
5. **Evidência antes da certeza** — confiança acompanha a qualidade das fontes.
6. **Incerteza visível** — desconhecido, não aplicável e não atendido são estados diferentes.
7. **Impacto distribuído** — benefício global não apaga perda concentrada.
8. **Custo integral** — preço de aquisição é apenas uma parte do custo.
9. **Sustentação real** — uma alternativa depende de capacidade para operar e manter.
10. **Simplicidade legítima** — menor sofisticação pode ser a escolha arquitetural mais coerente.
11. **Reversibilidade proporcional** — incerteza elevada pede compromissos graduais.
12. **Decisão humana** — método apoia; autoridade decide e responde.
13. **Dissenso preservado** — posição minoritária material não é apagada pela síntese.
14. **Revisão por gatilho** — toda decisão depende de condições identificáveis.
15. **Aprendizagem de previsão** — resultados reais retroalimentam critérios e estimativas.

## 11. Invariantes

- toda avaliação possui uma decisão explícita;
- toda alternativa possui identidade, versão e responsável pela descrição factual;
- alternativas comparadas possuem escopo e nível de detalhe equivalentes;
- manutenção da condição atual aparece como referência ou alternativa justificada;
- critérios materiais possuem origem e definição;
- requisitos obrigatórios são testados fora da pontuação compensatória;
- nota desconhecida não é convertida automaticamente em zero;
- dado não aplicável não recebe nota neutra sem explicação;
- todo peso possui justificativa e responsável;
- todo julgamento determinante possui evidência ou premissa explícita;
- custos incluem implantação, operação, manutenção, saída e tempo interno;
- impactos humanos identificam grupos afetados;
- riscos residuais exigem autoridade competente;
- combinação de alternativas é reavaliada como nova configuração;
- recomendação apresenta limites e condições;
- decisão diferente da recomendação registra justificativa;
- alternativa rejeitada preserva condição de retorno quando relevante;
- configuração escolhida mantém rastreabilidade até componentes e implantação.

## 12. Quando utilizar

Utilize quando:

- existir escolha arquitetural material;
- configurações produzirem impactos diferentes;
- houver tensão entre qualidade, custo, prazo, risco e manutenção;
- ferramenta, fornecedor, processo ou modelo operacional precisar ser escolhido;
- grau de centralização, padronização ou automação estiver em disputa;
- tecnologia ou IA alterar responsabilidade, dados ou autonomia;
- decisão criar dependência ou irreversibilidade significativa;
- alternativas envolverem grupos afetados de modos diferentes;
- houver necessidade de justificar investimento ou adiamento;
- uma combinação de componentes precisar ser selecionada;
- evidência parcial exigir decisão gradual;
- a escolha precisar ser reconstruída futuramente.

## 13. Quando não utilizar ou reduzir

Reduza a aplicação quando:

- uma única alternativa legítima decorre de obrigação incontornável;
- a escolha é local, barata, reversível e de baixo impacto;
- o objeto ainda não está suficientemente compreendido;
- alternativas são apenas nomes para a mesma configuração;
- falta desenho mínimo para comparar;
- a decisão já pertence a contrato ou norma vigente e não está aberta;
- o custo da avaliação excede o risco da escolha.

### 13.1 Registro da redução

| Campo | Registro |
| --- | --- |
| Decisão | [Preencher] |
| Motivo da aplicação reduzida | [Preencher] |
| Risco e reversibilidade | [Preencher] |
| Alternativa adotada | ALT-ARQ-___ |
| Autoridade | [Nome/papel] |
| Condição de revisão | [Preencher] |

Redução não autoriza ausência de decisão, requisito impeditivo, evidência mínima ou responsabilidade.

## 14. Proporcionalidade

| Nível | Situação típica | Aplicação mínima |
| --- | --- | --- |
| 1 — Local | Baixo custo, baixo impacto, reversível | Duas opções, critérios essenciais, decisão e revisão |
| 2 — Delimitado | Impacto em uma equipe ou processo | Alternativas estruturadas, admissibilidade e comparação qualitativa |
| 3 — Material | Várias dimensões, investimento ou mudança de trabalho | Dossiê completo, evidências, custos, riscos e sensibilidade |
| 4 — Crítico | Direitos, dados sensíveis, alta dependência ou irreversibilidade | Especialistas, validações independentes, cenários e decisão formal ampliada |

### 14.1 Fatores de profundidade

- magnitude do investimento;
- duração do compromisso;
- número e vulnerabilidade das pessoas afetadas;
- exposição de dados;
- criticidade da operação;
- dificuldade de retorno;
- dependência de fornecedor ou pessoa-chave;
- incerteza técnica e organizacional;
- efeito sobre autoridade e trabalho;
- obrigação legal, ética ou contratual.

## 15. Escalas e unidades de decisão

### 15.1 Escalas

| Escala | Exemplo | Cuidados |
| --- | --- | --- |
| Componente | Escolher ferramenta documental | Examinar interfaces e saída |
| Processo | Definir fluxo de atendimento | Comparar papéis, informação e exceções |
| Capacidade | Organizar produção de propostas | Evitar reduzir capacidade a software |
| Arquitetura | Escolher configuração organizacional | Comparar sistemas integrados |
| Portfólio | Priorizar várias iniciativas | Separar seleção da ordem de implantação |

### 15.2 Unidade comparável

Alternativas precisam responder à mesma decisão, ao mesmo horizonte e à mesma fronteira. Se uma alternativa inclui implantação completa e outra apenas aquisição, a comparação está estruturalmente inválida.

| Verificação | Alternativa A | Alternativa B | Alternativa C |
| --- | --- | --- | --- |
| Mesma decisão | [Sim/não] | [Sim/não] | [Sim/não] |
| Mesmo escopo | [Sim/não] | [Sim/não] | [Sim/não] |
| Mesmo horizonte | [Sim/não] | [Sim/não] | [Sim/não] |
| Mesma população afetada | [Sim/não] | [Sim/não] | [Sim/não] |
| Custos equivalentes | [Sim/não] | [Sim/não] | [Sim/não] |
| Riscos equivalentes em cobertura | [Sim/não] | [Sim/não] | [Sim/não] |

## 16. Participantes

| Participante | Contribuição | Autoridade | Limite |
| --- | --- | --- | --- |
| Responsável pela avaliação | Mantém método, versões e integridade | Solicita correções e evidências | Não decide fora da alçada |
| Arquiteto responsável | Garante coerência das configurações | Recomenda desenho | Não oculta impacto desfavorável |
| Dono da decisão | Define decisão e autoriza resultado | Decide e aceita compensações | Não altera evidência sem registro |
| Responsável financeiro | Estrutura custos e premissas | Valida fundamento financeiro | Não escolhe isoladamente pelo menor preço |
| Responsável técnico | Avalia viabilidade, segurança e manutenção | Pode declarar impedimento técnico fundamentado | Não transforma preferência técnica em obrigação |
| Operação | Informa trabalho real e capacidade de sustentação | Valida fatos operacionais | Não representa todos os afetados automaticamente |
| Pessoas afetadas | Revelam efeitos, barreiras e condições | Participam conforme impacto | Não carregam sozinhas a responsabilidade decisória |
| Especialista | Avalia tema específico | Emite parecer dentro da competência | Não extrapola escopo do parecer |
| Facilitador | Estrutura participação e dissenso | Protege processo | Não manipula convergência |
| Revisor independente | Testa consistência e viés | Solicita reabertura | Não substitui autoridade decisória |

### 16.1 Participantes reais

| Nome | Papel na organização | Papel na avaliação | Interesse afetado | Conflito possível | Participação |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Etapas] |

## 17. Autoridade, direitos e limites

| Ação | Responsável | Aprovação | Consulta mínima | Registro |
| --- | --- | --- | --- | --- |
| Delimitar decisão | [Papel] | [Papel] | [Pessoas] | AVA-ARQ-___ |
| Admitir ou excluir alternativa | [Papel] | [Papel] | [Especialistas] | Matriz de admissibilidade |
| Aprovar critérios | [Papel] | [Papel] | [Afetados/especialistas] | Catálogo de critérios |
| Validar custo e evidência | [Papel] | [Papel] | [Fontes] | EVD-ARQ-___ |
| Emitir recomendação | [Papel] | [Papel] | [Revisores] | AVA-ARQ-___ |
| Aceitar risco residual | [Papel competente] | [Instância] | [Especialistas/afetados] | DEC-ARQ-___ |
| Decidir | [Decisor] | [Instância, se houver] | [Conforme governança] | DEC-ARQ-___ |
| Reabrir avaliação | [Papel] | [Papel] | [Responsáveis] | Registro de mudança |

Nenhum método, consultor, sistema ou IA recebe autoridade institucional pelo simples fato de produzir uma pontuação ou recomendação.

## 18. Conflitos de interesse

| Pessoa/parte | Relação com alternativa | Benefício ou perda possível | Proteção | Estado |
| --- | --- | --- | --- | --- |
| [Preencher] | [Fornecedor, autor, usuário, decisor ou outro] | [Preencher] | [Declaração, segregação, revisão ou impedimento] | [Aberto/tratado] |

Proteções possíveis:

- declaração anterior à avaliação;
- separação entre produção da evidência e decisão;
- revisão independente;
- fonte alternativa;
- impedimento parcial;
- transparência sobre incentivo comercial;
- registro de divergência.

## 19. Entradas necessárias

| Entrada | Referência | Qualidade mínima | Responsável |
| --- | --- | --- | --- |
| Problema e decisão | Termo/Plano | Delimitados | [Papel] |
| Estado atual | Ficha 01/diagnóstico | Atual e verificável | [Papel] |
| Capacidades futuras | CAP-ARQ-___ | Resultado observável | [Papel] |
| Requisitos | REQ-ARQ-___ | Prioridade e aceite | [Papel] |
| Restrições | RES-ARQ-___ | Origem e efeito | [Papel] |
| Riscos | RSC-ARQ-___ | Exposição e tratamento | [Papel] |
| Alternativas | ALT-ARQ-___ | Comparáveis | [Papel] |
| Critérios | CRT-ARQ-___ | Definidos antes da nota | [Papel] |
| Evidências | EVD-ARQ-___ | Fonte e limitação | [Papel] |
| Custos | Planilha/referência | Horizonte equivalente | [Papel] |
| Impactos | Registros/participação | Grupos identificados | [Papel] |
| Premissas | PRE-ARQ-___ | Testáveis | [Papel] |
| Autoridade | Protocolo de decisão | Alçada confirmada | [Papel] |

## 20. Qualidade das entradas

Antes de comparar, verifique:

- o problema não está formulado como solução;
- a decisão cabe à instância identificada;
- o estado atual não foi caricaturado para favorecer mudança;
- as alternativas possuem maturidade equivalente;
- requisitos obrigatórios são realmente obrigatórios;
- custos usam mesma base temporal;
- benefícios não duplicam o mesmo resultado;
- riscos incluem operação e transição;
- grupos afetados estão representados;
- incertezas estão visíveis;
- fontes comerciais estão identificadas;
- ausências materiais bloqueiam ou condicionam a conclusão.

### 20.1 Entrada insuficiente

| Entrada ausente/frágil | Alternativas afetadas | Efeito | Ação | Decisão possível |
| --- | --- | --- | --- | --- |
| [Preencher] | [IDs] | [Viés, incerteza ou incomparabilidade] | [Obter, testar, estimar ou suspender] | [Nenhuma, provisória ou condicionada] |

## 21. Preparação

1. confirme a decisão e a autoridade;
2. identifique horizonte, fronteira e urgência;
3. reúna requisitos, riscos e restrições;
4. separe participantes e conflitos de interesse;
5. defina método e profundidade;
6. planeje geração independente de alternativas;
7. aprove critérios e impedimentos antes da avaliação;
8. defina evidências necessárias e escalas;
9. estabeleça como dissenso e incerteza serão registrados;
10. marque gates de revisão e decisão.

### 21.1 Prontidão

| Verificação | Estado | Pendência | Responsável |
| --- | --- | --- | --- |
| Decisão delimitada | [Pronto/não] | [Preencher] | [Papel] |
| Autoridade confirmada | [Pronto/não] | [Preencher] | [Papel] |
| Alternativas mínimas geradas | [Pronto/não] | [Preencher] | [Papel] |
| Critérios aprovados | [Pronto/não] | [Preencher] | [Papel] |
| Impedimentos definidos | [Pronto/não] | [Preencher] | [Papel] |
| Evidências acessíveis | [Pronto/não] | [Preencher] | [Papel] |
| Participação adequada | [Pronto/não] | [Preencher] | [Papel] |

## 22. Plano da avaliação

| Campo | Registro |
| --- | --- |
| Avaliação | AVA-ARQ-___ |
| Projeto | ARQ-AAAA-NNN |
| Decisão apoiada | [Descrição/ID] |
| Responsável | [Nome/papel] |
| Decisor | [Nome/papel] |
| Nível de profundidade | [1, 2, 3 ou 4] |
| Método principal | [Qualitativo, ponderado, custo–valor, dominância ou outro] |
| Período | [Datas] |
| Participantes | [Nomes/papéis] |
| Gate de critérios | [Data/registro] |
| Gate de admissibilidade | [Data/registro] |
| Gate de recomendação | [Data/registro] |
| Gate de decisão | [Data/registro] |

### 22.1 Atividades

| Atividade | Entrada | Saída | Responsável | Data | Estado |
| --- | --- | --- | --- | --- | --- |
| Delimitar decisão | [Referência] | Enunciado | [Papel] | [Data] | [Estado] |
| Gerar alternativas | [Perguntas] | ALT IDs | [Papel] | [Data] | [Estado] |
| Aprovar critérios | [REQ/RSC/RES] | CRT IDs | [Papel] | [Data] | [Estado] |
| Coletar evidências | [Plano] | EVD IDs | [Papel] | [Data] | [Estado] |
| Testar admissibilidade | [Alternativas] | Resultado | [Papel] | [Data] | [Estado] |
| Comparar | [Matrizes] | Síntese | [Papel] | [Data] | [Estado] |
| Testar sensibilidade | [Modelo] | Cenários | [Papel] | [Data] | [Estado] |
| Recomendar | [Análise] | Recomendação | [Papel] | [Data] | [Estado] |
| Decidir | [Dossiê] | DEC ID | [Papel] | [Data] | [Estado] |

## 23. Identificação, versão e validade

| Campo | Registro |
| --- | --- |
| Dossiê | AVA-ARQ-AAAA-NNN |
| Versão | [0.1] |
| Alternativas avaliadas | [IDs e versões] |
| Requisitos | [Versão] |
| Arquitetura de referência | [Versão] |
| Data de corte das evidências | [Data] |
| Horizonte da decisão | [Período] |
| Validade da recomendação | [Condição/data] |
| Estado | [Preparação, avaliação, recomendada, decidida, suspensa ou reaberta] |

### 23.1 Estados

| Estado | Significado |
| --- | --- |
| Preparação | Decisão, participantes e método estão sendo definidos |
| Geração | Alternativas estão sendo estruturadas |
| Avaliação | Critérios e evidências estão sendo aplicados |
| Recomendada | Análise concluída; decisão ainda não emitida |
| Decidida | Autoridade registrou o resultado |
| Condicionada | Resultado depende de condição anterior à implantação |
| Suspensa | Falta evidência, autoridade ou condição legítima |
| Reaberta | Gatilho material exige nova avaliação |
| Encerrada | Decisão foi substituída ou objeto deixou de existir |

## 24. Enunciado da decisão

> Decidir **[verbo e objeto]**, para produzir **[resultado/capacidade]**, dentro de **[escopo e horizonte]**, respeitando **[requisitos e restrições]**, com autoridade de **[papel]**, até **[data ou gatilho]**.

| Pergunta | Registro |
| --- | --- |
| O que será escolhido? | [Preencher] |
| Para qual resultado? | [Preencher] |
| Quem decide? | [Preencher] |
| Quem é afetado? | [Preencher] |
| Qual horizonte? | [Preencher] |
| Que recurso está comprometido? | [Preencher] |
| O que permanece fora? | [Preencher] |
| O que acontece se não houver decisão? | [Preencher] |

### 24.1 Teste de solução embutida

| Formulação | Problema | Reformulação necessária |
| --- | --- | --- |
| “Escolher um software de IA” | Supõe tecnologia e IA | “Definir como ampliar a capacidade X com qualidade e responsabilidade” |
| “Terceirizar o atendimento” | Supõe modelo de operação | “Definir configuração capaz de atender demanda Y” |
| “Automatizar o relatório” | Supõe mecanismo | “Reduzir ciclo e erro do relatório preservando validação” |

## 25. Fronteira da decisão

| Elemento | Dentro | Fora | Interface | Motivo |
| --- | --- | --- | --- | --- |
| Processo | [Preencher] | [Preencher] | [IDs] | [Preencher] |
| Unidade/público | [Preencher] | [Preencher] | [IDs] | [Preencher] |
| Tecnologia | [Preencher] | [Preencher] | [IDs] | [Preencher] |
| Dados | [Preencher] | [Preencher] | [IDs] | [Preencher] |
| Prazo | [Preencher] | [Preencher] | [IDs] | [Preencher] |
| Investimento | [Preencher] | [Preencher] | [IDs] | [Preencher] |

Alterar a fronteira depois de conhecer resultados exige registro e reavaliação da comparabilidade.

## 26. Horizonte e tempo

| Horizonte | Pergunta | Registro |
| --- | --- | --- |
| Transição | O que será necessário para mudar? | [Preencher] |
| Futuro inicial | O que precisa funcionar após estabilização? | [Preencher] |
| Operação recorrente | O que sustenta valor e controle? | [Preencher] |
| Evolução | Que mudança provável precisa ser suportada? | [Preencher] |
| Saída | Como substituir, reduzir ou encerrar? | [Preencher] |

Comparar apenas o estado futuro idealizado favorece alternativas que transferem custo e risco para implantação, manutenção ou encerramento.

## 27. Referência atual

| Dimensão | Condição atual | Evidência | Custo/valor atual | Risco de permanência | Limite da referência |
| --- | --- | --- | --- | --- | --- |
| Capacidade | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |
| Processo | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |
| Pessoas | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |
| Informação | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |
| Tecnologia/IA | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |
| Risco/controle | [Preencher] | [Fonte] | [Preencher] | [Preencher] | [Preencher] |

### 27.1 Viés contra o atual

O estado atual contém falhas, mas também capacidades, relações, conhecimentos e controles que podem ser destruídos pela mudança. A referência deve registrar ambos.

## 28. Espaço de decisão

| Eixo de variação | Polo 1 | Polo 2 | Possibilidades intermediárias |
| --- | --- | --- | --- |
| Centralização | Distribuída | Centralizada | Federação ou serviço compartilhado |
| Padronização | Adaptativa | Uniforme | Núcleo comum com variações |
| Execução | Humana | Automatizada | Apoio, recomendação ou gates |
| Tecnologia | Existente | Nova | Configuração, integração ou híbrida |
| Construção | Interna | Contratada | Composição ou parceria |
| Ritmo | Imediato | Gradual | Piloto e ondas |
| Controle | Preventivo | Detectivo | Combinação proporcional |

Mapear eixos antes de nomear produtos amplia o espaço legítimo de alternativas.

## 29. Geração de alternativas

Perguntas geradoras:

- o que pode ser resolvido por clareza de processo, sem nova ferramenta?
- que capacidade existente pode ser configurada ou combinada?
- o que muda se centralizarmos ou distribuirmos responsabilidade?
- qual é a menor intervenção que produz resultado suficiente?
- que configuração preserva opção de saída?
- que solução funciona com menor maturidade?
- qual alternativa reduz dependência de pessoa ou fornecedor?
- como seria a configuração sem IA?
- como seria com IA apenas em tarefas delimitadas?
- o que pode ser testado antes de comprometer o conjunto?
- que solução um grupo afetado proporia?
- o que ocorre se adiarmos ou não interviermos?

### 29.1 Regra de diversidade material

Três marcas do mesmo tipo de plataforma são candidatos comerciais dentro de uma alternativa tecnológica, não três arquiteturas materialmente distintas.

## 30. Alternativas mínimas a considerar

1. manter a condição atual com controles adicionais;
2. simplificar ou eliminar trabalho;
3. redesenhar processo e papéis sem nova tecnologia;
4. configurar capacidade já disponível;
5. contratar serviço ou solução externa;
6. integrar componentes existentes;
7. desenvolver capacidade específica;
8. combinar trabalho humano e automação;
9. realizar piloto limitado;
10. adiar com ações de proteção e gatilho;
11. não intervir dentro do horizonte definido.

A lista não obriga o detalhamento de opções inviáveis. Obriga demonstrar que o espaço da decisão não foi fechado prematuramente.

## 31. Registro mestre de alternativa

| Campo | Registro |
| --- | --- |
| ID | ALT-ARQ-___ |
| Nome descritivo | [Preencher] |
| Versão | [Preencher] |
| Tese de funcionamento | [Como produz o resultado] |
| Capacidades | CAP-ARQ-___ |
| Requisitos atendidos | REQ-ARQ-___ |
| Componentes | CMP-ARQ-___ |
| Processos | PRC-ARQ-___ |
| Papéis e decisões | PAP/DEC-ARQ-___ |
| Informação/documentos | INF/DOC-ARQ-___ |
| Tecnologia/integrações | TEC/ITG-ARQ-___ |
| IA | FIA/SIA-ARQ-___ ou N/A |
| Indicadores/controles | IND/CTL-ARQ-___ |
| Transição | [Síntese] |
| Operação e manutenção | [Síntese] |
| Continuidade e saída | [Síntese] |
| Custos | [Referência] |
| Benefícios | [Referência] |
| Riscos | RSC-ARQ-___ |
| Premissas | PRE-ARQ-___ |
| Evidências | EVD-ARQ-___ |
| Responsável pela descrição | [Nome/papel] |
| Estado | [Rascunho, comparável, condicionada, excluída, selecionada ou encerrada] |

### 31.1 Tese de funcionamento

> Se **[componentes e relações]** forem estabelecidos sob **[condições]**, a organização conseguirá **[capacidade]**, produzindo **[resultado]**, porque **[mecanismo causal ou operacional]**.

## 32. Descrição equivalente

| Dimensão | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- |
| Capacidade entregue | [Preencher] | [Preencher] | [Preencher] |
| Fluxo principal | [Preencher] | [Preencher] | [Preencher] |
| Responsabilidade | [Preencher] | [Preencher] | [Preencher] |
| Informação necessária | [Preencher] | [Preencher] | [Preencher] |
| Tecnologia/IA | [Preencher] | [Preencher] | [Preencher] |
| Controle | [Preencher] | [Preencher] | [Preencher] |
| Transição | [Preencher] | [Preencher] | [Preencher] |
| Manutenção | [Preencher] | [Preencher] | [Preencher] |
| Saída | [Preencher] | [Preencher] | [Preencher] |

Se uma célula material está vazia em uma alternativa, registre a lacuna; não presuma condição favorável.

## 33. Alternativa de manutenção

| Pergunta | Registro |
| --- | --- |
| O que é preservado? | [Preencher] |
| Que problema permanece? | [Preencher] |
| Que controles adicionais seriam necessários? | [Preencher] |
| Qual é o custo atual real? | [Preencher] |
| Qual é o custo de oportunidade? | [Preencher] |
| Que risco cresce com o tempo? | [Preencher] |
| Até quando a manutenção é aceitável? | [Preencher] |
| Qual gatilho encerra essa alternativa? | [Preencher] |

“Não fazer nada” raramente significa ausência de custo. Significa continuar financiando consequências, trabalho invisível, risco e oportunidade perdida.

## 34. Alternativa de simplificação

Antes de adicionar componente, pergunte:

- a atividade precisa existir?
- o requisito pode ser atendido por regra mais clara?
- o fluxo pode ter menos estados e transferências?
- um documento ou indicador pode ser eliminado?
- a mesma capacidade pode ser entregue com menor coordenação?
- a exceção pode ser reduzida na origem?
- uma tecnologia já disponível é suficiente?

| Elemento removido/reduzido | Valor preservado | Risco criado | Proteção | Evidência |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | EVD-ARQ-___ |

## 35. Alternativa de adiamento

| Campo | Registro |
| --- | --- |
| Motivo do adiamento | [Incerteza, recurso, dependência, prioridade ou outro] |
| Consequência durante espera | [Preencher] |
| Proteção temporária | [Preencher] |
| Evidência a obter | [Preencher] |
| Responsável | [Papel] |
| Data-limite | [Data] |
| Gatilho de reavaliação | [Evento/indicador] |
| Decisão se gatilho não ocorrer | [Preencher] |

Adiamento sem limite e responsável é abandono disfarçado.

## 36. Alternativa de piloto

Um piloto é adequado quando uma diferença entre alternativas depende de evidência que não pode ser obtida apenas por análise documental, demonstração comercial ou opinião.

| Campo | Registro |
| --- | --- |
| Alternativa testada | ALT-ARQ-___ |
| Incerteza focal | PRE/RSC/CRT-ARQ-___ |
| Escopo limitado | [Processo, público, período e volume] |
| Resultado esperado | [Preencher] |
| Critério de sucesso | [Condição observável] |
| Critério de interrupção | [Condição] |
| Proteções | [Controles] |
| Decisão após piloto | [Expandir, ajustar, comparar, suspender ou encerrar] |

### 36.1 Piloto comparável

Se apenas uma alternativa puder ser pilotada, registre como a diferença de maturidade da evidência será tratada. Resultado observado de uma opção não deve ser comparado diretamente com promessa não testada de outra sem qualificação.

## 37. Alternativa combinada

Combinar elementos pode produzir uma configuração superior, mas a combinação constitui uma nova alternativa e precisa ser reavaliada.

| Elemento | Alternativa de origem | Razão da incorporação | Interface criada | Efeito sistêmico | Reavaliação |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | ALT-ARQ-___ | [Preencher] | INT-ARQ-___ | [Preencher] | [Critérios/testes] |

### 37.1 Riscos de combinação

- selecionar apenas os benefícios declarados e esquecer os custos correlatos;
- criar interfaces que não existiam nas alternativas originais;
- duplicar responsabilidades ou sistemas;
- aumentar manutenção e dependência;
- perder coerência entre processo, papel, informação e tecnologia;
- produzir alternativa que nunca foi efetivamente desenhada.

## 38. Gate de comparabilidade

Antes de definir notas, confirme:

| Verificação | ALT-A | ALT-B | ALT-C | Tratamento |
| --- | --- | --- | --- | --- |
| Responde à mesma decisão | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Possui escopo equivalente | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Possui configuração coerente | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Inclui transição | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Inclui operação e manutenção | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Inclui continuidade e saída | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Custos usam a mesma base | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Benefícios usam o mesmo horizonte | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Incerteza está declarada | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |
| Evidência possui qualidade comparável | [Sim/não] | [Sim/não] | [Sim/não] | [Preencher] |

**Gate:** [Aprovado, aprovado com condições ou devolvido ao desenho]  
**Responsável:** [Nome/papel]  
**Data:** [DD/MM/AAAA]

## 39. Origem dos critérios

| Origem | Exemplo | Tratamento |
| --- | --- | --- |
| Requisito | Tempo máximo de resposta | Vincular ao `REQ` e ao critério de aceite |
| Capacidade | Conseguir reconstruir histórico | Avaliar manifestação observável |
| Risco | Evitar exposição de dado sensível | Definir limite e controle |
| Restrição | Investimento máximo | Testar admissibilidade |
| Princípio | Responsabilidade humana | Traduzir em condição verificável |
| Pessoa afetada | Acessibilidade do fluxo | Registrar participação e impacto |
| Operação | Capacidade de manutenção | Avaliar recurso e rotina reais |
| Estratégia | Portabilidade | Definir horizonte e indicador |
| Obrigação externa | Norma, contrato ou lei | Validar com competência adequada |

Critério sem origem pode representar preferência privada introduzida no modelo como se fosse necessidade do sistema.

## 40. Taxonomia de critérios

| Família | Objeto típico | Pergunta |
| --- | --- | --- |
| Atendimento | Requisitos e capacidade | A alternativa entrega o que precisa existir? |
| Qualidade | Resultado e experiência | Com que consistência e adequação? |
| Pessoas | Carga, autonomia, competência e equidade | Como o trabalho e as pessoas são afetados? |
| Processo | Fluxo, exceção e coordenação | Como o funcionamento se sustenta? |
| Informação | Qualidade, acesso e memória | Que informação é necessária e preservada? |
| Tecnologia | Compatibilidade, segurança e continuidade | A base técnica é adequada e sustentável? |
| IA | Qualidade variável, supervisão e risco | A função de IA permanece governável? |
| Financeiro | Custo, benefício e exposição | O compromisso é sustentável? |
| Implantação | Esforço, dependências e mudança | A organização consegue realizar a transição? |
| Operação | Manutenção, suporte e observabilidade | A configuração pode funcionar continuamente? |
| Estratégico | Flexibilidade, opção e alinhamento | A decisão preserva capacidade futura? |
| Ético/legal | Direitos, legitimidade e obrigação | A alternativa pode ser legitimamente adotada? |

## 41. Ficha mestra do critério

| Campo | Registro |
| --- | --- |
| ID | CRT-ARQ-___ |
| Nome | [Preencher] |
| Pergunta avaliativa | [Preencher] |
| Definição | [O que o critério significa] |
| Origem | [REQ, RSC, RES, princípio, decisão ou participante] |
| Tipo | [Obrigatório, comparativo, informativo ou investigativo] |
| Direção desejada | [Maior, menor, faixa ou condição] |
| Unidade | [Qualitativa, quantitativa ou binária] |
| Escala | [Referência] |
| Regra de atendimento | [Preencher] |
| Limite impeditivo | [Condição ou N/A] |
| Evidência necessária | [Preencher] |
| Horizonte | [Transição, operação, evolução ou saída] |
| Importância/peso | [Valor e justificativa] |
| Responsável semântico | [Papel] |
| Revisor | [Papel] |
| Relações | [Outros CRT/REQ/RSC] |

### 41.1 Pergunta testável

Prefira “qual proporção dos casos pode ser concluída sem retrabalho dentro do prazo?” a “a solução é eficiente?”. O critério precisa delimitar o que será observado, sem prometer causalidade que a evidência não sustenta.

## 42. Hierarquia e independência dos critérios

| Critério pai | Subcritério | O que mede | Sobreposição possível | Tratamento |
| --- | --- | --- | --- | --- |
| CRT-ARQ-___ | CRT-ARQ-___ | [Preencher] | [Outro CRT] | [Fundir, separar ou manter] |

### 42.1 Teste de dupla contagem

Pergunte:

- o mesmo benefício aparece como produtividade, tempo e economia?
- o mesmo risco aparece como segurança, conformidade e confiança?
- custo de pessoal está no custo operacional e no esforço interno?
- facilidade de uso e necessidade de treinamento representam o mesmo fenômeno?
- portabilidade e dependência de fornecedor usam as mesmas evidências?

Quando critérios compartilham causa ou medida, ajuste a hierarquia ou interprete o resultado sem agregação simples.

## 43. Critérios obrigatórios e comparativos

| Critério | Tipo | Limite | Compensável? | Autoridade para exceção |
| --- | --- | --- | --- | --- |
| CRT-ARQ-___ | Obrigatório | [Condição] | Não | [Nenhuma ou papel competente] |
| CRT-ARQ-___ | Comparativo | [Escala] | Sim | N/A |
| CRT-ARQ-___ | Investigativo | [Evidência] | Não pontuar | [Papel] |

Um critério somente pode migrar de obrigatório para comparativo mediante revisão de sua origem, do requisito relacionado e da autoridade que pode aceitar o efeito.

## 44. Formulação dos critérios

Critérios de qualidade:

- possuem uma ideia principal;
- usam linguagem compreensível;
- distinguem estado desejado de meio preferido;
- permitem evidência proporcional;
- informam direção ou faixa adequada;
- evitam adjetivos sem regra, como “moderno”, “robusto” ou “intuitivo”;
- não favorecem uma tecnologia pelo modo como são escritos;
- não confundem presença de funcionalidade com resultado organizacional.

| Formulação frágil | Problema | Formulação melhor |
| --- | --- | --- |
| “Ter IA” | Meio apresentado como valor | “Reduzir tempo de síntese mantendo verificabilidade” |
| “Sistema completo” | Escopo indefinido | “Atender requisitos X, Y e Z sem módulos ociosos” |
| “Fácil de usar” | Percepção sem público e tarefa | “Permitir que o papel X conclua a tarefa Y após treinamento Z” |
| “Baixo custo” | Base e horizonte ausentes | “Custo integral em 24 meses dentro da faixa aprovada” |

## 45. Escolha da escala

| Escala | Uso adequado | Limite |
| --- | --- | --- |
| Binária | Requisito objetivo | Pode ocultar atendimento parcial |
| Categórica | Estados distintos sem ordem | Não permite ranking |
| Ordinal | Julgamento por níveis ordenados | Distâncias não são iguais |
| Quantitativa | Medida com unidade | Exige dado comparável |
| Faixa | Estimativa incerta | Requer tratamento de sobreposição |
| Rubrica | Julgamento complexo | Exige descritores claros |
| Narrativa | Compensação ou contexto singular | Dificulta agregação, mas preserva significado |

Não converta escala ordinal em precisão intervalar sem justificar o método.

## 46. Rubrica qualitativa recomendada

| Estado | Definição |
| --- | --- |
| Atende com evidência forte | Condição demonstrada por fonte suficiente e relevante |
| Atende com condição | Atendimento depende de ação identificada, viável e anterior ao uso |
| Atende parcialmente | Parte material permanece descoberta |
| Não atende | Condição não é satisfeita |
| Desconhecido | Evidência insuficiente para julgar |
| Não aplicável | Critério foi examinado e não corresponde à alternativa |

### 46.1 Proibição de equivalência silenciosa

`Desconhecido` não equivale a `não atende`; `não aplicável` não equivale a nota média; `atende com condição` não equivale a atendimento atual.

## 47. Escala numérica

Quando útil, uma escala numérica precisa possuir âncoras observáveis.

| Nota | Descritor genérico | Regra específica do critério |
| --- | --- | --- |
| 0 | Não atende | [Preencher] |
| 1 | Atendimento muito baixo | [Preencher] |
| 2 | Atendimento parcial | [Preencher] |
| 3 | Atendimento suficiente | [Preencher] |
| 4 | Atendimento forte | [Preencher] |
| 5 | Atendimento superior e demonstrado | [Preencher] |

Se avaliadores não conseguem distinguir de modo consistente cinco níveis, reduza a escala.

## 48. Pesos

Pesos podem representar importância relativa entre critérios comparativos. Eles não devem ser aplicados a critérios impeditivos.

| Critério | Prioridade inicial | Peso proposto | Justificativa | Aprovador |
| --- | --- | --- | --- | --- |
| CRT-ARQ-___ | [Alta/média/baixa] | [Valor] | [Relação com decisão] | [Papel] |

### 48.1 Regras

- defina pesos antes de pontuar alternativas;
- limite a quantidade de critérios ponderados;
- registre quem participou;
- use pesos coerentes com a hierarquia;
- teste variações plausíveis;
- não ajuste peso para produzir vencedor desejado;
- preserve critérios qualitativos fora da soma quando necessário.

## 49. Métodos de definição de importância

| Método | Como funciona | Quando usar | Risco |
| --- | --- | --- | --- |
| Classificação | Ordena critérios | Poucos critérios | Não mostra distância |
| Distribuição de pontos | Aloca total fixo | Grupo pequeno e informado | Negociação estratégica |
| Comparação pareada | Compara critérios dois a dois | Decisão material | Carga e inconsistência |
| Faixas de prioridade | Agrupa importância | Contexto qualitativo | Empates amplos |
| Deliberação fundamentada | Produz consenso ou dissenso registrado | Impacto humano alto | Domínio de voz |

### 49.1 Peso de quem

Pesos podem diferir entre decisores, operação e pessoas afetadas. Antes de produzir média, examine se a diferença revela distribuição desigual de benefícios e perdas.

## 50. Normalização e agregação

Quando critérios usam unidades diferentes, qualquer transformação precisa permanecer legível.

| Critério | Unidade original | Transformação | Referência | Efeito possível |
| --- | --- | --- | --- | --- |
| [Preencher] | [R$, dias, %, rubrica] | [Regra] | [Faixa] | [Compressão, amplificação ou inversão] |

### 50.1 Soma ponderada

Uma forma simples é:

$$S_a = \sum_{i=1}^{n} w_i r_{ai}$$

em que $S_a$ é a pontuação da alternativa $a$, $w_i$ é o peso do critério $i$ e $r_{ai}$ é a avaliação normalizada da alternativa naquele critério.

A fórmula somente é válida dentro das hipóteses declaradas. Ela não autoriza compensar impedimentos, misturar escalas incompatíveis ou tratar diferenças ordinais como medidas exatas.

## 51. Desconhecido, ausente e não aplicável

| Estado | Significado | Tratamento |
| --- | --- | --- |
| Sem evidência | Fonte ainda não existe ou não foi obtida | Coletar, testar ou condicionar |
| Evidência inconclusiva | Fontes não sustentam uma direção | Registrar intervalo ou dissenso |
| Não atendido | Evidência demonstra falha | Excluir, redesenhar ou aceitar se compensável |
| Não aplicável | Critério não corresponde | Excluir do denominador com justificativa |
| Não informado | Campo não preenchido | Devolver; não avaliar |

### 51.1 Viés de disponibilidade

Alternativa conhecida costuma ter mais falhas documentadas; alternativa nova costuma ter mais benefícios prometidos e riscos desconhecidos. A avaliação deve penalizar a incerteza de modo transparente, não premiar ausência de histórico.

## 52. Matriz de admissibilidade

| Condição obrigatória | Origem | ALT-A | ALT-B | ALT-C | Evidência | Decisão |
| --- | --- | --- | --- | --- | --- | --- |
| REQ/RES/RSC/CRT-ARQ-___ | [Fonte] | [Atende/condiciona/não atende/desconhecido] | [Estado] | [Estado] | EVD-ARQ-___ | [Admitir, devolver ou excluir] |

### 52.1 Condição tratável

| Alternativa | Condição | Tratamento | Custo/prazo | Responsável | Evidência de viabilidade | Gate |
| --- | --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Papel] | EVD-ARQ-___ | [Antes da decisão/implantação] |

Condição futura só preserva admissibilidade quando tratamento, recurso, responsável e momento são plausíveis.

## 53. Resultado de admissibilidade

| Alternativa | Resultado | Motivo | Condições | Autoridade | Data |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Admitida, condicionada, devolvida ou excluída] | [IDs e síntese] | [Preencher] | [Nome/papel] | [Data] |

### 53.1 Exclusão

Excluir não significa apagar. Preserve a alternativa, o critério violado, a evidência e a condição que poderia permitir retorno.

## 54. Plano de evidências

| Questão/critério | Evidência necessária | Fonte provável | Método | Responsável | Prazo | Alternativas |
| --- | --- | --- | --- | --- | --- | --- |
| CRT-ARQ-___ | [Preencher] | [Preencher] | [Documento, dado, teste, entrevista ou parecer] | [Papel] | [Data] | [IDs] |

Priorize evidência que possa alterar admissibilidade, ranking, compensação ou confiança da recomendação.

## 55. Qualidade da evidência

| Dimensão | Pergunta | Classificação |
| --- | --- | --- |
| Relevância | Responde ao critério e ao uso real? | [Baixa/média/alta] |
| Validade | O método sustenta a conclusão? | [Baixa/média/alta] |
| Atualidade | Representa a condição da decisão? | [Baixa/média/alta] |
| Independência | A fonte possui interesse material? | [Baixa/média/alta] |
| Cobertura | Abrange cenários e públicos relevantes? | [Baixa/média/alta] |
| Comparabilidade | Foi produzida sob condições equivalentes? | [Baixa/média/alta] |
| Rastreabilidade | Pode ser localizada e reconstruída? | [Baixa/média/alta] |

### 55.1 Ficha da evidência

| Campo | Registro |
| --- | --- |
| ID | EVD-ARQ-___ |
| Afirmação sustentada | [Preencher] |
| Fonte | [Preencher] |
| Data/versão | [Preencher] |
| Método | [Preencher] |
| Alternativas | [IDs] |
| Critérios | [IDs] |
| Qualidade | [Síntese] |
| Limitação | [Preencher] |
| Responsável pela interpretação | [Papel] |

## 56. Fontes de evidência

| Fonte | Valor | Limite típico |
| --- | --- | --- |
| Operação atual | Revela trabalho real | Pode naturalizar limitação existente |
| Dados históricos | Permitem referência | Podem não representar futuro |
| Protótipo | Testa interação e entendimento | Escopo reduzido |
| Piloto | Observa funcionamento limitado | Efeito de novidade e seleção |
| Simulação | Examina cenários controlados | Depende do modelo e dos casos |
| Demonstração de fornecedor | Mostra capacidade possível | Ambiente preparado e incentivo comercial |
| Referência de cliente | Mostra experiência comparável | Contexto pode diferir |
| Parecer especializado | Interpreta tema complexo | Escopo e independência variam |
| Proposta comercial | Informa oferta e preço | Não demonstra resultado futuro |
| Pesquisa externa | Amplia comparação | Requer adequação ao contexto |

## 57. Estimativas

| Estimativa | Valor central | Faixa | Unidade | Horizonte | Método | Fonte | Confiança |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Valor] | [Mín.–máx.] | [Unidade] | [Período] | [Preencher] | EVD/PRE-ARQ-___ | [Baixa/média/alta] |

Estimativa pontual sem faixa pode criar diferença artificial entre alternativas cuja incerteza é maior do que a vantagem aparente.

## 58. Incerteza

| Tipo | Exemplo | Tratamento |
| --- | --- | --- |
| Epistêmica | Falta conhecimento | Pesquisa, teste ou especialista |
| Variabilidade | Demanda muda naturalmente | Faixa, distribuição ou cenário |
| Implementação | Adoção e integração podem falhar | Piloto, ondas e contingência |
| Externa | Regulação ou mercado pode mudar | Cenários e gatilho |
| Modelo | Regra de pontuação influencia resultado | Métodos alternativos e sensibilidade |
| Estratégica | Participante ajusta resposta por interesse | Governança e revisão |

### 58.1 Registro de confiança

| Julgamento | Evidência | Confiança | O que poderia mudar | Ação |
| --- | --- | --- | --- | --- |
| [Preencher] | EVD-ARQ-___ | [Baixa/média/alta] | [Preencher] | [Aceitar, investigar, pilotar ou condicionar] |

## 59. Premissas

| ID | Premissa | Alternativas | Critérios afetados | Impacto se falsa | Teste | Gatilho | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PRE-ARQ-___ | [Preencher] | [IDs] | [IDs] | [Baixo/médio/alto/crítico] | TST/VAL-ARQ-___ | [Evento] | [Papel] |

### 59.1 Premissa crítica

Premissa é crítica quando sua falsidade altera admissibilidade, vencedor, custo material, risco residual ou capacidade de implantação. Ela exige evidência antes da decisão ou compromisso reversível.

## 60. Faixas e intervalos

| Métrica | ALT-A | ALT-B | ALT-C | Sobreposição | Interpretação |
| --- | --- | --- | --- | --- | --- |
| Custo em 24 meses | [Faixa] | [Faixa] | [Faixa] | [Sim/não] | [Preencher] |
| Tempo de implantação | [Faixa] | [Faixa] | [Faixa] | [Sim/não] | [Preencher] |
| Capacidade mensal | [Faixa] | [Faixa] | [Faixa] | [Sim/não] | [Preencher] |

Quando faixas se sobrepõem amplamente, declare equivalência prática ou necessidade de outra evidência em vez de ordenar por valores centrais mínimos.

## 61. Linha de referência e metas

| Medida | Referência atual | Resultado suficiente | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Valor/faixa] | [Condição] | [Estimativa] | [Estimativa] | [Estimativa] |

Meta aspiracional não deve ser usada como previsão de benefício. A avaliação compara capacidade provável contra resultado suficiente e horizonte explícito.

## 62. Arquitetura de benefícios

| Benefício | Beneficiário | Mecanismo | Indicador | Horizonte | Condições de realização | Evidência |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Grupo/organização] | [Como a alternativa produz] | IND/CRT-ARQ-___ | [Período] | [Preencher] | EVD/PRE-ARQ-___ |

Benefício sem mecanismo e condição de realização é intenção, não fundamento comparativo.

## 63. Cadeia de realização de valor

```text
componente implantado
  -> uso e comportamento
  -> capacidade operacional
  -> resultado intermediário
  -> resultado organizacional
  -> benefício sustentado
```

| Elo | Condição | Responsável | Evidência atual | Risco de ruptura |
| --- | --- | --- | --- | --- |
| Implantação → uso | [Preencher] | [Papel] | [Fonte] | RSC-ARQ-___ |
| Uso → capacidade | [Preencher] | [Papel] | [Fonte] | RSC-ARQ-___ |
| Capacidade → resultado | [Preencher] | [Papel] | [Fonte] | RSC-ARQ-___ |
| Resultado → benefício | [Preencher] | [Papel] | [Fonte] | RSC-ARQ-___ |

## 64. Dupla contagem de benefícios

| Benefício A | Benefício B | Relação causal/semântica | Risco de duplicação | Tratamento |
| --- | --- | --- | --- | --- |
| [Tempo reduzido] | [Custo reduzido] | Tempo pode originar custo | [Alto/médio/baixo] | [Manter um, decompor ou ajustar] |

Se o mesmo ganho aparece em vários critérios, a alternativa pode ser favorecida múltiplas vezes pelo mesmo fenômeno.

## 65. Custo integral

O custo integral inclui compromissos financeiros, humanos, cognitivos, temporais e de dependência ao longo do ciclo de vida.

| Classe | Exemplos |
| --- | --- |
| Aquisição | Licença, contratação, equipamento, desenvolvimento |
| Preparação | Desenho, limpeza de dados, configuração, jurídico |
| Implantação | Integração, migração, teste, comunicação e mudança |
| Aprendizagem | Treinamento, curva de domínio, revisão e erro inicial |
| Operação | Pessoas, consumo, suporte, infraestrutura e controle |
| Manutenção | Atualização, documentação, avaliação e correção |
| Incidente | Interrupção, resposta, reparação e perda de confiança |
| Dependência | Reajuste, indisponibilidade, escassez de competência |
| Saída | Exportação, migração, encerramento e reconstrução |
| Oportunidade | Trabalho adiado e capital comprometido |

## 66. Modelo de custo total

| Custo | Inicial | Recorrente | Eventual | Horizonte | Fonte | Incerteza |
| --- | --- | --- | --- | --- | --- | --- |
| Aquisição | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Implantação | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Pessoas internas | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Operação técnica | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Governança/controle | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Manutenção | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |
| Continuidade/saída | [R$] | [R$] | [R$] | [Período] | [Fonte] | [Faixa] |

### 66.1 Valor presente e horizonte

Quando valores futuros forem descontados, registre taxa, justificativa e efeito. Em projetos pequenos, uma comparação nominal por horizonte comum pode ser mais compreensível e suficiente.

## 67. Tempo interno e capacidade

| Papel | Horas de implantação | Horas mensais | Trabalho deslocado | Competência necessária | Disponibilidade real |
| --- | --- | --- | --- | --- | --- |
| [Papel] | [h] | [h] | [Preencher] | [Preencher] | [Confirmada/incerta] |

Tempo interno não é gratuito. Se as pessoas necessárias não estão disponíveis, a alternativa pode ser financeiramente acessível e operacionalmente inviável.

## 68. Custo de oportunidade e atraso

| Alternativa | Recurso comprometido | Trabalho adiado | Valor não capturado | Custo do atraso | Evidência |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Faixa/método] | EVD/PRE-ARQ-___ |

### 68.1 Urgência legítima

Urgência aumenta o custo de esperar, mas também pode reduzir a qualidade do desenho. Compare ação imediata, proteção temporária e decisão gradual.

## 69. Acessibilidade financeira

| Verificação | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- |
| Cabe no orçamento aprovado | [Sim/não/condição] | [Estado] | [Estado] |
| Fluxo de desembolso é suportável | [Estado] | [Estado] | [Estado] |
| Reserva para incerteza existe | [Estado] | [Estado] | [Estado] |
| Custo recorrente é sustentável | [Estado] | [Estado] | [Estado] |
| Saída está financiável | [Estado] | [Estado] | [Estado] |

Menor custo não é sinônimo de maior valor; maior benefício projetado não torna o compromisso financeiramente sustentável.

## 70. Impactos humanos

| Grupo | Mudança no trabalho/experiência | Benefício | Perda/risco | Intensidade | Duração | Voz na decisão |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Baixa/média/alta] | [Período] | [Forma] |

### 70.1 Distribuição

Registre separadamente:

- quem recebe o benefício;
- quem realiza o trabalho de transição;
- quem assume manutenção;
- quem perde autonomia ou acesso;
- quem fica exposto a erro;
- quem pode contestar;
- quem responde quando a alternativa falha.

## 71. Carga e qualidade do trabalho

| Dimensão | Atual | Alternativa | Evidência | Efeito |
| --- | --- | --- | --- | --- |
| Volume de tarefas | [Preencher] | [Preencher] | [Fonte] | [Melhora/piora/incerto] |
| Complexidade | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Fragmentação | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Interrupções | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Autonomia | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Responsabilidade | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Trabalho de verificação | [Preencher] | [Preencher] | [Fonte] | [Estado] |
| Aprendizagem | [Preencher] | [Preencher] | [Fonte] | [Estado] |

Automação pode reduzir execução e aumentar revisão, exceção, monitoramento e responsabilização. Compare o ciclo completo.

## 72. Equidade e acessibilidade

| Questão | Evidência | Alternativas afetadas | Proteção | Resultado |
| --- | --- | --- | --- | --- |
| Quem encontra barreira de acesso? | [Fonte] | [IDs] | [Preencher] | [Preencher] |
| Quem recebe qualidade inferior? | [Fonte] | [IDs] | [Preencher] | [Preencher] |
| Que idioma, dispositivo ou condição foi presumido? | [Fonte] | [IDs] | [Preencher] | [Preencher] |
| Quem não participou do teste? | [Fonte] | [IDs] | [Preencher] | [Preencher] |
| Existe canal alternativo? | [Fonte] | [IDs] | [Preencher] | [Preencher] |

Média de satisfação não demonstra ausência de barreira para grupos específicos.

## 73. Poder, autonomia e vigilância

| Mudança | Poder ampliado de | Poder reduzido de | Justificativa | Proteção | Contestação |
| --- | --- | --- | --- | --- | --- |
| [Decisão, acesso, monitoramento ou automação] | [Papel/grupo] | [Papel/grupo] | [Preencher] | [Controle] | [Canal] |

Uma alternativa pode ser eficiente e ainda criar concentração indevida, vigilância excessiva ou impossibilidade prática de contestação.

## 74. Mudança e aprendizagem

| Alternativa | Mudança de prática | Competência nova | Tempo de aprendizagem | Apoio | Risco de adoção aparente |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Faixa] | [Preencher] | [Preencher] |

Disponibilizar ferramenta não cria capacidade. A comparação inclui compreensão, prática assistida, tempo de incorporação e suporte posterior.

## 75. Matriz distributiva

| Alternativa | Benefícios concentrados | Benefícios distribuídos | Custos concentrados | Riscos concentrados | Grupo sem voz | Tratamento |
| --- | --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

Uma compensação só é legítima quando sua distribuição é visível e a autoridade para aceitá-la está identificada.

## 76. Impacto sobre processos e coordenação

| Dimensão | ALT-A | ALT-B | ALT-C | Evidência |
| --- | --- | --- | --- | --- |
| Etapas criadas/removidas | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Transferências | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Pontos de decisão | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Exceções | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Esperas | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Confirmações | [Preencher] | [Preencher] | [Preencher] | [Fonte] |
| Escalonamentos | [Preencher] | [Preencher] | [Preencher] | [Fonte] |

Uma alternativa não deve receber nota positiva por automatizar uma etapa que o redesenho poderia eliminar.

## 77. Informação, conhecimento e documentação

| Pergunta | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- |
| Que informação nova precisa existir? | [Preencher] | [Preencher] | [Preencher] |
| Qual é a fonte oficial? | [Preencher] | [Preencher] | [Preencher] |
| Que conhecimento deixa de ser tácito? | [Preencher] | [Preencher] | [Preencher] |
| Que documentação recorrente surge? | [Preencher] | [Preencher] | [Preencher] |
| Como decisões serão reconstruídas? | [Preencher] | [Preencher] | [Preencher] |
| Que retenção e descarte são exigidos? | [Preencher] | [Preencher] | [Preencher] |
| O que ocorre na saída? | [Preencher] | [Preencher] | [Preencher] |

## 78. Adequação tecnológica

| Critério técnico | Regra | ALT-A | ALT-B | ALT-C | Evidência |
| --- | --- | --- | --- | --- | --- |
| Compatibilidade | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Interoperabilidade | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Escalabilidade suficiente | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Disponibilidade | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Observabilidade | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Recuperação | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |
| Portabilidade | [Preencher] | [Estado] | [Estado] | [Estado] | EVD-ARQ-___ |

“Possui integração” não informa contrato, objeto, frequência, reconciliação, falha ou responsabilidade.

## 79. Segurança, privacidade e dados

| Elemento | ALT-A | ALT-B | ALT-C | Limite impeditivo |
| --- | --- | --- | --- | --- |
| Dados tratados | [Classes] | [Classes] | [Classes] | [Condição] |
| Finalidade | [Preencher] | [Preencher] | [Preencher] | [Condição] |
| Minimização | [Estado] | [Estado] | [Estado] | [Condição] |
| Acesso e segregação | [Estado] | [Estado] | [Estado] | [Condição] |
| Localização/transferência | [Estado] | [Estado] | [Estado] | [Condição] |
| Retenção e eliminação | [Estado] | [Estado] | [Estado] | [Condição] |
| Registro e resposta | [Estado] | [Estado] | [Estado] | [Condição] |
| Continuidade | [Estado] | [Estado] | [Estado] | [Condição] |

Parecer técnico ou jurídico necessário deve ser identificado como entrada competente, não simulado pela equipe de avaliação.

## 80. Alternativas com inteligência artificial

Além dos critérios comuns, compare:

| Dimensão | Pergunta | Evidência |
| --- | --- | --- |
| Necessidade | A tarefa realmente exige IA? | Comparação com processo, regra e busca |
| Qualidade | A saída atende ao uso em casos representativos? | EIA/CJI/TST-ARQ-___ |
| Variabilidade | Como erros e inconsistências se distribuem? | Avaliações e amostras |
| Supervisão | Revisão humana é efetiva e sustentável? | Simulação de carga e registros |
| Autonomia | Que ações a função pode executar? | Contrato FIA/IHA-ARQ-___ |
| Dados | Que contexto e exposição adicionais surgem? | Arquitetura de informação |
| Segurança | Há risco de instrução hostil, exfiltração ou abuso? | Testes adversariais |
| Deriva | Mudança de modelo altera resultado? | Baseline e monitoramento |
| Explicabilidade operacional | Usuário compreende limite e fundamento suficiente? | Teste com usuários |
| Interrupção | A função pode ser suspensa sem perder operação? | Contingência testada |
| Portabilidade | Prompts, avaliações e memória funcional podem migrar? | Plano de saída |
| Custo variável | Custo por resultado aprovado é sustentável? | Medição completa |

### 80.1 Comparador mínimo

Toda alternativa com IA deve ser confrontada, quando legítimo, com:

1. melhoria de processo humano;
2. regra determinística;
3. busca ou recuperação de informação;
4. IA com menor autonomia;
5. não adoção ou piloto.

## 81. Fornecedor e proposta comercial

| Aspecto | Proposta | Evidência independente | Lacuna | Efeito na avaliação |
| --- | --- | --- | --- | --- |
| Funcionalidade | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Preço | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Nível de serviço | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Segurança | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Portabilidade | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Roadmap | [Preencher] | [Preencher] | [Preencher] | [Preencher] |
| Referências | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

Promessa de roadmap não recebe o mesmo estado de funcionalidade contratada e verificada.

## 82. Dependência e aprisionamento

| Dependência | Objeto dependente | Substituibilidade | Custo de troca | Prazo de saída | Proteção |
| --- | --- | --- | --- | --- | --- |
| [Fornecedor, formato, modelo, pessoa, licença ou integração] | [IDs] | [Alta/média/baixa] | [Faixa] | [Faixa] | [Preencher] |

### 82.1 Aprisionamento invisível

O aprisionamento pode estar em:

- formato de dados;
- histórico sem exportação suficiente;
- conhecimento de configuração;
- automações proprietárias;
- identidade e acesso;
- contratos e multas;
- integrações periféricas;
- prompts, avaliações e memória de IA;
- hábitos organizacionais;
- ausência de operação alternativa.

## 83. Manutenção e competência

| Componente | Manutenção | Frequência | Competência | Capacidade disponível | Alternativa se ausente |
| --- | --- | --- | --- | --- | --- |
| CMP-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Sim/não/incerta] | [Preencher] |

Uma arquitetura pode ser implementável e não ser sustentável. Avalie quem corrigirá erros, atualizará regras, responderá incidentes, treinará pessoas e decidirá mudanças.

## 84. Continuidade e resiliência

| Falha | ALT-A | ALT-B | ALT-C | Tempo tolerável | Evidência |
| --- | --- | --- | --- | --- | --- |
| Pessoa-chave indisponível | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |
| Ferramenta indisponível | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |
| Integração falha | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |
| Dado incorreto | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |
| Fornecedor encerra serviço | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |
| IA é suspensa | [Resposta] | [Resposta] | [Resposta] | [Tempo] | TST/EVD-ARQ-___ |

## 85. Reversibilidade e saída

| Dimensão | Pergunta | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- | --- |
| Decisão | Pode ser revertida por autoridade clara? | [Estado] | [Estado] | [Estado] |
| Dados | Podem ser exportados com significado? | [Estado] | [Estado] | [Estado] |
| Processo | Pode retornar ou migrar? | [Estado] | [Estado] | [Estado] |
| Pessoas | Competência anterior permanece? | [Estado] | [Estado] | [Estado] |
| Contrato | Encerramento é viável? | [Estado] | [Estado] | [Estado] |
| Tecnologia | Componentes podem ser substituídos? | [Estado] | [Estado] | [Estado] |
| Conhecimento | Configuração pode ser reconstruída? | [Estado] | [Estado] | [Estado] |
| Custo | Saída foi estimada? | [Estado] | [Estado] | [Estado] |

Reversibilidade não significa ausência de custo; significa conhecer o caminho, preservar possibilidade e atribuir responsabilidade.

## 86. Sustentabilidade organizacional

| Pergunta | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- |
| Cabe na capacidade de gestão? | [Preencher] | [Preencher] | [Preencher] |
| Depende de esforço heroico recorrente? | [Preencher] | [Preencher] | [Preencher] |
| Mantém conhecimento interno suficiente? | [Preencher] | [Preencher] | [Preencher] |
| Permite melhoria sem ruptura constante? | [Preencher] | [Preencher] | [Preencher] |
| Possui consumo técnico proporcional? | [Preencher] | [Preencher] | [Preencher] |
| Pode ser simplificada no futuro? | [Preencher] | [Preencher] | [Preencher] |

Quando impacto ambiental ou consumo de recursos for material, inclua energia, equipamento, descarte e cadeia de fornecimento com evidência apropriada.

## 87. Legitimidade, ética e conformidade

| Questão | Origem | Alternativas | Parecer/evidência | Resultado |
| --- | --- | --- | --- | --- |
| A finalidade é legítima? | [Princípio/norma] | [IDs] | [Fonte] | [Estado] |
| Pessoas compreendem efeitos relevantes? | [Princípio] | [IDs] | [Fonte] | [Estado] |
| Existe contestação efetiva? | [Princípio/norma] | [IDs] | [Fonte] | [Estado] |
| Direitos são preservados? | [Norma] | [IDs] | [Fonte] | [Estado] |
| Responsabilidade permanece atribuída? | [Governança] | [IDs] | [Fonte] | [Estado] |
| Uso secundário é impedido? | [Finalidade] | [IDs] | [Fonte] | [Estado] |

Conformidade formal é necessária quando aplicável, mas pode não ser suficiente para legitimidade, confiança e coerência com os princípios do projeto.

## 88. Arquitetura de riscos

| Risco | Alternativa | Causa | Evento | Consequência | Exposição inerente | Controle | Exposição residual |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSC-ARQ-___ | ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Faixa] | CTL-ARQ-___ | [Faixa] |

### 88.1 Riscos comparáveis e específicos

- riscos comuns devem usar a mesma escala;
- riscos específicos permanecem visíveis, mesmo sem equivalente;
- ausência de histórico não significa risco baixo;
- risco da transição não deve ser confundido com risco da operação;
- controle planejado não equivale a controle eficaz;
- risco transferido contratualmente pode continuar produzindo impacto organizacional.

## 89. Carga dos controles

| Controle | Risco tratado | Trabalho criado | Custo | Autonomia afetada | Eficácia esperada | Alternativa proporcional |
| --- | --- | --- | --- | --- | --- | --- |
| CTL-ARQ-___ | RSC-ARQ-___ | [Preencher] | [Faixa] | [Preencher] | [Evidência] | [Preencher] |

Uma alternativa não deve parecer segura porque acumula controles inviáveis de operar.

## 90. Risco residual e aceitação

| Risco residual | Alternativa | Pessoas/capacidades expostas | Justificativa | Autoridade | Condições | Revisão |
| --- | --- | --- | --- | --- | --- | --- |
| RSC-ARQ-___ | ALT-ARQ-___ | [Preencher] | [Preencher] | [Nome/papel] | [Limites] | [Gatilho/data] |

Aceitar risco é decisão; não é o estado automático de tudo que não foi tratado.

## 91. Viabilidade de implantação

| Dimensão | Critério | ALT-A | ALT-B | ALT-C |
| --- | --- | --- | --- | --- |
| Patrocínio | Autoridade e compromisso existem? | [Estado] | [Estado] | [Estado] |
| Recursos | Pessoas e orçamento estão disponíveis? | [Estado] | [Estado] | [Estado] |
| Sequência | Dependências podem ser resolvidas? | [Estado] | [Estado] | [Estado] |
| Dados | Qualidade e migração são viáveis? | [Estado] | [Estado] | [Estado] |
| Técnica | Configuração pode ser construída? | [Estado] | [Estado] | [Estado] |
| Mudança | Pessoas podem aprender e adotar? | [Estado] | [Estado] | [Estado] |
| Prazo | Janela é realista? | [Estado] | [Estado] | [Estado] |
| Retorno | Reversão ou contingência existe? | [Estado] | [Estado] | [Estado] |

## 92. Dependências e pré-condições

| Dependência | Alternativa | Tipo | Dono | Estado | Prazo | Efeito se ausente |
| --- | --- | --- | --- | --- | --- | --- |
| DEP-ARQ-___ | ALT-ARQ-___ | [Interna, externa, técnica, humana ou decisória] | [Papel] | [Estado] | [Data] | [Preencher] |

### 92.1 Dependência circular

Se a alternativa A depende de capacidade que somente existirá depois da própria implantação, registre o mecanismo de criação inicial, o estado transitório ou a inviabilidade.

## 93. Sequência e tempo para valor

| Marco | ALT-A | ALT-B | ALT-C | Critério de entrada | Critério de saída |
| --- | --- | --- | --- | --- | --- |
| Preparação | [Prazo] | [Prazo] | [Prazo] | [Preencher] | [Preencher] |
| Piloto/primeiro uso | [Prazo] | [Prazo] | [Prazo] | [Preencher] | [Preencher] |
| Capacidade mínima | [Prazo] | [Prazo] | [Prazo] | [Preencher] | [Preencher] |
| Estabilização | [Prazo] | [Prazo] | [Prazo] | [Preencher] | [Preencher] |
| Benefício sustentado | [Prazo] | [Prazo] | [Prazo] | [Preencher] | [Preencher] |

Tempo de instalação não equivale a tempo para capacidade nem a tempo para benefício.

## 94. Risco da transição

| Transição | Capacidade ameaçada | Probabilidade | Impacto | Proteção | Retorno |
| --- | --- | --- | --- | --- | --- |
| [Migração, troca de papel, corte, integração ou treinamento] | CAP-ARQ-___ | [Faixa] | [Faixa] | [Preencher] | [Preencher] |

Uma alternativa futura superior pode ser inadequada quando seu caminho de transição destrói capacidade crítica ou excede tolerância organizacional.

## 95. Cenários

| ID | Cenário | Condições | Variáveis alteradas | Horizonte | Objetivo |
| --- | --- | --- | --- | --- | --- |
| CEN-ARQ-___ | [Nome] | [Preencher] | [Demanda, custo, pessoa, fornecedor ou outro] | [Período] | [O que testar] |

O cenário deve ser plausível e material. Ele não é narrativa criada apenas para favorecer ou derrubar uma alternativa.

## 96. Cenários mínimos

Examine, conforme o escopo:

1. operação normal;
2. demanda inferior à prevista;
3. pico de demanda;
4. ausência de pessoa-chave;
5. atraso de implantação;
6. custo acima da estimativa;
7. qualidade abaixo do esperado;
8. falha de ferramenta ou integração;
9. indisponibilidade de fornecedor;
10. incidente de segurança ou privacidade;
11. mudança regulatória ou contratual;
12. necessidade de saída antecipada.

| Cenário | ALT-A | ALT-B | ALT-C | Alternativa mais robusta | Evidência necessária |
| --- | --- | --- | --- | --- | --- |
| CEN-ARQ-___ | [Resultado] | [Resultado] | [Resultado] | [ID/empate] | [Preencher] |

## 97. Matriz comparativa qualitativa

| Critério | Importância | ALT-A | Evidência | ALT-B | Evidência | ALT-C | Evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CRT-ARQ-___ | [Determinante/alta/média/baixa] | [Rubrica] | EVD-ARQ-___ | [Rubrica] | EVD-ARQ-___ | [Rubrica] | EVD-ARQ-___ |

### 97.1 Síntese por alternativa

| Alternativa | Forças demonstradas | Limitações | Condições | Incerteza | Compensação principal |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 98. Matriz comparativa quantitativa

| Critério | Peso | ALT-A nota | ALT-A evidência | ALT-B nota | ALT-B evidência | ALT-C nota | ALT-C evidência |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CRT-ARQ-___ | [Valor] | [Nota] | EVD-ARQ-___ | [Nota] | EVD-ARQ-___ | [Nota] | EVD-ARQ-___ |

| Alternativa | Pontuação indicativa | Critérios desconhecidos | Impedimentos | Confiança | Interpretação |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Valor/faixa] | [IDs] | [IDs/nenhum] | [Baixa/média/alta] | [Preencher] |

Não publique pontuação sem as notas, pesos, escalas, evidências e exceções que a produziram.

## 99. Mapa valor–esforço–risco

| Alternativa | Valor esperado | Esforço integral | Risco residual | Reversibilidade | Confiança |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Faixa] | [Faixa] | [Faixa] | [Nível] | [Nível] |

O mapa é uma visão de síntese. Ele não substitui análise distributiva, requisito obrigatório nem dependência crítica.

## 100. Análise de dominância

| Alternativa analisada | Possível dominante | Critérios iguais/melhores | Critérios piores | Conclusão |
| --- | --- | --- | --- | --- |
| ALT-ARQ-___ | ALT-ARQ-___ | [IDs] | [IDs/nenhum] | [Dominada, não dominada ou inconclusiva] |

### 100.1 Dominância aparente

Antes de eliminar uma alternativa dominada, confirme:

- mesma qualidade de evidência;
- mesmas condições e horizonte;
- ausência de critério omitido;
- ausência de grupo afetado invisível;
- custo e risco medidos na mesma base.

## 101. Fronteira eficiente e compensações

| Alternativa não dominada | Ganho determinante | Perda determinante | Quem recebe o ganho | Quem assume a perda |
| --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

Quando várias alternativas permanecem não dominadas, a decisão depende de prioridade legítima e aceitação explícita da compensação, não de busca por um vencedor matemático inexistente.

## 102. Sensibilidade aos pesos

| Teste | Alteração | Resultado original | Novo resultado | Mudança material? |
| --- | --- | --- | --- | --- |
| SNS-ARQ-___ | [Peso CRT X +/− faixa] | [Ordenação] | [Ordenação] | [Sim/não] |
| SNS-ARQ-___ | [Prioridade do grupo Y] | [Ordenação] | [Ordenação] | [Sim/não] |

### 102.1 Peso de troca

Identifique a menor variação plausível capaz de alterar a recomendação. Se pequena, a conclusão é sensível e deve ser apresentada como tal.

## 103. Sensibilidade às notas

| Critério | Alternativa | Nota central | Faixa plausível | Efeito no resultado | Evidência a melhorar |
| --- | --- | --- | --- | --- | --- |
| CRT-ARQ-___ | ALT-ARQ-___ | [Nota] | [Faixa] | [Preencher] | [Preencher] |

Evite testar variações arbitrárias. Use faixa sustentada por incerteza da evidência ou divergência entre avaliadores.

## 104. Sensibilidade a premissas e custos

| Premissa/variável | Valor base | Limite inferior | Limite superior | Alternativa favorecida | Ponto de mudança |
| --- | --- | --- | --- | --- | --- |
| PRE-ARQ-___ | [Valor] | [Valor] | [Valor] | [ID] | [Valor/condição] |

Exemplos:

- volume de demanda;
- taxa de adoção;
- custo por uso;
- tempo de revisão;
- rotatividade de equipe;
- inflação contratual;
- qualidade de dados;
- incidência de exceções.

## 105. Ponto de equilíbrio

| Comparação | Variável | Condição em que A supera B | Faixa provável | Conclusão |
| --- | --- | --- | --- | --- |
| ALT-A x ALT-B | [Volume, prazo, custo ou qualidade] | [Valor/condição] | [Faixa] | [Robusta/sensível/inconclusiva] |

O ponto de equilíbrio torna visível quando uma alternativa somente vence sob escala, adoção ou desempenho que ainda não estão demonstrados.

## 106. Robustez da recomendação

| Teste | Resultado | Estabilidade | Observação |
| --- | --- | --- | --- |
| Pesos plausíveis | [Preencher] | [Alta/média/baixa] | [Preencher] |
| Notas incertas | [Preencher] | [Alta/média/baixa] | [Preencher] |
| Cenários adversos | [Preencher] | [Alta/média/baixa] | [Preencher] |
| Custos máximos | [Preencher] | [Alta/média/baixa] | [Preencher] |
| Benefícios mínimos | [Preencher] | [Alta/média/baixa] | [Preencher] |
| Premissas críticas | [Preencher] | [Alta/média/baixa] | [Preencher] |

### 106.1 Classificação

| Classe | Definição | Consequência |
| --- | --- | --- |
| Robusta | Permanece recomendada em variações plausíveis | Pode avançar com condições normais |
| Condicional | Vence sob conjunto explícito de condições | Decisão precisa preservar gates e gatilhos |
| Sensível | Pequena variação altera conclusão | Obter evidência ou decidir por reversibilidade |
| Inconclusiva | Evidência não distingue legitimamente | Pilotar, adiar ou retornar ao desenho |

## 107. Escolha do método

| Situação | Método principal | Complemento |
| --- | --- | --- |
| Poucas alternativas e critérios claros | Comparação qualitativa estruturada | Admissibilidade e compensações |
| Vários critérios comparativos | Modelo ponderado transparente | Sensibilidade |
| Benefício equivalente | Custo-efetividade | Riscos e distribuição |
| Orçamento fixo | Maximização de valor dentro da restrição | Cenários |
| Incerteza elevada | Decisão robusta e piloto | Gatilhos |
| Critérios conflitantes sem unidade comum | Fronteira eficiente/deliberação | Registro de prioridade |
| Portfólio de iniciativas | Priorização e dependências | Capacidade e sequência |

Método mais complexo só é melhor quando aumenta compreensão e qualidade da decisão.

## 108. Comparação qualitativa estruturada

Use quando escalas numéricas criariam precisão artificial.

| Critério | Determinante? | ALT-A | ALT-B | Diferença material | Julgamento |
| --- | --- | --- | --- | --- | --- |
| CRT-ARQ-___ | [Sim/não] | [Evidência e rubrica] | [Evidência e rubrica] | [Preencher] | [Preencher] |

O resultado pode ser “A é preferível se X for prioritário; B é preferível se Y for prioritário”, acompanhado da decisão sobre a prioridade.

## 109. Modelo ponderado transparente

Aplicar somente quando:

- critérios comparativos são suficientemente independentes;
- escalas possuem âncoras;
- pesos têm significado;
- evidências são comparáveis;
- impedimentos foram tratados separadamente;
- sensibilidade será testada;
- decisores compreendem limites do modelo.

### 109.1 Auditoria do modelo

| Elemento | Versão | Responsável | Revisão | Resultado |
| --- | --- | --- | --- | --- |
| Critérios | [Versão] | [Papel] | [Nome] | [Aprovado/ajustado] |
| Pesos | [Versão] | [Papel] | [Nome] | [Aprovado/ajustado] |
| Escalas | [Versão] | [Papel] | [Nome] | [Aprovado/ajustado] |
| Notas | [Versão] | [Papel] | [Nome] | [Aprovado/ajustado] |
| Fórmula | [Versão] | [Papel] | [Nome] | [Aprovado/ajustado] |

## 110. Custo-efetividade

Quando alternativas entregam resultado comparável, examine custo por unidade de resultado aprovado.

| Alternativa | Resultado útil | Custo integral | Unidade | Razão | Incerteza |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Quantidade/qualidade] | [R$] | [Ex.: caso concluído] | [R$/unidade] | [Faixa] |

Resultado bruto não é resultado útil. Em IA, por exemplo, considere saída aprovada após revisão, correção e falha, não apenas quantidade gerada.

## 111. Priorização de portfólio

Quando a decisão envolve várias iniciativas, separe:

1. valor e admissibilidade de cada iniciativa;
2. dependências entre iniciativas;
3. capacidade simultânea de implantação;
4. sequência que cria capacidades habilitadoras;
5. risco de concentração;
6. valor de opção de adiar.

| Iniciativa | Valor | Esforço | Dependências | Capacidade consumida | Janela | Prioridade |
| --- | --- | --- | --- | --- | --- | --- |
| ALT/ITM-ARQ-___ | [Faixa] | [Faixa] | DEP-ARQ-___ | [Papéis/horas] | [Período] | [Preencher] |

Ranking isolado não produz portfólio executável.

## 112. Deliberação e participação

| Sessão | Objetivo | Participantes | Materiais prévios | Decisão permitida | Registro |
| --- | --- | --- | --- | --- | --- |
| SES-AVA-___ | [Critérios, evidências, compensações ou recomendação] | [Nomes/papéis] | [Referências] | [Preencher] | [Link] |

### 112.1 Proteções de participação

- distribuir critérios e evidências antes da sessão;
- coletar julgamento inicial antes da discussão quando útil;
- alternar ordem de apresentação das alternativas;
- distinguir fato, interpretação, preferência e decisão;
- registrar mudança de posição e sua razão;
- impedir que senioridade substitua evidência;
- oferecer canal reservado para risco ou discordância;
- verificar participação de pessoas que sustentam a operação.

## 113. Vieses e manipulação

| Viés/risco | Manifestação | Proteção |
| --- | --- | --- |
| Ancoragem | Primeira opção domina | Geração independente e ordem variável |
| Confirmação | Busca apenas evidência favorável | Hipótese contrária e revisor |
| Status quo | Atual parece sem custo | Alternativa de manutenção completa |
| Novidade | Sofisticação parece valor | Critérios de resultado e simplicidade |
| Custo afundado | Investimento passado domina | Avaliar custos futuros evitáveis |
| Autoridade | Opinião hierárquica vira fato | Evidência e julgamento separados |
| Disponibilidade | Caso recente domina frequência real | Dados e amostra |
| Precisão | Número exato parece confiável | Faixas e método |
| Enquadramento | Ganho/perda altera preferência | Apresentar ambos |
| Peso estratégico | Participante manipula importância | Justificativa e sensibilidade |
| Alternativa isca | Opção fraca favorece outra | Diversidade material |

### 113.1 Teste de decisão prévia

Pergunte anonimamente, antes da comparação: “qual alternativa você acredita que será escolhida e por quê?”. Se todos já tratam uma opção como vencedora, reforce independência dos critérios, da evidência e da revisão.

## 114. Apoio de inteligência artificial

IA pode apoiar:

- extrair critérios de documentos com confirmação humana;
- identificar duplicidades e lacunas;
- organizar evidências por alternativa;
- calcular cenários e sensibilidade a partir de modelo aprovado;
- testar consistência aritmética;
- resumir compensações preservando fontes;
- gerar perguntas adversariais;
- localizar afirmações sem evidência;
- produzir rascunhos de matrizes e relatórios.

IA não deve:

- definir sozinha critérios e pesos;
- inventar alternativas sem exame contextual;
- avaliar pessoas ou fornecedores com dados não autorizados;
- tratar fluência como prova;
- converter lacuna em nota;
- aceitar risco residual;
- escolher a configuração;
- apagar divergência;
- emitir decisão institucional.

### 114.1 Registro do apoio

| Função de IA | Entrada | Saída | Verificador | Correção material | Uso autorizado |
| --- | --- | --- | --- | --- | --- |
| FIA-ARQ-___ | [Referências] | [Objeto] | [Papel] | [Sim/não e síntese] | [Preencher] |

## 115. Revisão independente

| Pergunta de revisão | Resultado | Evidência | Ação |
| --- | --- | --- | --- |
| A decisão foi delimitada sem solução embutida? | [Preencher] | [Referência] | [Preencher] |
| Alternativas são materialmente distintas? | [Preencher] | [Referência] | [Preencher] |
| Existe comparabilidade suficiente? | [Preencher] | [Referência] | [Preencher] |
| Critérios precedem notas? | [Preencher] | [Referência] | [Preencher] |
| Impedimentos estão fora da soma? | [Preencher] | [Referência] | [Preencher] |
| Evidências e premissas estão separadas? | [Preencher] | [Referência] | [Preencher] |
| Impactos distribuídos estão visíveis? | [Preencher] | [Referência] | [Preencher] |
| Custos cobrem o ciclo de vida? | [Preencher] | [Referência] | [Preencher] |
| Sensibilidade foi examinada? | [Preencher] | [Referência] | [Preencher] |
| Recomendação corresponde à análise? | [Preencher] | [Referência] | [Preencher] |

O revisor não precisa produzir outra decisão. Precisa testar se o processo permite uma decisão legítima e reconstruível.

## 116. Síntese comparativa

| Dimensão | ALT-A | ALT-B | ALT-C | Diferença determinante | Confiança |
| --- | --- | --- | --- | --- | --- |
| Admissibilidade | [Resultado] | [Resultado] | [Resultado] | [Preencher] | [Nível] |
| Atendimento | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Valor | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Pessoas | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Risco | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Custo integral | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Implantação | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Sustentação | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Reversibilidade | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |
| Robustez | [Síntese] | [Síntese] | [Síntese] | [Preencher] | [Nível] |

### 116.1 Questões que permanecem abertas

| Questão | Por que importa | Evidência necessária | Efeito possível | Decisão atual |
| --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Muda admissibilidade, recomendação ou condição] | [Aceitar, investigar ou suspender] |

## 117. Recomendação

> Recomenda-se **[selecionar, combinar, pilotar, adiar ou não intervir]** a alternativa **[ALT-ARQ-___]** para **[decisão e resultado]**, porque **[diferenças determinantes sustentadas por evidência]**. A recomendação é **[robusta, condicional, sensível ou inconclusiva]** e permanece válida enquanto **[premissas e limites]**. Exige **[condições]** antes de **[decisão, implantação ou expansão]** e deve ser reavaliada quando **[gatilhos]**.

### 117.1 Estrutura completa

| Campo | Registro |
| --- | --- |
| Dossiê | AVA-ARQ-___ |
| Alternativa recomendada | ALT-ARQ-___ |
| Tipo | [Selecionar, combinar, pilotar, adiar, não intervir ou redesenhar] |
| Decisão apoiada | [Preencher] |
| Critérios determinantes | CRT-ARQ-___ |
| Evidências determinantes | EVD-ARQ-___ |
| Alternativa mais próxima | ALT-ARQ-___ |
| Compensação principal | [Preencher] |
| Riscos residuais | RSC-ARQ-___ |
| Premissas críticas | PRE-ARQ-___ |
| Robustez | [Classe] |
| Condições | [Preencher] |
| Gatilhos de revisão | [Preencher] |
| Responsável pela recomendação | [Nome/papel] |
| Data | [DD/MM/AAAA] |

### 117.2 Recomendação inconclusiva

Quando a evidência não distingue alternativas, recomende explicitamente:

- produzir evidência focal;
- realizar protótipo ou piloto;
- redesenhar alternativas;
- limitar compromisso;
- manter proteção temporária;
- adiar com gatilho;
- decidir por reversibilidade quando a espera for mais custosa.

## 118. Decisão humana

| Campo | Registro |
| --- | --- |
| ID | DEC-ARQ-___ |
| Decisão | [Preencher] |
| Alternativa/configuração | ALT/CMP-ARQ-___ |
| Decisor | [Nome/papel] |
| Alçada | [Referência] |
| Data | [DD/MM/AAAA] |
| Recomendação recebida | [Referência] |
| Resultado | [Aprovada, aprovada com condição, devolvida, adiada ou rejeitada] |
| Justificativa | [Preencher] |
| Compensações aceitas | [Preencher] |
| Riscos residuais aceitos | RSC-ARQ-___ |
| Condições | [Preencher] |
| Limites | [Preencher] |
| Gatilhos de revisão | [Preencher] |
| Comunicação | [Referência] |

### 118.1 Autoridade não é evidência

O decisor pode escolher entre alternativas admissíveis segundo prioridade legítima. Sua posição não altera retrospectivamente fatos, custos, riscos ou resultados de validação.

## 119. Decisão diferente da recomendação

| Elemento | Recomendação | Decisão | Diferença | Justificativa do decisor | Proteção |
| --- | --- | --- | --- | --- | --- |
| Alternativa | [ID] | [ID] | [Preencher] | [Preencher] | [Condição/monitoramento] |
| Risco aceito | [Síntese] | [Síntese] | [Preencher] | [Preencher] | [Controle] |
| Custo | [Faixa] | [Faixa] | [Preencher] | [Preencher] | [Limite] |
| Impacto | [Síntese] | [Síntese] | [Preencher] | [Preencher] | [Proteção] |

Escolha diferente não invalida o método, desde que permaneça dentro da autoridade, respeite impedimentos e registre compensações.

## 120. Dissenso e divergência

| ID | Tema | Posição A | Posição B | Evidências | Valor em disputa | Efeito | Tratamento |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DIV-ARQ-___ | [Preencher] | [Preencher] | [Preencher] | [IDs] | [Prioridade, risco ou impacto] | [Preencher] | [Decisão, teste ou preservação] |

### 120.1 Parecer minoritário

> **Papel/pessoa:** [Preencher]  
> **Alternativa defendida ou contestada:** [ID]  
> **Fundamento:** [Preencher]  
> **Evidências:** [IDs]  
> **Risco se a posição estiver correta:** [Preencher]  
> **Condição para revisão:** [Preencher]

Dissenso fundamentado é conhecimento do sistema, não ruído a ser eliminado.

## 121. Condições, compromissos e gatilhos

| Condição | Tipo | Momento | Responsável | Evidência de cumprimento | Consequência se ausente |
| --- | --- | --- | --- | --- | --- |
| COND-ARQ-___ | [Antes da implantação, expansão ou operação] | [Data/gate] | [Papel] | [Referência] | [Suspender, reduzir, voltar ou reavaliar] |

| Gatilho | Objeto monitorado | Limite/evento | Responsável | Ação | Registro |
| --- | --- | --- | --- | --- | --- |
| GAT-ARQ-___ | [Custo, qualidade, risco, volume, fornecedor ou outro] | [Condição] | [Papel] | [Reabrir, suspender, expandir ou encerrar] | [Referência] |

### 121.1 Compromisso decisório

| Compromisso | Dono | Prazo | Recurso | Dependência | Estado |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Papel] | [Data] | [Preencher] | DEP-ARQ-___ | [Estado] |

Condição sem dono e consequência não protege a decisão.

## 122. Configuração selecionada

| Elemento | Alternativa de origem | Estado aprovado | Ajuste após avaliação | Componente derivado |
| --- | --- | --- | --- | --- |
| [Processo, papel, regra, informação, tecnologia, IA ou controle] | ALT-ARQ-___ | [Preencher] | [Preencher] | CMP-ARQ-___ |

### 122.1 Teste de coerência da combinação

- os componentes sustentam a mesma tese de funcionamento?
- responsabilidades permanecem claras?
- interfaces adicionais foram desenhadas?
- custos e riscos da combinação foram recalculados?
- controles continuam proporcionais?
- manutenção possui responsável?
- a configuração combinada foi submetida aos critérios?
- a decisão corresponde à versão integrada?

### 122.2 Configuração mínima, inicial e evolutiva

| Horizonte | Conteúdo aprovado | Condição de entrada | Decisão necessária |
| --- | --- | --- | --- |
| Mínima | [Componentes essenciais] | [Preencher] | DEC-ARQ-___ |
| Inicial | [Configuração após estabilização] | [Preencher] | DEC-ARQ-___ |
| Evolutiva | [Possibilidade não aprovada agora] | [Gatilho] | Nova avaliação |

Possibilidade futura não deve ser apresentada à implantação como escopo já aprovado.

## 123. Alternativas não selecionadas

| Alternativa | Resultado | Valor preservado | Motivo | Condição de retorno | Destino do conhecimento |
| --- | --- | --- | --- | --- | --- |
| ALT-ARQ-___ | [Rejeitada, adiada, combinada ou superada] | [Preencher] | [IDs/síntese] | [Evento/evidência] | [Referência] |

### 123.1 Encerramento responsável

Registre:

- proposta e versão avaliadas;
- critérios determinantes;
- evidências ainda válidas;
- componente reutilizado na configuração escolhida;
- promessa que não foi demonstrada;
- condição que pode tornar a alternativa relevante no futuro;
- dado ou acesso que precisa ser encerrado após piloto.

## 124. Validação da avaliação e da alternativa

Existem dois objetos distintos:

| Objeto | Pergunta | Registro |
| --- | --- | --- |
| Processo de avaliação | A comparação foi íntegra, proporcional e rastreável? | Revisão do AVA |
| Configuração selecionada | A alternativa funciona sob critérios e cenários? | Registro de Validação |

### 124.1 Plano de validação derivado

| Diferença/hipótese | Alternativa | Critério | Método | Cenário | Resultado esperado | Gate |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | ALT-ARQ-___ | CRT/PRE/RSC-ARQ-___ | [Protótipo, teste, simulação, revisão ou piloto] | CEN-ARQ-___ | [Condição] | [Antes de decisão/implantação/expansão] |

### 124.2 Reabertura após validação

| Resultado | Efeito na alternativa | Efeito na comparação | Ação |
| --- | --- | --- | --- |
| Confirma | Mantém configuração | Aumenta confiança | Prosseguir |
| Confirma parcialmente | Exige ajuste | Recalcular dimensão material | Condicionar/reavaliar |
| Refuta premissa | Pode inviabilizar | Reabrir comparação | Suspender decisão |
| Revela alternativa nova | Amplia espaço | Gerar e comparar | Reabrir desenho |

## 125. Rastreabilidade

| Origem | Relação | Destino | Evidência/estado |
| --- | --- | --- | --- |
| REQ-ARQ-___ | restringe/é_atendido_por | ALT-ARQ-___ | [Estado/EVD] |
| RSC-ARQ-___ | afeta/é_tratado_por | ALT/CTL-ARQ-___ | [Estado] |
| CRT-ARQ-___ | avalia | ALT-ARQ-___ | [Rubrica/nota] |
| EVD-ARQ-___ | sustenta | [Julgamento/estimativa] | [Qualidade] |
| PRE-ARQ-___ | condiciona | ALT/DEC-ARQ-___ | [Estado] |
| ALT-ARQ-___ | é_selecionada_por | DEC-ARQ-___ | [Resultado] |
| ALT-ARQ-___ | origina | CMP-ARQ-___ | [Versão] |
| TST/VAL-ARQ-___ | verifica | ALT/CMP/PRE-ARQ-___ | [Resultado] |
| DEC-ARQ-___ | autoriza | ITM-ARQ-___ | [Condição] |

### 125.1 Cobertura

| Verificação | Resultado | Lacuna | Tratamento |
| --- | --- | --- | --- |
| Todo requisito obrigatório foi testado? | [Preencher] | [IDs] | [Preencher] |
| Todo critério possui origem? | [Preencher] | [IDs] | [Preencher] |
| Toda nota determinante possui evidência? | [Preencher] | [IDs] | [Preencher] |
| Toda premissa crítica possui teste/gatilho? | [Preencher] | [IDs] | [Preencher] |
| Todo risco residual possui decisão? | [Preencher] | [IDs] | [Preencher] |
| Todo componente deriva de alternativa decidida? | [Preencher] | [IDs] | [Preencher] |

## 126. Passagem para a Arquitetura Integrada

| Conteúdo transferido | Referência | Forma de absorção |
| --- | --- | --- |
| Decisão e alternativa selecionada | DEC/ALT-ARQ-___ | Visão de alternativas e decisões |
| Componentes e relações | CMP/INT-ARQ-___ | Configuração aprovada |
| Requisitos e compensações | REQ/CRT-ARQ-___ | Cobertura e decisões materiais |
| Riscos e controles | RSC/CTL-ARQ-___ | Visão de riscos |
| Premissas e condições | PRE/COND-ARQ-___ | Limites e estados temporais |
| Validações | TST/VAL-ARQ-___ | Evidências e condições |
| Alternativas rejeitadas | ALT-ARQ-___ | Memória e condição de retorno |

### 126.1 Regra de absorção

A Arquitetura Integrada descreve a configuração aprovada. O dossiê de avaliação preserva o caminho comparativo completo. Não copie toda a matriz para a arquitetura nem reduza a decisão a uma frase sem referência.

## 127. Passagem para o Módulo 4 — Implantação

| Elemento decisório | Tradução para implantação |
| --- | --- |
| Configuração mínima/inicial | Escopo e entregas |
| Dependências | Sequência e caminho crítico |
| Condições | Gates de entrada e expansão |
| Premissas críticas | Hipóteses a testar cedo |
| Riscos de transição | Planos de resposta e retorno |
| Competências | Treinamento e suporte |
| Custos e capacidade | Orçamento e alocação |
| Cenários | Testes e contingências |
| Gatilhos | Decisões durante implantação |
| Critérios | Aceite das entregas |

### 127.1 Itens de implantação

| Item | Origem | Alternativa/componente | Responsável | Pré-condição | Aceite | Retorno |
| --- | --- | --- | --- | --- | --- | --- |
| ITM-ARQ-___ | DEC/ALT-ARQ-___ | CMP-ARQ-___ | [Papel] | COND/DEP-ARQ-___ | CRT/TST-ARQ-___ | [Plano] |

O Módulo 4 decide como realizar a configuração aprovada; mudança material de escopo retorna ao Módulo 3.

## 128. Passagem para o Módulo 5 — Operação

| Elemento | Pergunta operacional |
| --- | --- |
| Benefício esperado | Está sendo realizado e para quem? |
| Custo integral | Permanece dentro da faixa? |
| Premissa | Continua verdadeira? |
| Risco residual | A exposição mudou? |
| Condição | Permanece atendida? |
| Indicador | Que resposta aciona? |
| Alternativa de continuidade | Funciona quando necessária? |
| Gatilho | Exige ajuste, suspensão ou reavaliação? |

### 128.1 Registro previsto–real

| Medida/premissa | Previsto | Real | Diferença | Explicação | Decisão |
| --- | --- | --- | --- | --- | --- |
| [Preencher] | [Faixa] | [Valor/faixa] | [Preencher] | [Preencher] | [Manter, ajustar ou reabrir] |

## 129. Passagem para os Módulos 6 e 8

O Módulo 6 — Inteligência Organizacional deve receber:

- premissas confirmadas e refutadas;
- qualidade das estimativas;
- diferenças entre benefício previsto e realizado;
- riscos que emergiram;
- critérios que realmente distinguiram alternativas;
- evidências que foram úteis;
- compensações que produziram efeitos inesperados;
- alternativas rejeitadas que se tornaram relevantes.

O Módulo 8 — Evolução deve usar esse conhecimento para melhorar:

- escalas e critérios padrão;
- faixas de custo e prazo;
- perguntas de geração de alternativas;
- padrões de risco;
- profundidade proporcional;
- gates de validação;
- decisões de construir, contratar, configurar, automatizar ou adiar.

### 129.1 Registro de previsão

| Previsão | Método | Faixa | Resultado real | Erro | Causa | Aprendizagem reutilizável |
| --- | --- | --- | --- | --- | --- | --- |
| [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] | [Preencher] |

## 130. Ciclo de vida e reabertura

| Estado | Entrada | Saída | Responsável |
| --- | --- | --- | --- |
| Rascunho | Decisão preliminar | Escopo confirmado | [Papel] |
| Comparável | Alternativas completas | Gate aprovado | [Papel] |
| Avaliada | Matrizes concluídas | Recomendação | [Papel] |
| Decidida | Autoridade registrada | Integração | [Papel] |
| Monitorada | Implantação/operação | Confirmação ou gatilho | [Papel] |
| Reaberta | Mudança material | Nova decisão | [Papel] |
| Encerrada | Substituição/cessação | Arquivo e aprendizagem | [Papel] |

### 130.1 Gatilhos de reabertura

- requisito material muda;
- premissa crítica é refutada;
- custo ou prazo ultrapassa limite;
- benefício fica abaixo da condição mínima;
- risco residual cresce;
- fornecedor altera serviço ou contrato;
- solução perde compatibilidade;
- grupo afetado revela impacto não considerado;
- validação reprova componente determinante;
- alternativa antes indisponível torna-se viável;
- decisão muda de escala, autonomia ou finalidade.

### 130.2 Controle de mudança

| Mudança | Objeto | Materialidade | Partes da avaliação afetadas | Decisão | Nova versão |
| --- | --- | --- | --- | --- | --- |
| MUD-ARQ-___ | [ALT, CRT, EVD, PRE, custo ou risco] | [Baixa/média/alta/crítica] | [Preencher] | [Manter, recalcular, revalidar ou reabrir] | [Versão] |

## 131. Artefato, acesso e versões

### 131.1 Estrutura recomendada

```text
avaliacoes-de-alternativas/
`-- AVA-ARQ-AAAA-NNN/
    |-- 01-decisao-escopo-e-autoridade/
    |-- 02-alternativas-e-versoes/
    |-- 03-requisitos-criterios-e-escalas/
    |-- 04-evidencias-premissas-e-estimativas/
    |-- 05-admissibilidade/
    |-- 06-comparacao-custos-impactos-e-riscos/
    |-- 07-cenarios-sensibilidade-e-robustez/
    |-- 08-recomendacao-revisao-e-dissenso/
    |-- 09-decisao-condicoes-e-rastreabilidade/
    `-- 10-aprendizagem-e-reabertura/
```

### 131.2 Acesso

| Conteúdo | Acesso | Motivo | Responsável | Revisão |
| --- | --- | --- | --- | --- |
| Dossiê principal | [Papéis] | [Decisão] | [Papel] | [Frequência] |
| Propostas comerciais | [Restrito] | [Confidencialidade] | [Papel] | [Data] |
| Dados pessoais | [Restrito] | [Proteção] | [Papel] | [Data] |
| Pareceres | [Papéis] | [Competência] | [Papel] | [Data] |
| Decisão e síntese | [Papéis] | [Transparência] | [Papel] | [Data] |

### 131.3 Histórico

| Versão | Data | Alteração | Motivo | Evidência/decisão | Responsável |
| --- | --- | --- | --- | --- | --- |
| 0.1 | 02/08/2026 | Criação | Avaliação inicial | [Referência] | [Nome] |

## 132. Registro estruturado ilustrativo

```yaml
avaliacao_id: AVA-ARQ-2026-001
decisao:
  objeto: "[descrever]"
  decisor: PAP-ARQ-001
  horizonte: "[período]"
alternativas:
  - id: ALT-ARQ-001
    versao: "0.3"
    admissibilidade: admitida
  - id: ALT-ARQ-002
    versao: "0.2"
    admissibilidade: condicionada
criterios:
  obrigatorios: [CRT-ARQ-001]
  comparativos: [CRT-ARQ-002, CRT-ARQ-003]
evidencias: [EVD-ARQ-001, EVD-ARQ-002]
premissas_criticas: [PRE-ARQ-001]
sensibilidade:
  classe: condicional
  teste: SNS-ARQ-001
recomendacao:
  tipo: selecionar
  alternativa: ALT-ARQ-001
  condicoes: [COND-ARQ-001]
decisao_registrada: DEC-ARQ-001
gatilhos: [GAT-ARQ-001]
```

### 132.1 Integridade do registro

- códigos resolvem para objetos existentes;
- versões avaliadas estão congeladas;
- escala e peso podem ser reconstruídos;
- evidência possui fonte e data;
- decisão aponta para a recomendação recebida;
- condição possui responsável e consequência;
- nenhum campo estruturado substitui justificativa material.

## 133. Checklists

### 133.1 Preparação

- [ ] decisão, escopo, horizonte e autoridade estão definidos;
- [ ] referência atual contém valor, custo e risco;
- [ ] alternativas incluem opções simples e não intervenção;
- [ ] alternativas são materialmente distintas;
- [ ] conflitos de interesse foram declarados;
- [ ] participantes afetados estão representados;
- [ ] profundidade é proporcional à decisão;
- [ ] critérios e impedimentos precedem as notas.

### 133.2 Alternativas e critérios

- [ ] cada alternativa possui tese de funcionamento;
- [ ] escopo, horizonte e nível de detalhe são equivalentes;
- [ ] transição, operação, manutenção e saída estão incluídas;
- [ ] critérios possuem definição, origem, escala e responsável;
- [ ] requisitos obrigatórios estão fora da compensação;
- [ ] sobreposição e dupla contagem foram examinadas;
- [ ] desconhecido, não aplicável e não atendido estão separados;
- [ ] pesos possuem justificativa anterior ao resultado.

### 133.3 Evidências e análise

- [ ] julgamentos determinantes possuem evidência;
- [ ] qualidade e conflito de interesse das fontes estão visíveis;
- [ ] estimativas possuem faixa e horizonte;
- [ ] premissas críticas possuem teste ou gatilho;
- [ ] benefícios possuem mecanismo e condição de realização;
- [ ] custos cobrem ciclo de vida e tempo interno;
- [ ] impactos humanos e distributivos foram examinados;
- [ ] riscos inerentes, controles e riscos residuais estão separados;
- [ ] viabilidade de implantação e sustentação foi comparada;
- [ ] cenários e sensibilidade foram executados proporcionalmente.

### 133.4 Recomendação e decisão

- [ ] recomendação corresponde à análise;
- [ ] robustez ou sensibilidade está declarada;
- [ ] compensações e grupos afetados estão visíveis;
- [ ] condições possuem dono, prazo e consequência;
- [ ] dissenso material está preservado;
- [ ] decisor e alçada estão confirmados;
- [ ] decisão divergente possui justificativa;
- [ ] riscos residuais foram aceitos por autoridade competente;
- [ ] alternativa escolhida foi integrada e versionada;
- [ ] alternativas rejeitadas possuem memória e condição de retorno;
- [ ] transição, monitoramento e reabertura estão preparados.

## 134. Exemplo integrado resumido

### 134.1 Contexto e decisão

O Estúdio precisa acompanhar demandas de clientes, responsáveis, prazos, decisões e documentos sem depender da memória de uma única pessoa. A decisão não é “qual aplicativo comprar?”, mas:

> Que configuração inicial permite manter cada demanda com estado, responsável, próxima ação, histórico e alerta, com baixa carga de manutenção e possibilidade de evolução?

### 134.2 Alternativas

| ID | Configuração | Tese |
| --- | --- | --- |
| ALT-ARQ-001 | Planilha controlada + repositório + ritual semanal | Estrutura simples e disciplina humana tornam o trabalho visível |
| ALT-ARQ-002 | Plataforma de gestão configurada + repositório integrado | Estados, responsáveis e alertas reduzem coordenação manual |
| ALT-ARQ-003 | Plataforma + IA para classificação e síntese | IA reduz trabalho cognitivo, com revisão humana antes de prioridade ou comunicação |
| ALT-ARQ-004 | Manter mensagens e registros atuais com checklist | Controles adicionais reduzem perda sem alterar o sistema atual |

### 134.3 Admissibilidade ilustrativa

| Condição | ALT-001 | ALT-002 | ALT-003 | ALT-004 |
| --- | --- | --- | --- | --- |
| Fonte oficial por demanda | Atende | Atende | Atende | Condiciona |
| Responsável e próxima ação | Atende | Atende | Atende | Condiciona |
| Histórico reconstruível | Atende | Atende | Atende | Não atende |
| Dados de cliente autorizados | Atende | Atende | Depende do contrato e configuração | Atende |
| Operação sem IA | N/A | Atende | Atende com contingência | N/A |

ALT-004 é devolvida porque o histórico permanece fragmentado. ALT-003 somente avança se dados, fornecedor, revisão e operação alternativa forem validados.

### 134.4 Critérios comparativos

| Critério | Importância | ALT-001 | ALT-002 | ALT-003 |
| --- | --- | --- | --- | --- |
| Clareza do fluxo | Alta | Suficiente | Forte | Forte |
| Carga de manutenção | Alta | Média | Baixa a média | Média devido à supervisão |
| Tempo para capacidade mínima | Alta | Curto | Médio | Longo |
| Custo em 12 meses | Alta | Baixo | Médio | Médio a alto |
| Continuidade | Determinante | Depende de disciplina | Boa com exportação | Boa apenas com modo sem IA |
| Evolução | Média | Limitada | Forte | Forte |
| Incerteza | Alta | Baixa | Média | Alta |

### 134.5 Compensações

| Alternativa | Ganho principal | Perda principal | Risco |
| --- | --- | --- | --- |
| ALT-001 | Entrada rápida e baixo custo | Manutenção manual crescente | Planilha se tornar sistema permanente sem revisão |
| ALT-002 | Coordenação e alertas estruturados | Configuração e aprendizagem inicial | Dependência da plataforma |
| ALT-003 | Potencial de síntese e triagem | Supervisão, dados e variabilidade | Automatizar antes de estabilizar processo |

### 134.6 Sensibilidade

- se o volume permanecer baixo, ALT-001 e ALT-002 ficam próximas em valor;
- se o custo do retrabalho manual aumentar, ALT-002 torna-se mais favorável;
- se a qualidade dos dados e o volume de síntese não forem suficientes, ALT-003 perde justificativa;
- se a plataforma não oferecer exportação adequada, ALT-002 deixa de ser robusta;
- se a demanda crescer antes da aprendizagem, a implantação simultânea de plataforma e IA aumenta risco.

### 134.7 Recomendação ilustrativa

Selecionar ALT-002 como futuro inicial, preservando uma operação mínima exportável e implantando por etapas. Tratar ALT-003 como possibilidade evolutiva, não como escopo atual: a função de IA somente será pilotada depois que estados, fonte oficial, qualidade dos dados e carga de revisão puderem ser medidos.

### 134.8 Decisão e gatilhos

| Elemento | Registro ilustrativo |
| --- | --- |
| Decisão | Aprovar ALT-002 com condição de exportação e contingência |
| Condição | Fluxo mínimo validado antes da configuração completa |
| Gatilho para IA | Volume e tempo de síntese acima de limite por dois ciclos |
| Gatilho de revisão | Custo, adoção ou qualidade fora da faixa por dois ciclos |
| Alternativa de continuidade | Registro manual controlado durante indisponibilidade |
| Aprendizagem esperada | Custo real por demanda acompanhada e carga de manutenção |

O exemplo demonstra que avaliação de alternativas não escolhe “a tecnologia mais avançada”. Ela escolhe a configuração adequada à capacidade atual, preserva evolução e impede que uma hipótese futura seja implantada como necessidade presente.

## 135. Indicadores, antipadrões, aprendizagem e conclusão

### 135.1 Indicadores de qualidade da aplicação

| Indicador | Pergunta | Fonte | Uso |
| --- | --- | --- | --- |
| Alternativas materialmente distintas | O espaço de decisão foi ampliado? | Registros ALT | Revisar geração |
| Cobertura de critérios | Critérios materiais foram aplicados? | Catálogo/matriz | Corrigir lacunas |
| Evidência determinante rastreável | Julgamentos centrais podem ser reconstruídos? | EVD | Reforçar análise |
| Premissas críticas testadas | A decisão depende de verdades não verificadas? | PRE/TST | Condicionar ou pilotar |
| Estabilidade da recomendação | A conclusão resiste a variações plausíveis? | SNS | Classificar robustez |
| Condições cumpridas | A decisão avança dentro dos limites? | COND | Liberar ou suspender |
| Erro de previsão | O previsto se aproximou do real? | Operação | Melhorar estimativas |
| Reaberturas materiais | Que gatilhos ocorreram? | Mudanças/decisões | Aprender sobre contexto |

### 135.2 Antipadrões

- começar pela marca ou ferramenta preferida;
- criar alternativas apenas para preencher a matriz;
- descrever a favorita em detalhe e as demais superficialmente;
- definir critérios depois de conhecer o resultado;
- rotular preferência como requisito obrigatório;
- usar pesos sem origem ou discussão;
- esconder impedimento dentro da média;
- converter desconhecido em zero;
- tratar proposta comercial como evidência de resultado;
- comparar custo de aquisição com custo integral de outra opção;
- contar economia de tempo e redução de custo como benefícios independentes sem ajuste;
- ignorar tempo interno, manutenção e saída;
- premiar alternativa nova pela ausência de incidentes históricos;
- usar muitas casas decimais para sugerir precisão;
- aceitar ranking instável como conclusão forte;
- escolher pela maioria sem autoridade ou análise distributiva;
- apagar dissenso após a decisão;
- combinar benefícios sem recomputar interfaces e riscos;
- enviar à implantação uma possibilidade evolutiva não aprovada;
- abandonar alternativas rejeitadas sem preservar aprendizado.

### 135.3 Aprendizagem da aplicação

| Pergunta | Registro |
| --- | --- |
| Que critério realmente diferenciou as alternativas? | [Preencher] |
| Que critério gerou carga sem alterar decisão? | [Preencher] |
| Que evidência mudou uma posição? | [Preencher] |
| Que premissa era mais frágil do que parecia? | [Preencher] |
| Que alternativa surgiu tarde e por quê? | [Preencher] |
| Onde houve dupla contagem ou falsa precisão? | [Preencher] |
| Que grupo revelou impacto invisível? | [Preencher] |
| Que estimativa deve melhorar no próximo projeto? | [Preencher] |
| Que proteção deve virar padrão do Estúdio? | [Preencher] |

### 135.4 Critérios de conclusão

- [ ] decisão, autoridade, fronteira e horizonte estão explícitos;
- [ ] referência atual contém valor, custo e risco;
- [ ] alternativas são reais, coerentes e comparáveis;
- [ ] manutenção, simplificação, piloto, adiamento ou não intervenção foram examinados;
- [ ] critérios e impedimentos foram definidos previamente;
- [ ] admissibilidade foi concluída antes da comparação;
- [ ] evidências, premissas, estimativas e lacunas estão separadas;
- [ ] benefícios, custos, impactos, riscos e manutenção cobrem o ciclo de vida;
- [ ] distribuição de ganhos e perdas está visível;
- [ ] sensibilidade e robustez foram avaliadas proporcionalmente;
- [ ] recomendação apresenta condições e limites;
- [ ] decisão humana, dissenso e riscos residuais estão registrados;
- [ ] configuração selecionada foi reavaliada como conjunto;
- [ ] rastreabilidade alcança componentes, validação e implantação;
- [ ] gatilhos de revisão e aprendizagem estão atribuídos.

### 135.5 Termo de conclusão

> A avaliação `AVA-ARQ-___`, versão **[versão]**, apoiou a decisão **[objeto]** mediante comparação das alternativas **[IDs]** contra requisitos e critérios **[IDs]**, utilizando evidências **[IDs]**, sob as premissas e limitações **[IDs/síntese]**. A recomendação resultante foi classificada como **[robusta, condicional, sensível ou inconclusiva]**. A autoridade **[nome/papel]** decidiu **[resultado]**, aceitando **[compensações e riscos]**, impondo **[condições]** e definindo **[gatilhos]**. A configuração aprovada foi transferida à Arquitetura Integrada e sua realização dependerá das validações e condições registradas.

### 135.6 Princípio de encerramento

Avaliar alternativas é preservar a liberdade de escolher com responsabilidade antes que o investimento, o hábito ou a ferramenta transformem uma hipótese em destino.

O Estúdio LICHTARA não busca a alternativa que pareça vencer uma tabela. Busca compreender qual configuração consegue produzir valor legítimo, sob limites reais, com capacidade de sustentação e possibilidade de revisão. A melhor decisão não é a que elimina toda incerteza; é a que torna visíveis as condições sob as quais vale a pena avançar, os riscos que permanecem, as pessoas que serão afetadas e o caminho disponível caso a realidade contradiga a previsão.

Com esta ficha, o diretório central de ferramentas do Módulo 3 completa sua arquitetura: compreender a mudança, desenhar suas dimensões, integrar o sistema e decidir entre configurações com evidências.

---

## Registro final

**Diretório:** `modulos/modulo-03-arquitetura-organizacional/ferramentas/`  
**Documento:** `10-avaliacao-de-alternativas.md`  
**Versão:** 0.1  
**Status:** Em desenvolvimento e validação pela prática  
**Data:** 02/08/2026  
**Ferramenta anterior:** `09-arquitetura-de-inteligencia-artificial.md`  
**Posição no catálogo:** décima e última ficha central prevista  
**Próximo movimento metodológico:** revisão integrada do Módulo 3 e consolidação das passagens para implantação  
**Observações:** [Preencher]
