# Relatório de Diagnóstico Organizacional

```yaml
id_diagnostico: DIA-AAAA-NNN
titulo: "[Nome do diagnóstico]"
subtitulo: "[Área, processo ou questão analisada]"
organizacao:
responsavel_cliente:
responsavel_diagnostico:
tipo_diagnostico: focal | funcional | sistemico
data_inicio: AAAA-MM-DD
data_conclusao:
data_emissao:
estado: em_elaboracao
nivel_sensibilidade: publica | interna | confidencial | sensivel
versao: 0.1
sintese_relacionada: sintese-diagnostica.md
matriz_de_evidencias: matriz-de-evidencias.md
decisao_relacionada:
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional de entrega
**Função:** Documentação completa da investigação, das evidências, das análises e dos resultados diagnósticos

**Documentos relacionados:**

* `briefing.md`;
* `plano-de-investigacao.md`;
* `matriz-de-evidencias.md`;
* `sintese-diagnostica.md`;
* registros de entrevistas;
* registros de observação;
* inventário documental;
* mapas e análises;
* registro de validação;
* `transicao-para-arquitetura.md`.

---

# 1. Finalidade

O Relatório de Diagnóstico Organizacional apresenta, de forma estruturada, rastreável e contextualizada, os resultados de uma investigação conduzida pelo Estúdio LICHTARA.

Sua função é registrar:

* a situação que originou o diagnóstico;
* a questão investigada;
* a decisão que o diagnóstico deverá apoiar;
* o escopo e os limites;
* o método utilizado;
* as fontes consultadas;
* a qualidade das evidências;
* as capacidades existentes;
* os problemas, riscos e restrições;
* as relações entre os achados;
* as hipóteses sustentadas ou rejeitadas;
* as divergências;
* as lacunas;
* as prioridades;
* os requisitos para a etapa seguinte;
* o processo de validação;
* os aprendizados metodológicos.

O relatório não deve apenas comunicar conclusões.

Ele deve permitir compreender:

1. o que foi investigado;
2. como a investigação foi conduzida;
3. quais evidências sustentam os achados;
4. quais limites condicionam as conclusões;
5. por que determinadas questões foram priorizadas;
6. como os resultados deverão orientar decisões futuras.

---

# 2. Relação entre síntese e relatório

A `sintese-diagnostica.md` apresenta a leitura essencial do diagnóstico.

O relatório apresenta a documentação ampliada.

## A síntese prioriza

* clareza;
* compreensão executiva;
* principais achados;
* relações centrais;
* prioridades;
* requisitos;
* próximos passos.

## O relatório acrescenta

* detalhamento metodológico;
* descrição das fontes;
* critérios de análise;
* avaliações de evidência;
* desenvolvimento dos achados;
* mapas;
* hipóteses;
* divergências;
* validações;
* anexos;
* rastreabilidade ampliada.

Nem todo diagnóstico precisa de um relatório extenso.

O relatório completo deve ser utilizado quando houver:

* múltiplas fontes;
* maior complexidade;
* impacto significativo;
* risco;
* necessidade de memória institucional;
* necessidade de prestação de contas;
* diagnóstico funcional ou sistêmico;
* decisão relevante;
* participação de diferentes pessoas;
* uso material de inteligência artificial;
* necessidade de documentação para continuidade.

---

# 3. Instruções de uso

Este template deve ser duplicado dentro da pasta de cada diagnóstico real.

O arquivo-mestre não deve ser preenchido diretamente.

O relatório deve ser produzido após:

* coleta suficiente de evidências;
* consolidação da matriz;
* formulação dos achados;
* revisão dos graus de confiança;
* registro das limitações;
* elaboração da síntese;
* validação factual no grau possível.

Seções não aplicáveis podem ser removidas, desde que isso não prejudique:

* compreensão;
* rastreabilidade;
* transparência;
* responsabilidade;
* continuidade.

O relatório deve ser proporcional ao diagnóstico.

---

# 4. Identificação

| Campo                            | Registro                                       |
| -------------------------------- | ---------------------------------------------- |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                 |
| **Título**                       | `[Nome do diagnóstico]`                        |
| **Subtítulo**                    | `[Área, processo ou questão]`                  |
| **Organização**                  | `[Nome]`                                       |
| **Responsável do cliente**       | `[Nome e função]`                              |
| **Responsável pelo diagnóstico** | `[Nome]`                                       |
| **Equipe participante**          | `[Nomes ou funções]`                           |
| **Tipo de diagnóstico**          | `[Focal, funcional ou sistêmico]`              |
| **Data de início**               | `[DD/MM/AAAA]`                                 |
| **Data de conclusão**            | `[DD/MM/AAAA]`                                 |
| **Data de emissão**              | `[DD/MM/AAAA]`                                 |
| **Versão**                       | `[0.1]`                                        |
| **Sensibilidade**                | `[Pública, interna, confidencial ou sensível]` |

## Estado

* [ ] Em elaboração
* [ ] Em revisão interna
* [ ] Aguardando validação
* [ ] Em validação
* [ ] Revisado
* [ ] Validado
* [ ] Validado com divergências
* [ ] Entregue
* [ ] Substituído
* [ ] Arquivado

---

# 5. Controle de distribuição

## Versão do relatório

* [ ] Completa interna
* [ ] Completa para o cliente
* [ ] Executiva
* [ ] Anonimizada
* [ ] Restrita
* [ ] Outra: `[Preencher]`

## Destinatários autorizados

| Pessoa ou função | Versão | Finalidade | Data de envio |
| ---------------- | ------ | ---------- | ------------- |
|                  |        |            |               |
|                  |        |            |               |

## Restrições

`[Descrever limites de compartilhamento, reprodução ou circulação.]`

## Informações removidas ou anonimizadas

* `[Informação 1]`
* `[Informação 2]`

## Local oficial de armazenamento

`[Preencher]`

---

# 6. Aviso de interpretação

Este relatório representa uma análise situada:

* no período investigado;
* no escopo aprovado;
* nas fontes disponíveis;
* nas condições de acesso;
* nos métodos utilizados.

Suas conclusões não devem ser generalizadas para:

* áreas não investigadas;
* períodos diferentes;
* pessoas não consultadas;
* decisões distintas;
* contextos que tenham mudado substancialmente.

O relatório não substitui avaliações especializadas de natureza:

* jurídica;
* contábil;
* financeira;
* médica;
* psicológica;
* regulatória;
* técnica;

quando essas competências forem necessárias.

---

# 7. Sumário executivo

Esta seção deve permitir compreender as conclusões centrais sem substituir a leitura das análises.

## Situação

`[Apresentar o contexto e a condição que originaram o diagnóstico.]`

## Questão diagnóstica

> `[Reproduzir a questão central.]`

## Conclusão geral

`[Apresentar em dois ou três parágrafos a compreensão principal produzida pelo diagnóstico.]`

## Capacidades centrais

* `[Capacidade 1]`
* `[Capacidade 2]`
* `[Capacidade 3]`

## Problemas prioritários

1. `[Problema 1]`
2. `[Problema 2]`
3. `[Problema 3]`

## Riscos principais

* `[Risco 1]`
* `[Risco 2]`

## Restrições principais

* `[Restrição 1]`
* `[Restrição 2]`

## Prioridades

1. `[Prioridade 1]`
2. `[Prioridade 2]`
3. `[Prioridade 3]`

## Requisito central para a arquitetura

`[Preencher]`

## Encaminhamento recomendado

* [ ] Prosseguir para arquitetura
* [ ] Realizar investigação complementar
* [ ] Realizar experimento
* [ ] Tomar decisão específica
* [ ] Encaminhar para especialista
* [ ] Monitorar
* [ ] Adiar
* [ ] Não intervir

## Principal limitação

`[Preencher]`

---

# 8. Contexto organizacional

## 8.1 Apresentação da organização

`[Descrever atividade, público, estágio, estrutura e contexto relevante.]`

## 8.2 Propósito declarado

`[Preencher.]`

## 8.3 Transformação ou valor produzido

`[Preencher.]`

## 8.4 Estágio atual

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

## 8.5 Estrutura atual

`[Número de pessoas, funções, unidades, clientes, projetos ou outra dimensão pertinente.]`

## 8.6 Mudanças recentes

* `[Mudança 1]`
* `[Mudança 2]`
* `[Mudança 3]`

## 8.7 Contexto externo

`[Mercado, regulação, tecnologia, comportamento do público ou outros elementos.]`

## 8.8 Restrições contextuais

* `[Restrição 1]`
* `[Restrição 2]`

## 8.9 Elementos identitários a considerar

* `[Elemento 1]`
* `[Elemento 2]`

---

# 9. Origem da demanda

## Relato inicial

`[Como a demanda foi apresentada?]`

## Sinais percebidos

* `[Sinal 1]`
* `[Sinal 2]`

## Sintomas iniciais

* `[Sintoma 1]`
* `[Sintoma 2]`

## Solução inicialmente solicitada

`[Preencher ou registrar “nenhuma”.]`

## Necessidade de diagnóstico

`[Explicar por que a solução ou problema precisava ser investigado antes da intervenção.]`

## Riscos de agir sem diagnóstico

* `[Risco 1]`
* `[Risco 2]`

---

# 10. Decisão apoiada

## Decisão

`[Que decisão o relatório deverá tornar possível?]`

## Responsável pela decisão

`[Nome e função]`

## Prazo ou condição

`[Preencher]`

## Decisão formal relacionada

* [ ] Não aplicável
* [ ] Sim

**ID:** `DEC-AAAA-NNN`

## Consequências possíveis

### Se a decisão for tomada adequadamente

`[Preencher]`

### Se a decisão for tomada sem evidências suficientes

`[Preencher]`

### Se a decisão for adiada

`[Preencher]`

---

# 11. Questões diagnósticas

## Questão central

> `[Preencher]`

## Questões secundárias

| ID      | Questão | Prioridade   | Estado                              | Confiança da resposta |
| ------- | ------- | ------------ | ----------------------------------- | --------------------- |
| QST-001 |         | Essencial    | Respondida / Parcial / Inconclusiva |                       |
| QST-002 |         | Relevante    |                                     |                       |
| QST-003 |         | Complementar |                                     |                       |

## Síntese das respostas

### `QST-001 — [Questão]`

`[Resposta diagnóstica.]`

**Confiança:** `[Alta, moderada, baixa ou inconclusiva.]`

**Limite:** `[Preencher.]`

---

### `QST-002 — [Questão]`

`[Resposta diagnóstica.]`

**Confiança:** `[Preencher.]`

**Limite:** `[Preencher.]`

---

# 12. Objetivos

## Objetivo geral

`[Preencher.]`

## Objetivos específicos

1. `[Objetivo 1]`
2. `[Objetivo 2]`
3. `[Objetivo 3]`
4. `[Objetivo 4]`

## Objetivos não incluídos

* `[Item 1]`
* `[Item 2]`

---

# 13. Escopo

## 13.1 Incluído

### Áreas

* `[Área 1]`
* `[Área 2]`

### Processos

* `[Processo 1]`
* `[Processo 2]`

### Pessoas ou funções

* `[Pessoa ou função 1]`
* `[Pessoa ou função 2]`

### Sistemas e ferramentas

* `[Sistema 1]`
* `[Sistema 2]`

### Documentos e dados

* `[Documento ou categoria 1]`
* `[Dado ou categoria 2]`

### Período analisado

`[Preencher.]`

### Canais, unidades ou públicos

`[Preencher.]`

---

## 13.2 Excluído

* `[Elemento 1]`
* `[Elemento 2]`

## 13.3 Justificativa das exclusões

`[Preencher.]`

## 13.4 Mudanças de escopo

| Data | Alteração | Motivo | Impacto | Aprovação |
| ---- | --------- | ------ | ------- | --------- |
|      |           |        |         |           |

## 13.5 Questões identificadas fora do escopo

| Questão | Relevância | Encaminhamento |
| ------- | ---------- | -------------- |
|         |            |                |
|         |            |                |

---

# 14. Método

## 14.1 Abordagem geral

`[Descrever como a investigação foi estruturada.]`

## 14.2 Etapas realizadas

1. qualificação da demanda;
2. formulação da questão;
3. delimitação do escopo;
4. formulação de hipóteses;
5. planejamento;
6. coleta;
7. organização das evidências;
8. análise;
9. formulação dos achados;
10. validação;
11. síntese;
12. devolutiva.

Devem permanecer apenas as etapas efetivamente realizadas.

## 14.3 Fontes

| Tipo                | Quantidade | Cobertura | Período |
| ------------------- | ---------- | --------- | ------- |
| Entrevistas         |            |           |         |
| Observações         |            |           |         |
| Documentos          |            |           |         |
| Sistemas            |            |           |         |
| Dados quantitativos |            |           |         |
| Fontes externas     |            |           |         |

## 14.4 Ferramentas

* [ ] Entrevista
* [ ] Observação
* [ ] Análise documental
* [ ] SWOT
* [ ] Canvas
* [ ] Jornada do Cliente
* [ ] Mapa de Processos
* [ ] Maturidade Digital
* [ ] Maturidade Organizacional
* [ ] Mapa de conhecimento
* [ ] Análise de dados
* [ ] Outra: `[Preencher]`

## 14.5 Triangulação

`[Descrever como relatos, documentos, observações e dados foram comparados.]`

## 14.6 Critério de saturação

`[Explicar por que a coleta foi considerada suficiente.]`

## 14.7 Matriz de evidências

**Arquivo:** `[Inserir referência.]`

## 14.8 Critérios de qualidade

* pertinência;
* proximidade;
* atualidade;
* integridade;
* rastreabilidade;
* convergência;
* possibilidade de verificação.

---

# 15. Participantes e fontes humanas

| ID      | Função ou relação | Motivo da participação | Método     | Limitação |
| ------- | ----------------- | ---------------------- | ---------- | --------- |
| ENT-001 |                   |                        | Entrevista |           |
| ENT-002 |                   |                        | Entrevista |           |

## Perspectivas não representadas

* `[Pessoa, função ou grupo]`

## Efeito da ausência

`[Como essa ausência limita o relatório?]`

## Cuidados de confidencialidade

`[Preencher.]`

---

# 16. Documentos analisados

| ID      | Documento | Data ou versão | Finalidade | Utilidade diagnóstica | Limitação |
| ------- | --------- | -------------- | ---------- | --------------------- | --------- |
| DOC-001 |           |                |            |                       |           |
| DOC-002 |           |                |            |                       |           |

## Situação geral do acervo

`[Preencher.]`

## Documentos ausentes relevantes

* `[Documento 1]`
* `[Documento 2]`

## Contradições documentais

* `[Contradição 1]`
* `[Contradição 2]`

---

# 17. Observações realizadas

| ID      | Processo ou situação | Data | Duração | Tipo | Limitação |
| ------- | -------------------- | ---- | ------- | ---- | --------- |
| OBS-001 |                      |      |         |      |           |
| OBS-002 |                      |      |         |      |           |

## Representatividade

`[Explicar até que ponto as observações representam a operação.]`

## Interferência da observadora

`[Preencher.]`

## Aspectos especialmente visíveis

* `[Aspecto 1]`
* `[Aspecto 2]`

---

# 18. Dados e indicadores

| ID      | Dado ou indicador | Definição | Período | Fonte | Qualidade | Limitação |
| ------- | ----------------- | --------- | ------- | ----- | --------- | --------- |
| DAD-001 |                   |           |         |       |           |           |
| DAD-002 |                   |           |         |       |           |           |

## Qualidade geral dos dados

`[Preencher.]`

## Problemas identificados

* dados ausentes;
* definições inconsistentes;
* períodos incompletos;
* duplicações;
* alterações de método;
* baixa rastreabilidade;
* outro: `[Preencher]`.

## O que os dados não permitem concluir

`[Preencher.]`

---

# 19. Participação da inteligência artificial

## Sistemas ou agentes utilizados

| Sistema ou agente | Função | Etapa | Dados fornecidos | Responsável pela revisão |
| ----------------- | ------ | ----- | ---------------- | ------------------------ |
|                   |        |       |                  |                          |

## Funções desempenhadas

* [ ] Preparação de instrumentos
* [ ] Transcrição
* [ ] Organização de notas
* [ ] Classificação inicial
* [ ] Comparação documental
* [ ] Identificação de padrões
* [ ] Formulação de hipóteses alternativas
* [ ] Revisão de completude
* [ ] Apoio à síntese
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## Medidas de proteção

* [ ] Minimização
* [ ] Anonimização
* [ ] Pseudonimização
* [ ] Redução de contexto
* [ ] Ambiente autorizado
* [ ] Revisão antes do envio
* [ ] Restrição de dados sensíveis
* [ ] Outra: `[Preencher]`

## Verificação humana

`[Descrever como as saídas foram verificadas.]`

## Limitações ou erros identificados

`[Preencher.]`

## Atividades mantidas exclusivamente humanas

* definição do escopo;
* interpretação contextual;
* julgamento ético;
* aprovação dos achados;
* comunicação de temas sensíveis;
* responsabilidade final.

---

# 20. Limitações metodológicas

## 20.1 Limitações de acesso

* `[Limitação 1]`
* `[Limitação 2]`

## 20.2 Limitações temporais

`[Preencher.]`

## 20.3 Limitações das fontes

`[Preencher.]`

## 20.4 Limitações de representatividade

`[Preencher.]`

## 20.5 Limitações dos dados

`[Preencher.]`

## 20.6 Limitações de especialidade

`[Preencher.]`

## 20.7 Lacunas aceitas

| Lacuna | Motivo da aceitação | Impacto | Efeito sobre a confiança |
| ------ | ------------------- | ------- | ------------------------ |
|        |                     |         |                          |

## 20.8 Efeito geral sobre as conclusões

`[Preencher.]`

---

# 21. Descrição da situação atual

Esta seção deve apresentar a realidade observada antes da interpretação dos achados.

## 21.1 Funcionamento geral

`[Descrever o sistema atual.]`

## 21.2 Fluxo principal

1. `[Etapa 1]`
2. `[Etapa 2]`
3. `[Etapa 3]`
4. `[Etapa 4]`

## 21.3 Pessoas e responsabilidades

`[Preencher.]`

## 21.4 Decisões

`[Preencher.]`

## 21.5 Informação e conhecimento

`[Preencher.]`

## 21.6 Ferramentas e tecnologia

`[Preencher.]`

## 21.7 Relação com clientes ou públicos

`[Preencher.]`

## 21.8 Resultados atuais

`[Preencher.]`

## 21.9 Diferenças entre realidade declarada e praticada

| Elemento | Declarado ou prescrito | Praticado | Implicação |
| -------- | ---------------------- | --------- | ---------- |
|          |                        |           |            |
|          |                        |           |            |

---

# 22. Capacidades existentes

As capacidades devem ser apresentadas como condições concretas que permitem à organização realizar algo de forma consistente.

## Quadro geral

| ID      | Capacidade | Evidências | Condições de sustentação | Importância |
| ------- | ---------- | ---------- | ------------------------ | ----------- |
| ACH-001 |            |            |                          |             |
| ACH-002 |            |            |                          |             |

---

## `ACH-NNN — [Título da capacidade]`

### Descrição

`[O que a organização consegue realizar?]`

### Evidências

* `EVD-___`
* `EVD-___`

### Condições que sustentam a capacidade

* `[Condição 1]`
* `[Condição 2]`

### Valor organizacional

`[Por que essa capacidade é importante?]`

### Vulnerabilidade

`[O que pode comprometer sua continuidade?]`

### Elementos a preservar

* `[Elemento 1]`
* `[Elemento 2]`

### Confiança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa

---

# 23. Achados diagnósticos

Esta seção deve ser duplicada para cada achado relevante.

---

## `ACH-NNN — [Título do achado]`

### Classificação

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

### Questões relacionadas

* `QST-___`
* `QST-___`

### Hipóteses relacionadas

* `HIP-___`
* `HIP-___`

### Evidências relacionadas

* `EVD-___`
* `EVD-___`
* `EVD-___`

### Evidências divergentes

* `EVD-___`
* `[Nenhuma identificada ou preencher.]`

### Interpretação

`[Como o conjunto das evidências foi compreendido?]`

### Grau de confiança

* [ ] Alta
* [ ] Moderada
* [ ] Baixa
* [ ] Inconclusiva

### Justificativa

`[Preencher.]`

### Limites

`[O que o achado não permite afirmar?]`

### Implicação

`[Por que o achado importa?]`

### Relação com outros achados

* `ACH-___`
* `ACH-___`

### Prioridade

* [ ] Imediata
* [ ] Alta
* [ ] Média
* [ ] Baixa

### Encaminhamento

* [ ] Preservar
* [ ] Corrigir
* [ ] Desenvolver
* [ ] Investigar
* [ ] Monitorar
* [ ] Interromper
* [ ] Encaminhar para especialista
* [ ] Não intervir neste momento

### Requisito decorrente

`[Que condição a arquitetura futura deverá atender?]`

---

# 24. Quadro consolidado dos achados

| ID      | Achado | Tipo | Confiança | Impacto | Prioridade | Encaminhamento |
| ------- | ------ | ---- | --------- | ------- | ---------- | -------------- |
| ACH-001 |        |      |           |         |            |                |
| ACH-002 |        |      |           |         |            |                |
| ACH-003 |        |      |           |         |            |                |

---

# 25. Relações sistêmicas

O relatório deve explicar como os achados se relacionam.

## 25.1 Relação central

`[Descrever o padrão organizacional principal.]`

## 25.2 Cadeia causal ou contributiva

```text
[Condição estrutural]
        ↓
