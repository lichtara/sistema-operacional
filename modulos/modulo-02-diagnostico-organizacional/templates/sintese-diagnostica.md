# Síntese Diagnóstica

```yaml id="m7w2kc"
id_diagnostico: DIA-AAAA-NNN
titulo: "[Nome do diagnóstico]"
organizacao:
area_ou_processo:
tipo_diagnostico: focal | funcional | sistemico
responsavel_pelo_diagnostico:
responsavel_cliente:
data_de_criacao: AAAA-MM-DD
data_da_ultima_revisao:
estado: em_elaboracao
nivel_sensibilidade: publica | interna | confidencial | sensivel
matriz_de_evidencias: matriz-de-evidencias.md
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional de síntese
**Função:** Integração e comunicação dos achados diagnósticos
**Documentos de entrada:**

* `briefing.md`
* `plano-de-investigacao.md`
* `matriz-de-evidencias.md`
* registros de entrevistas;
* registros de observação;
* inventário documental;
* mapas e análises produzidos.

---

# 1. Finalidade

A Síntese Diagnóstica organiza os principais resultados da investigação em uma leitura integrada, clara e utilizável.

Ela deve permitir que o cliente compreenda:

* por que o diagnóstico foi realizado;
* qual questão orientou a investigação;
* qual parte da organização foi observada;
* como as evidências foram produzidas;
* o que já funciona;
* quais problemas, riscos e restrições foram identificados;
* como os achados se relacionam;
* quais hipóteses foram sustentadas ou rejeitadas;
* quais lacunas permanecem;
* quais questões merecem prioridade;
* que requisitos devem orientar a etapa de arquitetura.

A síntese não deve reproduzir integralmente todas as fontes e análises realizadas.

Sua função é transformar uma base extensa de evidências em uma compreensão estruturada, preservando:

* rastreabilidade;
* contexto;
* grau de confiança;
* divergências;
* limites;
* responsabilidade interpretativa.

---

# 2. Relação com os demais documentos

## Briefing

Define:

* demanda;
* questão inicial;
* decisão apoiada;
* escopo;
* condições do diagnóstico.

## Plano de investigação

Define:

* perguntas;
* hipóteses;
* fontes;
* métodos;
* responsabilidades;
* cronograma.

## Matriz de evidências

Preserva:

* evidências;
* fontes;
* interpretações;
* divergências;
* lacunas;
* graus de confiança;
* relação com os achados.

## Síntese diagnóstica

Integra os elementos principais em uma narrativa compreensível.

## Relatório de diagnóstico

Quando necessário, apresenta maior detalhamento sobre:

* metodologia;
* análises;
* mapas;
* evidências;
* implicações;
* anexos.

## Transição para arquitetura

Transforma os achados validados em:

* requisitos;
* critérios;
* prioridades;
* restrições;
* perguntas para o Módulo 3.

---

# 3. Instruções de uso

Este template deve ser duplicado dentro da pasta de cada diagnóstico.

O arquivo-mestre não deve ser preenchido diretamente.

A síntese deve ser produzida após:

* consolidação suficiente da Matriz de Evidências;
* formulação dos achados;
* avaliação dos graus de confiança;
* registro das principais lacunas;
* revisão interna preliminar.

A síntese pode ser utilizada para:

* validação com o cliente;
* reunião de devolutiva;
* alinhamento interno;
* decisão sobre continuidade;
* preparação do relatório final;
* passagem para o Módulo 3.

---

# 4. Princípios da síntese

## 4.1 A síntese não deve ocultar complexidade relevante

Simplificar a comunicação não significa apagar:

* divergências;
* incertezas;
* riscos;
* limitações;
* relações sistêmicas.

---

## 4.2 A síntese não deve reproduzir toda a investigação

Devem permanecer apenas os elementos necessários para:

* compreensão;
* decisão;
* priorização;
* continuidade.

---

## 4.3 Capacidades devem aparecer antes ou junto aos problemas

O diagnóstico não deve apresentar a organização apenas por suas falhas.

A síntese deve reconhecer:

* conhecimentos;
* práticas eficazes;
* recursos;
* relações;
* diferenciais;
* capacidades de aprendizagem;
* elementos identitários a preservar.

---

## 4.4 Achados e recomendações devem permanecer distintos

### Achado

> O acompanhamento comercial depende de informações distribuídas entre múltiplos canais.

### Requisito ou encaminhamento

> A arquitetura futura deverá criar uma referência central de acompanhamento.

A síntese diagnóstica pode indicar requisitos e próximos movimentos, mas não deve apresentar uma solução específica como inevitável.

---

## 4.5 O grau de certeza deve permanecer visível

Afirmações devem indicar quando a confiança é:

* alta;
* moderada;
* baixa;
* inconclusiva.

---

## 4.6 A linguagem deve ser compreensível

Termos técnicos devem ser:

* necessários;
* definidos;
* relacionados ao contexto.

A síntese deve poder ser compreendida pelas pessoas responsáveis pela decisão.

---

# 5. Identificação

| Campo                            | Registro                                       |
| -------------------------------- | ---------------------------------------------- |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                 |
| **Título**                       | `[Nome do diagnóstico]`                        |
| **Organização**                  | `[Nome]`                                       |
| **Área ou processo**             | `[Quando aplicável]`                           |
| **Tipo**                         | `[Focal, funcional ou sistêmico]`              |
| **Responsável pelo diagnóstico** | `[Nome]`                                       |
| **Responsável do cliente**       | `[Nome e função]`                              |
| **Data de início**               | `[DD/MM/AAAA]`                                 |
| **Data da síntese**              | `[DD/MM/AAAA]`                                 |
| **Versão**                       | `[0.1]`                                        |
| **Sensibilidade**                | `[Pública, interna, confidencial ou sensível]` |

## Estado

* [ ] Em elaboração
* [ ] Em revisão interna
* [ ] Aguardando validação
* [ ] Em validação
* [ ] Revisada
* [ ] Validada
* [ ] Validada com divergências
* [ ] Substituída
* [ ] Encerrada

---

# 6. Leitura executiva

Esta seção deve permitir uma compreensão inicial do diagnóstico sem substituir a leitura completa.

## Situação

`[Descreva em um parágrafo a situação que originou o diagnóstico.]`

## Questão central

> `[Reproduzir a questão diagnóstica.]`

## Conclusão geral

`[Apresente, em um ou dois parágrafos, a compreensão central produzida pelo diagnóstico.]`

## Capacidades principais

* `[Capacidade 1]`
* `[Capacidade 2]`
* `[Capacidade 3]`

## Questões prioritárias

1. `[Prioridade 1]`
2. `[Prioridade 2]`
3. `[Prioridade 3]`

## Risco principal

`[Preencher]`

## Restrição principal

`[Preencher]`

## Requisito central para a etapa seguinte

`[Preencher]`

## Limite principal do diagnóstico

`[Preencher]`

---

# 7. Contexto

## Organização ou unidade analisada

`[Descrever brevemente a organização, área, processo ou projeto.]`

## Momento organizacional

* [ ] Ideação
* [ ] Implantação
* [ ] Operação inicial
* [ ] Crescimento
* [ ] Estruturação
* [ ] Transição
* [ ] Reorganização
* [ ] Crise
* [ ] Encerramento ou sucessão
* [ ] Outro: `[Preencher]`

## Situação que originou a investigação

`[Preencher]`

## Mudanças recentes relevantes

* `[Mudança 1]`
* `[Mudança 2]`

## Restrições contextuais

* `[Restrição 1]`
* `[Restrição 2]`

## Elementos identitários relevantes

* `[Elemento 1]`
* `[Elemento 2]`

---

# 8. Finalidade e decisão apoiada

## Por que o diagnóstico foi realizado?

`[Preencher]`

## Que decisão deverá ser apoiada?

`[Preencher]`

## Quem possui autoridade para decidir?

`[Nome e função]`

## Qual é o prazo ou condição da decisão?

`[Preencher]`

## O que poderia acontecer sem esta compreensão?

`[Preencher]`

---

# 9. Questão diagnóstica

## Questão central

> `[Preencher]`

## Questões secundárias

1. `[Questão 1]`
2. `[Questão 2]`
3. `[Questão 3]`
4. `[Questão adicional, quando necessária]`

## Estado das questões

| ID      | Questão | Estado                              | Síntese da resposta | Confiança |
| ------- | ------- | ----------------------------------- | ------------------- | --------- |
| QST-001 |         | Respondida / Parcial / Inconclusiva |                     |           |
| QST-002 |         |                                     |                     |           |
| QST-003 |         |                                     |                     |           |

---

# 10. Escopo

## Incluído

* `[Área, processo, período, público ou sistema 1]`
* `[Elemento 2]`
* `[Elemento 3]`

## Excluído

* `[Elemento 1]`
* `[Elemento 2]`

## Período analisado

`[Preencher]`

## Pessoas, áreas ou fontes consideradas

`[Síntese.]`

## Alterações de escopo

* [ ] Não houve
* [ ] Houve

### Alterações

`[Descrever motivo, impacto e aprovação.]`

---

# 11. Método

## Fontes utilizadas

| Tipo                | Quantidade ou cobertura | Exemplos |
| ------------------- | ----------------------- | -------- |
| Entrevistas         |                         |          |
| Observações         |                         |          |
| Documentos          |                         |          |
| Sistemas            |                         |          |
| Dados quantitativos |                         |          |
| Fontes externas     |                         |          |

## Ferramentas utilizadas

* [ ] Entrevista
* [ ] Observação
* [ ] Análise documental
* [ ] SWOT
* [ ] Canvas
* [ ] Jornada do Cliente
* [ ] Mapa de Processos
* [ ] Maturidade Digital
* [ ] Maturidade Organizacional
* [ ] Outra: `[Preencher]`

## Estratégia de triangulação

`[Como diferentes fontes foram comparadas?]`

## Matriz de evidências

**Arquivo:** `[Inserir caminho.]`

## Participação da inteligência artificial

`[Descrever brevemente as funções realizadas e a revisão humana.]`

---

# 12. Limitações metodológicas

## Limitações de acesso

* `[Limitação 1]`
* `[Limitação 2]`

## Limitações de tempo

`[Preencher]`

## Limitações das fontes

`[Preencher]`

## Limitações de representatividade

`[Preencher]`

## Lacunas aceitas

* `[Lacuna 1 e motivo]`
* `[Lacuna 2 e motivo]`

## Efeito das limitações

`[Como essas condições afetam a confiança ou o alcance das conclusões?]`

---

# 13. Situação atual

Esta seção deve descrever como a organização, área ou processo funciona atualmente.

## Estrutura geral

`[Descrição integrada do funcionamento atual.]`

## Fluxo principal

1. `[Etapa 1]`
2. `[Etapa 2]`
3. `[Etapa 3]`
4. `[Etapa 4]`

## Pessoas e responsabilidades

`[Como as responsabilidades estão distribuídas?]`

## Informação e conhecimento

`[Onde estão as informações, como circulam e onde existem dependências?]`

## Ferramentas e tecnologia

`[Que ferramentas são utilizadas e qual função real desempenham?]`

## Decisões

`[Como as decisões são tomadas, comunicadas e registradas?]`

## Resultados observados

`[Que resultados o sistema atual produz?]`

## Diferenças entre o declarado e o praticado

`[Preencher]`

---

# 14. Capacidades existentes

As capacidades devem ser descritas de maneira concreta.

## `ACH-NNN — [Título da capacidade]`

### Capacidade

`[O que a organização consegue realizar?]`

### Evidências relacionadas

* `EVD-___`
* `EVD-___`

### Condições que a sustentam

* `[Condição 1]`
* `[Condição 2]`

### Por que deve ser preservada?

`[Preencher]`

### Risco de perda durante mudanças

`[Preencher]`

### Confiança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa

---

## Síntese das capacidades

| ID      | Capacidade | Evidências | Importância | Encaminhamento |
| ------- | ---------- | ---------- | ----------- | -------------- |
| ACH-___ |            |            |             | Preservar      |
| ACH-___ |            |            |             | Desenvolver    |
| ACH-___ |            |            |             |                |

---

# 15. Achados diagnósticos

Esta seção deve ser duplicada para cada achado relevante.

---

## `ACH-NNN — [Título do achado]`

### Tipo

* [ ] Capacidade
* [ ] Problema
* [ ] Risco
* [ ] Restrição
* [ ] Oportunidade
* [ ] Contradição
* [ ] Lacuna
* [ ] Requisito
* [ ] Questão aberta

### Afirmação

`[O que o diagnóstico sustenta?]`

### Evidências relacionadas

* `EVD-___`
* `EVD-___`
* `EVD-___`

### Interpretação

`[Como o conjunto das evidências foi compreendido?]`

### Confiança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Inconclusiva

### Evidências divergentes

* `EVD-___`
* `[Nenhuma identificada ou preencher.]`

### Limites

`[O que este achado não permite afirmar?]`

### Implicação

`[Por que importa?]`

### Relação com outros achados

* `ACH-___`
* `ACH-___`

### Encaminhamento preliminar

* [ ] Preservar
* [ ] Corrigir
* [ ] Desenvolver
* [ ] Investigar
* [ ] Monitorar
* [ ] Interromper
* [ ] Encaminhar para especialista
* [ ] Não intervir neste momento

---

# 16. Quadro geral dos achados

| ID      | Achado | Tipo | Confiança | Impacto | Prioridade | Encaminhamento |
| ------- | ------ | ---- | --------- | ------- | ---------- | -------------- |
| ACH-001 |        |      |           |         |            |                |
| ACH-002 |        |      |           |         |            |                |
| ACH-003 |        |      |           |         |            |                |

## Escala de impacto

* Baixo
* Moderado
* Alto
* Crítico

## Escala de prioridade

* Baixa
* Média
* Alta
* Imediata

---

# 17. Relações entre os achados

O diagnóstico deve explicar como os achados se conectam.

## Relação principal

`[Descrever a cadeia ou sistema observado.]`

### Exemplo de estrutura

```text id="k3vp6z"
Responsabilidades pouco definidas
        ↓
