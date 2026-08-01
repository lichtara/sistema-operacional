# Matriz de Evidências

```yaml
id_diagnostico: DIA-AAAA-NNN
titulo: "[Nome do diagnóstico]"
organizacao:
area_ou_processo:
tipo_diagnostico: focal | funcional | sistemico
responsavel_pelo_diagnostico:
responsavel_pela_matriz:
data_de_abertura: AAAA-MM-DD
data_da_ultima_atualizacao:
estado: em_preparacao
nivel_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional de análise
**Função:** Organização, avaliação e rastreabilidade das evidências
**Documento metodológico:** `../matriz-de-evidencias.md`
**Plano relacionado:** `plano-de-investigacao.md`

---

# 1. Finalidade

Esta matriz organiza as evidências produzidas durante um diagnóstico organizacional.

Ela permite relacionar:

* questões de investigação;
* hipóteses;
* fontes;
* informações observadas ou relatadas;
* interpretações provisórias;
* convergências;
* divergências;
* lacunas;
* qualidade da evidência;
* grau de confiança;
* achados diagnósticos;
* ações de verificação.

Sua função é preservar a cadeia:

```text
Questão
   ↓
Hipótese
   ↓
Fonte
   ↓
Evidência
   ↓
Interpretação
   ↓
Achado
   ↓