[Fator contribuinte]
        ↓
[Problema]
        ↓
[Sintoma]
        ↓
[Consequência]
```

## 25.3 Achados estruturais

* `ACH-___ — [Título]`
* `ACH-___ — [Título]`

## 25.4 Achados derivados

* `ACH-___ — [Título]`
* `ACH-___ — [Título]`

## 25.5 Ciclos de reforço

`[Descrever situações em que um problema amplia outro e retorna ao primeiro.]`

## 25.6 Dependências

| Elemento | Depende de | Efeito |
| -------- | ---------- | ------ |
|          |            |        |
|          |            |        |

## 25.7 Possíveis efeitos não intencionais

`[Que problema pode surgir se apenas um sintoma for corrigido?]`

---

# 26. Sintomas, problemas e causas prováveis

| Sintoma | Problema formulado | Causa ou fator provável | Evidências | Confiança |
| ------- | ------------------ | ----------------------- | ---------- | --------- |
|         |                    |                         |            |           |
|         |                    |                         |            |           |

## Causas imediatas

* `[Causa 1]`
* `[Causa 2]`

## Fatores contribuintes

* `[Fator 1]`
* `[Fator 2]`

## Condições estruturais

* `[Condição 1]`
* `[Condição 2]`

## Explicações alternativas

* `[Explicação 1]`
* `[Explicação 2]`

## Limite causal

`[Explicar onde existem apenas associação, compatibilidade ou hipótese.]`

---

# 27. Contradições

| ID      | Contradição | Evidências | Interpretação | Impacto | Encaminhamento |
| ------- | ----------- | ---------- | ------------- | ------- | -------------- |
| CTR-001 |             |            |               |         |                |
| CTR-002 |             |            |               |         |                |

## Contradição principal

`[Descrever.]`

## Função possível da contradição

`[Que necessidade, transição ou conflito ela pode expressar?]`

## Condição para tratamento

`[Preencher.]`

---

# 28. Riscos

| ID      | Risco | Categoria | Probabilidade | Impacto | Exposição | Evidência | Encaminhamento |
| ------- | ----- | --------- | ------------- | ------- | --------- | --------- | -------------- |
| RSC-001 |       |           |               |         |           |           |                |
| RSC-002 |       |           |               |         |           |           |                |

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
* relacionamento.

## Riscos imediatos

* `[Risco 1]`
* `[Risco 2]`

## Riscos a monitorar

* `[Risco 1]`
* `[Risco 2]`

## Riscos aceitos

| Risco | Justificativa | Responsável | Condição de revisão |
| ----- | ------------- | ----------- | ------------------- |
|       |               |             |                     |

---

# 29. Restrições

| Restrição | Tipo       | Natureza                | Efeito atual | Implicação para a arquitetura |
| --------- | ---------- | ----------------------- | ------------ | ----------------------------- |
|           | Financeira | Temporária / estrutural |              |                               |
|           | Humana     |                         |              |                               |
|           | Técnica    |                         |              |                               |

## Restrições que precisam ser respeitadas

* `[Restrição 1]`
* `[Restrição 2]`

## Restrições que podem ser reduzidas

* `[Restrição 1]`
* `[Restrição 2]`

## Restrições que não devem ser tratadas como falha

* `[Restrição 1]`

---

# 30. Oportunidades

| ID      | Oportunidade | Evidência | Capacidade relacionada | Condição necessária | Risco | Prioridade |
| ------- | ------------ | --------- | ---------------------- | ------------------- | ----- | ---------- |
| OPR-001 |              |           |                        |                     |       |            |
| OPR-002 |              |           |                        |                     |       |            |

## Oportunidades imediatas

* `[Oportunidade 1]`
* `[Oportunidade 2]`

## Oportunidades futuras

* `[Oportunidade 1]`
* `[Oportunidade 2]`

## Oportunidades que ainda exigem investigação

* `[Oportunidade 1]`

---

# 31. Maturidade organizacional

Esta seção deve ser utilizada apenas quando houver critérios explícitos e evidências suficientes.

## Dimensões

| Dimensão     | Nível atual | Critério | Evidências | Confiança |
| ------------ | ----------- | -------- | ---------- | --------- |
| Estratégia   |             |          |            |           |
| Processos    |             |          |            |           |
| Conhecimento |             |          |            |           |
| Tecnologia   |             |          |            |           |
| IA           |             |          |            |           |
| Governança   |             |          |            |           |

## Escala utilizada

`[Descrever os níveis.]`

## Interpretação

`[Que nível de complexidade a organização consegue sustentar?]`

## Capacidade para mudança

`[Preencher.]`

## Condições para o próximo nível

* `[Condição 1]`
* `[Condição 2]`

## Limite

A maturidade descreve a capacidade atual.

Ela não deve ser utilizada como julgamento moral ou comparação descontextualizada.

---

# 32. Hipóteses

## Hipóteses sustentadas

| ID      | Hipótese | Evidências | Confiança | Implicação |
| ------- | -------- | ---------- | --------- | ---------- |
| HIP-001 |          |            |           |            |

## Hipóteses parcialmente sustentadas

| ID      | Parte sustentada | Parte não sustentada | Questão remanescente |
| ------- | ---------------- | -------------------- | -------------------- |
| HIP-002 |                  |                      |                      |

## Hipóteses rejeitadas

| ID      | Hipótese | Evidência contrária | Aprendizado |
| ------- | -------- | ------------------- | ----------- |
| HIP-003 |          |                     |             |

## Hipóteses inconclusivas

| ID      | Hipótese | Lacuna | Encaminhamento |
| ------- | -------- | ------ | -------------- |
| HIP-004 |          |        |                |

---

# 33. Lacunas e questões abertas

## Lacunas críticas

| ID      | Lacuna | Impacto | Encaminhamento |
| ------- | ------ | ------- | -------------- |
| LAC-001 |        |         |                |

## Lacunas relevantes

| ID      | Lacuna | Efeito sobre a confiança | Encaminhamento |
| ------- | ------ | ------------------------ | -------------- |
| LAC-002 |        |                          |                |

## Lacunas aceitas

| ID      | Lacuna | Justificativa | Responsável |
| ------- | ------ | ------------- | ----------- |
| LAC-003 |        |               |             |

## Questões abertas

1. `[Questão 1]`
2. `[Questão 2]`
3. `[Questão 3]`

---

# 34. Priorização

## Critérios utilizados

* impacto;
* urgência;
* risco;
* dependências;
* esforço;
* capacidade;
* reversibilidade;
* valor estratégico;
* efeito sobre autonomia;
* prontidão.

## Quadro de priorização

| Ordem | Achado  | Motivo | Dependência | Encaminhamento |
| ----- | ------- | ------ | ----------- | -------------- |
| 1     | ACH-___ |        |             |                |
| 2     | ACH-___ |        |             |                |
| 3     | ACH-___ |        |             |                |

## Preservar

* `[Capacidade ou prática]`

## Corrigir

* `[Problema]`

## Desenvolver

* `[Capacidade]`

## Investigar

* `[Questão]`

## Monitorar

* `[Risco]`

## Interromper

* `[Prática]`

---

# 35. Requisitos para a arquitetura

Os requisitos devem derivar diretamente dos achados.

| ID      | Requisito | Tipo        | Achado de origem | Critério de atendimento | Prioridade |
| ------- | --------- | ----------- | ---------------- | ----------------------- | ---------- |
| REQ-001 |           | Funcional   | ACH-___          |                         |            |
| REQ-002 |           | Operacional | ACH-___          |                         |            |
| REQ-003 |           | Humano      | ACH-___          |                         |            |

## Tipos

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

## Critérios gerais

A arquitetura futura deverá:

* preservar capacidades existentes;
* respeitar restrições reais;
* reduzir dependências críticas;
* ser proporcional à maturidade;
* manter responsabilidade humana;
* proteger dados;
* permitir aprendizagem;
* produzir evidências de funcionamento;
* ser revisável;
* não exigir manutenção superior à capacidade disponível.

---

# 36. Alternativas ainda abertas

O diagnóstico não deve escolher prematuramente a solução final.

## Alternativas identificadas

| Alternativa | Problema que poderia atender | Condições necessárias | Questões ainda abertas |
| ----------- | ---------------------------- | --------------------- | ---------------------- |
|             |                              |                       |                        |
|             |                              |                       |                        |

## Alternativa de não intervenção

`[Descrever quando pertinente.]`

## Alternativas descartadas nesta etapa

| Alternativa | Motivo |
| ----------- | ------ |
|             |        |

A exclusão definitiva de uma alternativa relevante deve ser registrada em decisão apropriada.

---

# 37. Elementos não definidos pelo diagnóstico

Permanecem para o Módulo 3 ou para decisão posterior:

* ferramenta específica;
* fornecedor;
* desenho final do processo;
* arquitetura completa;
* automação definitiva;
* distribuição final de responsabilidades;
* investimento total;
* cronograma de implantação;
* modelo final de governança.

## Exceções

`[Registrar elementos que precisaram ser definidos durante o diagnóstico.]`

---

# 38. Validação

## 38.1 Validação interna

**Responsável:** `[Nome]`
**Data:** `[DD/MM/AAAA]`

### Verificações

* [ ] aderência ao escopo;
* [ ] rastreabilidade;
* [ ] qualidade das evidências;
* [ ] graus de confiança;
* [ ] divergências;
* [ ] limitações;
* [ ] linguagem;
* [ ] proteção de dados;
* [ ] participação da IA;
* [ ] separação entre achados e recomendações.

---

## 38.2 Validação factual

| Pessoa | Elementos validados | Data | Resultado |
| ------ | ------------------- | ---- | --------- |
|        |                     |      |           |

## Correções factuais

`[Preencher.]`

---

## 38.3 Validação interpretativa

| Pessoa ou grupo | Temas discutidos | Resultado |
| --------------- | ---------------- | --------- |
|                 |                  |           |

## Novas evidências apresentadas

* `EVD-___`
* `[Nenhuma ou preencher.]`

## Achados reformulados

* `ACH-___ — [Alteração]`

---

## 38.4 Divergências

| Tema | Interpretação do relatório | Perspectiva divergente | Evidências | Efeito |
| ---- | -------------------------- | ---------------------- | ---------- | ------ |
|      |                            |                        |            |        |

## Resultado geral

* [ ] Validado
* [ ] Validado com ajustes
* [ ] Validado com divergências
* [ ] Parcialmente validado
* [ ] Requer investigação adicional
* [ ] Não validado

---

# 39. Devolutiva

## Data

`[DD/MM/AAAA]`

## Participantes

* `[Nome ou função]`

## Formato

* [ ] Reunião
* [ ] Oficina
* [ ] Apresentação
* [ ] Documento comentado
* [ ] Sessão individual
* [ ] Outro: `[Preencher]`

## Materiais apresentados

* `[Material 1]`
* `[Material 2]`

## Questões levantadas

* `[Questão 1]`
* `[Questão 2]`

## Decisões decorrentes

* `[Decisão 1]`
* `[Decisão 2]`

## Próximos passos acordados

| Ação | Responsável | Prazo |
| ---- | ----------- | ----- |
|      |             |       |
|      |             |       |

---

# 40. Encaminhamento

## Resultado recomendado

* [ ] Prosseguir para o Módulo 3
* [ ] Realizar investigação complementar
* [ ] Realizar experimento controlado
* [ ] Abrir decisão específica
* [ ] Encaminhar para especialista
* [ ] Monitorar
* [ ] Adiar
* [ ] Não intervir
* [ ] Suspender
* [ ] Encerrar

## Fundamentação

`[Preencher.]`

## Condições para continuidade

* `[Condição 1]`
* `[Condição 2]`
* `[Condição 3]`

## Responsável pela decisão seguinte

`[Nome e função]`

## Documento seguinte

* [ ] `transicao-para-arquitetura.md`
* [ ] Registro de decisão
* [ ] Plano de experimentação
* [ ] Novo diagnóstico
* [ ] Documento de especialista
* [ ] Outro: `[Preencher]`

---

# 41. Aprendizagem metodológica

## O que funcionou bem

* `[Elemento 1]`
* `[Elemento 2]`

## Perguntas mais produtivas

* `[Pergunta 1]`
* `[Pergunta 2]`

## Fontes mais úteis

* `[Fonte 1]`
* `[Fonte 2]`

## Ferramentas que produziram valor

* `[Ferramenta 1]`
* `[Ferramenta 2]`

## Ferramentas que produziram pouco valor

* `[Ferramenta 1]`

## Hipóteses equivocadas

* `[Hipótese e aprendizado]`

## Vieses percebidos

* `[Viés 1]`
* `[Viés 2]`

## Contribuição da IA

`[Preencher.]`

## Limitações do método

`[Preencher.]`

## Alterações recomendadas no Sistema Operacional

* `[Alteração 1]`
* `[Alteração 2]`

---

# 42. Conclusão

A conclusão deve responder diretamente à questão diagnóstica.

## O que está acontecendo?

`[Preencher.]`

## Como essa situação é produzida?

`[Preencher.]`

## O que já funciona?

`[Preencher.]`

## O que limita a organização?

`[Preencher.]`

## Por que isso importa?

`[Preencher.]`

## O que deve ser preservado?

`[Preencher.]`

## O que precisa ser tratado primeiro?

`[Preencher.]`

## O que ainda permanece desconhecido?

`[Preencher.]`

## Que condições devem orientar a próxima etapa?

`[Preencher.]`

---

# 43. Critérios de conclusão do relatório

O relatório pode ser considerado concluído quando:

* [ ] identifica o diagnóstico e sua finalidade;
* [ ] apresenta contexto suficiente;
* [ ] explicita a decisão apoiada;
* [ ] registra a questão e o escopo;
* [ ] descreve o método;
* [ ] informa as fontes utilizadas;
* [ ] registra limitações;
* [ ] apresenta a situação atual;
* [ ] reconhece capacidades;
* [ ] apresenta achados rastreáveis;
* [ ] informa graus de confiança;
* [ ] preserva divergências;
* [ ] diferencia sintomas, problemas e causas;
* [ ] registra riscos e restrições;
* [ ] explicita lacunas;
* [ ] apresenta prioridades;
* [ ] deriva requisitos dos achados;
* [ ] registra a participação da IA;
* [ ] protege dados sensíveis;
* [ ] registra a validação;
* [ ] define encaminhamento;
* [ ] incorpora aprendizagem metodológica;
* [ ] foi revisado;
* [ ] foi entregue ou validado no grau possível.

---

# 44. Aprovação

## Elaborado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Revisado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Aprovado pelo Estúdio

**Nome:** `[Preencher]`
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

# 45. Histórico de versões

| Data | Versão | Alteração            | Motivo | Responsável | Aprovador |
| ---- | ------ | -------------------- | ------ | ----------- | --------- |
|      | 0.1    | Criação do relatório |        |             |           |
|      |        |                      |        |             |           |

---

# 46. Referências internas

* `briefing.md`;
* `plano-de-investigacao.md`;
* `matriz-de-evidencias.md`;
* `sintese-diagnostica.md`;
* `registro-de-validacao.md`;
* `transicao-para-arquitetura.md`;
* `[Outros documentos.]`

---

# 47. Anexos

## Anexo A — Matriz de evidências

`[Inserir referência.]`

## Anexo B — Registro de fontes

`[Inserir referência.]`

## Anexo C — Mapas

* `[Mapa 1]`
* `[Mapa 2]`

## Anexo D — Avaliação de maturidade

`[Inserir referência.]`

## Anexo E — Dados e indicadores

`[Inserir referência.]`

## Anexo F — Registro de validação

`[Inserir referência.]`

## Anexo G — Outros materiais

* `[Material 1]`
* `[Material 2]`

---

# 48. Versão reduzida para diagnóstico focal

## Identificação

* **Diagnóstico:** `DIA-AAAA-NNN`
* **Organização:** `[Nome]`
* **Questão:** `[Preencher]`
* **Responsável:** `[Nome]`
* **Data:** `[DD/MM/AAAA]`

## Situação

`[Descrição breve.]`

## Escopo

`[Preencher.]`

## Método

`[Fontes e atividades realizadas.]`

## Capacidades

* `[Capacidade 1]`
* `[Capacidade 2]`

## Achados

| ID      | Achado | Evidências | Confiança | Implicação |
| ------- | ------ | ---------- | --------- | ---------- |
| ACH-001 |        |            |           |            |
| ACH-002 |        |            |           |            |

## Relação central

`[Preencher.]`

## Riscos e restrições

* `[Risco ou restrição 1]`
* `[Risco ou restrição 2]`

## Prioridade

`[Preencher.]`

## Requisitos

* `[Requisito 1]`
* `[Requisito 2]`

## Limitações

`[Preencher.]`

## Encaminhamento

`[Preencher.]`

## Validação

`[Data, participantes e resultado.]`

---

# 49. Princípio de encerramento

O Relatório de Diagnóstico Organizacional deve tornar visível não apenas o que o Estúdio concluiu, mas o caminho pelo qual essa conclusão foi construída.

Sua qualidade não depende do volume de páginas.

Depende da capacidade de:

* representar o contexto;
* distinguir fatos e interpretações;
* relacionar achados a evidências;
* reconhecer capacidades;
* preservar incertezas;
* tornar divergências visíveis;
* comunicar limites;
* apoiar decisões;
* preparar uma arquitetura proporcional.

O relatório não deve utilizar a complexidade da organização para produzir uma documentação inacessível.

Ele deve transformar complexidade em compreensão estruturada, sem reduzir a realidade além do que as evidências permitem.

Com este template, o diagnóstico passa a possuir três níveis de comunicação claramente distintos: **matriz para rastreabilidade, síntese para compreensão essencial e relatório para documentação completa**. O próximo template estrutural é o `transicao-para-arquitetura.md`, que encerrará o trabalho do Módulo 2 e transferirá requisitos validados ao Módulo 3.
