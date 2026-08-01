O briefing deve ser suficientemente completo para impedir ambiguidades de escopo, mas curto o bastante para ser preenchido antes de qualquer investigação aprofundada.

# Briefing de Diagnóstico Organizacional

```yaml
id: DIA-AAAA-NNN
titulo: "[Nome claro do diagnóstico]"
organizacao:
cliente_ou_responsavel:
responsavel_pelo_diagnostico:
data_de_abertura: AAAA-MM-DD
data_de_aprovacao:
estado: recebido
tipo_preliminar: focal | funcional | sistemico | a_definir
nivel_de_sensibilidade: publica | interna | confidencial | sensivel
decisao_relacionada:
versao: 0.1
```

---

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Template operacional
**Função:** Qualificação e alinhamento inicial da investigação
**Documento de referência:** `../protocolo-de-diagnostico.md`

---

# 1. Instruções de uso

Este documento deve ser duplicado para cada diagnóstico real.

O template-mestre não deve ser preenchido diretamente.

O briefing é utilizado para:

* registrar a demanda inicial;
* compreender por que o diagnóstico foi solicitado;
* formular a questão preliminar;
* identificar a decisão que será apoiada;
* delimitar o escopo inicial;
* reconhecer participantes, acessos e restrições;
* avaliar riscos e condições de continuidade;
* alinhar entregas e critérios de conclusão;
* autorizar a elaboração do plano de investigação.

O briefing não substitui o `plano-de-investigacao.md`.

Ele define **o que precisa ser compreendido e em quais condições**.

O plano de investigação definirá **como a investigação será conduzida**.

---

# 2. Identificação

| Campo                            | Registro                                         |
| -------------------------------- | ------------------------------------------------ |
| **ID do diagnóstico**            | `DIA-AAAA-NNN`                                   |
| **Título**                       | `[Nome específico e compreensível]`              |
| **Organização**                  | `[Nome da organização, projeto ou profissional]` |
| **Área ou processo**             | `[Quando aplicável]`                             |
| **Solicitante**                  | `[Nome e função]`                                |
| **Responsável do cliente**       | `[Pessoa com autoridade para aprovar o escopo]`  |
| **Responsável pelo diagnóstico** | `[Nome]`                                         |
| **Data de abertura**             | `[DD/MM/AAAA]`                                   |
| **Prazo desejado**               | `[DD/MM/AAAA ou período]`                        |
| **Estado atual**                 | `[Selecionar abaixo]`                            |

## Estado

* [ ] Recebido
* [ ] Em qualificação
* [ ] Aguardando informação
* [ ] Aguardando aprovação de escopo
* [ ] Aprovado para planejamento
* [ ] Redirecionado
* [ ] Recusado
* [ ] Suspenso
* [ ] Cancelado

---

# 3. Origem da demanda

## Como a demanda surgiu?

* [ ] Solicitação direta do cliente
* [ ] Reunião inicial
* [ ] Projeto em andamento
* [ ] Problema recorrente
* [ ] Incidente
* [ ] Mudança de estratégia
* [ ] Oportunidade identificada
* [ ] Diagnóstico anterior
* [ ] Decisão interna do Estúdio
* [ ] Outro: `[Preencher]`

## Relato inicial

Registre a demanda utilizando, sempre que possível, as palavras da pessoa solicitante.

`[Preencher]`

## Situação observada

O que aconteceu, está acontecendo ou pode acontecer?

`[Preencher]`

## Por que esta situação importa agora?

`[Preencher]`

## Desde quando ocorre?

`[Preencher ou registrar “não determinado”.]`

## Frequência ou recorrência

* [ ] Evento pontual
* [ ] Ocasional
* [ ] Recorrente
* [ ] Contínuo
* [ ] Em crescimento
* [ ] Não determinado

### Observações

`[Preencher]`

---

# 4. Solução inicialmente solicitada ou imaginada

## Existe uma solução já solicitada?

* [ ] Não
* [ ] Sim

### Solução mencionada

`[Exemplo: contratar CRM, automatizar atendimento, reorganizar arquivos, criar estratégia de conteúdo.]`

## Quem propôs essa solução?