Implicação
```

A matriz não substitui as fontes originais.

Ela conecta os registros de entrevistas, observações, documentos, sistemas e dados ao raciocínio diagnóstico.

---

# 2. Instruções de uso

Este template deve ser duplicado dentro da pasta de cada diagnóstico real.

O arquivo-mestre não deve ser preenchido diretamente.

## Durante a investigação

A matriz deve ser atualizada:

* após entrevistas;
* após observações;
* após análise documental;
* após recebimento de dados;
* quando uma evidência for corrigida;
* quando surgir divergência;
* quando uma hipótese for reformulada;
* antes da formulação dos achados.

## Regra central

O campo **Evidência** deve registrar o que foi:

* observado;
* declarado;
* documentado;
* medido;
* localizado em sistema.

O campo **Interpretação** deve registrar o significado possível atribuído à evidência.

Esses campos não devem ser misturados.

---

# 3. Identificação

| Campo                            | Registro                                       |
| -------------------------------- | ---------------------------------------------- |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                 |
| **Título**                       | `[Nome do diagnóstico]`                        |
| **Organização**                  | `[Nome]`                                       |
| **Área ou processo**             | `[Preencher]`                                  |
| **Tipo**                         | `[Focal, funcional ou sistêmico]`              |
| **Responsável pelo diagnóstico** | `[Nome]`                                       |
| **Responsável pela matriz**      | `[Nome]`                                       |
| **Data de abertura**             | `[DD/MM/AAAA]`                                 |
| **Última atualização**           | `[DD/MM/AAAA]`                                 |
| **Versão**                       | `[0.1]`                                        |
| **Sensibilidade**                | `[Pública, interna, confidencial ou sensível]` |

## Estado

* [ ] Em preparação
* [ ] Em preenchimento
* [ ] Em revisão
* [ ] Aguardando evidência
* [ ] Aguardando validação
* [ ] Consolidada
* [ ] Encerrada
* [ ] Reaberta

---

# 4. Referências do diagnóstico

## Briefing

`[Link ou caminho para briefing.md]`

## Plano de investigação

`[Link ou caminho para plano-de-investigacao.md]`

## Questão diagnóstica central

`[Reproduzir a pergunta principal.]`

## Decisão apoiada

`[Que decisão o diagnóstico deverá apoiar?]`

## Resultado esperado

`[O que deverá estar suficientemente compreendido ao final?]`

## Escopo

`[Síntese do que está incluído.]`

## Limites

`[Síntese do que está excluído ou não poderá ser afirmado.]`

---

# 5. Identificadores utilizados

## Questões

```text
QST-NNN
```

## Hipóteses

```text
HIP-NNN
```

## Evidências

```text
EVD-NNN
```

## Achados

```text
ACH-NNN
```

## Fontes

```text
ENT-NNN — Entrevista
OBS-NNN — Observação
DOC-NNN — Documento
DAD-NNN — Conjunto de dados
SIS-NNN — Sistema
EXT-NNN — Fonte externa
```

Os identificadores não devem ser reutilizados dentro do mesmo diagnóstico.

---

# 6. Questões de investigação

| ID      | Questão | Prioridade   | Finalidade | Estado          |
| ------- | ------- | ------------ | ---------- | --------------- |
| QST-001 |         | Essencial    |            | Em investigação |
| QST-002 |         | Relevante    |            | Em investigação |
| QST-003 |         | Complementar |            | Em investigação |

## Prioridades

* **Essencial:** precisa ser respondida para que o diagnóstico cumpra sua finalidade.
* **Relevante:** amplia significativamente a compreensão.
* **Complementar:** oferece contexto, mas não impede a conclusão.

## Estados

* Não iniciada
* Em investigação
* Parcialmente respondida
* Respondida
* Inconclusiva
* Fora do escopo
* Suspensa

---

# 7. Registro de hipóteses

| ID      | Hipótese | Questões relacionadas | Evidências favoráveis | Evidências contrárias | Estado   | Confiança |
| ------- | -------- | --------------------- | --------------------- | --------------------- | -------- | --------- |
| HIP-001 |          | QST-___               |                       |                       | Proposta | Baixa     |
| HIP-002 |          | QST-___               |                       |                       | Proposta | Baixa     |
| HIP-003 |          | QST-___               |                       |                       | Proposta | Baixa     |

## Estados das hipóteses

* Proposta
* Em investigação
* Parcialmente sustentada
* Sustentada
* Enfraquecida
* Rejeitada
* Inconclusiva
* Reformulada
* Substituída

## Hipóteses concorrentes

* `[Explicação alternativa 1]`
* `[Explicação alternativa 2]`
* `[Explicação alternativa 3]`

## O que poderia contradizer as hipóteses principais?

`[Preencher]`

---

# 8. Registro de fontes

| ID      | Fonte | Tipo       | Relação com o fenômeno | Data ou período | Sensibilidade | Estado     |
| ------- | ----- | ---------- | ---------------------- | --------------- | ------------- | ---------- |
| ENT-001 |       | Entrevista |                        |                 |               | Disponível |
| OBS-001 |       | Observação |                        |                 |               | Disponível |
| DOC-001 |       | Documento  |                        |                 |               | Disponível |
| DAD-001 |       | Dados      |                        |                 |               | Pendente   |

## Estados das fontes

* Planejada
* Solicitada
* Disponível
* Parcial
* Não localizada
* Acesso negado
* Inválida
* Descartada
* Não aplicável

## Fontes essenciais indisponíveis

| Fonte | Motivo | Impacto | Encaminhamento |
| ----- | ------ | ------- | -------------- |
|       |        |         |                |

---

# 9. Matriz principal de evidências

| ID      | Questão | Hipótese | Fonte   | Tipo          | Data ou período | Evidência | Interpretação provisória | Qualidade | Confiança | Convergências | Divergências | Lacuna | Ação necessária | Achado |
| ------- | ------- | -------- | ------- | ------------- | --------------- | --------- | ------------------------ | --------- | --------- | ------------- | ------------ | ------ | --------------- | ------ |
| EVD-001 | QST-___ | HIP-___  | ENT-___ | Declarada     |                 |           |                          |           |           |               |              |        |                 |        |
| EVD-002 | QST-___ | HIP-___  | OBS-___ | Observacional |                 |           |                          |           |           |               |              |        |                 |        |
| EVD-003 | QST-___ | HIP-___  | DOC-___ | Documental    |                 |           |                          |           |           |               |              |        |                 |        |
| EVD-004 | QST-___ | HIP-___  | DAD-___ | Quantitativa  |                 |           |                          |           |           |               |              |        |                 |        |

---

# 10. Orientações para preenchimento

## ID

Identificador único da evidência.

## Questão

Pergunta de investigação à qual a evidência está relacionada.

## Hipótese

Hipótese que a evidência pode:

* sustentar;
* enfraquecer;
* reformular;
* rejeitar.

Uma evidência pode não estar vinculada a hipótese inicial.

## Fonte

Origem exata da informação.

## Tipo

* Declarada
* Documental
* Observacional
* Quantitativa
* Sistêmica
* Comparativa
* Inferencial

## Data ou período

Momento a que a evidência corresponde.

## Evidência

Descrição factual, específica e contextualizada.

## Interpretação provisória

Significado possível da evidência.

## Qualidade

* Alta
* Moderada
* Baixa
* Não determinada

## Confiança

* Alta
* Moderada
* Baixa
* Inconclusiva

## Convergências

Outras evidências compatíveis.

Exemplo:

```text
EVD-003, EVD-006 e EVD-011
```

## Divergências

Evidências incompatíveis ou perspectivas distintas.

## Lacuna

Informação ainda ausente.

## Ação necessária

Verificação, aprofundamento, validação ou encerramento.

## Achado

ID do achado ao qual a evidência foi vinculada.

---

# 11. Formulação das evidências

## Evidência declarada

### Adequada

> ENT-001 relata utilizar WhatsApp, Instagram e e-mail para acompanhar contatos comerciais.

### Inadequada

> Os contatos comerciais ficam espalhados.

A segunda formulação transforma relato em conclusão.

---

## Evidência observacional

### Adequada

> Durante OBS-001, a participante consultou três ambientes diferentes antes de localizar o arquivo solicitado.

### Inadequada

> Os arquivos são desorganizados.

---

## Evidência documental

### Adequada

> DOC-003, versão 2.0, atribui a aprovação final das propostas à fundadora.

### Inadequada

> Todas as propostas são aprovadas pela fundadora.

A prática precisa ser verificada.

---

## Evidência quantitativa

### Adequada

> Das 18 propostas analisadas entre maio e julho, 11 não possuíam próxima ação registrada.

### Inadequada

> A maioria das propostas é esquecida.

---

# 12. Avaliação da qualidade

Cada evidência deve ser analisada pelas seguintes dimensões:

| Dimensão            | Pergunta                                               |
| ------------------- | ------------------------------------------------------ |
| **Pertinência**     | A evidência ajuda a responder à questão?               |
| **Proximidade**     | A fonte está próxima do fenômeno?                      |
| **Atualidade**      | Representa o período investigado?                      |
| **Integridade**     | Está suficientemente completa?                         |
| **Rastreabilidade** | A origem pode ser localizada?                          |
| **Convergência**    | Outras fontes independentes sustentam algo semelhante? |

## Registro detalhado opcional

| Evidência | Pertinência | Proximidade | Atualidade | Integridade | Rastreabilidade | Convergência | Qualidade geral |
| --------- | ----------- | ----------- | ---------- | ----------- | --------------- | ------------ | --------------- |
| EVD-001   |             |             |            |             |                 |              |                 |
| EVD-002   |             |             |            |             |                 |              |                 |

## Escala

* Alta
* Moderada
* Baixa
* Não determinada
* Não aplicável

A classificação geral deve ser justificada pelo conjunto dos critérios, sem cálculo automático obrigatório.

---

# 13. Grau de confiança

## Alta

Utilizar quando:

* existem evidências de boa qualidade;
* múltiplas fontes convergem;
* as explicações alternativas foram examinadas;
* não existem lacunas capazes de alterar materialmente a conclusão.

## Moderada

Utilizar quando:

* existem evidências relevantes;
* a interpretação é plausível;
* permanecem lacunas ou explicações concorrentes.

## Baixa

Utilizar quando:

* há fonte isolada;
* a interpretação depende de inferência ampla;
* existem contradições;
* o contexto é insuficiente.

## Inconclusiva

Utilizar quando não existe base suficiente para sustentar a interpretação.

## Justificativas de confiança

| Evidência ou achado | Confiança | Justificativa |
| ------------------- | --------- | ------------- |
| EVD-___             |           |               |
| ACH-___             |           |               |

---

# 14. Convergências

| ID      | Tema ou interpretação | Evidências convergentes | Independência das fontes | Efeito sobre a confiança |
| ------- | --------------------- | ----------------------- | ------------------------ | ------------------------ |
| CNV-001 |                       |                         |                          |                          |
| CNV-002 |                       |                         |                          |                          |

## Perguntas de controle

* As fontes são realmente independentes?
* Uma fonte apenas repete informação originada por outra?
* As evidências correspondem ao mesmo período?
* A convergência se refere ao fato ou apenas à interpretação?

---

# 15. Divergências

| ID      | Questão ou tema | Evidência 1 | Evidência 2 | Natureza da divergência | Ação de verificação | Efeito sobre a confiança |
| ------- | --------------- | ----------- | ----------- | ----------------------- | ------------------- | ------------------------ |
| DIV-001 |                 | EVD-___     | EVD-___     |                         |                     |                          |
| DIV-002 |                 |             |             |                         |                     |                          |

## Naturezas possíveis

* perspectivas diferentes;
* períodos diferentes;
* processo prescrito e praticado;
* exceção;
* informação incompleta;
* mudança recente;
* conflito;
* critérios diferentes;
* fonte possivelmente incorreta.

## Regra

A divergência deve permanecer registrada mesmo quando uma interpretação for considerada mais consistente.

---

# 16. Lacunas

| ID      | Informação ausente | Questão afetada | Classificação | Como obter | Responsável | Prazo | Estado |
| ------- | ------------------ | --------------- | ------------- | ---------- | ----------- | ----- | ------ |
| LAC-001 |                    | QST-___         | Crítica       |            |             |       | Aberta |
| LAC-002 |                    | QST-___         | Relevante     |            |             |       | Aberta |
| LAC-003 |                    | QST-___         | Complementar  |            |             |       | Aberta |

## Classificações

### Crítica

Impede conclusão responsável ou decisão relevante.

### Relevante

Reduz a confiança, mas não impede toda conclusão.

### Complementar

Ampliaria o contexto, mas possui baixo impacto sobre a finalidade.

## Estados

* Aberta
* Em investigação
* Resolvida
* Parcialmente resolvida
* Aceita
* Fora do escopo
* Não obtível

---

# 17. Lacunas aceitas

| Lacuna | Motivo da aceitação | Custo ou restrição | Impacto sobre a conclusão | Responsável pela aceitação |
| ------ | ------------------- | ------------------ | ------------------------- | -------------------------- |
|        |                     |                    |                           |                            |

A aceitação de uma lacuna deve ser explícita quando puder afetar:

* confiança;
* escopo;
* recomendação;
* risco;
* decisão posterior.

---

# 18. Ações de investigação

| ID      | Evidência, hipótese ou lacuna | Ação                       | Responsável | Prazo | Estado   | Resultado |
| ------- | ----------------------------- | -------------------------- | ----------- | ----- | -------- | --------- |
| ACA-001 | EVD-___                       | Validar com outra fonte    |             |       | Pendente |           |
| ACA-002 | HIP-___                       | Buscar evidência contrária |             |       | Pendente |           |
| ACA-003 | LAC-___                       | Solicitar documento        |             |       | Pendente |           |

## Estados

* Pendente
* Em execução
* Aguardando informação
* Concluída
* Cancelada
* Não aplicável

---

# 19. Matriz de achados

| ID      | Título do achado | Tipo       | Evidências relacionadas | Confiança | Implicação | Prioridade | Encaminhamento |
| ------- | ---------------- | ---------- | ----------------------- | --------- | ---------- | ---------- | -------------- |
| ACH-001 |                  | Capacidade |                         |           |            |            | Preservar      |
| ACH-002 |                  | Problema   |                         |           |            |            | Corrigir       |
| ACH-003 |                  | Risco      |                         |           |            |            | Monitorar      |
| ACH-004 |                  | Lacuna     |                         |           |            |            | Investigar     |

## Tipos de achado

* Capacidade
* Problema
* Risco
* Restrição
* Oportunidade
* Contradição
* Lacuna
* Requisito
* Questão aberta

## Encaminhamentos

* Preservar
* Corrigir
* Desenvolver
* Investigar
* Monitorar
* Interromper
* Encaminhar para especialista
* Não intervir neste momento

---

# 20. Registro detalhado do achado

Esta seção deve ser duplicada para cada achado relevante.

---

## `ACH-NNN — [Título do achado]`

### Tipo

`[Capacidade, problema, risco, restrição, oportunidade, contradição, lacuna, requisito ou questão aberta.]`

### Afirmação

`[O que o diagnóstico sustenta?]`

### Questões relacionadas

* `QST-___`
* `QST-___`

### Hipóteses relacionadas

* `HIP-___`
* `HIP-___`

### Evidências

* `EVD-___`
* `EVD-___`
* `EVD-___`

### Evidências contrárias ou divergentes

* `EVD-___`
* `[Nenhuma identificada ou preencher.]`

### Interpretação

`[Como o conjunto das evidências foi compreendido?]`

### Confiança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Inconclusiva

### Justificativa da confiança

`[Preencher]`

### Limites

`[O que não pode ser afirmado?]`

### Implicação

`[Por que o achado importa?]`

### Relação com outros achados

* `ACH-___`
* `ACH-___`

### Prioridade preliminar

* [ ] Alta
* [ ] Média
* [ ] Baixa
* [ ] A definir

### Encaminhamento

* [ ] Preservar
* [ ] Corrigir
* [ ] Desenvolver
* [ ] Investigar
* [ ] Monitorar
* [ ] Interromper
* [ ] Encaminhar
* [ ] Não intervir

### Requisito para a arquitetura

`[Que condição a solução futura deverá atender?]`

### Necessidade de validação

`[Pessoa, documento, sistema ou outra fonte.]`

---

# 21. Rastreabilidade dos achados

Cada achado deve permitir o percurso:

```text
ACH-NNN
   ↓
