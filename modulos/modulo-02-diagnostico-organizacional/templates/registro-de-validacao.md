# Registro de Validação Diagnóstica

```yaml id="w5f1pz"
id_validacao: VAL-AAAA-NNN
id_diagnostico: DIA-AAAA-NNN
titulo: "[Validação da síntese, dos achados ou do relatório]"
organizacao:
area_ou_processo:
responsavel_pelo_diagnostico:
responsavel_pela_validacao:
responsavel_cliente:
data_de_abertura: AAAA-MM-DD
data_da_validacao:
data_de_encerramento:
estado: em_preparacao
tipo_de_validacao: interna | factual | interpretativa | decisoria | mista
nivel_sensibilidade: publica | interna | confidencial | sensivel
documento_validado:
versao_validada:
versao_resultante:
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional de validação
**Função:** Registro de confirmações, correções, divergências e efeitos da validação sobre o diagnóstico

**Documentos relacionados:**

* `matriz-de-evidencias.md`;
* `sintese-diagnostica.md`;
* `relatorio-de-diagnostico.md`;
* `transicao-para-arquitetura.md`;
* registros de entrevistas;
* registros de observação;
* inventário documental;
* registros de decisão.

---

# 1. Finalidade

Este documento registra como os resultados de um diagnóstico foram submetidos à validação.

A validação pode envolver:

* verificação de fatos;
* revisão de datas;
* correção de nomes, funções ou processos;
* apresentação de novas evidências;
* discussão de interpretações;
* confronto de perspectivas;
* revisão de prioridades;
* registro de divergências;
* reformulação de achados;
* definição de condições para continuidade.

Sua função não é obter concordância artificial.

Ela deve tornar visível:

* o que foi confirmado;
* o que foi corrigido;
* o que permaneceu incerto;
* o que foi contestado;
* que novas evidências surgiram;
* que achados foram alterados;
* que divergências foram preservadas;
* qual versão resultou do processo.

---

# 2. Princípios da validação

## 2.1 Validar não significa transferir a autoria do diagnóstico

As pessoas participantes podem:

* corrigir fatos;
* acrescentar contexto;
* apresentar evidências;
* discordar de interpretações;
* indicar efeitos não considerados.

A responsabilidade pela formulação metodológica dos achados permanece com a pessoa responsável pelo diagnóstico.

---

## 2.2 Discordância não invalida automaticamente o achado

Uma divergência pode indicar:

* perspectiva diferente;
* posição organizacional distinta;
* acesso desigual à informação;
* conflito;
* período diferente;
* mudança recente;
* interpretação alternativa;
* ameaça percebida;
* erro no diagnóstico.

A divergência deve ser examinada, não eliminada.

---

## 2.3 Concordância não comprova automaticamente a conclusão

A concordância pode decorrer de:

* reconhecimento factual;
* visão compartilhada;
* influência hierárquica;
* desejo de encerrar;
* resposta socialmente desejável;
* desconhecimento das evidências.

A validação não substitui a Matriz de Evidências.

---

## 2.4 Fatos e interpretações devem ser tratados separadamente

### Validação factual

Verifica:

* datas;
* nomes;
* funções;
* documentos;
* etapas;
* eventos;
* ferramentas;
* números;
* responsabilidades declaradas.

### Validação interpretativa

Discute:

* relações;
* causas prováveis;
* implicações;
* riscos;
* prioridades;
* requisitos;
* leitura sistêmica.

---

## 2.5 Novas informações devem retornar à matriz

Informação apresentada durante a validação não deve ser incorporada diretamente como verdade.

Quando relevante, deve:

1. receber fonte;
2. ser registrada;
3. receber ID de evidência;
4. ser avaliada;
5. ser relacionada aos achados;
6. alterar a conclusão somente quando justificado.

---

## 2.6 A validação deve respeitar segurança e dignidade

A condução deve evitar:

* exposição desnecessária;
* atribuição pública de culpa;
* constrangimento;
* pressão por concordância;
* revelação indevida de fonte;
* circulação excessiva de informação sensível.

---

# 3. Tipos de validação

## 3.1 Interna

Realizada pelo Estúdio antes da apresentação ao cliente.

Verifica:

* coerência metodológica;
* rastreabilidade;
* linguagem;
* graus de confiança;
* limites;
* proteção de dados;
* participação da IA;
* separação entre achado e recomendação.

---

## 3.2 Factual

Realizada com pessoas capazes de confirmar ou corrigir elementos objetivos.

---

## 3.3 Interpretativa

Discute como os fatos foram compreendidos.

Não exige concordância total.

---

## 3.4 Decisória

Submete achados, prioridades ou requisitos à pessoa com autoridade para:

* aprovar continuidade;
* aceitar riscos;
* definir prioridades;
* autorizar transição;
* solicitar aprofundamento.

---

## 3.5 Mista

Combina dois ou mais tipos.

---

## Tipo desta validação

* [ ] Interna
* [ ] Factual
* [ ] Interpretativa
* [ ] Decisória
* [ ] Mista
* [ ] Outra: `[Preencher]`

---

# 4. Identificação

| Campo                            | Registro                                       |
| -------------------------------- | ---------------------------------------------- |
| **ID da validação**              | `VAL-AAAA-NNN`                                 |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                 |
| **Título**                       | `[Nome da validação]`                          |
| **Organização**                  | `[Nome]`                                       |
| **Área ou processo**             | `[Quando aplicável]`                           |
| **Responsável pelo diagnóstico** | `[Nome]`                                       |
| **Responsável pela validação**   | `[Nome]`                                       |
| **Responsável do cliente**       | `[Nome e função]`                              |
| **Data de abertura**             | `[DD/MM/AAAA]`                                 |
| **Data da validação**            | `[DD/MM/AAAA]`                                 |
| **Data de encerramento**         | `[DD/MM/AAAA]`                                 |
| **Versão do registro**           | `[0.1]`                                        |
| **Sensibilidade**                | `[Pública, interna, confidencial ou sensível]` |

## Estado

* [ ] Em preparação
* [ ] Aguardando participantes
* [ ] Aguardando documento
* [ ] Em validação
* [ ] Aguardando evidência adicional
* [ ] Em revisão
* [ ] Concluída
* [ ] Concluída com divergências
* [ ] Devolvida ao diagnóstico
* [ ] Suspensa
* [ ] Cancelada

---

# 5. Objeto da validação

## Documento principal

`[Nome e caminho do documento.]`

## Versão submetida

`[Preencher]`

## Data da versão

`[DD/MM/AAAA]`

## Elementos submetidos

* [ ] Questão diagnóstica
* [ ] Descrição da situação atual
* [ ] Mapa de processo
* [ ] Evidências
* [ ] Achados
* [ ] Capacidades
* [ ] Problemas
* [ ] Causas ou fatores prováveis
* [ ] Riscos
* [ ] Restrições
* [ ] Prioridades
* [ ] Requisitos
* [ ] Síntese diagnóstica
* [ ] Relatório
* [ ] Transição para arquitetura
* [ ] Outro: `[Preencher]`

## Elementos não submetidos

* `[Elemento 1]`
* `[Elemento 2]`

## Motivo

`[Preencher]`

---

# 6. Finalidade da validação

## Objetivo principal

`[O que precisa ser confirmado, corrigido, discutido ou decidido?]`

## Objetivos específicos

1. `[Objetivo 1]`
2. `[Objetivo 2]`
3. `[Objetivo 3]`

## Resultado esperado

`[Que condição permitirá considerar a validação concluída?]`

## O que não constitui objetivo

* `[Item 1]`
* `[Item 2]`

---

# 7. Escopo da validação

## Incluído

* `[Seção, achado, processo ou questão 1]`
* `[Elemento 2]`
* `[Elemento 3]`

## Excluído

* `[Elemento 1]`
* `[Elemento 2]`

## Limites

`[O que esta validação não poderá determinar?]`

## Decisões fora do escopo

* `[Decisão 1]`
* `[Decisão 2]`

---

# 8. Participantes

| Pessoa ou identificador | Função ou relação | Tipo de conhecimento | Papel na validação | Autoridade decisória |
| ----------------------- | ----------------- | -------------------- | ------------------ | -------------------- |
|                         |                   |                      |                    | Sim / Não            |
|                         |                   |                      |                    | Sim / Não            |
|                         |                   |                      |                    | Sim / Não            |

## Perspectivas representadas

* `[Perspectiva 1]`
* `[Perspectiva 2]`

## Perspectivas ausentes

* `[Pessoa, função ou grupo]`

## Efeito das ausências

`[Preencher]`

## Relações hierárquicas relevantes

`[Preencher ou registrar “não aplicável”.]`

## Medidas para reduzir influência hierárquica

* `[Medida 1]`
* `[Medida 2]`

---

# 9. Preparação

## Materiais enviados previamente

* `[Documento 1]`
* `[Documento 2]`

## Data de envio

`[DD/MM/AAAA]`

## Prazo para leitura

`[Preencher]`

## Orientações fornecidas

* distinguir correção factual de discordância interpretativa;
* apresentar exemplos e fontes;
* indicar trechos específicos;
* registrar informação sensível por canal adequado;
* evitar discussão centrada em culpa;
* informar quando não houver conhecimento suficiente.

## Perguntas enviadas previamente

1. `[Pergunta 1]`
2. `[Pergunta 2]`
3. `[Pergunta 3]`

## Temas sensíveis

* `[Tema 1]`
* `[Tema 2]`

## Riscos da validação

* [ ] Pressão por concordância
* [ ] Exposição de participante
* [ ] Defesa de interesse
* [ ] Conflito hierárquico
* [ ] Tentativa de alterar conclusão sem evidência
* [ ] Inclusão de informação fora do escopo
* [ ] Divulgação de dado sensível
* [ ] Outro: `[Preencher]`

## Proteções planejadas

`[Preencher]`

---

# 10. Formato da validação

* [ ] Reunião presencial
* [ ] Videoconferência
* [ ] Documento comentado
* [ ] Entrevistas individuais
* [ ] Oficina
* [ ] E-mail
* [ ] Mensagem registrada
* [ ] Assinatura
* [ ] Outro: `[Preencher]`

## Data

`[DD/MM/AAAA]`

## Horário

`[HH:MM]`

## Duração

`[Preencher]`

## Local ou plataforma

`[Preencher]`

## Forma de registro

* [ ] Ata
* [ ] Anotações
* [ ] Comentários no documento
* [ ] Gravação autorizada
* [ ] Transcrição
* [ ] Formulário
* [ ] Outro: `[Preencher]`

---

# 11. Abertura sugerida

> Esta validação tem a finalidade de verificar fatos, incorporar contexto relevante e discutir as interpretações produzidas pelo diagnóstico.
>
> Correções factuais e novas evidências serão incorporadas após verificação. Divergências interpretativas poderão permanecer registradas quando existirem leituras distintas sustentáveis.
>
> O objetivo não é produzir concordância obrigatória nem avaliar individualmente as pessoas participantes. O foco está na qualidade da compreensão e na utilidade do diagnóstico para a decisão e para a etapa seguinte.

---

# 12. Pauta

1. finalidade e limites;
2. síntese da investigação;
3. aspectos factuais;
4. capacidades identificadas;
5. achados principais;
6. evidências e graus de confiança;
7. divergências;
8. riscos e restrições;
9. prioridades;
10. requisitos;
11. questões abertas;
12. próximos passos.

## Ajustes de pauta

`[Preencher]`

---

# 13. Quadro geral de validação

| ID          | Elemento submetido | Tipo           | Resultado  | Correção ou comentário | Nova evidência | Ação |
| ----------- | ------------------ | -------------- | ---------- | ---------------------- | -------------- | ---- |
| VAL-ITM-001 |                    | Factual        | Confirmado |                        |                |      |
| VAL-ITM-002 |                    | Interpretativo | Ajustado   |                        |                |      |
| VAL-ITM-003 |                    | Interpretativo | Divergente |                        |                |      |

## Tipos

* Factual
* Interpretativo
* Metodológico
* Decisório
* Sensível
* Outro

## Resultados

* Confirmado
* Confirmado com ajuste
* Corrigido
* Complementado
* Contestado
* Divergente
* Inconclusivo
* Fora do escopo
* Reaberto
* Não avaliado

---

# 14. Validação factual

## Elementos verificados

| ID      | Elemento          | Registro submetido | Correção ou confirmação | Fonte da correção | Efeito |
| ------- | ----------------- | ------------------ | ----------------------- | ----------------- | ------ |
| FAT-001 | Data              |                    |                         |                   |        |
| FAT-002 | Responsabilidade  |                    |                         |                   |        |
| FAT-003 | Etapa do processo |                    |                         |                   |        |
| FAT-004 | Documento         |                    |                         |                   |        |
| FAT-005 | Dado              |                    |                         |                   |        |

## Categorias possíveis

* nomes;
* funções;
* datas;
* quantidades;
* sistemas;
* documentos;
* etapas;
* responsabilidades;
* eventos;
* contratos;
* regras;
* indicadores.

## Correções sem impacto interpretativo

* `[Correção 1]`
* `[Correção 2]`

## Correções com impacto interpretativo

* `[Correção 1]`
* `[Correção 2]`

## Ações necessárias

`[Preencher]`

---

# 15. Validação da situação atual

| Elemento          | Descrição apresentada | Confirmação | Ajuste | Fonte adicional |
| ----------------- | --------------------- | ----------- | ------ | --------------- |
| Fluxo             |                       |             |        |                 |
| Responsabilidades |                       |             |        |                 |
| Informação        |                       |             |        |                 |
| Ferramentas       |                       |             |        |                 |
| Decisões          |                       |             |        |                 |
| Resultados        |                       |             |        |                 |

## Diferenças entre perspectivas

`[Preencher]`

## Parte ainda não verificável

`[Preencher]`

---

# 16. Validação das capacidades

| ID do achado | Capacidade | Confirmada por | Ajuste necessário | Risco de perda | Resultado |
| ------------ | ---------- | -------------- | ----------------- | -------------- | --------- |
| ACH-___      |            |                |                   |                |           |
| ACH-___      |            |                |                   |                |           |

## Capacidades não reconhecidas inicialmente

* `[Capacidade 1]`
* `[Capacidade 2]`

## Evidências adicionais

* `EVD-___`
* `EVD-___`

## Elementos a preservar

* `[Elemento 1]`
* `[Elemento 2]`

---

# 17. Validação dos achados

Esta seção deve ser duplicada para cada achado relevante.

---

## `ACH-NNN — [Título do achado]`

### Afirmação submetida

`[Texto do achado antes da validação.]`

### Tipo

`[Capacidade, problema, risco, restrição, oportunidade, contradição, lacuna ou requisito.]`

### Evidências apresentadas

* `EVD-___`
* `EVD-___`
* `EVD-___`

### Confiança anterior

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Inconclusiva

### Resultado da validação

* [ ] Confirmado
* [ ] Confirmado com ajuste
* [ ] Complementado
* [ ] Contestado
* [ ] Divergência mantida
* [ ] Reaberto
* [ ] Rejeitado
* [ ] Inconclusivo

### Correções factuais

`[Preencher ou registrar “nenhuma”.]`

### Contexto adicional

`[Preencher]`

### Nova evidência

* `EVD-___`
* `[Nenhuma ou preencher.]`

### Perspectiva divergente

`[Preencher ou registrar “nenhuma”.]`

### Avaliação da divergência

`[Que efeito a divergência produz sobre o achado?]`

### Formulação resultante

`[Texto revisado do achado.]`

### Confiança resultante

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Inconclusiva

### Justificativa

`[Preencher]`

### Ação

* [ ] Manter
* [ ] Reformular
* [ ] Dividir em dois achados
* [ ] Rebaixar confiança
* [ ] Elevar confiança
* [ ] Buscar nova evidência
* [ ] Retirar da síntese
* [ ] Encaminhar para especialista
* [ ] Outra: `[Preencher]`

---

# 18. Novas evidências apresentadas

| ID      | Informação | Fonte | Tipo                                          | Questão relacionada | Achado relacionado | Estado      |
| ------- | ---------- | ----- | --------------------------------------------- | ------------------- | ------------------ | ----------- |
| EVD-___ |            |       | Declarada / documental / quantitativa / outra | QST-___             | ACH-___            | A verificar |
| EVD-___ |            |       |                                               |                     |                    |             |

## Procedimento

Toda nova evidência deve ser:

* [ ] registrada na Matriz de Evidências;
* [ ] vinculada à fonte;
* [ ] avaliada quanto à qualidade;
* [ ] comparada com evidências existentes;
* [ ] incorporada ou descartada com justificativa.

## Evidências ainda não verificadas

* `EVD-___`
* `EVD-___`

## Impacto potencial

`[Preencher]`

---

# 19. Divergências

| ID      | Tema | Diagnóstico | Perspectiva divergente | Fonte | Efeito | Estado     |
| ------- | ---- | ----------- | ---------------------- | ----- | ------ | ---------- |
| DIV-001 |      |             |                        |       |        | Aberta     |
| DIV-002 |      |             |                        |       |        | Registrada |

## Natureza da divergência

* [ ] Factual
* [ ] Interpretativa
* [ ] Temporal
* [ ] Hierárquica
* [ ] Experiencial
* [ ] Metodológica
* [ ] Decisória
* [ ] Interesse
* [ ] Outra: `[Preencher]`

## Estados

* Aberta
* Em investigação
* Resolvida por evidência
* Reduzida
* Mantida
* Aceita
* Fora do escopo
* Encaminhada

## Tratamento

`[Como a divergência será tratada?]`

## A divergência impede a conclusão?

* [ ] Não
* [ ] Parcialmente
* [ ] Sim
* [ ] A definir

## Justificativa

`[Preencher]`

---

# 20. Mudanças nos graus de confiança

| Achado ou questão | Confiança anterior | Confiança resultante | Motivo |
| ----------------- | ------------------ | -------------------- | ------ |
| ACH-___           |                    |                      |        |
| QST-___           |                    |                      |        |
| HIP-___           |                    |                      |        |

## Aumentos de confiança

`[Preencher]`

## Reduções de confiança

`[Preencher]`

## Elementos inconclusivos

`[Preencher]`

---

# 21. Revisão das hipóteses

| Hipótese | Estado anterior | Efeito da validação | Estado resultante                    | Evidências |
| -------- | --------------- | ------------------- | ------------------------------------ | ---------- |
| HIP-001  | Em investigação |                     | Sustentada / rejeitada / reformulada |            |
| HIP-002  |                 |                     |                                      |            |

## Hipóteses novas

* `HIP-___ — [Hipótese]`

## Hipóteses rejeitadas

* `HIP-___ — [Motivo]`

## Hipóteses reabertas

* `HIP-___ — [Motivo]`

---

# 22. Validação das relações sistêmicas

| Relação proposta | Elementos relacionados | Resultado | Ajuste |
| ---------------- | ---------------------- | --------- | ------ |
|                  | ACH-___ → ACH-___      |           |        |
|                  |                        |           |        |

## Cadeias revisadas

```text id="cdhwep"
[Condição]
   ↓