`[Preencher]`

## Por que essa solução parece adequada?

`[Preencher]`

## A solução será tratada como

* [ ] Pedido operacional já aprovado
* [ ] Possibilidade a ser investigada
* [ ] Hipótese inicial
* [ ] Restrição definida pelo cliente
* [ ] Não aplicável

## Observação metodológica

A solução solicitada não deve ser tratada como conclusão antes que o problema, o contexto e as condições de implantação sejam compreendidos.

---

# 5. Decisão que o diagnóstico apoiará

## Que decisão precisa ser tomada?

`[Preencher de maneira objetiva.]`

### Exemplos

* decidir se uma ferramenta deve ser implantada;
* escolher qual processo precisa ser reorganizado primeiro;
* definir requisitos para um novo sistema;
* avaliar se a organização está preparada para utilizar IA;
* decidir se o problema exige intervenção, treinamento ou investigação adicional.

## Quem possui autoridade para tomar essa decisão?

`[Nome e função]`

## Quando a decisão precisa ser tomada?

`[DD/MM/AAAA ou condição]`

## O que acontece se a decisão for adiada?

`[Preencher]`

## O que acontece se a decisão for tomada sem diagnóstico?

`[Preencher]`

## Existe uma decisão formal relacionada?

* [ ] Não
* [ ] Sim

**ID ou link:** `[DEC-AAAA-NNN]`

---

# 6. Formulação preliminar do problema

## Sinal

Que manifestação iniciou a investigação?

`[Preencher]`

## Sintomas relatados ou observados

* `[Sintoma 1]`
* `[Sintoma 2]`
* `[Sintoma 3]`

## Problema preliminar

Formule o problema sem pressupor uma solução.

`[Preencher]`

### Estrutura recomendada

> `[Condição observada]` afeta `[pessoa, processo ou resultado]`, produzindo `[consequência relevante]`.

## Consequências atuais

* `[Consequência 1]`
* `[Consequência 2]`

## Consequências potenciais

* `[Risco ou consequência futura 1]`
* `[Risco ou consequência futura 2]`

## A formulação foi validada?

* [ ] Ainda não
* [ ] Validada preliminarmente com o solicitante
* [ ] Precisa ser reformulada após investigação exploratória

---

# 7. Questão diagnóstica preliminar

## Pergunta central

`[Que pergunta o diagnóstico deverá responder?]`

### Critérios

A questão deve:

* poder ser investigada;
* estar vinculada a uma decisão;
* não pressupor a solução;
* possuir escopo reconhecível;
* produzir compreensão utilizável.

## Perguntas secundárias iniciais

1. `[Pergunta 1]`
2. `[Pergunta 2]`
3. `[Pergunta 3]`
4. `[Pergunta 4, quando necessária]`

## Questões explicitamente fora deste diagnóstico

* `[Questão fora do escopo 1]`
* `[Questão fora do escopo 2]`

---

# 8. Resultado esperado

## O que precisa estar compreendido ao final?

`[Preencher]`

## O que o cliente deverá ser capaz de decidir ou realizar?

`[Preencher]`

## Produtos esperados

* [ ] Síntese diagnóstica
* [ ] Mapa de processo
* [ ] Mapa de jornada
* [ ] Mapa de ferramentas
* [ ] Mapa de conhecimento
* [ ] Avaliação de maturidade
* [ ] Matriz de evidências
* [ ] Relatório de diagnóstico
* [ ] Devolutiva
* [ ] Requisitos para arquitetura
* [ ] Prioridades
* [ ] Recomendação de investigação complementar
* [ ] Outro: `[Preencher]`

## O que não constitui resultado esperado?

Registre entregas ou expectativas que não fazem parte deste diagnóstico.

`[Preencher]`

---

# 9. Tipo preliminar de diagnóstico

## Classificação

* [ ] Focal
* [ ] Funcional
* [ ] Sistêmico
* [ ] Exploratório
* [ ] A definir após qualificação

## Justificativa

`[Explique por que esse nível parece proporcional à questão.]`

## Possível mudança de classificação

Que evidência ou condição poderia ampliar ou reduzir o diagnóstico?

