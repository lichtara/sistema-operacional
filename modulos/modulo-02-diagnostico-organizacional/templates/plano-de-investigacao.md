# Plano de Investigação

```yaml
id_diagnostico: DIA-AAAA-NNN
titulo: "[Nome do diagnóstico]"
organizacao:
versao: 0.1
data_criacao: AAAA-MM-DD
data_aprovacao:
estado: em_elaboracao
tipo_diagnostico: focal | funcional | sistemico
responsavel_diagnostico:
responsavel_cliente:
data_inicio_prevista:
data_conclusao_prevista:
nivel_sensibilidade: publica | interna | confidencial | sensivel
briefing_relacionado: briefing.md
decisao_relacionada:
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional
**Função:** Planejamento da investigação diagnóstica
**Documento de referência:** `../protocolo-de-diagnostico.md`
**Documento de entrada:** `briefing-de-diagnostico.md`

---

# 1. Finalidade

O Plano de Investigação define como o diagnóstico será conduzido.

Ele transforma:

* a demanda qualificada;
* a questão diagnóstica;
* o escopo aprovado;
* as hipóteses preliminares;
* os resultados esperados;

em um conjunto organizado de:

* perguntas de investigação;
* fontes;
* métodos;
* ferramentas;
* atividades;
* responsabilidades;
* evidências esperadas;
* critérios de qualidade;
* prazos;
* cuidados éticos;
* mecanismos de validação.

O plano deve permitir que qualquer pessoa autorizada compreenda:

1. o que será investigado;
2. por que será investigado;
3. como as evidências serão obtidas;
4. quem participará;
5. quando cada atividade ocorrerá;
6. como as informações serão protegidas;
7. como os achados serão validados;
8. em que condições o diagnóstico poderá ser concluído.

---

# 2. Instruções de uso

Este documento deve ser criado após a aprovação do briefing.

O template-mestre não deve ser preenchido diretamente.

O plano deve ser proporcional ao diagnóstico.

## Diagnóstico focal

Pode utilizar uma versão reduzida, concentrada em:

* questão;
* hipóteses;
* fontes;
* métodos;
* cronograma;
* evidências;
* validação.

## Diagnóstico funcional

Deve incluir:

* perguntas secundárias;
* múltiplas fontes;
* ferramentas combinadas;
* matriz de evidências;
* análise de capacidades;
* critérios de maturidade, quando aplicável.

## Diagnóstico sistêmico

Deve apresentar:

* frentes de investigação;
* múltiplas perspectivas;
* triangulação;
* controle de dados;
* dependências;
* pontos de decisão;
* plano de validação em etapas.

O plano pode ser atualizado durante a investigação, desde que mudanças relevantes sejam registradas e aprovadas.

---

# 3. Identificação

| Campo                            | Registro                          |
| -------------------------------- | --------------------------------- |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                    |
| **Título**                       | `[Nome do diagnóstico]`           |
| **Organização**                  | `[Nome]`                          |
| **Área ou processo**             | `[Quando aplicável]`              |
| **Tipo de diagnóstico**          | `[Focal, funcional ou sistêmico]` |
| **Responsável pelo diagnóstico** | `[Nome]`                          |
| **Responsável do cliente**       | `[Nome e função]`                 |
| **Data de elaboração**           | `[DD/MM/AAAA]`                    |
| **Início previsto**              | `[DD/MM/AAAA]`                    |
| **Conclusão prevista**           | `[DD/MM/AAAA]`                    |
| **Versão do plano**              | `[0.1]`                           |
| **Estado**                       | `[Selecionar abaixo]`             |

## Estado do plano

* [ ] Em elaboração
* [ ] Em revisão
* [ ] Aguardando aprovação
* [ ] Aprovado
* [ ] Em execução
* [ ] Em atualização
* [ ] Suspenso
* [ ] Substituído
* [ ] Encerrado

---

# 4. Documentos de entrada

## Briefing aprovado

**Arquivo:** `[Inserir link]`

**Versão:** `[Preencher]`

**Data de aprovação:** `[DD/MM/AAAA]`

## Decisão relacionada

**ID:** `[DEC-AAAA-NNN ou não aplicável]`

**Arquivo:** `[Inserir link]`

## Outros documentos de referência

* `[Documento 1]`
* `[Documento 2]`
* `[Documento 3]`

## Alterações em relação ao briefing

O plano alterou algum elemento aprovado no briefing?

* [ ] Não
* [ ] Sim

### Alterações

| Elemento | Briefing aprovado | Alteração proposta | Motivo | Aprovação necessária |
| -------- | ----------------- | ------------------ | ------ | -------------------- |
|          |                   |                    |        |                      |

---

# 5. Síntese da investigação

## Situação

`[Descreva brevemente a condição que originou o diagnóstico.]`

## Problema preliminar

`[Reproduzir ou atualizar a formulação aprovada.]`

## Questão diagnóstica central

`[Pergunta principal.]`

## Decisão que será apoiada

`[Que escolha o diagnóstico deverá tornar possível?]`

## Resultado esperado

`[O que precisa estar suficientemente compreendido ao final?]`

## Tipo de diagnóstico

* [ ] Focal
* [ ] Funcional
* [ ] Sistêmico

## Justificativa da classificação

`[Preencher]`

---

# 6. Objetivos da investigação

## Objetivo geral

`[Descrever a finalidade principal da investigação.]`

### Estrutura recomendada

> Compreender `[fenômeno ou capacidade]` no contexto de `[organização, área ou processo]`, identificando `[elementos principais]` para apoiar `[decisão ou etapa posterior]`.

## Objetivos específicos

1. `[Objetivo específico 1]`
2. `[Objetivo específico 2]`
3. `[Objetivo específico 3]`
4. `[Objetivo específico 4]`
5. `[Objetivo específico adicional, quando necessário]`

## O que não constitui objetivo

* `[Item 1]`
* `[Item 2]`

---

# 7. Questões de investigação

## 7.1 Questão central

`[Inserir a questão diagnóstica principal.]`

## 7.2 Questões secundárias

| ID      | Questão | Finalidade | Decisão ou achado que poderá apoiar |
| ------- | ------- | ---------- | ----------------------------------- |
| QST-001 |         |            |                                     |
| QST-002 |         |            |                                     |
| QST-003 |         |            |                                     |
| QST-004 |         |            |                                     |

## 7.3 Subquestões

Quando uma questão exigir decomposição:

| Questão principal | Subquestão | Evidência necessária |
| ----------------- | ---------- | -------------------- |
| QST-001           |            |                      |
| QST-001           |            |                      |
| QST-002           |            |                      |

## 7.4 Prioridade das questões

* **Essencial:** precisa ser respondida para que o diagnóstico cumpra sua finalidade.
* **Relevante:** amplia significativamente a compreensão.
* **Complementar:** oferece contexto, mas não impede a conclusão.

| ID      | Prioridade   | Justificativa |
| ------- | ------------ | ------------- |
| QST-001 | Essencial    |               |
| QST-002 | Relevante    |               |
| QST-003 | Complementar |               |

---

# 8. Hipóteses de investigação

As hipóteses orientam a busca, mas não determinam sua conclusão.

| ID      | Hipótese | Questões relacionadas | Evidências favoráveis esperadas | Evidências contrárias esperadas | Confiança inicial |
| ------- | -------- | --------------------- | ------------------------------- | ------------------------------- | ----------------- |
| HIP-001 |          |                       |                                 |                                 | Baixa             |
| HIP-002 |          |                       |                                 |                                 | Baixa             |
| HIP-003 |          |                       |                                 |                                 | Baixa             |

## Hipóteses concorrentes

Que outras explicações poderiam produzir os mesmos sintomas?

* `[Hipótese concorrente 1]`
* `[Hipótese concorrente 2]`
* `[Hipótese concorrente 3]`

## Condições de refutação

O que demonstraria que as hipóteses principais estão incorretas?

`[Preencher]`

## Risco de confirmação prematura

`[Descreva fatores que podem induzir a equipe a buscar apenas evidências favoráveis.]`

## Proteções metodológicas

* [ ] Buscar fontes divergentes
* [ ] Formular perguntas não indutivas
* [ ] Comparar relato e prática
* [ ] Examinar períodos distintos
* [ ] Solicitar revisão externa
* [ ] Utilizar hipóteses concorrentes
* [ ] Outra: `[Preencher]`

---

# 9. Escopo operacional

## 9.1 Incluído

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

### Documentos

* `[Categoria documental 1]`
* `[Categoria documental 2]`

### Dados

* `[Conjunto de dados ou indicador 1]`
* `[Conjunto de dados ou indicador 2]`

### Período

`[Intervalo temporal analisado.]`

### Canais, unidades ou públicos

`[Preencher]`

---

## 9.2 Excluído

* `[Elemento excluído 1]`
* `[Elemento excluído 2]`

## 9.3 Limites da investigação

`[Descrever o que o diagnóstico não poderá afirmar.]`

## 9.4 Questões futuras

| Questão identificada | Motivo de exclusão | Encaminhamento                    |
| -------------------- | ------------------ | --------------------------------- |
|                      |                    | Registrar para diagnóstico futuro |
|                      |                    |                                   |

---

# 10. Frentes de investigação

Diagnósticos funcionais ou sistêmicos podem ser divididos em frentes.

| ID      | Frente                    | Objetivo | Questões relacionadas | Responsável |
| ------- | ------------------------- | -------- | --------------------- | ----------- |
| FRT-001 | Identidade e direção      |          |                       |             |
| FRT-002 | Clientes e valor          |          |                       |             |
| FRT-003 | Processos e operação      |          |                       |             |
| FRT-004 | Conhecimento e informação |          |                       |             |
| FRT-005 | Tecnologia e IA           |          |                       |             |

Devem ser mantidas apenas as frentes pertinentes ao diagnóstico.

---

# 11. Estratégia de produção de evidências

## 11.1 Princípio

Cada pergunta deve estar vinculada a:

* uma ou mais fontes;
* um método;
* uma evidência esperada;
* um responsável;
* uma forma de validação.

## 11.2 Mapa principal

| Questão | Hipótese | Fonte | Método ou ferramenta | Evidência esperada | Responsável | Validação |
| ------- | -------- | ----- | -------------------- | ------------------ | ----------- | --------- |
| QST-001 | HIP-001  |       |                      |                    |             |           |
| QST-002 | HIP-001  |       |                      |                    |             |           |
| QST-003 | HIP-002  |       |                      |                    |             |           |

## 11.3 Cobertura

Verificar se:

* [ ] toda questão essencial possui ao menos uma fonte;
* [ ] questões de alto impacto possuem fontes múltiplas;
* [ ] relatos relevantes poderão ser confrontados;
* [ ] processos serão observados quando necessário;
* [ ] documentos e dados poderão ser verificados;
* [ ] hipóteses concorrentes poderão ser examinadas.

---

# 12. Inventário de fontes

## 12.1 Pessoas

| ID      | Pessoa ou função | Relação com o fenômeno | Informação esperada | Método     | Sensibilidade |
| ------- | ---------------- | ---------------------- | ------------------- | ---------- | ------------- |
| ENT-001 |                  |                        |                     | Entrevista |               |
| ENT-002 |                  |                        |                     | Entrevista |               |

## 12.2 Documentos

| ID      | Documento ou categoria | Período | Responsável | Finalidade | Estado de acesso |
| ------- | ---------------------- | ------- | ----------- | ---------- | ---------------- |
| DOC-001 |                        |         |             |            | Pendente         |
| DOC-002 |                        |         |             |            | Pendente         |

## 12.3 Sistemas

| ID      | Sistema | Informação necessária | Tipo de acesso | Responsável | Limitação |
| ------- | ------- | --------------------- | -------------- | ----------- | --------- |
| SIS-001 |         |                       |                |             |           |

## 12.4 Dados

| ID      | Conjunto de dados | Período | Campos necessários | Origem | Qualidade inicial |
| ------- | ----------------- | ------- | ------------------ | ------ | ----------------- |
| DAD-001 |                   |         |                    |        | A avaliar         |

## 12.5 Processos a observar

| ID      | Processo | Contexto | Participantes | Duração prevista | Resultado esperado |
| ------- | -------- | -------- | ------------- | ---------------- | ------------------ |
| OBS-001 |          |          |               |                  |                    |

## 12.6 Fontes externas

| ID      | Fonte | Finalidade | Autoridade ou relevância | Forma de verificação |
| ------- | ----- | ---------- | ------------------------ | -------------------- |
| EXT-001 |       |            |                          |                      |

---

# 13. Critérios de seleção das fontes

As fontes foram selecionadas considerando:

* [ ] proximidade com o fenômeno;
* [ ] variedade de perspectivas;
* [ ] possibilidade de verificação;
* [ ] atualidade;
* [ ] relevância para a decisão;
* [ ] acesso proporcional;
* [ ] necessidade de triangulação;
* [ ] sensibilidade;
* [ ] custo e tempo.

## Fontes deliberadamente não utilizadas

| Fonte possível | Motivo da exclusão | Risco decorrente |
| -------------- | ------------------ | ---------------- |
|                |                    |                  |
|                |                    |                  |

---

# 14. Ferramentas selecionadas

| Ferramenta                | Pergunta que ajudará a responder | Motivo da escolha | Produto esperado |
| ------------------------- | -------------------------------- | ----------------- | ---------------- |
| Entrevista                |                                  |                   |                  |
| Observação                |                                  |                   |                  |
| Análise documental        |                                  |                   |                  |
| SWOT                      |                                  |                   |                  |
| Canvas                    |                                  |                   |                  |
| Jornada do Cliente        |                                  |                   |                  |
| Mapa de Processos         |                                  |                   |                  |
| Maturidade Digital        |                                  |                   |                  |
| Maturidade Organizacional |                                  |                   |                  |

Devem permanecer somente as ferramentas efetivamente utilizadas.

## Ferramentas consideradas e descartadas

| Ferramenta | Motivo de não utilização |
| ---------- | ------------------------ |
|            |                          |
|            |                          |

## Teste de proporcionalidade

* [ ] Cada ferramenta responde a uma pergunta.
* [ ] Nenhuma ferramenta foi incluída apenas por tradição.
* [ ] Não existem atividades redundantes.
* [ ] A carga de participação é compatível com o contexto.
* [ ] Os produtos serão utilizados na análise ou decisão.

---

# 15. Plano de entrevistas

## 15.1 Objetivo

`[Que tipo de compreensão as entrevistas deverão produzir?]`

## 15.2 Participantes

| ID      | Participante | Objetivo específico | Duração | Formato | Data prevista |
| ------- | ------------ | ------------------- | ------- | ------- | ------------- |
| ENT-001 |              |                     |         |         |               |
| ENT-002 |              |                     |         |         |               |

## 15.3 Temas

* `[Tema 1]`
* `[Tema 2]`
* `[Tema 3]`

## 15.4 Roteiro

**Template relacionado:** `roteiro-de-entrevista.md`

## 15.5 Registro

* [ ] Anotações manuais
* [ ] Gravação de áudio
* [ ] Gravação de vídeo
* [ ] Transcrição
* [ ] Síntese validada
* [ ] Outro: `[Preencher]`

## 15.6 Autorizações

* [ ] Participante informado sobre a finalidade
* [ ] Autorização para gravação
* [ ] Autorização para uso de IA na transcrição
* [ ] Regras de confidencialidade comunicadas
* [ ] Possibilidade de correção factual informada

## 15.7 Riscos de condução

* perguntas indutivas;
* diferença hierárquica;
* medo de exposição;
* resposta socialmente desejável;
* conflito;
* memória incompleta.

## Proteções

`[Preencher]`

---

# 16. Plano de observação

## 16.1 Objetivo

`[O que precisa ser compreendido por observação direta?]`

## 16.2 Situações observadas

| ID      | Processo ou situação | Contexto | Duração | Papel da observadora | Data |
| ------- | -------------------- | -------- | ------- | -------------------- | ---- |
| OBS-001 |                      |          |         |                      |      |

## 16.3 Elementos de interesse

* sequência de atividades;
* decisões;
* esperas;
* interrupções;
* transferências;
* retrabalho;
* uso de ferramentas;
* comunicação;
* exceções;
* dependência da memória.

## 16.4 Registro

**Template relacionado:** `ficha-de-observacao.md`

## 16.5 Interferência possível

Como a presença da observadora pode alterar o comportamento?

`[Preencher]`

## 16.6 Medidas de redução

`[Preencher]`

---

# 17. Plano de análise documental

## 17.1 Objetivo

`[Que questões serão examinadas por documentos?]`

## 17.2 Documentos

| ID      | Documento | Versão ou período | Critério de análise | Questão relacionada |
| ------- | --------- | ----------------- | ------------------- | ------------------- |
| DOC-001 |           |                   |                     |                     |
| DOC-002 |           |                   |                     |                     |

## 17.3 Aspectos observados

* autoria;
* versão;
* atualidade;
* finalidade;
* conteúdo;
* consistência;
* uso real;
* relação com outros documentos;
* aderência à prática;
* lacunas;
* duplicações.

## 17.4 Registro

**Template relacionado:** `inventario-documental.md`

---

# 18. Plano de análise de dados

## 18.1 Questões quantitativas

* `[Pergunta 1]`
* `[Pergunta 2]`

## 18.2 Indicadores

| Indicador | Definição | Fonte | Período | Limitação |
| --------- | --------- | ----- | ------- | --------- |
|           |           |       |         |           |
|           |           |       |         |           |

## 18.3 Verificações de qualidade

* [ ] origem conhecida;
* [ ] período adequado;
* [ ] campos completos;
* [ ] definições compreendidas;
* [ ] duplicações verificadas;
* [ ] valores ausentes registrados;
* [ ] alterações de metodologia identificadas;
* [ ] amostra adequada à conclusão.

## 18.4 Limites

`[Descrever o que os dados não permitem concluir.]`

---

# 19. Plano de mapeamento

## Mapas previstos

* [ ] Mapa de processo
* [ ] Jornada do cliente
* [ ] Mapa de responsabilidades
* [ ] Mapa de ferramentas
* [ ] Mapa de informação
* [ ] Mapa de conhecimento
* [ ] Mapa sistêmico
* [ ] Outro: `[Preencher]`

| Mapa | Finalidade | Fontes necessárias | Responsável | Forma de validação |
| ---- | ---------- | ------------------ | ----------- | ------------------ |
|      |            |                    |             |                    |

## Nível de detalhe

* [ ] Visão geral
* [ ] Processo intermediário
* [ ] Atividade detalhada

O nível deve ser suficiente para responder à questão, sem mapear detalhes que não serão utilizados.

---

# 20. Avaliação de maturidade

## Será aplicada?

* [ ] Não
* [ ] Maturidade digital
* [ ] Maturidade organizacional
* [ ] Maturidade para IA
* [ ] Outra: `[Preencher]`

## Finalidade

`[Que decisão ou entendimento essa avaliação apoiará?]`

## Dimensões

| Dimensão | Critério | Evidência necessária | Fonte |
| -------- | -------- | -------------------- | ----- |
|          |          |                      |       |
|          |          |                      |       |

## Regra

A maturidade não deve ser classificada apenas com base em autopercepção ou questionário isolado.

A classificação deverá utilizar:

* critérios explícitos;
* evidências;
* exemplos;
* validação;
* grau de confiança.

---

# 21. Matriz de evidências

## Documento

`matriz-de-evidencias.md`

## Estrutura escolhida

* [ ] Matriz reduzida
* [ ] Matriz completa
* [ ] Matriz dividida por frente
* [ ] Outro formato: `[Preencher]`

## Responsável pela atualização

`[Nome]`

## Frequência

* [ ] Após cada atividade
* [ ] Diariamente durante a coleta
* [ ] Por bloco de investigação
* [ ] Semanalmente
* [ ] Outra: `[Preencher]`

## Identificação

### Evidências

`EVD-NNN`

### Achados

`ACH-NNN`

### Hipóteses

`HIP-NNN`

## Critérios de inclusão

Uma informação será incorporada quando:

* estiver relacionada a uma questão;
* possuir fonte identificável;
* contribuir para hipótese, achado ou contexto;
* puder ser descrita sem misturar interpretação;
* tiver relevância para a finalidade.

---

# 22. Estratégia de triangulação

## Questões que exigem triangulação

| Questão | Fonte 1 | Fonte 2 | Fonte 3 | Motivo |
| ------- | ------- | ------- | ------- | ------ |
| QST-001 |         |         |         |        |
| QST-002 |         |         |         |        |

## Tipos de triangulação

* [ ] Relato e documento
* [ ] Relato e observação
* [ ] Diferentes participantes
* [ ] Diferentes períodos
* [ ] Dados e prática
* [ ] Processo prescrito e praticado
* [ ] Fonte interna e externa
* [ ] Outra: `[Preencher]`

## Divergências previstas

`[Onde é provável encontrar perspectivas distintas?]`

## Tratamento das divergências

`[Como serão registradas, aprofundadas e comunicadas?]`

---

# 23. Participação da inteligência artificial

## 23.1 Sistemas previstos

| Sistema ou agente | Função | Etapa | Dados recebidos | Responsável pela revisão |
| ----------------- | ------ | ----- | --------------- | ------------------------ |
|                   |        |       |                 |                          |

## 23.2 Atividades permitidas

* [ ] Preparação de roteiros
* [ ] Transcrição
* [ ] Organização de notas
* [ ] Classificação inicial
* [ ] Comparação documental
* [ ] Identificação de padrões
* [ ] Identificação de divergências
* [ ] Formulação de hipóteses alternativas
* [ ] Revisão de completude
* [ ] Apoio à síntese
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## 23.3 Atividades proibidas

* inventar evidências;
* preencher lacunas como fatos;
* classificar pessoas psicologicamente;
* atribuir intenção;
* definir culpa;
* aprovar achados;
* tomar decisão final;
* utilizar dados além da finalidade;
* alterar fontes originais;
* apresentar inferência como observação.

## 23.4 Tratamento dos dados

* [ ] Dados não sensíveis
* [ ] Dados anonimizados
* [ ] Dados pseudonimizados
* [ ] Contexto reduzido
* [ ] Ambiente autorizado
* [ ] Uso local ou restrito
* [ ] IA não receberá dados do cliente

## 23.5 Verificação

Toda saída utilizada deverá ser:

* [ ] comparada com a fonte original;
* [ ] revisada por pessoa responsável;
* [ ] classificada como apoio, não como evidência;
* [ ] registrada quando influenciar materialmente o diagnóstico.

## 23.6 Registro de uso

**Arquivo ou seção:** `[Preencher]`

---

# 24. Plano de gestão dos dados

## 24.1 Classificação geral

* [ ] Pública
* [ ] Interna
* [ ] Confidencial
* [ ] Sensível

## 24.2 Ciclo dos dados

| Etapa            | Procedimento | Responsável |
| ---------------- | ------------ | ----------- |
| Solicitação      |              |             |
| Recebimento      |              |             |
| Armazenamento    |              |             |
| Processamento    |              |             |
| Compartilhamento |              |             |
| Arquivamento     |              |             |
| Descarte         |              |             |

## 24.3 Acesso

| Pessoa ou função | Nível de acesso | Justificativa |
| ---------------- | --------------- | ------------- |
|                  |                 |               |

## 24.4 Medidas de proteção

* [ ] controle de acesso;
* [ ] separação de arquivos;
* [ ] anonimização;
* [ ] pseudonimização;
* [ ] minimização;
* [ ] cópia de segurança;
* [ ] restrição de exportação;
* [ ] registro de compartilhamento;
* [ ] descarte seguro;
* [ ] outra: `[Preencher]`.

## 24.5 Retenção

`[Prazo ou condição.]`

## 24.6 Incidente

Em caso de acesso indevido, perda ou exposição:

1. interromper o processamento;
2. preservar evidências do incidente;
3. comunicar a responsável;
4. avaliar impacto;
5. aplicar contenção;
6. informar o cliente quando necessário;
7. registrar o aprendizado.

---

# 25. Plano de trabalho

| ID      | Atividade | Etapa | Responsável | Participantes | Início | Prazo | Dependência | Produto |
| ------- | --------- | ----- | ----------- | ------------- | ------ | ----- | ----------- | ------- |
| ATV-001 |           |       |             |               |        |       |             |         |
| ATV-002 |           |       |             |               |        |       |             |         |
| ATV-003 |           |       |             |               |        |       |             |         |

## Estados

* Não iniciada
* Em preparação
* Em execução
* Aguardando informação
* Em revisão
* Concluída
* Cancelada

---

# 26. Cronograma por marcos

| Marco                 | Produto ou condição              | Data prevista | Responsável | Critério de conclusão |
| --------------------- | -------------------------------- | ------------- | ----------- | --------------------- |
| Plano aprovado        | Plano de investigação autorizado |               |             |                       |
| Coleta iniciada       | Primeira fonte registrada        |               |             |                       |
| Coleta intermediária  | Cobertura inicial das questões   |               |             |                       |
| Coleta concluída      | Fontes essenciais consultadas    |               |             |                       |
| Matriz consolidada    | Evidências organizadas           |               |             |                       |
| Achados preliminares  | Primeira formulação dos achados  |               |             |                       |
| Validação interna     | Revisão metodológica concluída   |               |             |                       |
| Validação com cliente | Aspectos factuais confrontados   |               |             |                       |
| Síntese final         | Documento revisado               |               |             |                       |
| Devolutiva            | Apresentação realizada           |               |             |                       |
| Transição             | Requisitos encaminhados          |               |             |                       |
| Encerramento          | Aprendizado registrado           |               |             |                       |

---

# 27. Papéis e responsabilidades

| Atividade            | Responsável | Aprovador | Consultado | Informado |
| -------------------- | ----------- | --------- | ---------- | --------- |
| Aprovar plano        |             |           |            |           |
| Liberar acessos      |             |           |            |           |
| Conduzir entrevistas |             |           |            |           |
| Realizar observações |             |           |            |           |
| Analisar documentos  |             |           |            |           |
| Atualizar matriz     |             |           |            |           |
| Formular achados     |             |           |            |           |
| Validar síntese      |             |           |            |           |
| Aprovar entrega      |             |           |            |           |
| Encerrar diagnóstico |             |           |            |           |

## Responsável final pelo diagnóstico

`[Nome]`

A responsabilidade final não pode ser atribuída à inteligência artificial.

---

# 28. Carga de participação

O diagnóstico deve respeitar a disponibilidade das pessoas.

| Participante | Atividade  | Quantidade | Duração estimada | Período |
| ------------ | ---------- | ---------- | ---------------- | ------- |
|              | Entrevista |            |                  |         |
|              | Validação  |            |                  |         |
|              | Observação |            |                  |         |

## Risco de sobrecarga

`[Preencher]`

## Medidas de redução

* combinar atividades;
* priorizar fontes essenciais;
* utilizar documentos já existentes;
* reduzir reuniões;
* validar por blocos;
* adequar horários;
* outra: `[Preencher]`.

---

# 29. Comunicação do projeto

## Canal oficial

`[Preencher]`

## Atualizações

| Tipo              | Frequência ou marco | Destinatários | Responsável |
| ----------------- | ------------------- | ------------- | ----------- |
| Progresso         |                     |               |             |
| Risco             | Sob ocorrência      |               |             |
| Mudança de escopo | Antes da execução   |               |             |
| Validação         |                     |               |             |

## Conteúdo das atualizações

* atividades concluídas;
* fontes consultadas;
* pendências;
* riscos;
* mudanças;
* próximos passos.

## Informações que não devem circular em atualizações gerais

`[Preencher]`

---

# 30. Riscos da investigação

| ID      | Risco | Categoria | Probabilidade | Impacto | Prevenção | Resposta | Responsável |
| ------- | ----- | --------- | ------------- | ------- | --------- | -------- | ----------- |
| RSC-001 |       |           |               |         |           |          |             |
| RSC-002 |       |           |               |         |           |          |             |

## Categorias

* escopo;
* prazo;
* acesso;
* qualidade de dados;
* confidencialidade;
* conflito;
* indisponibilidade;
* viés;
* interpretação;
* uso de IA;
* exposição;
* dependência de especialista;
* reputação;
* conformidade.

## Critérios de suspensão

O diagnóstico deverá ser suspenso se:

* `[Condição 1]`
* `[Condição 2]`
* `[Condição 3]`

## Critérios de escalonamento

A situação deverá ser encaminhada ao responsável do cliente quando:

* `[Condição 1]`
* `[Condição 2]`

---

# 31. Controle de vieses

## Vieses relevantes

* [ ] Confirmação
* [ ] Solução preferida
* [ ] Autoridade
* [ ] Fundador
* [ ] Disponibilidade
* [ ] Problema visível
* [ ] Ferramenta
* [ ] Complexidade
* [ ] Simplificação
* [ ] Tecnologia
* [ ] IA
* [ ] Outro: `[Preencher]`

## Proteções planejadas

| Viés | Proteção | Etapa | Responsável |
| ---- | -------- | ----- | ----------- |
|      |          |       |             |

## Pergunta de controle

> Que conclusão pareceria provável para nós antes mesmo da coleta, e como impediremos que ela determine a investigação?

`[Resposta]`

---

# 32. Critérios de qualidade

## 32.1 Coleta

* [ ] As fontes são pertinentes.
* [ ] O contexto será registrado.
* [ ] As perguntas não são excessivamente indutivas.
* [ ] As autorizações estão definidas.
* [ ] A coleta é proporcional.

## 32.2 Evidências

* [ ] A origem será rastreável.
* [ ] A data ou período será registrado.
* [ ] Evidência e interpretação permanecerão separadas.
* [ ] Divergências serão preservadas.
* [ ] Lacunas serão classificadas.

## 32.3 Análise

* [ ] Hipóteses alternativas serão consideradas.
* [ ] Causa e correlação serão diferenciadas.
* [ ] Capacidades serão identificadas.
* [ ] O contexto será considerado.
* [ ] O grau de confiança será registrado.

## 32.4 Síntese

* [ ] Os achados terão evidências relacionadas.
* [ ] Os limites estarão explícitos.
* [ ] A linguagem será proporcional.
* [ ] Recomendações não serão disfarçadas de achados.
* [ ] O cliente poderá reconstruir o raciocínio essencial.

---

# 33. Pontos de controle

## Ponto 1 — Prontidão para coleta

Antes de iniciar:

* [ ] plano aprovado;
* [ ] fontes identificadas;
* [ ] acessos solicitados;
* [ ] instrumentos preparados;
* [ ] tratamento de dados definido;
* [ ] participação da IA autorizada;
* [ ] participantes informados;
* [ ] cronograma confirmado.

## Ponto 2 — Revisão intermediária

Após a coleta inicial:

* [ ] questões essenciais possuem cobertura;
* [ ] hipóteses concorrentes foram consideradas;
* [ ] surgiram novas questões;
* [ ] existem lacunas críticas;
* [ ] o escopo permanece adequado;
* [ ] os riscos permanecem aceitáveis.

## Ponto 3 — Prontidão para síntese

Antes de formular conclusões:

* [ ] evidências estão organizadas;
* [ ] fontes podem ser rastreadas;
* [ ] divergências estão registradas;
* [ ] qualidade foi avaliada;
* [ ] graus de confiança estão definidos;
* [ ] não existem lacunas críticas não tratadas.

## Ponto 4 — Prontidão para validação

* [ ] achados estão estruturados;
* [ ] linguagem foi revisada;
* [ ] dados sensíveis foram protegidos;
* [ ] recomendações estão separadas;
* [ ] limites estão explícitos;
* [ ] participação da IA foi revisada.

---

# 34. Critérios de saturação suficiente

A coleta poderá ser encerrada quando:

* novas fontes repetirem padrões já registrados;
* as questões essenciais possuírem evidência suficiente;
* as hipóteses principais tiverem sido examinadas;
* as divergências relevantes estiverem compreendidas ou registradas;
* as lacunas remanescentes forem conhecidas;
* houver base para a decisão apoiada;
* o valor de novas informações for inferior ao custo de obtê-las.

## Critérios específicos

`[Preencher]`

## Quem decide encerrar a coleta?

`[Nome]`

## Lacunas aceitas

| Lacuna | Motivo da aceitação | Impacto | Grau de confiança afetado |
| ------ | ------------------- | ------- | ------------------------- |
|        |                     |         |                           |

---

# 35. Plano de análise

## Etapas

1. consolidar registros;
2. classificar evidências;
3. verificar qualidade;
4. identificar convergências;
5. registrar divergências;
6. revisar hipóteses;
7. reconhecer padrões;
8. formular achados;
9. definir graus de confiança;
10. reconhecer limites;
11. priorizar;
12. preparar síntese.

## Categorias analíticas

* propósito e identidade;
* estratégia;
* clientes;
* processos;
* pessoas;
* responsabilidades;
* conhecimento;
* tecnologia;
* IA;
* resultados;
* riscos;
* contexto.

Devem permanecer apenas as categorias pertinentes.

## Métodos analíticos previstos

* análise temática;
* comparação entre fontes;
* análise de processo;
* análise de causa;
* análise de capacidades;
* avaliação de maturidade;
* comparação temporal;
* análise de divergências;
* outra: `[Preencher]`.

---

# 36. Plano de validação

## 36.1 Validação interna

**Responsável:** `[Nome]`

**Data prevista:** `[DD/MM/AAAA]`

### Verificações

* coerência metodológica;
* rastreabilidade;
* linguagem;
* proteção de dados;
* vieses;
* graus de confiança;
* limites;
* participação da IA.

## 36.2 Validação factual

| Participante | Elementos que validará | Formato | Data |
| ------------ | ---------------------- | ------- | ---- |
|              |                        |         |      |

## 36.3 Validação interpretativa

| Participante | Achados ou temas | Formato | Data |
| ------------ | ---------------- | ------- | ---- |
|              |                  |         |      |

## 36.4 Divergências

Divergências serão registradas em:

`[Arquivo ou seção.]`

## 36.5 Critério de aceitação

A validação não exige concordância total.

O diagnóstico estará pronto quando:

* fatos relevantes tiverem sido confrontados;
* novas evidências tiverem sido avaliadas;
* divergências estiverem registradas;
* conclusões estiverem proporcionais;
* limites estiverem claros.

---

# 37. Produtos e entregas

| Produto                    | Finalidade                          | Formato      | Responsável | Data |
| -------------------------- | ----------------------------------- | ------------ | ----------- | ---- |
| Matriz de evidências       | Sustentar rastreabilidade           | Markdown     |             |      |
| Mapa                       | Tornar processo ou relação visível  |              |             |      |
| Síntese diagnóstica        | Comunicar achados                   | Markdown/PDF |             |      |
| Relatório                  | Registrar análise completa          |              |             |      |
| Devolutiva                 | Construir compreensão compartilhada | Reunião      |             |      |
| Transição para arquitetura | Transferir requisitos               | Markdown     |             |      |

Devem permanecer apenas os produtos acordados.

## Critério de qualidade das entregas

`[Preencher]`

## Destinatários

`[Preencher]`

## Restrições de compartilhamento

`[Preencher]`

---

# 38. Devolutiva

## Formato

* [ ] Reunião
* [ ] Oficina
* [ ] Apresentação
* [ ] Documento comentado
* [ ] Sessão individual
* [ ] Outro: `[Preencher]`

## Participantes

* `[Nome ou função]`

## Estrutura prevista

1. finalidade;
2. escopo;
3. método;
4. capacidades;
5. achados;
6. relações;
7. riscos;
8. prioridades;
9. limites;
10. próximos passos.

## Achados sensíveis

`[Identificar temas que exigem comunicação cuidadosa.]`

## Medidas de proteção

`[Preencher]`

---

# 39. Passagem para a arquitetura

## Produtos de transição previstos

* [ ] Capacidades a preservar
* [ ] Problemas prioritários
* [ ] Causas prováveis
* [ ] Restrições
* [ ] Riscos
* [ ] Dependências
* [ ] Requisitos
* [ ] Critérios de solução
* [ ] Questões abertas
* [ ] Maturidade atual
* [ ] Recomendações de experimentação

## Documento

`transicao-para-arquitetura.md`

## Responsável

`[Nome]`

## Critério

A passagem somente ocorrerá quando os requisitos puderem ser relacionados aos achados diagnósticos.

---

# 40. Controle de mudanças

Toda mudança relevante deve registrar:

| Data | Elemento alterado | Versão anterior | Nova versão | Motivo | Impacto | Aprovador |
| ---- | ----------------- | --------------- | ----------- | ------ | ------- | --------- |
|      |                   |                 |             |        |         |           |

## Mudanças que exigem aprovação

* ampliação de escopo;
* inclusão de novos participantes;
* acesso a dados sensíveis;
* alteração de prazo relevante;
* nova ferramenta de IA;
* mudança de entrega;
* aumento de custo;
* alteração da decisão apoiada;
* mudança do tipo de diagnóstico.

## Questões fora do escopo

Devem ser registradas sem alterar automaticamente o plano.

---

# 41. Dependências

| Dependência | Responsável | Prazo | Estado   | Impacto |
| ----------- | ----------- | ----- | -------- | ------- |
|             |             |       | Pendente |         |
|             |             |       | Pendente |         |

## Dependência crítica

`[Preencher]`

## Plano alternativo

`[O que será feito se a dependência não for atendida?]`

---

# 42. Recursos necessários

## Pessoas

* `[Recurso humano 1]`

## Tempo

`[Estimativa ou disponibilidade.]`

## Ferramentas

* `[Ferramenta 1]`

## Acessos

* `[Acesso 1]`

## Orçamento

`[Preencher ou registrar “não aplicável”.]`

## Especialistas

* `[Especialidade ou profissional]`

---

# 43. Critérios de conclusão

O diagnóstico poderá avançar para encerramento quando:

* [ ] as questões essenciais tiverem sido respondidas no grau possível;
* [ ] as evidências estiverem organizadas;
* [ ] os achados puderem ser rastreados;
* [ ] as capacidades tiverem sido reconhecidas;
* [ ] os problemas, riscos e restrições estiverem formulados;
* [ ] as divergências estiverem registradas;
* [ ] as lacunas remanescentes estiverem explícitas;
* [ ] a validação tiver sido realizada;
* [ ] as entregas tiverem sido concluídas;
* [ ] a devolutiva tiver sido realizada;
* [ ] os requisitos para a etapa seguinte estiverem definidos;
* [ ] o aprendizado metodológico tiver sido registrado;
* [ ] o tratamento dos dados tiver sido concluído.

## Critério específico

`[Condição particular que demonstrará que o diagnóstico cumpriu sua finalidade.]`

---

# 44. Critérios de encerramento antecipado

O diagnóstico poderá ser encerrado antes do plano quando:

* a questão for respondida com evidência suficiente;
* a necessidade deixar de existir;
* for identificada necessidade de especialista;
* não houver acesso mínimo;
* o cliente cancelar;
* os riscos se tornarem incompatíveis;
* o diagnóstico perder utilidade.

## Procedimento

1. registrar o motivo;
2. comunicar o cliente;
3. preservar o que foi produzido;
4. explicitar limites;
5. recomendar continuidade;
6. atualizar o índice.

---

# 45. Aprendizagem prevista

Durante o diagnóstico, serão observados:

* utilidade das perguntas;
* qualidade das fontes;
* adequação das ferramentas;
* dificuldades de acesso;
* vieses;
* contribuição da IA;
* carga de participação;
* clareza dos templates;
* problemas de validação;
* melhorias metodológicas.

## Documento

`retrospectiva.md`

## Responsável

`[Nome]`

---

# 46. Verificação de coerência

Antes da aprovação, verificar:

1. O plano responde ao briefing?
2. Cada pergunta possui finalidade?
3. Cada ferramenta está vinculada a uma pergunta?
4. A coleta é proporcional?
5. Existem fontes suficientes para as questões críticas?
6. As hipóteses concorrentes podem ser examinadas?
7. Os dados serão protegidos?
8. O papel da IA está limitado?
9. As responsabilidades humanas estão explícitas?
10. Os critérios de conclusão estão claros?
11. O cliente possui capacidade para participar?
12. O plano preserva identidade e autonomia?
13. Existe risco de o diagnóstico confirmar uma solução previamente escolhida?
14. Os resultados poderão ser utilizados no Módulo 3?

## Resultado

* [ ] Coerente
* [ ] Coerente com condições
* [ ] Precisa ser reformulado
* [ ] Não deve prosseguir

## Condições

`[Preencher ou registrar “nenhuma”.]`

---

# 47. Prontidão para execução

* [ ] briefing aprovado;
* [ ] plano revisado;
* [ ] responsáveis definidos;
* [ ] participantes informados;
* [ ] acessos essenciais disponíveis ou programados;
* [ ] instrumentos preparados;
* [ ] cronograma confirmado;
* [ ] dados classificados;
* [ ] riscos avaliados;
* [ ] uso de IA autorizado;
* [ ] canais de comunicação definidos;
* [ ] condições de suspensão conhecidas;
* [ ] plano aprovado.

## Pendências

| Pendência | Responsável | Prazo | Impacto |
| --------- | ----------- | ----- | ------- |
|           |             |       |         |

---

# 48. Aprovação

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

## Aprovado pelo cliente

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Forma de aprovação

* [ ] Registro neste documento
* [ ] E-mail
* [ ] Mensagem
* [ ] Reunião registrada
* [ ] Assinatura
* [ ] Outra: `[Preencher]`

## Evidência

`[Inserir referência.]`

---

# 49. Histórico de versões

| Data | Versão | Alteração        | Motivo | Responsável | Aprovador |
| ---- | ------ | ---------------- | ------ | ----------- | --------- |
|      | 0.1    | Criação do plano |        |             |           |
|      |        |                  |        |             |           |

---

# 50. Síntese executiva do plano

Esta seção deve ser concluída após a aprovação.

## Diagnóstico

`[ID e título]`

## Questão central

`[Preencher]`

## Resultado esperado

`[Preencher]`

## Escopo

`[Preencher]`

## Fontes essenciais

`[Preencher]`

## Métodos principais

`[Preencher]`

## Participação da IA

`[Preencher]`

## Riscos principais

`[Preencher]`

## Marcos

`[Preencher]`

## Critério de conclusão

`[Preencher]`

## Próxima atividade

`[Ação, responsável e data.]`

Este plano cria a cadeia operacional:

> **questão → hipótese → fonte → método → evidência esperada → responsável → validação.**

Essa relação será uma das estruturas centrais do método LICHTARA. Ela impede que a investigação se transforme em uma sucessão de reuniões e documentos sem vínculo claro com a decisão que precisa ser apoiada.