Decisões dependentes da fundadora
        ↓
Atraso na aprovação
        ↓
Acúmulo de tarefas
        ↓
Irregularidade na entrega
```

## Achados estruturais

São condições que influenciam múltiplos problemas.

* `ACH-___ — [Título]`
* `ACH-___ — [Título]`

## Achados derivados

São manifestações ou consequências.

* `ACH-___ — [Título]`
* `ACH-___ — [Título]`

## Ciclos de reforço

`[Descrever padrões que se alimentam mutuamente.]`

## Dependências

`[Que problema ou capacidade precisa ser tratado antes de outro?]`

---

# 18. Sintomas, problemas e causas prováveis

| Sintoma observado | Problema formulado | Causas ou fatores prováveis | Confiança |
| ----------------- | ------------------ | --------------------------- | --------- |
|                   |                    |                             |           |
|                   |                    |                             |           |

## Observação

Causas devem ser apresentadas como:

* prováveis;
* contribuintes;
* estruturais;
* contextuais;

quando não houver base para causalidade definitiva.

## Explicações alternativas

* `[Alternativa 1]`
* `[Alternativa 2]`

## Evidências ainda necessárias

* `[Evidência 1]`
* `[Evidência 2]`

---

# 19. Contradições relevantes

| ID      | Contradição | Evidências | Interpretação | Impacto |
| ------- | ----------- | ---------- | ------------- | ------- |
| CTR-001 |             |            |               |         |
| CTR-002 |             |            |               |         |

## Exemplos possíveis

* intenção de crescimento e capacidade operacional limitada;
* discurso de autonomia e decisões concentradas;
* promessa de simplicidade e jornada complexa;
* procedimentos formais e práticas informais incompatíveis;
* uso de IA para velocidade e aumento de retrabalho.

## Tratamento

`[A contradição precisa ser investigada, preservada, resolvida ou transformada em requisito?]`

---

# 20. Riscos

| ID      | Risco | Fonte | Probabilidade | Impacto | Exposição atual | Encaminhamento |
| ------- | ----- | ----- | ------------- | ------- | --------------- | -------------- |
| RSC-001 |       |       |               |         |                 |                |
| RSC-002 |       |       |               |         |                 |                |

## Categorias

* operacional;
* estratégico;
* financeiro;
* reputacional;
* jurídico;
* privacidade;
* segurança;
* conhecimento;
* dependência;
* tecnologia;
* IA;
* continuidade;
* relacionamento com cliente.

## Riscos que exigem ação imediata

* `[Risco 1]`
* `[Risco 2]`

## Riscos que podem ser monitorados

* `[Risco 1]`
* `[Risco 2]`

## Riscos aceitos

`[Preencher, com responsável e justificativa.]`

---

# 21. Restrições

| Restrição | Tipo                                                           | Efeito sobre a organização | Efeito sobre a arquitetura futura |
| --------- | -------------------------------------------------------------- | -------------------------- | --------------------------------- |
|           | Financeira / temporal / humana / técnica / jurídica / cultural |                            |                                   |
|           |                                                                |                            |                                   |

## Restrições temporárias

* `[Restrição]`

## Restrições estruturais

* `[Restrição]`

## Restrições que não devem ser tratadas como falhas

* `[Restrição]`

---

# 22. Oportunidades

| ID      | Oportunidade | Evidência | Capacidade relacionada | Condição necessária | Prioridade |
| ------- | ------------ | --------- | ---------------------- | ------------------- | ---------- |
| OPR-001 |              |           |                        |                     |            |
| OPR-002 |              |           |                        |                     |            |

## Regra

Uma oportunidade deve possuir relação com:

* necessidade;
* contexto;
* capacidade;
* recurso;
* resultado relevante.

Ideias atraentes sem base suficiente devem permanecer como hipóteses ou possibilidades futuras.

---

# 23. Maturidade

Esta seção deve ser utilizada apenas quando houver critérios e evidências adequados.

## Dimensão avaliada

* [ ] Organizacional
* [ ] Digital
* [ ] Conhecimento
* [ ] Processos
* [ ] Governança
* [ ] Inteligência artificial
* [ ] Outra: `[Preencher]`

## Escala utilizada

`[Descrever níveis e critérios.]`

## Avaliação

| Dimensão | Nível atual | Evidências | Confiança | Condição para o próximo nível |
| -------- | ----------- | ---------- | --------- | ----------------------------- |
|          |             |            |           |                               |
|          |             |            |           |                               |

## Síntese de maturidade

`[Que nível de complexidade a organização consegue sustentar atualmente?]`

## Limite

A maturidade não deve ser apresentada como julgamento de valor.

Ela descreve a capacidade atual para sustentar determinadas práticas ou estruturas.

---

# 24. Hipóteses

## Hipóteses sustentadas

| ID      | Hipótese | Evidências | Confiança |
| ------- | -------- | ---------- | --------- |
| HIP-001 |          |            |           |

## Hipóteses parcialmente sustentadas

| ID      | Hipótese | O que foi sustentado | O que permanece aberto |
| ------- | -------- | -------------------- | ---------------------- |
| HIP-002 |          |                      |                        |

## Hipóteses rejeitadas

| ID      | Hipótese | Evidências contrárias | Aprendizado |
| ------- | -------- | --------------------- | ----------- |
| HIP-003 |          |                       |             |

## Hipóteses inconclusivas

| ID      | Hipótese | Lacuna principal | Encaminhamento |
| ------- | -------- | ---------------- | -------------- |
| HIP-004 |          |                  |                |

---

# 25. Lacunas e questões abertas

## Lacunas críticas

* `LAC-___ — [Descrição]`

## Lacunas relevantes

* `LAC-___ — [Descrição]`

## Lacunas aceitas

* `LAC-___ — [Descrição e justificativa]`

## Questões abertas

1. `[Questão 1]`
2. `[Questão 2]`
3. `[Questão 3]`

## Encaminhamento

| Questão ou lacuna | Investigar agora | Investigar depois | Aceitar | Responsável |
| ----------------- | ---------------- | ----------------- | ------- | ----------- |
|                   |                  |                   |         |             |

---

# 26. Priorização

A priorização deve considerar:

* impacto;
* risco;
* urgência;
* dependências;
* esforço;
* capacidade;
* reversibilidade;
* valor estratégico;
* efeito sobre autonomia;
* prontidão.

## Quadro de prioridades

| Prioridade | Achado  | Motivo | Dependência | Encaminhamento |
| ---------- | ------- | ------ | ----------- | -------------- |
| 1          | ACH-___ |        |             |                |
| 2          | ACH-___ |        |             |                |
| 3          | ACH-___ |        |             |                |

## Categorias

### Preservar

* `[Capacidade ou elemento]`

### Corrigir

* `[Problema]`

### Desenvolver

* `[Capacidade]`

### Investigar

* `[Questão]`

### Monitorar

* `[Risco ou sinal]`

### Interromper

* `[Prática incompatível]`

---

# 27. Critérios de priorização

| Achado  | Impacto | Urgência | Dependência | Esforço | Prontidão | Prioridade final |
| ------- | ------- | -------- | ----------- | ------- | --------- | ---------------- |
| ACH-___ |         |          |             |         |           |                  |
| ACH-___ |         |          |             |         |           |                  |

A tabela não precisa produzir pontuação automática.

O julgamento deve permanecer explícito e contextual.

---

# 28. Requisitos para a arquitetura

Os requisitos traduzem achados em condições que o desenho futuro deverá atender.

| ID      | Requisito | Achado de origem | Motivo | Critério de atendimento |
| ------- | --------- | ---------------- | ------ | ----------------------- |
| REQ-001 |           | ACH-___          |        |                         |
| REQ-002 |           | ACH-___          |        |                         |
| REQ-003 |           | ACH-___          |        |                         |

## Tipos de requisito

* funcional;
* operacional;
* informacional;
* humano;
* tecnológico;
* ético;
* jurídico;
* financeiro;
* identitário;
* governança;
* segurança;
* aprendizagem.

## Exemplo

**Achado:**
O acompanhamento comercial depende da memória da fundadora.

**Requisito:**
A arquitetura futura deverá permitir registrar responsável, estado e próxima ação de cada oportunidade em uma referência acessível.

---

# 29. Critérios que a solução futura deverá respeitar

* `[Critério 1]`
* `[Critério 2]`
* `[Critério 3]`
* `[Critério 4]`

## Exemplos

* funcionar com a disponibilidade real da organização;
* preservar a voz e a identidade;
* reduzir dependência da memória;
* permitir implantação gradual;
* não exigir manutenção superior à capacidade disponível;
* manter responsabilidade humana;
* proteger dados;
* permitir reversão;
* gerar evidências de resultado.

---

# 30. Elementos que não devem ser definidos nesta etapa

O diagnóstico não deve decidir prematuramente:

* ferramenta específica;
* arquitetura completa;
* fornecedor;
* automação definitiva;
* desenho detalhado do processo futuro;
* investimento final;
* distribuição completa de responsabilidades futuras.

## Elementos que permanecem abertos

* `[Elemento 1]`
* `[Elemento 2]`

## Motivo

`[Por que devem ser tratados no Módulo 3?]`

---

# 31. Encaminhamento recomendado

## Resultado do diagnóstico

* [ ] Prosseguir para arquitetura organizacional
* [ ] Realizar investigação complementar
* [ ] Realizar experimentação controlada
* [ ] Tomar decisão específica
* [ ] Encaminhar para especialista
* [ ] Monitorar antes de intervir
* [ ] Adiar
* [ ] Não intervir
* [ ] Suspender
* [ ] Encerrar sem continuidade

## Fundamentação

`[Preencher]`

## Condições para continuidade

* `[Condição 1]`
* `[Condição 2]`

## Próximo documento

* [ ] `transicao-para-arquitetura.md`
* [ ] `relatorio-de-diagnostico.md`
* [ ] Registro de decisão
* [ ] Plano de experimentação
* [ ] Outro: `[Preencher]`

---

# 32. Plano de validação

## Aspectos factuais a validar

* nomes;
* datas;
* processos;
* responsabilidades;
* documentos;
* eventos;
* dados;
* ferramentas.

## Aspectos interpretativos a discutir

* relações;
* causas prováveis;
* prioridades;
* riscos;
* restrições;
* requisitos.

## Participantes

| Pessoa | Papel | Elementos a validar | Data |
| ------ | ----- | ------------------- | ---- |
|        |       |                     |      |

## Formato

* [ ] Reunião
* [ ] Documento comentado
* [ ] Oficina
* [ ] Validação individual
* [ ] Outro: `[Preencher]`

---

# 33. Registro da validação

## Data

`[DD/MM/AAAA]`

## Participantes

* `[Nome ou função]`

## Correções factuais

`[Preencher]`

## Novas evidências apresentadas

* `EVD-___`
* `[Nenhuma ou preencher.]`

## Achados reformulados

* `ACH-___ — [Alteração]`

## Divergências mantidas

`[Preencher]`

## Questões reabertas

`[Preencher]`

## Resultado

* [ ] Validada
* [ ] Validada com ajustes
* [ ] Validada com divergências
* [ ] Parcialmente validada
* [ ] Devolvida para investigação
* [ ] Não validada

---

# 34. Divergências de validação

| Tema | Interpretação do diagnóstico | Perspectiva divergente | Evidências | Efeito sobre a conclusão |
| ---- | ---------------------------- | ---------------------- | ---------- | ------------------------ |
|      |                              |                        |            |                          |
|      |                              |                        |            |                          |

A discordância não deve ser apagada apenas para produzir consenso.

Ela deve ser:

* compreendida;
* registrada;
* relacionada às fontes;
* incorporada ao grau de confiança.

---

# 35. Participação da inteligência artificial

## Sistemas ou agentes utilizados

| Sistema | Função | Etapa | Saída utilizada | Responsável pela revisão |
| ------- | ------ | ----- | --------------- | ------------------------ |
|         |        |       |                 |                          |

## Funções desempenhadas

* [ ] Organização de evidências
* [ ] Comparação de fontes
* [ ] Identificação de padrões
* [ ] Formulação de hipóteses alternativas
* [ ] Revisão de completude
* [ ] Apoio à estruturação
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## Dados fornecidos

`[Descrever categorias.]`

## Medidas de proteção

* [ ] Minimização
* [ ] Anonimização
* [ ] Pseudonimização
* [ ] Redução de contexto
* [ ] Ambiente autorizado
* [ ] Revisão antes do envio
* [ ] Não utilização de dados sensíveis
* [ ] Outra: `[Preencher]`

## Verificação humana

* [ ] As saídas foram comparadas com as fontes.
* [ ] Nenhum achado foi criado sem evidência.
* [ ] As interpretações foram revisadas.
* [ ] A linguagem foi ajustada ao grau de confiança.
* [ ] Os erros ou limites foram registrados.

## Limitações identificadas

`[Preencher ou registrar “nenhuma identificada”.]`

## Responsável final

`[Nome]`

A responsabilidade pela síntese e pelas conclusões permanece humana.

---

# 36. Confidencialidade e compartilhamento

## Classificação

* [ ] Pública
* [ ] Interna
* [ ] Confidencial
* [ ] Sensível

## Destinatários autorizados

* `[Nome ou função]`

## Informações removidas ou anonimizadas

* `[Informação 1]`
* `[Informação 2]`

## Versões produzidas

* [ ] Versão completa interna
* [ ] Versão executiva
* [ ] Versão anonimizada
* [ ] Versão para cliente
* [ ] Versão para especialista
* [ ] Outra: `[Preencher]`

## Restrições de compartilhamento

`[Preencher]`

## Local de armazenamento

`[Preencher]`

---

# 37. Teste de coerência da síntese

Antes da validação, verificar:

1. A síntese responde à questão diagnóstica?
2. Os achados possuem evidências relacionadas?
3. Fatos e interpretações estão separados?
4. O grau de confiança está explícito?
5. Capacidades foram reconhecidas?
6. Contradições relevantes foram preservadas?
7. As limitações estão claras?
8. Recomendações foram separadas dos achados?
9. A linguagem evita julgamento de pessoas?
10. A IA foi tratada como apoio?
11. Os dados sensíveis estão protegidos?
12. Os requisitos derivam dos achados?
13. A síntese pode ser compreendida pelo cliente?
14. A passagem para o Módulo 3 está preparada sem antecipar a solução?

## Resultado

* [ ] Coerente
* [ ] Coerente com ajustes
* [ ] Precisa ser reformulada
* [ ] Não está pronta para validação

## Ajustes necessários

`[Preencher]`

---

# 38. Critérios de conclusão

A síntese pode ser considerada concluída quando:

* [ ] a questão central foi respondida no grau possível;
* [ ] o contexto foi apresentado;
* [ ] o escopo e os limites estão explícitos;
* [ ] o método foi resumido;
* [ ] as capacidades estão registradas;
* [ ] os achados possuem rastreabilidade;
* [ ] os graus de confiança estão definidos;
* [ ] as relações entre achados estão explicadas;
* [ ] os riscos e restrições estão registrados;
* [ ] as lacunas remanescentes estão explícitas;
* [ ] as prioridades estão justificadas;
* [ ] os requisitos para arquitetura derivam dos achados;
* [ ] a participação da IA foi registrada;
* [ ] os dados sensíveis foram protegidos;
* [ ] a validação foi realizada no grau possível;
* [ ] as divergências foram preservadas;
* [ ] o encaminhamento está definido.

---

# 39. Síntese final

## O que está acontecendo?

`[Descrição clara da condição atual.]`

## Por que isso importa?

`[Impacto organizacional.]`

## O que já sustenta a organização?

`[Capacidades e recursos.]`

## O que está limitando seu funcionamento?

`[Problemas, restrições e riscos.]`

## Que relações explicam a situação?

`[Síntese sistêmica.]`

## O que deve ser preservado?

`[Preencher]`

## O que precisa ser tratado primeiro?

`[Preencher]`

## O que ainda precisa ser compreendido?

`[Preencher]`

## Que condições devem orientar a próxima etapa?

`[Preencher]`

---

# 40. Aprovação e validação

## Elaborado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Revisado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Validado com o cliente

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Forma de validação

* [ ] Reunião
* [ ] Documento comentado
* [ ] E-mail
* [ ] Mensagem
* [ ] Assinatura
* [ ] Outra: `[Preencher]`

## Evidência da validação

`[Link, arquivo ou referência.]`

---

# 41. Histórico de versões

| Data | Versão | Alteração          | Motivo | Responsável |
| ---- | ------ | ------------------ | ------ | ----------- |
|      | 0.1    | Criação da síntese |        |             |
|      |        |                    |        |             |

---

# 42. Versão resumida para diagnóstico focal

## Identificação

* **Diagnóstico:** `DIA-AAAA-NNN`
* **Título:** `[Preencher]`
* **Responsável:** `[Nome]`
* **Data:** `[DD/MM/AAAA]`

## Questão central

> `[Preencher]`

## Situação atual

`[Um ou dois parágrafos.]`

## Capacidades

* `[Capacidade 1]`
* `[Capacidade 2]`

## Achados

| ID      | Achado | Evidências | Confiança | Implicação |
| ------- | ------ | ---------- | --------- | ---------- |
| ACH-001 |        |            |           |            |
| ACH-002 |        |            |           |            |

## Relação principal

`[Como os achados se conectam?]`

## Prioridade

`[O que precisa ser tratado primeiro e por quê?]`

## Limitações

`[Preencher]`

## Requisitos para a próxima etapa

* `[Requisito 1]`
* `[Requisito 2]`

## Encaminhamento

* [ ] Arquitetura
* [ ] Investigação adicional
* [ ] Experimentação
* [ ] Decisão
* [ ] Monitoramento
* [ ] Não intervenção

## Próxima ação

`[Ação, responsável e prazo.]`

A síntese ocupa uma posição muito precisa no sistema:

> **A matriz preserva a arquitetura completa das evidências.
> A síntese revela a arquitetura essencial da compreensão.**

O próximo template coerente é o `relatorio-de-diagnostico.md`, destinado aos casos em que a síntese precisa ser expandida com metodologia, análises, mapas, evidências, validações e anexos.