`[Preencher]`

---

# 10. Escopo preliminar

## Incluído

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

### Documentos ou dados

* `[Categoria documental ou dado 1]`
* `[Categoria documental ou dado 2]`

### Período analisado

`[Exemplo: maio a julho de 2026.]`

### Unidades, canais ou públicos

`[Preencher, quando aplicável.]`

---

## Excluído

* `[Tema, área, processo ou período excluído 1]`
* `[Tema, área, processo ou período excluído 2]`

## Motivo das exclusões

`[Preencher]`

## Questões que devem ser apenas registradas para o futuro

* `[Questão futura 1]`
* `[Questão futura 2]`

---

# 11. Contexto organizacional

## Propósito ou atividade principal

`[O que a organização realiza e para quem?]`

## Estágio atual

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

## Tamanho e configuração

`[Número aproximado de pessoas, unidades, clientes ou estrutura relevante.]`

## Mudanças recentes

* `[Mudança 1]`
* `[Mudança 2]`

## Projetos ou iniciativas relacionados

* `[Projeto 1]`
* `[Projeto 2]`

## Restrições contextuais

* `[Restrição financeira, temporal, técnica, humana, cultural ou jurídica.]`

## Capacidades já percebidas

* `[Capacidade 1]`
* `[Capacidade 2]`

## Elementos identitários que precisam ser preservados

* `[Elemento 1]`
* `[Elemento 2]`

---

# 12. Pessoas envolvidas

## Participantes previstos

| Pessoa | Função ou relação | Participação esperada | Autoridade ou conhecimento | Disponibilidade |
| ------ | ----------------- | --------------------- | -------------------------- | --------------- |
|        |                   |                       |                            |                 |
|        |                   |                       |                            |                 |
|        |                   |                       |                            |                 |

## Pessoas afetadas que não participarão diretamente

| Pessoa ou grupo | Como será afetado | Motivo da não participação |
| --------------- | ----------------- | -------------------------- |
|                 |                   |                            |
|                 |                   |                            |

## Pessoas que precisam ser consultadas antes do início

* `[Nome ou função]`

## Especialistas possivelmente necessários

* [ ] Jurídico
* [ ] Contábil
* [ ] Financeiro
* [ ] Tecnologia
* [ ] Segurança da informação
* [ ] Proteção de dados
* [ ] Recursos humanos
* [ ] Saúde ou área clínica
* [ ] Outro: `[Preencher]`
* [ ] Nenhum identificado neste momento

---

# 13. Fontes preliminares

## Pessoas

* `[Entrevista ou consulta prevista]`

## Documentos

* `[Documento ou categoria]`

## Sistemas

* `[Sistema ou plataforma]`

## Dados

* `[Indicador, relatório ou conjunto de dados]`

## Processos a observar

* `[Processo 1]`
* `[Processo 2]`

## Materiais de comunicação

* `[Site, rede social, proposta, apresentação ou outro material]`

## Fontes externas

* `[Regulação, referência setorial, pesquisa, benchmark ou outra fonte]`

## Fonte essencial ainda indisponível

`[Preencher ou registrar “nenhuma identificada”.]`

---

# 14. Acessos e disponibilidade

## Acessos necessários

| Recurso | Tipo de acesso | Responsável pela liberação | Prazo | Estado   |
| ------- | -------------- | -------------------------- | ----- | -------- |
|         |                |                            |       | Pendente |
|         |                |                            |       | Pendente |

## Disponibilidade dos participantes

`[Dias, horários, restrições ou períodos.]`

## Dependências

O início ou a conclusão depende de:

* `[Aprovação, arquivo, acesso, pessoa ou evento.]`

## Impedimentos conhecidos

* `[Impedimento 1]`
* `[Impedimento 2]`

---

# 15. Dados, confidencialidade e sensibilidade

## Classificação geral do diagnóstico

* [ ] Público
* [ ] Interno
* [ ] Confidencial
* [ ] Sensível

## Categorias de informação envolvidas