EVD-NNN
   ↓
ENT / OBS / DOC / DAD / SIS / EXT
   ↓
Fonte original
```

## Verificação

| Achado  | Evidências vinculadas | Fontes localizáveis | Divergências registradas | Limites explícitos |
| ------- | --------------------- | ------------------- | ------------------------ | ------------------ |
| ACH-001 | Sim / Não             | Sim / Não           | Sim / Não                | Sim / Não          |
| ACH-002 |                       |                     |                          |                    |

Um achado não deve ser utilizado no relatório final quando sua base não puder ser reconstruída.

---

# 22. Evidências descartadas

Uma evidência pode ser descartada da análise principal sem ser apagada.

| ID      | Evidência | Motivo do descarte                                                           | Impacto | Responsável |
| ------- | --------- | ---------------------------------------------------------------------------- | ------- | ----------- |
| EVD-___ |           | Irrelevante / duplicada / inválida / fora do período / fonte não verificável |         |             |

## Regra

O descarte deve preservar:

* ID;
* origem;
* motivo;
* data;
* responsável.

---

# 23. Correções e reclassificações

| Data | Evidência ou achado | Registro anterior | Novo registro | Motivo | Responsável |
| ---- | ------------------- | ----------------- | ------------- | ------ | ----------- |
|      |                     |                   |               |        |             |

Devem ser registradas alterações como:

* correção factual;
* mudança de fonte;
* mudança de qualidade;
* alteração de confiança;
* reformulação de interpretação;
* invalidação;
* associação a novo achado.

---

# 24. Participação da inteligência artificial

## A IA foi utilizada?

* [ ] Não
* [ ] Organização de notas
* [ ] Classificação inicial
* [ ] Comparação de fontes
* [ ] Identificação de temas
* [ ] Identificação de divergências
* [ ] Formulação de hipóteses alternativas
* [ ] Revisão de completude
* [ ] Apoio à redação dos achados
* [ ] Outra: `[Preencher]`

## Registro dos sistemas

| Sistema ou agente | Data | Função | Fontes fornecidas | Saída utilizada | Responsável pela revisão |
| ----------------- | ---- | ------ | ----------------- | --------------- | ------------------------ |
|                   |      |        |                   |                 |                          |

## Medidas de proteção

* [ ] Minimização
* [ ] Anonimização
* [ ] Pseudonimização
* [ ] Redução de contexto
* [ ] Ambiente autorizado
* [ ] Revisão antes do envio
* [ ] Não utilização de dados sensíveis
* [ ] Outra: `[Preencher]`

## Verificações

* [ ] A saída foi comparada com as fontes.
* [ ] Nenhuma informação foi incorporada sem origem.
* [ ] As classificações foram revisadas.
* [ ] As interpretações foram avaliadas humanamente.
* [ ] Erros ou limitações foram registrados.

## Limitações ou erros identificados

`[Preencher ou registrar “nenhum identificado”.]`

## Regra

Saídas de IA não devem ser registradas como evidência do funcionamento da organização.

Elas podem apoiar:

* organização;
* análise;
* comparação;
* formulação de perguntas.

A evidência deve permanecer vinculada às fontes organizacionais reais.

---

# 25. Sensibilidade e controle de acesso

## Classificação geral

* [ ] Pública
* [ ] Interna
* [ ] Confidencial
* [ ] Sensível

## Acesso autorizado

| Pessoa ou função | Nível de acesso | Justificativa |
| ---------------- | --------------- | ------------- |
|                  |                 |               |

## Evidências com acesso restrito

| ID      | Classificação | Motivo | Forma de referência na matriz geral |
| ------- | ------------- | ------ | ----------------------------------- |
| EVD-___ | Sensível      |        | Resumo anonimizado                  |
| EVD-___ | Confidencial  |        | Identificador                       |

## Informações que não devem ser reproduzidas

* `[Informação 1]`
* `[Informação 2]`

## Local de armazenamento

`[Preencher]`

## Prazo de retenção

`[Preencher]`

---

# 26. Minimização de dados

A matriz deve registrar somente o necessário para:

* compreender a evidência;
* identificar sua origem;
* relacioná-la às questões;
* avaliar sua qualidade;
* sustentar os achados.

Não devem ser inseridos integralmente:

* transcrições;
* documentos;
* mensagens;
* dados pessoais;
* conteúdos sensíveis;

quando uma síntese ou referência for suficiente.

---

# 27. Revisão intermediária

## Cobertura das questões

| Questão | Quantidade de evidências | Variedade de fontes | Estado | Lacuna principal |
| ------- | ------------------------ | ------------------- | ------ | ---------------- |
| QST-001 |                          |                     |        |                  |
| QST-002 |                          |                     |        |                  |
| QST-003 |                          |                     |        |                  |

## Verificação

* [ ] Todas as questões essenciais possuem evidências.
* [ ] As questões de maior risco possuem triangulação.
* [ ] As hipóteses concorrentes foram examinadas.
* [ ] As divergências estão visíveis.
* [ ] As lacunas críticas possuem ação.
* [ ] O escopo permanece adequado.
* [ ] Não há coleta sem finalidade.
* [ ] O plano precisa ser atualizado.

## Mudanças necessárias

`[Preencher ou registrar “nenhuma”.]`

---

# 28. Prontidão para formulação dos achados

* [ ] As evidências relevantes possuem ID.
* [ ] As fontes estão identificadas.
* [ ] Evidência e interpretação estão separadas.
* [ ] A qualidade foi avaliada.
* [ ] As convergências foram verificadas.
* [ ] As divergências foram registradas.
* [ ] As lacunas críticas foram tratadas.
* [ ] Os graus de confiança são proporcionais.
* [ ] As hipóteses foram atualizadas.
* [ ] Os dados sensíveis estão protegidos.
* [ ] A participação da IA foi registrada.
* [ ] As conclusões podem ser reconstruídas.

## Resultado

* [ ] Pronta
* [ ] Pronta com limitações
* [ ] Requer nova coleta
* [ ] Requer revisão
* [ ] Não deve avançar

## Condições ou limitações

`[Preencher]`

---

# 29. Validação

## Validação interna

**Responsável:** `[Nome]`
**Data:** `[DD/MM/AAAA]`

### Verificado

* [ ] Rastreabilidade
* [ ] Qualidade
* [ ] Confiança
* [ ] Divergências
* [ ] Lacunas
* [ ] Linguagem
* [ ] Sensibilidade
* [ ] Participação da IA
* [ ] Aderência ao escopo

## Validação factual com o cliente

| Achado ou evidência | Pessoa responsável | Data | Resultado |
| ------------------- | ------------------ | ---- | --------- |
|                     |                    |      |           |

## Correções recebidas

`[Preencher]`

## Divergências mantidas

`[Preencher]`

## Resultado da validação

* [ ] Validada
* [ ] Validada com ajustes
* [ ] Validada com divergências
* [ ] Parcialmente validada
* [ ] Requer investigação adicional

---

# 30. Síntese da matriz

## Questões respondidas

* `QST-___ — [Síntese]`
* `QST-___ — [Síntese]`

## Questões parcialmente respondidas

* `QST-___ — [Limitação]`

## Questões inconclusivas

* `QST-___ — [Motivo]`

## Hipóteses sustentadas

* `HIP-___`

## Hipóteses rejeitadas

* `HIP-___`

## Capacidades principais

* `ACH-___ — [Título]`

## Problemas principais

* `ACH-___ — [Título]`

## Riscos principais

* `ACH-___ — [Título]`

## Restrições principais

* `ACH-___ — [Título]`

## Lacunas remanescentes

* `LAC-___ — [Descrição]`

## Requisitos para o Módulo 3

* `[Requisito 1]`
* `[Requisito 2]`
* `[Requisito 3]`

---

# 31. Critérios de conclusão

A matriz pode ser considerada consolidada quando:

* [ ] as questões essenciais foram investigadas;
* [ ] as fontes previstas foram consultadas ou suas ausências registradas;
* [ ] todas as evidências utilizadas possuem origem;
* [ ] evidências e interpretações estão separadas;
* [ ] a qualidade foi avaliada;
* [ ] os graus de confiança estão justificados;
* [ ] as divergências relevantes estão preservadas;
* [ ] as lacunas remanescentes estão explícitas;
* [ ] as hipóteses foram atualizadas;
* [ ] os achados possuem evidências relacionadas;
* [ ] os limites estão registrados;
* [ ] os dados sensíveis estão protegidos;
* [ ] a participação da IA está documentada;
* [ ] a matriz foi revisada;
* [ ] os aspectos factuais foram validados no grau possível;
* [ ] a síntese diagnóstica pode ser produzida.

## Estado final

* [ ] Consolidada
* [ ] Consolidada com limitações
* [ ] Aguardando validação
* [ ] Requer aprofundamento
* [ ] Reaberta
* [ ] Encerrada

## Limitações finais

`[Preencher]`

---

# 32. Histórico de versões

| Data | Versão | Alteração         | Motivo | Responsável |
| ---- | ------ | ----------------- | ------ | ----------- |
|      | 0.1    | Criação da matriz |        |             |
|      |        |                   |        |             |

---

# 33. Versão reduzida para diagnóstico focal

## Identificação

* **Diagnóstico:** `DIA-AAAA-NNN`
* **Título:** `[Preencher]`
* **Responsável:** `[Nome]`
* **Data:** `[DD/MM/AAAA]`

## Questão central

`[Preencher]`

## Hipóteses

* `HIP-001 — [Hipótese]`
* `HIP-002 — [Hipótese]`

## Matriz reduzida

| ID      | Pergunta | Fonte | Evidência | Interpretação | Qualidade | Confiança | Lacuna ou ação | Achado |
| ------- | -------- | ----- | --------- | ------------- | --------- | --------- | -------------- | ------ |
| EVD-001 |          |       |           |               |           |           |                |        |
| EVD-002 |          |       |           |               |           |           |                |        |
| EVD-003 |          |       |           |               |           |           |                |        |

## Achados

| ID      | Achado | Evidências | Confiança | Implicação | Encaminhamento |
| ------- | ------ | ---------- | --------- | ---------- | -------------- |
| ACH-001 |        |            |           |            |                |
| ACH-002 |        |            |           |            |                |

## Lacunas

* `[Lacuna 1]`
* `[Lacuna 2]`

## Limitações

`[Preencher]`

## Próxima ação

`[Ação, responsável e prazo.]`

Agora temos duas camadas distintas:

* `matriz-de-evidencias.md`, na raiz do módulo, explica **o método e seus critérios**;
* `templates/matriz-de-evidencias.md` é o **instrumento preenchível de cada diagnóstico**.

O próximo template lógico é `sintese-diagnostica.md`, que transformará os achados consolidados em uma leitura clara da situação atual, sem ainda assumir a extensão de um relatório completo.