[Fator]
   ↓
[Problema]
   ↓
[Consequência]
```

## Relações contestadas

`[Preencher]`

## Explicações alternativas

* `[Alternativa 1]`
* `[Alternativa 2]`

## Efeito sobre a síntese

`[Preencher]`

---

# 23. Validação de riscos

| Risco   | Avaliação apresentada | Ajuste | Nova evidência | Resultado |
| ------- | --------------------- | ------ | -------------- | --------- |
| RSC-___ |                       |        |                |           |
| RSC-___ |                       |        |                |           |

## Riscos novos

* `RSC-___ — [Descrição]`

## Riscos reclassificados

`[Preencher]`

## Riscos aceitos

| Risco | Responsável pela aceitação | Justificativa | Condição de revisão |
| ----- | -------------------------- | ------------- | ------------------- |
|       |                            |               |                     |

## Riscos encaminhados

`[Especialista, decisão ou outro tratamento.]`

---

# 24. Validação de restrições

| Restrição | Condição apresentada | Ajuste | Natureza                | Resultado |
| --------- | -------------------- | ------ | ----------------------- | --------- |
| RES-___   |                      |        | Temporária / estrutural |           |
| RES-___   |                      |        |                         |           |

## Restrições novas

* `RES-___ — [Descrição]`

## Restrições anteriormente tratadas como problemas

`[Preencher]`

## Efeito sobre a arquitetura

`[Preencher]`

---

# 25. Validação das prioridades

| Achado ou requisito | Prioridade anterior | Prioridade proposta | Fundamentação | Decisão |
| ------------------- | ------------------- | ------------------- | ------------- | ------- |
| ACH-___             |                     |                     |               |         |
| REQ-___             |                     |                     |               |         |

## Critérios utilizados

* impacto;
* urgência;
* risco;
* dependência;
* esforço;
* capacidade;
* prontidão;
* valor estratégico;
* reversibilidade.

## Divergências de prioridade

`[Preencher]`

## Prioridades resultantes

1. `[Prioridade 1]`
2. `[Prioridade 2]`
3. `[Prioridade 3]`

---

# 26. Validação dos requisitos

| ID      | Requisito | Achado de origem | Resultado | Ajuste | Critério resultante |
| ------- | --------- | ---------------- | --------- | ------ | ------------------- |
| REQ-001 |           | ACH-___          |           |        |                     |
| REQ-002 |           | ACH-___          |           |        |                     |

## Requisitos confirmados

* `REQ-___`
* `REQ-___`

## Requisitos reformulados

* `REQ-___ — [Nova formulação]`

## Requisitos retirados

* `REQ-___ — [Motivo]`

## Requisitos novos

* `REQ-___ — [Origem]`

## Requisitos ainda não aprovados

* `REQ-___ — [Questão pendente]`

---

# 27. Questões reabertas

| ID      | Questão | Motivo da reabertura | Evidência necessária | Responsável | Prazo |
| ------- | ------- | -------------------- | -------------------- | ----------- | ----- |
| QST-___ |         |                      |                      |             |       |
| QAB-___ |         |                      |                      |             |       |

## A reabertura afeta

* [ ] Síntese
* [ ] Relatório
* [ ] Transição
* [ ] Prioridades
* [ ] Requisitos
* [ ] Cronograma
* [ ] Decisão
* [ ] Outro: `[Preencher]`

---

# 28. Correções realizadas

| Documento            | Seção | Correção | Origem | Responsável | Data |
| -------------------- | ----- | -------- | ------ | ----------- | ---- |
| Matriz de Evidências |       |          |        |             |      |
| Síntese Diagnóstica  |       |          |        |             |      |
| Relatório            |       |          |        |             |      |
| Transição            |       |          |        |             |      |

## Versões resultantes

| Documento | Versão anterior | Nova versão |
| --------- | --------------- | ----------- |
|           |                 |             |
|           |                 |             |

---

# 29. Elementos mantidos sem alteração

* `[Elemento 1 e justificativa]`
* `[Elemento 2 e justificativa]`
* `[Elemento 3 e justificativa]`

## Elementos contestados, mas mantidos

| Elemento | Contestação | Motivo da manutenção | Confiança |
| -------- | ----------- | -------------------- | --------- |
|          |             |                      |           |
|          |             |                      |           |

---

# 30. Elementos retirados

| Elemento | Motivo | Efeito sobre o diagnóstico |
| -------- | ------ | -------------------------- |
|          |        |                            |
|          |        |                            |

## Retirada por ausência de evidência

* `[Elemento 1]`

## Retirada por erro factual

* `[Elemento 1]`

## Retirada por alteração de escopo

* `[Elemento 1]`

---

# 31. Decisões decorrentes

| ID           | Decisão | Responsável | Fundamentação | Prazo | Registro |
| ------------ | ------- | ----------- | ------------- | ----- | -------- |
| DEC-AAAA-NNN |         |             |               |       |          |
|              |         |             |               |       |          |

## Decisões não tomadas

* `[Decisão 1]`
* `[Decisão 2]`

## Motivo

`[Preencher]`

---

# 32. Resultado geral da validação

* [ ] Validada sem ajustes materiais
* [ ] Validada com ajustes factuais
* [ ] Validada com ajustes interpretativos
* [ ] Validada com divergências
* [ ] Parcialmente validada
* [ ] Devolvida para investigação adicional
* [ ] Não validada
* [ ] Cancelada

## Fundamentação

`[Explicar por que esse resultado foi atribuído.]`

## Confiança geral após validação

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Heterogênea por achado
* [ ] Inconclusiva

## A validação autoriza

* [ ] Concluir a síntese
* [ ] Emitir o relatório
* [ ] Prosseguir para arquitetura
* [ ] Tomar decisão específica
* [ ] Realizar investigação complementar
* [ ] Realizar experimento
* [ ] Encaminhar para especialista
* [ ] Suspender
* [ ] Encerrar sem continuidade

---

# 33. Condições para continuidade

* `[Condição 1]`
* `[Condição 2]`
* `[Condição 3]`

## Condições impeditivas

* `[Condição 1]`
* `[Condição 2]`

## Pendências

| Pendência | Responsável | Prazo | Impacto |
| --------- | ----------- | ----- | ------- |
|           |             |       |         |
|           |             |       |         |

---

# 34. Próximas ações

| Ação                           | Responsável | Prazo | Estado   |
| ------------------------------ | ----------- | ----- | -------- |
| Atualizar Matriz de Evidências |             |       | Pendente |
| Revisar Síntese Diagnóstica    |             |       | Pendente |
| Revisar Relatório              |             |       | Pendente |
| Atualizar Transição            |             |       | Pendente |
| Buscar nova evidência          |             |       | Pendente |
| Abrir decisão                  |             |       | Pendente |
| Encaminhar para especialista   |             |       | Pendente |

---

# 35. Participação da inteligência artificial

## A IA foi utilizada?

* [ ] Não
* [ ] Preparação dos materiais
* [ ] Organização dos comentários
* [ ] Comparação entre versões
* [ ] Identificação de divergências
* [ ] Consolidação de correções
* [ ] Revisão de completude
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## Sistema ou agente

`[Nome e versão, quando disponível.]`

## Dados fornecidos

`[Descrever categorias.]`

## Saídas utilizadas

`[Preencher]`

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

* [ ] Comentários comparados com o registro original
* [ ] Correções revisadas
* [ ] Divergências preservadas
* [ ] Nenhuma nova evidência foi inventada
* [ ] Decisões permaneceram humanas

## Responsável pela revisão

`[Nome]`

## Limitações ou erros identificados

`[Preencher ou registrar “nenhum identificado”.]`

---

# 36. Confidencialidade

## Classificação

* [ ] Pública
* [ ] Interna
* [ ] Confidencial
* [ ] Sensível

## Acesso autorizado

| Pessoa ou função | Nível de acesso | Justificativa |
| ---------------- | --------------- | ------------- |
|                  |                 |               |

## Informações sensíveis discutidas

`[Descrever categorias, sem reproduzir conteúdo desnecessário.]`

## Informações excluídas da versão geral

* `[Informação 1]`
* `[Informação 2]`

## Forma de anonimização

`[Preencher]`

## Local de armazenamento

`[Preencher]`

## Destino de gravações ou transcrições

`[Preencher]`

---

# 37. Incidentes

| Ocorrência | Momento | Impacto | Medida tomada | Seguimento |
| ---------- | ------- | ------- | ------------- | ---------- |
|            |         |         |               |            |

## Exemplos

* exposição indevida;
* conflito;
* interrupção;
* retirada de autorização;
* gravação incompleta;
* circulação não autorizada;
* pressão hierárquica;
* tentativa de alterar registro sem evidência.

## A validação permanece válida?

* [ ] Sim
* [ ] Sim, com limitações
* [ ] Parcialmente
* [ ] Não
* [ ] A definir

## Fundamentação

`[Preencher]`

---

# 38. Avaliação da condução

* [ ] A finalidade foi explicada.
* [ ] Fatos e interpretações foram diferenciados.
* [ ] As pessoas puderam corrigir informações.
* [ ] As pessoas puderam discordar.
* [ ] Novas evidências foram registradas.
* [ ] Divergências não foram apagadas.
* [ ] A hierarquia foi considerada.
* [ ] A discussão permaneceu no escopo.
* [ ] Dados sensíveis foram protegidos.
* [ ] A validação produziu efeito claro sobre os documentos.

## O que funcionou bem?

`[Preencher]`

## O que gerou dificuldade?

`[Preencher]`

## Que aspecto exigiu maior cuidado?

`[Preencher]`

## O que deve mudar em futuras validações?

`[Preencher]`

---

# 39. Critérios de conclusão

A validação pode ser considerada concluída quando:

* [ ] o objeto da validação foi definido;
* [ ] as pessoas relevantes participaram ou suas ausências foram registradas;
* [ ] os aspectos factuais foram confrontados;
* [ ] novas evidências foram registradas;
* [ ] as interpretações contestadas foram examinadas;
* [ ] divergências materiais foram preservadas;
* [ ] os graus de confiança foram revisados;
* [ ] hipóteses foram atualizadas;
* [ ] achados foram mantidos, reformulados ou retirados;
* [ ] riscos e restrições foram revisados;
* [ ] prioridades foram discutidas;
* [ ] requisitos foram validados no grau possível;
* [ ] as correções foram incorporadas;
* [ ] as versões resultantes foram registradas;
* [ ] o resultado geral foi definido;
* [ ] as próximas ações possuem responsáveis;
* [ ] a participação da IA foi documentada;
* [ ] os dados foram protegidos.

---

# 40. Aprovação do registro

## Elaborado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Revisado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Ciência do responsável do cliente

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Forma de ciência ou aprovação

* [ ] Registro neste documento
* [ ] Reunião registrada
* [ ] E-mail
* [ ] Mensagem
* [ ] Assinatura
* [ ] Outra: `[Preencher]`

## Evidência

`[Link, arquivo ou referência.]`

## Observação

A ciência do cliente não significa necessariamente concordância integral com todas as interpretações.

---

# 41. Histórico de versões

| Data | Versão | Alteração           | Motivo | Responsável |
| ---- | ------ | ------------------- | ------ | ----------- |
|      | 0.1    | Criação do registro |        |             |
|      |        |                     |        |             |

---

# 42. Síntese executiva da validação

## Documento validado

`[Nome e versão.]`

## Participantes

`[Síntese.]`

## Resultado geral

`[Preencher.]`

## Correções factuais principais

* `[Correção 1]`
* `[Correção 2]`

## Achados reformulados

* `ACH-___ — [Síntese]`

## Divergências mantidas

* `DIV-___ — [Síntese]`

## Novas evidências

* `EVD-___ — [Síntese]`

## Mudanças de confiança

* `[Elemento e alteração]`

## Condições para continuidade

* `[Condição 1]`
* `[Condição 2]`

## Próximo documento ou ação

`[Preencher]`

---

# 43. Versão resumida para diagnóstico focal

## Identificação

* **Validação:** `VAL-AAAA-NNN`
* **Diagnóstico:** `DIA-AAAA-NNN`
* **Documento:** `[Nome e versão]`
* **Data:** `[DD/MM/AAAA]`
* **Responsável:** `[Nome]`

## Participantes

* `[Nome ou função]`

## Elementos validados

* `[Elemento 1]`
* `[Elemento 2]`

## Quadro resumido

| Elemento | Resultado                          | Correção ou divergência | Ação |
| -------- | ---------------------------------- | ----------------------- | ---- |
|          | Confirmado / Ajustado / Divergente |                         |      |
|          |                                    |                         |      |

## Novas evidências

* `EVD-___ — [Descrição]`

## Achados alterados

* `ACH-___ — [Nova formulação]`

## Divergências mantidas

* `DIV-___ — [Descrição]`

## Resultado

* [ ] Validada
* [ ] Validada com ajustes
* [ ] Validada com divergências
* [ ] Requer investigação adicional
* [ ] Não validada

## Próxima ação

`[Ação, responsável e prazo.]`

---

# 44. Princípio de encerramento

A validação diagnóstica não existe para confirmar a autoridade de quem elaborou o diagnóstico nem para entregar às pessoas envolvidas o poder de eliminar conclusões desconfortáveis.

Ela existe para confrontar a interpretação com:

* fatos;
* experiências;
* documentos;
* perspectivas;
* novas evidências;
* limites;
* consequências.

Uma validação responsável pode produzir:

* confirmação;
* correção;
* maior precisão;
* menor confiança;
* reformulação;
* divergência;
* reabertura.

Seu resultado mais importante não é o consenso.

É uma compreensão mais rigorosa, explícita e utilizável.

Com este arquivo, o ciclo diagnóstico passa a registrar formalmente a diferença entre **ser informado, concordar, corrigir e validar**. O próximo documento de fechamento é o `retrospectiva.md`, que transformará cada diagnóstico concluído em aprendizagem para o próprio Sistema Operacional.