* [ ] Informações institucionais
* [ ] Estratégia
* [ ] Propriedade intelectual
* [ ] Dados pessoais
* [ ] Dados financeiros
* [ ] Informações jurídicas
* [ ] Informações de saúde
* [ ] Conflitos ou avaliações internas
* [ ] Credenciais ou segurança
* [ ] Dados de clientes
* [ ] Outro: `[Preencher]`

## Finalidade da coleta

`[Explique por que essas informações são necessárias.]`

## Dados que não devem ser coletados

`[Preencher]`

## Pessoas autorizadas a acessar os registros

* `[Nome ou função]`

## Local de armazenamento

`[Repositório, pasta, sistema ou ambiente autorizado.]`

## Regras especiais de proteção

* `[Anonimização, pseudonimização, restrição, criptografia, separação de arquivos ou outra medida.]`

## Prazo ou condição de retenção

`[Preencher]`

## Autorização necessária

* [ ] Não identificada
* [ ] Consentimento ou ciência dos participantes
* [ ] Aprovação do cliente
* [ ] Acordo de confidencialidade
* [ ] Autorização para gravação
* [ ] Autorização para uso de IA
* [ ] Outra: `[Preencher]`

---

# 16. Participação preliminar da inteligência artificial

## A IA poderá participar?

* [ ] Não está prevista
* [ ] Sim, na preparação
* [ ] Sim, na coleta ou transcrição
* [ ] Sim, na organização das evidências
* [ ] Sim, na análise exploratória
* [ ] Sim, na síntese
* [ ] A definir após avaliação dos dados

## Funções possíveis

* [ ] Preparação de perguntas
* [ ] Transcrição
* [ ] Organização de notas
* [ ] Classificação de evidências
* [ ] Comparação documental
* [ ] Identificação de padrões
* [ ] Formulação de hipóteses alternativas
* [ ] Revisão de coerência
* [ ] Apoio à redação
* [ ] Outra: `[Preencher]`

## Sistemas ou ambientes previstos

`[Preencher ou registrar “a definir”.]`

## Tipos de informação que poderão ser fornecidos

`[Descrever categorias, não reproduzir dados sensíveis.]`

## Informações proibidas ou restritas

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

## Responsável humano pela supervisão

`[Nome]`

## Atividades que permanecerão exclusivamente humanas

* `[Atividade 1]`
* `[Atividade 2]`

---

# 17. Restrições

## Prazo

`[Preencher]`

## Orçamento

`[Preencher ou registrar “não definido”.]`

## Disponibilidade humana

`[Preencher]`

## Acesso a dados

`[Preencher]`

## Limitações técnicas

`[Preencher]`

## Limitações legais ou contratuais

`[Preencher]`

## Limitações metodológicas já conhecidas

`[Preencher]`

## Outras restrições

`[Preencher]`

---

# 18. Riscos preliminares

| Risco | Categoria | Probabilidade        | Impacto                        | Medida inicial | Responsável |
| ----- | --------- | -------------------- | ------------------------------ | -------------- | ----------- |
|       |           | Baixa / Média / Alta | Baixo / Médio / Alto / Crítico |                |             |
|       |           | Baixa / Média / Alta | Baixo / Médio / Alto / Crítico |                |             |
|       |           | Baixa / Média / Alta | Baixo / Médio / Alto / Crítico |                |             |

## Categorias possíveis

* escopo;
* acesso;
* prazo;
* confidencialidade;
* proteção de dados;
* conflito de interesse;
* manipulação da conclusão;
* indisponibilidade de participante;
* baixa qualidade dos dados;
* exposição de pessoa;
* uso inadequado de IA;
* dependência de especialista;
* risco jurídico;
* risco reputacional;
* outro.

## Condição que exigiria suspensão

`[Preencher]`

---

# 19. Conflitos de interesse e expectativas

## Existe interesse comercial relacionado ao diagnóstico?

* [ ] Não
* [ ] Sim

### Descrição

`[Exemplo: o Estúdio também poderá implantar a solução posteriormente.]`

## Como o conflito será controlado?

`[Preencher]`

## Existe conclusão esperada ou desejada pelo solicitante?

* [ ] Não identificada
* [ ] Sim

### Conclusão esperada

`[Preencher]`

## Existe risco de o diagnóstico ser utilizado para responsabilizar pessoas?

* [ ] Não identificado
* [ ] Sim
* [ ] Precisa ser investigado

### Medidas de proteção

`[Preencher]`

## Expectativas que precisam ser ajustadas

* `[Expectativa 1]`
* `[Expectativa 2]`

---

# 20. Premissas iniciais

Premissas são condições consideradas verdadeiras para viabilizar o planejamento.

* `[Premissa 1]`
* `[Premissa 2]`
* `[Premissa 3]`

## Como serão verificadas?

| Premissa | Forma de verificação | Responsável | Prazo |
| -------- | -------------------- | ----------- | ----- |
|          |                      |             |       |
|          |                      |             |       |

---

# 21. Hipóteses preliminares

As hipóteses orientam a investigação, mas não constituem conclusões.

| ID      | Hipótese inicial | Evidência favorável possível | Evidência contrária possível | Confiança inicial |
| ------- | ---------------- | ---------------------------- | ---------------------------- | ----------------- |
| HIP-001 |                  |                              |                              | Baixa             |
| HIP-002 |                  |                              |                              | Baixa             |
| HIP-003 |                  |                              |                              | Baixa             |

## Observação

A existência de uma hipótese não obriga sua manutenção.

Hipóteses rejeitadas devem permanecer registradas como parte do aprendizado.

---

# 22. Critérios de viabilidade

## O diagnóstico é viável neste momento?

* [ ] Sim
* [ ] Sim, com condições
* [ ] Ainda não
* [ ] Deve ser redirecionado
* [ ] Deve ser recusado

## Verificação

* [ ] A questão pertence ao escopo do Estúdio.
* [ ] Existe decisão ou finalidade clara.
* [ ] Há acesso mínimo às fontes.
* [ ] O responsável do cliente está identificado.
* [ ] O prazo é compatível com análise responsável.
* [ ] Os dados podem ser tratados adequadamente.
* [ ] Não existe conflito de interesse impeditivo.
* [ ] Existe competência para conduzir a investigação.
* [ ] Especialistas necessários podem ser acessados.
* [ ] O resultado esperado é utilizável.

## Condições necessárias para viabilização

`[Preencher ou registrar “nenhuma”.]`

---

# 23. Entregas preliminares

| Entrega | Formato | Responsável | Destinatário | Data prevista |
| ------- | ------- | ----------- | ------------ | ------------- |
|         |         |             |              |               |
|         |         |             |              |               |
|         |         |             |              |               |

## Devolutiva prevista

* [ ] Reunião
* [ ] Documento
* [ ] Apresentação
* [ ] Oficina
* [ ] Sessão de validação
* [ ] Outro: `[Preencher]`

## Nível de detalhamento esperado

* [ ] Executivo
* [ ] Operacional
* [ ] Técnico
* [ ] Misto

---

# 24. Critérios de conclusão

O diagnóstico será considerado suficientemente concluído quando:

* [ ] a questão central tiver sido respondida no grau possível;
* [ ] os limites estiverem explícitos;
* [ ] as fontes essenciais tiverem sido consultadas ou suas ausências registradas;
* [ ] as evidências puderem ser rastreadas;
* [ ] capacidades e problemas tiverem sido identificados;
* [ ] riscos e restrições estiverem registrados;
* [ ] prioridades tiverem sido formuladas;
* [ ] os aspectos factuais tiverem sido validados;
* [ ] os requisitos para a etapa seguinte estiverem claros;
* [ ] a devolutiva tiver sido realizada;
* [ ] o aprendizado metodológico tiver sido registrado.

## Critério específico deste diagnóstico

`[Que condição particular demonstrará que a investigação cumpriu sua finalidade?]`

---

# 25. Limites preliminares da conclusão

Mesmo após o diagnóstico, provavelmente não será possível afirmar:

* `[Limite 1]`
* `[Limite 2]`
* `[Limite 3]`

## Motivo

`[Escopo, acesso, prazo, dados, especialidade ou outra restrição.]`

---

# 26. Cronograma preliminar

| Marco                 | Data ou período | Responsável | Dependência |
| --------------------- | --------------- | ----------- | ----------- |
| Aprovação do briefing |                 |             |             |
| Plano de investigação |                 |             |             |
| Início da coleta      |                 |             |             |
| Conclusão da coleta   |                 |             |             |
| Síntese inicial       |                 |             |             |
| Validação             |                 |             |             |
| Devolutiva            |                 |             |             |
| Encerramento          |                 |             |             |

O cronograma detalhado será definido no plano de investigação.

---

# 27. Comunicação

## Canal oficial

`[E-mail, plataforma, pasta, reunião ou outro canal.]`

## Frequência de atualização

* [ ] Por marco
* [ ] Semanal
* [ ] Quinzenal
* [ ] Sob ocorrência de risco
* [ ] Outra: `[Preencher]`

## Pessoas que receberão atualizações

* `[Nome ou função]`

## Quem pode aprovar mudanças de escopo?

`[Nome e função]`

---

# 28. Condições para continuidade

Antes da elaboração do plano de investigação, devem estar atendidas:

* [ ] questão preliminar registrada;
* [ ] decisão apoiada identificada;
* [ ] escopo inicial delimitado;
* [ ] responsável do cliente definido;
* [ ] responsável pelo diagnóstico definido;
* [ ] acessos essenciais reconhecidos;
* [ ] riscos preliminares avaliados;
* [ ] tratamento de dados definido;
* [ ] participação da IA avaliada;
* [ ] entregas preliminares alinhadas;
* [ ] critérios de conclusão definidos;
* [ ] briefing aprovado.

## Pendências

| Pendência | Responsável | Prazo | Impacto se não resolvida |
| --------- | ----------- | ----- | ------------------------ |
|           |             |       |                          |
|           |             |       |                          |

---

# 29. Recomendação de encaminhamento

## Resultado da qualificação

* [ ] Prosseguir para o plano de investigação
* [ ] Prosseguir com condições
* [ ] Realizar diagnóstico exploratório
* [ ] Solicitar informações adicionais
* [ ] Reduzir o escopo
* [ ] Ampliar o escopo
* [ ] Redirecionar para especialista
* [ ] Tratar como tarefa, sem diagnóstico formal
* [ ] Suspender
* [ ] Recusar

## Fundamentação

`[Preencher]`

## Condições obrigatórias

`[Preencher ou registrar “nenhuma”.]`

## Próximo passo

`[Ação concreta, responsável e data.]`

---

# 30. Aprovação

## Elaborado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Revisado por

**Nome:** `[Preencher]`
**Função:** `[Preencher]`
**Data:** `[DD/MM/AAAA]`

## Aprovado pelo cliente ou responsável

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

## Evidência da aprovação

`[Link, arquivo ou referência.]`

---

# 31. Histórico do briefing

| Data | Versão | Alteração | Motivo | Responsável |
| ---- | ------ | --------- | ------ | ----------- |
|      | 0.1    | Criação   |        |             |
|      |        |           |        |             |

---

# 32. Síntese executiva

Esta seção deve ser preenchida após a aprovação do briefing.

## Diagnóstico

`[Nome e ID]`

## Questão central

`[Reproduzir a pergunta principal.]`

## Decisão apoiada

`[Reproduzir a decisão.]`

## Escopo

`[Síntese do que está incluído.]`

## Resultado esperado

`[Síntese.]`

## Restrições principais

`[Síntese.]`

## Riscos principais

`[Síntese.]`

## Condições de continuidade

`[Síntese.]`

## Próximo documento

`plano-de-investigacao.md`

Este template cria uma fronteira importante: **antes do briefing aprovado, existe uma demanda; depois dele, existe um diagnóstico formalmente autorizado**.

Também preservei a separação entre três elementos que costumam ser confundidos:

* o **problema preliminar**, que ainda pode ser reformulado;
* a **questão diagnóstica**, que orienta a investigação;
* a **decisão apoiada**, que explica para que o diagnóstico será utilizado.

O próximo template lógico é o `plano-de-investigacao.md`, no qual cada pergunta será vinculada às fontes, ferramentas, evidências esperadas, responsáveis, cronograma e tratamento dos dados.
